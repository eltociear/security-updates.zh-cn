---
TOCTitle: 'MS07-JUN'
Title: 'Microsoft 安全公告摘要 (2007 年 6 月)'
ms:assetid: 'ms07-jun'
ms:contentKeyID: 61236906
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms07-jun(v=Security.10)'
---



Microsoft 安全公告摘要 (2007 年 6 月)
=====================================

发布时间: 2007年6月12日

**版本:** 1.0

本公告摘要列出了 2007 年 6 月发布的安全公告。

对于 2007 年 6 月发布的安全公告，本公告摘要替代 2007 年 6 月 7 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

要在 Microsoft 安全公告发布时即刻接收自动通知，请订阅 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2007 年 6 月 13 日（星期三）上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 6 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032327013&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (4)
--------


| 公告标识符       | Microsoft 安全公告 MS07-031                                                                                                                                                                                                                                                                                                                                                                                              |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Schannel 安全程序包中的漏洞可能允许远程执行代码 (935840)**](http://technet.microsoft.com/security/bulletin/ms07-031)                                                                                                                                                                                                                                                                                          |
| **摘要**         | 此关键安全更新解决了 Windows 中的安全通道 (Schannel) 安全数据包中秘密报告的漏洞。 Schannel 安全数据包实现安全套接字层 (SSL) 和传输层安全 (TLS) Internet 标准身份验证协议。 如果用户使用 Internet Web 浏览器查看特制网页或使用利用 SSL/TLS 的应用程序，则此漏洞可能允许远程执行代码。 但是，利用此漏洞的尝试最有可能导致 Internet Web 浏览器或应用程序退出。 重新启动系统之前，系统不能使用 SSL 或 TLS 连接到网站或资源。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                     |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                                                                             |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                                                                                                                                                                                                                  |
| **受影响的软件** | **Windows**。 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                                                                         |

| 公告标识符       | Microsoft 安全公告 MS07-033                                                                                                                                                                                                                                                                                                                   |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Internet Explorer 的累积性安全更新 (933566)**](http://technet.microsoft.com/security/bulletin/ms07-033)                                                                                                                                                                                                                                    |
| **摘要**         | 此关键安全更新可消除五个秘密报告的漏洞以及一个公开披露的漏洞。 如果用户使用 Internet Explorer 查看特制网页，那么其中一个漏洞可能允许远程执行代码。 一个漏洞可能允许欺骗，也可能涉及某特制网页。 在所有远程执行代码情形中，帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。 对于欺骗情形来说，漏洞利用需要用户交互。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                          |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                  |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                                                                                                                                       |
| **受影响的软件** | **Windows，Internet Explorer**。 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                           |

| 公告标识符       | Microsoft 安全公告 MS07-034                                                                                                                                                                                                                                                                                                                                                        |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Outlook Express 和 Windows Mail 的累积性安全更新 (929123)**](http://technet.microsoft.com/security/bulletin/ms07-034)                                                                                                                                                                                                                                                           |
| **摘要**         | 此关键安全更新解决了两个秘密报告的漏洞和两个公开披露的漏洞。 如果用户使用 Windows Vista 中的 Windows Mail 查看特制的电子邮件，则这些漏洞之一可能允许远程执行代码。 如果用户使用 Internet Explorer 访问特制网页，则其他漏洞可能允许信息泄露，而且不能在 Outlook Express 中直接被利用。 对于信息泄露漏洞，帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                               |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                                       |
| **检测**         | Microsoft 基准安全分析器和企业扫描工具可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                                                                                                                                                              |
| **受影响的软件** | **Windows、Outlook Express 和 Windows Mail**。 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                  |

| 公告标识符       | Microsoft 安全公告 MS07-035                                                                                                                                                                                                                                |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Win32 API 中的漏洞可能允许远程执行代码 (935839)**](http://technet.microsoft.com/security/bulletin/ms07-035)                                                                                                                                             |
| **摘要**         | 此关键安全更新可消除 Win32 API 中秘密报告的漏洞。 如果特制应用程序本地使用受影响的 API，此漏洞可能允许远程执行代码或特权提升。 因此，使用此 Win32 API 组件的应用程序可以用作此漏洞的媒介。 例如，Internet Explorer 在分析特制网页时使用此 Win32 API 函数。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                       |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                               |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                                                    |
| **受影响的软件** | **Windows**。 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                           |

重要 (1)
--------


| 公告标识符       | Microsoft 安全公告 MS07-030                                                                                                                                                                                                                                                              |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Visio 中的漏洞可能允许远程执行代码 (927051)**](http://technet.microsoft.com/security/bulletin/ms07-030)                                                                                                                                                                     |
| **摘要**         | 除了调查过程中确定的其他安全问题之外，此重要安全更新还可以消除秘密发现和负责报告的两个漏洞。 如果用户打开特制的 Visio 文件，则秘密报告的漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 要利用这些漏洞，需要进行用户交互。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                     |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                             |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                                                                                  |
| **受影响的软件** | **Office、Visio**。 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                   |

中等 (1)
--------


| 公告标识符       | Microsoft 安全公告 MS07-032                                                                                                           |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Vista 中的漏洞可能导致信息泄露 (931213)**](http://technet.microsoft.com/security/bulletin/ms07-032)                        |
| **摘要**         | 此中等安全更新可消除一个秘密报告的漏洞。 此漏洞可能允许非特权用户访问本地用户信息数据存储，包括注册表和本地文件系统中包含的管理密码。 |
| **最高严重等级** | [中等](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                  |
| **漏洞的影响**   | 信息泄露                                                                                                                              |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                               |
| **受影响的软件** | **Windows**。 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                      |

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
[**MS07-030**](http://technet.microsoft.com/security/bulletin/ms07-030)
</td>
<td style="border:1px solid black;">
[**MS07-031**](http://technet.microsoft.com/security/bulletin/ms07-031)
</td>
<td style="border:1px solid black;">
[**MS07-032**](http://technet.microsoft.com/security/bulletin/ms07-032)
</td>
<td style="border:1px solid black;">
[**MS07-033**](http://technet.microsoft.com/security/bulletin/ms07-033)
</td>
<td style="border:1px solid black;">
[**MS07-034**](http://technet.microsoft.com/security/bulletin/ms07-034)
</td>
<td style="border:1px solid black;">
[**MS07-035**](http://technet.microsoft.com/security/bulletin/ms07-035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<th colspan="7" style="border:1px solid black;">
受影响的 Windows 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](http://www.microsoft.com/downloads/details.aspx?familyid=5b8e728c-cb9f-4176-93a0-bf42d6387f93)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=3918ac76-ebb6-4886-9a9e-808eafb96b1b)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=8615e6f3-415b-4c23-ba52-7eef70a11d77)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=27c7f1b9-2d1d-40cb-ad7e-bfedb6156a9c)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99)
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
[中等](http://www.microsoft.com/downloads/details.aspx?familyid=cdf79d00-6f34-404b-8ad5-a2801ff35443)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
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
[中等](http://www.microsoft.com/downloads/details.aspx?familyid=89dde3f4-4123-4c97-86d8-00a83462c34b)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
受影响的 Windows 操作系统组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 5.01 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=3b49f1ed-abe3-4dbd-a91d-973415658f6b)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 6 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=5c958650-28d2-4dd0-96a8-dbfe79ce3f68)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=60fb294e-a8e1-405e-a289-2d2723edf7ee)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=086d6d6e-4703-4c6c-a7af-b6dafeeede5d)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=7ed19127-5c2d-48e4-a8d1-090dc69fd68b)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=1449eb5d-6e4c-4332-8cb6-ab9ee59c9a95)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows Server 2003 SP1（用于基于 Itanium 的系统）和 Windows Server 2003 SP2（用于基于 Itanium 的系统）的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=b628a3cc-a70c-478a-a10c-eee254ee34ab)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows XP Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=c2191703-8cbd-4959-9f84-e13f21173926)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=69c526b8-8b07-42bc-9bed-e18deae21c8e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](http://www.microsoft.com/downloads/details.aspx?familyid=a074d9c0-1fed-4753-845e-073cfce99f45)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](http://www.microsoft.com/downloads/details.aspx?familyid=744acb43-64da-48cc-ae69-9386b597eabc)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows Server 2003 SP1（用于基于 Itanium 的系统）和 Windows Server 2003 SP2（用于基于 Itanium 的系统）的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](http://www.microsoft.com/downloads/details.aspx?familyid=069c1560-b5e5-4dfe-a18d-e0507d406028)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 中的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=77287386-48eb-4aa9-9537-626a3093aaf7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 中的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=77287386-48eb-4aa9-9537-626a3093aaf7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows XP Service Pack 2 的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=27cca556-0872-4803-b610-4c895ceb99aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows XP Professional x64 Edition 的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows XP Professional x64 Edition Service Pack 2 的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows Server 2003 Service Pack 1 的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[低](http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows Server 2003 Service Pack 2 的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[低](http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows Server 2003 x64 Edition 的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows Server 2003 x64 Edition Service Pack 2 的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows Server 2003 SP1（用于基于 Itanium 的系统）的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[低](http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows Server 2003 SP2（用于基于 Itanium 的系统）的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[低](http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 中的 Windows Mail
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=ee57de19-44ea-48f2-ae28-e76fd2018633)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 中的 Windows Mail
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](http://www.microsoft.com/downloads/details.aspx?familyid=343db20f-7794-4423-b11d-885329fbdf78)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
受影响的 Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visio 2002 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=fc1d0483-27e8-4541-b81d-4a47973bea30)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
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
Visio 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=c47f432e-8538-42fd-92c9-7e0f1d643e8e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>

**备注**

**<sup>[1]</sup>** 此操作系统有一个可用的安全更新。 有关详细信息，请参阅本表中的受影响的软件或组件和相应的安全公告。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 详细信息，请参阅 [TechNet Update 管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)和 [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过搜索关键字“安全修补程序”，可以非常方便地找到这些更新。 最后，安全更新可从 Windows Update 目录下载。 有关 Windows Update 目录的详细信息，请参阅 [Microsoft 知识库文章 323166](http://support.microsoft.com/kb/323166)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft 基准安全分析器 (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS)、扩展安全更新清单工具以及企业更新扫描工具 (EST)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](http://support.microsoft.com/kb/910723)。

**Microsoft 基准安全分析器和企业** **更新扫描工具**

管理员可使用 Microsoft 基准安全分析器 (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft 基准安全分析器](http://go.microsoft.com/fwlink/?linkid=21134)。

当 MBSA 1.2.1 不支持对某特定安全更新的检测时，Microsoft 将为此特定安全更新发行一个企业更新扫描工具 (EST) 版本。 有关 EST 的详细信息，请访问[企业更新扫描工具](http://support.microsoft.com/default.aspx?id=894193)。

**注意** 2007 年 10 月 9 日以后，MBSA 1.2.1 使用的 MSSecure.XML 文件将不再更新。 在此日期后，MBSA 1.2.1 使用的 MSSecure.XML 文件中不会再添加新的安全更新，也不会再发行新版本的“企业扫描工具”。 有关详细信息，请访问 [Microsoft 基准安全分析器](http://go.microsoft.com/fwlink/?linkid=21134)。

**软件更新服务**

通过使用 Microsoft 软件更新服务 (SUS)，管理员可以在基于 Windows 2000 和 Windows Server 2003 的服务器以及运行 Windows 2000 Professional 或 Windows XP Professional 的台式机系统上快速而可靠地部署最新的关键更新和安全更新。

有关如何使用软件更新服务部署此安全更新的详细信息，请访问[软件更新服务](http://go.microsoft.com/fwlink/?linkid=21133)。

**Windows Server 更新服务**

通过使用 Windows Server 更新服务(WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server 更新服务部署此安全更新的详细信息，请访问 [Windows Server 更新服务](http://go.microsoft.com/fwlink/?linkid=50120)。

**系统管理服务器**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用[软件更新服务功能包](http://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft 基准安全分析器和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server 更新服务和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

注意，此工具**不**使用软件更新服务 (SUS) 分发。

#### MU、WU、WSUS 和 SUS 上的非安全、高优先级更新

在本月：

-   Microsoft 在 Microsoft Update (MU) 和 Windows Server 更新服务 (WSUS) 上发布了七个**非安全**高优先级更新。
-   Microsoft 在 Windows Update (WU) 和软件更新服务 (SUS) 上尚未发布任何**非安全**高优先级 Windows 更新。

注意，此信息**仅**适用于发布安全公告摘要当天 Microsoft Update、Windows Update、Windows Server 更新服务和软件更新服务上发布的**非安全**高优先级更新。 并**不**提供关于其他日期发布的**非安全**更新的信息。

#### 安全策略和社区

**更新管理策略**

[安全修补程序管理指南](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳实践建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过搜索关键字“安全修补程序”，可以非常方便地找到这些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   一名匿名研究员与 [iDefense VCP](http://idefense.com/) 一起报告了 [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835) 中描述的问题。
-   [ISS](http://www.iss.net/) 的 Tom Cross 与 Microsoft 一起努力处理了 [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835) 中描述的问题。
-   一名匿名研究员与 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835) 中描述的问题。
-   Sam Thomas 与 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835) 中描述的问题。
-   [CERT/CC](http://www.cert.org/certcc.html) 的 Will Dormann 报告了 [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835) 中描述的问题。
-   [Fortinet Security Research](http://www.fortinet.com/) 的 cocoruder 与 Microsoft 一起努力处理了 [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835) 中描述的问题。
-   Billy Rios 报告了 [MS07-035](http://go.microsoft.com/fwlink/?linkid=91397) 中描述的问题。
-   [COSEINC](http://www.coseinc.com/) 的 Thomas Lim 报告了 [MS07-031](http://go.microsoft.com/fwlink/?linkid=91396) 中描述的问题。
-   [SANS ISC](http://isc.sans.org/) 与我们一起努力处理了 [MS07-034](http://go.microsoft.com/fwlink/?linkid=88627) 中描述的问题。
-   [WebAppSec.JP](https://www.webappsec.jp/) 的 Yosuke Hasegawa 报告了 [MS07-034](http://go.microsoft.com/fwlink/?linkid=88627) 中描述的问题。
-   Robbie Sohlman 报告了 [MS07-032](http://go.microsoft.com/fwlink/?linkid=84693) 中描述的问题。

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2007 年 6 月 12 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
