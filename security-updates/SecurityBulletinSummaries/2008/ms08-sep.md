---
TOCTitle: 'MS08-SEP'
Title: 'Microsoft 安全公告摘要 (2008 年 9 月)'
ms:assetid: 'ms08-sep'
ms:contentKeyID: 61236926
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms08-sep(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2008 年 9 月)
=====================================

发布时间: 2008年9月9日

**版本:** 1.0

本公告摘要列出了 20078 年 9 月发布的安全公告。

对于 2008 年 9 月发布的安全公告，本公告摘要替代 2008 年 9 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2008 年 9 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 9 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374633&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (4)
--------


| 公告标识符       | Microsoft 安全公告 MS08-054                                                                                                                                                                                                                                                                                                                                                                |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Media Player 中的漏洞可能允许远程执行代码 (954154)**](http://technet.microsoft.com/security/bulletin/ms08-054)                                                                                                                                                                                                                                                                  |
| **摘要**         | 此安全更新解决了 Windows Media Player 中一个秘密报告的漏洞，当从 Windows Media 服务器流式传输特制音频文件时，该漏洞可能导致远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                       |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                                               |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                                                                         |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                                 |

| 公告标识符       | Microsoft 安全公告 MS08-052                                                                                                                                                                                                                          |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**GDI+ 中的漏洞可能允许远程执行代码 (954593)**](http://technet.microsoft.com/security/bulletin/ms08-052)                                                                                                                                            |
| **摘要**         | 此安全更新可解决 Microsoft Windows GDI+ 中许多秘密报告的漏洞。 如果用户使用受影响的软件查看特制图像文件或浏览包含特制内容的网站，则这些漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                 |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                         |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                                     |
| **受影响的软件** | **Microsoft Windows、Internet Explorer、.NET Framework、Office、SQL Server、Visual Studio。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                     |

| 公告标识符       | Microsoft 安全公告 MS08-053                                                                                                                                                                                                                                                                                                                                                  |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Media Encoder 9 中的漏洞可能允许远程执行代码 (954156)**](http://technet.microsoft.com/security/bulletin/ms08-053)                                                                                                                                                                                                                                                 |
| **摘要**         | 此安全更新解决了 Windows Media Encoder 9 Series 中一个秘密报告的漏洞。 如果用户查看了特制网页，此漏洞可能允许远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                         |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                                 |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                                                                                                                                                         |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                   |

| 公告标识符       | Microsoft 安全公告 MS08-055                                                                                                                                                                                                                                                                                                              |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Office 中的漏洞可能允许远程执行代码 (955047)**](http://technet.microsoft.com/security/bulletin/ms08-055)                                                                                                                                                                                                                    |
| **摘要**         | 此安全更新解决了 Microsoft Office 中一个秘密报告的漏洞。 如果用户点击特制的 OneNote URL，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                     |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                             |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 大多数情况下，此更新不需要重新启动。                                                                                                                                                                                                                         |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                |

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
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a860d2d9-653d-4ddb-bbff-323d3ccdb866)  
(KB938464)  
（严重）  
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c7cbcd19-acc1-4a89-adfa-99b2f431510d)  
(KB947739)  
（没有严重等级）  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6013f866-3ea1-4672-b1bf-e516204c3a7a)  
(KB947742)  
（没有严重等级）  
[Microsoft .NET Framework 2.0](https://www.microsoft.com/download/details.aspx?familyid=7f1cd013-2c4b-4582-9114-cb840a96124a)  
(KB947746)  
（没有严重等级）  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=215b73a3-46ab-44a8-a0fb-6d37bd1c39b8)  
(KB947748)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=0cabfbc0-db5d-4a6a-a4cd-e6df89ac2b25)  
（严重）
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高严重等级**
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
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=d5891180-5dd1-49ec-bcc6-3030a544202c)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e0bd6fbe-f46e-4961-9a79-49ec77d39439)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=57bcb3c2-49d3-4f18-8d03-36abd03d7403)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=caf8a45e-a9f8-4e91-98fd-87eddbeae64c)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c5d26771-1f49-4bbf-902c-bf92e527cadb)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=18efea9e-b103-46de-90d9-5e295854cec3)  
（严重）  
[Windows Media Encoder 9 Series x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=ebc1737c-6e78-4244-a1b2-a56d031f16e9)  
（严重）
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高严重等级**
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ac03f138-eca4-46e1-9782-e811820e547f)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=54ce1080-94cf-4e4f-8e09-a7dbab2757c5)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=93f1451b-5b62-47e5-8f0c-b720b957999a)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=c83011cd-90b8-494c-9cad-fa055e101992)  
（中等）  
[Windows Media Encoder 9 Series x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=d8f1b782-136b-443f-b5f2-63aa4d1fd94a)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=14e99f8a-cdd4-40d7-8cfc-73ae6bd6dfad)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=2f4118fd-1ffb-46da-b922-cd4ca4f9d84e)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=16f3ad21-ed77-4c32-93df-3b650b2b32a5)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=334352e7-d41f-494f-866d-f1f1745ffd17)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=aa47d016-f5c9-4586-8876-f1f4f255f54d)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
（严重）  
[Windows Media Encoder 9 Series x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=54d1279a-7f26-4727-a39d-5505bcd4fc53)  
（严重）
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://technet.microsoft.com/security/bulletin/ms08-054)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://technet.microsoft.com/security/bulletin/ms08-053)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=72fc6028-6af4-44ec-8d2a-28c53807d6bc)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=23bd3be5-cc66-46f8-9420-49d65d8afe1d)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=3906512b-26db-473e-b522-3883ff34a21c)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7f1e0f05-6c9d-4ad1-9b19-50ee4fa7bd7e)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](https://www.microsoft.com/download/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
（中等）  
[Windows Media Encoder 9 Series x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=e30f9427-26d0-4e86-b9b8-bc637c3b5734)\*  
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
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=5159bdba-3825-4816-a2be-ab035332b9e2)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**\*Windows Server 2008 服务器核心安装不受影响。** 如果安装 Windows Server 2008 时使用“服务器核心”安装选项，则此更新所解决的漏洞不会影响 Windows Server 2008 的受支持版本。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

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
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://technet.microsoft.com/security/bulletin/ms08-055)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 和 Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
（重要）  
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System 和 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](https://www.microsoft.com/download/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
（重要）
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](https://www.microsoft.com/download/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
（重要）  
[2007 Microsoft Office System Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://technet.microsoft.com/security/bulletin/ms08-055)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高严重等级**
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
Microsoft Visio 2002 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a6d9d3ef-f087-4f61-9ec1-522b7d4b9c48)  
(KB954479)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office PowerPoint Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint Viewer 2003](https://www.microsoft.com/download/details.aspx?familyid=cd503f08-1831-45ff-bdf4-dd918ca40505)  
(KB956500)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](https://www.microsoft.com/download/details.aspx?familyid=eb0d224e-a517-40d9-9fc6-2345fa12a841)  
(KB956483)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Digital Image Suite 2006
</td>
<td style="border:1px solid black;">
[Microsoft Digital Image Suite 2006](https://www.microsoft.com/download/details.aspx?familyid=04afd760-8173-4069-9e82-d3bf053d9eae)  
(KB955992)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office OneNote 2007
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office OneNote 2007](https://www.microsoft.com/download/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
（严重）  
[Microsoft Office OneNote 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
（严重）
</td>
</tr>
</table>


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
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL 2000 Reporting Services Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
不适用  
QFE 更新：  
安装在 Microsoft Windows 2000 Service Pack 4 上的 [SQL 2000 Reporting Services Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5f9e7f78-7439-414b-a9dc-a779b89427db)  
(KB954609)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
（严重）  
QFE 更新：  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
（严重）  
QFE 更新：  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 Service Pack 2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
（严重）  
QFE 更新：  
[SQL Server 2005 Service Pack 2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
（严重）
</td>
</tr>
</table>


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
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2002 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7848a652-4025-44bb-9c98-37a078b56d01)  
(KB947736)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9bc1e8f8-6c30-4aa0-90f5-fbb0ad5fd90e)  
(KB947737)  
（没有严重等级）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a7bf790b-3249-4ee8-9440-fa911ebbc08a)  
(KB947738)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?familyid=a8c80b29-6d00-4949-a005-5d706122919a)  
(KB952241)  
（没有严重等级）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=82833f27-081d-4b72-83ef-2836360a904d)  
(KB954765)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 Redistributable Package
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Report Viewer 2008 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=6ae0aa19-3e6c-474c-9d57-05b2347456b1)  
(KB954766)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 8.0 Service Pack 1
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Visual FoxPro 8.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1f4371b9-b8be-4455-94d2-2304ee340543)  
(KB955368)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 1
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Visual FoxPro 9.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=49b21e30-722d-446e-9020-aceb3870db69)  
(KB955369)  
（没有严重等级）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 2
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Visual FoxPro 9.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=36957f47-9d8b-477d-bd60-5959e5a2eafa)  
(KB955370)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Platform SDK Redistributable: GDI+
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK Redistributable: GDI+](https://www.microsoft.com/download/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
（没有严重等级）
</td>
</tr>
</table>


#### Microsoft 安全软件

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
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://technet.microsoft.com/security/bulletin/ms08-052)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 2000 Service Pack 4 上的 [Microsoft Forefront Client Security 1.0](https://www.microsoft.com/download/details.aspx?familyid=1eb1a79f-44ca-499e-90bb-ac51894e9d1e)  
(KB957177)  
（重要）
</td>
</tr>
</table>


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

-   [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Greg MacManus 报告了 MS08-052 中描述的问题
-   [Fortinet FortiGuard Global Security Research Team](http://www.fortinet.com/) 的 Bing Liu 报告了 MS08-052 中描述的问题
-   [NGSSoftware](http://www.ngssoftware.com/) 的 Peter Winter-Smith 和 Zero [Day Initiative](http://www.zerodayinitiative.com/) 的 Ivan Fratric 合作报告了 MS08-052 中描述的问题
-   [Assurent Secure Technologies 的 Vulnerability Research Team](http://www.assurent.com/)报告了 MS08-052 中描述的问题
-   一名匿名研究员与 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 MS08-052 中描述的问题
-   Nguyen Minh Duc 和 Le Manh Tung 与 [Bach Khoa Internetwork Security Center (BKIS) Hanoi University of Technology (Vietnam)](http://www1.hut.edu.vn/en/index.php?id=69,63,0,0,1,0) 合作报告了 MS08-053 中描述的问题
-   [Insomnia Security](http://www.insomniasec.com/) 的 Brett Moore 报告了 MS08-055 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2008 年 9 月 9 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
