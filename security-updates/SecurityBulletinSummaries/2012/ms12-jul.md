---
TOCTitle: 'MS12-JUL'
Title: 2012년 7월 Microsoft 보안 공지 요약
ms:assetid: 'ms12-jul'
ms:contentKeyID: 61230750
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms12-jul(v=Security.10)'
---


2012년 7월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2012년 7월 10일 화요일 | 업데이트된 날짜: 2012년 12월 12일 수요일

**버전:** 5.1

이 공지 요약 목록에는 2012년 7월에 발표된 보안 공지가 포함되어 있습니다.

2012년 7월 보안 공지 발표와 함께 이 공지 요약이 2012년 7월 5일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2012년 7월 11일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [7월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032518600). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://go.microsoft.com/fwlink/?linkid=217214) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254824"><strong>MS12-043</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services의 취약점으로 인한 원격 코드 실행 문제점(2722479)</strong><br />
<br />
이 보안 업데이트는 일반에 공개된 Microsoft XML Core Services의 취약점을 해결합니다. 이 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 공격자는 강제로 사용자가 이러한 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 전자 메일 메시지 또는 인스턴트 메신저 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하도록 유도하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office,<br />
Microsoft 개발자 도구,<br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254377"><strong>MS12-044</strong></a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2719177)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점들은 모두 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254441"><strong>MS12-045</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft Data Access</strong> <strong>Components의 취약점으로 인한 원격 코드 실행 문제점(2698365)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점은 사용자가 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252510"><strong>MS12-046</strong></a></td>
<td style="border:1px solid black;"><strong>Visual Basic for Applications의 취약점으로 인한 원격 코드 실행 문제점(2707960)</strong><br />
<br />
이 보안 업데이트는 Microsoft Visual Basic for Applications의 공개된 취약점 1건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 DLL(동적 연결 라이브러리) 파일과 동일한 디렉터리에 있는 합법적인 Microsoft Office 파일(예: .docx 파일)을 여는 경우 원격 코드 실행이 허용될 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 사용자가 관리자 권한의 사용자 권한으로 로그온한 경우 공격자가 영향을 받는 시스템을 완전히 제어할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft 개발자 도구</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254380"><strong>MS12-047</strong></a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2718523)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239507"><strong>MS12-048</strong></a></td>
<td style="border:1px solid black;"><strong>Windows 셸의 취약점으로 인한 원격 코드 실행 문제점(2691442)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점 1건을 해결합니다. 사용자가 특수하게 조작된 이름을 가진 파일 또는 디렉터리를 열 경우 이 취약점으로 인해 원격 코드가 실행될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251035"><strong>MS12-049</strong></a></td>
<td style="border:1px solid black;"><strong>TLS의 취약점으로 인한 정보 유출 문제점(2655992)</strong><br />
<br />
이 보안 업데이트는 TLS의 공개된 취약점을 해결합니다. 이 취약점은 공격자가 영향 받은 시스템에서 제공된 암호화된 웹 트래픽을 가로챌 경우 정보가 노출되도록 할 수 있습니다. CBC 모드를 사용하지 않는 모든 암호 그룹은 영향을 받지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;"><strong>SharePoint의 취약점으로 인한 권한 상승 문제점(2695502)</strong><br />
<br />
이 보안 업데이트는 Microsoft SharePoint 및 Windows SharePoint Services에서 발견되어 공개적으로 보고된 취약점 1건과 비공개적으로 보고된 취약점 5건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 특수하게 조작된 URL을 클릭하여 대상 SharePoint 사이트로 유인된 경우 권한 상승 문제가 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255000"><strong>MS12-051</strong></a></td>
<td style="border:1px solid black;"><strong>Microsoft Office for Mac의 취약점으로 인한 권한 상승 문제점(2721015)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office for Mac의 공개된 취약점 1건을 해결합니다. 이 취약점으로 인해 공격자가 영향을 받는 시스템에 악의적인 실행 파일을 배치하고 나중에 다른 사용자가 로그인하여 악의적인 실행 파일을 실행할 경우 권한 상승이 발생할 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254824"><strong>MS12-043</strong></a></td>
<td style="border:1px solid black;">MSXML 초기화되지 않은 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1889">CVE-2012-1889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 이 취약점을 악용하려는 제한적이며 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254377"><strong>MS12-044</strong></a></td>
<td style="border:1px solid black;">캐시된 개체 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1522">CVE-2012-1522</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254377"><strong>MS12-044</strong></a></td>
<td style="border:1px solid black;">특성 제거 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1524">CVE-2012-1524</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254441"><strong>MS12-045</strong></a></td>
<td style="border:1px solid black;">ADO Cachesize 힙 오버플로 RCE 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1891">CVE-2012-1891</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252510"><strong>MS12-046</strong></a></td>
<td style="border:1px solid black;">Visual Basic for Applications의 안전하지 않은 라이브러리 로드 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1854">CVE-2012-1854</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 이 취약점을 악용하려는 제한적이며 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254380"><strong>MS12-047</strong></a></td>
<td style="border:1px solid black;">키보드 레이아웃 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1890">CVE-2012-1890</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 악용 코드 구축 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254380"><strong>MS12-047</strong></a></td>
<td style="border:1px solid black;">Win32k 부정확한 유형 처리 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1893">CVE-2012-1893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239507"><strong>MS12-048</strong></a></td>
<td style="border:1px solid black;">명령 주입 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0175">CVE-2012-0175</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251035"><strong>MS12-049</strong></a></td>
<td style="border:1px solid black;">TLS 프로토콜 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1870">CVE-2012-1870</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">HTML 삭제 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">XSS scriptresx.ashx 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1859">CVE-2012-1859</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">SharePoint 사용자 이름 스크립트 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1861">CVE-2012-1861</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251611"><strong>MS12-050</strong></a></td>
<td style="border:1px solid black;">SharePoint 반영된 목록 매개 변수 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1863">CVE-2012-1863</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255000"><strong>MS12-051</strong></a></td>
<td style="border:1px solid black;">Office for Mac 잘못된 폴더 권한 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1894">CVE-2012-1894</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=017f1ed7-eed4-4de3-aca1-93fb25058866)  
(KB2719985)  
(긴급)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(긴급)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=017f1ed7-eed4-4de3-aca1-93fb25058866)  
(KB2719985)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=496e93ac-fcce-458f-839b-25ff1ab22fde)  
(KB2698365)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=a4bc78fb-3927-4059-ae1c-35c369e39203)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=405ce29a-7c97-44de-aed9-4c90cbdaaf1b)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=8324496f-aca4-4a86-833d-c22341e71cd3)  
(KB2655992)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d27bd5e9-a3a6-411e-bc50-2b03d64fb50c)  
(KB2719985)  
(긴급)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(긴급)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=aaf10833-0487-4026-805b-97543140b1fd)  
(KB2721693)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=64f8d1a4-4a9d-4ee0-8a66-d157d516afb5)  
(KB2698365)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=94029b68-5b7b-4d0e-b175-cfc2b0eba91a)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=36fc4c85-fa93-4c6b-b93a-94460e9ba23b)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5f268365-9c18-4fc7-b11e-b1f19c4a5a2a)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b7321c17-0e8e-4217-8da6-4c270dbfc802)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=3b56ba48-b74c-4681-8e17-715dc5d45e2c)  
(KB2721693)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=465ef3d0-df59-4f73-a06d-49a81286c01f)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d53bd571-ad30-41c7-8c5f-f217097770f5)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1f058336-4a6a-47d0-ad6f-276dc381d1db)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b13e2388-01f3-46bf-97b4-612e2778477a)  
(KB2655992)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=2b24d755-f96f-47d6-b286-2bfd4e278dcc)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=aaf10833-0487-4026-805b-97543140b1fd)  
(KB2721693)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d1955b23-5931-4891-9c11-401efcb6c05c)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5f261883-daec-4af3-8bc1-46da9c164de7)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5b6d6227-8695-4ecb-86e1-bb264f954898)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0bd0591-62f8-40d1-93fa-7f0afc4fc09c)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=eab0f4c6-3f2e-435d-aef7-d9230295ab15)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=68eb373e-2c1e-40db-8ad0-0a369a96255b)  
(KB2721693)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e46047d5-9a2d-48c4-b1c8-3db884c25b5c)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=60c57c8b-6d56-42de-ab1e-e4e3258c7818)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=563399b3-cb19-40e9-ba9d-0079032c8cee)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b91df558-5446-4858-92af-50cfbab27ff5)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f8ccdb90-66bd-471a-9c78-825d1140b5ac)  
(KB2719985)  
(긴급)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(긴급)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f8ccdb90-66bd-471a-9c78-825d1140b5ac)  
(KB2719985)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b6a75978-0c11-49fb-8aa7-c47efb3bf4e8)  
(KB2719177)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0c43c093-296e-4e12-b995-4f9e3f00cbe0)  
(KB2698365)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3c957f8a-8f32-4a12-ade9-10a7e2984e88)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2e9a4aeb-3f34-483c-ba3a-3141164e9e8a)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7286a6e2-9c31-493f-aae3-776f72e85503)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e8553934-a202-4033-b9c5-27bc4207469d)  
(KB2719985)  
(긴급)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(긴급)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e8553934-a202-4033-b9c5-27bc4207469d)  
(KB2719985)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=8470af29-68e2-4fd2-bc30-3c9188e65c59)  
(KB2719177)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4d9b91c9-a412-4344-b934-0d2fbd9526fd)  
(KB2698365)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7300636f-aefd-46bf-a7ba-780d6f939b4f)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=fe8467e2-8b37-4ec2-ba9f-324918f1f045)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c62ec513-887c-4a42-a3cc-3e92631526ed)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=42a869b9-085a-450a-b69e-f634d01075dd)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=42a869b9-085a-450a-b69e-f634d01075dd)  
(KB2719985)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=4009dd66-b6d0-4c14-acde-f52d75d8f9d1)  
(KB2719177)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a8ed6a19-c128-46e5-ae38-5fa9f843ba0d)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ed201422-7c65-4c20-a825-8cecab1aeebc)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d873c5a-57dc-4792-942e-124ce1a4ec2b)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=97030267-6b19-46ae-84ce-0bb1f91ab951)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7b2d780-cc92-4f3e-b5a2-9f2ac66b6f1c)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7b2d780-cc92-4f3e-b5a2-9f2ac66b6f1c)  
(KB2719985)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b609981c-fda8-4085-ae8d-5b760ad4e73f)  
(KB2719177)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=043464e4-9572-419b-a03a-ca11bf918052)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e1a27c9-6495-4030-8a46-264afd78a5a1)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d49e3e7e-910a-4069-b0b0-0987bb9fdde2)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8a5f6e84-5e5b-42c3-a5b7-65defdb0665f)  
(KB2655992)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=359a86d6-e94a-4de5-83d9-6b0273115bff)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=359a86d6-e94a-4de5-83d9-6b0273115bff)  
(KB2719985)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=00638d5e-6156-4c1b-a131-3d1fff514bdb)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=76f640b8-5aab-4880-9d74-22e2a5086342)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ca890b4d-124f-4293-b8d0-69f6302b5189)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e886c5f4-7f38-4c90-905b-a682e6a8ffd0)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(긴급)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(긴급)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0be922a4-6b8a-4017-bc31-1cadd8cdb472)  
(KB2719177)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=ed997ae7-2e45-4620-bcbe-a5006aaca448)  
(KB2698365)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b4bed780-b120-43a1-900e-89b3be7da8b1)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=8ab3eadf-9437-4323-8323-87dfd23245fd)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=da706b4e-7c22-4929-96d3-f8b0fa10f043)  
(KB2655992)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(긴급)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
(긴급)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d8a4817c-481c-4ed2-980a-21623f0ca6d2)  
(KB2719985)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0be922a4-6b8a-4017-bc31-1cadd8cdb472)  
(KB2719177)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=ed997ae7-2e45-4620-bcbe-a5006aaca448)  
(KB2698365)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=b4bed780-b120-43a1-900e-89b3be7da8b1)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=8ab3eadf-9437-4323-8323-87dfd23245fd)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=da706b4e-7c22-4929-96d3-f8b0fa10f043)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(긴급)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(긴급)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=739e4f24-8433-4dc9-a106-a70ae4040606)  
(KB2719177)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4040c290-bf41-4e14-8269-da95ee06d8e7)  
(KB2698365)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3efb0de1-252b-4b72-86f3-e747f8fa2229)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=f518f273-b3b9-4cbf-b820-05a1adc79342)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=07518fb7-031f-4fa0-836c-8f33c247868b)  
(KB2655992)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(긴급)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(긴급)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1962879-1725-4d60-933f-eb351bee56bc)  
(KB2719985)  
(긴급)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=739e4f24-8433-4dc9-a106-a70ae4040606)  
(KB2719177)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4040c290-bf41-4e14-8269-da95ee06d8e7)  
(KB2698365)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=3efb0de1-252b-4b72-86f3-e747f8fa2229)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=f518f273-b3b9-4cbf-b820-05a1adc79342)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=07518fb7-031f-4fa0-836c-8f33c247868b)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=91e8ecf8-4f6d-4e86-bc6b-617749090190)  
(KB2719177)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e749883d-221a-411a-9c85-759d50cefa9d)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f75a3d2d-8322-40a6-b735-faeb8b4873b6)  
(KB2719985)  
(보통)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=91e8ecf8-4f6d-4e86-bc6b-617749090190)  
(KB2719177)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e749883d-221a-411a-9c85-759d50cefa9d)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=eeab7dbb-f6ca-44bd-a172-c07fc5803fd6)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=772f2975-065d-44f3-adf8-82188bd43196)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c9c3b471-4a81-4a44-93ad-674650454c53)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=49e182b5-4499-42a1-8180-9bb920e154cb)  
(KB2655992)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(보통)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=77f45630-288e-46dd-8cb7-c59b07a4bde4)  
(KB2721691)  
(보통)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a745388e-9fef-412e-8d00-9195af506cf5)  
(KB2719985)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=eeab7dbb-f6ca-44bd-a172-c07fc5803fd6)  
(KB2698365)  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=772f2975-065d-44f3-adf8-82188bd43196)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=c9c3b471-4a81-4a44-93ad-674650454c53)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=49e182b5-4499-42a1-8180-9bb920e154cb)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c34c2511-84d4-4f7e-b61a-086e6ee26ffa)  
(KB2721691)  
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
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
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
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
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
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91fcc9f2-86ad-47e9-b298-91d74f852c19)  
(KB2721691)  
(보통)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Server Core 설치 옵션
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-044**](http://go.microsoft.com/fwlink/?linkid=254377)
</td>
<td style="border:1px solid black;">
[**MS12-045**](http://go.microsoft.com/fwlink/?linkid=254441)
</td>
<td style="border:1px solid black;">
[**MS12-047**](http://go.microsoft.com/fwlink/?linkid=254380)
</td>
<td style="border:1px solid black;">
[**MS12-048**](http://go.microsoft.com/fwlink/?linkid=239507)
</td>
<td style="border:1px solid black;">
[**MS12-049**](http://go.microsoft.com/fwlink/?linkid=251035)
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
<td style="border:1px solid black;">
없음
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2
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
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=ed201422-7c65-4c20-a825-8cecab1aeebc)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d873c5a-57dc-4792-942e-124ce1a4ec2b)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=97030267-6b19-46ae-84ce-0bb1f91ab951)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e1a27c9-6495-4030-8a46-264afd78a5a1)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d49e3e7e-910a-4069-b0b0-0987bb9fdde2)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=8a5f6e84-5e5b-42c3-a5b7-65defdb0665f)  
(KB2655992)  
(중요)
</td>
</tr>
<tr class="alternateRow">
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
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(중요)
</td>
</tr>
<tr>
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=73a9ff32-4009-4fd4-a82b-1e22c09d3087)  
(KB2718523)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=d16fa6b9-43aa-4d0f-a230-52664e972ab9)  
(KB2691442)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=c9ef728f-abef-4076-bb13-7488af471aa4)  
(KB2655992)  
(중요)
</td>
</tr>
</table>
 
**MS12-043 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="5">
Microsoft Office 제품군 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
<td style="border:1px solid black;">
[**MS12-051**](http://go.microsoft.com/fwlink/?linkid=255000)
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
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=c4c925b8-df99-4d4f-b939-878d77d64514)  
(KB2687627)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=d49c4893-d867-4d16-90f5-354eb4757d90)<sup>[1]</sup>
(KB2687626)  
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
Microsoft Office 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>
(KB2596744)  
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
Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=181bbd45-9128-4c26-af1e-fadfd83ff756)<sup>[1]</sup>
(KB2596744)  
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
Microsoft Office 2010(32비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=a7cc8fdc-1c64-434f-87a6-72ddcc356654)  
(KB2598243)  
(중요)  
[Microsoft Office 2010(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=3050c06c-3cfc-4ce7-83cd-017d0922d597)  
(KB2553447)  
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
Microsoft Office 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=a7cc8fdc-1c64-434f-87a6-72ddcc356654)  
(KB2598243)  
(중요)  
[Microsoft Office 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=3050c06c-3cfc-4ce7-83cd-017d0922d597)  
(KB2553447)  
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
Microsoft Office 2010(64비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=ab442918-8184-4c7c-84b0-5a3635fdb005)  
(KB2598243)  
(중요)  
[Microsoft Office 2010(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=0a8af868-abf7-4aeb-813a-418a04b31608)  
(KB2553447)  
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
Microsoft Office 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=ab442918-8184-4c7c-84b0-5a3635fdb005)  
(KB2598243)  
(중요)  
[Microsoft Office 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=0a8af868-abf7-4aeb-813a-418a04b31608)  
(KB2553447)  
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
<th style="border:1px solid black;" colspan="5">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
<td style="border:1px solid black;">
[**MS12-051**](http://go.microsoft.com/fwlink/?linkid=255000)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체** **심각도**
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=877700ed-3d03-4d46-a77b-5063d8f7d2e3)  
(KB2721015)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="5">
기타 Microsoft Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
</td>
<td style="border:1px solid black;">
[**MS12-051**](http://go.microsoft.com/fwlink/?linkid=255000)
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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
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
Microsoft Office 호환 기능 팩 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
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
Microsoft Office 호환 기능 팩 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
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
Microsoft Groove 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(긴급)

</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(긴급)

</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=da8fa3b6-5d01-49e1-a1ce-e3f47ace102b)  
(KB2596666)  
(중요)  
[Microsoft InfoPath 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0c826bc-aef8-4833-8471-1824a405c59f)  
(KB2596786)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=da8fa3b6-5d01-49e1-a1ce-e3f47ace102b)  
(KB2596666)  
(중요)  
[Microsoft InfoPath 2007 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=a0c826bc-aef8-4833-8471-1824a405c59f)  
(KB2596786)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010(32비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=698e6369-253b-4dbe-b6cd-7ea5ea09e043)  
(KB2553431)  
(중요)  
[Microsoft InfoPath 2010(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=036b2482-0fb4-46f0-9c38-8bae6d0d669b)  
(KB2553322)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=698e6369-253b-4dbe-b6cd-7ea5ea09e043)  
(KB2553431)  
(중요)  
[Microsoft InfoPath 2010 서비스 팩 1(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=036b2482-0fb4-46f0-9c38-8bae6d0d669b)  
(KB2553322)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010(64비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=3bf373aa-b4ad-4e1a-9578-800485ece148)  
(KB2553431)  
(중요)  
[Microsoft InfoPath 2010(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=e24337cb-83b4-424f-bc4d-0d43437228a2)  
(KB2553322)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=3bf373aa-b4ad-4e1a-9578-800485ece148)  
(KB2553431)  
(중요)  
[Microsoft InfoPath 2010 서비스 팩 1(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=e24337cb-83b4-424f-bc4d-0d43437228a2)  
(KB2553322)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**MS12-043 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

**MS12-046 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

<sup>[1]</sup>Microsoft Office에 대한 이러한 업데이트는 취약한 공유 Office 구성 요소를 포함하고 있는 지원 대상인 모든 Microsoft Office 제품군 및 기타 Microsoft Office 소프트웨어에 적용됩니다. 여기에는 지원 대상인 Microsoft Visio 및 Microsoft Project 버전이 포함됩니다.

**MS12-050 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
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
Microsoft Office SharePoint Server 2007 서비스 팩 2(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 2(coreserver)(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=4073d6e1-32f0-44a8-ae55-3c140ebc09d2)<sup>[1]</sup>
(KB2596663)  
(중요)  
[Microsoft Office SharePoint Server 2007 서비스 팩 2(xlsrvwfe)(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=d9091923-67c7-4535-b44c-40a5292a94d9)<sup>[1]</sup>
(KB2596942)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 서비스 팩 3(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 3(coreserver)(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=4073d6e1-32f0-44a8-ae55-3c140ebc09d2)<sup>[1]</sup>
(KB2596663)  
(중요)  
[Microsoft Office SharePoint Server 2007 서비스 팩 3(xlsrvwfe)(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=d9091923-67c7-4535-b44c-40a5292a94d9)<sup>[1]</sup>
(KB2596942)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 서비스 팩 2(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 2(coreserver)(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=b1acb373-0041-4883-8834-90a72ac04c91)<sup>[1]</sup>
(KB2596663)  
(중요)  
[Microsoft Office SharePoint Server 2007 서비스 팩 2(xlsrvwfe)(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=723a5553-8610-49bf-99c0-bd94926bdc0b)<sup>[1]</sup>
(KB2596942)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 서비스 팩 3(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 3(coreserver)(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=b1acb373-0041-4883-8834-90a72ac04c91)<sup>[1]</sup>
(KB2596663)  
(중요)  
[Microsoft Office SharePoint Server 2007 서비스 팩 2(xlsrvwfe)(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=723a5553-8610-49bf-99c0-bd94926bdc0b)<sup>[1]</sup>
(KB2596942)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010(wosrv)](http://www.microsoft.com/downloads/details.aspx?familyid=59cbb3d0-4ba5-4f89-b54c-ae9aa2aa3b41)  
(KB2553424)  
(중요)  
[Microsoft SharePoint Server 2010(coreserverloc)](http://www.microsoft.com/downloads/details.aspx?familyid=8a853489-a3ec-4be2-8093-6a992f9c8368)  
(KB2553194)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 서비스 팩 1(wosrv)](http://www.microsoft.com/downloads/details.aspx?familyid=59cbb3d0-4ba5-4f89-b54c-ae9aa2aa3b41)  
(KB2553424)  
(중요)  
[Microsoft SharePoint Server 2010 서비스 팩 1(coreserverloc)](http://www.microsoft.com/downloads/details.aspx?familyid=8a853489-a3ec-4be2-8093-6a992f9c8368)  
(KB2553194)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
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
Microsoft Groove Server 2007 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2010
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010](http://www.microsoft.com/downloads/details.aspx?familyid=e2346078-fc93-4355-bc83-0d0dc1cd4b2f)  
(KB2589325)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=e2346078-fc93-4355-bc83-0d0dc1cd4b2f)  
(KB2589325)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows SharePoint Services 및 Microsoft SharePoint Foundation
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 2.0
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=7a54f510-0782-44c4-848a-8ef90d332e61)<sup>[2]</sup>
(KB2760604)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 2(32비트 버전)
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 서비스 팩 2(32비트 버전)](http://www.microsoft.com/downloads/details.aspx?familyid=61b9f234-3d9c-41d4-854d-30ca5e6fd2a6)  
(KB2596911)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 2(64비트 버전)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 서비스 팩 2(64비트 버전)](http://www.microsoft.com/downloads/details.aspx?familyid=24265175-635f-4846-afcc-f692d4710707)  
(KB2596911)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010
</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010](http://www.microsoft.com/downloads/details.aspx?familyid=4d610646-a0bd-492c-9077-fb2c92588c14)  
(KB2553365)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=4d610646-a0bd-492c-9077-fb2c92588c14)  
(KB2553365)  
(중요)
</td>
</tr>
</table>
 
**MS12-043 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

**MS12-050 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

<sup>[1]</sup>지원 대상인 Microsoft Office SharePoint Server 2007 에디션의 경우 Microsoft Office SharePoint 2007용 보안 업데이트 패키지(KB2596663 및 KB2596942) 외에도 Microsoft Windows SharePoint Services 3.0용 보안 업데이트(KB2596911)를 설치해야 이 공지에 설명된 취약점을 방지할 수 있습니다.

<sup>[2]</sup>이 업데이트는 Microsoft 다운로드 센터에서만 다운로드할 수 있습니다.

#### Microsoft Office Web Apps

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-050**](http://go.microsoft.com/fwlink/?linkid=251611)
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
Microsoft Office Web Apps 2010
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010](http://www.microsoft.com/downloads/details.aspx?familyid=f2d1c371-d617-4792-966e-14ae9ed6b8a1)  
(KB2598239)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=f2d1c371-d617-4792-966e-14ae9ed6b8a1)  
(KB2598239)
</td>
</tr>
</table>
 
**MS12-050 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 개발자 도구 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Expression Web
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
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
Microsoft Expression Web 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=b45f5c9a-d601-4192-92c3-064e9b94785a)  
(KB2596856)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Visual Basic for Applications
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS12-043**](http://go.microsoft.com/fwlink/?linkid=254824)
</td>
<td style="border:1px solid black;">
[**MS12-046**](http://go.microsoft.com/fwlink/?linkid=252510)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic for Applications](http://www.microsoft.com/downloads/details.aspx?familyid=ea7c5762-586f-4e38-ad63-43eb05e79f4d)<sup>[1]</sup>
(KB2688865)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK<sup>[2]</sup><sup>[3]</sup>
(중요)
</td>
</tr>
</table>
 
**MS12-043 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

**MS12-046 참고 사항**

동일한 공지 ID의 추가 업데이트 파일에 대해서는 **영향을 받는 소프트웨어 및 다운로드 위치** 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

<sup>[1]</sup>이 업데이트 패키지는 지원 대상인 Microsoft Visual Basic for Applications 런타임(Vbe6.dll) 버전에 적용되며 Microsoft 다운로드 센터에서만 사용할 수 있습니다.

<sup>[2]</sup>지원 대상인 VBA SDK 버전은 Microsoft Visual Basic for Applications SDK 6.3, Microsoft Visual Basic for Applications SDK 6.4 및 Microsoft Visual Basic for Applications SDK 6.5입니다.

<sup>[3]</sup>독립 소프트웨어 공급업체(ISV)는 이 공지에서 설명하는 취약점을 해결한 업데이트된 버전의 Visual Basic for Applications SDK를 Summit Software Company에서 사용할 수 있습니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)을 참조하십시오.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx)를 참조하십시오.

**SystemCenter Configuration Manager**

System Center Configuration Manager 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. System Center Configuration Manager를 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

System Center Configuration Manager의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. System Center Configuration Manager의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 System Center Configuration Manager를 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. System Center Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)를 방문하십시오.

**Systems Management Server 2003**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

**참고** System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager를 지금 사용할 수 있습니다(이전 섹션의 **System** Center Configuration Manager 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)를 방문하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS12-043에서 설명한 문제점을 해결하기 위해 협력해 주신 [Google Security Team](http://www.google.com/)
-   MS12-043에서 설명한 문제점을 보고해 주신 [Qihoo 360 Security Center](http://www.360.cn/)
-   MS12-044에서 설명한 문제점을 [VeriSign iDefense Labs](http://labs.idefense.com/)와 협력하여 보고해 주신 spa-s3c.blogspot.com의 Jose A. Vazquez
-   MS12-044에서 설명한 문제점을 [VeriSign iDefense Labs](http://labs.idefense.com/)와 협력하여 보고해 주신 Omair
-   MS12-045에서 설명한 문제점을 [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS12-046에서 설명한 문제점을 보고해 주신 [Huawei Security Labs](http://www.huawei.com)의 Bai Haowen
-   MS12-047에서 설명한 문제점을 보고해 주신 [Core Security Technologies](http://www.coresecurity.com/)의 Nicolas Economou
-   MS12-047에서 설명한 문제점을 보고해 주신 [Qihoo 360 Security Center](http://www.360.cn/)
-   MS12-047에서 설명한 문제점을 [Secunia Research](http://secunia.com/)와 협력하여 보고해 주신 Neusoft Corporation의 Lufeng Li
-   MS12-048에서 설명한 문제점을 보고해 주신 [IBM Security Systems - Application Security](http://blog.watchfire.com/)의 Adi Cohen
-   MS12-050에서 설명한 문제점을 보고해 주신 [IBM Security Systems - Application Security](http://blog.watchfire.com/)의 Adi Cohen
-   MS12-050에서 설명한 문제점을 보고해 주신 [Salesforce.com Product Security Team](https://trust.salesforce.com/)의 Yang Yang

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617.aspx)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0 (2012년 7월 10일): 공지 요약이 게시되었습니다.
-   V1.1(2012년 7월 10일): 취약점의 심각도가 보통이므로 악용 가능성 인덱스에서 CVE-2012-1860을 제거했습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 악용 가능성 인덱스에 포함됩니다.
-   V2.0(2012년 8월 15일): MS12-043에서 Microsoft XML Core Services 5.0에 대한 다운로드 링크를 추가하였습니다.
-   V3.0(2012년 10월 9일): MS12-043에서 지원 대상 Windows 8 및 Windows Server 2012 에디션에 설치된 경우 영향을 받는 소프트웨어에 Microsoft XML Core Services 4.0이 추가되었습니다. 자세한 내용은 MS12-043 공지를 참조하십시오.
-   V4.0(2012년 11월 13일): MS12-046에서 Microsoft Office 2003 서비스 팩 3에 대한 KB2598361 업데이트를 KB2687626 업데이트로 교체했습니다. 자세한 내용은 MS12-046 공지를 참조하십시오.
-   V5.0(2012년 12월 11일): MS12-043에서 Microsoft Office 2003 서비스 팩 3에 설치된 Microsoft XML Core Services 5.0용 KB2687324 업데이트를 KB2687627 업데이트로 대체하고, 영향을 받는 모든 Microsoft Groove 2007, Microsoft Groove Server 2007, Microsoft Office SharePoint Server 2007 에디션과 함께 설치된 Microsoft XML Core Services 5.0용 KB2596679 업데이트를 KB2687497 업데이트로 대체했습니다. 자세한 내용은 MS12-043 공지를 참조하십시오.
-   V5.1(2012년 12월 12일): MS12-050에서 Microsoft Windows SharePoint Services 2.0에 대한 업데이트가 제공됨을 알리기 위해 공지 요약을 수정하였습니다. 이 업데이트는 Microsoft 다운로드 센터에서만 다운로드할 수 있습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
