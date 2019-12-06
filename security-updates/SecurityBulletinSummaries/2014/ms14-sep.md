---
TOCTitle: 'MS14-SEP'
Title: 'Microsoft 安全公告摘要（2014 年 9 月）'
ms:assetid: 'ms14-sep'
ms:contentKeyID: 62842597
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms14-sep(v=Security.10)'
---



Microsoft 安全公告摘要（2014 年 9 月）
======================================

发布日期： 2014 年 9 月 9 日

**版本：** 1.0

本公告摘要列出了 2014 年 9 月发布的安全公告。

对于 2014 年 9 月发布的安全公告，本公告摘要替代 2014 年 9 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2014 年 9 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。要查看每月网络广播和其他安全公告网络广播的链接，请参阅 [Microsoft 安全公告网络广播](https://technet.microsoft.com/security/dn756352)。

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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积性安全更新 (2977629)<br />
<br />
</strong>此安全更新可解决 Internet Explorer 中一个公开披露的漏洞和 36 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507670">MS14-053</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 中的漏洞可能允许拒绝服务 (2990931)</strong><br />
<br />
此安全更新可解决 Microsoft .NET Framework 中的一个秘密报告的漏洞。如果攻击者向已启用 .NET 的受影响网站发送少量特制请求，则该漏洞可能允许拒绝服务。默认情况下，在任何受支持的 Microsoft Windows 版本上安装 Microsoft .NET Framework 时不安装 ASP.NET。要受此漏洞影响，客户必须通过向 IIS 注册 ASP.NET 来手动安装和启用它。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507672">MS14-054</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 任务计划程序中的漏洞可能允许特权提升 (2988948)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者登录受影响的系统并运行特制应用程序，此漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Lync Server 中的漏洞可能允许拒绝服务 (2990928)</strong><br />
<br />
此安全更新可解决 Microsoft Lync Server 中三个秘密报告的漏洞。如果攻击者将特制请求发送到 Lync 服务器，则这些漏洞中最严重的漏洞可能允许拒绝服务。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>无需重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Lync Server</p></td>
</tr>  
</tbody>  
</table>
  
 
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
如何使用该表？
  
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
<thead>  
<tr class="header">  
<th><p>公告 ID</p></th>  
<th><p>漏洞标题</p></th>  
<th><p>CVE ID</p></th>  
<th><p>最新软件版本的利用评估</p></th>  
<th><p>较旧软件版本的利用评估</p></th>  
<th><p>拒绝服务利用评估</p></th>  
<th><p>重要注意事项</p></th>  
</tr>  
</thead>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 资源信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-7331">CVE-2013-7331</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。Microsoft 获悉尝试利用此漏洞的有限活动攻击。<br />
这是一个信息泄露漏洞： 攻击者可以推导出本地驱动器上的文件的状态。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2799">CVE-2014-2799</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4059">CVE-2014-4059</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4065">CVE-2014-4065</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4079">CVE-2014-4079</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4080">CVE-2014-4080</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4081">CVE-2014-4081</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4082">CVE-2014-4082</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4083">CVE-2014-4083</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4084">CVE-2014-4084</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4085">CVE-2014-4085</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4086">CVE-2014-4086</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4087">CVE-2014-4087</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4088">CVE-2014-4088</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4089">CVE-2014-4089</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4090">CVE-2014-4090</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4091">CVE-2014-4091</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4092">CVE-2014-4092</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4093">CVE-2014-4093</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4094">CVE-2014-4094</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4095">CVE-2014-4095</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4096">CVE-2014-4096</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4097">CVE-2014-4097</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4098">CVE-2014-4098</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4099">CVE-2014-4099</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>临时</p></td>
<td style="border:1px solid black;"><p>此内存损坏漏洞可能导致拒绝服务。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4100">CVE-2014-4100</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4101">CVE-2014-4101</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4102">CVE-2014-4102</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4103">CVE-2014-4103</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4104">CVE-2014-4104</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4105">CVE-2014-4105</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4106">CVE-2014-4106</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4107">CVE-2014-4107</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4108">CVE-2014-4108</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4109">CVE-2014-4109</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4110">CVE-2014-4110</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4111">CVE-2014-4111</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507670">MS14-053</a></p></td>
<td style="border:1px solid black;"><p>.NET Framework 拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4072">CVE-2014-4072</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个拒绝服务漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507672">MS14-054</a></p></td>
<td style="border:1px solid black;"><p>任务计划程序漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4074">CVE-2014-4074</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></p></td>
<td style="border:1px solid black;"><p>Lync 拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4068">CVE-2014-4068</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>临时</p></td>
<td style="border:1px solid black;"><p>这是一个拒绝服务漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></p></td>
<td style="border:1px solid black;"><p>Lync XSS 信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4070">CVE-2014-4070</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></p></td>
<td style="border:1px solid black;"><p>Lync 拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4071">CVE-2014-4071</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>临时</p></td>
<td style="border:1px solid black;"><p>这是一个拒绝服务漏洞。</p></td>
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
  
**Windows 操作系统和组件**

<p> </p>
<table style="border:1px solid black;">  
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-052**](https://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](https://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](https://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
（中等）  
Internet Explorer 7  
(2977629)  
（中等）  
Internet Explorer 8  
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2972207)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972214)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2973115)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
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
(2977629)  
（中等）  
Internet Explorer 7  
(2977629)  
（中等）  
Internet Explorer 8  
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972214)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2973115)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
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
(2977629)  
（中等）  
Internet Explorer 7  
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972214)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-052**](https://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](https://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](https://go.microsoft.com/fwlink/?linkid=507672)

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
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2977629)  
（严重）  
Internet Explorer 8  
(2977629)  
（严重）  
Internet Explorer 9  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
（严重）  
Internet Explorer 8  
(2977629)  
（严重）  
Internet Explorer 9  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-052**](https://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](https://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](https://go.microsoft.com/fwlink/?linkid=507672)

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
Internet Explorer 7  
(2977629)  
（中等）  
Internet Explorer 8  
(2977629)  
（中等）  
Internet Explorer 9  
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Internet Explorer 7  
(2977629)  
（中等）  
Internet Explorer 8  
(2977629)  
（中等）  
Internet Explorer 9  
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Internet Explorer 7  
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-052**](https://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](https://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](https://go.microsoft.com/fwlink/?linkid=507672)

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
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
（严重）  
Internet Explorer 9  
(2977629)  
（严重）  
Internet Explorer 10  
(2977629)  
（严重）  
Internet Explorer 11  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2973112)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
（严重）  
Internet Explorer 9  
(2977629)  
（严重）  
Internet Explorer 10  
(2977629)  
（严重）  
Internet Explorer 11  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2973112)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-052**](https://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](https://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](https://go.microsoft.com/fwlink/?linkid=507672)

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
Internet Explorer 8  
(2977629)  
（中等）  
Internet Explorer 9  
(2977629)  
（中等）  
Internet Explorer 10  
(2977629)  
（中等）  
Internet Explorer 11  
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2973112)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Internet Explorer 8  
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2973112)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-052**](https://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](https://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](https://go.microsoft.com/fwlink/?linkid=507672)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
（重要）  
Microsoft .NET Framework 3.5  
(2973113)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2988948)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
（重要）  
Microsoft .NET Framework 3.5  
(2973113)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2988948)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
（重要）  
Microsoft .NET Framework 3.5  
(2973114)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2988948)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
（重要）  
Microsoft .NET Framework 3.5  
(2973114)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2988948)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-052**](https://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](https://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](https://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
（重要）  
Microsoft .NET Framework 3.5  
(2973113)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2988948)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
（重要）  
Microsoft .NET Framework 3.5  
(2973114)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2988948)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-052**](https://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](https://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](https://go.microsoft.com/fwlink/?linkid=507672)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(2988948)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2988948)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-052**](https://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](https://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](https://go.microsoft.com/fwlink/?linkid=507672)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2973112)  
（重要）  
Microsoft .NET Framework 4  
(2972215)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Microsoft .NET Framework 3.5  
(2972212)  
（重要）  
Microsoft .NET Framework 3.5  
(2973113)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2988948)  
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
Microsoft .NET Framework 3.5  
(2972213)  
（重要）  
Microsoft .NET Framework 3.5  
(2973114)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2988948)  
（重要）

</td>
</tr>
</table>

 

**Microsoft 通信平台和软件**

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
**Microsoft Lync Server**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-055**](https://go.microsoft.com/fwlink/?linkid=507669)

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
Microsoft Lync Server 2010

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2010  
（服务器）  
(2982385)  
（没有严重等级）<sup>[1]</sup>  
Microsoft Lync Server 2010  
（响应组服务）  
(2982388)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
（服务器）  
(2986072)  
（重要）  
Microsoft Lync Server 2013  
（响应组服务）  
(2982389)  
（重要）  
Microsoft Lync Server 2013  
（核心组件）  
(2992965)  
（重要）  
Microsoft Lync Server 2013  
（Web 组件服务器）  
(2982390)  
（重要）

</td>
</tr>
</table>

**MS14-055 注释**

<sup>[1]</sup>严重等级不适用于指定软件的此更新；然而，作为一种纵深防御措施，Microsoft 建议这款软件的客户应用此安全更新，以帮助抵御将来识别的任何可能的新攻击媒介。

 

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

**MS14-052**

-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2799)
-   [Adlab of Venustech](https://www.venustech.com.cn/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2799)
-   [Adlab of Venustech](https://www.venustech.com.cn/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4059)
-   [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4065)
-   56e7aec02099b976120abfda31254b05 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4079)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4080)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4081)
-   [Adlab of Venustech](https://www.venustech.com.cn/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4081)
-   [Qihoo 360](https://www.360.cn/) 的 Yuki Chen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4082)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4082)
-   [Adlab of Venustech](https://www.venustech.com.cn/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4083)
-   [Adlab of Venustech](https://www.venustech.com.cn/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4084)
-   [KnownSec Team](https://www.knownsec.com/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4084)
-   Sky 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4085)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4086)
-   [Qihoo 360](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4086)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4087)
-   [Qihoo 360](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4087)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Hui Gao 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4088)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4089)
-   Garage4Hackers 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4090)
-   [Qihoo 360](https://www.360.cn/) 的 Yuki Chen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4091)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4092)
-   A3F2160DCA1BDE70DA1D99ED267D5DC1EC336192 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4092)
-   Jason Kratzer 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4092)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4093)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4094)
-   [Trend Micro](https://www.trendmicro.com/) 的 Yuki Chen 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4095)
-   cloudfuzzer 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4096)
-   [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4096)
-   [Trend Micro](https://www.trendmicro.com/) 的 Yuki Chen 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4096)
-   [Trend Micro](https://www.trendmicro.com/) 的 Yuki Chen 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4097)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4097)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4098)
-   SkyLined 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4099)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4100)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Xin Ouyang 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4101)
-   José A. Vázquez of Yenteasy 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4101)
-   [Qihoo 360](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4102)
-   [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4103)
-   [Qihoo 360](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4104)
-   [Trend Micro](https://www.trendmicro.com/) 的 Yuki Chen 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4105)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4106)
-   [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4107)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4108)
-   John Villamil (@day6reak) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4109)
-   [KnownSec Team](https://www.knownsec.com/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4110)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4111)
-   Masato Kinugawa 和 [Google Security Team](https://www.google.com/) 与我们合作处理了此公告中包括的纵深防御更改

**MS14-053**

-   [Cynops GmbH](https://www.cynops.de/) 的 Alexander Klink 报告了 .NET Framework 拒绝服务漏洞 (CVE-2014-4072)

**MS14-054**

-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了任务计划程序漏洞 (CVE-2014-4074)

**MS14-055**

-   [Telecommunication Software GmbH](https://www.telecomsoftware.com/) 的 Peter Schraffl 报告了 Lync 拒绝服务漏洞 (CVE-2014-4068)
-   Noam Rathaus 与 Beyond Security 的 [SecuriTeam Secure Disclosure](https://www.beyondsecurity.com/ssd.html) 团队合作报告了 Lync XSS 信息泄露漏洞 (CVE-2014-4070)

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

-   V1.0（2014 年 9 月 9 日）： 已发布公告摘要。

*页面生成时间：2014-09-18 16:20Z-07:00。*
