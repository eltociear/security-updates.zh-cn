---
TOCTitle: 'MS17-JAN'
Title: 'Microsoft 安全公告摘要（2017 年 1 月）'
ms:assetid: 'ms17-jan'
ms:contentKeyID: 74294058
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms17-jan(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2017 年 1 月）
======================================

发布时间：2017 年 1 月 10 日

**版本：**1.1

本公告摘要列出了 2017 年 1 月发布的安全公告。

有关每当 Microsoft 安全公告发布时如何接收自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新以及与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

**注意：**2017 年 1 月的星期二发布的更新中不存在安全修复或质量改进。因此，本月不存在仅安全质量更新或月度安全质量汇总更新版本。

提醒注意：[安全更新指南](https://portal.msrc.microsoft.com/zh-cn/security-guidance)自 2017 年 2 月起将替代安全公告。有关更多详细信息，请参阅我们的博客文章 [Furthering our commitment to security updates](https://blogs.technet.microsoft.com/msrc/2016/11/08/furthering-our-commitment-to-security-updates/)（深化我们对安全更新的承诺）。

执行摘要
--------

<span id="sectionToggle0"></span>
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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=838331">MS17-001</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 累积安全更新 (3214288)</strong><br />
此安全更新修复了 Microsoft Edge 中的漏洞。如果用户使用 Microsoft Edge 查看经特殊设计的网页，那么此漏洞可能允许特权提升。成功利用此漏洞的攻击者可能获得对易受攻击的系统的命名空间目录的提升权限并获得提升特权。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=838332">MS17-002</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 安全更新 (3214291)<br />
</strong>此安全更新修复了 Microsoft Office 中的一个漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么此漏洞可能会允许远程执行代码。成功利用此漏洞的攻击者可以在当前用户的环境中运行任意代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web Apps</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=838351">MS17-003</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 安全更新 (3214628)<br />
</strong>此安全更新修复了安装在 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10 和 Windows Server 2016 所有受支持版本上的 Adobe Flash Player 中的漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Adobe Flash Player</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=838352">MS17-004</a></p></td>
<td style="border:1px solid black;"><p><strong>本地安全认证子系统服务的安全更新 (3216771)<br />
</strong> 本地安全认证子系统服务 (LSASS) 处理身份验证请求的方式中存在拒绝服务漏洞。攻击者成功利用此漏洞会导致在目标系统的 LSASS 服务上拒绝服务，这将触发系统自动重启。此安全更新程序通过更改 LSASS 处理精心伪装身份验证申请的方式来修复漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>
<p> </p>



利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。按公告 ID（而非 CVE ID）顺序列出了漏洞。公告中仅包含严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
针对你可能需要安装的每个安全更新程序，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据你的特定配置，检查下面的每个评估，从而确定部署本月更新程序的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/zh-cn/security/cc998259)。
  
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
[**MS17-001：Microsoft Edge 累积安全更新 (3214288)**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0002](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0002)

</td>
<td style="border:1px solid black;">
Microsoft Edge 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 更可能被利用

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
[**MS17-002：Microsoft Office 安全更新 (3214291)**](https://go.microsoft.com/fwlink/?linkid=838332)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0003](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0003)

</td>
<td style="border:1px solid black;">
GDI 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 更可能被利用

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
[**MS17-003 Adobe Flash Player 安全更新 (3214628)**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB17-02](http://helpx.adobe.com/cn/security/products/flash-player/apsb17-02.html)

</td>
<td style="border:1px solid black;">
关于漏洞安全性和更新优先级级别的信息，请参阅 Adobe 安全公告 [APSB17-02](http://helpx.adobe.com/cn/security/products/flash-player/apsb17-02.html)。

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
[**MS17-004 本地安全认证子系统服务的安全更新 (3216771)**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0004](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0004)

</td>
<td style="border:1px solid black;">
本地安全认证子系统服务拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
</table>

受影响的软件
------------

<span id="sectionToggle2"></span>
下表按主要软件类别和严重性的排序列出了公告。

通过这些表，您可以了解可能需要安装的安全更新程序。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新程序。如果列出了软件程序或组件，则也会列出软件更新程序的严重等级。

**注意** 你可能必须为单个漏洞安装多个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新程序（基于系统上已安装的程序或组件）。

### Windows 操作系统和组件

<p> </p>

<table style="border:1px solid black;">
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
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista for Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista for Service Pack 2  
(3216775)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3216775)  
（重要）

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
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3216775)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3216775)  
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
(3216775)  
（重要）

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
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 x32 位系统）Service Pack 1  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 x32 位系统）Service Pack 1  
(3212642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
月度汇总更新

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3212646)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 x32 位系统）Service Pack 1  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 x32 位系统）Service Pack 1  
(3212642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
月度汇总更新

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3212646)  
（重要）

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
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack  
(3212642)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3212646)  
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
(3212642)  
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
(3212646)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

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
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
每月汇总补丁

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
Windows 8.1（用于基于 x64 的系统）  
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
每月汇总补丁

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
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

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
Adobe Flash Player  
(3214628)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月汇总补丁

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
仅安全

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月汇总补丁

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
<td style="border:1px solid black;" colspan="4">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月汇总补丁

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3210720)  
（严重）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3210720)  
（严重）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3210721)  
（严重）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3210721)  
（严重）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3211320)  
（严重）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3211320)  
（严重）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3211320)  
（中等）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3216775)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3216775)  
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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack（服务器核心安装）  
(3212642)  
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
(3212646)  
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
每月汇总

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

### Microsoft Office 套件和软件

<p> </p>

<table style="border:1px solid black;">
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
[**MS17-002**](https://go.microsoft.com/fwlink/?linkid=838332)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Word 2016（32 位版本）  
(3128057)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Word 2016（64 位版本）  
(3128057)  
（重要）

</td>
</tr>
</table>

### Microsoft Office Services 和 Web 应用

<p> </p>

<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>Microsoft Office Services 和 Web Apps</strong></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office Services 和 Web Apps</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><strong>公告标识符</strong></p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=838332"><strong>MS17-002</strong></a></p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>综合严重等级</strong></p></td>
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>Microsoft SharePoint Enterprise Server 2016 64 位版本</p></td>
<td style="border:1px solid black;"><p>Microsoft SharePoint Foundation 2016 64 位版本<br />
(3141486)<br />
（重要）</p></td>
</tr>
</tbody>
</table>

检测和部署工具及指导
--------------------

<span id="sectionToggle3"></span>
许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新程序。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](http://technet.microsoft.com/zh-cn/security/cc297183)。 

鸣谢
----

<span id="sectionToggle4"></span>
Microsoft 认可在安全社区中通过可靠的漏洞披露渠道帮助我们保护客户的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/mt745121.aspx)。

其他信息
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外发布的安全公告中不提供 Microsoft Windows 恶意软件删除工具的更新版本。

### MU、WU 和 WSUS 上的与安全无关的更新程序

若要了解 Windows 更新和 Microsoft 更新上的与安全无关的更新程序，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/zh-cn/wsus/bb456965)。显示除 Microsoft Windows 之外的其他 Microsoft 产品的所有新的、修订过的和重新发布的更新程序。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新程序之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件提供商可以使用此类漏洞信息通过其安全软件或设备（如防病毒、基于网络的入侵检测系统或基于主机的入侵防护系统）更新对客户提供的保护。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新程序**

可从以下位置获得针对其他安全问题的更新：

-   可从 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)获取安全更新。通过对“安全更新”进行关键词搜索可以非常方便地找到这些更新。
-   [Microsoft 更新](http://go.microsoft.com/fwlink/?linkid=40747)提供了适用于消费者平台的更新程序。
-   你可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关更多信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案：[TechNet 安全疑难解答和支持](http://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](http://support.microsoft.com/zh-cn/contactus/cu_sc_virsec_master)

基于国家/地区的本地支持：[国际支持](http://support.microsoft.com/zh-cn/common/international.aspx)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定用途的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订

-   V1.0（2017 年 1 月 10 日）：公告摘要已发布。
-   V1.1 (January 10, 2017): Bulletin Summary revised to change the severity of CVE-2017-0003 to Important. This is an informational change only。

*页面生成时间：01.06.2017 14:39-08:00。*
