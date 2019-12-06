---
TOCTitle: 'MS14-MAY'
Title: 'Microsoft 安全公告摘要（2014 年 5 月）'
ms:assetid: 'ms14-may'
ms:contentKeyID: 62258024
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms14-may(v=Security.10)'
---

Microsoft 安全公告摘要（2014 年 5 月）
======================================

发布日期： 2014 年 5 月 1 日 | 更新时间： 2014 年 5 月 13 日

**版本：** 2.0

本公告摘要列出了 2014 年 5 月发布的安全公告。

对于 2014 年 5 月发布的安全公告，本公告摘要替代 2014 年 5 月 8 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2014 年 5 月 14 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 5 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572979&culture=en-us)。

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
<thead>
<tr class="header">
<th><p>公告 ID</p></th>
<th><p>公告标题和摘要</p></th>
<th><p>最高严重等级和漏洞影响</p></th>
<th><p>重新启动要求</p></th>
<th><p>受影响的软件</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=397669"><strong>MS14-021</strong></a><br />
（2014 年 5 月 1 日发布带外更新）</p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 安全更新 (2965111)<br />
<br />
</strong>此安全更新可解决 Internet Explorer 中一个公开披露的漏洞。如果用户使用 Internet Explorer 的受影响版本查看特制网页，则该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=395261"><strong>MS14-029</strong></a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 安全更新 (2962482)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中两个秘密报告的漏洞。如果用户使用 Internet Explorer 查看特制网页，则所有漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft SharePoint Server 中的漏洞可能允许远程执行代码 (2952166)</strong><br />
<br />
此安全更新可解决 Microsoft Office 服务器和效率软件中多个秘密报告的漏洞。如果经过身份验证的攻击者向目标 SharePoint 服务器发送特制页面内容，这些漏洞中最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft 服务器软件,<br />
效率软件</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=393745"><strong>MS14-023</strong></a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (2961037)</strong><br />
<br />
此安全更新解决 Microsoft Office 中两个秘密报告的漏洞。如果用户打开与特制库文件位于同一网络目录下的 Office文件，最严重的漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396820"><strong>MS14-025</strong></a></p></td>
<td style="border:1px solid black;"><p><strong>组策略首选项中的漏洞可能允许特权提升 (2962486)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。如果 Active Directory 组策略首选项用于跨域分发密码，该漏洞可能允许特权提升，这种做法可能允许攻击者检索并解密使用组策略首选项存储的密码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396825"><strong>MS14-026</strong></a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 中的漏洞可能允许特权提升 (2958732)<br />
</strong><br />
此安全更新可解决 Microsoft .NET Framework 中的一个秘密报告的漏洞。如果经过身份验证的攻击者向使用 .NET Remoting 的受影响的工作站或服务器发送特制数据，则该漏洞可能允许特权提升。应用程序并未广泛使用 .NET Remoting；仅专门设计为使用 .NET Remoting 的自定义应用程序才会让系统遭受该漏洞的攻击。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396823"><strong>MS14-027</strong></a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Shell 处理程序中的漏洞可能允许特权提升 (2962488)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者运行使用 ShellExecute 的特制应用程序，则该漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=393744"><strong>MS14-028</strong></a></p></td>
<td style="border:1px solid black;"><p><strong>iSCSI 中的漏洞可能允许拒绝服务 (2962485)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中两个秘密报告的漏洞。如果攻击者通过目标网络发送大量特制 iSCSI 数据包，则该漏洞可能允许拒绝服务。此漏洞仅影响已启用 iSCSI 目标角色的服务器。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396835"><strong>MS14-024</strong></a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 公共控件中的漏洞可能允许安全功能绕过 (2961033)</strong><br />
<br />
此安全更新可解决 MSCOMCTL 公共控件库实施中的一个秘密报告的漏洞。如果用户在能够实例化 COM 组件（如 Internet Explorer）的 Web 浏览器中查看特制网页，则该漏洞可能允许安全功能绕过。在 Web 浏览攻击情形中，成功利用此漏洞的攻击者可能会绕过地址空间布局随机化 (ASLR) 安全功能，它有助于保护用户免遭多种漏洞。该安全功能绕过本身不允许执行任意代码。但是，攻击者可能会将此 ASLR 绕过漏洞与另一个漏洞（例如，可能利用 ASLR 绕过的远程执行代码漏洞）组合使用来运行任意代码。</p></td>
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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=397669"><strong>MS14-021</strong></a><br />
（2014 年 5 月 1 日发布带外更新）</p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1776">CVE-2014-1776</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。此漏洞最初在 <a href="https://technet.microsoft.com/library/security/2963983">Microsoft 安全通报 2963983</a> 中进行了说明。<br />
<br />
Microsoft 获悉尝试在 Internet Explorer 中利用此漏洞的有限目标攻击。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></p></td>
<td style="border:1px solid black;"><p>SharePoint 页面内容漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0251">CVE-2014-0251</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></p></td>
<td style="border:1px solid black;"><p>SharePoint XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1754">CVE-2014-1754</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=386285"><strong>MS14-022</strong></a></p></td>
<td style="border:1px solid black;"><p>Web Applications 页面内容漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1813">CVE-2014-1813</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>临时</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=393745"><strong>MS14-023</strong></a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 中文语法检查漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1756">CVE-2014-1756</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=393745"><strong>MS14-023</strong></a></p></td>
<td style="border:1px solid black;"><p>令牌重用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1808">CVE-2014-1808</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396835"><strong>MS14-024</strong></a></p></td>
<td style="border:1px solid black;"><p>MSCOMCTL ASLR漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1809">CVE-2014-1809</a></p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能绕过漏洞。<br />
<br />
Microsoft 获悉尝试使用此漏洞的有限目标攻击。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396820"><strong>MS14-025</strong></a></p></td>
<td style="border:1px solid black;"><p>组策略首选项密码特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1812">CVE-2014-1812</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396825"><strong>MS14-026</strong></a></p></td>
<td style="border:1px solid black;"><p>TypeFilterLevel 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1806">CVE-2014-1806</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396823"><strong>MS14-027</strong></a></p></td>
<td style="border:1px solid black;"><p>Windows Shell 文件关联漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1807">CVE-2014-1807</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>Microsoft 获悉尝试使用此漏洞的有限攻击。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=393744"><strong>MS14-028</strong></a></p></td>
<td style="border:1px solid black;"><p>iSCSI 目标远程拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0255">CVE-2014-0255</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>临时</p></td>
<td style="border:1px solid black;"><p>这是一个拒绝服务漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=393744"><strong>MS14-028</strong></a></p></td>
<td style="border:1px solid black;"><p>iSCSI 目标远程拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0256">CVE-2014-0256</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>临时</p></td>
<td style="border:1px solid black;"><p>这是一个拒绝服务漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=395261"><strong>MS14-029</strong></a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0310">CVE-2014-0310</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=395261"><strong>MS14-029</strong></a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1815">CVE-2014-1815</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>Microsoft 获悉尝试在 Internet Explorer 中利用此漏洞的有限攻击。</p></td>
</tr>  
</tbody>  
</table>
  
受影响的软件  
------------
  
<span id="sectionToggle2"></span>  
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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
（严重）  
Internet Explorer 7  
(2964358)  
（严重）  
Internet Explorer 8  
(2964358)  
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
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
（严重）  
Internet Explorer 7  
(2964358)  
（严重）  
Internet Explorer 8  
(2964358)  
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
不适用

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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
（中等）  
Internet Explorer 7  
(2964358)  
（中等）  
Internet Explorer 8  
(2964358)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2953522)  
（中等）  
Internet Explorer 7   
(2953522)  
（中等）  
Internet Explorer 8   
(2953522)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2931352)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2932079)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2926765)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
（中等）  
Internet Explorer 7  
(2964358)  
（中等）  
Internet Explorer 8  
(2964358)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2953522)  
（中等）  
Internet Explorer 7   
(2953522)  
（中等）  
Internet Explorer 8   
(2953522)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2932079)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2926765)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2964358)  
（中等）  
Internet Explorer 7  
(2964358)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2953522)  
（中等）  
Internet Explorer 7   
(2953522)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2932079)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2926765)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 7  
(2964358)  
（严重）  
Internet Explorer 8  
(2964358)  
（严重）  
Internet Explorer 9  
(2964358)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
（严重）  
Internet Explorer 8  
(2953522)  
（严重）  
Internet Explorer 9  
(2953522)  
（严重）

</td>
<td style="border:1px solid black;">
远程服务器管理工具  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）  
Microsoft .NET Framework 4.5  
(2931368)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931368)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2926765)  
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
Internet Explorer 7  
(2964358)  
（严重）  
Internet Explorer 8  
(2964358)  
（严重）  
Internet Explorer 9  
(2964358)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
（严重）  
Internet Explorer 8  
(2953522)  
（严重）  
Internet Explorer 9  
(2953522)  
（严重）

</td>
<td style="border:1px solid black;">
远程服务器管理工具  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）  
Microsoft .NET Framework 4.5  
(2931368)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931368)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2926765)  
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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
（中等）  
Internet Explorer 8  
(2964358)  
（中等）  
Internet Explorer 9  
(2964358)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
（中等）  
Internet Explorer 8  
(2953522)  
（中等）  
Internet Explorer 9  
(2953522)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）  
Microsoft .NET Framework 4.5  
(2931368)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931368)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2926765)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
（中等）  
Internet Explorer 8  
(2964358)  
（中等）  
Internet Explorer 9  
(2964358)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
（中等）  
Internet Explorer 8  
(2953522)  
（中等）  
Internet Explorer 9  
(2953522)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）  
Microsoft .NET Framework 4.5  
(2931368)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931368)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2926765)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2964358)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2953522)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2931354)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2926765)  
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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(2964358)  
（严重）  
Internet Explorer 9  
(2964358)  
（严重）  
Internet Explorer 10  
(2964358)  
（严重）  
Internet Explorer 11  
(2964358)  
（严重）  
Internet Explorer 11  
(2964444)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
（严重）  
Internet Explorer 9  
(2953522)  
（严重）  
Internet Explorer 10  
(2953522)  
（严重）  
Internet Explorer 11  
(2953522)  
（严重）  
Internet Explorer 11  
(2961851)  
（严重）

</td>
<td style="border:1px solid black;">
远程服务器管理工具  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）  
Microsoft .NET Framework 4.5  
(2931368)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931368)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2926765)  
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
Internet Explorer 8  
(2964358)  
（严重）  
Internet Explorer 9  
(2964358)  
（严重）  
Internet Explorer 10  
(2964358)  
（严重）  
Internet Explorer 11  
(2964358)  
（严重）  
Internet Explorer 11  
(2964444)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
（严重）  
Internet Explorer 9  
(2953522)  
（严重）  
Internet Explorer 10  
(2953522)  
（严重）  
Internet Explorer 11  
(2953522)  
（严重）  
Internet Explorer 11  
(2961851)  
（严重）

</td>
<td style="border:1px solid black;">
远程服务器管理工具  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）  
Microsoft .NET Framework 4.5  
(2931368)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931368)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2926765)  
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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
（中等）  
Internet Explorer 9  
(2964358)  
（中等）  
Internet Explorer 10  
(2964358)  
（中等）  
Internet Explorer 11  
(2964358)  
（中等）  
Internet Explorer 11  
(2964444)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
（中等）  
Internet Explorer 9  
(2953522)  
（中等）  
Internet Explorer 10  
(2953522)  
（中等）  
Internet Explorer 11  
(2953522)  
（中等）  
Internet Explorer 11  
(2961851)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）  
Microsoft .NET Framework 4.5  
(2931368)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931368)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2926765)  
（重要）

</td>
<td style="border:1px solid black;">
iSCSI Software Target 3.3  
(2933826)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2964358)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2953522)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2926765)  
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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 10  
(2964358)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
（严重）

</td>
<td style="border:1px solid black;">
远程服务器管理工具  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
（重要）  
Microsoft .NET Framework 4.5  
(2931367)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931367)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2926765)  
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
Internet Explorer 10  
(2964358)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
（严重）

</td>
<td style="border:1px solid black;">
远程服务器管理工具  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
（重要）  
Microsoft .NET Framework 4.5  
(2931367)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931367)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2926765)  
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
Internet Explorer 11  
(2964358)  
（严重）  
Internet Explorer 11  
(2964444)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
（严重）  
Internet Explorer 11  
(2961851)  
（严重）

</td>
<td style="border:1px solid black;">
远程服务器管理工具  
(2928120)  
（重要）  
远程服务器管理工具  
(2961899)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931366)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2926765)  
（重要）  
Windows 8.1（用于 32 位系统）  
(2962123)  
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
Internet Explorer 11  
(2964358)  
（严重）  
Internet Explorer 11  
(2964444)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
（严重）  
Internet Explorer 11  
(2961851)  
（严重）

</td>
<td style="border:1px solid black;">
远程服务器管理工具  
(2928120)  
（重要）  
远程服务器管理工具  
(2961899)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931366)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2926765)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(2962123)  
（重要）

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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2964358)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2928120)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
（重要）  
Microsoft .NET Framework 4.5  
(2931367)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931367)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2926765)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2933826)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2964358)  
（中等）  
Internet Explorer 11  
(2964444)  
（中等）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
（中等）  
Internet Explorer 11  
(2961851)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2928120)  
（重要）  
Windows Server 2012 R2  
(2961899)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931366)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2926765)  
（重要）  
Windows Server 2012 R2  
(2962123)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2933826)  
（重要）  
Windows Server 2012 R2  
(2962073)  
（重要）

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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 10  
(2964358)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2953522)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2931367)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931367)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(2926765)  
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
Internet Explorer 11  
(2964358)  
（严重）  
Internet Explorer 11  
(2964444)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2953522)  
（严重）  
Internet Explorer 11  
(2961851)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1  
(2931366)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2926765)  
（重要）  
Windows RT 8.1  
(2962123)  
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
[**MS14-021**](https://go.microsoft.com/fwlink/?linkid=397669)

</td>
<td style="border:1px solid black;">
[**MS14-029**](https://go.microsoft.com/fwlink/?linkid=395261)

</td>
<td style="border:1px solid black;">
[**MS14-025**](https://go.microsoft.com/fwlink/?linkid=396820)

</td>
<td style="border:1px solid black;">
[**MS14-026**](https://go.microsoft.com/fwlink/?linkid=396825)

</td>
<td style="border:1px solid black;">
[**MS14-027**](https://go.microsoft.com/fwlink/?linkid=396823)

</td>
<td style="border:1px solid black;">
[**MS14-028**](https://go.microsoft.com/fwlink/?linkid=309325)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）

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
(2926765)  
（重要）

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
(2926765)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2931356)  
（重要）  
Microsoft .NET Framework 4  
(2931365)  
（重要）  
Microsoft .NET Framework 4.5  
(2931368)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931368)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2926765)  
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
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931357)  
（重要）  
Microsoft .NET Framework 4.5  
(2931367)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931367)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2926765)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2933826)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2931358)  
（重要）  
Microsoft .NET Framework 4.5.1  
(2931366)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2926765)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(2962123)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2933826)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(2962073)  
（重要）

</td>
</tr>
</table>

 

### Office 套件和软件

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
[**MS14-023**](https://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](https://go.microsoft.com/fwlink/?linkid=396835)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3（校对工具）  
(2767772)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3 (mscomct2)  
(2596804)  
（重要）  
Microsoft Office 2007 Service Pack 3 (mscomctlocx)  
(2817330)  
（重要）  
Microsoft Office 2007 Service Pack 3 (msaddndr)  
(2880508)  
（重要）  
Microsoft Office 2007 Service Pack 3 (msstdfmt)  
(2880507)  
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
[**MS14-023**](https://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](https://go.microsoft.com/fwlink/?linkid=396835)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）（校对工具）  
(2878284)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本） (mscomct2)  
(2589288)  
（重要）  
Microsoft Office 2010 Service Pack 1（32 位版本） (mscomctlocx)  
(2810073)  
（重要）  
Microsoft Office 2010 Service Pack 1（32 位版本） (msaddndr)  
(2880971)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）（校对工具）  
(2878284)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本） (mscomct2)  
(2589288)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本） (mscomctlocx)  
(2810073)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本） (msaddndr)  
(2880971)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）（校对工具）  
(2878284)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本） (mscomct2)  
(2589288)  
（重要）  
Microsoft Office 2010 Service Pack 1（64 位版本） (msaddndr)  
(2880971)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）（校对工具）  
(2878284)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本） (mscomct2)  
(2589288)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本） (msaddndr)  
(2880971)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 和 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-023**](https://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](https://go.microsoft.com/fwlink/?linkid=396835)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）（校对工具）  
(2880463)  
（重要）  
Microsoft Office 2013（32 位版本）(mso)  
(2878316)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）(mscomct2)  
(2760272)  
（重要）  
Microsoft Office 2013（32 位版本）(mscomctlocx)  
(2880502)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）（校对工具）  
(2880463)  
（重要）  
Microsoft Office 2013 Service Pack 1（32 位版本）(mso) (2878316)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本） (mscomct2)  
(2760272)  
（重要）  
Microsoft Office 2013 Service Pack 1（32 位版本） (mscomctlocx)  
(2880502)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）（校对工具）  
(2880463)  
（重要）  
Microsoft Office 2013（64 位版本）(mso)  
(2878316)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）(mscomct2)  
(2760272)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）（校对工具）  
(2880463)  
（重要）  
Microsoft Office 2013 Service Pack 1（64 位版本） (mso)  
(2878316)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本） (mscomct2)  
(2760272)  
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
[**MS14-023**](https://go.microsoft.com/fwlink/?linkid=393745)

</td>
<td style="border:1px solid black;">
[**MS14-024**](https://go.microsoft.com/fwlink/?linkid=396835)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT（校对工具）  
(2880463)  
（重要）  
Microsoft Office 2013 RT (mso)  
(2878316)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT (mscomct2)  
(2760272)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1（校对工具）  
(2880463)  
（重要）  
Microsoft Office 2013 RT Service Pack 1 (mso)  
(2878316)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1 (mscomct2)  
(2760272)  
（重要）

</td>
</tr>
</table>

 

### Microsoft Server 软件

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
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3（32 位版本）  
(2837616)  
（严重）  
SharePoint Server 2007 Service Pack 3（32 位版本） (dlcapp)  
(2596902)  
（严重）  
SharePoint Server 2007 Service Pack 3（32 位版本） (dlc)  
(2596763)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3（64 位版本）  
(2837616)  
（严重）  
SharePoint Server 2007 Service Pack 3（64 位版本） (dlcapp)  
(2596902)  
（严重）  
SharePoint Server 2007 Service Pack 3（64 位版本） (dlc)  
(2596763)  
（严重）

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
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1 (wss)  
(2837588)  
（严重）  
Microsoft SharePoint Server 2010 Service Pack 1 (coreserver)  
(2837598)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wss)  
(2837588)  
（严重）  
Microsoft SharePoint Server 2010 Service Pack 2 (coreserver)  
(2837598)  
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
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 (sts)  
(2863856)  
（严重）  
Microsoft SharePoint Foundation 2013 (wssloc)  
(2863863)  
（严重）  
Microsoft SharePoint Server 2013 (coreserverloc)  
(2863829)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1 (sts)  
(2863856)  
（严重）  
Microsoft SharePoint Foundation 2013 Service Pack 1 (wssloc)  
(2863863)  
（严重）  
Microsoft SharePoint Server 2013 Service Pack 1 (coreserver)  
(2863829)  
（严重）

</td>
</tr>
</table>

**MS14-022 的注释**

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
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2010 Service Pack 1  
(2863922)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2010 Service Pack 2  
(2863922)  
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
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2013  
(2760236)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Project Server 2013 Service Pack 1  
(2760236)  
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
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 1  
(2880536)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2880536)  
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
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2880453)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(2880453)  
（严重）

</td>
</tr>
</table>

**MS14-022 的注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### 效率软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SharePoint Server 2013 客户端组件 SDK**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
SharePoint Server 2013 客户端组件 SDK（32 位版本）

</td>
<td style="border:1px solid black;">
SharePoint Server 2013 客户端组件 SDK（32 位版本）  
(2863854)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
SharePoint Server 2013 客户端组件 SDK（64 位版本）

</td>
<td style="border:1px solid black;">
SharePoint Server 2013 客户端组件 SDK（64 位版本）  
(2863854)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Designer 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2007 Service Pack 3 (ewd)  
(2596861)  
（严重）  
Microsoft SharePoint Designer 2007 Service Pack 3 (spd)  
(2596810)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Designer 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 1（32 位版本）  
(2810069)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 2（32 位版本）  
(2810069)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 1（64 位版本）  
(2810069)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2010 Service Pack 2（64 位版本）  
(2810069)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Microsoft SharePoint Designer 2013**

</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-022**](https://go.microsoft.com/fwlink/?linkid=386285)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013（32 位版本） (spdcore)  
(2752096)  
（严重）  
Microsoft SharePoint Designer 2013（32 位版本） (spd)  
(2863836)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 Service Pack 1（32 位版本） (spdcore)  
(2752096)  
（严重）  
Microsoft SharePoint Designer 2013 Service Pack 1（32 位版本） (spd)  
(2863836)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013（64 位版本） (spdcore)  
(2752096)  
（严重）  
Microsoft SharePoint Designer 2013（64 位版本） (spd)  
(2863836)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Designer 2013 Service Pack 1（64 位版本） (spdcore)  
(2752096)  
（严重）  
Microsoft SharePoint Designer 2013 Service Pack 1（64 位版本） (spd)  
(2863836)  
（严重）

</td>
</tr>
</table>

**MS14-022 的注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

管理员可使用 Microsoft Baseline Security Analyzer (MBSA) 在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/security/cc297183)。 

鸣谢
----

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

**MS14-021**

-   [FireEye, Inc.](https://www2.fireeye.com/) 与我们合作处理了 Internet Explorer 内存损坏漏洞 (CVE-2014-1776)

     

**MS14-023**

-   [NSFOCUS Security Team](https://www.nsfocus.com/) 报告了 Microsoft Office 中文语法检查漏洞 (CVE-2014-1756)
-   [ANSSI](https://www.ssi.gouv.fr/) 的 Arnaud Maillet 报告了令牌重用漏洞 (CVE-2014-1808)

     

**MS14-026**

-   [Context Information Security](https://www.contextis.com/) 的 James Forshawor 报告了 TypeFilterLevel 漏洞 (CVE-2014-1806)

     

**MS14-028**

-   一位匿名研究人员与 [SecuriTeam Secure Disclosure](https://www.beyondsecurity.com/ssd.html) 项目团队合作报告了 iSCSI 目标远程拒绝服务漏洞 (CVE-2014-0255)
-   一位匿名研究人员与 [SecuriTeam Secure Disclosure](https://www.beyondsecurity.com/ssd.html) 项目团队合作报告了 iSCSI 目标远程拒绝服务漏洞 (CVE-2014-0256)

     

**MS14-029**

-   [Google Security Team](https://www.google.com/) 的 Fermin J. Serna 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0310)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0310)
-   [Google Security Team](https://www.google.com/) 的 Clément Lecigne 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1815)

     

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

-   V1.0（2014 年 5 月 1 日）： 已发布公告摘要。
-   V2.0（2014 年 5 月 13 日）： 添加了 Microsoft 安全公告 MS13-022 至 MS13-029，添加了 5 月 14 日网络广播的公告网络广播链接。

*页面生成时间 2014-05-14 10:22Z-07:00。*
