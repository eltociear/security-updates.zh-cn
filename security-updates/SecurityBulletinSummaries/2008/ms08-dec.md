---
TOCTitle: 'MS08-DEC'
Title: 'Microsoft 安全公告摘要 (2008 年 12 月)'
ms:assetid: 'ms08-dec'
ms:contentKeyID: 61236914
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms08-dec(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2008 年 12 月)
======================================

发布时间: 2008年12月9日 | 更新时间: 2009年1月28日

**版本:** 5.0

本公告摘要列出了 2008 年 12 月发布的安全公告。

对于 2008 年 12 月发布的安全公告，本公告摘要替代 2008 年 12 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2008 年 12 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 12 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374647)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

对于添加到此公告摘要 (MS08-078) 的版本 3.0 的额外安全公告，Microsoft 将主持两次网络广播，以解决客户关于这些公告的疑问： 太平洋时间 2008 年 12 月 17 日下午 1:00（美国和加拿大）和太平洋时间 2008 年 12 月 18 日上午 11:00。 立即注册收听 [12 月 17 日的网络广播](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399448&culture=en-us)和 [12 月 18 日的网络广播](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399449&culture=en-us)。 然后，这些网络广播以点播方式提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-071">MS08-071</a></td>
<td style="border:1px solid black;"><strong>GDI 中的漏洞可能允许远程执行代码 (956802)</strong><br />
<br />
此安全更新可解决 GDI 中两个秘密报告的漏洞。 如果用户打开特制的 WMF 图像文件，利用其中任何一个漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-075">MS08-075</a></td>
<td style="border:1px solid black;"><strong>Windows Search 中的漏洞可能允许远程执行代码 (959349)</strong><br />
<br />
此安全更新可解决 Windows Search 中两个秘密报告的漏洞。 如果用户在 Windows Explorer 打开和保存特制的保存搜索文件，或者用户单击特制的搜索 URL，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (958215)</strong><br />
<br />
此安全更新可消除四个秘密报告的漏洞。 如果用户使用 Internet Explorer 查看特制网页，则所有漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-078">MS08-078</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的安全更新 (960714)</strong><br />
<br />
此安全更新解决了一个公开披露的漏洞。 如果用户使用 Internet Explorer 查看特制网页，则该漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;"><strong>Visual Basic 6.0 运行时扩展文件（ActiveX 控件）中的漏洞可能允许远程执行代码 (932349)</strong><br />
<br />
此安全更新解决了 Microsoft Visual Basic 6.0 运行时扩展文件的 ActiveX 控件中的五个秘密报告的漏洞和一个公开披露的漏洞。 如果用户浏览了包含特制内容的网站，这些漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft 开发工具和软件、Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word 中的漏洞可能允许远程执行代码 (957173)</strong><br />
<br />
此安全更新解决了 Microsoft Office Word 和 Microsoft Office Outlook 中八个秘密报告的漏洞，如果用户打开特制的 Word 或 RTF 文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-074">MS08-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel 中的漏洞可能允许远程执行代码 (959070)</strong><br />
<br />
此安全更新解决了 Microsoft Office Excel 中三个秘密报告的漏洞，如果用户打开特制的 Excel 文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-077">MS08-077</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office SharePoint Server 中的漏洞可能导致特权提升 (957175)</strong><br />
<br />
此安全更新可解决一个秘密报告的漏洞。 如果攻击者通过浏览 SharePoint 站点上的管理 URL 而绕过身份验证，此漏洞可能允许特权提升。 导致特权提升的成功攻击可能会引起拒绝服务或信息泄露的后果。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft 服务器软件</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-076">MS08-076</a></td>
<td style="border:1px solid black;"><strong>Windows Media 组件中的漏洞可能允许远程执行代码 (959807)</strong><br />
<br />
此安全更新可解决下列 Windows Media 组件中两个秘密报告的漏洞： Windows Media Player、Windows Media Format Runtime 和 Windows Media Services。 此最严重的漏洞可能允许远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/en-us/security/cc998259.aspx)。

<p> </p>
<table style="border:1px solid black;">  
<thead>  
<tr class="header">  
<th>公告 ID</th>  
<th>公告标题</th>  
<th>CVE ID</th>  
<th>利用指数评估</th>  
<th>重要注意事项</th>  
</tr>  
</thead>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 运行时扩展文件（ActiveX 控件）中的漏洞可能允许远程执行代码 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3704">CVE-2008-3704</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">一致漏洞检测代码公开提供</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 运行时扩展文件（ActiveX 控件）中的漏洞可能允许远程执行代码 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4252">CVE-2008-4252</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 运行时扩展文件（ActiveX 控件）中的漏洞可能允许远程执行代码 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4256">CVE-2008-4256</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 运行时扩展文件（ActiveX 控件）中的漏洞可能允许远程执行代码 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4253">CVE-2008-4253</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 运行时扩展文件（ActiveX 控件）中的漏洞可能允许远程执行代码 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4254">CVE-2008-4254</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-070">MS08-070</a></td>
<td style="border:1px solid black;">Visual Basic 6.0 运行时扩展文件（ActiveX 控件）中的漏洞可能允许远程执行代码 (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4255">CVE-2008-4255</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">Windows 2000 系统受到的威胁最大。 Windows XP SP2、Windows Server 2003 SP1 以及更高版本的操作系统由于更强堆保护而不太可能受功能漏洞检测代码的影响。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-071">MS08-071</a></td>
<td style="border:1px solid black;">GDI 中的漏洞可能允许远程执行代码 (956802)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3465">CVE-2008-3465</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-071">MS08-071</a></td>
<td style="border:1px solid black;">GDI 中的漏洞可能允许远程执行代码 (956802)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2249">CVE-2008-2249</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能被利用的功能漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 中的漏洞可能允许远程执行代码 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4024">CVE-2008-4024</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 中的漏洞可能允许远程执行代码 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4025">CVE-2008-4025</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 中的漏洞可能允许远程执行代码 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4026">CVE-2008-4026</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 中的漏洞可能允许远程执行代码 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4027">CVE-2008-4027</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 中的漏洞可能允许远程执行代码 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4028">CVE-2008-4028</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 中的漏洞可能允许远程执行代码 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4030">CVE-2008-4030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 中的漏洞可能允许远程执行代码 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4837">CVE-2008-4837</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-072">MS08-072</a></td>
<td style="border:1px solid black;">Microsoft Office Word 中的漏洞可能允许远程执行代码 (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4031">CVE-2008-4031</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能被利用的功能漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;">Internet Explorer 的累积性安全更新 (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4258">CVE-2008-4258</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;">Internet Explorer 的累积性安全更新 (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4259">CVE-2008-4259</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;">Internet Explorer 的累积性安全更新 (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4261">CVE-2008-4261</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-073">MS08-073</a></td>
<td style="border:1px solid black;">Internet Explorer 的累积性安全更新 (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4260">CVE-2008-4260</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-074">MS08-074</a></td>
<td style="border:1px solid black;">Microsoft Office Excel 中的漏洞可能允许远程执行代码 (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4265">CVE-2008-4265</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-074">MS08-074</a></td>
<td style="border:1px solid black;">Microsoft Office Excel 中的漏洞可能允许远程执行代码 (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4266">CVE-2008-4266</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-074">MS08-074</a></td>
<td style="border:1px solid black;">Microsoft Office Excel 中的漏洞可能允许远程执行代码 (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4264">CVE-2008-4264</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-075">MS08-075</a></td>
<td style="border:1px solid black;">Windows Search 中的漏洞可能允许远程执行代码 (959349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4269">CVE-2008-4269</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-075">MS08-075</a></td>
<td style="border:1px solid black;">Windows Search 中的漏洞可能允许远程执行代码 (959349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4268">CVE-2008-4268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 可能的不一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-076">MS08-076</a></td>
<td style="border:1px solid black;">Windows Media 组件中的漏洞可能允许远程执行代码 (959807)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3009">CVE-2008-3009</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">可以创建此问题的一致漏洞检测代码。 但是，攻击情形的有限性意味着实际攻击不太可能。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-076">MS08-076</a></td>
<td style="border:1px solid black;">Windows Media 组件中的漏洞可能允许远程执行代码 (959807)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3010">CVE-2008-3010</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">可以创建此问题的一致漏洞检测代码。 但是，攻击情形的有限性意味着实际攻击不太可能。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-077">MS08-077</a></td>
<td style="border:1px solid black;">Microsoft Office SharePoint Server 中的漏洞可能导致特权提升 (957175)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4032">CVE-2008-4032</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">可以创建此问题的一致漏洞检测代码。 但是，利用此漏洞的攻击只可能导致信息泄露，而不会导致远程执行代码。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-078">MS08-078</a></td>
<td style="border:1px solid black;">Internet Explorer 安全更新 (960714)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4844">CVE-2008-4844</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 可能的一致漏洞检测代码<br />
（发布公告时公开）</td>
<td style="border:1px solid black;">在主动攻击实例中，发现了一致漏洞检测代码。 但是，对于 Windows Vista 和 Windows Server 2008 的默认安装，Internet Explorer 在保护模式下运行，从而使漏洞利用难以进行。</td>
</tr>  
</tbody>  
</table>
  
受影响的软件和下载位置  
----------------------
  
  
**我如何使用该表呢？**
  
可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
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
<th>  
</th>  
</tr>  
<tr>  
<th colspan="6" style="border:1px solid black;">  
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=3b775fb1-1077-455d-af4a-4ccb5237974f)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=c242ba42-556b-4c87-bf33-9d99166ff096)  
（严重）  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c0583745-7e57-4265-9429-c3415cb8465f)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=d3e18732-47f1-40ce-999c-d1fd283bf138)  
（严重）  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=124c14b6-9323-4f6f-902b-727aa56444bc)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=c33d558e-45f9-4e85-b48c-03bd0e8cb4bc)  
(KB954600)  
（重要）  
[Windows Media Format Runtime 7.1 和 Windows Media Format Runtime 9.0](https://www.microsoft.com/download/details.aspx?familyid=6a459497-0ab8-41cb-87d0-b551631d8d8a)  
(KB952069)  
（重要）  
[Windows Media Services 4.1](https://www.microsoft.com/download/details.aspx?familyid=58b7d241-cef6-48fa-aa52-017695f71db1)  
(KB952068)  
（重要）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2151fbba-c464-4d1e-82d4-5b096e82bed0)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=af9a6cb0-725d-490c-9858-16ec40e98560)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1b582695-b3cc-4c65-bc4b-d673c9a6d82a)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=1d83e0af-46fa-4bfc-ba57-635435a7ef2d)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0190a289-164e-41a7-8c01-fa1aaed3f531)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=99241309-e644-4088-a8f3-38837fab4037)  
(KB954600)  
（重要）  
[Windows Media Format Runtime 9.0、Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=504f816c-f554-4b93-ac28-b085574d9bac)  
（仅限 Windows XP Service Pack 2）  
(KB952069)  
（重要）  
[Windows Media Format Runtime 9.0、Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=ad76fcf3-a2f9-4e36-bd1b-c1536749173c)  
（仅限 Windows XP Service Pack 3）  
(KB952069)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2247f6a5-aa33-4c68-9ea8-a63488d126d3)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=60bf9851-24fe-4658-8333-d353e82063c7)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=107cf54b-29d4-4c54-b091-2b5b3ffbf49d)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=a585cb73-2c1a-4fa8-862a-ad6aeaeaf2f8)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9ba71e23-8cef-4399-b215-983b0dcf5cb5)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=946d47c9-b208-4fab-8ef6-774413d61bc8)  
(KB954600)  
（重要）  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=644ef023-ee40-45b0-9c9d-c76d9fab0005)  
(KB952069)  
（重要）  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524)  
(KB952069)  
（重要）  
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=2dadc017-2be5-4240-ab8f-0291756dca6b)  
(KB952069)  
（重要）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0c396796-0929-4cd2-99e8-3c0f7075a89e)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=d53adf6f-9501-4862-a1ca-57eb4d40cd75)  
（中等）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9cdd4f9e-c578-405c-af9e-628f2d77fdf4)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=d81e9cf9-ce0c-463a-a359-49a348cb89ae)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=388847ec-817e-45cf-8fa7-32c7e1f57f80)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=2315ce20-2f46-42c2-bb40-045f003409d7)  
(KB954600)  
（重要）  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=d8958248-c889-499e-a6a9-3b394cdb27ea)  
(KB952069)  
（重要）  
[Windows Media Services 9 Series](https://www.microsoft.com/download/details.aspx?familyid=e71abc2d-d60e-444a-9b7b-062c5805fe9e)  
(KB952068)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d5c7d2f-1a82-4cdf-b3f2-b2c2390c6a64)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5e37cb34-32be-4bbe-87f3-c4e1974e4d00)  
（中等）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7c36f92c-d8a0-4b70-b85f-83588a0299a0)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=015df302-d79f-43a1-b5c5-32ac04de0510)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2ae17caf-6204-470e-8480-380d3d505657)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=4c29bed9-1b88-4d2f-80a5-305c2bedd89f)  
(KB954600)  
（重要）  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=2278022e-a716-46c0-bedf-d626933bd815)  
(KB952069)  
（重要）  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524)  
(KB952069)  
（重要）  
[Windows Media Services 9 Series](https://www.microsoft.com/download/details.aspx?familyid=e0030155-1a9a-46cc-bbc8-6d0d1ed65c1f)  
(KB952068)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1edb62b4-3d0f-4891-b4b3-8f8bc4e7bdfe)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=0da4e424-4682-4401-a226-7d8f1be19d44)  
（中等）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3811030d-5958-4b91-b5b8-20587dc7c4d6)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=18016305-7f72-47f6-ab4c-94282289bf5f)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=97d6c093-f68d-4ddf-8e3c-f29662a1940f)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=cddf9cf6-bdeb-4429-823a-879387a428d7)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0dcc5373-0435-42d5-864d-298e5bb122d9)  
(KB958623)  
（重要）  
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5b1b65f0-6848-47c6-bdd5-be3c0621b323)  
(KB958624)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3f62030a-9ce2-4c92-b948-143a6881921e)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7887111d-4fac-4823-bdd2-a18d9468fdf0)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=1fcdc8dd-26d9-4d1a-8b3f-7b6a21a95999)  
(KB952069)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=73dc3775-b6f0-40f1-bd36-6b5fb80eb2fa)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2112c5c8-7c9f-4491-b127-b1093085e105)  
(KB958623)  
（重要）  
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=eb1d0ffe-1644-457b-9e82-768bd4c7f7ab)  
(KB958624)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d8800493-fba4-41f8-bde5-a53eeaf89d54)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=69979d92-8d45-47fe-ac4c-c2f1f23cf1fb)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=8839f6cd-dfbf-448c-bf1e-1da9bb5f3f25)  
(KB952069)  
（重要）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://technet.microsoft.com/security/bulletin/ms08-071)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://technet.microsoft.com/security/bulletin/ms08-075)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://technet.microsoft.com/security/bulletin/ms08-073)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://technet.microsoft.com/security/bulletin/ms08-078)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://technet.microsoft.com/security/bulletin/ms08-076)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=bbed9e8b-e75e-44ef-ba1d-fd6f852c1f67)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=90ab7e6f-5ae7-4f55-8838-868fc98d8a16)\*\*\*  
(KB958623)  
（重要）  
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=470d506f-77ae-4a44-8598-df645f484295)\*\*\*  
(KB958624)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=45a0de3c-c7d1-4314-a456-1f7428b7c90a)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5552e564-dd1c-4e2a-9a42-6317522c884d)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=91ec4195-bc1c-444e-a7b0-ebde46c088fa)  
(KB952069)  
（重要）  
[Windows Media Services 2008](https://www.microsoft.com/download/details.aspx?familyid=ffb5d945-7f98-4849-b020-ed4873fa42df)\*  
(KB952068)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=48aecf4c-1296-490d-ba37-a28e3ec19bd6)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e1deab57-ada2-4b12-9157-5615e7b0071d)\*\*\*  
(KB958623)  
（重要）  
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e41f23e4-6a2f-4ebb-b425-d241a08da316)\*\*\*  
(KB958624)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=405b28db-47d7-4d6b-90e6-834c0a409323)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=889c6eb1-7d1f-4e60-b637-535cb6e4e443)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=8cab6fe8-161d-4d8c-9772-eb3174a2c3c3)  
(KB952069)  
（重要）  
[Windows Media Services 2008](https://www.microsoft.com/download/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72)\*  
(KB952068)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=9bfe15cd-02ff-45cf-85c8-5ff1e6c1a871)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=48bed90d-c243-4969-8e54-326d9a7af343)  
(KB958623)  
（重要）  
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=83de2263-de2a-4c13-96ba-ecfebdaf0bb9)  
(KB958624)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f0d4f321-941e-4da7-958f-582c75542ee8)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=06cb502a-6818-4599-aa24-6eddb83e4b84)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**MS08-078 注释**

MS08-078 中解决的漏洞是在 Windows Internet Explorer 8 Beta 2 发布之后报告的。鼓励运行 Windows Internet Explorer 8 Beta 2 的客户下载并向其系统应用此更新。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

**Windows Server 2008 的注释**

**\*Windows Server 2008 服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 的受支持版本，严重等级相同，无论安装 Windows Server 2008 时是否使用“服务器核心”安装选项。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*Windows Server 2008 服务器核心安装不受影响。** 如果安装 Windows Server 2008 时使用“服务器核心”安装选项，则此更新所解决的漏洞不会影响 Windows Server 2008 的受支持版本。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*\*Windows Server 2008 服务器核心安装不受影响。** 如果使用服务器核心安装选项安装了 Windows Server 2008，则这些更新解决的漏洞不会影响 Windows Server 2008 的受支持版本，即使系统上可能存在这些漏洞会影响的文件也是如此。 但是，仍将向具有受影响文件的用户提供此更新，因更新文件比您的系统上的当前文件更新（版本号较高）。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

#### Microsoft Office 套件和软件

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
<th colspan="5" style="border:1px solid black;">
Microsoft Office 套件、系统和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://technet.microsoft.com/security/bulletin/ms08-072)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://technet.microsoft.com/security/bulletin/ms08-074)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=43e8c4d8-307b-48f6-ac99-a9617421d40a)  
(KB956328)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f39d2a49-f861-4f2d-bf91-94a8a85af40c)  
(KB958435)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3ef41412-50b3-4077-b0e3-9a3704d2f876)  
(KB956329)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=72076e21-2aa3-48e8-883a-c3cb756fc72a)  
(KB958372)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=45c81c60-4b1b-4246-839b-198ebc4eeae2)  
(KB956357)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6c0771e5-fcd4-4365-b903-1a3bd95d9e66)  
(KB958436)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007](https://www.microsoft.com/download/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
（重要）  
[Microsoft Office Outlook 2007](https://www.microsoft.com/download/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007](https://www.microsoft.com/download/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf)  
(KB958437)\*\*\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
（重要）  
[Microsoft Office Outlook 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf)  
(KB958437)\*\*\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office FrontPage
</td>
<td style="border:1px solid black;">
[Microsoft Office FrontPage 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=0a6130ae-c5b4-43cb-afe3-ab6a55b9d9ea)\*  
(KB957797)  
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
Microsoft Office Project
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=89a44042-a629-40f3-800a-0bb45fc36591)  
(KB949045)  
（严重）  
[Microsoft Office Project 2007](https://www.microsoft.com/download/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6)  
(KB949046)  
（严重）  
[Microsoft Office Project 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6)  
(KB949046)  
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
<th colspan="5" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://technet.microsoft.com/security/bulletin/ms08-072)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://technet.microsoft.com/security/bulletin/ms08-074)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820)\*\*  
(KB960402)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820)\*\*  
(KB960402)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62)\*\*  
(KB960401)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62)\*\*  
(KB960401)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7)\*\*  
(KB960403)  
（重要）
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7)\*\*  
(KB960403)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://technet.microsoft.com/security/bulletin/ms08-072)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://technet.microsoft.com/security/bulletin/ms08-074)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](https://www.microsoft.com/download/details.aspx?familyid=1537d181-90d9-4bb5-b5ae-8d9990a349af)\*\*\*  
(KB959487)  
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
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](https://www.microsoft.com/download/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e)  
(KB958434)  
（重要）  
[Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e)  
(KB958434)  
（重要）  
[Microsoft Office Excel Viewer](https://www.microsoft.com/download/details.aspx?familyid=9dbb35c1-aa7a-481b-a330-8ba916ddd443)  
(KB958442)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 Service Pack 3 和 Microsoft Office Word Viewer](https://www.microsoft.com/download/details.aspx?familyid=70de7c3c-519f-4f4a-a03f-027f80b5415c)  
(KB956366)  
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
用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970)  
(KB956828)  
（重要）  
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970)  
(KB956828)  
（重要）
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)  
(KB958439)  
（重要）  
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)  
(KB958439)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
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
[Microsoft Office SharePoint Server 2007（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)  
(KB956716)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)  
(KB956716)  
（重要）  
[Microsoft Office SharePoint Server 2007（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86)  
(KB956716)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86)  
(KB956716)  
（重要）
</td>
</tr>
</table>

**MS08-070 注释**  
另请参阅下一节 **Microsoft 开发工具和软件**，了解更多更新文件。 此公告涵盖 Microsoft Office 和 Microsoft 开发工具和软件。

**MS08-077 注释**  
另请参阅 **Microsoft 服务器软件**一节，了解更多更新文件。 此公告涵盖 Microsoft Office 套件和软件以及 Microsoft 服务器软件。

**MS08-070 中有关 Microsoft Office FrontPage 的注释**  
\*此更新仅适用于 FrontPage 2002 Service Pack 3 的 Chinese Simplified (China)、Chinese Pan (Hong Kong)、Chinese Traditional (Taiwan) 和 Korean 版本。

**MS08-072 和 MS08-074 中有关 Microsoft Office for Mac 的注释**  
\*\*MS08-072 和 MS08-074 中的相应更新是相同的，由于漏洞位于相同的文件中，因此这两个公告的更新是相同的。

**MS08-072 中的 Works 8 注释**  
\*\*\*为收到此安全更新，运行 Microsoft Works 8.0 的客户必须首先按照 [Microsoft Works Update](http://www.microsoft.com/products/works/international/update_1001.mspx) 中所述更新到 Works 8.5。 这包括使用 Microsoft Works 8.0、Works Suite 2004 和 Works Suite 2005 的所有客户。对于运行 Works Suite 2006 的客户，Works 8.5 已包括。

**MS08-074 中关于 Microsoft Office Excel 2007 和 Microsoft Office Excel 2007 Service Pack 1 的注释**  
\*\*\*\*对于 Microsoft Office Excel 2007 和 Microsoft Office Excel 2007 Service Pack 1，除了安全更新程序包 KB958437 之外，客户还需要安装针对[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)的安全更新 (KB958439)，以免受 MS08-074 中所描述的漏洞影响。已成功安装 KB958437 和 KB958439 更新程序包的客户不需要重新安装。

#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Visual Studio。
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://technet.microsoft.com/security/bulletin/ms08-070)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic 6.0 运行时扩展文件](https://www.microsoft.com/download/details.aspx?familyid=e27eebcb-095d-43ec-a19e-4a46e591715c)  
(KB926857)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=afad980d-7f27-49d9-aa23-b762c7b94cd6)  
(KB958392)  
（严重）  
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6ac7cf8f-d046-43a8-b4ef-253153d65aed)  
(KB958393)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a6977f81-f7f6-486b-96ad-8d296d79f205)  
(KB958369)  
（严重）  
[Microsoft Visual FoxPro 9.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=386d27a6-b2c7-4acc-bf3e-edcbc7358172)  
(KB958370)  
（严重）  
[Microsoft Visual FoxPro 9.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5b1f28a9-da8d-463a-8ae4-dfc8fcc6c41a)  
(KB958371)  
（严重）
</td>
</tr>
</table>

**MS08-070 注释**
另请参阅上一节 **Microsoft Office 套件和软件**，了解更多更新文件。 此公告涵盖 Microsoft Office 套件和软件以及 Microsoft 开发工具和软件。

#### Microsoft 服务器软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
搜索服务器
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://technet.microsoft.com/security/bulletin/ms08-077)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Search Server
</td>
<td style="border:1px solid black;">
[Microsoft Search Server 2008（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)\*  
(KB956716)  
（重要）  
[Microsoft Search Server 2008（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86)\*\*  
(KB956716)  
（重要）
</td>
</tr>
</table>

**MS08-077 注释**

\*包括 Microsoft Search Server 2008 Express（32 位）

\*\*包括 Microsoft Search Server 2008 Express（64 位）

另请参阅 **Microsoft Office 套件和软件**一节，了解更多更新文件。 此公告涵盖 Microsoft Office 套件和软件以及 Microsoft 服务器软件。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)和 [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS) 和扩展安全更新清单工具 (ESUIT)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](http://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](http://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft Baseline Security Analyzer 和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： 2008 年 Software Update Services 和 Windows Server Update Services 内容的更改说明。包括所有 Windows 内容。
-   [Microsoft Windows 之外的其他 Microsoft 产品的新更新、经过修订的更新以及已发布的更新](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   [VenusTech](http://www.venustech.com.cn/) 的 ADLab 报告了 MS08-070 中描述的多个问题
-   [Affiliated Computer Services](http://www.acs-inc.com/) 的 Jason Medeiros 报告了 MS08-070 中描述的问题
-   [Secunia Research](http://secunia.com/) 的 Carsten Eiram 报告了 MS08-070 中描述的问题
-   Mark Dowd 与 [McAfee Avert Labs](http://www.avertlabs.com/)一起报告了 MS08-070 中描述的问题
-   [Insomnia Security](http://www.insomniasec.com/) 的 Brett Moore 报告了 MS08-070 中描述的问题
-   CHkr\_D591 与[TippingPoint](http://www.tippingpoint.com/)和[Zero Day Initiative](http://www.zerodayinitiative.com/)一起报告了 MS08-070 中描述的问题
-   Michal Bucko 与 [CERT/CC](http://www.cert.org/)一起报告了 MS08-070 中描述的问题
-   Symantec 的 [Security Intelligence Analysis Team](http://www.symantec.com/) 与我们一起报告了 MS08-070 中描述的问题
-   [Verisign iDefense Labs](http://labs.idefense.com/) 的 Jun Mao 报告了 MS08-071 中描述的问题
-   Juan Caballero 与 [Carnegie Mellon University 的 Bitblaze 小组和 UC Berkeley](http://bitblaze.cs.berkeley.edu/) 一起报告了 MS08-071 中描述的问题
-   [Core Security Technologies](http://www.coresecurity.com/) 的 Ricardo Narvaja 报告了 MS08-072 中描述的问题
-   [Secunia Research](http://secunia.com/) 的 Dyon Balding 报告了 MS08-072 中描述的问题。
-   [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS08-072 中描述的问题
-   Wushi 与 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 MS08-072 中描述的问题
-   [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/)的 Aaron Portnoy 报告了 MS08-072 中描述的问题
-   [team509](http://www.team509.com/) 的 Wushi 与 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作，报告了 MS08-072 中描述的问题
-   Wushi 和 Ling与 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 MS08-072 中描述的问题
-   Carlo Di Dato (aka shinnai) 报告了 MS08-073 中描述的问题。
-   Brett Moore 与 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 MS08-073 中描述的问题
-   [Casaba Security](http://www.casabasecurity.com/) 的 Chris Weber 报告了 MS08-073 中描述的问题
-   [Verisign iDefense Labs](http://labs.idefense.com/) 的 Jun Mao 报告了 MS08-073 中描述的问题
-   [Verisign iDefense Labs](http://labs.idefense.com/) 的 Joshua J. Drake 报告了 MS08-074 中描述的问题
-   [signedness.org](http://www.signedness.org/)的 Claes M Nyberg 报告了 MS08-074 中描述的问题
-   [Secunia](http://secunia.com/) 的 Dyon Balding 报告了 MS08-074 中描述的问题
-   [eEye Digital Security](http://www.eeye.com/) 的 Andre Protas 报告了 MS08-075 中描述的问题
-   Nate McFeters 报告了 MS08-075 中描述的问题
-   匿名发现者报告了 MS08-077 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2008 年 12 月 9 日）： 已发布公告摘要。
-   V2.0（2008 年 12 月 10 日）： 纠正了 MS08-076 的受影响软件，将 Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11 列为 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 上的单独更新。还为 MS08-076 删除了对 Windows XP Professional x64 Edition、Windows XP Professional x64 Edition Service Pack 2、Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 Windows Media Format Runtime 11 x64 Edition 的错误引用。
-   V3.0（2008 年 12 月 17 日）： 添加了 Microsoft 安全公告 MS08-078 - Internet Explorer 的 安全更新 (960714)。 还添加了此额外安全公告的公告网络广播链接。
-   V3.1（2008 年 12 月 18 日）： 对于 MS08-078，为 Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于基于 x64 的系统）中的 Windows Internet Explorer 7 添加了不受影响的服务器核心符号。
-   V3.2（2009 年 1 月 7 日）： 已从 MS08-072 受影响的软件中删除 Microsoft Office Word Viewer 2003。
-   V4.0（2009 年 1 月 13 日）： Microsoft 已重新发布 MS08-076，为 Windows XP Service Pack 2 (KB952069) 和 Windows XP Service Pack 3 (KB952069) 上的 Windows Media Format Runtime 9.5 提供了新的更新程序包。 运行所有其他受支持和受影响版本 Windows Media 组件并已应用原始 MS08-076 安全更新程序包的客户无需再采取任何措施。 另外，还为 MS08-076 将 Windows Media Player 6.4 和 Windows Media Services 4.1 作为所有 Microsoft Windows 2000 Service Pack 4 版本上的受影响软件列出；如果客户已收到但尚未应用针对 Windows Media Player 6.4 的 KB954600 或者针对 Windows Media Services 4.1 的 KB952068，则需要应用这些更新。 最后，已为 MS08-072 将 Microsoft Office Word Viewer 作为受影响软件列出；已成功安装安全更新 KB956366 的客户不需要重新安装。
-   V5.0（2009 年 1 月 28 日）： 在“**受影响的软件**”表中为 MS08-074 添加了脚注，属于针对受支持版本 Microsoft Office Excel 2007 的安全更新程序包 KB958437 和 KB958439。没有更改安全更新二进制文件或检测。 拥有 Microsoft Office Excel 2007 或 Microsoft Office Excel 2007 Service Pack 1 并已成功安装了 KB958437 和 KB958439 的客户不需要重新安装。

*Built at 2014-04-18T01:50:00Z-07:00*
