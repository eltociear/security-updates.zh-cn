---
TOCTitle: 'MS12-OCT'
Title: 'Microsoft 安全公告摘要（2012 年 10 月）'
ms:assetid: 'ms12-oct'
ms:contentKeyID: 61236974
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms12-oct(v=Security.10)'
---



Microsoft 安全公告摘要（2012 年 10 月）
=======================================

发布时间: 2012年10月9日 | 更新时间: 2012年10月23日

**版本:** 1.3

本公告摘要列出了 2012 年 10 月发布的安全公告。

随着 2012 年 10 月安全公告的发布，本公告摘要替代 2012 年 10 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2012 年 10 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 10 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522558&culture=en-us)。此日期之后，此网络广播[按需](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522558&culture=en-us)提供。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

### 公告信息

#### 摘要

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260965">MS12-064</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word 中的漏洞可能允许远程执行代码 (2742319)</strong><br />
<br />
此安全更新解决 Microsoft Office 中两个秘密报告的漏洞。如果用户打开或预览特制的 RTF 文件，较严重的漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft Server 软件</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263959">MS12-065</a></td>
<td style="border:1px solid black;"><strong>Microsoft Works 中的漏洞可能允许远程执行代码 (2754670)</strong><br />
<br />
此安全更新可解决 Microsoft Works 中一个秘密报告的漏洞。如果用户使用 Microsoft Works 打开特制 Microsoft Word 文件，该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260957">MS12-066</a></td>
<td style="border:1px solid black;"><strong>HTML 清理组件中的漏洞可能允许特权提升 (2741517)</strong><br />
<br />
此安全更新可解决 Microsoft Office、Microsoft Communications Platforms、Microsoft Server 软件和 Microsoft Office Web Apps 中一个公开披露的漏洞。如果攻击者将特制内容发送给用户，则该漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft 服务器软件,<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259736">MS12-067</a></td>
<td style="border:1px solid black;"><strong>FAST Search Server 2010 for SharePoint 分析中的漏洞可能允许执行远程代码 (2742321)</strong><br />
<br />
此安全更新解决了 Microsoft FAST Search Server 2010 for SharePoint 中一个公开披露的漏洞。该漏洞可能允许使用受限制的令牌在用户帐户的安全上下文中远程执行代码。只有当启用高级筛选包时，FAST Search Server for SharePoint 才会受影响。默认情况下，高级筛选包已禁用。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft Server 软件</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257912">MS12-068</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许特权提升 (2724197)</strong><br />
<br />  
此安全更新解决了 Microsoft Windows 所有受支持的版本（Windows 8 和 Windows Server 2012 除外）中一个秘密报告的漏洞。对于 Windows XP、Windows Server 2003、Windows Vista、Windows Server 2008、Windows 7 和 Windows Server 2008 R2 的所有受支持版本，此安全更新的等级为“重要”。<br />  
<br />
如果攻击者登录系统并运行特制应用程序，则该漏洞可能允许提升特权。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263962">MS12-069</a></td>
<td style="border:1px solid black;"><strong>Kerberos 中的漏洞可能允许拒绝服务 (2743555)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果远程攻击者向 Kerberos 服务器发送特制会话请求，则该漏洞可能允许拒绝服务。采用防火墙最佳做法和标准的默认防火墙配置，有助于保护网络免受从企业外部发起的攻击。按照最佳做法，应使连接到 Internet 的系统所暴露的端口数尽可能少。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263997">MS12-070</a></td>
<td style="border:1px solid black;"><strong>SQL Server 中的漏洞可能允许特权提升 (2754849)</strong><br />
<br />
此安全更新解决了运行 SQL Server Reporting Services (SSRS) 的系统上的 Microsoft SQL Server 中一个秘密报告的漏洞。该漏洞是一个跨站点脚本执行 (XSS) 漏洞，可能允许特权提升，使攻击者能够在目标用户的上下文中的 SSRS 站点上执行任意命令。攻击者可以通过向用户发送特制的链接并诱使用户单击该链接来利用此漏洞。攻击者还可以通过提供一个包含试图利用此漏洞的网页的网站来利用此漏洞。另外，接受或宿主用户提供的内容或广告的网站以及受到破坏的网站可能包含可能利用此漏洞的特制内容。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260965">MS12-064</a></td>
<td style="border:1px solid black;">Word PAPX 分区损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0182">CVE-2012-0182</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260965">MS12-064</a></td>
<td style="border:1px solid black;">RTF 文件 listid 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2528">CVE-2012-2528</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263959">MS12-065</a></td>
<td style="border:1px solid black;">Works 堆漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2550">CVE-2012-2550</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260957">MS12-066</a></td>
<td style="border:1px solid black;">HTML 清理漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2520">CVE-2012-2520</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259736">MS12-067</a></td>
<td style="border:1px solid black;">FAST Search Server 2010 for SharePoint 的高级筛选包包含多个可利用的漏洞</td>
<td style="border:1px solid black;">Oracle Outside In 包含多个可利用的漏洞</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">* 多个漏洞，详情请参阅 MS12-067 公告。<br />
<br />
这些漏洞已被公开披露。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257912">MS12-068</a></td>
<td style="border:1px solid black;">Windows 内核整数溢出漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2529">CVE-2012-2529</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263962">MS12-069</a></td>
<td style="border:1px solid black;">Kerberos 空指针解除引用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2551">CVE-2012-2551</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263997">MS12-070</a></td>
<td style="border:1px solid black;">反射型 XSS 漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2552">CVE-2012-2552</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
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
<th colspan="3" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
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
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6aa1e4b3-273a-49ff-8086-0d2c16dd14f3)  
(KB2724197)  
（重要）
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
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3c509cc0-63a1-4cc7-b7f9-cc9f0f12b378)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
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
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6c7dd00a-a983-477b-88b1-dc16f1b5e42a)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eaac4dae-62e6-4020-8b4d-a95e7e0e11f1)  
(KB2724197)  
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
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=315cc115-1496-471f-8887-f334a1ca8246)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
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
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=828ca8a2-777c-4b41-8d97-caed894a37cb)  
(KB2724197)  
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
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=731d67dc-e028-42e4-8ef3-454f74835593)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
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
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=526f786b-7aef-4a1f-b03d-587baadf3f5b)  
(KB2724197)  
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
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5697076c-541f-42b7-8dc3-e8bd4a25fda8)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6216b875-c7a6-4d62-8062-49996ac7a478)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
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
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=593a29c3-c459-4a39-9f25-016a5268fc7d)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=4ffa9c0e-26b1-4309-bfb4-fa5374f28d6c)  
(KB2743555)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=593a29c3-c459-4a39-9f25-016a5268fc7d)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=4ffa9c0e-26b1-4309-bfb4-fa5374f28d6c)  
(KB2743555)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=2d273f99-3460-4e84-9f2d-2a349bfc7ce6)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d5584b7d-434f-49fc-9c30-ef16c40d475f)  
(KB2743555)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2d273f99-3460-4e84-9f2d-2a349bfc7ce6)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d5584b7d-434f-49fc-9c30-ef16c40d475f)  
(KB2743555)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
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
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=848af16d-c5f7-4a70-b6a9-39f4e7999f1f)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d7210047-788c-4b33-953d-e3134f52f897)  
(KB2743555)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=848af16d-c5f7-4a70-b6a9-39f4e7999f1f)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d7210047-788c-4b33-953d-e3134f52f897)  
(KB2743555)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ded1f351-022a-463c-9f5f-84b6081e6173)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7dc47f1d-8af8-4f31-9f96-3ae226632723)  
(KB2743555)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=ded1f351-022a-463c-9f5f-84b6081e6173)  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7dc47f1d-8af8-4f31-9f96-3ae226632723)  
(KB2743555)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=526f786b-7aef-4a1f-b03d-587baadf3f5b)（服务器核心安装）  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5697076c-541f-42b7-8dc3-e8bd4a25fda8)（服务器核心安装）  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）（服务器核心安装）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=848af16d-c5f7-4a70-b6a9-39f4e7999f1f)（服务器核心安装）  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d7210047-788c-4b33-953d-e3134f52f897)（服务器核心安装）  
(KB2743555)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=848af16d-c5f7-4a70-b6a9-39f4e7999f1f)（服务器核心安装）  
(KB2724197)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d7210047-788c-4b33-953d-e3134f52f897)（服务器核心安装）  
(KB2743555)  
（重要）
</td>
</tr>
</table>


#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Office 套件和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-065**](http://go.microsoft.com/fwlink/?linkid=263959)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e49eadec-0fe1-43ce-9c25-a92aad17d940)  
(KB2687483)  
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
[Microsoft Word 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=be58b650-ee4f-405e-ab3c-c28aca48345b)<sup>[1]</sup>  
(KB2687315)  
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
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=be58b650-ee4f-405e-ab3c-c28aca48345b)<sup>[1]</sup>  
(KB2687315)  
（严重）
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
Microsoft Office 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=27e07115-d569-438c-b95f-203e444d4408)  
(KB2553488)  
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
Microsoft Office 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=30f9efac-3ecd-48a6-adcf-922f4d4d18d4)  
(KB2553488)  
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
<th colspan="4" style="border:1px solid black;">
其他 Microsoft Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-065**](http://go.microsoft.com/fwlink/?linkid=263959)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer](https://www.microsoft.com/download/details.aspx?familyid=1e392ff8-92e9-408d-bb14-1e0a6b4b6c9d)  
(KB2687485)  
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
Microsoft Office Compatibility Pack Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=301446f7-991e-4abd-a06e-4a854f05ac84)  
(KB2687314)  
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
Microsoft Office 兼容包 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 兼容包 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=301446f7-991e-4abd-a06e-4a854f05ac84)  
(KB2687314)  
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
Microsoft InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a0989a9f-3a7a-4343-9dd0-b2d694a0813b)  
(KB2687439)  
（重要）  
[Microsoft InfoPath 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=29330e1a-6bac-4c54-98ef-b9a831801247)  
(KB2687440)  
（重要）
</td>
</tr>
<tr class="alternateRow">
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
[Microsoft InfoPath 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=a0989a9f-3a7a-4343-9dd0-b2d694a0813b)  
(KB2687439)  
（重要）  
[Microsoft InfoPath 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=29330e1a-6bac-4c54-98ef-b9a831801247)  
(KB2687440)  
（重要）
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
[Microsoft InfoPath 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=724b12b9-84bf-4102-912e-56aa9ee0878c)  
(KB2687436)  
（重要）  
[Microsoft InfoPath 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=b0be62c6-4eae-458e-8cf5-754742393e4c)  
(KB2687417)  
（重要）
</td>
</tr>
<tr class="alternateRow">
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
[Microsoft InfoPath 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=17b36fa3-9964-480a-bff8-b028619c5dfd)  
(KB2687436)  
（重要）  
[Microsoft InfoPath 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=6e5a7817-345e-4b75-aeca-94f74691c0e0)  
(KB2687417)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](https://www.microsoft.com/download/details.aspx?familyid=7e48cd96-4b91-4f7b-b8a0-2b88131ba51d)  
(KB2754670)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**MS12-064注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

<sup>[1]</sup>对于 Microsoft Office Word 2007，除安全更新程序包 KB2687315 之外，客户还需要安装 Microsoft Office 兼容包的安全更新 (KB2687314)，以免受本公告中所描述的漏洞影响。

**MS12-066** **注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
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
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2（32 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 （coreserver）（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=a8a818bb-67a3-4558-aac1-aaa33c6f4584)<sup>[1]</sup>  
(KB2687405)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2007 Service Pack 3 （coreserver）（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=a8a818bb-67a3-4558-aac1-aaa33c6f4584)<sup>[1]</sup>  
(KB2687405)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 （coreserver）（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=93f4e385-880a-4edc-9cde-24f38a11a41d)<sup>[1]</sup>  
(KB2687405)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 3 （coreserver）（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=93f4e385-880a-4edc-9cde-24f38a11a41d)<sup>[1]</sup>  
(KB2687405)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Word Automation Services](https://www.microsoft.com/download/details.aspx?familyid=3582ab6c-930b-4660-afcd-e2423ce56d8f)  
(KB2598237)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1 (wosrv)](https://www.microsoft.com/download/details.aspx?familyid=af3ade8e-349f-4eec-a5c3-c5a70071582d)  
(KB2687435)  
（重要）  
[Microsoft SharePoint Server 2010 Service Pack 1 (coreserver)](https://www.microsoft.com/download/details.aspx?familyid=5518b70b-cac9-4aff-b049-156d3c08b04b)  
(KB2589280)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft FAST Search Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft FAST Search Server 2010 for SharePoint
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[高级筛选包](https://www.microsoft.com/download/details.aspx?familyid=17909d1f-c679-4a20-b39d-b99f9cc7dbc1)  
(KB2553402)  
（重要）
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
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
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=80552d2c-98f2-4c99-bfc6-e091fd1d51c4)  
(KB2687402)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows SharePoint Services 和 Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
[Microsoft Windows SharePoint Services 3.0 Service Pack 2（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=e3a31cd4-bba3-4572-ab24-7b1dd0c4c01c)  
(KB2687356)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3（32 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 3（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=e3a31cd4-bba3-4572-ab24-7b1dd0c4c01c)  
(KB2687356)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=77cab67c-be97-4808-9fb4-4defad563851)  
(KB2687356)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 3（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=77cab67c-be97-4808-9fb4-4defad563851)  
(KB2687356)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=79724c7c-7cdf-44c9-9e25-577104c5004b)  
(KB2687434)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
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
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e7a2dd61-36d5-4313-a8dc-15456b275b9c)  
(KB2687401)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e7a2dd61-36d5-4313-a8dc-15456b275b9c)  
(KB2687401)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**MS12-064 注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**注意s对 MS12-066**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

<sup>[1]</sup>对于 Microsoft SharePoint Server 2007 的受支持版本，除了 Microsoft SharePoint 2007 安全更新程序包 (KB2687405) 外，客户还需要安装 Microsoft Windows SharePoint Services 3.0 安全更新 (KB2687356)，以免受本公告中所描述的漏洞影响。

#### Microsoft 通信平台和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Communicator
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
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
Microsoft Communicator 2007 R2
</td>
<td style="border:1px solid black;">
[Microsoft Communicator 2007 R2](https://www.microsoft.com/download/details.aspx?familyid=a228c1dd-9e57-48cb-8db4-896d6c499b46)  
(KB2726391)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Lync
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010（32 位）
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010（32 位）](https://www.microsoft.com/download/details.aspx?familyid=6ea3afea-baa2-4b74-9747-8051c544ddf7)  
(KB2726382)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010（64 位）
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010（64 位）](https://www.microsoft.com/download/details.aspx?familyid=670c20e6-4f26-47b9-b6e0-25f195bf7000)  
(KB2726382)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendee](https://www.microsoft.com/download/details.aspx?familyid=7f98cb55-027a-40bf-b539-d8fa38ffcc83)  
（管理员级别安装）  
(KB2726388)  
（重要）  
[Microsoft Lync 2010 Attendee](https://www.microsoft.com/download/details.aspx?familyid=32860684-998e-4e55-b719-c44532bc753d)<sup>[1]</sup>  
（用户级别安装）  
(KB2726384)  
（重要）
</td>
</tr>
</table>

**注意s对 MS12-066**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

<sup>[1]</sup>此更新只能从 Microsoft 下载中心下载。

#### Microsoft SQL Server

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
SQL Server 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
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
Microsoft SQL Server 2000 Reporting Services Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Reporting Services Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1c70a2cb-e8a9-439f-b34a-7d1641daf325)  
(KB983814)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
SQL Server 2005
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
带 Advanced Services Service Pack 4 的 Microsoft SQL Server 2005 Express Edition
</td>
<td style="border:1px solid black;">
[带 Advanced Services Service Pack 4 的 Microsoft SQL Server 2005 Express Edition](https://www.microsoft.com/download/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>  
(GDR)  
(KB2716429)  
（重要）  
[带 Advanced Services Service Pack 4 的 Microsoft SQL Server 2005 Express Edition](https://www.microsoft.com/download/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)<sup>[1]</sup>  
(QFE)  
(KB2716427)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 Service Pack 4（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 Service Pack 4（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>  
(GDR)  
(KB2716429)  
（重要）  
[Microsoft SQL Server 2005 Service Pack 4（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)<sup>[1]</sup>  
(QFE)  
(KB2716427)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 Service Pack 4（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 Service Pack 4（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>  
(GDR)  
(KB2716429)  
（重要）  
[Microsoft SQL Server 2005 Service Pack 4（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)<sup>[1]</sup>  
(QFE)  
(KB2716427)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 Service Pack 4（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 Service Pack 4（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>  
(GDR)  
(KB2716429)  
（重要）  
[Microsoft SQL Server 2005 Service Pack 4（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)<sup>[1]</sup>  
(QFE)  
(KB2716427)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
SQL Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 2（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 Service Pack 2（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=1bf8dc30-2a90-4196-814c-717ccd74ea13)<sup>[1]</sup>  
(GDR)  
(KB2716434)  
（重要）  
[Microsoft SQL Server 2008 Service Pack 2（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=7d8b1b25-45ad-4f19-ba50-e77debf2b463)<sup>[1]</sup>  
(QFE)  
(KB2716433)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 3（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 Service Pack 3（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=04621a83-c2e2-4a60-9198-10104372b120)<sup>[1]</sup>  
(GDR)  
(KB2716436)  
（重要）  
[Microsoft SQL Server 2008 Service Pack 3（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=4c4597d2-dea0-49b9-a5a9-a7771a3d64c0)<sup>[1]</sup>  
(QFE)  
(KB2716435)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 Service Pack 2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1bf8dc30-2a90-4196-814c-717ccd74ea13)<sup>[1]</sup>  
(GDR)  
(KB2716434)  
（重要）  
[Microsoft SQL Server 2008 Service Pack 2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7d8b1b25-45ad-4f19-ba50-e77debf2b463)<sup>[1]</sup>  
(QFE)  
(KB2716433)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 3（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 Service Pack 3（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=04621a83-c2e2-4a60-9198-10104372b120)<sup>[1]</sup>  
(GDR)  
(KB2716436)  
（重要）  
[Microsoft SQL Server 2008 Service Pack 3（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=4c4597d2-dea0-49b9-a5a9-a7771a3d64c0)<sup>[1]</sup>  
(QFE)  
(KB2716435)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 Service Pack 2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1bf8dc30-2a90-4196-814c-717ccd74ea13)<sup>[1]</sup>  
(GDR)  
(KB2716434)  
（重要）  
[Microsoft SQL Server 2008 Service Pack 2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7d8b1b25-45ad-4f19-ba50-e77debf2b463)<sup>[1]</sup>  
(QFE)  
(KB2716433)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 3（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 Service Pack 3（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=04621a83-c2e2-4a60-9198-10104372b120)<sup>[1]</sup>  
(GDR)  
(KB2716436)  
（重要）  
[Microsoft SQL Server 2008 Service Pack 3（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=4c4597d2-dea0-49b9-a5a9-a7771a3d64c0)<sup>[1]</sup>  
(QFE)  
(KB2716435)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
SQL Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 Service Pack 1（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 Service Pack 1（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=215a9184-71c5-41e6-b4d5-03602182a88f)<sup>[1]</sup>  
(GDR)  
(KB2716440)  
（重要）  
[Microsoft SQL Server 2008 R2 Service Pack 1（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=cdc4fc03-dfba-41d4-b651-d7967a067eea)<sup>[1]</sup>  
(QFE)  
(KB2716439)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 Service Pack 1（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 Service Pack 1（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=215a9184-71c5-41e6-b4d5-03602182a88f)<sup>[1]</sup>  
(GDR)  
(KB2716440)  
（重要）  
[Microsoft SQL Server 2008 R2 Service Pack 1（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=cdc4fc03-dfba-41d4-b651-d7967a067eea)<sup>[1]</sup>  
(QFE)  
(KB2716439)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 Service Pack 1（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 Service Pack 1（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=215a9184-71c5-41e6-b4d5-03602182a88f)<sup>[1]</sup>  
(GDR)  
(KB2716440)  
（重要）  
[Microsoft SQL Server 2008 R2 Service Pack 1（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=cdc4fc03-dfba-41d4-b651-d7967a067eea)<sup>[1]</sup>  
(QFE)  
(KB2716439)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
SQL Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
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
Microsoft SQL Server 2012（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2012（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=e79b4e5b-1549-4e76-afef-b771b432365b)<sup>[1]</sup>  
(GDR)  
(KB2716442)  
（重要）  
[Microsoft SQL Server 2012（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=ebfcb341-e240-4107-92f1-ab75cc28151a)<sup>[1]</sup>  
(QFE)  
(KB2716441)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2012（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2012（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e79b4e5b-1549-4e76-afef-b771b432365b)<sup>[1]</sup>  
(GDR)  
(KB2716442)  
（重要）  
[Microsoft SQL Server 2012（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ebfcb341-e240-4107-92f1-ab75cc28151a)<sup>[1]</sup>  
(QFE)  
(KB2716441)  
（重要）
</td>
</tr>
</table>

**MS12-070 注释**

<sup>[1]</sup>仅向运行 SQL Server Reporting Services (SSRS) 的客户提供此更新。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全技术中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问 [Microsoft 安全中心](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到这些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS12-001”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请参阅 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://technet.microsoft.com/wsus/default)。

**SystemCenter Configuration Manager**

System Center Configuration Manager 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 System Center Configuration Manager，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

System Center Configuration Manager 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。System Center Configuration Manager 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关 System Center Configuration Manager 的详细信息，请参阅 [System Center 技术资源](http://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。SMS 的下一版本 System Center Configuration Manager 现已可用；请参阅前面的部分 **System Center Configuration Manager**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)中包含的[更新兼容性评估程序](http://technet.microsoft.com/library/cc749197)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

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

-   一位匿名研究员与 [TippingPoint's](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 MS12-064 中描述的一个问题
-   一位匿名研究员与 Beyond Security's[SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) 计划团队合作报告了 MS11-064 中描述的一个问题
-   [Google Security Team](http://www.google.com/) 的 Drew Hintz 报告了 MS12-066 中描述的一个问题
-   [CERT/CC](http://www.cert.org/) 的 Will Dorman 与我们合作处理了 MS12-067 中描述的 13 个问题
-   一位匿名研究员与 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作报告了 MS12-068 中描述的一个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](http://technet.microsoft.com/security/bb980617.aspx)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](http://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2012 年 10 月 9 日）： 已发布公告摘要。
-   V1.1（2012 年 10 月 10 日）： 对于 MS12-068 和 MS12-069，分别更正了 CVE-2012-2529 和 CVE-2012-2551 的**利用指数**中最新软件版本的利用评估。对于 MS12-066，更正了 Microsoft Lync 2010 Attendee （管理员级别安装）和 Microsoft Lync 2010 Attendee（用户级别安装）的 KB 编号。
-   V1.2（2012 年 10 月 17 日）： 对于 MS12-066，更正了 Microsoft Lync 2010 Attendee （管理员级别安装）和 Microsoft Lync 2010 Attendee（用户级别安装）的 KB 编号。
-   V1.3（2012 年 10 月 23 日）： 对于 MS12-066，已将 Microsoft Windows SharePoint Services 3.0 Service Pack 3（32 位版本）和 Microsoft Windows SharePoint Services 3.0 Service Pack 3（64 位版本）添加到“**受影响的软件和下载位置** ”部分。这仅仅是一个信息更改。检测逻辑或安全更新文件未发生更改。

*Built at 2014-04-18T01:50:00Z-07:00*
