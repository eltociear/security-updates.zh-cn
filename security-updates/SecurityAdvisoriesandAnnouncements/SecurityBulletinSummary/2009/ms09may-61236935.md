---
TOCTitle: 'MS09-MAY'
Title: 'Microsoft 安全公告摘要 (2009 年 5 月)'
ms:assetid: 'ms09-may'
ms:contentKeyID: 61236935
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms09-may(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2009 年 5 月)
=====================================

发布时间: 2009年5月12日

**版本:** 1.0

本公告摘要列出了 2009 年 5 月发布的安全公告。

对于 2009 年 5 月发布的安全公告，本公告摘要替代 2009 年 5 月 7 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2009 年 5 月 13 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 5 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032395223)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

摘要
----

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件及其下载位置**”。

<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th>公告 ID</th>
<th>公告标题和摘要</th>
<th>最高严重等级和漏洞影响</th>
<th>重新启动要求</th>
<th>受影响的软件</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340)</strong><br />
<br />
此安全更新解决了 Microsoft Office PowerPoint 中一个公开披露的漏洞和多个秘密报告的漏洞，如果用户打开特制的 PowerPoint 文件，则该漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID 和 CVE ID 的排序列出。
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 公告标题                                                          | CVE ID                                                                           | 利用指数评估                                                                                          | 重要注意事项                                   |  
|---------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------------------------------------------|  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-0220](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0220) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码         | （无）                                         |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-0221](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0221) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | **此漏洞当前正在 Internet 生态系统中被利用。** |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-0222](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0222) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | **此漏洞当前正在 Internet 生态系统中被利用。** |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-0223](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0223) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的功能漏洞检测代码 |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-0224](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0224) |                                                                                                       |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-0225](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0225) |                                                                                                       |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-0226](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0226) |                                                                                                       |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-0227](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0227) |                                                                                                       |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-0556](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0556) |                                                                                                       |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-1128](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1128) |                                                                                                       |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-1129](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1129) |                                                                                                       |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-1130](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1130) |                                                                                                       |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-1131](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1131) |                                                                                                       |                                                |  
| [MS09-017](http://technet.microsoft.com/security/bulletin/ms09-017) | Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (967340) | [CVE-2009-1137](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1137) |                                                                                                       |                                                |
  
受影响的软件和下载位置  
----------------------
  
<span></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">  
<tr class="thead">  
<th>  
</th>  
<th>  
</th>  
</tr>  
<tr>  
<th colspan="2" style="border:1px solid black;">  
Microsoft Office 套件、系统和组件  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://technet.microsoft.com/security/bulletin/ms09-017)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f443312a-ac74-4ebc-a4ac-7a756aa67894)  
(KB957790)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a24ec7ab-c1c7-4ddb-8b6e-107f1af67f49)  
(KB957781)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ccfa978b-3340-40db-a45d-c880ba36b106)  
(KB957784)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2007 Service Pack 1 和 Microsoft Office PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=11f8380f-ffb6-4c22-a89c-3dc55d0f9834)\*  
(KB957789)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://technet.microsoft.com/security/bulletin/ms09-017)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac\*\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac\*\*  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac\*\*  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://technet.microsoft.com/security/bulletin/ms09-017)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
PowerPoint Viewer
</td>
<td style="border:1px solid black;">
[PowerPoint Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6a57e6ed-bd24-406f-87bb-117391e083e0)  
(KB969615)  
（重要）  
[PowerPoint Viewer 2007 Service Pack 1 和 PowerPoint Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=141b8338-5c52-4326-a9e4-d2f2d8940d9c)  
(KB970059)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包以及用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 2 的 Microsoft Office 兼容包](http://www.microsoft.com/downloads/details.aspx?familyid=e1d3a4c3-538a-4f98-8d60-250803a80e2a)  
(KB969618)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
Microsoft Works 8.5\*\*  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9.0
</td>
<td style="border:1px solid black;">
Microsoft Works 9.0\*\*  
（重要）
</td>
</tr>
</table>

**MS09-017 注释**

\*对于 Microsoft Office PowerPoint 2007 Service Pack 1 和 Microsoft Office PowerPoint 2007 Service Pack 2，除了 KB957789 之外，客户还需要安装用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 1 和用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 2 的安全更新 (KB969618)，以免受本公告中所描述的漏洞影响。

\*\*Microsoft Office 2004 for Mac、Microsoft Office 2008 for Mac、Open XML File Format Converter for Mac、Microsoft Works 8.5 和 Microsoft Works 9.0 的更新仍在开发中。 测试完成后，Microsoft 将发布这些软件的更新，以确保其各自发布版本更高的质量。 由于存在目标明确的主动利用，因此 Microsoft 将增量发布此安全更新，并将在软件更新可用时进行发布。

目前 Microsoft 仅发现对 Windows 操作系统上运行的 Microsoft Office 版本的主动利用。 当前的安全更新可以保护大多数客户免受威胁。

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

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](http://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft Baseline Security Analyzer 和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [Microsoft Windows 之外的其他 Microsoft 产品的新更新、经过修订的更新以及已发布的更新](http://technet.microsoft.com/en-us/wsus/dd573344.aspx)。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   一位匿名研究人员与 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作，报告了 MS09-017 中描述的两个问题
-   [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Sean Larsson 报告了 MS09-017 中描述的两个问题
-   [VUPEN Security](http://www.vupen.com/) 的 Nicolas Joly 报告了 MS09-017 中描述的问题
-   [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Marsu Pilami 报告了 MS09-017 中描述的多个问题
-   [VUPEN Security](http://www.vupen.com/) 的 Nicolas Joly 报告了 MS09-017 中描述的问题
-   Marsu Pilami 与 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 MS09-017 中描述的问题
-   [team509](http://www.team509.com/) 的 Ling 和 Wushi 与 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 以及 [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Sean Larsson 合作，报告了 MS09-017 中描述的问题
-   [Secunia](http://secunia.com/) 的 Carsten H. Eiram 报告了 MS09-017 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/default.aspx?ln=zh-cn)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2009 年 5 月 12 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
