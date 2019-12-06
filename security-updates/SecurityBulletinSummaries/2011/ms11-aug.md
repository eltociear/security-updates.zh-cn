---
TOCTitle: 'MS11-AUG'
Title: 'Microsoft 安全公告摘要（2011 年 8 月）'
ms:assetid: 'ms11-aug'
ms:contentKeyID: 61236952
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms11-aug(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要（2011 年 8 月）
======================================

发布时间: 2011年8月9日 | 更新时间: 2011年10月26日

**版本:** 1.2

本公告摘要列出了 2011 年 8 月发布的安全公告。

对于 2011 年 8 月发布的安全公告，本公告摘要替代 2011 年 8 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2011 年 8 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 8 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487857)。此日期之后，此网络广播按需提供。有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://go.microsoft.com/fwlink/?linkid=217214)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累积性安全更新 (2559049)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中五个秘密报告的漏洞和两个公开披露的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td style="border:1px solid black;"><strong>DNS 服务器中的漏洞可能允许远程执行代码 (2562485)</strong><br />
<br />
此安全更新可解决 Windows DNS 服务器中两个秘密报告的漏洞。如果攻击者注册域、创建 NAPTR DNS 资源记录，然后将特制 NAPTR 查询发送到目标 DNS 服务器，则这些漏洞中较为严重的漏洞可能允许远程执行代码。没有启用 DNS 角色的服务器不受威胁。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td style="border:1px solid black;"><strong>Data Access Components 中的漏洞可能允许远程执行代码 (2560656)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开与特制库文件位于同一网络目录下的合法 Excel 文件（如 .xlsx 文件），此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio 中的漏洞可能允许远程执行代码 (2560978)</strong><br />
<br />
此安全更新解决 Microsoft Visio 中两个秘密报告的漏洞。如果用户打开特制的 Visio 文件，这些漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td style="border:1px solid black;"><strong>远程桌面 Web 访问中的漏洞可能允许特权提升 (2546250)</strong><br />
<br />
此安全更新可解决远程桌面 Web 访问中一个秘密报告的漏洞。该漏洞是一个跨站点脚本执行 (XSS) 漏洞，可能允许特权提升，使攻击者能够在目标用户的上下文中在站点上执行任意命令。当浏览到 Internet 区域中的远程桌面 Web 访问服务器时，Internet Explorer 8 和 Internet Explorer 9 中的 XSS 筛选器可针对其用户阻止此攻击。默认情况下，Internet Explorer 8 和 Internet Explorer 9 中的 XSS 筛选器在 Intranet 区域中未启用。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td style="border:1px solid black;"><strong>远程访问服务器 NDISTAPI 驱动程序中的漏洞可能允许特权提升</strong> <strong>(2566454)</strong><br />
<br />  
此安全更新解决了 Windows XP 和 Windows Server 2003 所有受支持的版本中一个秘密报告的漏洞。对于 Windows XP 和 Windows Server 2003 的所有受支持版本，此安全更新的等级为“重要”。Windows Vista、Windows Server 2008、Windows 7 和 Windows Server 2008 R2 不受此漏洞影响。<br />  
<br />
如果攻击者登录受影响的系统，并运行设计为利用该漏洞并完全控制受影响的系统的特制应用程序，该漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td style="border:1px solid black;"><strong>Windows 客户端/服务器运行时子系统中的漏洞可能允许特权提升 (2567680)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者登录受影响的系统，并运行设计为将设备事件消息发送到较高完整性进程的特制应用程序，该漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td style="border:1px solid black;"><strong>TCP/IP 堆栈中的漏洞可能允许拒绝服务 (2563894)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中两个秘密报告的漏洞。如果攻击者向目标系统发送一系列特制 Internet 控制消息协议 (ICMP) 消息，或者向服务于 Web 内容并且启用了基于 URL 的服务质量 (QoS) 功能，则该漏洞可能允许拒绝服务。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td style="border:1px solid black;"><strong>远程桌面协议中的漏洞可能允许拒绝服务 (2570222)</strong><br />
<br />
此安全更新可解决远程桌面协议中一个秘密报告的漏洞。如果受影响的系统收到一系列特制 RDP 数据包，则此漏洞可能允许拒绝服务。Microsoft 也收到了尝试利用此漏洞进行有限目标攻击的报告。默认情况下，任何 Windows 操作系统都未启用远程桌面协议 (RDP)。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td style="border:1px solid black;"><strong>Microsoft 图表控件中的漏洞可能导致信息泄露 (2567943)</strong><br />
<br />
此安全更新可消除 Microsoft .NET 图表控件中的一个秘密报告的漏洞。如果攻击者向托管图表控件的受影响服务器发送特制的 GET 请求，则该漏洞可能会导致信息泄露。请注意，攻击者无法利用此漏洞来执行代码或直接提升他们的用户权限，但可用于检索将试图进一步危及受影响系统安全的信息。仅使用 Microsoft 图表控件的 Web 应用程序会受这个问题影响。.NET Framework 的默认安装不受影响。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft .NET Framework，<br />
Microsoft 开发工具</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td style="border:1px solid black;"><strong>Microsoft Report Viewer 中的漏洞可能允许信息泄露 (2578230)</strong><br />
<br />
此安全更新可解决 Microsoft Report Viewer 中一个秘密报告的漏洞。如果用户查看特制网页，则该漏洞可能允许信息泄露。但是在所有情况下，攻击者无法强制用户访问网站。相反，攻击者必须说服用户访问网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接而转到容易受到攻击的网站。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft 开发工具</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223578">MS11-068</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许拒绝服务 (2556532)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。如果用户访问包含特制文件的网络共享（或者访问指向网络共享的网站），则该漏洞可能允许拒绝服务。但是在所有情况下，攻击者无法强制用户访问此类网络共享或网站。相反，攻击者必须说服用户访问网站或网络共享，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">中等</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221537">MS11-069</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的漏洞可能允许信息泄露 (2567951)</strong><br />
<br />
此安全更新可解决 Microsoft .NET Framework 中的一个秘密报告的漏洞。如果用户使用可以运行 XAML 浏览器应用程序 (XBAP) 的 Web 浏览器查看特制网页，则该漏洞可能允许信息泄露。在基于 Web 的攻击情形中，攻击者可能拥有一个网站，并在上面放置用来利用此漏洞的网页。另外，接受或宿主用户提供的内容或广告的网站以及受到破坏的网站可能包含可能利用此漏洞的特制内容。但是在所有情况下，攻击者无法强制用户访问这些网站。相反，攻击者必须诱使用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站。Windows .NET 应用程序也可能会使用此漏洞绕过代码访问安全性 (CAS) 限制。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">中等</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft .NET Framework</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**我如何使用该表呢？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。

<p> </p>
<table style="border:1px solid black;">  
<thead>  
<tr class="header">  
<th>公告 ID</th>  
<th>漏洞标题</th>  
<th>CVE ID</th>  
<th>最新软件版本的代码执行利用评估</th>  
<th>较旧软件版本的代码执行利用评估</th>  
<th>拒绝服务利用评估</th>  
<th>重要注意事项</th>  
</tr>  
</thead>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">窗口打开竞争状态漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1257">CVE-2011-1257</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">事件处理程序信息泄露漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1960">CVE-2011-1960</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">Telnet 处理程序远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1961">CVE-2011-1961</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">XSLT 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1963">CVE-2011-1963</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">样式对象内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1964">CVE-2011-1964</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td style="border:1px solid black;">DNS NAPTR 查询漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1966">CVE-2011-1966</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td style="border:1px solid black;">DNS 未初始化的内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1970">CVE-2011-1970</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td style="border:1px solid black;">Data Access Components 不安全库加载漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1975">CVE-2011-1975</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td style="border:1px solid black;">pStream 释放 RCE 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1972">CVE-2011-1972</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td style="border:1px solid black;">移动块 RCE 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1979">CVE-2011-1979</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td style="border:1px solid black;">远程桌面 Web 访问漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1263">CVE-2011-1263</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td style="border:1px solid black;">NDISTAPI 特权提升漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1974">CVE-2011-1974</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td style="border:1px solid black;">CSRSS 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1967">CVE-2011-1967</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td style="border:1px solid black;">ICMP 拒绝服务漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1871">CVE-2011-1871</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td style="border:1px solid black;">TCP/IP QOS 拒绝服务漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1965">CVE-2011-1965</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td style="border:1px solid black;">远程桌面协议漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1968">CVE-2011-1968</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">针对此漏洞报告了有限的目标攻击<br />
<br />
这是一个拒绝服务漏洞</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td style="border:1px solid black;">图表控制信息泄露漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1977">CVE-2011-1977</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td style="border:1px solid black;">Report Viewer 控件 XSS 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1976">CVE-2011-1976</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞</td>
</tr>  
</tbody>  
</table>
  
受影响的软件和下载位置  
----------------------
  
<span></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Windows 操作系统和组件
  
**表 1**

<p> </p>
<table style="border:1px solid black;">  
<tr class="thead">  
<th>  
</th>  
<th>  
</th>  
<th>  
</th>  
<th>  
</th>  
<th>  
</th>  
<th>  
</th>  
<th>  
</th>  
</tr>  
<tr>  
<th colspan="7" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-057**](https://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](https://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](https://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](https://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](https://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](https://go.microsoft.com/fwlink/?linkid=221864)
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
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=90312c78-1fbd-4143-b2e6-ae5c48af6f57)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a771c93b-55a4-456f-a315-d0d1f2696960)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5feb8ed7-99d2-4dd6-986f-57a7fd0c6f19)  
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
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6bc1f0ac-223d-4b0b-86cd-2ba3863955c4)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=0231c103-c0cb-4705-9d92-5356b8cbb265)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=23d77f3b-13f8-49f3-9c3c-27ad217cd59e)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=acb14d82-a801-4ec7-84cc-9f131009ebcb)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=272c813b-bd39-4e63-9fa7-c5b8ed0b08d7)  
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
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d5ee6787-408d-4870-af70-9338158b161b)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=09276f6e-e3f4-4b7e-996e-4ec376c103e1)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-057**](https://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](https://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](https://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](https://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](https://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](https://go.microsoft.com/fwlink/?linkid=221864)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重** **等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=26b5fb48-346a-49f1-840f-03f218a41c20)  
（重要）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=042552ad-f46a-4bfc-9e5c-58f095eba1de)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=648596fc-fd97-438a-97be-d5d590f1c561)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c2d4aa38-9241-465d-8d65-aba73e936d0f)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8de0f2db-aa09-48cd-a13b-e26a973e9cdc)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=870fdfdd-16bf-42a2-a23b-ed6045438d5e)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=9c3d14d8-6716-4423-91a9-a05373227237)  
（重要）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c9e283d8-d4a2-41e2-a73c-92fae957ba3d)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=470d56d1-5789-42cc-a088-a2c8ac934ab3)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2db4098a-f4f9-4211-b55d-5d0df1409c43)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8f208407-4bb3-41fe-b0d6-fc8a5e30e667)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=31af27b8-7b73-4090-94bd-2fb89d3970fc)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=64496a87-2225-402a-a94a-a8e92b17ac83)  
（重要）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5aa3a493-4188-48a9-a549-cf9ba01ed32a)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1934acfa-5637-4ae9-9e9a-fc7e58930b7a)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ef140089-d022-4ee8-9cc4-7fb25295a39d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=410c72d8-3b78-4c4a-ad61-acb7f854ffc2)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-057**](https://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](https://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](https://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](https://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](https://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](https://go.microsoft.com/fwlink/?linkid=221864)
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
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
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
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=66ddc7ce-5280-494d-bb3c-dab06e27fb5c)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a080f36e-c24f-40ac-bb40-b26cb31bcae3)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c82417ec-232f-4f84-ba2c-0ffad77e9bb5)  
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8f25ced5-ef86-4b9d-91fb-443c9a2c1458)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3f119902-8398-4814-8229-9eb9f0980e87)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=704c1c9c-d1c1-40cb-97a7-fbb1f195f9f8)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=a6ff7b27-bc21-4945-8b2e-757b6f83fa58)  
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d5b8ff09-237e-49f1-a566-e323ca11fbc3)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-057**](https://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](https://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](https://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](https://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](https://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](https://go.microsoft.com/fwlink/?linkid=221864)
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
无
</td>
<td style="border:1px solid black;">
无
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
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=da9c98d1-973c-44d9-aee5-f5c4a8e8c0e1)\*\*  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d65ae4cc-d82a-42da-829f-d9479e23b7a5)\*\*  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=70065bd0-7c97-4ffc-828f-2cc245d04429)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ac2d5122-6f9b-46f5-9840-77aa7ff84308)\*  
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
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1fbaabb9-8601-4760-813d-aeedfdcafb8b)\*  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9facff69-618f-4a64-8665-5dd6cde07de9)\*\*  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=00f28d81-3714-403c-bcd7-55f2ac97f75b)\*\*  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=9ce60689-ca85-4c9f-af96-a73b1e43c10b)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5f605f6f-3854-403d-878b-637626aef78f)\*  
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
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2e7253d8-fdc7-4563-9714-21ca3c77e4b1)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=01885624-cfb1-4918-abef-ab0ea765cb04)  
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fe37eb6d-b1fa-496c-a0d3-19a6d35a6cb9)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-057**](https://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](https://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](https://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](https://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](https://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](https://go.microsoft.com/fwlink/?linkid=221864)
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
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7019de24-8c58-4565-ada1-ca8755115096)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=12292081-23f7-4968-8cd7-17aaef2aed6a)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6bc168d9-6664-41fb-914f-dbd7514a4b0e)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f4551b77-eb09-448a-9dc5-66de846035e7)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=fcdb872f-2ee2-4f74-b7ae-1b82daf66761)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ef664114-6582-49d3-b332-078a7d075337)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=aafeff2d-db9a-4b3b-b620-be4ec5f5bdcc)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0fc9a501-523d-4cbb-8d99-a773089afc4c)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-057**](https://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](https://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](https://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](https://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](https://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](https://go.microsoft.com/fwlink/?linkid=221864)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=14fe68eb-2aa6-4a59-b9d8-deeae5236af2)\*\*  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=dd709da2-4cb1-482f-88eb-dfab4d3c59c6)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6a86e2cf-4e7d-4012-88c3-6957a3842dd3)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c29deec3-4672-4658-a550-dce244434cd4)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=777f3bbe-094c-411d-879d-34a5a20ae7f3)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2f4043df-c07c-4611-b06a-7fcbb7416e7d)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=82403fd3-ed75-4ea8-aa3f-ed9dda75612a)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1d6b8036-d38f-408a-a36c-027553faefc1)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b420cae3-de30-4c6c-8ed9-7431ad7ab4da)  
（重要）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。**此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**表 2**

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
<th>
</th>
<th>
</th>
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-064**](https://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](https://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](https://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](https://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](https://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c07e1630-43ba-491e-bd59-9eb53105986c)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=797a01dc-39fb-4511-832a-42d2975133f5)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-064**](https://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](https://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](https://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](https://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](https://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=694ba1a6-7512-497d-a572-646a6e07b13b)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=308da543-d49d-4591-8bbc-d65c524bb0ad)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
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
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3b459bf0-7844-4740-895c-d149d56e781f)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-064**](https://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](https://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](https://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](https://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](https://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=114c2835-921a-4d3e-be91-dfd217fd26a9)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9713b7b8-f260-440d-a994-845f17683fe9)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0fcee476-8d7e-49a7-b6ea-89043304a653)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4d67ec00-e86a-49b6-a9a2-85b2520fa4bb)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-064**](https://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](https://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](https://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](https://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](https://go.microsoft.com/fwlink/?linkid=221537)
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
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c01d9132-af5f-4039-8195-95f6761f2d0e)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=da219735-b8b7-4f97-b8a8-7c253838de6b)\*\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=70797adb-d693-4102-9e7c-ba1ea8fb07d0)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e077af5-5823-4377-a997-44b022a694d8)\*\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9babf81a-8b21-42ae-a65c-f414793516ab)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=560efa6f-c956-47cb-a2f4-a1f45278b7cd)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
（中等）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-064**](https://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](https://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](https://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](https://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](https://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=814bbdfa-7cbc-40e5-8ca3-8fed9d13ff00)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6c8dd72b-abf8-4e1f-aafc-777c1a3ef3db)  
（中等）
</td>
<td style="border:1px solid black;">
仅限 Windows 7（用于 32 位系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
（中等）  
仅限 Windows 7（用于 32 位系统）：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）  
仅限 Windows 7（用于 32 位系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
（中等）  
仅限 Windows 7（用于 32 位系统）Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=085ee785-b6ad-4c68-835a-e17bc8f12a53)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d90c07c1-3c07-4989-825c-fb8453541a0e)  
（中等）
</td>
<td style="border:1px solid black;">
仅限 Windows 7（用于基于 x64 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
（中等）  
仅限 Windows 7（用于基于 x64 的系统）：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）  
仅限 Windows 7（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
（中等）  
仅限 Windows 7（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-064**](https://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](https://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](https://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](https://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](https://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9fd2b4ba-d98e-4ad6-99f2-c471335042d3)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008 R2（用于基于 x64 的系统）：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=67cccd09-5b82-4546-884a-d2a9e2400820)\*\*\*  
（中等）
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008 R2（用于基于 x64 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)\*  
(KB2539634)  
（中等）  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)\*  
(KB2539635)  
（中等）  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=93752c8f-5461-4e6f-9cab-6401b985ef17)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>  
(KB2487367)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a1edf843-9a2a-4334-a95f-78e75a9b3ef1)  
（中等）
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
（中等）  
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）  
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
（中等）  
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>  
(KB2539636)  
（中等）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。**此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装，即使系统上可能存在此漏洞影响的文件，此更新解决的漏洞也不会影响 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本。但是，仍将向具有受影响文件的用户提供此更新，因更新文件比您的系统上的当前文件更新（版本号较高）。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS11-066 注释**

<sup>[1]</sup>**.NET Framework 4 客户端配置文件不受影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 客户端配置文件是 .NET Framework 4 的子集。此更新中解决的漏洞仅影响 .NET Framework 4 而并不影响 .NET Framework 4 客户端配置文件。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](https://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS11-069 注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](https://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

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
Microsoft Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-060**](https://go.microsoft.com/fwlink/?linkid=223425)
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
Microsoft Visio 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=866d64b3-7147-4b5f-80fe-4d3317f140df)  
(KB2553009)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a0eeabde-5a92-45ae-aef6-81b7bdb4e0cd)  
(KB2553010)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2010 和 Microsoft Visio 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 和 Microsoft Visio 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=6da236c2-0ef5-4c13-8393-673b70298a77)  
(KB2553008)  
（重要）  
[Microsoft Visio 2010 和 Microsoft Visio 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=b7f5f2a9-116a-41ef-a19e-a7dd0947d2cb)  
(KB2553008)  
（重要）
</td>
</tr>
</table>


#### Microsoft 开发工具和软件

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
Chart 控件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-066**](https://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-067**](https://go.microsoft.com/fwlink/?linkid=223643)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5 Service Pack 1 的图表控件
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1 的图表控件](https://www.microsoft.com/download/details.aspx?familyid=8a80cc03-0db9-4446-9ce6-159ad02cab52)  
(KB2500170)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Visual Studio 和 Microsoft Report Viewer
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-066**](https://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-067**](https://go.microsoft.com/fwlink/?linkid=223643)
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
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=59231988-5413-4238-a3aa-32a127871430)  
(KB2548826)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=28bf2ae0-9e21-4201-b7f1-a207abc2866f)  
(KB2579115)  
（重要）
</td>
</tr>
</table>

**MS11-066 注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/default.aspx)。

**System Center Configuration Manager 2007**

Configuration Manager 2007 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 Configuration Manager 2007，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

Configuration Manager 2007 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。Configuration Manager 2007 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关管理员如何使用 Configuration Manager 2007 部署更新的详细信息，请参阅[软件更新管理](https://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)。有关 Configuration Manager 的详细信息，请访问 [System Center Configuration Manager](https://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。SMS 的下一版本 System Center Configuration Manager 2007 现已可用；请参阅前面的部分 **System Center Configuration Manager 2007**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意：** SMS 使用 Microsoft Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   [Opera Software ASA](https://www.opera.com/) 的 Yngve N. Pettersen 报告了 MS11-057 中描述的一个问题
-   [Lostmon Lords](https://lostmon.blogspot.com) 报告了 MS11-057 中描述的一个问题
-   [Security Professionals Network Inc.](https://www.sec-pro.net/) 的 Makoto Shiotsuki 报告了 MS11-057 中描述的一个问题
-   一位匿名研究员与 [TippingPoint's](https://www.tippingpoint.com/)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS11-057 中描述的一个问题
-   [Harmony Security](https://www.harmonysecurity.com/) 的 Stephen Fewer 与 [TippingPoint's](https://www.tippingpoint.com/)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS11-057 中描述的两个问题
-   [Google Inc.](https://www.google.com/) 的 Michal Zalewski 与我们合作处理了 ms11-057 中涵盖的纵深防御更改问题
-   Grischa Zengel ([Zengel Medizintechnik GmbH](https://www.zmt.info/)) 报告了 MS11-058 中描述的一个问题
-   [Baidu Security Team](https://www.baidu.com) 的 Linlin Zhao 报告了 MS11-060 中描述的两个问题
-   Sven Taute 报告了 MS11-061 中描述的一个问题
-   的 Lufeng Li 报告了 MS11-062 中描述的一个问题
-   Winsider Seminars & Solutions Inc. 的 Alex Ionescu 报告了 MS11-063 中描述的一个问题
-   Context Information Security 的 Nico Leidecker 和 James Forshaw 报告了 MS11-066 中描述的一个问题
-   [Gotham Digital Science](https://www.gdssecurity.com/) 的 Adam Bixby 报告了 MS11-067 中描述的一个问题
-   [Qihoo 360 Security Center](https://www.360.cn/) 的 Zheng Wenbin 报告了 MS11-068 中描述的一个问题
-   Michael J. Liu 报告了 MS11-069 中描述的一个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。与安全更新有关的电话支持服务是免费的。有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。与安全更新有关的支持服务不收取任何费用。有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2011 年 8 月 9 日）： 已发布公告摘要。
-   V1.1（2011 年 8 月 10 日）： 对于 MS11-059，纠正了“**摘要**”部分中的重新启动要求信息。对于 MS11-065，纠正了 CVE-2011-1968 的“**利用指数**”的重要注释。对于 MS11-068，修订了 Windows Server 2008 和 Windows Server 2008 R2 的服务器核心符号。
-   V1.2（2011 年 10 月 26 日）： 对于 MS11-066 和 MS11-069，更正了 Windows Server 2008 R2（用于基于 x64 的系统）上 .NET Framework 4 的服务器核心安装适用性。

*Built at 2014-04-18T01:50:00Z-07:00*
