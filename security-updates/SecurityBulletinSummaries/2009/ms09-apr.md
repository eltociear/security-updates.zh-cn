---
TOCTitle: 'MS09-APR'
Title: 'Microsoft 安全公告摘要 (2009 年 4 月)'
ms:assetid: 'ms09-apr'
ms:contentKeyID: 61236927
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms09-apr(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2009 年 4 月)
=====================================

发布时间: 2009年4月14日

**版本:** 1.0

本公告摘要列出了 2009 年 4 月发布的安全公告。

对于 2009 年 4 月发布的安全公告，本公告摘要替代 2009 年 4 月 9 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2009 年 4 月 15 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 4 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395126)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-010">MS09-010</a></td>
<td style="border:1px solid black;"><strong>写字板和 Office 文本转换器中的漏洞可能允许远程执行代码 (960477)</strong><br />
<br />
此安全更新可解决 Microsoft 写字板和 Microsoft Office 文本转换器中两个公开披露和两个秘密报告的漏洞。 如果使用写字板或 Microsoft Office Word 打开特制文件，则该漏洞可能允许远程执行代码。 请勿使用写字板或 Microsoft Office Word 的受影响版本打开来自不受信任来源的 Microsoft Office、RTF、Write 或 WordPerfect 文件。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-013">MS09-013</a></td>
<td style="border:1px solid black;"><strong>Windows HTTP 服务中的漏洞可能允许远程执行代码 (960803)</strong><br />
<br />
此安全更新可解决 Microsoft Windows HTTP 服务 (WinHTTP) 中一个公开披露和两个秘密报告的漏洞。 此最严重的漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-011">MS09-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow 中的漏洞可能允许远程执行代码 (961373)</strong><br />
<br />
此安全更新解决了 Microsoft DirectX 中一个秘密报告的漏洞。 如果用户打开特制的 MJPEG 文件，此漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-014">MS09-014</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (963027)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中四个秘密报告的漏洞和两个公开披露的漏洞。 如果用户使用 Internet Explorer 查看特制网页，或者用户通过 HTTP 协议连接到攻击者的服务器，该漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-009">MS09-009</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel 中的漏洞可以导致远程执行代码 (968557)</strong><br />
<br />
此安全更新可解决一个秘密报告的漏洞以及一个公开披露的漏洞。 如果用户打开一个特制的 Excel 文件，该漏洞可以允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-012">MS09-012</a></td>
<td style="border:1px solid black;"><strong>Windows 中的漏洞可能允许特权提升 (959454)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中四个公开披露的漏洞。 如果攻击者可以登录系统，然后运行特制的应用程序，这些漏洞可能允许特权提升。 攻击者必须要能够在本地计算机上运行代码才能利用此漏洞。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-016">MS09-016</a></td>
<td style="border:1px solid black;"><strong>Microsoft ISA Server 和 Forefront Threat Management Gateway (Medium Business Edition) 中的漏洞可能导致拒绝服务 (961759)</strong><br />
<br />
此安全更新解决了 Microsoft Internet Security and Acceleration (ISA) Server 和 Microsoft Forefront Threat Management Gateway (TMG) (Medium Business Edition (MBE)) 中一个秘密报告的漏洞和一个公开披露的漏洞。 如果攻击者将特制的网络数据包发送到受影响的系统，这些漏洞可以允许拒绝服务，或者如果用户单击一个恶意 URL 或者访问包含受攻击者控制的内容的网站，则会导致信息泄露。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Forefront Edge Security</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-015">MS09-015</a></td>
<td style="border:1px solid black;"><strong>SearchPath 中的混合威胁漏洞可能允许特权提升 (959426)</strong><br />
<br />
此安全更新解决了 Windows SearchPath 功能中一个公开披露的漏洞，如果用户下载了特制文件到特定位置，然后打开在某些情况下可能加载该文件的应用程序，则该漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">中等</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID 和 CVE ID 的排序列出。
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 公告标题                                                                                                                | CVE ID                                                                               | 利用指数评估                                                                                          | 重要注意事项                                                                                                                                       |  
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-009](https://technet.microsoft.com/security/bulletin/ms09-009) | Microsoft Office Excel 中的漏洞可以导致远程执行代码 (968557)                                                            | [CVE-2009-0100](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0100)     | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码         | （无）                                                                                                                                             |  
| [MS09-009](https://technet.microsoft.com/security/bulletin/ms09-009) | Microsoft Office Excel 中的漏洞可以导致远程执行代码 (968557)                                                            | [CVE-2009-0238](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0238)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | **此漏洞当前正在 Internet 生态系统中被利用。**                                                                                                     |  
| [MS09-010](https://technet.microsoft.com/security/bulletin/ms09-010) | 写字板和 Office 文本转换器中的漏洞可能允许远程执行代码 (960477)                                                         | [CVE-2008-4841](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4841)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | **此漏洞当前正在 Internet 生态系统中被利用。**                                                                                                     |  
| [MS09-010](https://technet.microsoft.com/security/bulletin/ms09-010) | 写字板和 Office 文本转换器中的漏洞可能允许远程执行代码 (960477)                                                         | [CVE-2009-0087](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0087)     | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码         | 由于具有多个代码路径，这是一个复杂的漏洞。 大多数漏洞检测代码度将产生不一致的结果。 默认的缓解因素可抵御此媒介。                                   |  
| [MS09-010](https://technet.microsoft.com/security/bulletin/ms09-010) | 写字板和 Office 文本转换器中的漏洞可能允许远程执行代码 (960477)                                                         | [CVE-2009-0088](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0088)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | 此漏洞可利用，但只影响较旧版本以及较旧的特殊文件格式。 较新版本如 2007 Microsoft Office 系统和 Microsoft Office 2003 Service Pack 3 不会受到影响。 |  
| [MS09-010](https://technet.microsoft.com/security/bulletin/ms09-010) | 写字板和 Office 文本转换器中的漏洞可能允许远程执行代码 (960477)                                                         | [CVE-2009-0235](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0235)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | 此内存损坏漏洞可被轻松利用。                                                                                                                       |  
| [MS09-011](https://technet.microsoft.com/security/bulletin/ms09-011) | Microsoft DirectShow 中的漏洞可能允许远程执行代码 (961373)                                                              | [CVE-2009-0084](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0084)     | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码         | （无）                                                                                                                                             |  
| [MS09-012](https://technet.microsoft.com/security/bulletin/ms09-012) | Windows 中的漏洞可能允许特权提升 (959454)                                                                               | [CVE-2008-1436](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-1436)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | **此漏洞当前正在 Internet 生态系统中被利用。**                                                                                                     |  
| [MS09-012](https://technet.microsoft.com/security/bulletin/ms09-012) | Windows 中的漏洞可能允许特权提升 (959454)                                                                               | [CVE-2009-0078](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0078)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | **此漏洞当前正在 Internet 生态系统中被利用。**                                                                                                     |  
| [MS09-012](https://technet.microsoft.com/security/bulletin/ms09-012) | Windows 中的漏洞可能允许特权提升 (959454)                                                                               | [CVE-2009-0079](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0079)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | **此漏洞当前正在 Internet 生态系统中被利用。**                                                                                                     |  
| [MS09-012](https://technet.microsoft.com/security/bulletin/ms09-012) | Windows 中的漏洞可能允许特权提升 (959454)                                                                               | [CVE-2009-0080](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0080)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | **此漏洞当前正在 Internet 生态系统中被利用。**                                                                                                     |  
| [MS09-013](https://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP 服务中的漏洞可能允许远程执行代码 (960803)                                                                  | [CVE-2009-0086](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0086)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | 这是一个容易控制的内存漏洞，由于此技术的广泛应用，提供多个攻击媒介和利用机会。                                                                     |  
| [MS09-013](https://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP 服务中的漏洞可能允许远程执行代码 (960803)                                                                  | [CVE-2009-0089](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0089)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | 漏洞检测工具已公开                                                                                                                                 |  
| [MS09-013](https://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP 服务中的漏洞可能允许远程执行代码 (960803)                                                                  | [CVE-2009-0550](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)\*\* | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | 漏洞检测代码已公开。                                                                                                                               |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 的累积性安全更新 (963027)                                                                             | [CVE-2008-2540](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的功能漏洞检测代码 | 目前不存在此问题的已知攻击媒介，因为此漏洞要求另一个应用程序允许在用户不知情的情况下将文件保存在系统上。                                           |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 的累积性安全更新 (963027)                                                                             | [CVE-2009-0550](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)\*\* | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | 漏洞检测代码已公开。                                                                                                                               |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 的累积性安全更新 (963027)                                                                             | [CVE-2009-0551](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0551)     | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码         | （无）                                                                                                                                             |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 的累积性安全更新 (963027)                                                                             | [CVE-2009-0552](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0552)     | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的功能漏洞检测代码 | Internet Explorer 7 阻止代码执行的缓解因素。 如果没有更新应用所有的安全更新，则 Internet Explorer 6 以及早期版本被利用的几率将更高。               |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 的累积性安全更新 (963027)                                                                             | [CVE-2009-0553](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0553)     | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的功能漏洞检测代码 | （无）                                                                                                                                             |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 的累积性安全更新 (963027)                                                                             | [CVE-2009-0554](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0554)     | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码           | （无）                                                                                                                                             |  
| [MS09-015](https://technet.microsoft.com/security/bulletin/ms09-015) | SearchPath 中的混合威胁漏洞可能允许特权提升 (959426)                                                                    | [CVE-2008-2540](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码         | 攻击详细信息已公开。                                                                                                                               |  
| [MS09-016](https://technet.microsoft.com/security/bulletin/ms09-016) | Microsoft ISA Server 和 Forefront Threat Management Gateway (Medium Business Edition) 中的漏洞可能导致拒绝服务 (961759) | [CVE-2009-0077](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0077)     | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的功能漏洞检测代码 | 很有可能发生基于服务的拒绝服务。 但是，不可能发生代码执行。                                                                                        |  
| [MS09-016](https://technet.microsoft.com/security/bulletin/ms09-016) | Microsoft ISA Server 和 Forefront Threat Management Gateway (Medium Business Edition) 中的漏洞可能导致拒绝服务 (961759) | [CVE-2009-0237](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-0237)          | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的功能漏洞检测代码 | 可能导致信息泄露。 极不可能发生代码执行。                                                                                                          |
  
\*这对分配了相同的 CVE 编号的漏洞在两个安全更新中已被解决了。 有关详细信息，请参阅各自公告。
  
\*\*这对分配了相同的 CVE 编号的漏洞在两个安全更新中已被解决了。 有关详细信息，请参阅各自公告。
  
受影响的软件和下载位置  
----------------------
  
<span></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
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
<th>  
</th>  
</tr>  
<tr>  
<th colspan="7" style="border:1px solid black;">  
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
（没有严重等级）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=552d322a-5282-42c7-9c1e-1d8c494a7318)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=39d5468e-5733-4c3e-9e75-3adac8ac8cb9)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 8.1](https://www.microsoft.com/download/details.aspx?familyid=0ec5b7c7-13d3-467a-b24e-3cc6fb47adf6)  
（严重）  
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=8b98ed5c-a3ab-45a7-a61e-349eae304bc6)\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=7799fd05-5b26-449f-8a14-50227c9164d1)  
（严重）  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87f0c380-5c31-4099-a6a9-c12f9d69b03b)  
（严重）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=52b756e7-636f-4d9e-8a17-dbf467bfbe4d)  
(KB952004)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=c4e408d7-6716-4a12-ad3a-8029667f5c84)  
（没有严重等级）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=50a8519a-503e-43dd-a78a-c1bc764fd213)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=35af4151-1858-4c9a-85e4-9ff45feca1a4)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=feb5d821-f210-40e8-b1aa-2ca3170df8df)\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=052c29fc-e8df-402c-9ab1-1079bc738e1b)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=55d6729a-9f96-4da4-b564-676c0a0c9390)  
（严重）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=90fe715e-8190-43e9-9c43-df5be564d923)  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=73d2324f-be59-4b0c-b1ac-9876a13c2c03)  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3de0684d-605c-489b-bdc7-08bce9b2d4f6)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=49b16f0f-f6c3-4ca8-8041-392f4f7b5bbb)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=f1be8b7c-4874-4342-99b3-76ff725fbb9a)\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=84c62211-2e82-4ccc-9f9b-26462b026d86)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=191c2f20-89ae-4e1c-bdd4-24b4abfe6b6c)  
（严重）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a794c32a-9a0c-47d9-9c57-ff5d4a8e4944)  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b2f12ae5-0e46-47e1-ac5b-93550d030189)  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b743a7fe-7bf4-420d-a72e-39471e5659fa)  
（中等）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2233a4d2-7c8a-4c89-b020-100d9afb43c8)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=42509f5a-d0f9-444a-9445-5eabdb555011)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=c1b4cd76-1dd6-43fa-bb9a-20c428985bfd)\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=f73a3669-c17f-4b18-8456-96cb7d52ed86)  
（重要）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6a45dbd0-0520-4d9b-b76e-3f5109dd310d)  
（重要）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=25adec10-db8c-4cac-bf74-2c784678150a)  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=42aba890-8b76-4c5a-8fb6-609797d19831)  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=992bb0cd-fbc7-4a7c-9088-f7f9d9a3ead0)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7373ea32-bc2e-49f1-8b9f-4eeda5acc74c)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=f0e1e1db-94a5-451c-ab11-6b431fa065f1)\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=03a9d581-2bd5-4151-9826-17b96e16f606)  
（重要）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=60ccc1d6-ea31-420c-b630-d7878a8dc527)  
（重要）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b014c399-f404-4cb2-8f9d-864df382efeb)  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a0609f65-82d9-4d82-9f48-f3266e8de123)  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f0a58e8c-7d63-4d7d-ba95-b3787cf408f0)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e840b9cb-f1f4-482a-aa07-eb6b42b477c4)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=05e33cc5-cff6-4c71-be71-285f66a95e01)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=8f36c215-fa8a-40c2-b680-6b1fece03b8d)\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=53d13c07-80b0-4f05-b372-a2dac17e6157)  
（重要）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0abaa2fb-7c4f-4149-993d-1575888bfc84)  
（重要）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=6ada372b-ba17-433e-b022-d2c57b35af8a)  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=fda8837c-e5d2-4489-9b44-4c24a1102e77)  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=00c6479d-f81f-445d-b8e4-7b71d77d540a)  
（中等）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f071d770-3b6b-4040-9911-d4de8cde4c68)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d743849d-f3b5-4114-adef-ade2716d55ac)  
（严重）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f111b99a-e555-4f29-8d1f-e9ec03d5cf1f)  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d0ea1598-45cb-4c79-8945-caae98969675)  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2b672d45-f33b-4edc-9f22-2f2c8c726a8b)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7ceef2d0-f316-48d1-aecc-d74f91cc5e1f)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d191c8dc-a965-4a6a-b6d8-1470505eb55f)  
（严重）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=fa153bdc-6b48-4df2-9e5e-abacd6da782c)  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6dd82f4b-bb33-41ec-90a7-9ef91329b240)  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7576e7d5-5bb1-4a53-b568-1ee0500ce721)  
（中等）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=4c36548f-c8c9-4318-91e2-9e0501339548)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e2c6313c-3ba9-4f7c-b259-b4582a390146)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=9e3c7b52-65a7-42fb-beb5-1b374934737f)\*  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=d58702af-bbf8-4f1b-ae72-ced9ef23d581)\*  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=6b73cf5e-66fe-4b7d-95fc-91a1c262c1e5)\*  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1c3f0997-a8a9-4340-ae0c-2c4d6792c65c)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ebbade9d-704c-440b-8796-6d64225ac01a)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=eebb4d4d-29d2-4247-8cbb-63a3b17585ec)\*  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=20bf4e9b-909b-4bc3-ae43-322d74a4f1c3)\*  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7e60847c-b341-4c38-bc25-2e3cf2d4ae14)\*  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=0885b3b0-b78e-4980-902d-dff3886bcaac)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1b04aa6f-b787-4122-bf82-0d150618fe7a)  
（重要）
</td>
<td style="border:1px solid black;">
MSDTC 事务处理设备更新：  
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=cc383c24-b0f6-47c1-9e89-6a378b09e82f)  
(KB952004)  
（重要）  
Windows 服务隔离更新：  
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=bcc2b18f-67db-4109-a9f4-764f985423ee)  
(KB956572)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=de1c2b4b-af47-4b9a-8363-720e5527573c)  
（中等）
</td>
</tr>
</table>

**Windows Server 2008 的注释**

**\*Windows Server 2008 服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 的受支持版本，严重等级相同，无论安装 Windows Server 2008 时是否使用“服务器核心”安装选项。 有关该安装选项的详细信息，请参阅[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*Windows Server 2008 服务器核心安装不受影响。** 如果安装 Windows Server 2008 时使用“服务器核心”安装选项，则此更新所解决的漏洞不会影响 Windows Server 2008 的受支持版本。 有关该安装选项的详细信息，请参阅[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS09-010 注释**

另请参阅 **Microsoft Office 套件和软件**一节，了解更多更新文件。 此公告涉及 Windows 操作系统和组件以及 Microsoft Office 套件和软件。

**MS09-011 注释**

\*\*\*DirectX 9.0 的更新也适用于 DirectX 9.0a、DirectX 9.0b 和 DirectX 9.0c。

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
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 套件、系统和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](https://technet.microsoft.com/security/bulletin/ms09-009)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=95876927-e612-414c-bdec-3632a3100415)  
(KB921606)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3dc8b670-25a5-4f46-b7de-12bc693b628a)  
(KB959964)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e1db55c6-78fb-498d-89a5-9ad54d971546)  
(KB933399)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9a52bf4b-05f6-4b73-94b9-28ed7e20f86c)  
(KB959988)  
（重要）
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
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d9dbfa63-c0cb-4c84-9b8a-6e52568045b0)  
(KB959995)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=50d8630b-1365-4007-81a0-18c0d6d4b86e)\*  
(KB959997)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](https://technet.microsoft.com/security/bulletin/ms09-009)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=52271140-89be-4b9c-baa2-cea09097d703)  
(KB968695)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=f6e407eb-11a5-433f-8006-4b822953ca98)  
(KB968694)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](https://technet.microsoft.com/security/bulletin/ms09-009)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c72e6087-b48f-4d2d-8366-01d9f5ff6b6c)  
(KB959993)  
（重要）  
[Microsoft Office Excel Viewer](https://www.microsoft.com/download/details.aspx?familyid=58b3929c-5373-47a4-aa97-66d179758792)  
(KB960000)  
（重要）
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
[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=05f7c517-e551-4dcd-b24a-5d548f2d09cf)  
(KB960003)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](https://www.microsoft.com/download/details.aspx?familyid=d763fae3-b2af-47f9-a554-ec786766b3c3)  
(KB960476)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**MS09-010 注释**

另请参阅 **Windows 操作系统和组件**部分了解更多更新文件。 此公告涵盖 Windows 操作系统和组件及 Microsoft 服务器软件。

**MS09-009 注释**

\*对于 Microsoft Office Excel 2007 Service Pack 1，客户还需要安装用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 1 的安全更新，以免受本公告中所描述的漏洞影响。

#### Microsoft 服务器和安全软件

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
Microsoft Forefront
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-016**](https://technet.microsoft.com/security/bulletin/ms09-016)
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
Microsoft Forefront Threat Management Gateway
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Threat Management Gateway, Medium Business Edition](https://www.microsoft.com/download/details.aspx?familyid=6abf9fb4-42d0-4c67-935f-8dc67850148b)\*  
(KB968075)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Internet Security and Acceleration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-016**](https://technet.microsoft.com/security/bulletin/ms09-016)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=adf623fa-2d74-4f2a-9835-4b8debdb0e1b)\*\*  
(KB960995)  
（重要）  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d1d55ab6-3de5-4811-9693-8d43f49f5fe8)  
(KB960995)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](https://www.microsoft.com/download/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c77)  
(KB968078)  
（重要）  
[Microsoft Internet Security and Acceleration Server 2006 可支持性更新](https://www.microsoft.com/download/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c77)  
(KB968078)  
（重要）  
[Microsoft Internet Security and Acceleration Server 2006 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c77)  
(KB968078)  
（重要）
</td>
</tr>
</table>

**MS09-016 注释**

\*Microsoft Forefront Threat Management Gateway, Medium Business Edition 作为独立产品和 Windows Essential Business Server 2008 的组件交付。

\*\*Microsoft ISA Server 2004 Standard Edition 作为独立产品交付。 Microsoft ISA Server 2004 Standard Edition 还作为 Windows Small Business Server 2003 Enterprise Edition Service Pack 1 和 Windows Small Business Server 2003 R2 Enterprise Edition 的组件交付。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)和 [Office Update](https://go.microsoft.com/fwlink/?linkid=21135) 获得。 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS) 和扩展安全更新清单工具 (ESUIT)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](https://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](https://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](https://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft Baseline Security Analyzer 和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](https://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 中包含的[更新兼容性评估程序](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [Microsoft Windows 之外的其他 Microsoft 产品的新更新、经过修订的更新以及已发布的更新](https://technet.microsoft.com/en-us/wsus/dd573344.aspx)。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://www.microsoft.com/security/msrc/mapp/partners.mspx)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   [Fortinet FortiGuard Global Security Research Team](https://www.fortiguardcenter.com/) 的 Haifei Li 报告了 ms09-009 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Sean Larsson 和 Jun Mao 报告了 MS09-010 中描述的问题
-   Fortinet [FortiGuard Global Security Research Team](https://www.fortiguardcenter.com/) 的一位研究人员报告了 MS09-010 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的一位研究人员报告了 MS09-010 中描述的问题
-   [Kryptos Logic](https://www.kryptoslogic.com/) 的 Piotr Bania 报告了 MS09-011 中描述的问题
-   [Argeniss](https://www.argeniss.com/) 的 Cesar Cerrudo 报告了 MS09-012 中描述的问题
-   [iSIGHT Partners Labs](https://www.isightpartners.com/) 的 Greg MacManus 报告了 MS09-013 中描述的问题
-   [Google Inc.](https://www.google.com/) 的 Wan-Teh Chang 和 Cem Paya 报告了 MS09-013 中描述的问题
-   [Aviv Raff](https://aviv.raffon.net/) 报告了 MS09-014 中描述的问题
-   [Google Inc.](https://www.google.com/) 的 Michal Zalewski 报告了 MS09-014 中描述的问题
-   [iSIGHT Partners Labs](https://www.isightpartners.com/) 的 Ivan Fratric 报告了 MS09-014 中描述的问题
-   [Google Inc.](https://www.google.com/) 的 Skylined 报告了 MS09-014 中描述的问题
-   [VenusTech](https://www.venustech.com.cn/) 的 ADLab 报告了 MS09-014 中描述的问题
-   [Aviv Raff](https://aviv.raffon.net/) 报告了 MS09-015 中描述的问题
-   纽约州首席信息官/技术办公室报告了 MS09-016 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/default.aspx?ln=zh-cn)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2009 年 4 月 14 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
