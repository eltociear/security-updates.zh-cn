---
TOCTitle: 更改 Active Directory 缓存设置
Title: 更改 Active Directory 缓存设置
ms:assetid: '8789a7a5-2065-4fae-9104-e0a70f1f2fb6'
ms:contentKeyID: 18112634
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc747586(v=WS.10)'
---

更改 Active Directory 缓存设置
==============================

注册表中的设置指定了可存储在 Active Directory 缓存中的项数。要缩短客户端请求的响应时间，可以修改这些设置。有关详细信息，请参阅本主题中前面的“优化目录服务性能”。此外，您还可以指定存储在缓存中的信息的有效期。

在运行 Windows Server 2003 32 位版本的计算机上，以下注册表项是用于设置缓存的注册表项的完全子项路径：

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0\\DirectoryServices**

在运行 Windows Server 2003 64 位版本的计算机上，以下注册表项是用于设置缓存的注册表项的完全子项路径：

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0\\DirectoryServices**

下表列出了用于控制内存缓存行为的注册表项。



 
<p></p>

<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >名称</th>
<th style="border:1px solid black;" >类型</th>
<th style="border:1px solid black;" >默认值</th>
<th style="border:1px solid black;" >说明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">PrincipalCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">可存储在缓存中的主体及其电子邮件地址和 SID 的最大数目。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PrincipalCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">缓存的主体信息的有效期。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupIDCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">可存储在缓存中的组及其电子邮件地址和 SID 的最大数目。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupIDCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">缓存的组成员身份信息的有效期。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupMembershipCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">可存储在缓存中的组成员联系人的最大数目。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupMembershipCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">缓存的组成员联系人信息的有效期。</td>
</tr>
</tbody>
</table>

<p></p>

  
> [!CAUTION]  
> 错误编辑注册表可能会严重损坏系统。更改注册表之前，应备份计算机中的所有重要数据。 
  

> [!NOTE]  
> **PrincipalCacheExpireMinutes**、**GroupIDCacheExpireMinutes**、**GroupMembershipCacheExpireMinutes** 和 **ContactMembersofGroupCacheExpireMinutes** 注册表项还控制存储在数据库服务器上的目录服务中的本地 Active Directory 缓存的缓存到期时间。 
