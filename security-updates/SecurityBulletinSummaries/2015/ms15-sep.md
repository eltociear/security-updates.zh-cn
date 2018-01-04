---
TOCTitle: 'MS15-SEP'
Title: 'Microsoft 安全公告摘要（2015 年 9 月）'
ms:assetid: 'ms15-sep'
ms:contentKeyID: 69933023
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms15-sep(v=Security.10)'
---



Microsoft 安全公告摘要（2015 年 9 月）
======================================

发布日期：2015 年 9 月 8 日 | 更新时间：2015 年 11 月 10 日

**版本：** 4.0

本公告摘要列出了 2015 年 9 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节?**受影响的软件**?。

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>公告标题和执行摘要</strong></p></td>
<td style="border:1px solid black;"><p><strong>最高严重等级<br />
和漏洞影响</strong></p></td>
<td style="border:1px solid black;"><p><strong>重新启动要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>已知<br />
问题</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积安全更新程序 (3089548)</strong> <br />
此安全更新可解决 Internet Explorer 中的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看经特殊设计的网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-095">MS15-095</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 的累积安全更新 (3089665)<br />
</strong>此安全更新可修复 Microsoft Edge 中的漏洞。最严重的漏洞可能在用户使用 Microsoft Edge 查看经特殊设计的网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-096">MS15-096</a></p></td>
<td style="border:1px solid black;"><p><strong>Active Directory 服务中的漏洞可能允许拒绝服务 (3072595)<br />
</strong>此安全更新可修复 Active Directory 中的漏洞。如果已经过身份验证的攻击者创建多个计算机帐户，则此漏洞可能允许拒绝服务。要利用此漏洞，攻击者必须具有有权将计算机加入域的帐户。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 图形组件中的漏洞可能允许远程执行代码 (3089656)<br />
</strong>此安全更新可修复 Microsoft Windows、Microsoft Office 和 Microsoft Lync 中的漏洞。如果用户打开经特殊设计的文档或者访问嵌入了 OpenType 字体的不受信任网页，则这些漏洞中最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3086255">3086255</a><br />
<a href="https://support.microsoft.com/zh-cn/kb/3099414">3099414</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Office、<br />
Microsoft Lync</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-098">MS15-098</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 日记本中的漏洞可能允许远程执行代码 (3089669)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。如果用户打开经特殊设计的 Excel 文件，较严重的漏洞可能允许远程执行代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-099">MS15-099</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (3089664)<br />
</strong>此安全更新可修复 Microsoft Office 中的漏洞。最严重的漏洞可能在用户打开经特殊设计的 Microsoft Office 文件时允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft SharePoint Foundation</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-100">MS15-100</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Media Center 中的漏洞可能允许远程执行代码 (3087918)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。如果 Windows Media Center 打开引用了恶意代码的经特殊设计的 Media Center 链接 (.mcl) 文件，则此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-101">MS15-101</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 中的漏洞可能允许特权提升 (3089662)<br />
</strong>此安全更新可解决 Microsoft .NET Framework 中的漏洞。如果用户运行经特殊设计的 .NET 应用程序，则最严重的漏洞可能允许特权提升。但是，在所有情况下，攻击者无法强迫用户运行应用程序，攻击者必须说服用户执行此类操作。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-102">MS15-102</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 任务管理中的漏洞可能允许特权提升 (3089657)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。这些漏洞在攻击者登录系统并运行经特殊设计的应用程序时允许提升特权。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-103">MS15-103</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Exchange Server 中的漏洞可能允许信息泄漏 (3089250)<br />
</strong>此安全更新程序可修复 Microsoft Exchange Server 中的多个漏洞。如果 Outlook Web Access (OWA) 未正确处理 Web 请求和清理用户输入和电子邮件内容，最严重的漏洞可能允许信息泄漏。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Exchange Server</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-104">MS15-104</a></p></td>
<td style="border:1px solid black;"><p><strong>Skype for Business Server 和 Microsoft Lync Server 中的漏洞可能允许特权提升 (3089952)<br />
</strong>此安全更新可修复 Skype for Business Server 和 Microsoft Lync Server 中的漏洞。如果用户单击经特殊设计的 URL，则最严重的漏洞可能允许特权提升。攻击者必须诱使用户单击即时消息或电子邮件中的链接，通过经特殊设计的 URL 将用户转到受影响的网站。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3080353">3080353</a></p></td>
<td style="border:1px solid black;"><p>Skype for Business Server、<br />
Microsoft Lync Server</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-105">MS15-105</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Hyper-V 中的漏洞可能允许绕过安全功能 (3091287)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。如果攻击者运行经特殊设计的并可能导致 Windows Hyper-V 无法正确将访问控制列表 (ACL) 应用于配置设置的应用程序，此漏洞可能允许绕过安全功能。尚未启用 Hyper-V 角色的客户不会受到影响。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
对于您可能需要安装的每个安全更新，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/zh-cn/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新软件版本”是指主题软件，“较旧软件版本”是指主题软件的所有较旧的受支持版本。
  
<table style="width:100%;">  
<colgroup>  
<col width="16%" />  
<col width="16%" />  
<col width="16%" />  
<col width="16%" />  
<col width="16%" />  
<col width="16%" />  
</colgroup>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>漏洞标题</strong></p></td>
<td style="border:1px solid black;"><p><strong>CVE ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估<br />
</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估<br />
</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务<br />
利用评估</strong></p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2483">CVE-2015-2483</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>篡改漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2484">CVE-2015-2484</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2485">CVE-2015-2485</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2486">CVE-2015-2486</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2487">CVE-2015-2487</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2489">CVE-2015-2489</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2490">CVE-2015-2490</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2491">CVE-2015-2491</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2492">CVE-2015-2492</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>脚本引擎内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2493">CVE-2015-2493</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2494">CVE-2015-2494</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2498">CVE-2015-2498</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2499">CVE-2015-2499</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2500">CVE-2015-2500</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2501">CVE-2015-2501</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2541">CVE-2015-2541</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-094">MS15-094</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2542">CVE-2015-2542</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-095">MS15-095</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2485">CVE-2015-2485</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-095">MS15-095</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2486">CVE-2015-2486</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-095">MS15-095</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2494">CVE-2015-2494</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-095">MS15-095</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2542">CVE-2015-2542</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-096">MS15-096</a></p></td>
<td style="border:1px solid black;"><p>Active Directory 拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2535">CVE-2015-2535</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>OpenType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2506">CVE-2015-2506</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>字体驱动程序特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2507">CVE-2015-2507</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>字体驱动程序特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2508">CVE-2015-2508</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>临时</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>图形组件缓冲区溢出漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2510">CVE-2015-2510</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>Win32k 内存损坏特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2511">CVE-2015-2511</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>字体驱动程序特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2512">CVE-2015-2512</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>Win32k 内存损坏特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2517">CVE-2015-2517</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>Win32k 内存损坏特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2518">CVE-2015-2518</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>Win32k 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2527">CVE-2015-2527</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>内核 ASLR 绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2529">CVE-2015-2529</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-097">MS15-097</a></p></td>
<td style="border:1px solid black;"><p>Win32k 内存损坏特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2546">CVE-2015-2546</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-098">MS15-098</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本 RCE 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2513">CVE-2015-2513</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-098">MS15-098</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本 DoS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2514">CVE-2015-2514</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-098">MS15-098</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本 DoS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2516">CVE-2015-2516</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-098">MS15-098</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本整数溢出 RCE 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2519">CVE-2015-2519</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-098">MS15-098</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本 RCE 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2530">CVE-2015-2530</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-099">MS15-099</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2520">CVE-2015-2520</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-099">MS15-099</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2521">CVE-2015-2521</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-099">MS15-099</a></p></td>
<td style="border:1px solid black;"><p>Microsoft SharePoint XSS 欺骗漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2522">CVE-2015-2522</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-099">MS15-099</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2523">CVE-2015-2523</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-099">MS15-099</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 格式错误的 EPS 文件漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2545">CVE-2015-2545</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-100">MS15-100</a></p></td>
<td style="border:1px solid black;"><p>Windows Media Center RCE 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2509">CVE-2015-2509</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-101">MS15-101</a></p></td>
<td style="border:1px solid black;"><p>.NET 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2504">CVE-2015-2504</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-101">MS15-101</a></p></td>
<td style="border:1px solid black;"><p>MVC 拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2526">CVE-2015-2526</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>临时</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-102">MS15-102</a></p></td>
<td style="border:1px solid black;"><p>Windows 任务管理特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2524">CVE-2015-2524</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-102">MS15-102</a></p></td>
<td style="border:1px solid black;"><p>Windows 任务文件删除特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2525">CVE-2015-2525</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-102">MS15-102</a></p></td>
<td style="border:1px solid black;"><p>Windows 任务管理特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2528">CVE-2015-2528</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-103">MS15-103</a></p></td>
<td style="border:1px solid black;"><p>Exchange 信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2505">CVE-2015-2505</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-103">MS15-103</a></p></td>
<td style="border:1px solid black;"><p>Exchange 欺骗漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2543">CVE-2015-2543</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-103">MS15-103</a></p></td>
<td style="border:1px solid black;"><p>Exchange 欺骗漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2544">CVE-2015-2544</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-104">MS15-104</a></p></td>
<td style="border:1px solid black;"><p>Skype for Business Server 和 Lync Server XSS 信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2531">CVE-2015-2531</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-104">MS15-104</a></p></td>
<td style="border:1px solid black;"><p>Lync Server XSS 信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2532">CVE-2015-2532</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-104">MS15-104</a></p></td>
<td style="border:1px solid black;"><p>Skype for Business Server 和 Lync Server XSS 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2536">CVE-2015-2536</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-105">MS15-105</a></p></td>
<td style="border:1px solid black;"><p>Hyper-V 安全功能绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2534">CVE-2015-2534</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
</tbody>  
</table>
  
受影响的软件  
------------
  
<span id="sectionToggle2"></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
### Windows 操作系统和组件（表 1-2）

<p> </p>
<table style="border:1px solid black;">  
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-cn/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-cn/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-cn/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-cn/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
（严重）  
Internet Explorer 8  
(3087038)  
（严重）  
Internet Explorer 9  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3087039)  
（重要）  
Windows Vista Service Pack 2  
(3087135)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
（严重）  
Internet Explorer 8  
(3087038)  
（严重）  
Internet Explorer 9  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3087039)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3087135)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-cn/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-cn/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-cn/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-cn/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
（中等）  
Internet Explorer 8  
(3087038)  
（中等）  
Internet Explorer 9  
(3087038)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3087039)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3087135)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
（中等）  
Internet Explorer 8  
(3087038)  
（中等）  
Internet Explorer 9  
(3087038)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3087039)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3087135)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087038)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3087039)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3087135)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-cn/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-cn/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-cn/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-cn/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087038)  
（严重）  
Internet Explorer 9  
(3087038)  
（严重）  
Internet Explorer 10  
(3087038)  
（严重）  
Internet Explorer 11  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087038)  
（严重）  
Internet Explorer 9  
(3087038)  
（严重）  
Internet Explorer 10  
(3087038)  
（严重）  
Internet Explorer 11  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-cn/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-cn/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-cn/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-cn/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087038)  
（中等）  
Internet Explorer 9  
(3087038)  
（中等）  
Internet Explorer 10  
(3087038)  
（中等）  
Internet Explorer 11  
(3087038)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087038)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-cn/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-cn/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-cn/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-cn/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-cn/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-cn/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-cn/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-cn/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087038)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087038)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-cn/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-cn/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-cn/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-cn/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087038)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3069114)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-cn/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-cn/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-cn/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-cn/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081455)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081455)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3081455)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3081455)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081455)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081455)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3081455)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3081455)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-094**](https://technet.microsoft.com/zh-cn/library/security/ms15-094)

</td>
<td style="border:1px solid black;">
[**MS15-095**](https://technet.microsoft.com/zh-cn/library/security/ms15-095)

</td>
<td style="border:1px solid black;">
[**MS15-096**](https://technet.microsoft.com/zh-cn/library/security/ms15-096)

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-098**](https://technet.microsoft.com/zh-cn/library/security/ms15-098)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3087039)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3087135)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3087039)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3087135)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3072595)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3087039)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

**MS15-097 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

### Windows 操作系统和组件（表 2-2）

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-cn/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-cn/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-cn/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-cn/library/security/ms15-105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
（重要）  
Microsoft .NET Framework 4.6  
(3074554)  
（重要）  
Microsoft .NET Framework 4.6  
(3074233)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
（重要）  
Microsoft .NET Framework 4.6  
(3074554)  
（重要）  
Microsoft .NET Framework 4.6  
(3074233)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-cn/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-cn/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-cn/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-cn/library/security/ms15-105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
（重要）  
Microsoft .NET Framework 4.6  
(3074554)  
（重要）  
Microsoft .NET Framework 4.6  
(3074233)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
（重要）  
Microsoft .NET Framework 4.6  
(3074554)  
（重要）  
Microsoft .NET Framework 4.6  
(3074233)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3074541)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-cn/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-cn/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-cn/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-cn/library/security/ms15-105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3074543)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
（重要）  
Microsoft .NET Framework 4.6  
(3074554)  
（重要）  
Microsoft .NET Framework 4.6  
(3074233)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3074543)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
（重要）  
Microsoft .NET Framework 4.6  
(3074554)  
（重要）  
Microsoft .NET Framework 4.6  
(3074233)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-cn/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-cn/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-cn/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-cn/library/security/ms15-105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3074543)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
（重要）  
Microsoft .NET Framework 4.6  
(3074554)  
（重要）  
Microsoft .NET Framework 4.6  
(3074233)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3074543)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-cn/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-cn/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-cn/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-cn/library/security/ms15-105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074544)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
（重要）  
Microsoft .NET Framework 4.6  
(3074552)  
（重要）  
Microsoft .NET Framework 4.6  
(3074231)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3082089)  
（重要）  
Windows 8（用于 32 位系统）  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074544)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
（重要）  
Microsoft .NET Framework 4.6  
(3074552)  
（重要）  
Microsoft .NET Framework 4.6  
(3074231)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3082089)  
（重要）  
Windows 8（用于基于 x64 的系统）  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074545)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
（重要）  
Microsoft .NET Framework 4.6  
(3074553)  
（重要）  
Microsoft .NET Framework 4.6  
(3074232)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3082089)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3087918)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074545)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
（重要）  
Microsoft .NET Framework 4.6  
(3074553)  
（重要）  
Microsoft .NET Framework 4.6  
(3074232)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3082089)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3087088)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-cn/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-cn/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-cn/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-cn/library/security/ms15-105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074544)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
（重要）  
Microsoft .NET Framework 4.6  
(3074552)  
（重要）  
Microsoft .NET Framework 4.6  
(3074231)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3082089)  
（重要）  
Windows Server 2012  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074545)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
（重要）  
Microsoft .NET Framework 4.6  
(3074553)  
（重要）  
Microsoft .NET Framework 4.6  
(3074232)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3082089)  
（重要）  
Windows Server 2012 R2  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3087088)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-cn/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-cn/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-cn/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-cn/library/security/ms15-105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
（重要）  
Microsoft .NET Framework 4.6  
(3074231)  
（重要）  
Microsoft .NET Framework 4.6  
(3074552)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3082089)  
（重要）  
Windows RT  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
（重要）  
Microsoft .NET Framework 4.6  
(3074232)  
（重要）  
Microsoft .NET Framework 4.6  
(3074553)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3082089)  
（重要）  
Windows RT 8.1  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-cn/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-cn/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-cn/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-cn/library/security/ms15-105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3081455)  
（重要）  
Microsoft .NET Framework 4.6  
(3081455)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3081455)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3081455)  
（重要）  
Microsoft .NET Framework 4.6  
(3081455)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3081455)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3081455)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-100**](https://technet.microsoft.com/zh-cn/library/security/ms15-100)

</td>
<td style="border:1px solid black;">
[**MS15-101**](https://technet.microsoft.com/zh-cn/library/security/ms15-101)

</td>
<td style="border:1px solid black;">
[**MS15-102**](https://technet.microsoft.com/zh-cn/library/security/ms15-102)

</td>
<td style="border:1px solid black;">
[**MS15-105**](https://technet.microsoft.com/zh-cn/library/security/ms15-105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3074543)  
（重要）  
Microsoft .NET Framework 4  
(3074547)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074550)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074230)  
（重要）  
Microsoft .NET Framework 4.6  
(3074554)  
（重要）  
Microsoft .NET Framework 4.6  
(3074233)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074544)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074229)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3074549)  
（重要）  
Microsoft .NET Framework 4.6  
(3074552)  
（重要）  
Microsoft .NET Framework 4.6  
(3074231)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3082089)  
（重要）  
Windows Server 2012  
（服务器核心安装）  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3074545)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074548)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3074228)  
（重要）  
Microsoft .NET Framework 4.6  
(3074553)  
（重要）  
Microsoft .NET Framework 4.6  
(3074232)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3082089)  
（重要）  
Windows Server 2012 R2  
（服务器核心安装）  
(3084135)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3087088)  
（重要）

</td>
</tr>
</table>

### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-cn/library/security/ms15-099)

</td>
<td style="border:1px solid black;">
[**MS15-103**](https://technet.microsoft.com/zh-cn/library/security/ms15-103)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3085501)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 8  
(3089250)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 9  
(3089250)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3089250)  
（重要）

</td>
</tr>
</table>

**MS15-099 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-cn/library/security/ms15-099)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085546)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085620)  
（严重）  
Microsoft Excel 2007 Service Pack 3  
(3085543)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-cn/library/security/ms15-099)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3085529)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3085560)  
（严重）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3085526)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3085529)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3085560)  
（严重）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3085526)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-cn/library/security/ms15-099)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3085572)  
（严重）  
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(3085502)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office Service Pack 1（64 位版本）  
(3085572)  
（严重）  
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(3085502)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-cn/library/security/ms15-099)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1（32 位版本）  
(3085572)  
（严重）  
Microsoft Excel 2013 RT Service Pack 1  
(3085502)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-cn/library/security/ms15-099)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）  
(3085635)  
（严重）  
Microsoft Excel 2016（32 位版本）  
(2920693)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）  
(3085635)  
（严重）  
Microsoft Excel 2016（64 位版本）  
(2920693)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-cn/library/security/ms15-099)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3088501)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3088502)  
重要

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-099**](https://technet.microsoft.com/zh-cn/library/security/ms15-099)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(3054993)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3054995)  
（重要）

</td>
</tr>
</table>

**MS15-097 和 MS15-099 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

### Microsoft 通信平台和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-cn/library/security/ms15-104)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3081090)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-cn/library/security/ms15-104)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）  
(3081087)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）  
(3081087)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级别安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级别安装）  
(3081088)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）  
(3081089)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-cn/library/security/ms15-104)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）  
(Skype for Business)  
(3085500)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）  
(Skype for Business Basic)  
(3085500)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）  
(Skype for Business)  
(3085500)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）  
(Skype for Business Basic)  
(3085500)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Skype for Business 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-cn/library/security/ms15-104)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016（32 位）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（32 位）  
(2910994)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016（64 位）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（64 位）  
(2910994)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-cn/library/security/ms15-104)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
（Web 组件服务器）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
（Web 组件服务器）  
(3080353)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Skype for Business Server 2015**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-097**](https://technet.microsoft.com/zh-cn/library/security/ms15-097)

</td>
<td style="border:1px solid black;">
[**MS15-104**](https://technet.microsoft.com/zh-cn/library/security/ms15-104)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Server 2015

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Skype for Business Server 2015  
(3061064)  
（重要）

</td>
</tr>
</table>

**MS15-097 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](http://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn903755.aspx)部分。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/zh-cn/lifecycle)。

IT 专业人员安全解决方案：[TechNet 安全故障排除和支持](http://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

根据国家/地区进行本地支持：[国际支持](http://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2015 年 9 月 8 日）：已发布公告摘要。
-   V1.1（2015 年 9 月 8 日）：对于 MS15-097，针对 CVE-2015-2506 在“利用指数”中添加了利用评估。这仅仅是一个信息更改。
-   V1.2（2015 年 9 月 9 日）：对于 MS15-097，修订了 CVE-2015-2546“利用指数”中的利用评估；对于 MS15-099，修订了 CVE-2015-2545“利用指数”中的利用评估。这些仅仅是信息更改。
-   V1.3（2015 年 9 月 23 日）：公告经过修订更正了“利用指数”中 CVE-2015-2514 的标题。此仅为信息变更。已经成功安装了可解决此漏洞更新的客户不需要执行任何操作。
-   V1.4（2015 年 9 月 25 日）：对于 MS15-099，添加了 Microsoft Office 2016 for Mac 的 3088502 更新，自 2015 年 9 月 25 日起可用。有关更多信息，请参见 [Microsoft 知识库文章 3088502](https://support.microsoft.com/zh-cn/kb/3088502)。
-   V2.0（2015 年 9 月 30 日）：对于 MS15-097 中的 Microsoft Office 2016 和 MS15-099 中的 Skype for Business 2016，修订的公告摘要宣布了可用更新包。运行 Microsoft Office 2016 或 Skype for Business 2016 的客户应应用所需的更新以免受公告中讨论的漏洞攻击。大部分客户已启用“自动更新”，且不需要执行任何操作，因为系统将自动下载并安装所需更新。
-   V3.0（2015 年 10 月 13 日）：对于 MS15-099，修订的公告摘要宣布了可用于 Microsoft Excel 2016 的更新包。运行 Microsoft Excel 2016 的客户应应用更新 2920693 以免受 MS15-099 中讨论的漏洞攻击。大多数客户均启用了“自动更新”，他们不必采取任何操作，因为更新将自动下载并安装。
-   V4.0（2015 年 11 月 10 日）：对于 MS15-099，为了全面解决 CVE-2015-2545，Microsoft 重新发布了所有受影响 Microsoft Office 软件的安全更新。Microsoft 建议运行受影响的 Microsoft Office 软件版本的客户应安装随公告修订发布的安全更新以彻底免受该漏洞影响。运行其他 Microsoft Office 软件的客户无需采取任何措施。有关下载链接，请查看 [MS15-099](https://technet.microsoft.com/zh-cn/library/security/ms15-099)；有关详细信息，请参阅 [Microsoft 知识库文章 3089664](https://support.microsoft.com/zh-cn/kb/3089664)。

*页面生成时间：02.11.15 16:26:00-08:00。*
