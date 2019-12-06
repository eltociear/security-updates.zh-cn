---
TOCTitle: 'MS16-JUL'
Title: 'Microsoft 安全公告摘要（2016 年 7 月）'
ms:assetid: 'ms16-jul'
ms:contentKeyID: 73201203
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms16-jul(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2016 年 7 月）
======================================

发布日期：2016年7月12日

**版本：** 2.0

本公告摘要列出了 2016 年 7 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅**受影响的软件**部分。

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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=808143">MS16-084</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新 (3169991)<br />
</strong>此安全更新程序修复了 Internet Explorer 中的多个漏洞。如果用户使用 Internet Explorer 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，则攻击者可完全控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=808148">MS16-085</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 累积安全更新 (3169999)<br />
</strong>此安全更新程序可修复 Microsoft Edge 中的多个漏洞。如果用户使用 Microsoft Edge 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=808144">MS16-086</a></p></td>
<td style="border:1px solid black;"><p><strong>JScript 和 VBScript 的累积安全更新 (3169996)<br />
</strong>此安全更新可修复 Microsoft Windows 的 JScript 和 VBScript 脚本引擎中的漏洞。如果用户访问经特殊设计的网站，此漏洞可能允许远程执行代码。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，则成功利用这些漏洞的攻击者可以控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=808150">MS16-087</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 打印后台处理程序组件安全更新 (3170005)<br />
</strong>此安全更新修复了 Microsoft Windows 中的漏洞。如果攻击者能够在工作站或打印服务器上执行中间人 (MiTM) 攻击或在目标网络上设置恶意打印服务器，最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=808151">MS16-088</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 安全更新 (3170008)<br />
</strong>此安全更新可解决 Microsoft Office 中的漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么这些漏洞中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响较小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web Apps</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=808157">MS16-089</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 安全内核模式安全更新 (3170050)<br />
</strong>此安全更新修复了 Microsoft Windows 中的一个漏洞。如果 Windows 安全内核模式未正确地处理内存中的对象，会存在信息泄漏漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=808590">MS16-090</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序安全更新 (3171481)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的多个漏洞。如果攻击者登录受影响的系统并运行一个为利用这些漏洞而经特殊设计的应用程序并控制受影响的系统，最严重的漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=808156">MS16-091</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 安全更新 (3170048)<br />
</strong>此安全更新程序可修复 Microsoft .NET Framework 中的一个漏洞。如果攻击者将经特殊设计的 XML 文件上传到基于 Web 的应用程序，此漏洞可能允许信息泄漏。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=808706">MS16-092</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核安全更新程序 (3171910)<br />
</strong>此安全更新修复了 Microsoft Windows 中的漏洞。如果 Windows 内核无法确定何种低完整性应用程序可以使用特定对象管理器功能，最严重的漏洞可能允许安全功能绕过。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=809010">MS16-093</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 安全更新 (3174060)<br />
</strong>此安全更新可修复安装在所有受支持版本的 Windows 8.1、Windows Server 2012、Windows RT 8.1、Windows Server 2012 R2 和 Windows 10 漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Adobe Flash Player</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=817339">MS16-094</a></p></td>
<td style="border:1px solid black;"><p><strong>安全启动安全更新 (3177404)<br />
</strong>此安全更新修复了 Microsoft Windows 中的一个漏洞。如果攻击者在目标设备上安装受影响的策略，会存在安全启动安全功能绕过漏洞。攻击者必须具有管理权限或物理访问权限才可安装策略和绕过安全启动。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>




利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。按公告 ID（而非 CVE ID）顺序列出了漏洞。公告中仅包含严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
对于您可能需要安装的每个安全更新，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新程序的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。
  
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
**较旧软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**较旧软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-084：Internet Explorer 累积安全更新 (3169991)**](https://go.microsoft.com/fwlink/?linkid=808143)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3204](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3204)

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
[CVE-2016-3240](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3240)

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
[CVE-2016-3241](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3241)

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
[CVE-2016-3242](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3242)

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
[CVE-2016-3243](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3243)

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
[CVE-2016-3245](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3245)

</td>
<td style="border:1px solid black;">
Internet Explorer 安全功能绕过漏洞

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
[CVE-2016-3248](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3248)

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
[CVE-2016-3259](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3259)

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
[CVE-2016-3260](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3260)

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
[CVE-2016-3261](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3261)

</td>
<td style="border:1px solid black;">
Internet Explorer 信息泄漏漏洞

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
[CVE-2016-3264](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3264)

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
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3273](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3273)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3- 不太可能利用

</td>
<td style="border:1px solid black;">
3- 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3274](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3274)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

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
[CVE-2016-3276](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3276)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

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
[CVE-2016-3277](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3277)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

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
[**MS16-085：Microsoft Edge 累积安全更新 (3169999)**](https://go.microsoft.com/fwlink/?linkid=808148)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3244](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3244)

</td>
<td style="border:1px solid black;">
Microsoft Edge 安全功能绕过

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
[CVE-2016-3246](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3246)

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
[CVE-2016-3248](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3248)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

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
[CVE-2016-3259](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3259)

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
[CVE-2016-3260](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3260)

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
[CVE-2016-3264](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3264)

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
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3265](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3265)

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
[CVE-2016-3269](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3269)

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
[CVE-2016-3271](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3271)

</td>
<td style="border:1px solid black;">
脚本引擎信息泄漏漏洞

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
[CVE-2016-3273](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3273)

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
[CVE-2016-3274](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3274)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

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
[CVE-2016-3276](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3276)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

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
[CVE-2016-3277](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3277)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

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
[**MS16-086：JScript 和 VBScript 的累积安全更新 (3169996)**](https://go.microsoft.com/fwlink/?linkid=808144)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3204](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3204)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-087：Microsoft 打印后台处理程序安全更新 (3170005)**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3238](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3238)

</td>
<td style="border:1px solid black;">
Windows 打印后台处理程序远程执行代码漏洞

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
[CVE-2016-3239](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3239)

</td>
<td style="border:1px solid black;">
Windows 打印后台处理程序特权提升漏洞

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
[**MS16-088：Microsoft Office 安全更新 (3170008)**](https://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3278](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3278)

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
[CVE-2016-3279](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3279)

</td>
<td style="border:1px solid black;">
Microsoft 安全功能绕过漏洞

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
[CVE-2016-3280](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3280)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

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
[CVE-2016-3281](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3281)

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
<td style="border:1px solid black;">
[CVE-2016-3282](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3282)

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
[CVE-2016-3283](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3283)

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
[CVE-2016-3284](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3284)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-089：Windows 安全内核模式安全更新 (3170050)**](https://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3256](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3256)

</td>
<td style="border:1px solid black;">
Windows 安全内核信息泄漏漏洞

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
<td style="border:1px solid black;" colspan="5">
[**MS16-090：Windows 内核模式驱动程序安全更新 (3171481)**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3249](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3249)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3250](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3250)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3251](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3251)

</td>
<td style="border:1px solid black;">
Win32k 信息泄漏漏洞

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
[CVE-2016-3252](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3252)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

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
[CVE-2016-3254](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3254)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

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
[CVE-2016-3286](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3286)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

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
[**MS16-091：.NET Framework 安全更新 (3170048)**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3255](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3255)

</td>
<td style="border:1px solid black;">
.NET 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[**MS16-092：Windows 内核安全更新程序 (3171910)**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3258](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3258)

</td>
<td style="border:1px solid black;">
Windows 文件系统安全功能绕过

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
[CVE-2016-3272](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3272)

</td>
<td style="border:1px solid black;">
Windows 内核信息泄漏漏洞

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
[**MS16-093：Adobe Flash Player 安全更新 (3174060)**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-25](https://helpx.adobe.com/security/products/flash-player/apsb16-25.html)

</td>
<td style="border:1px solid black;">
请参阅 [Adobe 安全公告 APSB16-25](https://helpx.adobe.com/security/products/flash-player/apsb16-25.html)，了解漏洞严重性级别和更新优先级级别。

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
<td style="border:1px solid black;" colspan="5">
[**MS16-094：安全启动安全更新 (3177404)**](https://go.microsoft.com/fwlink/?linkid=817339)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3287](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3287)

</td>
<td style="border:1px solid black;">
安全启动安全功能绕过

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

下表按主要软件类别和严重性的排序列出了公告。

通过这些表，您可以了解可能需要安装的安全更新程序。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新程序。如果列出了软件程序或组件，则也会列出软件更新程序的严重等级。

**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新程序（基于系统上已安装的程序或组件）。

 

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
[**MS16-084**](https://go.microsoft.com/fwlink/?linkid=808143)                   

</td>
<td style="border:1px solid black;">
[**MS16-085**](https://go.microsoft.com/fwlink/?linkid=808148)                   

</td>
<td style="border:1px solid black;">
[**MS16-086**](https://go.microsoft.com/fwlink/?linkid=808144)                   

</td>
<td style="border:1px solid black;">
[**MS16-087**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](https://go.microsoft.com/fwlink/?linkid=808157)

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
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3170106)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3170455)  
（严重）

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
Internet Explorer 9  
(3170106)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3170455)  
（严重）

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
[**MS16-084**](https://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](https://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](https://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](https://go.microsoft.com/fwlink/?linkid=808157)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 9  
(3170106)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3170455)  
（严重）

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
Internet Explorer 9  
(3170106)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3170455)  
（严重）

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
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3170455)  
（严重）

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
[**MS16-084**](https://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](https://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](https://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](https://go.microsoft.com/fwlink/?linkid=808157)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 11  
(3170106)  
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
(3170455)  
（严重）

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
Internet Explorer 11  
(3170106)  
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
(3170455)  
（严重）

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
[**MS16-084**](https://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](https://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](https://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](https://go.microsoft.com/fwlink/?linkid=808157)

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
**无**

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
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
(3170455)  
（严重）

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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3170455)  
（严重）

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
[**MS16-084**](https://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](https://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](https://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](https://go.microsoft.com/fwlink/?linkid=808157)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 11  
(3170106)  
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
(3170455)  
（严重）

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
(3170106)  
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
(3170455)  
（严重）

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
[**MS16-084**](https://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](https://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](https://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](https://go.microsoft.com/fwlink/?linkid=808157)

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
**无**

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3170106)  
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
(3170455)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
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
(3170455)  
（严重）

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
[**MS16-084**](https://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](https://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](https://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](https://go.microsoft.com/fwlink/?linkid=808157)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
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
(3170455)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS16-084**](https://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](https://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](https://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](https://go.microsoft.com/fwlink/?linkid=808157)

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
(3163912)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163912)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163912)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163912)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163912)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163912)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163912)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163912)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3172985)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3172985)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3172985)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3172985)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3172985)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3172985)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3172985)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3172985)  
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
[**MS16-084**](https://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](https://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](https://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](https://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](https://go.microsoft.com/fwlink/?linkid=808157)

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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3169659)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3170455)  
（严重）

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
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3170455)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
JScript 5.8 和 VBScript 5.8  
(3169658)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3170455)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
Windows Server 2012（服务器核心安装）  
(3170455)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
Windows Server 2012 R2（服务器核心安装）  
(3170455)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS16-090**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](https://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163251)  
（重要）  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163251)  
（重要）  
Microsoft .NET Framework 4.6  
(3164025)  
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-090**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](https://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163251)  
（重要）  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163251)  
（重要）  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
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
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-090**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](https://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163251)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163251)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-090**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](https://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163251)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
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
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-090**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](https://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163291)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3170377)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3169704)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3172727)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163291)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3170377)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3169704)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3172727)  
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
[**MS16-090**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](https://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163246)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163250)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164023)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3170377)  
（重要）  
Windows Server 2012  
(3169704)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3172727)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163291)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3170377)  
（重要）  
Windows Server 2012 R2  
(3169704)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3172727)  
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
[**MS16-090**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](https://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3163291)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3170377)  
（重要）  
Windows RT 8.1  
(3169704)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3172727)  
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
[**MS16-090**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](https://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 10（用于 32 位系统）  
(3163912)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163912)  
（重要）  
Microsoft .NET Framework 4.6  
(3163912)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163912)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3163912)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163912)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163912)  
（重要）  
Microsoft .NET Framework 4.6  
(3163912)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163912)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3163912)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3172985)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3172985)  
（重要）  
Microsoft .NET Framework 4.6.1  
(3172985)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3172985)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3172985)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3172985)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3172985)  
（重要）  
Microsoft .NET Framework 4.6.1  
(3172985)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3172985)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3172985)  
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
[**MS16-090**](https://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](https://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](https://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](https://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](https://go.microsoft.com/fwlink/?linkid=817339)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3168965)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3168965)  
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
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163251)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163246)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163250)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164023)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3170377)  
（重要）  
Windows Server 2012（服务器核心安装）  
(3169704)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3172727)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3168965)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3163291)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3170377)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(3169704)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3172727)  
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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
(3115306)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3115311)  
（严重）

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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
(3115315)  
（严重）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3115322)  
（重要）  
Microsoft Outlook 2010 Service Pack 2（32 位版本）  
(3115246)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（32 位版本）  
(3115118)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3115317)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3115315)  
（严重）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3115322)  
（重要）  
Microsoft Outlook 2010 Service Pack 2（64 位版本）  
(3115246)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（64 位版本）  
(3115118)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3115317)  
（严重）

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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(3115262)  
（重要）  
Microsoft Outlook 2013 Service Pack 1（32 位版本）  
(3115259)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（32 位版本）  
(3115254)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3115292)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(3115262)  
（重要）  
Microsoft Outlook 2013 Service Pack 1（64 位版本）  
(3115259)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（64 位版本）  
(3115254)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3115292)  
（严重）

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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3115262)  
（重要）  
Microsoft Outlook 2013 RT Service Pack 1  
(3115259)  
（重要）  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3115254)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(3115292)  
（严重）

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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016（32 位版本）  
(3115272)  
（重要）  
Microsoft Outlook 2016（32 位版本）  
(3115279)  
（重要）  
Microsoft Word 2016（32 位版本）  
(3115301)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016（64 位版本）  
(3115272)  
（重要）  
Microsoft Outlook 2016（64 位版本）  
(3115279)  
（重要）  
Microsoft Word 2016（64 位版本）  
(3115301)  
（严重）

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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3170463)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3170463)  
（严重）

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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3170460)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3170460)  
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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(3115308)  
（重要）  
Microsoft Office 兼容包 Service Pack 3  
(3115309)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3115114)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115393)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115395)  
（严重）

</td>
</tr>
</table>

**MS16-088 注释**

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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Word Automation Services  
(3115312)  
（重要）

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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3115285)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft SharePoint Server 2016

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2016  
(3115299)  
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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
(3115318)  
（重要）

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
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3115289)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Office Online Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-088**](https://go.microsoft.com/fwlink/?linkid=808151)

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
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3115386)  
（重要）

</td>
</tr>
</table>

**MS16-088 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新程序。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。 

鸣谢
----

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/mt674627.aspx)。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外发布的安全公告中不提供 Microsoft Windows 恶意软件删除工具的更新版本。

### MU、WU 和 WSUS 上的与安全无关的更新程序

若要了解 Windows 更新和 Microsoft 更新上的与安全无关的更新程序，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/wsus/bb456965)。显示除 Microsoft Windows 之外的其他 Microsoft 产品的所有新的、修订过的和重新发布的更新程序。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件提供商可以使用此类漏洞信息通过其安全软件或设备（如防病毒、基于网络的入侵检测系统或基于主机的入侵防护系统）更新对客户提供的保护。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新程序**

可从以下位置获得针对其他安全问题的更新程序：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft 更新](https://go.microsoft.com/fwlink/?linkid=40747)提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新程序。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案：[TechNet 安全性疑难解答与支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](https://support.microsoft.com/zh-cn/contactus/cu_sc_virsec_master)

基于国家/地区的本地支持：[国际支持](https://support.microsoft.com/zh-cn/common/international.aspx)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不提供任何种类的明示或默示担保，包括对适销性和特定用途适用性的担保。在任何情况下，Microsoft Corporation 或其供应商都不会对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订

-   V1.0（2016 年 7 月 12 日）：已发布公告摘要。

*页面生成时间：2016/7/13 10:05-07:00。*
