---
TOCTitle: 替换 Active Directory 服务发现
Title: 替换 Active Directory 服务发现
ms:assetid: '9d97e7fb-5b05-4853-ad7b-6cc82b9729f0'
ms:contentKeyID: 18112665
ms:mtpsurl: 'https://technet.microsoft.com/zh-cn/library/Cc747614(v=WS.10)'
---

替换 Active Directory 服务发现
==============================

RMS 服务和客户端通过先在本地注册表中查找来发现服务位置。如果注册表中的某些项没有值，RMS 服务和客户端会在 Active Directory 中查找服务连接点 (SCP)。这意味着如果您在服务器或客户端注册表中键入特定项，则可以替代默认的 Active Directory 发现设置。

> [!NOTE]  
> 如果配置了 RMS 根群集，以便不在 Active Directory 中发布 SCP，则您可以使用这些项来使您的 RMS 客户端指向正确的位置。 

本节描述了注册表项，并提供有关如何创建这些项的详细信息。

替代仅授权群集注册子过程的服务发现
----------------------------------

如果您正在设置仅授权群集，并且希望向在仅授权群集的 Active Directory 林中部署的根群集以外的其他根群集通过注册子过程注册它，则必须替代注册子过程和帐户认证服务的发现。

#### 注册表项描述

下列注册表项用于替代注册子过程和帐户认证服务。

-   **SubEnrollmentURL**。此项指定当授权服务器在请求其服务器许可方证书时使用的根群集的路径。
-   **GicURL**。此项指定此仅授权群集的帐户认证服务的路径。

#### 项详细信息

在运行 Windows Server 2003 32 位版本的计算机上，仅授权群集注册子过程的服务发现条目的完整注册表子项路径为：

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0**

在运行 Windows Server 2003 64 位版本的计算机上，仅授权群集注册子过程的服务发现条目的完整注册表子项路径为：

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0**

下表列出了可以添加以替代服务发现的项。



 
<p></p>

<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >名称</th>
<th style="border:1px solid black;" >类型</th>
<th style="border:1px solid black;" >值</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SubEnrollmentURL</td>
<td style="border:1px solid black;">字符串</td>
<td style="border:1px solid black;">http（或 https）://<em>服务器名称</em>/_wmcs/certification/subenrollservice.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GicURL</td>
<td style="border:1px solid black;">字符串</td>
<td style="border:1px solid black;">http（或 https）://<em>服务器名称</em>/_wmcs/certification/certification.asmx</td>
</tr>
</tbody>
</table>

<p></p>

  
替代用于发布的客户端服务发现  
----------------------------
  
如果您的用户将发布其计算机中的内容，您可能需要根据在您的企业中使用的拓扑来替代用于发布的服务器的位置。用于发布的服务器的位置通常由客户端使用 Active Directory 来发现。通过在客户端计算机上添加合适的注册表项，客户端将绕过这些方法，改为使用您在注册表项值中指定的 URL。
  
> [!NOTE]  
> 本节中列出的客户端替代应作为项创建，而不应作为个别条目创建。这些项的值应在每个项的默认条目中创建。 
  
#### 注册表项描述
  
下列注册表项可用于替代 RMS 群集的自动发现。
  
-   **Activation**。此注册表项定义计算机激活服务的 URL。如果您运行的是带 Service Pack 1 或更高版本的 RMS 客户端，则不再使用此注册表项。  
-   **EnterprisePublishing**。此注册表项定义您希望将此客户端用于许可证请求的 RMS 安装的 URL。  
-   **CloudPublishing**。此注册表项定义在客户端无权访问 RMS 安装但可以访问 Internet 时可以使用的 Microsoft 主持的授权服务的 URL。
  
#### 项详细信息
  
用于发布的客户端服务发现条目的完整注册表子项路径为：
  
**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\MSDRM\\ServiceLocation\\**
  
下表列出了您可以在 RMS 客户端计算机上添加以替代服务发现的注册表项。
  


 
<p></p>

<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >名称</th>
<th style="border:1px solid black;" >类型</th>
<th style="border:1px solid black;" >值</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Activation</td>
<td style="border:1px solid black;">字符串</td>
<td style="border:1px solid black;">http（或 https）://<em>RMS 群集名称</em>/_wmcs/Certification，其中<em>RMS 群集名称</em>是 RMS 群集的名称。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">EnterprisePublishing</td>
<td style="border:1px solid black;">字符串</td>
<td style="border:1px solid black;">http（或 https）://<em>RMS 群集名称</em>/_wmcs/Licensing，其中 <em>RMS 群集名称</em>是 RMS 群集的名称。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CloudPublishing</td>
<td style="border:1px solid black;">字符串</td>
<td style="border:1px solid black;">http（或 https）://<em>FQDN 群集名称</em>/_wmcs/Licensing，其中 <em>FQDN 群集名称</em>是 RMS 群集的完全限定的域名。</td>
</tr>
</tbody>
</table>

<p></p>

  
我们建议您使用 Systems Management Server 或组策略来实施这些注册表项，以确保您企业中的所有客户端均使用正确的发布服务器。
  
> [!CAUTION]    
> 注册表编辑不当可能会严重损坏您的系统。在更改注册表之前，应备份计算机上任何有价值的数据。 
  
可以使用示例注册表文件 (.reg) 来在 RMS 群集中的每台服务器上导入正确的注册表项。
  
**在 RMS 群集中的每台服务器上导入正确的注册表项**  
1.  将下列示例注册表文件复制到记事本。

    ```
    Windows Registry Editor Version 5.00

    [HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation]

    [HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\Activation]

    @="http://<RMS_cluster_name>/_wmcs/certification"

    [HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\EnterprisePublishing]

    @="http://<RMS_cluster_name>/_wmcs/licensing"
    ```

2.  使用 RMS 群集的名称替换 &lt;RMS 群集名称&gt;。
  
3.  使用 .reg 文件扩展名保存文件。
  
4.  在 Windows 资源管理器中双击该文件的名称。
  
5.  如果出现“用户账户控制”对话框，请确认所显示的是您想要执行的操作，然后单击“继续”。. 当出现提示询问您是否要将信息添加到注册表时，请单击“是”。
