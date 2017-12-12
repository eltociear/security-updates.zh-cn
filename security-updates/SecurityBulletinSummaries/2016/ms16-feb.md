---
TOCTitle: 'MS16-FEB'
Title: 'Microsoft 安全公告摘要（2016 年 2 月）'
ms:assetid: 'ms16-feb'
ms:contentKeyID: 72239020
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms16-feb(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2016 年 2 月）
======================================

发布日期：2016 年 2 月 9 日 | 更新时间：2016 年 2 月 24 日

**版本：** 3.1

本公告摘要列出了 2016 年 2 月发布的安全公告。

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
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-009">MS16-009</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积安全更新程序 (3134220)</strong> <br />
此安全更新程序修复了 Internet Explorer 中的多个漏洞。如果用户使用 Internet Explorer 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，则成功利用此漏洞的攻击者可以控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3134814">3134814</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-011">MS16-011</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 的累积安全更新 (3134225)<br />
</strong>此安全更新可修复 Microsoft Edge 中的漏洞。如果用户使用 Microsoft Edge 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-012">MS16-012</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Microsoft Windows PDF 库安全更新程序 (3138938)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。如果 Microsoft Windows PDF 库处理应用程序编程接口 (API) 调用不当，那么其中较为严重的漏洞可能允许远程执行代码，允许攻击者在用户系统上运行任意代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。不过，攻击者无法强迫用户下载或打开恶意 PDF 文档。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-013">MS16-013</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Windows 日记本安全更新程序 (3134811)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果用户打开经特殊设计的日记文件，那么此漏洞可能允许远程执行代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-014">MS16-014</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Microsoft Windows 安全更新程序 (3134228)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的多个漏洞。如果攻击者可以登录目标系统并运行经特殊设计的应用程序，那么这些漏洞中最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3126041">3126041</a><br />
<a href="https://support.microsoft.com/zh-cn/kb/3126587">3126587</a><br />
<a href="https://support.microsoft.com/zh-cn/kb/3126593">3126593</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-015">MS16-015</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Microsoft Office 安全更新程序 (3134226)</strong><br />
此安全更新程序修复了 Microsoft Office 中的多个漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么这些漏洞中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web Apps、<br />
Microsoft Server 软件</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-016">MS16-016</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复特权提升漏洞的 WebDAV 安全更新程序 (3136041)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果攻击者使用 Microsoft Web 分布式创作和版本管理 (WebDAV) 客户端向服务器发送经特殊设计的输入，那么此漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-017">MS16-017</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复特权提升漏洞的远程桌面显示驱动程序安全更新程序 (3134700)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果已经过身份验证的攻击者使用 RDP 登录目标系统并通过连接发送经特殊设计的数据，那么此漏洞可能允许特权提升。默认情况下，在所有 Windows 操作系统上，RDP 均处于未启用状态。未启用 RDP 的系统均不存在这一风险。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3134700">3134700</a><br />
<a href="https://support.microsoft.com/zh-cn/kb/3126446">3126446</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-018">MS16-018</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复特权提升漏洞的 Windows 内核模式驱动程序安全更新程序 (3136082)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果攻击者登录受影响的系统并运行特制应用程序，此漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-019">MS16-019</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复拒绝服务漏洞的 .NET Framework 安全更新程序 (3137893)<br />
</strong>此安全更新可解决 Microsoft .NET Framework 中的漏洞。如果攻击者向客户端 XML Web 部件植入特定的 XSLT，这些漏洞更严重的可能会使服务器递归编译 XSLT 转换，导致服务器拒绝服务。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-020">MS16-020</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复拒绝服务漏洞的 Active Directory 联合身份验证服务的安全更新程序 (3134222)<br />
</strong>此安全更新可解决 Active Directory 联合身份验证服务 (ADFS) 中的一个漏洞。如果攻击者在基于窗体的身份验证时发送特定的输入数据到 ADFS 服务器，此漏洞可能会引起拒绝服务，导致服务器无法响应。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-021">MS16-021</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复拒绝服务漏洞的 NPS RADIUS 服务器安全更新程序 (3133043)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。如果攻击者将经特殊设计的用户名字符串发送到 NPS，则该漏洞可能会导致网络策略服务器 (NPS) 拒绝服务，进而拒绝 NPS 上的 RADIUS 身份验证。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-022">MS16-022</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 的安全更新 (3135782)<br />
</strong>此安全更新可修复安装在所有受支持版本的 Windows Server 2012、Windows 8.1、Windows Server 2012 R2、 Windows RT 8.1 以及 Windows 10 上的 Adobe Flash Player 漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows<br />
Adobe Flash Player</p></td>
</tr>
</tbody>
</table>
<p></p>

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
<td style="border:1px solid black;" colspan="2">
**最新软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**较旧软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-009：Internet Explorer 累积安全更新 (3134220)**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0041](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)

</td>
<td style="border:1px solid black;">
DLL 加载远程执行代码漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0059](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0059)

</td>
<td style="border:1px solid black;">
Internet Explorer 信息泄漏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0063](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0063)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0064](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0064)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0067](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0067)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0068](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0068)

</td>
<td style="border:1px solid black;">
Internet Explorer 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0069](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0069)

</td>
<td style="border:1px solid black;">
Internet Explorer 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0071](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0071)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0072](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0072)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-011：Microsoft Edge 累积安全更新程序 (3134225)**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0080)

</td>
<td style="border:1px solid black;">
Microsoft Edge ASLR 规避

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0084)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-012：用于修复远程执行代码漏洞的 Microsoft Windows PDF 库安全更新程序 (3138938)**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0046](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0046)

</td>
<td style="border:1px solid black;">
Microsoft Windows 阅读器漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0058](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0058)

</td>
<td style="border:1px solid black;">
Microsoft PDF 库缓冲区溢出漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-013：用于修复远程执行代码漏洞的 Windows 日记本安全更新程序 (3134811)**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0038](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0038)

</td>
<td style="border:1px solid black;">
Windows 日记本内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-014：用于修复远程执行代码漏洞的 Microsoft Windows 安全更新程序 (3134228)**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0040](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0040)

</td>
<td style="border:1px solid black;">
Windows 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0041](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)

</td>
<td style="border:1px solid black;">
DLL 加载远程执行代码漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0042](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0042)

</td>
<td style="border:1px solid black;">
Windows DLL 加载远程执行代码漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0044](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0044)

</td>
<td style="border:1px solid black;">
Windows DLL 加载拒绝服务漏洞

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0049](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0049)

</td>
<td style="border:1px solid black;">
Windows Kerberos 绕过安全功能

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-015：用于修复远程执行代码漏洞的 Microsoft Office 安全更新程序 (3134226)**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0022](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0022)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0039](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0039)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint XSS 漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0052](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0052)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0053](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0053)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0054](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0054)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0055](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0055)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0056](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0056)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-016：用于修复特权提升漏洞的 WebDAV 安全更新程序 (3136041)**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0051](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0051)

</td>
<td style="border:1px solid black;">
WebDAV 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-017：用于修复特权提升漏洞的远程桌面显示驱动程序安全更新程序 (3134700)**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0036](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0036)

</td>
<td style="border:1px solid black;">
远程桌面协议 (RDP) 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-018：用于修复特权提升漏洞的 Windows 内核模式驱动程序安全更新程序 (3136082)**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0048](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0048)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-019：用于修复拒绝服务漏洞的 .NET Framework 安全更新程序 (3137893)**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0033)

</td>
<td style="border:1px solid black;">
.NET Framework 堆栈溢出拒绝服务漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;">
[CVE-2016-0047](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0047)

</td>
<td style="border:1px solid black;">
Windows 窗体信息泄露漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-020：用于修复拒绝服务漏洞的 Active Directory 联合身份验证服务的安全更新程序 (3134222)**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0037)

</td>
<td style="border:1px solid black;">
Microsoft Active Directory 联合身份验证服务拒绝服务漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-021：用于修复拒绝服务漏洞的 NPS RADIUS 服务器安全更新程序 (3133043)**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0050](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0050)

</td>
<td style="border:1px solid black;">
网络策略服务器 RADIUS 实施拒绝服务漏洞

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-022：Adobe Flash Player 安全更新程序 (3135782)**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-04](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-04.html)

</td>
<td style="border:1px solid black;">
参阅 [Adobe 安全公告 APSB16-04](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-04.html)，了解漏洞严重性级别和更新优先级级别。

</td>
<td style="border:1px solid black;" colspan="2">
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
[**MS16-009**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

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
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
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
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3126587)  
（重要）  
Windows Vista Service Pack 2  
(3126593)  
（重要）  
Windows Vista Service Pack 2  
(3126041)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3124280)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
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
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3126587)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3126593)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3126041)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3124280)  
（重要）

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
[**MS16-009**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

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
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3126587)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3126593)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3126041)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3124280)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3126587)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3126593)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3126041)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3124280)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3126587)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3126593)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3126041)  
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
[**MS16-009**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

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
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3126587)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3126593)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3124280)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3126587)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3126593)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3124280)  
（重要）

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
[**MS16-009**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

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
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3126587)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3126593)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3124280)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3126587)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3126593)  
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
[**MS16-009**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

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
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3123294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3126587)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3126593)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3126041)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3126434)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3124280)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3123294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3126587)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3126593)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3126041)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3126434)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3124280)  
（中等）

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
[**MS16-009**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

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
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Internet Explorer 10  
(3134814)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3123294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3126587)  
（重要）  
Windows Server 2012  
(3126593)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3124280)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3123294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3115858)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126587)  
（重要）  
Windows Server 2012 R2  
(3126593)  
（重要）  
Windows Server 2012 R2  
(3126041)  
（重要）  
Windows Server 2012 R2  
(3126434)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3124280)  
（中等）

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
[**MS16-009**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

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
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
(3126587)  
（重要）  
Windows RT 8.1  
(3126593)  
（重要）  
Windows RT 8.1  
(3126434)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3124280)  
（中等）

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
[**MS16-009**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

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
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3135174)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3135174)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3135174)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3135174)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3135174)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3135174)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3135174)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3135174)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3135173)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3135173)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3135173)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3135173)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3135173)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3135173)  
（中等）

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
[**MS16-009**](https://technet.microsoft.com/zh-cn/library/security/ms16-009)

</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/zh-cn/library/security/ms16-011)

</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/zh-cn/library/security/ms16-012)

</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/zh-cn/library/security/ms16-013)

</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/zh-cn/library/security/ms16-014)

</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/zh-cn/library/security/ms16-016)

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
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3126587)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3126593)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3126041)  
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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3126587)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3126593)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3126041)  
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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3126587)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3126593)  
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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3126587)  
（重要）  
Windows Server 2012（服务器核心安装）  
(3126593)  
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
(3123294)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3126587)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(3126593)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(3126041)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

 

### Windows 操作系统和组件（表 2-2）

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
[**MS16-017**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

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
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122656)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127229)  
（重要）  
Microsoft .NET Framework 4.6  
(3122661)  
（重要）  
Microsoft .NET Framework 4.6  
(3127233)  
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
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122656)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127229)  
（重要）  
Microsoft .NET Framework 4.6  
(3122661)  
（重要）  
Microsoft .NET Framework 4.6  
(3127233)  
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
[**MS16-017**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122656)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127229)  
（重要）  
Microsoft .NET Framework 4.6  
(3122661)  
（重要）  
Microsoft .NET Framework 4.6  
(3127233)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3133043)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122656)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127229)  
（重要）  
Microsoft .NET Framework 4.6  
(3122661)  
（重要）  
Microsoft .NET Framework 4.6  
(3127233)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3133043)  
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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
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
[**MS16-017**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

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
<td style="border:1px solid black;">
**无**

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
Windows 7（用于 32 位系统）Service Pack 1  
(3126446)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3127220)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122656)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127229)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3126446)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3127220)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122656)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127229)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
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
[**MS16-017**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3127220)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122656)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127229)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3133043)  
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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3127220)  
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
[**MS16-017**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

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
<td style="border:1px solid black;">
**无**

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
Windows 8.1（用于 32 位系统）  
(3126446)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
（重要）  
Microsoft .NET Framework 3.5  
(3127222)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122654)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127226)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3126446)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
（重要）  
Microsoft .NET Framework 3.5  
(3127222)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122654)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127226)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
（严重）

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
[**MS16-017**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

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
Windows Server 2012  
(3126446)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122649)  
（重要）  
Microsoft .NET Framework 3.5  
(3127221)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122655)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127227)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3133043)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126446)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
（重要）  
Microsoft .NET Framework 3.5  
(3127222)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122654)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127226)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
（重要）

</td>
<td style="border:1px solid black;">
Active Directory 联合身份验证服务 3.0  
(3134222)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3133043)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
（严重）

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
[**MS16-017**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

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
<td style="border:1px solid black;">
**无**

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
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3122654)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127226)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
（严重）

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
[**MS16-017**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

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
<td style="border:1px solid black;">
**无**

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
Windows 10（用于 32 位系统）  
(3135174)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3135174)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135174)  
（重要）  
Microsoft .NET Framework 4.6  
(3135174)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3135174)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3135174)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135174)  
（重要）  
Microsoft .NET Framework 4.6  
(3135174)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
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
(3135173)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135173)  
（重要）  
Microsoft .NET Framework 4.6.1  
(3135173)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
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
(3135173)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135173)  
（重要）  
Microsoft .NET Framework 4.6.1  
(3135173)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
（严重）

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
[**MS16-017**](https://technet.microsoft.com/zh-cn/library/security/ms16-017)

</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/zh-cn/library/security/ms16-018)

</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/zh-cn/library/security/ms16-019)

</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/zh-cn/library/security/ms16-020)

</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/zh-cn/library/security/ms16-021)

</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/zh-cn/library/security/ms16-022)

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
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3134214)  
（重要）

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
(3133043)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3134214)  
（重要）

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
(3133043)  
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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3127220)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122656)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127229)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3133043)  
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
Windows Server 2012（服务器核心安装）  
(3126446)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122649)  
（重要）  
Microsoft .NET Framework 3.5  
(3127221)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122655)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127227)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3133043)  
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
Windows Server 2012 R2（服务器核心安装）  
(3126446)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3134214)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
（重要）  
Microsoft .NET Framework 3.5  
(3127222)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3122654)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3127226)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
（重要）

</td>
<td style="border:1px solid black;">
Active Directory 联合身份验证服务 3.0  
(3134222)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3133043)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

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
Microsoft Office 2007 Service Pack 3  
(3114742)  
（重要）  
Microsoft Excel 2007 Service Pack 3  
(3114741)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3114748)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

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
(3114752)  
（重要）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3114759)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3114755)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3114752)  
（重要）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3114759)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3114755)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

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
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(3114734)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3114724)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(3114734)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3114724)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

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
Microsoft Excel 2013 RT Service Pack 1  
(3114734)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(3114724)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

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
Microsoft Excel 2016（32 位版本）  
(3114698)  
（重要）  
Microsoft Word 2016（32 位版本）  
(3114702)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016（64 位版本）  
(3114698)  
（重要）  
Microsoft Word 2016（64 位版本）  
(3114702)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

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
Microsoft Excel for Mac 2011  
(3137721)  
（重要）  
Microsoft Word for Mac 2011  
(3137721)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3134241)  
（重要）  
Microsoft Word 2016 for Mac  
(3134241)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

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
Microsoft Office 兼容包 Service Pack 3  
(3114548)  
（重要）  
Microsoft Office 兼容包 Service Pack 3  
(3114745)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114747)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114773)  
（重要）

</td>
</tr>
</table>

**MS16-015 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）

</td>
<td style="border:1px solid black;">
Excel Services  
(3114432)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）

</td>
<td style="border:1px solid black;">
Excel Services  
(3114432)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3114401)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Excel Services  
(3114335)  
（重要）  
Word Automation Services  
(3114481)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3114407)  
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3114338)  
（重要）

</td>
</tr>
</table>

**MS16-015 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft Server 软件

<p> </p>

<table style="border:1px solid black;">
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
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3039768)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/zh-cn/library/security/ms16-015)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

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
(3114733)  
（重要）

</td>
</tr>
</table>

**MS16-015 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

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
Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn903755.aspx)部分。

其他信息
--------

<span id="sectionToggle5"></span>
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

面向 IT 专业人员的安全解决方案：[TechNet 安全疑难解答和支持](http://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

基于国家/地区的本地支持：[国际支持](http://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定用途的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2016 年 2 月 9 日）：已发布公告摘要。
-   V2.0（2016 年 2 月 10 日）：对于 MS16-014，公告经过修订，宣布发布适用于 Microsoft Windows Vista、Windows Server 2008、Windows Server 2008（用于基于 Itanium 的系统）、Windows 8.1 和 Windows Server 2012 R2 的更新 3126041。客户应应用适用的更新以免受此公告中讨论的漏洞攻击。大多数客户均启用了“自动更新”，他们不必采取任何操作，因为更新将自动下载并安装。对于 MS16-021，更正了 CVE-2016-0050 的利用评估。
-   V3.0（2016 年 2 月 16 日）：对于 MS16-015，截止到 2016 年 2 月 16 日，已推出适用于 Microsoft Office 2016 for Mac 的 3134241 更新以及适用于 Microsoft Office for Mac 2011 的 3137721 更新。有关详细信息，请参阅 [Microsoft 知识库文章 3134241](https://support.microsoft.com/zh-cn/kb/3134241) 和 [Microsoft 知识库文章 3137721](https://support.microsoft.com/zh-cn/kb/3137721)。
-   V3.1（2016 年 2 月 24 日）：向 MS16-014 的“执行摘要”表添加了已知问题的引用。有关详细信息，请参阅 [Microsoft 知识库文章 3126041](https://support.microsoft.com/zh-cn/kb/3126041)。另请注意,已向 [Microsoft 知识库文章 3126587](https://support.microsoft.com/zh-cn/kb/3126587) 添加了包含变通办法的第二个已知问题。

*页面生成时间：2016-02-24 13:45-08:00。*
