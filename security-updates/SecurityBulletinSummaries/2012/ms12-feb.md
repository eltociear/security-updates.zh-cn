---
TOCTitle: 'MS12-FEB'
Title: 'Microsoft 安全公告摘要（2012 年 2 月）'
ms:assetid: 'ms12-feb'
ms:contentKeyID: 61236967
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms12-feb(v=Security.10)'
---



Microsoft 安全公告摘要（2012 年 2 月）
======================================

发布时间: 2012年2月14日

**版本:** 1.0

本公告摘要列出了 2012 年 2 月发布的安全公告。

对于 2012 年 2 月发布的安全公告，本公告摘要替代 2012 年 2 月 9 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2012 年 2 月 15 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 2 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499501)。此日期之后，此网络广播按需提供。有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://go.microsoft.com/fwlink/?linkid=217214)。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=238387">MS12-008</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许远程执行代码 (2660465)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞和一个公开披露的漏洞。如果用户访问包含特制内容的网站或者本地运行特制的应用程序，则其中较严重的漏洞可能允许远程执行代码。攻击者无法强迫用户访问恶意网站。相反，攻击者必须诱使用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=236989">MS12-010</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2647516)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中的四个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与登录用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=238617">MS12-013</a></td>
<td style="border:1px solid black;"><strong>C 运行时库中的漏洞可能允许远程执行代码 (2654428)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开宿主在网站上或作为电子邮件附件发送的特制媒体文件，此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=235370">MS12-016</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 和 Microsoft Silverlight 中的漏洞可能允许远程执行代码 (2651026)</strong><br />
<br />
此安全更新可解决 Microsoft .NET Framework 和 Microsoft Silverlight 中一个公开披露的漏洞和一个秘密报告的漏洞。如果用户使用可运行 XAML 浏览器应用程序 (XBAP) 或 Silverlight 应用程序的 Web 浏览器查看特制网页，则这些漏洞可能允许在客户端系统上远程执行代码。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft .NET Framework，<br />
Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=238474">MS12-009</a></td>
<td style="border:1px solid black;"><strong>辅助功能驱动程序中的漏洞可能允许特权提升 (2645640)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中两个秘密报告的漏洞。如果攻击者登录用户的系统，并运行特制应用程序，则此漏洞可能允许提升特权。攻击者必须拥有有效的登录凭据并能本地登录才能利用漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=238500">MS12-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint 中的漏洞可能允许特权提升 (2663841)</strong><br />
<br />
此安全更新可解决 Microsoft SharePoint 和 Microsoft SharePoint Foundation 中三个秘密报告的漏洞。如果用户单击特制的 URL，这些漏洞可能允许特权提升或信息泄露。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft 服务器软件</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=239941">MS12-012</a></td>
<td style="border:1px solid black;"><strong>颜色控制面板中的漏洞可能允许远程执行代码 (2643719)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。如果用户打开与特制动态链接库 (DLL) 文件位于同一目录下的合法文件（例如 .icm 或 .icc 文件），此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=239945">MS12-014</a></td>
<td style="border:1px solid black;"><strong>Indeo 编解码器中的漏洞可能允许远程执行代码 (2661637)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。如果用户打开与特制动态链接库 (DLL) 文件位于同一目录下的合法文件（例如 .avi 文件），此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可能以登录用户的身份运行任意代码。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。如果用户使用管理用户权限登录，攻击者便可完全控制受影响的系统。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=238400">MS12-015</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio Viewer 2010 中的漏洞可能允许远程执行代码 (2663510)</strong><br />
<br />
此安全更新可解决 Microsoft Office 中五个秘密报告的漏洞。如果用户打开特制的 Visio 文件，这些漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与登录用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/security/cc998259.aspx)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
| 公告 ID                                                   | 漏洞标题                           | CVE ID                                                                           | 最新软件版本的利用评估                                                                        | 较旧软件版本的利用评估                                                                        | 拒绝服务利用评估 | 重要注意事项                                                                                      |  
|-----------------------------------------------------------|------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|------------------|---------------------------------------------------------------------------------------------------|  
| [MS12-008](https://go.microsoft.com/fwlink/?linkid=238387) | 键盘布局释放后使用漏洞             | [CVE-2012-0154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0154) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                            |  
| [MS12-008](https://go.microsoft.com/fwlink/?linkid=238387) | GDI 访问冲突漏洞                   | [CVE-2011-5046](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-5046) | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建       | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建       | 永久             | 此漏洞已公开披露。                                                                                |  
| [MS12-009](https://go.microsoft.com/fwlink/?linkid=238474) | AfdPoll 特权提升漏洞               | [CVE-2012-0148](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0148) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 永久             | x64 会被利用，x86 不会。                                                                          |  
| [MS12-009](https://go.microsoft.com/fwlink/?linkid=238474) | 辅助功能驱动程序特权提升漏洞       | [CVE-2012-0149](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0149) | 不受影响                                                                                      | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 永久             | 只有 Windows Server 2003 受影响。                                                                 |  
| [MS12-010](https://go.microsoft.com/fwlink/?linkid=236989) | HTML 布局远程执行代码漏洞          | [CVE-2012-0011](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0011) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 临时             | （无）                                                                                            |  
| [MS12-010](https://go.microsoft.com/fwlink/?linkid=236989) | 空字节信息泄露漏洞                 | [CVE-2012-0012](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0012) | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 不受影响                                                                                      | 不适用           | 这是一个信息泄露漏洞。                                                                            |  
| [MS12-010](https://go.microsoft.com/fwlink/?linkid=236989) | VML 远程执行代码漏洞               | [CVE-2012-0155](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0155) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不受影响                                                                                      | 临时             | （无）                                                                                            |  
| [MS12-011](https://go.microsoft.com/fwlink/?linkid=238500) | inplview.aspx 中的 XSS 漏洞        | [CVE-2012-0017](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0017) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不受影响                                                                                      | 不适用           | （无）                                                                                            |  
| [MS12-011](https://go.microsoft.com/fwlink/?linkid=238500) | themeweb.aspx 中的 XSS 漏洞        | [CVE-2012-0144](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0144) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不受影响                                                                                      | 不适用           | （无）                                                                                            |  
| [MS12-011](https://go.microsoft.com/fwlink/?linkid=238500) | wizardlist.aspx 中的 XSS 漏洞      | [CVE-2012-0145](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0145) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不受影响                                                                                      | 不适用           | （无）                                                                                            |  
| [MS12-012](https://go.microsoft.com/fwlink/?linkid=239941) | 颜色控制面板库加载不安全漏洞       | [CVE-2010-5082](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-5082) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | 此漏洞已公开披露。                                                                                |  
| [MS12-013](https://go.microsoft.com/fwlink/?linkid=238617) | Msvcrt.dll 缓冲区溢出漏洞          | [CVE-2012-0150](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0150) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 临时             | （无）                                                                                            |  
| [MS12-014](https://go.microsoft.com/fwlink/?linkid=239945) | Indeo 音频编解码器库加载不安全漏洞 | [CVE-2010-3138](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3138) | 不受影响                                                                                      | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | 此漏洞已公开披露。                                                                                |  
| [MS12-015](https://go.microsoft.com/fwlink/?linkid=238400) | VSD 文件格式内存损坏漏洞           | [CVE-2012-0019](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0019) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不受影响                                                                                      | 不适用           | 这会影响 Visio Viewer 2010 和 Visio Viewer 2010 Service Pack 1（Visio Viewer 唯一受支持的版本）。 |  
| [MS12-015](https://go.microsoft.com/fwlink/?linkid=238400) | VSD 文件格式内存损坏漏洞           | [CVE-2012-0020](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0020) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不受影响                                                                                      | 不适用           | 这会影响 Visio Viewer 2010 和 Visio Viewer 2010 Service Pack 1（Visio Viewer 唯一受支持的版本）。 |  
| [MS12-015](https://go.microsoft.com/fwlink/?linkid=238400) | VSD 文件格式内存损坏漏洞           | [CVE-2012-0136](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0136) | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 不受影响                                                                                      | 不适用           | 这会影响 Visio Viewer 2010 和 Visio Viewer 2010 Service Pack 1（Visio Viewer 唯一受支持的版本）。 |  
| [MS12-015](https://go.microsoft.com/fwlink/?linkid=238400) | VSD 文件格式内存损坏漏洞           | [CVE-2012-0137](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0137) | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 不受影响                                                                                      | 不适用           | 这会影响 Visio Viewer 2010 和 Visio Viewer 2010 Service Pack 1（Visio Viewer 唯一受支持的版本）。 |  
| [MS12-015](https://go.microsoft.com/fwlink/?linkid=238400) | VSD 文件格式内存损坏漏洞           | [CVE-2012-0138](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0138) | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 不受影响                                                                                      | 不适用           | 这会影响 Visio Viewer 2010 和 Visio Viewer 2010 Service Pack 1（Visio Viewer 唯一受支持的版本）。 |  
| [MS12-016](https://go.microsoft.com/fwlink/?linkid=235370) | .NET Framework 不受管理的对象漏洞  | [CVE-2012-0014](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0014) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                            |  
| [MS12-016](https://go.microsoft.com/fwlink/?linkid=235370) | .NET Framework 堆损坏漏洞          | [CVE-2012-0015](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0015) | 不受影响                                                                                      | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | 此漏洞已公开披露。                                                                                |
  
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
[**MS12-008**](https://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[**MS12-010**](https://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[**MS12-013**](https://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[**MS12-016**](https://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[**MS12-009**](https://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[**MS12-012**](https://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[**MS12-014**](https://go.microsoft.com/fwlink/?linkid=239945)
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
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=832afe5e-d61e-4554-b889-9174df042b32)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=a7d59fa8-0a49-4985-9f14-92218d3b5cea)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6025c5d6-696c-49cd-9264-96af5766d318)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5b37f5b1-207f-4fa1-9769-c873d672e80c)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=32e5c9ad-b610-4afb-b6f0-bb0b5fbdd1f6)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ff2c141c-08b4-42c6-9f66-580f8678c01f)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=96d404e7-8928-494e-8a3c-3897817cda7b)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b40bc334-edbc-48d5-9196-b7fb0e19966e)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2fc9d519-94b3-4b56-92fd-4c0ccf8210fe)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=82f5c503-d2ea-4fed-8f9d-f30bee2f60b3)  
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
<th colspan="8" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-008**](https://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[**MS12-010**](https://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[**MS12-013**](https://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[**MS12-016**](https://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[**MS12-009**](https://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[**MS12-012**](https://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[**MS12-014**](https://go.microsoft.com/fwlink/?linkid=239945)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f0e6e06d-89db-45ad-9660-7959c6f9b546)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=c4642890-2fba-45da-bbe9-fcaa84e4aa0c)  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9e157b88-2c11-44dc-b13d-1051f9c39890)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bf8ad019-e710-4e16-be4f-8168df5c5343)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5ee4bef7-b355-4aae-8bba-834a16d44744)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b81decda-9d82-4ffb-baae-78b190e553ea)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=c4a52801-55b5-4eef-9db3-c29a45863198)  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f162ad36-c096-43ba-a440-ec4d3fb54c21)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ef4a9002-b2da-40af-abc0-737565fea179)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b53cf810-0ea3-4cb0-91f9-de1406ccfc96)  
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
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=8dcd71c8-82ad-4f86-b386-7f1ea09e157f)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=3b42f935-7f59-4871-a01f-480033c3ad40)  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=24fe7c08-4736-455b-9b98-1b6a65718143)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3b18d22d-e192-498b-a105-b946a5f5bfad)  
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
<th colspan="8" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-008**](https://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[**MS12-010**](https://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[**MS12-013**](https://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[**MS12-016**](https://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[**MS12-009**](https://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[**MS12-012**](https://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[**MS12-014**](https://go.microsoft.com/fwlink/?linkid=239945)
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
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5852118c-fc39-45e2-8b44-ce1401d310e2)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6ec23c7e-0166-47dc-ae86-c49b505206bb)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bbf627df-0bc0-478f-aa34-a7e5f039e589)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=d287496a-411c-4c1b-9d98-bacc553041ae)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c503c7b1-24f8-40a4-8283-c1e4abf90b57)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
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
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5161d16d-1037-49d5-8d4d-c353288cb41c)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b30a8cc5-b9ad-476f-928c-c49c993d0e80)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3a8b966a-bf34-42fd-8758-9a5e8e3c7689)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=22cc0245-1877-4c76-914f-dd68f6cd45f0)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ddbd9fcf-10c4-4089-88c0-c2a6c288222b)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=73e240a6-2d5e-4ceb-8500-8dacca0e4a43)  
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
<th colspan="8" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-008**](https://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[**MS12-010**](https://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[**MS12-013**](https://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[**MS12-016**](https://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[**MS12-009**](https://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[**MS12-012**](https://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[**MS12-014**](https://go.microsoft.com/fwlink/?linkid=239945)
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=45c6c511-a4fa-4c3b-af26-6c113f6f5f5e)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=21f7dba4-fe97-487e-8b37-45914e106db0)\*\*  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=98d5b024-0eda-4e5d-ba9d-b828ad3d048e)\*\*  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=025a5af0-39f1-481c-920c-43d2b3d85dc5)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0c1812af-f57d-455d-a81d-5e03db99b2f7)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3f6f89b3-3bc8-4325-b8d8-9a5a398b99c6)\*\*  
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
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=046932cf-0671-49e6-8ddf-98abfc97c5f0)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2cd8e296-dae8-41ce-8373-f8a71b4555e9)\*\*  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=246f9995-fe19-43d0-8f67-0e91eb961bab)\*\*  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c216e01d-2f46-4a46-bdc7-9d0fe98193a3)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e1b66bb5-ea12-44a5-807a-f21ede0dc76d)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0e06e77d-7e5d-4d57-98b2-0817f68a1ebb)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=35e6bd04-594f-42ef-97f8-abcf578b4f10)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=304bd0c5-f4ee-4f8c-89b4-4cbaaf418679)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=05c0e6eb-c641-43ab-958a-f43933cdbba7)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3a96ab34-8f45-48bf-a98b-9e683b50aaa0)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=56cbeba9-0c39-4418-9042-7244ac9d03db)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d1d51b26-2d01-42a9-9bb1-9fb82c1fb914)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
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
[**MS12-008**](https://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[**MS12-010**](https://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[**MS12-013**](https://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[**MS12-016**](https://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[**MS12-009**](https://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[**MS12-012**](https://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[**MS12-014**](https://go.microsoft.com/fwlink/?linkid=239945)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3e5ca1bf-9415-412c-9dff-dd1abc57e74d)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8b423683-cd29-4049-82d6-f0845842e7f0)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c83a9c74-a5a7-4b3e-ba36-7a7024d99fd8)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=403f355c-2273-42ac-8263-d662f5d7740c)  
（严重）
</td>
<td style="border:1px solid black;">
仅限 Windows 7（用于 32 位系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc)  
(KB2633879)  
（严重）  
仅限 Windows 7（用于 32 位系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5)  
(KB2633873)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78cbbe02-a3d3-4cef-9b54-a3e78c1b885a)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a5d00138-4e24-4a07-92dd-3d8a14476197)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=bbc9d6ae-9ec5-401f-bf16-4811b63709d1)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8bd8e804-ca4d-4326-bc60-345e2975b7aa)  
（严重）
</td>
<td style="border:1px solid black;">
仅限 Windows 7（用于基于 x64 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc)  
(KB2633879)  
（严重）  
仅限 Windows 7（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5)  
(KB2633873)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=299d107d-ab9f-42b6-8f94-a2f1d242c127)  
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
<th colspan="8" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-008**](https://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[**MS12-010**](https://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[**MS12-013**](https://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[**MS12-016**](https://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[**MS12-009**](https://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[**MS12-012**](https://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[**MS12-014**](https://go.microsoft.com/fwlink/?linkid=239945)
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6b228ad6-d5a4-4b91-8aa8-0874deb22116)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3074a898-54bb-44ff-a8f4-77f831c28771)\*\*  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=1896a6da-f7ee-484b-a97c-455fce7b82b8)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d868c5ef-165a-46a0-b832-e6ca55a910f9)\*  
（严重）
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008 R2（用于基于 x64 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc)\*  
(KB2633879)  
（严重）  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5)\*  
(KB2633873)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)\*<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=576192d3-f050-4718-a7da-c84fce6bf744)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8c51e09b-51c3-4860-836e-6bcffde75f04)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=922b2438-0cfc-49e3-b9a0-52c68b69126a)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7f7c0bc3-fc26-4ee8-aedb-c251247cbeb5)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e5416371-495b-4dc7-a239-f9185f968969)  
（严重）
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc)  
(KB2633879)  
（严重）  
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5)  
(KB2633873)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>  
(KB2633870)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d6a9b2c9-7582-4953-8ab1-a55c63fcc8dc)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=fba58a1b-9d9f-4a10-b1df-08a0ebfa2358)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。**此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*\*\*服务器核心安装受到影响。**当使用服务器核心安装选项进行安装时，此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级较低。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS12-010 的注释**

<sup>[1]</sup>严重等级不适用于指定软件的此更新，因为本公告中讨论的漏洞的已知攻击媒介已在默认配置中阻止。然而，作为一种纵深防御措施，Microsoft 建议这款软件的客户应用此安全更新。

**MS12-016 的注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](https://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
其他 Microsoft Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-015**](https://go.microsoft.com/fwlink/?linkid=238400)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 和 Microsoft Visio Viewer 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 和 Microsoft Visio Viewer 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=173dc4e6-31b4-42ec-808c-f8cd005517ab)  
(KB2597170)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 和 Microsoft Visio Viewer 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 和 Microsoft Visio Viewer 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=34b234e1-1322-4edc-829c-7bc2fbd99338)  
(KB2597170)  
（重要）
</td>
</tr>
</table>


#### Microsoft 服务器软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-011**](https://go.microsoft.com/fwlink/?linkid=238500)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 和 Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 和 Microsoft SharePoint Server 2010 Service Pack 1 (moss)](https://www.microsoft.com/download/details.aspx?familyid=44a8eb5a-e469-4d36-b5a0-7e030c1d3244)  
(KB2597124)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-011**](https://go.microsoft.com/fwlink/?linkid=238500)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 和 Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 和 Microsoft SharePoint Foundation 2010 Service Pack 1 (sts)](https://www.microsoft.com/download/details.aspx?familyid=dd348109-953b-4154-b265-85e4694238e6)  
(KB2553413)  
（重要）
</td>
</tr>
</table>


#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-016**](https://go.microsoft.com/fwlink/?linkid=235370)
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
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
安装在 Mac 上的 [Microsoft Silverlight 4](https://www.microsoft.com/download/details.aspx?familyid=4c3602f0-9781-4374-8fef-669ddd2c0d40)  
(KB2668562)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 [Microsoft Silverlight 4](https://www.microsoft.com/download/details.aspx?familyid=4c3602f0-9781-4374-8fef-669ddd2c0d40)  
(KB2668562)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 [Microsoft Silverlight 4](https://www.microsoft.com/download/details.aspx?familyid=4c3602f0-9781-4374-8fef-669ddd2c0d40)  
(KB2668562)  
（严重）
</td>
</tr>
</table>

**MS12-016 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/default.aspx)。

**System Center Configuration Manager 2007**

Configuration Manager 2007 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 Configuration Manager 2007，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

Configuration Manager 2007 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。Configuration Manager 2007 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关管理员如何使用 Configuration Manager 2007 部署更新的详细信息，请参阅[软件更新管理](https://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)。有关 Configuration Manager 的详细信息，请访问 [System Center Configuration Manager](https://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。SMS 的下一版本 System Center Configuration Manager 2007 现已可用；请参阅前面的部分 **System Center Configuration Manager 2007**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

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

-   [Azimuth Security](https://www.azimuthsecurity.com/) 的 Tarjei Mandt 报告了 MS12-008 中描述的一个问题
-   [Azimuth Security](https://www.azimuthsecurity.com/) 的 Tarjei Mandt 报告了 MS12-009 中描述的两个问题
-   [Jan Schejbal](https://janschejbal.wordpress.com/) 报告了 MS12-010 中描述的一个问题
-   [Harmony Security](https://www.harmonysecurity.com/) 的 Stephen Fewer 与 [TippingPoint's](https://www.tippingpoint.com/)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS12-010 中描述的两个问题
-   [HP Cloud Services](https://www.hpcloud.com/) 的 Jason Hullinger 报告了 MS12-010 中描述的一个问题
-   John Hollenberger 报告了 MS12-011 中描述的一个问题
-   stratsec 的 Rocco Calvi 报告了 MS12-011 中描述的一个问题
-   Minded Security 的 Giorgio Fedon 与我们合作解决了 MS12-011 中的纵深防御更新问题
-   Alexander Gavrun 与 [TippingPoint's](https://www.tippingpoint.com/)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS12-013 中描述的一个问题
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Xin Ouyang 报告了 MS12-015 中描述的五个问题
-   [Sumatra](https://www.sumatra.nl/) 的 Jeroen Frijters 报告了 MS12-016 中描述的一个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY (1-866-727-2338) 获得技术支持。与安全更新有关的电话支持服务是免费的。有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。与安全更新有关的支持服务不收取任何费用。有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2012 年 2 月 14 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
