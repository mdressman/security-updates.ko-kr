---
TOCTitle: 'MS14-FEB'
Title: 2014년 2월 Microsoft 보안 공지 요약
ms:assetid: 'ms14-feb'
ms:contentKeyID: 61597933
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms14-feb(v=Security.10)'
---

2014년 2월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2014년 2월 11일 | 업데이트 날짜: 2014년 9월 25일

**버전:** 1.3

이 공지 요약 목록에는 2014년 2월 발표된 보안 공지가 포함되어 있습니다.

2014년 2월 보안 공지 발표와 함께 이 공지 요약이 2014년 2월 10일 월요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2014년 2월 12일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [2월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572879&culture=en-us).

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 영향을 받는 소프트웨어를 참조하십시오.

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
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><strong>공지 제목 및 용약</strong></td>
<td style="border:1px solid black;"><strong>최대 심각도 및 취약점 영향</strong></td>
<td style="border:1px solid black;"><strong>다시 시작 요구 사항</strong></td>
<td style="border:1px solid black;"><strong>영향을 받는 소프트웨어</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2909921)<br />
<br />
이 보안 업데이트는 Internet Explorer의 공개된 취약점 1건과 비공개로 보고된 취약점 23건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 가장 위험한 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391023">MS14-011</a></td>
<td style="border:1px solid black;">VBScript 스크립팅 엔진의 취약점으로 인한 원격 코드 실행 문제점(2928390)<br />
<br />
이 보안 업데이트는 Microsoft Windows의 VBScript 스크립팅 엔진에서 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 공격자는 강제로 사용자가 웹 사이트를 방문하도록 할 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386447">MS14-007</a></td>
<td style="border:1px solid black;">Direct2D의 취약점으로 인한 원격 코드 실행 문제점(2912390)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 공격자는 강제로 사용자가 특수하게 조작된 콘텐츠를 보도록 만들 수는 없습니다. 대신 공격자는 사용자가 공격자의 웹 사이트에 연결되는 전자 메일 메시지나 메신저 메시지에서 링크를 클릭하게 하거나 전자 메일을 통해 보낸 첨부 파일을 열도록 하는 등의 조치를 취하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390218">MS14-008</a></td>
<td style="border:1px solid black;">Exchange용 Microsoft Forefront Protection의 취약점으로 인한 원격 코드 실행 문제점(2927022)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Forefront의 취약점을 해결합니다. 특수하게 조작된 전자 메일 메시지가 스캔된 경우 원격 코드 실행이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft 보안 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">.NET Framework의 취약점으로 인한 권한 상승 문제점(2916607)<br />
<br />
이 보안 업데이트는 Microsoft .NET Framework의 공개된 취약점 2건과 비공개적으로 보고된 취약점 1건을 해결합니다. 사용자가 특수하게 조작된 웹 사이트 또는 특수하게 조작된 웹 콘텐츠를 포함한 웹 사이트를 방문하는 경우 가장 위험한 취약점으로 인해 권한 상승이 발생할 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 공격에 노출된 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391022">MS14-005</a></td>
<td style="border:1px solid black;">Microsoft XML Core Services의 취약점으로 인한 정보 유출 문제점(2916036)<br />
<br />
이 보안 업데이트는 Microsoft Windows에 포함된 Microsoft XML Core Services의 공개된 취약점을 해결합니다. 이 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 정보 유출을 허용할 수 있습니다. 공격자는 강제로 사용자가 특수하게 조작된 콘텐츠를 보도록 만들 수는 없습니다. 대신 공격자는 사용자가 공격자의 웹 사이트에 연결되는 전자 메일 메시지나 메신저 메시지에서 링크를 클릭하게 하거나 전자 메일을 통해 보낸 첨부 파일을 열도록 하는 등의 조치를 취하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386450">MS14-006</a></td>
<td style="border:1px solid black;">IPv6의 취약점으로 인한 서비스 거부 문제점(2904659)<br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 대량의 특수하게 조작된 IPv6 패킷을 영향을 받는 시스템으로 보낼 경우 서비스 거부가 발생할 수 있습니다. 이 취약점을 악용하려면 공격자의 시스템이 대상 시스템과 동일한 서브넷에 속해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
<p> </p>
<table style="border:1px solid black;">
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
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><strong>취약점 제목</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>최신 소프트웨어 버전에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>이전 소프트웨어 버전에 대한 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>서비스 거부 악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>주요 정보</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391022">MS14-005</a></td>
<td style="border:1px solid black;">MSXML 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0266">CVE-2014-0266</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 이 취약점을 악용하려는 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386450">MS14-006</a></td>
<td style="border:1px solid black;">TCP/IP 버전 6(IPv6) 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0254">CVE-2014-0254</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386447">MS14-007</a></td>
<td style="border:1px solid black;">Microsoft 그래픽 구성 요소 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0263">CVE-2014-0263</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390218">MS14-008</a></td>
<td style="border:1px solid black;">RCE 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0294">CVE-2014-0294</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">POST 요청 DoS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0253">CVE-2014-0253</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">유형 탐색 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0257">CVE-2014-0257</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">VSAVB7RT ASLR 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0295">CVE-2014-0295</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 이 취약점을 악용하려는 제한적이며 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0267">CVE-2014-0267</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0268">CVE-2014-0268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0269">CVE-2014-0269</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0270">CVE-2014-0270</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0271">CVE-2014-0271</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0272">CVE-2014-0272</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0273">CVE-2014-0273</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0274">CVE-2014-0274</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0275">CVE-2014-0275</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0276">CVE-2014-0276</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0277">CVE-2014-0277</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0278">CVE-2014-0278</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0279">CVE-2014-0279</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0280">CVE-2014-0280</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0281">CVE-2014-0281</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0283">CVE-2014-0283</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0284">CVE-2014-0284</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0285">CVE-2014-0285</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0286">CVE-2014-0286</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0287">CVE-2014-0287</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0288">CVE-2014-0288</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0289">CVE-2014-0289</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0290">CVE-2014-0290</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Internet Explorer 도메인 간 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0293">CVE-2014-0293</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391023">MS14-011</a></td>
<td style="border:1px solid black;">VBScript 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0271">CVE-2014-0271</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어  
----------------------
  
<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
없음

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
Windows XP 서비스 팩 3

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2909921)  
(긴급)  
Internet Explorer 7   
(2909921)  
(긴급)  
Internet Explorer 8   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(긴급)  
VBScript 5.8   
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0 서비스 팩 3  
(2904878)  
(중요)  
(Media Center Edition 2005 서비스 팩 3 및 Tablet PC Edition 2005 서비스 팩 3만 해당)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901111)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898856)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)

</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2909921)  
(긴급)  
Internet Explorer 7   
(2909921)  
(긴급)  
Internet Explorer 8   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(긴급)  
VBScript 5.7   
(2909212)  
(긴급)  
VBScript 5.8   
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901111)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898856)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도

</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
없음

</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 6   
(2909921)  
(보통)  
Internet Explorer 7  
(2909921)  
(보통)  
Internet Explorer 8  
(2909921)  
(중요)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(보통)  
VBScript 5.7   
(2909212)  
(보통)  
VBScript 5.8   
(2909210)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2901115)  
(중요)  
Microsoft .NET Framework 1.1 서비스 팩 1  
(2898860)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901111)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898856)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2909921)  
(보통)  
Internet Explorer 7  
(2909921)  
(보통)  
Internet Explorer 8  
(2909921)  
(중요)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(보통)  
VBScript 5.7   
(2909212)  
(보통)  
VBScript 5.8   
(2909210)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901111)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898856)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2916036)  
(낮음)

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
Internet Explorer 6   
(2909921)  
(보통)  
Internet Explorer 7  
(2909921)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(보통)  
VBScript 5.7   
(2909212)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901111)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898856)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
없음

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
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(긴급)  
Internet Explorer 8  
(2909921)  
(긴급)  
Internet Explorer 9   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(긴급)  
Internet Explorer 8을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)  
Internet Explorer 9를 실행하는 시스템의 VBScript 5.8  
(2909921)<sup>[1]</sup>
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901113)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898858)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2911502)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)  
Microsoft .NET Framework 4.5  
(2901118)  
(중요)  
Microsoft .NET Framework 4.5  
(2898864)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2916036)  
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
Internet Explorer 7  
(2909921)  
(긴급)  
Internet Explorer 8  
(2909921)  
(긴급)  
Internet Explorer 9   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(긴급)  
Internet Explorer 8을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)  
Internet Explorer 9를 실행하는 시스템의 VBScript 5.8  
(2909921)<sup>[1]</sup>
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901113)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898858)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2911502)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)  
Microsoft .NET Framework 4.5  
(2901118)  
(중요)  
Microsoft .NET Framework 4.5  
(2898864)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도

</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
없음

</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(보통)  
Internet Explorer 8  
(2909921)  
(중요)  
Internet Explorer 9   
(2909921)  
(중요)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(보통)  
Internet Explorer 8을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(보통)  
Internet Explorer 9를 실행하는 시스템의 VBScript 5.8  
(2909921)<sup>[1]</sup>
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901113)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898858)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2911502)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)  
Microsoft .NET Framework 4.5  
(2901118)  
(중요)  
Microsoft .NET Framework 4.5  
(2898864)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2916036)  
(낮음)

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
Internet Explorer 7  
(2909921)  
(보통)  
Internet Explorer 8  
(2909921)  
(중요)  
Internet Explorer 9   
(2909921)  
(중요)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(보통)  
Internet Explorer 8을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(보통)  
Internet Explorer 9를 실행하는 시스템의 VBScript 5.8  
(2909921)<sup>[1]</sup>
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901113)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898858)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2911502)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)  
Microsoft .NET Framework 4.5  
(2901118)  
(중요)  
Microsoft .NET Framework 4.5  
(2898864)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2901113)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2898858)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2911502)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2909921)  
(긴급)  
Internet Explorer 9   
(2909921)  
(긴급)  
Internet Explorer 10   
(2909921)  
(긴급)  
Internet Explorer 11   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 8을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)  
Internet Explorer 9를 실행하는 시스템의 VBScript 5.8  
(2909921)<sup>[1]</sup>
(긴급)  
Internet Explorer 10을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)  
Internet Explorer 11을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)  
Microsoft .NET Framework 4.5  
(2901118)  
(중요)  
Microsoft .NET Framework 4.5  
(2898864)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2909921)  
(긴급)  
Internet Explorer 9   
(2909921)  
(긴급)  
Internet Explorer 10   
(2909921)  
(긴급)  
Internet Explorer 11   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 8을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)  
Internet Explorer 9를 실행하는 시스템의 VBScript 5.8  
(2909921)<sup>[1]</sup>
(긴급)  
Internet Explorer 10을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)  
Internet Explorer 11을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)  
Microsoft .NET Framework 4.5  
(2901118)  
(중요)  
Microsoft .NET Framework 4.5  
(2898864)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도

</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)

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
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2909921)  
(중요)  
Internet Explorer 9   
(2909921)  
(중요)  
Internet Explorer 10   
(2909921)  
(중요)  
Internet Explorer 11   
(2909921)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 8을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(보통)  
Internet Explorer 9를 실행하는 시스템의 VBScript 5.8  
(2909921)<sup>[1]</sup>
(보통)  
Internet Explorer 10을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(보통)  
Internet Explorer 11을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)  
Microsoft .NET Framework 4.5  
(2901118)  
(중요)  
Microsoft .NET Framework 4.5  
(2898864)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2909921)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 8을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 10을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(중요)  
Microsoft .NET Framework 3.5  
(2898866)  
(중요)  
Microsoft .NET Framework 4.5  
(2901119)  
(중요)  
Microsoft .NET Framework 4.5  
(2898865)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2904659)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 10을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(중요)  
Microsoft .NET Framework 3.5  
(2898866)  
(중요)  
Microsoft .NET Framework 4.5  
(2901119)  
(중요)  
Microsoft .NET Framework 4.5  
(2898865)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2904659)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(중요)  
Microsoft .NET Framework 3.5  
(2898868)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(중요)  
Microsoft .NET Framework 3.5  
(2898868)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도

</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)

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
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 10   
(2909921)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 10을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(중요)  
Microsoft .NET Framework 3.5  
(2898866)  
(중요)  
Microsoft .NET Framework 4.5  
(2901119)  
(중요)  
Microsoft .NET Framework 4.5  
(2898865)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2904659)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(중요)

</td>
<td style="border:1px solid black;">
Internet Explorer 11을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(중요)  
Microsoft .NET Framework 3.5  
(2898868)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 10을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2901119)  
(중요)  
Microsoft .NET Framework 4.5  
(2898865)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(2904659)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(긴급)

</td>
<td style="border:1px solid black;">
Internet Explorer 11을 실행하는 시스템의 VBScript 5.8  
(2909210)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2912390)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1  
(2901128)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2916036)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도

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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)

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
VBScript 5.7   
(2909212)  
(심각도 없음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(심각도 없음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(2909210)  
(심각도 없음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(중요)  
Microsoft .NET Framework 4  
(2901110)  
(중요)  
Microsoft .NET Framework 4  
(2898855)  
(중요)  
Microsoft .NET Framework 4.5  
(2901118)  
(중요)  
Microsoft .NET Framework 4.5  
(2898864)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

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
VBScript 5.8   
(2909210)  
(심각도 없음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(중요)  
Microsoft .NET Framework 3.5  
(2898866)  
(중요)  
Microsoft .NET Framework 4.5  
(2901119)  
(중요)  
Microsoft .NET Framework 4.5  
(2898865)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2904659)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(2909210)  
(심각도 없음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(중요)  
Microsoft .NET Framework 3.5  
(2898868)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(중요)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2916036)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
</table>
 
MS14-011 참고 사항

[<sup>[1]</sup>](http://go.microsoft.com/fwlink/?linkid=390977)Internet Explorer 9를 실행하는 시스템의 경우 이 취약점은 MS14-010의 Internet Explorer 9용 누적 업데이트 2909921로 해결됩니다.

 

### Microsoft 보안 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
<strong>Exchange Server용 Microsoft Forefront Protection 2010</strong>

</td>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호

</td>
<td style="border:1px solid black;">
[MS14-008](http://go.microsoft.com/fwlink/?linkid=390218)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도

</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Exchange Server용 Microsoft Forefront Protection 2010

</td>
<td style="border:1px solid black;">
Exchange Server용 Microsoft Forefront Protection 2010  
(2927022)  
(긴급)

</td>
</tr>
</table>
 
 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 존재합니다.

-   관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 구성 오류를 검색할 수 있습니다.
-   WSUS(Windows Server Update Services), SMS(Systems Management Server), System Center Configuration Manager는 관리자가 보안 업데이트를 배포하는 데 도움이 됩니다.
-   ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](http://technet.microsoft.com/security/cc297183)를 참조하십시오. 

감사의 말
---------

<span id="sectionToggle4"></span>
고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

MS14-005

-   MSXML 정보 유출 취약점(CVE-2014-0266)에 대해 Microsoft와 협력해 주신 [FireEye, Inc.](http://www2.fireeye.com/)(영문)

MS14-007

-   Microsoft 그래픽 구성 요소 메모리 손상 취약점(CVE-2014-0263)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Omair](http://krash.in/)(영문)

MS14-009

-   유형 탐색 취약점(CVE-2014-0257)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw

MS14-010

-   Internet Explorer 메모리 손상 취약점(CVE-2014-0267)에 대해 Microsoft와 협력해 주신 [KeenTeam](http://www.k33nteam.org/)(영문)(@K33nTeam)의 Liang Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0267)에 대해 Microsoft와 협력해 주신 [VulnHunt](http://www.vulnhunt.com/)(영문)의 Code Audit Labs
-   Internet Explorer 권한 상승 취약점(CVE-2014-0268)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0269)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0270)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Yenteasy - Security Research의 Jose A. Vazquez
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0270)을 [VeriSign iDefense Labs](http://labs.idefense.com/)(영문)와 협력하여 보고해 주신 Yenteasy - Security Research의 Jose A. Vazquez
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0272)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0273)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0274)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Arthur Gerkis
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0274)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 lokihardt@ASRT
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0275)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0276)을 보고해 주신 [Security-Assessment.com](http://www.security-assessment.com/)(영문)의 Scott Bell
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0277)을 보고해 주신 [Security-Assessment.com](http://www.security-assessment.com/)(영문)의 Scott Bell
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0278)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0278)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0279)을 보고해 주신 [Security-Assessment.com](http://www.security-assessment.com/)(영문)의 Scott Bell
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0279)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0280)을 보고해 주신 [Security-Assessment.com](http://www.security-assessment.com/)(영문)의 Scott Bell
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0281)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 cons0ul 및 suto
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0283)을 보고해 주신 Sachin Shinde
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0284)을 보고해 주신 Sachin Shinde
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0285)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0285)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0286)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0287)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Corelan](http://www.corelangcv.com/)의 Peter 'corelanc0d3r' Van Eeckhoutte
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0288)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Arthur Gerkis
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0289)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 lokihardt@ASRT
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0290)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0290)을 보고해 주신 [Qihoo](http://www.360.cn/)(중문)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-0290)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Trend Micro](http://www.trendmicro.com/)(영문)의 Yuki Chen
-   Internet Explorer 도메인 간 정보 유출 취약점(CVE-2014-0293)을 보고해 주신 [Dieyu dieu deus deva divine dio theos dievas dewa ilu Diyin Ayóo Átʼéii atua tiānzhŭ Yahweh Zeus Odin El](http://dieyu.org/)

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 버전에서 Microsoft는 Windows 업데이트, Microsoft 업데이트, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 발표에서 사용할 수 없습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows 업데이트 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너(영문)](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

업데이트 관리 전략

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

기타 보안 관련 업데이트 받기

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft 업데이트](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows 업데이트를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 개정 내역

-   V1.0(2014년 2월 12일): 공지 요약이 게시되었습니다.
-   V1.1(2014년 2월 13일): MS14-008에서 CVE-2014-0294의 악용 가능성 인덱스의 이전 소프트웨어 버전에 대한 악용 가능성 평가를 개정했습니다.
-   V1.2(2014년 2월 14일): MS14-011에서 CVE-2014-0271의 악용 가능성 인덱스의 최신 소프트웨어 버전에 대한 악용 가능성 평가를 개정했습니다.
-   V1.3(2014년 9월 25일): MS14-009에서 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(2898855)에 설치된 Microsoft .NET Framework 4에 대한 영향을 받는 소프트웨어 표에 누락된 Server Core 항목을 추가했습니다. 이 변경 사항은 정보에만 해당됩니다. Server Core 설치에서 이 영향을 받는 소프트웨어를 실행 중인 고객 중 이미 2898855 업데이트를 적용한 고객은 조치를 취할 필요가 없습니다. Server Core 설치에서 이 영향을 받는 소프트웨어를 실행 중인 고객 중 아직 업데이트를 설치하지 않은 고객은 MS14-009에서 설명한 취약점으로부터 보호하기 위한 절차를 따라주십시오. 다운로드 링크는 공지를 확인하십시오.

*2014년 9월 23일 14:39Z-07:00에 페이지가 생성되었습니다.*
