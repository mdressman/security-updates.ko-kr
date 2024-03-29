---
TOCTitle: 'MS12-AUG'
Title: 2012 년 8 월 Microsoft 보안 공지 요약
ms:assetid: 'ms12-aug'
ms:contentKeyID: 61230746
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms12-aug(v=Security.10)'
---


2012 년 8 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2012년 8월 14일 화요일 | 업데이트된 날짜: 2012년 12월 12일 수요일

**버전:** 3.0

이 공지 요약 목록에는 2012년 8월 발표된 보안 공지가 포함되어 있습니다.

2012년 8월 보안 공지 발표와 함께 이 공지 요약이 2012년 8월 9일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2012년 8월 15일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [8월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522490&culture=en-us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://go.microsoft.com/fwlink/?linkid=217214) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2722913) <br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 4건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257906">MS12-053</a></td>
<td style="border:1px solid black;">원격 데스크톱의 취약점으로 인한 원격 코드 실행 문제점(2723135) <br />
<br />
이 보안 업데이트는 원격 데스크톱 프로토콜의 비공개적으로 보고된 취약점을 해결합니다. 공격자가 영향을 받는 시스템에 특수하게 조작된 일련의 RDP 패킷을 보낼 경우 이 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 기본적으로 RDP(원격 데스크톱 프로토콜)은 모든 Windows 운영 체제에서 사용되도록 설정되어 있지는 않습니다. RDP가 사용 가능하지 않는 시스템은 취약하지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">Windows Networking Components의 취약점으로 인한 원격 코드 실행 문제점(2733594) <br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 4건을 해결합니다. 이 중 가장 심각한 취약점으로 인해 공격자가 특수하게 조작된 응답을 Windows 인쇄 스풀러 요청에 전송할 경우 원격 코드 실행이 허용될 수 있습니다. 최선의 방화벽 구성 방법과 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 들어오는 공격으로부터 네트워크를 보호할 수 있습니다. 인터넷과 직접 연결되는 시스템의 경우 필요한 포트만 최소한으로 열어 두는 것이 안전합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254386">MS12-060</a></td>
<td style="border:1px solid black;">Windows 공용 컨트롤의 취약점으로 인한 원격 코드 실행 문제점(2720573) <br />
<br />
이 보안 업데이트는 Windows 공용 컨트롤의 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 취약점을 악용하도록 설계된 특수하게 조작된 콘텐츠가 포함된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 그러나 어떠한 경우에도 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다. 악성 파일은 전자 메일 첨부 파일로도 전송될 수 있지만 공격자가 이 취약점을 악용하려면 사용자가 첨부 파일을 열도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft Server 소프트웨어,<br />
Microsoft 개발자 도구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259630">MS12-058</a></td>
<td style="border:1px solid black;">Microsoft Exchange Server WebReady 문서 보기가 원격 코드 실행을 허용할 수 있는 취약점(2740358)  <br />
이 보안 업데이트는 Microsoft Exchange Server WebReady 문서 보기의 공개된 취약점을 해결합니다. 이 취약점은 사용자가 OWA(Outlook Web App)를 사용하여 특수하게 조작된 파일을 미리보는 경우 Exchange 서버에 있는 코드 변환 서비스의 보안 컨텍스트에서 원격 코드를 실행하도록 허용할 수 있습니다. WebReady 문서 보기에 사용되는 Exchange에 있는 코드 변환 서비스는 LocalService 계정에서 실행되고 있습니다. LocalService 계정에는 로컬 컴퓨터의 최소 권한이 있으며 네트워크에서 익명 자격 증명을 제시합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257907">MS12-055</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2731847) <br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점 1건을 해결합니다. 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=256487">MS12-056</a></td>
<td style="border:1px solid black;">JScript 및 VBScript 엔진의 취약점으로 인한 원격 코드 실행 취약점(2706045) <br />
<br />
이 보안 업데이트는 64비트 버전 Microsoft Windows에서 실행되는 JScript 및 VBScript 스크립팅 엔진의 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 공격자는 강제로 사용자가 웹 사이트를 방문하도록 할 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257684">MS12-057</a></td>
<td style="border:1px solid black;">Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점(2731879)  <br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점 1건을 해결합니다. 사용자가 특수하게 조작된 파일을 열거나 특수하게 조작된 CGM(Computer Graphics Metafile) 그래픽 파일을 Office 파일에 포함하는 경우 이 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255002">MS12-059</a></td>
<td style="border:1px solid black;">Microsoft Visio의 취약점으로 인한 원격 코드 실행 문제점(2733918)  <br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Office의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 Visio 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">레이아웃 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1526">CVE-2012-1526</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">비동기 NULL 개체 액세스 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2521">CVE-2012-2521</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">가상 함수 테이블 손상 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2522">CVE-2012-2522</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">JavaScript 정수 오버플로 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2523">CVE-2012-2523</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=256487">MS12-056</a>도 이 취약점을 해결합니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257906">MS12-053</a></td>
<td style="border:1px solid black;">원격 데스크톱 프로토콜 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2526">CVE-2012-2526</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">원격 관리 프로토콜 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1850">CVE-2012-1850</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">인쇄 스풀러 서비스 형식 문자열 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1851">CVE-2012-1851</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">원격 관리 프로토콜 힙 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1852">CVE-2012-1852</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a>- 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">원격 관리 프로토콜 스택 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1853">CVE-2012-1853</a>(영문)</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257907">MS12-055</a></td>
<td style="border:1px solid black;">Win32k 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2527">CVE-2012-2527</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=256487">MS12-056</a></td>
<td style="border:1px solid black;">JavaScript 정수 오버플로 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2523">CVE-2012-2523</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a>도 이 취약점을 해결합니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257684">MS12-057</a></td>
<td style="border:1px solid black;">CGM 파일 형식 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2524">CVE-2012-2524</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259630">MS12-058</a></td>
<td style="border:1px solid black;">악용 가능한 여러 취약점이 Oracle Outside In에 포함되어 있음</td>
<td style="border:1px solid black;">다수*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">*여러 취약점에 대한 자세한 내용은 <a href="http://go.microsoft.com/fwlink/?linkid=259630">MS12-058</a> 공지를 참조하십시오.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255002">MS12-059</a></td>
<td style="border:1px solid black;">Visio DXF 파일 형식 버퍼 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1888">CVE-2012-1888</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254386">MS12-060</a></td>
<td style="border:1px solid black;">MSCOMCTL.OCX RCE 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1856">CVE-2012-1856</a>(영문)</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">Microsoft는 이 취약점을 악용하려는 제한적이며 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
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
<th style="border:1px solid black;" colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
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
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e1df425a-a67e-42f8-9eb5-a503f684c201&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5afc85e3-a214-4774-93ab-17f9d199ebde&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=213b3590-381e-437c-9391-ff6d7400f250&displaylang=ko)  
(KB2722913)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=ccc3d8fb-2631-42d0-87ed-5d29d4b1f598&displaylang=ko)  
(KB2723135)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=5403c78c-6b87-4788-89c3-0140b887ec6f&displaylang=ko)  
(KB2705219)  
(긴급)  
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=c28e01d6-0030-417d-80dd-b34febd22ec1&displaylang=ko)  
(KB2712808)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=db21a230-0f6b-4d74-9f32-3718a59efd28&displaylang=ko)  
(KB2731847)  
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2fdbe657-1810-4c5d-9ba8-5da148272756)  
(KB2722913)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ce5e8621-5457-4a27-9816-9ce719fd6937)  
(KB2722913)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=01784bbc-20fc-4d0f-bfcd-a5a25dd603e8)  
(KB2722913)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a8eb0583-071d-4d8e-92fb-937035411b49)  
(KB2705219)  
(긴급)  
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9e41497-5c49-45fc-8ad0-c853516609df)  
(KB2712808)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a036c343-5c6e-4484-b7f7-c7161c6880fd)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=e1b9a081-0329-4db6-b026-04a332cb0b4d)  
(KB2706045)  
(중요)
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
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
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
없음
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e5e3e9be-ba36-4fdf-93f6-a30fb087d273&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0bced0f3-9778-4ee3-86fb-7f28b57adbce&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=19393940-2519-4e97-89cd-de993ced31d5&displaylang=ko)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2847952f-0234-4cf6-820a-1f0a285b2fb7&displaylang=ko)  
(KB2705219)  
(중요)  
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c20f475d-5211-4fdc-8a2f-4408f1baaece&displaylang=ko)  
(KB2712808)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=50090b08-3f82-4680-b871-2b18fc2386d0&displaylang=ko)  
(KB2731847)  
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=eb92185b-405a-4d96-b119-13f234a9c4ac&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=26cda257-6607-4bd8-9152-cbcc2a753915&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fe7a78fc-f882-4748-a9e3-04b85d136ca2&displaylang=ko)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3833d768-1dab-4a85-822f-87c7fa3db261&displaylang=ko)  
(KB2705219)  
(중요)  
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad883d42-d8bb-482b-bf36-e2007cf73f84&displaylang=ko)  
(KB2712808)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7f72ba9a-80b2-459d-acad-da6a8b900d6f&displaylang=ko)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=81f5d8a5-12e5-4227-ae6f-5aea6ffff2a5&displaylang=ko)  
(KB2706045)  
(낮음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6c5edf14-ecb6-40af-a315-b049457415d6)  
(KB2722913)  
(보통)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c890335b-6ceb-427a-9cc7-95ef8c26d306)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=2fba3a11-3621-464d-ab22-d902195205f4)  
(KB2705219) (중요)  
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=2857701f-3447-452c-a986-9f2fe42fe64d)(KB2712808)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=9e647f22-2e80-4f4a-b648-615243741df2)  
(KB2731847)  
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
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=862bd543-2fc5-4c4c-8d18-4623ccc68166&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=709a85b7-d192-4bba-990a-ea98fdf6e882&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=430a43fa-78b8-4273-81e1-3081767ddcf9&displaylang=ko)  
(KB2722913)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=cbae6606-3721-48b9-ba3e-9d85df7e08b9&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b4b216dc-533e-4fb4-acc8-ce5eb231320e&displaylang=ko)  
(KB2712808)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=41362740-876e-4c9e-9729-67dea6830438&displaylang=ko)  
(KB2731847)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=da933584-40ba-42a0-82fc-b84b41c6c5a4&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ec48d017-d9ed-4b0e-b51f-0f04996088b6&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=5341a615-b737-4e48-8dfd-828725d9d513&displaylang=ko)  
(KB2722913)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e4b4e53b-69d6-4ab6-98bb-3f8871048abe&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=dc966826-83e6-4bdc-bc58-8b6eb8917934&displaylang=ko)  
(KB2712808)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=007b4d50-b770-4e8f-b8d0-060f7bb58ad5&displaylang=ko)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=294a7eb4-c47f-449f-8931-262bec7d6ecc&displaylang=ko)  
(KB2706045)  
(중요)
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
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
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
없음
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=91062e12-401e-472e-a6b6-0eb7216f5264&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=77612ea1-13fb-4c53-bbd2-8796f0d5a9ed&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=f016949d-b931-49f3-867b-f1c64839379e&displaylang=ko)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=354e502b-3016-4c5e-8611-bc1b35e1a7eb&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=35fb03b1-162a-4552-8bb9-6b564acbd57b&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ec759712-2f38-41a9-8b6d-c6908cc58479&displaylang=ko)  
(KB2731847)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a610d606-ca70-4dbd-9971-b6915dc4dc59&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=defe6c53-66d7-4ea5-93b1-7487ccf19f24&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=e5ab43bb-dbdb-4b2b-bbf2-260297ee5518&displaylang=ko)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2b8a730c-46ac-49b7-b9ae-73062d5a79f2&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e89024ca-a9e8-4ebf-91eb-cbf8e05398e7&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=caf68d77-3315-4383-a901-ba0385ffe561&displaylang=ko)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=47b2e47f-30f1-48e8-a857-70df319011ef&displaylang=ko)  
(KB2706045)  
(낮음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6564a6a1-c8ba-4275-81b5-6664c8e3d010)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=cce9a924-a74c-49e0-869f-6b9c1cd12cba)  
(KB2705219)  
(보통)  
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=57153478-4837-438a-8487-929a48fd758a)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=dee601c7-4ab4-4556-8d83-90864b09d365)  
(KB2731847)  
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
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
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
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=625c45f5-5ad1-4ade-8883-33019587ab49&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b2760784-6163-4a8d-86fb-72c88ed2b8ef&displaylang=ko)  
(KB2722913)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=f83f6d97-24f1-4ee0-971d-ab79071fede6&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=2bcfb574-a7d0-4d7e-b557-41bdcddfde42&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c709aabf-4b3f-4780-8b82-c6c33a211e31&displaylang=ko)  
(KB2731847)  
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=625c45f5-5ad1-4ade-8883-33019587ab49&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b2760784-6163-4a8d-86fb-72c88ed2b8ef&displaylang=ko)  
(KB2722913)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=f83f6d97-24f1-4ee0-971d-ab79071fede6&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=2bcfb574-a7d0-4d7e-b557-41bdcddfde42&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=c709aabf-4b3f-4780-8b82-c6c33a211e31&displaylang=ko)  
(KB2731847)  
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f5bc6713-2540-4571-ae1f-04f427b33019&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=cac3b463-fb9c-474e-9e3d-bb96f7b4c14f&displaylang=ko)  
(KB2722913)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=f49e3f9e-8a96-43e6-8b0a-5c9b78cd819d&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=655182f9-110b-4b81-b140-0a5986d7343f&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=f62cf24a-8926-4dde-95ac-cc5f62e448be&displaylang=ko)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ece661be-4ddf-42cc-a62b-15ce53b9d74b&displaylang=ko)  
(KB2706045)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f5bc6713-2540-4571-ae1f-04f427b33019&displaylang=ko)  
(KB2722913)  
(긴급)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=cac3b463-fb9c-474e-9e3d-bb96f7b4c14f&displaylang=ko)  
(KB2722913)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=f49e3f9e-8a96-43e6-8b0a-5c9b78cd819d&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=655182f9-110b-4b81-b140-0a5986d7343f&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=f62cf24a-8926-4dde-95ac-cc5f62e448be&displaylang=ko)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ece661be-4ddf-42cc-a62b-15ce53b9d74b&displaylang=ko)  
(KB2706045)  
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
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
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
없음
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[낮음](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f6ea664b-575c-4cf0-b479-d1a2653288ee&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=30a43d95-f489-49c2-a48a-a262fa196bbf&displaylang=ko)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242&displaylang=ko)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=bbb876e6-a6b9-4193-be5e-d84390d30f1e&displaylang=ko)  
(KB2706045)  
(낮음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f6ea664b-575c-4cf0-b479-d1a2653288ee&displaylang=ko)  
(KB2722913)  
(보통)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=30a43d95-f489-49c2-a48a-a262fa196bbf&displaylang=ko)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242&displaylang=ko)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=bbb876e6-a6b9-4193-be5e-d84390d30f1e&displaylang=ko)  
(KB2706045)  
(낮음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=05a09f6e-b608-4430-b6d4-bb9d10d8347a)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=be89e6a5-34ef-4c23-8e16-722b9ae92073)  
(KB2705219)  
(보통)  
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=27b52fb5-ff3c-4dca-9752-1517b873c9cb)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=7f17c057-939e-415d-b56a-01082695ab77)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=97004a96-0c83-421d-91a9-d55be32610c9)  
(KB2706045)  
(낮음)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=05a09f6e-b608-4430-b6d4-bb9d10d8347a)  
(KB2722913)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=be89e6a5-34ef-4c23-8e16-722b9ae92073)  
(KB2705219)  
(보통)  
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=27b52fb5-ff3c-4dca-9752-1517b873c9cb)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7f17c057-939e-415d-b56a-01082695ab77)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
[JScript 5.8 및 VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=97004a96-0c83-421d-91a9-d55be32610c9)  
(KB2706045)  
(낮음)
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
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
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
없음
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=354e502b-3016-4c5e-8611-bc1b35e1a7eb&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=35fb03b1-162a-4552-8bb9-6b564acbd57b&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ec759712-2f38-41a9-8b6d-c6908cc58479&displaylang=ko)  
(KB2731847)  
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2b8a730c-46ac-49b7-b9ae-73062d5a79f2&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e89024ca-a9e8-4ebf-91eb-cbf8e05398e7&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=caf68d77-3315-4383-a901-ba0385ffe561&displaylang=ko)  
(KB2731847)  
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242&displaylang=ko)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175&displaylang=ko)  
(KB2705219)  
(보통)  
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a&displaylang=ko)  
(KB2712808)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242&displaylang=ko)  
(KB2731847)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Office 제품군 및 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-057](http://go.microsoft.com/fwlink/?linkid=257684)
</td>
<td style="border:1px solid black;">
[MS12-059](http://go.microsoft.com/fwlink/?linkid=255002)
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
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b&displaylang=ko)  
(Windows 공용 컨트롤)  
(KB2726929)  
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
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)  
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=cc2a0eae-5b7e-465b-ab4c-a93ae7c7c458&displaylang=ko)  
(KB2596615)  
(중요)  
[Microsoft Office 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c2b0cb0f-db07-452f-a9a4-886124d3943e&displaylang=ko)  
(KB2596754)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)  
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=cc2a0eae-5b7e-465b-ab4c-a93ae7c7c458&displaylang=ko)  
(KB2596615)  
(중요)  
[Microsoft Office 2007 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=c2b0cb0f-db07-452f-a9a4-886124d3943e&displaylang=ko)  
(KB2596754)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=4e08bab7-1408-444d-bad7-a4db76c7f6d3&displaylang=ko)  
(Windows 공용 컨트롤)  
(KB2597986)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=953b9b69-2f66-4f71-b342-467cc05030ba&displaylang=ko)  
(KB2687501)  
(중요)  
[Microsoft Office 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=a55a33f9-1eb6-469a-967c-a483764772c3&displaylang=ko)  
(KB2687510)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=de95d8b9-51a5-43cd-8ba3-8cbb1320d099&displaylang=ko)  
(KB2687508)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=90b99372-4f13-4f3a-ae52-da6543745248&displaylang=ko)  
(KB2687501)  
(중요)  
[Microsoft Office 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=da8a4d12-d4fc-4b6e-b65f-096dedddf529&displaylang=ko)  
(KB2687510)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=af690cd8-cb2c-4743-96f0-ffaec77adf10&displaylang=ko)  
(KB2687508)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Office Web Components
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-057](http://go.microsoft.com/fwlink/?linkid=257684)
</td>
<td style="border:1px solid black;">
[MS12-059](http://go.microsoft.com/fwlink/?linkid=255002)
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
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Web Components 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Web Components 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b&displaylang=ko)  
(Windows 공용 컨트롤)  
(KB2726929)  
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
<th style="border:1px solid black;" colspan="4">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-057](http://go.microsoft.com/fwlink/?linkid=257684)
</td>
<td style="border:1px solid black;">
[MS12-059](http://go.microsoft.com/fwlink/?linkid=255002)
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
없음
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=62e87f7b-f48e-43a7-86d7-cbb8f0603ea3&displaylang=ko)  
(KB2598287)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=3889e1b3-69b2-4a8f-a0d9-de8c7dc6f5ec&displaylang=ko)  
(KB2598287)  
(중요)
</td>
</tr>
</table>
 
MS12-060 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-058](http://go.microsoft.com/fwlink/?linkid=259630)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[Microsoft SQL Server 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=22be7d30-86f8-4a3b-ba46-b08624581c61&displaylang=ko)  
(KB983812)  
(긴급)  
QFE 업데이트:  
[Microsoft SQL Server 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=09ebb11b-2b82-4891-8ae9-03481c0d7b29&displaylang=ko)  
(KB983811)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Analysis Services 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Analysis Services 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=3f5f7d2c-1fd1-437d-a74c-f316c2cd7818&displaylang=ko)  
(KB983813)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005(32비트 시스템용) 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005(32비트 시스템용) 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b&displaylang=ko)<sup>[1]</sup>
(Windows 공용 컨트롤)  
(KB2726929)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005(x64 기반 시스템용) 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005(x64기반 시스템용) 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b&displaylang=ko)<sup>[1]</sup>
(Windows 공용 컨트롤)  
(KB2726929)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005(Itanium 기반 시스템용) 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005(Itanium 기반 시스템용) 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Windows 공용 컨트롤)  
(KB2726929)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
고급 서비스가 포함된 Microsoft SQL Server 2005 Express Edition 서비스 팩 4
</td>
<td style="border:1px solid black;">
[고급 서비스가 포함된 Microsoft SQL Server 2005 Express Edition 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b&displaylang=ko)<sup>[1]</sup>
(Windows 공용 컨트롤)  
(KB2726929)(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008(32비트 시스템용) 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008(32비트 시스템용) 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008(x64 기반 시스템용) 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008(x64 기반 시스템용) 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097&displaylang=ko)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows 공용 컨트롤)  
(KB2687441)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Commerce Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-058](http://go.microsoft.com/fwlink/?linkid=259630)
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
Microsoft Commerce Server 2002 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2002 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=9ad19d40-16ed-47ad-b907-8a48bb64c6d3)  
(KB2716389)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d972437-f71a-4576-b5c1-a940c0824438)  
(KB2716390)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2009
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009](http://www.microsoft.com/downloads/details.aspx?familyid=3879fecd-8360-4c01-b88e-d56e8570cafb)  
(KB2716392)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2009 R2
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009 R2](http://www.microsoft.com/downloads/details.aspx?familyid=ce4f9470-e2b2-417e-9015-30355e837fbb)  
(KB2716393)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Host Integration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=3dde4ef1-d41f-45b0-8660-a546cbe3fc81)  
(KB2711207)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-058](http://go.microsoft.com/fwlink/?linkid=259630)
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
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=21a26e23-9d83-41b6-95be-4b48f6e76023&displaylang=ko)  
(KB2756497)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=8646aaca-9829-4d3f-a77b-d24673818da7&displaylang=ko)  
(KB2756496)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b24182a-cee9-4ca0-9cc5-c4453475999d&displaylang=ko)  
(KB2756485)  
(긴급)
</td>
</tr>
</table>
 
MS12-060 참고사 항

<sup>[1]</sup>이 업데이트는 Microsoft Office 2003용 KB2726929 업데이트와 동일합니다.

<sup>[2]</sup>이 업데이트는 Microsoft Office 2007용 KB2687441 업데이트와 동일합니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 개발자 도구 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Visual FoxPro
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
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
Microsoft Visual FoxPro 8.0 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=0bef712a-b9e0-4ea9-98bf-68db366c8b8b&displaylang=ko)  
(KB2708940)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1ee09491-4871-41ca-a39c-8360d5a568d4&displaylang=ko)  
(KB2708941)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Visual Basic
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
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
Visual Basic 6.0 Runtime
</td>
<td style="border:1px solid black;">
[Visual Basic 6.0 Runtime](http://www.microsoft.com/downloads/details.aspx?familyid=847ec64b-95be-463b-bdfb-969e91fe3207&displaylang=ko)  
(KB2708437)  
(긴급)
</td>
</tr>
</table>
 
MS12-060 참고 사항

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

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx)를 참조하십시오.

System Center Configuration Manager

System Center Configuration Manager 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. System Center Configuration Manager를 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

System Center Configuration Manager의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. System Center Configuration Manager의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 System Center Configuration Manager를 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. System Center Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)를 방문하십시오.

Systems Management Server 2003

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

참고 System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager를 지금 사용할 수 있습니다(이전 섹션의 System Center Configuration Manager 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (영문)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet.microsoft.com/library/cc749197) (영문) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199) : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

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

-   MS12-052에서 설명한 문제점을VeriSign iDefense Labs와 협력하여 보고해 주신 [GWSlabs](http://labs.idefense.com/)(영문)
-   MS12-052에서 설명한 문제점을 [Beyond Security's SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) (영문)프로그램과 협력하여 보고해 주신 Derek Soeder
-   MS12-052에서 설명한 문제점을 보고해 주신 [Trend Micro](http://www.trendmicro.com/)(영문)의 Sing-ting Tsai 및 Ming-Chieh Pan
-   MS12-052에서 설명한 문제점을 보고해 주신 [Google's Chrome Security Team](http://chrome.google.com/)의 Cris Neckar
-   MS12-053에서 설명한 문제점을 보고해 주신 NCC Group의 Edward Torkington
-   MS12-054에서 설명한 네 가지 문제점을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Yamata Li
-   MS12-055에서 설명한 문제점을 보고해 주신 [Google Inc](http://www.google.com/)의 [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   MS12-056에서 설명한 문제점을 보고해 주신 [Google's Chrome Security Team](http://chrome.google.com/)의 Cris Neckar
-   MS12-057에서 설명한 문제점을 보고해 주신 [Andrei Costin](http://www.andreicostin.com)(영문)
-   MS12-058에서 설명한 13가지 문제점을 해결하기 위해 협력해 주신 [CERT/CC](http://www.cert.org/)(영문)의 Will Dorman
-   MS12-059에서 설명한 문제점을 [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Alexander Gavrun

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617.aspx)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2012년 8월 14일): 공지 요약이 게시되었습니다.
-   V2.0(2012년 10월 9일): MS12-053, MS12-054, MS12-055 및 MS12-058의 업데이트 패키지 다시 릴리스와 일치하도록 공지가 개정되었습니다. 고객은 Microsoft 보안 권고 2749655에 설명된 디지털 인증서 관련 문제를 방지하기 위해 다시 릴리스된 업데이트 패키지를 적용해야 합니다. 자세한 내용은 공지를 참조하십시오.
-   V3.0(2012년 12월 12일): MS12-057에서는 영향을 받는 모든 Microsoft Office 2010 에디션용 KB2553260 업데이트와 KB2589322 업데이트를 KB2687501 업데이트와 KB2687510 업데이트로 각각 대체했습니다. MS12-059에서는 영향을 받는 모든 Microsoft Visio 2010 에디션용 KB2597171 업데이트를 KB2687508 업데이트로 대체했습니다. MS12-060에서는 영향을 받는 모든 Microsoft Office 2003, Microsoft Office 2003 Web Components, Microsoft SQL Server 2005 에디션에 설치된 Windows 공용 컨트롤용 KB2687323 업데이트를 KB2726929 업데이트로 대체했습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
