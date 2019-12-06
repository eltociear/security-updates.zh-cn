---
TOCTitle: 'MS16-MAR'
Title: 'Microsoft 安全公告摘要（2016 年 3 月）'
ms:assetid: 'ms16-mar'
ms:contentKeyID: 72464181
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms16-mar(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2016 年 3 月）
======================================

发布日期： 2016 年 3 月 8 日 | 更新时间： 2016 年 3 月 25 日

**版本：** 3.1

本公告摘要列出了 2016 年 3 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新程序和与每月安全更新程序同日发布的任何非安全更新程序进行优先排序。 请参阅**其他信息**部分。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

<p> </p>
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>公告标题和执行摘要</strong></p></td>
<td style="border:1px solid black;"><p><strong>最高严重等级<br />
和漏洞影响</strong></p></td>
<td style="border:1px solid black;"><p><strong>重新启动要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>已知<br />
问题</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-023">MS16-023</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新程序 (3142015)<br />
</strong>此安全更新程序修复了 Internet Explorer 中的多个漏洞。 如果用户使用 Internet Explorer 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。 如果当前用户使用管理用户权限登录，则成功利用此漏洞的攻击者可以控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-024">MS16-024</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 的累积安全更新程序 (3142019)<br />
</strong>此安全更新程序可修复 Microsoft Edge 中的多个漏洞。 如果用户使用 Microsoft Edge 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-025">MS16-025</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Windows 库加载安全更新程序 (3140709)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的一个漏洞。 如果 Microsoft Windows 在加载某些库之前无法正确验证输入，此漏洞可能会允许远程执行代码。 但是，攻击者必须首先获得本地系统的访问权限，才能执行恶意应用程序。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-026">MS16-026</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的图形字体安全更新程序 (3143148)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的多个漏洞。 如果攻击者诱使用户打开经特殊设计的文档或访问包含经特殊设计的嵌入式 OpenType 字体的网站，则其中最为严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-027">MS16-027</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Windows Media 安全更新程序 (3143146)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的多个漏洞。 如果用户打开网站上托管的经特殊设计的媒体内容，那么这些漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-028">MS16-028</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Microsoft Windows PDF 库安全更新程序 (3143081)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的多个漏洞。 如果用户打开经特殊设计的 .pdf 文件，这些漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-029">MS16-029</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Microsoft Office 安全更新程序 (3141806)</strong><br />
此安全更新程序修复了 Microsoft Office 中的多个漏洞。 如果用户打开经特殊设计的 Microsoft Office 文件，那么这些漏洞中最严重的漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web Apps、<br />
Microsoft Server 软件</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-030">MS16-030</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复远程执行代码漏洞的 Windows OLE 安全更新程序 (3143136)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的多个漏洞。 当 Windows OLE 无法正确验证用户输入时，这些漏洞可能允许远程执行代码。 攻击者可以利用这些漏洞以执行恶意代码。 但是，攻击者必须首先诱使用户在网页或电子邮件中打开经特殊设计的文件或程序。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-031">MS16-031</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复特权提升漏洞的 Microsoft Windows 安全更新程序 (3140410)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的一个漏洞。 如果攻击者可以登录目标系统，并且运行经特殊设计的应用程序，该漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-032">MS16-032</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复特权提升漏洞的辅助登录安全更新程序 (3143141)</strong><br />
此安全更新程序修复了 Microsoft Windows 中的一个漏洞。 如果 Windows 辅助登录服务无法正确管理内存中的请求句柄，此漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-033">MS16-033</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复特权提升漏洞的 Windows USB 大容量存储类驱动程序安全更新程序 (3143142)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的一个漏洞。 如果具有物理访问权限的攻击者将经特殊设计的 USB 设备插入到系统中，此漏洞可能会允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-034">MS16-034</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复特权提升漏洞的 Windows 内核模式驱动程序安全更新程序 (3143145)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的多个漏洞。 如果攻击者登录系统并运行经特殊设计的应用程序，这些漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-035">MS16-035</a></p></td>
<td style="border:1px solid black;"><p><strong>用于修复安全功能绕过漏洞的 .NET Framework 安全更新程序 (3141780)</strong><br />
此安全更新程序可修复 Microsoft .NET Framework 中的一个漏洞。 如果 .NET Framework 组件不能正确验证已签名 XML 文档中的某些元素，该组件中会存在安全功能绕过漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
绕过安全功能</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3135996">3135996</a><br />
<a href="https://support.microsoft.com/zh-cn/kb/3136000">3136000</a><br />  
<a href="https://support.microsoft.com/zh-cn/kb/3149737">3149737</a><br />
<a href="https://support.microsoft.com/zh-cn/kb/3148821">3148821</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-036">MS16-036</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 安全更新程序 (3144756)</strong><br />
此安全更新程序可修复安装在所有受支持版本的 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 以及 Windows 10 上的 Adobe Flash Player 漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Adobe Flash Player</p></td>
</tr>
</tbody>
</table>




利用指数
--------

下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。

**如何使用该表？**

对于您可能需要安装的每个安全更新程序，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。 根据您的特定配置，检查下面的每个评估，从而确定部署本月更新程序的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。

在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新软件版本”是指主题软件，“较旧软件版本”是指主题软件的所有较旧的受支持版本。

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**漏洞标题**

</td>
<td style="border:1px solid black;" colspan="2">
**最新软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**较旧软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-023： Internet Explorer 累积安全更新程序 (3142015)**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0102](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0102)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0103](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0103)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0104](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0104)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影响

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0105](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0105)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0106](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0106)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0107](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0107)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0108](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0108)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0109](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0109)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0110](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0110)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0111](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0111)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0112](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0112)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0113](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0113)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0114](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0114)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-024： Microsoft Edge 累积安全更新程序 (3142019)**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0102](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0102)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0105](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0105)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0109](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0109)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0110](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0110)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0111](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0111)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0116](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0116)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0123](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0123)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0124](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0124)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0125](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0125)

</td>
<td style="border:1px solid black;">
Microsoft Edge 信息泄漏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0129](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0129)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0130](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0130)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-025： 用于修复远程执行代码漏洞的 Windows 库加载安全更新程序 (3140709)**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0100](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0100)

</td>
<td style="border:1px solid black;">
库加载输入验证远程执行代码漏洞

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-026： 用于修复远程执行代码漏洞的图形字体安全更新程序 (3143148)**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0120](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0120)

</td>
<td style="border:1px solid black;">
OpenType 字体分析漏洞

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0121](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0121)

</td>
<td style="border:1px solid black;">
OpenType 字体分析漏洞

</td>
<td style="border:1px solid black;" colspan="2">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-027： 用于修复远程执行代码漏洞的 Windows Media 安全更新程序 (3143146)**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0098](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0098)

</td>
<td style="border:1px solid black;">
Windows Media 分析远程执行代码漏洞

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影响

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0101](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0101)

</td>
<td style="border:1px solid black;">
Windows Media 分析远程执行代码漏洞

</td>
<td style="border:1px solid black;" colspan="2">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-028： 用于修复远程执行代码漏洞的 Microsoft Windows PDF 库安全更新程序 (3143081)**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0117](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0117)

</td>
<td style="border:1px solid black;">
Windows 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0118](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0118)

</td>
<td style="border:1px solid black;">
Windows 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-029： 用于修复远程执行代码漏洞的 Microsoft Office 安全更新程序 (3141806)**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0021](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0021)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影响

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0057](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0057)

</td>
<td style="border:1px solid black;">
Microsoft Office 安全功能绕过漏洞

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0134](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0134)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-030： 用于修复远程执行代码漏洞的 Windows OLE 安全更新程序 (3143136)**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0091](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0091)

</td>
<td style="border:1px solid black;">
Windows OLE 内存远程执行代码漏洞

</td>
<td style="border:1px solid black;" colspan="2">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0092](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0092)

</td>
<td style="border:1px solid black;">
Windows OLE 内存远程执行代码漏洞

</td>
<td style="border:1px solid black;" colspan="2">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-031： 用于修复特权提升漏洞的 Microsoft Windows 安全更新程序 (3140410)**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0087](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0087)

</td>
<td style="border:1px solid black;">
Windows 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-032： 用于修复特权提升漏洞的辅助登录安全更新程序 (3143141)**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0099](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0099)

</td>
<td style="border:1px solid black;">
辅助登录特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-033： 用于修复特权提升漏洞的 Windows USB 大容量存储类驱动程序安全更新程序 (3143142)**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0133](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0133)

</td>
<td style="border:1px solid black;">
USB 大容量存储特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-034： 用于修复特权提升漏洞的 Windows 内核模式驱动程序安全更新程序 (3143145)**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0093](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0093)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0094](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0094)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0095](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0095)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
4 - 不受影响

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0096](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0096)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;" colspan="2">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-035： 用于修复安全功能绕过漏洞的 .NET Framework 安全更新程序 (3141780)**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0132](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0132)

</td>
<td style="border:1px solid black;">
.NET XML 验证安全功能绕过漏洞

</td>
<td style="border:1px solid black;" colspan="2">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-036： Adobe Flash Player 安全更新程序 (3144756)**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-08](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-08.html)

</td>
<td style="border:1px solid black;">
请参阅 [Adobe 安全公告 APSB16-08](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-08.html)，了解漏洞严重性级别和更新程序优先级级别。

</td>
<td style="border:1px solid black;" colspan="2">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

受影响的软件
------------

下表按主要软件类别和严重性的排序列出了公告。

通过这些表可了解可能需要安装的安全更新程序。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新程序。 如果列出了软件程序或组件，则也会列出软件更新程序的严重等级。

**注意** 您可能必须为单个漏洞安装几个安全更新程序。 查看列出的每个公告标识符的整列，核实必须安装的更新程序（基于系统上已安装的程序或组件）。

 

### Windows 操作系统和组件（表 2-1）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3140709)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3140709)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3140709)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3139929)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3140709)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3140709)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3138910)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(3138962)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3138910)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3138962)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3138910)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3138962)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3138910)  
（严重）  
Windows 8.1（用于 32 位系统）  
(3138962)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3137513)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3138910)  
（严重）  
Windows 8.1（用于基于 x64 的系统）  
(3138962)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3137513)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3139929)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3138910)  
（严重）  
Windows Server 2012  
(3138962)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3137513)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3138910)  
（严重）  
Windows Server 2012 R2  
(3138962)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3137513)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3139929)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3138910)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3137513)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3140745)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3140745)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3140745)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3140768)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3140768)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3140768)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-023**](https://technet.microsoft.com/zh-cn/library/security/ms16-023)

</td>
<td style="border:1px solid black;">
[**MS16-024**](https://technet.microsoft.com/zh-cn/library/security/ms16-024)

</td>
<td style="border:1px solid black;">
[**MS16-025**](https://technet.microsoft.com/zh-cn/library/security/ms16-025)

</td>
<td style="border:1px solid black;">
[**MS16-026**](https://technet.microsoft.com/zh-cn/library/security/ms16-026)

</td>
<td style="border:1px solid black;">
[**MS16-027**](https://technet.microsoft.com/zh-cn/library/security/ms16-027)

</td>
<td style="border:1px solid black;">
[**MS16-028**](https://technet.microsoft.com/zh-cn/library/security/ms16-028)

</td>
<td style="border:1px solid black;">
[**MS16-030**](https://technet.microsoft.com/zh-cn/library/security/ms16-030)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3140709)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3140709)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3139940)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3140735)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3137513)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3139940)  
（重要）

</td>
</tr>
</table>

 

### Windows 操作系统和组件（表 2-2）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3135987)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135996)  
（重要）  
Microsoft .NET Framework 4.6  
(3136000)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3135987)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135996)  
（重要）  
Microsoft .NET Framework 4.6  
(3136000)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3135987)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135996)  
（重要）  
Microsoft .NET Framework 4.6  
(3136000)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3135987)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135996)  
（重要）  
Microsoft .NET Framework 4.6  
(3136000)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3135982)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3135988)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135996)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3136000)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3135988)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135996)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3136000)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3135988)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135996)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3136000)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
（重要）  
Microsoft .NET Framework 3.5  
(3135991)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135994)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
（重要）  
Microsoft .NET Framework 3.5  
(3135991)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135994)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135984)  
（重要）  
Microsoft .NET Framework 3.5  
(3135989)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135995)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3135997)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
（重要）  
Microsoft .NET Framework 3.5  
(3135991)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135994)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3135994)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3140745)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3140745)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3140745)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140745)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3140745)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3140745)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3140745)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3140745)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140745)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3140745)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3140768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3140768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3140768)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140768)  
（重要）  
Microsoft .NET Framework 4.6.1  
(3140768)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3140768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3140768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3140768)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3140768)  
（重要）  
Microsoft .NET Framework 4.6.1  
(3140768)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3144756)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-031**](https://technet.microsoft.com/zh-cn/library/security/ms16-031)

</td>
<td style="border:1px solid black;">
[**MS16-032**](https://technet.microsoft.com/zh-cn/library/security/ms16-032)

</td>
<td style="border:1px solid black;">
[**MS16-033**](https://technet.microsoft.com/zh-cn/library/security/ms16-033)

</td>
<td style="border:1px solid black;">
[**MS16-034**](https://technet.microsoft.com/zh-cn/library/security/ms16-034)

</td>
<td style="border:1px solid black;">
[**MS16-035**](https://technet.microsoft.com/zh-cn/library/security/ms16-035)

</td>
<td style="border:1px solid black;">
[**MS16-036**](https://technet.microsoft.com/zh-cn/library/security/ms16-036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3140410)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3135983)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3135988)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135996)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135984)  
（重要）  
Microsoft .NET Framework 3.5  
(3135989)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135995)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3135997)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3139914)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3139398)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3139852)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135985)  
（重要）  
Microsoft .NET Framework 3.5  
(3135991)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3135994)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3135998)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

 

### Microsoft Office 套件和软件

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2956110)  
（重要）  
Microsoft InfoPath 2007 Service Pack 3  
(3114426)  
（重要）  
Microsoft Outlook 2007 Service Pack 3  
(2880510)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3114901)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2956063)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3114873)  
（重要）  
Microsoft InfoPath 2010 Service Pack 2（32 位版本）  
(3114414)  
（重要）  
Microsoft Outlook 2010 Service Pack 2（32 位版本）  
(3114883)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3114878)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3114873)  
（重要）  
Microsoft InfoPath 2010 Service Pack 2（64 位版本）  
(3114414)  
（重要）  
Microsoft Outlook 2010 Service Pack 2（64 位版本）  
(3114883)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3114878)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3039746)  
（重要）  
Microsoft InfoPath 2013 Service Pack 1（32 位版本）  
(3114833)  
（重要）  
Microsoft Outlook 2013 Service Pack 1（32 位版本）  
(3114829)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3114824)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft InfoPath 2013 Service Pack 1（64 位版本）  
(3114833)  
（重要）  
Microsoft Outlook 2013 Service Pack 1（64 位版本）  
(3114829)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3114824)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 RT Service Pack 1  
(3114829)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(3114824)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）  
(3114690)  
（重要）  
Microsoft Outlook 2016（32 位版本）  
(3114861)  
（重要）  
Microsoft Word 2016（32 位版本）  
(3114855)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Outlook 2016（64 位版本）  
(3114861)  
（重要）  
Microsoft Word 2016（64 位版本）  
(3114855)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3138328)<sup>[1]</sup>  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3138327)<sup>[1]</sup>  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(3114900)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114812)  
（重要）

</td>
</tr>
</table>

**MS16-029 注释**

<sup>[1]</sup>从 2016 年 3 月 16 日起，推出了适用于 Microsoft Office 2016 for Mac 的 3138327 更新和适用于 Microsoft Office for Mac 2011 的 3138328 更新。请注意，适用于 Microsoft Outlook 2016 for Mac 的 3138327 更新没有在 3 月 16 日发布。准备就绪后便会立即发布此更新，并将通过公告修订通知用户。 有关详细信息，请参阅 [Microsoft 知识库文章 3138327](https://support.microsoft.com/zh-cn/kb/3138327) 和 [Microsoft 知识库文章 3138328](https://support.microsoft.com/zh-cn/kb/3138328)。

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft Office Services 和 Web Apps

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3114866)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3114814)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3114880)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-029**](https://technet.microsoft.com/zh-cn/library/security/ms16-029)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3114821)  
（重要）

</td>
</tr>
</table>

**MS16-029 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新程序。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新程序和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新程序。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。 有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn903755.aspx)部分。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。 带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新版本。

### MU、WU 和 WSUS 上的非安全更新程序

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新程序之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新程序管理策略**

[更新管理安全指导](https://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新程序的最佳方案建议的其他信息。

**获取其他安全更新程序**

可从以下位置获得针对其他安全问题的更新程序：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新程序。 通过输入关键字“安全更新程序”可以非常方便地找到这些更新程序。
-   [Microsoft 更新](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn)提供了消费者平台的更新程序。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新程序。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/zh-cn/lifecycle)。

面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

基于国家/地区的本地支持： [国际支持](https://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定用途的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2016 年 3 月 8 日）： 已发布公告摘要。
-   V2.0（2016 年 3 月 10 日）： 公告摘要已经过修订，以记录 MS16-036 的带外发布。
-   V2.1（2016 年 3 月 10 日）： 向 MS16-035 的“执行摘要”表添加了已知问题的引用。有关详细信息，请参阅 [Microsoft 知识库文章 3148821](https://support.microsoft.com/zh-cn/kb/3148821)。
-   V2.2（2016 年 3 月 15 日）： 向 MS16-035 的执行摘要表添加了一个已知问题引用。有关更多信息，请参阅 [Microsoft 知识库文章 3135996](https://support.microsoft.com/zh-cn/kb/3135996)、[Microsoft 知识库文章 3136000](https://support.microsoft.com/zh-cn/kb/3136000) 和 [Microsoft 知识库文章 3149737](https://support.microsoft.com/zh-cn/kb/3149737)。
-   V3.0（2016 年 3 月 16 日）： 对于 MS16-029，添加了适用于 Microsoft Office 2016 for Mac 的 3138327 更新和适用于 Microsoft Office for Mac 2011 的 3138328 更新，这些更新从 2016 年 3 月 16 日起可用。请注意，适用于 Microsoft Outlook 2016 for Mac 的 3138327 更新没有在 3 月 16 日发布。准备就绪后便会立即发布此更新，并将通过公告修订通知用户。 有关详细信息，请参阅 [Microsoft 知识库文章 3138327](https://support.microsoft.com/zh-cn/kb/3138327) 和 [Microsoft 知识库文章 3138328](https://support.microsoft.com/zh-cn/kb/3138328)。
-   V3.1（2016 年 3 月 25 日）： 对于 MS16-028，从 Windows 操作系统和组件（见表 1，共 2 个表）中删除了 Windows Server 2012（服务器核心安装），因为它不受影响。 此仅为信息变更。

*页面生成时间：2016-03-25 11:32-07:00。*
