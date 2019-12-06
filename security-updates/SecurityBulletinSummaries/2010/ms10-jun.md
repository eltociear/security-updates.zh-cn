---
TOCTitle: 'MS10-JUN'
Title: 'Microsoft 安全公告摘要 (2010 年 6 月)'
ms:assetid: 'ms10-jun'
ms:contentKeyID: 61236945
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms10-jun(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2010 年 6 月)
=====================================

发布时间: 2010年6月8日 | 更新时间: 2010年6月9日

**版本:** 1.1

本公告摘要列出了 2010 年 6 月发布的安全公告。

对于 2010 年 6 月发布的安全公告，本公告摘要替代 2010 年 6 月 3 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2010 年 6 月 9 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 6 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427727&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

摘要
----

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件及其下载位置**”。

<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th>公告 ID</th>
<th>公告标题和摘要</th>
<th>最高严重等级和漏洞影响</th>
<th>重新启动要求</th>
<th>受影响的软件</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-033">MS10-033</a></td>
<td style="border:1px solid black;"><strong>媒体解压缩中的漏洞可能允许远程执行代码 (979902)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中两个秘密报告的漏洞。 如果用户打开一个特制的媒体文件或从网站或提供 Web 内容的任何应用程序接收特制的流式内容，这些漏洞则可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-034">MS10-034</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit 的累积性安全更新 (980195)</strong><br />
<br />  
此安全更新可解决 Microsoft 软件的两个秘密报告的漏洞。 对于 Microsoft Windows 2000、Windows XP、Windows Vista 和 Windows 7 的所有受支持版本，此安全更新的等级为“严重”；对于 Windows Server 2003、Windows Server 2008 和 Windows Server 2008 R2 的所有受支持版本，此安全更新的等级为“中等”。<br />  
<br />
如果用户使用 Internet Explorer 查看可实例化特定 ActiveX 控件的特制网页，则此漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 此更新也包括用于四个第三方 ActiveX 控件的 kill bit。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-035">MS10-035</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (982381)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中五个秘密报告的漏洞和一个公开披露的漏洞。 最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-032">MS10-032</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升 (979559)</strong><br />
<br />
此安全更新解决 Windows 内核模式驱动程序中两个公开披露的漏洞和一个秘密报告的漏洞。 如果用户查看用特制 TrueType 字体呈现的内容，则该漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-036">MS10-036</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的 COM 验证漏洞可能允许远程执行代码 (983235)</strong><br />
<br />
此安全更新解决了 Microsoft Office 中 COM 验证的一个秘密报告的漏洞。 如果用户使用受影响的 Microsoft Office 版本打开特制的 Excel、Word、Visio、Publisher 或 PowerPoint 文件，则此漏洞可能允许远程执行代码。 此漏洞无法通过电子邮件自动加以利用。 用户必须打开电子邮件附件，以电子邮件为载体的攻击才会得逞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-037">MS10-037</a></td>
<td style="border:1px solid black;"><strong>OpenType Compact 字体格式 (CFF) 驱动程序中的漏洞可能允许特权提升 (980218)</strong><br />
<br />
此安全更新解决了 Windows 的 OpenType Compact 字体格式 (CFF) 驱动程序中一个秘密报告的漏洞。 如果用户查看用特制 CFF 字体呈现的内容，则该漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。 匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-038">MS10-038</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel 中的漏洞可能允许远程执行代码 (2027452)</strong><br />
<br />
此安全更新可解决 Microsoft Office 中 14 个秘密报告的漏洞。 如果用户打开特制的 Excel 文件，较严重的漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-039">MS10-039</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint 中的漏洞可能允许特权提升 (2028554)</strong><br />
<br />
此安全更新解决了 Microsoft SharePoint 中一个公开披露和两个秘密报告的漏洞。 如果攻击者说服目标 SharePoint 站点的一位用户单击特制链接，最严重的漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft 服务器软件</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-040">MS10-040</a></td>
<td style="border:1px solid black;"><strong>Internet Information Services 中的漏洞可能允许远程执行代码 (982666)</strong><br />
<br />
此安全更新解决 Internet Information Services (IIS) 中的一个秘密报告的漏洞。 如果用户收到特制的 HTTP 请求，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-041">MS10-041</a></td>
<td style="border:1px solid black;"><strong>Microsoft .NET Framework 中的漏洞可能允许篡改 (981343)</strong><br />
<br />
此安全更新解决了 Microsoft .NET Framework 中一个公开披露的漏洞。 此漏洞可能允许篡改签名 XML 内容中的数据，而且检测不到。 在定制应用中，安全影响取决于具体应用程序中签名内容的使用方式。 签名 XML 消息通过安全通道（例如 SSL）传输的情况不受此漏洞影响。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
篡改</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按利用评估级别 和 CVE ID 降序顺序列出。 仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 漏洞标题                              | CVE ID                                                                           | 利用指数评估                                                                                      | 重要注意事项                                                                                             |  
|---------------------------------------------------------------------|---------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|  
| [MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032) | Win32k 窗口创建漏洞                   | [CVE-2010-0485](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0485) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039) | Help.aspx XSS 漏洞                    | [CVE-2010-0817](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0817) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 此漏洞最初在 [Microsoft 安全通报 983438](http://technet.microsoft.com/security/advisory/983438) 中报告。 |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 对象堆栈溢出漏洞                | [CVE-2010-0822](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0822) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 记录内存损坏漏洞                | [CVE-2010-0824](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0824) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 记录内存损坏漏洞                | [CVE-2010-1245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1245) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel RTD 内存损坏漏洞                | [CVE-2010-1246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1246) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 内存损坏漏洞                    | [CVE-2010-1247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1247) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel HFPicture 内存损坏漏洞          | [CVE-2010-1248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1248) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 内存损坏漏洞                    | [CVE-2010-1249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1249) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel EDG 内存损坏漏洞                | [CVE-2010-1250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1250) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel ADO 对象漏洞                    | [CVE-2010-1253](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1253) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Mac Office Open XML 权限漏洞          | [CVE-2010-1254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1254) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035) | 未初始化的内存损坏漏洞                | [CVE-2010-1259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1259) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035) | 内存损坏漏洞                          | [CVE-2010-1262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1262) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-036](http://technet.microsoft.com/security/bulletin/ms10-036) | COM 验证漏洞                          | [CVE-2010-1263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033) | 媒体解压缩漏洞                        | [CVE-2010-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1879) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                   |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035) | 跨域信息泄露漏洞                      | [CVE-2010-0255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0255) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 此漏洞最初在 [Microsoft 安全通报 980088](http://technet.microsoft.com/security/advisory/980088) 中报告。 |  
| [MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032) | Win32k 数据验证不正确漏洞             | [CVE-2010-0484](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0484) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                   |  
| [MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037) | OpenType CFF 字体驱动程序内存损坏漏洞 | [CVE-2010-0819](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0819) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 记录分析内存损坏漏洞            | [CVE-2010-0821](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0821) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 内存损坏漏洞                    | [CVE-2010-0823](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0823) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 记录堆栈损坏漏洞                | [CVE-2010-1251](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1251) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                   |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038) | Excel 字符串变量漏洞                  | [CVE-2010-1252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1252) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                   |  
| [MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032) | Win32k TrueType 字体分析漏洞          | [CVE-2010-1255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1255) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                   |  
| [MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040) | IIS 身份验证内存损坏漏洞              | [CVE-2010-1256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1256) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                   |  
| [MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033) | MJPEG 媒体解压缩漏洞                  | [CVE-2010-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1880) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                   |  
| [MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041) | XML 签名 HMAC 截断身份验证绕过漏洞    | [CVE-2009-0217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0217) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是欺骗和篡改漏洞                                                                                       |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035) | toStaticHTML 信息泄露漏洞             | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 此漏洞也影响 [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039)                         |  
| [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039) | toStaticHTML 信息泄露漏洞             | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 此漏洞也影响 [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)                         |  
| [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039) | SharePoint 帮助页拒绝服务漏洞         | [CVE-2010-1264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1264) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | （无）                                                                                                   |
  
受影响的软件和下载位置  
----------------------
  
<span></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
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
</tr>  
<tr>  
<th colspan="8" style="border:1px solid black;">  
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
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
无
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
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=60c8579b-1540-40d8-80a0-956edadd63ce)  
（重要）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow) (DirectX 9)](https://www.microsoft.com/download/details.aspx?familyid=a51c53bd-f9c1-4d53-8ed2-034fd57bc75a)<sup>[1]</sup>  
(KB975562)  
（严重）  
[Windows Media Format Runtime 9](https://www.microsoft.com/download/details.aspx?familyid=8417c0ac-bb6d-48f1-8237-77a4bdd8ccb2)<sup>[2]</sup>  
(KB978695)  
（严重）  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
（重要）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=1f929739-08a1-4faf-9ccf-5f1f43c5bb9e)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=d3955983-0079-476e-a488-99713097259c)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=0a6c09e5-c655-41a0-a133-78d55267a527)  
（没有严重等级）<sup>[1]</sup>  
[Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e2f27eeb-54be-40be-a00e-72867090b8e7)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=5d645891-31e9-42c4-b12b-eb351473fd0c)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
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
无
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
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=023a777a-3d83-4a4e-8029-da8b095b074b)  
（重要）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=e77d5af8-e8e0-425c-a809-4cf274e17cc5)  
(KB975562)  
（严重）  
仅限 Windows XP Service Pack 2：  
[Windows Media Format Runtime 9、Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=bf8b9b46-ba28-4f48-9dac-6a90b7d592d3)  
(KB978695)  
（严重）  
仅限 Windows XP Service Pack 3：  
[Windows Media Format Runtime 9、Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=ebbccd82-c637-4c88-86ea-d39ae713c085)  
(KB978695)  
（严重）  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
（重要）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=55c05cb8-aa6c-460b-9aa7-084842dab280)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8c3f2e81-c0ea-494a-a47c-4f8982effb49)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=bfe87761-ed9e-4fec-a393-d7fddb919db4)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fc02fc7e-ee85-4377-b54c-012fa60a8c9c)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9cff9aba-7743-4c33-87c7-37d06ed60a21)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b42a17c5-997e-4504-ba5b-bfa62166b460)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
仅 Windows XP Media Center Edition 2005：  
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
（重要）  
仅 Windows XP Media Center Edition 2005 和 Windows XP Tablet PC Edition 2005：  
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
（重要）  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
（重要）  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e3aac9d-7747-435f-9678-f621e314e070)  
（重要）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=7914fdae-9a7a-4a10-8ce7-c621eb903452)  
(KB975562)  
（严重）  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=b56839e3-e7d3-48da-b90c-d403d8dbeed2)  
(KB978695)  
（严重）  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555)<sup>[3]</sup>  
(KB978695)  
（严重）  
[Windows Media Format Runtime 11](https://www.microsoft.com/download/details.aspx?familyid=d2887448-9d3c-472f-a0bd-ab083a65eafc)  
(KB978695)  
（严重）  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
（重要）  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
（重要）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=c110d26e-9a1e-4e47-9ce2-4068f2733a2f)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f3e462fb-df95-4b79-a8bc-5359c2967503)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=7780af61-a206-49aa-a805-a49bdcbb5419)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6c7cda29-161e-49b4-976a-c718c0aa11a0)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=37cd7533-ddad-4d0d-85c0-1491308e1ff8)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dc835b94-3368-4c1c-8f29-40517c73540e)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
（重要）  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad) (KB979909)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=79a11dcd-5d88-4d83-beae-6580ef6fc2c0)  
（重要）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=fc15c43b-d48f-4872-8f9d-ed973170db9a)  
(KB975562)  
（严重）  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=bb580e94-8c02-46f1-b7f6-e7d4373cb1c5)  
(KB978695)  
（严重）  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
（重要）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=0ddf95ac-dd49-4cb1-b6f6-bd4e987b0f06)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3c0bd349-aa77-47de-ba1d-1fcc72dcad28)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=bfb9acdb-2d9c-4c22-963c-8b9ce247350f)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f0187b69-3ed9-494c-89f1-90a35e22078c)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ebab6101-fcf1-4842-b22d-893a20c1c10f)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ca49b5b5-db8e-4ebc-9a3c-b1ace09ac3c0)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet 信息服务 6.0](https://www.microsoft.com/download/details.aspx?familyid=0761c207-5465-4f42-b61f-bd02efcef27d)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f82e1b73-7f8b-4f4c-8187-4050a11db44c)  
(KB979907)  
（重要）  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f42cc5d4-1bea-4a4a-8a08-b3eb92503588)  
（重要）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=d28ecdf7-9fd4-437e-9db7-c6b579248abe)  
(KB975562)  
（严重）  
[Windows Media Format Runtime 9.5](https://www.microsoft.com/download/details.aspx?familyid=41faf16f-c7a8-4ce0-b388-a65478576163)  
(KB978695)  
（严重）  
[Windows Media Format Runtime 9.5 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555)<sup>[3]</sup>  
(KB978695)  
（严重）  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
（重要）  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
（重要）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=77b1d55c-b015-4863-aab0-6463b90d4bf7)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4aa0ec4f-5502-4f2a-9732-975518c34444)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=81644c43-22c0-4c61-b395-3264516516a6)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=50b8ee2e-31f8-473d-83d1-822c89c28070)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=87e13912-f861-4985-ab9d-260a5898dfd4)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b0794e7e-c925-4672-b7a5-4bb3f847f045)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet 信息服务 6.0](https://www.microsoft.com/download/details.aspx?familyid=023572ff-ce5d-4428-a96b-1245db6ff312)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
（重要）  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=50efb1cf-9d89-4522-929d-f87fd98d6fe8)  
（重要）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=7f101f4c-dcc8-474c-a844-fe0c45d6697c)  
(KB975562)  
（严重）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=f34bc115-022b-46b0-9517-806bd0fc73c5)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=55d9d7f0-f9d9-4833-b5cc-eb87a62da6a8)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=abcdc3bb-4659-4b63-a9bd-e448f8bed90a)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=123bf547-9005-451f-9eba-97a68037304e)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=6e76ebea-bde1-4352-a283-dd71c2cc51a1)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet 信息服务 6.0](https://www.microsoft.com/download/details.aspx?familyid=f1f3e524-8ac6-4210-a3a8-4ffc58a606ea)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
（重要）  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
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
Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7cb64633-d2a0-4e38-be35-ec32ea655a04)  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows Vista Service Pack 1：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=b64107f2-990a-42df-a75a-5bf371709fd6)  
(KB975562)  
（严重）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=75e4c9cb-a55a-4e2a-9c97-60a40353cae3)  
(KB979482)  
（严重）  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=9fab91da-1528-4df9-a2dd-90e57a3c24cf)  
(KB979332)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2ddaa4b3-1a98-4183-94af-ebdae4e7b76a)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=661c9528-917d-4df6-a330-c89f39dc5ce4)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=640f9216-3e99-46b6-aac8-cd051eedad3c)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=363b503a-2e1e-4284-a029-9695d2acfcb6)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet 信息服务 7.0](https://www.microsoft.com/download/details.aspx?familyid=01382926-2313-4769-a0a5-262c4f9f18a1)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
（重要）  
仅限 Windows Vista Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
（重要）  
仅限 Windows Vista Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
（重要）  
仅限 Windows Vista Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb) (KB979910)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bbfc4d80-67eb-4deb-9595-cb67942a0df2)  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows Vista x64 Edition Service Pack 1：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=0754addb-2f04-45c9-8594-174b8b8b297c)  
(KB975562)  
（严重）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=c9f033f6-f587-494d-b968-1316f1deed06)  
(KB979482)  
（严重）  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=63bba49e-6d80-47b3-b109-fa9b2392af4f)  
(KB979332)  
（重要）  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=e19aeef8-6bef-45ee-bc9f-3e4b81a58e33)  
(KB979332)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ddf55e74-dbaa-45f7-ac5b-ae3da24e0e33)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d9f5feb0-fa1a-40c1-9971-9b8af6f0b4a5)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3076d1ea-7716-4b54-8ec4-660374f14dcb)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3f512b86-3a99-47f7-a90e-1ae9b291385c)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet 信息服务 7.0](https://www.microsoft.com/download/details.aspx?familyid=7fb6f2b8-c7a6-4239-99f3-cf3aacf89b0f)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
（重要）  
仅限 Windows Vista x64 Edition Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
（重要）  
仅限 Windows Vista x64 Edition Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
（重要）  
仅限 Windows Vista x64 Edition Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=22d550fe-ba35-4750-a9d6-624858b67c94)\*  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008（用于 32 位系统）：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=18fd814b-51f3-470b-a5bd-97be752298d9)\*\*  
(KB975562)  
（严重）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=5c5e2dfc-0078-4f2a-9c2e-75e45bb7638e)\*  
(KB979482)  
（严重）  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=1ce1e47f-b1c3-4480-bafd-74f8b12e2171)\*\*  
(KB979332)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a06b9f42-47ac-4ff2-ac32-e4958cdb611e)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=bed14484-7fc5-455d-b996-3192467543cc)\*\*  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=24ed08c7-a474-4458-8269-3b9de5e22385)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e78ad607-d209-48c4-b0f3-ed4c70993174)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](https://www.microsoft.com/download/details.aspx?familyid=84a54246-5d9e-49e2-8170-af48b43f984d)\*<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
（重要）  
仅限 Windows Server 2008（用于 32 位系统）：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
（重要）  
仅限 Windows Server 2008（用于 32 位系统）：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
（重要）  
仅限 Windows Server 2008（用于 32 位系统）Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=09025626-4116-4a31-8700-215382898ee2)\*  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008（用于基于 x64 的系统）：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=4e40da51-23ee-44f0-9ea0-99bda8cca731)\*\*  
(KB975562)  
（严重）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=bfc0b62c-2d79-48dd-896f-d05057c02e8c)\*  
(KB979482)  
（严重）  
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=93cc5ace-6382-4a2f-875b-9348b7e198a6)\*\*  
(KB979332)  
（重要）  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=d650a7d7-5620-4bb7-a7ad-0848dd28dae3)\*\*  
(KB979332)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d0a3f7c-2617-4bc6-a4c7-cda26c6471e1)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a24554e8-213b-4c24-b062-ec424d64128e)\*\*  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=cf84469b-ce6d-45e8-8336-7b4501c6cf91)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=85f6fc5d-efd1-4351-b4c0-b9b7080e6173)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](https://www.microsoft.com/download/details.aspx?familyid=38286e43-89a6-4895-8ff9-69452df38706)\*<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
（重要）  
仅限 Windows Server 2008（用于基于 x64 的系统）：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
（重要）  
仅限 Windows Server 2008（用于基于 x64 的系统）：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
（重要）  
仅限 Windows Server 2008（用于基于 x64 的系统）Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0035cfe2-d38d-41cd-b704-ec1feda307d8)  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008（用于基于 Itanium 的系统）：  
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=120c68f5-4575-4e2a-912a-eed52736c403)  
(KB975562)  
（严重）  
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=6e5753ab-848d-475f-917d-ba70f70b65f5)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=38347fa6-5946-4bb5-9fea-a5b2f4e7c1f2)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dee5c0c0-b844-490d-8daf-6e6ec8a39e35)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c6f1aae5-e8fd-4121-89b2-b97c571e8223)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet 信息服务 7.0](https://www.microsoft.com/download/details.aspx?familyid=8ad19eba-9821-48b4-a942-4ee4f002f913)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
（重要）  
仅限 Windows Server 2008（用于基于 Itanium 的系统）：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
（重要）  
仅限 Windows Server 2008（用于基于 Itanium 的系统）：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
（重要）  
仅限 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2：  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
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
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=3e0ff389-4612-4c92-bbff-bb45b5bdfc6a)  
（重要）
</td>
<td style="border:1px solid black;">
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=63567e99-087d-4804-953a-f23bdeba7772)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=5bce87fe-dcbb-4638-b248-3f0755537b00)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5c835885-9375-4882-a92f-4d4cfcacc005)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=969af8d6-f6da-4dd1-a7d7-2de54a5a8978)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=588167cb-f62a-4fb8-8a18-ac15dc322495)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=2b1e4aff-605a-4e94-88f9-135ce35f0646)  
（重要）
</td>
<td style="border:1px solid black;">
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=6c261dbf-14c6-4071-8523-e8ba8059fa54)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ee68ecd0-5b8a-4c1e-bdee-bd8616558d43)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5cfc5776-0c6b-4092-bc98-94df077c60d8)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b069e5b2-aa2d-452e-b687-8734b5ba0051)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=1c45d0c8-1629-470b-8167-c6bf66054595)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
（重要）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=4272277f-b2dd-4406-8bbd-bc461c9923b8)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=1331f2bc-7479-4be7-a413-52afb488a330)\*  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=901f7c89-02af-4f87-8592-dad318997d77)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7c4ff5ae-eadd-431e-b982-d5f179efb8c0)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=45242c7c-3752-44bf-a766-024ad7d28f53)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=5d9b7705-6280-4d2e-94fa-3160b3ce5cfa)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)\*  
(KB979916)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7d636f82-e828-468c-ac36-808ff9d37c7f)  
（重要）
</td>
<td style="border:1px solid black;">
[Asycfilt.dll（COM 组件）](https://www.microsoft.com/download/details.aspx?familyid=7a1ee54f-3f73-4557-9071-5af236e70937)  
(KB979482)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=4958b221-2776-43d7-9e1c-1e1cb318a694)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=52c04d85-911f-47be-852e-c9bb4934744d)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=0a271fb5-da5b-4a17-9593-e56b9a843b8f)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=869e900a-0063-4d8b-9b7c-7d12f6be12cd)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
（重要）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS10-033 注释**

<sup>[1]</sup>Quartz.dll (Direct Show) (DirectX 9) 的更新也适用于 DirectX 9.0a、DirectX 9.0b 和 DirectX 9.0c。

<sup>[2]</sup>此更新程序包适用于具有启用 DRM 的媒体播放器更新 (KB891122) 的 Microsoft Windows 2000 上的 Windows Media Format 9 SDK Runtime。 有关详细信息，请参阅 [Microsoft 知识库文章 974316](http://support.microsoft.com/kb/974316)。

<sup>[3]</sup>如果您已安装 Windows Media Format Runtime 9.5 x64 Edition，您必须应用 Windows Media Format Runtime 9.5 和 Windows Media Format Runtime 9.5 x64 Edition 安装更新以安全防止 MS10-033 中所讨论的漏洞。

**MS10-035 注释**

<sup>[1]</sup>严重等级不适用于此更新，因为此公告中讨论的漏洞不影响此软件。 然而，提供此更新以解决 [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979) 发生的一个回归问题。有关详细信息，请参阅 [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)。

**MS10-040 注释**

<sup>[1]</sup>该操作系统仅在安装了 “对身份验证的扩展保护”时才受影响。 请参阅 [Microsoft 知识库文章 973917。](http://support.microsoft.com/kb/973917)

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
<th>
</th>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Office 套件、系统和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://technet.microsoft.com/security/bulletin/ms10-036)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://technet.microsoft.com/security/bulletin/ms10-038)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=fec14a92-79a1-4281-8ee2-659b2dfd283f)  
(KB982299)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=80fdd134-2a86-4115-aea1-841f19af92e3)  
(KB982311)  
（重要）  
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1)<sup>[2]</sup>  
(KB982133)  
（重要）  
[Microsoft Office PowerPoint 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6b6204c1-559f-45a5-8f6c-a1e216192efc)<sup>[2]</sup>  
(KB982157)  
（重要）  
[Microsoft Office Publisher 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071)<sup>[2]</sup>  
(KB982122)  
（重要）  
[Microsoft Office Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=1595ada3-bb4f-40f6-8137-23eba918bc8a)<sup>[2]</sup>  
(KB982126)  
（重要）  
[Microsoft Office Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d2c40eb5-1149-4466-840c-84f406f64245)<sup>[2]</sup>  
(KB982134)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1)  
(KB982133)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ee6-4af-0ab40-8f62-35dc1a)  
(KB982312)  
（重要）  
[Microsoft Office Excel 2007 Service Pack 1 和 Microsoft Office Excel 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec)<sup>[3]</sup>  
(KB982308)  
（重要）  
[Microsoft Office PowerPoint 2007 Service Pack 1 和 Microsoft Office PowerPoint 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=decb834d-3958-45cc-a5ae-4283adb2462a)<sup>[3]</sup>  
(KB982158)  
（重要）  
[Microsoft Office Publisher 2007 Service Pack 1 和 Microsoft Office Publisher 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6a74b986-1e99-4aa1-828f-757a36896f65)<sup>[3]</sup>  
(KB982124)  
（重要）  
[Microsoft Office Visio 2007 Service Pack 1 和 Microsoft Office Visio 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d5df052e-1f38-4308-bcca-296cff22729b)<sup>[3]</sup>  
(KB982127)  
（重要）  
[Microsoft Office Word 2007 Service Pack 1 和 Microsoft Office Word 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7e9708f0-8cd6-4f0b-8585-bccc54fa2755)<sup>[3]</sup>  
(KB982135)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 和 Microsoft Office Excel 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec)<sup>[1]</sup>  
(KB982308)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://technet.microsoft.com/security/bulletin/ms10-036)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://technet.microsoft.com/security/bulletin/ms10-038)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=16c71ab8-9284-407a-856a-93c67995f125)  
(KB2028866)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=d46255bd-6470-4106-9fe2-ea67acd3f1bd)  
(KB2028864)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=b6ca7b05-cf97-43a2-95eb-7b5caf7c1528)  
(KB2078051)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://technet.microsoft.com/security/bulletin/ms10-036)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://technet.microsoft.com/security/bulletin/ms10-038)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
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
Microsoft Excel Viewer Service Pack 1 和 Microsoft Office Excel Viewer Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 和 Microsoft Office Excel Viewer Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=033b3bf3-7826-4064-b001-11e4dce2d91a)  
(KB982333)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包以及用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 2 的 Microsoft Office 兼容包
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包以及用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 2 的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=7f89a734-cda4-4abb-9a10-f6dfe560e8d0)  
(KB982331)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office InfoPath 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=4f79d376-0ea2-4218-9200-3c34c83ba336)  
(KB980923)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office InfoPath 2007 Service Pack 1 和 Microsoft Office InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2007 Service Pack 1 和 Microsoft Office InfoPath 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bfa8765a-7970-4feb-996c-7c27d71c97c6)  
(KB979441)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 1 和 Microsoft Office SharePoint Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=52a55423-33d4c-1a919e-b806972f553-c6507b739ca0)<sup>[1]</sup>  
(KB979445)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 2（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=52a55423-33d4c-1a919e-b806972f553-c6507b739ca0)<sup>[1]</sup>  
(KB979445)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90)<sup>[1]</sup>  
(KB979445)  
（重要）  
[Microsoft Office SharePoint Server 2007 Service Pack 2（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90)<sup>[1]</sup>  
(KB979445)  
（重要）
</td>
</tr>
</table>

**MS10-036 注释**

<sup>[1]</sup>无更新。 有关详细信息，请参阅公告。

<sup>[2]</sup>除此更新外，客户还需要安装 Microsoft Office 2003 Service Pack 3 更新 (KB982311) 以避免此公告中描述的漏洞。

<sup>[3]</sup>除此更新外，客户还需要安装 2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2 更新 (KB982312) 以避免此公告中描述的漏洞。

**MS10-038 注释**

<sup>[1]</sup> 除此更新外，客户还需要安装用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 1 和用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 2 的安全更新 (KB982308)，以免受本公告中所描述的漏洞影响。

**MS10-039 注释**

<sup>[1]</sup>对于 Microsoft Office SharePoint Server 2007 的支持版本，除了安全更新程序包 KB979445 外，客户还需要安装 Microsoft Windows SharePoint Services 3.0 安全更新 (KB983444) 以避免此公告中描述的漏洞。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

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
Windows SharePoint Services
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 1 和 Microsoft Windows SharePoint Services 3.0 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 和 Microsoft Windows SharePoint Services 3.0 Service Pack 2（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=3841c0-4e5e-8d1-7cd-954850783f51e0f6)  
(KB983444)  
（重要）  
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 和 Microsoft Windows SharePoint Services 3.0 Service Pack 2（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=94bc76d4-78e4-4bda-8922-36c3a9d3854f)  
(KB983444)  
（重要）
</td>
</tr>
</table>

**MS10-039 注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**注意** 从 2009 年 8 月 1 日起，Microsoft 将不再对 Office Update 和 Office Update 清单工具提供支持。 要继续获得 Microsoft Office 产品的最新更新，请使用 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)。 有关详细信息，请参阅[关于 Microsoft Office Update： 常见问题](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。 该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。 有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用安全更新清单工具 (SUIT) 来帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)中列出）提供的活动保护网站。

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

-   [VUPEN Vulnerability Research Team](http://www.vupen.com/) 的 Sebastien Renaud 报告了 MS10-032 中描述的问题
-   [Secunia Research](http://secunia.com/) 与我们合作，解决 MS10-032 中描述的问题
-   [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS10-033 中描述的两个问题
-   [NGS Software](http://www.ngssoftware.com/) 的 Shaun Colley 报告了 MS10-034 中描述的问题
-   Chris Ries of Carnegie Mellon University Computing Services 的 Chris Ries 报告了 MS10-034 中描述的问题
-   [Casaba Security](http://www.casabasecurity.com/) 的 Chris Weber 报告了 MS10-035 和 MS10-039 中描述的问题
-   [Mitsui Bussan Secure Directions, Inc.](http://www.mbsd.jp/) 的 Takeshi Terada 报告了 MS10-035 中描述的问题
-   [Google Inc.](http://www.google.com/) 的 Michal Zalewski 报告了 MS10-035 中描述的问题
-   [Matasano Security](http://www.matasano.com/) 的 Chris Rohlf 报告了 MS10-035 中描述的两个问题
-   Peter Vreugdenhil 与 [TippingPoint's](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 MS10-035 中描述的问题
-   [IBM ISS X-Force](http://www.iss.net/) 的 David Dewey 和 [Accuvant](http://www.accuvant.com/)（以前称 [VeriSign iDefense Labs](http://labs.idefense.com/)）的 Ryan Smith 与我们合作处理 MS10-036 中包括的纵深防御更改
-   Laserforce International 的 Chris Carton 与 [Secunia](http://secunia.com/) 一起报告了 MS10-037 中描述的问题
-   一名匿名研究人员与 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 MS10-038 中描述的问题
-   [VUPEN Vulnerability Research Team](http://www.vupen.com/) 的 Nicolas Joly 报告了 MS10-038 中描述的八个问题
-   [Fortinet's FortiGuard Labs](http://www.fortiguard.com/) 的 Bing Liu 报告了 MS10-038 中描述的问题
-   [Secunia](http://secunia.com/) 的 Carsten Eiram 报告了 MS10-038 中描述的两个问题
-   一名匿名研究人员与 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 MS10-038 中描述的问题
-   亚利桑那州 Gilbert 的Gilbert Public Schools 的 Rick Glaspie 报告了 MS10-038 中描述的问题
-   Dallas County Community College District 的 Rik Jones 报告了 MS10-039 中描述的问题
-   [WhiteHat Security](http://www.whitehatsec.com) 的 Arian Evans 报告了 MS10-041 中通过纵深防御更改解决的绕过 ASP.NET 请求验证的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2010 年 6 月 8 日）： 已发布公告摘要。
-   V1.1（2010 年 6 月 9 日）： 修订了“**受影响的软件和下载位置**”部分的 MS10-033 注释。

*Built at 2014-04-18T01:50:00Z-07:00*
