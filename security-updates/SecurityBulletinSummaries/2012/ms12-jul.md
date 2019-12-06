---
TOCTitle: 'MS12-JUL'
Title: 'Microsoft 安全公告摘要（2012 年 7 月）'
ms:assetid: 'ms12-jul'
ms:contentKeyID: 61236969
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms12-jul(v=Security.10)'
---



Microsoft 安全公告摘要（2012 年 7 月）
======================================

发布时间: 2012年7月10日 | 更新时间: 2012年12月12日

**版本:** 5.1

本公告摘要列出了 2012 年 7 月发布的安全公告。

对于 2012 年 7 月发布的安全公告，本公告摘要替代 2012 年 7 月 5 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2012 年 7 月 11 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 7 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032518600)。此日期之后，此网络广播按需提供。有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://go.microsoft.com/fwlink/?linkid=217214)。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254824"><strong>MS12-043</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services 中的漏洞可能允许远程执行代码 (2722479)</strong><br />
<br />
此安全更新解决了 Microsoft XML Core Services 中一个公开披露的漏洞。如果用户使用 Internet Explorer 查看特制网页，则该漏洞可能允许远程执行代码。但是，攻击者无法强迫用户访问这样的网站。相反，攻击者必须诱使用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft Office，<br />  
Microsoft 开发工具，<br />
Microsoft Server 软件</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254377"><strong>MS12-044</strong></a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2719177)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中两个秘密报告的漏洞。如果用户使用 Internet Explorer 查看特制网页，则所有漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254441"><strong>MS12-045</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft Data Access Components</strong> <strong>中的漏洞可能允许远程执行代码 (2698365)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户查看特制网页，此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252510"><strong>MS12-046</strong></a></td>
<td style="border:1px solid black;"><strong>Visual Basic for Applications 的漏洞可能允许远程执行代码 (2707960)</strong><br />
<br />
此安全更新解决 Microsoft Visual Basic for Applications 中一个公开披露的漏洞。如果用户打开与特制动态链接库 (DLL) 文件位于同一目录下的合法 Microsoft Office 文件（例如 .docx 文件），此漏洞可能允许远程执行代码。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。如果用户使用管理用户权限登录，攻击者便可完全控制受影响的系统。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft 开发工具</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254380"><strong>MS12-047</strong></a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升 (2718523)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中一个公开披露和一个秘密报告的漏洞。这些漏洞在攻击者登录系统并运行特制应用程序时允许提升特权。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239507"><strong>MS12-048</strong></a></td>
<td style="border:1px solid black;"><strong>Windows Shell 中的漏洞可能允许远程执行代码 (2691442)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开包含特制名称的文件或目录，则该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251035"><strong>MS12-049</strong></a></td>
<td style="border:1px solid black;"><strong>TLS 中的漏洞可能允许信息泄露 (2655992)</strong><br />
<br />
此安全更新解决了 TLS 中一个公开披露的漏洞。如果攻击者截取受影响的系统中经过加密的 Web 通信，则该漏洞可能会允许信息泄露。不使用 CBC 模式的所有密码套件不受影响。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;"><strong>SharePoint 中的漏洞可能允许特权提升 (2695502)</strong><br />
<br />
此安全更新可解决 Microsoft SharePoint 和 Windows SharePoint Services 中一个公开披露的漏洞和五个秘密报告的漏洞。如果用户单击可将用户定向到目标 SharePoint 网站的特制 URL，则最严重的漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft Server 软件</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255000"><strong>MS12-051</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft Office for Mac 中的漏洞可能允许特权提升 (2721015)</strong><br />
<br />
此安全更新解决 Microsoft Office for Mac 中一个公开披露的漏洞。如果攻击者将恶意可执行文件放在受影响的系统上，然后另一用户登录并运行该恶意可执行文件，则该漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">无需重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/security/cc998259.aspx)。
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254824"><strong>MS12-043</strong></a></td>
<td style="border:1px solid black;">MSXML 未初始化的内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1889">CVE-2012-1889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。<br />
<br />
Microsoft 获悉尝试使用此漏洞的有限目标攻击。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254377"><strong>MS12-044</strong></a></td>
<td style="border:1px solid black;">缓存对象远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1522">CVE-2012-1522</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254377"><strong>MS12-044</strong></a></td>
<td style="border:1px solid black;">属性删除远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1524">CVE-2012-1524</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254441"><strong>MS12-045</strong></a></td>
<td style="border:1px solid black;">ADO 缓存大小堆溢出 RCE 漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1891">CVE-2012-1891</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252510"><strong>MS12-046</strong></a></td>
<td style="border:1px solid black;">Visual Basic for Applications 不安全库加载漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1854">CVE-2012-1854</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。<br />
<br />
Microsoft 获悉尝试使用此漏洞的有限目标攻击。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254380"><strong>MS12-047</strong></a></td>
<td style="border:1px solid black;">键盘版式漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1890">CVE-2012-1890</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">此漏洞已公开披露。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254380"><strong>MS12-047</strong></a></td>
<td style="border:1px solid black;">Win32k 错误的类型处理漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1893">CVE-2012-1893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239507"><strong>MS12-048</strong></a></td>
<td style="border:1px solid black;">命令注入漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0175">CVE-2012-0175</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251035"><strong>MS12-049</strong></a></td>
<td style="border:1px solid black;">TLS 协议漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1870">CVE-2012-1870</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。<br />
<br />
这是一个信息泄露漏洞。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">HTML 清理漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。<br />
<br />
这是一个信息泄露漏洞。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">XSS scriptresx.ashx 漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1859">CVE-2012-1859</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">用户名 SharePoint 脚本漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1861">CVE-2012-1861</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">SharePoint 反映列表参数漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1863">CVE-2012-1863</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255000"><strong>MS12-051</strong></a></td>
<td style="border:1px solid black;">Office for Mac 不正确的文件夹权限漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1894">CVE-2012-1894</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。</td>
</tr>  
</tbody>  
</table>
  
受影响的软件和下载位置  
----------------------
  
  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">  
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
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
无
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=017f1ed7-eed4-4de3-aca1-93fb25058866)  
(KB2719985)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=017f1ed7-eed4-4de3-aca1-93fb25058866)  
(KB2719985)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=496e93ac-fcce-458f-839b-25ff1ab22fde)  
(KB2698365)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=a4bc78fb-3927-4059-ae1c-35c369e39203)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=405ce29a-7c97-44de-aed9-4c90cbdaaf1b)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8324496f-aca4-4a86-833d-c22341e71cd3)  
(KB2655992)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=d27bd5e9-a3a6-411e-bc50-2b03d64fb50c)  
(KB2719985)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=aaf10833-0487-4026-805b-97543140b1fd)  
(KB2721693)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=64f8d1a4-4a9d-4ee0-8a66-d157d516afb5)  
(KB2698365)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=94029b68-5b7b-4d0e-b175-cfc2b0eba91a)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=36fc4c85-fa93-4c6b-b93a-94460e9ba23b)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5f268365-9c18-4fc7-b11e-b1f19c4a5a2a)  
(KB2655992)  
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
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
无
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=b7321c17-0e8e-4217-8da6-4c270dbfc802)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=3b56ba48-b74c-4681-8e17-715dc5d45e2c)  
(KB2721693)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=465ef3d0-df59-4f73-a06d-49a81286c01f)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d53bd571-ad30-41c7-8c5f-f217097770f5)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1f058336-4a6a-47d0-ad6f-276dc381d1db)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b13e2388-01f3-46bf-97b4-612e2778477a)  
(KB2655992)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=2b24d755-f96f-47d6-b286-2bfd4e278dcc)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=aaf10833-0487-4026-805b-97543140b1fd)  
(KB2721693)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d1955b23-5931-4891-9c11-401efcb6c05c)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5f261883-daec-4af3-8bc1-46da9c164de7)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5b6d6227-8695-4ecb-86e1-bb264f954898)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a0bd0591-62f8-40d1-93fa-7f0afc4fc09c)  
(KB2655992)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=eab0f4c6-3f2e-435d-aef7-d9230295ab15)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=68eb373e-2c1e-40db-8ad0-0a369a96255b)  
(KB2721693)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e46047d5-9a2d-48c4-b1c8-3db884c25b5c)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=60c57c8b-6d56-42de-ab1e-e4e3258c7818)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=563399b3-cb19-40e9-ba9d-0079032c8cee)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b91df558-5446-4858-92af-50cfbab27ff5)  
(KB2655992)  
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
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=f8ccdb90-66bd-471a-9c78-825d1140b5ac)  
(KB2719985)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=f8ccdb90-66bd-471a-9c78-825d1140b5ac)  
(KB2719985)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b6a75978-0c11-49fb-8aa7-c47efb3bf4e8)  
(KB2719177)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=0c43c093-296e-4e12-b995-4f9e3f00cbe0)  
(KB2698365)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3c957f8a-8f32-4a12-ade9-10a7e2984e88)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2e9a4aeb-3f34-483c-ba3a-3141164e9e8a)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7286a6e2-9c31-493f-aae3-776f72e85503)  
(KB2655992)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=e8553934-a202-4033-b9c5-27bc4207469d)  
(KB2719985)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=e8553934-a202-4033-b9c5-27bc4207469d)  
(KB2719985)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=8470af29-68e2-4fd2-bc30-3c9188e65c59)  
(KB2719177)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=4d9b91c9-a412-4344-b934-0d2fbd9526fd)  
(KB2698365)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7300636f-aefd-46bf-a7ba-780d6f939b4f)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fe8467e2-8b37-4ec2-ba9f-324918f1f045)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c62ec513-887c-4a42-a3cc-3e92631526ed)  
(KB2655992)  
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
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=42a869b9-085a-450a-b69e-f634d01075dd)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=42a869b9-085a-450a-b69e-f634d01075dd)  
(KB2719985)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4009dd66-b6d0-4c14-acde-f52d75d8f9d1)  
(KB2719177)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=a8ed6a19-c128-46e5-ae38-5fa9f843ba0d)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ed201422-7c65-4c20-a825-8cecab1aeebc)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d873c5a-57dc-4792-942e-124ce1a4ec2b)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=97030267-6b19-46ae-84ce-0bb1f91ab951)  
(KB2655992)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=f7b2d780-cc92-4f3e-b5a2-9f2ac66b6f1c)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=f7b2d780-cc92-4f3e-b5a2-9f2ac66b6f1c)  
(KB2719985)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b609981c-fda8-4085-ae8d-5b760ad4e73f)  
(KB2719177)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=043464e4-9572-419b-a03a-ca11bf918052)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e1a27c9-6495-4030-8a46-264afd78a5a1)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d49e3e7e-910a-4069-b0b0-0987bb9fdde2)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8a5f6e84-5e5b-42c3-a5b7-65defdb0665f)  
(KB2655992)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=359a86d6-e94a-4de5-83d9-6b0273115bff)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=359a86d6-e94a-4de5-83d9-6b0273115bff)  
(KB2719985)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=00638d5e-6156-4c1b-a131-3d1fff514bdb)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=76f640b8-5aab-4880-9d74-22e2a5086342)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ca890b4d-124f-4293-b8d0-69f6302b5189)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e886c5f4-7f38-4c90-905b-a682e6a8ffd0)  
(KB2655992)  
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
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=0be922a4-6b8a-4017-bc31-1cadd8cdb472)  
(KB2719177)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=ed997ae7-2e45-4620-bcbe-a5006aaca448)  
(KB2698365)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=b4bed780-b120-43a1-900e-89b3be7da8b1)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=8ab3eadf-9437-4323-8323-87dfd23245fd)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=da706b4e-7c22-4929-96d3-f8b0fa10f043)  
(KB2655992)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=0be922a4-6b8a-4017-bc31-1cadd8cdb472)  
(KB2719177)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=ed997ae7-2e45-4620-bcbe-a5006aaca448)  
(KB2698365)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b4bed780-b120-43a1-900e-89b3be7da8b1)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8ab3eadf-9437-4323-8323-87dfd23245fd)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=da706b4e-7c22-4929-96d3-f8b0fa10f043)  
(KB2655992)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=739e4f24-8433-4dc9-a106-a70ae4040606)  
(KB2719177)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=4040c290-bf41-4e14-8269-da95ee06d8e7)  
(KB2698365)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3efb0de1-252b-4b72-86f3-e747f8fa2229)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=f518f273-b3b9-4cbf-b820-05a1adc79342)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=07518fb7-031f-4fa0-836c-8f33c247868b)  
(KB2655992)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=739e4f24-8433-4dc9-a106-a70ae4040606)  
(KB2719177)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=4040c290-bf41-4e14-8269-da95ee06d8e7)  
(KB2698365)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3efb0de1-252b-4b72-86f3-e747f8fa2229)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f518f273-b3b9-4cbf-b820-05a1adc79342)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=07518fb7-031f-4fa0-836c-8f33c247868b)  
(KB2655992)  
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
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=91e8ecf8-4f6d-4e86-bc6b-617749090190)  
(KB2719177)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=e749883d-221a-411a-9c85-759d50cefa9d)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=91e8ecf8-4f6d-4e86-bc6b-617749090190)  
(KB2719177)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=e749883d-221a-411a-9c85-759d50cefa9d)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=eeab7dbb-f6ca-44bd-a172-c07fc5803fd6)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=772f2975-065d-44f3-adf8-82188bd43196)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=c9c3b471-4a81-4a44-93ad-674650454c53)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=49e182b5-4499-42a1-8180-9bb920e154cb)  
(KB2655992)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](https://www.microsoft.com/download/details.aspx?familyid=eeab7dbb-f6ca-44bd-a172-c07fc5803fd6)  
(KB2698365)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=772f2975-065d-44f3-adf8-82188bd43196)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c9c3b471-4a81-4a44-93ad-674650454c53)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=49e182b5-4499-42a1-8180-9bb920e154cb)  
(KB2655992)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
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
<th colspan="7" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
无
</td>
<td style="border:1px solid black;">
无
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
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
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ed201422-7c65-4c20-a825-8cecab1aeebc)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d873c5a-57dc-4792-942e-124ce1a4ec2b)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=97030267-6b19-46ae-84ce-0bb1f91ab951)  
(KB2655992)  
（重要）
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e1a27c9-6495-4030-8a46-264afd78a5a1)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d49e3e7e-910a-4069-b0b0-0987bb9fdde2)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8a5f6e84-5e5b-42c3-a5b7-65defdb0665f)  
(KB2655992)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）
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
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
（重要）
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
（重要）
</td>
</tr>
</table>

**MS12-043 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="5" style="border:1px solid black;">
Microsoft Office 套件和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
<td style="border:1px solid black;">
[**MS12-051**](http://go.microsoft.com/fwlink/?linkid=255000)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=c4c925b8-df99-4d4f-b939-878d77d64514)  
(KB2687627)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d49c4893-d867-4d16-90f5-354eb4757d90)<sup>[1]</sup>  
(KB2687626)  
（重要）
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
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>  
(KB2596744)  
（重要）
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
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>  
(KB2596744)  
（重要）
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
Microsoft Office 2010（32 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=a7cc8fdc-1c64-434f-87a6-72ddcc356654)  
(KB2598243)  
（重要）  
[Microsoft Office 2010（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=3050c06c-3cfc-4ce7-83cd-017d0922d597)  
(KB2553447)  
（重要）
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
Microsoft Office 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=a7cc8fdc-1c64-434f-87a6-72ddcc356654)  
(KB2598243)  
（重要）  
[Microsoft Office 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=3050c06c-3cfc-4ce7-83cd-017d0922d597)  
(KB2553447)  
（重要）
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
Microsoft Office 2010（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=ab442918-8184-4c7c-84b0-5a3635fdb005)  
(KB2598243)  
（重要）  
[Microsoft Office 2010（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=0a8af868-abf7-4aeb-813a-418a04b31608)  
(KB2553447)  
（重要）
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
Microsoft Office 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=ab442918-8184-4c7c-84b0-5a3635fdb005)  
(KB2598243)  
（重要）  
[Microsoft Office 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=0a8af868-abf7-4aeb-813a-418a04b31608)  
(KB2553447)  
（重要）
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
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
<td style="border:1px solid black;">
[**MS12-051**](http://go.microsoft.com/fwlink/?linkid=255000)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重** **等级**
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
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
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=877700ed-3d03-4d46-a77b-5063d8f7d2e3)  
(KB2721015)  
（重要）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
其他 Microsoft Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
<td style="border:1px solid black;">
[**MS12-051**](http://go.microsoft.com/fwlink/?linkid=255000)
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
无
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
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
Microsoft Office Compatibility Pack Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
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
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
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
Microsoft Groove 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
（严重）

</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
（严重）

</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=da8fa3b6-5d01-49e1-a1ce-e3f47ace102b)  
(KB2596666)  
（重要）  
[Microsoft InfoPath 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a0c826bc-aef8-4833-8471-1824a405c59f)  
(KB2596786)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=da8fa3b6-5d01-49e1-a1ce-e3f47ace102b)  
(KB2596666)  
（重要）  
[Microsoft InfoPath 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=a0c826bc-aef8-4833-8471-1824a405c59f)  
(KB2596786)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010（32 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=698e6369-253b-4dbe-b6cd-7ea5ea09e043)  
(KB2553431)  
（重要）  
[Microsoft InfoPath 2010（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=036b2482-0fb4-46f0-9c38-8bae6d0d669b)  
(KB2553322)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=698e6369-253b-4dbe-b6cd-7ea5ea09e043)  
(KB2553431)  
（重要）  
[Microsoft InfoPath 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=036b2482-0fb4-46f0-9c38-8bae6d0d669b)  
(KB2553322)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=3bf373aa-b4ad-4e1a-9578-800485ece148)  
(KB2553431)  
（重要）  
[Microsoft InfoPath 2010（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=e24337cb-83b4-424f-bc4d-0d43437228a2)  
(KB2553322)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=3bf373aa-b4ad-4e1a-9578-800485ece148)  
(KB2553431)  
（重要）  
[Microsoft InfoPath 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=e24337cb-83b4-424f-bc4d-0d43437228a2)  
(KB2553322)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**MS12-043** **的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS12-046** **的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

<sup>[1]</sup> 这些 Microsoft Office 更新适用于所有受支持的 Microsoft Office 套件以及其他包含易受攻击的共享 Office 组件的 Microsoft Office 软件。这包括但不限于 Microsoft Visio 和 Microsoft Project 的受支持版本。

**MS12-050 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 （coreserver）（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=4073d6e1-32f0-44a8-ae55-3c140ebc09d2)<sup>[1]</sup>  
(KB2596663)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 2 （xlsrvwfe）（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=d9091923-67c7-4535-b44c-40a5292a94d9)<sup>[1]</sup>  
(KB2596942)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 3（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 3 （coreserver）（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=4073d6e1-32f0-44a8-ae55-3c140ebc09d2)<sup>[1]</sup>  
(KB2596663)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 3 （xlsrvwfe）（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=d9091923-67c7-4535-b44c-40a5292a94d9)<sup>[1]</sup>  
(KB2596942)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 （coreserver）（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=b1acb373-0041-4883-8834-90a72ac04c91)<sup>[1]</sup>  
(KB2596663)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 2 （xlsrvwfe）（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=723a5553-8610-49bf-99c0-bd94926bdc0b)<sup>[1]</sup>  
(KB2596942)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 3（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 3 （coreserver）（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=b1acb373-0041-4883-8834-90a72ac04c91)<sup>[1]</sup>  
(KB2596663)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 2 （xlsrvwfe）（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=723a5553-8610-49bf-99c0-bd94926bdc0b)<sup>[1]</sup>  
(KB2596942)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 (wosrv)](https://www.microsoft.com/download/details.aspx?familyid=59cbb3d0-4ba5-4f89-b54c-ae9aa2aa3b41)  
(KB2553424)  
（重要）  
[Microsoft SharePoint Server 2010 (coreserverloc)](https://www.microsoft.com/download/details.aspx?familyid=8a853489-a3ec-4be2-8093-6a992f9c8368)  
(KB2553194)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1 (wosrv)](https://www.microsoft.com/download/details.aspx?familyid=59cbb3d0-4ba5-4f89-b54c-ae9aa2aa3b41)  
(KB2553424)  
（重要）  
[Microsoft SharePoint Server 2010 Service Pack 1 (coreserverloc)](https://www.microsoft.com/download/details.aspx?familyid=8a853489-a3ec-4be2-8093-6a992f9c8368)  
(KB2553194)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2010
</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010](https://www.microsoft.com/download/details.aspx?familyid=e2346078-fc93-4355-bc83-0d0dc1cd4b2f)  
(KB2589325)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e2346078-fc93-4355-bc83-0d0dc1cd4b2f)  
(KB2589325)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows SharePoint Services 和 Microsoft SharePoint Foundation
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 2.0
</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 2.0](https://www.microsoft.com/download/details.aspx?familyid=7a54f510-0782-44c4-848a-8ef90d332e61)<sup>[2]</sup>  
(KB2760604)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2（32 位版本）
</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=61b9f234-3d9c-41d4-854d-30ca5e6fd2a6)  
(KB2596911)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=24265175-635f-4846-afcc-f692d4710707)  
(KB2596911)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010
</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010](https://www.microsoft.com/download/details.aspx?familyid=4d610646-a0bd-492c-9077-fb2c92588c14)  
(KB2553365)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=4d610646-a0bd-492c-9077-fb2c92588c14)  
(KB2553365)  
（重要）
</td>
</tr>
</table>

**MS12-043** **的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS12-050** **的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

<sup>[1]</sup>对于 Microsoft Office SharePoint Server 2007 的受支持版本，除了 Microsoft Office SharePoint 2007 安全更新程序包（KB2596663 和 KB2596942）外，客户还需要安装 Microsoft Windows SharePoint Services 3.0 安全更新 (KB2596911)，以免受本公告中所描述的漏洞影响。

<sup>[2]</sup>此更新只能通过 Microsoft 下载中心下载。

#### Microsoft Office Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
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
Microsoft Office Web Apps 2010
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010](https://www.microsoft.com/download/details.aspx?familyid=f2d1c371-d617-4792-966e-14ae9ed6b8a1)  
(KB2598239)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f2d1c371-d617-4792-966e-14ae9ed6b8a1)  
(KB2598239)
</td>
</tr>
</table>

**MS12-050 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Expression Web
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
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
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Visual Basic for Applications
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic for Applications](https://www.microsoft.com/download/details.aspx?familyid=ea7c5762-586f-4e38-ad63-43eb05e79f4d)<sup>[1]</sup>  
(KB2688865)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK<sup>[2]</sup><sup>[3]</sup>  
（重要）
</td>
</tr>
</table>

**MS12-043** **的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS12-046** **的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

<sup>[1]</sup>此更新包适用于 Microsoft Visual Basic for Applications runtime (Vbe6.dll) 的受支持版本，只能从 Microsoft 下载中心获得。

<sup>[2]</sup>VBA SDK 的受支持版本是 Microsoft Visual Basic for Applications SDK 6.3、Microsoft Visual Basic for Applications SDK 6.4 和 Microsoft Visual Basic for Applications SDK 6.5。

<sup>[3]</sup>可通过 Summit Software Company 为独立软件供应商 (ISV) 提供 Visual Basic for Applications SDK 的更新版本以解决此公告中描述的漏洞。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx)。

**SystemCenter Configuration Manager**

System Center Configuration Manager 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 System Center Configuration Manager，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

System Center Configuration Manager 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。System Center Configuration Manager 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关管理员如何使用 System Center Configuration Manager 部署更新的详细信息，请参阅[软件更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)。有关 System Center Configuration Manager 的详细信息，请访问 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。SMS 的下一版本 System Center Configuration Manager 现已可用；请参阅前面的部分 **System Center Configuration Manager**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

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

-   [Google Security Team](http://www.google.com/) 与我们合作处理了 MS11-043 中描述的一个问题
-   [Qihoo 360 Security Center](http://www.360.cn/) 报告了 MS12-043 中描述的一个问题
-   spa-s3c.blogspot.com 的 Jose A.Vazquez，与[VeriSign iDefense Labs](http://labs.idefense.com/) 合作报告了 MS12-044 中描述的一个问题
-   Omair 与 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作报告了 MS12-044 中描述的一个问题
-   一位匿名研究员与 [TippingPoint 的](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 MS12-045 中描述的一个问题
-   [Huawei Security Labs](http://www.huawei.com) 的 Bai Haowen 报告了 MS12-046 中描述的一个问题
-   [Core Security Technologies](http://www.coresecurity.com/) 的 Nicolas Economou 报告了 MS12-047 中描述的一个问题
-   [Qihoo 360 Security Center](http://www.360.cn/) 报告了在 MS12-047 中描述的一个问题
-   Neusoft Corporation 的 Lufeng Li 与 [Secunia Research](http://secunia.com/) 合作报告了 MS12-047 中描述的一个问题
-   [IBM Security Systems - Application Security](http://blog.watchfire.com/) 的 Adi Cohen 报告了 MS12-048 中描述的一个问题
-   [IBM Security Systems - Application Security](http://blog.watchfire.com/) 的 Adi Cohen 报告了 MS12-050 中描述的一个问题
-   [Salesforce.com Product Security Team](https://trust.salesforce.com/) 的 Yang Yang 报告了 MS12-050 中描述的一个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](http://technet.microsoft.com/security/bb980617.aspx)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](http://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2012 年 7 月 10 日）： 已发布公告摘要。
-   V1.1（2012 年 7 月 10 日）： 已从利用指数中删除 CVE-2012-1860，因为漏洞的严重等级为“中等”。仅包括已包含在利用指数中的公告中严重等级为“严重”或“重要”的漏洞。
-   V2.0（2012 年 8 月 15 日）： 对 MS12-043 添加了 Microsoft XML Core Services 5.0 的下载链接。
-   V3.0（2012 年 10 月 9 日）： 对于 MS12-043，将 Windows 8 和 Windows Server 2012 的受支持版本上安装的 Microsoft XML Core Services 4.0 添加到受影响的软件。有关详细信息，请参阅 MS12-043 公告。
-   V4.0（2012 年 11 月 13 日）： 对于 MS12-046，已将 Microsoft Office 2003 Service Pack 3 的 KB2598361 更新替换为 KB2687626 更新。请参阅 MS12-046 公告了解详细信息。
-   V5.0（2012 年 12 月 11 日）： 对于 MS12-043，针对 Microsoft Office 2003 Service Pack 3 上的 Microsoft XML Core Services 5.0 将更新 KB2687324 替换为更新 KB2687627，针对安装在 Microsoft Groove 2007、Microsoft Groove Server 2007 和 Microsoft Office SharePoint Server 2007 上的 Microsoft XML Core Services 5.0 将 KB2596679 更新替换为更新 KB2687497。有关详细信息，请参阅公告 MS12-043。
-   V5.1（2012 年 12 月 12 日）： 对于 MS12-050，修订的公告摘要宣布了一项可用于Microsoft Windows SharePoint Services2.0 的更新。此更新只能从 Microsoft 下载中心下载。

*Built at 2014-04-18T01:50:00Z-07:00*
