---
TOCTitle: 'MS12-JAN'
Title: 'Microsoft 安全公告摘要（2012 年 1 月）'
ms:assetid: 'ms12-jan'
ms:contentKeyID: 61236968
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms12-jan(v=Security.10)'
---



Microsoft 安全公告摘要（2012 年 1 月）
======================================

发布时间: 2012年1月10日 | 更新时间: 2012年1月27日

**版本:** 2.1

本公告摘要列出了 2012 年 1 月发布的安全公告。

对于 2012 年 1 月发布的安全公告，本公告摘要替代 2012 年 1 月 5 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2012 年 1 月 11 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 1 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499498)。此日期之后，此网络广播按需提供。有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://go.microsoft.com/fwlink/?linkid=217214)。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=227487">MS12-004</a></td>
<td style="border:1px solid black;"><strong>Windows Media 中的漏洞可能允许远程执行代码 (2636391)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中两个秘密报告的漏洞。如果用户打开特制的媒体文件，这些漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235999">MS12-001</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许绕过安全功能 (2644615)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。此漏洞可能允许攻击者在软件应用程序中绕过 SafeSEH 安全功能。然后，攻击者可能利用其他漏洞，借助结构化异常处理工具，运行任意代码。只能使用由 Microsoft Visual C++ .NET 2003 编译的软件应用程序才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
安全功能绕过</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229637">MS12-002</a></td>
<td style="border:1px solid black;"><strong>Winodws 对象包装程序中的漏洞可能允许远程执行代码 (2603381)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开与特制可执行文件位于同一网络目录下的含有嵌入的包对象的合法文件，此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235400">MS12-003</a></td>
<td style="border:1px solid black;"><strong>Windows 客户端/服务器运行时子系统中的漏洞可能允许特权提升 (2646524)</strong><br />
<br />  
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。对于 Windows XP、Windows Server 2003、Windows Vista 和 Windows Server 2008 的所有受支持版本，此安全更新的等级为“重要”。Windows 7 和 Windows Server 2008 R2 的所有受支持版本不受此漏洞的影响。<br />  
<br />
如果攻击者登录受影响的系统并运行特制应用程序，此漏洞可能允许特权提升。攻击者随后可完全控制受影响的系统并安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户等。此漏洞只能在配置有中文、日文或韩文系统区域设置的系统上才能被利用。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=230777">MS12-005</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 中的漏洞可能允许远程执行代码 (2584146)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开含有恶意的嵌入式 ClickOnce 应用程序的特制 Microsoft Office 文件，此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232510">MS12-006</a></td>
<td style="border:1px solid black;"><strong>SSL/TLS 中的漏洞可能允许信息泄露 (2643584)</strong><br />
<br />
此安全更新可解决 SSL 3.0 和 TLS 1.0 中公开披露的漏洞。此漏洞影响协议本身，并不特定于 Windows 操作系统。如果攻击者截取受影响的系统中经过加密的 Web 通信，则该漏洞可能会允许信息泄露。TLS 1.1、TLS 1.2 和不使用 CBC 模式的所有密码套件不受影响。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=227561">MS12-007</a></td>
<td style="border:1px solid black;"><strong>AntiXSS</strong> <strong>库中的漏洞可能允许信息泄露 (2607664)</strong><br />
<br />
此安全更新可解决 Microsoft 防跨站点脚本 (AntiXSS) 库中一个秘密报告的漏洞。如果攻击者利用 AntiXSS 库 的清理功能向某一网站传递恶意脚本，该漏洞可能允许信息泄露。披露该信息的后果取决于信息本身的性质。请注意，攻击者无法利用此漏洞来执行代码或直接提升他们的用户权限，但可用于生成将试图进一步危及受影响系统安全的信息。只有使用 AntiXSS 库的清理模块的站点才会受此漏洞影响。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft 开发工具和软件</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/security/cc998259.aspx)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
| 公告 ID                                                   | 漏洞标题                         | CVE ID                                                                           | 最新软件版本的利用评估                                                                        | 较旧软件版本的利用评估                                                                        | 拒绝服务利用评估 | 重要注意事项                                       |  
|-----------------------------------------------------------|----------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|------------------|----------------------------------------------------|  
| [MS12-001](http://go.microsoft.com/fwlink/?linkid=235999) | Windows 内核 SafeSEH 绕过漏洞    | [CVE-2012-0001](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0001) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | 这是一个安全绕过漏洞。                             |  
| [MS12-002](http://go.microsoft.com/fwlink/?linkid=229637) | 对象包装程序不安全可执行启动漏洞 | [CVE-2012-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0009) | 不受影响                                                                                      | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                             |  
| [MS12-003](http://go.microsoft.com/fwlink/?linkid=235400) | CSRSS 特权提升漏洞               | [CVE-2012-0005](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0005) | 不受影响                                                                                      | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 永久             | （无）                                             |  
| [MS12-004](http://go.microsoft.com/fwlink/?linkid=227487) | MIDI 远程执行代码漏洞            | [CVE-2012-0003](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0003) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                             |  
| [MS12-004](http://go.microsoft.com/fwlink/?linkid=227487) | DirectShow 远程执行代码漏洞      | [CVE-2012-0004](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0004) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                             |  
| [MS12-005](http://go.microsoft.com/fwlink/?linkid=230777) | 程序集执行漏洞                   | [CVE-2012-0013](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0013) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                             |  
| [MS12-006](http://go.microsoft.com/fwlink/?linkid=232510) | SSL 和 TLS 协议漏洞              | [CVE-2011-3389](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3389) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 不适用           | 这是一个信息泄露漏洞，已公开泄露了有限的详细信息。 |  
| [MS12-007](http://go.microsoft.com/fwlink/?linkid=227561) | AntiXSS 库绕过漏洞               | [CVE-2012-0007](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0007) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 不适用           | 这是一个信息泄露漏洞。                             |
  
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
[**MS12-004**](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[**MS12-001**](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[**MS12-002**](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[**MS12-003**](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[**MS12-005**](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[**MS12-006**](http://go.microsoft.com/fwlink/?linkid=232510)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=a142f7ba-4268-4453-a8eb-470213c028ac)  
(KB2598479)  
（严重）  
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=89b23d72-410f-4133-9c14-24eb01e5a732)  
(KB2628259)  
（仅限 Windows XP Media Center Edition 2005 Service Pack 3）  
（严重）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=4b168ee8-eb15-4c2c-afb0-e63d62b4a6dc)  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=feaeda8c-84ee-47be-8c68-736f0e5b1fc7)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=cfc38dc2-c4c7-4a44-8e5a-b98bb9bc0396)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=1bcb1d1e-9261-4a36-9256-90d3df9bd4fb)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=fb0360b1-254c-4ecb-a36a-807cabfec1ab)  
(KB2585542)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=0928d720-ae88-40d6-b76f-636d67da8526)  
(KB2598479)  
（严重）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=13d74cc6-8d8e-45ea-8cdc-c15782f6626b)  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=46386269-6e37-4710-bfef-cedfe60d881c)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=211827f2-fe6a-4e16-a90c-0cc3b60a722d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3956db98-88d9-49fc-be51-247b40bfc272)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2c687796-4c41-4d17-b738-511d2fbfc126)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=afe6b34d-21b1-4dfa-afa6-2c5c2a678e9e)  
(KB2585542)  
（重要）  
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=986f1156-0190-48c2-9f39-29cacb91f0f9)  
(KB2638806)  
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
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS12-004**](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[**MS12-001**](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[**MS12-002**](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[**MS12-003**](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[**MS12-005**](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[**MS12-006**](http://go.microsoft.com/fwlink/?linkid=232510)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
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
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=3c266dfb-630d-4f32-b2ca-63955279b6a9)  
(KB2598479)  
（严重）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=89ae6ed0-537f-421c-b755-ef28691abd88)  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9cdfc0fe-8f43-4e13-8a1f-2b48ff9ff472)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8e46267-7988-4fbe-ae94-68b6fdb2e7d9)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=39f5f8fb-ee4d-4b7a-9cd7-3d1e9c8abd8c)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2c39be84-1eab-4794-b3ed-e529643aca21)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e2c503a5-3f15-4a77-9a05-9ea0fbaf4503)  
(KB2585542)  
（重要）  
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c23e7604-d489-4836-8b54-3b2b3d6a365c)  
(KB2638806)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=8dd1c882-4ed1-4e47-a017-7d162bd94194)  
(KB2598479)  
（严重）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=08be569c-e9d1-4fc5-8670-ebe9da0a2072)  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4e5783aa-6847-404c-9b75-621fa14ebbb8)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5975b01e-139b-4b9d-a0d5-a87a279bfea1)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e27d85f8-a285-4e95-85a0-0868286cc2b9)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3cf29dfd-239e-4707-92e6-952133c1c1c2)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2ad34496-40af-40cb-9f85-5d3c31543211)  
(KB2585542)  
（重要）  
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f36e991-4e1a-4b8c-8cfb-e7f20d97cf0b)  
(KB2638806)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=3a9b09d6-7060-47ab-9f76-c3c5acb024e6)  
(KB2598479)  
（严重）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=3401ac20-3701-471f-9757-097a9402d761)  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=cdf8208c-d55b-428f-bdd3-26e291dfb08d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=26079c35-4b96-42fc-ad47-138be25a6bf0)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b69bd01d-9925-4ff1-bfeb-b4473631578c)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=623c1c7d-6902-4876-9614-1b6e1ef80831)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=56deb935-9226-49f8-b705-edb3d662d8aa)  
(KB2585542)  
（重要）  
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=2d72cf5a-cca7-4341-b862-017e3f34a3c9)  
(KB2638806)  
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
[**MS12-004**](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[**MS12-001**](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[**MS12-002**](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[**MS12-003**](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[**MS12-005**](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[**MS12-006**](http://go.microsoft.com/fwlink/?linkid=232510)
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
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=99d9b9fc-ed37-4a32-a20d-6604a1b9c4ca)  
(KB2598479)  
（严重）  
[Windows Vista 的 Windows Media Center TV Pack（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=f345e093-336d-4464-b7f8-a14398b62ebf)<sup>[1]</sup>  
(KB2628642)  
（重要）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=4818059a-52ad-4c2e-9605-4e0f5d9da5ba)  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=44eeb0a2-ae17-4971-8a7e-e25b260c582c)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=73682d4b-3179-4488-8ba9-94ed68c4896b)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=038970b6-aeec-4e18-8dfe-887b260a7c87)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f9269bd6-8c4f-476e-8481-fc0de52a22e6)  
(KB2585542)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=44aa8d91-2b30-4191-8965-8aee2b860d50)  
(KB2598479)  
（严重）  
[Windows Vista 的 Windows Media Center TV Pack（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=559d028f-9810-4c50-b65d-f567cbb15427)<sup>[1]</sup>  
(KB2628642)  
（重要）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=13cc2519-860d-4c64-b7f8-8f9c0bdaefcf)  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=79ceba86-59a1-4138-a5de-8df20ad81b02)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b5c33025-13d9-43d2-a415-a8a4d683a821)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=23abeb12-f2fe-43fd-9c4a-4d3d244832f8)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0403c753-d4fa-4e3d-a61b-7f816f5c352b)  
(KB2585542)  
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
[**MS12-004**](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[**MS12-001**](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[**MS12-002**](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[**MS12-003**](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[**MS12-005**](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[**MS12-006**](http://go.microsoft.com/fwlink/?linkid=232510)
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
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=787e6285-3ba5-4aae-9d8d-e3c1eca3b35d)\*  
(KB2598479)  
（严重）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=92df13c1-fdf6-4602-acb2-e634a1bcd9da)\*\*  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5ab87c6c-5802-4454-bce4-12501e5b816d)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fbf119cf-a8ed-4266-a673-442149992f7c)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d089d9cb-382c-4e64-94c5-69b9864010b1)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2fe2f398-433f-4338-a273-813185b43ea8)\*  
(KB2585542)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=9eff12b2-70a4-452b-b6bc-0d83f2edcf6c)\*  
(KB2598479)  
（严重）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=7ff10d7f-26a6-403a-a4b7-7aff55e2fa16)\*\*  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=726ff17e-ac90-4832-91e7-46f71ad2f868)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e8e68f89-27f4-4142-94ca-58f086a98157)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1ac8a368-4298-4c1d-9cfd-924d6df563af)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f54ac30d-8e41-4df9-bd43-db6742a24d4c)\*  
(KB2585542)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows 多媒体库](https://www.microsoft.com/download/details.aspx?familyid=4e2edb23-7f4e-4fe4-848c-1d744e0dce9f)  
(KB2598479)  
（严重）  
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=5e0394c9-3de4-46f6-ae7f-18d5a555532e)  
(KB2631813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ba2c3d57-1bdd-44f2-9233-86c7ea6f0ddb)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fc6491e8-6c3e-43a1-bc56-16c9a2fd2749)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3e08b242-2516-4cf6-b38e-35ec2b8b788d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3979db3b-4961-4df8-84a4-1f26672b127c)  
(KB2585542)  
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
[**MS12-004**](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[**MS12-001**](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[**MS12-002**](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[**MS12-003**](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[**MS12-005**](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[**MS12-006**](http://go.microsoft.com/fwlink/?linkid=232510)
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
<td style="border:1px solid black;">
无
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
Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=d736daf8-db6d-485f-b0cb-7f2d8c86f9a2)  
(KB2631813)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0ee22036-b7f4-40f5-8f40-a77e8faf48b2)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7422605b-7a02-4161-b7f8-92b3ccffef64)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0f433f2c-c61d-461d-af9c-0145af4b72ab)  
(KB2585542)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=21b37775-3e7b-462d-8234-7c47d52daef9)  
(KB2631813)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7444e20c-9821-4c91-9779-2728c537dd6a)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=4ba46bc7-af7a-445a-84f2-b0c13674409b)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0839fec0-b6a7-4e47-9da3-2caef44a7df4)  
(KB2585542)  
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
[**MS12-004**](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[**MS12-001**](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[**MS12-002**](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[**MS12-003**](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[**MS12-005**](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[**MS12-006**](http://go.microsoft.com/fwlink/?linkid=232510)
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
<td style="border:1px solid black;">
无
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
Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=355c980d-ec2e-4b2d-a7d4-2e3dbd3a0dde)\*\*  
(KB2631813)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=4c73a16d-e9fa-48de-9dca-a6360ce3d029)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=db3a4814-a409-4def-944d-4eaa540b83b0)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=34542a5a-88df-4a07-b1ed-d4c845502cd8)\*  
(KB2585542)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](https://www.microsoft.com/download/details.aspx?familyid=d4b2389e-fd9f-47c7-9afd-4077f5632c21)  
(KB2631813)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1cc14ee8-f035-4bfc-bf38-33c6b9a2e776)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2101663a-ed3d-4850-b79a-16960ab56b45)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=fe661936-06e1-45d3-89f6-1093504496a7)  
(KB2585542)  
（重要）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。**此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS12-004 的注释**

<sup>[1]</sup>Windows Vista 的 Windows Media Center TV Pack 作为可选组件，仅在 Windows Vista 的 Home Premium 和 Ultimate 版本的原始设备制造商 (OEM) 安装中可用。安装了此可选组件的客户应安装其 Windows Vista 版本适用的所有更新。为保持最佳做法，Microsoft 建议首先安装操作系统更新 (KB2598479 和 KB2631813)，然后再安装 Windows Media Center TV Pack 更新 (KB2628642)。

#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft 防跨站点脚本库
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-007**](http://go.microsoft.com/fwlink/?linkid=227561)
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
Microsoft 防跨站点脚本库 V3.x 和 Microsoft 防跨站点脚本库 V4.0
</td>
<td style="border:1px solid black;">
[Microsoft 防跨站点脚本库 V3.x 和 Microsoft 防跨站点脚本库 V4.0](https://www.microsoft.com/download/details.aspx?familyid=b3ef05ce-70fe-4f25-9aee-cb7a42a53d11)<sup>[1]</sup><sup>[2]</sup>
</td>
</tr>
</table>

**MS12-007 的注释**

<sup>[1]</sup>此下载将把 Microsoft 防跨站点脚本 (AntiXSS) 库升级到一个更新的、不受漏洞影响的版本。

<sup>[2]</sup>此更新只能从 Microsoft 下载中心下载。

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

-   [Accuvant LABS](http://www.accuvant.com/) 的 Joshua J. Drake 报告了 MS12-001 中描述的问题
-   Parvez Anwar 与 [Secunia Research](http://secunia.com/) 合作报告了 MS12-002 中描述的问题
-   [Shenzhen Jowto Research Dep](http://www.jowto.com) 的 Kang Wu 报告了 MS12-003 中描述的问题
-   [IBM Security System's X-Force Research](http://xforce.iss.net/) 的 Shane Garrett 报告了 MS12-004 中描述的问题
-   [Google Inc.](http://www.google.com/) 的 Neel Mehta 报告了 MS12-004 中描述的问题
-   Yorick Koster 与 [Beyond Security's SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) 计划团队合作报告了 MS12-005 中描述的问题
-   [IBM Rational Application Security](http://blog.watchfire.com/) 的 Adi Cohen 报告了 MS12-007 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY (1-866-727-2338) 获得技术支持。与安全更新有关的电话支持服务是免费的。有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。与安全更新有关的支持服务不收取任何费用。有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2012 年 1 月 10 日）： 已发布公告摘要。
-   V2.0（2012 年 1 月 11 日）： 对于 MS12-003，更正了 CVE-2012-0005 的“**利用指数**”中最新软件版本的利用评估。对于 MS12-007，进行了修订以宣布重新发布了公告。有关详细信息，请参阅 MS12-007 公告。
-   V2.1（2012 年 1 月 27 日）： 对于 MS12-004，针对 Windows XP、Windows Server 2003、Windows Vista 和 Windows Server 2008 的所有受支持版本更正了 KB2631813 更新程序包的综合严重等级。有关详细信息，请参阅 MS12-004 公告。

*Built at 2014-04-18T01:50:00Z-07:00*
