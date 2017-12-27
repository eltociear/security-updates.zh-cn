---
TOCTitle: 'MS16-SEP'
Title: 'Microsoft 安全公告摘要（2016 年 9 月）'
ms:assetid: 'ms16-sep'
ms:contentKeyID: 73896028
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms16-sep(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2016 年 9 月）
======================================

发布时间：2016 年 9 月 13 日 | 更新日期：2017 年 7 月 11 日

**版本：**2.0

本公告摘要列出了 2016 年 9 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新以及与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅**受影响的软件**部分。

<p> </p>
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
<td style="border:1px solid black;"><p><strong>重启要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>已知<br />
问题</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=823624">MS16-104</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新程序 (3183038)<br />
</strong>此安全更新程序修复了 Internet Explorer 中的漏洞。如果用户使用 Internet Explorer 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，那么攻击者便可控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3185319">3185319</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=823625">MS16-105</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 累积安全更新程序 (3183043)<br />
</strong>此安全更新程序修复了 Microsoft Edge 中的漏洞。如果用户使用 Microsoft Edge 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=824814">MS16-106</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Graphics Component 安全更新程序 (3185848)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的漏洞。如果用户访问经特殊设计的网站或打开经特殊设计的文档，则其中最严重的漏洞可能允许远程执行代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=824817">MS16-107</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 安全更新程序 (3185852)<br />
</strong>此安全更新程序修复了 Microsoft Office 中的漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么这些漏洞中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响较小。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web Apps</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=824829">MS16-108</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Exchange Server 安全更新程序 (3185883)<br />
</strong>此安全更新程序修复了 Microsoft Exchange Server 中的漏洞。如果攻击者向易受攻击的 Exchange 服务器发送附带经特殊设计的附件的电子邮件，则其中最严重的漏洞可能允许在构建到 Exchange Server 中的 Oracle Outside In 库中远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Exchange</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=824768">MS16-109</a></p></td>
<td style="border:1px solid black;"><p><strong>Silverlight 安全更新程序 (3182373)<br />
</strong>此安全更新程序修复了 Microsoft Silverlight 中的一个漏洞。如果用户访问包含经特殊设计的 Silverlight 应用程序的遭到入侵的网站，则该漏洞可能允许远程执行代码。攻击者无法强迫用户访问遭到入侵的网站。而必须诱使用户进行访问，通常是通过诱使用户单击电子邮件或即时消息中的链接将用户转到攻击者的网站。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=821596">MS16-110</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 安全更新程序 (3178467)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的漏洞。如果攻击者创建经特殊设计的请求，并利用提升的特权在目标系统上执行任意代码，则最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3187754">3187754</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=825142">MS16-111</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Kernel 安全更新程序 (3186973)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的漏洞。如果攻击者在目标系统上运行经特殊设计的应用程序，此漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3175024">3175024</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=821605">MS16-112</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Lock Screen 安全更新程序 (3178469)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果 Windows 错误地允许从 Windows 锁屏加载 Web 内容，此漏洞将允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=824825">MS16-113</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Secure Kernel Mode 安全更新程序 (3185876)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果 Windows 安全内核模式未正确地处理内存中的对象，会存在信息泄漏漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=824826">MS16-114</a></p></td>
<td style="border:1px solid black;"><p><strong>SMBv1 Server 安全更新程序 (3185879)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。在 Windows Vista、Windows Server 2008、Windows 7 和 Windows Server 2008 R2 操作系统中，如果已身份验证的攻击者将经特殊设计的数据包发送至受影响的 Microsoft 服务器消息块 1.0 (SMBv1) 服务器，则此漏洞可能允许远程代码执行。其他 SMB 服务器版本不受此漏洞影响。尽管更高版本的操作系统受影响，但潜在的影响为拒绝服务。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=825727">MS16-115</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows PDF Library 安全更新程序 (3188733)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的漏洞。当用户在线查看经特殊设计的 PDF 内容或打开经特殊设计的 PDF 文档时，此漏洞可能允许信息泄漏。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=825725">MS16-116</a></p></td>
<td style="border:1px solid black;"><p><strong>适用于 VBScript Scripting Engine 的 OLE Automation 的安全更新程序 (3188724)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果攻击者成功诱使受影响系统的用户访问恶意或已入侵的网站，则此漏洞可能允许远程执行代码。请注意，必须安装两个更新程序才能免受此公告中所讨论漏洞的侵害：此公告 MS16-116 中的更新程序和 <a href="http://go.microsoft.com/fwlink/?linkid=823624">MS16-104</a> 中的更新程序。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows<br />
</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=825603">MS16-117</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 安全更新程序 (3188128)<br />
</strong>此安全更新程序修复了 Adobe Flash Player 在 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10 所有支持版本上安装时的漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Adobe Flash Player</p></td>
</tr>
</tbody>
</table>




利用指数
--------

下表提供了本月解决的各个漏洞的利用评估。按公告 ID（而非 CVE ID）顺序列出了漏洞。公告中仅包含严重等级为“严重”或“重要”的漏洞。

**如何使用该表？**

针对你可能需要安装的每个安全更新程序，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据你的特定配置，检查下面的每个评估，从而确定部署本月更新程序的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/zh-cn/security/cc998259)。

在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新软件版本”是指主题软件，“较旧软件版本”是指主题软件的所有较旧的受支持版本。

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**漏洞标题**

</td>
<td style="border:1px solid black;">
**最新软件版本的  
利用性评估**

</td>
<td style="border:1px solid black;">
**旧软件版本的  
利用性评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用性评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-104：Internet Explorer 累积安全更新程序 (3183038)**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3247)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3291](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3291)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3292](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3292)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3295](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3295)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3297](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3297)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3324](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3324)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3325](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3325)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3351](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3351)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3353](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3353)

</td>
<td style="border:1px solid black;">
Internet Explorer 安全功能绕过

</td>
<td style="border:1px solid black;">
3- 不太可能利用

</td>
<td style="border:1px solid black;">
3- 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3375](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3375)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-105：Microsoft Edge 累积安全更新程序 (3183043)**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3247)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3291](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3291)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3294](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3294)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3295](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3295)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3297](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3297)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3325](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3325)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3330](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3330)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3350](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3350)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3351](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3351)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3370](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3370)

</td>
<td style="border:1px solid black;">
PDF 库信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3374](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3374)

</td>
<td style="border:1px solid black;">
PDF 库信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3377](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3377)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-106：Microsoft 图形组件安全更新 (3185848)**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3348](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3348)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3349](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3349)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE–2016-3354](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3354)

</td>
<td style="border:1px solid black;">
GDI 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE–2016-3355](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3355)

</td>
<td style="border:1px solid black;">
GDI 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE–2016-3356](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3356)

</td>
<td style="border:1px solid black;">
GDI 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-107：Microsoft Office 安全更新 (3185852)**](http://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0137](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0137)

</td>
<td style="border:1px solid black;">
Microsoft APP-V ASLR 绕过

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0141)

</td>
<td style="border:1px solid black;">
Microsoft 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3357](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3357)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3358](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3358)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3359](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3359)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3360](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3360)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3361](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3361)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3362](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3362)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3363](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3363)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3364](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3364)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3365](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3365)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3366](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3366)

</td>
<td style="border:1px solid black;">
Microsoft Office 欺骗漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3381](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3381)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-108：Microsoft Exchange Server 安全更新 (3185883)**](http://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0138)

</td>
<td style="border:1px solid black;">
Microsoft Exchange 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3378](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3378)

</td>
<td style="border:1px solid black;">
Microsoft Exchange 开放重定向漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3379](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3379)

</td>
<td style="border:1px solid black;">
Microsoft Exchange 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-109：Silverlight 安全更新 (3182373)**](http://go.microsoft.com/fwlink/?linkid=824768)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3367](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3367)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 内存损坏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-110：Windows 安全更新 (3178467)**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3346](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3346)

</td>
<td style="border:1px solid black;">
Windows 权限执行特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3352](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3352)

</td>
<td style="border:1px solid black;">
Microsoft 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3368](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3368)

</td>
<td style="border:1px solid black;">
Windows 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3369](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3369)

</td>
<td style="border:1px solid black;">
Windows 拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-111：Windows 内核安全更新程序 (3186973)**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3305](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3305)

</td>
<td style="border:1px solid black;">
Windows 会话对象特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3306](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3306)

</td>
<td style="border:1px solid black;">
Windows 会话对象特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3371](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3371)

</td>
<td style="border:1px solid black;">
Windows 内核特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3372](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3372)

</td>
<td style="border:1px solid black;">
Windows 内核特权提升漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3373](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3373)

</td>
<td style="border:1px solid black;">
Windows 内核特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-112：锁屏安全更新 (3178469)**](http://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3302](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3302)

</td>
<td style="border:1px solid black;">
Windows 锁屏特权提升漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-113：Windows 安全内核模式安全更新 (3185876)**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3344](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3344)

</td>
<td style="border:1px solid black;">
Windows 安全内核模式信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-114：SMBv1 Server 安全更新 (3185879)**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3345](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3345)

</td>
<td style="border:1px solid black;">
Windows SMB 已验证远程执行代码漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-115：Microsoft Windows PDF 库安全更新程序 (3188733)**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3370](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3370)

</td>
<td style="border:1px solid black;">
PDF 库信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3374](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3374)

</td>
<td style="border:1px solid black;">
PDF 库信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-116：适用于 VBScript 脚本引擎的 OLE 自动化安全更新程序 (3188724)**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3375](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3375)

</td>
<td style="border:1px solid black;">
脚本引擎信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-117：Adobe Flash Player 安全更新程序 (3188128)**](http://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-29](http://helpx.adobe.com/cn/security/products/flash-player/apsb16-29.html)

</td>
<td style="border:1px solid black;">
关于漏洞安全性和更新优先级级别的信息，请参阅 Adobe 安全公告 [APSB16-29](http://helpx.adobe.com/cn/security/products/flash-player/apsb16-29.html)。

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

受影响的软件
------------

下表按主要软件类别和严重性的排序列出了公告。

通过这些表，您可以了解可能需要安装的安全更新程序。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新程序。如果列出了软件程序或组件，则也会列出软件更新程序的严重等级。

**注意** 你可能必须为单个漏洞安装多个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新程序（基于系统上已安装的程序或组件）。

 

### Windows 操作系统和组件（表 2-1）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 9   
(3185319)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3175024)  
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
Internet Explorer 9   
(3185319)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 9   
(3185319)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3175024)  
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
Internet Explorer 9   
(3185319)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3175024)  
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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 11  
(3185319)  
（严重）

</td>
<td style="border:1px solid black;">
不适用                   

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3175024)  
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
Internet Explorer 11  
(3185319)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 11  
(3185319)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3175024)  
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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3184471)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3187754)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3178539)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3184471)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3187754)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 64 位系统）  
(3178539)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3185319)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3175024)  
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
Internet Explorer 11  
(3185319)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3178539)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185319)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184471)  
（重要）  
Windows RT 8.1  
(3187754)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3178539)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185611)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185611)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3185611)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185611)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185611)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3185611)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185614)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185614)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3185614)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185614)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3185614)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3185614)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3189866)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3189866)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3189866)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3189866)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3189866)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3189866)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3189866)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3189866)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3189866)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3189866)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3189866)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3189866)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于 32 位系统）  
(4025342)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于基于 x64 的系统）  
(4025342)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-104**](http://go.microsoft.com/fwlink/?linkid=823624)

</td>
<td style="border:1px solid black;">
[**MS16-105**](http://go.microsoft.com/fwlink/?linkid=823625)

</td>
<td style="border:1px solid black;">
[**MS16-106**](http://go.microsoft.com/fwlink/?linkid=824814)

</td>
<td style="border:1px solid black;">
[**MS16-110**](http://go.microsoft.com/fwlink/?linkid=821596)

</td>
<td style="border:1px solid black;">
[**MS16-111**](http://go.microsoft.com/fwlink/?linkid=825142)

</td>
<td style="border:1px solid black;">
[**MS16-112**](http://go.microsoft.com/fwlink/?linkid=821605)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3175024)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 64 位系统）Service Pack 2（服务器核心安装）  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 64 位系统）Service Pack 2（服务器核心安装）  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于 64 位系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于 64 位系统）Service Pack 1（服务器核心安装）  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于 64 位系统）Service Pack 1（服务器核心安装）  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于 64 位系统）Service Pack 1（服务器核心安装）  
(3175024)  
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
Windows Server 2012（服务器核心安装）  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3175024)  
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
暂无

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3185911)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3184471)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3175024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3178539)  
（重要）

</td>
</tr>
</table>

 

### Windows 操作系统和组件（表 2-2）

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
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

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
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3184122)  
（严重）

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
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3184122)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3184122)  
（中等）

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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3184122)  
（中等）

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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3184122)  
（中等）

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
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

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
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3184122)  
（严重）

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
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3184122)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3184122)  
（中等）

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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3184122)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3184943)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3184122)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3188128)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3184943)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3184122)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3188128)  
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
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184943)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3184122)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3188128)  
（中等）

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
Windows Server 2012 R2  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184943)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3184122)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3188128)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT 8.1  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184943)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3184122)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3188128)  
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
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3185611)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3188128)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3185611)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3185611)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3188128)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3185614)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3188128)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3185614)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3188128)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3189866)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3189866)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3188128)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3185614)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3189866)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3189866)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3188128)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

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
[**MS16-113**](http://go.microsoft.com/fwlink/?linkid=824825)

</td>
<td style="border:1px solid black;">
[**MS16-114**](http://go.microsoft.com/fwlink/?linkid=824826)

</td>
<td style="border:1px solid black;">
[**MS16-115**](http://go.microsoft.com/fwlink/?linkid=825727)

</td>
<td style="border:1px solid black;">
[**MS16-116**](http://go.microsoft.com/fwlink/?linkid=825725)

</td>
<td style="border:1px solid black;">
[**MS16-117**](http://go.microsoft.com/fwlink/?linkid=825603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3184122)  
（中等）

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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3184122)  
（中等）

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3184122)  
（中等）

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
Windows Server 2012（服务器核心安装）  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3184122)  
（中等）

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
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3177186)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3184122)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

 

### Microsoft Office 套件和软件

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3118300)  
（严重）  
Microsoft Excel 2007 Service Pack 3  
(3115459)  
（重要）  
Microsoft Outlook 2007  
(3118303)  
（重要）  
Microsoft PowerPoint 2007 Service Pack 3  
(3114744)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3118309)  
（严重）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2553432)  
（严重）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3118316)  
（重要）  
Microsoft Outlook 2010 Service Pack 2（32 位版本）  
(3118313)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（32 位版本）  
(3115467)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3118309)  
（严重）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2553432)  
（严重）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3118316)  
（重要）  
Microsoft Outlook 2010 Service Pack 2（64 位版本）  
(3118313)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（64 位版本）  
(3115467)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3118268)  
（严重）  
Microsoft Office 2013 Service Pack 1（32 位版本）<sup>[1]</sup>  
（重要）  
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(3118284)  
（重要）  
Microsoft Outlook 2013 Service Pack 1（32 位版本）  
(3118280)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（32 位版本）  
(3115487)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）  
(3118268)  
（严重）  
Microsoft Office 2013 Service Pack 1（64 位版本）<sup>[1]</sup>  
（重要）  
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(3118284)  
（重要）  
Microsoft Outlook 2013 Service Pack 1（64 位版本）  
(3118280)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（64 位版本）  
(3115487)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3118268)  
（严重）  
Microsoft Excel 2013 RT Service Pack 1  
(3118284)  
（重要）  
Microsoft Outlook 2013 RT Service Pack 1  
(3118280)  
（重要）  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3115487)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）<sup>[1]</sup>  
Microsoft Office 2016（32 位版本）  
(3118292)  
（严重）  
Microsoft Excel 2016（32 位版本）  
(3118290)  
（重要）  
Microsoft Outlook 2016（32 位版本）  
(3118293)  
（重要）  
Microsoft Visio 2016（32 位版本）  
（重要）<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）<sup>[1]</sup>  
Microsoft Office 2016（64 位版本）  
(3118292)  
（严重）  
Microsoft Excel 2016（64 位版本）  
(3118290)  
（重要）  
Microsoft Outlook 2016（64 位版本）  
(3118293)  
（重要）  
Microsoft Visio 2016（64 位版本）  
（重要）<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3186805)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3186807)  
（重要）  
Microsoft PowerPoint 2016 for Mac  
(3186807)  
（重要）  
Microsoft Word 2016 for Mac  
(3186807)  
（严重）  
Microsoft Outlook 2016 for Mac  
(3186807)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2597974)  
（重要）  
Microsoft Office 兼容包 Service Pack 3  
(3115462)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3115463)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(3054969)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3118297)  
（严重）

</td>
</tr>
</table>

<sup>[1]</sup>此条目仅适用于即点即用 (C2R) 版本。

 

### Microsoft Office Services 和 Web Apps

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Excel Services  
(3115112)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）

</td>
<td style="border:1px solid black;">
Excel Services  
(3115112)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3115119)  
（重要）  
Word Automation Services  
(3115466)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3054862)  
（严重）  
Excel Automation Services  
(3115169)  
（严重）  
Word Automation Services  
(3115443)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3115472)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3118270)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-107**](http://go.microsoft.com/fwlink/?linkid=824817)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3118299)  
（重要）

</td>
</tr>
</table>

 

### Microsoft Server 软件

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-108**](http://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(3184711)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-108**](http://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(3184728)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-108**](http://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3184736)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新程序 12

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新程序 12  
(3184736)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新程序 13

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新程序 13  
(3184736)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-108**](http://go.microsoft.com/fwlink/?linkid=824829)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累积更新 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累积更新程序 1  
(3184736)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累积更新程序 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累积更新程序 2  
(3184736)  
（重要）

</td>
</tr>
</table>

### Microsoft 开发人员工具和软件

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-109**](http://go.microsoft.com/fwlink/?linkid=824768)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**                                                     

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 在 Mac 上安装时  
(3182373)  
（重要）  
Microsoft Silverlight 5 Developer Runtime 在 Mac 上安装时  
(3182373)  
（重要）  
Microsoft Silverlight 5 在 Microsoft Windows 客户端所有支持版本上安装时  
(3182373)  
（重要）  
Microsoft Silverlight 5 Developer Runtime 在 Microsoft Windows 客户端所有支持版本上安装时  
(3182373)  
（重要）  
Microsoft Silverlight 5 在 Microsoft Windows 服务器所有支持版本上安装时  
(3182373)  
（重要）

</td>
</tr>
</table>

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新程序。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](http://technet.microsoft.com/zh-cn/security/cc297183)。 

鸣谢
----

Microsoft 认可在安全社区中通过可靠的漏洞披露渠道帮助我们保护客户的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/mt674627.aspx)。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外发布的安全公告中不提供 Microsoft Windows 恶意软件删除工具的更新版本。

### MU、WU 和 WSUS 上的与安全无关的更新程序

若要了解 Windows 更新和 Microsoft 更新上的与安全无关的更新程序，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/zh-cn/wsus/bb456965)。显示除 Microsoft Windows 之外的其他 Microsoft 产品的所有新的、修订过的和重新发布的更新程序。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新程序之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件提供商可以使用此类漏洞信息通过其安全软件或设备（如防病毒、基于网络的入侵检测系统或基于主机的入侵防护系统）更新对客户提供的保护。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新程序**

可从以下位置获得针对其他安全问题的更新：

-   可从 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)获取安全更新。通过对“安全更新”进行关键词搜索可以非常方便地找到这些更新。
-   [Microsoft 更新](http://go.microsoft.com/fwlink/?linkid=40747)提供了适用于消费者平台的更新程序。
-   你可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案：[TechNet 安全疑难解答和支持](http://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](http://support.microsoft.com/zh-cn/contactus/cu_sc_virsec_master)

基于国家/地区的本地支持：[国际支持](http://support.microsoft.com/zh-cn/common/international.aspx)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定用途的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（[2016 年 9 月 13 日](https://technet.microsoft.com/zh-CN/library/bulletin+summary_publisheddate(v=Security.10))）：已发布公告摘要。
-   V2.0（2017 年 7 月 11 日）：对于 MS16-111，将受 CVE-2016-3305 影响的 Windows 10 版本 1703（用于 32 位系统）和 Windows 10 版本 1703（用于基于 x64 的系统）添加到了受影响的软件表。Microsoft 建议运行 Windows 10 版本 1703 的客户应安装更新 4025342，以防止受到此漏洞影响。

*页面生成时间：2017-07-03 16:05-07:00。*
