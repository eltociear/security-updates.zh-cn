---
TOCTitle: 'MS14-DEC'
Title: 'Microsoft 安全公告摘要（2014 年 12 月）'
ms:assetid: 'ms14-dec'
ms:contentKeyID: 63745970
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms14-dec(v=Security.10)'
---



Microsoft 安全公告摘要（2014 年 12 月）
=======================================

发布日期： 2014 年 12 月 9 日

**版本：** 1.0

本公告摘要列出了 2014 年 12 月发布的安全公告。

对于 2014 年 12 月发布的安全公告，本公告摘要替代 2014 年 12 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/zh-cn/security/gg309152.aspx)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。 请参阅**其他信息**部分。

摘要
----

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>公告标题和执行摘要</strong></p></td>
<td style="border:1px solid black;"><p><strong>最高严重等级和漏洞影响</strong></p></td>
<td style="border:1px solid black;"><p><strong>重新启动要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms14-075">MS14-075</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Exchange Server 中的漏洞可能允许特权提升 (3009712)<br />
<br />
</strong>此安全更新可解决 Microsoft Exchange Server 中 4 个私下报告的漏洞。 如果用户单击经特殊设计定向到目标 Outlook Web App 网站的 URL，则其中最严重的漏洞可能允许特权提升。 攻击者无法强迫用户访问经特殊设计的网站。 相反，攻击者必须诱使用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站，然后诱使他们单击经特殊设计的 URL。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Exchange</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新 (3008923)<br />
<br />
</strong>此安全更新可解决 Internet Explorer 中 14 个私下报告的漏洞。 最严重的漏洞可能在用户使用 Internet Explorer 查看经特殊设计的网页时允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Word 和 Microsoft Office Web App 中的漏洞可能允许远程执行代码 (3017301)<br />
<br />
</strong>此安全更新解决了 Microsoft Word 和 Microsoft Office Web App 中 2 个私下报告的漏洞。 如果攻击者诱使用户在受影响的 Microsoft Office 软件版本中打开或预览经特殊设计的 Microsoft Word 文件，这些漏洞可能允许远程执行代码。 成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。 如果当前用户使用管理用户权限登录，则攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519135">MS14-082</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (3017349)<br />
<br />
</strong>此安全更新可解决 Microsoft Office 中一个私下报告的漏洞。 如果在受影响的 Microsoft Office 版本中打开经特殊设计的文件，则该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Excel 中的这些漏洞可能允许远程执行代码 (3017347)<br />
<br />
</strong>此安全更新可解决 Microsoft Excel 中两个私下报告的漏洞。 如果攻击者诱使用户在受影响的 Microsoft Office 软件版本中打开或预览经特殊设计的 Microsoft Excel 文件，这些漏洞可能允许远程执行代码。 成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。 如果当前用户使用管理用户权限登录，则攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519131">MS14-084</a></p></td>
<td style="border:1px solid black;"><p><strong>VBScript 脚本引擎中的漏洞可能允许远程执行代码 (3016711)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 的 VBScript 脚本引擎中一个私下报告的漏洞。 如果用户访问经特殊设计的网站，此漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。 如果当前用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519129">MS14-085</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Graphics 组件中的漏洞可能允许信息泄露 (3013126)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。 如果用户浏览包含经特殊设计的 JPEG 内容的网站，该漏洞可能允许信息泄露。 攻击者可能使用该信息泄露漏洞获取有关系统的信息，然后结合其他攻击手段来破坏该系统。 信息泄露漏洞自身不允许执行任意代码。 然而，攻击者可以结合其他漏洞使用该信息泄露漏洞绕过地址空间布局随机化 (ASLR) 等安全功能。</p></td>
<td style="border:1px solid black;"><p><a href="http://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
信息泄露</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>
  
 
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。 根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/zh-cn/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
<table style="width:100%;">  
<colgroup>  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
</colgroup>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>漏洞标题</strong></p></td>
<td style="border:1px solid black;"><p><strong>CVE ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>最新软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>重要注意事项</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms14-075">MS14-075</a></p></td>
<td style="border:1px solid black;"><p>Outlook Web App 令牌欺骗漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6319">CVE-2014-6319</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。 在社交工程攻击中，此漏洞可用于欺骗。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms14-075">MS14-075</a></p></td>
<td style="border:1px solid black;"><p>OWA XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6325">CVE-2014-6325</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms14-075">MS14-075</a></p></td>
<td style="border:1px solid black;"><p>OWA XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6326">CVE-2014-6326</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms14-075">MS14-075</a></p></td>
<td style="border:1px solid black;"><p>Exchange URL 重定向漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6336">CVE-2014-6336</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。 在社交工程攻击中，此漏洞可用于欺骗。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6327">CVE-2014-6327</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer XSS 筛选器绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6328">CVE-2014-6328</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个绕过安全功能漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6329">CVE-2014-6329</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6330">CVE-2014-6330</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>VBScript 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer XSS 筛选器绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6365">CVE-2014-6365</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个绕过安全功能漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6366">CVE-2014-6366</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer ASLR 绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6368">CVE-2014-6368</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个绕过安全功能漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6369">CVE-2014-6369</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6373">CVE-2014-6373</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6374">CVE-2014-6374</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6375">CVE-2014-6375</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6376">CVE-2014-6376</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-8966">CVE-2014-8966</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></p></td>
<td style="border:1px solid black;"><p>无效索引远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6356">CVE-2014-6356</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></p></td>
<td style="border:1px solid black;"><p>释放后使用 Word 远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6357">CVE-2014-6357</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519135">MS14-082</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 组件释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6364">CVE-2014-6364</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></p></td>
<td style="border:1px solid black;"><p>Excel 中全局空闲远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6360">CVE-2014-6360</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></p></td>
<td style="border:1px solid black;"><p>Excel 无效指针远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6361">CVE-2014-6361</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519131">MS14-084</a></p></td>
<td style="border:1px solid black;"><p>VBScript 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="http://go.microsoft.com/fwlink/?linkid=519129">MS14-085</a></p></td>
<td style="border:1px solid black;"><p>Graphics 组件信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6355">CVE-2014-6355</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。</p></td>
</tr>  
</tbody>  
</table>
  
 
  
受影响的软件  
------------
  
<span id="sectionToggle2"></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">  
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
（中等）  
Internet Explorer 7  
(3008923)  
（中等）  
Internet Explorer 8  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
（中等）  
VBScript 5.7   
(3012172)  
（中等）  
VBScript 5.8   
(3012176)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
（中等）  
Internet Explorer 7  
(3008923)  
（中等）  
Internet Explorer 8  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
（中等）  
VBScript 5.7   
(3012172)  
（中等）  
VBScript 5.8   
(3012176)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
（中等）  
Internet Explorer 7  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
（中等）  
VBScript 5.7   
(3012172)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
（严重）  
Internet Explorer 8  
(3008923)  
（严重）  
Internet Explorer 9  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
（严重）  
VBScript 5.8   
（仅适用于安装了 IE8 的系统）<sup>[1]</sup>  
(3012176)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
（严重）  
Internet Explorer 8  
(3008923)  
（严重）  
Internet Explorer 9  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
（严重）  
VBScript 5.8   
（仅适用于安装了 IE8 的系统）<sup>[1]</sup>  
(3012176)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
（中等）  
Internet Explorer 8  
(3008923)  
（中等）  
Internet Explorer 9  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
（中等）  
VBScript 5.8   
（仅适用于安装了 IE8 的系统）<sup>[1]</sup>  
(3012176)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
（中等）  
Internet Explorer 8  
(3008923)  
（中等）  
Internet Explorer 9  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
（中等）  
VBScript 5.8   
（仅适用于安装了 IE8 的系统）<sup>[1]</sup>  
(3012176)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
（严重）  
Internet Explorer 9  
(3008923)  
（严重）  
Internet Explorer 10  
(3008923)  
（严重）  
Internet Explorer 11  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
VBScript 5.8   
（仅适用于安装了 IE8 的系统）<sup>[1]</sup>  
(3012176)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
（严重）  
Internet Explorer 9  
(3008923)  
（严重）  
Internet Explorer 10  
(3008923)  
（严重）  
Internet Explorer 11  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
VBScript 5.8   
（仅适用于安装了 IE8 的系统）<sup>[1]</sup>  
(3012176)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
（中等）  
Internet Explorer 9  
(3008923)  
（中等）  
Internet Explorer 10  
(3008923)  
（中等）  
Internet Explorer 11  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.8   
（仅适用于安装了 IE8 的系统）<sup>[1]</sup>  
(3012176)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.8   
（仅适用于安装了 IE8 的系统）<sup>[1]</sup>  
(3012176)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

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
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
（无严重等级）<sup>[2]</sup>  
VBScript 5.8   
(3012176)  
（无严重等级）<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
（无严重等级）<sup>[2]</sup>  
VBScript 5.8   
(3012176)  
（无严重等级）<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(3012176)  
（无严重等级）<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3013126)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3013126)  
（重要）

</td>
</tr>
</table>

**MS14-080 注释**

Windows Technical Preview 和 Windows Server Technical Preview 均受到影响。 鼓励运行这些操作系统的客户应用此更新，此更新通过 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供。

**MS14-084 注释**

VBScript 5.8 更新可用于 Windows Technical Preview 和 Windows Server Technical Preview，并通过 Internet Explorer 累积更新 3008923 ([MS14-080](http://go.microsoft.com/fwlink/?linkid=521659)) 的方式提供。 鼓励运行预览版的客户应用此更新，此更新通过 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供。

<sup>[1]</sup>应用于安装了 Internet Explorer 8 的系统上。 其系统运行 Internet Explorer 9 或更高版本的客户应应用 Internet Explorer 累积更新 ([MS14-080](http://go.microsoft.com/fwlink/?linkid=521659))，这也解决了 MS14-084 中讨论的漏洞。

<sup>[2]</sup>严重等级不适用于指定软件，因为 MS14-084 中讨论的漏洞通过 Internet Explorer 进行的已知攻击媒介被阻止。 然而，作为一种纵深防御措施，Microsoft 建议这款软件的客户应用此安全更新，以帮助抵御将来识别的任何可能的新攻击媒介。

 

### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-075**](https://technet.microsoft.com/zh-cn/library/security/ms14-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2996150)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-075**](https://technet.microsoft.com/zh-cn/library/security/ms14-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2986475)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3011140)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 6  
(3011140)  
（重要）

</td>
</tr>
</table>

 

### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2920793)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2596927)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2984942)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2899518)  
（严重）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(2899519)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2553154)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(2910902)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2899518)  
（严重）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(2899519)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2553154)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(2910902)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013 和 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）  
(2910916)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）  
(2726958)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013（32 位版本）  
(2910929)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1（32 位版本）  
(2910916)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(2726958)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(2910929)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）  
(2910916)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）  
(2726958)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013（64 位版本）  
(2910929)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1（64 位版本）  
(2910916)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）  
(2726958)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(2910929)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT  
(2910916)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2726958)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2910929)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT Service Pack 1  
(2910916)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2726958)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(2910929)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3018888)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2920729)  
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
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2920792)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2920790)  
（重要）

</td>
</tr>
</table>

**MS14-081 注释**

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
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2899581)  
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
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883050)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883050)  
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
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2910892)  
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
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](http://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2889851)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(2889851)  
（重要）

</td>
</tr>
</table>

**MS14-081 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](http://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。 有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn820091.aspx)。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。 带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199/zh-cn)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://www.microsoft.com/downloads/results.aspx?displaylang=zh-cn&freetext=security%20update)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Microsoft Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086/zh-cn)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](http://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害： [病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

本地支持（根据您的国家/地区）： [国际支持](http://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州/地区不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2014 年 12 月 9 日）： 已发布公告摘要。

*页面生成时间：2014-12-04 13:31Z-08:00。*
