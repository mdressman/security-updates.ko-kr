---
TOCTitle: 'MS09-OCT'
Title: 2009 년 10 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-oct'
ms:contentKeyID: 61230718
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-oct(v=Security.10)'
---


2009 년 10 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2009년 10월 14일 수요일 | 업데이트된 날짜: 2010년 6월 23일 수요일

**버전:** 4.2

이 공지 요약 목록에는 2009년 10월 발표된 보안 공지가 포함되어 있습니다.

2009년 10월 공지 발표와 함께 이 공지 요약이 2009년 10월 8일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2009년 10월 14일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [10월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407488&culture=en-us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

요약
----

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어 및 다운로드 위치**를 참조하십시오.

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >공지 번호</th>
<th style="border:1px solid black;" >공지 제목 및 용약</th>
<th style="border:1px solid black;" >최대 심각도 및 취약점 영향</th>
<th style="border:1px solid black;" >다시 시작 요구 사항</th>
<th style="border:1px solid black;" >영향을 받는 소프트웨어</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-050">MS09-050</a></td>
<td style="border:1px solid black;"><strong>SMBv2의 취약점으로 인한 원격 코드 실행 문제점(975517)</strong><br />
<br />
이 보안 업데이트는 SMBv2(Server Message Block Version 2)에서 발견되어 공개적으로 보고된 취약점 1건과 비공개적으로 보고된 취약점 2건을 해결합니다. 가장 위험한 취약점은 공격자가 서버 서비스를 실행하는 컴퓨터로 특수하게 조작된 SMB 패킷을 전송할 경우 원격 코드 실행을 허용할 수 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다. 인터넷과 연결되는 시스템의 경우, 필요한 포트만 최소한으로 열어 두는 것이 안전합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-051">MS09-051</a></td>
<td style="border:1px solid black;"><strong>Windows Media Runtime의 취약점으로 인한 원격 코드 실행 문제점(975682)</strong><br />
<br />
이 보안 업데이트는 Windows Media Runtime에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 미디어 파일을 열거나, 웹 사이트 또는 웹 콘텐츠를 제공하는 응용 프로그램으로부터 특수하게 조작된 스트리밍 콘텐츠를 받을 경우 원격 코드 실행이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-052">MS09-052</a></td>
<td style="border:1px solid black;"><strong>Windows Media Player의 취약점으로 인한 원격 코드 실행 문제점(974112)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows Media Player의 취약점을 해결합니다. 이 취약점으로 인해 Windows Media Player 6.4를 사용하여 특수하게 조작된 ASF 파일을 재생할 경우 원격 코드 실행이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-054">MS09-054</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(974455)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에 대해 비공개적으로 보고된 취약점 3건과 공개된 취약점 1건을 해결합니다. 이 취약점들은 모두 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. WPF(Windows Presentation Foundation) 플러그인을 비활성화하지 않고 실행하는 Firefox 사용자도 이 보안 업데이트를 적용해야 합니다. 이 문제점에 대한 자세한 내용은 HTML 구성 요소 처리 취약점(CVE-2009-2529)에 대한 FAQ 항목을 참조하십시오.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-055">MS09-055</a></td>
<td style="border:1px solid black;"><strong>ActiveX 킬(Kill) 비트 누적 보안 업데이트(973525)</strong><br />
<br />
이 보안 업데이트는 현재 악용되고 있는 ActiveX 컨트롤에서 비공개적으로 보고된 취약점 1건을 해결합니다. 취약한 버전의 Microsoft ATL(액티브 템플릿 라이브러리)을 사용하여 컴파일된 ActiveX 컨트롤의 취약점으로 인해 사용자가 Internet Explorer로 ActiveX 컨트롤을 인스턴스화하는 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-060">MS09-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office용 Microsoft ATL(액티브 템플릿 라이브러리) ActiveX 컨트롤의 취약점으로 인한 원격 코드 실행 문제점(973965)</strong><br />
<br />
이 보안 업데이트는 취약한 버전의 Microsoft ATL(액티브 템플릿 라이브러리)을 사용하여 컴파일된 Microsoft Office용 ActiveX 컨트롤에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 구성 요소 또는 컨트롤을 로드하는 경우 원격 코드 실행이 발생할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-061">MS09-061</a></td>
<td style="border:1px solid black;"><strong>Microsoft .NET 공용 언어 런타임의 취약점으로 인한 원격 코드 실행 문제점(974378)</strong><br />
<br />
이 보안 업데이트는 Microsoft .NET Framework 및 Microsoft Silverlight에서 비공개적으로 보고된 취약점 3건을 해결합니다. 사용자가 XBAP(XAML 브라우저 응용 프로그램) 또는 Silverlight 응용 프로그램을 실행할 수 있는 웹 브라우저를 사용하여 특수하게 조작된 웹 페이지를 보거나, 공격자가 특수하게 조작한 Microsoft .NET 응용 프로그램을 실행하도록 사용자를 유인하는 데 성공할 경우 이 취약점으로 인해 클라이언트 시스템에 원격 코드 실행이 발생할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 서버에서 ASP.NET 페이지 처리를 허용하고 공격자가 해당 서버에 특수하게 조작한 ASP.NET 페이지를 성공적으로 업로드하여 실행할 경우 이 취약점으로 인해 IIS를 실행하는 서버 시스템에 원격 코드 실행이 발생할 수 있습니다. 이러한 경우는 웹 호스팅 시나리오에서 발생할 수 있습니다. 악의적이지 않은 Microsoft .NET 응용 프로그램, Silverlight 응용 프로그램, XBAP 및 ASP.NET 페이지는 이 취약점으로 인해 공격을 받을 위험이 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-062">MS09-062</a></td>
<td style="border:1px solid black;"><strong>GDI+의 취약점으로 인한 원격 코드 실행 문제점(957488)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows GDI+에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 이 취약점으로 인해 사용자가 영향을 받는 소프트웨어를 사용하여 특수하게 조작된 이미지를 보거나 특수하게 조작된 콘텐츠가 포함된 웹사이트를 탐색할 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer,<br />
Microsoft .NET Framework,<br />
Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft 개발자 도구,<br />
Microsoft Forefront</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-053">MS09-053</a></td>
<td style="border:1px solid black;"><strong>IIS(인터넷 정보 서비스) FTP 서비스의 취약점으로 인한 원격 코드 실행 문제점(975254)</strong><br />
<br />
이 보안 업데이트는 Microsoft IIS(인터넷 정보 서비스) 5.0, Microsoft IIS(인터넷 정보 서비스) 5.1, Microsoft IIS(인터넷 정보 서비스) 6.0 및 Microsoft IIS(인터넷 정보 서비스) 7.0의 FTP 서비스에 대해 공개적으로 보고된 취약점 2건을 해결합니다. IIS 7.0에서는 FTP 서비스 6.0만 영향을 받습니다. 이 취약점으로 인해 IIS 5.0에서 FTP 서비스를 실행하고 있는 시스템에 원격 코드 실행(RCE)이 발생하거나 IIS 5.0, IIS 5.1, IIS 6.0 또는 IIS 7.0에서 FTP 서비스를 실행하고 있는 시스템에 서비스 거부(DoS)가 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-056">MS09-056</a></td>
<td style="border:1px solid black;"><strong>Windows CryptoAPI의 취약점으로 인한 스푸핑 허용 문제점(974571)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 공개적으로 보고된 취약점 2건을 해결합니다. 최종 사용자가 인증에 사용한 인증서에 공격자가 액세스할 수 있는 경우 이 취약점으로 인해 스푸핑이 허용됩니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
스푸핑</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-057">MS09-057</a></td>
<td style="border:1px solid black;"><strong>인덱싱 서비스의 취약점으로 인한 원격 코드 실행 문제(969059)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 ActiveX 구성 요소에 대한 호출을 통해 인덱싱 서비스를 실행하는 악의적인 웹 페이지를 설정할 경우 원격 코드 실행을 허용할 수 있습니다. 이 호출은 악의적인 URL을 포함할 수 있으며, 취약점을 악용하여 웹 페이지를 검색하는 사용자의 권한으로 클라이언트 시스템에 액세스할 수 있는 권한을 공격자에게 부여합니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-058">MS09-058</a></td>
<td style="border:1px solid black;"><strong>Windows 커널의 취약점으로 인한 권한 상승 문제점(971486)</strong><br />
<br />
이 보안 업데이트는 Windows 커널에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 가장 위험한 취약점은 공격자가 시스템에 로그온하여 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승을 허용할 수 있습니다. 이러한 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-059">MS09-059</a></td>
<td style="border:1px solid black;"><strong>로컬 보안 기관 하위 시스템 서비스의 취약점으로 인한 서비스 거부 문제(975467)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. NTLM 인증 프로세스 중에 공격자가 악의적으로 조작된 패킷을 보낼 경우 이 취약점으로 인해 서비스 거부가 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 공지 제목                                                                                                                 | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                                                                                                                                                                                                                                                                                                 |  
|---------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-050](http://technet.microsoft.com/security/bulletin/ms09-050) | SMBv2의 취약점으로 인한 원격 코드 실행 문제점(975517)                                                                     | [CVE-2009-2526 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2526) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이는 제한적인 서비스 거부 취약점입니다.                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-050](http://technet.microsoft.com/security/bulletin/ms09-050) | SMBv2의 취약점으로 인한 원격 코드 실행 문제점(975517)                                                                     | [CVE-2009-2532 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2532) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-050](http://technet.microsoft.com/security/bulletin/ms09-050) | SMBv2의 취약점으로 인한 원격 코드 실행 문제점(975517)                                                                     | [CVE-2009-3103 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3103) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 악용 코드가 일반에 공개되었습니다.                                                                                                                                                                                                                                                                                                                                        |  
| [MS09-051](http://technet.microsoft.com/security/bulletin/ms09-051) | Windows Media Runtime의 취약점으로 인한 원격 코드 실행 문제점(975682)                                                     | [CVE-2009-0555 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0555) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-051](http://technet.microsoft.com/security/bulletin/ms09-051) | Windows Media Runtime의 취약점으로 인한 원격 코드 실행 문제점(975682)                                                     | [CVE-2009-2525 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2525) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-052](http://technet.microsoft.com/security/bulletin/ms09-052) | Windows Media Player의 취약점으로 인한 원격 코드 실행 문제점(974112)                                                      | [CVE-2009-2527 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2527) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-053](http://technet.microsoft.com/security/bulletin/ms09-053) | IIS(인터넷 정보 서비스) FTP 서비스의 취약점으로 인한 원격 코드 실행 문제점(975254)                                        | [CVE-2009-2521 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2521) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이것은 서비스 거부 취약점입니다. 악용 코드가 일반에 공개되었습니다.                                                                                                                                                                                                                                                                                                       |  
| [MS09-053](http://technet.microsoft.com/security/bulletin/ms09-053) | IIS(인터넷 정보 서비스) FTP 서비스의 취약점으로 인한 원격 코드 실행 문제점(975254)                                        | [CVE-2009-3023 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3023) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 악용 코드가 일반에 공개되었습니다.                                                                                                                                                                                                                                                                                                                                        |  
| [MS09-054](http://technet.microsoft.com/security/bulletin/ms09-054) | Internet Explorer 누적 보안 업데이트(974455)                                                                              | [CVE-2009-1547 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1547) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-054](http://technet.microsoft.com/security/bulletin/ms09-054) | Internet Explorer 누적 보안 업데이트(974455)                                                                              | [CVE-2009-2529 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2529) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-054](http://technet.microsoft.com/security/bulletin/ms09-054) | Internet Explorer 누적 보안 업데이트(974455)                                                                              | [CVE-2009-2530 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2530) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | Microsoft Windows 2000 시스템의 경우 힙 보호를 사용하지 않으면 악용 가능성 인덱스 평가가 [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능으로 증가합니다.                                                                                                                                                              |  
| [MS09-054](http://technet.microsoft.com/security/bulletin/ms09-054) | Internet Explorer 누적 보안 업데이트(974455)                                                                              | [CVE-2009-2531 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2531) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 |                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-055](http://technet.microsoft.com/security/bulletin/ms09-055) | ActiveX 킬(Kill) 비트 누적 보안 업데이트(973525)                                                                          | [CVE-2009-2493 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | 없음                                                                                                  | (이 취약점은 이미 [7월 공지 요약](http://technet.microsoft.com/security/bulletin/ms09-jul)의 악용 가능성 인덱스 평가에 지정되어 있습니다. [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035)에서 처음으로 이 취약점이 해결되었기 때문입니다.) [MS09-060](http://technet.microsoft.com/security/bulletin/ms09-060)에 있는 동일한 CVE 번호도 참조하십시오. |  
| [MS09-056](http://technet.microsoft.com/security/bulletin/ms09-056) | Windows CryptoAPI의 취약점으로 인한 스푸핑 허용 문제점(974571)                                                            | [CVE-2009-2510 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2510) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점은 스푸핑 취약점입니다.                                                                                                                                                                                                                                                                                                                                          |  
| [MS09-056](http://technet.microsoft.com/security/bulletin/ms09-056) | Windows CryptoAPI의 취약점으로 인한 스푸핑 허용 문제점(974571)                                                            | [CVE-2009-2511 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2511) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점은 스푸핑 취약점입니다.                                                                                                                                                                                                                                                                                                                                          |  
| [MS09-057](http://technet.microsoft.com/security/bulletin/ms09-057) | 인덱싱 서비스의 취약점으로 인한 원격 코드 실행 문제(969059)                                                               | [CVE-2009-2507 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2507) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-058](http://technet.microsoft.com/security/bulletin/ms09-058) | Windows 커널의 취약점으로 인한 권한 상승 문제점(971486)                                                                   | [CVE-2009-2515 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2515) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-058](http://technet.microsoft.com/security/bulletin/ms09-058) | Windows 커널의 취약점으로 인한 권한 상승 문제점(971486)                                                                   | [CVE-2009-2516 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2516) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 네트워크 공유를 사용하여 대상을 지정한 경우 이 취약점으로 인해 서비스 거부가 발생할 수 있으며, 로컬에서 로컬 시스템을 대상으로 지정한 경우 이 취약점으로 인해 권한 상승 상태가 발생할 수 있습니다.                                                                                                                                                                        |  
| [MS09-058](http://technet.microsoft.com/security/bulletin/ms09-058) | Windows 커널의 취약점으로 인한 권한 상승 문제점(971486)                                                                   | [CVE-2009-2517 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2517) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이것은 서비스 거부 취약점입니다.                                                                                                                                                                                                                                                                                                                                          |  
| [MS09-059](http://technet.microsoft.com/security/bulletin/ms09-059) | 로컬 보안 기관 하위 시스템 서비스의 취약점으로 인한 서비스 거부 문제점(975467)                                            | [CVE-2009-2524 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2524) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이는 제한적인 서비스 거부 취약점입니다.                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-060](http://technet.microsoft.com/security/bulletin/ms09-060) | Microsoft Office용 Microsoft ATL(액티브 템플릿 라이브러리) ActiveX 컨트롤의 취약점으로 인한 원격 코드 실행 문제점(973965) | [CVE-2009-0901 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | 없음                                                                                                  | (이 취약점은 이미 [7월 공지 요약](http://technet.microsoft.com/security/bulletin/ms09-jul)의 악용 가능성 인덱스 평가에 지정되어 있습니다. 그 이유는 이 취약점이 [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035)에서 처음 해결되었기 때문입니다.)                                                                                                      |  
| [MS09-060](http://technet.microsoft.com/security/bulletin/ms09-060) | Microsoft Office용 Microsoft ATL(액티브 템플릿 라이브러리) ActiveX 컨트롤의 취약점으로 인한 원격 코드 실행 문제점(973965) | [CVE-2009-2493 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | 없음                                                                                                  | (이 취약점은 이미 [7월 공지 요약](http://technet.microsoft.com/security/bulletin/ms09-jul)의 악용 가능성 인덱스 평가에 지정되어 있습니다. [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035)에서 처음으로 이 취약점이 해결되었기 때문입니다.) [MS09-055](http://technet.microsoft.com/security/bulletin/ms09-055)에 있는 동일한 CVE 번호도 참조하십시오. |  
| [MS09-060](http://technet.microsoft.com/security/bulletin/ms09-060) | Microsoft Office용 Microsoft ATL(액티브 템플릿 라이브러리) ActiveX 컨트롤의 취약점으로 인한 원격 코드 실행 문제점(973965) | [CVE-2009-2495 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이는 정보 유출 취약점입니다.                                                                                                                                                                                                                                                                                                                                              |  
| [MS09-061](http://technet.microsoft.com/security/bulletin/ms09-061) | Microsoft .NET 공용 언어 런타임의 취약점으로 인한 원격 코드 실행 문제점(974378)                                           | [CVE-2009-0090 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0090) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-061](http://technet.microsoft.com/security/bulletin/ms09-061) | Microsoft .NET 공용 언어 런타임의 취약점으로 인한 원격 코드 실행 문제점(974378)                                           | [CVE-2009-0091 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0091) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-061](http://technet.microsoft.com/security/bulletin/ms09-061) | Microsoft .NET 공용 언어 런타임의 취약점으로 인한 원격 코드 실행 문제점(974378)                                           | [CVE-2009-2497 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2497) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 인터넷에 영향을 주는 공격 가능성이 있습니다.                                                                                                                                                                                                                                                                                                                              |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | GDI+의 취약점으로 인한 원격 코드 실행 문제점(957488)                                                                      | [CVE-2009-2500 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2500) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | GDI+의 취약점으로 인한 원격 코드 실행 문제점(957488)                                                                      | [CVE-2009-2501 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2501) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | GDI+의 취약점으로 인한 원격 코드 실행 문제점(957488)                                                                      | [CVE-2009-2502 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2502) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | GDI+의 취약점으로 인한 원격 코드 실행 문제점(957488)                                                                      | [CVE-2009-2503 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2503) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | GDI+의 취약점으로 인한 원격 코드 실행 문제점(957488)                                                                      | [CVE-2009-2504 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2504) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | GDI+의 취약점으로 인한 원격 코드 실행 문제점(957488)                                                                      | [CVE-2009-2518 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2518) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | GDI+의 취약점으로 인한 원격 코드 실행 문제점(957488)                                                                      | [CVE-2009-2528 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2528) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                                                                                                                                    |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | GDI+의 취약점으로 인한 원격 코드 실행 문제점(957488)                                                                      | [CVE-2009-3126 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3126) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                                                                                                                                    |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="13">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**없음**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[DirectShow WMA 음성 코덱](http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b&displaylang=ko)  
(KB969878)  
(긴급)  
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=8f850a82-61f9-447b-a0aa-a2c192cc5d2e&displaylang=ko)  
(KB954155)  
(긴급)  
[오디오 압축 관리자](http://www.microsoft.com/downloads/details.aspx?familyid=6dfd5405-cabe-4bd7-9330-b6bde1d99194&displaylang=ko)  
(KB975025)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=13035ef7-7e47-487c-8b7c-7795d33ce7de&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=26515c7b-d7a6-4405-96b5-a518dcb39d38&displaylang=ko)  
(긴급)  
[Microsoft Internet Explorer 6 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=8154ba37-0fbc-4d31-9d6e-0b21586ad65a&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=edfea805-9544-4dc0-a52c-d7594205657b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01&displaylang=ko)(KB953300)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e&displaylang=ko)(KB974417)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=f3fef608-dafb-4b37-a65a-9cc4ae8e2c4c&displaylang=ko)  
(KB958869)  
(긴급)  
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=ecf78619-80fa-417d-852b-1b5b2cf574e2&displaylang=ko)  
(KB971108)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=3e534aa8-29c2-4379-9f57-931a6ff47418&displaylang=ko)  
(KB971110)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e6f5e730-85cc-4c08-a50d-c456b1e9f5bc&displaylang=ko)  
(KB971111)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=7fecd367-aaff-458b-91bc-8925c8e57528&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=52b9198d-b65f-467a-a5ab-141e23d64a86&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=b34d94b5-b828-4e16-a636-04344c60d945&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=bdfa6583-28a2-4d6b-91d2-157a8518b664&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="13">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[DirectShow WMA 음성 코덱](http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b&displaylang=ko)  
(KB969878)  
(긴급)  
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=4516c219-e357-485e-a52b-23dcb8ee49d8&displaylang=ko)  
(KB954155)  
(긴급)  
(Windows XP 서비스 팩 2만 해당)  
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=746d3440-5a6a-421e-9286-7b534a1dfe54&displaylang=ko)  
(KB954155)  
(긴급)  
(Windows XP 서비스 팩 3만 해당)  
[오디오 압축 관리자](http://www.microsoft.com/downloads/details.aspx?familyid=6ecc7129-8caa-4daf-a8e2-8f3536225fb3&displaylang=ko)  
(KB975025)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=b2efe1ac-d8d7-41bb-b87d-fc5e22afef0f&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9aacf890-afb4-46a7-a13f-dd9fe3c0ca4a&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dc166dc6-577f-4d8d-94df-dd963233dd85&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8799159d-df69-49f6-9db5-49147690ce0c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=171d43d3-669c-4923-b266-e47591833c05&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=1bc56c26-1c7c-47e3-94f4-37af7e00392c&displaylang=ko)  
(KB953295)  
(긴급)  
(Tablet PC Edition 2005 및 Media Center Edition 2005만)  
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01&displaylang=ko)(KB953300)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e&displaylang=ko)(KB974417)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=e2acde20-a6d3-4135-b6eb-1214f743d474&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=2ae0bdd4-f8b2-420a-b1ac-d2cdaa87c828&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=9c5ab624-e37b-418a-a919-d8f652b15679&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=768fd74e-0a2f-4353-ac22-65d0d6321739&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=cece4c55-0756-4357-9d2d-6709e8426068&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=e997ea40-668e-40df-bd50-0ca53437b375&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[DirectShow WMA 음성 코덱](http://www.microsoft.com/downloads/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a&displaylang=ko)  
(KB969878)  
(긴급)  
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=4729de51-8fd8-46c6-b4ad-9c9f25202684)  
(KB954155)  
(긴급)  
Windows Media Format SDK 9.5 x64 Edition의 [Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2&displaylang=ko)  
(KB954155)  
(긴급)  
Windows Media Format SDK 11의 [Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=a866a490-6d3a-4ecd-acf4-770312ba2fd6)  
(KB954155)  
(긴급)  
[오디오 압축 관리자](http://www.microsoft.com/downloads/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b&displaylang=ko)  
(KB975025)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=a9e7dfd8-7ba1-4f14-8e60-92ef00d91467)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=89a2cf2a-a7a2-4d4b-aa6f-24dde288d500)  
(긴급)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=bd54e595-25f2-4839-a838-2a0f809bde2b)  
(긴급)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=77b18fc2-e769-47c6-8e72-916716a49e58)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c08623bf-94bc-4c50-8c10-f50fb8448a0b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01&displaylang=ko)(KB953300)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e&displaylang=ko)(KB974417)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad92503a-8c91-4d73-98b0-942d7961637d)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=819dd2d1-cad5-4784-9baf-185d8a76df5d)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad29696d-4611-4a12-9dfa-74fa6866b759)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=270ec100-5ba1-4f8c-aa36-105d30ad57bf)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5459b7d4-1fab-4a04-ab9d-b8323505c1e2)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=17008892-7950-44c4-850d-002c8d73495f)<sup>[1]</sup>
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="13">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[DirectShow WMA 음성 코덱](http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b&displaylang=ko)  
(KB969878)  
(긴급)  
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=00b3cb86-c9eb-4fbe-987e-2b0d94271d87&displaylang=ko)  
(KB954155)  
(긴급)  
[오디오 압축 관리자](http://www.microsoft.com/downloads/details.aspx?familyid=ab1803ff-2371-487f-a7b6-95747c46ba4e&displaylang=ko)  
(KB975025)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=5f82d01c-573e-425e-b9f2-86a54f377b19&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=8101625d-ee93-46e5-aec2-3bdbf2d86472&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4647bcf1-69fb-4ad6-9e03-7bc22d8a914b&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9eae7eca-1a6f-4397-a6e2-7dda6b9d5276&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f3249c99-82e4-45dc-a254-28e647e822c8&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=d1b4a58b-f0b1-4400-a6e6-0255b0513bd1&displaylang=ko) (KB953298)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01&displaylang=ko)(KB953300)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e&displaylang=ko)(KB974417)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=414466a4-39a0-476d-9a43-ae7674cbd6a0&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=48256ea3-b433-4e84-9019-22300069cfc1&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=78072164-84d1-44da-8ede-2a9d212d47a9&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1e3f3842-f8fd-4969-a2cf-706db38d7580&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9dff4662-7771-4bdc-87ec-7899d79b3a55&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[DirectShow WMA 음성 코덱](http://www.microsoft.com/downloads/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a&displaylang=ko)  
(KB969878)  
(긴급)  
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=13ba4839-7fa9-4bbb-95f6-3fafb6c49f20&displaylang=ko)  
(KB954155)  
(긴급)  
Windows Media Format SDK 9.5 x64 Edition의 [Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2&displaylang=ko)  
(KB954155)  
(긴급)  
[오디오 압축 관리자](http://www.microsoft.com/downloads/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b&displaylang=ko)  
(KB975025)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=65e9036e-2e1b-40ff-a84b-c507107bcce8&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2f966053-01eb-4a23-a9d5-71deac2498ea&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e7d77bd9-8317-42f3-9ad1-a0b8bfa65b53&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=708a549d-11fd-43bf-a6e1-309e3205d59d&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1ad3f7b3-58d5-4507-ae20-a265e47cee9c&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01&displaylang=ko)(KB953300)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e&displaylang=ko)(KB974417)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=eb95e8d9-6ef5-4526-99d2-507e50de049b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=61bded07-201e-4815-ac1e-468bf907e063&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8aa1f97d-ad53-4450-bb93-4a147dd10a87&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=95286b8d-4b53-4e6c-af59-e9e18fad3559&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8df7a2d9-2f97-4f18-84e8-415a1632cf09&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=79a1a94d-3b47-47e9-9476-2f591c3f6a59)  
(긴급)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=07e66c09-2cd7-47ba-bf87-d3da602184b4)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=575e75d9-e348-4fbb-9eaa-43240e4d715e)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01&displaylang=ko)(KB953300)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e&displaylang=ko)(KB974417)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=a678ceb9-a37a-4c29-8bd1-f209922990e5)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b99d4d9b-e0cc-4a8c-ad99-6a53958b37c8)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=2ede1eb9-7f5f-411d-bbc3-5db46d80e0bb)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=fb5678b9-5ef1-42db-902e-c9ea02880e0a)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=faef714b-5f46-47f2-bea7-881df05a1bc0)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=83c77015-7f96-4c0d-bd56-60aef90ea2f8)<sup>[1]</sup>
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="13">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=29842c0c-8930-4b5f-83c6-1a718974b63f&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=f17ee0ea-f1e2-49f4-9f90-60296246ddfe&displaylang=ko)  
(KB954155)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f6995616-2a84-4c26-9599-26f1314873ed&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e8f6014f-950b-4e11-a105-51d298069f1a&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7313c03b-8844-4086-a0cc-43dfdb3ca48c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(긴급)  
[Microsoft .NET Framework 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63&displaylang=ko)(KB974468)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882&displaylang=ko)(KB974292)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233&displaylang=ko)(KB974467)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 및 Windows Vista 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=19aa01f3-026d-4264-85f8-216d0597969b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=bb96eb1c-66a2-4276-9773-eea22179bcd4&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b5a9a95-9439-40c8-acef-000b919daa04&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 및 Windows Vista 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=04ae306b-0d0d-4767-ab54-cc11aec477ed&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda&displaylang=ko)(KB974291)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8&displaylang=ko)(KB974469)  
(긴급)
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4&displaylang=ko)(KB974470)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
위와 같음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=62ed5d0a-5ca6-4942-80c9-7808b14cb6b5&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=26905f12-92c7-4d45-99e7-227f03d2cb82&displaylang=ko)  
(KB954155)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b3de5236-afdd-436e-8648-5382d564cc99&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=85978f28-5fc0-481b-9b03-2021c785889b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7216bcb1-ff16-402b-ad1b-1500d46d0157&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(긴급)  
[Microsoft .NET Framework 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63&displaylang=ko)(KB974468)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882&displaylang=ko)(KB974292)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233&displaylang=ko)(KB974467)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=8f5f0c1d-1dd6-47fa-aef2-d3c96c8fc06e&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=bce096c8-833b-45c8-99cd-1280f0744f2f&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4a60f789-1a4a-49a8-8d13-fda989ed40be&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=58c995ca-f308-4e07-8e60-2e542384d95d&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda&displaylang=ko)(KB974291)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8&displaylang=ko)(KB974469)  
(긴급)
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)(KB953297)  
(긴급)  
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4&displaylang=ko)(KB974470)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
위와 같음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="13">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**낮음**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ff6bfcf3-76c9-4c45-b57d-22f94458dd6e&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=2eaa9857-a147-4f31-9bf4-b9e2cf4c15c3&displaylang=ko)\*\*  
(KB954155)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=72dd580e-eb53-41da-a5c0-a392ad388bfc&displaylang=ko)\*\*  
(긴급)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1baf7e96-ba3e-47e7-8ea3-eb092e653a39&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=51eb56fa-8204-45f3-86d7-6d03a2c8d78d&displaylang=ko)\*\*  
(낮음)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)\*\*  
(KB953297)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda&displaylang=ko)\*\*  
(KB974291)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8&displaylang=ko)\*\*  
(KB974469)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=fd1694af-8873-43aa-9243-91f7cde452b7&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d9c5039f-d0cf-4d84-850f-f2f7701dcb79&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f9b487af-fe73-42a8-b240-d59c4321f95b&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f2f617c2-f149-4e9b-bfdd-08ed0f3f99db&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)\*\*  
(KB953297)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8&displaylang=ko)\*\*  
(KB974469)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
위와 같음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aff6f9c7-4a72-48f2-b750-204d796c7daa&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media 오디오 음성 디코더](http://www.microsoft.com/downloads/details.aspx?familyid=70aabba3-53d6-4b52-be83-6d3f3869ecbd&displaylang=ko)\*\*  
(KB954155)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0111d741-bda4-4a50-a12b-d3337ff4441d&displaylang=ko)\*\*  
(긴급)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a4b755b-7fa0-43aa-8862-c1d0c7d94c2c&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=131b047a-ae93-4a99-83e5-71d5a79e96ea&displaylang=ko)\*\*  
(낮음)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)\*\*  
(KB953297)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda&displaylang=ko)\*\*  
(KB974291)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8&displaylang=ko)\*\*  
(KB974469)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=41bc4cdb-273a-4a6e-80d9-c8ce20e32da9&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=db969ddc-708e-42b7-9956-6c27bf346bbb&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0d8a2a3e-d7d4-47fb-8364-16fce28e4d38&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=deb84cb8-2ba3-47e3-9185-2bbc5b0a7e18)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)\*\*  
(KB953297)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4&displaylang=ko)\*\*  
(KB974470)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
위와 같음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7b70108b-7f59-4898-ab4e-76be990de878)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e81f30b7-ef05-4488-b62a-d330e17129cf)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3d16c5bf-ee5c-4220-9755-5cb92eac2aae)  
(낮음)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)  
(KB953297)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda&displaylang=ko)  
(KB974291)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2 및 Microsoft .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8&displaylang=ko)  
(KB974469)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=a4f42085-1cb9-4b8d-a931-85be71fdf06d)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a221451a-cb4e-4a43-a225-4b1e86e87525)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8962f0b6-f346-4e88-9d83-4d15b699dd9d)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aac0e3e-9b49-4a4a-ab17-707ff03b4d9b)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f&displaylang=ko)  
(KB953297)  
(중요)  
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4&displaylang=ko)  
(KB974470)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
위와 같음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
(보통)
</td>
<td style="border:1px solid black;">
위와 같음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="13">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=89d1fb78-68cd-48dd-afc2-15a79ebe9fde&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b64bcc14-38a7-45b9-8f85-acc573777506&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ad6f06d5-27db-445d-a8b2-c42adc90afc0&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=35b85783-90df-4f67-a3cb-02351432133e&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=10d9f7ac-65f4-437c-91cc-171632c69b0e&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=809e29f3-ec68-4a2b-b04e-11759dd16001&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=70cd0270-77e9-492a-82d9-798364640c10&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=97010f2c-6c10-4fda-84fd-6c8749968db5&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="13">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**낮음**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f50307d6-7869-4996-9ff7-23f87d08994b&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=bcd2b944-6852-48f2-820b-cce7d195e391&displaylang=ko)\*\*  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ce78c019-ec08-4ec6-abec-334f5ec5cb76&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=597ac3a7-e02d-49a5-9b8e-d097e867acea&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9b6a28ae-b3f2-42b0-8209-e3950ec37abb)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=85e76e55-3766-4ffe-9a18-8655de935b7c)  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=6442a77a-3c0d-4beb-b2d2-2885376c2135&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=abc94857-37d8-4bb8-ad9e-46e687fca40e)  
(중요)
</td>
</tr>
</table>
 
**Windows Server 2008 및 Windows Server 2008 R2 참고 사항**

**\*Server Core 설치가 영향을 받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

**\*\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

**MS09-061 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

**MS09-062 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

**MS09-059 참고 사항**

<sup>[1]</sup>이 운영 체제는 KB968389, 인증에 대한 확장된 보호([Microsoft Security Advisory 973811](http://technet.microsoft.com/security/advisory/973811) 참조)가 설치된 경우에만 영향을 받습니다. 자세한 내용은 [MS09-059의 이 보안 업데이트와 관련된 자주 제기되는 질문 사항](http://technet.microsoft.com/security/bulletin/ms09-059) 섹션을 참조하십시오.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-060**](http://technet.microsoft.com/security/bulletin/ms09-060)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2002 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=04878c2c-eb97-426f-be08-89036a6799db&displaylang=ko)  
(KB973702)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d&displaylang=ko)<sup>[2]</sup>
(KB974811)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=79e2b2e8-d5e8-4014-b489-720af2b5083d&displaylang=ko)  
(KB973705)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7&displaylang=ko)<sup>[3]</sup>
(KB972580)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2007 서비스 팩 1 및 Microsoft Office Outlook 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d39234a3-c62c-44ba-a626-3179a183ca09&displaylang=ko)  
(KB972363)  
(긴급)
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System 서비스 팩 1 및 2007 Microsoft Office System 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec&displaylang=ko)\[4\]  
(KB972581)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-060**](http://technet.microsoft.com/security/bulletin/ms09-060)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=920ee70b-c5c1-47b5-8f33-938ffe14eea4&displaylang=ko)  
(KB975365)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio Viewer
</td>
<td style="border:1px solid black;">
Microsoft Visio 2002 Viewer<sup>[1]</sup>
(긴급)  
Microsoft Office Visio 2003 Viewer<sup>[1]</sup>
(긴급)  
[Microsoft Office Visio Viewer 2007 서비스 팩 1 및 Microsoft Office Visio Viewer 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d20004c5-dd01-459e-8120-5f127e20c085)  
(KB973709)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio Viewer 2007, Microsoft Office Visio Viewer 2007 서비스 팩 1 및 Microsoft Office Visio Viewer 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d&displaylang=ko)<sup>[2]</sup>
(KB974811)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer, Microsoft Office Excel Viewer 및 Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer, Microsoft Word Viewer 2003, Microsoft Word Viewer 2003 서비스 팩 3, Microsoft Office Excel Viewer 2003, Microsoft Office Excel Viewer 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7&displaylang=ko)<sup>[3]</sup>
(KB972580)  
(중요)  
[Microsoft Office Excel Viewer, PowerPoint Viewer 2007, PowerPoint Viewer 2007 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec&displaylang=ko)\[4\]  
(KB972581)  
(중요)  
[PowerPoint Viewer 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec&displaylang=ko)\[4\]  
(KB972581)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](http://www.microsoft.com/downloads/details.aspx?familyid=6f96de9a-62d8-428f-9567-51d55c129be6&displaylang=ko)  
(KB973636)  
(중요)
</td>
</tr>
</table>
 
**MS09-060 참고 사항**

<sup>[1]</sup>Microsoft Visio Viewer 2002 및 Microsoft Visio Viewer 2003 사용자는 Microsoft Office Visio Viewer 2007 서비스 팩 2로 업그레이드하는 것이 좋습니다.

**MS09-062 참고 사항**

<sup>[2]</sup>이 업데이트는 동일합니다.

<sup>[3]</sup>이 업데이트는 동일합니다.

\[4\]이 업데이트는 동일합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2000 Reporting Services 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트  
해당 사항 없음  
QFE 업데이트:  
[SQL Server 2000 Reporting Services 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=33554f96-5af7-4683-a537-9db293b67b8d&displaylang=ko)  
(KB970899)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23&displaylang=ko)  
(KB970895)  
(긴급)  
QFE 업데이트:  
[SQL Server 2005 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235&displaylang=ko)  
(KB970896)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23&displaylang=ko)  
(KB970895)  
(긴급)  
QFE 업데이트:  
[SQL Server 2005 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235&displaylang=ko)  
(KB970896)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 서비스 팩 2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 서비스 팩 2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23&displaylang=ko)  
(KB970895)  
(긴급)  
QFE 업데이트:  
[SQL Server 2005 서비스 팩 2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235&displaylang=ko)  
(KB970896)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 서비스 팩 3
</td>
<td style="border:1px solid black;">
GDR 업데이트  
[SQL Server 2005 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce&displaylang=ko)  
(KB970892)  
(긴급)  
QFE 업데이트:  
[SQL Server 2005 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f&displaylang=ko)  
(KB970894)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition 서비스 팩 3
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 x64 Edition 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce&displaylang=ko)  
(KB970892)  
(긴급)  
QFE 업데이트:  
[SQL Server 2005 x64 Edition 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f&displaylang=ko)  
(KB970894)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 서비스 팩 3(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 서비스 팩 3(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce&displaylang=ko)  
(KB970892)  
(긴급)  
QFE 업데이트:  
[SQL Server 2005 서비스 팩 3(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f&displaylang=ko)  
(KB970894)  
(긴급)
</td>
</tr>
</table>
 
**MS09-062 참고 사항**

<sup>[1]</sup>SharePoint 종속 Reporting Services를 사용하는 SQL Server 2005 서비스 팩 2 고객은 Microsoft 다운로드 센터에서 [서비스 팩 2용 Microsoft SQL Server 2005 Reporting Services 추가 기능](http://www.microsoft.com/downloads/details.aspx?familyid=%20f4d4d0ae-e5d4-4ed1-8d78-7137578161ce&displaylang=en)도 설치해야 합니다.

<sup>[2]</sup>SharePoint 종속 Reporting Services를 사용하는 SQL Server 2005 서비스 팩 3 고객은 Microsoft 다운로드 센터에서 [서비스 팩 3용 Microsoft SQL Server 2005 Reporting Services 추가 기능](http://www.microsoft.com/downloads/details.aspx?familyid=%20648766ac-2a35-4238-a3f4-c26d7077f2a9&displaylang=en)도 설치해야 합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 개발자 도구 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Mac에 설치된 Microsoft Silverlight 2 (영문)](http://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup>
(KB970363)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](http://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup>(모든 Microsoft Windows 클라이언트 릴리스에 설치된 경우)  
(KB970363)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](http://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup>(모든 Microsoft Windows 서버\*\* 릴리스에 설치된 경우)  
(KB970363)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=9e3b52d3-b211-4d62-891c-ae8f2e4ffc6c&displaylang=ko)  
(KB971022)  
(심각도 없음<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=e186aeed-e9d7-4a02-84b3-bbed116ca060&displaylang=ko)  
(KB971023)  
(심각도 없음<sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=4fa10c93-ce20-43df-a725-ef4c77353747&displaylang=ko)  
(KB972221)  
(심각도 없음<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=b904dee8-8a26-43f8-8ca9-86ad12cfdb52&displaylang=ko)  
(KB972222)  
(심각도 없음<sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4에 설치된 Microsoft Visual FoxPro 8.0 서비스 팩 1  
(KB971104)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=e5d0d515-4b36-4025-bc6f-1c5cdf09e1af)  
Microsoft Windows 2000 서비스 팩 4에 설치 시  
(KB971104)  
(심각도 없음<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4에 설치된 Microsoft Visual FoxPro 9.0 서비스 팩 2  
(KB971105)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2a930f56-59ac-49a6-830f-bfae7c540ec7)  
Microsoft Windows 2000 서비스 팩 4에 설치 시  
(KB971105)  
(심각도 없음<sup>[2]</sup>)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Report Viewer
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 서비스 팩 1 재배포 가능 패키지
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 서비스 팩 1 재배포 가능 패키지](http://www.microsoft.com/downloads/details.aspx?familyid=0dfaf300-2b53-4678-a779-0d805ddfe538&displaylang=ko)  
(KB971117)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 재배포 가능 패키지
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 재배포 가능 패키지](http://www.microsoft.com/downloads/details.aspx?familyid=42ed040f-cf94-4754-b0b3-c8016fbcbe22&displaylang=ko)  
(KB971118)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 재배포 가능 패키지 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 재배포 가능 패키지 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=6aaa74bd-a46e-4478-b4e1-2063d18d2d42&displaylang=ko)  
(KB971119)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Platform SDK 재배포 가능 파일: GDI+
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK 재배포 가능 파일: GDI+](http://www.microsoft.com/downloads/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(KB975337)  
(심각도 없음<sup>[2]</sup>)
</td>
</tr>
</table>
 
**MS09-061 참고 사항**

<sup>[1]</sup>이 다운로드는 Microsoft Silverlight 2를 취약점이 해결된 Microsoft Silverlight 3으로 업그레이드합니다.

**\*\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

**MS09-062 참고 사항**

<sup>[2]</sup>Microsoft에서 이 공지에 이러한 소프트웨어와 관련하여 설명한 취약점에 관한 공격 경로를 파악하지 못했기 때문에 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 이 보안 업데이트는 이 소프트웨어를 사용하는 개발자가 자체적으로 업데이트한 응용 프로그램을 실행할 수 있도록 하기 위해 개발자에게 제공됩니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 보안 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Client Security 1.0](http://www.microsoft.com/downloads/details.aspx?familyid=c0ce624c-8df3-4223-8a7a-5cba4ac334a8&displaylang=ko)  
Microsoft Windows 2000 서비스 팩 4에 설치 시  
(KB975962)  
(긴급)
</td>
</tr>
</table>
 
**MS09-062 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**참고** 2009년 8월 1일부터 Microsoft는 Office 업데이트와 Office 업데이트 인벤토리 도구에 대한 지원을 중단합니다. 계속해서 Microsoft Office 제품에 필요한 최신 업데이트를 받으려면 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)를 사용하십시오. 자세한 내용은 [Microsoft Office 업데이트 정보: 자주 제기되는 질문 사항(FAQ) (영문)](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx)을 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](http://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS09-050에서 설명한 문제점을 보고해 주신 [Netherlands Forensics Institute (영문)](http://www.nederlandsforensischinstituut.nl/)의 [Matthieu Suiche (영문)](http://www.msuiche.net/)
-   MS09-051에서 설명한 문제점을 보고해 주신 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)의 Ivan Fratric및 [McAfee Avert Labs (영문)](http://www.avertlabs.com/)의 Jun Xie
-   MS09-051에서 설명한 문제점을 보고해 주신 [Adobe Systems, Inc. (영문)](http://www.adobe.com/)의 Vinay Anantharaman
-   MS09-052에서 설명한 문제점을 보고해 주신 [Palo Alto Networks (영문)](http://www.paloaltonetworks.com/)의 Yamata Li
-   MS09-054에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 SkyLined
-   MS09-054에서 설명한 문제점을 보고해 주신 [IBM ISS X-Force](http://www.iss.net/)의 Mark Dowd
-   MS09-054에서 설명한 문제점을 보고해 주신 [TippingPoint](http://www.tippingpoint.com/) 및 [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   MS09-054에서 설명한 문제점을 [Zero Day Initiative](http://www.zerodayinitiative.com/) 및 [TippingPoint](http://www.tippingpoint.com/)와 협력하여 보고해 주신 Sam Thomas(http://eshu.co.uk/)
-   MS09-056에서 설명한 문제점을 해결하기 위해 협력해 주신 [Citrix (영문)](http://www.citrix.com/)의 Ian Wright 및 Jean-Luc Giraud
-   MS09-056에서 설명한 두 가지 문제점을 보고해 주신 [IOActive (영문)](http://www.ioactive.com/)의 Dan Kaminsky
-   MS09-057에서 설명한 문제점을 보고해 주신 [Palo Alto Networks (영문)](http://www.paloaltonetworks.com/)의 Yamata Li
-   MS09-058에서 설명한 두 가지 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 Tavis Ormandy 및 Neel Mehta
-   MS09-058에서 설명한 문제점을 보고해 주신 [NSFocus Security Team (영문)](http://www.nsfocus.com/)
-   MS09-060에서 설명한 문제점을 보고해 주신 [IBM ISS X-Force](http://www.iss.net/)의 David Dewey
-   MS09-060에서 설명한 두 가지 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Ryan Smith
-   MS09-061에서 설명한 문제점을 보고해 주신 [Pavel Minaev (영문)](http://int19h.org/)
-   MS09-061에서 설명한 문제점을 보고해 주신 [Sumatra (영문)](http://www.sumatra.nl/)의 Jeroen Frijters
-   MS09-062에서 설명한 문제점을 보고해 주신 [Palo Alto Networks (영문)](http://www.paloaltonetworks.com/)의 Yamata Li
-   MS09-062에서 설명한 문제점을 보고해 주신 [SkyRecon (영문)](http://www.skyrecon.com/)의 Thomas Garnier
-   MS09-062에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Wushi
-   MS09-062에서 설명한 문제점을 보고해 주신 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)의 Ivan Fratric
-   MS09-062에서 설명한 두 가지 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 Tavis Ormandy
-   MS09-062에서 설명한 문제점을 보고해 주신 Carlo Di Dato(다른 이름: shinnai)
-   MS09-062에서 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Marsu Pilami
-   MS09-062에서 설명한 문제점을 보고해 주신 [Secunia (영문)](http://secunia.com/)의 Carsten H. Eiram

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   미국 및 캐나다 고객은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 기술 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 10월 14일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 10월 15일): Windows XP x64 Edition 서비스 팩 2를 위한 MS09-055의 다운로드 링크가 수정되었습니다.
-   V1.2(2009년 10월 19일): Firefox 사용자에게 지침을 제공하기 위해 MS09-054의 요약이 개정되었습니다.
-   V2.0(2009년 10월 29일): Microsoft Office Visio Viewer 2007, Microsoft Office Visio Viewer 2007 서비스 팩 1 및 Microsoft Office Visio Viewer 2007 서비스 팩 2가 MS09-062의 영향을 받는 소프트웨어로 추가되고 MS09-062에 SharePoint 종속 Reporting Services를 사용하는 SQL Server 2005 고객에 대한 설명이 추가되었습니다.
-   V3.0(2009년 11월 3일): 응용 프로그램 호환성 문제를 해결하는 MS09-054에 대한 핫픽스가 릴리스되었음을 알리기 위해 개정되었습니다. 이 업데이트를 이미 적용한 고객은 Microsoft 기술 자료 문서 976749에서 핫픽스를 설치할 수 있습니다.
-   V3.1(2009년 11월 5일): MS09-060 및 MS09-062에서 Microsoft Office Visio Viewer 2007이 영향을 받는 소프트웨어로 잘못 언급되어 있는 것을 삭제하였습니다.
-   V4.0(2009년 11월 11일): MS09-051의 Microsoft Windows 2000 서비스 팩 4에 설치된 오디오 압축 관리자의 검색 문제를 해결하는 업데이트가 다시 발표되었음을 알리기 위해 이 공지를 개정하였습니다. 이 변경 사항은 검색에만 해당됩니다. 바이너리에 대한 변경 사항은 없습니다. 시스템을 성공적으로 업데이트한 고객은 이 업데이트를 다시 설치할 필요가 없습니다.
-   V4.1(2010년 1월 13일): MS09-062의 영향을 받는 소프트웨어에서 Microsoft Expression Web, Microsoft Expression Web 2, Microsoft Office Groove 2007 및 Microsoft Office Groove 2007 서비스 팩 1을 제거하였습니다.
-   V4.2(2010년 6월 23일): MS09-061에서 Windows 7 및 Windows Server 2008 R2의 .NET Framework 1.1 서비스 팩 1이 영향을 받는 구성 요소에서 제거되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
