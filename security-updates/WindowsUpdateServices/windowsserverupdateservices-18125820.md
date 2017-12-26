---
TOCTitle: Windows Server Update Services 自述文件
Title: Windows Server Update Services 自述文件
ms:assetid: '4244109a-395a-4ff8-9989-ea55ab0964a3'
ms:contentKeyID: 18125820
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc720505(v=WS.10)'
---

Windows Server Update Services 自述文件
=======================================

本文档描述了影响 Windows Server Update Services (WSUS) 的已知问题。它包括安装 WSUS 的建议和要求。

| ![](images/Cc720505.note(WS.10).gif)注意                                                                                         |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Microsoft 下载中心 ([http://go.microsoft.com/fwlink/?LinkId=48126](http://go.microsoft.com/fwlink/?linkid=48126))（页面可能为英文）提供了本文档的可下载副本。 |

开始之前
--------

#### 问题 1：必须安装 IIS

Microsoft® Windows Server™ Update Services (WSUS) 要求安装 Internet Information Services (IIS)。但是，在 Microsoft Windows Server 2003 和 Microsoft Windows® 2000 Server 上，默认情况下不安装 IIS，因此 Windows Server Update Services 安装程序可能无法继续，并且显示一条错误消息，表明未安装 IIS。

安装 IIS：

1.  打开控制面板。
2.  双击“添加或删除程序”。
3.  单击“添加/删除 Windows 组件”。
4.  在“组件”列表中，单击“应用程序服务器”。
5.  单击“详细信息”。
6.  选择“ASP.NET”复选框。“启用网络 COM+ 访问”和“Internet 信息服务 (IIS)”将被自动选中。
7.  选择“Internet 信息服务 (IIS)”，然后单击“详细信息”，以查看 IIS 可选组件列表。
8.  选择想要安装的所有可选组件。“万维网服务”可选组件包括重要的子组件，如“Active Server Pages”组件和“远程管理 (HTML)”。要查看和选择这些子组件，请单击“万维网服务”，然后单击“详细信息”。单击“确定”，直到返回到 Windows 组件向导。
9.  单击“下一步”，并完成 Windows 组件向导。
10. 安装 IIS 后，运行 Windows Server Update Services 安装程序。

#### 问题 2：对于运行 Windows 2000 Server 的服务器，安装 WSUS 之前，IIS 中必须至少存在一个网站

如果运行安装程序时，IIS 中不存在任何网站，则 Windows Server Update Services 安装程序可能无法创建网站。例如，如果您将 Software Update Services (SUS) 1.0 网站作为 IIS 中的唯一网站，并且在安装 WSUS 之前删除了该网站，则可能发生此问题。

在这种情况下，您需要使用 Internet 信息服务 (IIS) 管理器管理单元创建新的网站。一旦完成创建新的网站，您就可以在 WSUS 安装期间选择此网站或指定新的网站。

如果由于不存在任何网站，您已经尝试了安装 WSUS，而安装程序失败，请打开 IIS 管理器管理单元，并删除网站“网站 \#1”。然后按照上述步骤执行操作，并再次运行安装程序。

#### 问题 3：安装必备组件

#### 软件要求

下表显示每个受支持的操作系统所必需的软件。运行 WSUS 安装程序之前，请确保 WSUS 服务器符合此列表中的要求。如果任何这些更新需要在完成安装后重新启动计算机，您应该在安装 WSUS 之前重新启动。

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
<td style="border:1px solid black;">Microsoft Internet Information Services (IIS) 5.0</td>
<td style="border:1px solid black;">从操作系统进行安装。
请参阅问题 1：必须安装 IIS。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">所有操作系统</td>
<td style="border:1px solid black;">后台智能传输服务 (BITS) 2.0</td>
<td style="border:1px solid black;">对于 Windows Server 2003 操作系统，请参阅下载中心上的<a href="http://go.microsoft.com/fwlink/?linkid=47251">用于后台智能传输服务 (BITS) 2.0 和 WinHTTP 5.1 Windows Server 2003 的更新程序 (KB842773)</a> (http://go.microsoft.com/fwlink/?LinkId=47251)（页面可能为英文）。
对于 Windows Server 2000 操作系统，请参阅下载中心上的<a href="http://go.microsoft.com/fwlink/?linkid=46794">用于后台智能传输服务 (BITS) 2.0 和 WinHTTP 5.1 Windows 2000 的更新程序 (KB842773)</a> (http://go.microsoft.com/fwlink/?LinkId=46794)（页面可能为英文）。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47358">Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003</a>
或者，转到 <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a> 并扫描关键更新和 Service Pack；安装 Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">与 Microsoft SQL 完全兼容的数据库软件</td>
<td style="border:1px solid black;">暂缺</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">与 Microsoft SQL 完全兼容的数据库软件</td>
<td style="border:1px solid black;">如果您未使用 Microsoft SQL Server 2000，则可能安装 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000)。这需要几个步骤。有关详细信息，请参阅下面的“在 Windows 2000 上安装 MSDE”。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft Internet Explorer 6.0 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47359">Internet Explorer 6 Service Pack 1</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 版可再发行组件包</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47369">Microsoft .NET Framework 1.1 版可再发行组件包</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47368">Microsoft .NET Framework 1.1 Service Pack 1</a>
或者，转到 <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a> 并扫描关键更新和 Service Pack；安装 Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2000。</td>
</tr>
</tbody>
</table>
 

除了这些要求之外，如有必要，WSUS 可能在您的服务器上安装或配置 ASP.NET 1.1 版。（WSUS 安装程序配置 ASP.NET。）

#### 在 Windows 2000 上安装 MSDE 2000

如果您使用的是用于 WSUS 的 Windows 2000，且不具备访问 Microsoft SQL Server 2000 的权限，则在运行 WSUS 安装程序之前，您应安装 Microsoft SQL Server 2000 Desktop Engine (MSDE)。如果您已在 WSUS 服务器上安装了 MSDE，则不必为其设置用于 WSUS 的特殊示例。在 WSUS 安装过程中，您可以仅指明现有实例名称。

在 Windows 2000 Server 上安装 MSDE 包括四个步骤。首先，您必须将 MSDE 存档下载到您的 WSUS 服务器上的某个文件夹，并将其展开。下一步，使用命令提示符和命令行选项来运行 MSDE 安装程序，设置 sa 密码，然后将 WSUS 分配为实例名称。然后，完成 MSDE 安装后，您应该验证 WSUS 实例是否作为 NT 服务运行。最后，您必须将安全更新添加到 MSDE 以保护您的 WSUS 服务器。

#### 步骤 1：下载并展开 MSDE 存档

您必须将 MSDE 存档下载到您的 WSUS 服务器上的某个文件夹，并将其展开。请参阅 [Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Release A](http://go.microsoft.com/fwlink/?linkid=47366)。

#### 步骤 2：安装 MSDE

使用命令提示符和命令行选项来运行 MSDE 安装程序，设置 sa 密码，然后将 WSUS 分配为实例名称。完成 MSDE 安装后，您应该验证 WSUS 实例是否作为 NT 服务运行。

要安装 MSDE，请设置 sa 密码，并分配实例名称：

1.  在命令提示符处，导航到在“步骤 1：下载并展开 MSDE 存档”中指定的 MSDE 安装文件夹。
2.  键入下列内容：**setup sapwd="***密码***" instancename=WSUS**
    其中，*密码*是指此 MSDE 实例上 sa 帐户的强密码，**instancename** 是数据库实例的名称。或者，您可以将默认实例名称（而不是“WSUS”）用于您的 WSUS 数据库。如果您选择这样做，则不必在命令行参数中键入 **instancename=WSUS**。此命令启动 MSDE 安装程序，设置 sa 密码，并将此 MSDE 实例命名为您指定的值。

#### 步骤 3：验证是否已安装 MSDE 的 WSUS 实例

您应该确保您可以看到 MSDE 的 WSUS 实例。

1.  单击“开始”，然后单击“运行”。
2.  在“打开”框中，键入 **services.msc**，然后单击“确定”。

向下滚动服务列表，验证是否存在名为 MSSQL$WSUS（如果您使用“WSUS”作为实例名称）或 MSSQLSERVER（如果您使用默认实例名称）的服务。

#### 步骤 4：启动 MSDE 实例。

在 MSDE 安装结束时，您必须启动实例。如果您使用“WSUS”作为实例名称，则会启动“MSSQL$WSUS。”如果您使用默认实例名称，则会启动 MSSQLSERVER。除非您启动了此服务，否则 WSUS 将无法使用数据库实例。

#### 步骤 5：更新 MSDE

您必须下载并安装公告 [MS03-031：SQL Server 累积安全修补程序](http://go.microsoft.com/fwlink/?linkid=47364)中描述的安全更新。

要下载该安全更新，请参阅 [SQL Server 2000（32 位）安全修补程序 MS03-031](http://go.microsoft.com/fwlink/?linkid=47363)。

#### 问题 4：最低磁盘空间要求

以下是安装 Windows Server Update Services 的最低磁盘空间要求：

-   系统分区，1 GB
-   将存储数据库文件的卷，2 GB
-   6 GB，以内容投影编号为基础

#### 问题 5：安装最新版本之前，必须通过使用“添加或删除程序”卸载 WSUS 的早期版本

如果您计划在安装了 Windows Update Services Beta 1 或 Beta 2 的服务器上安装 Windows Server Update Services，则首先必须使用控制面板中的“添加或删除程序”卸载早期版本。

#### 问题 6：WSUS 要求在 SQL Server 中启用嵌套触发器选项

默认情况下，此选项是启用的；但是，可以由 SQL Server 管理员禁用。

如果您计划使用 SQL Server 数据库作为 Windows Server Update Services 数据存储，则在 WSUS 管理员安装 WSUS 并在安装期间指定数据库之前，SQL Server 管理员应该验证是否已启用服务器上的嵌套触发器选项。

WSUS 安装程序启用 RECURSIVE\_TRIGGERS 选项，这是数据库特定的选项；但是，它不会启用嵌套触发器选项，此为服务器全局选项。

要查看是否已启用嵌套触发器选项，请使用下列内容：

**sp\_configure 'nested triggers'**

要在 SQL Server 中启用嵌套触发器选项，请在运行 SQL Server 的计算机上的批文件中运行下列内容：

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

#### 问题 7：WSUS 安装程序命令行参数

您可以执行无人参与的 WSUS 安装。有关命令行参数的详细信息，请参阅[部署 Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777) 中的“附录 A：无人参与安装”。

已知问题
--------

#### 问题 1：IIS 锁定向导

如果您在运行 Windows 2000 Server 的计算机上运行 Internet Information Services (IIS)，请从 Microsoft TechNet 上的“IIS 锁定工具”页面中安装 IIS 锁定向导的最新版本（包括 URLScan）。Microsoft 强烈建议您安装此工具，以帮助确保您的 IIS 服务器的安全。IIS 锁定向导的工作原理是禁用 IIS 中不必要的功能，从而降低安全风险。

| ![](images/Cc720505.note(WS.10).gif)注意                                                                 |
|---------------------------------------------------------------------------------------------------------------------------------------|
| WSUS 安装程序不安装这些组件。您必须手动安装这些组件。您不需要在运行 Windows Server 2003 的计算机上安装 IIS 锁定，因为此功能是内置的。 |

#### 问题 2：不支持直接在数据库中更改 WSUS 配置

Windows Server Update Services 在数据库（MSDE 或 SQL Server）中存储其配置数据。但是，不支持通过直接访问数据库更改配置数据。管理员不得以此方式尝试修改 WSUS 配置。支持的更改 WSUS 配置的方式是使用 WSUS 控制台或调用 WSUS API。

#### 问题 3：为了访问 WSUS 管理网站，必须启用活动脚本

在管理员的工作站上，您必须配置 Internet Explorer，以便在您使用 Internet Explorer 访问 WSUS 管理网站之前允许启用活动脚本。

#### 问题 4：在 WSUS 安装期间，必须重新启动 IIS

Windows Server Update Services 安装程序将重新启动 IIS，而不发出通知。这可能影响您组织中现有的网站。

#### 问题 5：更改 WSUS 或 SMS 管理点 (MP) 虚拟目录访问

默认情况下，Windows Server Update Services 的内容虚拟目录是通过匿名访问设置的。如果您将此设置更改为需要身份验证，客户端将接收到身份验证错误，并被拒绝访问以下载更新。这是一个已知问题，当需要进行隐式身份验证时，Winhttp.dll 会使用错误的身份验证上下文，因此身份验证质询将失败。要避免此问题，请确保 WSUS 服务器和 SMS MP 是通过匿名访问 IIS 虚拟目录进行设置的。

#### 问题 6：在 Windows Small Business Server 2003 上安装 WSUS 时，必须修改默认网站 WSUS 虚拟根目录的访问设置，以便使 WSUS 客户端能够从服务器自行更新

WSUS 服务器安装两个虚拟根（SelfUpdate 和 ClientWebService）以及默认网站（端口 80 上）主目录下的一些文件。这使客户端能够通过默认网站自行更新。默认情况下，在 Windows Small Business Server 2003 上，默认网站配置为拒绝访问非服务器上的任何 IP 或 localhost。这意味着 SelfUpdate 和 ClientWebService 虚拟根被拒绝访问，客户端无法自行更新。要向客户端授予自行更新的访问权限，请在默认网站的 SelfUpdate 和 ClientWebService 虚拟根上完成下列步骤。

1.  单击虚拟根“属性”，单击“目录安全性”，单击“IP 地址和域名限制”，然后单击“编辑”。
2.  选择“授权访问”，然后单击“确定”。关闭所有属性页。

#### 问题 7：在 Small Business Server 上安装 WSUS - 集成问题

-   如果 Windows Small Business Server 2003 使用 ISA 代理服务器访问 Internet，则必须在“设置”用户界面中手动输入下列内容：代理服务器设置、代理服务器名称和端口。
-   如果 ISA 使用 Windows 身份验证，则应按照“DOMAIN\\user”（属于“Internet 用户”组的用户）格式输入代理服务器凭据。

#### 问题 8：将某台计算机从一个计算机组移动到另一个计算机组，并且从管理控制台查看时，此计算机可能需要多达一小时才会出现在新组中

首次将某台计算机分配到目标组时，会使用组信息修改计算机上的数据。该数据会定期或每隔一个小时被刷新。因此，当将某台计算机从一个计算机组移动到另一个计算机组时，在客户端上刷新该信息并根据 WSUS 管理控制台中的更改显示可能需要多达一小时。

#### 问题 9：如果您在成员服务器上安装了 WSUS，随后想要将成员服务器提升为域控制器，则应该首先卸载 WSUS

如果您在成员服务器上安装了 WSUS，随后想要将成员服务器提升为域控制器，则需要执行下列步骤：

1.  卸载 WSUS。
2.  将服务器提升为域控制器。
3.  重新安装 WSUS。

#### 问题 10：如果您想要将 WSUS 服务器从域控制器降级为成员服务器，则应首先卸载 WSUS

如果您在域控制器上运行 WSUS 服务器，并且想要将域控制器降级为成员服务器，则需要完成下列步骤：

1.  卸载 WSUS，并保留数据库。
2.  创建名为 ASPNET 的用户帐户。
3.  在命令提示符处，键入 **aspnet\_regiis -i**。
4.  重新安装 WSUS，并使用保留的数据库。

#### 问题 11：如果在安装 WSUS 之后安装了 .NET Framework 1.0 或 2.0，则 WSUS 管理控制台将不会出现

这是由于下列情况引起的：.NET Framework 1.0 是使用 IIS 注册的，并且 WSUS 服务器需要.NET Framework 1.1。要解决此问题，请打开 aspnet\_regiis.exe，并运行下列命令，其中*网站 ID* 是指下列注册表项中包含的值：

HKLM\\Software\\Microsoft\\WindowsUpdateServices\\Server\\Setup\\IISTargetWebsiteIndex

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*网站 ID*&gt;\\ROOT\\ReportingWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*网站 ID*&gt;\\ROOT\\ClientWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*网站 ID*&gt;\\ROOT\\SimpleAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*网站 ID*&gt;\\ROOT\\WSUSAdmin
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*网站 ID*&gt;\\ROOT\\AdministrationWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*网站 ID*&gt;\\ROOT\\ServrSyncWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*网站 ID*&gt;\\ROOT\\DssAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*网站 ID*&gt;\\ROOT\\Content

#### 问题 12：远程 SQL 限制

WSUS 为在独立于带有其他 WSUS 应用程序的计算机的其他计算机上运行数据库软件提供了限制支持。

-   您不能将 Windows 2000 Server 用作远程 SQL 对中的前端计算机。
-   您不能将配置为域控制器的服务器用于远程 SQL 对的前端或后端。
-   您不能将 WMSDE 或 MSDE 用于后端计算机上的数据库软件。
-   如果已在远程服务器上安装终端服务，并且它正在应用程序模式下运行，则远程 SQL Server（以用作 WSUS 数据库）的安装程序将会失败。当在终端服务服务器上安装 SQL Server 时，您必须执行下列操作：
    1.  在运行安装程序之前，请打开命令提示符并键入：**change user /install**
    2.  运行 SQL Server 安装程序。
    3.  运行安装程序之后，在命令提示符处键入：**change user /execute**
-   要设置远程 SQL Server WSUS 数据库，您必须是前端和后端计算机上本地管理员安全组的成员。
-   有关远程 SQL 问题的详细信息，请参阅[部署 Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777) 中的“附录 C：远程 SQL”。

#### 问题 13：副本下游服务器的批准可能比父级上游服务器少

副本下游服务器的批准可能比父级上游服务器少。这是因为只有当内容在上游服务器上完成下载之后，安装批准才会流向下游服务器。

#### 问题 14：如果同步失败，则重试同步

如果同步失败，您可能收到错误消息。如果出现这种情况，您应首先尝试同步。

#### 问题 15：尝试访问 WSUS 管理控制台时，可能出现错误消息 System.IO.FileNotFoundException

如果您收到下列错误消息，则可能需要调整网络服务或 ASP.NET 帐户的权限：

System.IO.FileNotFoundException：找不到文件或程序集名称 *xxxxxx*.dll，或其依赖关系之一

其中 *xxxx* 是随机名称。

要解决 Windows Server 2003 操作系统中的此问题，请授予网络服务帐户对 %systemroot%\\Temp 的读/写访问权限。在 Windows 2000 Server 中，授予 ASP.NET 帐户对 %systemroot%\\Temp 的读/写访问权限。

#### 问题 16：SQL 安全更新 MS03-031 (KB815495)

此更新可能显示为已安装在 WSUS 服务器上，即使安装实际在客户端上已失败。这可能导致将包重新提供给客户端。您可以通过取消对服务器上更新的批准来解决此问题。

#### 问题 17：IIS 设置在 RTM 升级期间丢失。

如果您在安装了 WSUS 的以前版本的服务器（如 RC）上安装 WSUS RTM，则 WSUS RTM 将卸载早期版本，然后安装新的版本。这意味着将删除 IIS 中与 WSUS 相关联的虚拟根和文件。

如果在默认网站上安装了 WSUS，则您将丢失对 WSUS 虚拟根所做的任何 WSUS 相关设置。例如，如果您已为 SSL 配置了 WSUS 虚拟根，为确保 WSUS 的安全，您需要在安装 RTM 版本的 WSUS 后再次配置它们。注意：您将在 WSUS 控制台上收到关于未启用 SSL 的通知。

如果您已在非默认网站上安装了 WSUS，则 WSUS 网站级别的所有附加设置均将丢失。

#### 问题 18：使用主机头

如果您想要将主机头值分配到 IIS 中的默认网站（WSUS 网站），则需要添加“全部未分配”或已分配的 IP 地址到 IP 地址列表，而无需将主机头值分配到默认网站。这也应添加到非默认网站

**警告**：这可能破坏 Windows® SharePoint® Services 和 Exchange 功能。

#### 问题 19：需要将 WSUS 控制台 URL 添加到启用了 Internet Explorer 强化的计算机上的“受信任的站点”和“本地 Intranet”Web 内容区域的列表中

如果您已在计算机上启用了 Internet Explorer 强化（也称为 Microsoft Windows Server 2003 Internet Explorer 增强的安全配置组件），并且未将 WSUS 控制台添加到“受信任的站点”和“本地 Intranet”Web 内容区域，则每当您在 WSUS 控制台中打开页面时，系统会提示您提供用户凭据。

将 WSUS 控制台添加到“本地 Intranet”和“受信任的站点”Web 内容区域：

1.  打开“Internet 选项”（例如，单击“开始”，指向“控制面板”，然后单击“Internet 选项”）。
2.  在“安全”选项卡上，依次单击“本地 Intranet”、“站点”、“高级”，添加 URL (http://*WSUS 服务器名称*/WSUSAdmin)，然后单击“确定”。
3.  单击“受信任的站点”，单击“站点”，添加 WSUS 控制台 URL，单击“确定”，然后再次单击“确定”以退出“Internet 选项”。

#### 问题 20：从 WSUS 候选发布版本升级失败

由于自行更新树问题，从 WSUS 候选发布版本升级可能失败。如果您在尝试升级时多个客户端自行更新，则可能出现这种情况。

解决此问题：

1.  使 WSUS 服务器与网络断开连接，并确保客户端不能连接到网络。
2.  在命令提示符处，键入：**iisrestart /reset**，然后按 Enter。
3.  运行升级。

#### 问题 21：SUS 1.0 中的某些批准无法迁移到 WSUS。

从 SUS 1.0 迁移到 WSUS 时，SUS 1.0 服务器上的某些批准无法迁移到 WSUS 服务器。这是因为可用于 SUS 1.0 的许多更新不再可用于 WSUS。此外，因为 WSUS 支持的更新比 SUS 多，在迁移过程完成后，WSUS 服务器上可能存在未批准的重要更新。

Microsoft 强烈建议您在从 SUS 1.0 迁移后，查看 WSUS 服务器上未批准的更新集。

有关从 SUS 1.0 迁移到 WSUS 的详细信息，请参阅[从 Software Update Services 迁移到 Windows Server Update Services 的分步指南](http://go.microsoft.com/fwlink/?linkid=48042) (http://go.microsoft.com/fwlink/?LinkId=48042)（页面可能为英文）。

#### 问题 22：如果您已从 WMSDE 迁移到 SQL Server，请在升级到 WSUS 2.0 Service Pack 1 之前修正此注册表项

如果您计划将 WSUS 2.0 升级到 Service Pack 1，并且已将 WMSDE 安装迁移到 SQL Server（不管是远程还是本地），请确保更改下列注册表项：

HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled

该值应从 1 更改为 0。

#### 问题 23：从远程 SQL 安装迁移到 WSUS 2.0 Service Pack 1

使用远程 SQL 配置迁移到 WSUS 2.0 Service Pack 1 时，请执行下列步骤：

1) 在前端上不带开关运行安装程序包并选择升级

2) 在后端上不带开关运行安装程序包并选择升级。

#### 版权

本文档包含的信息代表 Microsoft Corporation 截至发布日期就所讨论的问题发表的最新观点。由于 Microsoft 必须对不断变化的市场状况作出反应，因此这些观点不应被解释为 Microsoft 的承诺，并且 Microsoft 不保证所示任何信息在发布日期之后仍准确。

本文档仅供参考。Microsoft 不对本文档中的信息作出任何明示、暗示或法律的保证。

遵守所有适用的著作权法是用户的责任。在不限制著作权所辖权利的前提下，未经 Microsoft Corporation 的明确书面许可，本文档的任何部分不得被复制、存储或引进检索系统，或者以任何形式、任何方式（电子、机械、复制、录音等）或为任何目的进行传播。

Microsoft 可能具有涉及本文档中主题的专利、专利申请、商标、版权或其他知识产权。除非 Microsoft 的书面许可协议明确规定，否则提供本文档并不意味着赋予您这些专利、商标、版权或其他知识产权的任何许可。

除非另行说明，否则本文档示例中涉及的公司、组织、产品、域名、电子邮件地址、徽标、人物、地点和事件均属虚构，与任何真实的公司、组织、产品、域名、电子邮件地址、徽标、人物、地点或事件无关，也不应进行这方面的推断。

© 2005 Microsoft Corporation。保留所有权利。

Microsoft、SQL Server、Windows 和 Windows Server 均为 Microsoft Corporation 在美国和/或其他国家或地区的注册商标或商标。

本文档所提及的真实公司和产品名称可能是其各自所有者的商标。
