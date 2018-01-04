---
TOCTitle: 配置 Extranet URL
Title: 配置 Extranet URL
ms:assetid: '88fec9ff-c96c-4d20-8856-0485e7507572'
ms:contentKeyID: 18112662
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc747661(v=WS.10)'
---

配置 Extranet URL
=================

如果要在现有的 RMS 系统配置中支持 Extranet 用户，可以添加专用于 Extranet 的授权服务器或群集。

设置 Extranet 授权服务器时，可以为其指定群集的 URL，就象为任何 RMS 服务器指定 URL 一样。指定的 URL 通常是 Extranet 用户无法访问的内部 URL。这是 RMS 用于服务发现的 URL。它必须是组织中的有效 URL。

如果是将 Extranet 群集 URL 添加到已在使用中的 RMS 服务器，则当前 RMS 客户端必须获取新的客户端许可方证书，以便访问授权的 Extranet 群集。

有关详细信息，请参阅本主题中稍后的“[添加 Extranet 群集 URL](https://technet.microsoft.com/12c83186-ce9e-4100-bbd1-d87a885331c7)”。
