---
TOCTitle: 'MS12-MAR'
Title: 2012 년 3 월 Microsoft 보안 공지 요약
ms:assetid: 'ms12-mar'
ms:contentKeyID: 61230752
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms12-mar(v=Security.10)'
---


2012 년 3 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2012년 3월 14일 수요일

**버전:** 1.0

이 공지 요약 목록에는 2012년 3월 발표된 보안 공지가 포함되어 있습니다.

2012년 3월 보안 공지 발표와 함께 이 공지 요약이 2012년 3월 8일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2012년 3월 14일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [3월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499508). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약(영문)](http://go.microsoft.com/fwlink/?linkid=217214) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td style="border:1px solid black;">원격 데스크톱의 취약점으로 인한 원격 코드 실행 문제점(2671387) <br />
<br />
이 보안 업데이트는 원격 데스크톱 프로토콜에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 중 가장 심각한 취약점은 공격자가 특수하게 조작된 RDP 패킷 시퀀스를 영향을 받는 시스템에 전송할 경우 원격 코드 실행을 허용할 수 있습니다. 기본적으로 RDP(원격 데스크톱 프로토콜)은 모든 Windows 운영 체제에서 사용되도록 설정되어 있지는 않습니다. RDP가 사용 가능하지 않는 시스템은 취약하지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235401">MS12-017</a></td>
<td style="border:1px solid black;">DNS 서버의 취약점으로 인한 서비스 거부 문제점(2647170) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 인증되지 않은 원격 공격자가 특수하게 조작된 DNS 쿼리를 대상 DNS 서버에 보낼 경우 서비스 거부가 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235364">MS12-018</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2641653) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235362">MS12-021</a></td>
<td style="border:1px solid black;">Visual Studio의 취약점으로 인한 권한 상승 문제점(2651019) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Visual Studio의 취약점 1건을 해결합니다. 이 취약점으로 인해 공격자가 Visual Studio에서 사용되는 경로에 특수하게 조작된 추가 기능을 배치하고 보다 높은 권한을 갖는 사용자가 Visual Studio를 시작하도록 유도할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235361">MS12-022</a></td>
<td style="border:1px solid black;">Expression Design의 취약점으로 인한 원격 코드 실행 문제점(2651018) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Expression Design의 취약점 1건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 DLL(동적 연결 라이브러리) 파일과 동일한 네트워크 디렉터리에 있는 합법적인 파일(예: .xpr 또는 .DESIGN 파일)을 여는 경우 원격 코드 실행이 허용될 수 있습니다. 이렇게 하면 합법적인 파일을 열 때 Microsoft Expression Design이 DLL 파일 로드 및 포함된 코드 실행을 시도할 수 있습니다. 공격에 성공하려면, 사용자가 신뢰할 수 없는 원격 파일 시스템 위치 또는 WebDAV 공유를 방문하거나 이러한 위치에서 취약한 응용 프로그램이 로드되는 합법적인 파일(예: .xpr 또는 .DESIGN 파일)을 열어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Expression Design</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239573">MS12-019</a></td>
<td style="border:1px solid black;">DirectWrite의 취약점으로 인한 서비스 거부 문제점(2665364) <br />
<br />
이 보안 업데이트는 Windows DirectWrite의 공개된 취약점을 해결합니다. 이 취약점으로 인해 인스턴트 메신저 기반 시나리오에서 공격자가 특수하게 조작된 Unicode 문자 시퀀스를 인스턴트 메신저 클라이언트에 바로 전송할 경우 서비스 거부가 발생할 수 있습니다. DirectWrite가 특수하게 조작된 Unicode 문자 시퀀스를 렌더링할 때 대상 응용 프로그램이 응답하지 않을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">보통</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
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

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >공지 번호</th>
<th style="border:1px solid black;" >취약점 제목</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >최신 소프트웨어 버전에 대한 악용 가능성 평가</th>
<th style="border:1px solid black;" >이전 소프트웨어 버전에 대한 악용 가능성 평가</th>
<th style="border:1px solid black;" >서비스 거부 악용 가능성 평가</th>
<th style="border:1px solid black;" >주요 정보</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235401">MS12-017</a></td>
<td style="border:1px solid black;">DNS 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0006">CVE-2012-0006(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235364">MS12-018</a></td>
<td style="border:1px solid black;">PostMessage 함수 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0157">CVE-2012-0157(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td style="border:1px solid black;">원격 데스크톱 프로토콜 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0002">CVE-2012-0002(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이것은 인증되지 않은 원격 코드 실행 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td style="border:1px solid black;">터미널 서버 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0152">CVE-2012-0152(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.<br />
<br />
최신 버전만 DoS의 영향을 받습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235362">MS12-021</a></td>
<td style="border:1px solid black;">Visual Studio 추가 기능 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0008">CVE-2012-0008(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235361">MS12-022</a></td>
<td style="border:1px solid black;">Expression Design의 안전하지 않은 라이브러리 로드 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0016">CVE-2012-0016(영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
</tbody>
</table>
  
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
<th style="border:1px solid black;" colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=18a1fe48-1318-4b93-afad-206950bb1ae5)  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=2922411c-9755-461b-9904-f6940322af19)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=eccf865d-399a-4862-b26f-f35580419875)  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e72b6b1f-68f5-4e1a-878e-290a5f03ca30)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=b69b4b9b-c0a1-4c1e-b081-8529eaf1536a)  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=b04da098-666f-4760-90da-d2a17e78bf47)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=599e5db1-3bf1-4d44-bc7c-81bc545c58ec)  
(중요)
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
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=8081e67f-288c-4714-bff8-e0ff9777692f)  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=647eaf09-3959-439e-8418-fd25221eb6b9)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=482c2890-8d4c-4e13-820f-d5ff256b6a3a)  
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
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=521baa02-5d7a-4cba-8a1a-2af1b6e4cbe4)  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=92f3af60-9a9b-4419-9e95-55f5cb54cf00)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ccd0f116-73c2-4471-a6d9-e07d1dbdd406)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=39abdf7b-ea9d-4b95-a28d-4140374d531d)  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=f4e73a92-583b-4352-b19d-7a8e3ef162b7)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=7da5b341-6a6f-46de-8d01-448da38e9908)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=e5970daf-4440-42fa-8efc-e6190c6a22aa)  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=ead9d29b-becf-448e-bff4-d5bb12d02c64)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=1ba25d9c-0fef-471f-8e30-045fe9586a9c)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=fef2c1d7-2004-43d7-aa49-673c6f374670)\*  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=233c62b7-f2b1-49ce-9a7f-e51435be0d26)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=dd547364-f6bb-453c-9e4d-6b80dfc47fbb)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=45a4784e-5051-4628-9a19-d53f30c1fdf3)\*\*  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=4ffae13f-3432-4849-a2da-a76f96d7ceb3)\*  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=56eae770-5990-4e1b-8b48-3d0602fcc72b)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=5ff65fc2-5969-4d7e-9c72-9a2096dafdcf)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=503cb9c0-d6db-4deb-a555-67af0b25739b)\*\*  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=67581250-50fd-4f4c-a3cc-45ce2662b0c3)  
(KB2621440)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=eeb5385c-fb81-4d33-af2a-986e6cf14ee2)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=16b0195c-84d3-4c08-8b98-ff2c80d144e1)  
(KB2621440)  
(긴급)  
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=3a6c7fdf-105a-4886-ad52-c892f37e32d1)  
(KB2667402)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=75fd93ff-5be5-42b5-ab00-3378e545c271)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=f3a14012-38ae-490e-a48e-7c851f82a7e6)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=40b62d08-d2a2-4900-b01c-46fc761973d0)  
(KB2621440)  
(긴급)  
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=1bbe7cda-4bee-4d65-8127-3c13624a1168)  
(KB2667402)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=71ffba4c-d816-45a9-abef-131915885bc8)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=760b5aa4-4e65-4ff1-9ae2-771234803bf0)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=7c1774cc-e00c-47f3-97a2-bc90de857793)\*  
(KB2621440)  
(긴급)  
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=7ec21f41-1673-4592-b45c-6438ad57e08c)\*  
(KB2667402)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=19a4f3d1-24d2-41af-a41a-e5cc2c6232e8)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=22d6a234-6447-4854-8119-4fddd3c6e1bb)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=86095b20-5869-4b55-8777-ee0af82aaf37)\*\*  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=6a07f99c-8ab4-4e44-8d48-6ac787dd2b51)  
(KB2621440)  
(긴급)  
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=469aa1f6-ed89-4649-8736-eaa5e2ad44ee)  
(KB2667402)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=cb5ac981-e8e5-4df7-84bb-7a2a916d0ce9)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=dc5c336f-329c-4a56-8b24-555e3c8afd50)  
(보통)
</td>
</tr>
</table>
 
Windows Server 2008 및 Windows Server 2008 R2 참고 사항

\*Server Core 설치가 영향을 받습니다. 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

\*\*Server Core 설치는 영향을 받지 않습니다. Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리(영문)](http://technet.microsoft.com/ko-kr/library/ee441255(ws.10).aspx) 및 [Server Core 설치 서비스(영문)](http://technet.microsoft.com/ko-kr/library/ff698994(ws.10).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교(영문)](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

#### Microsoft 개발자 도구 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-021](http://go.microsoft.com/fwlink/?linkid=235362)
</td>
<td style="border:1px solid black;">
[MS12-022](http://go.microsoft.com/fwlink/?linkid=235361)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
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
Microsoft Visual Studio 2008 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=99d7c39a-14f1-4e7e-8a4f-2466b16821eb)  
(KB2669970)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2010
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=f80235ae-da15-4527-93b3-c2f31ec2f387)  
(KB2644980)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=e2aaec35-b2c0-48f0-8a51-34e44f6d12fb)  
(KB2645410)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Expression Design
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-021](http://go.microsoft.com/fwlink/?linkid=235362)
</td>
<td style="border:1px solid black;">
[MS12-022](http://go.microsoft.com/fwlink/?linkid=235361)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=49e12f3a-718d-4d54-82be-b78efb372d07)  
(KB2675064)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Design 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 서비스 팩 1](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=899c6860-6081-429b-971a-4d689444920f)  
(KB2667724)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 2](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=2ca4fb5a-3ab4-410b-b42b-075eb1d70410)  
(KB2667725)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Design 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 3](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=73b44e97-6dda-4e24-9758-e86a1de4c0c8)  
(KB2667727)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design 4
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 4](http://www.microsoft.com/downloads/ko-kr/details.aspx?familyid=be56221e-4271-42dc-a6e4-ebf0290e4ad8)  
(KB2667730)  
(중요)
</td>
</tr>
</table>
 

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

Configuration Manager 2007의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. Configuration Manager 2007의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 Configuration Manager 2007을 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager(영문)](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)를 방문하십시오.

Systems Management Server 2003

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

참고 System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다(이전 섹션의 System Center Configuration Manager 2007 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=ko)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포(영문)](http://technet.microsoft.com/ko-kr/library/cc917507.aspx)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) (영문)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

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

-   MS12-018에서 설명한 문제점을 보고해 주신 [Nikolaos Bougalis](https://technet.microsoft.com/ko-KR/mailto:nikb@bougalis.net)
-   MS12-019에서 설명한 문제점을 보고해 주신 Khaled M. Salameh
-   MS12-020에서 설명한 문제점을 [TippingPoint(영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Luigi Auriemma
-   MS12-021에서 설명한 문제점을 보고해 주신 [Laplinker(영문)](http://www.laplinker.com)
-   MS12-022에서 설명한 문제점을 보고해 주신 [Laplinker(영문)](http://www.laplinker.com)

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2012년 3월 14일): 공지 요약이 게시되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
