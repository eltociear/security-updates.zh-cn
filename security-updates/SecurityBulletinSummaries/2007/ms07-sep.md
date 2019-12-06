---
TOCTitle: 'MS07-SEP'
Title: 'Microsoft 安全公告摘要 (2007 年 9 月)'
ms:assetid: 'ms07-sep'
ms:contentKeyID: 61236911
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms07-sep(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2007 年 9 月)
=====================================

发布时间: 2007年9月11日 | 更新时间: 2007年9月12日

**版本:** 1.1

本公告摘要列出了 2007 年 9 月发布的安全公告。

对于 2007 年 9 月发布的安全公告，本公告摘要替代 2007 年 9 月 6 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2007 年 9 月 12 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 9 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344690&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (1)
--------

| 公告标识符       | Microsoft 安全公告 MS07-051                                                                                                                                                                                                                              |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Agent 中的漏洞可能允许远程执行代码 (938827)**](https://technet.microsoft.com/security/bulletin/ms07-051)                                                                                                                                     |
| **摘要**         | 此严重安全更新可消除一个秘密报告的漏洞。 Microsoft Agent 由于其处理某些特制 URL 的方式而存在一个远程执行代码漏洞。 该漏洞可能允许攻击者在受影响的系统上远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                     |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                             |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                                                                                                                    |
| **受影响的软件** | **Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                         |

重要事项 (3)
------------

| 公告标识符       | Microsoft 安全公告 MS07-052                                                                                                                                                           |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Crystal Reports for Visual Studio 中的漏洞可能允许远程执行代码 (941522)**](https://technet.microsoft.com/security/bulletin/ms07-052)                                                |
| **摘要**         | 此重要安全更新解决了一个公开披露的漏洞。 如果用户打开特制的 RPT 文件，该漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                  |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                          |
| **检测**         | Microsoft 基准安全分析器和企业更新扫描工具可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                             |
| **受影响的软件** | **Visual Studio。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                |

| 公告标识符       | Microsoft 安全公告 MS07-053                                                                                                                                                                                    |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Services for UNIX 中的漏洞可能允许特权提升 (939778)**](https://technet.microsoft.com/security/bulletin/ms07-053)                                                                                     |
| **摘要**         | 此重要安全更新可解决一个公开报告的漏洞。 Windows Services for UNIX 3.0、Windows Services for UNIX 3.5 和基于 UNIX 的应用程序子系统中存在一个漏洞，在此运行特定的 setuid 二进制文件可能允许攻击者获得特权提升。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                           |
| **漏洞的影响**   | 特权提升                                                                                                                                                                                                       |
| **检测**         | Microsoft 基准安全分析器和企业更新扫描工具可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                                                        |
| **受影响的软件** | **Windows Services for UNIX、基于 UNIX 的应用程序的子系统。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                               |

| 公告标识符       | Microsoft 安全公告 MS07-054                                                                                                                                                                                                                                                              |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**MSN Messenger 和 Windows Live Messenger 中的漏洞可能允许远程执行代码 (942099)**](https://technet.microsoft.com/security/bulletin/ms07-054)                                                                                                                                             |
| **摘要**         | 此安全更新可消除 MSN Messenger 和 Windows Live Messenger 中公开披露的漏洞。 当用户接受攻击者的网络摄像机或视频聊天邀请时，漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                     |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                             |
| **检测**         | 这些产品提供自动检测和部署更新的内部机制。 该更新可能要求重新启动。                                                                                                                                                                                                                      |
| **受影响的软件** | **MSN Messenger、Windows Live Messenger。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                           |

受影响的软件和下载位置
----------------------

**我如何使用该表呢？**

可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果列出了一个软件程序或组件，则会列出漏洞的影响，并且还会使用超链接将其链接到可用的软件更新。

**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

**受影响的软件和下载位置**

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
详细信息        
</th>
<th>
详细信息        
</th>
<th>
详细信息        
</th>
<th>
详细信息        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS07-051**](https://technet.microsoft.com/security/bulletin/ms07-051)
</td>
<td style="border:1px solid black;">
[**MS07-052**](https://technet.microsoft.com/security/bulletin/ms07-052)
</td>
<td style="border:1px solid black;">
[**MS07-053**](https://technet.microsoft.com/security/bulletin/ms07-053)
</td>
<td style="border:1px solid black;">
[**MS07-054**](https://technet.microsoft.com/security/bulletin/ms07-054)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高严重等级**
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows 操作系统
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=7cd248ed-d154-4dce-89ef-ceefd2700965)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows 操作系统组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 2000 Service Pack 4 上的 Windows Services for UNIX 3.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 2000 Service Pack 4 上的 Windows Services for UNIX 3.5
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 上的 Windows Services for UNIX 3.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 上的 Windows Services for UNIX 3.5
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 Windows Services for UNIX 3.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 Windows Services for UNIX 3.5
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的基于 UNIX 的应用程序子系统
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=8ab5cc43-0b9c-45eb-aa51-47568ab6ce3f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的基于 UNIX 的应用程序子系统
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=1d21e3e8-b5f6-4044-9db6-054af836492b)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 上的基于 UNIX 的应用程序子系统
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=4d52e4f4-2888-42df-8163-85c648e65b29)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 上的基于 UNIX 的应用程序子系统
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=4be667cc-c239-480b-a9a0-939bcd27f0de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
开发工具和平台
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2002 Service Pack 1  
(KB937057)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=2608c83b-e1b2-4449-9a0e-1e566aac3d76)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio .NET 2003  
(KB937058)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=d612ad41-5a0d-4e13-99ea-d6a5589786d6)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2003 Service Pack 1  
(KB937059)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=0b10b04b-932c-4bff-9cbc-b3eeb15064b1)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio 2005  
(KB937060)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=21073cc2-919c-40df-8ebb-aa3db06050d2)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio 2005 Service Pack 1  
(KB937061)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=967d43c8-efba-4221-beb0-981e7deef33a)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
受影响的其他软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 MSN Messenger 6.2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 MSN Messenger 7.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2、Windows XP Professional x64 Edition、Windows XP Professional x64 Edition Service Pack 2、Windows Server 2003 Service Pack 1、Windows Server 2003 Service Pack 2、Windows Server 2003 x64 Edition、Windows Server 2003 x64 Edition Service Pack 2、Windows Vista 和 Windows Vista x64 Edition 上的 MSN Messenger 6.2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2、Windows XP Professional x64 Edition、Windows XP Professional x64 Edition Service Pack 2、Windows Server 2003 Service Pack 1、Windows Server 2003 Service Pack 2、Windows Server 2003 x64 Edition、Windows Server 2003 x64 Edition Service Pack 2、Windows Vista 和 Windows Vista x64 Edition 上的 MSN Messenger 7.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2、Windows XP Professional x64 Edition、Windows XP Professional x64 Edition Service Pack 2、Windows Server 2003 Service Pack 1、Windows Server 2003 Service Pack 2、Windows Server 2003 x64 Edition、Windows Server 2003 x64 Edition Service Pack 2、Windows Vista 和 Windows Vista x64 Edition 上的 MSN Messenger 7.5
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2、Windows XP Professional x64 Edition、Windows XP Professional x64 Edition Service Pack 2、Windows Server 2003 Service Pack 1、Windows Server 2003 Service Pack 2、Windows Server 2003 x64 Edition、Windows Server 2003 x64 Edition Service Pack 2、Windows Vista 和 Windows Vista x64 Edition 上的 Windows Live Messenger 8.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
</table>

**备注**

**<sup>[1]</sup>** 此操作系统有一个可用的安全更新。 有关详细信息，请参阅本表中的受影响的软件或组件和相应的安全公告。

**<sup>[2]</sup>** 并非 Visual Studio 的所有版本均受影响。 有关具体的受影响版本列表，请参阅适当的安全公告。

**<sup>[3]</sup>** 还有一个可用于此软件的选项，用于通过 MSN Messenger 或 Windows Live Messenger 服务执行联机升级。 有关详细信息，请参阅相应的安全公告。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)和 [Office Update](https://go.microsoft.com/fwlink/?linkid=21135) 获得。 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过搜索关键字“安全修补程序”，可以非常方便地找到这些更新。 最后，安全更新可从 Windows Update 目录下载。 有关 Windows Update 目录的详细信息，请参阅 [Microsoft 知识库文章 323166](https://support.microsoft.com/kb/323166)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft 基准安全分析器 (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS)、扩展安全更新清单工具以及企业更新扫描工具 (EST)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](https://support.microsoft.com/kb/910723)。

**Microsoft 基准安全分析器和企业 更新扫描工具**

管理员可使用 Microsoft 基准安全分析器 (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft 基准安全分析器](https://go.microsoft.com/fwlink/?linkid=21134)。

当 MBSA 1.2.1 不支持对某特定安全更新的检测时，Microsoft 将为此特定安全更新发行一个企业更新扫描工具 (EST) 版本。 有关 EST 的详细信息，请访问[企业更新扫描工具](https://support.microsoft.com/default.aspx?id=894193)。

**注意** 2007 年 10 月 9 日以后，MBSA 1.2.1 使用的 MSSecure.XML 文件将不再更新。 在此日期后，MBSA 1.2.1 使用的 MSSecure.XML 文件中不会再添加新的安全更新，也不会再发行新版本的“企业扫描工具”。 有关详细信息，请访问 [Microsoft 基准安全分析器](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](https://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](https://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft 基准安全分析器和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](https://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

在本月：

-   Microsoft 未在 Microsoft Update (MU) 和 Windows Server 更新服务 (WSUS) 上发布**非安全**、高优先级更新。
-   Microsoft 未在 Windows Update (WU) 上发布**非安全**、高优先级 Windows 更新。

注意，此信息**仅**适用于 Microsoft Update、Windows Update 和 Windows Server Update Services 上在发布安全公告摘要当天发布的**非安全**、高优先级更新。 并**不**提供关于其他日期发布的**非安全**更新的信息。

#### 安全策略和社区

**更新管理策略**

[安全修补程序管理指南](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳实践建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过搜索关键字“安全修补程序”，可以非常方便地找到这些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   [Assurent Secure Technologies](https://www.assurent.com/) 的漏洞研究小组报告了 [MS07-051](https://technet.microsoft.com/security/bulletin/ms07-051) 中描述的问题
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 [MS07-051](https://technet.microsoft.com/security/bulletin/ms07-051) 中描述的问题
-   一名与 [iDefense VCP](https://labs.idefense.com/) 合作的匿名研究员报告了 [MS07-051](https://technet.microsoft.com/security/bulletin/ms07-051) 中描述的问题
-   WolfeReiter 的 Brian A. Reiter 与我们合作，报告了 [MS07-053](https://technet.microsoft.com/security/bulletin/ms07-053) 中报告的问题
-   [team 509](https://www.team509.com/) 的 Woo Shi 报告了 [MS07-054](https://technet.microsoft.com/security/bulletin/ms07-054) 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](https://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2007 年 9 月 11 日）： 已发布公告摘要。
-   V1.1（2007 年 9 月 12 日）： 已重申重新启动要求，并且已为 MS07-045 添加下载链接。

*Built at 2014-04-18T01:50:00Z-07:00*
