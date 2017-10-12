---
TOCTitle: RMS 的 Internet 信息服务支持
Title: RMS 的 Internet 信息服务支持
ms:assetid: 'bd4dc69f-1e4e-4e95-9ae2-c925d8a14d4c'
ms:contentKeyID: 18112701
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc747649(v=WS.10)'
---

RMS 的 Internet 信息服务支持
============================

主 RMS 服务是通过一组 ASP .NET Web 服务来提供的。这些 Web 服务可以在 Microsoft® Internet 信息服务 (IIS) 上运行。在设置服务器的过程中，RMS 将在 IIS 中建立虚拟目录。Web 服务的应用程序文件将安装在这些虚拟目录中。

在设置服务器的过程中，您可以从该服务器的现有网站列表中选择要在其下建立虚拟目录的网站。在设置服务器之前，您可能要为 RMS 创建一个专用网站。这样，您就可以针对具体的 RMS 部署来配置身份验证和访问限制。

默认情况下，Web 服务文件和虚拟目录受随机访问控制列表 (DACL) 的保护，以避免未经授权的用户访问其功能。这些项的访问控制项 (ACE) 如下所示：

-   管理员组具有完全控制权限
-   本地系统具有完全控制权限
-   RMS 服务组具有读取和执行权限
-   来宾和用户具有读取和执行、列出文件夹内容以及读取权限
-   不允许匿名访问

下表列出了 IIS 中创建的虚拟目录以及安装在虚拟目录中的服务。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >虚拟目录</th>
<th style="border:1px solid black;" >服务</th>
<th style="border:1px solid black;" >Web 服务文件</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">_wmcs</td>
<td style="border:1px solid black;">这是 RMS 群集管理虚拟目录</td>
<td style="border:1px solid black;">不适用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Certification</td>
<td style="border:1px solid black;">此虚拟目录包含支持 RMS 认证的服务</td>
<td style="border:1px solid black;">不适用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">激活代理</td>
<td style="border:1px solid black;">Activation.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">帐户认证</td>
<td style="border:1px solid black;">Certification.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">预认证</td>
<td style="border:1px solid black;">Precertification.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">服务定位器</td>
<td style="border:1px solid black;">ServiceLocator.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">服务器</td>
<td style="border:1px solid black;">Server.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">服务器认证</td>
<td style="border:1px solid black;">ServerCertification.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">移动设备认证</td>
<td style="border:1px solid black;">MobileDeviceCertfication.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">注册</td>
<td style="border:1px solid black;">SubEnrollService.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">授权</td>
<td style="border:1px solid black;">此虚拟目录包含支持 RMS 授权的服务</td>
<td style="border:1px solid black;">不适用</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">授权</td>
<td style="border:1px solid black;">License.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">发布</td>
<td style="border:1px solid black;">Publish.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">服务器</td>
<td style="border:1px solid black;">Server.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">服务定位器</td>
<td style="border:1px solid black;">ServiceLocator.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Admin</td>
<td style="border:1px solid black;">此虚拟目录包含支持 RMS 管理的服务</td>
<td style="border:1px solid black;">不适用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">管理</td>
<td style="border:1px solid black;">AdminSvc.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DrmRemote</td>
<td style="border:1px solid black;">.NET Remoting 接口</td>
<td style="border:1px solid black;">不适用</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DirectoryServices</td>
<td style="border:1px solid black;">这是 DrmRemote 的子目录</td>
<td style="border:1px solid black;">不适用</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747649.note(WS.10).gif)注意                                                                                                                                                                                                                                                                  |  
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 管理服务的限制比其他 Web 服务更为严格，因为其提供的接口可用于配置 RMS。因此，用户组的成员无法访问管理服务。此外，还可启用 IP 筛选功能仅将访问权限授予本地计算机。 客人没有访问 DirectoryServices 虚拟目录的权限。 服务定位器服务还将完全控制权限授予网络服务帐户。 要设置授权服务器，必须更改默认的 ACE，以便允许 RMS 管理员进行访问。 |
