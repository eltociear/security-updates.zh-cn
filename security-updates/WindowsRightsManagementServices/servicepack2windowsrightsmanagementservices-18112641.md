---
TOCTitle: 带有 Service Pack 2 的 Windows Rights Management Services 的发行说明
Title: 带有 Service Pack 2 的 Windows Rights Management Services 的发行说明
ms:assetid: '78067886-681f-49a6-b43d-bfd08a369b69'
ms:contentKeyID: 18112641
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc747637(v=WS.10)'
---

带有 Service Pack 2 的 Windows Rights Management Services 的发行说明
====================================================================

*发布日期：2006 年 12 月*

开始之前
--------

在安装 Microsoft® Windows® Rights Management Services (RMS) Service Pack 2 (SP2) 之前，请查看下列信息。这些发行说明中包含的信息适用于 RMS SP2 服务器，而不适用于 RMS 客户端。有关 RMS 客户端的信息，请参阅“Rights Management Services”([http://go.microsoft.com/fwlink/?LinkId=68637](http://go.microsoft.com/fwlink/?linkid=68637))（页面可能为英文）。

#### 系统要求

下表列出了运行 RMS SP2 的硬件要求。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >要求</th>
<th style="border:1px solid black;" >建议</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">具有一个 Pentium III 处理器（800 MHz 或更高）的计算机</td>
<td style="border:1px solid black;">具有两个 Pentium 4 处理器（1500 MHz 或更高）的计算机</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">256 MB RAM</td>
<td style="border:1px solid black;">512 MB RAM</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">20 GB 可用硬盘空间</td>
<td style="border:1px solid black;">40 GB 可用硬盘空间</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747637.note(WS.10).gif)注意                |  
|--------------------------------------------------------------------------------------|  
| RMS SP2 服务器设计用于 32 位计算机。如果安装在 64 位计算机上，则将在仿真模式下运行。 |
  
下表列出了运行 RMS SP2 的服务器的软件要求。
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >组件</th>
<th style="border:1px solid black;" >要求</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">操作系统</td>
<td style="border:1px solid black;">Microsoft Windows Server® 2003，RMS SP2 的 Web Edition 除外。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Rights Management Services SP2</td>
<td style="border:1px solid black;">必须安装 RMS Service Pack 1 (SP1) 才能升级到 RMS SP2。RMS SP2 客户端没有此项要求。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">文件系统</td>
<td style="border:1px solid black;">建议使用 NTFS 文件系统。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">必备组件</td>
<td style="border:1px solid black;"><ul>
<li>消息队列（也称为 MSMQ），并启用 Active Directory® 目录服务集成。<br />
<br />
</li>
<li>Internet Information Services (IIS)，并启用 ASP.NET。<br />
<br />
</li>
<li>Microsoft .NET Framework 1.1<br />
<br />
</li>
</ul></td>
</tr>
</tbody>
</table>
 

| ![](images/Cc747637.note(WS.10).gif)注意                                             |
|-------------------------------------------------------------------------------------------------------------------|
| 如果 RMS SP2 配置为允许进行远程管理，则连接到 RMS SP2 管理服务的计算机必须使用 Internet Explorer 6.0 或更高版本。 |

下表列出了运行 RMS SP2 版的服务器的基础结构要求。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >组件</th>
<th style="border:1px solid black;" >要求</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">目录服务</td>
<td style="border:1px solid black;">运行 Windows Server 2000 Service Pack 3 (SP3) 或更高版本的域控制器上的 Active Directory，其所在域与安装 RMS 的域相同。使用 RMS 获取许可证和发布内容的所有用户和组都必须拥有在 Active Directory 中配置的电子邮件地址。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">数据库服务器</td>
<td style="border:1px solid black;">RMS SP2 需要数据库和存储过程才能执行操作。您可以使用 Microsoft SQL Server™ 2000 SP3a 或更高版本，或者 Microsoft SQL Server 2005。对于测试或其他单机部署，可以使用 Microsoft SQL Server Desktop Engine (MSDE 2000) Release A 或 Microsoft SQL Server 2005 Express Edition。</td>
</tr>
</tbody>
</table>
  
RMS 设计用于运行 Microsoft SQL Server 2000 和 Microsoft SQL Server 2005 的数据库服务器，并且经过测试。如果它们符合下列条件，则 RMS 可以在其他数据库服务器上运行：
  
-   支持 Microsoft .NET Framework 1.1 提供的 ADO.NET 接口。  
-   由于 RMS 初始化脚本和 RMS 存储过程使用 Transact-SQL，因此与 Microsoft SQL Server 使用的结构化查询语言 Transact-SQL 兼容。  
-   支持 Microsoft SQL Server 的所有特定扩展。  
-   响应 .NET Framework 的 System.Data.SqlClient 命名空间的方法调用。  
-   提供 System.Data.SqlClient 命名空间的相应功能。  
-   使用 Windows 身份验证模式。
  
要查明数据库服务器是否支持上述条件，请联系相关的数据库供应商。
  
下表列出了使用 RMS 执行不同活动时所需的用户权限。
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >活动</th>
<th style="border:1px solid black;" >帐户要求</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">安装 RMS</td>
<td style="border:1px solid black;">具有本地计算机管理员凭据的域用户</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">设置 RMS 根群集</td>
<td style="border:1px solid black;">具有本地计算机管理员凭据以及 Active Directory 查找和写入权限的域用户</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">设置 RMS 仅授权群集</td>
<td style="border:1px solid black;">具有本地计算机管理员凭据和 Active Directory 查找权限的域用户</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">使用新的配置数据库进行设置</td>
<td style="border:1px solid black;">具有本地计算机管理员凭据并且对运行 SQL Server 的计算机具有读取、写入和创建权限的域用户</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">使用现有的配置数据库进行设置</td>
<td style="border:1px solid black;">具有本地计算机管理员凭据并且对运行数据库服务器的计算机具有读取和写入权限的域用户</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">管理 RMS</td>
<td style="border:1px solid black;">具有本地计算机管理员凭据的域用户</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747637.note(WS.10).gif)注意                                                                                                                                                                    |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 有关 Windows Server 配置、Active Directory、消息队列、IIS 和文件系统的详细信息，请参阅 Windows Server 2003 TechCenter ([http://go.microsoft.com/fwlink/?LinkId=78135](http://go.microsoft.com/fwlink/?linkid=78135))（页面可能为英文）。 |
  
如果在群集部署中使用 RMS，请确保已解决下表中列出的项目。
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >条件</th>
<th style="border:1px solid black;" >建议</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">使用 RMS 的台式机过多</td>
<td style="border:1px solid black;">使用 Systems Management Server (SMS) 或组策略来安装 RMS SP2 客户端。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">具有大量客户端请求</td>
<td style="border:1px solid black;">使用负载平衡服务器、Windows Server 操作系统中的网络负载平衡服务或硬件负载平衡功能来在群集之间分发请求。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">有两个网络适配器使用虚拟 IP 寻址为 Extranet 和 Intranet 请求提供服务</td>
<td style="border:1px solid black;">确保向 Extranet 公开虚拟 IP 地址的任何域名系统 (DNS) 注册也同时向 Intranet 公开此地址。</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747637.Important(WS.10).gif)要点                                                                                                                                                                                                          |  
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 如果没有为 Intranet 进行 DNS 注册，则内部客户端许可证请求将失败。如果无法修改 DNS 设置，则可以对群集中每台服务器的主机表进行修改，以便将群集的 URL 映射到该群集的虚拟 IP 地址。需要在设置 RMS 之前完成 DNS 注册。如果已经设置了该服务，您必须从服务器中删除 RMS，然后重复设置过程。 |
  
#### 此版本支持的客户端
  
没有 Service Pack 的 RMS 客户端、RMS SP1 客户端或 RMS SP2 客户端可以在运行 Microsoft Windows 2000、Windows XP 和 Windows Server 2003 的任何计算机上安装。此版本不支持 Windows 操作系统的早期版本。
  
| ![](images/Cc747637.Caution(WS.10).gif)警告                             |  
|------------------------------------------------------------------------------------------------------|  
| 如果您使用没有 Service Pack 的 RMS 客户端，则客户端不能针对 RMS SP1 或更高版本的服务器使用联机发布。 |
  
功能更改  
--------
  
RMS SP2 中有许多新功能：
  
-   [增强的跨林组扩展](#bkmk_cif1)  
-   [数据库日志记录更改](#bkmk_cif2)  
-   [更大的服务器批处理大小](#bkmk_cif3)  
-   [与 Microsoft SQL Server 2005 兼容](#bkmk_cif4)
  
<span id="BKMK_CIF1"></span>
#### 增强的跨林组扩展
  
#### 此功能有何用途？
  
在 RMS 中，跨林组扩展使 RMS 能够在不同的林（两个林之间没有重复的组成员身份）中扩展 Active Directory 通用组成员身份。当一个林中的用户向其他林中的用户发送受权限保护的内容时，RMS 会完成一个发现期，验证用户是否有权限访问内容。此验证过程通过从一个林到其他林使用 LDAP 查询来完成，以找到远程林的 RMS 服务连接点 (SCP)。发现远程林的 SCP 后，RMS 服务帐户向组扩展管道发送一个请求。此请求会询问远程林此用户是否为某个组的成员。
  
#### 此功能适用于哪些对象？
  
位于多林 Active Directory 环境（林之间不复制通用组成员身份）中的 RMS 客户将对此新功能感兴趣。
  
#### 为什么此更改很重要？
  
对于部署多林 Active Directory 环境的客户而言，新的林信任扩展协议将提高可靠性。
  
#### 工作方式有何不同？
  
在 RMS SP2 之前，跨林组扩展使用 .NET 远程调用来实现。在此版本中，跨林组扩展协议已更改为 ASP.NET Web 服务，向林信任组扩展管道发送 SOAP/HTTP 请求。
  
| ![](images/Cc747637.note(WS.10).gif)注意                                                     |  
|---------------------------------------------------------------------------------------------------------------------------|  
| 对于后向兼容性，RMS SP2 仍然支持 .NET 远程调用。但是，为了充分利用新的跨林组扩展协议，所有 RMS 群集必须至少运行 RMS SP2。 |
  
#### RMS SP2 增加或更改了哪些设置？
  
在 RMS SP2 中，新的 RMS 组扩展管道默认配置为最安全的设置，仅本地 RMS 服务和管理员组具有访问权限。要授予某个帐户访问权限，您应该更改组扩展管道（位于 wwwroot\\\_wmcs\\GroupExpansion\\GroupExpansion.asmx）上的访问控制列表。
  
| ![](images/Cc747637.Important(WS.10).gif)要点                                                                                                                                                                                 |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 确保验证每个 Active Directory 林中的 RMS 服务帐户是否均可以访问群集中各个 RMS 服务器上的组扩展管道。如果帐户不具有访问权限，则组扩展将会失败。或者，您可以在每个林中创建同一帐户，并为每个帐户分配相同的密码。在这种情况下，只能向组扩展管道添加一个帐户。 |
  
添加到 RMS SP2 的新事件将通知您没有提交到消息队列服务的错误消息。这些新的事件日志包括在消息无法进行数字签名或者消息无法进行验证时向您发送通知的事件。验证问题的一些示例包括格式不正确消息、缺少哈希或签名，或者不正确的哈希或签名。
  
<span id="BKMK_CIF2"></span>
#### 数据库日志记录更改
  
#### 此功能有何用途？
  
RMS 使用日志记录侦听程序服务，该服务通过使用消息队列将所有 RMS 通信发送到日志记录数据库。RMS 群集将消息提交到消息队列服务，日志记录侦听程序服务从“消息队列”队列中检索这些消息，并将其写入日志记录数据库。
  
#### 此功能适用于哪些对象？
  
此功能适用于使用 RMS 日志侦听程序服务的当前用户，以及考虑使用日志侦听程序服务的 RMS SP2 新用户。
  
#### 为什么此更改很重要？
  
在 RMS 的以前版本中，RMS 日志记录队列使用访问控制列表来进行保护，但是没有启用身份验证。如果不使用身份验证，恶意用户可以潜在地将错误的消息写入 RMS 日志记录队列。
  
#### 工作方式有何不同？
  
在 RMS SP2 中，通过使用消息队列在 RMS 群集传输的消息上提供了附加的身份验证。除了可防止未经授权访问消息队列的访问控制列表之外，“消息队列”队列还使用消息真实性验证机制来进行保护。当消息发送到消息队列服务时，RMS 管道通过使用 RMS 群集的私钥来生成消息的哈希，并对其进行数字签名。日志记录侦听程序服务首先计算其自身的消息哈希，并将其与消息附带的哈希进行比较。如果哈希匹配，则日志记录侦听程序服务会使用群集的公钥和消息中的哈希验证签名。如果哈希匹配，并且签名通过了验证，则消息会被发送到日志记录数据库。如果验证步骤没有成功，则从“消息队列”队列中永久地删除该消息，并且在事件查看器的应用程序日志中写入一个事件警告。
  
#### RMS SP2 增加或更改了哪些设置？
  
添加到 RMS SP2 的新事件旨在指明何时问题消息没有提交到“消息队列”队列。这些新事件被写入到应用程序日志，并且包括无法进行数字签署的消息或者无法验证消息上的数字签名。验证问题的一些示例包括格式不正确消息、缺少哈希或签名，或者不正确的哈希或签名。
  
<span id="BKMK_CIF3"></span>
#### 更大的服务器批处理大小
  
#### 此功能有何用途？
  
相对于为每个许可证发出单独的请求，RMS 中的批处理通过允许将多个许可证请求作为单个请求发送到 RMS 群集来提高性能。
  
#### 此功能适用于哪些对象？
  
启用了 RMS 并且 需要针对受权限保护的内容一次性获取多个许可证的应用程序会对支持更大的服务器批处理大小这一功能感兴趣。
  
#### 为什么此更改很重要？
  
RMS 批处理允许向 AcquireLicense RMS 管道发出单个请求，以便根据一个或多个发布许可证获取多个权限帐户证书 (RAC) 的用户许可证。如果批处理大小不大于 1，则启用了 RMS 的应用程序必须为每个用户单独请求用户许可证。
  
#### 工作方式有何不同？
  
在早于 RMS SP2 的 RMS 版本中，RMS 群集支持的最大批处理大小为 1。如果最大大小设置为大于 1 的数，则群集将忽略它。对于 RMS SP2，最大批处理大小可以高达 100。
  
| ![](images/Cc747637.note(WS.10).gif)注意 |  
|-----------------------------------------------------------------------|  
| 仅 AcquireLicense RMS 管道包括对批处理请求的支持。                    |
  
在 RMS SP2 中，错误报告已得到增强，将批处理请求考虑在内。例如，如果您发送一批 10 个请求，且第二个和第三个请求失败，则将针对每个失败在事件日志中写入一个事件。
  
<span id="BKMK_CIF4"></span>
#### 与 Microsoft SQL Server 2005 兼容
  
#### 此功能有何用途？
  
在 RMS SP2中，Microsoft SQL Server 2005 可以用作一个数据库服务器来支持 RMS 配置和日志记录数据库，而不需要执行任何其他配置。
  
#### 此功能适用于哪些对象？
  
想要使用 Microsoft SQL Server 2005 作为其 RMS 数据库的 RMS 客户会对支持 Microsoft SQL Server 2005 这一功能感兴趣。
  
#### 为什么此更改很重要？
  
在 RMS 的早期版本中，sysmessages 表中使用的一些参数的数据类型与 Microsoft SQL Server 2005 格式规范不兼容。有关详细信息，请参阅 Microsoft 知识库文章 913372 ([http://go.microsoft.com/fwlink/?LinkId=68638](http://go.microsoft.com/fwlink/?linkid=68638))（页面可能为英文）。
  
#### 工作方式有何不同？
  
在早于 RMS SP2 的 RMS 版本中，使用 SQL RAISERROR 语句来通知 RMS 用户出现错误。RAISERROR 语句查询 sysmessages 表，以检索此表中存储的 RMS 错误消息。RMS SP2 使用不同的技术来传播 SQL 错误，因此不再依靠 sysmessages 表。
  
| ![](images/Cc747637.note(WS.10).gif)注意                                                                                                    |  
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 如果将 RMS SP1 升级到 RMS SP2，则 sysmessages 表将不再查询错误消息，但是错误消息本身将保留在 sysmessages 表中。RMS SP2 全新安装将不会在 sysmessages 表中添加任何新条目。 |
  
已知问题  
--------
  
下列各节讨论了此 RMS 版本的已知问题。
  
#### 帮助文件仍引用 RMS Service Pack 1
  
RMS SP2 安装中包括的帮助文件仍然引用 RMS SP1。有关 RMS SP2 的详细信息，请参阅“Rights Management Services”([http://go.microsoft.com/fwlink/?LinkId=68637](http://go.microsoft.com/fwlink/?linkid=68637))（页面可能为英文）。
  
#### Windows Update 无法在基于 x64 或基于 Itanium 的计算机上安装 RMS SP2 客户端
  
如果将 RMS 客户端或 RMS SP1 客户端安装在基于 x64 的计算机上，并且尝试从 Windows Update 将客户端升级到 RMS SP2 客户端 (x64)，则安装将失败。尽管以前的 RMS 客户端（为 32 位系统创建的）在基于 x64 的计算机上工作，但是无法将它们升级到 RMS SP2 客户端 (x64)。您需要首先卸载以前的 RMS 客户端，然后再次启动更新。Windows Update 会检测操作系统的版本，并且提供合适的 RMS SP2 客户端。对于基于 Itanium 的计算机，原理相同。
  
#### 重新设置始终无法启动日志记录侦听程序服务
  
当取消设置群集时，日志记录侦听程序服务无法让服务处于“已停止”状态。为了完全停止服务，您必须重新启动计算机。
  
#### 不能删除基于非软件的可信发布域
  
在使用基于非软件的私钥实现导入可信发布域后，不可能删除它。不应该从 Windows Rights Management Services 管理控制台导入基于非软件的私钥。有关如何导出和导入私钥的说明，请联系合适的硬件提供商。
  
#### Microsoft .NET Framework 2.0 安装在 RMS 服务器上会更改 IIS 虚拟根
  
RMS SP2 使用 .NET Framework 1.1 版本附带提供的 ASP.NET 脚本映射。由更高版本提供的映射与 RMS SP2 不兼容。但是，两种版本可以共存，而不会影响其他相关应用程序。如果您的服务器安装了 .NET Framework 1.1 和 .NET Framework 2.0 或更高版本，则在 RMS SP2 的安装和设置显示为已经成功完成之后，RMS 群集可能无法正常工作。原因是 RMS 虚拟根需要使用 ASP.NET 脚本映射 1.1 版而不是 2.0 版本注册。要使用 ASP.NET 脚本映射 1.1 版注册 RMS 虚拟根，请在命令提示符处运行下列命令：
  
**%windir%\\Microsoft.NET\\Framework\\v1.1.4322&gt;aspnet\_regiis.exe -s W3SVC/1/ROOT/\_wmcs**
  
运行此命令将正确地注册 RMS 虚拟根，并使 RMS SP2 能够在服务器上运行。
  
#### 如果使用 Active Directory Windows 2000 本机功能级别，则组成员身份可能丢失
  
在 Active Directory 基础结构级别已经被提升到 Windows 2000 本机功能级别的环境中部署 RMS 后，当尝试扩展已经隐藏的通讯组列表的组成员身份时，RMS 可能无法读取 Active Directory 对象的 memberOf 属性。要允许 RMS 读取 memberOf 属性，RMS 服务帐户必须使用属于 Pre-Windows 2000 Compatible Access 组的成员的域帐户。有关详细信息，请参阅 Microsoft 知识库文章 812841 ([http://go.microsoft.com/fwlink/?LinkId=78152](http://go.microsoft.com/fwlink/?linkid=78152))（页面可能为英文）。
  
#### 当数据库不可访问时，日志记录侦听程序服务会向死信队列发送消息队列消息。
  
存在一些日志记录侦听程序服务无法访问数据库的实例（例如，数据库关闭、网络连接问题等等）。在这种情况下，消息将被发送到死信队列。恢复这些消息（即，将其发送到日志记录数据库）的唯一方法是使用 RMS 管理工具包提供的 RMS 队列恢复工具。要下载 RMS 管理工具包，请参阅 [http://go.microsoft.com/fwlink/?LinkId=33841](http://go.microsoft.com/fwlink/?linkid=33841)（页面可能为英文）。
  
| ![](images/Cc747637.note(WS.10).gif)注意                                                                               |  
|-----------------------------------------------------------------------------------------------------------------------------------------------------|  
| 已从 LogRecoveryCmd 中删除了 Recover 和 RecoverandPurge。这将确保所有消息通过消息队列服务路由回来，并且在消息发送到日志记录数据库之前进行身份验证。 |
  
#### 必须在升级 Microsoft SQL Server 2005 之前升级 RMS SP2
  
在升级 RMS SP2 以及将 Microsoft SQL Server 2000 升级到 Microsoft SQL Server 2005 时，请确保首先升级 RMS。这将避免 Microsoft SQL Server 升级带来的任何兼容性问题。
  
#### RMS SP2 无法在其名称包括撇号 (') 的网站上设置
  
如果试图在其名称包括撇号 (') 的网站上设置 RMS SP2，则设置过程将失败，并且出现“参数无效”错误消息。要在网站上设置 RMS SP2，请从此网站的名称中删除撇号。
  
#### 在运行 Windows Server 2003 的 64 位版本的服务器上启用 ASP.NET V1.1
  
RMS 帮助中的“系统要求”主题阐述了安装 Internet Information Services (IIS) 之后如何安装 .NET Framework 1.1 和启用 ASP.NET 1.1。但是，如果在安装 IIS 之前已经安装了 .NET Framework 1.1，则 ASP.NET 1.1 不会在 Web 服务扩展中列出，因此所述过程将不适用。如果在安装 .NET Framework 1.1 之后安装 IIS，则在命令提示符处运行下列命令以启用 ASP.NET：
  
**%SystemRoot%\\Microsoft.NET\\Framework\\v1.1.4322\\aspnet\_regiis.exe -i –enable**
  
如果安装了版本高于 1.1 的任何 .NET Framework ，则在此命令中使用 **-ir** 替换 **-i** 以避免重置任何现有的 IIS 脚本映射。
  
#### 必须将远程林 RMS 服务帐户添加到本地组扩展管道
  
从组扩展管道上的 ACL 中删除 BUILTIN\\users 可以解决安全问题。这可能破坏跨林组扩展方案。要解决此问题，请完成下列步骤：
  
**将 RMS 服务帐户添加到远程林**  
1.  在 Forest1 上，其中 Forest1 是第一个林中的 RMS 根群集，转到 inetpub\\wwwroot\\\_wmcs。
  
2.  右键单击“GroupExpansion”文件夹，然后选择“属性”。
  
3.  在“GroupExpansion 属性”窗口中，单击“安全”选项卡，为 *Forest2\\RmsServiceAccount* 添加条目（例如，rmil31\\rmsvc），其中 Forest2 是第二个林中的 RMS 根群集。
  
4.  单击“确定”。
  
5.  单击“运行”，键入 iisreset，然后单击“确定”。
  
#### 升级 .NET Framework 可能导致数据丢失
  
如果在安装和设置 RMS 之后升级 .NET Framework (CLR)  1.1 版，则将 vroots 设置为使用 .NET Framework 2.0 版。如果发生这种情况，则不会在日志记录数据库中记录任何信息。这将导致数据丢失。请执行下列操作之一：
  
-   在安装和设置 RMS 之前升级 .NET Framework。  
-   在升级 .NET Framework 后重置 vroots 以使用 1.1 版本。
  
本版本中的文档更改  
------------------
  
以下是本版本中更改的主题列表：
  
-   信任基于 Passport 的权限帐户证书 ([http://go.microsoft.com/fwlink/?LinkId=70369](http://go.microsoft.com/fwlink/?linkid=70369))（页面可能为英文）  
-   RMS 的软件要求 ([http://go.microsoft.com/fwlink/?LinkId=70371](http://go.microsoft.com/fwlink/?linkid=70371))（页面可能为英文）  
-   如何部署 RMS 客户端 ([http://go.microsoft.com/fwlink/?LinkId=70373](http://go.microsoft.com/fwlink/?linkid=70373))（页面可能为英文）  
-   从命令提示符窗口安装 RMS ([http://go.microsoft.com/fwlink/?LinkId=70374](http://go.microsoft.com/fwlink/?linkid=70374))（页面可能为英文）  
-   RMS 核心配置数据库表 ([http://go.microsoft.com/fwlink/?LinkId=70375](http://go.microsoft.com/fwlink/?linkid=70375))（页面可能为英文）  
-   RMS 配置数据库认证表 ([http://go.microsoft.com/fwlink/?LinkId=70376](http://go.microsoft.com/fwlink/?linkid=70376))（页面可能为英文）  
-   RMS 日志记录数据库表 ([http://go.microsoft.com/fwlink/?LinkId=70377](http://go.microsoft.com/fwlink/?linkid=70377))（页面可能为英文）  
-   评估等级要求 [http://go.microsoft.com/fwlink/?LinkId=70378](http://go.microsoft.com/fwlink/?linkid=70378))（页面可能为英文）  
-   保证 RMS 部署安全 ([http://go.microsoft.com/fwlink/?LinkId=70379](http://go.microsoft.com/fwlink/?linkid=70379))（页面可能为英文）  
-   启用取消配置服务 ([http://go.microsoft.com/fwlink/?LinkId=70380](http://go.microsoft.com/fwlink/?linkid=70380))（页面可能为英文）  
-   计划外部 RMS 用户 [http://go.microsoft.com/fwlink/?LinkId=70381](http://go.microsoft.com/fwlink/?linkid=70381))（页面可能为英文）  
-   对移动设备和服务器服务启用 RMS 服务器支持 ([http://go.microsoft.com/fwlink/?LinkId=70382](http://go.microsoft.com/fwlink/?linkid=70382))（页面可能为英文）
  
#### 版权
  
*本文档包含的信息代表 Microsoft Corporation 截至发布日期就所讨论的问题发表的最新观点。由于 Microsoft 必须对不断变化的市场状况作出反应，因此这些观点不应被解释为 Microsoft 的承诺，并且 Microsoft 不保证所示任何信息在发布日期之后仍准确。*
  
*本文档仅供参考。Microsoft 不对本文档中的信息作出任何明示、暗示或法律的保证。*
  
*遵守所有适用的著作权法是用户的责任。在不限制著作权所辖权利的前提下，未经 Microsoft Corporation 的明确书面许可，本文档的任何部分不得被复制、存储或引进检索系统，或者以任何形式、任何方式（电子、机械、复制、录音等）或为任何目的进行传播。*
  
*Microsoft 可能具有涉及本文档中主题的专利、专利申请、商标、版权或其他知识产权。除非 Microsoft 的书面许可协议明确规定，否则提供本文档并不意味着赋予您这些专利、商标、版权或其他知识产权的任何许可。*
  
*除非另有说明，否则本文档中作为示例叙述的公司、组织、产品、域名、电子邮件地址、徽标、人员、地点以及事件均为虚构，不与任何真实的公司、组织、产品、域名、电子邮件地址、徽标、人员、地点和事件有联系，也不应作任何此类联系方面的推断。*
  
*© 2006 Microsoft Corporation。保留所有权利。*
  
*Active Directory、Microsoft、MS-DOS、Visual Studio、Windows、Windows Server、SQL Server 和 Windows NT 均为 Microsoft Corporation 在美国和/或其他国家或地区的注册商标或商标。*
  
*本文档所提及的真实公司和产品名称可能是其各自所有者的商标。*
