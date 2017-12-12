---
TOCTitle: 'MS16-JAN'
Title: 'Microsoft 安全公告摘要（2016 年 1 月）'
ms:assetid: 'ms16-jan'
ms:contentKeyID: 72150174
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms16-jan(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2016 年 1 月）
======================================

发布日期： 2016 年 1 月 12 日

**版本：** 1.0

本公告摘要列出了 2016 年 1 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。 请参阅**其他信息**部分。

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
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=717999">MS16-001</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积安全更新 (3124903)</strong> <br />
此安全更新可修复 Internet Explorer 中的漏洞。 较为严重的漏洞可能在用户使用 Internet Explorer 查看经特殊设计的网页时允许远程执行代码。 成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。 如果当前用户使用管理用户权限登录，成功利用该漏洞的攻击者便可控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=718002">MS16-002</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 的累积安全更新 (3124904)<br />
</strong>此安全更新可修复 Microsoft Edge 中的漏洞。 如果用户使用 Microsoft Edge 查看经特殊设计的网页，则所有漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=718004">MS16-003</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 JScript 和 VBScript 累积安全更新 (3125540) <br />
</strong>此安全更新可修复 Microsoft Windows 的 VBScript 脚本引擎中一个漏洞。 如果用户访问经特殊设计的网站，此漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。 如果当前用户使用管理用户权限登录，成功利用该漏洞的攻击者便可控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=717998">MS16-004</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Microsoft Office 安全更新 (3124585)</strong> <br />
此安全更新可修复 Microsoft Office 中的漏洞。 最严重的漏洞可能在用户打开特制 Microsoft Office 文件时允许远程执行代码。 成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Visual Basic</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=718001">MS16-005</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Windows 内核模式驱动程序安全更新 (3124584)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。 如果用户访问恶意网站，则其中较为严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=717994">MS16-006</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Silverlight 安全更新 (3126036)</strong> <br />
此安全更新可修复 Microsoft Silverlight 中的漏洞。 如果用户访问包含经特殊设计的 Silverlight 应用程序的受到破坏的网站，则该漏洞可能允许远程执行代码。 攻击者无法强迫用户访问受到破坏的网站。 而必须诱使他们进行访问，通常是通过让用户单击电子邮件或即时消息中的链接转到攻击者的网站。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Silverlight</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=718006">MS16-007</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Microsoft Windows 安全更新 (3124901)</strong> <br />
此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者能够登录目标系统并且运行经特殊设计的应用程序，则其中最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/en-us/kb/3124266">3124266</a><br />
<a href="https://support.microsoft.com/en-us/kb/3124263">3124263</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=718007">MS16-008</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复特权提升漏洞的 Windows 内核安全更新 (3124605)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者登录受影响的系统并运行经特殊设计的应用程序，则这些漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=717997">MS16-010</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复欺骗漏洞的 Microsoft Exchange Server 安全更新 (3124557)</strong><br />
此安全更新可修复 Microsoft Exchange Server 中的多个漏洞。 如果 Outlook Web Access (OWA) 未正确处理 Web 请求和清理用户输入和电子邮件内容，则其中最严重的漏洞可能允许欺骗。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
欺骗</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Exchange Server</p></td>
</tr>  
</tbody>  
</table>
<p> </p>



利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月修复的各个漏洞的利用评估。 这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
对于您可能需要安装的每个安全更新，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。 根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/zh-cn/security/cc998259)。
  
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
<td style="border:1px solid black;">
**较旧软件版本的利用评估**

</td>
<td style="border:1px solid black;">
**较旧软件版本的利用评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-001： Internet Explorer 累积安全更新 (3124903)**](http://go.microsoft.com/fwlink/?linkid=717999)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0002](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0002)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0005](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0005)

</td>
<td style="border:1px solid black;">
Internet Explorer 特权提升漏洞

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-002： Microsoft Edge 的累积安全更新 (3124904)**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0003](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0003)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0024](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0024)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-003： 用于修复远程执行代码漏洞的 JScript 和 VBScript 累积安全更新 (3125540)**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0002](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0002)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-004： 用于修复远程执行代码漏洞的 Microsoft Office 安全更新 (3124585)**](http://go.microsoft.com/fwlink/?linkid=717998)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6117)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint 安全功能绕过漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

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
[CVE-2016-0010](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0010)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0011](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0011)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint 安全功能绕过漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0012](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0012)

</td>
<td style="border:1px solid black;">
Microsoft Office ASLR 绕过

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0035](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0035)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-005： 用于修复特权提升漏洞的 Windows 内核模式驱动程序安全更新 (3124584)**](http://go.microsoft.com/fwlink/?linkid=718001)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0008](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0008)

</td>
<td style="border:1px solid black;">
Windows GDI32.dll ASLR 绕过漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0009)

</td>
<td style="border:1px solid black;">
Win32k 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-006： 用于修复远程执行代码漏洞的 Silverlight 安全更新 (3126036)**](http://go.microsoft.com/fwlink/?linkid=717994)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0034](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0034)

</td>
<td style="border:1px solid black;">
Silverlight 运行时远程执行代码漏洞

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-007： 用于修复远程执行代码漏洞的 Microsoft Windows 安全更新 (3124901)**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0014](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0014)

</td>
<td style="border:1px solid black;">
DLL 加载特权提升漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0015)

</td>
<td style="border:1px solid black;">
DirectShow 堆损坏远程执行代码漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0016)

</td>
<td style="border:1px solid black;">
DLL 加载远程执行代码漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0018](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0018)

</td>
<td style="border:1px solid black;">
DLL 加载远程执行代码漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0019](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0019)

</td>
<td style="border:1px solid black;">
Windows 远程桌面协议安全绕过漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

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
[CVE-2016-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0020)

</td>
<td style="border:1px solid black;">
MAPI DLL 加载特权提升漏洞

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-008: 用于修复特权提升漏洞的 Windows 内核安全更新 (3124605)**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0006](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0006)

</td>
<td style="border:1px solid black;">
Windows 装入点特权提升漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0007](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0007)

</td>
<td style="border:1px solid black;">
Windows 装入点特权提升漏洞

</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;" colspan="5">
[**MS16-010： 用于修复欺骗漏洞的 Microsoft Exchange Server 安全更新 (3124557)**](http://go.microsoft.com/fwlink/?linkid=717997)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0029)

</td>
<td style="border:1px solid black;">
Exchange 欺骗漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

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
[CVE-2016-0030](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0030)

</td>
<td style="border:1px solid black;">
Exchange 欺骗漏洞

</td>
<td style="border:1px solid black;">
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
[CVE-2016-0031](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0031)

</td>
<td style="border:1px solid black;">
Exchange 欺骗漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

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
[CVE-2016-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0032)

</td>
<td style="border:1px solid black;">
Exchange 欺骗漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

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

通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果列出了软件程序或组件，则也会列出软件更新的严重等级。

**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

 

### Windows 操作系统和组件（表 1-2）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=717999)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
（严重）  
Internet Explorer 8  
(3124275)  
（严重）  
Internet Explorer 9  
(3124275)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3124000)  
（严重）  
Windows Vista Service Pack 2  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
（严重）  
Internet Explorer 8  
(3124275)  
（严重）  
Internet Explorer 9  
(3124275)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3124000)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
（中等）  
Internet Explorer 8  
(3124275)  
（中等）  
Internet Explorer 9  
(3124275)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3124000)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
（中等）  
Internet Explorer 8  
(3124275)  
（中等）  
Internet Explorer 9  
(3124275)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3124000)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3124000)  
（严重）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
（严重）  
Internet Explorer 9  
(3124275)  
（严重）  
Internet Explorer 10  
(3124275)  
（严重）  
Internet Explorer 11  
(3124275)  
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
(3124000)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
（严重）  
Internet Explorer 9  
(3124275)  
（严重）  
Internet Explorer 10  
(3124275)  
（严重）  
Internet Explorer 11  
(3124275)  
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
(3124000)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
（中等）  
Internet Explorer 9  
(3124275)  
（中等）  
Internet Explorer 10  
(3124275)  
（中等）  
Internet Explorer 11  
(3124275)  
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
(3124000)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3124000)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3124001)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124266)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124266)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3124266)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124266)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124266)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3124266)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位 Windows 10 版本 1511 系统

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124263)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124263)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
32 位 Windows 10 版本 1511 系统  
(3124263)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124263)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124263)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3124263)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
VBScript 5.7  
(3124624)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3124000)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3124001)  
（重要）

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
VBScript 5.7  
(3124624)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3124000)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3124001)  
（重要）

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
VBScript 5.8  
(3124625)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3124000)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3124001)  
（重要）

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
Windows Server 2012  
（服务器核心安装）  
(3124001)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3124001)  
（重要）

</td>
</tr>
</table>

 

### Windows 操作系统和组件（表 2-2）

<p> </p>

<table style="border:1px solid black;">
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
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3121918)  
（重要）  
Windows Vista Service Pack 2  
(3109560)  
（重要）  
Windows Vista Service Pack 2  
(3110329)  
（重要）  
Windows Vista Service Pack 2  
(3108664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3121918)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3109560)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3110329)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3108664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3121212)  
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
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3121918)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3109560)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3110329)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3108664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3121918)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3109560)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3110329)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3108664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3121918)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3109560)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3110329)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3108664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3121212)  
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
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3121918)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3109560)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3110329)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3121461)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3108664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3121918)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3109560)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3110329)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3121461)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3108664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3121212)  
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
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3121918)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3109560)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3110329)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3108664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3121918)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3109560)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3110329)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3108664)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3121212)  
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
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3121918)  
（重要）  
Windows 8（用于 32 位系统）  
(3109560)  
（重要）  
Windows 8（用于 32 位系统）  
(3110329)  
（重要）  
Windows 8（用于 32 位系统）  
(3121461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3121918)  
（重要）  
Windows 8（用于基于 x64 的系统）  
(3109560)  
（重要）  
Windows 8（用于基于 x64 的系统）  
(3110329)  
（重要）  
Windows 8（用于基于 x64 的系统）  
(3121461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3121918)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3109560)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3110329)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3121461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3121918)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3109560)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3110329)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3121461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3121212)  
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
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3121918)  
（重要）  
Windows Server 2012  
(3109560)  
（重要）  
Windows Server 2012  
(3110329)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3121918)  
（重要）  
Windows Server 2012 R2  
(3109560)  
（重要）  
Windows Server 2012 R2  
(3110329)  
（重要）  
Windows Server 2012 R2  
(3121461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3121212)  
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
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3121918)  
（重要）  
Windows RT  
(3110329)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3121918)  
（重要）  
Windows RT 8.1  
(3110329)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3124266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3124266)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3124266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3124266)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
32 位 Windows 10 版本 1511 系统

</td>
<td style="border:1px solid black;">
32 位 Windows 10 版本 1511 系统  
(3124263)  
（重要）

</td>
<td style="border:1px solid black;">
32 位 Windows 10 版本 1511 系统  
(3124263)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3124263)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3124263)  
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
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3121918)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3121918)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3121918)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3121918)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3121212)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3121918)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3121212)  
（重要）

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
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
(2881067)  
（重要）  
Microsoft Office 2007 Service Pack 3  
(3114541)  
（严重）  
Microsoft Excel 2007 Service Pack 3  
(3114540)  
（重要）  
Microsoft PowerPoint 2007 Service Pack 3  
(3114429)  
（重要）  
Microsoft Visio 2007 Service Pack 3  
(3114421)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3114549)  
（重要）

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
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
(2881029)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3114553)  
（严重）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3114554)  
（重要）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3114564)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（32 位版本）  
(3114396)  
（重要）  
Microsoft Visio 2010 Service Pack 2（32 位版本）  
(3114402)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3114557)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3114553)  
（严重）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3114554)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3114564)  
（重要）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3114564)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（64 位版本）  
(3114396)  
（重要）  
Microsoft Visio 2010 Service Pack 2（64 位版本）  
(3114402)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3114557)  
（重要）

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
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3039794)  
（重要）  
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3114486)  
（严重）  
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(3114504)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（32 位版本）  
(3114482)  
（重要）  
Microsoft Visio 2013 Service Pack 1（32 位版本）  
(3114489)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3114494)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）  
(3114486)  
（严重）  
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(3114504)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（64 位版本）  
(3114482)  
（重要）  
Microsoft Visio 2013 Service Pack 1（64 位版本）  
(3114489)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3114494)  
（重要）

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
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
Microsoft Office 2013 RT Service Pack 1  
(3114486)  
（严重）  
Microsoft Excel 2013 RT Service Pack 1  
(3114504)  
（重要）  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3114482)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(3114494)  
（重要）

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
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
Microsoft Office 2016（32 位版本）  
(2920727)  
（重要）  
Microsoft Office 2016（32 位版本）  
(3114527)  
（严重）  
Microsoft Excel 2016（32 位版本）  
(3114520)  
（重要）  
Microsoft PowerPoint 2016（32 位版本）  
(3114518)  
（重要）  
Microsoft Visio 2016（32 位版本）  
(3114511)  
（重要）  
Microsoft Word 2016（32 位版本）  
(3114526)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）  
(3114527)  
（严重）  
Microsoft Office 2016（64 位版本）  
(3114520)  
（重要）  
Microsoft Excel 2016（64 位版本）  
(3114520)  
（重要）  
Microsoft PowerPoint 2016（64 位版本）  
(3114518)  
（重要）  
Microsoft Visio 2016（64 位版本）  
(3114511)  
（重要）  
Microsoft Word 2016（64 位版本）  
(3114526)  
（重要）

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
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
(3133699)  
（严重）  
Microsoft PowerPoint for Mac 2011  
(3133699)  
（严重）  
Microsoft Word for Mac 2011  
(3133699)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3133711)  
（严重）  
Microsoft PowerPoint 2016 for Mac  
(3133711)  
（严重）  
Microsoft Word 2016 for Mac  
(3133711)  
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
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(3114546)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114547)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114569)  
（严重）

</td>
</tr>
</table>

**MS16-004 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft 开发工具和软件

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-006**](http://go.microsoft.com/fwlink/?linkid=717994)

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
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5  
(3126036)  
（严重）  
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3126036)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5  
(3126036)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3126036)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5  
(3126036)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3126036)  
（严重）

</td>
</tr>
</table>

 

### Microsoft Server 软件

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3114503)  
（重要）

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
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3124557)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 10  
(3124557)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 11  
(3124557)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016  
(3124557)  
（重要）

</td>
</tr>
</table>

**MS16-004 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

### Microsoft Visual Basic 软件

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Visual Basic 6.0 Runtime**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要提示**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Basic 6.0 Runtime

</td>
<td style="border:1px solid black;">
Visual Basic 6.0 Runtime  
(3096896)  
（重要）

</td>
</tr>
</table>

**MS16-004 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

检测和部署工具及指导
--------------------

<span id="sectionToggle3"></span>
许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](http://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

<span id="sectionToggle4"></span>
Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。 有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn903755.aspx)部分。

其他信息
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。 带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/zh-cn/lifecycle)。

IT 专业人员安全解决方案： [TechNet 安全故障排除和支持](http://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害： [病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

根据国家/地区进行本地支持： [国际支持](http://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2016 年 1 月 12 日）： 已发布公告摘要。

*页面生成时间：2016-01-07 13:56-08:00。*
