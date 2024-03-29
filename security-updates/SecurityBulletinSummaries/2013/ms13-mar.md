---
TOCTitle: 'MS13-MAR'
Title: 2013 년 3 월 Microsoft 보안 공지 요약
ms:assetid: 'ms13-mar'
ms:contentKeyID: 61230764
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms13-mar(v=Security.10)'
---

2013 년 3 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2013년 3월 12일 화요일 | 업데이트된 날짜: 2013년 3월 16일 토요일

**버전:** 1.1

이 공지 요약 목록에는 2013년 3월 발표된 보안 공지가 포함되어 있습니다.

2013년 3월 보안 공지 발표와 함께 이 공지 요약이 2013년 3월 7일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2013년 3월 13일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [3월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538636&culture=en-us). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538636&culture=en-us)으로 제공됩니다.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

### 공지 정보

#### 요약

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 영향을 받는 소프트웨어 및 다운로드 위치를 참조하십시오.

<p> </p>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279923">MS13-021</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2809289)  <br />
<br />
이 보안 업데이트는 Internet Explorer에 대해 비공개적으로 보고된 취약점 8건과 공개된 취약점 1건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275737">MS13-022</a></td>
<td style="border:1px solid black;">Silverlight의 취약점으로 인한 원격 코드 실행 문제점(2814124) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Silverlight의 취약점을 해결합니다. 공격자가 취약점을 악용할 수 있도록 특수하게 조작된 Silverlight 응용 프로그램을 포함한 웹 사이트를 호스팅하고 사용자가 웹 사이트를 보도록 유도하는 경우 이 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 공격자는 사용자가 제공한 콘텐츠가 광고를 허용하거나 호스팅하는 웹 사이트와 공격에 노출된 웹 사이트를 이용할 수도 있습니다. 이러한 웹 사이트에는 이 취약점을 악용할 수 있도록 특수하게 조작된 콘텐츠가 포함될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다. 배너 광고에서 특수하게 조작된 웹 콘텐츠를 표시하거나 웹 콘텐츠를 전달하는 다른 방법을 사용하여 영향을 받는 시스템에 대한 공격을 시도할 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276801">MS13-023</a></td>
<td style="border:1px solid black;">Microsoft Visio Viewer 2010의 취약점으로 인한 원격 코드 실행 문제점(2801261)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Visio 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271610">MS13-024</a></td>
<td style="border:1px solid black;">SharePoint의 취약점으로 인한 권한 상승 문제점(2780176)  <br />
<br />
이 보안 업데이트는 Microsoft SharePoint 및 Microsoft SharePoint Foundation에서 비공개적으로 보고된 취약점 4건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 URL을 클릭하여 대상 SharePoint 사이트로 유인된 경우 권한 상승 문제가 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282355">MS13-025</a></td>
<td style="border:1px solid black;">Microsoft OneNote의 취약점으로 인한 정보 유출 문제점(2816264)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft OneNote의 취약점을 해결합니다. 공격자가 특수하게 조작된 OneNote 파일을 열도록 사용자를 유도하는 경우 이 취약점으로 인해 정보가 유출될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280673">MS13-026</a></td>
<td style="border:1px solid black;">Microsoft Office for Mac의 취약점으로 인한 정보 유출 문제(2813682)  <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office for Mac의 취약점 1건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 전자 메일 메시지를 열 경우 정보 유출이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282639">MS13-027</a></td>
<td style="border:1px solid black;">커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2807986)  <br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 이 취약점으로 인해 공격자가 시스템에 액세스하는 경우 권한 상승이 허용될 수 있습니다.</td>
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
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
| 공지 번호                                                 | 취약점 제목                                                  | CVE ID                                                                                 | 최신 소프트웨어 버전에 대한 악용 가능성 평가                                           | 이전 소프트웨어 버전에 대한 악용 가능성 평가                                           | 서비스 거부 악용 가능성 평가 | 주요 정보                             |  
|-----------------------------------------------------------|--------------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|------------------------------|---------------------------------------|  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer OnResize 해제 후 사용 취약점               | [CVE-2013-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0087)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer saveHistory 해제 후 사용 취약점            | [CVE-2013-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0088)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CMarkupBehaviorContext 해제 후 사용 취약점 | [CVE-2013-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0089)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CCaret 해제 후 사용 취약점                 | [CVE-2013-0090](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0090)(영문) | [2](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 구축 어려움 | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CElement 해제 후 사용 취약점               | [CVE-2013-0091](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0091)(영문) | 영향 받지 않음                                                                         | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer GetMarkupPtr 해제 후 사용 취약점           | [CVE-2013-0092](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0092)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer onBeforeCopy 해제 후 사용 취약점           | [CVE-2013-0093](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0093)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer removeChild 해제 후 사용 취약점            | [CVE-2013-0094](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0094)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CTreeNode 해제 후 사용 취약점              | [CVE-2013-1288](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1288)(영문) | 영향 받지 않음                                                                         | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | 이 취약점은 공개되었습니다.           |  
| [MS13-022](http://go.microsoft.com/fwlink/?linkid=275737) | Silverlight 이중 역참조 취약점                               | [CVE-2013-0074](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0074)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음                                                                         | 해당 사항 없음               | (없음)                                |  
| [MS13-023](http://go.microsoft.com/fwlink/?linkid=276801) | Visio 트리 개체 유형 혼란 취약점                             | [CVE-2013-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0079)(영문) | 영향 받지 않음                                                                         | [2](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 구축 어려움 | 해당 사항 없음               | (없음)                                |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | 콜백 기능 취약점                                             | [CVE-2013-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0080)(영문) | 영향 받지 않음                                                                         | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | SharePoint XSS 취약점                                        | [CVE-2013-0083](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0083)(영문) | 영향 받지 않음                                                                         | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | SharePoint 디렉터리 탐색 취약점                              | [CVE-2013-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0084)(영문) | 영향 받지 않음                                                                         | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 해당 사항 없음               | (없음)                                |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | 버퍼 오버플로 취약점                                         | [CVE-2013-0085](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0085)(영문) | 영향 받지 않음                                                                         | [3](http://technet.microsoft.com/security/cc998259) - 악용 코드 불가능                 | 임시                         | 이 취약점은 서비스 거부 취약점입니다. |  
| [MS13-025](http://go.microsoft.com/fwlink/?linkid=282355) | 버퍼 크기 유효성 검사 취약점                                 | [CVE-2013-0086](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0086)(영문) | 영향 받지 않음                                                                         | [3](http://technet.microsoft.com/security/cc998259) - 악용 코드 불가능                 | 해당 사항 없음               | 이는 정보 유출 취약점입니다.          |  
| [MS13-026](http://go.microsoft.com/fwlink/?linkid=280673) | 의도하지 않은 콘텐츠 로딩 취약점                             | [CVE-2013-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0095)(영문) | [3](http://technet.microsoft.com/security/cc998259) - 악용 코드 불가능                 | [3](http://technet.microsoft.com/security/cc998259) - 악용 코드 불가능                 | 해당 사항 없음               | 이는 정보 유출 취약점입니다.          |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Windows USB 설명자 취약점                                    | [CVE-2013-1285](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1285)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | (없음)                                |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Windows USB 설명자 취약점                                    | [CVE-2013-1286](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1286)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | (없음)                                |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Windows USB 설명자 취약점                                    | [CVE-2013-1287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1287)(영문) | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | [1](http://technet.microsoft.com/ko-kr/security/cc998259.aspx) - 악용 코드 가능        | 영구                         | (없음)                                |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------

다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="3">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=ace6994d-7482-40de-84ad-a87853a35860&displaylang=ko)   
(2809289)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=50c59794-4ec7-404a-b316-dae314521ebb&displaylang=ko)  
(2809289)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7e5d96a7-d9f5-4832-b4f9-b6e0148c655b)  
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=ba528d03-b0a6-40a5-a6bd-13c062a8a877&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=795cef4e-9c01-447f-916c-e52e69eca4a3)   
(2809289)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=16993a2c-1fe1-4c1e-bcd9-db1a7dd4a058)  
(2809289)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=66a08524-883d-4d67-82cc-2c0f55c56b31)  
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4f8a48d4-b1bb-465c-a232-d29fe94d1429)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e3c911b3-7fdd-4105-a20a-eef65b0908e3&displaylang=ko&displaylang=ko)   
(2809289)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0f58d63e-0d2c-41d2-9792-edbb2f4a539d)  
(2809289)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e6b63da9-a414-40ee-b877-4fb0d62bacba&displaylang=ko)  
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=835651b7-79fb-4d50-b48e-f02173062253&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=eaf2c568-089a-4c2f-bca6-da83f7332de9&displaylang=ko)   
(2809289)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5a18b139-2773-44c8-85f9-8dce24249e71&displaylang=ko)  
(2809289)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d6feba92-f014-4521-b6c4-7f5f358a3ce3&displaylang=ko)  
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9d5f1ed1-f33b-4c90-9b29-ee8ac587d31b&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=088fd3ec-62e1-4737-8132-6b51219ed37f)   
(2809289)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=799748d8-056d-4139-86e1-9bd0cb0151b4)  
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=28d441e7-abcf-4cc9-84e0-572e5b79aab7)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0bf77905-1199-4219-a67d-1e9ad3f63757&displaylang=ko)  
(2809289)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=76e328f8-4f86-4e50-b7e0-22db0385ab01&displaylang=ko)  
(2809289)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c26f74fc-e224-4533-a4e3-b52125dca5cd&displaylang=ko)   
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8472bc7-9e20-4238-adcf-a1e1a91687a1&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7b652bb4-7a0a-437b-bcc5-ebbbb820c559&displaylang=ko)  
(2809289)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=67b09398-ceb6-403c-bba4-261d9d9dea98&displaylang=ko)  
(2809289)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=3f1795a5-4376-4929-8748-743840ec2154&displaylang=ko)   
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e412c54a-a93d-4c5b-9b13-40b59d1dff35&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0303fcb1-34d5-47da-b6ee-18222fe3235a&displaylang=ko)  
(2809289)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=337068a5-9281-4db6-9ff1-5282cdfa0763&displaylang=ko)  
(2809289)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c672c196-5072-468c-8d88-34534fa219fd&displaylang=ko)   
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f22b9327-1430-44cb-a609-ea1bb9b7b8f8&displaylang=ko)  
(2809289)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0496cbfe-77d2-4de6-b78d-937225dc8974&displaylang=ko)  
(2809289)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=5c40f237-b4c8-41eb-a649-baad46dfa13c)   
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=09e4832c-b95e-4581-a73b-49cb6a60c1df)  
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=af2e8e83-fb8f-4ba5-83ec-8bd4347a5fe6)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0&displaylang=ko)  
(2809289)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085&displaylang=ko)   
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0&displaylang=ko)  
(2809289)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085&displaylang=ko)   
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d&displaylang=ko)  
(2809289)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae&displaylang=ko)   
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d&displaylang=ko)  
(2809289)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae&displaylang=ko)   
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6&displaylang=ko)  
(2809289)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37&displaylang=ko)   
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6&displaylang=ko)  
(2809289)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37&displaylang=ko)   
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=7c348fe3-f4f0-4f22-8a7f-8563705c1f64&displaylang=ko)   
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 8(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=de4ec125-c337-4615-b39b-8456658dae22&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=0c503b83-5b13-41da-a5ff-7519bc244521&displaylang=ko)   
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 8(64비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c1539e94-0635-4f51-8172-a96a737d81d3&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=f9b299f1-8a73-40b2-9942-e6419496bb39&displaylang=ko)   
(2809289)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752&displaylang=ko)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>   
(2809289)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Server Core 설치 옵션
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e&displaylang=ko)(Server Core 설치)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6&displaylang=ko)(Server Core 설치)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e&displaylang=ko)(Server Core 설치)   
(2807986)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e&displaylang=ko)(Server Core 설치)   
(2807986)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752&displaylang=ko)(Server Core 설치)   
(2807986)  
(중요)
</td>
</tr>
</table>
 
MS13-021 참고 사항

<sup>[1]</sup>Windows RT 보안 업데이트는 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다.

#### Microsoft Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-023](http://go.microsoft.com/fwlink/?linkid=276801)
</td>
<td style="border:1px solid black;">
[MS13-025](http://go.microsoft.com/fwlink/?linkid=282355)
</td>
<td style="border:1px solid black;">
[MS13-026](http://go.microsoft.com/fwlink/?linkid=280673)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=b01b4410-1107-472f-bf96-234304e91e77&displaylang=ko)   
(2687505)  
(긴급)
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
Microsoft Visio Viewer 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=24065dd5-251b-4a3c-bb44-8d552a1f265e&displaylang=ko)   
(2687505)  
(긴급)
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
Microsoft Visio 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=7a1a21e7-3137-4201-a005-cc66379fc1c5&displaylang=ko)   
(2760762)  
(심각도 없음)<sup>[1]</sup>
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
Microsoft Visio 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=7b7d39f0-a341-4d48-8177-329cccb5a7f1&displaylang=ko)   
(2760762)  
(심각도 없음)<sup>[1]</sup>
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
Microsoft Office 2010 Filter Pack 서비스 팩 1(32비트 버전)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Filter Pack 서비스 팩 1(32비트 버전)](http://www.microsoft.com/downloads/details.aspx?familyid=f10db48f-a980-47bf-83a5-c0da4e615114&displaylang=ko)   
(2553501)  
(심각도 없음)<sup>[1]</sup>
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
Microsoft Office 2010 Filter Pack 서비스 팩 1(64비트 버전)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Filter Pack 서비스 팩 1(64비트 버전)](http://www.microsoft.com/downloads/details.aspx?familyid=70d3372b-74a8-4b68-b6c4-18863835915d&displaylang=ko)   
(2553501)  
(심각도 없음)<sup>[1]</sup>
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
Microsoft OneNote 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=da4bfd31-65b9-496b-aa98-4fa8b729dcf3&displaylang=ko)   
(2760600)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft OneNote 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=10fc7350-e1d4-40b6-a5d1-8670263faf05&displaylang=ko)   
(2760600)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d7aef20a-922b-4495-b473-1afa4a7ac514&displaylang=ko)   
(2817449)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=4960674b-1cb4-499a-999e-7aa4d4c49e5e&displaylang=ko)   
(2817452)  
(중요)
</td>
</tr>
</table>
 
MS13-023 참고 사항

<sup>[1]</sup>이 취약점에 대해 알려진 공격 경로가 차단되므로 지정된 소프트웨어에 대한 이 업데이트에는 심각도가 적용되지 않습니다.

#### Microsoft 개발자 도구 및 소프트웨어

<p> </p>
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
[MS13-022](http://go.microsoft.com/fwlink/?linkid=275737)
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
Mac에 설치된 Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Mac에 설치된 [Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9&displaylang=ko)   
(2814124)   
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5 Developer 런타임
</td>
<td style="border:1px solid black;">
Mac에 설치된 [Microsoft Silverlight 5 Developer 런타임](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9&displaylang=ko)   
(2814124)   
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원 대상인 모든 Microsoft Windows 클라이언트 릴리스에 설치된 Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
지원 대상인 모든 Microsoft Windows 클라이언트 릴리스에 설치된 [Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9&displaylang=ko)   
(2814124)   
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
지원 대상인 모든 Microsoft Windows 클라이언트 릴리스에 설치된 Microsoft Silverlight 5 Developer 런타임
</td>
<td style="border:1px solid black;">
지원 대상인 모든 Microsoft Windows 클라이언트 릴리스에 설치된 [Microsoft Silverlight 5 Developer 런타임](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9&displaylang=ko)   
(2814124)   
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원 대상인 모든 Microsoft Windows 서버 릴리스에 설치된 Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
지원 대상인 모든 Microsoft Windows 서버 릴리스에 설치된 [Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9&displaylang=ko)  
(2814124)   
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
지원 대상인 모든 Microsoft Windows 서버 릴리스에 설치된 Microsoft Silverlight 5 Developer 런타임
</td>
<td style="border:1px solid black;">
지원 대상인 모든 Microsoft Windows 서버 릴리스에 설치된 [Microsoft Silverlight 5 Developer 런타임](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)   
(긴급)
</td>
</tr>
</table>
 

#### Microsoft Server 소프트웨어

<p> </p>
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
[MS13-024](http://go.microsoft.com/fwlink/?linkid=271610)
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
Microsoft SharePoint Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=a9e8acbd-90e5-4acd-aa8f-b743a352787b&displaylang=ko)<sup>[1]</sup>   
(wasrv)  
(2553407)  
(긴급)
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
[MS13-024](http://go.microsoft.com/fwlink/?linkid=271610)
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
Microsoft SharePoint Foundation 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=293666ec-3290-4c6f-a7f6-b44c9b7fa0a6&displaylang=ko)   
(2687418)  
(중요)
</td>
</tr>
</table>
 
MS13-024 참고 사항

<sup>[1]</sup>고객은 이 공지에서 설명한 취약점으로부터 보호하기 위해 지원 대상인 Microsoft SharePoint Server 2010 에디션에 Microsoft SharePoint 2010(2553407)용 보안 업데이트 패키지와 함께 Microsoft SharePoint Foundation 2010용 보안 업데이트(2687418)를 설치해야 합니다.

검색, 배포 도구 및 지침
-----------------------

<span></span>
보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security TechCenter](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [Microsoft 안전 및 보안 센터](http://go.microsoft.com/fwlink/?linkid=85102)를 방문하거나 "보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS13-001")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

검색 및 배포 지침

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

Microsoft Baseline Security Analyzer

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 참조하십시오.

Windows Server Update Services

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://technet.microsoft.com/wsus/default)를 참조하십시오.

System Center Configuration Manager

System Center Configuration Manager 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. System Center Configuration Manager를 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

System Center Configuration Manager의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. System Center Configuration Manager의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. System Center Configuration Manager에 대한 자세한 내용은 [System Center 기술 리소스](http://technet.microsoft.com/systemcenter/bb980621)를 참조하십시오.

Systems Management Server 2003

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

참고 System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://go.microsoft.com/fwlink/?linkid=21742) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager를 지금 사용할 수 있습니다(이전 섹션의 System Center Configuration Manager 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (영문)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet.microsoft.com/library/cc749197) (영문) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 버전에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 발표에서 사용할 수 없습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

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

MS13-021

-   Internet Explorer OnResize 해제 후 사용 취약점(CVE-2013-0087)을 보고해 주신 [TELUS Security Labs](http://telussecuritylabs.com/)(영문)의 Arseniy Akuney
-   Internet Explorer saveHistory 해제 후 사용 취약점(CVE-2013-0088)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer CMarkupBehaviorContext 해제 후 사용 취약점(CVE-2013-0089)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer CCaret 해제 후 사용 취약점(CVE-2013-0090)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Harmony Security](http://www.harmonysecurity.com)(영문)의 Stephen Fewer
-   Internet Explorer CCaret 해제 후 사용 취약점(CVE-2013-0090)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 SkyLined
-   Internet Explorer CElement 해제 후 사용 취약점(CVE-2013-0091)을 [Exodus Intelligence](https://www.exodusintel.com/)(영문)와 협력하여 보고해 주신 Yenteasy Security Research의 Jose A Vazquez
-   Internet Explorer GetMarkupPtr 해제 후 사용 취약점(CVE-2013-0092)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com)
-   Internet Explorer onBeforeCopy 해제 후 사용 취약점(CVE-2013-0093)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com)
-   Internet Explorer removeChild 해제 후 사용 취약점(CVE-2013-0094)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Microsoft와 협력하여 Internet Explorer CTreeNode 해제 후 사용 취약점(CVE-2013-1288)을 해결한 [Venustech](http://www.venustech.com.cn/) ADLab의 Gen Chen
-   Internet Explorer CTreeNode 해제 후 사용 취약점(CVE-2013-1288)에 대해 Microsoft와 함께 작업해 주신 [Qihoo 360 Security Center](http://www.360.cn/)(중문)

MS13-022

-   Silverlight 이중 역참조 취약점(CVE-2013-0074)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw

MS13-023

-   Visio Viewer Tree Object 유형 혼동 취약점(CVE-2013-0079)을 [VeriSign iDefense Labs](http://labs.idefense.com/)(영문)와 협력하여 보고해 주신 [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com)

MS13-024

-   콜백 기능 취약점(CVE-2013-0080)을 보고해 주신 [BugSec](http://www.bugsec.com/)(영문)의 Emanuel Bronshtein
-   SharePoint XSS 취약점(CVE-2013-0083)을 보고해 주신 INR Labs([Network Intelligence India](http://niiconsulting.com/))의 Sunil Yadav
-   SharePoint 디렉터리 탐색 취약점(CVE-2013-0084)을 보고해 주신 [n.runs AG](http://www.nruns.com/)(영문)의 Moritz Jodeit

MS13-025

-   버퍼 크기 유효성 검사 취약점(CVE-2013-0086)을 보고해 주신 (영문)의 Christopher Gabriel

MS13-026

-   의도하지 않은 콘텐츠 로딩 취약점(CVE- 2013-0095)을 보고해 주신 [Nick Semenkovich](https://technet.microsoft.com/ko-KR/mailto:semenko@alum.mit.edu)(영문)

MS13-027

-   Windows USB 설명자 취약점(CVE-2013-1285)을 보고해 주신 NCC Group의 Andy Davis
-   Windows USB 설명자 취약점(CVE-2013-1286)을 보고해 주신 NCC Group의 Andy Davis
-   Windows USB 설명자 취약점(CVE-2013-1287)을 보고해 주신 NCC Group의 Andy Davis

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617.aspx)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2013년 3월 12일): 공지 요약이 게시되었습니다.
-   MS13-026의 V1.1(2013년 3월 16일)에서 요약 섹션의 공지 제목을 수정했습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
