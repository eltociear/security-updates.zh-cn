---
TOCTitle: WSUS Service Pack 1 的自述文件
Title: WSUS Service Pack 1 的自述文件
ms:assetid: '937ecfe9-e8e0-41ac-85f7-4b65956f3d1e'
ms:contentKeyID: 18125909
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc708486(v=WS.10)'
---

WSUS Service Pack 1 的自述文件
==============================

本文档描述了影响装有 Service Pack 1 的 Windows Server 更新服务 (WSUS SP1) 的已知问题。在了解了关于 WSUS SP1 的信息之后，您便可查找原始 WSUS 自述文件说明中原来包含的所有信息。此信息包括安装 WSUS 的建议和要求。要下载 WSUS SP1，请参阅 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=67516)。

WSUS SP1 的新增功能
-------------------

WSUS SP1 是可改善 WSUS 的安全性、可靠性、可扩展性、兼容性和性能的服务包版本。新的功能和改善包括：

-   Windows Vista 客户支持：运行 Windows Vista 的计算机可通过装有 SP1 服务器的 WSUS 进行更新。
-   更多客户语言支持：支持所有 Office 和 Windows Vista 语言。
-   新版本 WMSDE：WMSDE 实例将由 WSUS SP1 升级为 WMSDE SP4（WSUS RTM 使用 WMSDE SP3）。
-   性能改善：WSUS SP1 包括各种可缩短用户界面响应时间的性能改善。
-   所有热修补程序：WSUS SP1 包括自 WSUS RTM 以来已发行的所有变更和热修补程序。
-   支持 SQL Server 2005。

开始对 WSUS SP1 进行升级之前
----------------------------

下列问题是升级 WSUS SP1 所特有的。请注意，此主题原始版本的“开始之前”部分中概述的问题和要求在本部分中并没有列出，但仍保持有效。例如，原始“开始之前”部分中概述的设置要求仍然有效。

**注意**   将 SP1 应用至 WSUS 2.0 之后，不能卸载服务包。卸载 SP1 将会卸载整个产品。

**重要提示**   本文档包含了关于如何修改注册表的信息。确保在修改注册表之前对其进行备份。确保知道在出现问题时如何还原注册表。有关如何备份、还原和修改注册表的信息，请参阅 Microsoft 知识库中的下列文章：

[Microsoft Windows 注册表描述](http://support.microsoft.com/kb/256986) (http://support.microsoft.com/kb/256986/)

#### 问题 1：确保有备份数据库所需的足够磁盘空间

当从 WSUS RTM 进行升级时，WSUS SP1 安装程序会自动创建 WSUS 数据库的备份。您需要确保 WSUS 服务器文件系统上有足够的磁盘空间，以存储 WSUS 数据库的备份，否则 WSUS SP1 的安装将会失败。

**确定是否有足够的空间**
1.  打开 Windows 资源管理器，导航至存储有 WSUS 数据库的文件夹。默认情况下，WSUS 在此处安装数据库：

    
        ```
2.  按住 **Ctrl**，选择 **SUSDB.MDF** 和 **SUSDB\_log.LDF**，然后右击并选择“属性”。

3.  在“文件”对话框中，阅读“磁盘大小”中的值。您的磁盘必须至少具备如此多的可用空间，以用于 WSUS SP1 安装。

4.  从“开始”菜单，单击“我的电脑”。确保安装有 WSUS 的磁盘具备所需的磁盘空间。

如果由于某些原因 WSUS SP1 安装程序失败，请手动还原备份数据库。有关还原 WSUS 数据库的说明，请参阅 [WSUS 操作指南](http://technet2.microsoft.com/windowsserver/en/library/05f2e884-ae62-4c90-9681-6c9f2f3c9fd91033.mspx)。

#### 问题 2：WSUS SP1 仅升级 WSUS RTM

仅可使用 WSUS SP1 升级 WSUS RTM。此时，不支持从 WSUS 发行候选版本进行的升级。如果您安装了 WSUS 发行候选版本或 WSUS 的任何较早内部版本，您必须卸载这些内部版本，然后运行 WSUS SP1。

#### 问题 3：在更新 WSUS SP1 期间，您服务器上的 IIS 服务将停止

在升级过程中，WSUS SP1 升级安装程序会停止您服务器上的“Internet 信息服务 (IIS)”服务。这意味着您服务器上由 IIS 安装托管的所有网站将不在升级期间提供。升级结束时，IIS 将自动启动。

#### 问题 4：在升级期间，您不得运行调用 WSUS API 的应用程序

WSUS 应用程序接口 (API) 调用将与 WSUS SP1 安装程序发生冲突，从而导致升级失败（您将接收到要求您重启服务器以完成升级的消息）。

#### 问题 5：升级为 WSUS SP1 时，可能需要禁用防病毒程序

通过应用 WSUS SP1 升级 WSUS 时，在成功地执行升级或应用服务包之前，可能需要禁用防病毒程序。禁用防病毒程序之后，在应用升级或服务包之前，请重启 Windows Server 计算机。此过程能防止锁定升级过程需要访问的文件。完成安装后，请确保重新启用您的防病毒程序。请访问防病毒程序供应商的网站，以获取禁用和重新启用防病毒程序和版本的精确步骤。

| ![](images/Cc708486.Caution(WS.10).gif)警告                                                                                                               |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 此操作可能使您的计算机或您的网络更易于受到恶意用户或诸如病毒之类恶意软件的攻击。我们不建议执行此操作，但提供相关信息，以便您能自行决定是否实施此操作。如果执行此操作，应独自承担风险。 |

| ![](images/Cc708486.note(WS.10).gif)注意                                                                        |
|----------------------------------------------------------------------------------------------------------------------------------------------|
| 旨在帮助防止计算机受病毒侵袭的防病毒程序。您不得从不信任的来源下载或打开文件，不得在禁用防病毒程序时，访问您不信任的网站或打开电子邮件附件。 |

#### 问题 6：如果您正在使用代理服务器，SP1 升级可能清除代理配置用户名和密码

如果您正在使用代理服务器，有时候 SP1 升级可能会清除代理配置用户名和密码。这可能导致 Microsoft Servers 升级的同步，从而产生“参数无效”错误。要解决此问题，请重置代理配置用户名和密码并重新同步您的服务器。

#### 问题 7：如何恢复失败的升级以便将您的 WSUS 服务器还原为一致状态，然后重试升级。

如果 WSUS SP1 的升级失败，这可能使您的 WSUS 安装处于不一致或不可用状态。为了重试对 WSUS SP1 进行升级，您需要使您的 WSUS 安装处于一致状态。要执行此操作，您可使用升级过程开始时创建的备份数据库以便将您的 WSUS 还原为升级前状态。

如果升级失败，请遵循这些步骤，以重试升级至 WSUS SP1：

**重试升级至 WSUS SP1**
1.  通过查看 WSUSSetup\_%timestamp%.log 文件的内容，确定备份数据库的位置。此文件位于以下文件夹中：

    -   %programfiles%\\Update Services\\LogFiles

2.  使用下列内容还原 WSUS 计算机上的备份数据库：

    -   osql.exe -S &lt;DatabaseInstance&gt; -E -Q "USE master ALTER DATABASE SUSDB SET SINGLE\_USER WITH ROLLBACK IMMEDIATE RESTORE DATABASE SUSDB FROM DISK=N'&lt;PathToDatabaseBackup&gt;' WITH REPLACE ALTER DATABASE SUSDB SET MULTI\_USER"
    -   谨记用您的安装的值替换 &lt;DatabaseInstance&gt; 和 &lt;PathToDatabaseBackup&gt;。
    -   对于 &lt;DatabaseInstance&gt;，请使用以下注册表项中的值：
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\SqlServerName
    -   对于 &lt;PathToDatabaseBackup&gt;，请使用步骤 1 中确定的值

3.  卸载 WSUS，但保留 WSUS 数据库和日志文件，并在受到提示删除文件时更新文件。（确保未选定“删除 Microsoft Windows Server 更新服务”中的所有选项。）

4.  重新安装 WSUS RTM（原始版本不是 WSUS SP1）。当您受到提示执行此操作时，请使用现有数据库。这将使您的 WSUS 返回至一致状态。

5.  安装 WSUS SP1。

**注意**   您不能将上述步骤 1 中所得的备份数据库直接用于对 WSUS SP1 进行的全新安装中。数据库架构已更改，如不升级至 WSUS SP1，此数据库将不兼容。

#### 问题 8：当 WMSDE 数据库已迁移时，WSUS SP1 升级有时可能失败

解决方案根据您是否已迁移到本地或远程 SQL 服务器而有所不同。

#### WMSDE 数据库迁移至本地 SQL 2000 服务器

为了便于 WSUS SP1 的安装程序包能确定无 WMSDE 数据库需要更新，必须更改注册表项值。

如果您已将 WMSDE 迁移至本地 SQL 2000 服务器，在尝试升级至 WSUS SP1 之前，必须对以下注册表进行更改：

-   将以下注册表项的值从“1”更改为“0”：
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled

#### WMSDE 数据库迁移至远程 SQL 2000 服务器

为了便于 WSUS SP1 的安装程序包能确定无 WMSDE 数据库需要更新，必须更改两个注册表项值。必须先在后端服务器初始化更新，然后在前端服务器初始化更新。  

如果您已将 WMSDE 迁移至远程 SQL 服务器，在尝试升级至 WSUS SP1 之前，必须对以下注册表进行更改：

1.  将以下注册表项的值从“1”更改为“0”：
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled
2.  将以下注册表项的值从“0x80”更改为“0x20”
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\InstallType 

更新这些注册表项值后，先后在台端服务器和前端服务器上初始化更新。

#### 问题 9：WSUS SP1 不更新用远程 SQL 部署进行设置的 WSUS 服务器

必须在前端服务器和后端服务器上运行 WSUS SP1 安装程序包。

**使用远程 SQL 时升级至 WSUS SP1**
1.  在无交换机的前端上运行安装程序包并选择升级。

2.  在无交换机的后台上运行安装程序包并选择升级。

#### 问题 10：在升级至 WSUS SP1 之前更改计算机的名称可能导致升级失败

如果您在安装了 WSUS RTM 和在升级至 WSUS SP1 之前更改了计算机名称，WSUS SP1 升级可能失败。

请使用下列脚本来删除并重新添加 ASPNET 和 WSUS Administrators 组。然后再次运行升级。

        ```
| ![](images/Cc708486.note(WS.10).gif)注意     |
|---------------------------------------------------------------------------|
| 您必须用存储有您实际内容的路径替换最后一行中的 &lt;ContentDirectory&gt;。 |

然后替换 WSUS Readme 中的原始内容
---------------------------------

下列是 WSUS readme 中的原始内容。WSUS SP1 *不能*解决下列任何问题。此处包括有此内容，以供参考。

开始之前
--------

#### 问题 1：必须安装 IIS

Microsoft® Windows Server™ 更新服务 (WSUS) 需要安装 Internet 信息服务 (IIS)。然而，在 Microsoft Windows Server 2003 和 Microsoft Windows® 2000 Server 上，默认情况下不安装 IIS，所以 Windows Server 更新服务设置可能无法继续，显示出的错误消息表示未安装 IIS。

安装 IIS：

1.  打开控制面板。
2.  双击“添加或删除程序”。
3.  单击“添加/删除 Windows 组件”。
4.  在“组件”列表中，单击“应用程序服务器”。
5.  单击“详细信息”。
6.  选择 **ASP.NET** 复选框。启用“网络 COM+ 访问”，Internet 信息服务 (IIS) 将自动被选定。
7.  选择“Internet 信息服务 (IIS)”，然后单击“详细信息”，以查看 IIS 选用组件列表。
8.  选择想要安装的所有选用组件。“万维网服务”选用组件包括重要的诸如“Active Server Pages”组件和“远程管理 (HTML)”之类的子组件。要查看和选择这些组件，请单击“万维网服务”，然后单击“详细信息”。单击“确定”，直到返回至“Windows 组件向导”。
9.  单击“下一步”，并完成“Windows 组件向导”。
10. 安装 IIS 后，运行“Windows Server 更新服务设置”。

#### 问题 2：对于运行了 Windows 2000 Server 的服务器，安装 WSUS 之前，IIS 中至少需要存在一个网站

如果运行安装程序时，IIS 中不存在任何网站，Windows Server 更新服务设置可能无法创建网站。例如，如果您将 Software Update Services (SUS) 1.0 网站作为 IIS 中的唯一网站且在安装 WSUS 之前删除了该网站，可能会发生此问题。

在此情况下，您需要使用 Internet 信息服务 (IIS) 管理器管理单元创建新的网站，一旦完成创建新网站，您就可在 WSUS 安装期间选择此网站或指定新的网站。

如果因为不存在任何网站，您尝试安装 WSUS 和安装程序失败，请打开 IIS 管理器管理单元，并删除网站“Web Site \#1”。然后遵循上述步骤，并再次运行安装程序。

#### 问题 3：安装首要组件

#### 软件要求

下表显示每一受支持的操作系统所必需的软件。运行 WSUS 安装程序之前，请确保 WSUS 服务器符合此列表中的要求。如果任何这些更新需要在完成安装后重启计算机，您应在安装 WSUS 之前进行重启。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >操作系统</th>
<th style="border:1px solid black;" >要求</th>
<th style="border:1px solid black;" >下载</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">所有操作系统</td>
<td style="border:1px solid black;">Microsoft Internet 信息服务 (IIS) 5.0</td>
<td style="border:1px solid black;">从操作系统进行安装。
请参见问题 1：必须安装 IIS。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">所有操作系统</td>
<td style="border:1px solid black;">后台智能传输服务 (BITS) 2.0</td>
<td style="border:1px solid black;">有关 Windows Server 2003 操作系统的信息，请参阅下载中心 (<a href="http://go.microsoft.com/fwlink/?linkid=47251">http://go.microsoft.com/fwlink/?LinkId=47251</a>）上的“后端智能传输服务 (BITS) 2.0 更新”和“WinHTTP 5.1 Windows Server 2003 (KB842773)”。
有关 Windows Server 2000 操作系统的信息，请参阅下载中心 (<a href="http://go.microsoft.com/fwlink/?linkid=46794">http://go.microsoft.com/fwlink/?LinkId=46794</a>）上的“后台智能传输服务 (BITS) 2.0 更新”和“WinHTTP 5.1 Windows Server 2000 (KB842773)”。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">用于 Windows Server 2003 的 Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47358">用于 Windows Server 2003 的 Microsoft .NET Framework 1.1 Service Pack 1</a>
或者，转到<a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a>并扫描“Critical Updates”和“Service Packs”；安装用于 Windows Server 2003 的 Microsoft .NET Framework 1.1 Service Pack 1。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">与 Microsoft SQL 完全兼容的数据库软件</td>
<td style="border:1px solid black;">N/A</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">与 Microsoft SQL 完全兼容的数据库软件</td>
<td style="border:1px solid black;">如果您未使用 Microsoft SQL Server 2000，则可能安装 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000)。这需要几个步骤。有关详细信息，请参阅以下“在 Windows 2000 上安装 MSDE”。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft Internet Explorer 6.0 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47359">Microsoft Internet Explorer 6 Service Pack 1</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 版可重新分发包</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47369">Microsoft .NET Framework 1.1 版可重新分发包</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47368">Microsoft .NET Framework 1.1 Service Pack 1</a>
或者，转到<a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a>并扫描“Critical Updates”和“Service Packs”；安装用于 Windows Server 2000 的 Microsoft .NET Framework 1.1 Service Pack 1。</td>
</tr>
</tbody>
</table>
 

除了这些要求之外，如必要，WSUS 可能在您的服务器上安装或配置 1.1 版本的 ASP.NET。（WSUS 安装程序配置 ASP.NET.）

#### 在 Windows 2000 上安装 MSDE 2000

如果您使用的是用于 WSUS 的 Windows 2000，且不具备访问 Microsoft SQL Server 2000 的权限，在运行 WSUS 安装程序之前，您应安装 Microsoft SQL Server 2000 Desktop Engine (MSDE)。如果您已在 WSUS 服务器上安装了 MSDE，则不必为其设置用于 WSUS 的特殊示例。在 WSUS 安装过程中您仅需标明现有示例的名称即可。

在 Windows 2000 Server 上安装 MSDE 需要四个步骤。首先，必须将 MSDE 存档下载至您的 WSUS 服务器上的文件夹，并将其展开。其次，使用命令提示符和命令行选项来运行 MSDE 安装程序，设置 sa 密码，然后将 WSUS 指派为示例名称。然后，完成 MSDE 安装后，您应检验 WSUS 实例是否运行为 NT 服务。最后，必须添加安全修补程序至 MSDE，以保护您的 WSUS 服务器。

#### 步骤 1：下载并展开 MSDE 存档

首先，必须将 MSDE 存档下载至您的 WSUS 服务器上的文件夹，并将其展开。请参阅 [Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Release A](http://go.microsoft.com/fwlink/?linkid=47366)。

#### 步骤 2：安装 MSDE

其次，使用命令提示符和命令行选项来运行 MSDE 安装程序，设置 sa 密码，然后将 WSUS 指派为示例名称。然后，完成 MSDE 安装后，您应检验 WSUS 实例是否运行为 NT 服务。

要安装 MSDE，请设置 sa 密码，并指派示例名称：

1.  在命令提示符下，导航至在“步骤 1：下载并展开 MSDE 存档”中指定的 MSDE 安装文件夹。
2.  键入下列内容：**setup sapwd="***password***" instancename=WSUS**
    其中的 *password* 是 MSDE 示例中 sa 帐户的强密码，**instancename** 是数据库的名称。或者，您可将默认示例名称（而不是“WSUS”）用于您的 WSUS 数据库。如果您选择此操作，那么您就不必在命令行参数中键入 **instancename=WSUS**。此命令启动 MSDE 安装程序，设置 sa 密码，并将此 MSDE 示例命名为您指定的值。

#### 步骤 3：验证是否已安装 MSDE 的 WSUS 示例

1.  单击“开始”，然后单击“运行”。
2.  在“打开”对话框中，键入 **services.msc**，然后单击“确定”。

向下滚动服务列表，验证是否存在名称为 MSSQL$WSUS（如果您使用“WSUS”作为 instancename）或 MSSQLSERVER（如果您使用默认的 instancename）的服务。

#### 步骤 4：启动 MSDE 示例。

在 MSDE 安装结束时，必须启动实例。如果您使用“WSUS”作为 instancename，则会启动“MSSQL$WSUS。”如果您使用默认的 instancename，则会启动 MSSQLSERVER。除非您启动了此服务，否则 WSUS 将无法使用示例中的数据库。

#### 步骤 5：更新 MSDE

您必须下载和安装 [MS03-031 公告中所述的安全修补程序：用于 SQL Server 的累积安全修补程序](http://go.microsoft.com/fwlink/?linkid=47364)。

要下载安全修补程序，请参阅 [SQL Server 2000（32 位）安全修补程序 MS03-031](http://go.microsoft.com/fwlink/?linkid=47363)。

#### 问题 4：最低可用磁盘空间要求

下列是安装“服务器更新服务”的最低可用磁盘空间要求：

-   系统分区，1 GB
-   将存储数据库文件的卷，2 GB
-   6 GB，以内容投影编号为基础

#### 问题 5：安装最新版本之前，必须通过使用“添加或删除程序”卸载早期版本的 WSUS

如果您计划在安装了 Windows Update Services Beta 1 或 Beta 2 的服务器上安装 Windows Server 更新服务，首先您需要通过使用“控制面板”中的“添加或删除程序”卸载早期版本。

#### 问题 6：WSUS 要求在 SQL Server 中打开嵌套触发器选项

默认情况下，此选项是打开的，但可通过 SQL Server 管理员关闭。

如果您计划使用 SQL Server 数据库作为 Windows Server 更新服务数据存储，在 WSUS 管理员安装 WSUS 及在安装期间指定数据库之前，SQL Server 管理员应检验是否已打开服务器上的嵌套触发器选项。

WSUS 安装打开 RECURSIVE\_TRIGGERS 选项，这是数据库特有的选项，但是，它不会打开嵌套触发器选项，嵌套触发器选项是服务器全局选项。

要查看是否已打开嵌套触发器选项，请使用下列：

**sp\_configure 'nested triggers'**

要在 SQL Server 中打开嵌套触发器选项，请在运行 SQL Server 的计算机上的批文件中运行下列：

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

#### 问题 7：WSUS 安装命令行参数

您可执行无人参与的 WSUS 安装。有关命令行参数的详细信息，请参阅“附录 A：无人参与的安装”，它位于[部署 Microsoft Windows Server 更新服务](http://go.microsoft.com/fwlink/?linkid=41777)中。

已知问题
--------

#### 问题 1：IIS 锁定向导

如果您在运行 Windows 2000 Server 的计算机上运行 Internet 信息服务 (IIS)，请从 Microsoft TechNet 上的“IIS Lockdown Tool”页中安装最新版本的“IIS 锁定向导”（包括 URLScan）。Microsoft 强烈建议您安装此工具，以帮助确保您的 IIS 服务器的安全。关闭不需要的 IIS 功能，减少潜在的安全风险，即可运行 IIS 锁定向导。

| ![](images/Cc708486.note(WS.10).gif)注意                                                             |
|-----------------------------------------------------------------------------------------------------------------------------------|
| WSUS 安装不安装这些组件。必须手动安装这些组件。您不需要在运行了 Windows Server 2003 的计算机上安装 IIS 锁定，因为此功能是内置的。 |

#### 问题 2：不支持直接在数据库中更改 WSUS 配置

Windows Server 更新服务在数据库（MSDE 或 SQL Server）中存储其配置数据。但是，不支持通过直接访问数据库更改配置数据。管理员不得以此方式尝试修改 WSUS 配置。受支持的更改 WSUS 配置的方式是通过使用 WSUS 控制台或调用 WSUS API。

#### 问题 3：为了访问 WSUS 管理网站，必须启动活动脚本

在管理员工作站上，您必须配置 Internet Explorer，以便在您使用 Internet Explorer 访问 WSUS 管理网站之前允许启用活动脚本。

#### 问题 4：在 WSUS 安装期间，必须重启 IIS

Windows Server 更新服务安装程序将重启 IIS，而不给予通知。这可能影响您组织中现有的网站。

#### 问题 5：更改 WSUS 或 SMS 管理点 (MPs) 虚拟目录访问

默认情况下，Windows Server 更新服务的内容虚拟目录是通过匿名访问设置的。如果您将此设置更改为需要身份验证，客户端将接收到身份验证错误，并被拒绝访问下载更新。这是一个已知问题，当需要进行隐式身份验证时，其中的 Winhttp.dll 会使用错误的身份验证上下文，所以身份验证质询将失败。要防止此问题，请确保 WSUS 服务器和 SMS MP 是通过匿名访问 IIS 虚拟目录而得以设置的。

#### 问题 6：在 Windows Small Business Server 2003 上安装 WSUS 时，必须修改默认网站 WSUS 虚拟根目录的访问设置，以便使 WSUS 客户端能从服务器进行自我更新

WSUS 服务器安装两个虚拟根目录（SelfUpdate 和 ClientWebService）及默认网站（端口 80 上）主目录下的一些文件。这使客户端能通过默认网站进行自我更新。默认情况下，在 Windows Small Business Server 2003 上，默认网站配置为拒绝访问非服务器上的任何 IP 或 localhost。这意味着 SelfUpdate 和 ClientWebService 根目录被拒绝访问，客户端无法进行自我更新。要授予客户端进行自我更新的访问权限，请在默认网站的 SelfUpdate 和 ClientWebService 虚拟根目录下完成下列步骤。

1.  单击虚拟根“属性”，单击“目录安全”，单击“IP 地址和域名限制”，然后单击“编辑”。
2.  选择“已授予访问权限”，然后单击“确定”。关闭所有属性页。

#### 问题 7：在 Small Business Server 上安装 WSUS - 集成问题

-   如果 Windows Small Business Server 2003 使用 ISA 代理服务器访问 Internet，必须在**设置**用户界面中手动输入下列内容：代理服务器设置，代理服务器名称和端口。
-   如果 ISA 使用了 Windows 身份验证，应在“DOMAIN\\user”（属于“Internet 用户”组的用户）表中输入代理服务器凭据。

#### 问题 8：将某台计算机从一个计算机组移动至另一计算机组时，从管理控制台查看此计算机出现于新的组中可能需要一个小时

首次将某台计算机指派至目标组时，组信息会修改计算机上的数据。该数据会定期或每隔一个小时被刷新。因此，当将某台计算机从一个计算机组移动至另一计算机组时，在客户端上刷新该信息并将其显示于 WSUS 管理控制台上可能需要一个小时。

#### 问题 9：如果您在成员服务器上安装了 WSUS，且想要将成员服务器升级为域控制器，则应该首先卸载 WSUS

如果您在成员服务器上安装了 WSUS，且想要将成员服务器升级为域控制器，则需要执行下列步骤：

1.  卸载 WSUS。
2.  将服务器升级为域控制器。
3.  重新安装 WSUS。

#### 问题 10：如果您想要将 WSUS 服务器从域控制器降级为成员服务器，则应首先卸载 WSUS

如果您在域控制器上运行了 WSUS 服务器，且想要将域控制器降级为成员服务器，则需要完成下列步骤：

1.  卸载 WSUS，保留数据库。
2.  创建名称为 ASPNET 的用户帐户。
3.  在命令提示符下，键入 **aspnet\_regiis -i**。
4.  重新安装 WSUS，并使用保留的数据库。

#### 问题 11：如果您是在安装了 WSUS 之后才安装.NET Framework 1.0 或 2.0，WSUS 管理控制台将不会出现

这是由于.NET Framework 1.0 是用 IIS 注册的，且该 WSUS 服务器需要.NET Framework 1.1。要解决此问题，请打开 aspnet\_regiis.exe，并运行下列命令，其中 *website id* 是下列注册表项中包含的值：

HKLM\\Software\\Microsoft\\WindowsUpdateServices\\Server\\Setup\\IISTargetWebsiteIndex

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\ReportingWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\ClientWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\SimpleAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\WSUSAdmin
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\AdministrationWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\ServrSyncWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\DssAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*website id*&gt;\\ROOT\\Content

#### 问题 12：远程 SQL 限制

WSUS 为在与带有其他 WSUS 应用程序的计算机分离的计算机上运行数据库软件提供了限制支持。

-   您不能将 Windows 2000 Server 用作远程 SQL 对中的前端计算机。
-   您不能将配置为域控制器的服务器用作远程 SQL 对的前端或后端。
-   您不能将 WMSDE 或 MSDE 用作后端计算机上的数据库软件。
-   如果终端服务安装在远程服务器上且以应用程序模式运行,则远程 SQL Server（用作 WSUS 数据库）的安装失败。在终端服务服务器上安装 SQL Server 时，您必须执行下列操作：
    1.  在运行设置之前，请打开命令提示符并键入：“change user /install”
    2.  运行 SQL Server 安装程序。
    3.  运行安装程序之后，在命令提示符下键入：“change user /execute”
-   要设置远程 SQL Server WSUS 数据库，您必须是前端和后端计算机上本地管理员安全组的成员。
-   有关远程 SQL 问题的详细信息，请参阅“附录 C:远程 SQL”，它位于[部署 Microsoft Windows Server 更新服务](http://go.microsoft.com/fwlink/?linkid=41777)中。

#### 问题 13：副本下游服务器的核准可能比父级上游服务器的少

副本下游服务器的核准可能比父级上游服务器的少。这是因为只有当内容在上游服务器上完成下载之后，安装核准才会流向下游服务器。

#### 问题 14：在初始同步失败时重试同步

如果同步失败，您首先应解决的疑难就是尝试再次同步服务器。如果后续的同步仍失败，请使用 WSUS 操作指南中的疑难解答信息。

#### 问题 15：尝试访问 WSUS 管理控制台时，可能出现错误消息 System.IO.FileNotFoundException

如果您收到下列错误消息，则可能需要调整“网络服务”或“ASP.NET 帐户”上的权限：

System.IO.FileNotFoundException：未找到文件或程序集名称 *xxxxxx*.dll，或其任一依赖性。

其中 *xxxx* 是随机名称。

要解决 Windows Server 20003 操作系统中的此问题，请授予“网络服务”帐户对 %systemroot%\\Temp 的读/写访问权限。在 Windows 2000 Server 中，授予 ASP.NET 帐户对 %systemroot%\\Temp 的读/写访问权限。

#### 问题 16：SQL 安全更新 MS03-031 (KB815495)

此更新可能显示为已安装在 WSUS 服务器上，即使安装实际在客户端上已失败。这可能导致将包重新提供给客户端。取消对服务器上更新的核准，即可解决此问题。

#### 问题 17：IIS 在 RTM 升级期间丢失。

如果您用原先版本的 WSUS（如，RC）在服务器上安装了 WSUS RTM，WSUS RTM 将卸载原先版本，然后安装新的版本。这意味着将删除与 IIS 中的 WSUS 相关的虚拟根目录和文件。

如果在默认网站上安装了 WSUS，对 WSUS 虚拟根目录作出的任何与 WSUS 相关的设置将丢失。例如，如果您已为 SSL 配置了 WSUS 虚拟根目录，为确保 WSUS 的安全，您需要在安装 RTM 版本的 WSUS 后再次配置它们。注意：您将收到未在 WSUS 控制台上启用 SSL 的通知。

如果您已在非默认网站上安装了 WSUS，则 WSUS 网站层级的所有附加设置均将丢失。

#### 问题 18：使用主机头

如果您想要将主机头值指派至 IIS 中的默认网站（WSUS 网站），则需要添加“所有未指派的”或已指派的 IP 地址至 IP 地址列表，而无需将主机头值指派至默认网站。这应同时添加至非默认网站

**警告**：这可能破坏“Microsoft 共享点与交换机”功能。

#### 问题 19：需要将 WSUS 控制台 URL 添加至受信任的网站和已启用 Internet Explorer 增强功能的计算机的 Local intranet Web 内容区

如果您已在计算机上启用了 Internet Explorer 增强功能（也称为 Microsoft Windows Server 2003 Internet Explorer 增强安全配置组件），且您未将 WSUS 控制台添加至受信任的站点和 Local intranet Web 内容区上，每当您打开 WSUS 控制台上的页面，系统就会提示您提供用户凭据。

要将 WSUS 控制台添加至 **Local intranet** 和**受信任的站点**内容区：

1.  打开“Internet 选项”（例如，单击“开始”，指向“控制面板”，然后单击“Internet 选项”）。
2.  在“安全性”选项卡上，单击“Local intranet”，单击“站点”，单击“高级”，添加 URLL (http://*WSUSServername*/WSUSAdmin)，然后单击“确定”。
3.  单击“受信任站点”，单击“站点”，添加 WSUS 控制台 URL，单击“确定”，然后再次单击“确定”以退出“Internet 选项”。

#### 版权所有

本文档包含的信息代表 Microsoft Corporation 截至发布日期就所讨论的问题发表的最新观点。由于 Microsoft 必须对不断变化的市场状况作出反应，因此这些观点不应被解释为 Microsoft 的承诺，并且 Microsoft 不保证所示任何信息在发布日期之后仍准确。

本文档仅供参考。对本文档中的信息，Microsoft 不作任何明示、默示或法定保证。

遵守所有适用的版权法是用户的责任。在不限制版权法所规定的权利的情况下，未经 Microsoft Corporation 明确的书面许可，不得出于任何目的、以任何形式或手段（电子的、机械的、影印、录制等等）复制、传播本文档的任何部分，也不得将其存储或引入到检索系统中。

Microsoft 可能具有涉及本文档中主题的专利、专利申请、商标、版权或其他知识产权。除非 Microsoft 的书面许可协议明确规定，否则提供本文档并不意味着赋予您这些专利、商标、版权或其他知识产权的任何许可。

除非另行说明，否则本文档示例中涉及的公司、组织、产品、域名、电子邮件地址、徽标、人物、地点和事件均属虚构，与任何真实的公司、组织、产品、域名、电子邮件地址、徽标、人物、地点或事件无关，也不应进行这方面的推断。

© 2006 Microsoft Corporation。保留所有权利。

Microsoft、SQL Server、Windows 和 Windows Server 均为 Microsoft Corporation 在美国和/或其他国家或地区的注册商标或商标。

本文档中提及的实际公司和产品的名称可能是其各自所有者的商标。
