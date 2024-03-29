---
TOCTitle: 'MS14-AUG'
Title: 2014년 8월 Microsoft 보안 공지 요약
ms:assetid: 'ms14-aug'
ms:contentKeyID: 62757463
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms14-aug(v=Security.10)'
---

2014년 8월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2014년 8월 12일 | 업데이트된 날짜: 2014년 12월 19일

**버전:** 2.2

이 공지 요약 목록에는 2014년 8월에 발표된 보안 공지가 포함되어 있습니다.

2014년 8월 보안 공지 발표와 함께 이 공지 요약이 2014년 8월 7일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2014년 8월 13일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. 월간 웹캐스트를 보고 추가 보안 공지 웹캐스트에 대한 링크를 확인하려면 [Microsoft 보안 공지 웹캐스트](http://technet.microsoft.com/security/dn756352)를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어**를 참조하십시오.

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2976627)<br />
<br />
</strong>이 보안 업데이트는 Internet Explorer의 공개된 취약점 1건과 비공개로 보고된 취약점 25건을 해결합니다. 가장 심각한 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507337">MS14-043</a></td>
<td style="border:1px solid black;"><strong>Windows Media Center의 취약점으로 인한 원격 코드 실행 문제점(2978742)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 취약점은 사용자가 Windows Media Center 리소스를 실행하는 특수하게 조작된 Microsoft Office 파일을 열 때 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402461">MS14-048</a></td>
<td style="border:1px solid black;"><strong>OneNote의 취약점으로 인한 원격 코드 실행 문제점(2977201)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft OneNote의 취약점을 해결합니다. 이 취약점으로 인해 영향을 받는 Microsoft OneNote 버전에서 특수하게 조작된 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></td>
<td style="border:1px solid black;"><strong>SQL Server의 취약점으로 인한 권한 상승 문제점(2984340)</strong><br />
<br />
이 보안 업데이트는 Microsoft SQL Server의 비공개적으로 보고된 취약점 2건(각각 SQL Server Master Data Services 및 SQL Server 관련 데이터베이스 관리 시스템의 취약점)을 해결합니다. 둘 중 더욱 심각한 SQL Server Master Data Services에 영향을 미치는 취약점은 사용자가 클라이언트측 스크립트를 Internet Explorer의 사용자 인스턴스에 주입하는 특수하게 조작된 웹사이트를 방문하는 경우 권한 상승을 허용할 수 있습니다. 어떠한 경우에도 공격자는 강제로 사용자가 공격자 제어 콘텐츠를 보도록 만들 수는 없습니다. 대신 공격자는 사용자가 공격자의 웹 사이트에 연결되는 전자 메일 메시지나 메신저 메시지에서 링크를 클릭하게 하거나 전자 메일을 통해 보낸 첨부 파일을 열도록 하는 등의 조치를 취하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;"><strong>커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2984615)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로<strong></strong>보고된 취약점 3건을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 시스템에 로그온하여 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396822">MS14-049</a></td>
<td style="border:1px solid black;"><strong>Windows Installer 서비스의 취약점으로 인한 권한 상승 문제점(2962490)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점은 공격자가 이전에 설치된 응용 프로그램을 복구하려고 하는 특수하게 조작된 응용 프로그램을 실행할 경우 권한 상승을 허용할 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402463">MS14-050</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server의 취약점으로 인한 권한 상승 문제점(2977202)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft SharePoint Server의 취약점 1건을 해결합니다. 이 취약점 악용에 성공한 인증된 공격자는 현재 SharePoint 사이트의 사용자 컨텍스트에서 임의의 JavaScript를 실행하기 위해 특수하게 조작된 앱을 사용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Server 소프트웨어</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507038">MS14-046</a></td>
<td style="border:1px solid black;"><strong>.NET Framework의 취약점으로 인한 보안 기능 우회(2984625)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft .NET Framework의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 웹 사이트를 방문할 경우 보안 기능 우회가 허용될 수 있습니다. 웹 검색을 통한 공격의 경우, 이 취약점 악용에 성공한 공격자는 다양한 취약점 클래스로부터 사용자를 보호해 주는 ASLR(Address Space Layout Randomization) 보안 기능을 우회할 수 있습니다. 보안 기능을 우회하는 것만으로는 임의의 코드 실행이 허용되지 않지만 공격자는 이 ASLR 우회 취약점을 다른 취약점 즉, ASLR 우회를 통해 임의의 코드를 실행할 수 있는 원격 코드 실행 취약점 등과 함께 사용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507336">MS14-047</a></td>
<td style="border:1px solid black;"><strong>LRPC의 취약점으로 인한 보안 기능 우회(2978668)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 공격자가 현재 취약점을 ASLR을 우회해 임의 코드를 실행하는 데 유리한 원격 코드 실행 취약점 같은 다른 취약점과 함께 사용하면 보안 기능을 우회할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
보안 기능 우회</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507337">MS14-043</a></td>
<td style="border:1px solid black;">CSyncBasePlayer 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4060">CVE-2014-4060</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></td>
<td style="border:1px solid black;">SQL Master Data Services XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1820">CVE-2014-1820</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></td>
<td style="border:1px solid black;">Microsoft SQL Server 스택 오버런 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4061">CVE-2014-4061</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;">Win32k 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0318">CVE-2014-0318</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;">글꼴 이중 페치 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1819">CVE-2014-1819</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></td>
<td style="border:1px solid black;">Windows 커널 풀 할당 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4064">CVE-2014-4064</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507038">MS14-046</a></td>
<td style="border:1px solid black;">.NET ASLR 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4062">CVE-2014-4062</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.<br />
<br />
Microsoft는 이 보안 공지를 처음에 게시했을 때 이 취약점이 고객을 공격하는 데 공개적으로 사용되었다는 정보를 확인하지 못했습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507336">MS14-047</a></td>
<td style="border:1px solid black;">LRPC ASLR 우회 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0316">CVE-2014-0316</a></td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">3 - 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 보안 기능 우회 취약점입니다.<br />
<br />
Microsoft는 이 보안 공지를 처음에 게시했을 때 이 취약점이 고객을 공격하는 데 공개적으로 사용되었다는 정보를 확인하지 못했습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402461">MS14-048</a></td>
<td style="border:1px solid black;">OneNote 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2815">CVE-2014-2815</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396822">MS14-049</a></td>
<td style="border:1px solid black;">Windows Installer 복구 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1814">CVE-2014-1814</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402463">MS14-050</a></td>
<td style="border:1px solid black;">SharePoint 페이지 콘텐츠 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2816">CVE-2014-2816</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2774">CVE-2014-2774</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2784">CVE-2014-2784</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2796">CVE-2014-2796</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2808">CVE-2014-2808</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2810">CVE-2014-2810</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2811">CVE-2014-2811</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2817">CVE-2014-2817</a></td>
<td style="border:1px solid black;">0 - 악용 검색됨</td>
<td style="border:1px solid black;">0 - 악용 검색됨</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 이 취약점을 악용하려는 제한적인 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2818">CVE-2014-2818</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2819">CVE-2014-2819</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2820">CVE-2014-2820</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2821">CVE-2014-2821</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2822">CVE-2014-2822</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2823">CVE-2014-2823</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2824">CVE-2014-2824</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2825">CVE-2014-2825</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2826">CVE-2014-2826</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2827">CVE-2014-2827</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4050">CVE-2014-4050</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4051">CVE-2014-4051</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4052">CVE-2014-4052</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4055">CVE-2014-4055</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4056">CVE-2014-4056</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4057">CVE-2014-4057</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4058">CVE-2014-4058</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4063">CVE-2014-4063</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4067">CVE-2014-4067</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6354">CVE-2014-4145</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6354">CVE-2014-6354</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">없음</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어  
----------------------
  
<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
**Windows 운영 체제 및 구성 요소**

<p> </p>
<table style="border:1px solid black;">
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
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

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
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(보통)  
Internet Explorer 7  
(2976627)  
(보통)  
Internet Explorer 8  
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2993651)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2918614)  
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
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(보통)  
Internet Explorer 7  
(2976627)  
(보통)  
Internet Explorer 8  
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2993651)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2918614)  
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
Internet Explorer 6  
(2976627)  
(보통)  
Internet Explorer 7  
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2993651)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2918614)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

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
**없음**

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
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(긴급)  
Internet Explorer 8  
(2976627)  
(긴급)  
Internet Explorer 9  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2993651)  
(중요)  
Windows Vista 서비스 팩 2  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2937608)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2943344)  
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
(2976627)  
(긴급)  
Internet Explorer 8  
(2976627)  
(긴급)  
Internet Explorer 9  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2993651)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2937608)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2943344)  
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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

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
**없음**

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
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(보통)  
Internet Explorer 8  
(2976627)  
(보통)  
Internet Explorer 9  
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2993651)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2937608)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2943344)  
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
Internet Explorer 7  
(2976627)  
(보통)  
Internet Explorer 8  
(2976627)  
(보통)  
Internet Explorer 9  
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2993651)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2937608)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2943344)  
(중요)

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
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2993651)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2937608)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2943344)  
(중요)

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
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

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
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(긴급)  
Internet Explorer 9  
(2976627)  
(긴급)  
Internet Explorer 10  
(2976627)  
(긴급)  
Internet Explorer 11  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(Starter 및 Home Basic 에디션을 제외한 모든 에디션)  
(2978742)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2993651)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(긴급)  
Internet Explorer 9  
(2976627)  
(긴급)  
Internet Explorer 10  
(2976627)  
(긴급)  
Internet Explorer 11  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(Starter 및 Home Basic 에디션을 제외한 모든 에디션)  
(2978742)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2993651)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

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
**없음**

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
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(보통)  
Internet Explorer 9  
(2976627)  
(보통)  
Internet Explorer 10  
(2976627)  
(보통)  
Internet Explorer 11  
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2993651)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2993651)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

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
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8 32비트 시스템에 설치된 Windows Media Center(Professional 에디션만)  
(2978742)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2993651)  
(중요)  
Windows 8(32비트 시스템용)  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(중요)  
Microsoft .NET Framework 3.5  
(2966827)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8 x64 기반 시스템에 설치된 Windows Media Center(Professional 에디션만)  
(2978742)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2993651)  
(중요)  
Windows 8(x64 기반 시스템용)  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(중요)  
Microsoft .NET Framework 3.5  
(2966827)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1 32비트 시스템에 설치된 Windows Media Center(Professional 에디션만)  
(2978742)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2993651)  
(중요)  
Windows 8.1(32비트 시스템용)  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(중요)  
Microsoft .NET Framework 3.5  
(2966828)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 기반 시스템에 설치된 Windows Media Center(Professional 에디션만)  
(2978742)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2993651)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(중요)  
Microsoft .NET Framework 3.5  
(2966828)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

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
**없음**

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
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2993651)  
(중요)  
Windows Server 2012  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(중요)  
Microsoft .NET Framework 3.5  
(2966827)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(보통)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2993651)  
(중요)  
Windows Server 2012 R2  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(중요)  
Microsoft .NET Framework 3.5  
(2966828)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

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
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(2993651)  
(중요)  
Windows RT  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2993651)  
(중요)  
Windows RT 8.1  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2978668)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](http://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://go.microsoft.com/fwlink/?linkid=507336)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

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
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2993651)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2918614)  
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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2993651)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2918614)  
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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2993651)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2978668)  
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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2993651)  
(중요)  
Windows Server 2012(Server Core 설치)  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(중요)  
Microsoft .NET Framework 3.5  
(2966827)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2978668)  
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
해당 사항 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2993651)  
(중요)  
Windows Server 2012 R2(Server Core 설치)  
(2976897)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2918614)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(중요)  
Microsoft .NET Framework 3.5  
(2966828)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2978668)  
(중요)

</td>
</tr>
</table>
 
**MS14-043 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

**Microsoft Office 소프트웨어**

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
**Microsoft Office 소프트웨어**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-048**](http://go.microsoft.com/fwlink/?linkid=402461)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft OneNote 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft OneNote 2007 서비스 팩 3  
(2596857)  
(중요)

</td>
</tr>
</table>
 
 

**Microsoft SQL Server**

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-044**](http://go.microsoft.com/fwlink/?linkid=507036)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(32비트 시스템용) 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(32비트 시스템용) 서비스 팩 3  
(GDR)  
(2977321)  
(중요)  
Microsoft SQL Server 2008(32비트 시스템용) 서비스 팩 3  
(QFE)  
(2977322)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(x64 기반 시스템용) 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(x64 기반 시스템용) 서비스 팩 3  
(GDR)  
(2977321)  
(중요)  
Microsoft SQL Server 2008(x64 기반 시스템용) 서비스 팩 3  
(QFE)  
(2977322)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 3  
(GDR)  
(2977321)  
(중요)  
Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 3  
(QFE)  
(2977322)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(32비트 시스템용) 서비스 팩 2  
(GDR)  
2977320)  
(중요)  
Microsoft SQL Server 2008 R2(32비트 시스템용) 서비스 팩 2  
(QFE)  
(2977319)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2(x64 기반 시스템용) 서비스 팩 2  
(GDR)  
(2977320)  
(중요)  
Microsoft SQL Server 2008 R2(x64 기반 시스템용) 서비스 팩 2  
(QFE)  
(2977319)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(GDR)  
(2977320)  
(중요)  
Microsoft SQL Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(QFE)  
(2977319)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012(32비트 시스템용) 서비스 팩 1  
(GDR)  
(2977326)  
(중요)  
Microsoft SQL Server 2012(32비트 시스템용) 서비스 팩 1  
(QFE)  
(2977325)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012(x64 기반 시스템용) 서비스 팩 1  
(GDR)  
(2977326)  
(중요)  
Microsoft SQL Server 2012(x64 기반 시스템용) 서비스 팩 1  
(QFE)  
(2977325)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2014(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014(x64 기반 시스템용)  
(GDR)  
(2977315)  
(중요)  
Microsoft SQL Server 2014(x64 기반 시스템용)  
(QFE)  
(2977316)  
(중요)

</td>
</tr>
</table>
 
 

**Microsoft Server 소프트웨어**

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-050**](http://go.microsoft.com/fwlink/?linkid=402463)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013  
(2880994)  
(중요)  
Microsoft SharePoint Foundation 2013  
(2880994)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1  
(2880994)  
(중요)  
Microsoft SharePoint Foundation 2013 서비스 팩 1  
(2880994)  
(중요)

</td>
</tr>
</table>
 
 

**기타 소프트웨어**

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Media Center TV Pack for Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://go.microsoft.com/fwlink/?linkid=507337)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Center TV Pack for Windows Vista(32비트 에디션)

</td>
<td style="border:1px solid black;">
Windows Media Center TV Pack for Windows Vista(32비트 에디션)  
(2978742)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Center TV Pack for Windows Vista(64비트 에디션)

</td>
<td style="border:1px solid black;">
Windows Media Center TV Pack for Windows Vista(64비트 에디션)  
(2978742)  
(긴급)

</td>
</tr>
</table>
 
**MS14-043 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 섹션의 다른 표를 확인하십시오.

 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 존재합니다.

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 구성 오류를 검색할 수 있습니다.

WSUS(Windows Server Update Services), SMS(Systems Management Server), System Center Configuration Manager는 관리자가 보안 업데이트를 배포하는 데 도움이 됩니다.

ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](http://technet.microsoft.com/security/cc297183)를 참조하십시오. 

감사의 말
---------

<span id="sectionToggle4"></span>
고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

**MS14-043**

-   CSyncBasePlayer 해제 후 사용 취약점(CVE-2014-4060)을 [HP](http://www.hpenterprisesecurity.com/products)(영어)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영어)와 협력해서 보고해 주신 Alisa Esage(@alisaesage)

**MS14-045**

-   글꼴 이중 페치 취약점(CVE-2014-1819)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Wang Yu
-   Windows 커널 풀 할당 취약점(CVE-2014-4064)을 보고해 주신 Ilja Van Sprundel

**MS14-047**

-   LRPC ASLR 우회 취약점(CVE-2014-0316)을 보고해 주신 [Alex Ionescu](http://www.alex-ionescu.com/)(영어)

**MS14-048**

-   OneNote 원격 코드 실행 취약점(CVE-2014-2815)을 보고해 주신 Beyond Security의 [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html)(영어) 프로그램과 협력한 Eduardo Prado

**MS14-049**

-   Windows Installer 복구 취약점(CVE-2012-4784)을 보고해 주신 [Entisys](http://www.entisys.com/)(영어)의 Denis Gundarev
-   이 공지에 포함된 심층 보안 변경 사항에 대해 협력해 주신 [Stepfan Kanthak](http://home.arcor.de/skanthak/safer.html)(영어)

**MS14-051**

-   Internet Explorer 메모리 손상 취약점(CVE-2014-2774)을 보고해 주신 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2784)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Yujie Wen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2796)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2808)을 보고해 주신 [NSFOCUS Security Team](http://www.nsfocus.com/)(영문)의 [Chen Zhang(demi6od)](https://github.com/demi6od)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2810)을 보고해 주신 [NSFOCUS Security Team(영문)](http://www.nsfocus.com/)의 [Chen Zhang(demi6od)](https://github.com/demi6od)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2811)을 [VeriSign iDefense Labs](http://labs.idefense.com/)(영문)와 협력하여 보고해 주신 IronRock
-   Internet Explorer 권한 상승 취약점(CVE-2014-2817)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2818)을 보고해 주신 [HP(영문)](http://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri
-   Internet Explorer 권한 상승 취약점(CVE-2014-2819)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 [Team509](http://team509.com/)(영문)의 Zeguang Zhao 및 [KeenTeam](http://www.k33nteam.org/)(영문)의 Liang Chen(@K33nTeam)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2820)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Arthur Gerkis
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2821)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2822)을 보고해 주신 [Palo Alto Networks(영문)](http://www.paloaltonetworks.com/)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2823)을 보고해 주신 [NSFOCUS Security Team](http://www.nsfocus.com/)(영문)의 [Chen Zhang(demi6od)](https://github.com/demi6od)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2824)을 보고해 주신 [Qihoo 360(중문)](http://www.360.cn/)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2825)을 보고해 주신 [NSFOCUS Security Team](http://www.nsfocus.com/)(영문)의 [Chen Zhang(demi6od)](https://github.com/demi6od)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2826)을 보고해 주신 [NSFOCUS Security Team](http://www.nsfocus.com/)(영문)의 [Chen Zhang(demi6od)](https://github.com/demi6od)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-2827)을 보고해 주신 [HP(영문)](http://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)의 Simon Zuckerbraun
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4050)을 [HP(영문)](http://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Omair](http://krash.in/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4051)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Corelan](http://www.corelangcv.com/)(영문)의 Peter 'corelanc0d3r' Van Eeckhoutte
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4052)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4055)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4056)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Corelan(영문)](http://www.corelangcv.com/)의 Peter 'corelanc0d3r' Van Eeckhoutte
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4057)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative(영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 [Trend Micro](http://www.trendmicro.com/)(영문)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4058)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Sky
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4063)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4067)을 보고해 주신 [VulnHunt](http://www.vulnhunt.com/)(영문)의 Wei Wang
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4067)을 [HP의](http://www.hpenterprisesecurity.com/products)(영문) [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [lokihardt@ASRT](https://technet.microsoft.com/ko-KR/mailto:lokihardt@asrt)
-   Internet Explorer 메모리 손상 취약성(CVE-2014-4145)을 [HP](http://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Omair
-   Internet Explorer 메모리 손상 취약성(CVE-2014-6354)을 [HP](http://www.hpenterprisesecurity.com/products)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Omair

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

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft 업데이트](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows 업데이트를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617)

Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)

국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 개정 내역

-   V1.0(2014년 8월 13일): 공지 요약이 게시되었습니다.
-   V2.0(2014년 8월 28일): MS14-045에서 지원 대상인 모든 Microsoft Windows 릴리스에 대해 2982791 업데이트가 2993651 업데이트로 대체되었음을 알리기 위해 공지가 다시 릴리스되었습니다. 자세한 내용은 보안 공지를 참조하십시오.
-   V2.2(2014년 12월 19일): MS14-051에는 CVE-2014-6354의 악용 가능성 인덱스에 대한 악용 가능성 평가가 추가되었습니다. 이 변경 사항은 정보 제공용입니다.

*2014년 9월 24일 11:23Z-07:00에 페이지가 생성되었습니다.*
