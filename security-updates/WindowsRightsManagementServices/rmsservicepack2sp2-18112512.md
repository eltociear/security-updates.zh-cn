---
TOCTitle: '使用 RMS Service Pack 2 (SP2) 更新您的部署'
Title: '使用 RMS Service Pack 2 (SP2) 更新您的部署'
ms:assetid: '27ee06a1-f467-4a6c-b662-45ddb5f8c13e'
ms:contentKeyID: 18112512
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc720225(v=WS.10)'
---

使用 RMS Service Pack 2 (SP2) 更新您的部署
==========================================

本节提供的信息可帮助您在组织中使用现有 RMS 部署安装 Microsoft® Windows® Rights Management Services (RMS) Service Pack 2 (SP2)。仅已经部署了 RMS 的组织需要使用 RMS SP2 更新其部署。首次部署 RMS 的组织可以按照此文档集中的“规划 RMS 部署”([http://go.microsoft.com/fwlink/?LinkId=74999](http://go.microsoft.com/fwlink/?linkid=74999))（页面可能为英文）和“部署 RMS 系统”([http://go.microsoft.com/fwlink/?LinkID=75000](http://go.microsoft.com/fwlink/?linkid=75000))（页面可能为英文）中的指导来部署 RMS SP2。

您可以安装 RMS SP2 而不必删除现有的 RMS SP1 安装。RMS SP2 的安装程序会检测到已安装 RMS SP1，并根据需要添加其他功能和设置。

> [!NOTE]   
> 不支持从没有 Service Pack 的 RMS 服务器升级到 RMS SP2。如果您使用的是没有 Service Pack 的 RMS 服务器，则必须先升级到 RMS SP1，然后再升级到 RMS SP2。RMS 客户端可以从 RMS 客户端的任何先前版本进行升级。 

**在此主题中**

-   [准备 RMS SP2 更新](#bkmk_preparingforsp2update)
-   [执行 RMS SP2 更新](#bkmk_performingsp2update)
-   [更新群集](#bkmk_updateclusters)
-   [更新 RMS 客户端](#bkmk_updateclients)
-   [与 RMS 1.0 版的互操作性](#bkmk_interop)
-   [删除 RMS SP2](#bkmk_removingrms)

<span id="bkmk_PreparingForSP2Update"></span>
准备 RMS SP2 更新
-----------------

RMS SP2 更新旨在允许您持续运行 RMS，不会造成中断。但是，在您升级 RMS 群集之前，建议您执行下列操作：

-   备份配置数据库和 RMS 私钥。有关详细信息，请参阅本文档集中的“RMS 的系统备份”([http：//go.microsoft.com/fwlink/?LinkId=75001](http://go.microsoft.com/fwlink/?linkid=75001))（页面可能为英文）。

-   如果您使用的是基于软件的私钥，请确保您拥有 RMS 私钥密码。
-   如果您要保留先前记录的统计信息，请备份记录数据库。
-   确保在您的客户端和服务器上为操作系统安装了最新的关键更新和安全更新。要验证您是否拥有所有关键更新和安全更新，请单击“开始”，单击“Windows Update”，然后按照出现在屏幕上的说明操作。

<span id="bkmk_PerformingSP2Update"></span>
执行 RMS SP2 更新
-----------------

当 Windows Rights Management Services Service Pack 2 安装向导检测到您的 RMS 安装时，它会查看您当前的 RMS SP1 安装，并只添加新文件或替换需要针对 RMS SP2 进行更改的文件。如果您已经成功运行 RMS，则在安装 RMS SP2 后，您不需要重新设置任何其他配置即可继续运行 RMS。

<span id="bkmk_UpdateClusters"></span>
更新群集
--------

如果您已在群集配置中安装了 RMS，则应该计划更新您的群集以降低更新对您的安装的影响。确定如何最佳地在您的组织中实施 RMS SP2 时，请考虑下列建议：

-   最佳方案是，一次性在群集的某个部分上安装 RMS SP2，以便群集的升级可预测性更强，并且在升级期间导致服务降级的可能性最小。

-   如果您有多个 RMS 群集，则应该首先升级根认证群集，然后升级通过注册子过程注册的授权群集。
-   如果您使用跨林组扩展，则可以在林中单独升级群集，而不会影响 RMS 服务器跨林扩展组成员身份的功能。
-   如果 RMS SP2、RMS SP1 和 RMS 1.0 版服务器在不同的 Active Directory 林中，则可以共存并具有互操作性。建议不要在同一群集中安装不同的 RMS 服务器版本。
-   RMS SP2 安装程序包也可以用于在服务器上安装 RMS SP2 的新部署；它不需要安装 RMS SP1。

<span id="bkmk_UpdateClients"></span>
更新 RMS 客户端
---------------

新的 RMS SP2 客户端可以从 Windows Update 或 Microsoft 下载中心下载。RMS SP2 客户端安装程序包也可以用于在计算机上安装 RMS SP2 客户端的新版本；它不需要安装 RMS 1.0 版客户端。RMS SP2 客户端包括后向兼容性功能，使它能够与启用了 RMS 并且需要 RMS 1.0 版的应用程序配合使用。

有关更新和安装 RMS 客户端的详细信息，请参阅“分发 RMS 客户端”([http://go.microsoft.com/fwlink/?LinkId=75070](http://go.microsoft.com/fwlink/?linkid=75070))（页面可能为英文）。

<span id="bkmk_InterOp"></span>
与 RMS 1.0 版的互操作性
-----------------------

由于 RMS SP2 提供了许多改进和性能增强功能，您应该在下一升级周期期间安装它。虽然运行 RMS SP2 的 RMS 服务器和客户端完全可与不运行 RMS SP2 的 RMS 服务器和客户端互操作，但是应了解它们在混合环境中工作方式的差异：

-   仅运行 RMS SP1 及更高版本的服务器能够脱机注册。

-   仅运行 RMS SP1 及更高版本的客户端能够自激活。
-   下表描述了混合环境支持的功能：

###  

 
<p> </p> 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >RMS 服务器版本</th>
<th style="border:1px solid black;" >版本 1 客户端支持的功能</th>
<th style="border:1px solid black;" >SP2 客户端支持的功能</th>
<th style="border:1px solid black;" >在混合客户端环境中支持的功能</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">1.0</td>
<td style="border:1px solid black;">所有以前的功能。
服务器无法进行脱机注册。服务器必须通过 Internet 注册。
客户端无法自激活。</td>
<td style="border:1px solid black;">所有以前的功能。
服务器无法进行脱机注册。
客户端可以自激活。</td>
<td style="border:1px solid black;">所有以前的功能。
对于 SP2 客户端，客户端是自激活的。
对于 版本 1 客户端，客户端必须通过 Internet 激活。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SP2</td>
<td style="border:1px solid black;">所有以前的功能。
服务器可以脱机注册。
客户端无法自激活。</td>
<td style="border:1px solid black;">所有 SP1 功能。
服务器可以脱机注册。
客户端可以自激活。
服务器密码箱。
Microsoft SQL Server™ 2005 支持开箱即用。</td>
<td style="border:1px solid black;">所有以前的功能加上 SP2 功能。
服务器可以脱机注册。
对于 SP2 客户端，客户端是自激活的。
对于 版本 1 客户端，客户端必须通过 Internet 激活。</td>
</tr>
</tbody>
</table>
 

<span id="bkmk_RemovingRMS"></span>
删除 RMS SP2
------------

如果您在安装 RMS SP2 之后想要将 RMS 服务器恢复到其以前的配置，则可以使用控制面板中的“添加或删除程序”来删除 RMS SP2。
