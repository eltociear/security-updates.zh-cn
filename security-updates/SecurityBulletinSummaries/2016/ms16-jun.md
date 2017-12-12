---
TOCTitle: 'MS16-JUN'
Title: 'Microsoft 安全公告摘要（2016 年 6 月）'
ms:assetid: 'ms16-jun'
ms:contentKeyID: 73145348
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms16-jun(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2016 年 6 月）
======================================

发布时间：2016 年 6 月 14 日 | 更新时间：2016 年 6 月 16 日

**版本：** 2.0

本公告摘要列出了 2016 年 6 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

执行摘要
--------

<span id="sectionToggle0"></span>
下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

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
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-063">MS16-063</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新 (3163649)<br />
</strong>此安全更新程序修复了 Internet Explorer 中的多个漏洞。如果用户使用 Internet Explorer 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，那么攻击者便可控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-068">MS16-068</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 的累积安全更新 (3163656)<br />
</strong>此安全更新可修复 Microsoft Edge 中的漏洞。如果用户使用 Microsoft Edge 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-069">MS16-069</a></p></td>
<td style="border:1px solid black;"><p><strong>JScript 和 VBScript 的累积安全更新 (3163640)<br />
</strong>此安全更新可解决 Microsoft Windows 的 JScript 和 VBScript 脚本引擎中的漏洞。如果用户访问经特殊设计的网站，那么此漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，则成功利用这些漏洞的攻击者可以控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-070">MS16-070</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 安全更新 (3163610)<br />
</strong>此安全更新可解决 Microsoft Office 中的漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么这些漏洞中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web Apps</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-071">MS16-071</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows DNS 服务器安全更新 (3164065)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果攻击者向 DNS 服务器发送经特殊设计的请求，此漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-072">MS16-072</a></p></td>
<td style="border:1px solid black;"><p><strong>组策略安全更新 (3163622)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果攻击者对域控制器与目标计算机之间的流量启动中间人 (MiTM) 攻击，漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="http://support.microsoft.com/kb/3159398">3159398</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-073">MS16-073</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序安全更新 (3164028)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的多个漏洞。如果攻击者登录受影响的系统并运行经特殊设计的应用程序，最严重的漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-074">MS16-074</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 图形组件安全更新 (3164036)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的多个漏洞。如果用户打开经特殊设计的应用程序，最严重的漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-075">MS16-075</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows SMB 服务器安全更新 (3164038)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果攻击者登录系统并运行经特殊设计的应用程序，则该漏洞可能允许提升特权。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-076">MS16-076</a></p></td>
<td style="border:1px solid black;"><p><strong>Netlogon 安全更新 (3167691)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果有权访问目标网络上的域控制器 (DC) 的攻击者运行经特殊设计的应用程序与作为副本域控制器的 DC 建立安全通道，漏洞可能允许远程代码执行。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-077">MS16-077</a></p></td>
<td style="border:1px solid black;"><p><strong>WPAD 安全更新 (3165191)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的多个漏洞。如果 Web 代理自动发现 (WPAD) 协议回退到目标系统上的易受攻击的代理发现进程，该漏洞可能会允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-078">MS16-078</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 诊断中心安全更新 (3165479)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果攻击者登录受影响的系统并运行经特殊设计的应用程序，此漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-063">MS16-079</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Exchange Server 安全更新 (3160339)<br />
</strong>此安全更新程序可修复 Microsoft Exchange Server 中的多个漏洞。如果攻击者在 Outlook Web Access (OWA) 邮件中发送从攻击者控制的 URL 加载的（在未警告或筛选的情况下）经特殊设计的图像 URL，最严重的漏洞可能允许信息泄漏。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Exchange Server</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-080">MS16-080</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows PDF 安全更新 (3164302)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的多个漏洞。如果用户打开经特殊设计的 .pdf 文件，较严重的漏洞可能允许远程代码执行。成功利用此漏洞的攻击者可以在当前用户的上下文中执行任意代码。但攻击者无法强迫用户打开经特殊设计的 .pdf 文件。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-081">MS16-081</a></p></td>
<td style="border:1px solid black;"><p><strong>Active Directory 安全更新 (3160352)<br />
</strong>此安全更新可修复 Active Directory 中的漏洞。如果已经过身份验证的攻击者创建多个计算机帐户，则此漏洞可能允许拒绝服务。若要利用此漏洞，攻击者必须具有有权将计算机加入域的帐户。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-082">MS16-082</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows 搜索组件安全更新 (3165270)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。此漏洞在攻击者登录目标系统并运行经特殊设计的应用程序时允许提升特权。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-083">MS16-083</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 安全更新 (3167685)<br />
</strong>此安全更新可修复安装在 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10 的所有受支持版本上的 Adobe Flash Player 的漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows<br />
Adobe Flash Player</p></td>
</tr>
</tbody>
</table>  
<p> </p>



利用指数
--------

<span id="sectionToggle1"></span>
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。

**如何使用该表？**

对于您可能需要安装的每个安全更新，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/zh-cn/security/cc998259)。

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
**较低的软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**较低的软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-063：Internet Explorer 累积安全更新 (3163649)**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0199)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

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
[CVE-2016-0200](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0200)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

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
[CVE-2016-3202](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3202)

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
[CVE-2016-3205](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3205)

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
<td style="border:1px solid black;">
[CVE-2016-3206](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3206)

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
<td style="border:1px solid black;">
[CVE-2016-3207](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3207)

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
<td style="border:1px solid black;">
[CVE-2016-3210](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3210)

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
<td style="border:1px solid black;">
[CVE-2016-3211](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3211)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

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
[CVE-2016-3212](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3212)

</td>
<td style="border:1px solid black;">
Internet Explorer XSS 筛选器漏洞

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
[CVE-2016-3213](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3213)

</td>
<td style="border:1px solid black;">
WPAD 特权提升漏洞

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
[**MS16-068：Microsoft Edge 累积安全更新 (3163656)**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3198](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3198)

</td>
<td style="border:1px solid black;">
Microsoft Edge 安全功能绕过

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
[CVE-2016-3199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3199)

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
[CVE-2016-3201](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3201)

</td>
<td style="border:1px solid black;">
Windows PDF 信息泄漏漏洞

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
[CVE-2016-3202](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3202)

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
[CVE-2016-3203](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3203)

</td>
<td style="border:1px solid black;">
Windows PDF 远程代码执行漏洞

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
[CVE-2016-3214](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3214)

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
[CVE-2016-3215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3215)

</td>
<td style="border:1px solid black;">
Windows PDF 信息泄漏漏洞

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
[CVE-2016-3222](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3222)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-069：JScript 和 VBScript 累积安全更新 (3163640)**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3205](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3205)

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
<td style="border:1px solid black;">
[CVE-2016-3206](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3206)

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
<td style="border:1px solid black;">
[CVE-2016-3207](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3207)

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
[**MS16-070：Microsoft Office 安全更新 (3163610)**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0025](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0025)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

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
[CVE-2016-3233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3233)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

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
[CVE-2016-3234](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3234)

</td>
<td style="border:1px solid black;">
Microsoft Office 信息泄漏漏洞

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
[CVE-2016-3235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3235)

</td>
<td style="border:1px solid black;">
Microsoft Office OLE DLL 侧面加载漏洞

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
[**MS16-071：Microsoft Windows DNS 服务器安全更新 (3164065)**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3227](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3227)

</td>
<td style="border:1px solid black;">
Windows DNS 服务器释放后使用漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-072：组策略安全更新 (3163622)**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3223](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3223)

</td>
<td style="border:1px solid black;">
组策略特权提升漏洞

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
[**MS16-073：Windows 内核模式驱动程序安全更新 (3164028)**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3218](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3218)

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
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3221](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3221)

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
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3232)

</td>
<td style="border:1px solid black;">
Windows Virtual PCI 信息泄漏漏洞

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
<td style="border:1px solid black;" colspan="5">
[**MS16-074：Microsoft 图形组件安全更新 (3164036)**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3216](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3216)

</td>
<td style="border:1px solid black;">
Windows 图形组件信息泄漏漏洞

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
[CVE-2016-3219](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3219)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

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
[CVE-2016-3220](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3220)

</td>
<td style="border:1px solid black;">
ATMFD.DLL 特权提升漏洞

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
[**MS16-075：Windows SMB 服务器安全更新 (3164038)**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3225](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3225)

</td>
<td style="border:1px solid black;">
Windows SMB 服务器特权提升漏洞

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
[**MS16-076：Netlogon 安全更新 (3167691)**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3228](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3228)

</td>
<td style="border:1px solid black;">
Windows Netlogon 内存损坏远程代码执行漏洞

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
<td style="border:1px solid black;" colspan="5">
[**MS16-077：WPAD 安全更新 (3165191)**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3213](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3213)

</td>
<td style="border:1px solid black;">
Windows WPAD 特权提升漏洞

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
[CVE-2016-3236](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3236)

</td>
<td style="border:1px solid black;">
Windows WPAD 代理发现特权提升漏洞

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
[**MS16-078：Windows 诊断中心安全更新 (3165479)**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3231)

</td>
<td style="border:1px solid black;">
Windows 诊断中心特权提升漏洞

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
[**MS16-079：Microsoft Exchange Server 安全更新 (3160339)**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0028](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0028)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-080：Microsoft Windows PDF 安全更新 (3164302)**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3201](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3201)

</td>
<td style="border:1px solid black;">
Windows PDF 信息泄漏漏洞

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
[CVE-2016-3203](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3203)

</td>
<td style="border:1px solid black;">
Windows PDF 远程代码执行漏洞

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
[CVE-2016-3215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3215)

</td>
<td style="border:1px solid black;">
Windows PDF 信息泄漏漏洞

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
[**MS16-081：Active Directory 安全更新 (3160352)**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3226](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3226)

</td>
<td style="border:1px solid black;">
Active Directory 拒绝服务漏洞

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
[**MS16-082：Microsoft Windows 搜索组件安全更新 (3165270)**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3230](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3230)

</td>
<td style="border:1px solid black;">
Windows 搜索组件拒绝服务漏洞

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
[**MS16-083：Adobe Flash Player 安全更新 (3167685)**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-18](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-18.html)

</td>
<td style="border:1px solid black;">
有关漏洞严重性级别和更新优先级级别，请参阅 [Adobe 安全公告 APSB16-18](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-18.html)。

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

<span id="sectionToggle2"></span>
下表按主要软件类别和严重性的排序列出了公告。

通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。

**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

 

### Windows 操作系统和组件（表 1-2）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

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
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3160005)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158364)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3164033)  
（重要）  
Windows Vista Service Pack 2  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3160005)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158364)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3164033)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

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
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3160005)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158364)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3164033)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3160005)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158364)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3164033)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3161561)  
（重要）

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
VBScript 5.7  
(3158364)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3164033)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
（严重）

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
Windows 7（用于 32 位系统）Service Pack 1  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3164033)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
（严重）

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
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3164033)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

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
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
（中等）

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3164033)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3161561)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3164033)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
（严重）

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
Windows 8.1（用于 32 位系统）  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3164033)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
（严重）

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
Windows 8.1（用于基于 x64 的系统）  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3164033)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3160005)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161951)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161664)  
（重要）  
Windows Server 2012  
(3164294)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3164033)  
（重要）  
Windows Server 2012  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161951)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161664)  
（重要）  
Windows Server 2012 R2  
(3164294)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3164033)  
（重要）  
Windows Server 2012 R2  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
（严重）

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
Windows RT 8.1  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3164033)  
（重要）  
Windows RT 8.1  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3161561)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163017)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163017)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163017)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163017)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163017)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163017)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163018)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163018)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3163018)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163018)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163018)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3163018)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-063**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
<td style="border:1px solid black;">
[**MS16-068**](https://technet.microsoft.com/zh-cn/library/security/ms16-068)

</td>
<td style="border:1px solid black;">
[**MS16-069**](https://technet.microsoft.com/zh-cn/library/security/ms16-069)

</td>
<td style="border:1px solid black;">
[**MS16-071**](https://technet.microsoft.com/zh-cn/library/security/ms16-071)

</td>
<td style="border:1px solid black;">
[**MS16-072**](https://technet.microsoft.com/zh-cn/library/security/ms16-072)

</td>
<td style="border:1px solid black;">
[**MS16-073**](https://technet.microsoft.com/zh-cn/library/security/ms16-073)

</td>
<td style="border:1px solid black;">
[**MS16-074**](https://technet.microsoft.com/zh-cn/library/security/ms16-074)

</td>
<td style="border:1px solid black;">
[**MS16-075**](https://technet.microsoft.com/zh-cn/library/security/ms16-075)

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
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
VBScript 5.7  
(3158364)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3164033)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3161561)  
（重要）

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
VBScript 5.7  
(3158364)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3164033)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3161561)  
（重要）

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
JScript 5.8 和 VBScript 5.8  
(3158363)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3161664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3164033)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3161561)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3161951)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3161664)  
（重要）  
Windows Server 2012（服务器核心安装）  
(3164294)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3164033)  
（重要）  
Windows Server 2012（服务器核心安装）  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3161561)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3161951)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3159398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3161664)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(3164294)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3164033)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(3164035)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3161561)  
（重要）

</td>
</tr>
</table>

 

### Windows 操作系统和组件（表 2-2）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-cn/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

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
(3161949)  
（重要）

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
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3161949)  
（重要）

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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-cn/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3161561)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3161949)  
（重要）

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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3161561)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3161949)  
（重要）

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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3161561)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3161949)  
（重要）

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
<td style="border:1px solid black;" colspan="8">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-cn/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3161949)  
（重要）

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
Windows 7（用于 32 位系统）Service Pack 1  
(3161958)  
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
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3161949)  
（重要）

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
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3161958)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-cn/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3161561)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3161949)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3160352)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3161958)  
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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3161561)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3161949)  
（重要）

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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3161958)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-cn/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3161949)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3157569)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3161958)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
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
(3161949)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3157569)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3161958)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-cn/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161561)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161949)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3157569)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3160352)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161958)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3162343)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161949)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3157569)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3160352)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161958)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-cn/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3161949)  
（重要）

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
Windows RT 8.1  
(3161958)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-cn/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
（严重）

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
Windows 10（用于基于 x64 的系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163017)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3163018)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-076**](https://technet.microsoft.com/zh-cn/library/security/ms16-076)

</td>
<td style="border:1px solid black;">
[**MS16-077**](https://technet.microsoft.com/zh-cn/library/security/ms16-077)

</td>
<td style="border:1px solid black;">
[**MS16-078**](https://technet.microsoft.com/zh-cn/library/security/ms16-078)

</td>
<td style="border:1px solid black;">
[**MS16-080**](https://technet.microsoft.com/zh-cn/library/security/ms16-080)

</td>
<td style="border:1px solid black;">
[**MS16-081**](https://technet.microsoft.com/zh-cn/library/security/ms16-081)

</td>
<td style="border:1px solid black;">
[**MS16-082**](https://technet.microsoft.com/zh-cn/library/security/ms16-082)

</td>
<td style="border:1px solid black;">
[**MS16-083**](https://technet.microsoft.com/zh-cn/library/security/ms16-083)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3161949)  
（重要）

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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3161949)  
（重要）

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3161949)  
（重要）

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
(3160352)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3161958)  
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
Windows Server 2012  
（服务器核心安装）  
(3161561)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3161949)  
（重要）

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
(3160352)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3161958)  
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
Windows Server 2012 R2  
（服务器核心安装）  
(3162343)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3161949)  
（重要）

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
(3160352)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3161958)  
（重要）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

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
Microsoft Excel 2007 Service Pack 3  
(3115107)  
（重要）  
Microsoft Visio 2007 Service Pack 3  
(3114740)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3115195)  
（严重）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

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
(3115198)  
（严重）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3115130)  
（重要）  
Microsoft Visio 2010 Service Pack 2（32 位版本）  
(3114872)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3115243)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3115198)  
（严重）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3115130)  
（重要）  
Microsoft Visio 2010 Service Pack 2（64 位版本）  
(3114872)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3115243)  
（严重）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

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
Microsoft Visio 2013 Service Pack 1（32 位版本）  
(3115020)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3115173)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Visio 2013 Service Pack 1（64 位版本）  
(3115020)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3115173)  
（严重）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

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
Microsoft Word 2013 RT Service Pack 1  
(3115173)  
（严重）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

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
Microsoft Office 2016（32 位版本）  
(3115144)  
（重要）  
Microsoft Visio 2016（32 位版本）  
(3115041)  
（重要）  
Microsoft Word 2016（32 位版本）  
(3115182)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）  
(3115144)  
（重要）  
Microsoft Visio 2016（64 位版本）  
(3115041)  
（重要）  
Microsoft Word 2016（64 位版本）  
(3115182)  
（严重）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3165796)  
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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3165798)  
（严重）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(3115111)  
（重要）  
Microsoft Office 兼容包 Service Pack 3  
(3115194)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2007 Service Pack 3  
(2596915)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010（32 位版本）  
(2999465)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010（64 位版本）  
(2999465)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115187)  
（重要）

</td>
</tr>
</table>

**MS16-070 注释**

此公告涉及多个软件类别。有关其他受影响的软件，请参阅本节中的其他表。

### Microsoft Office Services 和 Web Apps

<p> </p>

<table style="border:1px solid black;">
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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3115196)  
（重要）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3115014)  
（重要）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3115244)  
（重要）

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
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3115170)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Office Online Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-070**](https://technet.microsoft.com/zh-cn/library/security/ms16-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3115134)  
（重要）

</td>
</tr>
</table>

**MS16-070 注释**

此公告涉及多个软件类别。有关其他受影响的软件，请参阅本节中的其他表。

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
[**MS16-079**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(3151086)  
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
[**MS16-079**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(3151097)  
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
[**MS16-079**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3150501)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 11

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 11  
(3150501)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 12

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 12  
(3150501)  
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
[**MS16-079**](https://technet.microsoft.com/zh-cn/library/security/ms16-063)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016  
(3150501)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累积更新 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累积更新 1  
(3150501)  
（重要）

</td>
</tr>
</table>

检测和部署工具及指导
--------------------

<span id="sectionToggle3"></span>
许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](http://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

<span id="sectionToggle4"></span>
Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/mt674627.aspx)部分。

其他信息
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为了让客户获得更多安全保护，Microsoft 在发布每月安全更新程序之前会向主要的安全软件提供商提供漏洞信息。然后，安全软件提供商可以使用此类漏洞信息通过其安全软件或设备（如防病毒、基于网络的入侵检测系统或基于主机的入侵防护系统）更新对客户提供的保护。若要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。若要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/zh-cn/lifecycle)。

面向 IT 专业人员的安全解决方案：[TechNet 安全故障排除和支持](http://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

基于国家/地区的本地支持：[国际支持](http://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不提供任何种类的明示或默示担保，包括对适销性和特定用途适用性的担保。在任何情况下，Microsoft Corporation 或其供应商都不会对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2016 年 6 月 14 日）：已发布公告摘要。
-   V1.1（2016 年 6 月 15 日）：对于 MS16-072，向“执行摘要”表中添加了已知问题。MS16-072 中的更新更改了用户组策略检索使用的安全上下文。有关这个特别设计的行为更改的更多信息，请参见 [Microsoft 知识库文章 3163622](https://support.microsoft.com/en-us/kb/3163622)。对于 MS16-074，修订了“执行摘要”，以修改攻击平台说明。这仅仅是一个信息方面的更改。
-   V2.0（2016 年 6 月 16 日）：修订了公告摘要，以便存档 MS16-083 的带外版本。

*页面生成时间：2016/6/16 10:24:00-07:00。*
