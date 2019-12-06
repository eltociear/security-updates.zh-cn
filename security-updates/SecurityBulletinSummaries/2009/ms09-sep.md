---
TOCTitle: 'MS09-SEP'
Title: 'Microsoft 安全公告摘要 (2009 年 9 月)'
ms:assetid: 'ms09-sep'
ms:contentKeyID: 61236938
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms09-sep(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2009 年 9 月)
=====================================

发布时间: 2009年9月8日

**版本:** 1.0

本公告摘要列出了 2009 年 9 月发布的安全公告。

对于 2009 年 9 月发布的安全公告，本公告摘要替代 2009 年 9 月 3 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2009 年 9 月 9 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 9 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407486&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-045">MS09-045</a></td>
<td style="border:1px solid black;"><strong>JScript 脚本引擎中的漏洞可能允许远程执行代码 (971961)</strong><br />
<br />
此安全更新可解决 JScript 脚本引擎中一个秘密报告的漏洞，如果用户打开特制文件、访问特制网站或调用格式错误的脚本，此漏洞可能允许远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-049">MS09-049</a></td>
<td style="border:1px solid black;"><strong>无线局域网 AutoConfig 服务中的漏洞可能允许远程执行代码 (970710)</strong><br />
<br />
此安全更新解决无线局域网 AutoConfig 服务中一个秘密报告的漏洞。 如果启用了无线网络接口的客户端或服务器收到特制的无线帧，该漏洞可能允许远程执行代码。 未启用无线卡的系统不受此漏洞的威胁。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-047">MS09-047</a></td>
<td style="border:1px solid black;"><strong>Windows Media Format 中的漏洞可能允许远程执行代码 (973812)</strong><br />
<br />
此安全更新可解决 Windows Media Format 中两个秘密报告的漏洞。 如果用户打开特制媒体文件，这两个漏洞可能允许远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-048">MS09-048</a></td>
<td style="border:1px solid black;"><strong>Windows TCP/IP 中的漏洞可能允许远程执行代码 (967723)</strong><br />
<br />
此安全更新可解决传输控制协议/Internet 协议 (TCP/IP) 中多个秘密报告的漏洞。 如果攻击者通过网络向具有监听服务的计算机发送特制的 TCP/IP 包，这些漏洞可能允许远程执行代码。 采用防火墙最佳做法和标准的默认防火墙配置，有助于保护网络免受从企业外部发起的攻击。 按照最佳做法，应使连接到 Internet 的系统所暴露的端口数尽可能少。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-046">MS09-046</a></td>
<td style="border:1px solid black;"><strong>DHTML 编辑组件 ActiveX 控件中的安全漏洞可能允许远程执行代码 (956844)</strong><br />
<br />
此安全更新解决 DHTML 编辑组件 ActiveX 控件中的一个秘密报告的漏洞。 攻击者可以通过构建特制的网页来利用该漏洞。 当用户查看网页时，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID 和 CVE ID 的排序列出。
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 公告标题                                                             | CVE ID                                                                           | 利用指数评估                                                                                      | 重要注意事项                                                        |  
|---------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|  
| [MS09-045](http://technet.microsoft.com/security/bulletin/ms09-045) | JScript 脚本引擎中的漏洞可能允许远程执行代码 (971961)                | [CVE-2009-1920](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1920) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                              |  
| [MS09-046](http://technet.microsoft.com/security/bulletin/ms09-046) | DHTML 编辑组件 ActiveX 控件中的安全漏洞可能允许远程执行代码 (956844) | [CVE-2009-2519](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2519) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                              |  
| [MS09-047](http://technet.microsoft.com/security/bulletin/ms09-047) | Windows Media Format 中的漏洞可能允许远程执行代码 (973812)           | [CVE-2009-2498](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2498) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                              |  
| [MS09-047](http://technet.microsoft.com/security/bulletin/ms09-047) | Windows Media Format 中的漏洞可能允许远程执行代码 (973812)           | [CVE-2009-2499](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2499) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                              |  
| [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) | Windows TCP/IP 中的漏洞可能允许远程执行代码 (967723)                 | [CVE-2008-4609](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4609) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是拒绝服务的内存消耗类型。                                        |  
| [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) | Windows TCP/IP 中的漏洞可能允许远程执行代码 (967723)                 | [CVE-2009-1925](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1925) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 漏洞检测代码可能实现但不太可能可靠地利用。 拒绝服务是更可能的结果。 |  
| [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) | Windows TCP/IP 中的漏洞可能允许远程执行代码 (967723)                 | [CVE-2009-1926](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1926) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是拒绝服务的内存消耗类型。                                        |  
| [MS09-049](http://technet.microsoft.com/security/bulletin/ms09-049) | 无线局域网 AutoConfig 服务中的漏洞可能允许远程执行代码 (970710)      | [CVE-2009-1132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1132) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 堆保护使此漏洞难以可靠地利用。                                      |
  
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
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
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
[JScript 5.1 和 JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=2bb3af8d-f36c-4497-9f48-fc59bcff2583)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.0](https://www.microsoft.com/download/details.aspx?familyid=02b9dc42-38c2-44b1-a77c-34854f4a86c4)  
(KB968816)  
（严重）
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4<sup>[3]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=6dd4b0f8-6b54-49a6-a6df-9420f9fd3333)  
（严重）
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
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
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
无
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
[Windows XP Service Pack 2 上的 JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=0af373b2-2240-4079-a748-a38d1bc06f39)  
（严重）  
[Windows XP Service Pack 2 上的 JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a)<sup>[1]</sup>  
（严重）  
[Windows XP Service Pack 3 上的 JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a)  
（严重）  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=992602d8-d857-41cf-b7b1-527afdc1dc0f)<sup>[2]</sup>  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.0、Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=6ffc081e-f892-4818-acb9-6d79e15d473c)  
(KB968816)  
（严重）  
（仅限 Windows XP Service Pack 2）  
[Windows Media Format Runtime 9.0、Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=31585f5a-9aaa-40da-b15a-11284b4b800c)  
(KB968816)  
（严重）  
（仅限 Windows XP Service Pack 3）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8523d5be-88a2-4124-9b02-660f612e2a12)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=0d671004-da4e-4dbd-a066-861b53b0c59c)  
（严重）  
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=9aae426d-ee9a-4736-b0a2-e0f8890a6895)<sup>[1]</sup>  
（严重）  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=00bae02a-64eb-4b91-965f-da2dc987a2ff)<sup>[2]</sup>  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=3780d565-d027-4f54-8fc0-05f5c3c6ba1a)  
(KB968816)  
（严重）  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ce515188-db3c-4694-85da-177c8f76b68c)  
(KB968816)  
（严重）  
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=9a465f92-3067-4a5a-9882-1fc2cf796c99)  
(KB968816)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dbc33f6b-61bf-409a-89b5-60002192e0e0)  
（严重）
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
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
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
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=6acc9d2d-b71f-4b5c-9aea-b217b6ae240b)  
（严重）  
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=6af5d034-fd89-42e2-bc18-d44b7a6b0a85)<sup>[1]</sup>  
（严重）  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=ecf9f7e2-3104-4de2-8b3d-99dcdcae6e62)<sup>[2]</sup>  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=4ab34e3d-34cb-4e35-a2da-b348ace8a8f7)  
(KB968816)  
（严重）  
[Windows Media Services 9.1](https://www.microsoft.com/download/details.aspx?familyid=61cd0581-c36e-4da6-ae95-41609adbe922)  
(KB972554)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=48d82036-2fde-4bb0-a60e-92eed83ddc3f)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7478f73f-dd20-4cfa-a650-4c84f37ada2f)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=d0de3ab1-73e9-4a09-841f-81ade41a8c81)  
（严重）  
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=8f48bc05-ffac-4a21-8d21-dd20355cda8a)<sup>[1]</sup>  
（严重）  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=643f9e2f-2e5b-48dd-b1a0-22ccb633ed18)<sup>[2]</sup>  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=8654ee33-6083-447f-ae5b-43ef8d8b613d)  
(KB968816)  
（严重）  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ce515188-db3c-4694-85da-177c8f76b68c)  
(KB968816)  
（严重）  
[Windows Media Services 9.1](https://www.microsoft.com/download/details.aspx?familyid=67c46f26-e6df-4ba2-9c03-1590b31e454c)  
(KB972554)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e0298ddf-026e-4137-8197-ed9d9b889825)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=88bf502d-1a7c-447a-ac4c-401e1698669b)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[JScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=e78cf021-54f5-4526-b5f0-f781aebf9d72)  
（严重）  
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=fb1ca290-cea4-49c0-a37e-613a654bff3c)<sup>[1]</sup>  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=c948c4d8-5788-4c1a-9fb6-a969b06a888d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=8d881ff8-f51f-4476-8cb6-2bebd5b2047f)  
（中等）
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
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
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
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=bcb12e57-f5d6-4b4e-88ab-13c28137f11a)  
（严重）  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=80e7390f-df39-4d99-b2e1-01c7f6a951bb)<sup>[2]</sup>  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e9fe967f-d78d-43c2-bbcc-5098bd20267e)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 和 Microsoft Media Foundation](https://www.microsoft.com/download/details.aspx?familyid=d2bdefcc-f6b9-47c3-a55d-a4f33f967828)  
(KB968816)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7d72f845-9feb-4685-a669-f9d6ab54f9ed)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=8b1b76d5-a6b0-4c2f-8768-e55e82c2c118)  
（严重）  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=24457cdd-1973-40c9-9c2d-c1a75fdfa7fa)<sup>[2]</sup>  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f93470bd-2e6d-4340-88c6-bb212baf750a)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 和 Microsoft Media Foundation](https://www.microsoft.com/download/details.aspx?familyid=97f00b25-fb8f-4300-80c0-c63179f32182)  
(KB968816)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b2930ff1-5f0a-4a5d-bf2a-9fb76dd8da63)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
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
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
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
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=df88e6e5-78d3-4fa6-858d-b935d812cada)\*  
（严重）  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=e7b07be6-a4f8-4847-9c55-9b3d2965fa77)\*,<sup>[2]</sup>  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ac3f6800-bc3e-4b35-a482-54e1a2da1ab5)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 和 Microsoft Media Foundation](https://www.microsoft.com/download/details.aspx?familyid=9c111bff-aff6-4ff7-81f6-e736cfcbe3ed)\*\*  
(KB968816)  
（严重）  
[Windows Media Services 2008](https://www.microsoft.com/download/details.aspx?familyid=2801f69b-37d0-4d0f-9632-31382b824d36)\*  
(KB972554)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=35c1d5a9-a953-4fc6-90c0-d2358c7b89e6)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=f584f8ca-f6b1-4285-a44c-3df5e51e75de)\*  
（严重）  
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=9eddbb89-4178-49c2-836a-2d292fe50936)\*,<sup>[2]</sup>  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7d1b9b4f-bf35-44aa-a660-afb2ef2c9e30)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 和 Microsoft Media Foundation](https://www.microsoft.com/download/details.aspx?familyid=59615c8b-a07f-4326-836d-f17b2fcc4695)\*\*  
(KB968816)  
（严重）  
[Windows Media Services 2008](https://www.microsoft.com/download/details.aspx?familyid=7fad3793-174f-46db-9d0a-873a0ea8be65)\*  
(KB972554)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6e46822e-f79d-492d-ad01-ee680ad324f5)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=b84fca1d-914d-45af-a48c-d9bc5d20c6b7)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2ac76ee2-b1b6-4300-9cba-af33d9dd54eb)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**Windows Server 2008 的注释**

**\*Windows Server 2008 服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 的受支持版本，严重等级相同，无论安装 Windows Server 2008 时是否使用“服务器核心”安装选项。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*Windows Server 2008 服务器核心安装不受影响。** 如果安装 Windows Server 2008 时使用“服务器核心”安装选项，则此更新所解决的漏洞不会影响 Windows Server 2008 的受支持版本。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS09-045 注释**

<sup>[1]</sup>在安装了 Internet Explorer 7 的系统上

<sup>[2]</sup>在安装了 Internet Explorer 8 的系统上

**MS09-048 注释**

<sup>[3]</sup> 无更新。 有关详细信息，请参阅 [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) 中的**与此安全更新相关的常见问题 (FAQ)** 条目。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**注意** 从 2009 年 8 月 1 日起，Microsoft 将不再对 Office Update 和 Office Update 清单工具提供支持。 要继续获得 Microsoft Office 产品的最新更新，请使用 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)。 有关详细信息，请参阅[关于 Microsoft Office Update： 常见问题](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。 该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。 有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用安全更新清单工具 (SUIT) 来帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

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

-   [team509](http://www.team509.com/) 的 Wushi 与 Zero Day Initiative 合作，报告了 MS09-045 中描述的问题
-   [Google Inc.](http://www.google.com/) 的 Tavis Ormandy 报告了 MS09-046 中描述的问题
-   [NGS Software](http://www.ngssoftware.com/) 的 Peter Winter-Smith 报告了 MS09-047 中所述的问题。
-   Alice Carroll 爱好者俱乐部的 Hiroshi Noguchi 报告了 MS09-047 中描述的问题
-   [Outpost24](http://www.outpost24.com/) 的 Jack C. Louis 报告了 MS09-048 中描述的问题
-   [Recurity Labs GmbH](http://www.recurity-labs.com/) 的 Felix Lindner 报告了 MS09-048 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/default.aspx?ln=zh-cn)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2009 年 9 月 8 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
