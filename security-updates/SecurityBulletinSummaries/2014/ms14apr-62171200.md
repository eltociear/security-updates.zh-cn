---
TOCTitle: 'MS14-APR'
Title: 'Microsoft 安全公告摘要（2014 年 4 月）'
ms:assetid: 'ms14-apr'
ms:contentKeyID: 62171200
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms14-apr(v=Security.10)'
---

Microsoft 安全公告摘要（2014 年 4 月）
======================================

发布日期： 2014 年 4 月 8 日

**版本：** 1.0

本公告摘要列出了 2014 年 4 月发布的安全公告。

对于 2014 年 4 月发布的安全公告，本公告摘要替代 2014 年 4 月 3 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2014 年 4 月 9 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 4 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572978&culture=en-us)。

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
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393531">MS14-017</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Word 和 Office Web App 中的漏洞可能允许远程执行代码 (2949660)</strong><br />
<br />
此安全更新可解决 Microsoft Office 中一个公开披露的漏洞和两个秘密报告的漏洞。如果在 Microsoft Office 软件受影响的版本中打开或预览特制文件，则这些漏洞中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office，<br />
Microsoft Office 服务，<br />
Microsoft Office Web Apps</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积性安全更新 (2950467)<br />
<br />
</strong>此安全更新解决 Internet Explorer 中的六个秘密报告的漏洞。如果用户使用 Internet Explorer 查看特制网页，则这些漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=392069">MS14-019</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 文件处理组件中的漏洞可能允许远程执行代码 (2922229)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。如果用户从受信任的或不完全受信任的网络位置运行特制的 .bat 和 .cmd 文件，则该漏洞可能允许远程执行代码。攻击者无法强迫用户访问网络位置或运行特制文件。相反，攻击者必须说服用户执行此类操作。例如，攻击者可能诱使用户单击链接以使用户链接到攻击者的特制文件，随后诱使他们运行它们。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393603">MS14-020</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Publisher 中的漏洞可能允许远程执行代码 (2950145)<br />
</strong><br />
此安全更新解决了 Microsoft Office 中一个秘密报告的漏洞。如果用户使用受影响的 Microsoft Publisher 版本打开特制文件，该漏洞可能允许远程执行代码。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
如何使用该表？
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/security/cc998259)。
  
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
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393531">MS14-017</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 文件格式转换器漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1757">CVE-2014-1757</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393531">MS14-017</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Word 堆栈溢出漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1758">CVE-2014-1758</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393531">MS14-017</a></p></td>
<td style="border:1px solid black;"><p>Word RTF 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1761">CVE-2014-1761</a></p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />
Microsoft 获悉尝试使用此漏洞的有限目标攻击。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0325">CVE-2014-0325</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1751">CVE-2014-1751</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1752">CVE-2014-1752</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1753">CVE-2014-1753</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1755">CVE-2014-1755</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1760">CVE-2014-1760</a></p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=392069">MS14-019</a></p></td>
<td style="border:1px solid black;"><p>Windows 文件处理漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0315">CVE-2014-0315</a></p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=393603">MS14-020</a></p></td>
<td style="border:1px solid black;"><p>任意指针解除引用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1759">CVE-2014-1759</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
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
<td style="border:1px solid black;" colspan="3">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
（严重）  
Internet Explorer 7   
(2936068)  
（严重）  
Internet Explorer 8   
(2936068)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
（严重）  
Internet Explorer 7   
(2936068)  
（严重）  
Internet Explorer 8   
(2936068)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
（中等）  
Internet Explorer 7  
(2936068)  
（中等）  
Internet Explorer 8  
(2936068)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
（中等）  
Internet Explorer 7  
(2936068)  
（中等）  
Internet Explorer 8  
(2936068)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
（中等）  
Internet Explorer 7  
(2936068)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
（严重）  
Internet Explorer 8  
(2936068)  
（严重）  
Internet Explorer 9   
(2936068)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
（严重）  
Internet Explorer 8  
(2936068)  
（严重）  
Internet Explorer 9   
(2936068)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
（中等）  
Internet Explorer 8  
(2936068)  
（中等）  
Internet Explorer 9   
(2936068)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
（中等）  
Internet Explorer 8  
(2936068)  
（中等）  
Internet Explorer 9   
(2936068)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2936068)  
（严重）  
Internet Explorer 9   
(2936068)  
（严重）  
Internet Explorer 11   
(2936068)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2936068)  
（严重）  
Internet Explorer 9   
(2936068)  
（严重）  
Internet Explorer 11   
(2936068)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2936068)  
（中等）  
Internet Explorer 9   
(2936068)  
（中等）  
Internet Explorer 11   
(2936068)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2936068)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 8（用于 32 位系统）  
(2922229)  
（重要）

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
Windows 8（用于基于 x64 的系统）  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2936068)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2936068)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2936068)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2936068)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2922229)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2922229)  
（重要）

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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2922229)  
（重要）

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
(2922229)  
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
Windows Server 2012（服务器核心安装）  
(2922229)  
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
Windows Server 2012 R2（服务器核心安装）  
(2922229)  
（重要）

</td>
</tr>
</table>

 

**Microsoft Office 套件和软件**

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2003 Service Pack 3  
(2878303)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Publisher 2003 Service Pack 3  
(2878299)  
（重要）

</td>
</tr>
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
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2878237)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Publisher 2007 Service Pack 3  
(2817565)  
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
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 1（32 位版本）  
(2863926)  
（严重）  
Microsoft Word 2010 Service Pack 1（32 位版本）  
(2863919)  
（严重）

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
Microsoft Word 2010 Service Pack 2（32 位版本）  
(2863926)  
（严重）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(2863919)  
（严重）

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
Microsoft Word 2010 Service Pack 1（64 位版本）  
(2863926)  
（严重）  
Microsoft Word 2010 Service Pack 1（64 位版本）  
(2863919)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 2（64 位版本）  
(2863926)  
（严重）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(2863919)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Word 2013（32 位版本）  
(2863910)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1（32 位版本）  
(2863910)  
（严重）

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
Microsoft Office 2013（64 位版本）  
(2863910)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1（64 位版本）  
(2863910)  
（严重）

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
Microsoft Word 2013 RT  
(2863910)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT Service Pack 1  
(2863910)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2939132)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2878304)  
（严重）

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
Microsoft Office 兼容包 Service Pack 3  
(2878236)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

**MS14-017 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

**Microsoft Office Services 和 Web Apps**

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
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2878220)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2878220)  
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
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2863907)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2863907)  
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
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 1  
(2878221)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2878221)  
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
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2878219)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(2878219)  
（严重）

</td>
</tr>
</table>

**MS14-017 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

-   管理员可使用 Microsoft Baseline Security Analyzer (MBSA) 在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。
-   Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。
-   Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](http://technet.microsoft.com/security/cc297183)。 

鸣谢
----

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

**MS14-017**

-   [CERT/CC](http://www.cert.org/) 的 Will Dormann 报告了 Microsoft Office 文件格式转换器漏洞 (CVE-2014-1757)
-   Yuhong Bao 报告了 Microsoft Word 堆栈溢出漏洞 (CVE-2014-1758)
-   [Google Security Team pellegrino](http://www.google.com/) 中的 Drew Hintz、Shane Huntley 和 Matty Pellegrino 报告了 Word RTF 内存损坏漏洞 (CVE-2014-1761)

**MS14-018**

-   一名匿名研究人员与 [HP's](http://www.hpenterprisesecurity.com/products) [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0325)
-   [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Dr. Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1751)
-   [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Dr. Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1752)
-   [Trend Micro](http://www.trendmicro.com/) 的 Yuki Chen 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1753)
-   096dc2a463051c0ac4b7caaf233f7eff 和 AMol NAik 与 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1755)
-   [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1760)

**对于 MS14-019**

-   Stefan Kanthak 与我们合作处理了 Windows 文件处理漏洞 (CVE-2014-0315)

**对于 MS14-020**

-   一位匿名研究人员与 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作报告了任意指针解除引用漏洞 (CVE-2014-1759)

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](http://technet.microsoft.com/security/bb980617)

帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)

本地支持（根据您的国家/地区）： [国际支持](http://support.microsoft.com/common/international.aspx)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2014 年 4 月 8 日）： 已发布公告摘要。

 

*页面生成时间 2014-06-30 14:26Z-07:00.。*
