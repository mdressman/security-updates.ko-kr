---
TOCTitle: 'MS09-AUG'
Title: 2009 년 8 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-aug'
ms:contentKeyID: 61230709
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-aug(v=Security.10)'
---


2009 년 8 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2009년 8월 12일 수요일 | 업데이트된 날짜: 2009년 10월 28일 수요일

**버전:** 4.0

이 공지 요약 목록에는 2009년 8월 발표된 보안 공지가 포함되어 있습니다.

2009년 8월 공지 발표와 함께 이 공지 요약이 2009년 8월 6일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2009년 8월 13일 목요일 오전 3시(한국 표준시)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [8월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407484&eventcategory=4&culture=en-us&countrycode=us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-043">MS09-043</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Web Components의 취약점으로 인한 원격 코드 실행 문제점 (957638)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 여러 건의 취약점을 해결합니다. 사용자가 특수하게 조작된 웹 페이지를 열면 Microsoft Office Web Components 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Visual Studio, Microsoft ISA Server, Microsoft BizTalk Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-044">MS09-044</a></td>
<td style="border:1px solid black;"><strong>원격 데스크톱 연결의 취약점으로 인한 원격 코드 실행 문제점 (970927)</strong><br />
<br />
이 보안 업데이트는 Microsoft 원격 데스크톱 연결에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 공격자가 터미널 서비스 사용자로 하여금 악성 RDP 서버에 연결하도록 유도한 경우, 또는 사용자가 이 취약점을 악용하는 특수하게 조작된 웹 사이트를 방문하는 경우 원격 코드 실행이 발생할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Remote Desktop Connection Client for Mac</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-039">MS09-039</a></td>
<td style="border:1px solid black;"><strong>WINS의 취약점으로 인한 원격 코드 실행 문제점 (969883)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 WINS(Windows Internet Name Service)의 취약점 2건을 해결합니다. 이러한 취약점으로 인해 사용자가 WINS 서비스가 실행되는 영향 받은 시스템에서 특수하게 조작된 WINS 복제 패킷을 수신할 경우 원격 코드 실행이 발생할 수 있습니다. 기본적으로 WINS는 영향을 받는 운영 체제 버전에 설치되지 않으며, 이 구성 요소를 수동으로 설치한 고객만 이 문제의 영향을 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-038">MS09-038</a></td>
<td style="border:1px solid black;"><strong>Windows Media 파일 처리의 취약점으로 인한 원격 코드 실행 문제점 (971557)</strong><br />
<br />
이 보안 업데이트는 Windows Media 파일 처리에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 AVI 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 사용자가 관리자 권한으로 로그온한 경우, 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-037">MS09-037</a></td>
<td style="border:1px solid black;"><strong>Microsoft ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (973908)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft ATL(액티브 템플릿 라이브러리)의 몇 가지 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 구성 요소를 로드하거나 악성 웹 사이트에서 호스팅하는 컨트롤을 로드하는 경우 원격 코드 실행이 발생할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-041">MS09-041</a></td>
<td style="border:1px solid black;"><strong>Workstation 서비스의 취약점으로 인한 권한 상승 문제점 (971657)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows Workstation 서비스의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 RPC 메시지를 만든 후 영향 받는 시스템으로 전송할 경우 권한 상승이 발생할 수 있습니다. 이 취약점 악용에 성공한 공격자는 임의 코드를 실행하여 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 공격자가 이 취약점을 악용하려면 취약한 시스템에 대한 유효한 로그온 자격 증명이 필요합니다. 익명 사용자는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-040">MS09-040</a></td>
<td style="border:1px solid black;"><strong>Message Queuing의 취약점으로 인한 권한 상승 문제점 (971032)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows MSMQ(Message Queuing Service)의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 영향 받은 MSMQ 서비스에 대해 특수하게 조작된 요청을 받은 경우 권한 상승이 발생할 수 있습니다. 기본적으로 Message Queuing 구성 요소는 영향을 받는 운영 체제 에디션에 설치되지 않으며, 관리자 권한을 가진 사용자가 직접 설정해야만 사용할 수 있습니다. Message Queuing 구성 요소를 수동으로 설치하는 고객만 이 문제에 취약할 가능성이 높습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-036">MS09-036</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows의 ASP.NET 취약점으로 인한 서비스 거부 문제점 (970957)</strong><br />
<br />
이 보안 업데이트는 비공개로 보고된 Microsoft Windows의 Microsoft .NET Framework 구성 요소의 서비스 거부 취약점을 해결합니다. 이 취약점은 IIS(인터넷 정보 서비스) 7.0이 설치되어 있고 ASP.NET이 영향을 받는 Microsoft Windows 버전에서 통합 모드를 사용하도록 구성된 경우에만 악용될 수 있습니다. 공격자는 관련된 응용 프로그램 풀이 다시 시작되기 전까지는 영향을 받는 웹 서버가 응답하지 못하도록 만드는 특수하게 조작된 익명의 HTTP 요청을 만들 수 있습니다. 클래식 모드에서 IIS 7.0 응용 프로그램 풀을 실행하는 고객은 이 취약점의 영향을 받지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-042">MS09-042</a></td>
<td style="border:1px solid black;"><strong>텔넷의 취약점으로 인한 원격 코드 실행 문제점 (960859)</strong><br />
<br />
이 보안 업데이트는 일반에 공개된 Microsoft 텔넷 서비스의 취약점을 해결합니다. 이 취약점으로 인해 공격자는 자격 증명을 획득한 후 이 자격 증명을 사용하여 영향 받는 시스템에 다시 로그인할 수 있습니다. 그런 후 공격자는 로그온한 사용자의 사용자 권한과 동일한 시스템에 대한 사용자 권한을 획득합니다. 이 시나리오에서는 결과적으로 영향 받는 시스템에서 원격 코드가 실행될 수 있습니다. 취약점 악용에 성공한 공격자는 프로그램을 설치하거나 데이터를 보고 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
원격 코드 실행</td>
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
  
| 공지 번호                                                           | 공지 제목                                                                                | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                                                                                                                                                                                            |  
|---------------------------------------------------------------------|------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-036](http://technet.microsoft.com/security/bulletin/ms09-036) | Microsoft Windows의 ASP.NET 취약점으로 인한 서비스 거부 문제점 (970957)                  | [CVE-2009-1536 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1536) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 서비스 거부 도구가 사용될 수 있습니다. 그러나 원격 코드 실행 악용 코드 기능은 불가능합니다.                                                                                                                                                                          |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (973908) | [CVE-2008-0015 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.**                                                                                                                                                                                                            |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (973908) | [CVE-2008-0020 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0020) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                               |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (973908) | [CVE-2009-0901 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | 없음                                                                                                  | (이 취약점은 이미 [7월 공지 요약](http://technet.microsoft.com/security/bulletin/ms09-jul)의 악용 가능성 인덱스 평가에 지정되어 있습니다. 그 이유는 이 취약점이 [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035)에서 처음 해결되었기 때문입니다.) |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (973908) | [CVE-2009-2493 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | 없음                                                                                                  | (이 취약점은 이미 [7월 공지 요약](http://technet.microsoft.com/security/bulletin/ms09-jul)의 악용 가능성 인덱스 평가에 지정되어 있습니다. 그 이유는 이 취약점이 [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035)에서 처음 해결되었기 때문입니다.) |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft ATL(액티브 템플릿 라이브러리)의 취약점으로 인한 원격 코드 실행 문제점 (973908) | [CVE-2009-2494 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2494) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                               |  
| [MS09-038](http://technet.microsoft.com/security/bulletin/ms09-038) | Windows Media 파일 처리의 취약점으로 인한 원격 코드 실행 문제점 (971557)                 | [CVE-2009-1545 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1545) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                               |  
| [MS09-038](http://technet.microsoft.com/security/bulletin/ms09-038) | Windows Media 파일 처리의 취약점으로 인한 원격 코드 실행 문제점 (971557)                 | [CVE-2009-1546 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1546) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                               |  
| [MS09-039](http://technet.microsoft.com/security/bulletin/ms09-039) | WINS의 취약점으로 인한 원격 코드 실행 문제점 (969883)                                    | [CVE-2009-1923 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1923) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                               |  
| [MS09-039](http://technet.microsoft.com/security/bulletin/ms09-039) | WINS의 취약점으로 인한 원격 코드 실행 문제점 (969883)                                    | [CVE-2009-1924 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1924) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | Windows 2000 대상에 대해 악용이 성공할 가능성이 더 높습니다.                                                                                                                                                                                                         |  
| [MS09-040](http://technet.microsoft.com/security/bulletin/ms09-040) | Message Queuing의 취약점으로 인한 권한 상승 문제점 (971032)                              | [CVE-2009-1922 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1922) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점의 원격 공격은 불가능합니다.                                                                                                                                                                                                                                |  
| [MS09-041](http://technet.microsoft.com/security/bulletin/ms09-041) | Workstation 서비스의 취약점으로 인한 권한 상승 문제점 (971657)                           | [CVE-2009-1544 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1544) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 공격자가 이 취약점을 악용하려면 인증이 필요합니다.                                                                                                                                                                                                                   |  
| [MS09-042](http://technet.microsoft.com/security/bulletin/ms09-042) | 텔넷의 취약점으로 인한 원격 코드 실행 문제점 (960859)                                    | [CVE-2009-1930 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1930) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 악용 코드가 이미 존재한다는 점에서 이전의 NTLM 자격 증명 리플렉션 취약점과 비슷합니다.                                                                                                                                                                   |  
| [MS09-043](http://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web Components의 취약점으로 인한 원격 코드 실행 문제점 (957638)         | [CVE-2009-0562 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0562) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                               |  
| [MS09-043](http://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web Components의 취약점으로 인한 원격 코드 실행 문제점 (957638)         | [CVE-2009-1136 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1136) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점에 대한 악용 코드는 일반에 공개되었습니다.                                                                                                                                                                                                                  |  
| [MS09-043](http://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web Components의 취약점으로 인한 원격 코드 실행 문제점 (957638)         | [CVE-2009-1534 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1534) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                               |  
| [MS09-043](http://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web Components의 취약점으로 인한 원격 코드 실행 문제점 (957638)         | [CVE-2009-2496 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2496) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                               |  
| [MS09-044](http://technet.microsoft.com/security/bulletin/ms09-044) | 원격 데스크톱 연결의 취약점으로 인한 원격 코드 실행 문제점 (970927)                      | [CVE-2009-1133 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1133) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                                                               |  
| [MS09-044](http://technet.microsoft.com/security/bulletin/ms09-044) | 원격 데스크톱 연결의 취약점으로 인한 원격 코드 실행 문제점 (970927)                      | [CVE-2009-1929 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1929) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                                                               |
  
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
</tr>
<tr>
<th style="border:1px solid black;" colspan="9">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[RDP 버전 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=027e757d-08d5-4932-b8c4-52ee1be1c864&displaylang=ko)\*\*\*  
(KB958471) 및 [RDP 버전 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=027e757d-08d5-4932-b8c4-52ee1be1c864&displaylang=ko)(KB958470)  
(긴급)  
[RDP 버전 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2&displaylang=ko)\*\*\*\*  
(KB958470)  
(긴급)  
[RDP 버전 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2&displaylang=ko)\*\*\*\*  
(KB958470)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=b5b9228a-66c0-49e6-afde-cc2825a6851f&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=5f80bf0b-898c-46ca-b20c-21e0e729c332&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6f9fcbe9-8496-4d23-8a16-b334157688c2&displaylang=ko)  
(KB973354)  
(긴급)  
[Microsoft Outlook Express 6 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=f340af34-b9a0-44fb-b595-dbb346c727bf&displaylang=ko)  
(KB973354)  
(긴급)  
[Windows Media Player 9](http://www.microsoft.com/downloads/details.aspx?familyid=bd7c9fc4-61cb-4c23-9961-6d63f234731c&displaylang=ko)  
(KB973354)  
(긴급)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=c773149a-f4fc-486a-b718-6b8ff7a36ae2&displaylang=ko)  
(KB973507)  
(긴급)  
[DHTML 편집 구성 요소 ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=223e25d2-83d7-4cb7-85c4-46a42b8110e0&displaylang=ko)  
(KB973869)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ed8bad7-2885-452c-9c34-3982cd498be8&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=240977d6-3581-4058-b9f1-7847e4edcf8a&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="9">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2의 RDP 버전 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=2a8830dd-8fb3-4556-a6e7-2c237235357f&displaylang=ko)  
(KB958470)  
(긴급)  
[Windows XP 서비스 팩 2용 RDP 버전 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=2a8830dd-8fb3-4556-a6e7-2c237235357f&displaylang=ko)\*\*\*\*  
(KB958470)  
(긴급)  
[Windows XP 서비스 팩 2용 RDP 버전 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719&displaylang=ko)\*\*\*\*  
(KB956744)  
(중요)  
[Windows XP 서비스 팩 2용 RDP 버전 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719&displaylang=ko)\*\*\*\*  
(KB956744)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=2e8a68ee-eb24-424c-b084-450636ccaeec&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=c67b5506-00ea-47cc-a0e8-897057b7380c&displaylang=ko)  
(KB973354)  
(긴급)  
[Windows Media Player 9, Windows Media Player 10 및 Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=34b2b14d-5811-4635-ba83-f837dcb03d04&displaylang=ko)  
(KB973540)  
(긴급)  
(Windows XP 서비스 팩 2만 해당)  
[Windows Media Player 9, Windows Media Player 10 및 Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=ec84c98b-6bc7-442f-9280-d6e204280b2f&displaylang=ko)  
(KB973540)  
(긴급)  
(Windows XP 서비스 팩 3만 해당)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=4b4c6fc5-e8e6-4d89-a181-e231240468f9&displaylang=ko)  
(KB973507)  
(긴급)  
[DHTML 편집 구성 요소 ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=bdfcd0c3-7c18-4e63-91dd-d8f82cd89592&displaylang=ko)  
(KB973869  
(긴급)  
[Microsoft MSWebDVD ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=8b71bcc9-5146-4afc-8847-0af21d7fad36&displaylang=ko)  
(KB973769)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=9c0e5bff-c248-4e87-a83b-82ba52f5299d&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=93490aa7-9985-4658-b0d7-88fb3f27ada0&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=b3331388-1e52-4924-b512-23275a8fde84&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2의 RDP 버전 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=948da99a-44ed-4390-b1b4-7ed3f15a9cda)  
(KB958469)  
(긴급)  
[Windows XP Professional x64 Edition 서비스 팩 2용 RDP 버전 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=5061615f-fa8f-465f-ac8f-393998b7e91b)\*\*\*\*  
(KB956744)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a1ff2ace-b9dc-4cf3-a151-ac6959bcb3a6)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=ede1a73a-e303-435e-a2c7-0281ce2370da)  
(KB973354)  
(긴급)  
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?familyid=bb98187a-8db9-47e4-88ac-15544c5268f6)  
(KB973540)  
(긴급)  
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=9e8b9027-4407-4c31-a2ba-9e094557d467)  
(KB973540)  
(긴급)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=2f2b93fc-f977-4f23-af90-c27f744fad0a)  
(KB973507)  
(긴급)  
[DHTML 편집 구성 요소 ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=d04a6959-41a4-4a87-b3ad-7455d8fe8b99)  
(KB973869)  
(긴급)  
[Microsoft MSWebDVD ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=85b2dcdb-cea9-4c4a-8ebd-50264e781ade)  
(KB973815)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7b64a454-d383-47e3-b469-b87e2b3c1a9f)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=12e6be68-dc87-450e-927b-3c9b6873eb13)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a6ee7af3-3e39-4866-a893-92bf1c786cd4)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="9">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[RDP 버전 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=60c79729-ef01-4630-bd67-ec63e7f8b56b&displaylang=ko)  
(KB958469)  
(긴급)  
[RDP 버전 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a37a2d8a-a5ce-4f06-bf07-8cafa16e7a59&displaylang=ko)\*\*\*\*  
(KB956744)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3a8d8ef9-ad41-4237-9cbb-daecfd8f216c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=cba78658-899c-428f-8b04-cfe14ce3c255&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=3119ab1e-6729-40a1-b28f-0dab50502be6&displaylang=ko)  
(KB973354)  
(긴급)  
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?familyid=ab054890-983b-4414-ad0a-da1b2d2a4895&displaylang=ko)  
(KB973540)  
(긴급)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=7d9369b5-0c54-4c17-bc62-fba0a7b4728c&displaylang=ko)  
(KB973507)  
(긴급)  
[DHTML 편집 구성 요소 ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=bfc474c2-e3c5-40df-85d4-4ac666ff0561&displaylang=ko)  
(KB973869  
(긴급)  
[Microsoft MSWebDVD ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=301ad191-8d3f-41d3-b41c-e2e863893f73&displaylang=ko)  
(KB973769)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9cb0477f-0656-47f5-bd35-5716e0572fbd&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=52f59c56-2aba-4626-a90e-311e0e73c813&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3fe9c745-d87c-43b0-9b2a-356fb34282b4&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[RDP 버전 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=57393588-dc96-4bda-ab1e-ae550961e5d4)  
(KB958469)  
(긴급)  
[RDP 버전 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=957c2e01-89a1-4550-aacb-de8ff896d762)\*\*\*\*  
(KB956744)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e132d051-4444-4ef1-9b6f-2d7da9d2e88e&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=58a7c8d9-ec36-46a6-a89b-d8dfd989fda4&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=17bd00e3-810c-4a72-bd13-1b55ffb52a5e&displaylang=ko)  
(KB973354)  
(긴급)  
[Windows Media Player 10](http://www.microsoft.com/downloads/details.aspx?familyid=5890233a-d8f7-490c-8bf5-3ed4bd1c6991&displaylang=ko)  
(KB973540)  
(긴급)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=90e0e014-ed7e-498a-9f61-18bb09a384b3&displaylang=ko)  
(KB973507)  
(긴급)  
[DHTML 편집 구성 요소 ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=9f502d79-99a8-45dc-9876-2df27e14ffaa&displaylang=ko)  
(KB973869  
(긴급)  
[Microsoft MSWebDVD ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=2ae71a65-5eee-4dd2-bc79-b7c5a73022bc&displaylang=ko)  
(KB973769)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=96fbf65f-1db2-432d-92a0-6669d8abaeb0&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2f77ef7b-54f8-4260-b6a6-d62a0f85ef45&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e2a788e7-a9d1-4574-b106-f8ab44c6c4a2&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[RDP 버전 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=8f88a714-b917-4193-9002-19fa65722028)  
(KB958469)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=96c3f496-7b2f-4dbc-b484-216c9943c2b1)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=187b02bd-73d6-4f72-81d1-d9477d495499)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=7978b921-c5b5-461f-a284-b9848f568aa9)  
(KB973354)  
(긴급)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=ad1791b3-8553-4433-a9f7-8b4f857665be)  
(KB973507)  
(긴급)  
[DHTML 편집 구성 요소 ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=82c0bb02-70ad-4605-a1f4-4698adf9f4ac)  
(KB973869)  
(긴급)  
[Microsoft MSWebDVD ActiveX 컨트롤](http://www.microsoft.com/downloads/details.aspx?familyid=5b8a8958-c3cd-4b24-85a2-1baacf92d218)  
(KB973815)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=11321f48-8997-4b99-982a-3ba4ad3f5992)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ad55c653-ee6b-4c92-b7f4-3923bb916546)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=4f625d39-29d4-44f9-b4bd-cd99f1ea422d)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="9">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista의 RDP 버전 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cf95a552-f6fd-4e35-815a-d16c015cd3ea&displaylang=ko)  
(KB956744)  
(중요)  
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2용 RDP 버전 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad&displaylang=ko)  
(KB956744)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=81fce7bd-f33c-4586-949d-ac40d415f755&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=3766aed9-93f5-478e-a5bf-b7ee0b577088&displaylang=ko)  
(KB973540)  
(긴급)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=80de158d-157e-4c21-9154-c1dbd6e57cb3&displaylang=ko)  
(KB973507)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=979ac9da-940f-49e7-91a2-b12db3708076&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Vista](http://www.microsoft.com/downloads/details.aspx?familyid=00afd94c-b483-4155-884f-b617acca6e7d&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista만: [Microsoft .NET Framework 2.0 서비스 팩 1 및 .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff&displaylang=ko) (KB972591) 및 [Microsoft .NET Framework 2.0 서비스 팩 2 및 .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e&displaylang=ko)\*\*\*\* (KB972592)  
(중요)  
Windows Vista 서비스 팩 1만:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd&displaylang=ko) (KB972593) 및 [Microsoft .NET Framework 2.0 서비스 팩 2 및 .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f&displaylang=ko)\*\*\*\* (KB972594)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d77f406d-11cb-4d19-94ec-938b356c3427&displaylang=ko)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition의 RDP 버전 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad&displaylang=ko)  
(KB956744)  
(중요)  
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2의 RDP 버전 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad&displaylang=ko)  
(KB956744)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a6cea61a-4ad9-4e18-bf18-348ae4ae51c4&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=64edbd64-9faa-4f54-b0d5-836c683ca7cd&displaylang=ko)  
(KB973540)  
(긴급)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=82940d30-6a30-47ca-b184-2ac96e35c294&displaylang=ko)  
(KB973507)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9aa04cc-a5c5-47ae-bf0f-250cff275d26&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=a0c698aa-a913-4981-8798-6bbb8cacfb86&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition만: [Microsoft .NET Framework 2.0 서비스 팩 1 및 .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff&displaylang=ko) (KB972591) 및 [Microsoft .NET Framework 2.0 서비스 팩 2 및 .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e&displaylang=ko)\*\*\*\* (KB972592)  
(중요)  
Windows Vista x64 Edition 서비스 팩 1만:  
[Microsoft .NET Framework 2.0 서비스 팩 1 및 .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd&displaylang=ko) (KB972593) 및 [Microsoft .NET Framework 2.0 서비스 팩 2 및 .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f&displaylang=ko) (KB972594)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7a41b8c1-f955-474e-a08e-5e73964327d1&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="9">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[RDP 버전 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=71c17a87-710b-434d-9b2a-2f471674915a&displaylang=ko)\*\*  
(KB956744)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=fdc96a07-ed79-4798-8077-b2e9ca64cd0f&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=85d9e69f-99a2-467f-bf37-4b47466a12d4&displaylang=ko)\*\*  
(KB973540)  
(긴급)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=ba423491-6c29-49f2-811b-ac3f9bbc58fc&displaylang=ko)\*  
(KB973507)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=24c77c27-0b7d-4a35-a871-b453f90e5913&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008만(32비트 시스템용): [Microsoft .NET Framework 2.0 서비스 팩 1 및 .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd&displaylang=ko) (KB972593) 및 [Microsoft .NET Framework 2.0 서비스 팩 2 및 .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f&displaylang=ko) (KB972594)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=62f2e0a6-5e68-41c7-a851-d99bcff6ff3e&displaylang=ko)\*  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[RDP 버전 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=f095d2d5-4513-4ae1-96c7-cbcf83304261&displaylang=ko)\*\*  
(KB956744)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e3afba4-6761-4b3d-98bb-4b4145e27b7f&displaylang=ko)\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=9501c8c2-a526-4661-8cba-7847bace1aa0&displaylang=ko)\*\*  
(KB973540)  
(긴급)  
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=b9311953-889a-415f-a396-250a005e95cd&displaylang=ko)\*  
(KB973507)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=48d0432e-704a-4bbb-b0a1-cd14069a8e93&displaylang=ko)\*  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008만(x64 기반 시스템용): [Microsoft .NET Framework 2.0 서비스 팩 1 및 .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd&displaylang=ko) (KB972593) 및 [Microsoft .NET Framework 2.0 서비스 팩 2 및 .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f&displaylang=ko) (KB972594)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e5d1db9-efef-4112-8138-62f14670cf0d&displaylang=ko)\*  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[RDP 버전 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=65d0af4e-22a2-4524-a003-2f4858012fa8)  
(KB956744)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa1bb13a-5905-48c4-8e74-a41104593046)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows ATL 구성 요소](http://www.microsoft.com/downloads/details.aspx?familyid=e5612bb4-5f37-4b38-bd2e-f198c413371c)  
(KB973507)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c119223c-f4e0-449b-8e7b-a6bf11c98f94)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용)만: [Microsoft .NET Framework 2.0 서비스 팩 1 및 .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) 및 [Microsoft .NET Framework 2.0 서비스 팩 2 및 .NET Framework 3.5 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)  
(중요
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b813c74-b2ae-4962-9ebb-1311193d9e2d)  
(보통)
</td>
</tr>
</table>
 
**Windows Server 2008 참고 사항**

**\* Windows Server 2008 Server Core 설치가 영향을 받습니다.** 지원 대상인 Windows Server 2008 에디션에 대해 이 업데이트의 심각도는 Windows Server 2008에 Server Core 설치 옵션의 사용 여부와 상관없이 동일하게 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교](http://www.microsoft.com/korea/windowsserver2008/compare-core-installation.aspx)를 참조하십시오.

**\*\* Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 Windows Server 2008이 설치된 경우 이 업데이트에서 해결하는 취약점은 지원되는 모든 Windows Server 2008 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교](http://www.microsoft.com/korea/windowsserver2008/compare-core-installation.aspx)를 참조하십시오.

**MS09-044 참고 사항**

**\*\*\*** Microsoft Windows 2000 서비스 팩 4에서 RDP 버전 5.0을 사용하는 사용자는 KB958471 및 KB958470을 모두 설치해야 합니다.

**\*\*\*\*** 관리자는 이 부정기 다운로드를 수동으로 설치할 수 있습니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 "Mac용 클라이언트 소프트웨어" 하위 섹션을 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

**MS09-036 참고 사항**

**\*\*\*\*\*** Windows Vista Starter 및 Windows Vista Home Basic에서 IIS 7.0이 실행되지 않으므로 다음 에디션은 영향을 받지 않습니다. Windows Vista Starter(32비트), Windows Vista Home Basic(32비트) 및 Windows Vista Home Basic(64비트).

#### Client Software for Mac

 
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
원격 데스크톱
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Remote Desktop Connection Client for Mac
</td>
<td style="border:1px solid black;">

[Remote Desktop Connection Client for Mac 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd9ec77e-5b07-4332-849f-046611458871)**\***  
(중요)
</td>
</tr>
</table>
 
**MS09-044 참고 사항**

**\*** 이 소프트웨어는 Remote Desktop Connection Client for Mac 2.0을 Remote Desktop Connection Client for Mac 2.0.1로 업그레이드하여 취약점을 해결합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 "Windows 운영 체제 및 구성 요소" 하위 섹션을 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Office 제품군 및 소프트웨어

 
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
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580&displaylang=ko)  
(KB947320)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7&displaylang=ko)  
(KB947319)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Office Web Components
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Web Components
</td>
<td style="border:1px solid black;">
[Microsoft Office 2000 Web Components 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580&displaylang=ko)  
(KB947320)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Web Components
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Web Components 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580&displaylang=ko)  
(KB947320)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Web Components
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Web Components 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7&displaylang=ko)  
(KB947319)  
(긴급)  
[2007 Microsoft Office System용 Microsoft Office 2003 Web Components 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=644008e0-77c9-4a02-ac9b-e30d0930c4be&displaylang=ko)\*  
(KB947318)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
기타 Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Small Business Accounting 2006
</td>
<td style="border:1px solid black;">
[Microsoft Office Small Business Accounting 2006](http://www.microsoft.com/downloads/details.aspx?familyid=0d77ddb3-4d34-4cfe-913b-d05981f59a82)  
(KB968377)  
(긴급)
</td>
</tr>
</table>
 
**MS09-043 참고**

**\*** SQL Server 2008 및 Microsoft Forefront Threat Management Gateway Medium Business Edition은 영향 받는 2007 Microsoft Office System용 Office 2003 Web Components를 재배포합니다. 2007 Microsoft Office System용 Office 2003 Web Components 구성 요소에 대한 업데이트는SQL Server 2008 및 Microsoft Forefront Threat Management Gateway Medium Business Edition을 검색하여 고객에게 업데이트를 제공합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 하위 섹션을 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 개발자 도구 및 소프트웨어

 
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
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=ba2915a0-f5f4-4e18-b0c0-534d2a948585&displaylang=ko)  
(KB969172)  
(긴급)
</td>
</tr>
</table>
 
**MS09-043 참고**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 하위 섹션을 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Server and Security Software

 
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
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326&displaylang=ko)\*  
(KB947826)  
(긴급)  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326&displaylang=ko)  
(KB947826)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006 Standard Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326&displaylang=ko)  
(KB947826)  
(긴급)  
[Microsoft Internet Security and Acceleration Server 2006 Enterprise Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326&displaylang=ko)  
(KB947826)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2002
</td>
<td style="border:1px solid black;">
[Microsoft BizTalk Server 2002](http://www.microsoft.com/downloads/details.aspx?familyid=495839b6-0322-4755-997d-4a7762c53333)  
(KB971388)  
(긴급)
</td>
</tr>
</table>
 
**MS09-043 참고**

\*Microsoft ISA Server 2004 Standard Edition은 독립 실행형 제품으로 공급됩니다. Microsoft ISA Server 2004 Standard Edition은 Windows Small Business Server 2003 Premium Edition 서비스 팩 1 및 Windows Small Business Server 2003 R2 Premium Edition의 구성 요소로 공급됩니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 하위 섹션을 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://technet.microsoft.com/ko-kr/updatemanagement/default.aspx)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://www.microsoft.com/korea/protect/default.mspx)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**참고** 2009년 8월 1일부터 Microsoft는 Office 업데이트와 Office 업데이트 인벤토리 도구에 대한 지원을 중단합니다. 계속해서 Microsoft Office 제품에 필요한 최신 업데이트를 받으려면 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)를 사용하십시오. 자세한 내용은 [Microsoft Office 업데이트 정보: 자주 제기되는 질문 사항(FAQ) (영문)](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx)을 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](http://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) (영문)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/dd573344.aspx)

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://technet.microsoft.com/security/bulletin/policy)드립니다.

-   MS09-036에서 설명한 문제점을 보고해 주신 [Digitiria (영문)](http://www.digitaria.com/)의 Alexander Pfandt
-   MS09-037에서 설명한 문제점을 처음 보고해 주신 [IBM ISS X-Force (영문)](http://www.iss.net/)의 Ryan Smith 및 Alex Wheeler
-   MS09-037에서 설명한 문제점을 보고해 주신 [IBM ISS X-Force (영문)](http://www.iss.net/)의 Robert Freeman
-   MS09-037에서 설명한 문제점을 보고해 주신 [IBM ISS X-Force (영문)](http://www.iss.net/)의 David Dewey
-   MS09-037에서 설명한 두 가지 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Ryan Smith
-   MS09-038에 설명된 두 가지 문제점을 보고해 주신 [Adobe Systems, Inc. (영문)](http://www.adobe.com/)의 Vinay Anantharaman
-   MS09-039에서 설명한 문제점을 보고해 주신 [TippingPoint (영문)](http://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)
-   MS09-039에 설명한 문제점을 보고해 주신 [National University of Defense Technology (영문)](http://english.nudt.edu.cn/)의 LiGen
-   MS09-040에 설명한 문제점을 보고해 주신 [Positive Technologies Research Team (영문)](http://en.securitylab.ru/lab/)의 Nikita Tarakanov
-   MS09-041에서 설명한 문제점을 보고해 주신 [TippingPoint DVLabs (영문)](http://dvlabs.tippingpoint.com/)의 Cody Pierce
-   MS09-043에서 설명한 두 가지 문제점을 보고해 주신 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)의 Peter Vreugdenhil
-   MS09-043에서 설명한 문제점을 보고해 주신 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)의 Peter Vreugdenhil 및 Fortinet의 [FortiGuard Global Security Research Team (영문)](http://www.fortiguardcenter.com/)에 소속된 Haifei Li
-   MS09-043에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Sean Larsson
-   MS09-044에서 설명한 문제점을 Zero Day Initiative와 협력하여 보고해 주신 [Team509 (영문)](http://www.team509.com/)의 Wushi
-   MS09-044에서 설명한 문제점을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)의 Yamata Li

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 8월 12일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 8월 14일): MS09-044와 관련하여, 공지를 일치시키기 위해 Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3에 대한 RDP 업데이트 목록이 수정되었습니다. MS09-037, MS09-042 및 MS09-044의 다시 시작 요구 사항이 변경되었습니다.
-   V2.0(2009년 8월 26일): MS09-044에서 Windows XP 서비스 팩 2용 RDP 버전 5.2(KB958469)에 대한 다운로드 링크가 수정되었습니다. 또한 KB958471 및 KB958470에 대해 잘못된 설치 단계를 지시하는 각주가 수정되었습니다. 이러한 업데이트를 성공적으로 설치한 고객은 다시 설치할 필요가 없습니다.
-   V3.0(2009년 9월 9일): Microsoft는 Windows XP Media Center Edition 2005 및 지원 대상인 모든 Windows Vista 에디션의 HtmlInput Object ActiveX 컨트롤에 대한 새로운 업데이트를 제공하기 위해 MS09-037을 발표했습니다.
-   V4.0(2009년 10월 28일): Microsoft는 검색 문제를 해결하는 Microsoft Office 2003 서비스 팩 3 및 Microsoft Office 2003 Web Components 서비스 팩 3에 대한 업데이트를 다시 제공하기 위해 MS09-043을 다시 릴리스하였습니다. 이 변경 사항은 검색에만 해당됩니다. 바이너리에 대한 변경 사항은 없습니다. 시스템을 성공적으로 업데이트한 고객은 이 업데이트를 다시 설치할 필요가 없습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
