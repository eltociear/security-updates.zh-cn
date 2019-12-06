---
TOCTitle: 'MS15-AUG'
Title: 'Microsoft 安全公告摘要（2015 年 8 月）'
ms:assetid: 'ms15-aug'
ms:contentKeyID: 68235988
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms15-aug(v=Security.10)'
---



Microsoft 安全公告摘要（2015 年 8 月）
======================================

发布日期： 2015 年 8 月 11 日 | 更新时间： 2015 年 12 月 1 日

**版本：** 3.1

本公告摘要列出了 2015 年 8 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。 请参阅**其他信息**部分。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节?**受影响的软件**?。

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
<td style="border:1px solid black;"><p><strong>重新启动要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>已知<br />
问题</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积安全更新程序 (3082442)</strong> <br />
此安全更新可解决 Internet Explorer 中的漏洞。 最严重的漏洞可能在用户使用 Internet Explorer 查看经特殊设计的网页时允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Graphics 组件中的漏洞可能允许远程执行代码 (3078662)</strong><br />
此安全更新可修复 Microsoft Windows、Microsoft .NET Framework、Microsoft Office、Microsoft Lync 和 Microsoft Silverlight 中的漏洞。 如果用户打开经特殊设计的文档或者访问嵌入了 TrueType 或 OpenType 字体的不受信任网页，则这些漏洞中最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework，<br />  
Microsoft Office、<br />  
Microsoft Lync，<br />
Microsoft Silverlight</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (3080790)<br />
</strong>此安全更新可修复 Microsoft Office 中的漏洞。 最严重的漏洞可能在用户打开经特殊设计的 Microsoft Office 文件时允许远程执行代码。 成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3080790">3080790</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-082">MS15-082</a></p></td>
<td style="border:1px solid black;"><p><strong>RDP 中的漏洞可能允许远程执行代码 (3080348)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者先在目标用户的当前工作目录中放置经特殊设计的动态链接库 (DLL) 文件，然后诱使用户打开远程桌面协议 (RDP) 文件或启动旨在加载受信任的 DLL 文件的程序加载攻击者经特殊设计的 DLL 文件，其中最严重的漏洞可能会允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3080348">3080348</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-083">MS15-083</a></p></td>
<td style="border:1px solid black;"><p><strong>服务器消息块中的漏洞可能允许远程执行代码 (3073921)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者向 SMB 服务器错误记录发送特殊设计的数据包，此漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-084">MS15-084</a></p></td>
<td style="border:1px solid black;"><p><strong>XML Core Services 中的漏洞可能允许信息泄露 (3080129)</strong><br />
此安全更新可修复 Microsoft Windows 和 Microsoft Office 中的漏洞。 如果用户单击经特殊设计的链接公开内存地址或以显式方式允许使用安全套接字层 (SSL) 2.0，则这些漏洞可能导致信息泄露。 但是，在所有情况下，攻击者无法强制用户单击经特殊设计的链接。 攻击者必须说服用户单击此链接，通常方式为通过电子邮件或 Instant Messenger 消息进行诱骗。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3076895">3076895</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Office</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-085">MS15-085</a></p></td>
<td style="border:1px solid black;"><p><strong>Mount Manager 中的漏洞可能允许特权提升 (3082487)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者将恶意 USB 设备插入目标系统，则该漏洞可能会允许特权提升。 然后，攻击者会将恶意二进制文件写入磁盘并执行。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3071756">3071756</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-086">MS15-086</a></p></td>
<td style="border:1px solid black;"><p><strong>System Center Operations Manager 中的漏洞可能允许特权提升 (3075158)</strong><br />
此安全更新可解决 Microsoft System Center Configuration Manager 中的一个漏洞。 如果用户通过特制 URL 访问受影响的网站，则该漏洞可能允许特权提升。 但是，攻击者无法强迫用户访问这样的网站。 相反，攻击者必须诱使用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到受影响的网站。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Server 软件</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-087">MS15-087</a></p></td>
<td style="border:1px solid black;"><p><strong>UDDI Services 中的漏洞可能允许特权提升 (3082459)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者通过将恶意脚本插入网页搜索参数以执行跨站点脚本 (XSS)，则该漏洞可能允许特权提升。 用户必须访问随后会在其中执行恶意脚本的经特殊设计的网页。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Server 软件</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-088">MS15-088</a></p></td>
<td style="border:1px solid black;"><p><strong>不安全的命令行参数传递可能会导致信息泄露 (3082458) </strong><br />
此安全更新还有助于解决 Microsoft Windows、Internet Explorer 和 Microsoft Office 中的信息泄露漏洞。 为了利用此漏洞，攻击者首先必须使用 Internet Explorer 中的另一个漏洞以在沙盒进程中执行代码。 然后，攻击者通过不安全的命令行参数执行 Notepad、Visio、PowerPoint、Excel 或 Word 以引起信息泄露。 为了免受此漏洞影响，客户必须应用此公告中提供的更新，以及 <a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a> 中针对 Internet Explorer 提供的更新。 同样，运行受影响 Microsoft Office 产品的客户必须还要安装 <a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a> 中提供的适用更新。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-089">MS15-089</a></p></td>
<td style="border:1px solid black;"><p><strong>WebDAV 中的漏洞可能导致信息泄露 (3076949)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者通过启用了安全套接字层 (SSL) 2.0 的 WebDAV 服务器强制执行加密的 SSL 2.0 会话并使用中间人 (MiTM) 攻击解密部分加密流量，则该漏洞可能导致信息泄露。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-090">MS15-090</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows 中的漏洞可能允许特权提升 (3060716)</strong> <br />
此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者登录受影响系统并运行经特殊设计的应用程序，或说服用户打开经特殊设计的文件以调用容易受攻击的沙盒应用程序，从而允许攻击者逃离沙盒，则该漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3060716">3060716</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-091">MS15-091</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 的累积安全更新 (3084525)<br />
</strong>此安全更新可修复 Microsoft Edge 中的漏洞。 最严重的漏洞可能在用户使用 Microsoft Edge 查看经特殊设计的网页时允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-092">MS15-092</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 中的漏洞可能允许特权提升 (3086251)<br />
</strong>此安全更新可解决 Microsoft .NET Framework 中的漏洞。 如果用户运行经特殊设计的 .NET 应用程序，则该漏洞可能允许特权提升。 但是，在所有情况下，攻击者无法强迫用户运行应用程序，攻击者必须说服用户执行此类操作。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-093">MS15-093</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的安全更新 (3088903)</strong><br />
此安全更新可解决 Internet Explorer 中的漏洞。 如果用户使用 Internet Explorer 查看经特殊设计的网页，则该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
</tbody>
</table>


利用指数
--------

下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。

**如何使用该表？**

对于您可能需要安装的每个安全更新，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。 根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。

在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新软件版本”是指主题软件，“较旧软件版本”是指主题软件的所有较旧的受支持版本。

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
<td style="border:1px solid black;"><p><strong>漏洞标题</strong></p></td>
<td style="border:1px solid black;"><p><strong>CVE ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估<br />
</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估<br />
</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务<br />
利用评估</strong></p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>不安全的命令行参数传递漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2441">CVE-2015-2441</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2442">CVE-2015-2442</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2443">CVE-2015-2443</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2444">CVE-2015-2444</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>ASLR 绕过</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2445">CVE-2015-2445</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2446">CVE-2015-2446</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2447">CVE-2015-2447</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2448">CVE-2015-2448</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>ASLR 绕过</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2449">CVE-2015-2449</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2450">CVE-2015-2450</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2451">CVE-2015-2451</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-079">MS15-079</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2452">CVE-2015-2452</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 图形组件远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2431">CVE-2015-2431</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>OpenType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2432">CVE-2015-2432</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>内核 ASLR 绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2433">CVE-2015-2433</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>TrueType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2435">CVE-2015-2435</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>Windows CSRSS 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2453">CVE-2015-2453</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>Windows KMD 安全功能绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2454">CVE-2015-2454</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>TrueType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2455">CVE-2015-2455</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>TrueType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2456">CVE-2015-2456</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>OpenType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2458">CVE-2015-2458</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>OpenType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2459">CVE-2015-2459</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>OpenType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2460">CVE-2015-2460</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>OpenType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2461">CVE-2015-2461</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>OpenType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2462">CVE-2015-2462</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>TrueType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2463">CVE-2015-2463</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>TrueType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2464">CVE-2015-2464</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-080">MS15-080</a></p></td>
<td style="border:1px solid black;"><p>Windows Shell 安全功能绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2465">CVE-2015-2465</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1642">CVE-2015-1642</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a></p></td>
<td style="border:1px solid black;"><p>不安全的命令行参数传递漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2466">CVE-2015-2466</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2467">CVE-2015-2467</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2468">CVE-2015-2468</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2469">CVE-2015-2469</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 整数下溢漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2470">CVE-2015-2470</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-081">MS15-081</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2477">CVE-2015-2477</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-082">MS15-082</a></p></td>
<td style="border:1px solid black;"><p>远程桌面会话主机欺骗漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2472">CVE-2015-2472</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-082">MS15-082</a></p></td>
<td style="border:1px solid black;"><p>远程桌面协议 DLL 种植远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2473">CVE-2015-2473</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-083">MS15-083</a></p></td>
<td style="border:1px solid black;"><p>服务器消息块内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2474">CVE-2015-2474</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-084">MS15-084</a></p></td>
<td style="border:1px solid black;"><p>MSXML 信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2434">CVE-2015-2434</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-084">MS15-084</a></p></td>
<td style="border:1px solid black;"><p>MSXML 信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2440">CVE-2015-2440</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-084">MS15-084</a></p></td>
<td style="border:1px solid black;"><p>MSXML 信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2471">CVE-2015-2471</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-085">MS15-085</a></p></td>
<td style="border:1px solid black;"><p>Mount Manager 中的特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1769">CVE-2015-1769</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-086">MS15-086</a></p></td>
<td style="border:1px solid black;"><p>System Center Operations Manager Web 控制台 XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2420">CVE-2015-2420</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-087">MS15-087</a></p></td>
<td style="border:1px solid black;"><p>UDDI 服务特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2475">CVE-2015-2475</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-088">MS15-088</a></p></td>
<td style="border:1px solid black;"><p>不安全的命令行参数传递漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=619309">MS15-089</a></p></td>
<td style="border:1px solid black;"><p>WebDAV 客户端信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2476">CVE-2015-2476</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-090">MS15-090</a></p></td>
<td style="border:1px solid black;"><p>Windows 对象管理器特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2428">CVE-2015-2428</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-090">MS15-090</a></p></td>
<td style="border:1px solid black;"><p>Windows 注册表特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2429">CVE-2015-2429</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-090">MS15-090</a></p></td>
<td style="border:1px solid black;"><p>Windows 文件系统特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2430">CVE-2015-2430</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-091">MS15-091</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2441">CVE-2015-2441</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-091">MS15-091</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2442">CVE-2015-2442</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-091">MS15-091</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2446">CVE-2015-2446</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-091">MS15-091</a></p></td>
<td style="border:1px solid black;"><p>ASLR 绕过</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2449">CVE-2015-2449</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-092">MS15-092</a></p></td>
<td style="border:1px solid black;"><p>RyuJIT 优化特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2479">CVE-2015-2479</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-092">MS15-092</a></p></td>
<td style="border:1px solid black;"><p>RyuJIT 优化特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2480">CVE-2015-2480</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-092">MS15-092</a></p></td>
<td style="border:1px solid black;"><p>RyuJIT 优化特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2481">CVE-2015-2481</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-093">MS15-093</a></p></td>
<td style="border:1px solid black;"><p>内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2502">CVE-2015-2502</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
</tbody>  
</table>
  
受影响的软件  
------------
  
<span id="sectionToggle2"></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
### Windows 操作系统和组件（表 1-3）

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
[**MS15-079**](https://technet.microsoft.com/zh-cn/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/zh-cn/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/zh-cn/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
（严重）  
Internet Explorer 8  
(3078071)  
（严重）  
Internet Explorer 9  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3078601)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
（严重）  
Microsoft .NET Framework 4  
(3072309)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
（严重）  
Microsoft .NET Framework 4.6  
(3072311)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3075220)  
（重要）  
Windows Vista Service Pack 2  
(3075221)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3073921)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
（严重）  
Internet Explorer 8  
(3078071)  
（严重）  
Internet Explorer 9  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3078601)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
（严重）  
Microsoft .NET Framework 4  
(3072309)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
（严重）  
Microsoft .NET Framework 4.6  
(3072311)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3075220)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3075221)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3073921)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[**MS15-079**](https://technet.microsoft.com/zh-cn/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/zh-cn/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/zh-cn/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
（中等）  
Internet Explorer 8  
(3078071)  
（中等）  
Internet Explorer 9  
(3078071)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3078601)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
（严重）  
Microsoft .NET Framework 4  
(3072309)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
（严重）  
Microsoft .NET Framework 4.6  
(3072311)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3073921)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
（中等）  
Internet Explorer 8  
(3078071)  
（中等）  
Internet Explorer 9  
(3078071)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3078601)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
（严重）  
Microsoft .NET Framework 4  
(3072309)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
（严重）  
Microsoft .NET Framework 4.6  
(3072311)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3073921)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3078601)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3073921)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[**MS15-079**](https://technet.microsoft.com/zh-cn/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/zh-cn/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/zh-cn/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
（严重）  
Internet Explorer 9  
(3078071)  
（严重）  
Internet Explorer 10  
(3078071)  
（严重）  
Internet Explorer 11  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3078601)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3072305)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3075220)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3075222)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3075226)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
（严重）  
Internet Explorer 9  
(3078071)  
（严重）  
Internet Explorer 10  
(3078071)  
（严重）  
Internet Explorer 11  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3078601)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3072305)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3075220)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3075222)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3075226)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[**MS15-079**](https://technet.microsoft.com/zh-cn/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/zh-cn/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/zh-cn/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
（中等）  
Internet Explorer 9  
(3078071)  
（中等）  
Internet Explorer 10  
(3078071)  
（中等）  
Internet Explorer 11  
(3078071)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3078601)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3072305)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3075220)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3075222)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3075226)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3078601)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/zh-cn/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/zh-cn/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/zh-cn/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3078601)  
（严重）  
Microsoft .NET Framework 3.5  
(3072306)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3078601)  
（严重）  
Microsoft .NET Framework 3.5  
(3072306)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3078601)  
（严重）  
Microsoft .NET Framework 3.5  
(3072307)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3078601)  
（严重）  
Microsoft .NET Framework 3.5  
(3072307)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[**MS15-079**](https://technet.microsoft.com/zh-cn/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/zh-cn/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/zh-cn/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3078601)  
（严重）  
Microsoft .NET Framework 3.5  
(3072306)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3078601)  
（严重）  
Microsoft .NET Framework 3.5  
(3072307)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/zh-cn/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/zh-cn/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/zh-cn/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(3078601)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3078601)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
[**MS15-079**](https://technet.microsoft.com/zh-cn/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/zh-cn/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/zh-cn/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081436)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3081436)  
（严重）  
Microsoft .NET Framework 3.5  
(3081436)  
（严重）

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
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081436)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3081436)  
（严重）  
Microsoft .NET Framework 3.5  
(3081436)  
（严重）

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
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/zh-cn/library/security/ms15-079)

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/zh-cn/library/security/ms15-082)

</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/zh-cn/library/security/ms15-083)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3078601)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3073921)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
(3078601)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3073921)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
(3078601)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3072305)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
(3078601)  
（严重）  
Microsoft .NET Framework 3.5  
(3072306)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
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
(3078601)  
（严重）  
Microsoft .NET Framework 3.5  
(3072307)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3075220)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 MSXML Core Services 6.0  
(3076895)  
（重要）

</td>
</tr>
</table>

**MS15-080 和 MS15-084 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

### Windows 操作系统和组件（表 2-3）

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
[**MS15-085**](https://technet.microsoft.com/zh-cn/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/zh-cn/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/zh-cn/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/zh-cn/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046017)  
（重要）  
Windows Vista Service Pack 2  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046017)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3060716)  
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
[**MS15-085**](https://technet.microsoft.com/zh-cn/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/zh-cn/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/zh-cn/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/zh-cn/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3073893)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3046017)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3073893)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3046017)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3046017)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3060716)  
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
[**MS15-085**](https://technet.microsoft.com/zh-cn/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/zh-cn/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/zh-cn/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/zh-cn/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3046017)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3046017)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3060716)  
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
[**MS15-085**](https://technet.microsoft.com/zh-cn/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/zh-cn/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/zh-cn/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/zh-cn/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3046017)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3046017)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/zh-cn/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/zh-cn/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/zh-cn/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/zh-cn/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3060716)  
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
[**MS15-085**](https://technet.microsoft.com/zh-cn/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/zh-cn/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/zh-cn/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/zh-cn/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/zh-cn/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/zh-cn/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/zh-cn/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/zh-cn/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3076949)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3060716)  
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
[**MS15-085**](https://technet.microsoft.com/zh-cn/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/zh-cn/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/zh-cn/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/zh-cn/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3081436)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3081436)  
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
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3081436)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3081436)  
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
<td style="border:1px solid black;" colspan="6">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/zh-cn/library/security/ms15-085)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/zh-cn/library/security/ms15-088)

</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/zh-cn/library/security/ms15-089)

</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/zh-cn/library/security/ms15-090)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3073893)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3046017)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3073893)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3046017)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3046017)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3079757)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3060716)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3071756)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3046017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3060716)  
（重要）

</td>
</tr>
</table>

**MS15-087 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

### Windows 操作系统和组件（表 3-3）

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
[**MS15-091**](https://technet.microsoft.com/zh-cn/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/zh-cn/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/zh-cn/library/security/ms15-093)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083186)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
（严重）  
Internet Explorer 8  
(3087985)  
（严重）  
Internet Explorer 9  
(3087985)  
（严重）

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
Microsoft .NET Framework 4.6  
(3083186)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
（严重）  
Internet Explorer 8  
(3087985)  
（严重）  
Internet Explorer 9  
(3087985)  
（严重）

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
[**MS15-091**](https://technet.microsoft.com/zh-cn/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/zh-cn/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/zh-cn/library/security/ms15-093)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083186)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
（中等）  
Internet Explorer 8  
(3087985)  
（中等）  
Internet Explorer 9  
(3087985)  
（中等）

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
Microsoft .NET Framework 4.6  
(3083186)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
（中等）  
Internet Explorer 8  
(3087985)  
（中等）  
Internet Explorer 9  
(3087985)  
（中等）

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
Internet Explorer 7  
(3087985)  
（中等）

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
[**MS15-091**](https://technet.microsoft.com/zh-cn/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/zh-cn/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/zh-cn/library/security/ms15-093)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
（严重）  
Internet Explorer 9  
(3087985)  
（严重）  
Internet Explorer 10  
(3087985)  
（严重）  
Internet Explorer 11  
(3087985)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
（严重）  
Internet Explorer 9  
(3087985)  
（严重）  
Internet Explorer 10  
(3087985)  
（严重）  
Internet Explorer 11  
(3087985)  
（严重）

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
[**MS15-091**](https://technet.microsoft.com/zh-cn/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/zh-cn/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/zh-cn/library/security/ms15-093)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
（中等）  
Internet Explorer 9  
(3087985)  
（中等）  
Internet Explorer 10  
(3087985)  
（中等）  
Internet Explorer 11  
(3087985)  
（中等）

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
Internet Explorer 8  
(3087985)  
（中等）

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
[**MS15-091**](https://technet.microsoft.com/zh-cn/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/zh-cn/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/zh-cn/library/security/ms15-093)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083184)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
（严重）

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
Microsoft .NET Framework 4.6  
(3083184)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
（严重）

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
[**MS15-091**](https://technet.microsoft.com/zh-cn/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/zh-cn/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/zh-cn/library/security/ms15-093)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083184)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
（中等）

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
[**MS15-091**](https://technet.microsoft.com/zh-cn/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/zh-cn/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/zh-cn/library/security/ms15-093)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Microsoft .NET Framework 4.6  
(3083184)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
（严重）

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
[**MS15-091**](https://technet.microsoft.com/zh-cn/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/zh-cn/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/zh-cn/library/security/ms15-093)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081436)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3081436)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081444)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081436)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3081436)  
（重要）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081444)  
（严重）

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
[**MS15-091**](https://technet.microsoft.com/zh-cn/library/security/ms15-091)

</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/zh-cn/library/security/ms15-092)

</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/zh-cn/library/security/ms15-093)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

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
Microsoft .NET Framework 4.6  
(3083186)  
（重要）

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
Microsoft .NET Framework 4.6  
(3083186)  
（重要）

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
Microsoft .NET Framework 4.6  
(3083186)  
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
Microsoft .NET Framework 4.6  
(3083184)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

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
Microsoft .NET Framework 4.6  
(3083185)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft System Center 2012 Operations Manager**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS15-086**](https://technet.microsoft.com/zh-cn/library/security/ms15-086)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager

</td>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager  
（安装更新汇总 8）  
(3071089)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager Service Pack 1

</td>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager Service Pack 1  
（安装更新汇总 10）  
(3071088)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft System Center 2012 Operations Manager R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-086**](https://technet.microsoft.com/zh-cn/library/security/ms15-086)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager R2

</td>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager R2  
（安装更新汇总 7）  
(3064919)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft BizTalk Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-086**](https://technet.microsoft.com/zh-cn/library/security/ms15-086)

</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/zh-cn/library/security/ms15-087)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2010

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2010  
(3087119)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2013

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2013  
(3087119)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2013 R2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2013 R2  
(3087119)  
（重要）

</td>
</tr>
</table>

**MS15-087 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3054890)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2687409)  
（重要）  
Microsoft Office 2007 Service Pack 3  
(3054888)  
（严重）  
Microsoft Office 2007 Service Pack 3  
(2596650)  
（严重）  
Microsoft Office 2007 Service Pack 3  
(2837610)  
（重要）  
Microsoft Excel 2007 Service Pack 3  
(3054992)  
（重要）  
Microsoft PowerPoint 2007 Service Pack 3  
(3055051)  
（重要）  
Microsoft Visio 2007 Service Pack 3  
(2965280)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3055052)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 5.0  
(2825645)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3054846)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2965310)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3055037)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2553313)  
（严重）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2598244)  
（重要）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3055044)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（32 位版本）  
(3055033)  
（重要）  
Microsoft Visio 2010 Service Pack 2（32 位版本）  
(3054876)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3055039)  
（重要）

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
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3054846)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2965310)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3055037)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2553313)  
（严重）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2598244)  
（重要）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3055044)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（64 位版本）  
(3055033)  
（重要）  
Microsoft Visio 2010 Service Pack 2（64 位版本）  
(3054876)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3055039)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3039734)  
（重要）  
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3039798)  
（严重）  
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3054816)  
（重要）  
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(3054991)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（32 位版本）  
(3055029)  
（重要）  
Microsoft Visio 2013 Service Pack 1（32 位版本）  
(3054929)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3055030)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）  
(3039734)  
（重要）  
Microsoft Office 2013 Service Pack 1（64 位版本）  
(3039798)  
（严重）  
Microsoft Office 2013 Service Pack 1（64 位版本）  
(3054816)  
（重要）  
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(3054991)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（64 位版本）  
(3055029)  
（重要）  
Microsoft Visio 2013 Service Pack 1（64 位版本）  
(3054929)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3055030)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3039798)  
（严重）  
Microsoft Office 2013 RT Service Pack 1  
(3054816)  
（重要）  
Microsoft Excel 2013 RT Service Pack 1  
(3054991)  
（重要）  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3055029)  
（重要）  
Microsoft Visio 2013 RT Service Pack 1  
(3054929)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(3055030)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）  
(3085538)  
（严重）  
Microsoft Visio 2016（32 位版本）  
(2920708)  
（重要）  
Microsoft Word 2016（32 位版本）  
(2920691)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）  
(3085538)  
（严重）  
Microsoft Visio 2016（64 位版本）  
(2920708)  
（重要）  
Microsoft Word 2016（64 位版本）  
(2920691)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3081349)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2016

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2016  
(3082420)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/zh-cn/library/security/ms15-084)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2986254)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3055053)  
（重要）  
Microsoft Word Viewer  
(3055054)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
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
Microsoft XML Core Services 5.0  
(2825645)  
（重要）

</td>
</tr>
</table>

**MS15-080、MS15-081 和 MS15-084 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

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
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3054960)  
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
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3054858)  
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
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3054974)  
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
[**MS15-081**](https://technet.microsoft.com/zh-cn/library/security/ms15-081)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3055003)  
（重要）

</td>
</tr>
</table>

**MS15-081 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

### Microsoft 通信平台和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符                 **

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3075591)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）  
(3075593)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）  
(3075593)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级别安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级别安装）  
(3075592)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）  
(3075590)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）  
(Skype for Business)  
(3055014)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）  
(Skype for Business Basic)  
(3055014)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）  
(Skype for Business)  
(3055014)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）  
(Skype for Business Basic)  
(3055014)  
（严重）

</td>
</tr>
</table>

**MS15-080 注释**

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
[**MS15-080**](https://technet.microsoft.com/zh-cn/library/security/ms15-080)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5  
(3080333)  
（严重）  
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3080333)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5  
(3080333)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3080333)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5  
(3080333)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3080333)  
（严重）

</td>
</tr>
</table>

**MS15-080 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。 有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn903755.aspx)部分。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。 带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/zh-cn/lifecycle)。

IT 专业人员安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

根据国家/地区进行本地支持： [国际支持](https://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2015 年 8 月 11 日）： 已发布公告摘要。
-   V2.0（2015 年 8 月 18 日）： 公告摘要经过修订，在八月的安全公告发布中新增了一个带外公告 MS15-093。 该额外公告可解决 Internet Explorer 中的漏洞。 请参阅 MS15-093 了解详细信息。
-   V3.0（2015 年 10 月 13 日）： 对于 MS15-081，修订的公告摘要宣布了可用于 Microsoft Office 2016、Microsoft Visio 2016 和 Microsoft Word 2016 的更新包。运行 Microsoft Office 2016、Microsoft Visio 2016 或 Microsoft Word 2016 的客户应应用所需的更新以免受 MS15-081 中讨论的漏洞攻击。大多数客户均启用了“自动更新”，他们不必采取任何操作，因为更新将自动下载并安装。
-   V3.1（2015 年 12 月 1 日）： 修订了公告摘要，以告知客户对于与 MS15-085 (3071756) 和 MS15-090 (3060716) 相关的更新，已添加到 Microsoft 知识库文章的已知问题文档。 请参阅“执行摘要”表了解超链接。

*页面生成时间：2015-12-01 10:00Z-08:00。*
