---
TOCTitle: 'MS11-NOV'
Title: 'Microsoft 安全公告摘要（2011 年 11 月）'
ms:assetid: 'ms11-nov'
ms:contentKeyID: 61236960
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms11-nov(v=Security.10)'
---



Microsoft 安全公告摘要（2011 年 11 月）
=======================================

发布时间: 2011年11月8日

**版本:** 1.0

本公告摘要列出了 2011 年 11 月发布的安全公告。

对于 2011 年 11 月发布的安全公告，本公告摘要替代 2011 年 11 月 3 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2011 年 11 月 9 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 11 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487958)。此日期之后，此网络广播按需提供。有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://go.microsoft.com/fwlink/?linkid=217214)。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229071">MS11-083</a></td>
<td style="border:1px solid black;"><strong>TCP/IP 中的漏洞可能允许远程执行代码 (2588516)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者向目标系统上的封闭端口发送特制 UDP 数据包的持续流，则此漏洞可能允许远程执行代码。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229638">MS11-085</a></td>
<td style="border:1px solid black;"><strong>Windows Mail 和 Windows 会议室中的漏洞可能允许远程执行代码 (2620704)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开与特制动态链接库 (DLL) 文件位于同一网络目录下的合法文件（例如 .eml 或 .wcinv 文件），此漏洞可能允许远程执行代码。然后，当打开该合法文件时，Windows Mail 或 Windows 会议室可能会尝试加载该 DLL 文件，并执行它所包含的任何代码。要成功进行攻击，用户必须访问不受信任的远程文件系统位置或 WebDAV 共享，并从该位置打开合法文件（例如 .eml 或 .wcinv 文件），然后由容易受攻击的应用程序加载此文档。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229253">MS11-086</a></td>
<td style="border:1px solid black;"><strong>Active Directory 中的漏洞可能允许特权提升 (2630837)</strong><br />
<br />
此安全更新解决 Active Directory、Active Directory 应用程序模式 (ADAM) 和 Active Directory 轻型目录服务 (AD LDS) 中一个秘密报告的漏洞。如果 Active Directory 配置为使用 LDAP over SSL (LDAPS)，则该漏洞可能允许特权提升；攻击者将获取与有效的域帐户相关联的已吊销证书，然后使用该证书向 Active Directory 域执行身份验证。默认情况下，Active Directory 未配置为使用 LDAP over SSL。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229245">MS11-084</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许拒绝服务 (2617657)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。如果用户作为电子邮件附件打开特制的 TrueType 字体文件或者导航到包含特制 TrueType 字体文件的网络共享或 WebDAV 位置，则该漏洞可能允许拒绝服务。要成功进行远程攻击，用户必须访问包含特制 TrueType 字体文件的不受信任的远程文件系统位置或 WebDAV 共享，或者作为电子邮件附件打开该文件。但是在所有情况下，攻击者无法强制用户执行这些操作。相反，攻击者必须说服用户这样做，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">中等</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**我如何使用该表呢？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/security/cc998259.aspx)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
| 公告 ID                                                   | 漏洞标题                      | CVE ID                                                                           | 最新软件版本的代码执行利用评估                                                          | 较旧软件版本的代码执行利用评估                                                          | 拒绝服务利用评估 | 重要注意事项 |  
|-----------------------------------------------------------|-------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|------------------|--------------|  
| [MS11-083](http://go.microsoft.com/fwlink/?linkid=229071) | 引用计数器溢出漏洞            | [CVE-2011-2013](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2013) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码可能不一致 | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码可能不一致 | 永久             | （无）       |  
| [MS11-085](http://go.microsoft.com/fwlink/?linkid=229638) | Windows Mail 不安全库加载漏洞 | [CVE-2011-2016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2016) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码 | 不适用           | （无）       |  
| [MS11-086](http://go.microsoft.com/fwlink/?linkid=229253) | LDAPS 身份验证绕过漏洞        | [CVE-2011-2014](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2014) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码 | 不适用           | （无）       |
  
受影响的软件和下载位置  
----------------------
  
  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">  
<tr class="thead">  
<th>  
</th>  
<th>  
</th>  
<th>  
</th>  
<th>  
</th>  
<th>  
</th>  
</tr>  
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
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
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
无
</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=8c7c21c5-677d-4a5d-8f2b-8ca7691b6b00)  
(KB2616310)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=989cca2d-cce1-4f52-b50e-43152693f240)  
(KB2616310)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
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
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
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
无
</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=08b27ce7-c32e-41e4-ad04-481c5eab17a7)  
(KB2601626)  
（重要）  
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=f116824e-ea48-422d-b284-c9ffa7604bf5)  
(KB2616310)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=de5a74f2-2cc8-4677-b495-3a40fe3d6b9e)  
(KB2601626)  
（重要）  
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=1af1b734-62c7-4e08-91c8-90b6d026da84)  
(KB2616310)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=6168bc67-3d59-450f-bd8a-02d61dabe16b)  
(KB2601626)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
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
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
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
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fc3fe87c-2493-431d-a904-dec9310f6042)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e08266d8-fffa-40bf-b8f6-10a65ee27524)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=2bd602cf-ae0d-4790-a5d0-6133fd7d01a0)  
(KB2601626)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=042c1a8f-834d-4eed-8a59-9e030ccc6d39)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4f2365ed-d50e-44d9-b859-1ec54d3b4d38)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=783521ad-5c50-4194-a582-4e5a1c9999e7)  
(KB2601626)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
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
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
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
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=79382bf2-d2cb-42ea-92dc-64f949353521)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f82dc413-668c-4ca8-a8c8-db74f05346bc)\*\*  
（中等）
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory 和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=b5688923-3914-4f6c-8bc9-036fb4870cc6)\*  
(KB2601626)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=71ff3a89-d7ad-4dda-9e59-fab54b21bd5d)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=06ad5637-56a1-4478-aaa0-063e877503c9)\*\*  
（中等）
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory 和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=51f47181-08f6-4de1-80e5-253355675965)\*  
(KB2601626)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b1c0cb05-c284-49b1-ae4f-92813fdf520f)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2de5de74-e643-4045-9c22-ff95b0dbcafc)  
（中等）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
不适用
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
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
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
[**低**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=4ddb4c2a-bada-49b0-ad78-e07e7e11ced7)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2307fa93-8e45-4841-a5a9-7e89960712f9)  
（低）
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=b06f9f55-e3b2-4705-83d0-1b9f5de9d378)  
(KB2601626)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=156c1bd9-55bc-482c-874b-61998d1ef153)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=05eef5d7-acf6-46e4-abfc-dc83f0a7cae5)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=62603d18-1b21-400c-8eba-202193182960)  
（低）
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=790f1d99-96a5-438d-b433-895b692912ce)  
(KB2601626)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5c7db930-5495-43f0-928c-d586ac9e80d0)  
（中等）
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
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
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
[**低**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3f9f74a6-e984-4aab-837c-ef7286e7305f)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c9cf6a22-f9ab-427a-9b16-33c60baaabb5)\*\*  
（低）
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory 和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=cc1e99af-fc67-400b-a82c-171f8c4d1ac9)\*  
(KB2601626)  
（重要）
</td>
<td style="border:1px solid black;" colspan="2">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5d810dae-5c52-4155-b5c2-163d27be6e78)\*\*\*  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b20bfcbd-a515-4074-b56e-b82539fe5bad)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=012777f5-51f2-4944-91af-a9c79b8081a1)  
（低）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=395819e2-1028-44b7-ace4-ca754b1a7543)  
（中等）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。**此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装，即使系统上可能存在此漏洞影响的文件，此更新解决的漏洞也不会影响 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本。但是，仍将向具有受影响文件的用户提供此更新，因更新文件比您的系统上的当前文件更新（版本号较高）。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

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

**System Center Configuration Manager 2007**

Configuration Manager 2007 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 Configuration Manager 2007，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

Configuration Manager 2007 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。Configuration Manager 2007 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关管理员如何使用 Configuration Manager 2007 部署更新的详细信息，请参阅[软件更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)。有关 Configuration Manager 的详细信息，请访问 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。SMS 的下一版本 System Center Configuration Manager 2007 现已可用；请参阅前面的部分 **System Center Configuration Manager 2007**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

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

-   [CERT/CC](http://www.cert.org/) 的 Will Dorman 报告了 MS11-084 中描述的一个问题
-   EvilCode 的 Ivan Sanchez 报告了 MS11-085 中描述的一个问题
-   Autosécurité 的 Xavier Lassoie 和 Sébastien Godard 报告了 MS11-086 中描述的一个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY (1-866-727-2338) 获得技术支持。与安全更新有关的电话支持服务是免费的。有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。与安全更新有关的支持服务不收取任何费用。有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2011 年 11 月 8 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
