---
TOCTitle: 'MS08-AUG'
Title: 'Microsoft 安全公告摘要 (2008 年 8 月)'
ms:assetid: 'ms08-aug'
ms:contentKeyID: 61236913
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms08-aug(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2008 年 8 月)
=====================================

发布时间: 2008年8月12日

**版本:** 1.0

本公告摘要列出了 2008 年 8 月发布的安全公告。

对于 2008 年 8 月发布的安全公告，本公告摘要替代 2008 年 8 月 7 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2008 年 8 月 13 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 8 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032374631&culture=en-us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (6)
--------


| 公告标识符       | Microsoft 安全公告 MS08-046                                                                                                                                                                                                                                                                                                                                               |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Windows 图像颜色管理系统中的漏洞可能允许远程执行代码 (952954)**](https://technet.microsoft.com/security/bulletin/ms08-046)                                                                                                                                                                                                                                    |
| **摘要**         | 此安全更新解决了 Microsoft 图像颜色管理 (ICM) 系统中一个秘密报告的漏洞，该漏洞可能允许在当前用户的上下文中远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                      |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                              |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                                                                                                                                                          |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                |

| 公告标识符       | Microsoft 安全公告 MS08-045                                                                                                                                                                                                 |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Internet Explorer 的累积性安全更新 (953838)**](https://technet.microsoft.com/security/bulletin/ms08-045)                                                                                                                  |
| **摘要**         | 此安全更新可消除五个秘密报告的漏洞以及一个公开披露的漏洞。 如果用户使用 Internet Explorer 查看特制网页，则所有漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                        |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                            |
| **受影响的软件** | **Microsoft Windows、Internet Explorer。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                               |

| 公告标识符       | Microsoft 安全公告 MS08-041                                                                                                                                                                                                                  |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Snapshot Viewer for Microsoft Access 的 ActiveX 控件中的漏洞可能允许远程执行代码 (955617)**](https://technet.microsoft.com/security/bulletin/ms08-041)                                                                                     |
| **摘要**         | 此安全更新解决 Snapshot Viewer for Microsoft Access 的 ActiveX 控件中一个秘密报告的漏洞。 攻击者可以通过构建特制的网页来利用该漏洞。 当用户查看网页时，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                         |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                 |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                           |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                    |

| 公告标识符       | Microsoft 安全公告 MS08-043                                                                                                                                                                                                                                                                                                                      |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Excel 中的漏洞可能允许远程执行代码 (954066)**](https://technet.microsoft.com/security/bulletin/ms08-043)                                                                                                                                                                                                                             |
| **摘要**         | 此安全更新解决了 Microsoft Office Excel 中四个秘密报告的漏洞，如果用户打开特制的 Excel 文件，则该漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                             |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                     |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                               |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                        |

| 公告标识符       | Microsoft 安全公告 MS08-051                                                                                                                                                                                                                                                                                                                                                                        |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft PowerPoint 中的漏洞可能允许远程执行代码 (949785)**](https://technet.microsoft.com/security/bulletin/ms08-051)                                                                                                                                                                                                                                                                          |
| **摘要**         | 此安全更新解决了 Microsoft Office PowerPoint 和 Microsoft Office PowerPoint Viewer 中三个秘密报告的漏洞，如果用户打开特制的 PowerPoint 文件，则这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                               |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                                                       |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                                                                                 |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                                          |

| 公告标识符       | Microsoft 安全公告 MS08-044                                                                                                                                                                            |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Office 筛选器中的漏洞可能允许远程执行代码 (924090)**](https://technet.microsoft.com/security/bulletin/ms08-044)                                                                            |
| **摘要**         | 此安全更新可消除五个秘密报告的漏洞。 如果用户使用 Microsoft Office 查看特制图像文件，这些漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                   |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                           |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                     |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                              |

重要 (5)
--------


| 公告标识符       | Microsoft 安全公告 MS08-047                                                                                                                                                                                                                                                                                                                                                         |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**IPsec 策略处理中的漏洞可能导致信息泄露 (953733)**](https://technet.microsoft.com/security/bulletin/ms08-047)                                                                                                                                                                                                                                                                      |
| **摘要**         | 此更新解决了应用特定 Windows Internet 协议安全性 (IPsec) 规则的方式中的一个秘密报告的漏洞。 此漏洞可能导致系统忽略 IPsec 策略并以明文形式传输网络流量。 而这样会泄露往往在网络上会被加密的信息。 查看网络流量的攻击者能够查看并且可能修改流量的内容。 请注意，此漏洞不允许攻击者直接执行代码或提升他们的用户权限。 它可能用于收集有用的信息，从而试图进一步损坏受影响的系统或网络。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                |
| **漏洞的影响**   | 信息泄露                                                                                                                                                                                                                                                                                                                                                                            |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                                                                                                                                                                    |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                          |

| 公告标识符       | Microsoft 安全公告 MS08-049                                                                                                                                                                                         |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**事件系统中的漏洞可能允许远程执行代码 (950974)**](https://technet.microsoft.com/security/bulletin/ms08-049)                                                                                                        |
| **摘要**         | 此更新解决 Microsoft Windows 事件系统中可能允许远程执行代码的两个秘密报告的漏洞。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者随后可安装程序；查看、更改或删除数据；或者创建拥有完全管理权限的新帐户。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                        |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                    |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                          |

| 公告标识符       | Microsoft 安全公告 MS08-048                                                                                                                                                                                                      |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Outlook Express 和 Windows Mail 的安全更新 (951066)**](https://technet.microsoft.com/security/bulletin/ms08-048)                                                                                                               |
| **摘要**         | 此安全更新解决了 Outlook Express 和 Windows Mail 中一个秘密报告的漏洞。 如果用户使用 Internet Explorer 访问特制网页，该漏洞可能允许信息泄露。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                             |
| **漏洞的影响**   | 信息泄露                                                                                                                                                                                                                         |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                             |
| **受影响的软件** | **Microsoft Windows、Outlook Express 和 Windows Mail。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                      |

| 公告标识符       | Microsoft 安全公告 MS08-050                                                                                                                                                                                                                                                                                     |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Messenger 中的漏洞可能导致信息泄露 (955702)**](https://technet.microsoft.com/security/bulletin/ms08-050)                                                                                                                                                                                              |
| **摘要**         | 此安全更新解决了 Windows Messenger 的受支持版本中一个公开报告的漏洞。 由于此漏洞，ActiveX 控件的脚本可能允许登录用户的上下文中出现信息泄露。 攻击者可以在登录用户不知情的情况下更改状态、获取联系人信息以及启动音频和视频聊天会话。 攻击者还可以捕获用户的登录 ID 并远程登录用户的 Messenger 客户端假冒该用户。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                            |
| **漏洞的影响**   | 信息泄露                                                                                                                                                                                                                                                                                                        |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                                                                                                |
| **受影响的软件** | **Microsoft Windows、Windows Messenger。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                   |

| 公告标识符       | Microsoft 安全公告 MS08-042                                                                                                                                                                                                                                                                                                          |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Word 中的漏洞可能允许远程执行代码 (955048)**](https://technet.microsoft.com/security/bulletin/ms08-042)                                                                                                                                                                                                                  |
| **摘要**         | 此安全更新可解决 Microsoft Word 中一个公开报告的漏洞。 如果用户打开特制的 Word 文件，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                 |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                         |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                   |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                            |

受影响的软件和下载位置
----------------------

**我如何使用该表呢？**

可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。

**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

#### Windows 操作系统

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
[**MS08-046**](https://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](https://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](https://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](https://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](https://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](https://technet.microsoft.com/security/bulletin/ms08-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=db455d17-435f-46d7-b2dd-5babb5a1eeb3)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=1557b93b-ecba-4f42-b89d-db0ee067d65b)  
（严重）  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=aa780735-5928-4c46-89a4-63a814954796)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=1b2ad648-7dc9-407a-99f6-f39922746027)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6257bfae-35f0-4c0e-b960-bca7aa6f86f7)  
（重要）  
[Microsoft Outlook Express 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=dab178f7-c282-41f4-acb1-a86e6aa4c91b)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
（重要）
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
[**MS08-046**](https://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](https://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](https://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](https://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](https://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](https://technet.microsoft.com/security/bulletin/ms08-050)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高严重等级**
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d313f42c-f43f-48ea-82ef-3bc33077c7fa)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=69af2f30-138e-4b15-ab8d-4fce44cc0bc2)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8e2125c7-52cb-4052-82a3-2d3c6a953752)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=01a34aa4-a456-4efc-a93a-c3c682b0181c)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=91469f2f-461c-4a67-8738-d42520427f6b)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](https://www.microsoft.com/download/details.aspx?familyid=8f588f7e-c4ed-42a0-b157-54b1eda60474)  
(KB946648)  
（重要）  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3150c6b8-f50b-4b84-a7ce-c8daf77c080c)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=4780b89e-9735-4d3f-8def-34e7337ff604)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=39b41e4b-3237-409d-a818-ab0517c5e7cf)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=246b2686-e330-47a2-b4d4-68f218ad4021)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=2220aece-79d2-426f-90ec-24a17470567a)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](https://www.microsoft.com/download/details.aspx?familyid=a5fc5457-832f-4ee8-be60-4cc8518d1c10)  
(KB946648)  
（重要）  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
（重要）
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
[**MS08-046**](https://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](https://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](https://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](https://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](https://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](https://technet.microsoft.com/security/bulletin/ms08-050)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高严重等级**
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=828d8fdc-8534-4621-85a5-08aec255496f)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=0617a5dd-dce9-4de0-b0a0-ce38efe13524)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b3c2e2fd-1cb9-491b-937c-053dd59a65bf)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=92a3d08f-c117-4b24-bc78-2b913d270df6)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=30f2244a-f6fd-4fc1-a871-abf6958cb660)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](https://www.microsoft.com/download/details.aspx?familyid=302315a8-ccb2-47c2-9104-b8e1d1f49aa0)  
(KB954723)  
（中等）  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0a13776f-d543-41df-b904-d51e368c81cc)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=32a63f52-9fe6-48e3-bb4e-7d4dda5e0a90)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=88a26b76-f7df-45c9-8ed0-7d3cd71c1987)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows 2003 Server x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6bfbb6d8-5106-4adf-83cb-35ffc6e8eaf8)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=3287f006-cbb2-4c6d-820c-32833e08035a)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](https://www.microsoft.com/download/details.aspx?familyid=be94d138-7d7b-489e-baa6-e214950be6b9)  
(KB954723)  
（中等）  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=9566493f-4260-4072-947a-527887d2cd63)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=1855997e-a3be-46b1-a0bc-bb55eb0045fe)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=97d0d37d-5d76-4bc3-8cbd-1e3976c82acf)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=45356565-697f-41b3-9879-3edd11dbcb7e)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=c8570e40-355b-4a9b-933d-53ae021cbda5)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Messenger 4.7](https://www.microsoft.com/download/details.aspx?familyid=e4b72618-536b-4a21-bd91-d91be9ca24e5)  
(KB954723)  
（中等）  
[Windows Messenger 5.1](https://www.microsoft.com/download/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774)  
(KB899283)  
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
[**MS08-046**](https://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](https://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](https://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](https://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](https://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](https://technet.microsoft.com/security/bulletin/ms08-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=13cba012-dd20-48f9-8e44-e4cb104c4cad)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3f21a8a2-9861-4fef-9d1e-caf5f7822c1a)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6418c78f-f008-4028-beb1-5a5ea8e797a1)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=3851bcf8-f971-4d38-b27f-97396854aac0)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
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
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ead919c2-d548-47b7-9cd6-80f991266428)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=aa04a754-fbfb-42a7-89d2-14373e3f4742)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e03ccfb0-3ea3-4c59-adcf-9882d7086013)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=3bf7eb8a-b347-4661-be2d-682adc713769)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
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
[**MS08-046**](https://technet.microsoft.com/security/bulletin/ms08-046)
</td>
<td style="border:1px solid black;">
[**MS08-045**](https://technet.microsoft.com/security/bulletin/ms08-045)
</td>
<td style="border:1px solid black;">
[**MS08-047**](https://technet.microsoft.com/security/bulletin/ms08-047)
</td>
<td style="border:1px solid black;">
[**MS08-049**](https://technet.microsoft.com/security/bulletin/ms08-049)
</td>
<td style="border:1px solid black;">
[**MS08-048**](https://technet.microsoft.com/security/bulletin/ms08-048)
</td>
<td style="border:1px solid black;">
[**MS08-050**](https://technet.microsoft.com/security/bulletin/ms08-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4b52ff2f-d2f5-4c20-b6cf-86d86c56b0f8)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=c3363df6-39dc-4910-9ce5-66553155378e)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=0640f95e-1eee-4dd1-b4dd-2b82b7e984b9)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=dc3c4b63-acd3-4469-8d47-e0562d99ee65)\*\*  
（低）
</td>
<td style="border:1px solid black;">
不适用
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
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=df9814a6-5be0-4ac1-a767-a0eae8d5ee5d)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=39dd1722-412b-469d-a475-b6513764838c)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=51a93538-5e94-4f81-a6e0-d497a7b4899d)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=5f973f54-2322-4b41-8c1a-3e712c0da8ae)\*\*  
（低）
</td>
<td style="border:1px solid black;">
不适用
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
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ffc3cfcb-73fe-4a6d-9595-e9d7a5b3d3f7)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e9c6cd46-30ad-46ee-9c8b-d0b446e660c4)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=390da130-749d-4890-aad7-be91e15b32bb)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Mail](https://www.microsoft.com/download/details.aspx?familyid=9226cd85-1445-4976-a126-757c5d142ffd)  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**\*Windows Server 2008 服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 的受支持版本，严重等级相同，无论安装 Windows Server 2008 时是否使用“服务器核心”安装选项。 有关该安装选项的详细信息，请参阅[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*Windows Server 2008 服务器核心安装不受影响。** 如果安装 Windows Server 2008 时使用“服务器核心”安装选项，则此更新所解决的漏洞不会影响 Windows Server 2008 的受支持版本。 有关该安装选项的详细信息，请参阅[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

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
<th>
</th>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Microsoft Office 套件、系统和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-041**](https://technet.microsoft.com/security/bulletin/ms08-041)
</td>
<td style="border:1px solid black;">
[**MS08-043**](https://technet.microsoft.com/security/bulletin/ms08-043)
</td>
<td style="border:1px solid black;">
[**MS08-051**](https://technet.microsoft.com/security/bulletin/ms08-051)
</td>
<td style="border:1px solid black;">
[**MS08-044**](https://technet.microsoft.com/security/bulletin/ms08-044)
</td>
<td style="border:1px solid black;">
[**MS08-042**](https://technet.microsoft.com/security/bulletin/ms08-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 8
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
[Microsoft Works 8](https://www.microsoft.com/download/details.aspx?familyid=458985c3-9c6f-4049-81cd-0d0389c81f11)  
(KB955428)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=54e4031d-298f-480c-88d5-0ad3b2b62ba9)  
(KB955441)  
（严重）
</td>
<td style="border:1px solid black;">
[Excel 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=4bf8688e-e5b9-4e53-a1a1-8cf1acfdb80b)  
(KB951582)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e7c044d8-778a-4985-b25b-4f7f6e4abadd)  
(KB949007)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3ab323ec-9f92-453c-b7c7-9a95a9efcaea)  
(KB921595)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=34b655f8-1922-4246-94ca-ed381c3e3b13)  
(KB955440)  
（严重）
</td>
<td style="border:1px solid black;">
[Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9bbf7550-f5c4-4b9b-bd86-1e7be6c42eb5)  
(KB951551)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f8921074-7985-4d42-ac2b-d2f3b1d466ba)  
(KB948995)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79)  
(KB921596)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c7146dfc-e1be-4d13-877b-1d9bcacc4a64)  
(KB954463)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 和 Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Access 2003 Service Pack 2 和 Microsoft Office Access 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=fd698517-a504-427d-9e5f-fde8f102142c)  
(KB955439)  
（严重）
</td>
<td style="border:1px solid black;">
[Excel 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0)  
(KB951548)  
（重要）  
[Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0)  
(KB951548)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f)  
(KB948988)  
（重要）  
[Microsoft Office PowerPoint 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f)  
(KB948988)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e0df2f6e-1102-461d-829f-5f3e2d7eb4b3)  
(KB921598)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=13a37b76-9fec-426f-8176-3c95f934efe0)  
(KB954464)  
（重要）  
[Microsoft Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=13a37b76-9fec-426f-8176-3c95f934efe0)  
(KB954464)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System 和 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Excel 2007](https://www.microsoft.com/download/details.aspx?familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd)  
(KB951546)  
（重要）  
[Excel 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd)  
(KB951546)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2007](https://www.microsoft.com/download/details.aspx?familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef1)  
(KB951338)  
（重要）  
[Microsoft Office PowerPoint 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef1)  
(KB951338)  
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
<th colspan="6" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-041**](https://technet.microsoft.com/security/bulletin/ms08-041)
</td>
<td style="border:1px solid black;">
[**MS08-043**](https://technet.microsoft.com/security/bulletin/ms08-043)
</td>
<td style="border:1px solid black;">
[**MS08-051**](https://technet.microsoft.com/security/bulletin/ms08-051)
</td>
<td style="border:1px solid black;">
[**MS08-044**](https://technet.microsoft.com/security/bulletin/ms08-044)
</td>
<td style="border:1px solid black;">
[**MS08-042**](https://technet.microsoft.com/security/bulletin/ms08-042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高严重等级**
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project 2002
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
[Microsoft Project 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79)  
(KB921596)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SnapShot Viewer for Microsoft Access
</td>
<td style="border:1px solid black;">
SnapShot Viewer for Microsoft Access\*
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
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office PowerPoint Viewer 2003
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint Viewer 2003](https://www.microsoft.com/download/details.aspx?familyid=911c8872-dec8-4b8e-9708-93dcabd3e036)  
(KB949041)  
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
Microsoft Office Excel Viewer 2003 和 Microsoft Office Excel Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](https://www.microsoft.com/download/details.aspx?familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1)  
(KB951589)  
（重要）  
[Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1)  
(KB951589)  
（重要）
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
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer](https://www.microsoft.com/download/details.aspx?familyid=b574d906-7f09-49b0-80bf-e84dee8c4583)  
(KB955472)  
（重要）
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
Microsoft Office Converter Pack
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
[Microsoft Office Converter Pack](https://www.microsoft.com/download/details.aspx?familyid=199b08c7-6d79-4930-8f0c-31034629c485)  
(KB925256)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包以及用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9)  
(KB951596)  
（重要）  
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9)  
(KB951596)  
（重要）
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=84ce5d58-0010-4945-bce9-67a41f898f2f) (KB954038)  
（重要）  
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=84ce5d58-0010-4945-bce9-67a41f898f2f) (KB954038)  
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
Microsoft Office SharePoint Server 2007 和 Microsoft Office SharePoint Server 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007](https://www.microsoft.com/download/details.aspx?familyid=a7731749-b026-4765-808a-e151b990f0e1)  
(KB953397)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a7731749-b026-4765-808a-e151b990f0e1)  
(KB953397)  
（重要）
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
Microsoft Office SharePoint Server 2007 x64 Edition 和 Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b)  
(KB953397)  
（重要）  
[Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b)  
(KB953397)  
（重要）
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
<th colspan="6" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-041**](https://technet.microsoft.com/security/bulletin/ms08-041)
</td>
<td style="border:1px solid black;">
[**MS08-043**](https://technet.microsoft.com/security/bulletin/ms08-043)
</td>
<td style="border:1px solid black;">
[**MS08-051**](https://technet.microsoft.com/security/bulletin/ms08-051)
</td>
<td style="border:1px solid black;">
[**MS08-044**](https://technet.microsoft.com/security/bulletin/ms08-044)
</td>
<td style="border:1px solid black;">
[**MS08-042**](https://technet.microsoft.com/security/bulletin/ms08-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5)  
(KB956343)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5)  
(KB953824)  
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
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=9515c70d-be80-4ade-856a-ea542f7d84e1)  
(KB956344)  
（重要）
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

**\*SnapShot Viewer for Microsoft Access 的备注 (MS08-041)：** Microsoft 当前正在为此受影响的软件开发软件更新，不久即将发布安全更新。 在发布安全更新时，Microsoft 也将更新安全公告和此公告摘要。

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

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： 2008 年 Software Update Services 和 Windows Server Update Services 内容的更改说明。包括所有 Windows 内容。
-   [Microsoft Windows 之外的其他 Microsoft 产品的新更新、经过修订的更新以及已发布的更新](https://technet.microsoft.com/en-us/wsus/bb466214.aspx)。

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

-   [ISC/SANS](https://isc.sans.org/) 报告了 MS08-042 中描述的问题
-   [VeriSign iDefense](https://www.idefense.com/vcp) VCP 报告了 MS08-043 中描述的问题
-   [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 报告了 MS08-043 中描述的问题
-   Jeremy Funk 报告了 MS08-043 中描述的问题
-   [NGS Software](https://www.nextgenss.com/) 的 Shaun Colley 报告了 MS08-044 中描述的问题
-   [Zero Day Initiative (ZDI)](https://www.zerodayinitiative.com/) 报告了 MS08-052 中描述的问题
-   一名匿名研究员与 [iDefense VCP](https://labs.idefense.com/) 一起报告了 MS08-044 中描述的问题
-   Damian Put 与 [iDefense VCP](https://labs.idefense.com/) 一起报告了 MS08-044 中描述的问题
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS08-045 中描述的问题
-   [Google Security Team](https://www.google.com/) 的 Tavis Ormandy 报告了 MS08-045 中描述的问题
-   Sam Thomas 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS08-045 中描述的问题
-   [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 报告了 MS08-045 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Jun Mao 报告了 MS08-046 中描述的问题
-   [Core Security Technologies](https://www.coresecurity.com/) 的 Jorge Luis Alvarez Medina 报告了 MS08-048 中描述的问题
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS08-049 中描述的问题
-   [Fortinet Security Response Team](https://www.fortinet.com/) 的 Haifei Li (cocoruder) 报告了 MS08-050 中描述的问题
-   [Reversemode.com](https://reversemode.com/) 的 Ruben Santamarta 与 [iDefense Labs](https://labs.idefense.com/) 一起报告了 MS08-051 中描述的问题
-   [Venustech](https://www.venustech.com.cn/) 的 ADLab 报告了 MS08-051 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](https://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2008 年 8 月 12 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
