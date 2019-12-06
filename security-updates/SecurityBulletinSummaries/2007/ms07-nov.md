---
TOCTitle: 'MS07-NOV'
Title: 'Microsoft 安全公告摘要 (2007 年 11 月)'
ms:assetid: 'ms07-nov'
ms:contentKeyID: 61236909
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms07-nov(v=Security.10)'
---



Microsoft 安全公告摘要 (2007 年 11 月)
======================================

发布时间: 2007年11月13日

**版本:** 1.0

本公告摘要列出了 2007 年 11 月发布的安全公告。

对于 2007 年 11 月发布的安全公告，本公告摘要替代 2007 年 11 月 8 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2007 年 11 月 14 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 11 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344694&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (1)
--------

| 公告标识符       | Microsoft 安全公告 MS07-061                                                                                                                                                                                                                                                                                                                                              |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows URI 处理中的漏洞可能允许远程执行代码 (943460)**](http://technet.microsoft.com/security/bulletin/ms07-061)                                                                                                                                                                                                                                                     |
| **摘要**         | 此更新可消除一个公开报告的漏洞。 Windows Shell 处理传递给它的特制 URI 的方式中存在一个远程执行代码漏洞。 如果 Windows Shell 没有充分验证这些 URI，则攻击者可能利用此漏洞并执行任意代码。 Microsoft 仅识别了在使用 Internet Explorer 7 的系统上利用此漏洞的方式。但是，Windows XP 和 Windows Server 2003 的所有受支持版本中包括的 Windows 文件 Shell32.dll 中存在该漏洞。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                     |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                             |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                                                                                                                                                                                                                       |
| **受影响的软件** | **Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                         |

重要 (1)
--------

| 公告标识符       | Microsoft 安全公告 MS07-062                                                                                                                                         |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**DNS 中的漏洞可能允许欺骗 (941672)**](http://technet.microsoft.com/security/bulletin/ms07-062)                                                                    |
| **摘要**         | 此重要安全更新可解决一个秘密报告的漏洞。 此欺骗漏洞存在于 Windows DNS 服务器中，允许攻击者向 DNS 请求发送特制响应，从而导致欺骗或者从合法位置重定向 Internet 流量。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                |
| **漏洞的影响**   | 欺骗                                                                                                                                                                |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动，在某些情况下除外。                                                  |
| **受影响的软件** | **Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                    |

受影响的软件和下载位置
----------------------

**我如何使用该表呢？**

可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果列出了一个软件程序或组件，则会列出漏洞的影响，并且还会使用超链接将其链接到可用的软件更新。

**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

**受影响的软件和下载位置**

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
详细信息        
</th>
<th>
详细信息        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS07-061**](http://technet.microsoft.com/security/bulletin/ms07-061)
</td>
<td style="border:1px solid black;">
[**MS07-062**](http://technet.microsoft.com/security/bulletin/ms07-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows 操作系统
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Server Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=c80fcd9b-d0f8-44db-96fc-bf2ead054ff4)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=8ba1c2f9-1bde-4e97-b327-21259c5e5104)
</td>
<td style="border:1px solid black;">
** **
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">
** **
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
</table>


检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)和 [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS) 和扩展安全更新清单工具 (ESUIT)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](http://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**注意** 2007 年 10 月 9 日以后，MBSA 1.2.1 使用的 MSSecure.XML 文件将不再更新。 在此日期后，MBSA 1.2.1 使用的 MSSecure.XML 文件中不会再添加新的安全更新，也不会再发行新版本的“企业扫描工具”。 这不影响 SMS 2.0 和 SMS 2003 的安全更新清单工具 (SUIT) 或扩展安全更新清单工具 (ESUIT)。有关详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](http://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft Baseline Security Analyzer 和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

在本月：

-   Microsoft 已在 Microsoft Update (MU) 和 Windows Server 更新服务 (WSUS) 上发布三个**非安全**、高优先级更新。
-   Microsoft 未在 Windows Update (WU) 上发布**非安全**、高优先级 Windows 更新。

注意，此信息**仅**适用于 Microsoft Update、Windows Update 和 Windows Server Update Services 上在发布安全公告摘要当天发布的**非安全**、高优先级更新。 并**不**提供关于其他日期发布的**非安全**更新的信息。

#### 安全策略和社区

**更新管理策略**

[安全修补程序管理指南](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳实践建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   Jesper Johansson 与我们一起努力处理了 MS07-061 中描述的问题
-   [Secunia](http://corporate.secunia.com/) 的 Carsten H. Eiram 与我们一起处理了 MS07-061 中描述的问题
-   [Finjan](http://www.finjan.com/) 的 Aviv Raff 与我们一起处理了 MS07-061 中描述的问题
-   [GNUCITIZEN](http://www.gnucitizen.org/) 的 Petko Petkov 与我们一起处理了 MS07-061 中描述的问题
-   [Scanit](http://www.scanit.be/) 的 Alla Berzroutchko 报告了 MS07-062 中描述的问题
-   [Trusteer](http://www.trusteer.com/) 的 Amit Klein 报告了 MS07-062 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2007 年 11 月 13 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
