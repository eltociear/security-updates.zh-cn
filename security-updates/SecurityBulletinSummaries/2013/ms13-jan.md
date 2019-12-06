---
TOCTitle: 'MS13-JAN'
Title: 'Microsoft 安全公告摘要（2013 年 1 月）'
ms:assetid: 'ms13-jan'
ms:contentKeyID: 61236980
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms13-jan(v=Security.10)'
---



Microsoft 安全公告摘要（2013 年 1 月）
======================================

发布时间: 2013年1月8日 | 更新时间: 2013年3月12日

**版本:** 4.0

本公告摘要列出了 2013 年 1 月发布的安全公告。

对于 2013 年 1 月发布的安全公告，本公告摘要替代 2013 年 1 月 3 日最初发布的公告预先通知和 2013 年 1 月13 日发布的带外公告预先通知。有关公告预先通知服务的详细信息，[Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2013 年 1 月 9 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 1 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623&culture=en-us)。此日期之后，此网络广播[按需](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623&culture=en-us)提供。

Microsoft 将在 2013 年 1 月 14 日下午 1 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于额外安全公告的疑问。[立即注册申请收听 2013 年 1 月 14 日的带外安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=en-us)。此日期之后，此网络广播[按需](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=en-us)提供。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的安全更新 (2799329)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Internet Explorer 中一个公开披露的漏洞。如果用户使用 Internet Explorer 查看特制网页，则该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;"><strong>Windows Print Spooler</strong> <strong>组件中的漏斗可能允许远程执行代码</strong> <strong>(2769369)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果打印服务器收到特制的打印作业，则该漏洞可能允许远程执行代码。采用防火墙最佳做法和标准的默认防火墙配置，有助于保护网络免受从企业外部发起的攻击。按照最佳做法，应使直接连接到 Internet 的系统所暴露的端口数尽可能少。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services 中的漏洞可能允许远程执行代码 (2756145)</strong><br />
<br />
此安全更新解决了 Microsoft XML Core Services 中两个秘密报告的漏洞。如果用户使用 Internet Explorer 查看特制网页，则所有漏洞可能允许远程执行代码。但是，攻击者无法强迫用户访问这样的网站。相反，攻击者必须诱使用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft Office，<br />  
Microsoft 开发工具，<br />
Microsoft Server 软件</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;"><strong>System Center Operations Manager 中的漏洞可能允许特权提升 (2748552)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Microsoft System Center Operations Manager 中两个秘密报告的漏洞。如果用户通过特制 URL 访问受影响的网站，则这些漏洞可能允许特权提升。但是，攻击者无法强迫用户访问这样的网站。相反，攻击者必须诱使用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到受影响的网站。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">无需重新启动</td>
<td style="border:1px solid black;">Microsoft Server 软件</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;"><strong>.NETFramework中的漏洞可能允许远程执行代码</strong> <strong>(2769324)<br />
<br />
</strong>此安全更新可解决 .NET Framework<strong></strong>中四个秘密报告的漏洞。如果用户使用可运行 XAML 浏览器应用程序 (XBAP) 的 Web 浏览器查看特制网页，则这些漏洞中最严重的漏洞可能允许特权提升。Windows .NET 应用程序也可能会使用此漏洞绕过代码访问安全性 (CAS) 限制。成功利用这些漏洞的攻击者可以获得与登录用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升</strong> <strong>(2778930)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者运行特制的应用程序，则该漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;"><strong>Microsoft</strong> <strong>Windows中的漏洞可能允许绕过安全功能(2785220)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 的 SSL 和 TLS 实施中一个秘密报告的漏洞。如果攻击者截取加密的 Web 通信握手，则该漏洞可能允许安全功能绕过。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
安全功能绕过</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;"><strong>开放数据协议中的漏洞可能允许拒绝服务</strong> <strong>(2769327)<br />
<br />
</strong>此安全更新可解决开放数据 (OData) 协议中一个秘密报告的漏洞。如果未经身份验证的攻击者向受影响的网站发送特制 HTTP 请求，则该漏洞可能允许拒绝服务。采用防火墙最佳做法和标准的默认防火墙配置，有助于保护网络免受从企业外部发起的攻击。按照最佳做法，应使连接到 Internet 的系统所暴露的端口数尽可能少。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft .NET Framework</td>
</tr>
</tbody>
</table>


利用指数
--------

下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。

**如何使用该表？**

使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/security/cc998259)。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;">Windows Print Spooler 组件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0011">CVE-2013-0011</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">MSXML 整数截断漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0006">CVE-2013-0006</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">MSXML XSLT 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0007">CVE-2013-0007</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">System Center Operations Manager Web 控制台 XSS 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0009">CVE-2013-0009</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">System Center Operations Manager Web 控制台 XSS 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0010">CVE-2013-0010</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">WinForms 缓冲区溢出漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0002">CVE-2013-0002</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">S.DS.P 缓冲区溢出漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0003">CVE-2013-0003</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">双重建筑漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0004">CVE-2013-0004</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;">Win32k 消息处理不正确漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0008">CVE-2013-0008</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;">Microsoft SSL 版本 3 和 TLS 协议安全功能绕过漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0013">CVE-2013-0013</a></td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个安全功能绕过漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;">拒绝服务漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0005">CVE-2013-0005</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4792">CVE-2012-4792</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。<br />
<br />
Microsoft 获悉尝试通过 Internet Explorer8 利用此漏洞的目标攻击。</td>
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
<th colspan="8" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
**无**
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
<td style="border:1px solid black;">
**无**
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=20d8d873-a709-4834-a956-f3d9d82dbb73)  
(KB2799329)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dcdcf814-e39d-4515-bc5d-12e11f214d08)  
(KB2799329)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4e0d584a-c684-408c-bc47-6bd4ecaa9b8a)  
(KB2799329)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=137cc5ee-abf0-4a10-b1c4-d464331cbcfd)  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=155a2984-2cd9-40a4-abaa-c1ea21e76062)  
(KB2742607)  
（仅限 Media Center Edition 2005 Service Pack 3 和 Tablet PC Edition 2005 Service Pack 3）  
（重要）  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
（重要）  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
（没有严重等级<sup>[2]</sup>）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=f35f2ea5-d60e-405a-9ed3-248e0d733c2b)  
(KB2799329)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=36c9d6a9-d939-4e19-b9f5-576fee048764)  
(KB2799329)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=396f26bd-8c8b-459d-9467-6ec17a11c9d4)  
(KB2799329)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=d147f865-6a56-4db2-8d78-14f2bee6da18)  
(KB2757638)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9)  
(KB2758696)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
（重要）  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
（没有严重等级<sup>[2]</sup>）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
**无**
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=1a7cfc5a-2872-4516-a371-f42d4d3969a6)  
(KB2799329)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4b7c2bcd-a732-46ba-9d09-cc192efd4755)  
(KB2799329)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7f134d1c-670d-4528-b755-22124aa4d8c9)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=6a12de5f-de80-48e4-8276-6c420f5a2948)  
(KB2758696)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f1a2eb6e-0290-4a53-b93c-017a48b19973)  
(KB2742604)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
（重要）  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
（没有严重等级<sup>[2]</sup>）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=00304f3b-069f-49dc-a416-b0b5fb97aa4b)  
(KB2799329)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4911899c-863f-4499-9477-340ef8daad29)  
(KB2799329)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b0cf6516-aea6-4879-9a6e-171d4825ae20)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=29985fdc-8aba-44b2-9420-970ca475052e)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9)  
(KB2758696)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
（重要）  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
（没有严重等级<sup>[2]</sup>）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b2c635b7-56ad-426b-8bd6-4aee9deadb69)  
(KB2799329)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b33197ab-f489-4c11-a229-044b186d7dda)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=bca95077-a28f-406c-9fe4-51dbcf6adee8)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=fb834cf7-d1fe-4291-8a0d-c866fdbdf0e6)  
(KB2758696)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=95d603e8-9440-4aa6-9765-20c77a55966a)  
(KB2799329)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=64b498a6-54fc-4b88-bcc3-2cc15a16abb5)  
(KB2799329)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=d477235d-60f4-420d-8161-82194b4e62e7)  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
（重要）  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
（没有严重等级<sup>[2]</sup>）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8b1aef73-cfb2-4998-bca6-35cccfbb2078)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3107fadf-5ba8-48f6-bb23-0c0003b4ba76)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a35ccbff-c476-4ee2-be9c-5b6a4b1664e9)  
(KB2799329)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b427bace-5297-4593-9dd2-66847ae506c6)  
(KB2799329)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3)  
(KB2757638)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3)  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
（重要）  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
（没有严重等级<sup>[2]</sup>）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4287381f-6f23-4a36-a7dc-f79c44bac124)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=098958e5-83cd-4ed2-b758-e970cef33325)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
**无**
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3ce450f1-f71f-4d5d-bf1c-db4742522d18)  
(KB2799329)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2d1266fc-f6b0-4062-9799-7b3721c2cf52)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
（重要）  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
（没有严重等级<sup>[2]</sup>）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0f87dd60-92c2-444c-a9ea-dfeb106c88fa)  
(KB2799329)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2f71f8e6-309c-4bea-abde-d91040c46611)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
（重要）  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
（没有严重等级<sup>[2]</sup>）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e47425e9-f53e-4e20-a7ec-b4c552bd66eb)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
（重要）  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
（没有严重等级<sup>[2]</sup>）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d949fde9-31e7-4553-a34c-b41625a8cdc8)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ab117984-c4cb-473b-8c20-2b0d0409d8d6)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285)  
(KB2799329)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390)  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b)  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285)  
(KB2799329)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390)  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b)  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154)  
(KB2799329)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32)  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154)  
(KB2799329)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32)  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>  
(KB2742595)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>  
(KB2736428)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
**无**
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
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
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=e19d1373-a3f3-4f60-9142-c2484726aac8)  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
（重要）  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=1f5441f1-a66d-42c0-bf0e-2f6867d4d43a)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=9f40864f-5347-44ef-bb08-afea45b5351b)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c)  
(KB2757638)  
（严重）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c)  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
（重要）  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=9d71dc77-9c01-4a1f-b403-8a18ca10979d)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=1b40baad-784a-4eba-a4ef-703250248057)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
**无**
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](https://www.microsoft.com/download/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
（重要）  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d)  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a)  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
（重要）  
[管理 OData IIS 扩展](https://www.microsoft.com/download/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1)  
(KB2753596)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0<sup>[1]</sup>  
(KB2758694)  
（严重）  
Microsoft XML Core Services 6.0<sup>[1]</sup>  
(KB2757638)  
（严重）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>  
(KB2742614)  
（重要）
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-008**](https://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](https://go.microsoft.com/fwlink/?linkid=268284)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](https://www.microsoft.com/download/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
（中等）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的](https://www.microsoft.com/download/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45)（服务器核心安装）  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004)（服务器核心安装）  
(KB2785220)  
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services3.0](https://www.microsoft.com/download/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735)(服务器核心安装)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (服务器核心安装)  
(KB2758694)  
（中等）  
[Microsoft XML Core Services6.0](https://www.microsoft.com/download/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735) (服务器核心安装)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068)（服务器核心安装）  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc)（服务器核心安装）  
(KB2785220)  
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)（服务器核心安装）  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services3.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)(服务器核心安装)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (服务器核心安装)  
(KB2758694)  
（中等）  
[Microsoft XML Core Services6.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (服务器核心安装)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)（服务器核心安装）  
(KB2742598)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)（服务器核心安装）  
(KB2756920)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)（服务器核心安装）  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)（服务器核心安装）  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)（服务器核心安装）  
(KB2736418)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)（服务器核心安装）  
(KB2769369)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services3.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)(服务器核心安装)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (服务器核心安装)  
(KB2758694)  
（中等）  
[Microsoft XML Core Services6.0](https://www.microsoft.com/download/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (服务器核心安装)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)（服务器核心安装）  
(KB2742599)  
（重要）  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)（服务器核心安装）  
(KB2756921)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>（服务器核心安装）  
(KB2742595)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)（服务器核心安装）  
(KB2742613)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)（服务器核心安装）  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)（服务器核心安装）  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)（服务器核心安装）  
(KB2736422)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>（服务器核心安装）  
(KB2736428)  
（重要）
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
[Microsoft XML Core Services3.0](https://www.microsoft.com/download/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528)(服务器核心安装)  
(KB2757638)  
（中等）  
[Microsoft XML Core Services4.0](https://www.microsoft.com/download/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (服务器核心安装)  
(KB2758694)  
（中等）  
[Microsoft XML Core Services6.0](https://www.microsoft.com/download/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528) (服务器核心安装)  
(KB2757638)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)（服务器核心安装）  
(KB2742616)  
（重要）  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)（服务器核心安装）  
(KB2756923)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)（服务器核心安装）  
(KB2742614)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d)（服务器核心安装）  
(KB2778930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a)（服务器核心安装）  
(KB2785220)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)（服务器核心安装）  
(KB2736693)  
（重要）  
[管理 OData IIS 扩展](https://www.microsoft.com/download/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1)（服务器核心安装）  
(KB2753596)  
（重要）
</td>
</tr>
</table>

**MS13-002** **的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

<sup>[1]</sup> Windows RT 安全更新仅通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

**MS13-004 的注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](https://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

<sup>[2]</sup>严重等级不适用于指定软件的此更新，因为本公告中讨论的漏洞的已知攻击媒介已在默认配置中阻止。然而，作为一种纵深防御措施，Microsoft 建议这款软件的客户应用此安全更新。

<sup>[3]</sup>Windows RT 安全更新仅通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

**MS13-005的注释**

<sup>[1]</sup>Windows RT 安全更新仅通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

**MS13-006的注释**

<sup>[1]</sup>Windows RT 安全更新仅通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

**MS13-007 的注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](https://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office 套件和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=d108d56c-f9fb-4823-b38e-3d2f838592de)  
(KB2760574)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
（严重）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
其他 Microsoft Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
（严重）
</td>
</tr>
</table>

**MS13-002 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
（严重）
</td>
</tr>
</table>

**MS13-002 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-003**](https://go.microsoft.com/fwlink/?linkid=261863)
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
**无**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2（64 位版本）
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
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
（严重）
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
[Microsoft XML Core Services 5.0](https://www.microsoft.com/download/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
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
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-003**](https://go.microsoft.com/fwlink/?linkid=261863)
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
**无**
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
<th colspan="3" style="border:1px solid black;">
Microsoft System Center Operations Manager
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-002**](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-003**](https://go.microsoft.com/fwlink/?linkid=261863)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center Operations Manager 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f848d74d-fdae-4a19-a0f5-12d2d4389db9)<sup>[1]</sup>  
(KB2809182)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft System Center Operations Manager 2007 R2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 R2](https://www.microsoft.com/download/details.aspx?familyid=4e1ab3bd-af0c-41f8-8ebc-1cdc68a3ee37)<sup>[1]</sup><sup>[2]</sup>  
(KB2783850)  
（重要）
</td>
</tr>
</table>

**MS13-002 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS13-003** **的注释**

<sup>[1]</sup>此更新只能从 Microsoft 下载中心下载。

<sup>[2]</sup>此更新是累积性的，将替代指定软件以前的累积性更新。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全技术中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问 [Microsoft 安全中心](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到这些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS13-001”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请参阅 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://technet.microsoft.com/wsus/default)。

**SystemCenter Configuration Manager**

System Center Configuration Manager 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 System Center Configuration Manager，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

System Center Configuration Manager 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。System Center Configuration Manager 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关 System Center Configuration Manager 的详细信息，请参阅 [System Center 技术资源](https://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。SMS 的下一版本 System Center Configuration Manager 现已可用；请参阅前面的部分 **System Center Configuration Manager**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/systemcenter/bb545936)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)中包含的[更新兼容性评估程序](https://technet.microsoft.com/library/cc749197)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

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

-   [Agarri](https://www.agarri.fr/) 的 Nicolas Gregoire 报告了 MS13-002 中描述的一个问题
-   BAE Systems Detica 的 Andy Yang 报告了 MS13-003 中描述的一个问题
-   [iSIGHT Partners Labs](https://www.isightpartners.com/) 的 Jon Erickson 报告了 MS13-004 中描述的问题
-   Vitaliy Toropov 与 [Tipping Point's](https://www.tippingpoint.com/)[Zero Day Initiative](https://www.zerodayinitiative.com/) 报告了 MS13-004 中描述的两个问题
-   Context Information Security 的 James Forshawor 报告了 MS13-004 中描述的一个问题
-   [Kenichiro Katayama](https://twitter.com/pin_ptr) 报告了 MS13-006 中描述的一个问题
-   [Exodus Intelligence](https://www.exodusintel.com) 与我们合作处理了 MS13-008 中的一个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/security/bb980617.aspx)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](https://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2013 年 1 月 8 日）： 已发布公告摘要。
-   V1.1（2013 年 1 月 8 日）： 对于 MS13-002，已向安装在 Windows Server 2008 （用于 32 位系统）Service Pack 2 上的 Microsoft XML Core Services 4.0 以及安装在 Windows Server 2008（用于 32 位系统）Service Pack 2 上的 Microsoft XML Core Services 6.0 的受影响软件添加了服务器核心安装条目。已经成功更新了其系统的客户不需要执行任何操作。
-   V2.0 （2013 年 1 月 4 日）： 添加了 Microsoft 安全公告 MS13-008、Internet Explorer 的安全更新 (2799329)，并添加了此带外安全公告的公告网络广播链接。
-   V3.0 （2013 年 1 月 22 日)： 对于 MS13-004，重新发布此公告是为了向以已知具有潜在兼容性问题的特定配置运行的系统重新提供 Windows 7 和 Windows Server 2008 R2 的 KB2756920 更新。请参阅公告以了解详细信息。
-   V4.0（2013 年 3 月 12 日）： 对于 MS13-003，发布了公告以宣布 Microsoft System Center Operations Manager 2007 Service Pack 1 更新的可用性。没有其他更新程序包受此重新发布版本的影响。请参阅公告以了解详细信息。

*Built at 2014-04-18T01:50:00Z-07:00*
