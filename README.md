<h1 align="center">WindowsPrivilegeEscalation</h1>

<p align="center">
  <img      src="https://visitor-badge.glitch.me/badge?page_id=https://github.com/ycdxsb/WindowsPrivilegeEscalation/README.md"/>
  <img      src="https://img.shields.io/github/stars/ycdxsb/WindowsPrivilegeEscalation"/>
  <img      src="https://img.shields.io/github/forks/ycdxsb/WindowsPrivilegeEscalation"/>
  <img      src="https://img.shields.io/github/issues/ycdxsb/WindowsPrivilegeEscalation"/>
  <img      src="https://img.shields.io/github/license/ycdxsb/WindowsPrivilegeEscalation"/>
</p>
<p align="center">
<img      src="https://img.shields.io/github/commit-activity/m/ycdxsb/WindowsPrivilegeEscalation"/>
<img      src="https://img.shields.io/github/last-commit/ycdxsb/WindowsPrivilegeEscalation"/>
<img      src="https://img.shields.io/github/repo-size/ycdxsb/WindowsPrivilegeEscalation"/>
</p>

> A collection of Windows Privilege Escalation vulnerabilities (Analyse / PoC / Exp )
>
> Based on:
>
> - [PocOrExp_in_Github](https://github.com/ycdxsb/PocOrExp_in_Github/)
> - [KernelHub](https://github.com/Ascotbe/Kernelhub)
> - [Windows_kernel_exploits](https://github.com/SecWiki/windows-kernel-exploits)
> - [exploitdb](https://github.com/offensive-security/exploitdb/tree/master/exploits)




- [2023](#2023)
  - [CVE-2023-21823](#cve-2023-21823)
  - [CVE-2023-21768](#cve-2023-21768)
  - [CVE-2023-21752](#cve-2023-21752)
- [2022](#2022)
  - [CVE-2022-37969](#cve-2022-37969)
  - [CVE-2022-37967](#cve-2022-37967)
  - [CVE-2022-35841](#cve-2022-35841)
  - [CVE-2022-34718](#cve-2022-34718)
  - [CVE-2022-34715](#cve-2022-34715)
  - [CVE-2022-33679](#cve-2022-33679)
  - [CVE-2022-30206](#cve-2022-30206)
  - [CVE-2022-30136](#cve-2022-30136)
  - [CVE-2022-26937](#cve-2022-26937)
  - [CVE-2022-26923](#cve-2022-26923)
  - [CVE-2022-26809](#cve-2022-26809)
  - [CVE-2022-24494](#cve-2022-24494)
  - [CVE-2022-24483](#cve-2022-24483)
- [2021](#2021)
  - [CVE-2021-43893](#cve-2021-43893)
  - [CVE-2021-43883/CVE-2021-41379](#cve-2021-43883cve-2021-41379)
  - [CVE-2021-43224](#cve-2021-43224)
  - [CVE-2021-42278/CVE-2021-42278](#cve-2021-42278cve-2021-42278)
  - [CVE-2021-40449](#cve-2021-40449)
  - [CVE-2021-40444](#cve-2021-40444)
  - [CVE-2021-38639](#cve-2021-38639)
  - [CVE-2021-36934](#cve-2021-36934)
  - [CVE-2021-34527](#cve-2021-34527)
  - [CVE-2021-34486](#cve-2021-34486)
  - [CVE-2021-33739](#cve-2021-33739)
  - [CVE-2021-31956](#cve-2021-31956)
  - [CVE-2021-28310](#cve-2021-28310)
  - [CVE-2021-26868](#cve-2021-26868)
  - [CVE-2021-24096](#cve-2021-24096)
  - [CVE-2021-21551](#cve-2021-21551)
  - [CVE-2021-1732](#cve-2021-1732)
- [2020](#2020)
  - [CVE-2020-17087](#cve-2020-17087)
  - [CVE-2020-17057](#cve-2020-17057)
  - [CVE-2020-16898](#cve-2020-16898)
  - [CVE-2020-1362](#cve-2020-1362)
  - [CVE-2020-1350](#cve-2020-1350)
  - [CVE-2020-1337](#cve-2020-1337)
  - [CVE-2020-1313](#cve-2020-1313)
  - [CVE-2020-1301](#cve-2020-1301)
  - [CVE-2020-1066](#cve-2020-1066)
  - [CVE-2020-1054](#cve-2020-1054)
  - [CVE-2020-1048](#cve-2020-1048)
  - [CVE-2020-1034](#cve-2020-1034)
  - [CVE-2020-1015](#cve-2020-1015)
  - [CVE-2020-0883](#cve-2020-0883)
  - [CVE-2020-0814](#cve-2020-0814)
  - [CVE-2020-0796](#cve-2020-0796)
  - [CVE-2020-0787](#cve-2020-0787)
  - [CVE-2020-0754](#cve-2020-0754)
  - [CVE-2020-0753](#cve-2020-0753)
  - [CVE-2020-0683](#cve-2020-0683)
  - [CVE-2020-0668](#cve-2020-0668)
  - [CVE-2020-0624](#cve-2020-0624)
  - [CVE-2020-0610](#cve-2020-0610)
  - [CVE-2020-0609](#cve-2020-0609)
- [2019](#2019)
  - [CVE-2019-1477](#cve-2019-1477)
  - [CVE-2019-1476](#cve-2019-1476)
  - [CVE-2019-1458](#cve-2019-1458)
  - [CVE-2019-1422](#cve-2019-1422)
  - [CVE-2019-1405](#cve-2019-1405)
  - [CVE-2019-1388](#cve-2019-1388)
  - [CVE-2019-1385](#cve-2019-1385)
  - [CVE-2019-1322](#cve-2019-1322)
  - [CVE-2019-1315](#cve-2019-1315)
  - [CVE-2019-1253](#cve-2019-1253)
  - [CVE-2019-1215](#cve-2019-1215)
  - [CVE-2019-1132](#cve-2019-1132)
  - [CVE-2019-1129/1130](#cve-2019-11291130)
  - [CVE-2019-1064](#cve-2019-1064)
  - [CVE-2019-1040](#cve-2019-1040)
  - [CVE-2019-0986](#cve-2019-0986)
  - [CVE-2019-0863](#cve-2019-0863)
  - [CVE-2019-0859](#cve-2019-0859)
  - [CVE-2019-0803](#cve-2019-0803)
  - [CVE-2019-0708](#cve-2019-0708)
  - [CVE-2019-0623](#cve-2019-0623)
- [2018](#2018)
  - [CVE-2018-8639](#cve-2018-8639)
  - [CVE-2018-8453](#cve-2018-8453)
  - [CVE-2018-8440](#cve-2018-8440)
  - [CVE-2018-8414](#cve-2018-8414)
  - [CVE-2018-8120](#cve-2018-8120)
  - [CVE-2018-7249](#cve-2018-7249)
  - [CVE-2018-1038](#cve-2018-1038)
  - [CVE-2018-0886](#cve-2018-0886)
  - [CVE-2018-0824](#cve-2018-0824)
- [2017](#2017)
  - [CVE-2017-11783](#cve-2017-11783)
  - [CVE-2017-8543](#cve-2017-8543)
  - [CVE-2017-8465](#cve-2017-8465)
  - [CVE-2017-8464](#cve-2017-8464)
  - [CVE-2017-7269](#cve-2017-7269)
  - [CVE-2017-0290](#cve-2017-0290)
  - [CVE-2017-0263](#cve-2017-0263)
  - [CVE-2017-0213](#cve-2017-0213)
  - [CVE-2017-0143 (MS17-010)](#cve-2017-0143-ms17-010)
  - [CVE-2017-0101 (MS17-017)](#cve-2017-0101-ms17-017)
  - [CVE-2017-0100 (MS17-012)](#cve-2017-0100-ms17-012)
  - [CVE-2017-0005 (MS17-013)](#cve-2017-0005-ms17-013)
- [2016](#2016)
  - [CVE-2016-7255 (MS16-135)](#cve-2016-7255-ms16-135)
  - [CVE-2016-3371 (MS16-111)](#cve-2016-3371-ms16-111)
  - [CVE-2016-3308/3309 (MS16-098)](#cve-2016-33083309-ms16-098)
  - [CVE-2016-3225 (MS16-075)](#cve-2016-3225-ms16-075)
  - [CVE-2016-0099 (MS16-032)](#cve-2016-0099-ms16-032)
  - [CVE-2016-0095 (MS16-034)](#cve-2016-0095-ms16-034)
  - [CVE-2016-0051 (MS16-016)](#cve-2016-0051-ms16-016)
  - [CVE-2016-0041 (MS16-014)](#cve-2016-0041-ms16-014)
- [2015](#2015)
  - [CVE-2015-2546 (MS15-097)](#cve-2015-2546-ms15-097)
  - [CVE-2015-2387 (MS15-077)](#cve-2015-2387-ms15-077)
  - [CVE-2015-2370 (MS15-076)](#cve-2015-2370-ms15-076)
  - [CVE-2015-1726 (MS15-061)](#cve-2015-1726-ms15-061)
  - [CVE-2015-1701 (MS15-051)](#cve-2015-1701-ms15-051)
  - [CVE-2015-0062 (MS15-015)](#cve-2015-0062-ms15-015)
  - [CVE-2015-0057 (MS15-010)](#cve-2015-0057-ms15-010)
  - [CVE-2015-0003 (MS15-010)](#cve-2015-0003-ms15-010)
  - [CVE-2015-0002 (MS15-001)](#cve-2015-0002-ms15-001)
- [2014](#2014)
  - [CVE-2014-6324 (MS14-068)](#cve-2014-6324-ms14-068)
  - [CVE-2014-6321 (MS14-066)](#cve-2014-6321-ms14-066)
  - [CVE-2014-4113 (MS14-058)](#cve-2014-4113-ms14-058)
  - [CVE-2014-4076 (MS14-070)](#cve-2014-4076-ms14-070)
  - [CVE-2014-1767 (MS14-040)](#cve-2014-1767-ms14-040)
- [2013](#2013)
  - [CVE-2013-5065 (MS14-002)](#cve-2013-5065-ms14-002)
  - [CVE-2013-1345 (MS13-053)](#cve-2013-1345-ms13-053)
  - [CVE-2013-1332 (MS13-046)](#cve-2013-1332-ms13-046)
  - [CVE-2013-1300 (MS13-053)](#cve-2013-1300-ms13-053)
  - [CVE-2013-0008 (MS13-005)](#cve-2013-0008-ms13-005)
- [2012](#2012)
  - [CVE-2012-0217 (MS12-042)](#cve-2012-0217-ms12-042)
  - [CVE-2012-0152 (MS12-020)](#cve-2012-0152-ms12-020)
  - [CVE-2012-0002 (MS12-020)](#cve-2012-0002-ms12-020)
- [2011](#2011)
  - [CVE-2011-2005 (MS11-080)](#cve-2011-2005-ms11-080)
  - [CVE-2011-1974 (MS11-062)](#cve-2011-1974-ms11-062)
  - [CVE-2011-1249 (MS11-046)](#cve-2011-1249-ms11-046)
  - [CVE-2011-1237 (MS11-034)](#cve-2011-1237-ms11-034)
  - [CVE-2011-0045 (MS11-011)](#cve-2011-0045-ms11-011)
- [2010](#2010)
  - [CVE-2010-3338 (MS10-092)](#cve-2010-3338-ms10-092)
  - [CVE-2010-2730 (MS10-065)](#cve-2010-2730-ms10-065)
  - [CVE-2010-2554 (MS10-059)](#cve-2010-2554-ms10-059)
  - [CVE-2010-1897 (MS10-048)](#cve-2010-1897-ms10-048)
  - [CVE-2010-1887 (MS10-048)](#cve-2010-1887-ms10-048)
  - [CVE-2010-0270 (MS10-020)](#cve-2010-0270-ms10-020)
  - [CVE-2010-0233 (MS10-015)](#cve-2010-0233-ms10-015)
  - [CVE-2010-0020 (MS10-012)](#cve-2010-0020-ms10-012)
- [2009](#2009)
  - [CVE-2009-2532 (MS09-050)](#cve-2009-2532-ms09-050)
  - [CVE-2009-1535 (MS09-020)](#cve-2009-1535-ms09-020)
  - [CVE-2009-0229 (MS09-022)](#cve-2009-0229-ms09-022)
  - [CVE-2009-0079 (MS09-012)](#cve-2009-0079-ms09-012)
- [2008](#2008)
  - [CVE-2008-4250 (MS08-067)](#cve-2008-4250-ms08-067)
  - [CVE-2008-4037 (MS08-068)](#cve-2008-4037-ms08-068)
  - [CVE-2008-3464 (MS08-066)](#cve-2008-3464-ms08-066)
  - [CVE-2008-1084 (MS08-025)](#cve-2008-1084-ms08-025)
- [2007](#2007)
  - [CVE-2007-0843](#cve-2007-0843)
  - [CVE-2007-0038](#cve-2007-0038)
- [2006](#2006)
  - [CVE-2006-3439 (MS06-040)](#cve-2006-3439-ms06-040)
- [2005](#2005)
  - [CVE-2005-1983 (MS05-039)](#cve-2005-1983-ms05-039)
- [2003](#2003)
  - [CVE-2003-0352 (MS03-026)](#cve-2003-0352-ms03-026)
- [2000](#2000)
  - [CVE-2000-0979](#cve-2000-0979)

# 2023

## CVE-2023-21823

> Windows Graphics Component Remote Code Execution Vulnerability

- **Exp**
  - [https://github.com/Elizarfish/CVE-2023-21823](https://github.com/Elizarfish/CVE-2023-21823) :  ![starts](https://img.shields.io/github/stars/Elizarfish/CVE-2023-21823.svg) ![forks](https://img.shields.io/github/forks/Elizarfish/CVE-2023-21823.svg)



## CVE-2023-21768

> Windows Ancillary Function Driver for WinSock Elevation of Privilege Vulnerability

- **Analyse**
  - https://www.zoemurmure.top/posts/cve_2023_21768/
  - https://securityintelligence.com/posts/patch-tuesday-exploit-wednesday-pwning-windows-ancillary-function-driver-winsock/
  - https://mp.weixin.qq.com/s/9W9puJltbK-xto2A1duqgQ
- **Exp**
  - [https://github.com/SamuelTulach/nullmap](https://github.com/SamuelTulach/nullmap) :  ![starts](https://img.shields.io/github/stars/SamuelTulach/nullmap.svg) ![forks](https://img.shields.io/github/forks/SamuelTulach/nullmap.svg)
  - [https://github.com/Malwareman007/CVE-2023-21768](https://github.com/Malwareman007/CVE-2023-21768) :  ![starts](https://img.shields.io/github/stars/Malwareman007/CVE-2023-21768.svg) ![forks](https://img.shields.io/github/forks/Malwareman007/CVE-2023-21768.svg)
  - [https://github.com/CKevens/CVE-2023-21768-POC](https://github.com/CKevens/CVE-2023-21768-POC) :  ![starts](https://img.shields.io/github/stars/CKevens/CVE-2023-21768-POC.svg) ![forks](https://img.shields.io/github/forks/CKevens/CVE-2023-21768-POC.svg)
  - [https://github.com/cl4ym0re/cve-2023-21768-compiled](https://github.com/cl4ym0re/cve-2023-21768-compiled) :  ![starts](https://img.shields.io/github/stars/cl4ym0re/cve-2023-21768-compiled.svg) ![forks](https://img.shields.io/github/forks/cl4ym0re/cve-2023-21768-compiled.svg)
  - [https://github.com/zoemurmure/CVE-2023-21768-AFD-for-WinSock-EoP-exploit](https://github.com/zoemurmure/CVE-2023-21768-AFD-for-WinSock-EoP-exploit) :  ![starts](https://img.shields.io/github/stars/zoemurmure/CVE-2023-21768-AFD-for-WinSock-EoP-exploit.svg) ![forks](https://img.shields.io/github/forks/zoemurmure/CVE-2023-21768-AFD-for-WinSock-EoP-exploit.svg)
  - [https://github.com/h1bAna/CVE-2023-21768](https://github.com/h1bAna/CVE-2023-21768) :  ![starts](https://img.shields.io/github/stars/h1bAna/CVE-2023-21768.svg) ![forks](https://img.shields.io/github/forks/h1bAna/CVE-2023-21768.svg)
  - [https://github.com/HKxiaoli/Windows_AFD_LPE_CVE-2023-21768](https://github.com/HKxiaoli/Windows_AFD_LPE_CVE-2023-21768) :  ![starts](https://img.shields.io/github/stars/HKxiaoli/Windows_AFD_LPE_CVE-2023-21768.svg) ![forks](https://img.shields.io/github/forks/HKxiaoli/Windows_AFD_LPE_CVE-2023-21768.svg)

## CVE-2023-21752

> Windows Backup Service Elevation of Privilege Vulnerability

- **Analyse**
  - https://blog.0patch.com/2023/01/micropatching-arbitrary-file-delete.html
- **Exp**
  - [https://github.com/Wh04m1001/CVE-2023-21752](https://github.com/Wh04m1001/CVE-2023-21752) :  ![starts](https://img.shields.io/github/stars/Wh04m1001/CVE-2023-21752.svg) ![forks](https://img.shields.io/github/forks/Wh04m1001/CVE-2023-21752.svg)


# 2022

## CVE-2022-37969

> Windows Common Log File System Driver Elevation of Privilege Vulnerability

- **Analyse**
  - https://www.coresecurity.com/core-labs/articles/understanding-cve-2022-37969-windows-clfs-lpe
  - https://www.zscaler.com/blogs/security-research/technical-analysis-windows-clfs-zero-day-vulnerability-cve-2022-37969-part
- **PoC**
  - [https://github.com/fortra/CVE-2022-37969](https://github.com/fortra/CVE-2022-37969) :  ![starts](https://img.shields.io/github/stars/fortra/CVE-2022-37969.svg) ![forks](https://img.shields.io/github/forks/fortra/CVE-2022-37969.svg)

## CVE-2022-37967

> Windows Kerberos Elevation of Privilege Vulnerability

- **Analyse**
  - https://geekmungus.co.uk/?p=3619
- **PoC**
  - [https://github.com/bmcmcm/Get-msDSSupportedEncryptionTypes](https://github.com/bmcmcm/Get-msDSSupportedEncryptionTypes) :  ![starts](https://img.shields.io/github/stars/bmcmcm/Get-msDSSupportedEncryptionTypes.svg) ![forks](https://img.shields.io/github/forks/bmcmcm/Get-msDSSupportedEncryptionTypes.svg)

## CVE-2022-35841

> Windows Enterprise App Management Service Remote Code Execution Vulnerability

- **Analyse**
  - [https://github.com/Wack0/CVE-2022-35841](https://github.com/Wack0/CVE-2022-35841) :  ![starts](https://img.shields.io/github/stars/Wack0/CVE-2022-35841.svg) ![forks](https://img.shields.io/github/forks/Wack0/CVE-2022-35841.svg)




## CVE-2022-34718

> Windows TCP/IP Remote Code Execution Vulnerability

- **Analyse**
  - https://medium.com/numen-cyber-labs/analysis-and-summary-of-tcp-ip-protocol-remote-code-execution-vulnerability-cve-2022-34718-8fcc28538acf
  - https://securityonline.info/researchers-release-poc-for-windows-tcp-ip-rce-flaw-cve-2022-34718/
  - https://securityintelligence.com/posts/dissecting-exploiting-tcp-ip-rce-vulnerability-evilesp/
- **PoC**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/SecLabResearchBV/CVE-2022-34718-PoC](https://github.com/SecLabResearchBV/CVE-2022-34718-PoC) :  ![starts](https://img.shields.io/github/stars/SecLabResearchBV/CVE-2022-34718-PoC.svg) ![forks](https://img.shields.io/github/forks/SecLabResearchBV/CVE-2022-34718-PoC.svg)

## CVE-2022-34715

> Windows Network File System Remote Code Execution Vulnerability.

- **Analyse**
  - https://www.thezdi.com/blog/2022/8/31/cve-2022-34715-more-microsoft-windows-nfs-v4-remote-code-execution
- **PoC**
  - [https://github.com/Starssgo/CVE-2022-34715-POC](https://github.com/Starssgo/CVE-2022-34715-POC) :  ![starts](https://img.shields.io/github/stars/Starssgo/CVE-2022-34715-POC.svg) ![forks](https://img.shields.io/github/forks/Starssgo/CVE-2022-34715-POC.svg)


## CVE-2022-33679

> Windows Kerberos Elevation of Privilege Vulnerability

- **Analyse**
  - https://googleprojectzero.blogspot.com/2022/10/rc4-is-still-considered-harmful.html
  - https://bugs.chromium.org/p/project-zero/issues/detail?id=2310
  - https://www.silverfort.com/blog/technical-analysis-of-cve-2022-33679-and-cve-2022-33647-kerberos-vulnerabilities/
  - https://www.horizon3.ai/from-cve-2022-33679-to-unauthenticated-kerberoasting/
- **PoC**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/Bdenneu/CVE-2022-33679](https://github.com/Bdenneu/CVE-2022-33679) :  ![starts](https://img.shields.io/github/stars/Bdenneu/CVE-2022-33679.svg) ![forks](https://img.shields.io/github/forks/Bdenneu/CVE-2022-33679.svg)
  - [https://github.com/Amulab/CVE-2022-33679](https://github.com/Amulab/CVE-2022-33679) :  ![starts](https://img.shields.io/github/stars/Amulab/CVE-2022-33679.svg) ![forks](https://img.shields.io/github/forks/Amulab/CVE-2022-33679.svg)
  - [https://github.com/notareaperbutDR34P3r/Kerberos_CVE-2022-33679](https://github.com/notareaperbutDR34P3r/Kerberos_CVE-2022-33679) :  ![starts](https://img.shields.io/github/stars/notareaperbutDR34P3r/Kerberos_CVE-2022-33679.svg) ![forks](https://img.shields.io/github/forks/notareaperbutDR34P3r/Kerberos_CVE-2022-33679.svg)
  - [https://github.com/Blyth0He/CVE-2022-33679](https://github.com/Blyth0He/CVE-2022-33679) :  ![starts](https://img.shields.io/github/stars/Blyth0He/CVE-2022-33679.svg) ![forks](https://img.shields.io/github/forks/Blyth0He/CVE-2022-33679.svg)



## CVE-2022-30206

> Windows Print Spooler Elevation of Privilege Vulnerability. This CVE ID is unique from CVE-2022-22022, CVE-2022-22041, CVE-2022-30226.

- **PoC**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/Pwnrin/CVE-2022-30206](https://github.com/Pwnrin/CVE-2022-30206) :  ![starts](https://img.shields.io/github/stars/Pwnrin/CVE-2022-30206.svg) ![forks](https://img.shields.io/github/forks/Pwnrin/CVE-2022-30206.svg)
  - [https://github.com/Malwareman007/CVE-2022-30206](https://github.com/Malwareman007/CVE-2022-30206) :  ![starts](https://img.shields.io/github/stars/Malwareman007/CVE-2022-30206.svg) ![forks](https://img.shields.io/github/forks/Malwareman007/CVE-2022-30206.svg)



## CVE-2022-30136

Windows Network File System Remote Code Execution Vulnerability.

- **Analyse**
  - https://www.coresecurity.com/core-labs/articles/analysis-cve-2022-30136-windows-network-file-system-vulnerability
  - https://www.zerodayinitiative.com/blog/2022/7/13/cve-2022-30136-microsoft-windows-network-file-system-v4-remote-code-execution-vulnerability
  - [https://github.com/fortra/CVE-2022-30136](https://github.com/fortra/CVE-2022-30136) :  ![starts](https://img.shields.io/github/stars/fortra/CVE-2022-30136.svg) ![forks](https://img.shields.io/github/forks/fortra/CVE-2022-30136.svg)
- **PoC**
  - [https://github.com/fortra/CVE-2022-30136](https://github.com/fortra/CVE-2022-30136) :  ![starts](https://img.shields.io/github/stars/fortra/CVE-2022-30136.svg) ![forks](https://img.shields.io/github/forks/fortra/CVE-2022-30136.svg)


## CVE-2022-26937

> Windows Network File System Remote Code Execution Vulnerability.

- **Analyse**
  - https://www.zerodayinitiative.com/blog/2022/6/7/cve-2022-26937-microsoft-windows-network-file-system-nlm-portmap-stack-buffer-overflow
- **PoC**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

  - [https://github.com/omair2084/CVE-2022-26937](https://github.com/omair2084/CVE-2022-26937) :  ![starts](https://img.shields.io/github/stars/omair2084/CVE-2022-26937.svg) ![forks](https://img.shields.io/github/forks/omair2084/CVE-2022-26937.svg)

  - [https://github.com/Malwareman007/CVE-2022-26937](https://github.com/Malwareman007/CVE-2022-26937) :  ![starts](https://img.shields.io/github/stars/Malwareman007/CVE-2022-26937.svg) ![forks](https://img.shields.io/github/forks/Malwareman007/CVE-2022-26937.svg)



## CVE-2022-26923

> Active Directory Domain Services Elevation of Privilege Vulnerability.

- **Analyse**
  - https://research.ifcr.dk/certifried-active-directory-domain-privilege-escalation-cve-2022-26923-9e098fe298f4
- **PoC**
  - [https://github.com/LudovicPatho/CVE-2022-26923_AD-Certificate-Services](https://github.com/LudovicPatho/CVE-2022-26923_AD-Certificate-Services) :  ![starts](https://img.shields.io/github/stars/LudovicPatho/CVE-2022-26923_AD-Certificate-Services.svg) ![forks](https://img.shields.io/github/forks/LudovicPatho/CVE-2022-26923_AD-Certificate-Services.svg)
  - [https://github.com/lsecqt/CVE-2022-26923-Powershell-POC](https://github.com/lsecqt/CVE-2022-26923-Powershell-POC) :  ![starts](https://img.shields.io/github/stars/lsecqt/CVE-2022-26923-Powershell-POC.svg) ![forks](https://img.shields.io/github/forks/lsecqt/CVE-2022-26923-Powershell-POC.svg)


## CVE-2022-26809

> Remote Procedure Call Runtime Remote Code Execution Vulnerability. This CVE ID is unique from CVE-2022-24492, CVE-2022-24528.

- **Analyse**
  - https://medium.com/@knownsec404team/recurrence-and-analysis-of-rpc-high-risk-vulnerability-cve-2022-26809-7851cc88f81c
  - https://s1ckb017.github.io/2022/06/17/CVE-2022-26809-Server-Side-vulnerable-point-reachability.html
  - https://www.linkedin.com/pulse/cve-2022-26809-dynamics-around-security-community-microsoft-analyzing-?trk=organization-update-content_share-article
- **PoC**
  - [https://github.com/s1ckb017/PoC-CVE-2022-26809](https://github.com/s1ckb017/PoC-CVE-2022-26809) :  ![starts](https://img.shields.io/github/stars/s1ckb017/PoC-CVE-2022-26809.svg) ![forks](https://img.shields.io/github/forks/s1ckb017/PoC-CVE-2022-26809.svg)
  - [https://github.com/yuanLink/CVE-2022-26809](https://github.com/yuanLink/CVE-2022-26809) :  ![starts](https://img.shields.io/github/stars/yuanLink/CVE-2022-26809.svg) ![forks](https://img.shields.io/github/forks/yuanLink/CVE-2022-26809.svg)
  - [https://github.com/michealadams30/Cve-2022-26809](https://github.com/michealadams30/Cve-2022-26809) :  ![starts](https://img.shields.io/github/stars/michealadams30/Cve-2022-26809.svg) ![forks](https://img.shields.io/github/forks/michealadams30/Cve-2022-26809.svg)

## CVE-2022-24494

> Windows Ancillary Function Driver for WinSock Elevation of Privilege Vulnerability.

- **PoC**
  - [https://github.com/vportal/AFD](https://github.com/vportal/AFD) :  ![starts](https://img.shields.io/github/stars/vportal/AFD.svg) ![forks](https://img.shields.io/github/forks/vportal/AFD.svg)


## CVE-2022-24483

> Windows Kernel Information Disclosure Vulnerability.

- **PoC**
  - [https://github.com/waleedassar/CVE-2022-24483](https://github.com/waleedassar/CVE-2022-24483) :  ![starts](https://img.shields.io/github/stars/waleedassar/CVE-2022-24483.svg) ![forks](https://img.shields.io/github/forks/waleedassar/CVE-2022-24483.svg)




# 2021

## CVE-2021-43893

> Windows Encrypting File System (EFS) Elevation of Privilege Vulnerability

- **Analyse**
  - https://www.rapid7.com/blog/post/2022/02/14/dropping-files-on-a-domain-controller-using-cve-2021-43893/
- **Exp**
  - [https://github.com/jbaines-r7/blankspace](https://github.com/jbaines-r7/blankspace) :  ![starts](https://img.shields.io/github/stars/jbaines-r7/blankspace.svg) ![forks](https://img.shields.io/github/forks/jbaines-r7/blankspace.svg)



## CVE-2021-43883/CVE-2021-41379

> Windows Installer Elevation of Privilege Vulnerability

- **Analyse**
  - https://attackerkb.com/topics/7LstI2clmF/cve-2021-41379/rapid7-analysis
- **Exp**
  - [https://github.com/klinix5/InstallerFileTakeOver](https://github.com/klinix5/InstallerFileTakeOver) :  ![starts](https://img.shields.io/github/stars/klinix5/InstallerFileTakeOver.svg) ![forks](https://img.shields.io/github/forks/klinix5/InstallerFileTakeOver.svg)
  - [https://github.com/jbaines-r7/shakeitoff](https://github.com/jbaines-r7/shakeitoff) :  ![starts](https://img.shields.io/github/stars/jbaines-r7/shakeitoff.svg) ![forks](https://img.shields.io/github/forks/jbaines-r7/shakeitoff.svg)



## CVE-2021-43224

> Windows Common Log File System Driver Information Disclosure Vulnerability

- **PoC**
  - [https://github.com/KaLendsi/CVE-2021-43224-POC](https://github.com/KaLendsi/CVE-2021-43224-POC) :  ![starts](https://img.shields.io/github/stars/KaLendsi/CVE-2021-43224-POC.svg) ![forks](https://img.shields.io/github/forks/KaLendsi/CVE-2021-43224-POC.svg)


## CVE-2021-42278/CVE-2021-42278

> Active Directory Domain Services Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-42282, CVE-2021-42287, CVE-2021-42291.

- **Analyse**
  - https://xz.aliyun.com/t/10666
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/cube0x0/noPac](https://github.com/cube0x0/noPac) :  ![starts](https://img.shields.io/github/stars/cube0x0/noPac.svg) ![forks](https://img.shields.io/github/forks/cube0x0/noPac.svg)
  - [https://github.com/WazeHell/sam-the-admin](https://github.com/WazeHell/sam-the-admin) :  ![starts](https://img.shields.io/github/stars/WazeHell/sam-the-admin.svg) ![forks](https://img.shields.io/github/forks/WazeHell/sam-the-admin.svg)
  - [https://github.com/ly4k/Pachine](https://github.com/ly4k/Pachine) :  ![starts](https://img.shields.io/github/stars/ly4k/Pachine.svg) ![forks](https://img.shields.io/github/forks/ly4k/Pachine.svg)
  - [https://github.com/Ridter/noPac](https://github.com/Ridter/noPac) :  ![starts](https://img.shields.io/github/stars/Ridter/noPac.svg) ![forks](https://img.shields.io/github/forks/Ridter/noPac.svg)
  - [https://github.com/waterrr/noPac](https://github.com/waterrr/noPac) :  ![starts](https://img.shields.io/github/stars/waterrr/noPac.svg) ![forks](https://img.shields.io/github/forks/waterrr/noPac.svg)

## CVE-2021-40449

> Win32k Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-40450, CVE-2021-41357.

- **Analyse**
  - https://www.secrss.com/articles/35266
  - https://bbs.pediy.com/thread-269930.htm
  - https://www.freebuf.com/articles/paper/292528.html
- **PoC**
  - [https://github.com/ly4k/CallbackHell](https://github.com/ly4k/CallbackHell) :  ![starts](https://img.shields.io/github/stars/ly4k/CallbackHell.svg) ![forks](https://img.shields.io/github/forks/ly4k/CallbackHell.svg)
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/KaLendsi/CVE-2021-40449-Exploit](https://github.com/KaLendsi/CVE-2021-40449-Exploit) :  ![starts](https://img.shields.io/github/stars/KaLendsi/CVE-2021-40449-Exploit.svg) ![forks](https://img.shields.io/github/forks/KaLendsi/CVE-2021-40449-Exploit.svg)
  - [https://github.com/hakivvi/CVE-2021-40449](https://github.com/hakivvi/CVE-2021-40449) :  ![starts](https://img.shields.io/github/stars/hakivvi/CVE-2021-40449.svg) ![forks](https://img.shields.io/github/forks/hakivvi/CVE-2021-40449.svg)

## CVE-2021-40444

> Microsoft MSHTML Remote Code Execution Vulnerability

- **Analyse**
  - https://paper.seebug.org/1718/
  - https://bbs.pediy.com/thread-270017.htm
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/lockedbyte/CVE-2021-40444](https://github.com/lockedbyte/CVE-2021-40444) :  ![starts](https://img.shields.io/github/stars/lockedbyte/CVE-2021-40444.svg) ![forks](https://img.shields.io/github/forks/lockedbyte/CVE-2021-40444.svg)
  - [https://github.com/klezVirus/CVE-2021-40444](https://github.com/klezVirus/CVE-2021-40444) :  ![starts](https://img.shields.io/github/stars/klezVirus/CVE-2021-40444.svg) ![forks](https://img.shields.io/github/forks/klezVirus/CVE-2021-40444.svg)

## CVE-2021-38639

> Win32k Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-36975.

- **PoC**
  - [https://github.com/DarkSprings/CVE-2021-38639](https://github.com/DarkSprings/CVE-2021-38639) :  ![starts](https://img.shields.io/github/stars/DarkSprings/CVE-2021-38639.svg) ![forks](https://img.shields.io/github/forks/DarkSprings/CVE-2021-38639.svg)

## CVE-2021-36934

> Windows Elevation of Privilege Vulnerability

- **Analyse**
  - https://www.jianshu.com/p/979ea7a93531
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/cube0x0/CVE-2021-36934](https://github.com/cube0x0/CVE-2021-36934) :  ![starts](https://img.shields.io/github/stars/cube0x0/CVE-2021-36934.svg) ![forks](https://img.shields.io/github/forks/cube0x0/CVE-2021-36934.svg)
  - [https://github.com/HuskyHacks/ShadowSteal](https://github.com/HuskyHacks/ShadowSteal) :  ![starts](https://img.shields.io/github/stars/HuskyHacks/ShadowSteal.svg) ![forks](https://img.shields.io/github/forks/HuskyHacks/ShadowSteal.svg)

## CVE-2021-34527

> Windows Print Spooler Remote Code Execution Vulnerability

- **Analyse**
- **PoC**
  - [https://github.com/byt3bl33d3r/ItWasAllADream](https://github.com/byt3bl33d3r/ItWasAllADream) :  ![starts](https://img.shields.io/github/stars/byt3bl33d3r/ItWasAllADream.svg) ![forks](https://img.shields.io/github/forks/byt3bl33d3r/ItWasAllADream.svg)
- **Exp**
  - [https://github.com/JohnHammond/CVE-2021-34527](https://github.com/JohnHammond/CVE-2021-34527) :  ![starts](https://img.shields.io/github/stars/JohnHammond/CVE-2021-34527.svg) ![forks](https://img.shields.io/github/forks/JohnHammond/CVE-2021-34527.svg)
  - [https://github.com/BeetleChunks/SpoolSploit](https://github.com/BeetleChunks/SpoolSploit) :  ![starts](https://img.shields.io/github/stars/BeetleChunks/SpoolSploit.svg) ![forks](https://img.shields.io/github/forks/BeetleChunks/SpoolSploit.svg)
  - [https://github.com/ly4k/PrintNightmare](https://github.com/ly4k/PrintNightmare) :  ![starts](https://img.shields.io/github/stars/ly4k/PrintNightmare.svg) ![forks](https://img.shields.io/github/forks/ly4k/PrintNightmare.svg)
  - [https://github.com/nemo-wq/PrintNightmare-CVE-2021-34527](https://github.com/nemo-wq/PrintNightmare-CVE-2021-34527) :  ![starts](https://img.shields.io/github/stars/nemo-wq/PrintNightmare-CVE-2021-34527.svg) ![forks](https://img.shields.io/github/forks/nemo-wq/PrintNightmare-CVE-2021-34527.svg)

## CVE-2021-34486

> Windows Event Tracing Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-26425, CVE-2021-34487.

- **Analyse**
  - https://www.pixiepointsecurity.com/blog/advisory-cve-2021-34486.html
- **Exp**
  - [https://github.com/KaLendsi/CVE-2021-34486](https://github.com/KaLendsi/CVE-2021-34486) :  ![starts](https://img.shields.io/github/stars/KaLendsi/CVE-2021-34486.svg) ![forks](https://img.shields.io/github/forks/KaLendsi/CVE-2021-34486.svg)
  - [https://github.com/b1tg/CVE-2021-34486-exp](https://github.com/b1tg/CVE-2021-34486-exp) :  ![starts](https://img.shields.io/github/stars/b1tg/CVE-2021-34486-exp.svg) ![forks](https://img.shields.io/github/forks/b1tg/CVE-2021-34486-exp.svg)

## CVE-2021-33739

> Microsoft DWM Core Library Elevation of Privilege Vulnerability

- **Analyse**
  - https://www.cnblogs.com/zUotTe0/p/15227947.html
  - https://zhuanlan.zhihu.com/p/384636717
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/giwon9977/CVE-2021-33739_PoC](https://github.com/giwon9977/CVE-2021-33739_PoC) :  ![starts](https://img.shields.io/github/stars/giwon9977/CVE-2021-33739_PoC.svg) ![forks](https://img.shields.io/github/forks/giwon9977/CVE-2021-33739_PoC.svg)
  - [https://github.com/freeide2017/CVE-2021-33739-POC](https://github.com/freeide2017/CVE-2021-33739-POC) :  ![starts](https://img.shields.io/github/stars/freeide2017/CVE-2021-33739-POC.svg) ![forks](https://img.shields.io/github/forks/freeide2017/CVE-2021-33739-POC.svg)

## CVE-2021-31956

> Windows NTFS Elevation of Privilege Vulnerability

- **Analyse**
  - https://research.nccgroup.com/2021/07/15/cve-2021-31956-exploiting-the-windows-kernel-ntfs-with-wnf-part-1/
  - https://research.nccgroup.com/2021/08/17/cve-2021-31956-exploiting-the-windows-kernel-ntfs-with-wnf-part-2/



## CVE-2021-28310

> Win32k Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-27072

- **Analyse**
  - https://securelist.com/zero-day-vulnerability-in-desktop-window-manager-cve-2021-28310-used-in-the-wild/101898/

## CVE-2021-26868

> Windows Graphics Component Elevation of Privilege Vulnerability

- **Analyse**
  - https://zhuanlan.zhihu.com/p/384636717
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/KangD1W2/CVE-2021-26868](https://github.com/KangD1W2/CVE-2021-26868) :  ![starts](https://img.shields.io/github/stars/KangD1W2/CVE-2021-26868.svg) ![forks](https://img.shields.io/github/forks/KangD1W2/CVE-2021-26868.svg)

## CVE-2021-24096

>  Windows Kernel Elevation of Privilege Vulnerability  

- **PoC**
  - [https://github.com/FunPhishing/CVE-2021-24096](https://github.com/FunPhishing/CVE-2021-24096) :  ![starts](https://img.shields.io/github/stars/FunPhishing/CVE-2021-24096.svg) ![forks](https://img.shields.io/github/forks/FunPhishing/CVE-2021-24096.svg)

## CVE-2021-21551

> Dell dbutil_2_3.sys driver contains an insufficient access control vulnerability which may lead to escalation of privileges, denial of service, or information disclosure. Local authenticated user access is required.

- **Analyse**
  - https://labs.sentinelone.com/cve-2021-21551-hundreds-of-millions-of-dell-computers-at-risk-due-to-multiple-bios-driver-privilege-escalation-flaws/
- **Exp**
  - [https://github.com/waldo-irc/CVE-2021-21551](https://github.com/waldo-irc/CVE-2021-21551) :  ![starts](https://img.shields.io/github/stars/waldo-irc/CVE-2021-21551.svg) ![forks](https://img.shields.io/github/forks/waldo-irc/CVE-2021-21551.svg)

## CVE-2021-1732

> Windows Win32k Elevation of Privilege Vulnerability This CVE ID is unique from CVE-2021-1698

- **Analyse**
  - https://www.freebuf.com/vuls/270295.html
  - https://021w.github.io/2021/03/12/CVE-2021-1732Win32kfull-sys%E5%86%85%E6%A0%B8%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/
  - https://laptrinhx.com/shen-ru-pou-xicve-2021-1732lou-dong-1153028117/
  - https://bbs.pediy.com/thread-266362.htm
  - https://www.secrss.com/articles/29758
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2021-1732](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2021-1732) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/KaLendsi/CVE-2021-1732-Exploit](https://github.com/KaLendsi/CVE-2021-1732-Exploit) :  ![starts](https://img.shields.io/github/stars/KaLendsi/CVE-2021-1732-Exploit.svg) ![forks](https://img.shields.io/github/forks/KaLendsi/CVE-2021-1732-Exploit.svg)
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2021-1732](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2021-1732) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)
  - [https://github.com/k-k-k-k-k/CVE-2021-1732](https://github.com/k-k-k-k-k/CVE-2021-1732) :  ![starts](https://img.shields.io/github/stars/k-k-k-k-k/CVE-2021-1732.svg) ![forks](https://img.shields.io/github/forks/k-k-k-k-k/CVE-2021-1732.svg)
  - [https://github.com/jessica0f0116/cve_2021_1732](https://github.com/jessica0f0116/cve_2021_1732) :  ![starts](https://img.shields.io/github/stars/jessica0f0116/cve_2021_1732.svg) ![forks](https://img.shields.io/github/forks/jessica0f0116/cve_2021_1732.svg)
  - [https://github.com/oneoy/CVE-2021-1732-Exploit](https://github.com/oneoy/CVE-2021-1732-Exploit) :  ![starts](https://img.shields.io/github/stars/oneoy/CVE-2021-1732-Exploit.svg) ![forks](https://img.shields.io/github/forks/oneoy/CVE-2021-1732-Exploit.svg)



# 2020

## CVE-2020-17087

> Windows Kernel Local Elevation of Privilege Vulnerability

- **Analyse**
  - https://blog.csdn.net/weixin_43815930/article/details/114123728
  - https://www.anquanke.com/post/id/221964
- **PoC**
  - [https://github.com/Ascotbe/Kernelhub/CVE-2020-17087](https://github.com/Ascotbe/Kernelhub/CVE-2020-17087) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/TinToSer/CVE2020-17087](https://github.com/TinToSer/CVE2020-17087) :  ![starts](https://img.shields.io/github/stars/TinToSer/CVE2020-17087.svg) ![forks](https://img.shields.io/github/forks/TinToSer/CVE2020-17087.svg)
  - [https://github.com/revengsh/CVE-2020-17087](https://github.com/revengsh/CVE-2020-17087) :  ![starts](https://img.shields.io/github/stars/revengsh/CVE-2020-17087.svg) ![forks](https://img.shields.io/github/forks/revengsh/CVE-2020-17087.svg)

## CVE-2020-17057

> Windows Win32k Elevation of Privilege Vulnerability

- **Analyse**
  - https://blogs.360.cn/post/CVE-2020-17057%20detail%20and%20exploit.html
- **PoC**
  - [https://github.com/ze0r/cve-2020-17057](https://github.com/ze0r/cve-2020-17057) :  ![starts](https://img.shields.io/github/stars/ze0r/cve-2020-17057.svg) ![forks](https://img.shields.io/github/forks/ze0r/cve-2020-17057.svg)
  - [https://github.com/lsw29475/CVE-2020-17057](https://github.com/lsw29475/CVE-2020-17057) :  ![starts](https://img.shields.io/github/stars/lsw29475/CVE-2020-17057.svg) ![forks](https://img.shields.io/github/forks/lsw29475/CVE-2020-17057.svg)

## CVE-2020-16898

> A remote code execution vulnerability exists when the Windows TCP/IP stack improperly handles ICMPv6 Router Advertisement packets, aka 'Windows TCP/IP Remote Code Execution Vulnerability'.

- **Analyse**
  - https://www.anquanke.com/post/id/220862
  - https://bestwing.me/CVE-2020-15898-analysis.html
  - http://www.v4ler1an.com/2020/10/cve-2020-16898/
  - https://cert.360.cn/report/detail?id=771d8ddc2d703071d5761b6a2b139793
- **PoC**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2020-16898](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2020-16898) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/advanced-threat-research/CVE-2020-16898](https://github.com/advanced-threat-research/CVE-2020-16898) :  ![starts](https://img.shields.io/github/stars/advanced-threat-research/CVE-2020-16898.svg) ![forks](https://img.shields.io/github/forks/advanced-threat-research/CVE-2020-16898.svg)
  - [https://github.com/0xeb-bp/cve-2020-16898](https://github.com/0xeb-bp/cve-2020-16898) :  ![starts](https://img.shields.io/github/stars/0xeb-bp/cve-2020-16898.svg) ![forks](https://img.shields.io/github/forks/0xeb-bp/cve-2020-16898.svg)
  - [https://github.com/ZephrFish/CVE-2020-16898](https://github.com/ZephrFish/CVE-2020-16898) :  ![starts](https://img.shields.io/github/stars/ZephrFish/CVE-2020-16898.svg) ![forks](https://img.shields.io/github/forks/ZephrFish/CVE-2020-16898.svg)
  - [https://github.com/momika233/CVE-2020-16898-exp](https://github.com/momika233/CVE-2020-16898-exp) :  ![starts](https://img.shields.io/github/stars/momika233/CVE-2020-16898-exp.svg) ![forks](https://img.shields.io/github/forks/momika233/CVE-2020-16898-exp.svg)
  - [https://github.com/corelight/CVE-2020-16898](https://github.com/corelight/CVE-2020-16898) :  ![starts](https://img.shields.io/github/stars/corelight/CVE-2020-16898.svg) ![forks](https://img.shields.io/github/forks/corelight/CVE-2020-16898.svg)
  - [https://github.com/komomon/CVE-2020-16898--EXP-POC](https://github.com/komomon/CVE-2020-16898--EXP-POC) :  ![starts](https://img.shields.io/github/stars/komomon/CVE-2020-16898--EXP-POC.svg) ![forks](https://img.shields.io/github/forks/komomon/CVE-2020-16898--EXP-POC.svg)
  - [https://github.com/jiansiting/cve-2020-16898](https://github.com/jiansiting/cve-2020-16898) :  ![starts](https://img.shields.io/github/stars/jiansiting/cve-2020-16898.svg) ![forks](https://img.shields.io/github/forks/jiansiting/cve-2020-16898.svg)
  - [https://github.com/komomon/CVE-2020-16898-EXP-POC](https://github.com/komomon/CVE-2020-16898-EXP-POC) :  ![starts](https://img.shields.io/github/stars/komomon/CVE-2020-16898-EXP-POC.svg) ![forks](https://img.shields.io/github/forks/komomon/CVE-2020-16898-EXP-POC.svg)
  - [https://github.com/Maliek/CVE-2020-16898_Check](https://github.com/Maliek/CVE-2020-16898_Check) :  ![starts](https://img.shields.io/github/stars/Maliek/CVE-2020-16898_Check.svg) ![forks](https://img.shields.io/github/forks/Maliek/CVE-2020-16898_Check.svg)
  - [https://github.com/initconf/CVE-2020-16898-Bad-Neighbor](https://github.com/initconf/CVE-2020-16898-Bad-Neighbor) :  ![starts](https://img.shields.io/github/stars/initconf/CVE-2020-16898-Bad-Neighbor.svg) ![forks](https://img.shields.io/github/forks/initconf/CVE-2020-16898-Bad-Neighbor.svg)
  - [https://github.com/CPO-EH/CVE-2020-16898_Checker](https://github.com/CPO-EH/CVE-2020-16898_Checker) :  ![starts](https://img.shields.io/github/stars/CPO-EH/CVE-2020-16898_Checker.svg) ![forks](https://img.shields.io/github/forks/CPO-EH/CVE-2020-16898_Checker.svg)
  - [https://github.com/esnet-security/cve-2020-16898](https://github.com/esnet-security/cve-2020-16898) :  ![starts](https://img.shields.io/github/stars/esnet-security/cve-2020-16898.svg) ![forks](https://img.shields.io/github/forks/esnet-security/cve-2020-16898.svg)
  - [https://github.com/Q1984/CVE-2020-16898](https://github.com/Q1984/CVE-2020-16898) :  ![starts](https://img.shields.io/github/stars/Q1984/CVE-2020-16898.svg) ![forks](https://img.shields.io/github/forks/Q1984/CVE-2020-16898.svg)

## CVE-2020-1362

> An elevation of privilege vulnerability exists in the way that the Windows WalletService handles objects in memory, aka 'Windows WalletService Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-1344, CVE-2020-1369.

- **Analyse**
  - https://paper.seebug.org/1276/
  - https://www.023niu.com/show-62-811-1.html
  - https://blog.csdn.net/gental_z/article/details/107937110
- **Exp**
  - [https://github.com/Q4n/CVE-2020-1362](https://github.com/Q4n/CVE-2020-1362) :  ![starts](https://img.shields.io/github/stars/Q4n/CVE-2020-1362.svg) ![forks](https://img.shields.io/github/forks/Q4n/CVE-2020-1362.svg)
  - [https://github.com/Al1ex/WindowsElevation](https://github.com/Al1ex/WindowsElevation) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)

## CVE-2020-1350

> A remote code execution vulnerability exists in Windows Domain Name System servers when they fail to properly handle requests, aka 'Windows DNS Server Remote Code Execution Vulnerability'.

- **Analyse**
  - https://saturn35.com/2020/07/24/20200724-1/
  - https://www.anquanke.com/post/id/210812
  - https://cert.360.cn/report/detail?id=5b7082dae4756f361d43a5efde233ed
- **PoC**
  - [https://github.com/ZephrFish/CVE-2020-1350](https://github.com/ZephrFish/CVE-2020-1350) :  ![starts](https://img.shields.io/github/stars/ZephrFish/CVE-2020-1350.svg) ![forks](https://img.shields.io/github/forks/ZephrFish/CVE-2020-1350.svg)
  - [https://github.com/maxpl0it/CVE-2020-1350-DoS](https://github.com/maxpl0it/CVE-2020-1350-DoS) :  ![starts](https://img.shields.io/github/stars/maxpl0it/CVE-2020-1350-DoS.svg) ![forks](https://img.shields.io/github/forks/maxpl0it/CVE-2020-1350-DoS.svg)
  - [https://github.com/tinkersec/cve-2020-1350](https://github.com/tinkersec/cve-2020-1350) :  ![starts](https://img.shields.io/github/stars/tinkersec/cve-2020-1350.svg) ![forks](https://img.shields.io/github/forks/tinkersec/cve-2020-1350.svg)
  - [https://github.com/psc4re/NSE-scripts](https://github.com/psc4re/NSE-scripts) :  ![starts](https://img.shields.io/github/stars/psc4re/NSE-scripts.svg) ![forks](https://img.shields.io/github/forks/psc4re/NSE-scripts.svg)
  - [https://github.com/captainGeech42/CVE-2020-1350](https://github.com/captainGeech42/CVE-2020-1350) :  ![starts](https://img.shields.io/github/stars/captainGeech42/CVE-2020-1350.svg) ![forks](https://img.shields.io/github/forks/captainGeech42/CVE-2020-1350.svg)
  - [https://github.com/T13nn3s/CVE-2020-1350](https://github.com/T13nn3s/CVE-2020-1350) :  ![starts](https://img.shields.io/github/stars/T13nn3s/CVE-2020-1350.svg) ![forks](https://img.shields.io/github/forks/T13nn3s/CVE-2020-1350.svg)
  - [https://github.com/corelight/SIGRed](https://github.com/corelight/SIGRed) :  ![starts](https://img.shields.io/github/stars/corelight/SIGRed.svg) ![forks](https://img.shields.io/github/forks/corelight/SIGRed.svg)
  - [https://github.com/connormcgarr/CVE-2020-1350](https://github.com/connormcgarr/CVE-2020-1350) :  ![starts](https://img.shields.io/github/stars/connormcgarr/CVE-2020-1350.svg) ![forks](https://img.shields.io/github/forks/connormcgarr/CVE-2020-1350.svg)
  - [https://github.com/zoomerxsec/Fake_CVE-2020-1350](https://github.com/zoomerxsec/Fake_CVE-2020-1350) :  ![starts](https://img.shields.io/github/stars/zoomerxsec/Fake_CVE-2020-1350.svg) ![forks](https://img.shields.io/github/forks/zoomerxsec/Fake_CVE-2020-1350.svg)
  - [https://github.com/graph-inc/CVE-2020-1350](https://github.com/graph-inc/CVE-2020-1350) :  ![starts](https://img.shields.io/github/stars/graph-inc/CVE-2020-1350.svg) ![forks](https://img.shields.io/github/forks/graph-inc/CVE-2020-1350.svg)
  - [https://github.com/Plazmaz/CVE-2020-1350-poc](https://github.com/Plazmaz/CVE-2020-1350-poc) :  ![starts](https://img.shields.io/github/stars/Plazmaz/CVE-2020-1350-poc.svg) ![forks](https://img.shields.io/github/forks/Plazmaz/CVE-2020-1350-poc.svg)
  - [https://github.com/simeononsecurity/CVE-2020-1350-Fix](https://github.com/simeononsecurity/CVE-2020-1350-Fix) :  ![starts](https://img.shields.io/github/stars/simeononsecurity/CVE-2020-1350-Fix.svg) ![forks](https://img.shields.io/github/forks/simeononsecurity/CVE-2020-1350-Fix.svg)
  - [https://github.com/CVEmaster/CVE-2020-1350](https://github.com/CVEmaster/CVE-2020-1350) :  ![starts](https://img.shields.io/github/stars/CVEmaster/CVE-2020-1350.svg) ![forks](https://img.shields.io/github/forks/CVEmaster/CVE-2020-1350.svg)
  - [https://github.com/gdwnet/cve-2020-1350](https://github.com/gdwnet/cve-2020-1350) :  ![starts](https://img.shields.io/github/stars/gdwnet/cve-2020-1350.svg) ![forks](https://img.shields.io/github/forks/gdwnet/cve-2020-1350.svg)
  - [https://github.com/Secuora-Org/CVE-2020-1350-checker.ps1](https://github.com/Secuora-Org/CVE-2020-1350-checker.ps1) :  ![starts](https://img.shields.io/github/stars/Secuora-Org/CVE-2020-1350-checker.ps1.svg) ![forks](https://img.shields.io/github/forks/Secuora-Org/CVE-2020-1350-checker.ps1.svg)
  - [https://github.com/jmaddington/dRMM-CVE-2020-1350-response](https://github.com/jmaddington/dRMM-CVE-2020-1350-response) :  ![starts](https://img.shields.io/github/stars/jmaddington/dRMM-CVE-2020-1350-response.svg) ![forks](https://img.shields.io/github/forks/jmaddington/dRMM-CVE-2020-1350-response.svg)

## CVE-2020-1337

> An elevation of privilege vulnerability exists when the Windows Print Spooler service improperly allows arbitrary writing to the file system, aka 'Windows Print Spooler Elevation of Privilege Vulnerability'.

- **Analyse**
  - https://bbs.pediy.com/thread-261557.htm
- **Exp**
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-1337](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-1337) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)
  - [https://github.com/sailay1996/cve-2020-1337-poc](https://github.com/sailay1996/cve-2020-1337-poc) :  ![starts](https://img.shields.io/github/stars/sailay1996/cve-2020-1337-poc.svg) ![forks](https://img.shields.io/github/forks/sailay1996/cve-2020-1337-poc.svg)
  - [https://github.com/math1as/CVE-2020-1337-exploit](https://github.com/math1as/CVE-2020-1337-exploit) :  ![starts](https://img.shields.io/github/stars/math1as/CVE-2020-1337-exploit.svg) ![forks](https://img.shields.io/github/forks/math1as/CVE-2020-1337-exploit.svg)
  - [https://github.com/neofito/CVE-2020-1337](https://github.com/neofito/CVE-2020-1337) :  ![starts](https://img.shields.io/github/stars/neofito/CVE-2020-1337.svg) ![forks](https://img.shields.io/github/forks/neofito/CVE-2020-1337.svg)
  - [https://github.com/password520/cve-2020-1337-poc](https://github.com/password520/cve-2020-1337-poc) :  ![starts](https://img.shields.io/github/stars/password520/cve-2020-1337-poc.svg) ![forks](https://img.shields.io/github/forks/password520/cve-2020-1337-poc.svg)

## CVE-2020-1313

> An elevation of privilege vulnerability exists when the Windows Update Orchestrator Service improperly handles file operations, aka 'Windows Update Orchestrator Service Elevation of Privilege Vulnerability'.

- **Analyse**
  - https://cloud.tencent.com/developer/article/1683124
- **PoC**
  - [https://github.com/irsl/CVE-2020-1313](https://github.com/irsl/CVE-2020-1313) :  ![starts](https://img.shields.io/github/stars/irsl/CVE-2020-1313.svg) ![forks](https://img.shields.io/github/forks/irsl/CVE-2020-1313.svg)

## CVE-2020-1301 

> A remote code execution vulnerability exists in the way that the Microsoft Server Message Block 1.0 (SMBv1) server handles certain requests, aka 'Windows SMB Remote Code Execution Vulnerability'.

- **Analyse**
  - https://bbs.pediy.com/thread-260339.htm
  - https://s.tencent.com/research/bsafe/1007.html
  - https://airbus-cyber-security.com/diving-into-the-smblost-vulnerability-cve-2020-1301/
- **PoC**
  - [https://github.com/shubham0d/CVE-2020-1301](https://github.com/shubham0d/CVE-2020-1301) :  ![starts](https://img.shields.io/github/stars/shubham0d/CVE-2020-1301.svg) ![forks](https://img.shields.io/github/forks/shubham0d/CVE-2020-1301.svg)

## CVE-2020-1066

> An elevation of privilege vulnerability exists in .NET Framework which could allow an attacker to elevate their privilege level.To exploit the vulnerability, an attacker would first have to access the local machine, and then run a malicious program.The update addresses the vulnerability by correcting how .NET Framework activates COM objects., aka '.NET Framework Elevation of Privilege Vulnerability'.

- **Analyse**
  - https://www.anquanke.com/post/id/205105
  - https://blog.csdn.net/qq_37353105/article/details/114481214
- **Exp**
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-1066](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-1066) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)
  - [https://github.com/cbwang505/CVE-2020-1066-EXP](https://github.com/cbwang505/CVE-2020-1066-EXP) :  ![starts](https://img.shields.io/github/stars/cbwang505/CVE-2020-1066-EXP.svg) ![forks](https://img.shields.io/github/forks/cbwang505/CVE-2020-1066-EXP.svg)
  - [https://github.com/xyddnljydd/cve-2020-1066](https://github.com/xyddnljydd/cve-2020-1066) :  ![starts](https://img.shields.io/github/stars/xyddnljydd/cve-2020-1066.svg) ![forks](https://img.shields.io/github/forks/xyddnljydd/cve-2020-1066.svg)

## CVE-2020-1054

> An elevation of privilege vulnerability exists in Windows when the Windows kernel-mode driver fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-1143.

- **Analyse**
  - https://www.anquanke.com/post/id/209329
  - https://mp.weixin.qq.com/s?__biz=MjM5NTc2MDYxMw==&mid=2458334073&idx=1&sn=d8ffd415a148aac507b0173eb906badb&chksm=b18003f386f78ae5c76971e993f42409a0c22fd52468949bf08436469e7456f4cc836ab9ba71&scene=21
  - https://bbs.pediy.com/thread-260884.htm
- **Exp**
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-1054](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-1054) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)
  - [https://github.com/0xeb-bp/cve-2020-1054](https://github.com/0xeb-bp/cve-2020-1054) :  ![starts](https://img.shields.io/github/stars/0xeb-bp/cve-2020-1054.svg) ![forks](https://img.shields.io/github/forks/0xeb-bp/cve-2020-1054.svg)
  - [https://github.com/KaLendsi/CVE-2020-1054](https://github.com/KaLendsi/CVE-2020-1054) :  ![starts](https://img.shields.io/github/stars/KaLendsi/CVE-2020-1054.svg) ![forks](https://img.shields.io/github/forks/KaLendsi/CVE-2020-1054.svg)
  - [https://github.com/Iamgublin/CVE-2020-1054](https://github.com/Iamgublin/CVE-2020-1054) :  ![starts](https://img.shields.io/github/stars/Iamgublin/CVE-2020-1054.svg) ![forks](https://img.shields.io/github/forks/Iamgublin/CVE-2020-1054.svg)
  - [https://github.com/Graham382/CVE-2020-1054](https://github.com/Graham382/CVE-2020-1054) :  ![starts](https://img.shields.io/github/stars/Graham382/CVE-2020-1054.svg) ![forks](https://img.shields.io/github/forks/Graham382/CVE-2020-1054.svg)

## CVE-2020-1048

> An elevation of privilege vulnerability exists when the Windows Print Spooler service improperly allows arbitrary writing to the file system, aka 'Windows Print Spooler Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-1070.

- **Analyse**
  - https://zhuanlan.kanxue.com/article-11214.htm
  - https://www.anquanke.com/post/id/222730
  - https://bbs.pediy.com/thread-261557.htm
- **Exp**
  - [https://github.com/neofito/CVE-2020-1337](https://github.com/neofito/CVE-2020-1337) :  ![starts](https://img.shields.io/github/stars/neofito/CVE-2020-1337.svg) ![forks](https://img.shields.io/github/forks/neofito/CVE-2020-1337.svg)
  - [https://github.com/shubham0d/CVE-2020-1048](https://github.com/shubham0d/CVE-2020-1048) :  ![starts](https://img.shields.io/github/stars/shubham0d/CVE-2020-1048.svg) ![forks](https://img.shields.io/github/forks/shubham0d/CVE-2020-1048.svg)
  - [https://github.com/Ken-Abruzzi/CVE-2020-1048](https://github.com/Ken-Abruzzi/CVE-2020-1048) :  ![starts](https://img.shields.io/github/stars/Ken-Abruzzi/CVE-2020-1048.svg) ![forks](https://img.shields.io/github/forks/Ken-Abruzzi/CVE-2020-1048.svg)

## CVE-2020-1034

> An elevation of privilege vulnerability exists in the way that the Windows Kernel handles objects in memory, aka 'Windows Kernel Elevation of Privilege Vulnerability'.

- **Analyse**
  - https://windows-internals.com/exploiting-a-simple-vulnerability-in-35-easy-steps-or-less
  - https://windows-internals.com/exploiting-a-simple-vulnerability-part-1-5-the-info-leak/
  - https://windows-internals.com/exploiting-a-simple-vulnerability-part-2-what-if-we-made-exploitation-harder/
  - https://cloud.tencent.com/developer/article/1750818
  - https://www.4hou.com/posts/Np4N
  - https://www.anquanke.com/post/id/223724
- **PoC**
  - [https://github.com/yardenshafir/CVE-2020-1034](https://github.com/yardenshafir/CVE-2020-1034) :  ![starts](https://img.shields.io/github/stars/yardenshafir/CVE-2020-1034.svg) ![forks](https://img.shields.io/github/forks/yardenshafir/CVE-2020-1034.svg)

## CVE-2020-1015

> An elevation of privilege vulnerability exists in the way that the User-Mode Power Service (UMPS) handles objects in memory, aka 'Windows Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-0934, CVE-2020-0983, CVE-2020-1009, CVE-2020-1011.

- **Analyse**
  - https://0xeb-bp.com/blog/2020/05/12/cve-2020-1015-analysis.html
  - https://www.anquanke.com/post/id/217526
- **PoC**
  - [https://github.com/0xeb-bp/cve-2020-1015](https://github.com/0xeb-bp/cve-2020-1015) :  ![starts](https://img.shields.io/github/stars/0xeb-bp/cve-2020-1015.svg) ![forks](https://img.shields.io/github/forks/0xeb-bp/cve-2020-1015.svg)

## CVE-2020-0883

> A remote code execution vulnerability exists in the way that the Windows Graphics Device Interface (GDI) handles objects in the memory, aka 'GDI+ Remote Code Execution Vulnerability'. This CVE ID is unique from CVE-2020-0881.

- **Exp**
  - [https://github.com/syadg123/CVE-2020-0883](https://github.com/syadg123/CVE-2020-0883) :  ![starts](https://img.shields.io/github/stars/syadg123/CVE-2020-0883.svg) ![forks](https://img.shields.io/github/forks/syadg123/CVE-2020-0883.svg)
  - [https://github.com/thelostworldFree/CVE-2020-0883](https://github.com/thelostworldFree/CVE-2020-0883) :  ![starts](https://img.shields.io/github/stars/thelostworldFree/CVE-2020-0883.svg) ![forks](https://img.shields.io/github/forks/thelostworldFree/CVE-2020-0883.svg)

## CVE-2020-0814

> An elevation of privilege vulnerability exists in Windows Installer because of the way Windows Installer handles certain filesystem operations.To exploit the vulnerability, an attacker would require unprivileged execution on the victim system, aka 'Windows Installer Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-0779, CVE-2020-0798, CVE-2020-0842, CVE-2020-0843.

- **Exp**
  - [https://github.com/klinix5/CVE-2020-0814](https://github.com/klinix5/CVE-2020-0814) :  ![starts](https://img.shields.io/github/stars/klinix5/CVE-2020-0814.svg) ![forks](https://img.shields.io/github/forks/klinix5/CVE-2020-0814.svg)

## CVE-2020-0796

> A remote code execution vulnerability exists in the way that the Microsoft Server Message Block 3.1.1 (SMBv3) protocol handles certain requests, aka 'Windows SMBv3 Client/Server Remote Code Execution Vulnerability'.

- **Analyse**
  - https://paper.seebug.org/1168/
  - https://www.freebuf.com/column/230770.html
  - https://jcxp.github.io/2020/03/31/CVE-2020-0796-SMB%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/
  - https://www.cnblogs.com/potatsoSec/p/12484973.html
  - https://blog.csdn.net/RatOnSea/article/details/106399450
  - https://blogs.360.cn/post/CVE-2020-0796.html
  - https://zhuanlan.zhihu.com/p/133460472
- **PoC**
  - [https://github.com/eerykitty/CVE-2020-0796-PoC](https://github.com/eerykitty/CVE-2020-0796-PoC) :  ![starts](https://img.shields.io/github/stars/eerykitty/CVE-2020-0796-PoC.svg) ![forks](https://img.shields.io/github/forks/eerykitty/CVE-2020-0796-PoC.svg)
  - [https://github.com/psc4re/NSE-scripts](https://github.com/psc4re/NSE-scripts) :  ![starts](https://img.shields.io/github/stars/psc4re/NSE-scripts.svg) ![forks](https://img.shields.io/github/forks/psc4re/NSE-scripts.svg)
  - [https://github.com/claroty/CVE2020-0796](https://github.com/claroty/CVE2020-0796) :  ![starts](https://img.shields.io/github/stars/claroty/CVE2020-0796.svg) ![forks](https://img.shields.io/github/forks/claroty/CVE2020-0796.svg)
  - [https://github.com/ioncodes/SMBGhost](https://github.com/ioncodes/SMBGhost) :  ![starts](https://img.shields.io/github/stars/ioncodes/SMBGhost.svg) ![forks](https://img.shields.io/github/forks/ioncodes/SMBGhost.svg)
  - [https://github.com/jiansiting/CVE-2020-0796](https://github.com/jiansiting/CVE-2020-0796) :  ![starts](https://img.shields.io/github/stars/jiansiting/CVE-2020-0796.svg) ![forks](https://img.shields.io/github/forks/jiansiting/CVE-2020-0796.svg)
  - [https://github.com/k8gege/PyLadon](https://github.com/k8gege/PyLadon) :  ![starts](https://img.shields.io/github/stars/k8gege/PyLadon.svg) ![forks](https://img.shields.io/github/forks/k8gege/PyLadon.svg)
  - [https://github.com/T13nn3s/CVE-2020-0796](https://github.com/T13nn3s/CVE-2020-0796) :  ![starts](https://img.shields.io/github/stars/T13nn3s/CVE-2020-0796.svg) ![forks](https://img.shields.io/github/forks/T13nn3s/CVE-2020-0796.svg)
  - [https://github.com/ZecOps/SMBGhost-SMBleed-scanner](https://github.com/ZecOps/SMBGhost-SMBleed-scanner) :  ![starts](https://img.shields.io/github/stars/ZecOps/SMBGhost-SMBleed-scanner.svg) ![forks](https://img.shields.io/github/forks/ZecOps/SMBGhost-SMBleed-scanner.svg)
  - [https://github.com/maxpl0it/Unauthenticated-CVE-2020-0796-PoC](https://github.com/maxpl0it/Unauthenticated-CVE-2020-0796-PoC) :  ![starts](https://img.shields.io/github/stars/maxpl0it/Unauthenticated-CVE-2020-0796-PoC.svg) ![forks](https://img.shields.io/github/forks/maxpl0it/Unauthenticated-CVE-2020-0796-PoC.svg)
  - [https://github.com/Aekras1a/CVE-2020-0796-PoC](https://github.com/Aekras1a/CVE-2020-0796-PoC) :  ![starts](https://img.shields.io/github/stars/Aekras1a/CVE-2020-0796-PoC.svg) ![forks](https://img.shields.io/github/forks/Aekras1a/CVE-2020-0796-PoC.svg)
  - [https://github.com/GuoKerS/aioScan_CVE-2020-0796](https://github.com/GuoKerS/aioScan_CVE-2020-0796) :  ![starts](https://img.shields.io/github/stars/GuoKerS/aioScan_CVE-2020-0796.svg) ![forks](https://img.shields.io/github/forks/GuoKerS/aioScan_CVE-2020-0796.svg)
  - [https://github.com/joaozietolie/CVE-2020-0796-Checker](https://github.com/joaozietolie/CVE-2020-0796-Checker) :  ![starts](https://img.shields.io/github/stars/joaozietolie/CVE-2020-0796-Checker.svg) ![forks](https://img.shields.io/github/forks/joaozietolie/CVE-2020-0796-Checker.svg)
  - [https://github.com/gabimarti/SMBScanner](https://github.com/gabimarti/SMBScanner) :  ![starts](https://img.shields.io/github/stars/gabimarti/SMBScanner.svg) ![forks](https://img.shields.io/github/forks/gabimarti/SMBScanner.svg)
  - [https://github.com/w1ld3r/SMBGhost_Scanner](https://github.com/w1ld3r/SMBGhost_Scanner) :  ![starts](https://img.shields.io/github/stars/w1ld3r/SMBGhost_Scanner.svg) ![forks](https://img.shields.io/github/forks/w1ld3r/SMBGhost_Scanner.svg)
  - [https://github.com/dickens88/cve-2020-0796-scanner](https://github.com/dickens88/cve-2020-0796-scanner) :  ![starts](https://img.shields.io/github/stars/dickens88/cve-2020-0796-scanner.svg) ![forks](https://img.shields.io/github/forks/dickens88/cve-2020-0796-scanner.svg)
  - [https://github.com/jiansiting/CVE-2020-0796-Scanner](https://github.com/jiansiting/CVE-2020-0796-Scanner) :  ![starts](https://img.shields.io/github/stars/jiansiting/CVE-2020-0796-Scanner.svg) ![forks](https://img.shields.io/github/forks/jiansiting/CVE-2020-0796-Scanner.svg)
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2020-0796](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2020-0796) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/danigargu/CVE-2020-0796](https://github.com/danigargu/CVE-2020-0796) :  ![starts](https://img.shields.io/github/stars/danigargu/CVE-2020-0796.svg) ![forks](https://img.shields.io/github/forks/danigargu/CVE-2020-0796.svg)
  - [https://github.com/ollypwn/SMBGhost](https://github.com/ollypwn/SMBGhost) :  ![starts](https://img.shields.io/github/stars/ollypwn/SMBGhost.svg) ![forks](https://img.shields.io/github/forks/ollypwn/SMBGhost.svg)
  - [https://github.com/ZecOps/CVE-2020-0796-RCE-POC](https://github.com/ZecOps/CVE-2020-0796-RCE-POC) :  ![starts](https://img.shields.io/github/stars/ZecOps/CVE-2020-0796-RCE-POC.svg) ![forks](https://img.shields.io/github/forks/ZecOps/CVE-2020-0796-RCE-POC.svg)
  - [https://github.com/ZecOps/CVE-2020-0796-LPE-POC](https://github.com/ZecOps/CVE-2020-0796-LPE-POC) :  ![starts](https://img.shields.io/github/stars/ZecOps/CVE-2020-0796-LPE-POC.svg) ![forks](https://img.shields.io/github/forks/ZecOps/CVE-2020-0796-LPE-POC.svg)
  - [https://github.com/Barriuso/SMBGhost_AutomateExploitation](https://github.com/Barriuso/SMBGhost_AutomateExploitation) :  ![starts](https://img.shields.io/github/stars/Barriuso/SMBGhost_AutomateExploitation.svg) ![forks](https://img.shields.io/github/forks/Barriuso/SMBGhost_AutomateExploitation.svg)
  - [https://github.com/Rvn0xsy/CVE_2020_0796_CNA](https://github.com/Rvn0xsy/CVE_2020_0796_CNA) :  ![starts](https://img.shields.io/github/stars/Rvn0xsy/CVE_2020_0796_CNA.svg) ![forks](https://img.shields.io/github/forks/Rvn0xsy/CVE_2020_0796_CNA.svg)
  - [https://github.com/rsmudge/CVE-2020-0796-BOF](https://github.com/rsmudge/CVE-2020-0796-BOF) :  ![starts](https://img.shields.io/github/stars/rsmudge/CVE-2020-0796-BOF.svg) ![forks](https://img.shields.io/github/forks/rsmudge/CVE-2020-0796-BOF.svg)
  - [https://github.com/eastmountyxz/CVE-2020-0796-SMB](https://github.com/eastmountyxz/CVE-2020-0796-SMB) :  ![starts](https://img.shields.io/github/stars/eastmountyxz/CVE-2020-0796-SMB.svg) ![forks](https://img.shields.io/github/forks/eastmountyxz/CVE-2020-0796-SMB.svg)
  - [https://github.com/Almorabea/SMBGhost-LPE-Metasploit-Module](https://github.com/Almorabea/SMBGhost-LPE-Metasploit-Module) :  ![starts](https://img.shields.io/github/stars/Almorabea/SMBGhost-LPE-Metasploit-Module.svg) ![forks](https://img.shields.io/github/forks/Almorabea/SMBGhost-LPE-Metasploit-Module.svg)
  - [https://github.com/f1tz/CVE-2020-0796-LPE-EXP](https://github.com/f1tz/CVE-2020-0796-LPE-EXP) :  ![starts](https://img.shields.io/github/stars/f1tz/CVE-2020-0796-LPE-EXP.svg) ![forks](https://img.shields.io/github/forks/f1tz/CVE-2020-0796-LPE-EXP.svg)
  - [https://github.com/thelostworldFree/CVE-2020-0796](https://github.com/thelostworldFree/CVE-2020-0796) :  ![starts](https://img.shields.io/github/stars/thelostworldFree/CVE-2020-0796.svg) ![forks](https://img.shields.io/github/forks/thelostworldFree/CVE-2020-0796.svg)

## CVE-2020-0787

> An elevation of privilege vulnerability exists when the Windows Background Intelligent Transfer Service (BITS) improperly handles symbolic links, aka 'Windows Background Intelligent Transfer Service Elevation of Privilege Vulnerability'.

- **Analyse**
  - https://f5.pm/go-28382.html
  - https://itm4n.github.io/cve-2020-0787-windows-bits-eop/
  - https://xz.aliyun.com/t/7935
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2020-0787](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2020-0787) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/cbwang505/CVE-2020-0787-EXP-ALL-WINDOWS-VERSION](https://github.com/cbwang505/CVE-2020-0787-EXP-ALL-WINDOWS-VERSION) :  ![starts](https://img.shields.io/github/stars/cbwang505/CVE-2020-0787-EXP-ALL-WINDOWS-VERSION.svg) ![forks](https://img.shields.io/github/forks/cbwang505/CVE-2020-0787-EXP-ALL-WINDOWS-VERSION.svg)
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-0787](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-0787) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)

## CVE-2020-0754

> An elevation of privilege vulnerability exists in Windows Error Reporting (WER) when WER handles and executes files, aka 'Windows Error Reporting Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-0753.

- **Exp**
  - [https://github.com/afang5472/CVE-2020-0753-and-CVE-2020-0754](https://github.com/afang5472/CVE-2020-0753-and-CVE-2020-0754) :  ![starts](https://img.shields.io/github/stars/afang5472/CVE-2020-0753-and-CVE-2020-0754.svg) ![forks](https://img.shields.io/github/forks/afang5472/CVE-2020-0753-and-CVE-2020-0754.svg)

## CVE-2020-0753

> An elevation of privilege vulnerability exists in Windows Error Reporting (WER) when WER handles and executes files, aka 'Windows Error Reporting Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-0754.

- **Exp**
  - [https://github.com/afang5472/CVE-2020-0753-and-CVE-2020-0754](https://github.com/afang5472/CVE-2020-0753-and-CVE-2020-0754) :  ![starts](https://img.shields.io/github/stars/afang5472/CVE-2020-0753-and-CVE-2020-0754.svg) ![forks](https://img.shields.io/github/forks/afang5472/CVE-2020-0753-and-CVE-2020-0754.svg)

## CVE-2020-0683

> An elevation of privilege vulnerability exists in the Windows Installer when MSI packages process symbolic links, aka 'Windows Installer Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-0686.

- **Exp**
  - [https://github.com/padovah4ck/CVE-2020-0683](https://github.com/padovah4ck/CVE-2020-0683) :  ![starts](https://img.shields.io/github/stars/padovah4ck/CVE-2020-0683.svg) ![forks](https://img.shields.io/github/forks/padovah4ck/CVE-2020-0683.svg)
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-0683](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-0683) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)

## CVE-2020-0668

> An elevation of privilege vulnerability exists in the way that the Windows Kernel handles objects in memory, aka 'Windows Kernel Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-0669, CVE-2020-0670, CVE-2020-0671, CVE-2020-0672.

- **Analyse**
  - https://www.anquanke.com/post/id/199011
  - https://www.freebuf.com/vuls/227557.html
  - https://itm4n.github.io/cve-2020-0668-windows-service-tracing-eop/
- **PoC**
  - [https://github.com/itm4n/SysTracingPoc](https://github.com/itm4n/SysTracingPoc) :  ![starts](https://img.shields.io/github/stars/itm4n/SysTracingPoc.svg) ![forks](https://img.shields.io/github/forks/itm4n/SysTracingPoc.svg)
- **Exp**
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-0668](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2020-0668) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)
  - [https://github.com/RedCursorSecurityConsulting/CVE-2020-0668](https://github.com/RedCursorSecurityConsulting/CVE-2020-0668) :  ![starts](https://img.shields.io/github/stars/RedCursorSecurityConsulting/CVE-2020-0668.svg) ![forks](https://img.shields.io/github/forks/RedCursorSecurityConsulting/CVE-2020-0668.svg)
  - [https://github.com/Nan3r/CVE-2020-0668](https://github.com/Nan3r/CVE-2020-0668) :  ![starts](https://img.shields.io/github/stars/Nan3r/CVE-2020-0668.svg) ![forks](https://img.shields.io/github/forks/Nan3r/CVE-2020-0668.svg)


## CVE-2020-0624 

> An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-0642.

- **Analyse**
  - https://bbs.pediy.com/thread-260605.htm
  - https://www.sec-wiki.com/news/28042
  - https://mp.weixin.qq.com/s/GHiTqWlxisyVWxVHcACpvg
- **PoC**
  - [https://github.com/james0x40/CVE-2020-0624](https://github.com/james0x40/CVE-2020-0624) :  ![starts](https://img.shields.io/github/stars/james0x40/CVE-2020-0624.svg) ![forks](https://img.shields.io/github/forks/james0x40/CVE-2020-0624.svg)

## CVE-2020-0610

> A remote code execution vulnerability exists in Windows Remote Desktop Gateway (RD Gateway) when an unauthenticated attacker connects to the target system using RDP and sends specially crafted requests, aka 'Windows Remote Desktop Gateway (RD Gateway) Remote Code Execution Vulnerability'. This CVE ID is unique from CVE-2020-0609.

- **Analyse**
  - https://www.4hou.com/posts/mMpn
  - https://www.023niu.com/show-62-552-1.html
- **PoC**
  - [https://github.com/ollypwn/BlueGate](https://github.com/ollypwn/BlueGate) :  ![starts](https://img.shields.io/github/stars/ollypwn/BlueGate.svg) ![forks](https://img.shields.io/github/forks/ollypwn/BlueGate.svg)
  - [https://github.com/ioncodes/BlueGate](https://github.com/ioncodes/BlueGate) :  ![starts](https://img.shields.io/github/stars/ioncodes/BlueGate.svg) ![forks](https://img.shields.io/github/forks/ioncodes/BlueGate.svg)
  - [https://github.com/MalwareTech/RDGScanner](https://github.com/MalwareTech/RDGScanner) :  ![starts](https://img.shields.io/github/stars/MalwareTech/RDGScanner.svg) ![forks](https://img.shields.io/github/forks/MalwareTech/RDGScanner.svg)
  - [https://github.com/2d4d/rdg_scanner_cve-2020-0609](https://github.com/2d4d/rdg_scanner_cve-2020-0609) :  ![starts](https://img.shields.io/github/stars/2d4d/rdg_scanner_cve-2020-0609.svg) ![forks](https://img.shields.io/github/forks/2d4d/rdg_scanner_cve-2020-0609.svg)

## CVE-2020-0609

> A remote code execution vulnerability exists in Windows Remote Desktop Gateway (RD Gateway) when an unauthenticated attacker connects to the target system using RDP and sends specially crafted requests, aka 'Windows Remote Desktop Gateway (RD Gateway) Remote Code Execution Vulnerability'. This CVE ID is unique from CVE-2020-0610.

- **Analyse**
  - https://www.4hou.com/posts/mMpn
  - https://www.023niu.com/show-62-552-1.html
- **PoC**
  - [https://github.com/ollypwn/BlueGate](https://github.com/ollypwn/BlueGate) :  ![starts](https://img.shields.io/github/stars/ollypwn/BlueGate.svg) ![forks](https://img.shields.io/github/forks/ollypwn/BlueGate.svg)
  - [https://github.com/ioncodes/BlueGate](https://github.com/ioncodes/BlueGate) :  ![starts](https://img.shields.io/github/stars/ioncodes/BlueGate.svg) ![forks](https://img.shields.io/github/forks/ioncodes/BlueGate.svg)
  - [https://github.com/MalwareTech/RDGScanner](https://github.com/MalwareTech/RDGScanner) :  ![starts](https://img.shields.io/github/stars/MalwareTech/RDGScanner.svg) ![forks](https://img.shields.io/github/forks/MalwareTech/RDGScanner.svg)
  - [https://github.com/2d4d/rdg_scanner_cve-2020-0609](https://github.com/2d4d/rdg_scanner_cve-2020-0609) :  ![starts](https://img.shields.io/github/stars/2d4d/rdg_scanner_cve-2020-0609.svg) ![forks](https://img.shields.io/github/forks/2d4d/rdg_scanner_cve-2020-0609.svg)
  - [https://github.com/Archi73ct/CVE-2020-0609](https://github.com/Archi73ct/CVE-2020-0609) :  ![starts](https://img.shields.io/github/stars/Archi73ct/CVE-2020-0609.svg) ![forks](https://img.shields.io/github/forks/Archi73ct/CVE-2020-0609.svg)

# 2019

## CVE-2019-1477

> An elevation of privilege vulnerability exists when the Windows Printer Service improperly validates file paths while loading printer drivers, aka 'Windows Printer Service Elevation of Privilege Vulnerability'.

- **PoC**
  - - [https://github.com/2yong1/CVE-2019-1477](https://github.com/2yong1/CVE-2019-1477) :  ![starts](https://img.shields.io/github/stars/2yong1/CVE-2019-1477.svg) ![forks](https://img.shields.io/github/forks/2yong1/CVE-2019-1477.svg)

## CVE-2019-1476

> An elevation of privilege vulnerability exists when Windows AppX Deployment Service (AppXSVC) improperly handles hard links, aka 'Windows Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-1483.

- **Exp**
  - [https://github.com/sgabe/CVE-2019-1476](https://github.com/sgabe/CVE-2019-1476) :  ![starts](https://img.shields.io/github/stars/sgabe/CVE-2019-1476.svg) ![forks](https://img.shields.io/github/forks/sgabe/CVE-2019-1476.svg)

## CVE-2019-1458

> An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'.

- **Analyse**
  - github https://github.com/piotrflorczyk/cve-2019-1458_POC
  - https://bbs.pediy.com/thread-260268.htm
  - https://thunderjie.github.io/2020/03/21/CVE-2019-1458-%E4%BB%8E-%E6%BC%8F%E6%B4%9E%E6%8A%A5%E5%91%8A-%E5%88%B0POC%E7%9A%84%E7%BC%96%E5%86%99%E8%BF%87%E7%A8%8B/
- **PoC**
  - [https://github.com/piotrflorczyk/cve-2019-1458_POC](https://github.com/piotrflorczyk/cve-2019-1458_POC) :  ![starts](https://img.shields.io/github/stars/piotrflorczyk/cve-2019-1458_POC.svg) ![forks](https://img.shields.io/github/forks/piotrflorczyk/cve-2019-1458_POC.svg)
  - [https://github.com/DreamoneOnly/CVE-2019-1458-malware](https://github.com/DreamoneOnly/CVE-2019-1458-malware) :  ![starts](https://img.shields.io/github/stars/DreamoneOnly/CVE-2019-1458-malware.svg) ![forks](https://img.shields.io/github/forks/DreamoneOnly/CVE-2019-1458-malware.svg)
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2019-1458](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2019-1458) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/unamer/CVE-2019-1458](https://github.com/unamer/CVE-2019-1458) :  ![starts](https://img.shields.io/github/stars/unamer/CVE-2019-1458.svg) ![forks](https://img.shields.io/github/forks/unamer/CVE-2019-1458.svg)

## CVE-2019-1422

> An elevation of privilege vulnerability exists in the way that the iphlpsvc.dll handles file creation allowing for a file overwrite, aka 'Windows Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-1420, CVE-2019-1423.

- **Exp**
  - [https://github.com/ze0r/cve-2019-1422](https://github.com/ze0r/cve-2019-1422) :  ![starts](https://img.shields.io/github/stars/ze0r/cve-2019-1422.svg) ![forks](https://img.shields.io/github/forks/ze0r/cve-2019-1422.svg)

## CVE-2019-1405

> An elevation of privilege vulnerability exists when the Windows Universal Plug and Play (UPnP) service improperly allows COM object creation, aka 'Windows UPnP Service Elevation of Privilege Vulnerability'.

- **Analyse**
  - https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2019/november/cve-2019-1405-and-cve-2019-1322-elevation-to-system-via-the-upnp-device-host-service-and-the-update-orchestrator-service/
  - https://www.anquanke.com/post/id/193022
  - https://nosec.org/m/share/3177.html
- **Exp**
  - [https://github.com/apt69/COMahawk](https://github.com/apt69/COMahawk) :  ![starts](https://img.shields.io/github/stars/apt69/COMahawk.svg) ![forks](https://img.shields.io/github/forks/apt69/COMahawk.svg)
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2019-1405](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2019-1405) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)

## CVE-2019-1388

>  An elevation of privilege vulnerability exists in the Windows Certificate Dialog when it does not properly enforce user privileges, aka 'Windows Certificate Dialog Elevation of Privilege Vulnerability'.

- **Analyse**
  - http://blog.leanote.com/post/snowming/38069f423c76
  - https://mp.weixin.qq.com/s/q4UICIVwC4HX-ytvWo8Dvw
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2019-1388](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2019-1388) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/jas502n/CVE-2019-1388](https://github.com/jas502n/CVE-2019-1388) :  ![starts](https://img.shields.io/github/stars/jas502n/CVE-2019-1388.svg) ![forks](https://img.shields.io/github/forks/jas502n/CVE-2019-1388.svg)
  - [https://github.com/sv3nbeast/CVE-2019-1388](https://github.com/sv3nbeast/CVE-2019-1388) :  ![starts](https://img.shields.io/github/stars/sv3nbeast/CVE-2019-1388.svg) ![forks](https://img.shields.io/github/forks/sv3nbeast/CVE-2019-1388.svg)
  - [https://github.com/jaychouzzk/CVE-2019-1388](https://github.com/jaychouzzk/CVE-2019-1388) :  ![starts](https://img.shields.io/github/stars/jaychouzzk/CVE-2019-1388.svg) ![forks](https://img.shields.io/github/forks/jaychouzzk/CVE-2019-1388.svg)

## CVE-2019-1385

> An elevation of privilege vulnerability exists when the Windows AppX Deployment Extensions improperly performs privilege management, resulting in access to system files.To exploit this vulnerability, an authenticated attacker would need to run a specially crafted application to elevate privileges.The security update addresses the vulnerability by correcting how AppX Deployment Extensions manages privileges., aka 'Windows AppX Deployment Extensions Elevation of Privilege Vulnerability'.

- **Exp**
  - [https://github.com/klinix5/CVE-2019-1385](https://github.com/klinix5/CVE-2019-1385) :  ![starts](https://img.shields.io/github/stars/klinix5/CVE-2019-1385.svg) ![forks](https://img.shields.io/github/forks/klinix5/CVE-2019-1385.svg)
  - [https://github.com/0x413x4/CVE-2019-1385](https://github.com/0x413x4/CVE-2019-1385) :  ![starts](https://img.shields.io/github/stars/0x413x4/CVE-2019-1385.svg) ![forks](https://img.shields.io/github/forks/0x413x4/CVE-2019-1385.svg)



## CVE-2019-1322

> An elevation of privilege vulnerability exists when Windows improperly handles authentication requests, aka 'Microsoft Windows Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-1320, CVE-2019-1340.

- **Analyse**
  - https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2019/november/cve-2019-1405-and-cve-2019-1322-elevation-to-system-via-the-upnp-device-host-service-and-the-update-orchestrator-service/
  - https://www.anquanke.com/post/id/193022
  - https://nosec.org/m/share/3177.html
- **Exp**
  - [https://github.com/apt69/COMahawk](https://github.com/apt69/COMahawk) :  ![starts](https://img.shields.io/github/stars/apt69/COMahawk.svg) ![forks](https://img.shields.io/github/forks/apt69/COMahawk.svg)

## CVE-2019-1315

> An elevation of privilege vulnerability exists when Windows Error Reporting manager improperly handles hard links, aka 'Windows Error Reporting Manager Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-1339, CVE-2019-1342.

- **Analyse**
  - https://offsec.almond.consulting/windows-error-reporting-arbitrary-file-move-eop.html
  - https://nosec.org/home/detail/3027.html
- **PoC**
  - [https://github.com/Mayter/CVE-2019-1315](https://github.com/Mayter/CVE-2019-1315) :  ![starts](https://img.shields.io/github/stars/Mayter/CVE-2019-1315.svg) ![forks](https://img.shields.io/github/forks/Mayter/CVE-2019-1315.svg)

## CVE-2019-1253

>  An elevation of privilege vulnerability exists when the Windows AppX Deployment Server improperly handles junctions.To exploit this vulnerability, an attacker would first have to gain execution on the victim system, aka 'Windows Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-1215, CVE-2019-1278, CVE-2019-1303.

- **Exp**
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2019-1253](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2019-1253) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)
  - [https://github.com/padovah4ck/CVE-2019-1253](https://github.com/padovah4ck/CVE-2019-1253) :  ![starts](https://img.shields.io/github/stars/padovah4ck/CVE-2019-1253.svg) ![forks](https://img.shields.io/github/forks/padovah4ck/CVE-2019-1253.svg)
  - [https://github.com/rogue-kdc/CVE-2019-1253](https://github.com/rogue-kdc/CVE-2019-1253) :  ![starts](https://img.shields.io/github/stars/rogue-kdc/CVE-2019-1253.svg) ![forks](https://img.shields.io/github/forks/rogue-kdc/CVE-2019-1253.svg)
  - [https://github.com/sgabe/CVE-2019-1253](https://github.com/sgabe/CVE-2019-1253) :  ![starts](https://img.shields.io/github/stars/sgabe/CVE-2019-1253.svg) ![forks](https://img.shields.io/github/forks/sgabe/CVE-2019-1253.svg)
  - [https://github.com/likescam/CVE-2019-1253](https://github.com/likescam/CVE-2019-1253) :  ![starts](https://img.shields.io/github/stars/likescam/CVE-2019-1253.svg) ![forks](https://img.shields.io/github/forks/likescam/CVE-2019-1253.svg)



## CVE-2019-1215

> An elevation of privilege vulnerability exists in the way that ws2ifsl.sys (Winsock) handles objects in memory, aka 'Windows Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-1253, CVE-2019-1278, CVE-2019-1303.

- **Analyse**
  - https://labs.bluefrostsecurity.de/blog/2020/01/07/cve-2019-1215-analysis-of-a-use-after-free-in-ws2ifsl/
  - https://bbs.pediy.com/thread-257435.htm
  - https://www.freebuf.com/vuls/226167.html
  - https://www.163.com/dy/article/FQBEHKLS0511CJ6O.html
  - https://saturn35.com/2020/01/09/20200109-1/
  - https://day.fujieace.com/security-research/600.html
- **Exp**
  - [https://github.com/bluefrostsecurity/CVE-2019-1215](https://github.com/bluefrostsecurity/CVE-2019-1215) :  ![starts](https://img.shields.io/github/stars/bluefrostsecurity/CVE-2019-1215.svg) ![forks](https://img.shields.io/github/forks/bluefrostsecurity/CVE-2019-1215.svg)

## CVE-2019-1132

> An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'.

- **Analyse**
  - https://zhuanlan.zhihu.com/p/335166796
  - https://ti.qianxin.com/blog/articles/buhtrap-cve-2019-1132-attack-event-related-vulnerability-sample-analysis/
  - https://www.welivesecurity.com/2019/07/10/windows-zero-day-cve-2019-1132-exploit/
  - https://www.anquanke.com/post/id/181794
- **Exp**
  - [https://github.com/Vlad-tri/CVE-2019-1132](https://github.com/Vlad-tri/CVE-2019-1132) :  ![starts](https://img.shields.io/github/stars/Vlad-tri/CVE-2019-1132.svg) ![forks](https://img.shields.io/github/forks/Vlad-tri/CVE-2019-1132.svg)
  - [https://github.com/petercc/CVE-2019-1132](https://github.com/petercc/CVE-2019-1132) :  ![starts](https://img.shields.io/github/stars/petercc/CVE-2019-1132.svg) ![forks](https://img.shields.io/github/forks/petercc/CVE-2019-1132.svg)

## CVE-2019-1129/1130

> An elevation of privilege vulnerability exists when Windows AppX Deployment Service (AppXSVC) improperly handles hard links, aka 'Windows Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-1130.

- **Exp**
  - [https://github.com/S3cur3Th1sSh1t/SharpByeBear](https://github.com/S3cur3Th1sSh1t/SharpByeBear) :  ![starts](https://img.shields.io/github/stars/S3cur3Th1sSh1t/SharpByeBear.svg) ![forks](https://img.shields.io/github/forks/S3cur3Th1sSh1t/SharpByeBear.svg)

## CVE-2019-1064

> An elevation of privilege vulnerability exists when Windows AppX Deployment Service (AppXSVC) improperly handles hard links, aka 'Windows Elevation of Privilege Vulnerability'.

- **Analyse**
  - http://cn-sec.com/archives/74164.html
- **PoC**
  - [https://github.com/RythmStick/CVE-2019-1064](https://github.com/RythmStick/CVE-2019-1064) :  ![starts](https://img.shields.io/github/stars/RythmStick/CVE-2019-1064.svg) ![forks](https://img.shields.io/github/forks/RythmStick/CVE-2019-1064.svg)
  - [https://github.com/0x00-0x00/CVE-2019-1064](https://github.com/0x00-0x00/CVE-2019-1064) :  ![starts](https://img.shields.io/github/stars/0x00-0x00/CVE-2019-1064.svg) ![forks](https://img.shields.io/github/forks/0x00-0x00/CVE-2019-1064.svg)

## CVE-2019-1040

> A tampering vulnerability exists in Microsoft Windows when a man-in-the-middle attacker is able to successfully bypass the NTLM MIC (Message Integrity Check) protection, aka 'Windows NTLM Tampering Vulnerability'.

- **Analyse**
  - https://bbs.pediy.com/thread-252018.htm
  - https://zhuanlan.zhihu.com/p/345406848
- **PoC**
  - [https://github.com/fox-it/cve-2019-1040-scanner](https://github.com/fox-it/cve-2019-1040-scanner) :  ![starts](https://img.shields.io/github/stars/fox-it/cve-2019-1040-scanner.svg) ![forks](https://img.shields.io/github/forks/fox-it/cve-2019-1040-scanner.svg)
  - [https://github.com/lazaars/UltraRealy_with_CVE-2019-1040](https://github.com/lazaars/UltraRealy_with_CVE-2019-1040) :  ![starts](https://img.shields.io/github/stars/lazaars/UltraRealy_with_CVE-2019-1040.svg) ![forks](https://img.shields.io/github/forks/lazaars/UltraRealy_with_CVE-2019-1040.svg)
- **Exp**
  - [https://github.com/Ridter/CVE-2019-1040](https://github.com/Ridter/CVE-2019-1040) :  ![starts](https://img.shields.io/github/stars/Ridter/CVE-2019-1040.svg) ![forks](https://img.shields.io/github/forks/Ridter/CVE-2019-1040.svg)
  - [https://github.com/QAX-A-Team/dcpwn](https://github.com/QAX-A-Team/dcpwn) :  ![starts](https://img.shields.io/github/stars/QAX-A-Team/dcpwn.svg) ![forks](https://img.shields.io/github/forks/QAX-A-Team/dcpwn.svg)
  - [https://github.com/Ridter/CVE-2019-1040-dcpwn](https://github.com/Ridter/CVE-2019-1040-dcpwn) :  ![starts](https://img.shields.io/github/stars/Ridter/CVE-2019-1040-dcpwn.svg) ![forks](https://img.shields.io/github/forks/Ridter/CVE-2019-1040-dcpwn.svg)
  - [https://github.com/wzxmt/CVE-2019-1040](https://github.com/wzxmt/CVE-2019-1040) :  ![starts](https://img.shields.io/github/stars/wzxmt/CVE-2019-1040.svg) ![forks](https://img.shields.io/github/forks/wzxmt/CVE-2019-1040.svg)

## CVE-2019-0986

> An elevation of privilege vulnerability exists when the Windows User Profile Service (ProfSvc) improperly handles symlinks, aka 'Windows User Profile Service Elevation of Privilege Vulnerability'.

- **PoC**
  - [https://github.com/padovah4ck/CVE-2019-0986](https://github.com/padovah4ck/CVE-2019-0986) :  ![starts](https://img.shields.io/github/stars/padovah4ck/CVE-2019-0986.svg) ![forks](https://img.shields.io/github/forks/padovah4ck/CVE-2019-0986.svg)

## CVE-2019-0863

> An elevation of privilege vulnerability exists in the way Windows Error Reporting (WER) handles files, aka 'Windows Error Reporting Elevation of Privilege Vulnerability'.

- **Analyse**
  - https://xz.aliyun.com/t/5571
  - https://unit42.paloaltonetworks.com/tale-of-a-windows-error-reporting-zero-day-cve-2019-0863/
  - https://www.anquanke.com/post/id/181457
- **Exp**
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2019-0863/WerTrigger-master](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2019-0863/WerTrigger-master) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)
  - [https://github.com/sailay1996/WerTrigger](https://github.com/sailay1996/WerTrigger) :  ![starts](https://img.shields.io/github/stars/sailay1996/WerTrigger.svg) ![forks](https://img.shields.io/github/forks/sailay1996/WerTrigger.svg)



## CVE-2019-0859

> An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-0685, CVE-2019-0803.

- **Analyse**
  - https://www.secrss.com/articles/9942
  - https://blog.csdn.net/blackorbird/article/details/102462546
  - https://www.4hou.com/posts/3jRO
  - https://nosec.org/home/detail/2490.html
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2019-0859](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2019-0859) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/Sheisback/CVE-2019-0859-1day-Exploit](https://github.com/Sheisback/CVE-2019-0859-1day-Exploit) :  ![starts](https://img.shields.io/github/stars/Sheisback/CVE-2019-0859-1day-Exploit.svg) ![forks](https://img.shields.io/github/forks/Sheisback/CVE-2019-0859-1day-Exploit.svg)

## CVE-2019-0803

> An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-0685, CVE-2019-0859.

- **Analyse**
  - https://bbs.pediy.com/thread-260289.htm
  - https://www.jianshu.com/p/91e0f79f36eb
  - https://zhuanlan.zhihu.com/p/62520006
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2019-0803](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2019-0803) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2019-0803](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2019-0803) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)
  - [https://github.com/ExpLife0011/CVE-2019-0803](https://github.com/ExpLife0011/CVE-2019-0803) :  ![starts](https://img.shields.io/github/stars/ExpLife0011/CVE-2019-0803.svg) ![forks](https://img.shields.io/github/forks/ExpLife0011/CVE-2019-0803.svg)

## CVE-2019-0708

> A remote code execution vulnerability exists in Remote Desktop Services formerly known as Terminal Services when an unauthenticated attacker connects to the target system using RDP and sends specially crafted requests, aka 'Remote Desktop Services Remote Code Execution Vulnerability'.

- **Analyse**
  - https://xz.aliyun.com/t/5243
  - https://bbs.pediy.com/thread-256734.htm
  - https://www.anquanke.com/post/id/178964
  - https://www.cnblogs.com/backlion/p/11482322.html
- **PoC**
  - [https://github.com/Ekultek/BlueKeep](https://github.com/Ekultek/BlueKeep) :  ![starts](https://img.shields.io/github/stars/Ekultek/BlueKeep.svg) ![forks](https://img.shields.io/github/forks/Ekultek/BlueKeep.svg)
  - [https://github.com/zerosum0x0/CVE-2019-0708](https://github.com/zerosum0x0/CVE-2019-0708) :  ![starts](https://img.shields.io/github/stars/zerosum0x0/CVE-2019-0708.svg) ![forks](https://img.shields.io/github/forks/zerosum0x0/CVE-2019-0708.svg)
  - [https://github.com/robertdavidgraham/rdpscan](https://github.com/robertdavidgraham/rdpscan) :  ![starts](https://img.shields.io/github/stars/robertdavidgraham/rdpscan.svg) ![forks](https://img.shields.io/github/forks/robertdavidgraham/rdpscan.svg)
  - [https://github.com/n1xbyte/CVE-2019-0708](https://github.com/n1xbyte/CVE-2019-0708) :  ![starts](https://img.shields.io/github/stars/n1xbyte/CVE-2019-0708.svg) ![forks](https://img.shields.io/github/forks/n1xbyte/CVE-2019-0708.svg)
  - [https://github.com/k8gege/CVE-2019-0708](https://github.com/k8gege/CVE-2019-0708) :  ![starts](https://img.shields.io/github/stars/k8gege/CVE-2019-0708.svg) ![forks](https://img.shields.io/github/forks/k8gege/CVE-2019-0708.svg)
  - [https://github.com/0xeb-bp/bluekeep](https://github.com/0xeb-bp/bluekeep) :  ![starts](https://img.shields.io/github/stars/0xeb-bp/bluekeep.svg) ![forks](https://img.shields.io/github/forks/0xeb-bp/bluekeep.svg)
  - [https://github.com/nccgroup/BKScan](https://github.com/nccgroup/BKScan) :  ![starts](https://img.shields.io/github/stars/nccgroup/BKScan.svg) ![forks](https://img.shields.io/github/forks/nccgroup/BKScan.svg)
  - [https://github.com/Leoid/CVE-2019-0708](https://github.com/Leoid/CVE-2019-0708) :  ![starts](https://img.shields.io/github/stars/Leoid/CVE-2019-0708.svg) ![forks](https://img.shields.io/github/forks/Leoid/CVE-2019-0708.svg)
  - [https://github.com/worawit/CVE-2019-0708](https://github.com/worawit/CVE-2019-0708) :  ![starts](https://img.shields.io/github/stars/worawit/CVE-2019-0708.svg) ![forks](https://img.shields.io/github/forks/worawit/CVE-2019-0708.svg)
  - [https://github.com/biggerwing/CVE-2019-0708-poc](https://github.com/biggerwing/CVE-2019-0708-poc) :  ![starts](https://img.shields.io/github/stars/biggerwing/CVE-2019-0708-poc.svg) ![forks](https://img.shields.io/github/forks/biggerwing/CVE-2019-0708-poc.svg)
  - [https://github.com/umarfarook882/CVE-2019-0708](https://github.com/umarfarook882/CVE-2019-0708) :  ![starts](https://img.shields.io/github/stars/umarfarook882/CVE-2019-0708.svg) ![forks](https://img.shields.io/github/forks/umarfarook882/CVE-2019-0708.svg)
  - [https://github.com/Jaky5155/cve-2019-0708-exp](https://github.com/Jaky5155/cve-2019-0708-exp) :  ![starts](https://img.shields.io/github/stars/Jaky5155/cve-2019-0708-exp.svg) ![forks](https://img.shields.io/github/forks/Jaky5155/cve-2019-0708-exp.svg)
- **Exp**
  - https://www.rapid7.com/blog/post/2019/09/06/initial-metasploit-exploit-module-for-bluekeep-cve-2019-0708/
  - [https://github.com/algo7/bluekeep_CVE-2019-0708_poc_to_exploit](https://github.com/algo7/bluekeep_CVE-2019-0708_poc_to_exploit) :  ![starts](https://img.shields.io/github/stars/algo7/bluekeep_CVE-2019-0708_poc_to_exploit.svg) ![forks](https://img.shields.io/github/forks/algo7/bluekeep_CVE-2019-0708_poc_to_exploit.svg)
  - [https://github.com/cbwang505/CVE-2019-0708-EXP-Windows](https://github.com/cbwang505/CVE-2019-0708-EXP-Windows) :  ![starts](https://img.shields.io/github/stars/cbwang505/CVE-2019-0708-EXP-Windows.svg) ![forks](https://img.shields.io/github/forks/cbwang505/CVE-2019-0708-EXP-Windows.svg)
  - [https://github.com/Cyb0r9/ispy](https://github.com/Cyb0r9/ispy) :  ![starts](https://img.shields.io/github/stars/Cyb0r9/ispy.svg) ![forks](https://img.shields.io/github/forks/Cyb0r9/ispy.svg)
  - [https://github.com/NAXG/cve_2019_0708_bluekeep_rce](https://github.com/NAXG/cve_2019_0708_bluekeep_rce) :  ![starts](https://img.shields.io/github/stars/NAXG/cve_2019_0708_bluekeep_rce.svg) ![forks](https://img.shields.io/github/forks/NAXG/cve_2019_0708_bluekeep_rce.svg)
  - [https://github.com/dorkerdevil/Remote-Desktop-Services-Remote-Code-Execution-Vulnerability-CVE-2019-0708-](https://github.com/dorkerdevil/Remote-Desktop-Services-Remote-Code-Execution-Vulnerability-CVE-2019-0708-) :  ![starts](https://img.shields.io/github/stars/dorkerdevil/Remote-Desktop-Services-Remote-Code-Execution-Vulnerability-CVE-2019-0708-.svg) ![forks](https://img.shields.io/github/forks/dorkerdevil/Remote-Desktop-Services-Remote-Code-Execution-Vulnerability-CVE-2019-0708-.svg)
  - [https://github.com/TinToSer/bluekeep-exploit](https://github.com/TinToSer/bluekeep-exploit) :  ![starts](https://img.shields.io/github/stars/TinToSer/bluekeep-exploit.svg) ![forks](https://img.shields.io/github/forks/TinToSer/bluekeep-exploit.svg)
  - [https://github.com/coolboy4me/cve-2019-0708_bluekeep_rce](https://github.com/coolboy4me/cve-2019-0708_bluekeep_rce) :  ![starts](https://img.shields.io/github/stars/coolboy4me/cve-2019-0708_bluekeep_rce.svg) ![forks](https://img.shields.io/github/forks/coolboy4me/cve-2019-0708_bluekeep_rce.svg)
  - [https://github.com/mai-lang-chai/CVE-2019-0708-RCE](https://github.com/mai-lang-chai/CVE-2019-0708-RCE) :  ![starts](https://img.shields.io/github/stars/mai-lang-chai/CVE-2019-0708-RCE.svg) ![forks](https://img.shields.io/github/forks/mai-lang-chai/CVE-2019-0708-RCE.svg)
  - [https://github.com/rockmelodies/CVE-2019-0708-Exploit](https://github.com/rockmelodies/CVE-2019-0708-Exploit) :  ![starts](https://img.shields.io/github/stars/rockmelodies/CVE-2019-0708-Exploit.svg) ![forks](https://img.shields.io/github/forks/rockmelodies/CVE-2019-0708-Exploit.svg)
  - to more on github...

## CVE-2019-0623

> An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'.

- **Analyse**
  - https://paper.seebug.org/832/
- **Exp**
  - [https://github.com/DreamoneOnly/CVE-2019-0623-32-exp](https://github.com/DreamoneOnly/CVE-2019-0623-32-exp) :  ![starts](https://img.shields.io/github/stars/DreamoneOnly/CVE-2019-0623-32-exp.svg) ![forks](https://img.shields.io/github/forks/DreamoneOnly/CVE-2019-0623-32-exp.svg)



# 2018

## CVE-2018-8639

> An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka "Win32k Elevation of Privilege Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2019, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers. This CVE ID is unique from CVE-2018-8641.

- **Analyse**
  - https://www.anquanke.com/post/id/183358
  - https://bbs.pediy.com/thread-251400.htm
  - https://bbs.pediy.com/thread-254305.htm
- **Exp** 
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2018-8639](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2018-8639) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/ze0r/CVE-2018-8639-exp](https://github.com/ze0r/CVE-2018-8639-exp) :  ![starts](https://img.shields.io/github/stars/ze0r/CVE-2018-8639-exp.svg) ![forks](https://img.shields.io/github/forks/ze0r/CVE-2018-8639-exp.svg)
  - [https://github.com/timwhitez/CVE-2018-8639-EXP](https://github.com/timwhitez/CVE-2018-8639-EXP) :  ![starts](https://img.shields.io/github/stars/timwhitez/CVE-2018-8639-EXP.svg) ![forks](https://img.shields.io/github/forks/timwhitez/CVE-2018-8639-EXP.svg)

## CVE-2018-8453

> An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka "Win32k Elevation of Privilege Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2019, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

- **Analyse**
  - github https://github.com/thepwnrip/leHACK-Analysis-of-CVE-2018-8453
  - https://www.anquanke.com/post/id/162894
  - https://paper.seebug.org/784/
  - https://paper.seebug.org/798/
  - https://bbs.pediy.com/thread-249021.htm
  - https://www.jianshu.com/p/082bd9992b57
  - https://www.whsgwl.net/blog/CVE-2018-8453_0.html
  - https://www.whsgwl.net/blog/CVE-2018-8453_1.html
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2018-8453](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2018-8453) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/ze0r/cve-2018-8453-exp](https://github.com/ze0r/cve-2018-8453-exp) :  ![starts](https://img.shields.io/github/stars/ze0r/cve-2018-8453-exp.svg) ![forks](https://img.shields.io/github/forks/ze0r/cve-2018-8453-exp.svg)
  - [https://github.com/Mkv4/cve-2018-8453-exp](https://github.com/Mkv4/cve-2018-8453-exp) :  ![starts](https://img.shields.io/github/stars/Mkv4/cve-2018-8453-exp.svg) ![forks](https://img.shields.io/github/forks/Mkv4/cve-2018-8453-exp.svg)

## CVE-2018-8440

> An elevation of privilege vulnerability exists when Windows improperly handles calls to Advanced Local Procedure Call (ALPC), aka "Windows ALPC Elevation of Privilege Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

- **Analyse**
  - https://blog.0patch.com/2018/08/how-we-micropatched-publicly-dropped.html
  - https://blog.0patch.com/2018/09/comparing-our-micropatch-with.html
  - https://www.anquanke.com/post/id/169382
- **Exp**
  - [https://github.com/sourceincite/CVE-2018-8440](https://github.com/sourceincite/CVE-2018-8440) :  ![starts](https://img.shields.io/github/stars/sourceincite/CVE-2018-8440.svg) ![forks](https://img.shields.io/github/forks/sourceincite/CVE-2018-8440.svg)

## CVE-2018-8414

> A remote code execution vulnerability exists when the Windows Shell does not properly validate file paths, aka "Windows Shell Remote Code Execution Vulnerability." This affects Windows 10 Servers, Windows 10.

- **Analyse**
  - https://www.anquanke.com/post/id/157782
  - https://www.cnblogs.com/backlion/p/9642241.html
- **Exp**
  - [https://github.com/whereisr0da/CVE-2018-8414-POC](https://github.com/whereisr0da/CVE-2018-8414-POC) :  ![starts](https://img.shields.io/github/stars/whereisr0da/CVE-2018-8414-POC.svg) ![forks](https://img.shields.io/github/forks/whereisr0da/CVE-2018-8414-POC.svg)

## CVE-2018-8120

> An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka "Win32k Elevation of Privilege Vulnerability." This affects Windows Server 2008, Windows 7, Windows Server 2008 R2. This CVE ID is unique from CVE-2018-8124, CVE-2018-8164, CVE-2018-8166.

- **Analyse**
  - github https://github.com/EVOL4/CVE-2018-8120/blob/master/CVE-2018-8120.md
  - https://b2ahex.github.io/blog/2018/05/15/8120%E5%88%86%E6%9E%90/index.html
  - https://paper.seebug.org/614/
  - https://xz.aliyun.com/t/8667
  - http://xz.aliyun.com/t/5966
- **PoC**
  - [https://github.com/areuu/CVE-2018-8120](https://github.com/areuu/CVE-2018-8120) :  ![starts](https://img.shields.io/github/stars/areuu/CVE-2018-8120.svg) ![forks](https://img.shields.io/github/forks/areuu/CVE-2018-8120.svg)
  - [https://github.com/StartZYP/CVE-2018-8120](https://github.com/StartZYP/CVE-2018-8120) :  ![starts](https://img.shields.io/github/stars/StartZYP/CVE-2018-8120.svg) ![forks](https://img.shields.io/github/forks/StartZYP/CVE-2018-8120.svg)
- **Exp**
  - [https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2018-8120](https://github.com/Al1ex/WindowsElevation/tree/master/CVE-2018-8120) :  ![starts](https://img.shields.io/github/stars/Al1ex/WindowsElevation.svg) ![forks](https://img.shields.io/github/forks/Al1ex/WindowsElevation.svg)
  - [https://github.com/unamer/CVE-2018-8120](https://github.com/unamer/CVE-2018-8120) :  ![starts](https://img.shields.io/github/stars/unamer/CVE-2018-8120.svg) ![forks](https://img.shields.io/github/forks/unamer/CVE-2018-8120.svg)
  - [https://github.com/alpha1ab/CVE-2018-8120](https://github.com/alpha1ab/CVE-2018-8120) :  ![starts](https://img.shields.io/github/stars/alpha1ab/CVE-2018-8120.svg) ![forks](https://img.shields.io/github/forks/alpha1ab/CVE-2018-8120.svg)
  - [https://github.com/bigric3/cve-2018-8120](https://github.com/bigric3/cve-2018-8120) :  ![starts](https://img.shields.io/github/stars/bigric3/cve-2018-8120.svg) ![forks](https://img.shields.io/github/forks/bigric3/cve-2018-8120.svg)
  - [https://github.com/ne1llee/cve-2018-8120](https://github.com/ne1llee/cve-2018-8120) :  ![starts](https://img.shields.io/github/stars/ne1llee/cve-2018-8120.svg) ![forks](https://img.shields.io/github/forks/ne1llee/cve-2018-8120.svg)
  - [https://github.com/ozkanbilge/CVE-2018-8120](https://github.com/ozkanbilge/CVE-2018-8120) :  ![starts](https://img.shields.io/github/stars/ozkanbilge/CVE-2018-8120.svg) ![forks](https://img.shields.io/github/forks/ozkanbilge/CVE-2018-8120.svg)
  - [https://github.com/EVOL4/CVE-2018-8120](https://github.com/EVOL4/CVE-2018-8120) :  ![starts](https://img.shields.io/github/stars/EVOL4/CVE-2018-8120.svg) ![forks](https://img.shields.io/github/forks/EVOL4/CVE-2018-8120.svg)
  - [https://github.com/qiantu88/CVE-2018-8120](https://github.com/qiantu88/CVE-2018-8120) :  ![starts](https://img.shields.io/github/stars/qiantu88/CVE-2018-8120.svg) ![forks](https://img.shields.io/github/forks/qiantu88/CVE-2018-8120.svg)
  - [https://github.com/Y0n0Y/cve-2018-8120-exp](https://github.com/Y0n0Y/cve-2018-8120-exp) :  ![starts](https://img.shields.io/github/stars/Y0n0Y/cve-2018-8120-exp.svg) ![forks](https://img.shields.io/github/forks/Y0n0Y/cve-2018-8120-exp.svg)
  - [https://github.com/DreamoneOnly/CVE-2018-8120](https://github.com/DreamoneOnly/CVE-2018-8120) :  ![starts](https://img.shields.io/github/stars/DreamoneOnly/CVE-2018-8120.svg) ![forks](https://img.shields.io/github/forks/DreamoneOnly/CVE-2018-8120.svg)
  - [https://github.com/wikiZ/cve-2018-8120](https://github.com/wikiZ/cve-2018-8120) :  ![starts](https://img.shields.io/github/stars/wikiZ/cve-2018-8120.svg) ![forks](https://img.shields.io/github/forks/wikiZ/cve-2018-8120.svg)

## CVE-2018-7249

> An issue was discovered in secdrv.sys as shipped in Microsoft Windows Vista, Windows 7, Windows 8, and Windows 8.1 before KB3086255, and as shipped in Macrovision SafeDisc. Two carefully timed calls to IOCTL 0xCA002813 can cause a race condition that leads to a use-after-free. When exploited, an unprivileged attacker can run arbitrary code in the kernel.

- **Exp**
  - [https://github.com/Elvin9/NotSecDrv](https://github.com/Elvin9/NotSecDrv) :  ![starts](https://img.shields.io/github/stars/Elvin9/NotSecDrv.svg) ![forks](https://img.shields.io/github/forks/Elvin9/NotSecDrv.svg)

## CVE-2018-1038

> The Windows kernel in Windows 7 SP1 and Windows Server 2008 R2 SP1 allows an elevation of privilege vulnerability due to the way it handles objects in memory, aka "Windows Kernel Elevation of Privilege Vulnerability."

- **Analyse**
  - https://blog.xpnsec.com/total-meltdown-cve-2018-1038/
  - https://www.anquanke.com/post/id/106156
  - https://de4dcr0w.github.io/%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/CVE-2018-1038-TotalMeltdown%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90%E7%9A%84%E4%B8%80%E7%82%B9%E8%AE%B0%E5%BD%95.html
- **Exp**
  - https://gist.github.com/xpn/3792ec34d712425a5c47caf5677de5fe
  - https://www.exploit-db.com/exploits/44581

## CVE-2018-0886

> The Credential Security Support Provider protocol (CredSSP) in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1 and RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, and 1709 Windows Server 2016 and Windows Server, version 1709 allows a remote code execution vulnerability due to how CredSSP validates request during the authentication process, aka "CredSSP Remote Code Execution Vulnerability".

- **Analyse**
  - https://www.anquanke.com/post/id/101158
- **Exp**
  - [https://github.com/preempt/credssp](https://github.com/preempt/credssp) :  ![starts](https://img.shields.io/github/stars/preempt/credssp.svg) ![forks](https://img.shields.io/github/forks/preempt/credssp.svg)

## CVE-2018-0824

> A remote code execution vulnerability exists in "Microsoft COM for Windows" when it fails to properly handle serialized objects, aka "Microsoft COM for Windows Remote Code Execution Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

- **Analyse**
  - https://codewhitesec.blogspot.com/2018/06/cve-2018-0624.html
  - https://www.anquanke.com/post/id/148749
- **Exp**
  - https://www.exploit-db.com/exploits/44906
  - [https://github.com/codewhitesec/UnmarshalPwn](https://github.com/codewhitesec/UnmarshalPwn) :  ![starts](https://img.shields.io/github/stars/codewhitesec/UnmarshalPwn.svg) ![forks](https://img.shields.io/github/forks/codewhitesec/UnmarshalPwn.svg)

# 2017

## CVE-2017-11783

> Microsoft Windows 8.1, Windows Server 2012 R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allows an elevation of privilege vulnerability in the way it handles calls to Advanced Local Procedure Call (ALPC), aka "Windows Elevation of Privilege Vulnerability".

- **Exp**
  - [https://github.com/Sheisback/CVE-2017-11783](https://github.com/Sheisback/CVE-2017-11783) :  ![starts](https://img.shields.io/github/stars/Sheisback/CVE-2017-11783.svg) ![forks](https://img.shields.io/github/forks/Sheisback/CVE-2017-11783.svg)

## CVE-2017-8543

> Microsoft Windows XP SP3, Windows XP x64 XP2, Windows Server 2003 SP2, Windows Vista, Windows 7 SP1, Windows Server 2008 SP2 and R2 SP1, Windows 8, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allow an attacker to take control of the affected system when Windows Search fails to handle objects in memory, aka "Windows Search Remote Code Execution Vulnerability".

- **Analyse**
  - https://paper.seebug.org/355/

## CVE-2017-8465

> Microsoft Windows 8.1 and Windows RT 8.1, Windows Server 2012 R2, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allow an attacker to run processes in an elevated context when the Windows kernel improperly handles objects in memory, aka "Win32k Elevation of Privilege Vulnerability." This CVE ID is unique from CVE-2017-8468.

- **Exp**
  - [https://github.com/nghiadt1098/CVE-2017-8465](https://github.com/nghiadt1098/CVE-2017-8465) :  ![starts](https://img.shields.io/github/stars/nghiadt1098/CVE-2017-8465.svg) ![forks](https://img.shields.io/github/forks/nghiadt1098/CVE-2017-8465.svg)

## CVE-2017-8464

> Windows Shell in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows local users or remote attackers to execute arbitrary code via a crafted .LNK file, which is not properly handled during icon display in Windows Explorer or any other application that parses the icon of the shortcut. aka "LNK Remote Code Execution Vulnerability."

- **Analyse**
  - https://my.oschina.net/u/4310658/blog/3695267
  - https://www.anquanke.com/post/id/202705
  - https://wohin.me/0dayan-quan-external-stuxnet-cve-2017-8464/
  - https://blog.csdn.net/baidu_41647119/article/details/103875396
  - http://www.vxjump.net/files/vuln_analysis/cve-2017-8464.txt
- **PoC**
  - [https://github.com/Elm0D/CVE-2017-8464](https://github.com/Elm0D/CVE-2017-8464) :  ![starts](https://img.shields.io/github/stars/Elm0D/CVE-2017-8464.svg) ![forks](https://img.shields.io/github/forks/Elm0D/CVE-2017-8464.svg)
- **Exp**
  - https://www.exploit-db.com/exploits/42382/
  - https://www.exploit-db.com/exploits/42429/
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2017-8464](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2017-8464) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/3gstudent/CVE-2017-8464-EXP](https://github.com/3gstudent/CVE-2017-8464-EXP) :  ![starts](https://img.shields.io/github/stars/3gstudent/CVE-2017-8464-EXP.svg) ![forks](https://img.shields.io/github/forks/3gstudent/CVE-2017-8464-EXP.svg)
  - [https://github.com/Securitykid/CVE-2017-8464-exp-generator](https://github.com/Securitykid/CVE-2017-8464-exp-generator) :  ![starts](https://img.shields.io/github/stars/Securitykid/CVE-2017-8464-exp-generator.svg) ![forks](https://img.shields.io/github/forks/Securitykid/CVE-2017-8464-exp-generator.svg)
  - [https://github.com/xssfile/CVE-2017-8464-EXP](https://github.com/xssfile/CVE-2017-8464-EXP) :  ![starts](https://img.shields.io/github/stars/xssfile/CVE-2017-8464-EXP.svg) ![forks](https://img.shields.io/github/forks/xssfile/CVE-2017-8464-EXP.svg)
  - [https://github.com/X-Vector/usbhijacking](https://github.com/X-Vector/usbhijacking) :  ![starts](https://img.shields.io/github/stars/X-Vector/usbhijacking.svg) ![forks](https://img.shields.io/github/forks/X-Vector/usbhijacking.svg)

## CVE-2017-7269

> Buffer overflow in the ScStoragePathFromUrl function in the WebDAV service in Internet Information Services (IIS) 6.0 in Microsoft Windows Server 2003 R2 allows remote attackers to execute arbitrary code via a long header beginning with "If: <http://" in a PROPFIND request, as exploited in the wild in July or August 2016.

- **Analyse**
  - https://paper.seebug.org/259/
- **PoC**
  - [https://github.com/lcatro/CVE-2017-7269-Echo-PoC](https://github.com/lcatro/CVE-2017-7269-Echo-PoC) :  ![starts](https://img.shields.io/github/stars/lcatro/CVE-2017-7269-Echo-PoC.svg) ![forks](https://img.shields.io/github/forks/lcatro/CVE-2017-7269-Echo-PoC.svg)
- **Exp**
  - [https://github.com/zcgonvh/cve-2017-7269](https://github.com/zcgonvh/cve-2017-7269) :  ![starts](https://img.shields.io/github/stars/zcgonvh/cve-2017-7269.svg) ![forks](https://img.shields.io/github/forks/zcgonvh/cve-2017-7269.svg)
  - [https://github.com/zcgonvh/cve-2017-7269-tool](https://github.com/zcgonvh/cve-2017-7269-tool) :  ![starts](https://img.shields.io/github/stars/zcgonvh/cve-2017-7269-tool.svg) ![forks](https://img.shields.io/github/forks/zcgonvh/cve-2017-7269-tool.svg)
  - [https://github.com/g0rx/iis6-exploit-2017-CVE-2017-7269](https://github.com/g0rx/iis6-exploit-2017-CVE-2017-7269) :  ![starts](https://img.shields.io/github/stars/g0rx/iis6-exploit-2017-CVE-2017-7269.svg) ![forks](https://img.shields.io/github/forks/g0rx/iis6-exploit-2017-CVE-2017-7269.svg)
  - [https://github.com/eliuha/webdav_exploit](https://github.com/eliuha/webdav_exploit) :  ![starts](https://img.shields.io/github/stars/eliuha/webdav_exploit.svg) ![forks](https://img.shields.io/github/forks/eliuha/webdav_exploit.svg)
  - [https://github.com/Al1ex/CVE-2017-7269](https://github.com/Al1ex/CVE-2017-7269) :  ![starts](https://img.shields.io/github/stars/Al1ex/CVE-2017-7269.svg) ![forks](https://img.shields.io/github/forks/Al1ex/CVE-2017-7269.svg)
  - [https://github.com/slimpagey/IIS_6.0_WebDAV_Ruby](https://github.com/slimpagey/IIS_6.0_WebDAV_Ruby) :  ![starts](https://img.shields.io/github/stars/slimpagey/IIS_6.0_WebDAV_Ruby.svg) ![forks](https://img.shields.io/github/forks/slimpagey/IIS_6.0_WebDAV_Ruby.svg)
  - [https://github.com/caicai1355/CVE-2017-7269-exploit](https://github.com/caicai1355/CVE-2017-7269-exploit) :  ![starts](https://img.shields.io/github/stars/caicai1355/CVE-2017-7269-exploit.svg) ![forks](https://img.shields.io/github/forks/caicai1355/CVE-2017-7269-exploit.svg)


## CVE-2017-0290

> The Microsoft Malware Protection Engine running on Microsoft Forefront and Microsoft Defender on Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 does not properly scan a specially crafted file leading to memory corruption, aka "Microsoft Malware Protection Engine Remote Code Execution Vulnerability."

- **Analyse**
  - https://0patch.blogspot.jp/2017/05/0patching-worst-windows-remote-code.html
  - https://www.anquanke.com/post/id/86136
  - https://arstechnica.com/information-technology/2017/05/windows-defender-nscript-remote-vulnerability/
- **Exp**
  - https://www.exploit-db.com/exploits/41975/
  - [https://github.com/homjxi0e/CVE-2017-0290-](https://github.com/homjxi0e/CVE-2017-0290-) :  ![starts](https://img.shields.io/github/stars/homjxi0e/CVE-2017-0290-.svg) ![forks](https://img.shields.io/github/forks/homjxi0e/CVE-2017-0290-.svg)

## CVE-2017-0263

> The kernel-mode drivers in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allow local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability."

- **Analyse**
  - https://www.anquanke.com/post/id/102377
  - https://www.anquanke.com/post/id/102378
  - https://xz.aliyun.com/t/9287
  - https://50u1w4y.github.io/site/recurrence/CVE-2017-0263/
- **PoC**
  - https://www.exploit-db.com/exploits/44478

## CVE-2017-0213

> Windows COM Aggregate Marshaler in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allows an elevation privilege vulnerability when an attacker runs a specially crafted application, aka "Windows COM Elevation of Privilege Vulnerability". This CVE ID is unique from CVE-2017-0214.

- **Analyse**
  - https://cloud.tencent.com/developer/article/1045805
- **Exp**
  - https://www.exploit-db.com/exploits/42020/
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2017-0213](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2017-0213) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/zcgonvh/CVE-2017-0213](https://github.com/zcgonvh/CVE-2017-0213) :  ![starts](https://img.shields.io/github/stars/zcgonvh/CVE-2017-0213.svg) ![forks](https://img.shields.io/github/forks/zcgonvh/CVE-2017-0213.svg)
  - [https://github.com/eonrickity/CVE-2017-0213](https://github.com/eonrickity/CVE-2017-0213) :  ![starts](https://img.shields.io/github/stars/eonrickity/CVE-2017-0213.svg) ![forks](https://img.shields.io/github/forks/eonrickity/CVE-2017-0213.svg)
  - [https://github.com/jbooz1/CVE-2017-0213](https://github.com/jbooz1/CVE-2017-0213) :  ![starts](https://img.shields.io/github/stars/jbooz1/CVE-2017-0213.svg) ![forks](https://img.shields.io/github/forks/jbooz1/CVE-2017-0213.svg)
  - [https://github.com/Jos675/CVE-2017-0213-Exploit](https://github.com/Jos675/CVE-2017-0213-Exploit) :  ![starts](https://img.shields.io/github/stars/Jos675/CVE-2017-0213-Exploit.svg) ![forks](https://img.shields.io/github/forks/Jos675/CVE-2017-0213-Exploit.svg)
  - [https://github.com/shaheemirza/CVE-2017-0213-](https://github.com/shaheemirza/CVE-2017-0213-) :  ![starts](https://img.shields.io/github/stars/shaheemirza/CVE-2017-0213-.svg) ![forks](https://img.shields.io/github/forks/shaheemirza/CVE-2017-0213-.svg)

## CVE-2017-0143 (MS17-010)

> The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0144, CVE-2017-0146, and CVE-2017-0148.

- **Analyse**
  - https://www.anquanke.com/post/id/86270
  - github https://github.com/worawit/MS17-010/blob/master/BUG.txt
  - https://yi0934.github.io/2019/04/08/CVE%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/ms17-010/
  - https://cy2cs.top/2020/08/22/%E3%80%90owva%E3%80%91%E6%B0%B8%E6%81%92%E4%B9%8B%E8%93%9D%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/
  - https://paper.seebug.org/280/
- **PoC**
  - [https://github.com/peterpt/eternal_scanner](https://github.com/peterpt/eternal_scanner) :  ![starts](https://img.shields.io/github/stars/peterpt/eternal_scanner.svg) ![forks](https://img.shields.io/github/forks/peterpt/eternal_scanner.svg)
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS17-010](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS17-010) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/worawit/MS17-010](https://github.com/worawit/MS17-010) :  ![starts](https://img.shields.io/github/stars/worawit/MS17-010.svg) ![forks](https://img.shields.io/github/forks/worawit/MS17-010.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2017-0143](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2017-0143) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/3ndG4me/AutoBlue-MS17-010](https://github.com/3ndG4me/AutoBlue-MS17-010) :  ![starts](https://img.shields.io/github/stars/3ndG4me/AutoBlue-MS17-010.svg) ![forks](https://img.shields.io/github/forks/3ndG4me/AutoBlue-MS17-010.svg)
  - [https://github.com/bhassani/EternalBlueC](https://github.com/bhassani/EternalBlueC) :  ![starts](https://img.shields.io/github/stars/bhassani/EternalBlueC.svg) ![forks](https://img.shields.io/github/forks/bhassani/EternalBlueC.svg)
  - [https://github.com/mez-0/MS17-010-Python](https://github.com/mez-0/MS17-010-Python) :  ![starts](https://img.shields.io/github/stars/mez-0/MS17-010-Python.svg) ![forks](https://img.shields.io/github/forks/mez-0/MS17-010-Python.svg)
  - [https://github.com/hanshaze/MS17-010-EternalBlue-WinXP-Win10](https://github.com/hanshaze/MS17-010-EternalBlue-WinXP-Win10) :  ![starts](https://img.shields.io/github/stars/hanshaze/MS17-010-EternalBlue-WinXP-Win10.svg) ![forks](https://img.shields.io/github/forks/hanshaze/MS17-010-EternalBlue-WinXP-Win10.svg)
  - [https://github.com/povlteksttv/Eternalblue](https://github.com/povlteksttv/Eternalblue) :  ![starts](https://img.shields.io/github/stars/povlteksttv/Eternalblue.svg) ![forks](https://img.shields.io/github/forks/povlteksttv/Eternalblue.svg)
  - [https://github.com/pythonone/MS17-010](https://github.com/pythonone/MS17-010) :  ![starts](https://img.shields.io/github/stars/pythonone/MS17-010.svg) ![forks](https://img.shields.io/github/forks/pythonone/MS17-010.svg)
  - [https://github.com/d4t4s3c/SMBploit](https://github.com/d4t4s3c/SMBploit) :  ![starts](https://img.shields.io/github/stars/d4t4s3c/SMBploit.svg) ![forks](https://img.shields.io/github/forks/d4t4s3c/SMBploit.svg)
  - too more on github...


##  CVE-2017-0101 (MS17-017)

> The kernel-mode drivers in Transaction Manager in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2; Windows 7 SP1; Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1; Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allow local users to gain privileges via a crafted application, aka "Windows Elevation of Privilege Vulnerability."

- **Analyse**
  - https://paper.seebug.org/586/
  - https://bbs.pediy.com/thread-256949.htm
- **Exp**
  - https://www.exploit-db.com/exploits/44479/
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2017-0101](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2017-0101) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/kuteminh11/MS17-017-Microsoft-Windows-7-SP1-x86-Privilege-Escalation-Vulnerability](https://github.com/kuteminh11/MS17-017-Microsoft-Windows-7-SP1-x86-Privilege-Escalation-Vulnerability) :  ![starts](https://img.shields.io/github/stars/kuteminh11/MS17-017-Microsoft-Windows-7-SP1-x86-Privilege-Escalation-Vulnerability.svg) ![forks](https://img.shields.io/github/forks/kuteminh11/MS17-017-Microsoft-Windows-7-SP1-x86-Privilege-Escalation-Vulnerability.svg)

## CVE-2017-0100 (MS17-012)

> A DCOM object in Helppane.exe in Microsoft Windows 7 SP1; Windows Server 2008 R2; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows local users to gain privileges via a crafted application, aka "Windows HelpPane Elevation of Privilege Vulnerability."

- **Analyse**
  - https://ha.cker.in/index.php/Article/22608
- **Exp**
  - [https://github.com/Cn33liz/MS17-012](https://github.com/Cn33liz/MS17-012) :  ![starts](https://img.shields.io/github/stars/Cn33liz/MS17-012.svg) ![forks](https://img.shields.io/github/forks/Cn33liz/MS17-012.svg)
  - [https://github.com/cssxn/CVE-2017-0100](https://github.com/cssxn/CVE-2017-0100) :  ![starts](https://img.shields.io/github/stars/cssxn/CVE-2017-0100.svg) ![forks](https://img.shields.io/github/forks/cssxn/CVE-2017-0100.svg)

## CVE-2017-0005 (MS17-013)

> The Graphics Device Interface (GDI) in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607 allows local users to gain privileges via a crafted application, aka "Windows GDI Elevation of Privilege Vulnerability." This vulnerability is different from those described in CVE-2017-0001, CVE-2017-0025, and CVE-2017-0047.

- **Analyse**
  - https://www.anquanke.com/post/id/86669
  - https://www.microsoft.com/security/blog/2017/03/27/detecting-and-mitigating-elevation-of-privilege-exploit-for-cve-2017-0005/?source=mmpc
- **PoC**
  - [https://github.com/sheri31/0005poc](https://github.com/sheri31/0005poc) :  ![starts](https://img.shields.io/github/stars/sheri31/0005poc.svg) ![forks](https://img.shields.io/github/forks/sheri31/0005poc.svg)

# 2016

## CVE-2016-7255 (MS16-135)

> The kernel-mode drivers in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, and 1607, and Windows Server 2016 allow local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability."

- **Analyse**
  - https://www.anquanke.com/post/id/85232
- **PoC**
  - [https://github.com/FuzzySecurity/PSKernel-Primitives/tree/master/Sample-Exploits/MS16-135](https://github.com/FuzzySecurity/PSKernel-Primitives/tree/master/Sample-Exploits/MS16-135) :  ![starts](https://img.shields.io/github/stars/FuzzySecurity/PSKernel-Primitives.svg) ![forks](https://img.shields.io/github/forks/FuzzySecurity/PSKernel-Primitives.svg)
  - [https://github.com/tinysec/public/tree/master/CVE-2016-7255](https://github.com/tinysec/public/tree/master/CVE-2016-7255) :  ![starts](https://img.shields.io/github/stars/tinysec/public.svg) ![forks](https://img.shields.io/github/forks/tinysec/public.svg)
  - [https://github.com/FSecureLABS/CVE-2016-7255](https://github.com/FSecureLABS/CVE-2016-7255) :  ![starts](https://img.shields.io/github/stars/FSecureLABS/CVE-2016-7255.svg) ![forks](https://img.shields.io/github/forks/FSecureLABS/CVE-2016-7255.svg)
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-135](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-135) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-7255](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-7255) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/heh3/CVE-2016-7255](https://github.com/heh3/CVE-2016-7255) :  ![starts](https://img.shields.io/github/stars/heh3/CVE-2016-7255.svg) ![forks](https://img.shields.io/github/forks/heh3/CVE-2016-7255.svg)
  - [https://github.com/yuvatia/page-table-exploitation](https://github.com/yuvatia/page-table-exploitation) :  ![starts](https://img.shields.io/github/stars/yuvatia/page-table-exploitation.svg) ![forks](https://img.shields.io/github/forks/yuvatia/page-table-exploitation.svg)
  - [https://github.com/bbolmin/cve-2016-7255_x86_x64](https://github.com/bbolmin/cve-2016-7255_x86_x64) :  ![starts](https://img.shields.io/github/stars/bbolmin/cve-2016-7255_x86_x64.svg) ![forks](https://img.shields.io/github/forks/bbolmin/cve-2016-7255_x86_x64.svg)
  - [https://github.com/homjxi0e/CVE-2016-7255](https://github.com/homjxi0e/CVE-2016-7255) :  ![starts](https://img.shields.io/github/stars/homjxi0e/CVE-2016-7255.svg) ![forks](https://img.shields.io/github/forks/homjxi0e/CVE-2016-7255.svg)



## CVE-2016-3371 (MS16-111)

> The kernel API in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, and Windows 10 Gold, 1511, and 1607 does not properly enforce permissions, which allows local users to obtain sensitive information via a crafted application, aka "Windows Kernel Elevation of Privilege Vulnerability."

- **Exp**
  - https://www.exploit-db.com/exploits/40429/
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-111](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-111) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-3371](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-3371) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2016-3308/3309 (MS16-098)

> The kernel-mode drivers in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607 allow local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability," a different vulnerability than CVE-2016-3309, CVE-2016-3310, and CVE-2016-3311.

- **Analyse**
  - https://paper.seebug.org/37/
  - https://xz.aliyun.com/t/4543
  - github https://github.com/55-AA/CVE-2016-3308/blob/master/CVE-2016-3308.md
  - https://xz.aliyun.com/t/2919
  - https://paper.seebug.org/320/
  - https://security.tencent.com/index.php/blog/msg/117
  - https://www.anquanke.com/post/id/85302
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-098](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-098) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-3309](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-3309) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/sensepost/gdi-palettes-exp](https://github.com/sensepost/gdi-palettes-exp) :  ![starts](https://img.shields.io/github/stars/sensepost/gdi-palettes-exp.svg) ![forks](https://img.shields.io/github/forks/sensepost/gdi-palettes-exp.svg)
  - [https://github.com/55-AA/CVE-2016-3308](https://github.com/55-AA/CVE-2016-3308) :  ![starts](https://img.shields.io/github/stars/55-AA/CVE-2016-3308.svg) ![forks](https://img.shields.io/github/forks/55-AA/CVE-2016-3308.svg)
  - [https://github.com/siberas/CVE-2016-3309_Reloaded](https://github.com/siberas/CVE-2016-3309_Reloaded) :  ![starts](https://img.shields.io/github/stars/siberas/CVE-2016-3309_Reloaded.svg) ![forks](https://img.shields.io/github/forks/siberas/CVE-2016-3309_Reloaded.svg)



##  CVE-2016-3225 (MS16-075)

> The SMB server component in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, and Windows 10 Gold and 1511 allows local users to gain privileges via a crafted application that forwards an authentication request to an unintended service, aka "Windows SMB Server Elevation of Privilege Vulnerability."

- **Exp**
  - https://www.exploit-db.com/exploits/45562/
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-075](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-075) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-3225](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-3225) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - https://www.secpulse.com/archives/72798.html

## CVE-2016-0099 (MS16-032)

> The Secondary Logon Service in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, and Windows 10 Gold and 1511 does not properly process request handles, which allows local users to gain privileges via a crafted application, aka "Secondary Logon Elevation of Privilege Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-032](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-032) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-0099](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-0099) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/zcgonvh/MS16-032](https://github.com/zcgonvh/MS16-032) :  ![starts](https://img.shields.io/github/stars/zcgonvh/MS16-032.svg) ![forks](https://img.shields.io/github/forks/zcgonvh/MS16-032.svg)
  - [https://github.com/Meatballs1/ms16-032](https://github.com/Meatballs1/ms16-032) :  ![starts](https://img.shields.io/github/stars/Meatballs1/ms16-032.svg) ![forks](https://img.shields.io/github/forks/Meatballs1/ms16-032.svg)
  - [https://github.com/Sh3lldor/Get_System](https://github.com/Sh3lldor/Get_System) :  ![starts](https://img.shields.io/github/stars/Sh3lldor/Get_System.svg) ![forks](https://img.shields.io/github/forks/Sh3lldor/Get_System.svg)

## CVE-2016-0095 (MS16-034)

> The kernel-mode driver in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, and Windows 10 Gold and 1511 allows local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability," a different vulnerability than CVE-2016-0093, CVE-2016-0094, and CVE-2016-0096.

- **Analyse**
  - https://xz.aliyun.com/t/6008
  - http://weaponx.site/2017/08/11/CVE-2016-0095%E4%BB%8EPoC%E5%88%B0Exploit/
  - https://whereisk0shl.top/ssctf_pwn450_windows_kernel_exploitation_writeup.html
  - github https://github.com/k0keoyo/SSCTF-pwn450-ms16-034-writeup
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-034](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-034) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-0095](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-0095) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/fengjixuchui/cve-2016-0095-x64](https://github.com/fengjixuchui/cve-2016-0095-x64) :  ![starts](https://img.shields.io/github/stars/fengjixuchui/cve-2016-0095-x64.svg) ![forks](https://img.shields.io/github/forks/fengjixuchui/cve-2016-0095-x64.svg)

## CVE-2016-0051 (MS16-016)

> The WebDAV client in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, and Windows 10 Gold and 1511 allows local users to gain privileges via a crafted application, aka "WebDAV Elevation of Privilege Vulnerability."

- **Exp**
  - https://www.exploit-db.com/exploits/39788/
  - https://www.exploit-db.com/exploits/39432/
  - https://www.exploit-db.com/exploits/40085/
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-016](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-016) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-0051](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-0051) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/koczkatamas/CVE-2016-0051](https://github.com/koczkatamas/CVE-2016-0051) :  ![starts](https://img.shields.io/github/stars/koczkatamas/CVE-2016-0051.svg) ![forks](https://img.shields.io/github/forks/koczkatamas/CVE-2016-0051.svg)
  - [https://github.com/hexx0r/CVE-2016-0051](https://github.com/hexx0r/CVE-2016-0051) :  ![starts](https://img.shields.io/github/stars/hexx0r/CVE-2016-0051.svg) ![forks](https://img.shields.io/github/forks/hexx0r/CVE-2016-0051.svg)

## CVE-2016-0041 (MS16-014)

> Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold and 1511, and Internet Explorer 10 and 11 mishandle DLL loading, which allows local users to gain privileges via a crafted application, aka "DLL Loading Remote Code Execution Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-014](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS16-014) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-0041](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2016-0041) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

# 2015

## CVE-2015-2546 (MS15-097)

>  The kernel-mode driver in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT Gold and 8.1, and Windows 10 allows local users to gain privileges via a crafted application, aka "Win32k Memory Corruption Elevation of Privilege Vulnerability," a different vulnerability than CVE-2015-2511, CVE-2015-2517, and CVE-2015-2518.

- **Analyse**
  - http://drops.xmd5.com/static/drops/papers-9276.html
  - https://bbs.pediy.com/thread-263673.htm
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-097](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-097) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-2546](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-2546) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/k0keoyo/CVE-2015-2546-Exploit](https://github.com/k0keoyo/CVE-2015-2546-Exploit) :  ![starts](https://img.shields.io/github/stars/k0keoyo/CVE-2015-2546-Exploit.svg) ![forks](https://img.shields.io/github/forks/k0keoyo/CVE-2015-2546-Exploit.svg)

## CVE-2015-2387 (MS15-077)

> ATMFD.DLL in the Adobe Type Manager Font Driver in Microsoft Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows local users to gain privileges via a crafted application, aka "ATMFD.DLL Memory Corruption Vulnerability."

- **Exp**
  - https://www.exploit-db.com/exploits/37098/
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-077](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-077) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-2387](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-2387) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2015-2370 (MS15-076)

> The authentication implementation in the RPC subsystem in Microsoft Windows Server 2003 SP2 and R2 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 does not prevent DCE/RPC connection reflection, which allows local users to gain privileges via a crafted application, aka "Windows RPC Elevation of Privilege Vulnerability."

- **Analyse**
  - http://bobao.360.cn/learning/detail/584.html
  - https://blog.csdn.net/oShuangYue12/article/details/84677607
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-076](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-076) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-2370](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-2370) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/monoxgas/Trebuchet](https://github.com/monoxgas/Trebuchet) :  ![starts](https://img.shields.io/github/stars/monoxgas/Trebuchet.svg) ![forks](https://img.shields.io/github/forks/monoxgas/Trebuchet.svg)

## CVE-2015-1726 (MS15-061)

> Use-after-free vulnerability in the kernel-mode drivers in Microsoft Windows Server 2003 SP2 and R2 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows local users to gain privileges via a crafted application, aka "Microsoft Windows Kernel Brush Object Use After Free Vulnerability."

- **Analyse**
  - github https://github.com/LibreCrops/translation-zh_CN/blob/master/source/ms-15-061.rst
  - https://translation-zh-cn.readthedocs.io/zh_CN/latest/ms-15-061.html
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-061](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-061) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-1725](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-1725) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/Rootkitsmm-zz/MS15-061](https://github.com/Rootkitsmm-zz/MS15-061) :  ![starts](https://img.shields.io/github/stars/Rootkitsmm-zz/MS15-061.svg) ![forks](https://img.shields.io/github/forks/Rootkitsmm-zz/MS15-061.svg)

## CVE-2015-1701 (MS15-051)

> Win32k.sys in the kernel-mode drivers in Microsoft Windows Server 2003 SP2, Vista SP2, and Server 2008 SP2 allows local users to gain privileges via a crafted application, as exploited in the wild in April 2015, aka "Win32k Elevation of Privilege Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-051](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-051) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-1701](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-1701) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/hfiref0x/CVE-2015-1701](https://github.com/hfiref0x/CVE-2015-1701) :  ![starts](https://img.shields.io/github/stars/hfiref0x/CVE-2015-1701.svg) ![forks](https://img.shields.io/github/forks/hfiref0x/CVE-2015-1701.svg)

## CVE-2015-0062 (MS15-015)

> Microsoft Windows Server 2008 R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allow local users to gain privileges via a crafted application that leverages incorrect impersonation handling in a process that uses the SeAssignPrimaryTokenPrivilege privilege, aka "Windows Create Process Elevation of Privilege Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-015](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-015) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-0062](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-0062) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2015-0057 (MS15-010)

> win32k.sys in the kernel-mode drivers in Microsoft Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability."

- **Analyse**
  - https://xz.aliyun.com/t/4549
  - https://paper.seebug.org/1439/
  - https://www.anquanke.com/post/id/163973
  - https://blog.csdn.net/qq_35713009/article/details/102921859
- **PoC**
  - https://www.exploit-db.com/exploits/39035
- **Exp**
  - https://www.exploit-db.com/exploits/37098
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-0057](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-0057) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/55-AA/CVE-2015-0057](https://github.com/55-AA/CVE-2015-0057) :  ![starts](https://img.shields.io/github/stars/55-AA/CVE-2015-0057.svg) ![forks](https://img.shields.io/github/forks/55-AA/CVE-2015-0057.svg)

## CVE-2015-0003 (MS15-010)

> win32k.sys in the kernel-mode drivers in Microsoft Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows local users to gain privileges or cause a denial of service (NULL pointer dereference) via a crafted application, aka "Win32k Elevation of Privilege Vulnerability."

- **Analyse**
  - https://www.shuzhiduo.com/A/Vx5M1WrL5N/
  - https://www.cnblogs.com/flycat-2016/p/5452929.html
  - https://www.fireeye.com/blog/threat-research/2015/07/dyre_banking_trojan.html
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-010](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-010) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-0003](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-0003) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2015-0002 (MS15-001)

> The AhcVerifyAdminContext function in ahcache.sys in the Application Compatibility component in Microsoft Windows 7 SP1, Windows Server 2008 R2 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 does not verify that an impersonation token is associated with an administrative account, which allows local users to gain privileges by running AppCompatCache.exe with a crafted DLL file, aka MSRC ID 20544 or "Microsoft Application Compatibility Infrastructure Elevation of Privilege Vulnerability."

- **Analyse**
  - https://googleprojectzero.blogspot.com/2015/02/a-tokens-tale_9.html
  - http://www.vuln.cn/6702
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-001](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS15-001) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-0002](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2015-0002) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

# 2014

## CVE-2014-6324 (MS14-068)

> The Kerberos Key Distribution Center (KDC) in Microsoft Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, and Windows Server 2012 Gold and R2 allows remote authenticated domain users to obtain domain administrator privileges via a forged signature in a ticket, as exploited in the wild in November 2014, aka "Kerberos Checksum Vulnerability."

- **Analyse**
  - https://naykcin.top/2020/01/12/ms14068/
  - https://www.cnblogs.com/feizianquan/p/11760564.html
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS14-068](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS14-068) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/ianxtianxt/MS14-068](https://github.com/ianxtianxt/MS14-068) :  ![starts](https://img.shields.io/github/stars/ianxtianxt/MS14-068.svg) ![forks](https://img.shields.io/github/forks/ianxtianxt/MS14-068.svg)

## CVE-2014-6321 (MS14-066)

> Schannel in Microsoft Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows remote attackers to execute arbitrary code via crafted packets, aka "Microsoft Schannel Remote Code Execution Vulnerability."

- **Analyse**
  - http://bobao.360.cn/learning/detail/114.html
  - https://wooyun.js.org/drops/CVE-2014-6321%20schannel%E5%A0%86%E6%BA%A2%E5%87%BA%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90.html
  - https://www.freebuf.com/vuls/52110.html
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS14-066](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS14-066) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/anexia-it/winshock-test](https://github.com/anexia-it/winshock-test) :  ![starts](https://img.shields.io/github/stars/anexia-it/winshock-test.svg) ![forks](https://img.shields.io/github/forks/anexia-it/winshock-test.svg)

## CVE-2014-4113 (MS14-058)

> win32k.sys in the kernel-mode drivers in Microsoft Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows local users to gain privileges via a crafted application, as exploited in the wild in October 2014, aka "Win32k.sys Elevation of Privilege Vulnerability."

- **Analyse**
  - https://xz.aliyun.com/t/4456
  - https://b2ahex.github.io/blog/2017/06/13/4113%E5%88%86%E6%9E%90/index.html
  - https://www.anquanke.com/post/id/84477
  - https://bbs.pediy.com/thread-198194.htm
  - https://wooyun.js.org/drops/CVE-2014-4113%E6%BC%8F%E6%B4%9E%E5%88%A9%E7%94%A8%E8%BF%87%E7%A8%8B%E5%88%86%E6%9E%90.html
  - http://www.netfairy.net/?post=209
- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2014-4113](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2014-4113) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/sam-b/CVE-2014-4113](https://github.com/sam-b/CVE-2014-4113) :  ![starts](https://img.shields.io/github/stars/sam-b/CVE-2014-4113.svg) ![forks](https://img.shields.io/github/forks/sam-b/CVE-2014-4113.svg)
  - [https://github.com/nsxz/Exploit-CVE-2014-4113](https://github.com/nsxz/Exploit-CVE-2014-4113) :  ![starts](https://img.shields.io/github/stars/nsxz/Exploit-CVE-2014-4113.svg) ![forks](https://img.shields.io/github/forks/nsxz/Exploit-CVE-2014-4113.svg)
  - [https://github.com/johnjohnsp1/CVE-2014-4113](https://github.com/johnjohnsp1/CVE-2014-4113) :  ![starts](https://img.shields.io/github/stars/johnjohnsp1/CVE-2014-4113.svg) ![forks](https://img.shields.io/github/forks/johnjohnsp1/CVE-2014-4113.svg)
  - [https://github.com/wikiZ/cve-2014-4113](https://github.com/wikiZ/cve-2014-4113) :  ![starts](https://img.shields.io/github/stars/wikiZ/cve-2014-4113.svg) ![forks](https://img.shields.io/github/forks/wikiZ/cve-2014-4113.svg)

## CVE-2014-4076 (MS14-070)

> Microsoft Windows Server 2003 SP2 allows local users to gain privileges via a crafted IOCTL call to (1) tcpip.sys or (2) tcpip6.sys, aka "TCP/IP Elevation of Privilege Vulnerability."

- **Analyse**
  - https://bbs.pediy.com/thread-198600.htm
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS14-070](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS14-070) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2014-4076](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2014-4076) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/dev-zzo/exploits-nt-privesc/MS14-070](https://github.com/dev-zzo/exploits-nt-privesc/MS14-070) :  ![starts](https://img.shields.io/github/stars/dev-zzo/exploits-nt-privesc.svg) ![forks](https://img.shields.io/github/forks/dev-zzo/exploits-nt-privesc.svg)
  - [https://github.com/fungoshacks/CVE-2014-4076](https://github.com/fungoshacks/CVE-2014-4076) :  ![starts](https://img.shields.io/github/stars/fungoshacks/CVE-2014-4076.svg) ![forks](https://img.shields.io/github/forks/fungoshacks/CVE-2014-4076.svg)

## CVE-2014-1767 (MS14-040)

> Double free vulnerability in the Ancillary Function Driver (AFD) in afd.sys in the kernel-mode drivers in Microsoft Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows local users to gain privileges via a crafted application, aka "Ancillary Function Driver Elevation of Privilege Vulnerability."

- **Analyse**
  - https://xz.aliyun.com/t/6770
  - https://www.bbsmax.com/A/E35p6R28zv/
- **Exp**
  - https://www.exploit-db.com/exploits/39446/
  - https://www.exploit-db.com/exploits/39525/
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS14-040](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS14-040) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2014-1767](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2014-1767) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

# 2013

## CVE-2013-5065 (MS14-002)

> NDProxy.sys in the kernel in Microsoft Windows XP SP2 and SP3 and Server 2003 SP2 allows local users to gain privileges via a crafted application, as exploited in the wild in November 2013.

- **Analyse**
  - https://bbs.pediy.com/thread-182135.htm
- **Exp**
  - https://www.exploit-db.com/exploits/37732/
  - [https://github.com/dev-zzo/exploits-nt-privesc/tree/master/MS14-002](https://github.com/dev-zzo/exploits-nt-privesc/tree/master/MS14-002) :  ![starts](https://img.shields.io/github/stars/dev-zzo/exploits-nt-privesc.svg) ![forks](https://img.shields.io/github/forks/dev-zzo/exploits-nt-privesc.svg)
  - [https://github.com/Friarfukd/RobbinHood](https://github.com/Friarfukd/RobbinHood) :  ![starts](https://img.shields.io/github/stars/Friarfukd/RobbinHood.svg) ![forks](https://img.shields.io/github/forks/Friarfukd/RobbinHood.svg)

## CVE-2013-1345 (MS13-053)

> win32k.sys in the kernel-mode drivers in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows Server 2012, and Windows RT does not properly handle objects in memory, which allows local users to gain privileges via a crafted application, aka "Win32k Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS13-053](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS13-053) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2013-1345](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2013-1345) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2013-1332 (MS13-046)

> dxgkrnl.sys (aka the DirectX graphics kernel subsystem) in the kernel-mode drivers in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows Server 2012, and Windows RT does not properly handle objects in memory, which allows local users to gain privileges via a crafted application, aka "DirectX Graphics Kernel Subsystem Double Fetch Vulnerability."

- **Analyse**
  - https://www.anquanke.com/vul/id/1045064
  - http://www.91ri.org/6708.html
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS13-046](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS13-046) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2013-1332](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2013-1332) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2013-1300 (MS13-053)

> win32k.sys in the kernel-mode drivers in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows Server 2012, and Windows RT does not properly handle objects in memory, which allows local users to gain privileges via a crafted application, aka "Win32k Memory Allocation Vulnerability."

- **Analyse**
  - https://labs.mwrinfosecurity.com/blog/2013/09/06/mwr-labs-pwn2own-2013-write-up---kernel-exploit/
- **Exp**
  - [https://github.com/Meatballs1/cve-2013-1300](https://github.com/Meatballs1/cve-2013-1300) :  ![starts](https://img.shields.io/github/stars/Meatballs1/cve-2013-1300.svg) ![forks](https://img.shields.io/github/forks/Meatballs1/cve-2013-1300.svg)

## CVE-2013-0008 (MS13-005)

> win32k.sys in the kernel-mode drivers in Microsoft Windows Vista SP2, Windows Server 2008 SP2, R2, and R2 SP1, Windows 7 Gold and SP1, Windows 8, Windows Server 2012, and Windows RT does not properly handle window broadcast messages, which allows local users to gain privileges via a crafted application, aka "Win32k Improper Message Handling Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS13-005](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS13-005) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2013-0008](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2013-0008) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

# 2012

##  CVE-2012-0217 (MS12-042)

> The x86-64 kernel system-call functionality in Xen 4.1.2 and earlier, as used in Citrix XenServer 6.0.2 and earlier and other products; Oracle Solaris 11 and earlier; illumos before r13724; Joyent SmartOS before 20120614T184600Z; FreeBSD before 9.0-RELEASE-p3; NetBSD 6.0 Beta and earlier; Microsoft Windows Server 2008 R2 and R2 SP1 and Windows 7 Gold and SP1; and possibly other operating systems, when running on an Intel processor, incorrectly uses the sysret path in cases where a certain address is not a canonical address, which allows local users to gain privileges via a crafted application. NOTE: because this issue is due to incorrect use of the Intel specification, it should have been split into separate identifiers; however, there was some value in preserving the original mapping of the multi-codebase coordinated-disclosure effort to a single identifier.

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS12-042](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS12-042) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2012-0217](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2012-0217) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2012-0152 (MS12-020)

> The Remote Desktop Protocol (RDP) service in Microsoft Windows Server 2008 R2 and R2 SP1 and Windows 7 Gold and SP1 allows remote attackers to cause a denial of service (application hang) via a series of crafted packets, aka "Terminal Server Denial of Service Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS12-020](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS12-020) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/rutvijjethwa/RDP_jammer](https://github.com/rutvijjethwa/RDP_jammer) :  ![starts](https://img.shields.io/github/stars/rutvijjethwa/RDP_jammer.svg) ![forks](https://img.shields.io/github/forks/rutvijjethwa/RDP_jammer.svg)
  - [https://github.com/anmolksachan/MS12-020](https://github.com/anmolksachan/MS12-020) :  ![starts](https://img.shields.io/github/stars/anmolksachan/MS12-020.svg) ![forks](https://img.shields.io/github/forks/anmolksachan/MS12-020.svg)

## CVE-2012-0002 (MS12-020)

> The Remote Desktop Protocol (RDP) implementation in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2, R2, and R2 SP1, and Windows 7 Gold and SP1 does not properly process packets in memory, which allows remote attackers to execute arbitrary code by sending crafted RDP packets triggering access to an object that (1) was not properly initialized or (2) is deleted, aka "Remote Desktop Protocol Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS12-020](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS12-020) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)

# 2011

## CVE-2011-2005 (MS11-080)

> afd.sys in the Ancillary Function Driver in Microsoft Windows XP SP2 and SP3 and Server 2003 SP2 does not properly validate user-mode input passed to kernel mode, which allows local users to gain privileges via a crafted application, aka "Ancillary Function Driver Elevation of Privilege Vulnerability."

- **Analyse**
  - http://qq53.github.io/1500623869.html
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS11-080](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS11-080) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2011-2005](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2011-2005) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2011-1974 (MS11-062)

> NDISTAPI.sys in the NDISTAPI driver in Remote Access Service (RAS) in Microsoft Windows XP SP2 and SP3 and Windows Server 2003 SP2 does not properly validate user-mode input, which allows local users to gain privileges via a crafted application, aka "NDISTAPI Elevation of Privilege Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS11-062](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS11-062) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2011-1974](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2011-1974) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2011-1249 (MS11-046)

> The Ancillary Function Driver (AFD) in afd.sys in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP1 and SP2, Windows Server 2008 Gold, SP2, R2, and R2 SP1, and Windows 7 Gold and SP1 does not properly validate user-mode input, which allows local users to gain privileges via a crafted application, aka "Ancillary Function Driver Elevation of Privilege Vulnerability."

- **Analyse**
  - github https://github.com/Madusanka99/OHTS/blob/master/IT16075504%20-OHTS%20Report.pdf
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS11-046](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS11-046) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2011-1249](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2011-1249) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2011-1237 (MS11-034)

> Use-after-free vulnerability in win32k.sys in the kernel-mode drivers in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP1 and SP2, Windows Server 2008 Gold, SP2, R2, and R2 SP1, and Windows 7 Gold and SP1 allows local users to gain privileges via a crafted application that leverages incorrect driver object management, a different vulnerability than other "Vulnerability Type 1" CVEs listed in MS11-034, aka "Win32k Use After Free Vulnerability."

- **Analyse**
  - https://lse.epita.fr/lse-summer-week-2013/slides/lse-summer-week-2013-26-Bruno%20Pujos-A%20Look%20into%20the%20Windows%20Kernel.pdf
- **Exp**
  - [https://github.com/BrunoPujos/CVE-2011-1237](https://github.com/BrunoPujos/CVE-2011-1237) :  ![starts](https://img.shields.io/github/stars/BrunoPujos/CVE-2011-1237.svg) ![forks](https://img.shields.io/github/forks/BrunoPujos/CVE-2011-1237.svg)

## CVE-2011-0045 (MS11-011)

> The Trace Events functionality in the kernel in Microsoft Windows XP SP3 does not properly perform type conversion, which causes integer truncation and insufficient memory allocation and triggers a buffer overflow, which allows local users to gain privileges via a crafted application, related to WmiTraceMessageVa, aka "Windows Kernel Integer Truncation Vulnerability."

- **Analyse**
  - https://blog.csdn.net/QEver/article/details/6227415
  - https://www.geek-share.com/detail/2510409740.html
  - https://bbs.pediy.com/thread-130487.htm
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS11-011](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS11-011) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)

# 2010

## CVE-2010-3338 (MS10-092)

> The Windows Task Scheduler in Microsoft Windows Vista SP1 and SP2, Windows Server 2008 Gold, SP2, and R2, and Windows 7 does not properly determine the security context of scheduled tasks, which allows local users to gain privileges via a crafted application, aka "Task Scheduler Vulnerability." NOTE: this might overlap CVE-2010-3888.

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-092](https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-092) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2010-3338](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2010-3338) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

  
## CVE-2010-2730 (MS10-065)

> Buffer overflow in Microsoft Internet Information Services (IIS) 7.5, when FastCGI is enabled, allows remote attackers to execute arbitrary code via crafted headers in a request, aka "Request Header Buffer Overflow Vulnerability."

- **Analyse**
  - https://blog.51cto.com/gnaw0725/1635204
  - https://www.youtube.com/watch?v=23Mtx1F_CM0
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-065](https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-065) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)

## CVE-2010-2554 (MS10-059)

> The Tracing Feature for Services in Microsoft Windows Vista SP1 and SP2, Windows Server 2008 Gold, SP2, and R2, and Windows 7 has incorrect ACLs on its registry keys, which allows local users to gain privileges via vectors involving a named pipe and impersonation, aka "Tracing Registry Key ACL Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-059](https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-059) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)

## CVE-2010-1897 (MS10-048)

> The Windows kernel-mode drivers in win32k.sys in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP1 and SP2, Windows Server 2008 Gold, SP2, and R2, and Windows 7 do not properly validate pseudo-handle values in callback parameters during window creation, which allows local users to gain privileges via a crafted application, aka "Win32k Window Creation Vulnerability."

- **Exp**
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2010-1897](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2010-1897) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2010-1887 (MS10-048)

> The Windows kernel-mode drivers in win32k.sys in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP1 and SP2, Windows Server 2008 Gold, SP2, and R2, and Windows 7 do not properly validate an unspecified system-call argument, which allows local users to cause a denial of service (system hang) via a crafted application, aka "Win32k Bounds Checking Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-048](https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-048) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)

## CVE-2010-0270 (MS10-020)

> he SMB client in Microsoft Windows Server 2008 R2 and Windows 7 does not properly validate fields in SMB transaction responses, which allows remote SMB servers and man-in-the-middle attackers to execute arbitrary code or cause a denial of service (memory corruption and reboot) via a crafted (1) SMBv1 or (2) SMBv2 response, aka "SMB Client Transaction Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-012/MS10-020.py](https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-012/MS10-020.py) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2010-0270](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2010-0270) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2010-0233 (MS10-015)

> Double free vulnerability in the kernel in Microsoft Windows 2000 SP4, XP SP2 and SP3, Server 2003 SP2, Vista Gold, SP1, and SP2, and Server 2008 Gold and SP2 allows local users to gain privileges via a crafted application, aka "Windows Kernel Double Free Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS10-015](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS10-015) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2010-0233](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2010-0233) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2010-0020 (MS10-012)

> The SMB implementation in the Server service in Microsoft Windows 2000 SP4, Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista Gold, SP1, and SP2, Windows Server 2008 Gold, SP2, and R2, and Windows 7 does not properly validate request fields, which allows remote authenticated users to execute arbitrary code via a malformed request, aka "SMB Pathname Overflow Vulnerability."

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-012/MS10-012.txt](https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS10-012/MS10-012.txt) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)

# 2009

## CVE-2009-2532 (MS09-050)

> Microsoft Windows Vista Gold, SP1, and SP2, Windows Server 2008 Gold and SP2, and Windows 7 RC do not properly process the command value in an SMB Multi-Protocol Negotiate Request packet, which allows remote attackers to execute arbitrary code via a crafted SMBv2 packet to the Server service, aka "SMBv2 Command Value Vulnerability."

- **Analyse**
  - https://www.giantbranch.cn/2017/08/26/Educatedscholar%E5%88%A9%E7%94%A8%E7%9A%84%E6%BC%8F%E6%B4%9Ems09-050%E5%88%86%E6%9E%90%E5%8F%8A%E5%85%B6%E5%88%A9%E7%94%A8%E7%9A%84shellcode%E5%88%86%E6%9E%90%E5%8F%8A%E4%B8%8Emsf%E5%88%A9%E7%94%A8%E5%AF%B9%E6%AF%94/
  - https://zhuanlan.zhihu.com/p/27155431
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS09-050](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS09-050) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2009-2532](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2009-2532) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/mazding/ms09050](https://github.com/mazding/ms09050) :  ![starts](https://img.shields.io/github/stars/mazding/ms09050.svg) ![forks](https://img.shields.io/github/forks/mazding/ms09050.svg)

## CVE-2009-1535 (MS09-020)

> The WebDAV extension in Microsoft Internet Information Services (IIS) 5.1 and 6.0 allows remote attackers to bypass URI-based protection mechanisms, 
> and list folders or read, create, or modify files, via a %c0%af (Unicode / character) at an arbitrary position in the URI, 
> as demonstrated by inserting %c0%af into a "/protected/" initial pathname component to bypass the password protection on the protected\ folder, 
> aka "IIS 5.1 and 6.0 WebDAV Authentication Bypass Vulnerability," a different vulnerability than CVE-2009-1122.

- **Analyse**
  - https://www.twblogs.net/a/5b96d7fd2b717750bda69ce9
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS09-020](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS09-020) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2009-1535](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2009-1535) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2009-0229 (MS09-022)

> The Windows Printing Service in Microsoft Windows 2000 SP4, XP SP2 and SP3, Server 2003 SP2, Vista Gold, SP1, and SP2, and Server 2008 SP2 allows local users to read arbitrary files via a crafted separator page, aka "Print Spooler Read File Vulnerability."

- **PoC**
  - [https://github.com/zveriu/CVE-2009-0229-PoC](https://github.com/zveriu/CVE-2009-0229-PoC) :  ![starts](https://img.shields.io/github/stars/zveriu/CVE-2009-0229-PoC.svg) ![forks](https://img.shields.io/github/forks/zveriu/CVE-2009-0229-PoC.svg)

## CVE-2009-0079 (MS09-012)

> The RPCSS service in Microsoft Windows XP SP2 and SP3 and Server 2003 SP1 and SP2 does not properly implement isolation among a set of distinct processes that (1) all run under the NetworkService account or (2) all run under the LocalService account, which allows local users to gain privileges by accessing the resources of one of the processes, aka "Windows RPCSS Service Isolation Vulnerability."

- **Analyse**
  - https://xz.aliyun.com/t/8091
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS09-012](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS09-012) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2009-0079](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2009-0079) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

# 2008

## CVE-2008-4250 (MS08-067)

> The Server service in Microsoft Windows 2000 SP4, XP SP2 and SP3, Server 2003 SP1 and SP2, Vista Gold and SP1, Server 2008, and 7 Pre-Beta allows remote attackers to execute arbitrary code via a crafted RPC request that triggers the overflow during path canonicalization, as exploited in the wild by Gimmiv.A in October 2008, aka "Server Service Vulnerability."

- **Analyse**
  - https://bbs.pediy.com/thread-251219.htm
  - https://www.jianshu.com/p/d086eb1ab0a6
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS08-067](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS08-067) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2008-4250](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2008-4250) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  - [https://github.com/andyacer/ms08_067](https://github.com/andyacer/ms08_067) :  ![starts](https://img.shields.io/github/stars/andyacer/ms08_067.svg) ![forks](https://img.shields.io/github/forks/andyacer/ms08_067.svg)
  - [https://github.com/dnkls/ms08-067automation](https://github.com/dnkls/ms08-067automation) :  ![starts](https://img.shields.io/github/stars/dnkls/ms08-067automation.svg) ![forks](https://img.shields.io/github/forks/dnkls/ms08-067automation.svg)

## CVE-2008-4037 (MS08-068)

> Microsoft Windows 2000 Gold through SP4, XP Gold through SP3, Server 2003 SP1 and SP2, Vista Gold and SP1, and Server 2008 allows remote SMB servers to execute arbitrary code on a client machine by replaying the NTLM credentials of a client user, as demonstrated by backrush, aka "SMB Credential Reflection Vulnerability." NOTE: some reliable sources report that this vulnerability exists because of an insufficient fix for CVE-2000-0834.

- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS08-068](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS08-068) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2008-4037](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2008-4037) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

## CVE-2008-3464 (MS08-066)

> afd.sys in the Ancillary Function Driver (AFD) component in Microsoft Windows XP SP2 and SP3 and Windows Server 2003 SP1 and SP2 does not properly validate input sent from user mode to the kernel, which allows local users to gain privileges via a crafted application, as demonstrated using crafted pointers and lengths that bypass intended ProbeForRead and ProbeForWrite restrictions, aka "AFD Kernel Overwrite Vulnerability."

- **Analyse**
  - https://bbs.pediy.com/thread-74811.htm
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS08-066](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS08-066) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2008-3464](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2008-3464) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  

## CVE-2008-1084 (MS08-025)

> Unspecified vulnerability in the kernel in Microsoft Windows 2000 SP4, XP SP2, Server 2003 SP1 and SP2, through Vista SP1, and Server 2008 allows local users to execute arbitrary code via unknown vectors related to improper input validation. NOTE: it was later reported that one affected function is NtUserFnOUTSTRING in win32k.sys.

- **Analyse**
  - github https://github.com/lyshark/Windows-exploits/blob/master/Windows%20%E5%86%85%E6%A0%B8%E6%BC%8F%E6%B4%9E%20ms08025%20%E5%88%86%E6%9E%90.7z
  - https://bbs.pediy.com/thread-63099.htm
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS08-025](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS08-025) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2008-1084](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2008-1084) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

# 2007

## CVE-2007-0843

> The ReadDirectoryChangesW API function on Microsoft Windows 2000, XP, Server 2003, and Vista does not check permissions for child objects, which allows local users to bypass permissions by opening a directory with LIST (READ) access and using ReadDirectoryChangesW to monitor changes of files that do not have LIST permissions, which can be leveraged to determine filenames, access times, and other sensitive information.

- **Exp**
  - [https://github.com/z3APA3A/spydir](https://github.com/z3APA3A/spydir) :  ![starts](https://img.shields.io/github/stars/z3APA3A/spydir.svg) ![forks](https://img.shields.io/github/forks/z3APA3A/spydir.svg)

## CVE-2007-0038

> Stack-based buffer overflow in the animated cursor code in Microsoft Windows 2000 SP4 through Vista allows remote attackers to execute arbitrary code or cause a denial of service (persistent reboot) via a large length value in the second (or later) anih block of a RIFF .ANI, cur, or .ico file, which results in memory corruption when processing cursors, animated cursors, and icons, a variant of CVE-2005-0416, as originally demonstrated using Internet Explorer 6 and 7. NOTE: this might be a duplicate of CVE-2007-1765; if so, then CVE-2007-0038 should be preferred.

- **PoC**
  - [https://github.com/Axua/CVE-2007-0038](https://github.com/Axua/CVE-2007-0038) :  ![starts](https://img.shields.io/github/stars/Axua/CVE-2007-0038.svg) ![forks](https://img.shields.io/github/forks/Axua/CVE-2007-0038.svg)
  - [https://github.com/Cheesse/cve2007-0038x64](https://github.com/Cheesse/cve2007-0038x64) :  ![starts](https://img.shields.io/github/stars/Cheesse/cve2007-0038x64.svg) ![forks](https://img.shields.io/github/forks/Cheesse/cve2007-0038x64.svg)

# 2006

##  CVE-2006-3439 (MS06-040)

> Buffer overflow in the Server Service in Microsoft Windows 2000 SP4, XP SP1 and SP2, and Server 2003 SP1 allows remote attackers, including anonymous users, to execute arbitrary code via a crafted RPC message, a different vulnerability than CVE-2006-1314.

- **Analyse**
  - http://www.atomsec.org/%E5%AE%89%E5%85%A8/ms06-040cve-2006-3439%E9%9D%99%E6%80%81%E5%88%86%E6%9E%90/
  - https://bbs.pediy.com/thread-266157.htm
- **Exp**
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS06-040](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS06-040) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2006-3439](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2006-3439) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)



# 2005

## CVE-2005-1983 (MS05-039)

> Stack-based buffer overflow in the Plug and Play (PnP) service for Microsoft Windows 2000 and Windows XP Service Pack 1 allows remote attackers to execute arbitrary code via a crafted packet, and local users to gain privileges via a malicious application, as exploited by the Zotob (aka Mytob) worm.

- **Analyse**
  
  - https://blog.csdn.net/tomqq/article/details/1951128
- **Exp**
  
  - [https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS05-039](https://github.com/SecWiki/windows-kernel-exploits/tree/master/MS05-039) :  ![starts](https://img.shields.io/github/stars/SecWiki/windows-kernel-exploits.svg) ![forks](https://img.shields.io/github/forks/SecWiki/windows-kernel-exploits.svg)
  
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2005-1983](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2005-1983) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)
  

# 2003

## CVE-2003-0352 (MS03-026)

> Buffer overflow in a certain DCOM interface for RPC in Microsoft Windows NT 4.0, 2000, XP, and Server 2003 allows remote attackers to execute arbitrary code via a malformed message, as exploited by the Blaster/MSblast/LovSAN and Nachi/Welchia worms.

- **Analyse**
  - https://blog.51cto.com/executer/2174779
- **Exp**
  - [https://github.com/abatchy17/WindowsExploits/tree/master/MS03-026](https://github.com/abatchy17/WindowsExploits/tree/master/MS03-026) :  ![starts](https://img.shields.io/github/stars/abatchy17/WindowsExploits.svg) ![forks](https://img.shields.io/github/forks/abatchy17/WindowsExploits.svg)
  - [https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2003-0352](https://github.com/Ascotbe/Kernelhub/tree/master/CVE-2003-0352) :  ![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) ![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg)

# 2000

## CVE-2000-0979

> File and Print Sharing service in Windows 95, Windows 98, and Windows Me does not properly check the password for a file share, which allows remote attackers to bypass share access controls by sending a 1-byte password that matches the first character of the real password, aka the "Share Level Password" vulnerability.

- **Exp**
  - [https://github.com/Z6543/CVE-2000-0979](https://github.com/Z6543/CVE-2000-0979) :  ![starts](https://img.shields.io/github/stars/Z6543/CVE-2000-0979.svg) ![forks](https://img.shields.io/github/forks/Z6543/CVE-2000-0979.svg)

