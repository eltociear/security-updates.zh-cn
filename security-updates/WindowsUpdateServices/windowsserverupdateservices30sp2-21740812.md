---
TOCTitle: 'Windows Server Update Services 3.0 SP2 发行说明'
Title: 'Windows Server Update Services 3.0 SP2 发行说明'
ms:assetid: 'b3723422-489d-47b7-abfa-663353647da0'
ms:contentKeyID: 21740812
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Dd939886(v=WS.10)'
---

Windows Server Update Services 3.0 SP2 发行说明
===============================================

这些发行说明介绍了 Windows Server Update Services 3.0 Service Pack 2 (WSUS 3.0 SP2) 版本。本文档包含以下部分：

1.  本发行版本的新增功能
2.  WSUS 3.0 SP2 服务器安装的系统要求
3.  WSUS 服务器的配置先决条件和最佳实践建议
4.  Windows Small Business Server 先决条件
5.  WSUS 3.0 SP2 远程控制台安装的系统要求
6.  客户端安装的系统要求
7.  升级要求和建议
8.  安装 WSUS 3.0 SP2
9.  为无人参与的 WSUS 3.0 SP2 安装设置命令行参数
10. 已知问题

本发行版本的新增功能
--------------------

-   与 Windows Server 2008 R2 的集成。
-   对 Windows Server 2008 R2 中 BranchCache 功能的支持。
-   对 Windows 7 客户端的支持。
-   Windows Update Agent (WUA) 客户端改进。新的 WUA 客户端提供了许多性能增强、用户体验改善，以及一系列基于用户反馈的错误修复。
    -   客户端扫描时间较以前版本更短。
    -   现在，WSUS 服务器管理的计算机可以对相同的 WSUS 服务器运行“选区”扫描，而不需要执行完全扫描。通过此功能，使用 Microsoft Update API（例如 Windows Defender）可以对应用程序进行大量的快速扫描。
    -   Windows Update Agent (WUA) 用户体验改善可帮助用户更好地组织更新，并提供更明确的更新值和更新行为。
    -   映像计算机可以更清晰地显示在 WSUS 控制台中。有关详细信息，请参见以下标题的文章[使用 Windows 2000、Windows Server 2003 或 Windows XP 映像安装的基于 Windows 2000、基于 Windows Server 2003 或基于 Windows XP 的计算机没有在 WSUS 控制台中显示](http://go.microsoft.com/fwlink/?linkid=159749)。
-   新增功能：
    -   目前，自动审批规则允许为所有计算机或特定计算机组指定审批截止日期和时间。
    -   对下游服务器的语言选择操作进行改进处理，当您决定下载指定语言的更新时，会出现一个新的警告对话框。
    -   使用新更新和计算机状态报告，您可以筛选已审批的更新以进行安装。您可以从 WSUS 控制台运行这些报告，或使用应用程序编程接口 (API) 将此功能添加到您自己的报告中。
-   用户界面可在客户端和服务器上 WSUS 3.0 的 Service Pack 1 与 Service Pack 2 之间兼容。
-   软件更新。
-   本发行版本中 Windows Update Agent 已解决的已知问题：
    1.  WSUS 3.0 SP2 和 Windows 7 包含 Windows Update Agent（对于 Windows XP、Windows Vista、Windows Server 2000、Windows Server 2003 和 Windows Server 2008）的新发行版本。本发行版本解决了以下问题：非交互会话中的非本地系统调用方调用的 API 失败。
    2.  版本 7.2.6001.788 的 Windows Update Agent 解决的问题。本更新解决了以下问题：当您尝试同时从 Windows Update 网页或 Microsoft Update 网页安装 80 个（或以上）更新时，您可能会收到错误代码 0x80070057。
    3.  Windows Update Agent 的 7.2.6001.784 版本做出的改进和解决的问题。本更新包含以下改进：改进了 Windows Update 的扫描次数和签名更新的传输速度、提供了对 Windows Installer 重新安装功能的支持，并改进了错误消息。

<span id="BKMK_SysReqWSUS30SP2"></span>
WSUS 3.0 SP2 服务器安装的系统要求
---------------------------------

本部分介绍了安装 WSUS 3.0 SP2 所需的软件和硬件要求。

### WSUS 服务器软件先决条件

-   您必须安装了下面其中一种受支持的操作系统：
    -   Windows Server 2008 R2
    -   Windows Server 2008 SP1 或更高版本
 
        <table style="border:1px solid black;">
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th style="border:1px solid black;" ><img src="images/Dd939886.Warning(WS.10).gif" />警告</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;">如果在升级到 Windows Server 2008 R2 之前已在 Windows Server 2008 上安装了 WSUS 3.0 SP2，则到 Windows Server 2008 R2 的升级将会失败。请参阅<a href="#bkmk_knownissues">已知问题</a>部分了解详细信息。
        </td>
        </tr>
        </tbody>
        </table>
 

    -   Windows Server 2003 SP1 或更高版本
    -   Windows Small Business Server 2008
    -   Windows Small Business Server 2003

    请注意，其他先决条件适用于 Windows Small Business Server。有关详细信息，请参见“Windows Small Business Server 先决条件”部分。
-   Internet 信息服务 (IIS) 6.0 或更高版本
-   Microsoft .NET Framework 2.0 或更高版本
-   您必须安装了下面其中一种受支持的数据库：
    -   Microsoft SQL Server 2008 标准版或企业版
    -   Microsoft SQL Server 2005 SP3 或更高版本
    -   Windows 内部数据库

    如果尚未安装受支持的 SQL Server 版本，则 WSUS 3.0 SP2 安装向导将安装 Windows 内部数据库。
-   Microsoft 管理控制台 3.0
-   Microsoft Report Viewer Redistributable 2008

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939886.Important(WS.10).gif" />重要事项</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 R2 需要 WSUS 3.0 SP2。如果您安装的是 Windows Server 2008 R2，则应该安装 WSUS 3.0 SP2。请不要在 Windows Server 2008 R2 上安装 WSUS 3.0 SP1。

在远程 SQL 配置中的前端服务器上，不支持将 WSUS 3.0 SP2 与终端服务一起使用。
</td>
</tr>
</tbody>
</table>
 

### WSUS 管理控制台软件先决条件

-   以下受支持的操作系统之一：Windows Server 2008 R2、Windows Server 2008、Windows Server 2003 SP2 或更高版本、Windows Small Business Server 2008 或 Windows Small Business Server 2003、Windows Vista 或 Windows XP SP2
-   Microsoft .NET Framework 2.0 或更高版本
-   Microsoft 管理控制台 3.0
-   Microsoft Report Viewer Redistributable 2008

### WSUS Server 最低硬件要求

下表包含进行基本服务器安装所需的最低硬件要求。请访问 WSUS 3.0 SP2 部署指南（网址是 [http://go.microsoft.com/fwlink/?LinkId=139832](http://go.microsoft.com/fwlink/?linkid=139832)）以获得受支持硬件配置的完整列表。

-   系统分区和安装 WSUS 3.0 SP2 的分区都必须采用 NTFS 文件系统进行格式化。
-   系统分区上至少有 1 GB 的可用空间。
-   存储数据库文件的卷上至少有 2 GB 的可用空间。
-   存储内容的卷上至少有 20 GB 的可用空间，建议可用空间为 30 GB。

 
> [!IMPORTANT]
> WSUS 3.0 SP2 不能安装在压缩的驱动器上。
 

WSUS 服务器的配置先决条件和最佳实践建议
---------------------------------------

在安装 WSUS 3.0 SP2 之前，请确保您已完成此部分的相应任务。

### IIS

-   在 Server Manager 的“Web 服务器 (IIS) 角色服务”页中，安装所有需要的功能、所有默认的 IIS 角色服务以及以下角色服务：“ASP.NET”、“Windows 身份验证”、“动态内容压缩”和“IIS 6 管理兼容性”。
-   如果 IIS 正以 IIS 5.0 隔离模式运行，安装将失败。在安装 WSUS 3.0 SP2 之前，禁用 IIS 5.0 隔离模式。
-   如果在 64 位平台上以 32 位兼容模式安装任何 IIS 组件，则 WSUS 3.0 SP2 安装可能会失败。应在 64 位平台上以纯模式安装所有 IIS 组件。

### 代理服务器

WSUS 3.0 SP2 仅允许代理服务器支持 HTTP。最佳实践为：在从配置向导或管理控制台配置 WSUS Server 之前，使用命令行 (**wsusutil configuresslproxy**) 配置另一台运行 HTTPS 的代理服务器。

### 在端口 80 上运行的网站

如果在端口 80 上运行的网站存在两个或两个以上（如 Windows SharePoint Services），请在安装 WSUS 之前删除其他所有网站，仅保留一个网站。否则，服务器的客户端可能无法进行自我更新。

### 防病毒程序

在安装 WSUS 3.0 SP2 时，您可能需要禁用防病毒程序，然后才能成功执行安装。禁用防病毒软件后，应先重新启动计算机，然后再安装 WSUS。重新启动计算机可防止在安装过程中必须访问文件时文件被锁定。安装完成后，一定要重新启用防病毒软件。要了解禁用和重新启用防病毒软件的确切步骤以及了解程序版本，请访问防病毒软件供应商的网站。

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939886.Caution(WS.10).gif" />注意</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">此解决办法可能会使计算机或网络更容易受到恶意用户或恶意软件（如病毒）的攻击。我们不建议您使用这种解决办法，而提供此信息是为了使您自行决定是否实施此解决办法。使用此解决办法的风险由您自己承担。

防病毒软件有助于保护您的计算机免受病毒的攻击。在禁用防病毒程序后，切勿从不信任的来源下载或打开文件、访问不信任的网站或打开电子邮件附件。
</td>
</tr>
</tbody>
</table>
 

### SQL Server 的嵌套触发器选项

如果计划将 SQL Server 数据库用作 Windows Server Update Services 数据存储，SQL Server 管理员应首先确认在服务器上打开了嵌套触发器选项，然后 WSUS 管理员才能安装 WSUS 3.0 SP2。默认情况下，嵌套触发器选项处于打开状态，但 SQL Server 管理员可将其关闭。WSUS 3.0 SP2 安装程序将打开 RECURSIVE\_TRIGGERS 选项（该选项为数据库特定的选项）。但 WSUS 3.0 SP2 安装程序不会打开嵌套触发器选项（该选项为服务器全局选项）。

### 远程 SQL 限制和要求

WSUS 3.0 SP2 支持在独立于运行 WSUS 3.0 SP2 应用程序的计算机的计算机上运行兼容版本的 SQL Server 软件。下列要求适用于远程 SQL 安装。

-   无法将配置为域控制器的服务器用作远程 SQL 对的后端。
-   无法在将成为远程 SQL 安装的前端服务器的计算机上运行终端服务。
-   前端计算机和后端计算机都必须加入 Active Directory 域。如果前端计算机和后端计算机在不同的域中，请在运行 WSUS 安装程序之前在域之间建立跨域信任。
-   如果已在远程 SQL 配置中安装了 WSUS 2.0，并且希望升级到 WSUS 3.0 SP2，请在安装 WSUS 之前执行以下操作：
    1.  卸载 WSUS 2.0（使用“控制面板”中的“添加或删除程序”），同时确保现有数据库保持不变。
    2.  安装 SQL Server 2005 SP2 或 SQL Server 2008，并升级现有数据库。

### 在 WSUS 3.0 SP2 安装期间重新启动 IIS

WSUS 3.0 SP2 安装程序将在不发出通知的情况下重新启动 IIS，这可能会影响组织中的现有网站。最佳实践为：在此安装前对将受影响的各方发出通知。请注意，如果 IIS 未运行，则 WSUS 3.0 SP2 安装程序将在安装过程中启动 IIS。

Windows Small Business Server 先决条件
--------------------------------------

如果您要在 Windows Small Business Server 上安装 WSUS 3.0 SP2，则以下先决条件适用。

### 如果 IIS 虚拟根目录限制为某些 IP 地址或域名

某些 Windows Small Business Server 安装可能为“IP 地址和域名限制”配置了默认 IIS 网站。此时，服务器上的 Windows Update Client 可能无法自行更新。安装 WSUS 3.0 SP2 之前删除限制。

### 如果您正在使用 ISA 代理服务器

-   如果 Windows Small Business Server 使用 ISA 代理服务器访问 Internet，请在“设置”用户界面 (UI) 中键入**代理服务器设置、代理服务器名称、端口**。
-   如果 ISA 使用的是 Windows 身份验证，请以*域*\\*用户*形式输入代理服务器凭据。用户应该是 Internet User 组的成员。

### 如果您将子网添加到了您的网络，且没有使用 Windows Small Business Server 向导

WSUS 服务器安装过程将在服务器上安装以下两个 IIS 虚拟根目录：SelfUpdate 和 ClientWebService。安装程序还会在默认网站（在端口 80 上）的根目录下面放置一些文件，以使客户端计算机能够通过默认网站进行自我更新。默认情况下，将默认网站配置为拒绝对除 localhost 外的任何 IP 地址或连接到服务器的特定子网进行访问。因此，不在 localhost 或这些特定子网上的客户端计算机无法进行自我更新。如果您在没有使用 Microsoft Windows Small Business Server 向导的情况下将子网添加到了网络，请执行以下操作：

1.  在“服务器管理”中，依次展开“高级管理”、“Internet 信息服务”、“网站”和“默认网站”，右键单击“Selfupdate”虚拟目录，然后单击“属性”。
2.  单击“目录安全性”。
3.  在“IP 地址和域名限制”下，单击“编辑”，然后单击“授权访问”。
4.  单击“确定“，右键单击 **ClientWebService** 虚拟目录，然后单击“属性”。
5.  单击“目录安全性”。
6.  在“IP 地址和域名限制”下，单击“编辑”，然后单击“授权访问”。

WSUS 3.0 SP2 远程控制台安装的系统要求
-------------------------------------

WSUS 3.0 SP2 远程控制台可以在以下任一操作系统中安装：

-   Windows Server 2008 R2、Windows Server 2008 SP1 或更高版本、Windows Server 2003 SP2 或更高版本、Windows Small Business Server 2003、Windows Small Business Server 2005 或 Windows Small Business Server 2008、Windows Vista，或 Windows XP Professional SP3 或更高版本。

WSUS 客户端安装的系统要求
-------------------------

自动更新和 WSUS 客户端软件可在以下任一操作系统上安装：

-   Windows Server 2008 R2、Windows Server 2008 SP1 或更高版本、Windows Server 2003 SP2 或更高版本、Windows Small Business Server 2003、Windows Small Business Server 2005 或 Windows Small Business Server 2008、Windows Vista、Windows XP Professional RTM、Windows XP Professional SP1、Windows XP Professional SP2、Windows XP Professional SP3 或更高版本、Windows 2000 SP4，或 Windows 7 客户端。

升级要求和建议
--------------

以下版本的 WSUS 可升级到 WSUS 3.0 SP2，且无需卸载早期版本：

-   WSUS 2.0、2.0 SP1、3.0 和 3.0 SP1。

不支持从 WSUS 1.0 升级到 WSUS 3.0 SP2。在安装 WSUS 3.0 SP2 之前卸载 Software Update Services (SUS) 1.0。

Windows Server 2008 R2 需要 WSUS 3.0 SP2。如果您安装的是 Windows Server 2008 R2，则应该安装 WSUS 3.0 SP2。请不要在 Windows Server 2008 R2 上安装 WSUS 3.0 SP1。

#### 升级到 WSUS 3.0 SP2 之前

1.  检查事件日志中的最近错误、下游服务器和上游服务器之间的同步问题，以及客户端报告问题。在升级之前解决这些问题。

2.  或者，您可以运行 DBCC CHECKDB 以确保 WSUS 数据库被正确索引。有关 DBCC CHECKDB 的详细信息，请访问 [DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948)。

3.  备份 WSUS 数据库。请注意，WSUS 3.0 SP2 安装程序会将新数据库添加到默认目录中，此默认目录为 *drive*\\WSUS（*drive* 是拥有最大可用空间的本地 NTFS 驱动器）。如果此目录中已经存在数据库备份，则该备份可能会被覆盖。最佳实践为：升级到 WSUS 3.0 SP2 之前，将当前版本的 WSUS 数据库备份保存在其他位置。

4.  如果您手动（即没有使用 Wsusutil 实用程序）更改了 WSUS 使用的端口，且当前运行的是 SUS 1.0 或 WSUS 2.0，请在卸载 SUS 1.0 或 WSUS 2.0 64 位之前启动默认网址。

5.  如果现有 WSUS 数据库的连接已打开（例如，如果 SQL Server Management Studio 已打开），安装可能会失败。安装 WSUS 3.0 SP2 之前关闭所有连接。

### 从失败的升级中恢复

如果您将较早版本的 WSUS 升级到 WSUS 3.0 SP2，但升级失败（由于尝试从 SUS 1.0 进行不受支持的升级以外的原因)，请执行以下任务。

1.  重新安装 WSUS 的早期版本。
2.  在尝试升级之前，从您所做的备份还原数据库。如果存在以前安装的 WSUS 3.0 SP2 数据库，则无法成功完成升级。大多数情况下，WSUS 还会自动创建备份。有关位置的信息，请参见 WSUSSetup.log 文件。
3.  请查看日志以确定故障产生的原因，然后解决该问题。
4.  安装 WSUS 3.0 SP2。

### 升级到 WSUS 3.0 SP2 之前更改计算机名称可能导致升级失败

如果在安装 WSUS 2.0 之后而尚未升级到 WSUS 3.0 SP2 时更改计算机名称，升级可能失败。

请使用以下脚本删除并重新添加 ASPNET 和 WSUS Administrators 组。然后重新运行升级。

        ```

### 如果已从 MSDE 迁移到 WSUS 2.0 上的 SQL Server 2008 或 SQL Server 2005，则必须更改注册表值

如果您已安装 WSUS 2.0 并且迁移到 SQL Server 2008 或 SQL Server 2005，则必须将 **HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** 值从 1 更改为 0。如果在升级到 WSUS 3.0 SP2 之前未更改此值，升级将失败。

### 如果卸载 WSUS 3.0 SP2 时遗留了日志文件，在重新安装后这些文件的权限可能不正确

卸载 WSUS 3.0 SP2 时，可以选择保留安装的日志文件。重新安装 WSUS 3.0 SP2 时，旧的日志文件会失去其权限（通常仅针对 WSUS 管理员）。最佳实践为：在安装后确认这些日志文件的权限。

### 如果 WSUS 2.0 客户端的更新为“不适用”状态，则升级到 WSUS 3.0 SP2 后的短时间内，更新将显示为“未知”。

如果现有 WSUS 2.0 服务器客户端的更新为“不适用”，则升级到 WSUS 3.0 SP2 后的短时间内，这些更新可能会列为“未知”状态。下次客户端完成扫描后，更新状态将返回“不适用”。

安装 WSUS 3.0 SP2
-----------------

WSUS 循序渐进安装指南（网址为 [http://go.microsoft.com/fwlink/?LinkId=139836](http://go.microsoft.com/fwlink/?linkid=139836)）提供了有关使用 Windows Server Manager 或 WSUSSetup.exe 文件安装 WSUS 3.0 SP2 的说明。

有关如何安装和使用 WSUS 的全部信息，请参见：

WSUS 部署指南：[http://go.microsoft.com/fwlink/?LinkId=139832](http://go.microsoft.com/fwlink/?linkid=139832)。

WSUS 操作指南：[http://go.microsoft.com/fwlink/?LinkId=139838](http://go.microsoft.com/fwlink/?linkid=139838)。

为无人参与的 WSUS 3.0 SP2 安装设置命令行参数
--------------------------------------------

您可以使用 WSUS 命令行安装程序来执行 WSUS 3.0 SP2 无人参与的安装。下表显示了 WSUS 3.0 SP2 安装程序的命令行参数。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >选项</th>
<th style="border:1px solid black;" >描述</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>/q</strong></td>
<td style="border:1px solid black;">执行无提示安装。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/u</strong></td>
<td style="border:1px solid black;">卸载。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">先决条件检查。检测系统，并报告所有丢失的先决条件。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">显示命令行参数及其描述。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">从以前版本的 WSUS 升级。（不支持从 SUS 1.0 升级。）此选项的唯一有效参数为 /q（无提示安装）。此选项的唯一有效属性为 DEFAULT_WEBSITE。</td>
</tr>
</tbody>
</table>
  
下表显示了 WSUS 3.0 SP2 的命令行属性。
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >属性</th>
<th style="border:1px solid black;" >描述</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">CONTENT_LOCAL</td>
<td style="border:1px solid black;">0=在本地存储内容，1=存储在 Microsoft Update 上</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CONTENT_DIR</td>
<td style="border:1px solid black;">内容目录路径。默认路径为 <em>WSUSInstallationDrive\WSUS\WSUSContent</em>，其中 <em>WSUSInstallationDrive</em> 是具有最大可用空间的本地驱动器。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Windows Internal Database 数据目录的路径。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQLINSTANCE_NAME</td>
<td style="border:1px solid black;">该名称应以 <em>ServerName</em>\<em>SQLInstanceName</em> 格式显示。如果该数据库实例位于本地计算机上，请使用 %COMPUTERNAME% 环境变量。如果未提供现有实例，则默认为 %COMPUTERNAME%\WSUS。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DEFAULT_WEBSITE</td>
<td style="border:1px solid black;">0=端口 8530，1=端口 80</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PREREQ_CHECK_LOG</td>
<td style="border:1px solid black;">日志文件的路径和文件名</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CONSOLE_INSTALL</td>
<td style="border:1px solid black;">0=安装 WSUS server，1=仅安装控制台</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ENABLE_INVENTORY</td>
<td style="border:1px solid black;">0=不安装清单功能，1=安装清单功能</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_DATABASE</td>
<td style="border:1px solid black;">0=保留数据库，1=删除数据库</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DELETE_CONTENT</td>
<td style="border:1px solid black;">0=保留内容文件，1=删除内容文件</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_LOGS</td>
<td style="border:1px solid black;">0=保留日志文件，1=删除日志文件（与 /u 安装开关一起使用）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=使用当前数据库，1=创建数据库</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">返回 Windows Installer 进度消息的窗口句柄</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=加入 Microsoft Update 改善计划，0=不加入 Microsoft Update 改善计划</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=不将内容的位置写入数据库，0=将内容的位置写入数据库（用于 NLB）</td>
</tr>
</tbody>
</table>
  
### 示例用法
  
```  
WSUSSetup.exe /q DEFAULT\_WEBSITE=0（使用端口 8530 在安静模式下安装） WSUSSetup.exe /q /u（卸载 WSUS）  
```
 
> [!IMPORTANT]
> 如果在安静模式下安装 WSUS 3.0 SP2 (/q)，并且计算机没有安装所有必备组件，安装将生成一个名为 WSUSPreReqCheck.xml 的文件，并将其保存在 %TEMP% 目录中。
 

<span id="BKMK_KnownIssues"></span>
已知问题
--------

-   WSUS 安装向导成功完成后，将指示用户单击“完成”。极少数情况下，会出现一个包含以下消息的错误对话框：“**与服务器进行通信时发生错误，此向导必须关闭”。您可以从 WSUS 控制台“选项”页重新启动 WSUS Server 配置向导**”。为确保您的安装选项已保存，请打开 WSUS 管理控制台上的“选项”页，然后确认每节的设置。
-   **Windows Update Agent (WUA) 客户端的本地化版本将于 WSUS 3.0 SP2 发行以后发行**。这是由于该发行版本依赖于 Windows 7 的本地化计划。在发行 WSUS 3.0 SP2 和发行 WUA 客户端的本地化版本期间，WUA 客户端仅支持五种语言（英语、德语、法语、西班牙语和日语）。
-   **在从 WSUS 3.0 SP2 服务器管理的下游 WSUS 3.0 SP1 服务器环境中，此 SP2 发行版本中介绍的新更新和计算机状态报告不能正常运行**。如果为 SP1 服务器运行新报告，则会显示以下错误消息：“生成报告时发生错误。请尝试重新运行该报告，如果问题仍存在，请联系您的网络管理员”。重新运行报告不能解决问题，此问题也与网络无关。新的报告取决于 SP1 中不存在的 API 功能；但是，SP2 管理控制台在管理 SP1 服务器时不会阻止新报告。
-   **在没有证书名称的情况下配置 SSL 时，会导致到 WSUS 3.0 SP2 的升级失败**。配置 SSL 时必须提供证书名称。
-   **安装在 Windows Server 2008 上运行 Windows Internal Database 的 WSUS 3.0 SP2 会阻止到 Windows Server 2008 R2** 的升级。在继续升级到 Windows Server 2008 R2 之前，会显示一条兼容性报告错误消息，提示您关闭 Windows Internal Database。必须首先升级 Windows Internal Database，才能继续升级到 Windows Server 2008 R2。请参见[如何获取 Windows Internal Database 的最新 service pack](http://go.microsoft.com/fwlink/?linkid=162104) (http://go.microsoft.com/fwlink/?LinkId=162104) 以获取相关说明及升级 Windows Internal Database 的详细信息。

版权声明
--------

本文档中的信息（包括 URL 和对其他 Internet 网站的引用）如有变更，恕不另行通知。除非另行说明，否则本文档示例中涉及的公司、组织、产品、域名、电子邮件地址、徽标、人物、地点和事件均属虚构，与任何真实的公司、组织、产品、域名、电子邮件地址、徽标、人物、地点或事件无关，也不应进行这方面的推断。遵守所有适用的版权法是用户的责任。在不限制版权权利的情况下，未经 Microsoft Corporation 的明确书面许可，不得出于任何目的，以任何形式或通过任何手段（电子、机械、复印、录制或其他方式）复制本文档的任何部分或将其存储或引入到检索系统中或进行传播。

本文档可能涉及 Microsoft 的专利、专利申请、商标、版权或其他知识产权。除非在 Microsoft 的任何书面许可协议中作了明确规定，否则，提供本文档并不意味着向您授予对这些专利、商标、版权或其他知识产权的任何许可。

© 2009 Microsoft Corporation。保留所有权利。

Microsoft、Active Directory、ActiveX、Authenticode、Excel、InfoPath、Internet Explorer、MSDN、Outlook、Visual Studio、Win32、Windows、Windows Server 和 Windows Vista 均为 Microsoft 集团公司的商标。

所有其他商标均为其各自所有者的财产。
