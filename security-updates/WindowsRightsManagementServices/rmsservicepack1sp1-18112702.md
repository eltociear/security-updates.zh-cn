---
TOCTitle: '使用 RMS Service Pack 1 (SP1) 更新您的部署'
Title: '使用 RMS Service Pack 1 (SP1) 更新您的部署'
ms:assetid: 'a562c4b0-15df-46db-9d61-24db74871cfa'
ms:contentKeyID: 18112702
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc747714(v=WS.10)'
---

使用 RMS Service Pack 1 (SP1) 更新您的部署
==========================================

本节提供的信息可帮助您在组织中使用现有 RMS 部署安装 Microsoft® Windows® Rights Management Services (RMS) Service Pack 1 (SP1)。仅已经部署了 RMS 的组织需要使用 RMS SP1 更新其部署。首次部署 RMS 的组织可以按照此文档集中的“规划 RMS 部署”和“部署 RMS 系统”中的指导部署 RMS SP1。

您可以安装 RMS SP1 而不必删除现有的 RMS 安装。RMS SP1 的安装程序会检测到已安装 RMS，并根据需要添加其他功能和设置。

**在此主题中**

-   [准备 RMS SP1 更新](#bkmk_1)
-   [执行 RMS SP1 更新](#bkmk_2)
-   [更新群集](#bkmk_3)
-   [更新 RMS 客户端](#bkmk_4)
-   [与 RMS 1.0 版的互操作性](#bkmk_5)
-   [删除 RMS SP1](#bkmk_6)

<span id="BKMK_1"></span>
准备 RMS SP1 更新
-----------------

RMS SP1 更新旨在允许您持续运行 RMS 操作，不会造成中断。但是，在您升级 RMS 服务器之前，建议您执行下列操作：

-   备份配置数据库和 RMS 私钥。有关详细信息，请参阅本文档集的“规划 RMS 部署”一节中的“RMS 的系统备份”。
-   确保您拥有 RMS 私钥密码。
-   如果您要保留之前记录的统计信息，请备份记录数据库。
-   确保在您的客户端和服务器上为操作系统安装了最新的关键更新和安全更新。要验证您是否拥有所有关键更新和安全更新，请单击“开始”，单击“Windows Update”，然后按照出现在屏幕上的说明操作。

<span id="BKMK_2"></span>
执行 RMS SP1 更新
-----------------

当 RMS SP1 安装程序检测到您的 RMS 安装时，它只添加新文件或替换需要针对 RMS SP1 进行更改的文件。如果您已经成功运行 RMS，则在安装 RMS SP1 后，您不需要重新设置任何其他配置即可继续运行 RMS。

<span id="BKMK_3"></span>
更新群集
--------

如果您已在群集配置中安装了 RMS，则应该计划更新您的群集以降低更新对您的安装的影响。确定如何最佳地在您的组织中实施 RMS SP1 时，请考虑下列建议：

-   最佳方案是，一次性在群集的某个部分上安装 RMS SP1，以便群集的升级可预测性更强，并且在升级期间导致服务降级的可能性最小。
-   如果您有多个 RMS 群集，则应该首先升级根认证群集，然后升级通过注册子过程注册的授权群集。
-   如果您使用跨林组扩展，则可以在林中单独升级群集，而不会影响 RMS 服务器跨林扩展组成员身份的功能。
-   RMS SP1 和 RMS 1.0 版服务器可以共存和互操作。
-   RMS SP1 安装程序包也可以用于在服务器上安装 RMS SP1 的新版本；它不需要安装 RMS 1.0 版。

<span id="BKMK_4"></span>
更新 RMS 客户端
---------------

新的 RMS 客户端包括在 RMS SP1 中。RMS SP1 客户端安装程序包也可以用于在计算机上安装 RMS SP1 客户端的新版本；它不需要安装 RMS 1.0 版客户端。RMS SP1 客户端包括后向兼容性功能，使它能够与启用了 RMS 并且需要 RMS 1.0 版的应用程序配合使用。

此新 RMS 客户端提供下列功能：

-   客户端不再需要通过 Internet 连接到 Microsoft 并下载密码箱。
-   如果您使用 SMS 或组策略安装 RMS 客户端，则安装不需要管理员特权。
-   RMS SP1 客户端包括新的服务器密码箱（也称为服务器安全处理器），它可用于启用了 RMS 的 Web 服务或服务器端应用程序（例如 Windows SharePoint® Services 和 Exchange Server 2003），以允许服务使用和重新分发 RMS 保护的内容。设计此密码箱是为了使其在受信任的服务器应用程序中使用时具有高性能和可扩展性
-   RMS 客户端使用 FIPS 140-2 认证的加密算法。这使客户端能够在符合 FIPS 的组织中部署。

<span id="BKMK_5"></span>
与 RMS 1.0 版的互操作性
-----------------------

由于 RMS SP1 提供了许多改进和性能增强功能，您应该在完成测试后安装它。虽然运行 RMS SP1 的 RMS 服务器和客户端完全可与不运行 RMS SP1 的 RMS 服务器和客户端互操作，但是应了解它们在混合环境中工作方式的差异：

-   仅运行 RMS SP1 的服务器能够脱机注册。
-   仅运行 RMS SP1 的客户端能够自激活。
-   下表描述了混合环境支持的功能：

###  

 
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
<th style="border:1px solid black;" >V1 客户端支持的功能</th>
<th style="border:1px solid black;" >SP1 客户端支持的功能</th>
<th style="border:1px solid black;" >在混合（V1 和 SP1）客户端环境中支持的功能</th>
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
对于 SP1 客户端，客户端是自激活的。
对于 V1 客户端，客户端必须通过 Internet 激活。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SP1</td>
<td style="border:1px solid black;">所有以前的功能。
服务器可以脱机注册。
客户端无法自激活。</td>
<td style="border:1px solid black;">所有 SP1 功能。
服务器可以脱机注册。
客户端可以自激活。
服务器密码箱。</td>
<td style="border:1px solid black;">所有先前的功能加上 SP1 功能。
服务器可以脱机注册。
对于 SP1 客户端，客户端是自激活的。
对于 V1 客户端，客户端必须通过 Internet 激活。</td>
</tr>
</tbody>
</table>
 

<span id="BKMK_6"></span>
删除 RMS SP1
------------

如果您在安装 RMS SP1 之后想要将 RMS 服务器恢复到其以前的配置，则可以使用控制面板中的“添加或删除程序”来删除 RMS SP1。

**注意**   如果您在安装 RMS SP1 之前进行了配置数据库备份，则可以还原该备份以彻底删除 RMS SP1 引入的所有更改。如果您未备份配置数据库，则可能可以将 RMS SP1 安装中的配置数据库与还原的 RMS 安装配合使用。还原的 RMS 安装将忽略 RMS SP1 安装在配置数据库中添加的额外字段，因为它不使用这些字段。
