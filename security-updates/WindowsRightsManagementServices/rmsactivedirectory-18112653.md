---
TOCTitle: RMS 的 Active Directory 支持
Title: RMS 的 Active Directory 支持
ms:assetid: '9589127d-19b3-44f1-b7a1-01992e78218a'
ms:contentKeyID: 18112653
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc747604(v=WS.10)'
---

RMS 的 Active Directory 支持
============================

RMS 使用 Active Directory 有以下几个目的：

-   **提供用户身份验证。**Active Directory 提供了可用于验证 RMS 用户身份的目录服务。有关身份验证和 RMS 的详细信息，请参阅本主题后面的“[RMS 安全模型](https://technet.microsoft.com/665db831-366d-4dca-9bb3-cc2912481fe1)”。
-   **解析组成员身份和个人用户帐户 ID。**Active Directory 提供了有关组成员身份的信息，当发布许可证将权限授予组而非个人用户帐户时，RMS 将使用这些信息来授予使用受 RMS 保护的内容的用户许可证。为减少提交给 Active Directory 的 LDAP 查询数，RMS 将获得的信息缓存到本地缓存以及集中的目录服务数据库中。有关详细信息，请参阅本主题前面的“[RMS Active Directory 缓存](https://technet.microsoft.com/c721a2eb-2fe9-4346-b426-3cc169b97265)”和“[RMS 目录服务数据库](https://technet.microsoft.com/6f6b8586-5d17-4a40-94a3-4dc738195301)”。
-   **存储 RMS 服务发现位置。**必须将服务请求（如用户许可证、发布许可证或授权服务器的注册子过程）发送到 Web 服务（响应请求）的可执行模块的 URL。所有服务请求都从对服务器 Web 服务 (Server.asmx) 的 URL 进行 Active Directory 查询开始，而该 Web 服务又为服务请求提供相应的 URL。有关详细信息，请参阅本主题后面的“[RMS 服务发布和服务发现](https://technet.microsoft.com/336c0d55-fd7f-4aa9-b3e6-bfd6565b1086)”。
