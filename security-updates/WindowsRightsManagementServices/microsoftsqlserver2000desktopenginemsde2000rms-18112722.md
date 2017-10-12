---
TOCTitle: '安装 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) 为 RMS 提供数据库支持'
Title: '安装 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) 为 RMS 提供数据库支持'
ms:assetid: 'c9b9cd08-98c4-424f-b3fc-d685f57c002e'
ms:contentKeyID: 18112722
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc747667(v=WS.10)'
---

安装 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) 为 RMS 提供数据库支持
===============================================================================

安装 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) 为 RMS 提供数据库支持
-------------------------------------------------------------------------------

#### 安装 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) 为 RMS 提供数据库支持

1.  在要安装 Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) 的服务器上，使用属于本地“管理员”组的域帐户登录。

2.  从 [Microsoft 网站](http://www.microsoft.com/) (http://www.microsoft.com/) 下载 MSDE 2000 并将它保存至计算机中的某个位置。

3.  运行 MSDE2000A.exe 文件，将 MSDE 2000 安装包提取到一个文件夹中。默认情况下，此文件夹命名为 MSDERelA，但是您可以指定其他名称。

4.  打开命令提示符窗口并导航至保存 MSDE 2000 安装程序的位置。

5.  键入以下命令以安装 Microsoft SQL Server 2000 Desktop Engine 应用程序，该命令中包含使用 RMS 所需的正确配置，并用所选的强密码替换 *password*：

    **Setup.exe /i setup\\sqlrun10.msi INSTANCENAME=RMS DISABLEAGENTSTARTUP=1 SAPWD=***password*

    | ![](images/Cc747667.Important(WS.10).gif)要点                                                                           |
    |------------------------------------------------------------------------------------------------------------------------------------------------------|
    | 安装 MSDE 服务后，必须启动它。您可以从“**控制面板**”的“**服务**”中启动该服务。建议将此服务配置为自动启动，以确保在 RMS 运行时，MSDE 数据库始终可用。 |

在安装支持 RMS 配置数据库的数据库之前，不要在服务器上设置 RMS。

建议仅在测试环境中使用 Microsoft SQL Server Desktop Engine 支持 RMS 数据库，原因是 Microsoft SQL Server Desktop Engine 不包括完全操作和支持企业范围数据库所必需的工具。另外，由于 MSDE 不支持远程网络，因此必须将它与 RMS 安装在同一台服务器上，并且不能将其他 RMS 服务器添加至 RMS 群集。Microsoft SQL Server Desktop Engine 的使用条款规定不能使用 SQL Server 客户端工具对 Microsoft SQL Server Desktop Engine 数据库执行操作。由于此限制，您将无法备份和还原 RMS 配置数据库、查看日志信息或直接修改配置数据库中存储的数据。
