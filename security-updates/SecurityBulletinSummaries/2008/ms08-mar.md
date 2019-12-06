---
TOCTitle: 'MS08-MAR'
Title: 'Microsoft 安全公告摘要 (2008 年 3 月)'
ms:assetid: 'ms08-mar'
ms:contentKeyID: 61236920
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms08-mar(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2008 年 3 月)
=====================================

发布时间: 2008年3月11日

**版本:** 1.0

本公告摘要列出了 2008 年 3 月发布的安全公告。

对于 2008 年 3 月发布的安全公告，本公告摘要替代 2008 年 3 月 6 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2008 年 3 月 12 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 3 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357217&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (4)
--------

| 公告标识符       | Microsoft 安全公告 MS08-014                                                                                                                                                                                                                                                                                                                                |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Excel 中的漏洞可能允许远程执行代码 (949029)**](http://technet.microsoft.com/security/bulletin/ms08-014)                                                                                                                                                                                                                                       |
| **摘要**         | 此安全更新解决了 Microsoft Office Excel 中多个秘密报告和公开报告的漏洞，如果用户打开特制的 Excel 文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                       |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                               |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                                         |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                  |

| 公告标识符       | Microsoft 安全公告 MS08-015                                                                                                                                                                                                                                                                                                                                             |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Outlook 中的漏洞可能允许远程执行代码 (949031)**](http://technet.microsoft.com/security/bulletin/ms08-015)                                                                                                                                                                                                                                                  |
| **摘要**         | 此安全更新解决了 Microsoft Office Outlook 中一个秘密报告的漏洞。 该漏洞可能允许远程执行代码（如果 Outlook 客户端被传递特制的 mailto URI）。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 只是通过 Outlook 预览窗格查看电子邮件并不会被此漏洞利用。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                    |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                            |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                                                      |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                               |

| 公告标识符       | Microsoft 安全公告 MS08-016                                                                                                                                                                                                                                                                                                                 |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Office 中的漏洞可能允许远程执行代码 (949030)**](http://technet.microsoft.com/security/bulletin/ms08-016)                                                                                                                                                                                                                       |
| **摘要**         | 此安全更新解决了 Microsoft Office 中两个秘密报告的漏洞，如果用户打开格式错误的 Office 文件，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                        |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                          |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                   |

| 公告标识符       | Microsoft 安全公告 MS08-017                                                                                                                                                                                                                                                                                                                       |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Office Web Components 中的漏洞可能允许远程执行代码 (933103)**](http://technet.microsoft.com/security/bulletin/ms08-017)                                                                                                                                                                                                              |
| **摘要**         | 此严重更新可解决 Microsoft Office Web Components 中两个秘密报告的漏洞。 如果用户查看了特制网页，这些漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                              |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                      |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                                                                                                                              |
| **受影响的软件** | **Microsoft Office Web Components。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                          |

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
[**MS08-014**](http://technet.microsoft.com/security/bulletin/ms08-014)
</td>
<td style="border:1px solid black;">
[**MS08-015**](http://technet.microsoft.com/security/bulletin/ms08-015)
</td>
<td style="border:1px solid black;">
[**MS08-016**](http://technet.microsoft.com/security/bulletin/ms08-016)
</td>
<td style="border:1px solid black;">
[**MS08-017**](http://technet.microsoft.com/security/bulletin/ms08-017)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高严重等级**
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
<th colspan="5" style="border:1px solid black;">
Office 套件和软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=72735aa1-e22c-40ed-8c79-38fba89979aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=9cf8aafa-71a5-4017-b53c-4e80ef6e1188)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=f7f90c30-1bfd-406b-a77f-612443e30185)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=907f96d5-d1e9-4471-b41c-3ac811e63038)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=296e5f2c-f594-41c8-a20a-3e4c40ae3948)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=280bb2ac-b21a-46b5-8751-5a50fbebf107)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel 2007
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=e7634cb5-9531-4284-9554-4168fc488e0c)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=e9251d71-9098-4125-ae91-7d4c83ea58ad)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Outlook 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=714a49cd-5bca-4719-96a1-e1077f279533)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Outlook 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=59853687-d885-4059-9460-ee403855dbd8)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Outlook 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Outlook 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Outlook 2007
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=4e2baf00-88eb-4eb6-961a-54245b363c21)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=8fe8c32a-6d7a-482b-97c6-42562f089ee4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
其他软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB931660)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=806c654a-35e3-4385-855a-4b803249bfcf)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB932031)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=f54d2a5e-c0ed-4f70-9746-38dd61c8e9d7)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB933367)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=d71b23fa-a873-406d-bad7-e38e565dee39)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB933369)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=2fe10ccd-40cb-4090-b83d-eae3d4eca174)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=e0993e49c0a811d2973d00c04f79e4b3)   
**<sup>[2]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=12b7d09a92ab4596996670799837d961)   
**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB941305)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=71de76ba-b62c-4a7a-a78a-9317f5255b13)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Components 2000  
(KB948257)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=526d87bd-c3da-412e-8765-c15987ae9b01)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio .NET 2002 Service Pack 1  
(KB933367)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2003 Service Pack 1  
(KB933369)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft BizTalk Server 2000  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2002  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2000  
(KB941305)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Security and Acceleration Server 2000 Service Pack 2  
(KB948257)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
</table>

**备注**

**<sup>[1]</sup>** 此软件有一个可用的安全更新。 有关详细信息，请参阅本表中的受影响的软件或组件和相应的安全公告。

**<sup>[2]</sup>** 此安全更新与 Microsoft BizTalk Server 2000 关联。有关详细信息，请参阅适当的安全公告。

**<sup>[3]</sup>** 此安全更新与 Microsoft BizTalk Server 2002 关联。有关详细信息，请参阅适当的安全公告。

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

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

在本月：

-   Microsoft 在 Microsoft Update (MU) 和 Windows Server 更新服务 (WSUS) 上发布了两个**非安全**高优先级更新。
-   Microsoft 已在 Windows Update (WU) 和 WSUS 上发布三个**非安全性**、高优先级 Windows 更新。

注意，此信息**仅**适用于 Microsoft Update、Windows Update 和 Windows Server Update Services 上在发布安全公告摘要当天发布的**非安全**、高优先级更新。 并**不**提供关于其他日期发布的**非安全**更新的信息。

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

-   [SAIC](http://www.saic.com/) 的 Mike Scott 报告了 MS08-014 中描述的问题
-   [VeriSign](http://www.verisign.com/) 的 Matt Richard 报告了 MS08-014 中描述的问题
-   [iDefense Labs](http://labs.idefense.com/) 的 Greg MacManus 报告了 MS08-014 中描述的问题
-   [JFE Systems](http://www.jfe-systems.com/) 的 Yoshiya Sasaki 报告了 MS08-014 中描述的问题
-   [Fortinet](http://www.fortinet.com/) 的 Bing Liu 报告了 MS08-014 中描述的问题
-   [iDefense Labs](http://labs.idefense.com/) 报告了 MS08-014 中描述中的问题
-   [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) 的 Cody Pierce 报告了 MS08-014 中描述的问题
-   [Websense Security Labs](http://www.websense.com/) 的 Moti Joseph 和 Dan Hubbard 报告了 MS08-014 中描述的问题
-   [iDefense Labs](http://labs.idefense.com/) 的 Greg MacManus 报告了 MS08-015 中描述的问题
-   Arnaud Dovi 与 [Zero Day Initiative (ZDI)](http://www.zerodayinitiative.com/) 合作，报告了 MS08-016 中描述的问题
-   匿名发现者报告了 MS08-016 中描述的问题
-   [VigilantMinds Inc.](http://www.vigilantminds.com/) 的 Chris Ries 报告了 MS08-017 中描述的问题
-   [NCNIPC](http://www.nipc.org.cn/) 的 Xiao Hui 报告了 MS08-017 中描述的问题
-   [Finjan](http://www.finjan.com/) 的 Yuval Ben-Itzhak 报告了 MS08-017 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2008 年 3 月 11 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
