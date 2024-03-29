---
TOCTitle: 'MS12-FEB'
Title: 2012 년 2 월 Microsoft 보안 공지 요약
ms:assetid: 'ms12-feb'
ms:contentKeyID: 61230748
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms12-feb(v=Security.10)'
---


2012 년 2 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2012년 2월 15일 수요일

**버전:** 1.0

이 공지 요약 목록에는 2012년 2월 발표된 보안 공지가 포함되어 있습니다.

2012년 2월 보안 공지 발표와 함께 이 공지 요약이 2012년 2월 9일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2012년 2월 15일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [2월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499501). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://go.microsoft.com/fwlink/?linkid=217214) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

### 공지 정보

요약
----

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 영향을 받는 소프트웨어 및 다운로드 위치를 참조하십시오.

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms12-008">MS12-008</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 원격 코드 실행 문제점(2660465) <br />
<br />
이 보안 업데이트는 Microsoft Windows의 비공개적으로 보고된 취약점 1건과 공개적으로 보고된 취약점 1건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 콘텐츠를 포함하는 웹 사이트를 방문하거나 특수하게 조작된 응용 프로그램이 로컬에서 실행되고 있을 경우 원격 코드 실행이 허용될 수 있습니다. 공격자는 강제로 사용자가 악의적인 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms12-010">MS12-010</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2647516) <br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 4건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms12-013">MS12-013</a></td>
<td style="border:1px solid black;">C 런타임 라이브러리의 취약점으로 인한 원격 코드 실행 문제점(2654428) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 웹 사이트에서 호스팅되거나 전자 메일 첨부 파일로 전송된 특수하게 조작된 미디어 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 이 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms12-016">MS12-016</a></td>
<td style="border:1px solid black;">.NET Framework 및 Microsoft Silverlight의 취약점으로 인한 원격 코드 실행 문제점(2651026) <br />
<br />
이 보안 업데이트는 Microsoft .NET Framework 및 Microsoft Silverlight의 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 사용자가 XBAP(XAML 브라우저 응용 프로그램) 또는 Silverlight 응용 프로그램을 실행할 수 있는 웹 브라우저를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 이 취약점으로 인해 클라이언트 시스템에서 원격 코드가 실행될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms12-009">MS12-009</a></td>
<td style="border:1px solid black;">Ancillary Function Driver의 취약점으로 인한 권한 상승 문제점(2645640) <br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 공격자가 사용자의 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms12-011">MS12-011</a></td>
<td style="border:1px solid black;">Microsoft SharePoint의 취약점으로 인한 권한 상승 문제점(2663841) <br />
<br />
이 보안 업데이트는 Microsoft SharePoint 및 Microsoft SharePoint Foundation에서 비공개적으로 보고된 취약점 3건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 URL을 클릭하면 권한 상승이나 정보 유출이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms12-012">MS12-012</a></td>
<td style="border:1px solid black;">색 제어판의 취약점으로 인한 원격 코드 실행 문제점(2643719) <br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 1건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 DLL(동적 연결 라이브러리) 파일과 동일한 디렉터리에 있는 합법적인 파일(예: .icm 또는 .icc 파일)을 여는 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms12-014">MS12-014</a></td>
<td style="border:1px solid black;">Indeo 코덱의 취약점으로 인한 원격 코드 실행 문제점(2661637) <br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 1건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 DLL(동적 연결 라이브러리) 파일과 동일한 디렉터리에 있는 합법적인 파일(예: .avi 파일)을 여는 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용에 성공한 공격자는 로그온한 사용자 자격으로 임의 코드를 실행할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 사용자가 관리자 권한의 사용자 권한으로 로그온한 경우 공격자가 영향을 받는 시스템을 완전히 제어할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/bulletin/ms12-015">MS12-015</a></td>
<td style="border:1px solid black;">Microsoft Visio Viewer 2010의 취약점으로 인한 원격 코드 실행 문제점(2663510) <br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 5건을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Visio 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 이러한 취약점을 성공적으로 악용한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259.aspx)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
| 공지 번호                                                                 | 취약점 제목                                              | CVE ID                                                                                 | 최신 소프트웨어 버전에 대한 악용 가능성 평가                                           | 이전 소프트웨어 버전에 대한 악용 가능성 평가                                           | 서비스 거부 악용 가능성 평가 | 주요 정보                                                                                                 |  
|---------------------------------------------------------------------------|----------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|------------------------------|-----------------------------------------------------------------------------------------------------------|  
| [MS12-008](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-008) | 키보드 레이아웃 해제 후 사용 취약점                      | [CVE-2012-0154(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0154) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                    |  
| [MS12-008](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-008) | GDI 액세스 위반 취약점                                   | [CVE-2011-5046(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-5046) | [2](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 구축 어려움 | [2](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 구축 어려움 | 영구                         | 이 취약점은 공개되었습니다.                                                                               |  
| [MS12-009](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-009) | AfdPoll 권한 상승 취약점                                 | [CVE-2012-0148(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0148) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 가능        | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능      | 영구                         | x64는 악용될 수 있으며, x86은 그렇지 않습니다.                                                            |  
| [MS12-009](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-009) | Ancillary Function Driver 권한 상승 취약점               | [CVE-2012-0149(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0149) | 영향 받지 않음                                                                         | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | Windows Server 2003만 영향을 받습니다.                                                                    |  
| [MS12-010](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-010) | HTML 레이아웃 원격 코드 실행 취약점                      | [CVE-2012-0011(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0011) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 임시                         | (없음)                                                                                                    |  
| [MS12-010](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-010) | 널 바이트 정보 유출 취약점                               | [CVE-2012-0012(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0012) | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능      | 영향 받지 않음                                                                         | 해당 사항 없음               | 이는 정보 유출 취약점입니다.                                                                              |  
| [MS12-010](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-010) | VML 원격 코드 실행 취약점                                | [CVE-2012-0155(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0155) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영향 받지 않음                                                                         | 임시                         | (없음)                                                                                                    |  
| [MS12-011](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-011) | inplview.aspx의 XSS 취약점                               | [CVE-2012-0017(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0017) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영향 받지 않음                                                                         | 해당 사항 없음               | (없음)                                                                                                    |  
| [MS12-011](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-011) | themeweb.aspx의 XSS 취약점                               | [CVE-2012-0144(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0144) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영향 받지 않음                                                                         | 해당 사항 없음               | (없음)                                                                                                    |  
| [MS12-011](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-011) | wizardlist.aspx의 XSS 취약점                             | [CVE-2012-0145(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0145) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영향 받지 않음                                                                         | 해당 사항 없음               | (없음)                                                                                                    |  
| [MS12-012](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-012) | 색 제어판의 안전하지 않은 라이브러리 로드 취약점         | [CVE-2010-5082(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-5082) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | 이 취약점은 공개되었습니다.                                                                               |  
| [MS12-013](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-013) | Msvcrt.dll 버퍼 오버플로 취약점                          | [CVE-2012-0150(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0150) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 임시                         | (없음)                                                                                                    |  
| [MS12-014](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-014) | Indeo 오디오 코덱의 안전하지 않은 라이브러리 로드 취약점 | [CVE-2010-3138(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3138) | 영향 받지 않음                                                                         | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | 이 취약점은 공개되었습니다.                                                                               |  
| [MS12-015](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-015) | VSD 파일 형식 레코드 메모리 손상 취약점                  | [CVE-2012-0019(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0019) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영향 받지 않음                                                                         | 해당 사항 없음               | Visio Viewer 2010 및 Visio Viewer 2010 서비스팩 1(유일하게 지원되는 Visio Viewer 버전)에 영향을 미칩니다. |  
| [MS12-015](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-015) | VSD 파일 형식 레코드 메모리 손상 취약점                  | [CVE-2012-0020(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0020) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영향 받지 않음                                                                         | 해당 사항 없음               | Visio Viewer 2010 및 Visio Viewer 2010 서비스팩 1(유일하게 지원되는 Visio Viewer 버전)에 영향을 미칩니다. |  
| [MS12-015](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-015) | VSD 파일 형식 레코드 메모리 손상 취약점                  | [CVE-2012-0136(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0136) | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능      | 영향 받지 않음                                                                         | 해당 사항 없음               | Visio Viewer 2010 및 Visio Viewer 2010 서비스팩 1(유일하게 지원되는 Visio Viewer 버전)에 영향을 미칩니다. |  
| [MS12-015](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-015) | VSD 파일 형식 레코드 메모리 손상 취약점                  | [CVE-2012-0137(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0137) | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능      | 영향 받지 않음                                                                         | 해당 사항 없음               | Visio Viewer 2010 및 Visio Viewer 2010 서비스팩 1(유일하게 지원되는 Visio Viewer 버전)에 영향을 미칩니다. |  
| [MS12-015](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-015) | VSD 파일 형식 레코드 메모리 손상 취약점                  | [CVE-2012-0138(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0138) | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능      | 영향 받지 않음                                                                         | 해당 사항 없음               | Visio Viewer 2010 및 Visio Viewer 2010 서비스팩 1(유일하게 지원되는 Visio Viewer 버전)에 영향을 미칩니다. |  
| [MS12-016](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-016) | .NET Framework 비관리 개체 취약점                        | [CVE-2012-0014(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0014) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                                                                                    |  
| [MS12-016](http://technet.microsoft.com/ko-kr/security/bulletin/ms12-016) | .NET Framework 힙 손상 취약점                            | [CVE-2012-0015(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0015) | 영향 받지 않음                                                                         | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | 이 취약점은 공개되었습니다.                                                                               |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="8">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=832afe5e-d61e-4554-b889-9174df042b32&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=a7d59fa8-0a49-4985-9f14-92218d3b5cea&displaylang=ko)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6025c5d6-696c-49cd-9264-96af5766d318&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5b37f5b1-207f-4fa1-9769-c873d672e80c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59&displaylang=ko)  
(KB2633880)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=32e5c9ad-b610-4afb-b6f0-bb0b5fbdd1f6&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ff2c141c-08b4-42c6-9f66-580f8678c01f)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=96d404e7-8928-494e-8a3c-3897817cda7b)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b40bc334-edbc-48d5-9196-b7fb0e19966e)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2fc9d519-94b3-4b56-92fd-4c0ccf8210fe)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=82f5c503-d2ea-4fed-8f9d-f30bee2f60b3)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f0e6e06d-89db-45ad-9660-7959c6f9b546&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=c4642890-2fba-45da-bbe9-fcaa84e4aa0c&displaylang=ko)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9e157b88-2c11-44dc-b13d-1051f9c39890&displaylang=ko)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=bf8ad019-e710-4e16-be4f-8168df5c5343&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59&displaylang=ko)  
(KB2633880)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5ee4bef7-b355-4aae-8bba-834a16d44744&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b81decda-9d82-4ffb-baae-78b190e553ea&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=c4a52801-55b5-4eef-9db3-c29a45863198&displaylang=ko)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f162ad36-c096-43ba-a440-ec4d3fb54c21&displaylang=ko)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ef4a9002-b2da-40af-abc0-737565fea179&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59&displaylang=ko)  
(KB2633880)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b53cf810-0ea3-4cb0-91f9-de1406ccfc96&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=8dcd71c8-82ad-4f86-b386-7f1ea09e157f)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=3b42f935-7f59-4871-a01f-480033c3ad40)  
(심각도 없음<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=24fe7c08-4736-455b-9b98-1b6a65718143)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5269e18b-d4f0-4c64-8df8-283a2ca66c59)  
(KB2633880)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3b18d22d-e192-498b-a105-b946a5f5bfad)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5852118c-fc39-45e2-8b44-ce1401d310e2&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6ec23c7e-0166-47dc-ae86-c49b505206bb&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=bbf627df-0bc0-478f-aa34-a7e5f039e589&displaylang=ko)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=d287496a-411c-4c1b-9d98-bacc553041ae&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c503c7b1-24f8-40a4-8283-c1e4abf90b57&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7&displaylang=ko)  
(KB2633874)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5161d16d-1037-49d5-8d4d-c353288cb41c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b30a8cc5-b9ad-476f-928c-c49c993d0e80&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3a8b966a-bf34-42fd-8758-9a5e8e3c7689&displaylang=ko)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=22cc0245-1877-4c76-914f-dd68f6cd45f0&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ddbd9fcf-10c4-4089-88c0-c2a6c288222b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7&displaylang=ko)  
(KB2633874)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=73e240a6-2d5e-4ceb-8500-8dacca0e4a43&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=45c6c511-a4fa-4c3b-af26-6c113f6f5f5e&displaylang=ko)\*\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=21f7dba4-fe97-487e-8b37-45914e106db0&displaylang=ko)\*\*  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=98d5b024-0eda-4e5d-ba9d-b828ad3d048e&displaylang=ko)\*\*  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=025a5af0-39f1-481c-920c-43d2b3d85dc5&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0c1812af-f57d-455d-a81d-5e03db99b2f7&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7&displaylang=ko)  
(KB2633874)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3f6f89b3-3bc8-4325-b8d8-9a5a398b99c6&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=046932cf-0671-49e6-8ddf-98abfc97c5f0&displaylang=ko)\*\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2cd8e296-dae8-41ce-8373-f8a71b4555e9&displaylang=ko)\*\*  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=246f9995-fe19-43d0-8f67-0e91eb961bab&displaylang=ko)\*\*  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c216e01d-2f46-4a46-bdc7-9d0fe98193a3&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e1b66bb5-ea12-44a5-807a-f21ede0dc76d&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7&displaylang=ko)  
(KB2633874)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0e06e77d-7e5d-4d57-98b2-0817f68a1ebb&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=35e6bd04-594f-42ef-97f8-abcf578b4f10&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=304bd0c5-f4ee-4f8c-89b4-4cbaaf418679)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=05c0e6eb-c641-43ab-958a-f43933cdbba7)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3a96ab34-8f45-48bf-a98b-9e683b50aaa0)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aab7826d-539b-4e36-b3a1-afa94b37dbe7)  
(KB2633874)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=56cbeba9-0c39-4418-9042-7244ac9d03db)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d1d51b26-2d01-42a9-9bb1-9fb82c1fb914)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=3e5ca1bf-9415-412c-9dff-dd1abc57e74d&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8b423683-cd29-4049-82d6-f0845842e7f0&displaylang=ko)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c83a9c74-a5a7-4b3e-ba36-7a7024d99fd8&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=403f355c-2273-42ac-8263-d662f5d7740c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc&displaylang=ko)  
(KB2633879)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5&displaylang=ko)  
(KB2633873)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=78cbbe02-a3d3-4cef-9b54-a3e78c1b885a&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a5d00138-4e24-4a07-92dd-3d8a14476197&displaylang=ko)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bbc9d6ae-9ec5-401f-bf16-4811b63709d1&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=8bd8e804-ca4d-4326-bc60-345e2975b7aa&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc&displaylang=ko)  
(KB2633879)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5&displaylang=ko)  
(KB2633873)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=299d107d-ab9f-42b6-8f94-a2f1d242c127&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-008](http://go.microsoft.com/fwlink/?linkid=238387)
</td>
<td style="border:1px solid black;">
[MS12-010](http://go.microsoft.com/fwlink/?linkid=236989)
</td>
<td style="border:1px solid black;">
[MS12-013](http://go.microsoft.com/fwlink/?linkid=238617)
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
<td style="border:1px solid black;">
[MS12-009](http://go.microsoft.com/fwlink/?linkid=238474)
</td>
<td style="border:1px solid black;">
[MS12-012](http://go.microsoft.com/fwlink/?linkid=239941)
</td>
<td style="border:1px solid black;">
[MS12-014](http://go.microsoft.com/fwlink/?linkid=239945)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=6b228ad6-d5a4-4b91-8aa8-0874deb22116&displaylang=ko)\*\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3074a898-54bb-44ff-a8f4-77f831c28771&displaylang=ko)\*\*  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=1896a6da-f7ee-484b-a97c-455fce7b82b8&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=d868c5ef-165a-46a0-b832-e6ca55a910f9&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc&displaylang=ko)\*  
(KB2633879)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용)만 해당:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)<sup>[1]</sup>
(KB2633870)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5&displaylang=ko)\*  
(KB2633873)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119&displaylang=ko)\*<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=576192d3-f050-4718-a7da-c84fce6bf744&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=8c51e09b-51c3-4860-836e-6bcffde75f04&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=922b2438-0cfc-49e3-b9a0-52c68b69126a)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7f7c0bc3-fc26-4ee8-aedb-c251247cbeb5)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=e5416371-495b-4dc7-a239-f9185f968969)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)만 해당:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5a5f3ee7-ca49-41c8-aeec-7c76b66712fc)  
(KB2633879)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1만 해당:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=243e8c64-8b6e-4cea-9e99-58d4b1ad35b5)  
(KB2633873)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=70aadf34-abdc-4577-8da9-a0669dccc119)<sup>[1]</sup>
(KB2633870)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=d6a9b2c9-7582-4953-8ab1-a55c63fcc8dc)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=fba58a1b-9d9f-4a10-b1df-08a0ebfa2358)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
Windows Server 2008 및 Windows Server 2008 R2 참고 사항

\*Server Core 설치가 영향을 받습니다. 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*Server Core 설치는 영향을 받지 않습니다. Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*\*\*Server Core 설치가 영향을 받습니다. 이 업데이트는 Server Core 설치 옵션을 사용하여 설치할 때 더 낮은 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

MS12-010 참고 사항

<sup>[1]</sup>이 공지에서 설명한 취약점에 대해 알려진 공격 경로가 기본 구성으로 차단되므로 지정된 소프트웨어에 대한 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 심층적인 보안 대응책으로써 이 소프트웨어를 사용하는 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

MS12-016참고 사항

<sup>[1]</sup>.NET Framework 4 and .NET Framework 4 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4 및 .NET Framework 4 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4 Client Profile은 .NET Framework 4의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4 및 .NET Framework 4 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, [.NET Framework 설치](http://msdn.microsoft.com/ko-kr/library/5a4x27ek.aspx)를 참조하십시오.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-015](http://go.microsoft.com/fwlink/?linkid=238400)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 및 Microsoft Visio Viewer 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 및 Microsoft Visio Viewer 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=173dc4e6-31b4-42ec-808c-f8cd005517ab&displaylang=ko)  
(KB2597170)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 및 Microsoft Visio Viewer 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 및 Microsoft Visio Viewer 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=34b234e1-1322-4edc-829c-7bc2fbd99338&displaylang=ko)  
(KB2597170)  
(중요)
</td>
</tr>
</table>
 

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-011](http://go.microsoft.com/fwlink/?linkid=238500)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 및 Microsoft SharePoint Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 및 Microsoft SharePoint Server 2010 서비스 팩 1(moss)](http://www.microsoft.com/downloads/details.aspx?familyid=44a8eb5a-e469-4d36-b5a0-7e030c1d3244&displaylang=ko)  
(KB2597124)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-011](http://go.microsoft.com/fwlink/?linkid=238500)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 및 Microsoft SharePoint Foundation 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 및 Microsoft SharePoint Foundation 2010 서비스 팩 1(sts)](http://www.microsoft.com/downloads/details.aspx?familyid=dd348109-953b-4154-b265-85e4694238e6&displaylang=ko)  
(KB2553413)  
(중요)
</td>
</tr>
</table>
 

#### Microsoft 개발자 도구 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-016](http://go.microsoft.com/fwlink/?linkid=235370)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
Mac에 설치된 [Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c3602f0-9781-4374-8fef-669ddd2c0d40&displaylang=ko)  
(KB2668562)  
(긴급)  
지원 대상인 모든 Microsoft Windows 클라이언트 릴리스에 설치된 [Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c3602f0-9781-4374-8fef-669ddd2c0d40&displaylang=ko)  
(KB2668562)  
(긴급)  
지원 대상인 모든 Microsoft Windows 서버 릴리스에 설치된 [Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c3602f0-9781-4374-8fef-669ddd2c0d40&displaylang=ko)  
(KB2668562)  
(긴급)
</td>
</tr>
</table>
 
MS12-016참고사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

검색 및 배포 지침

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

Microsoft Baseline Security Analyzer

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

Windows Server Update Services

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services(영문)](http://technet.microsoft.com/ko-kr/wsus/default.aspx)를 참조하십시오.

System Center Configuration Manager 2007

Configuration Manager 2007 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. Configuration Manager 2007을 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

Configuration Manager 2007의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. Configuration Manager 2007의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 Configuration Manager 2007을 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)를 방문하십시오.

Systems Management Server 2003

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

참고 System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다(이전 섹션의 System Center Configuration Manager 2007 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=ko)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter(영문)](http://technet.microsoft.com/ko-kr/systemcenter/bb545936.aspx)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ko)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) (영문)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199)
-   : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/wsus/bb456965.aspx)
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너(영문)](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

업데이트 관리 전략

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

기타 보안 관련 업데이트 받기

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS12-008에서 설명한 문제점을 보고해 주신[Azimuth Security(영문)](http://www.azimuthsecurity.com/)의 Tarjei Mandt
-   MS12-009에서 설명한 문제점 2건을 보고해 주신Azimuth Security(영문)의 Tarjei Mandt
-   MS12-010에서 설명한 문제점을 보고해 주신 [Jan Schejbal(영문)](http://janschejbal.wordpress.com/)
-   MS12-010에서 설명한 문제점 2건을 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하며 보고해 주신 [Harmony Security(영문)](http://www.harmonysecurity.com/)의 Stephen Fewer
-   MS12-010에서 설명한 문제점을 보고해 주신 [HP Cloud Services(영문)](http://www.hpcloud.com/)의 Jason Hullinger
-   MS12-011에서 설명한 문제점을 보고해 주신 John Hollenberger
-   MS12-011에서 설명한 문제점을 보고해 주신 stratsec의 Rocco Calvi
-   MS12-011의 심층 보안 업데이트에 대해 협력해 주신 Minded Security의 Giorgio Fedon
-   MS12-013에서 설명한 문제점을 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Alexander Gavrun
-   MS12-015에서 설명한 다섯 가지 문제점을 보고해 주신 [Palo Alto Networks(영문)](http://www.paloaltonetworks.com/)의 Xin Ouyang
-   MS12-016에서 설명한 문제점을 보고해 주신 [Sumatra(영문)](http://www.sumatra.nl/)의 Jeroen Frijters

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2012년 2월 15일): 공지 요약이 게시되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
