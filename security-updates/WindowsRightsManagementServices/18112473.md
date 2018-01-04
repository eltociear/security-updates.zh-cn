---
TOCTitle: 添加 Extranet 群集 URL
Title: 添加 Extranet 群集 URL
ms:assetid: '12c83186-ce9e-4100-bbd1-d87a885331c7'
ms:contentKeyID: 18112473
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc720193(v=WS.10)'
---

添加 Extranet 群集 URL
======================

要执行该过程，必须使用正在访问的计算机上是“管理员”组成员的域用户帐户从本地登录到管理网站。“Domain Admins”组成员也可以执行该过程。作为一种最佳安全设置，可以考虑使用“**运行方式**”选项来执行该过程。

要打开“**全局管理**”页面，单击“**开始**”，依次选择“**所有程序**”、“**Windows RMS**”，然后单击“**Windows RMS 管理**”。

确保在域名系统 (DNS) 中注册 URL，验证其可以使用并可从 Internet 和 Extranet 进行访问。如果为 Web 服务文件启用了 SSL，则必须为群集 URL 指定 HTTPS。

如果是将 extranet 群集 URL 添加到已在使用中的 RMS 服务器，则当前 RMS 客户端必须获取新的客户端许可方证书，以便访问授权的 extranet 群集。

添加 Extranet 群集 URL
----------------------

#### 添加 Extranet 群集 URL

1.  打开“**全局管理**”页面，然后在要添加 Extranet 群集 URL 的网站旁边，单击“**在此网站上管理 RMS**”。

2.  在“**管理链接**”区域中，单击“**Extranet 群集的 URL 设置**”。

3.  在“**Extranet 群集的 URL**”区域中，指定希望作为外部用户获得许可证的来源的 URL。可以选择 HTTP 或 HTTPS。

4.  单击“**提交**”。
