---
TOCTitle: 'MS08-APR'
Title: 'Microsoft 安全公告摘要 (2008 年 4 月)'
ms:assetid: 'ms08-apr'
ms:contentKeyID: 61236912
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms08-apr(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2008 年 4 月)
=====================================

发布时间: 2008年4月8日

**版本:** 1.0

本公告摘要列出了 2008 年 4 月发布的安全公告。

对于 2008 年 4 月发布的安全公告，本公告摘要替代 2008 年 4 月 3 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2008 年 4 月 9 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 4 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357219&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (5)
--------


| 公告标识符       | Microsoft 安全公告 MS08-018                                                                                                                                                                                                                                                                                                                    |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Project 中的漏洞可能允许远程执行代码 (950183)**](https://technet.microsoft.com/security/bulletin/ms08-018)                                                                                                                                                                                                                         |
| **摘要**         | 此安全更新解决了 Microsoft Office Project 中秘密报告的漏洞，如果用户打开特制的 Project 文件，则该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                           |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                   |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                             |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                      |

| 公告标识符       | Microsoft 安全公告 MS08-021                                                                                                                                                                                                                                      |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**GDI 中的漏洞可能允许远程执行代码 (948590)**](https://technet.microsoft.com/security/bulletin/ms08-021)                                                                                                                                                         |
| **摘要**         | 此安全更新可解决 GDI 中两个秘密报告的漏洞。 如果用户打开特制的 EMF 或 WMF 图像文件，利用其中任何一个漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                             |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                     |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                                                 |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                       |

| 公告标识符       | Microsoft 安全公告 MS08-022                                                                                                                                                                                    |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**VBScript 和 JScript 脚本引擎中的漏洞可能允许远程执行代码 (944338)**](https://technet.microsoft.com/security/bulletin/ms08-022)                                                                               |
| **摘要**         | 此安全更新解决了 Windows 的 VBScript 和 JScript 脚本引擎中一个秘密报告的漏洞。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                           |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                   |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                               |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                     |

| 公告标识符       | Microsoft 安全公告 MS08-023                                                                                                                                                                                                                                                 |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**ActiveX Kill Bit 的安全更新 (948881)**](https://technet.microsoft.com/security/bulletin/ms08-023)                                                                                                                                                                         |
| **摘要**         | 此安全更新可解决 Microsoft 产品的一个秘密报告的漏洞。 此更新还包括 Yahoo! 的一个 kill bit 自动唱片点唱机产品。 如果用户使用 Internet Explorer 查看特制网页，此漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                        |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                                                        |
| **受影响的软件** | **Microsoft Windows、Internet Explorer。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                               |

| 公告标识符       | Microsoft 安全公告 MS08-024                                                                                                                                                                       |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Internet Explorer 的累积性安全更新 (947864)**](https://technet.microsoft.com/security/bulletin/ms08-024)                                                                                        |
| **摘要**         | 此安全更新可解决一个秘密报告的漏洞。 如果用户使用 Internet Explorer 查看特制网页，此漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                              |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                      |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                  |
| **受影响的软件** | **Microsoft Windows、Internet Explorer。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                     |

重要事项 (3)
------------


| 公告标识符       | Microsoft 安全公告 MS08-020                                                                                                                                     |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**DNS 客户端中的漏洞可能允许欺骗 (945553)**](https://technet.microsoft.com/security/bulletin/ms08-020)                                                          |
| **摘要**         | 此安全更新可解决一个秘密报告的漏洞。 此欺骗漏洞存在于 Windows DNS 客户端中，允许攻击者向 DNS 请求发送特制响应，从而导致欺骗或者从合法位置重定向 Internet 流量。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                            |
| **漏洞的影响**   | 欺骗                                                                                                                                                            |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                      |

| 公告标识符       | Microsoft 安全公告 MS08-025                                                                                                                                         |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows 内核中的漏洞可能允许特权提升 (941693)**](https://technet.microsoft.com/security/bulletin/ms08-025)                                                        |
| **摘要**         | 此安全更新解决 Windows 内核中一个秘密报告的漏洞。 成功利用此漏洞的本地攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建新帐户。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                |
| **漏洞的影响**   | 特权提升                                                                                                                                                            |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                    |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                          |

| 公告标识符       | Microsoft 安全公告 MS08-019                                                                                                                                                                                                                                                                                                                |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Visio 中的漏洞可能允许远程执行代码 (949032)**](https://technet.microsoft.com/security/bulletin/ms08-019)                                                                                                                                                                                                                       |
| **摘要**         | 此安全更新解决了 Microsoft Office Visio 中秘密报告的漏洞，如果用户打开特制的 Visio 文件，则该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                       |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                               |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                         |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                  |

受影响的软件和下载位置
----------------------

**如何使用该表？**

可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。

**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

#### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识符</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=caac000a-22b6-48cb-aa00-1a0bfe886de2">Microsoft Windows 2000 Service Pack 4</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.1 和 JScript 5.1</a><br />
（严重）<br />  
<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.6 和 JScript 5.6</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0395451f-b719-4f71-a7b4-403d0c7e8fcc">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
（严重）<br />  
<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=ba6d3aeb-e35a-47cc-bace-7bd9d58a9d3f">Microsoft Internet Explorer 6 Service Pack 1</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=b051ae04-fe81-440d-9136-d6b239ca954e">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
（严重）<br />  
<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=75d2dc78-e3a4-4ff6-9e2d-bf1935003e8e">Microsoft Internet Explorer 6 Service Pack 1</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=41326ade-96b6-47ce-9291-d4e3039471c4">Microsoft Windows 2000 Service Pack 4</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8db9f328-da0e-4fb8-96c4-6d368b47c224">Microsoft Windows 2000 Service Pack 4</a><br />
（重要）</td>
</tr>
</tbody>
</table>


<p> </p>
<table style="border:1px solid black;">
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识符</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=c2763dd8-a03e-4a48-aa86-a7ec00250a7a">Windows XP Service Pack 2</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=c0124698-3b94-4474-9473-22a2f39a4a56">VBScript 5.6 和 JScript 5.6</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=9dbf002f-fe53-4cc7-a430-35f45c520d10">Windows XP Service Pack 2</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=36c641ad-953f-4b09-ba1c-9c383295e180">Microsoft Internet Explorer 6</a><br />
（严重）<br />  
<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=e771efe8-8881-4f23-b5b0-15651a390ba9">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=893f4cef-0395-4c44-ba28-7a10b6e7dd48">Windows XP Service Pack 2</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0e937f65-abd0-46dd-8883-5bfd70ea1178">Windows XP Service Pack 2</a><br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=166f2ab5-913c-47a9-86fe-b814797b751e">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=87b80ae3-e299-4d15-a135-3b1bcf943652">VBScript 5.6 和 JScript 5.6</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=01400970-df68-4daf-aa39-2fc4f969974c">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=85beacc0-8ca2-4ded-9c24-23348d05c735">Microsoft Internet Explorer 6</a><br />
（严重）<br />  
<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=bf81-6505-4788-958d-a4bd29dc98ad">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8fdd1207-6e93-4c43-bacc-fe3623a6ebe7">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=a29bbd13-761f-44fa-8948-e1a8c244bd7a">Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2</a><br />
（重要）</td>
</tr>
</tbody>
</table>


<p> </p>
<table style="border:1px solid black;">
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识符</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=bee91d80-d49a-4d3d-82d6-d5aa63f54979">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=88518aa6-e334-4529-aa63-0bf2ef417ce3">VBScript 5.6 和 JScript 5.6</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=ad384fea-53be-4be3-8acb-1cd23a7f5405">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
（中等）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0444b76e-93fa-43c2-b1bc-a5c054529eb5">Microsoft Internet Explorer 6</a><br />
（严重）<br />  
<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=9acd2a03-5530-49c8-9ea1-0bfaf259700d">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=214bd8f5-6eb2-414c-b013-c516a306d692">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d3b855a6-4648-4771-826d-11a151828eac">Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2</a><br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=e3dde449-e062-4ce0-a9f4-433bff23e224">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=12cefefc-8553-4dca-9850-c653371de61e">VBScript 5.6 和 JScript 5.6</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=ffc5c893-cb24-4875-b0a7-6d5c7aa4d642">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
（中等）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=5ebb5ef9-615f-4cab-bac5-6f45f1b94952">Microsoft Internet Explorer 6</a><br />
（严重）<br />  
<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=a9e406aa-33e2-49b8-ab54-4a7328e46147">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=fd123394-a5d6-4b55-be74-2938f52ce922">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=320fd100-35e1-4345-9399-796393235cbc">Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2</a><br />
（重要）</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=7886a802-f2b5-489c-b14b-631f4c4c0742">Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=fe22a828-cca4-4b51-bbd5-995c65fead21">VBScript 5.6 和 JScript 5.6</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=94cf78d3-b6c3-41bc-993e-3af3be0d70f1">Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）</a><br />
（中等）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=63da8040-fda2-42c7-8543-26ad6f9811f2">Microsoft Internet Explorer 6</a><br />
（严重）<br />  
<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=75a05d3a-92a0-4a00-95d4-e2b2f6755180">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=e0e63f03-904d-47ee-94fc-51a8dea668eb">Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=126426a7-be38-4327-89db-02d99d76589d">Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）</a><br />
（重要）</td>
</tr>
</tbody>
</table>


<p> </p>
<table style="border:1px solid black;">
<caption>Windows Vista</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识符</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows Vista 和 Windows Vista Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=9b51deb8-3873-4146-977f-7e3d0840a4c5">Windows Vista 和 Windows Vista Service Pack 1</a><br />
（严重）</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d7f14001-7f42-4ca0-9193-cdf061179b59">Windows Vista 和 Windows Vista Service Pack 1</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d4e24966-6530-463a-9ee2-f6a9d000f998">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8203d303-c855-4579-9bbf-b06ddf5c1b87">Windows Vista</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=9640cd8b-d749-4ddd-8af9-b298cebed969">Windows Vista 和 Windows Vista Service Pack 1</a><br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=4ad6dcd1-6ea5-43bf-8bee-a5f507beadc6">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1</a><br />
（严重）</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d33462b6-7391-482d-babe-fb4cd0beaa21">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=295cf8f2-265e-4570-b708-21033337fe05">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=73f3a234-3973-4467-be7e-69efa7ee978c">Windows Vista x64 Edition</a><br />
（重要）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=d56bb4fe-304e-45e0-95f2-fde2f47b2a04">Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1</a><br />
（重要）</td>
</tr>
</tbody>
</table>


<p> </p>
<table style="border:1px solid black;">
<caption>Windows Server 2008</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识符</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-021"><strong>MS08-021</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-022"><strong>MS08-022</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-023"><strong>MS08-023</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-024"><strong>MS08-024</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-020"><strong>MS08-020</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-025"><strong>MS08-025</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008（用于 32 位系统）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=006d5c47-53e6-4ee1-932c-497611804938">Windows Server 2008（用于 32 位系统）</a><br />
（严重）</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=95691924-2813-4a86-9e11-99d853f8e606">Windows Server 2008（用于 32 位系统）</a><br />
（低）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=e57b4d94-19ad-4818-8311-a3f94be01a4b">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=4497333c-9418-4b91-83dc-0155735421c0">Windows Server 2008（用于 32 位系统）</a><br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2008（用于基于 x64 的系统）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=8909f144-655b-4f07-916f-fd967f1efb2b">Windows Server 2008（用于基于 x64 的系统）</a><br />
（严重）</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=920ae29b-19d0-4089-ac79-f2da824a2256">Windows Server 2008（用于基于 x64 的系统）</a><br />
（低）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=93e9f52a-c7d0-4033-9c12-740665a219af">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=5aefc7a6-79a4-45a2-b534-35d0ec400dda">Windows Server 2008（用于基于 x64 的系统）</a><br />
（重要）</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008（用于基于 Itanium 的系统）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=b7771a4a-4e4f-48d1-8551-bb8b778ca5a7">Windows Server 2008（用于基于 Itanium 的系统）</a><br />
（严重）</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=66df79ac-8364-4922-9688-ebc7ec76d89f">Windows Server 2008（用于基于 Itanium 的系统）</a><br />
（低）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=acf948e8-c4a9-40da-b282-f5e584e77b05">Windows Internet Explorer 7</a><br />
（严重）</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=3080c26b-7456-41ef-8668-28f15bc7b8ce">Windows Server 2008（用于基于 Itanium 的系统）</a><br />
（重要）</td>
</tr>
</tbody>
</table>


#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Project</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识符</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-018"><strong>MS08-018</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-019"><strong>MS08-019</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Microsoft Project 2000 Service Release 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=fbe46241-b9da-40c6-803d-42eb6234be77">Project 2000 Service Release 1</a><br />
(KB949043)<br />
（严重）</td>
<td style="border:1px solid black;">无</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Microsoft Project 2002 Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=07a90718-6597-426d-9dca-a336d60c01b8">Project 2002 Service Pack 1</a><br />
(KB949005)<br />
（重要）</td>
<td style="border:1px solid black;">无</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Microsoft Project 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=aaba07d6-e972-4e85-bccd-406aa2c4a4f4">Project 2003 Service Pack 2</a><br />
(KB948962)<br />
（重要）</td>
<td style="border:1px solid black;">无</td>
</tr>  
</tbody>  
</table>

<p> </p>
<table style="border:1px solid black;">  
<caption>Microsoft Office XP、Microsoft Office 2003 和 2007 Microsoft Office System</caption>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识符</strong></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-018"><strong>MS08-018</strong></a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms08-019"><strong>MS08-019</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office XP Service Pack 3</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0056a936-def5-40fa-bcfc-0ab0dd5c3964">Visio 2002 Service Pack 3</a><br />
(KB947896)<br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2003 Service Pack 2</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 2</a><br />
(KB947650)<br />
（重要）</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 3</a><br />
(KB947650)<br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">2007 Microsoft Office System</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007</a><br />
(KB947590)<br />
（重要）</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">2007 Microsoft Office System Service Pack 1</td>
<td style="border:1px solid black;">无</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007 Service Pack 1</a><br />
(KB947590)<br />
（重要）</td>
</tr>
</tbody>
</table>


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

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： 2008 年 Software Update Services 和 Windows Server Update Services 内容的更改说明。包括所有 Windows 内容。
-   [Microsoft Windows 之外的其他 Microsoft 产品的新更新、经过修订的更新以及已发布的更新。](https://technet.microsoft.com/en-us/wsus/bb466214.aspx)

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

-   大韩民国的 [National Cyber Security Center](https://www.ncsc.go.kr/eng/) 报告了 MS08-018 中描述的问题
-   匿名发现者报告了 MS08-019 中描述的问题
-   匿名发现者报告了 MS08-019 中描述的另一问题
-   [Trusteer](https://www.trusteer.com/) 的 Amit Klein 报告了 MS08-020 中描述的问题
-   [Scanit](https://www.scanit.be/) 的 Alla Berzroutchko 报告了 MS08-020 中描述的问题
-   [Nominet UK](https://www.nominet.org.uk/) 的 Roy Arends 报告了 MS08-020 中描述的问题
-   [iDefense Labs](https://labs.idefense.com/) 的 Jun Mao 报告了 MS08-021 中描述的问题
-   [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Sebastian Apelt 报告了 MS08-021 中描述的问题
-   [SkyRecon](https://www.skyrecon.com/) 的 Thomas Garnier 报告了 MS08-021 中描述的问题
-   Yamata Li 报告了 MS08-021 中描述的问题
-   [Symantec](https://www.symantec.com/) 的 Peter Ferrie 报告了 MS08-022 中描述的问题
-   一名匿名研究员与 [iDefense VCP](https://labs.idefense.com/vcp/) 一起报告了 MS08-023 中描述的问题
-   [Secunia](https://secunia.com/) 的 Carsten Eiram 报告了 MS08-024 中描述的问题
-   [SkyRecon](https://www.skyrecon.com/) 的 Thomas Garnier 报告了 MS08-025 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](https://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2008 年 4 月 8 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
