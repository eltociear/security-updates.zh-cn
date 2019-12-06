---
TOCTitle: 'MS16-DEC'
Title: 'Microsoft 安全公告摘要（2016 年 12 月）'
ms:assetid: 'ms16-dec'
ms:contentKeyID: 74262521
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms16-dec(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2016 年 12 月）
=======================================

发布时间：2016 年 12 月 13 日

**版本：**1.0

本公告摘要列出了 2016 年 12 月发布的安全公告。

每当 Microsoft 安全公告发布时，如需了解如何收到自动通知的相关信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新以及与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

**注意** 重要提醒：[安全更新指南](https://portal.msrc.microsoft.com/zh-cn/security-guidance)自 2017 年 2 月起将替代安全公告。有关更多详细信息，请参阅我们的博客文章 [Furthering our commitment to security updates](https://blogs.technet.microsoft.com/msrc/2016/11/08/furthering-our-commitment-to-security-updates/)（深化我们对安全更新的承诺）。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节**受影响的软件**。

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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834441">MS16-144</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新 (3204059)</strong><br />
此安全更新修复了 Internet Explorer 中的漏洞。如果用户使用 Internet Explorer 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，那么攻击者便可控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834442">MS16-145</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 累积安全更新 (3204062)</strong><br />
此安全更新修复了 Microsoft Edge 中的漏洞。如果用户使用 Microsoft Edge 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834444">MS16-146</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Graphics Component 安全更新程序 (3204066)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的漏洞。如果用户访问经特殊设计的网站或打开经特殊设计的文档，则其中最严重的漏洞可能允许远程执行代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834947">MS16-147</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Uniscribe 安全更新 (3204063)</strong><br />
此安全更新修复了 Windows Uniscribe 中的一个漏洞。如果用户访问经特殊设计的网站或打开经特殊设计的文档，则该漏洞可能允许远程执行代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834445">MS16-148</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 安全更新程序 (3204068)<br />
</strong>此安全更新程序修复了 Microsoft Office 中的漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么这些漏洞中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响较小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web Apps</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834964">MS16-149</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 安全更新程序 (3205655)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的漏洞。如果本地已认证的攻击者运行经特殊设计的应用程序，较严重的漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834939">MS16-150</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Secure Kernel Mode 安全更新程序 (3205642)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的一个漏洞。如果本地已认证攻击者在目标系统上运行经特殊设计的应用程序，此漏洞可能允许特权提升。成功利用此漏洞的攻击者可能违反了 VTL（Virtual Trust Level，虚拟信任级别）。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834956">MS16-151</a></p></td>
<td style="border:1px solid black;"><p><strong>内核模式驱动程序安全更新 (3205651)<br />
</strong>此安全更新修复了 Microsoft Windows 中的漏洞。如果攻击者登录到受影响的系统并运行一个为利用这些漏洞而经特殊设计的应用程序并控制受影响的系统，漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834960">MS16-152</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核安全更新程序 (3199709)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的漏洞。当 Windows 内核不正确地处理内存中对象时，该漏洞可能允许信息泄漏。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=835768">MS16-153</a></p></td>
<td style="border:1px solid black;"><p><strong>通用日志文件系统驱动程序安全更新 (3207328)<br />
</strong>此安全更新修复了 Microsoft Windows 中的漏洞。当 Windows CLFS（Common Log File System，通用日志文件系统）驱动程序不正确地处理内存中对象时，该漏洞可能允许特权提升。在本地攻击情形中，攻击者可能通过运行经特殊设计的应用程序利用此漏洞，进而控制受影响的系统。成功利用此漏洞的攻击者可以在特权提升环境中运行进程。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834443">MS16-154</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 安全更新程序 (3209498)<br />
</strong>此安全更新程序修复了 Adobe Flash Player 在 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10 和 Windows Server 2016 所有支持版本上安装时的漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Adobe Flash Player</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=834937">MS16-155</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 安全更新 (3205640)<br />
</strong>此安全更新修复了 Microsoft .Net Framework 中的漏洞。.NET Framework 4.6.2 中存在安全漏洞，可能允许攻击者访问应由加密机制保护的静态信息。此更新通过更正 Framework 处理开发人员提供密钥的方式来修复漏洞，从而合理保护静态数据。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、Microsoft .NET Framework</p></td>
</tr>  
</tbody>  
</table>

  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。按公告 ID（而非 CVE ID）顺序列出了漏洞。公告中仅包含严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
针对你可能需要安装的每个安全更新程序，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据你的特定配置，检查下面的每个评估，从而确定部署本月更新程序的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。
  
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
**最新软件版本的  
利用性评估**

</td>
<td style="border:1px solid black;">
**旧软件版本的  
利用性评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用性评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-144：Internet Explorer 累积安全更新程序 (3204059)**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7202](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7202)

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
[CVE-2016-7278](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7278)

</td>
<td style="border:1px solid black;">
Windows 超链接对象库信息泄漏漏洞

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
[CVE-2016-7279](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7279)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

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
[CVE-2016-7281](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7281)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器安全功能绕过

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[CVE-2016-7282](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7282)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[CVE-2016-7283](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-cve-2016-7283)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

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
[CVE-2016-7284](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7284)

</td>
<td style="border:1px solid black;">
Internet Explorer 信息泄漏漏洞

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
[CVE-2016-7287](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7287)

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
[**MS16-145：Microsoft Edge 累积安全更新程序 (3204062)**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7181](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7181)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[CVE-2016-7206](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7206)

</td>
<td style="border:1px solid black;">
Microsoft Edge 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[CVE-2016-7279](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7279)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7280](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7280)

</td>
<td style="border:1px solid black;">
Microsoft Edge 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[CVE-2016-7281](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7281)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器安全功能绕过

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[CVE-2016-7282](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7282)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[CVE-2016-7286](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7286)

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
[CVE-2016-7287](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7287)

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
<td style="border:1px solid black;">
[CVE-2016-7288](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7288)

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
[CVE-2016-7296](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7296)

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
<td style="border:1px solid black;">
[CVE-2016-7297](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7297)

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
[**MS16-146：Microsoft 图形组件安全更新 (3204066)**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7257](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7257)

</td>
<td style="border:1px solid black;">
GDI 信息泄漏漏洞

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
[CVE-2016-7272](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7272)

</td>
<td style="border:1px solid black;">
Windows 图形远程代码执行漏洞

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
[CVE-2016-7273](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7273)

</td>
<td style="border:1px solid black;">
Windows 图形远程代码执行漏洞

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
[**MS16-147：Microsoft Uniscribe 安全更新 (3204063)**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7274](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7274)

</td>
<td style="border:1px solid black;">
Windows Uniscribe 远程代码执行漏洞

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
[**MS16-148：Microsoft Office 安全更新 (3204068)**](https://go.microsoft.com/fwlink/?linkid=834445)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7257](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7257)

</td>
<td style="border:1px solid black;">
GDI 信息泄漏漏洞

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
[CVE-2016-7262](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7262)

</td>
<td style="border:1px solid black;">
Microsoft Office 安全功能绕过漏洞

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
[CVE-2016-7263](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7263)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[CVE-2016-7264](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7264)

</td>
<td style="border:1px solid black;">
Microsoft Office 信息泄漏漏洞

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
[CVE-2016-7265](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7265)

</td>
<td style="border:1px solid black;">
Microsoft Office 信息泄漏漏洞

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
[CVE-2016-7266](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7266)

</td>
<td style="border:1px solid black;">
Microsoft Office 安全功能绕过漏洞

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
[CVE-2016-7267](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7267)

</td>
<td style="border:1px solid black;">
Microsoft Office 安全功能绕过漏洞

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
[CVE-2016-7268](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7268)

</td>
<td style="border:1px solid black;">
Microsoft Office 信息泄漏漏洞

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
[CVE-2016-7275](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7275)

</td>
<td style="border:1px solid black;">
Microsoft Office OLE DLL 侧面加载漏洞

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
[CVE-2016-7276](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7276)

</td>
<td style="border:1px solid black;">
Microsoft Office 信息泄漏漏洞

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
[CVE-2016-7277](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7277)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

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
[CVE-2016-7289](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7289)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

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
<td style="border:1px solid black;">
[CVE-2016-7290](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7290)

</td>
<td style="border:1px solid black;">
Microsoft Office 信息泄漏漏洞

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
[CVE-2016-7291](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7291)

</td>
<td style="border:1px solid black;">
Microsoft Office 信息泄漏漏洞

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
[CVE-2016-7298](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7298)

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
[CVE-2016-7300](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7300)

</td>
<td style="border:1px solid black;">
Microsoft Office 特权提升漏洞

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
[**MS16-149：Windows 安全更新 (3205655)**](https://go.microsoft.com/fwlink/?linkid=834964)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7219](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7219)

</td>
<td style="border:1px solid black;">
Windows Crypto 驱动程序信息泄漏漏洞

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
[CVE-2016-7292](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7292)

</td>
<td style="border:1px solid black;">
Windows Installer 特权提升漏洞

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
[**MS16-150：Windows 安全内核模式安全更新 (3205642)**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7271](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7271)

</td>
<td style="border:1px solid black;">
Windows 安全内核模式特权提升漏洞

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
[**MS16-151：内核模式驱动程序安全更新 (3205651)**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7259](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7259)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7260](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7260)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

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
[**MS16-152：Windows 内核安全更新程序 (3199709)**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7258](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7258)

</td>
<td style="border:1px solid black;">
Windows 内核内存地址信息泄露漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-153：通用日志文件系统驱动程序安全更新程序 (3207328)**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7295](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7295)

</td>
<td style="border:1px solid black;">
Windows 通用日志文件系统驱动程序信息泄漏漏洞

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
[**MS16-154：Adobe Flash Player 安全更新程序 (3202790)**](https://go.microsoft.com/fwlink/?linkid=834443)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-39](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-39.html)

</td>
<td style="border:1px solid black;">
关于漏洞安全性和更新优先级级别的信息，请参阅 Adobe 安全公告 [APSB16-39](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-39.html)。

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-155：.NET Framework 安全更新 (3205640)**](https://go.microsoft.com/fwlink/?linkid=834937)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7270](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7270)

</td>
<td style="border:1px solid black;">
.NET Framework 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

受影响的软件
------------

下表按主要软件类别和严重性的排序列出了公告。

通过这些表，您可以了解可能需要安装的安全更新程序。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新程序。如果列出了软件程序或组件，则也会列出软件更新程序的严重等级。

**注意** 你可能必须为单个漏洞安装多个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新程序（基于系统上已安装的程序或组件）。

### Windows 操作系统和组件（表 2-1）

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
（严重）  
Microsoft Windows 超链接对象库  
(3208481)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3204724)  
（重要）  
Windows Vista Service Pack 2  
(3205638)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3196348)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3204808)  
（重要）  
Windows Vista Service Pack 2  
(3196726)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
（严重）  
Microsoft Windows 超链接对象库  
(3208481)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3204724)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3205638)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3196348)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3204808)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3196726)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 9   
(3203621)  
（中等）  
Microsoft Windows 超链接对象库  
(3208481)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3204724)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3205638)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3196348)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3204808)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3196726)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
（中等）  
Microsoft Windows 超链接对象库  
(3208481)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3204724)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3205638)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3196348)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3204808)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3196726)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3204724)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3205638)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3196348)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3204808)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3196726)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
仅安全

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
不适用                   

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3205394)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
每月汇总

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3207752)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
仅安全

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
每月汇总

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
仅安全

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205394)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
每月汇总

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3207752)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3205394)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3207752)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
仅安全

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205400)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
每月汇总

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205401)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
仅安全

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205400)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
每月汇总

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205401)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
仅安全

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3205408)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月汇总

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3205409)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
仅安全

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205400)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月汇总

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月汇总

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205383)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205383)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3205383)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3205383)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3205383)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205383)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205383)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3205383)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3205383)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3205383)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205386)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205386)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3205386)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3205386)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3205386)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205386)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205386)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3205386)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3205386)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3205386)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3206632)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3206632)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3206632)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3204724)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3205638)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3196348)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3204808)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3196726)  
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
Windows Server 2008（用于 x64 系统）Service Pack 2（服务器核心安装）  
(3204724)  
（重要）  
Windows Server 2008（用于 x64 系统）Service Pack 2（服务器核心安装）  
(3205638)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3196348)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 x64 系统）Service Pack 2（服务器核心安装）  
(3204808)  
（重要）  
Windows Server 2008（用于 x64 系统）Service Pack 2（服务器核心安装）  
(3196726)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3205394)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3205394)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3207752)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3207752)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3205408)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3205408)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3205408)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3205409)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3205409)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3205409)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205400)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205400)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205401)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205401)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(3206632)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(3206632)  
（重要）

</td>
</tr>
</table>

### Windows 操作系统和组件（表 2-2）

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3204723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3203838)  
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
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3204723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3203838)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3204723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3203838)  
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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3204723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3203838)  
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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3204723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3203838)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用                   

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205400)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205400)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205400)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205400)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3205383)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3205383)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3205383)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3205383)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3205383)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3205383)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3205383)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3205383)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3205386)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3205386)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3205386)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3205386)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3205386)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3205386)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3205386)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3205386)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**服务器核心安装**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3204723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3203838)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3204723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3203838)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3205394)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3207752)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3205408)  
（重要）

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
Windows Server 2012  
（服务器核心安装）  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3205409)  
（重要）

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
Windows Server 2012 R2  
（服务器核心安装）  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205400)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205400)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
每月汇总

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3205401)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(3206632)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table> 

### Microsoft .NET Framework – 仅安全版本

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7 和 Windows Server 2008 R2  
Microsoft .NET Framework 4.6.2 更新 (KB3205406)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=827590)

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
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204801)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 10 版本 1607（用于 32 位系统）  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2016（用于基于 x64 的系统）  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204801)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）（服务器核心安装）  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
（重要）

</td>
</tr>
</table>

**MS16-155 须知**

此公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

### Microsoft .NET Framework – 每月汇总补丁版本

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7 和 Windows Server 2008 R2  
Microsoft .NET Framework 4.6.2 更新 (KB3205406)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205378)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205378)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205377)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205378)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 10 版本 1607（用于 32 位系统）  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2016（用于基于 x64 的系统）  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205379)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205377)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3205378)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）（服务器核心安装）  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
（重要）

</td>
</tr>
</table>

**MS16-155 须知**

此公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

 

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3128019)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3128025)  
（重要）  
Microsoft Office 2007 Service Pack 3  
(2883033)  
（严重）  
Microsoft Office 2007 Service Pack 3  
(3128020)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3128032)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3118380)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2889841)  
（严重）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3128037)  
（重要）  
Microsoft Publisher 2010 Service Pack 2（32 位版本）  
(3114395)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3128034)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3128032)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3118380)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2889841)  
（严重）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3128037)  
（重要）  
Microsoft Publisher 2010 Service Pack 2（64 位版本）  
(3114395)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3128034)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(3128008)  
（重要）  
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3127968)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(3128008)  
（重要）  
Microsoft Office 2013 Service Pack 1（64 位版本）  
(3127968)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3128008)  
（重要）  
Microsoft Office 2013 RT Service Pack 1  
(3127968)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016（32 位版本）  
(3128016)  
（重要）  
Microsoft Office 2016（32 位版本）  
(3127986)  
（重要）  
Microsoft Office 2016（32 位版本）  
（重要）<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016（64 位版本）  
(3128016)  
（重要）  
Microsoft Office 2016（64 位版本）  
(3127986)  
（重要）  
Microsoft Office 2016（64 位版本）  
（重要）<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3198808)  
（重要）  
Microsoft Excel for Mac 2011  
(3198808)  
（重要）  
Microsoft Word for Mac 2011  
(3198808)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
</td>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac  
(3198800)  
（重要）  
Microsoft Excel 2016 for Mac  
(3198800)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
其他 Office 软件

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(3128022)  
（重要）  
Microsoft Office 兼容包 Service Pack 3  
(3128024)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3128023)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3128044)  
（重要）  
Microsoft Word Viewer  
(3127995)  
（严重）

</td>
</tr>
</table>
<sup>[1]</sup>此条目仅适用于即点即用 (C2R) 版本。

**MS16-148 须知**

此公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

 

### Microsoft Office Services 和 Web Apps

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）

</td>
<td style="border:1px solid black;">
Excel Services  
(3127892)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）

</td>
<td style="border:1px solid black;">
Excel Services  
(3127892)  
（重要）

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3128029)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3128026)  
（重要）

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3128035)  
（重要）

</td>
</tr>
</table>

**MS16-148 须知**

此公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新程序。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。 

鸣谢
----

Microsoft 认可在安全社区中通过可靠的漏洞披露渠道帮助我们保护客户的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/mt674627.aspx)。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外发布的安全公告中不提供 Microsoft Windows 恶意软件删除工具的更新版本。

### MU、WU 和 WSUS 上的与安全无关的更新程序

若要了解 Windows 更新和 Microsoft 更新上的与安全无关的更新程序，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/wsus/bb456965)。显示除 Microsoft Windows 之外的其他 Microsoft 产品的所有新的、修订过的和重新发布的更新程序。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新程序之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件提供商可以使用此类漏洞信息通过其安全软件或设备（如防病毒、基于网络的入侵检测系统或基于主机的入侵防护系统）更新对客户提供的保护。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新程序**

可从以下位置获得针对其他安全问题的更新：

-   可从 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)获取安全更新。通过对“安全更新”进行关键词搜索可以非常方便地找到这些更新。
-   [Microsoft 更新](https://go.microsoft.com/fwlink/?linkid=40747)提供了适用于消费者平台的更新程序。
-   你可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案：[TechNet 安全疑难解答和支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](https://support.microsoft.com/zh-cn/contactus/cu_sc_virsec_master)

基于国家/地区的本地支持：[国际支持](https://support.microsoft.com/zh-cn/common/international.aspx)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定用途的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版

-   V1.0（2016 年 12 月 13 日）：公告摘要已发布。

*页面生成时间：2016-12-07 12:39-08:00。*
