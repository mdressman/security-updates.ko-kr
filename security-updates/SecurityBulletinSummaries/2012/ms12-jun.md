---
TOCTitle: 'MS12-JUN'
Title: 2012 년 6 월 Microsoft 보안 공지 요약
ms:assetid: 'ms12-jun'
ms:contentKeyID: 61230751
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms12-jun(v=Security.10)'
---


2012 년 6 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2012년 6월 13일 수요일

**버전:** 1.0

이 공지 요약 목록에는 2012년 6월 발표된 보안 공지가 포함되어 있습니다.

2012년 6월 보안 공지 발표와 함께 이 공지 요약이 2012년 6월 7일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2012년 6월 13일 오전 11시(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [6월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499671). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://go.microsoft.com/fwlink/?linkid=217214) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246927">MS12-036</a></td>
<td style="border:1px solid black;">원격 데스크톱의 취약점으로 인한 원격 코드 실행 문제점(2685939) <br />
<br />
이 보안 업데이트는 원격 데스크톱 프로토콜의 비공개적으로 보고된 취약점을 해결합니다. 공격자가 영향을 받는 시스템에 특수하게 조작된 일련의 RDP 패킷을 보낼 경우 이 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 기본적으로 RDP(원격 데스크톱 프로토콜)은 모든 Windows 운영 체제에서 사용되도록 설정되어 있지는 않습니다. RDP가 사용 가능하지 않는 시스템은 취약하지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=249045">MS12-037</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2699988) <br />
<br />
이 보안 업데이트는 Internet Explorer의 공개된 취약점 1건과 비공개로 보고된 취약점 12건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251095">MS12-038</a></td>
<td style="border:1px solid black;">.NET Framework의 취약점으로 인한 원격 코드 실행 문제점(2706726) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft .NET Framework의 취약점 한 가지를 해결합니다. 사용자가 XBAP(XAML 브라우저 응용 프로그램)을 실행할 수 있는 웹 브라우저를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 이 취약점으로 인해 클라이언트 시스템에서 원격 코드가 실행될 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 이 취약점은 CAS(코드 액세스 보안) 제한을 우회하기 위해 Windows .NET 응용 프로그램에서 사용될 수도 있습니다. 웹 탐색을 통한 공격의 경우 공격자는 호스팅하는 웹 사이트에 이 취약점을 악용하는 웹 페이지를 포함할 수 있습니다. 또한 사용자가 제공한 콘텐츠나 광고를 허용하거나 호스팅하는 공격 당한 웹 사이트에는 이 취약점을 악용할 수 있는 특수하게 조작된 콘텐츠가 포함되어 있을 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252488">MS12-039</a></td>
<td style="border:1px solid black;">Lync의 취약점 으로 인한 원격 코드 실행 문제점(2707956) <br />
<br />
이 보안 업데이트는 Microsoft Lync의 공개된 취약점 1건과 비공개로 보고된 취약점 3건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 TrueType 글꼴이 포함된 공유 콘텐츠를 볼 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251612">MS12-040</a></td>
<td style="border:1px solid black;">Microsoft Dynamics AX Enterprise Portal의 취약점으로 인한 권한 상승 문제점(2709100) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Dynamics AX Enterprise Portal의 취약점 1건을 해결합니다. 취약점으로 인해 사용자가 특수하게 조작된 URL을 클릭하거나 특수하게 조작된 웹 사이트를 방문할 경우 권한 상승 문제가 발생할 수 있습니다. 전자 메일을 통한 공격의 경우 공격자는 특수하게 조작한 URL이 포함된 메일 메시지를 대상 Microsoft Dynamics AX Enterprise Portal 사이트의 사용자에게 보내고 특수하게 조작된 URL을 클릭하도록 유도하는 방식으로 취약점을 악용할 수 있습니다. 인터넷 영역에서 Microsoft Dynamics AX Enterprise Portal 사이트로 이동하는 Internet Explorer 8 및 Internet Explorer 9 사용자는 위험 발생률이 낮습니다. 기본적으로 Internet Explorer 8 및 Internet Explorer 9의 XSS 필터가 인터넷 영역에서 이러한 공격을 방지합니다. 하지만 Internet Explorer 8 및 Internet Explorer 9의 XSS 필터는 인트라넷 영역에서 기본적으로 사용되지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Dynamics AX</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251707">MS12-041</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2709162) <br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 5건을 해결합니다. 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이러한 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252515">MS12-042</a></td>
<td style="border:1px solid black;">Windows 커널의 취약점으로 인한 권한 상승 문제점(2711167) <br />
<br />
이 보안 업데이트는 Microsoft Windows의 비공개적으로 보고된 취약점 1건과 공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점으로 인해 공격자가 영향을 받는 시스템에 로그온한 후 이 취약점을 악용하기 위해 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259.aspx)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
| 공지 번호                                                 | 취약점 제목                                     | CVE ID                                                                                 | 최신 소프트웨어 버전에 대한 악용 가능성 평가                                      | 이전 소프트웨어 버전에 대한 악용 가능성 평가                                      | 서비스 거부 악용 가능성 평가 | 주요 정보                                                                                                        |  
|-----------------------------------------------------------|-------------------------------------------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|------------------------------|------------------------------------------------------------------------------------------------------------------|  
| [MS12-036](http://go.microsoft.com/fwlink/?linkid=246927) | 원격 데스크톱 프로토콜 취약점                   | [CVE-2012-0173](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0173)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영구                         | (없음)                                                                                                           |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | Center 요소 원격 코드 실행 취약점               | [CVE-2012-1523](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1523)(영문) | 영향 받지 않음                                                                    | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 임시                         | (없음)                                                                                                           |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | HTML 삭제 취약점                                | [CVE-2012-1858](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858)(영문) | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능 | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능 | 해당 사항 없음               | 이는 정보 유출 취약점입니다. [MS12-039](http://go.microsoft.com/fwlink/?linkid=252488)도 이 취약점을 해결합니다. |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | 널 바이트 정보 유출 취약점                      | [CVE-2012-1873](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1873)(영문) | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능 | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능 | 해당 사항 없음               | 이는 정보 유출 취약점입니다.                                                                                     |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | 개발자 도구 모음 원격 코드 실행 취약점          | [CVE-2012-1874](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1874)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능 | 임시                         | (없음)                                                                                                           |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | 동일한 ID 속성 원격 코드 실행 취약점            | [CVE-2012-1875](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1875)(영문) | 영향 받지 않음                                                                    | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 임시                         | Microsoft는 이 취약점을 악용하려는 제한된 공격에 대한 보고를 받았습니다.                                         |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | Col 요소 원격 코드 실행 취약점                  | [CVE-2012-1876](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1876)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 임시                         | (없음)                                                                                                           |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | Title 요소 변경 원격 코드 실행 취약점           | [CVE-2012-1877](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1877)       | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 임시                         | (없음)                                                                                                           |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | OnBeforeDeactivate 이벤트 원격 코드 실행 취약점 | [CVE-2012-1878](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1878)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 임시                         | (없음)                                                                                                           |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | insertAdjacentText 원격 코드 실행 취약점        | [CVE-2012-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1879)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 임시                         | (없음)                                                                                                           |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | insertRow 원격 코드 실행 취약점                 | [CVE-2012-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1880)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 임시                         | (없음)                                                                                                           |  
| [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) | OnRowsInserted 이벤트 원격 코드 실행 취약점     | [CVE-2012-1881](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1881)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 임시                         | (없음)                                                                                                           |  
| [MS12-038](http://go.microsoft.com/fwlink/?linkid=251095) | .NET Framework 메모리 액세스 취약점             | [CVE-2012-1855](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1855)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 해당 사항 없음               | (없음)                                                                                                           |  
| [MS12-039](http://go.microsoft.com/fwlink/?linkid=252488) | TrueType 글꼴 구문 분석 취약점                  | [CVE-2011-3402](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402)(영문) | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능 | 영향 받지 않음                                                                    | 영구                         | 이 취약점은 공개되었습니다.                                                                                      |  
| [MS12-039](http://go.microsoft.com/fwlink/?linkid=252488) | TrueType 글꼴 구문 분석 취약점                  | [CVE-2012-0159](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159)(영문) | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능 | 영향 받지 않음                                                                    | 영구                         | (없음)                                                                                                           |  
| [MS12-039](http://go.microsoft.com/fwlink/?linkid=252488) | Lync의 안전하지 않은 라이브러리 로드 취약점     | [CVE-2012-1849](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1849)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영향 받지 않음                                                                    | 해당 사항 없음               | (없음)                                                                                                           |  
| [MS12-039](http://go.microsoft.com/fwlink/?linkid=252488) | HTML 삭제 취약점                                | [CVE-2012-1858](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858)(영문) | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능 | [3](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 불가능 | 해당 사항 없음               | 이는 정보 유출 취약점입니다. [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045)도 이 취약점을 해결합니다. |  
| [MS12-040](http://go.microsoft.com/fwlink/?linkid=251612) | Dynamic AX Enterprise Portal XSS 취약점         | [CVE-2012-1857](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1857)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영향 받지 않음                                                                    | 해당 사항 없음               | (없음)                                                                                                           |  
| [MS12-041](http://go.microsoft.com/fwlink/?linkid=251707) | 문자열 Atom 클래스 이름 처리 취약점             | [CVE-2012-1864](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1864)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영구                         | (없음)                                                                                                           |  
| [MS12-041](http://go.microsoft.com/fwlink/?linkid=251707) | 문자열 Atom 클래스 이름 처리 취약점             | [CVE-2012-1865](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1865)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영구                         | (없음)                                                                                                           |  
| [MS12-041](http://go.microsoft.com/fwlink/?linkid=251707) | 클립보드 형식 Atom 이름 처리 취약점             | [CVE-2012-1866](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1866)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영구                         | (없음)                                                                                                           |  
| [MS12-041](http://go.microsoft.com/fwlink/?linkid=251707) | 글꼴 리소스 Refcount 정수 오버플로 취약점       | [CVE-2012-1867](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1867)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영구                         | (없음)                                                                                                           |  
| [MS12-041](http://go.microsoft.com/fwlink/?linkid=251707) | Win32k.sys 경쟁 조건 취약점                     | [CVE-2012-1868](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1868)(영문) | 영향 받지 않음                                                                    | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영구                         | (없음)                                                                                                           |  
| [MS12-042](http://go.microsoft.com/fwlink/?linkid=252515) | User Mode Scheduler 메모리 손상 취약점          | [CVE-2012-0217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0217)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영향 받지 않음                                                                    | 영구                         | (없음)                                                                                                           |  
| [MS12-042](http://go.microsoft.com/fwlink/?linkid=252515) | BIOS ROM 손상 취약점                            | [CVE-2012-1515](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1515)(영문) | 영향 받지 않음                                                                    | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능   | 영구                         | 이 취약점은 공개되었습니다.                                                                                      |
  
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
<th style="border:1px solid black;" colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-036](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[MS12-037](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[MS12-038](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[MS12-041](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[MS12-042](http://go.microsoft.com/fwlink/?linkid=252515)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=fd2216eb-283b-4a23-b259-018a7fa5fe47&displaylang=ko)  
(KB2685939)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7f222e05-2a8d-4099-851f-2044811f7425&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=07c75ac6-f92a-4204-aa58-bdf8c033df9e&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5bc1656f-cf1d-4f77-a078-a8602401b8e1&displaylang=ko)  
(KB2699988)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f&displaylang=ko)  
(KB2686828)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=a399bd47-ffe1-4476-932c-9c119496222a&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=0efff733-4c8d-4fce-8de3-28465c6b762b&displaylang=ko)  
(KB2707511)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e354955-32ae-447c-b16f-960acc01773b)  
(KB2685939)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=57e8bf9d-97c3-4166-a5d4-6b0c99afc6a1)  
(KB2699988)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b35e90b-145d-44c2-a8bc-4f9108d46fa1)  
(KB2699988)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0a386b16-74f7-4d36-93d0-75e7da9bf9b5)  
(KB2699988)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdb356db-bd36-4159-8e64-ecdb3dfc61bf)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-036](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[MS12-037](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[MS12-038](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[MS12-041](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[MS12-042](http://go.microsoft.com/fwlink/?linkid=252515)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e856fec-9f05-49b7-91b6-11c2636a2f1d&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b1dcc826-7e96-464b-830e-39946e7802aa&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=de828031-1ace-43df-80f2-db7d503fb0a2&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4e6e5589-b767-4e8a-b8b3-df7b97e002e5&displaylang=ko)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f&displaylang=ko)  
(KB2686828)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0b39b00-d7db-4008-8310-1258e84a72a2&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=855611a1-91ad-4d22-8c1c-fdcd6af4cef0&displaylang=ko)  
(KB2707511)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9b63fa4d-b42e-43ca-9f2c-cf60c37731a5&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b060e03b-e63e-446b-9cfd-ea4e1e9383a6&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a36f7ffe-d537-4f9e-b676-22a24f50c089&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b1acb2f0-63ba-4524-94cf-42b3534e21e7&displaylang=ko)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f&displaylang=ko)  
(KB2686828)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ed7359ce-13e8-42b2-956d-e8be534583aa&displaylang=ko)  
(KB2709162)  
(중요)
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
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=7dfdc5dc-54b0-49e3-bf5a-bbc40b0f159f)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=893667c4-ef9f-48d3-ab18-a0df51bd3dcc)  
(KB2699988)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=30a9d518-8067-44f4-90fd-09fec8a0c883)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=2317c8d9-cae8-497b-952e-78eb4a6d585c)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-036](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[MS12-037](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[MS12-038](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[MS12-041](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[MS12-042](http://go.microsoft.com/fwlink/?linkid=252515)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
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
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f55b62bf-0571-4888-9061-3f7cc75d7f17&displaylang=ko)  
(KB2685939)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=16f4404e-e6d6-4bde-af15-3bb692412213&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=610e753a-21db-43e6-bc42-3e1227fa4bb1&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=828fdb71-747b-481d-9683-895325331478&displaylang=ko)  
(KB2699988)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b&displaylang=ko)  
(KB2686833)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9188f1eb-b568-4a99-9b39-745c760a693d&displaylang=ko)  
(KB2709162)  
(중요)
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
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ab06290c-4f57-4349-8abd-a382b9044631&displaylang=ko)  
(KB2685939)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=993c5bc4-8903-4c8c-bbc9-da2e47d959f9&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=87100a7e-7feb-4a18-b7aa-04fdd2d6ef52&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7b551d67-e0f1-498a-ac4f-06376a0fcf18&displaylang=ko)  
(KB2699988)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b&displaylang=ko)  
(KB2686833)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b94ae42-2882-444c-ad5e-74e34b805006&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-036](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[MS12-037](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[MS12-038](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[MS12-041](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[MS12-042](http://go.microsoft.com/fwlink/?linkid=252515)
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
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e7f9ad40-d515-4224-90ff-4bd4bff9180f&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c4eaeff8-7b7a-4418-a479-09b2146df2bf&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=a20c839c-ce3b-46a5-becb-588de404878d&displaylang=ko)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b&displaylang=ko)  
(KB2686833)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745&displaylang=ko)  
(KB2709162)  
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
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7420c9f3-8f7e-4823-aaba-b14b957408d8&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fd5308b7-7430-4713-922c-f06c46886fad&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=1a737d87-0689-470b-8fc0-8c874af18794&displaylang=ko)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b&displaylang=ko)  
(KB2686833)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2&displaylang=ko)  
(KB2709162)  
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
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c4b8af1c-b483-4aed-9be5-b0f1698b2c28)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=472842c4-5fe7-4d4c-a927-05be030b5b4e)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=098607b3-9424-4440-8832-fc1de010977e)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-036](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[MS12-037](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[MS12-038](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[MS12-041](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[MS12-042](http://go.microsoft.com/fwlink/?linkid=252515)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef&displaylang=ko)  
(KB2685939)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620&displaylang=ko)  
(KB2699988)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236&displaylang=ko)  
(KB2686830)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620&displaylang=ko)  
(KB2699988)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b&displaylang=ko)  
(KB2686831)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07&displaylang=ko)  
(KB2685939)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503&displaylang=ko)  
(KB2699988)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236&displaylang=ko)  
(KB2686830)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb&displaylang=ko)  
(KB2709715)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1&displaylang=ko)  
(KB2699988)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503&displaylang=ko)  
(KB2699988)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b&displaylang=ko)  
(KB2686831)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb&displaylang=ko)  
(KB2709715)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-036](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[MS12-037](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[MS12-038](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[MS12-041](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[MS12-042](http://go.microsoft.com/fwlink/?linkid=252515)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf&displaylang=ko)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236&displaylang=ko)  
(KB2686830)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c&displaylang=ko)  
(KB2709715)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929&displaylang=ko)  
(KB2699988)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf&displaylang=ko)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b&displaylang=ko)  
(KB2686831)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c&displaylang=ko)  
(KB2709715)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c)  
(KB2699988)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="6">
Server Core 설치 옵션
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-036](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[MS12-037](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[MS12-038](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[MS12-041](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[MS12-042](http://go.microsoft.com/fwlink/?linkid=252515)
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
없음
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236&displaylang=ko)  
(KB2686830)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c&displaylang=ko)  
(KB2709715)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266&displaylang=ko)  
(KB2685939)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b&displaylang=ko)  
(KB2686831)  
(긴급)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145&displaylang=ko)<sup>[1]</sup>
(KB2686827)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8&displaylang=ko)  
(KB2709162)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c&displaylang=ko)  
(KB2709715)  
(중요)
</td>
</tr>
</table>
 
MS12-038 참고 사항

<sup>[1]</sup>.NET Framework 4 and .NET Framework 4 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4 및 .NET Framework 4 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4 Client Profile은 .NET Framework 4의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4 및 .NET Framework 4 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, [.NET Framework 설치](http://msdn.microsoft.com/ko-kr/library/5a4x27ek.aspx)를 참조하십시오.

#### Microsoft Communications Platforms and Software

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Communicator
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-039](http://go.microsoft.com/fwlink/?linkid=252488)
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
Microsoft Communicator 2007 R2
</td>
<td style="border:1px solid black;">
[Microsoft Communicator 2007 R2](http://www.microsoft.com/downloads/details.aspx?familyid=75eea324-689a-4892-bdd9-03ef399c4cba&displaylang=ko)  
(KB2708980)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Lync
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-039](http://go.microsoft.com/fwlink/?linkid=252488)
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
Microsoft Lync 2010(32비트)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010(32비트)](http://www.microsoft.com/downloads/details.aspx?familyid=425406ea-28b9-46f7-8c49-0c7ea46f16e3&displaylang=ko)  
(KB2693282)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010(64비트)](http://www.microsoft.com/downloads/details.aspx?familyid=06e5285f-1947-4409-b608-e0a145fadba4&displaylang=ko)  
(KB2693282)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendee](http://www.microsoft.com/downloads/details.aspx?familyid=c40f0d38-af90-4966-a0f0-346fa48683d0&displaylang=ko)  
(관리자 수준 설치)  
(KB2696031)  
(중요)  
[Microsoft Lync 2010 Attendee](http://www.microsoft.com/downloads/details.aspx?familyid=ad864c0e-5850-44a3-b74f-5980a998a384&displaylang=ko)<sup>[1]</sup>
(사용자 수준 설치)  
(KB2693283)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendant(32비트)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendant(32비트)](http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053&displaylang=ko)  
(KB2702444)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendant(64비트)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendant(64비트)](http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053&displaylang=ko)  
(KB2702444)  
(중요)
</td>
</tr>
</table>
 
MS12-039 참고 사항

<sup>[1]</sup>이 업데이트는 Microsoft 다운로드 센터에서만 다운로드할 수 있습니다

#### Microsoft Enterprise Resource Planning (ERP) Solutions

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Dynamics ERP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-040](http://go.microsoft.com/fwlink/?linkid=251612)
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
Microsoft Dynamics AX 2012
</td>
<td style="border:1px solid black;">
[Microsoft Dynamics AX 2012 Enterprise Portal](http://www.microsoft.com/downloads/details.aspx?familyid=45df362d-8fed-4d99-91c1-81c61878300a)<sup>[1]</sup>
(KB2706738)  
(중요)  
[Microsoft Dynamics AX 2012 Enterprise Portal](http://www.microsoft.com/downloads/details.aspx?familyid=780ddcef-19da-44c4-beca-d10b652cd22a)<sup>[1]</sup>
(KB2710639)  
(중요)  
[Microsoft Dynamics AX 2012 Enterprise Portal](http://www.microsoft.com/downloads/details.aspx?familyid=41dc5958-c224-40f9-89c2-179607a8ee2a)<sup>[1]</sup>
(KB2711239)  
(중요)
</td>
</tr>
</table>
 
MS12-040 참고 사항

<sup>[1]</sup>이 업데이트는 Microsoft 다운로드 센터, Microsoft Dynamics CustomerSource 및 Microsoft Dynamics PartnerSource 웹 사이트에서만 제공됩니다.

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

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://technet.microsoft.com/ko-kr/wsus/default.aspx)(영문)를 참조하십시오.

System Center Configuration Manager

System Center Configuration Manager 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. System Center Configuration Manager를 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

System Center Configuration Manager의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. System Center Configuration Manager의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 System Center Configuration Manager를 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. System Center Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)를 방문하십시오.

Systems Management Server 2003

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

참고 System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager를 지금 사용할 수 있습니다(이전 섹션의 System Center Configuration Manager 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)(영문)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (영문)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (영문)구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199)
-   : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

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

-   MS12-037에서 설명한 문제점을 [VeriSign iDefense Labs](http://labs.idefense.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS12-037에서 설명한 문제점을 보고해 주신 [IBM Security Systems - Application Security](http://blog.watchfire.com/)(영문)의 Adi Cohen
-   MS12-037에서 설명한 문제점을 보고해 주신 Masato Kinugawa
-   MS12-037에서 설명한 문제점을 보고해 주신 LinkedIn의 Roman Shafigullin
-   MS12-037에서 설명한 문제점을 보고해 주신 [VulnHunt](http://www.vulnhunt.com)(영문)의 Code Audit Labs
-   MS12-037에서 설명한 문제점을 보고해 주신 [VulnHunt](http://www.vulnhunt.com)(영문)의 Dark Son
-   MS12-037에서 설명한 문제점을 해결하기 위해 협력해 주신 [Qihoo 360 Security Center](http://www.360.cn/)(영문)
-   MS12-037에서 설명한 문제점을 해결하기 위해 협력해 주신 McAfee Labs의 Yichong Lin
-   MS12-037에서 설명한 문제점을 해결하기 위해 협력해 주신 [Google Inc(영문).](http://www.google.com/)
-   MS12-037에서 설명한 문제점을 [TippingPoint](http://www.tippingpoint.com/)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 [VUPEN Security](http://www.vupen.com)(영문)
-   MS12-037에서 설명한 문제점을 [TippingPoint](http://www.tippingpoint.com/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS12-037에서 설명한 문제점을 [TippingPoint](http://www.tippingpoint.com/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS12-037에서 설명한 문제점을 [TippingPoint](http://www.tippingpoint.com/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS12-037에서 설명한 문제점을 [TippingPoint](http://www.tippingpoint.com/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS12-037에서 설명한 문제점을 [TippingPoint](http://www.tippingpoint.com/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   MS12-038에서 설명한 문제점을 [Tipping Point](http://www.tippingpoint.com/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Vitaliy Toropov
-   MS12-039에서 설명한 문제점을 보고해 주신 Secunia SVCRP의 hamburgers maccoy
-   MS12-039에서 설명한 문제점을 보고해 주신 [IBM Security Systems - Application Security](http://blog.watchfire.com/)(영문)의 Adi Cohen
-   MS12-039에서 설명한 문제점을 [Tipping Point](http://www.tippingpoint.com/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Alin Rad Pop
-   MS12-040에서 설명한 문제점을 보고해 주신 Finian Mackin
-   MS12-041에서 설명한 문제점 3건을 보고해 주신[Azimuth Security](http://www.azimuthsecurity.com/)(영문)의 Tarjei Mandt
-   MS12-041에서 설명한 문제점을 보고해 주신 [Google Inc(영문).](http://www.google.com)의 [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org)(영문)
-   MS12-042에서 설명한 문제점을 보고해 주신 [Bromium](http://www.bromium.com/)(영문)의 Rafal Wojtczuk과 [SUSE](http://www.suse.com/)(영문)의 Jan Beulich

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617.aspx)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2012년 6월 13일): 공지 요약이 게시되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
