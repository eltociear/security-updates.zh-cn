---
TOCTitle: 'MS10-MAY'
Title: 'Microsoft 安全公告摘要 (2010 年 5 月)'
ms:assetid: 'ms10-may'
ms:contentKeyID: 61236947
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms10-may(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2010 年 5 月)
=====================================

发布时间: 2010年5月11日

**版本:** 1.0

本公告摘要列出了 2010 年 5 月发布的安全公告。

对于 2010 年 5 月发布的安全公告，本公告摘要替代 2010 年 5 月 6 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2010 年 5 月 12 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 5 月份安全公告网络广播](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032427724&culture=en-us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-030">MS10-030</a></td>
<td style="border:1px solid black;"><strong>Outlook Express 和 Windows Mail 中的漏洞可能允许远程执行代码 (978542)</strong><br />
<br />
此安全更新解决 Outlook Express、Windows Mail 和 Windows Live Mail 中的一个秘密报告的漏洞。 如果用户访问恶意电子邮件服务器，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-031">MS10-031</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visual Basic for Applications 中的漏洞可能允许远程执行代码 (978213)</strong><br />
<br />
此安全更新解决 Microsoft Visual Basic for Applications 中的一个秘密报告的漏洞。 如果主机应用程序打开一个特制文件并将其传递到 Visual Basic for Applications runtime，此漏洞可以允许远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft Visual Basic for Applications</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按利用评估级别 和 CVE ID 降序顺序列出。 仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 漏洞标题                                     | CVE ID                                                                           | 利用指数评估                                                                                    | 重要注意事项                                                         |  
|---------------------------------------------------------------------|----------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|  
| [MS10-031](http://technet.microsoft.com/security/bulletin/ms10-031) | VBE6.DLL 堆栈内存损坏漏洞                    | [CVE-2010-0815](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0815) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现 | （无）                                                               |  
| [MS10-030](http://technet.microsoft.com/security/bulletin/ms10-030) | Outlook Express 和 Windows Mail 整数溢出漏洞 | [CVE-2010-0816](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0816) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现 | Windows Vista 及更高版本操作系统上的漏洞利用由于堆缓解而可能性较小。 |
  
受影响的软件和下载位置  
----------------------
  
<span></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Windows 操作系统和组件

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
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=661f5de3-a593-4961-8e8d-2777797eb5c5)  
(KB978542)  
（严重）  
[Microsoft Outlook Express 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=cda75174-b535-4559-a52d-b5ec3a1df349)  
(KB978542)  
（严重）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=99707c3d-a3cb-47da-b38e-8ae0227fd703)  
(KB978542)  
（严重）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=99707c3d-a3cb-47da-b38e-8ae0227fd703)<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=44bc97bb-6f76-4c96-af72-69daaea80fff)  
(KB978542)  
（严重）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=44bc97bb-6f76-4c96-af72-69daaea80fff)<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=eb9742fc-0934-4b38-9ec4-3597fc71ec00)  
(KB978542)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=5678515a-97ea-4e00-8700-d3f2fcdc0efc)  
(KB978542)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=60ef635b-cb6d-402f-b904-e69b519d797f)  
(KB978542)  
（严重）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=a970c869-24fe-4ef4-b189-7a6bac2411f1)  
(KB978542)  
（严重）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=a970c869-24fe-4ef4-b189-7a6bac2411f1)<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=9a7853b5-4f9f-4467-9530-eea2efd504a5)  
(KB978542)  
（严重）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=9a7853b5-4f9f-4467-9530-eea2efd504a5)<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=5f77a640-247c-4ed2-9fca-4b7344f4dc7c)\*\*  
(KB978542)  
（严重）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=5f77a640-247c-4ed2-9fca-4b7344f4dc7c)\*\*<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=b0eab011-5847-44e4-bc0d-5c5355e1e8d0)\*\*  
(KB978542)  
（严重）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=b0eab011-5847-44e4-bc0d-5c5355e1e8d0)\*\*<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=da01ae82-895e-4739-916f-a63b9095a076)  
(KB978542)  
（严重）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=da01ae82-895e-4739-916f-a63b9095a076)<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=1f0c17be-ba4c-4a1c-b9c3-8ac368800947)<sup>[2]</sup>  
(KB978542)  
（重要）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=1f0c17be-ba4c-4a1c-b9c3-8ac368800947)<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=a70f15e1-512c-44ca-a308-928e237ac0ce)<sup>[2]</sup>  
(KB978542)  
（重要）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=a70f15e1-512c-44ca-a308-928e237ac0ce)<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=e2e25c02-38ce-4868-a01a-39fc7d2a4150)\*\* <sup>[2]</sup>  
(KB978542)  
（重要）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=e2e25c02-38ce-4868-a01a-39fc7d2a4150)\*\* <sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=53ed1055-b5ee-4fde-9550-f8b401916467)<sup>[2]</sup>  
(KB978542)  
（重要）  
[Windows Live Mail](https://www.microsoft.com/download/details.aspx?familyid=53ed1055-b5ee-4fde-9550-f8b401916467)<sup>[1]</sup>  
(KB978542)  
（重要）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

<sup>[1]</sup>Windows Live Mail 是此操作系统上的一个即装即用组件，需要单独安装才会有此漏洞。

<sup>[2]</sup>Windows Live 是此操作系统上的一个即装即用组件，需要单独安装才会有此漏洞。

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
[**MS10-031**](http://technet.microsoft.com/security/bulletin/ms10-031)
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=72c23b0f-4e24-4334-bc8a-334adc8bc42b)   
(KB976380)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f8eac9bc-8389-4ac8-8b29-9a8180d9fd34)   
(KB976382)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=160ad53e-6475-4550-90c2-444e4abea730)   
(KB976321)  
（重要）
</td>
</tr>
</table>

**MS10-031 注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

#### Microsoft 开发工具和软件

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
Microsoft Visual Basic for Applications
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-031**](http://technet.microsoft.com/security/bulletin/ms10-031)
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
Microsoft Visual Basic for Applications
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic for Applications](https://www.microsoft.com/download/details.aspx?familyid=436a8a66-352e-44d1-a610-c825083ad24a)<sup>[1]</sup>  
(KB974945)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK
</td>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK<sup>[2]</sup><sup>[3]</sup>  
（严重）
</td>
</tr>
</table>

**MS10-031 注释**

<sup>[1]</sup>此更新包适用于 Microsoft Visual Basic for Applications runtime (Vbe6.dll) 的受支持版本，只能从 Microsoft 下载中心获得。

<sup>[2]</sup>VBA SDK 的受支持版本是 Microsoft Visual Basic for Applications SDK 6.3、Microsoft Visual Basic for Applications SDK 6.4 和 Microsoft Visual Basic for Applications SDK 6.5。

<sup>[3]</sup>可通过 [Summit Software Company](http://www.summsoft.com/) 为独立软件供应商 (ISV) 提供 Visual Basic for Applications SDK 的更新版本以解决此公告中描述的漏洞。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**注意** 从 2009 年 8 月 1 日起，Microsoft 将不再对 Office Update 和 Office Update 清单工具提供支持。 要继续获得 Microsoft Office 产品的最新更新，请使用 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)。 有关详细信息，请参阅[关于 Microsoft Office Update： 常见问题](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。 该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。 有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用安全更新清单工具 (SUIT) 来帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

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

-   Protek Research Lab 的 Francis Provencher 报告了 MS10-030 中描述的问题
-   [NSFocus Security Team](http://www.nsfocus.com/) 报告了 MS10-031 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2010 年 5 月 11 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
