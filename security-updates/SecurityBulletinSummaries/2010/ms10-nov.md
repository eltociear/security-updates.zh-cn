---
TOCTitle: 'MS10-NOV'
Title: 'Microsoft 安全公告摘要 (2010 年 11 月)'
ms:assetid: 'ms10-nov'
ms:contentKeyID: 61236948
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms10-nov(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2010 年 11 月)
======================================

发布时间: 2010年11月9日 | 更新时间: 2011年4月13日

**版本:** 2.1

本公告摘要列出了 2010 年 11 月发布的安全公告。

对于 2010 年 11 月发布的安全公告，本公告摘要替代 2010 年 11 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2010 年 11 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 11 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032454441)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-087">MS10-087</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (2423930)</strong><br />
<br />
此安全更新可解决 Microsoft Office 中一个公开披露的漏洞和五个秘密报告的漏洞。 如果用户打开或预览特制的 RTF 电子邮件，最严重的漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-088">MS10-088</a></td>
<td style="border:1px solid black;"><strong>Microsoft PowerPoint 中的漏洞可能允许远程执行代码 (2293386)</strong><br />
<br />
此安全更新可解决 Microsoft Office 中两个秘密报告的漏洞，如果用户打开特制的 PowerPoint 文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-089">MS10-089</a></td>
<td style="border:1px solid black;"><strong>Forefront Unified Access Gateway (UAG) 中的漏洞可能允许特权提升 (2316074)</strong><br />
<br />
此安全更新可解决 Forefront Unified Access Gateway (UAG) 中四个秘密报告的漏洞。 如果用户使用特制的 URL 访问受影响的网站，则其中最严重的漏洞可能允许特权提升。 但是，攻击者无法强迫用户访问该网站。 相反，攻击者必须说服用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Forefront United Access Gateway</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按利用评估级别 和 CVE ID 降序顺序列出。 仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 漏洞标题                                                                | CVE ID                                                                           | 利用指数评估                                                                                  | 重要注意事项                                                                         |  
|---------------------------------------------------------------------|-------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|  
| [MS10-088](https://technet.microsoft.com/security/bulletin/ms10-088) | PowerPoint 分析缓冲区溢出漏洞                                           | [CVE-2010-2572](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2572) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                                                               |  
| [MS10-089](https://technet.microsoft.com/security/bulletin/ms10-089) | UAG XSS 允许 EOP 漏洞                                                   | [CVE-2010-2733](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2733) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                                                               |  
| [MS10-089](https://technet.microsoft.com/security/bulletin/ms10-089) | Forefront Unified Access Gateway 中的 UAG 移动门户网站上的 XSS 问题漏洞 | [CVE-2010-2734](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2734) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                                                               |  
| [MS10-087](https://technet.microsoft.com/security/bulletin/ms10-087) | RTF 堆栈缓冲区溢出漏洞                                                  | [CVE-2010-3333](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3333) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                                                               |  
| [MS10-087](https://technet.microsoft.com/security/bulletin/ms10-087) | Office 艺术绘制记录漏洞                                                 | [CVE-2010-3334](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3334) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                                                               |  
| [MS10-087](https://technet.microsoft.com/security/bulletin/ms10-087) | 绘制异常处理漏洞                                                        | [CVE-2010-3335](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3335) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                                                               |  
| [MS10-087](https://technet.microsoft.com/security/bulletin/ms10-087) | 库加载不安全漏洞                                                        | [CVE-2010-3337](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3337) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | **此漏洞已公开披露**                                                                 |  
| [MS10-089](https://technet.microsoft.com/security/bulletin/ms10-089) | Signurl.asp 中的 XSS 漏洞                                               | [CVE-2010-3936](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3936) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                                                               |  
| [MS10-087](https://technet.microsoft.com/security/bulletin/ms10-087) | PowerPoint 整数下溢导致堆损坏漏洞                                       | [CVE-2010-2573](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2573) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | [MS10-088](https://technet.microsoft.com/security/bulletin/ms10-088) 也可解决此漏洞。 |  
| [MS10-088](https://technet.microsoft.com/security/bulletin/ms10-088) | PowerPoint 整数下溢导致堆损坏漏洞                                       | [CVE-2010-2573](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2573) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | [MS10-087](https://technet.microsoft.com/security/bulletin/ms10-087) 也可解决此漏洞。 |  
| [MS10-087](https://technet.microsoft.com/security/bulletin/ms10-087) | MSO 大型 SPID 读取 AV 漏洞                                              | [CVE-2010-3336](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3336) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                                                               |  
| [MS10-089](https://technet.microsoft.com/security/bulletin/ms10-089) | UAG 重定向欺骗漏洞                                                      | [CVE-2010-2732](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2732) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的代码     | 这只是一个欺骗漏洞                                                                   |
  
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
<th>  
</th>  
</tr>  
<tr>  
<th colspan="3" style="border:1px solid black;">  
Microsoft Office 套件和组件  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-087**](https://technet.microsoft.com/security/bulletin/ms10-087)
</td>
<td style="border:1px solid black;">
[**MS10-088**](https://technet.microsoft.com/security/bulletin/ms10-088)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f32648e3-2fb5-472c-932f-360e5d3c0931)  
(KB2289169)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3efbf9f6-734a-46ac-8f92-87b6ec819bfa)  
(KB2413272)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=07a6cf76-2cea-4c54-b66d-50e9eed108ac)  
(KB2289187)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=108286d4-fb68-40d6-a7b1-64b3a4eb87ee)  
(KB2413304)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=be0c5878-60c0-4700-8836-50d369b51d04)  
(KB2289158)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=0b308508-0e1e-4e90-b2b8-7e32bfc5dbf4)  
(KB2289161)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=534c6a2a-e7c6-4adf-8b81-e009a2b5fff4)  
(KB2289161)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-087**](https://technet.microsoft.com/security/bulletin/ms10-087)
</td>
<td style="border:1px solid black;">
[**MS10-088**](https://technet.microsoft.com/security/bulletin/ms10-088)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac<sup>[1]</sup>  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ad1b1984-b2b2-49b3-a1dd-385b77d9248a)  
(KB2476512)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=8bd6ca3b-8004-4e8d-a09d-220dcbbce799)  
(KB2454823)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=b846d255-a7d4-4a2c-a084-d434c29fe676)  
(KB2476511)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-087**](https://technet.microsoft.com/security/bulletin/ms10-087)
</td>
<td style="border:1px solid black;">
[**MS10-088**](https://technet.microsoft.com/security/bulletin/ms10-088)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Viewer 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=df826b79-7398-45de-943c-6f6f0af1b4e3)  
(KB2413381)  
（重要）
</td>
</tr>
</table>

**MS10-087 注释**

<sup>[1]</sup>自 2011 年 4 月 12 日起提供 Microsoft Office 2004 for Mac (KB2505924) 安全更新。有关详细信息，请参阅公告。

**MS10-088 注释**

<sup>[1]</sup>自 2011 年 4 月 12 日起提供 Microsoft Office 2004 for Mac (KB2505924) 安全更新。有关详细信息，请参阅公告。

#### Microsoft Remote Access 软件

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
Microsoft Forefront Unified Access Gateway
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-089**](https://technet.microsoft.com/security/bulletin/ms10-089)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Unified Access Gateway
</td>
<td style="border:1px solid black;">
[Forefront Unified Access Gateway 2010](https://www.microsoft.com/download/details.aspx?familyid=5f2ee08e-e289-47db-bd3f-7b9cfc1eb985)<sup>[1]</sup>  
(KB2433585)  
（重要）  
[Forefront Unified Access Gateway 2010 Update 1](https://www.microsoft.com/download/details.aspx?familyid=db0b70c8-1fa5-4d92-9888-3500c7566b19)<sup>[1]</sup>  
(KB2433584)  
（重要）  
[Forefront Unified Access Gateway 2010 Update 2](https://www.microsoft.com/download/details.aspx?familyid=4e3ee07a-771c-46ee-959f-82389bab67d7)<sup>[1]</sup>  
(KB2418933)  
（重要）
</td>
</tr>
</table>

**MS10-089 注释**

<sup>[1]</sup>此更新只能从 Microsoft 下载中心下载。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。 该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。 有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](https://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用安全更新清单工具 (SUIT) 来帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2.0 管理功能包](https://go.microsoft.com/fwlink/?linkid=21161)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://www.microsoft.com/security/msrc/mapp/partners.mspx)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   一名匿名研究人员与 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-087 中描述的问题
-   [team509](https://www.team509.com/) 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 MS10-087 中描述的问题
-   [Secunia](https://secunia.com/) 的 Dyon Balding 报告了 MS10-087 中描述的问题
-   [CERT Coordination Center](https://www.cert.org/) 的 Will Dorman 报告了 MS10-087 中描述的问题
-   [TippingPoint 的](https://www.tippingpoint.com/) [Zero Day Initiative](https://www.zerodayinitiative.com/) 报告了 MS10-087 中描述的问题
-   [VUPEN Vulnerability Research Team](https://www.vupen.com/) 的 Chaouki Bekrar 报告了 MS10-087 中描述的问题
-   [Fortinet FortiGuard Labs](https://www.fortiguard.com/) 的 Haifei Li 报告了 MS10-087 中描述的问题
-   [ACROS Security](https://www.acrossecurity.com) 的 Simon Raner 报告了 MS10-087 中描述的问题
-   [Secunia Research](https://secunia.com/) 的 Alin Rad Pop 报告了 MS10-088 中描述的问题
-   一名匿名研究人员与 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-088 中描述的问题
-   [BugSec](https://www.bugsec.com/) 的 Eyal Gruner 与我们一起努力处理了 MS10-089 中描述的三个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2010 年 11 月 9 日）： 已发布公告摘要。
-   V1.1（2010 年 11 月 9 日）： 对于 MS10-088，已将受影响版本从“Microsoft PowerPoint Viewer”更正为“Microsoft PowerPoint Viewer 2007 Service Pack 2”。 这仅仅是一个信息更改。 已经成功地更新了其系统的客户（包括启用了自动更新的客户）不需要执行任何操作。 以前未安装过此更新的客户可能需要根据修订的受影响的软件重新评估其系统，了解其系统是否需要此更新。
-   V1.2（2010 年 11 月 17 日）： 对于 MS10-087，更正了利用指数，以添加 CVE-2010-2573 作为此更新所解决的漏洞。 这仅仅是一个信息更改。
-   V2.0（2010 年 12 月 15 日）： 对于 MS10-087，已修订此公告摘要，以宣布 Microsoft Office 2008 for Mac (KB2476512) 和 Open XML File Format Converter for Mac (KB2476511) 的安全更新已可用。 Microsoft 建议使用这些软件的客户尽早应用这些更新。
-   V2.1（2011 年 4 月 13 日）： 已修订此公告摘要，宣布 Microsoft Office 2004 for Mac (KB2505924) 更新已可用。 有关详细信息，请参阅 MS10-087 和 MS10-088。

*Built at 2014-04-18T01:50:00Z-07:00*
