---
TOCTitle: 'MS13-DEC'
Title: 'Microsoft 安全公告摘要（2013 年 12 月）'
ms:assetid: 'ms13-dec'
ms:contentKeyID: 61236978
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms13-dec(v=Security.10)'
---

Microsoft 安全公告摘要（2013 年 12 月）
=======================================

发布日期： 2013 年 12 月 10 日

**版本：** 1.0

本公告摘要列出了 2013 年 12 月发布的安全公告。

对于 2013 年 12 月发布的安全公告，本公告摘要替代 2013 年 12 月 5 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2013 年 12 月 11 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 12 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557386&culture=en-us)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

摘要
----

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>公告标题和摘要</strong></p></td>
<td style="border:1px solid black;"><p><strong>最高严重等级和漏洞影响</strong></p></td>
<td style="border:1px solid black;"><p><strong>重新启动要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Graphics 组件中的漏洞可能允许远程执行代码 (2908005)</strong><br />
<br />
此安全更新可解决 Microsoft Windows、Microsoft Office 和 Microsoft Lync 中一个公开披露的漏洞 如果用户查看包含特制 TIFF 文件的内容，则该漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Microsoft Office，<br />
Microsoft Lync</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积性安全更新 (2898785)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中 7 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些最严重的漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 中的漏洞可能允许远程执行代码 Execution (2893294)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户或应用程序在受影响的系统上运行或安装特制的、经过签名的可移植可执行 （PE) 文件，则该漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 脚本运行时对象库中的漏洞可能允许远程执行代码 (2909158)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者诱使用户访问特制网站或者托管特制内容的网站，则此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Exchange Server 中的漏洞可能允许远程执行代码 (2915705)</strong><br />
<br />
此安全更新解决 Microsoft Exchange Server 中三个公开披露的漏洞和一个秘密报告的漏洞。Microsoft Exchange Server 的 WebReady Document Viewing 和数据丢失防护功能中存在最严重的漏洞。如果攻击者向受影响的 Exchange Server 中的用户发送包含特制文件的电子邮件，则这些漏洞可能允许在 LocalService 帐户的安全上下文中远程执行代码。LocalService 帐户在本地系统上具有最低特权，在网络上提供匿名凭据。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>无需重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Exchange</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft SharePoint Server 中的漏洞可能允许远程执行代码 (2904244)</strong><br />
<br />
此安全更新可解决 Microsoft Office 服务器软件中多个秘密报告的漏洞。如果经过身份验证的攻击者向 SharePoint 服务器发送特制网页内容，则这些漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以在目标 SharePoint 站点的 W3WP 服务帐户的安全上下文中运行任意代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft SharePoint</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升 (2880430)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中秘密报告的五个漏洞。如果攻击者登录某个系统并运行特制应用程序，更严重的漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 反恶意软件客户端中的漏洞可能允许特权提升 (2898715)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者欺骗 LRPC 服务器并向任何 LRPC 客户端发送特制 LPC 端口消息，则该漏洞可能允许特权提升。成功利用此漏洞的攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全管理员权限的新帐户。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></p></td>
<td style="border:1px solid black;"><p><strong>ASP.NET SignalR 中的漏洞可能允许特权提升 (2905244)</strong><br />
<br />
此安全更新可解决 ASP.NET SignalR 中一个秘密报告的漏洞。如果攻击者将特制 JavaScript 反映回目标用户的浏览器，则该漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>无需重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft 开发工具</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许信息泄露 (2909976)</strong><br />
<br />
此安全更新可解决 Microsoft Office 中一个秘密报告的漏洞，如果用户尝试打开恶意网站上托管的 Office 文件，则该漏洞可能允许信息泄露。成功利用此漏洞的攻击者可以确定用于在目标 SharePoint 或其他 Microsoft Office Server 站点上对当前用户进行身份验证的访问令牌。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄露</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 共享组件中的漏洞可能允许安全功能绕过绕过<br />
(2905238)</strong><br />  
<br />
此安全更新解决了 Microsoft Office 共享组件中目前正在被利用的一个公开披露的漏洞。如果用户在能够实例化 COM 组件（如 Internet Explorer）的 Web 浏览器中查看特制网页，则该漏洞可能允许安全功能绕过。在 Web 浏览攻击情形中，成功利用此漏洞的攻击者可能会绕过地址空间布局随机化 (ASLR) 安全功能，它有助于保护用户免遭多种漏洞。该安全功能绕过本身不允许执行任意代码。但是，攻击者可能会将此 ASLR 绕过漏洞与另一个漏洞（例如，可能利用 ASLR 绕过的远程执行代码漏洞）组合使用来运行任意代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
</tbody>  
</table>
  
 
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
<table style="width:100%;">  
<colgroup>  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
</colgroup>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>漏洞标题</strong></p></td>
<td style="border:1px solid black;"><p><strong>CVE ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>最新软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>重要注意事项</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Graphics 组件内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3906">CVE-2013-3906</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />
Microsoft 获悉尝试在 Microsoft Office 产品中利用此漏洞的目标攻击。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5045">CVE-2013-5045</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5046">CVE-2013-5046</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5047">CVE-2013-5047</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5048">CVE-2013-5048</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5049">CVE-2013-5049</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5051">CVE-2013-5051</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5052">CVE-2013-5052</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></p></td>
<td style="border:1px solid black;"><p>WinVerifyTrust 签名验证漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3900">CVE-2013-3900</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>Microsoft 获悉尝试使用此漏洞的目标攻击。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></p></td>
<td style="border:1px solid black;"><p>Microsoft 脚本运行时对象库中的释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5056">CVE-2013-5056</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></p></td>
<td style="border:1px solid black;"><p>SharePoint 页面内容漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5059">CVE-2013-5059</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></p></td>
<td style="border:1px solid black;"><p>Win32k 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3899">CVE-2013-3899</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></p></td>
<td style="border:1px solid black;"><p>Win32k 释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3902">CVE-2013-3902</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></p></td>
<td style="border:1px solid black;"><p>TrueType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3903">CVE-2013-3903</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></p></td>
<td style="border:1px solid black;"><p>端口类驱动程序双重提取漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3907">CVE-2013-3907</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></p></td>
<td style="border:1px solid black;"><p>Win32k 整数溢出漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5052">CVE-2013-5058</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个拒绝服务漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></p></td>
<td style="border:1px solid black;"><p>LRPC 客户端缓冲区溢出漏洞 </p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3878">CVE-2013-3878</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></p></td>
<td style="border:1px solid black;"><p>SignalR XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5042">CVE-2013-5042</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></p></td>
<td style="border:1px solid black;"><p>令牌劫持漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5054">CVE-2013-5054</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。<br />
<br />
Microsoft 获悉尝试使用此漏洞的有限目标攻击。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></p></td>
<td style="border:1px solid black;"><p>MAC 已禁用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1330">CVE-2013-1330</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></p></td>
<td style="border:1px solid black;"><p>Oracle Outside In 包含多个可利用的漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5763">CVE-2013-5763</a><br />
<br />  
和<br />  
<br />
<a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5791">CVE-2013-5791</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这些漏洞已被公开披露。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></p></td>
<td style="border:1px solid black;"><p>OWA XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5072">CVE-2013-5072</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></p></td>
<td style="border:1px solid black;"><p>HXDS ASLR 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5057">CVE-2013-5057</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能绕过漏洞。<br />
<br />  
此漏洞已公开披露。<br />  
<br />
Microsoft 获悉尝试使用此漏洞的有限目标攻击。</p></td>
</tr>
</tbody>
</table>


 

受影响的软件
------------

下表按主要软件类别和严重性的排序列出了公告。

**如何使用这些表？**

通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。

**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
（严重）  
Internet Explorer 7   
(2898785)  
（严重）  
Internet Explorer 8   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.7  
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2893984)  
（重要）

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2898715)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
（严重）  
Internet Explorer 7   
(2898785)  
（严重）  
Internet Explorer 8   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.6  
(2892076)  
（严重）  
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2893984)  
（重要）

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2898715)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
（中等）  
Internet Explorer 7  
(2898785)  
（重要）  
Internet Explorer 8  
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
（严重）  
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2893984)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2898715)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
（中等）  
Internet Explorer 7  
(2898785)  
（重要）  
Internet Explorer 8  
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
（严重）  
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2893984)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2898715)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
（中等）  
Internet Explorer 7  
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
（严重）  
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2893984)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2898715)  
（重要）

</td>
</tr>
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2  
(2901674)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
（严重）  
Internet Explorer 8  
(2898785)  
（严重）  
Internet Explorer 9   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2893984)  
（中等）  
Windows Vista Service Pack 2  
(2887069)  
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
Windows Vista x64 Edition Service Pack 2  
(2901674)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
（严重）  
Internet Explorer 8  
(2898785)  
（严重）  
Internet Explorer 9   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2893984)  
（中等）  
Windows Vista x64 Edition Service Pack 2  
(2887069)  
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(2901674)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
（重要）  
Internet Explorer 8  
(2898785)  
（重要）  
Internet Explorer 9   
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2893984)  
（中等）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2887069)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2901674)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
（重要）  
Internet Explorer 8  
(2898785)  
（重要）  
Internet Explorer 9   
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2893984)  
（中等）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2887069)  
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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2901674)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2893984)  
（中等）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2887069)  
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(2898785)  
（严重）  
Internet Explorer 9   
(2898785)  
（严重）  
Internet Explorer 10   
(2898785)  
（严重）  
Internet Explorer 11   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2893984)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(2887069)  
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
Internet Explorer 8  
(2898785)  
（严重）  
Internet Explorer 9   
(2898785)  
（严重）  
Internet Explorer 10   
(2898785)  
（严重）  
Internet Explorer 11   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2893984)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2887069)  
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(2898785)  
（重要）  
Internet Explorer 9   
(2898785)  
（重要）  
Internet Explorer 10   
(2898785)  
（重要）  
Internet Explorer 11   
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2893984)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2887069)  
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
Internet Explorer 8  
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2893984)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2887069)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2893984)  
（中等）  
Windows 8（用于 32 位系统）  
(2887069)  
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
不适用

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2893984)  
（中等）  
Windows 8（用于基于 x64 的系统）  
(2887069)  
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
不适用

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2893984)  
（中等）

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
不适用

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2893984)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

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
Internet Explorer 10   
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893984)  
（中等）  
Windows Server 2012  
(2887069)  
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
Internet Explorer 11   
(2898785)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893984)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 10   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(2893984)  
（中等）  
Windows RT  
(2887069)  
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
Internet Explorer 11   
(2898785)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893984)  
（中等）

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2901674)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2893984)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2901674)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2893984)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2893984)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2893984)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2893294)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2893984)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

**MS13-096 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Office 2003 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3 (2850047)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2817641)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2850022)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）  
(2817670)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）  
(2850016)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2817670)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2850016)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）  
(2817670)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）  
(2850016)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2817670)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2850016)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）  
(2850064)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）  
(2850064)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2850064)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2817641)  
（严重）

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
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2850047)  
（严重）

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
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2817641)  
（严重）

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
Microsoft PowerPoint 2010 Viewer Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 1  
(2817670)  
（严重）

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
Microsoft PowerPoint 2010 Viewer Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 2  
(2817670)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

**MS13-096 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (coreserverloc)  
(2850058)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2903911)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2  
(2903903)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2905616)  
（严重）

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
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 2  
(2880833)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 3  
(2880833)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

**MS13-100 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

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
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2553298)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2553298)  
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
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2837629)  
（重要）  
Excel Services  
(2837631)  
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
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2910228)  
（重要）

</td>
</tr>
</table>

**MS13-100 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft 通信平台和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）  
(2899397)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）  
(2899397)  
（重要）

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
(2899393)  
（重要）

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
(2899395)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 （32 位）  
(2850057)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 （32 位）  
(2850057)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 （64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 （64 位）  
(2850057)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013（64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013  
（64位）  
(2850057)  
（重要）

</td>
</tr>
</table>

**MS13-096 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**ASP.NET**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-103**](https://go.microsoft.com/fwlink/?linkid=329969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET SignalR

</td>
<td style="border:1px solid black;">
ASP.NET SignalR 1.1.x   
(2903919)  
（重要）  
ASP.NET SignalR 2.0.x   
(2903919)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Visual Studio Team Foundation Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS13-103**](https://go.microsoft.com/fwlink/?linkid=329969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2013   
(2903566)  
（重要）

</td>
</tr>
</table>

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

-   管理员可使用 Microsoft Baseline Security Analyzer (MBSA) 在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。
-   Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。
-   Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/security/cc297183)。 

鸣谢
----

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

**MS13-096**

-   McAfee Labs IPS Team 的 Haifei Li 报告了 Microsoft Graphics 组件内存损坏漏洞 (CVE-2013-3906)

**MS13-097**

-   Context Information Security 的 James Forshaw 报告了 Internet Explorer 特权提升漏洞 (CVE-2013-5045)
-   Context Information Security 的 James Forshaw 报告了 Internet Explorer 特权提升漏洞 (CVE-2013-5046)
-   [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-5047)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-5048)
-   Jose Antonio Vazquez Gonzalez 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-5049)
-   [OUSPG](https://www.ee.oulu.fi/research/ouspg/) 的 Atte Kettunen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-5051)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-5052)
-   Alex Inführ 与我们一起努力处理了此公告中包括的 Internet Explorer XSS 筛选器纵深防御更改

**MS13-098**

-   Kingsoft Internet Security Center @ [Kingsoft Internet Security Software Co.Ltd](https://www.ijinshan.com/) 的 Kingsoft Internet Security Center 报告了 WinVerifyTrust 签名验证漏洞 (CVE-2013-3900)

**MS13-101**

-   [Qihoo](https://www.360.cn/) 的 Renguang Yuan 报告了 Win32k 内存损坏漏洞 (CVE-2013-3899)
-   一位匿名研究人员与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Win32k 内存损坏漏洞 (CVE-2013-3899)
-   [F13 Laboratory](https://www.f13-labs.net/) 的 Ling Chuan Lee 报告了 TrueType 字体分析漏洞 (CVE-2013-3903)
-   [Core Security Technologies](https://www.coresecurity.com/) 的 Nicolas Economou 报告了 Win32k 整数溢出漏洞 (CVE-2013-5058)

**MS13-102**

-   [Qihoo](https://www.360.cn/) 的 Renguang Yuan 报告了 LRPC 客户端缓冲区溢出漏洞 (CVE-2013-3878)

**MS13-104**

-   [Adallom](https://www.adallom.com/) 的 Noam Liran 报告了令牌劫持漏洞 (CVE-2013-5054)

**MS13-105**

-   [Minded Security](https://www.mindedsecurity.com/) 代表 [Criteo](https://www.criteo.com/) 报告了 OWA XSS 漏洞 (CVE-2013-5072)

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/security/bb980617)

帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master)

本地支持（根据您的国家/地区）： [国际支持](https://support.microsoft.com/common/international.aspx)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2013 年 12 月 10 日）： 已发布公告摘要。

 

*页面生成时间 2014-05-09 17:27Z-07:00。*
