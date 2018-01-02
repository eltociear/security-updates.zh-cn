---
TOCTitle: 'MS13-OCT'
Title: 'Microsoft 安全公告摘要（2013 年 10 月）'
ms:assetid: 'ms13-oct'
ms:contentKeyID: 61236986
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms13-oct(v=Security.10)'
---



Microsoft 安全公告摘要（2013 年 10 月）
=======================================

发布时间: 2013年10月8日 | 更新时间: 2013年11月6日

**版本:** 1.2

本公告摘要列出了 2013 年 10 月发布的安全公告。

对于 2013 年 10 月发布的安全公告，本公告摘要替代 2013 年 10 月 3 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2013 年 10 月 9 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 10 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557381&culture=en-us)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

### 公告信息

#### 摘要

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2879017)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中一个公开披露的漏洞和八个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些最严重的漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许远程执行代码 (2870008)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中秘密报告的 7 个漏洞。如果用户查看嵌入 OpenType 或 TrueType 字体文件的共享内容，则这些漏洞中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以完全控制受影响的系统。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的漏洞可能允许远程执行代码 (2878890)</strong><br />
<br />
此安全更新可解决 Microsoft .NET Framework 中两个秘密报告的漏洞和一个公开披露的漏洞。如果用户使用能够实例化 XBAP 应用程序的浏览器访问包含特制 OpenType 字体 (OTF) 文件的网站，则最严重的漏洞可能允许远程执行代码。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;"><strong>Windows 公共控件库中的漏洞可能允许远程执行代码 (2864058)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者将特制的 Web 请求发送到受影响的系统上运行的 ASP .NET Web 应用程序，该漏洞可能允许远程执行代码。攻击者可能利用此漏洞，无需身份验证即可运行任意代码。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server 中的漏洞可能允许远程执行代码 (2885089)</strong><br />
<br />
此安全更新可解决 Microsoft Office 服务器软件中两个秘密报告的漏洞。如果用户在 Microsoft SharePoint Server、Microsoft Office Services 或 Web Apps 的受影响版本中打开特制 Office 文件，则最严重的漏洞可能允许远程执行代码。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft Server 软件</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel 中的漏洞可能允许远程执行代码 (2885080)</strong><br />
<br />
此安全更新解决 Microsoft Office 中两个秘密报告的漏洞。如果用户使用受影响的 Microsoft Excel 版本或者其他受影响的 Microsoft Office 软件打开特制的 Office 文件，则这些漏洞可能允许远程执行代码。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word 中的漏洞可能允许远程执行代码 (2885084)</strong><br />
<br />
此安全更新解决 Microsoft Office 中两个秘密报告的漏洞。如果特制文件在 Microsoft Word 的受影响版本或其他受影响的 Microsoft Office 软件中打开，则这些漏洞可能允许远程执行代码。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;"><strong>Silverlight 中的漏洞可能允许信息泄露 (2890788)</strong><br />
<br />
此安全更新解决了 Microsoft Silverlight 中一个秘密报告的漏洞。如果攻击者拥有包含可以利用此漏洞的特制 Silverlight 应用程序的网站，然后诱使用户查看该网站，则该漏洞可能允许信息泄露。攻击者还可能利用受到破坏的网站以及接受或宿主用户提供的内容或广告的网站。此类网站可能包含可以利用此漏洞的特制内容。但是在所有情况下，攻击者无法强制用户访问网站。相反，攻击者必须诱使用户访问该网站，通常是让用户单击电子邮件或 Instant Messenger 消息中的链接使用户链接到攻击者的网站。它还可能使用横幅广告或其他方式显示特制的 Web 内容，以便将 Web 内容传递至受影响的系统。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">无需重新启动</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。

<p> </p>
<table style="border:1px solid black;">  
<thead>  
<tr class="header">  
<th>公告 ID</th>  
<th>漏洞标题</th>  
<th>CVE ID</th>  
<th>最新软件版本的利用评估</th>  
<th>较旧软件版本的利用评估</th>  
<th>拒绝服务利用评估</th>  
<th>重要注意事项</th>  
</tr>  
</thead>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3872">CVE-2013-3872</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3873">CVE-2013-3873</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3874">CVE-2013-3874</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3875">CVE-2013-3875</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3882">CVE-2013-3882</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3885">CVE-2013-3885</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3886">CVE-2013-3886</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3893">CVE-2013-3893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。<br />
<br />
Microsoft 获悉尝试通过 Internet Explorer 8 和 Internet Explorer 9 利用此漏洞的目标攻击。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3897">CVE-2013-3897</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">Microsoft 获悉尝试在 Internet Explorer 8 中利用此漏洞的目标攻击。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">OpenType 字体分析漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">此漏洞也影响 <a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Windows USB 描述符漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3200">CVE-2013-3200</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Win32k 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3879">CVE-2013-3879</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">应用容器特权提升漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3880">CVE-2013-3880</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">这是一个可能导致特权提升的信息泄露漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Win32k 空页漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3881">CVE-2013-3881</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">DirectX 图形内核子系统双重提取漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3888">CVE-2013-3888</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">TrueType 字体 CMAP 表漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3894">CVE-2013-3894</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">OpenType 字体分析漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞也影响 <a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">实体扩展漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3860">CVE-2013-3860</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">JSON 分析漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3861">CVE-2013-3861</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。<br />
<br />
此漏洞已公开披露。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;">Comctl32 整数溢出漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3195">CVE-2013-3195</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Microsoft Excel 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞也影响 <a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">参数注入漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3895">CVE-2013-3895</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞也影响 <a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Microsoft Excel 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3890">CVE-2013-3890</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3891">CVE-2013-3891</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3892">CVE-2013-3892</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;">Silverlight 漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3896">CVE-2013-3896</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个可能导致安全功能绕过的信息泄露漏洞。</td>
</tr>  
</tbody>  
</table>
  
受影响的软件  
------------
  
  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">  
<tr>  
<th colspan="5" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
（严重）  
Internet Explorer 7  
(2879017)  
（严重）  
Internet Explorer 8  
(2879017)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2847311)  
（严重）  
Windows XP Service Pack 3  
(2862330)  
（重要）  
Windows XP Service Pack 3  
(2862335)  
（重要）  
Windows XP Service Pack 3  
(2868038)  
（重要）  
Windows XP Service Pack 3  
(2883150)  
（严重）  
Windows XP Service Pack 3  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4  
(2861188)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
（严重）  
Internet Explorer 7  
(2879017)  
（严重）  
Internet Explorer 8  
(2879017)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2847311)  
（严重）  
Windows XP Professional x64 Edition Service Pack 2  
(2862330)  
（重要）  
Windows XP Professional x64 Edition Service Pack 2  
(2862335)  
（重要）  
Windows XP Professional x64 Edition Service Pack 2  
(2868038)  
（重要）  
Windows XP Professional x64 Edition Service Pack 2  
(2883150)  
（严重）  
Windows XP Professional x64 Edition Service Pack 2  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4  
(2861188)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2864058)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
（中等）  
Internet Explorer 7  
(2879017)  
（中等）  
Internet Explorer 8  
(2879017)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2847311)  
（严重）  
Windows Server 2003 Service Pack 2  
(2862330)  
（重要）  
Windows Server 2003 Service Pack 2  
(2862335)  
（重要）  
Windows Server 2003 Service Pack 2  
(2868038)  
（重要）  
Windows Server 2003 Service Pack 2  
(2883150)  
（严重）  
Windows Server 2003 Service Pack 2  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4  
(2861188)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2864058)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
（中等）  
Internet Explorer 7  
(2879017)  
（中等）  
Internet Explorer 8  
(2879017)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2847311)  
（严重）  
Windows Server 2003 x64 Edition Service Pack 2  
(2862330)  
（重要）  
Windows Server 2003 x64 Edition Service Pack 2  
(2862335)  
（重要）  
Windows Server 2003 x64 Edition Service Pack 2  
(2868038)  
（重要）  
Windows Server 2003 x64 Edition Service Pack 2  
(2883150)  
（严重）  
Windows Server 2003 x64 Edition Service Pack 2  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4  
(2861188)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2864058)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2879017)  
（中等）  
Internet Explorer 7  
(2879017)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2847311)  
（严重）  
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2862330)  
（重要）  
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2862335)  
（重要）  
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2868038)  
（重要）  
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2883150)  
（严重）  
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
（重要）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2864058)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
（严重）  
Internet Explorer 8  
(2879017)  
（严重）  
Internet Explorer 9  
(2879017)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2847311)  
（严重）  
Windows Vista Service Pack 2  
(2855844)  
（严重）  
Windows Vista Service Pack 2  
(2862330)  
（重要）  
Windows Vista Service Pack 2  
(2862335)  
（重要）  
Windows Vista Service Pack 2  
(2864202)  
（重要）  
Windows Vista Service Pack 2  
(2868038)  
（重要）  
Windows Vista Service Pack 2  
(2876284)  
（重要）  
Windows Vista Service Pack 2  
(2883150)  
（严重）  
Windows Vista Service Pack 2  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4  
(2861188)  
（严重）  
Microsoft .NET Framework 4.5  
(2861193)  
（严重）  
Microsoft .NET Framework 4.5  
(2861208)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2864058)  
（没有严重等级）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
（严重）  
Internet Explorer 8  
(2879017)  
（严重）  
Internet Explorer 9  
(2879017)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2847311)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(2855844)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(2862330)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(2862335)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(2864202)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(2868038)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(2876284)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(2883150)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4  
(2861188)  
（严重）  
Microsoft .NET Framework 4.5  
(2861193)  
（严重）  
Microsoft .NET Framework 4.5  
(2861208)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2864058)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
（中等）  
Internet Explorer 8  
(2879017)  
（中等）  
Internet Explorer 9  
(2879017)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2847311)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2855844)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2862330)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2862335)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2864202)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2868038)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2876284)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2883150)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4  
(2861188)  
（严重）  
Microsoft .NET Framework 4.5  
(2861193)  
（严重）  
Microsoft .NET Framework 4.5  
(2861208)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2864058)  
（没有严重等级）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
（中等）  
Internet Explorer 8  
(2879017)  
（中等）  
Internet Explorer 9  
(2879017)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2847311)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2855844)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2862330)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2862335)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2864202)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2868038)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2876284)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2883150)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4  
(2861188)  
（严重）  
Microsoft .NET Framework 4.5  
(2861193)  
（严重）  
Microsoft .NET Framework 4.5  
(2861208)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2864058)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2847311)  
（严重）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2862330)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2862335)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2864202)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2868038)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2876284)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2883150)  
（严重）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
（重要）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2864058)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
（严重）  
Internet Explorer 9  
(2879017)  
（严重）  
Internet Explorer 10  
(2879017)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2847311)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(2855844)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(2862330)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(2862335)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(2864202)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(2868038)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(2876284)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(2883150)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2861698)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2863240)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4.5  
(2861208)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2864058)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
（严重）  
Internet Explorer 9  
(2879017)  
（严重）  
Internet Explorer 10  
(2879017)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2847311)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2855844)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2862330)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2862335)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2864202)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2868038)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2876284)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2883150)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2861698)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2863240)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4.5  
(2861208)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2864058)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
（中等）  
Internet Explorer 9  
(2879017)  
（中等）  
Internet Explorer 10  
(2879017)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2847311)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2855844)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2862330)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2862335)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2864202)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2868038)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2876284)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2883150)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2861698)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2863240)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4.5  
(2861208)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2864058)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2847311)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2855844)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2862330)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2862335)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2864202)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2868038)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2876284)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2883150)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2863240)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2864058)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2879017)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2847311)  
（严重）  
Windows 8（用于 32 位系统）  
(2862330)  
（重要）  
Windows 8（用于 32 位系统）  
(2862335)  
（重要）  
Windows 8（用于 32 位系统）  
(2863725)  
（重要）  
Windows 8（用于 32 位系统）  
(2864202)  
（重要）  
Windows 8（用于 32 位系统）  
(2868038)  
（重要）  
Windows 8（用于 32 位系统）  
(2883150)  
（严重）  
Windows 8（用于 32 位系统）  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
（严重）  
Microsoft .NET Framework 3.5  
(2861704)  
（重要）  
Microsoft .NET Framework 3.5  
(2863243)  
（重要）  
Microsoft .NET Framework 4.5  
(2861702)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2864058)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2879017)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）  
(2847311)  
（严重）  
Windows 8（用于 64 位系统）  
(2862330)  
（重要）  
Windows 8（用于 64 位系统）  
(2862335)  
（重要）  
Windows 8（用于 64 位系统）  
(2863725)  
（重要）  
Windows 8（用于 64 位系统）  
(2864202)  
（重要）  
Windows 8（用于 64 位系统）  
(2868038)  
（重要）  
Windows 8（用于 64 位系统）  
(2883150)  
（严重）  
Windows 8（用于 64 位系统）  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
（严重）  
Microsoft .NET Framework 3.5  
(2861704)  
（重要）  
Microsoft .NET Framework 3.5  
(2863243)  
（重要）  
Microsoft .NET Framework 4.5  
(2861702)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）  
(2864058)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2879017)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2847311)  
（严重）  
Windows Server 2012  
(2862330)  
（重要）  
Windows Server 2012  
(2862335)  
（重要）  
Windows Server 2012  
(2863725)  
（重要）  
Windows Server 2012  
(2864202)  
（重要）  
Windows Server 2012  
(2868038)  
（重要）  
Windows Server 2012  
(2883150)  
（严重）  
Windows Server 2012  
(2884256)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
（严重）  
Microsoft .NET Framework 3.5  
(2861704)  
（重要）  
Microsoft .NET Framework 3.5  
(2863243)  
（重要）  
Microsoft .NET Framework 4.5  
(2861702)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2864058)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2879017)  
（严重）
</td>
<td style="border:1px solid black;">
Windows RT  
(2847311)  
（严重）  
Windows RT  
(2862330)  
（重要）  
Windows RT  
(2862335)  
（重要）  
Windows RT  
(2863725)  
（重要）  
Windows RT  
(2864202)  
（重要）  
Windows RT  
(2868038)  
（重要）  
Windows RT  
(2883150)  
（严重）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2861702)  
（重要）
</td>
<td style="border:1px solid black;">
Windows RT  
(2864058)  
（没有严重等级）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
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
**无**
</td>
<td style="border:1px solid black;">
**无**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>  
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8.1（用于 64 位系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>  
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
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
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
**无**
</td>
<td style="border:1px solid black;">
**无**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>  
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
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows RT 8.1
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
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
**无**
</td>
<td style="border:1px solid black;">
**无**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>  
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
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
**无**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2847311)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2862330)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2862335)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2864202)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2876284)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2883150)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2864058)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2847311)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2862330)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2862335)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2864202)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2876284)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2883150)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2864058)  
（严重）
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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2847311)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2862330)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2862335)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2864202)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2876284)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2883150)  
（严重）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2863240)  
（重要）  
Microsoft .NET Framework 4  
(2858302)  
（重要）  
Microsoft .NET Framework 4.5  
(2861208)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2864058)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2847311)  
（严重）  
Windows Server 2012（服务器核心安装）  
(2862330)  
（重要）  
Windows Server 2012（服务器核心安装）  
(2862335)  
（重要）  
Windows Server 2012（服务器核心安装）  
(2863725)  
（重要）  
Windows Server 2012（服务器核心安装）  
(2864202)  
（重要）  
Windows Server 2012（服务器核心安装）  
(2883150)  
（严重）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
（严重）  
Microsoft .NET Framework 3.5  
(2861704)  
（重要）  
Microsoft .NET Framework 3.5  
(2863243)  
（重要）  
Microsoft .NET Framework 4.5  
(2861702)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2864058)  
（严重）
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
不适用
</td>
</tr>
</table>

**MS13-080 的注释**

<sup>[1]</sup>对于 Internet Explorer 11，客户需要应用 Windows RT 8.1、Windows 8.1 和 Windows Server 2012 R2 更新汇总： 2013 年 10 月 (2883200)。请注意，2883200 更新汇总包含安全性和与安全性无关的更改。有关详细信息和可用的下载链接，请参阅 [Microsoft 知识库文章 2883200](http://support.microsoft.com/kb/2883200)。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft Word 2003 Service Pack 3  
(2826020)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2827324)  
（重要）  
Microsoft Office 2007 Service Pack 3  
(2760585)  
（重要）  
Microsoft Office 2007 Service Pack 3  
(2760591)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2827330)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
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
Microsoft Office 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1（32 位版本）  
(2826033)  
（重要）  
Microsoft Office 2010 Service Pack 1（32 位版本）  
(2826023)  
（重要）  
Microsoft Office 2010 Service Pack 1（32 位版本）  
(2826035)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1（64 位版本）  
(2826033)  
（重要）  
Microsoft Office 2010 Service Pack 1（64 位版本）  
(2826023)  
（重要）  
Microsoft Office 2010 Service Pack 1（64 位版本）  
(2826035)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(2826033)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2826023)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2826035)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(2826033)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2826023)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2826035)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
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
Microsoft Office 2013（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013（32 位版本）  
(2827238)  
（重要）  
Microsoft Office 2013（32 位版本）  
(2817623)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013（64 位版本）  
(2827238)  
（重要）  
Microsoft Office 2013（64 位版本）  
(2817623)  
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
Microsoft Excel 2013 RT  
(2827238)  
（重要）  
Microsoft Office 2013 RT  
(2817623)  
（重要）
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
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
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
**无**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2889496)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
其他 Microsoft Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
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
Microsoft Office 兼容包 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2827326)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2827329)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2827328)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>


#### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc)（32 位版本）  
(2596741)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc)（64 位版本）  
(2596741)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1 (wssloc)  
(2589365)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wssloc)  
(2589365)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (pptserver)  
(2760561)  
（重要）
</td>
</tr>
</table>

**MS13-084 的注释**

有关相同公告标识符下的更多更新文件，请参阅本部分“**受影响的软件**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft Office Services 和 Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
（重要）  
Word Automation Services  
(2826022)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
（重要）  
Word Automation Services  
(2826022)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Excel Services  
(2752002)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Word Automation Services  
(2826036)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office Web Apps 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 1  
(2826030)  
（重要）  
Microsoft Excel Web App 2010 Service Pack 1  
(2826028)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2826030)  
（重要）  
Microsoft Excel Web App 2010 Service Pack 2  
(2826028)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office Web Apps 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2827222)  
（重要）
</td>
</tr>
</table>

**MS13-084 的注释**

有关相同公告标识符下的更多更新文件，请参阅本部分“**受影响的软件**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-087**](http://go.microsoft.com/fwlink/?linkid=324590)
</td>
</tr>
<tr class="alternateRow">
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
安装在 Mac 上的 Microsoft Silverlight 5  
(2890788)  
（重要）  
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(2890788)  
（重要）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5  
(2890788)  
（重要）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(2890788)  
（重要）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5  
(2890788)  
（重要）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(2890788)  
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

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](http://technet.microsoft.com/security/cc297183)。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

**MS13-080**

-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3872)
-   Yenteasy - Security Research 的 Jose A. Vazquez 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3873)
-   Amol Naik 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3874)
-   一位匿名研究人员与 [VeriSign iDefense Labs](http://labs.idefense.com) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3874)
-   Yenteasy - Security Research 的 Jose A. Vazquez 与 [VeriSign iDefense Labs](http://labs.idefense.com) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3875)
-   [Google Security Team](http://www.google.com/) 的 Ivan Fratric 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3882)
-   Yenteasy - Security Research 的 Jose A. Vazquez 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3882)
-   Yenteasy - Security Research 的 Jose A. Vazquez 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3885)
-   Yenteasy - Security Research 的 Jose A. Vazquez 与 [VeriSign iDefense Labs](http://labs.idefense.com) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3886)
-   [LAC Co.](http://www.lac.co.jp/) 的 Yoshihiro Ishikawa 与我们合作处理了 Internet Explorer 内存损坏漏洞 (CVE-2013-3893)
-   Hoodie22 与荷兰的国家网络安全中心同我们合作处理了 Internet Explorer 内存损坏漏洞 (CVE-2013-3897)
-   Trustwave SpiderLabs Team 的 Daniel Chechik 与我们合作处理了 Internet Explorer 内存损坏漏洞 (CVE-2013-3897)
-   [IOprotect GmbH](http://ioprotect.ch/) 的 Renato Ettisberger 与我们合作处理了 Internet Explorer 内存损坏漏洞 (CVE-2013-3897)

**MS13-081**

-   一名匿名研究人员与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 报告了 OpenType 字体分析漏洞 (CVE-2013-3128)
-   [NCC Group](http://www.nccgroup.com/) 的 Andy Davis 报告了 Windows USB 描述符漏洞 (CVE-2013-3200)
-   ANSSI 的 Lucas Bouillot 报告了 Windows USB 描述符漏洞 (CVE-2013-3200)
-   [Endgame](http://www.endgame.com/) 的 Seth Gibson 和 Dan Zentnerfor 报告了 Win32k 空页漏洞 (CVE-2013-3881)
-   ZombiE 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 TrueType 字体 CMAP 表漏洞 (CVE-2013-3895)

**MS13-082**

-   一名匿名研究人员与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 报告了 OpenType 字体分析漏洞 (CVE-2013-3128)
-   [Context Information Security](http://www.contextis.com/) 的 James Forshaw 报告了实体扩展漏洞 (CVE-2013-3860)

**MS13-083**

-   孙晓山报告了 Comctl32 整数溢出漏洞 (CVE-2013-3195)

**MS13-084**

-   [Google Security Team](http://www.google.com/) 的 Mateusz Jurczyk、Ivan Fratric 和 Ben Hawkes 报告了 Microsoft Excel 内存损坏漏洞 (CVE-2013-3889)
-   Nutan kumar panda 报告了参数注入漏洞 (CVE-2013-3895)
-   [National Institutes of Health](http://nih.gov/) 的 Ari Elias-Bachrach 和 Angela Kelsofor 与我们一起努力处理了此公告中包括的纵深防御更改

**MS13-085**

-   [Google Security Team](http://www.google.com/) 的 Mateusz Jurczyk、Ivan Fratric 和 Ben Hawkes 报告了 Microsoft Excel 内存损坏漏洞 (CVE-2013-3889)
-   [Google Security Team](http://www.google.com/) 的 Mateusz Jurczyk、Ivan Fratric 和 Ben Hawkes 报告了 Microsoft Excel 内存损坏漏洞 (CVE-2013-3890)

**MS13-086**

-   Yuhong Bao 报告了内存损坏漏洞 (CVE-2013-3891)
-   [Google Security Team](http://www.google.com/) 的 Mateusz Jurczyk、Ivan Fratric 和 Ben Hawkes 报告了内存损坏漏洞 (CVE-2013-3892)

**MS13-087**

-   Vitaliy Toropov 报告了 Silverlight 漏洞 (CVE-2013-3896)

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](http://technet.microsoft.com/security/bb980617)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](http://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2013 年 10 月 8 日）： 已发布公告摘要。
-   V1.1（2013 年 10 月 10 日）： 对于 MS13-080，从利用指数中删除了对 CVE-2013-3871. 的利用评估。最初利用指数中包含此 CVE 属于文档错误。计划在以后的安全更新中解决 CVE-2013-3871。这仅仅是一个信息更改。对于 MS13-082，更新了公告以表明 Windows Server 2012 的服务器核心安装受到在 2861194 更新中解决的漏洞影响。检测逻辑或安全更新文件未发生更改。已经成功更新了其系统的客户不需要执行任何操作。
-   V1.2 （2013 年 11 月 6 日）： 对于 MS13-084，更正了 Microsoft Office Web Apps Server 2013 (2827222) 更新的产品名称。

*Built at 2014-04-18T01:50:00Z-07:00*
