---
TOCTitle: 'MS08-OCT'
Title: 'Microsoft 安全公告摘要 (2008 年 10 月)'
ms:assetid: 'ms08-oct'
ms:contentKeyID: 61236925
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms08-oct(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2008 年 10 月)
======================================

发布时间: 2008年10月14日

**版本:** 1.0

本公告摘要列出了 2008 年 10 月发布的安全公告。

对于 2008 年 10 月发布的安全公告，本公告摘要替代 2008 年 10 月 9 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2008 年 10 月 15 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 10 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374639)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (4)
--------


| 公告标识符       | Microsoft 安全公告 MS08-060                                                                                                                                                                                                                                                                                                                                                           |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Active Directory 中的漏洞可能允许远程执行代码 (957280)**](http://technet.microsoft.com/security/bulletin/ms08-060)                                                                                                                                                                                                                                                                 |
| **摘要**         | 此安全更新可解决 Microsoft Windows 2000 Server 上的 Active Directory 实施中一个秘密报告的漏洞。 如果攻击者获得受影响网络的访问权限，则该漏洞可能允许远程执行代码。 此漏洞仅影响配置为主域控制器的 Microsoft Windows 2000 服务器。 如果 Microsoft Windows 2000 服务器没有被提升为域控制器，则它不会侦听轻量目录访问协议 (LDAP) 或 LDAP over SSL (LDAPS) 查询，因此不会被暴露给此漏洞。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                  |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                                          |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                                                                                                                                                                      |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                            |

| 公告标识符       | Microsoft 安全公告 MS08-058                                                                                                                                                                                                         |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Internet Explorer 的累积性安全更新 (956390)**](http://technet.microsoft.com/security/bulletin/ms08-058)                                                                                                                          |
| **摘要**         | 此安全更新可消除五个秘密报告的漏洞以及一个公开披露的漏洞。 如果用户使用 Internet Explorer 查看特制网页，这些漏洞可能允许泄露信息或远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                        |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                    |
| **受影响的软件** | **Microsoft Windows、Internet Explorer。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                       |

| 公告标识符       | Microsoft 安全公告 MS08-059                                                                                                                                                                                                                                                                                                |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Host Integration Server RPC 服务中的漏洞可能允许远程执行代码 (956695)**](http://technet.microsoft.com/security/bulletin/ms08-059)                                                                                                                                                                                       |
| **摘要**         | 此安全更新解决了 Microsoft Host Integration Server 中一个秘密报告的漏洞。 如果攻击者向受影响的系统发送特制的远程过程调用 (RPC) 请求，则该漏洞可能允许远程执行代码。 遵循最佳方案并将 SNA RPC 服务帐户配置为对系统具有较少用户权限的客户所受到的影响可能比将 SNA RPC 服务帐户配置为具有管理用户权限的客户所受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                       |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                               |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                                                                                                       |
| **受影响的软件** | **Microsoft Host Integration Server。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                 |

| 公告标识符       | Microsoft 安全公告 MS08-057                                                                                                                                                                                                                                                                                                                      |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Excel 中的漏洞可能允许远程执行代码 (956416)**](http://technet.microsoft.com/security/bulletin/ms08-057)                                                                                                                                                                                                                             |
| **摘要**         | 此安全更新解决了 Microsoft Office Excel 中三个秘密报告的漏洞，如果用户打开特制的 Excel 文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                             |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                     |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                                                                                                               |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                        |

重要 (6)
--------


| 公告标识符       | Microsoft 安全公告 MS08-066                                                                                                                                                                           |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft 辅助功能驱动程序中的漏洞可能允许特权提升 (956803)**](http://technet.microsoft.com/security/bulletin/ms08-066)                                                                            |
| **摘要**         | 此安全更新可解决 Microsoft 辅助功能驱动程序中一个秘密报告的漏洞。 成功利用此漏洞的本地攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                  |
| **漏洞的影响**   | 特权提升                                                                                                                                                                                              |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                      |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                            |

| 公告标识符       | Microsoft 安全公告 MS08-061                                                                                                                                                       |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows 内核中的漏洞可能允许特权提升 (954211)**](http://technet.microsoft.com/security/bulletin/ms08-061)                                                                      |
| **摘要**         | 此安全更新可解决 Windows 内核中一个公开披露和两个秘密报告的漏洞。 成功利用这些漏洞的本地攻击者可以完全控制受影响的系统。 匿名用户无法利用这些漏洞，也无法以远程方式利用这些漏洞。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                              |
| **漏洞的影响**   | 特权提升                                                                                                                                                                          |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                  |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                        |

| 公告标识符       | Microsoft 安全公告 MS08-062                                                                                                                                                                                                                                                                                                                                   |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Internet 打印服务中的漏洞可能允许远程执行代码 (953155)**](http://technet.microsoft.com/security/bulletin/ms08-062)                                                                                                                                                                                                                                 |
| **摘要**         | 此更新解决了 Windows Internet 打印服务中一个秘密报告的漏洞，该漏洞可能允许在当前用户的上下文中远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                          |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                  |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                                                                                                                                              |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                    |

| 公告标识符       | Microsoft 安全公告 MS08-063                                                                                                                                                                                                  |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**SMB 中的漏洞可能允许远程执行代码 (957095)**](http://technet.microsoft.com/security/bulletin/ms08-063)                                                                                                                     |
| **摘要**         | 此安全更新解决了 Microsoft 服务器消息块 (SMB) 中一个秘密报告的漏洞。 该漏洞可能允许在共享文件或文件夹的服务器上远程执行代码。 成功利用这些漏洞的攻击者可以安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                         |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                 |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                             |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                   |

| 公告标识符       | Microsoft 安全公告 MS08-064                                                                                                                                                                                                                                       |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**虚拟地址描述符操作中的漏洞可能允许特权提升 (956841)**](http://technet.microsoft.com/security/bulletin/ms08-064)                                                                                                                                                |
| **摘要**         | 此安全更新可解决虚拟地址描述符中一个秘密报告的漏洞。 如果用户运行特制的应用程序，则该漏洞可能允许特权提升。 成功利用此漏洞并经过身份验证的攻击者可以在受影响的系统上获得特权提升。 攻击者随后可安装程序；查看、更改或删除数据；或者创建拥有完全管理权限的新帐户。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                              |
| **漏洞的影响**   | 特权提升                                                                                                                                                                                                                                                          |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                                                  |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                        |

| 公告标识符       | Microsoft 安全公告 MS08-065                                                                                                                                             |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**消息队列中的漏洞可能允许远程执行代码 (951071)**](http://technet.microsoft.com/security/bulletin/ms08-065)                                                            |
| **摘要**         | 此安全更新解决了 Microsoft Windows 2000 系统上消息队列服务 (MSMQ) 中一个秘密报告的漏洞。 此漏洞可能允许在启用了 MSMQ 服务的 Microsoft Windows 2000 系统上远程执行代码。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                    |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                            |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                        |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                              |

中等 (1)
--------


| 公告标识符       | Microsoft 安全公告 MS08-056                                                                                                                                                                                                                        |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Office 中的漏洞可能允许信息泄露 (957699)**](http://technet.microsoft.com/security/bulletin/ms08-056)                                                                                                                                  |
| **摘要**         | 此安全更新解决了 Microsoft Office 中一个秘密报告的漏洞。 如果用户点击特制的 CDO URL，该漏洞可能允许信息泄露。 成功利用此漏洞的攻击者可以在用户的浏览器中注入客户端脚本，该脚本可能欺骗内容、泄露信息或执行用户可以在受影响的网站上执行的任何操作。 |
| **最高严重等级** | [中等](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                               |
| **漏洞的影响**   | 信息泄露                                                                                                                                                                                                                                           |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                                 |
| **受影响的软件** | **Microsoft Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                          |

利用指数
--------

**我如何使用该表呢？**

使用该表了解为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 关于这些等级的含义以及如何确定这些等级的更多信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/en-us/security/cc998259.aspx)。

| 公告 ID                                                             | 公告标题                                                                                                                             | CVE ID        | 利用指数评估                                                                              | 重要注意事项                                                                                                                                                                |
|---------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------|-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [MS08-056](http://technet.microsoft.com/security/bulletin/ms08-056) | [Microsoft Office 中的漏洞可能允许信息泄露 (957699)](http://technet.microsoft.com/security/bulletin/ms08-056)                        | CVE-2008-4020 | [2 - 可能的不一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 攻击者可能创建漏洞检测代码。 不过，其严重性影响有限，因为该漏洞仅允许在特定 Web 应用程序情形的对话中进行欺骗。 因此，攻击者较少利用这种方法。                               |
| [MS08-057](http://technet.microsoft.com/security/bulletin/ms08-057) | [Microsoft Excel 中的漏洞可能允许远程执行代码 (956416)](http://technet.microsoft.com/security/bulletin/ms08-057)                     | CVE-2008-4019 | [1 - 可能的一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)   |                                                                                                                                                                             |
| [MS08-057](http://technet.microsoft.com/security/bulletin/ms08-057) | [Microsoft Excel 中的漏洞可能允许远程执行代码 (956416)](http://technet.microsoft.com/security/bulletin/ms08-057)                     | CVE-2008-3471 | [2 - 可能的不一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                             |
| [MS08-057](http://technet.microsoft.com/security/bulletin/ms08-057) | [Microsoft Excel 中的漏洞可能允许远程执行代码 (956416)](http://technet.microsoft.com/security/bulletin/ms08-057)                     | CVE-2008-3477 | [2 - 可能的不一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                             |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 的累积性安全更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                               | CVE-2008-2947 | （发布公告时公开）                                                                        |                                                                                                                                                                             |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 的累积性安全更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                               | CVE-2008-3472 | [1 - 可能的一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)   |                                                                                                                                                                             |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 的累积性安全更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                               | CVE-2008-3473 | [1 - 可能的一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)   |                                                                                                                                                                             |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 的累积性安全更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                               | CVE-2008-3475 | [2 - 可能的不一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                             |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 的累积性安全更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                               | CVE-2008-3474 | [3 - 不太可能被利用的代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)     |                                                                                                                                                                             |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Internet Explorer 的累积性安全更新 (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                               | CVE-2008-3476 | [3 - 不太可能被利用的代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)     |                                                                                                                                                                             |
| [MS08-059](http://technet.microsoft.com/security/bulletin/ms08-059) | [Host Integration Server RPC Service 中的漏洞可能允许远程执行代码 (956695)](http://technet.microsoft.com/security/bulletin/ms08-059) | CVE-2008-3466 | [1 - 可能的一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)   | 尽管只有特定类型的企业客户可能安装 Host Integration Server，但是攻击者可能创建有效漏洞检测代码。                                                                            |
| [MS08-060](http://technet.microsoft.com/security/bulletin/ms08-060) | [Active Directory 中的漏洞可能允许远程执行代码 (957280)](http://technet.microsoft.com/security/bulletin/ms08-060)                    | CVE-2008-4023 | [2 - 可能的不一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx) | 可能触发导致拒绝服务情形的漏洞。 不过，由于无法控制所需的写入地址，创建漏洞检测代码来利用远程执行代码很困难。                                                               |
| [MS08-061](http://technet.microsoft.com/security/bulletin/ms08-061) | [Windows 内核中的漏洞可能允许特权提升 (954211)](http://technet.microsoft.com/security/bulletin/ms08-061)                             | CVE-2008-2250 | [1 - 可能的一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)   |                                                                                                                                                                             |
| [MS08-061](http://technet.microsoft.com/security/bulletin/ms08-061) | [Windows 内核中的漏洞可能允许特权提升 (954211)](http://technet.microsoft.com/security/bulletin/ms08-061)                             | CVE-2008-2252 | [1 - 可能的一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)   | 针对多处理器系统创建有效漏洞检测代码的可能性最大。                                                                                                                          |
| [MS08-061](http://technet.microsoft.com/security/bulletin/ms08-061) | [Windows 内核中的漏洞可能允许特权提升 (954211)](http://technet.microsoft.com/security/bulletin/ms08-061)                             | CVE-2008-2251 | [3 - 不太可能被利用的代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)     | 触发漏洞是可能的，但要创建成功有效的漏洞检测代码非常困难。                                                                                                                  |
| [MS08-062](http://technet.microsoft.com/security/bulletin/ms08-062) | [Windows Internet 打印服务中的漏洞可能允许远程执行代码 (953155)](http://technet.microsoft.com/security/bulletin/ms08-062)            | CVE-2008-1446 | [1 - 可能的一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)   | 在有限的、目标明确的攻击实例中，发现了一致漏洞检测代码。 在所有平台上，尽管 Internet 打印协议 (IPP) 服务在默认情况下启用，但通过 IIS 访问该服务在默认情况下也要求身份验证。 |
| [MS08-063](http://technet.microsoft.com/security/bulletin/ms08-063) | [SMB 中的漏洞可能允许远程执行代码 (957095)](http://technet.microsoft.com/security/bulletin/ms08-063)                                 | CVE-2008-4038 | [2 - 可能的不一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                             |
| [MS08-064](http://technet.microsoft.com/security/bulletin/ms08-064) | [虚拟地址描述符操作中的漏洞可能允许特权提升 (956841)](http://technet.microsoft.com/security/bulletin/ms08-064)                       | CVE-2008-4036 | [2 - 可能的不一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                             |
| [MS08-065](http://technet.microsoft.com/security/bulletin/ms08-065) | [消息队列中的漏洞可能允许远程执行代码 (951071)](http://technet.microsoft.com/security/bulletin/ms08-065)                             | CVE-2008-3479 | [3 - 不太可能被利用的代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)     | 尽管可能发生信息泄露，但绝对不可能从内存中获取有用内容。 可能触发内存损坏问题，但要实现远程执行代码非常困难。                                                               |
| [MS08-066](http://technet.microsoft.com/security/bulletin/ms08-066) | [Microsoft Ancillary Function Driver 中的漏洞可能允许特权提升 (956803)](http://technet.microsoft.com/security/bulletin/ms08-066)     | CVE-2008-3464 | [1 - 可能的一致漏洞检测代码](http://technet.microsoft.com/en-us/security/cc998259.aspx)   |                                                                                                                                                                             |

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
<th>
</th>
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
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
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4 上的 Active Directory](https://www.microsoft.com/download/details.aspx?familyid=8ed7bb9a-4b26-49d7-8c14-60226d2bc20d)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=257c0478-56dd-42eb-a90e-607d01613db7)  
（严重）  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=02390258-08e9-4b75-960d-be081b749558)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=3a6165a6-d7e7-4526-9291-290caf0639b4)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=8163d1f6-feb5-4f39-8134-3ed42326b822)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=9ed29c3a-0682-4586-bbc2-a73deaa18e4c)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=899e2728-2433-4ccb-a195-05b5d65e5469)  
（重要）
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=a7f0f47b-b1ee-4516-9fbf-bf8e579963d0)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4e73de2b-05e6-4901-9bac-46d8f469e635)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b16d9dac-c430-4dd8-a1e5-9a614801f1d9)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7718bf14-c26c-43f3-be67-4c79ab5b2607)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e7ef571f-c9e8-4e14-95a3-3eeaec55b784)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2f7e5981-6eef-4f08-86c0-c6a7607ea5d0)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=25997b73-a640-49c1-b19e-768a18bbe22c)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=234c05fb-988b-4e02-aab6-bb23e447df3d)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ccf7a3e3-ec30-4b95-9a86-00032301513c)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5b607efc-c6fb-4079-8478-e4f3262386d3)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b06d3a02-b6e4-4d40-913a-3759a31f20f3)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3ae4b913-bff0-4974-b198-828ca10d2a87)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4e1675eb-6b06-48e9-9765-23a2c7737bdc)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=50fae854-0bde-46f8-9444-b9e0d9bfecad)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=ae8d22d5-20aa-471d-a423-f54c9d75febe)  
（中等）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=feaf2adf-7892-4dbf-a147-db4d5dbe52f3)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ee88ff2d-1b12-4f4c-a081-9f27a6fba074)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6e696762-d652-4a8f-ab8f-622f9746c320)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=437a9b68-6a0c-48c8-9348-0d6fda48aa21)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dbbebb3f-f1c7-402c-bd16-6f88da0d042c)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e8ef3d5f-dd8e-4945-92cd-9d3e30b16667)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
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
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=07fc88c4-2571-4a4d-b573-ae576798ab4c)  
（中等）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=319dba34-07ca-47f9-a1e9-20df2df7966b)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ab4d94d3-458c-4946-ab7f-03a279629d25)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=57ca28ea-e5e1-4191-a3d6-84aa90a3d668)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d3df6508-a568-449d-ac97-fbf3f97b98ef)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=989ac6f1-515c-467d-a200-2aabe66d9319)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c2e754f9-086a-494c-bc19-5feed7df8b65)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
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
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b68937af-f04a-4d1e-9d7f-ec92af5194de)  
（中等）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=47381d91-4a14-4a09-96b3-3345155df52d)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=63234f85-6e5d-4ef6-b7cf-d1d2c78a5517)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1e6c3f81-85bb-48e6-a5af-635a7e540c93)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=748f54f1-40b9-407c-9819-909061b53743)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=91589cfb-15ba-4dd2-9e3b-107899fbcba6)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=5a3832ec-3f8f-42c1-a603-b1330d527547)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4756e04b-6e1c-4d78-a3c0-17f6b4b97975)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3483b400-cedc-441f-ba8e-594e3df89190)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3d6290d8-1745-4bc0-9ca9-eeb1ad0be4a5)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=72dd6015-25d1-45f4-a769-88ac43074b44)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b4212db5-093e-497d-b999-2e3780f9f7c2)  
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
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=bd19c72b-4f83-47ab-93be-d2c286e732c4)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=905ab030-14a5-4a3d-aa11-e8f957f6a1ea)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a33c833c-d5c5-4e37-8f89-7b9079f92e59)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f793af16-5464-4db1-a42b-1c5f17c538ed)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c20808cb-c30a-4b53-91e5-810eb6b4b2e3)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ec73f416-2204-42d6-8932-c96578ac819f)\*\*  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=8b97114a-71aa-47a2-b9e7-f4e158c18c80)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=3d6290d8-1745-4bc0-9ca9-eeb1ad0be4a5)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=cf6744e6-b54c-40f6-a78d-7ba9453133c0)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=ec9eeb82-0497-4c55-94bb-9a47cb3521b4)\*  
（重要）
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
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=baacd1c2-9764-4fea-bd4d-c49791974fef)\*\*  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=6e641db2-90c8-458f-9795-3e46b70a5203)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=a33c833c-d5c5-4e37-8f89-7b9079f92e59)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=223236e8-7b19-4b47-8a90-bfc35eb9318a)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=0bc178b8-f8ae-4f41-8f88-fb6a75be1bca)\*  
（重要）
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
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=250a45dd-7eae-4440-bd10-02a703940976)  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b6546e1c-bf7b-4354-8574-6c16fa707de0)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=31783e88-76e2-4bc6-b4ae-308443c6d223)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=077b697c-04a0-45bd-b08c-331d5c30cb47)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=0af72663-4945-4916-8c55-090ba4d82793)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**\*Windows Server 2008 服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 的受支持版本，严重等级相同，无论安装 Windows Server 2008 时是否使用“服务器核心”安装选项。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*Windows Server 2008 服务器核心安装不受影响。** 如果安装 Windows Server 2008 时使用“服务器核心”安装选项，则这些漏洞不会影响 Windows Server 2008 的受支持版本。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

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
[**MS08-057**](http://technet.microsoft.com/security/bulletin/ms08-057)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://technet.microsoft.com/security/bulletin/ms08-056)
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
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=1b2740e0-ecdd-48ca-84e0-eb187c31eb16)  
(KB955461)  
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
[Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=27cedef1-c47c-472c-a343-cd9b4ebc2bba)  
(KB955464)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b1aee2d5-bfa0-40e3-91b6-98bf65524e8c)  
(KB956464)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 和 Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368)  
(KB955466)  
（重要）  
[Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368)  
(KB955466)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System 和 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[Excel 2007](https://www.microsoft.com/download/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f)  
(KB955470)  
（重要）  
[Excel 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f)  
(KB955470)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
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
[**MS08-057**](http://technet.microsoft.com/security/bulletin/ms08-057)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://technet.microsoft.com/security/bulletin/ms08-056)
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
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ba4fa21a-7e01-4ef8-9b9f-9d51d00ef094)  
(KB958312)  
（重要）
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
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=e70c5ae0-2858-46de-81f8-dcd1786656b7)  
(KB958267)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=2a8d9a3b-b8a4-43b6-82a6-a2e7d16ae11d)  
(KB958304)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
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
[**MS08-057**](http://technet.microsoft.com/security/bulletin/ms08-057)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://technet.microsoft.com/security/bulletin/ms08-056)
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
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](https://www.microsoft.com/download/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b)  
(KB955468)  
（重要）  
[Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b)  
(KB955468)  
（重要）  
[Microsoft Office Excel Viewer](https://www.microsoft.com/download/details.aspx?familyid=83c88444-75b8-44d1-b280-3671394ade45)  
(KB955935)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9)  
(KB955936)  
（重要）  
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9)  
(KB955936)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007](https://www.microsoft.com/download/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535)\*  
(KB955937)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535)\*  
(KB955937)  
（重要）  
[Microsoft Office SharePoint Server 2007 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f)\*  
(KB955937)  
（重要）  
[Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f)\*  
(KB955937)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

\*此更新适用于安装了 Excel Services 的服务器，例如 Microsoft Office SharePoint Server 2007 Enterprise 和 Microsoft Office SharePoint Server 2007 For Internet Sites 的默认配置。 Microsoft Office SharePoint Server 2007 Standard 不包含 Excel Services。

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
Microsoft Host Integration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-059**](http://technet.microsoft.com/security/bulletin/ms08-059)
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
Microsoft Host Integration Server 2000
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2000 Service Pack 2（服务器）](https://www.microsoft.com/download/details.aspx?familyid=11cca58b-59a4-4e93-9eb1-19b07c290a10)  
（严重）  
[Microsoft Host Integration Server 2000 管理员客户端](https://www.microsoft.com/download/details.aspx?familyid=41b49291-1231-4e23-aef7-818207453d56)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 （服务器）](https://www.microsoft.com/download/details.aspx?familyid=9ca255ed-9334-4848-af94-49ef3078cdc0)  
（严重）  
[Microsoft Host Integration Server 2004 Service Pack 1（服务器）](https://www.microsoft.com/download/details.aspx?familyid=eca756a1-ca56-4481-b23c-53c159a4e08c)  
（严重）  
[Microsoft Host Integration Server 2004（客户端）](https://www.microsoft.com/download/details.aspx?familyid=92cb54e7-f4ff-40a4-99cb-6257c4d8d4cd)  
（严重）  
[Microsoft Host Integration Server 2004 Service Pack 1（客户端）](https://www.microsoft.com/download/details.aspx?familyid=d776515c-09aa-4a04-876d-606bfc26a006)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2006（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=1ae79da3-ec17-4d4b-8011-d777a237ac93)  
（严重）  
[Microsoft Host Integration Server 2006（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=05da4540-4976-458a-a612-7385d78695a2)  
（严重）
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

-   [NetAgent Co., Ltd.](http://www.netagent.co.jp/) 报告了 MS08-056 中描述的问题
-   [iDefense](http://labs.idefense.com/) 的 Joshua J. Drake 报告了 MS08-057 中描述的问题
-   Wushi 与 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 MS08-057 中描述的问题
-   [Labo Skopia](http://www.laboskopia.com/) 的 Lionel d'Hauenens 与 [iDefense VCP](http://labs.idefense.com/) 合作，报告了 MS08-057 中描述的问题
-   David Bloom 报告了 MS08-058 中描述的问题
-   Gregory Rubin 报告了 MS08-058 中描述的问题
-   [Ivan Fratric](http://ifsec.blogspot.com/) 与 [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 MS08-058 中描述的问题
-   [n.runs](http://www.nruns.com/) 的 Thierry Zoller 报告了 MS08-058 中描述的问题
-   [Composica](http://www.composica.com/) 的 Lee Dagon 报告了 MS08-058 中描述的问题
-   [Harmony Security](http://www.harmonysecurity.com/) 的 Stephen Fewer 与 [iDefense VCP](http://labs.idefense.com/) 一起报告了 MS08-059 中描述的问题
-   [nCircle](http://www.ncircle.com/) 的 Paul Miseiko 报告了 MS08-060 中描述的问题
-   [iShadow](http://www.ishadow.com/) 的 Paul Caton 报告了 MS08-061 中描述的问题
-   [SkyRecon](http://www.skyrecon.com/) 的 Thomas Garnier 报告了 MS08-061 中描述的问题
-   [CERT/CC](http://www.cert.org/) 报告了 MS08-062 中描述的问题
-   [Codenomicon](http://www.codenomicon.com/) 的 Joshua Morin 报告了 MS08-063 中描述的问题
-   [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 报告了 MS08-065 中描述的问题
-   [SkyRecon](http://www.skyrecon.com/) 的 Fabien Le Mentec 报告了 MS08-066 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2008 年 10 月 14 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
