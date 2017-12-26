---
TOCTitle: Service Pack 2 中的新增功能
Title: Service Pack 2 中的新增功能
ms:assetid: 'a944cb73-d900-42bb-b7aa-92916dead408'
ms:contentKeyID: 18112684
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc747629(v=WS.10)'
---

Service Pack 2 中的新增功能
===========================

Rights Management Services (RMS) Service Pack 2 (SP2) 提供对下列功能的支持：

-   **对 Microsoft® SQL Server™ 2005 的本机支持**。在 RMS 的以前版本中，需要解决方法才能将 RMS 与 SQL Server 2005 配合使用。有关此解决方法的信息，请参阅 Microsoft 知识库文章 913372 ([http://go.microsoft.com/fwlink/?LinkId=68638](http://go.microsoft.com/fwlink/?linkid=68638))（页面可能为英文）。在 RMS SP2 中，已解决此问题。
-   **Microsoft Office SharePoint® Server 2007**。在此版本中，支持 Office SharePoint Server 2007。Office SharePoint Server 2007 文档库在下载文档时根据 Office SharePoint Server 2007 权限自动将 RMS 权限应用于这些文档。这通过在 Office SharePoint Server 2007 服务器上安装 RMS SP2 客户端实现。建议您不要在同一台计算机上安装 RMS SP2 服务器和 Office SharePoint Server 2007。
-   **提高了将消息写入日志记录数据库的安全性**。在此版本中，从 RMS 服务器到 RMS 日志记录数据库的所有消息队列消息都已经过数字签名。
-   **更大的服务器批处理大小**。在此版本中，启用了 RMS 的应用程序现在能够通过单个许可证请求将不同用户帐户的多个使用许可证检索到 RMS 服务器。这通过降低同一部分受权限保护内容的多个许可证请求的开销来提高性能。
-   **增强了跨林组扩展**。在此版本中，RMS 跨林组扩展通过简单对象访问协议 (SOAP) 向 RMS 服务器上运行的新 ASP.NET Web 服务发出请求来实现。
