---
TOCTitle: 'MS13-JUL'
Title: 2013 년 7 월 Microsoft 보안 공지 요약
ms:assetid: 'ms13-jul'
ms:contentKeyID: 61230762
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms13-jul(v=Security.10)'
---

2013 년 7 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2013년 7월 10일 수요일 | 업데이트된 날짜: 2013년 8월 28일 수요일

**버전:** 3.0

이 공지 요약 목록에는 2013년 7월에 발표된 보안 공지가 포함되어 있습니다.

2013년 7월 보안 공지 발표와 함께 이 공지 요약이 2013년 7월 4일 목요일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)(영문)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2013년 7월 10일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [7월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032556406&culture=en-us)(영문). 이 날짜 이후 이 웹캐스트는 [주문형](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us)으로 제공됩니다.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. 기타 정보 섹션을 참조하십시오.

### 공지 정보

#### 요약

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 영향을 받는 소프트웨어를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">.NET Framework 및 Silverlight의 취약점으로 인한 원격 코드 실행 문제점(2861561) <br />
<br />
이 보안 업데이트는 Microsoft .NET Framework 및 Microsoft Silverlight의 비공개적으로 보고된 취약점 5건과 공개된 취약점 2건을 해결합니다. 이 중 가장 심각한 취약점으로 인해 신뢰할 수 있는 응용 프로그램에서 특정 패턴의 코드를 사용할 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Windows 커널 모드 드라이버의 취약점으로 인한 원격 코드 실행 문제점(2850851)<br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 2건과 비공개적으로 보고된 6건의 취약점을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 TrueType 글꼴 파일이 포함된 공유 콘텐츠를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;">GDI+ 의 취약점으로 인한 원격 코드 실행 문제점(2848295)<br />
<br />
이 보안 업데이트는 Microsoft Windows, Microsoft Office, Microsoft Lync 및 Microsoft Visual Studio에서 비공개적으로 보고된 취약점을 해결합니다. 취약점으로 인해 사용자가 TrueType 글꼴 파일이 포함된 공유 콘텐츠를 볼 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office,<br />
Microsoft Visual Studio,<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2846071)  <br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 17건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 가장 위험한 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;">Microsoft DirectShow의 취약점으로 인한 원격 코드 실행 문제점(2845187)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 이미지 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;">Windows Media Format Runtime의 취약점으로 인한 원격 코드 실행 문제점(2847883)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 미디어 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;">Windows Defender의 취약점으로 인한 권한 상승 문제점(2847927)<br />
<br />
이 보안 업데이트는 Windows 7용 Windows Defender 및 Windows Server 2008 R2에 설치된 Windows Defender에서 비공개적으로 보고된 취약점을 해결합니다. Windows Defender에서 사용된 경로 이름 때문에 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 임의 코드를 실행하여 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자는 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 공격자가 이 취약점을 악용하기 위해서는 유효한 로그온 자격 증명이 필요합니다. 익명 사용자는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft 보안 소프트웨어</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------

다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은[Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.

<p> </p>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">TrueType 글꼴 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">배열 액세스 위반 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3131">CVE-2013-3131</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">대리자 리플렉션 우회 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3132">CVE-2013-3132</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">익명 메서드 주입 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3133">CVE-2013-3133</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">배열 할당 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3134">CVE-2013-3134</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">대리자 직렬화 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3171">CVE-2013-3171</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Null 포인터 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3178">CVE-2013-3178</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 메모리 할당 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1300">CVE-2013-1300</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 역참조 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1340">CVE-2013-1340</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 최신 소프트웨어 버전에 대한 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1345">CVE-2013-1345</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 최신 소프트웨어 버전에 대한 서비스 거부 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">TrueType 글꼴 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3167">CVE-2013-3167</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 권한 상승을 허용할 수 있는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 버퍼 덮어쓰기 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3173">CVE-2013-3173</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 읽기 AV 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3660">CVE-2013-3660</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다.<br />
<br />
Microsoft는 이 취약점을 권한 상승 취약점으로 악용하려는 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;">TrueType 글꼴 구문 분석 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3115">CVE-2013-3115</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3143">CVE-2013-3143</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3144">CVE-2013-3144</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3145">CVE-2013-3145</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3146">CVE-2013-3146</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3147">CVE-2013-3147</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3148">CVE-2013-3148</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3149">CVE-2013-3149</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3150">CVE-2013-3150</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3151">CVE-2013-3151</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3152">CVE-2013-3152</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3153">CVE-2013-3153</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3161">CVE-2013-3161</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3162">CVE-2013-3162</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3163">CVE-2013-3163</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 Internet Explorer 8을 통해 이 취약점을 악용하려는 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3164">CVE-2013-3164</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Shift JIS 문자 인코딩 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3166">CVE-2013-3166</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;">DirectShow 임의 메모리 덮어쓰기 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3174">CVE-2013-3174</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;">WMV 비디오 디코더 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3127">CVE-2013-3127</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;">Microsoft Windows 7 Defender 부적절한 경로 이름 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3154">CVE-2013-3154</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어  
----------------------

다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
이 표를 어떻게 사용합니까?
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.
  
참고 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0 서비스 팩 3  
(Media Center Edition 2005 서비스 팩 3 및 Tablet PC Edition 2005 서비스 팩 3만 해당)  
(2833951)  
(중요)  
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833941)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833940)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2844285)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2832411)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2840629)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)
</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(Windows GDI+)  
(2834886)  
(긴급)  
Windows XP 서비스 팩 3  
(Windows XP Tablet PC Edition 2005만 해당)  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(긴급)  
Internet Explorer 7   
(2846071)  
(긴급)  
Internet Explorer 8   
(2846071)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Format Runtime 11<sup>[1]</sup>
(wmvdecod.dll)  
(Media Center Edition만 해당)  
(2834904)  
(긴급)  
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(Media Center Edition만 해당)  
(2834905)  
(긴급)  
Windows Media Format Runtime 9  
(wmvdmod.dll)  
(2803821)  
(긴급)  
Windows Media Format Runtime 9.5<sup>[2]</sup>
(wmvdmod.dll)  
(2834902)  
(긴급)  
Windows Media Format Runtime 9.5<sup>[3]</sup>
(wmvdmod.dll)  
(2834903)  
(긴급)  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
(긴급)  
wmv9vcm.dll(코덱)  
(2845142)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833941)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833940)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2(2844285)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2832411)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>(2840628)  
(중요)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(Windows GDI+)  
(2834886)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(긴급)  
Internet Explorer 7   
(2846071)  
(긴급)  
Internet Explorer 8   
(2846071)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(긴급)  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(긴급)  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
(긴급)  
wmv9vcm.dll(코덱)  
(2845142)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833949)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833940)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2844285)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2832411)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2840629)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(Windows GDI+)  
(2834886)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(보통)  
Internet Explorer 7  
(2846071)  
(보통)  
Internet Explorer 8  
(2846071)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(긴급)  
wmv9vcm.dll(코덱)  
(2845142)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833941)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833940)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2844285)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2832411)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2840629)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(Windows GDI+)  
(2834886)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(보통)  
Internet Explorer 7  
(2846071)  
(보통)  
Internet Explorer 8  
(2846071)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(긴급)  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(긴급)  
Windows Media Format Runtime 11  
(wmvdmod.dll)  
(2834904)  
(긴급)  
wmv9vcm.dll(코덱)  
(2845142)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833941)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833940)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2844285)  
(중요)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2840629)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(Windows GDI+)  
(2834886)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(보통)  
Internet Explorer 7  
(2846071)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833941)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833947)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2844287)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2832412)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2840629)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)  
Microsoft .NET Framework 4.5  
(2835622)  
(긴급)  
Microsoft .NET Framework 4.5  
(2833957)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840642)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(DirectWrite)  
(2835361)  
(긴급)  
Windows Vista 서비스 팩 2  
(Windows GDI+)  
(2834886)  
(긴급)  
Windows Vista 서비스 팩 2  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(긴급)  
Internet Explorer 8  
(2846071)  
(긴급)  
Internet Explorer 9   
(2846071)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
(긴급)  
wmv9vcm.dll(코덱)  
(2845142)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833941)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833947)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2844287)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2832412)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2840629)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)  
Microsoft .NET Framework 4.5  
(2835622)  
(긴급)  
Microsoft .NET Framework 4.5  
(2833957)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840642)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(DirectWrite)  
(2835361)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(Windows GDI+)  
(2834886)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(긴급)  
Internet Explorer 8  
(2846071)  
(긴급)  
Internet Explorer 9   
(2846071)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
(긴급)  
wmv9vcm.dll(코덱)  
(2845142)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833941)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833947)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2844287)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2832412)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2840629)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)  
Microsoft .NET Framework 4.5  
(2835622)  
(긴급)  
Microsoft .NET Framework 4.5  
(2833957)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840642)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(DirectWrite)  
(2835361)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Windows GDI+)  
(2834886)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(보통)  
Internet Explorer 8  
(2846071)  
(보통)  
Internet Explorer 9   
(2846071)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(긴급)  
wmv9vcm.dll(코덱) \[5\]  
(2845142)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833941)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833947)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2844287)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2832412)  
(긴급)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2840629)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)  
Microsoft .NET Framework 4.5  
(2835622)  
(긴급)  
Microsoft .NET Framework 4.5  
(2833957)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840642)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(DirectWrite)  
(2835361)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Windows GDI+)  
(2834886)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(보통)  
Internet Explorer 8  
(2846071)  
(보통)  
Internet Explorer 9   
(2846071)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(긴급)  
wmv9vcm.dll(코덱) \[5\]  
(2845142)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2833941)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2833947)  
(긴급)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2844287)  
(중요)  
Microsoft .NET Framework 3.5 서비스 팩 1  
(2840629)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(Windows GDI+)  
(2834886)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(보통)
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
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)  
Microsoft .NET Framework 4.5  
(2833957)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840642)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(DirectWrite)  
(2835361)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(Windows GDI+)  
(2834886)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(긴급)  
Internet Explorer 9   
(2846071)  
(긴급)  
Internet Explorer 10   
(2846071)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)  
Microsoft .NET Framework 4.5  
(2833957)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840642)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(DirectWrite)  
(2835361)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(Windows GDI+)  
(2834886)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(긴급)  
Internet Explorer 9   
(2846071)  
(긴급)  
Internet Explorer 10   
(2846071)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)  
Microsoft .NET Framework 4.5  
(2833957)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840642)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(DirectWrite)  
(2835361)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Windows GDI+)  
(2834886)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(보통)  
Internet Explorer 9   
(2846071)  
(보통)  
Internet Explorer 10   
(2846071)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(DirectWrite)  
(2835361)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(Windows GDI+)  
(2834886)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(보통)
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
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(긴급)  
Microsoft .NET Framework 3.5  
(2833959)  
(긴급)  
Microsoft .NET Framework 3.5  
(2840633)  
(중요)  
Microsoft .NET Framework 3.5  
(2844289)  
(중요)  
Microsoft .NET Framework 4.5  
(2833958)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840632)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(DirectWrite)  
(2835361)  
(긴급)  
Windows 8(32비트 시스템용)  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(긴급)  
Microsoft .NET Framework 3.5  
(2833959)  
(긴급)  
Microsoft .NET Framework 3.5  
(2840633)  
(중요)  
Microsoft .NET Framework 3.5  
(2844289)  
(중요)  
Microsoft .NET Framework 4.5  
(2833958)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840632)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)  
(DirectWrite)  
(2835361)  
(긴급)  
Windows 8(64비트 시스템용)  
(Journal)  
(2835364)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(64비트 시스템용)  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
[보통](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(긴급)  
Microsoft .NET Framework 3.5  
(2833959)  
(긴급)  
Microsoft .NET Framework 3.5  
(2840633)  
(중요)  
Microsoft .NET Framework 3.5  
(2844289)  
(중요)  
Microsoft .NET Framework 4.5  
(2833958)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840632)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(DirectWrite)  
(2835361)  
(긴급)  
Windows Server 2012  
(Journal)  
(2835364)(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845187)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
없음
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2833958)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840632)  
(중요)
</td>
<td style="border:1px solid black;">
Windows RT  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows RT  
(DirectWrite)  
(2835361)  
(긴급)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Server Core 설치 옵션
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](http://go.microsoft.com/fwlink/?linkid=301528)
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(Windows GDI+)  
(2834886)  
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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(Windows GDI+)  
(2834886)  
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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(긴급)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(중요)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(긴급)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(중요)  
Microsoft .NET Framework 4.5  
(2833957)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840642)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(Windows GDI+)  
(2834886)  
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
Windows Server 2012(Server Core 설치)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(긴급)  
Microsoft .NET Framework 3.5  
(2833959)  
(긴급)  
Microsoft .NET Framework 3.5  
(2840633)  
(중요)  
Microsoft .NET Framework 3.5  
(2844289)  
(중요)  
Microsoft .NET Framework 4.5  
(2833958)  
(긴급)  
Microsoft .NET Framework 4.5  
(2840632)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2850851)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(DirectWrite)  
(2835361)  
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
</table>
 
MS13-052 참고 사항

<sup>[1]</sup>.NET Framework 4 및 .NET Framework 4 Client Profile이 영향을 받습니다. .NET Framework 버전 4 재배포 가능 패키지는 .NET Framework 4 및 .NET Framework 4 Client Profile의 두 가지 프로필로 제공됩니다. .NET Framework 4 Client Profile은 .NET Framework 4의 하위 집합입니다. 이 업데이트로 해결된 취약점은 .NET Framework 4 및 .NET Framework 4 Client Profile에 모두 영향을 줍니다. 자세한 내용은 MSDN 문서, [.NET Framework 설치](http://msdn.microsoft.com/library/5a4x27ek)를 참조하십시오.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

MS13-053 및 MS13-055 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

MS13-054 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

MS13-057 참고 사항

<sup>[1]</sup>이 업데이트는 Windows Media Format Runtime 11 또는 Windows Media Player 11로 업그레이드된 시스템에만 제공됩니다.
<sup>[2]</sup>이 업데이트는 Windows Media Format Runtime 9.5 NL을 실행하는 시스템에만 제공됩니다.
<sup>[3]</sup>이 업데이트는 Windows Media Format Runtime 9.5 L을 실행하는 시스템에만 제공됩니다.
\[4\]이 업데이트는 선택적 데스크톱 경험 기능이 활성화된 경우에만 제공됩니다.
\[5\]이 업데이트는 선택적 데스크톱 경험 기능이 활성화되어 있고 wmv9vcm.dll 코덱이 있는 경우에만 제공됩니다. 자세한 정보를 보려면 공지를 확인하십시오.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3  
(2817480)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2687309)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(2687276)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(2687276)  
(중요)
</td>
</tr>
</table>
 
MS13-054 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 개발자 도구 및 소프트웨어

<p> </p>
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
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Visual Studio .NET 2003 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 서비스 팩 1<sup>[1]</sup>
(2856545)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Silverlight
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
[MS13-052](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
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
</td>
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5  
(2847559)  
(긴급)  
Mac에 설치된 Microsoft Silverlight 5 Developer 런타임  
(2847559)  
(긴급)  
Microsoft Windows(32비트 에디션) 클라이언트에 설치된 Microsoft Silverlight 5  
(2847559)  
(긴급)  
Microsoft Windows(x64 기반 에디션) 클라이언트에 설치된 Microsoft Silverlight 5  
(2847559)  
(긴급)  
지원 대상인 모든 Microsoft Windows 클라이언트 릴리스에 설치된 Microsoft Silverlight 5 Developer 런타임  
(2847559)  
(긴급)  
Microsoft Windows(32비트 에디션) 서버에 설치된 Microsoft Silverlight 5  
(2847559)  
(긴급)  
Microsoft Windows(x64 기반 에디션) 서버에 설치된 Microsoft Silverlight 5  
(2847559)  
(긴급)  
지원 대상인 모든 Microsoft Windows 서버 릴리스에 설치된 Microsoft Silverlight 5 Developer 런타임  
(2847559)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
MS13-052 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

MS13-054 참고 사항

<sup>[1]</sup>이 업데이트는 Microsoft 다운로드 센터에서만 다운로드할 수 있습니다

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 통신 플랫폼 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Lync
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-054](http://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Lync 2010(32비트)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)  
(2843160)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)  
(2843160)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(사용자 수준 설치)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(사용자 수준 설치)  
(2843162)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)  
(2843163)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013(32비트)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013(32비트)  
(2817465)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(32비트)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(32비트)  
(2817465)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013(64비트)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013(64비트)  
(2817465)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(64비트)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013(64비트)  
(2817465)  
(긴급)
</td>
</tr>
</table>
 
MS13-054 참고 사항

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

#### Microsoft 보안 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
스파이웨어 방지 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-058](http://go.microsoft.com/fwlink/?linkid=308992)
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
Windows 7용 Windows Defender(x86)
</td>
<td style="border:1px solid black;">
Windows 7용 Windows Defender(x86)   
(2847927)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7용 Windows Defender(x64)
</td>
<td style="border:1px solid black;">
Windows 7용 Windows Defender(x64)   
(2847927)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64)에 설치된 Windows Defender
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64)에 설치된 Windows Defender   
(2847927)  
(중요)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------

보안 센터

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security TechCenter](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [Microsoft 안전 및 보안 센터](http://go.microsoft.com/fwlink/?linkid=85102)를 방문하거나 "보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

Microsoft Office for Mac의 경우 Microsoft AutoUpdate for Mac을 통해 Microsoft 소프트웨어를 최신으로 유지할 수 있습니다. Microsoft AutoUpdate for Mac 사용에 대한 자세한 내용은 [자동으로 소프트웨어 업데이트 확인](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)(영문)을 참조하십시오.

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

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)(영문)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936)(영문)를 방문하십시오.

참고 SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포](http://go.microsoft.com/fwlink/?linkid=33341)(영문)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)(영문)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (영문)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet.microsoft.com/library/cc749197) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 버전에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 발표에서 사용할 수 없습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199)
-   : 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/wsus/bb456965)
-   . Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

업데이트 관리 전략

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)(영문)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

기타 보안 관련 업데이트 받기

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

MS13-052

-   TrueType 글꼴 분석 취약점(CVE-2013-3129)을 보고해 주신 [F-13 Laboratory](http://www.f13-labs.net/)(영문)의 Ling Chuan Lee 및 Lee Yee Chan
-   배열 액세스 위반 취약점(CVE-2013-3131)을 보고해 주신 Alon Fliess
-   대리자 리플렉션 우회 취약점(CVE-2013-3132)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw
-   익명 메서드 주입 취약점(CVE-2013-3133)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw
-   대리자 직렬화 취약점(CVE-2013-3171)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw
-   Null 포인터 취약점(CVE-2013-3178)을 보고해 주신 Vitaliy Toropov

MS13-053

-   Win32k 메모리 할당 취약점(CVE-2013-1300)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 MWR Labs의 Jon Butler 및 Nils
-   Win32k 역참조 취약점(CVE-2013-1340)을 보고해 주신 [Dr.Web](http://drweb.com/)(영문)의 Alexander Chizhov
-   Win32k 창 처리 취약점(CVE-2013-1345)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   TrueType 글꼴 분석 취약점(CVE-2013-3129)을 보고해 주신 [F13 Laboratory](http://www.f13-labs.net/)(영문)의 Ling Chuan Lee 및 Lee Yee Chan
-   Win32k 정보 유출 취약점(CVE-2013-3167)을 보고해 주신 [Tencent PC Manager](http://guanjia.qq.com)(중문)의 Yinliang
-   Win32k 버퍼 오버플로 취약점(CVE-2013-3172)을 보고해 주신 [Google Inc](http://www.google.com/)의 [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)(영문)
-   Win32k 버퍼 덮어쓰기 취약점(CVE-2013-3173)을 보고해 주신 [Qihoo 360 Security Center](http://www.360.cn/)(중문)의 Wen Yujie 및 Guo Pengfei

MS13-054

-   TrueType 글꼴 분석 취약점(CVE-2013-3129)을 보고해 주신 [F13 Laboratory](http://www.f13-labs.net/)(영문)의 Ling Chuan Lee 및 Lee Yee Chan

MS13-055

-   Internet Explorer 메모리 손상 취약점(CVE-2013-3115)을 보고해 주신 [Google Security Team](http://www.google.com/)의 Ivan Fratric 및 Ben Hawkes
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3143)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 SkyLined
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3144)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3145)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Toan Pham Van
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3146)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Toan Pham Van
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3147)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com)
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3148)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Bluesea
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3149)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Bluesea
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3150)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Omair](http://krash.in/)(영문)
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3151)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Toan Pham Van
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3152)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3153)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 e6af8de8b1d4b2b6d5ba2610cbf9cd38
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3161)을 보고해 주신 [Google Security Team](http://www.google.com/)의 Ivan Fratric 및 Ben Hawkes
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3162)을 보고해 주신 [Google Security Team](http://www.google.com/)의 Ivan Fratric 및 Ben Hawkes
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3163)을 [VeriSign iDefense Labs](http://labs.idefense.com)(영문)와 협력하여 보고해 주신 Jose Antonio Vazquez Gonzalez
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3164)을 보고해 주신 [Security-Assessment.com](http://www.security-assessment.com/)(영문)의 Scott Bell
-   Shift JIS 문자 인코딩 취약점(CVE-2013-3166)을 보고해 주신 Masato Kinugawa
-   이 공지(CVE-2013-4015)에 포함된 심층 방어 변경 작업에 Microsoft와 협력해 주신 IBM X-Force의 Mark Yason

MS13-056

-   DirectShow 임의 메모리 덮어쓰기 취약점(CVE-2013-3174)을 보고해 주신 Andrés Gómez Ramírez

MS13-057

-   [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 WMV 비디오 디코더 원격 코드 실행 취약점(CVE-2013-3127)을 보고해 주신 익명 연구자

MS13-058

-   Microsoft Windows 7 Defender 부적절한 경로 이름 취약점(CVE-2013-3154)을 보고해 주신 [Reserve Bank of Australia](http://www.rba.gov.au/)(영문)의 Alton Blom

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2013년 7월 10일): 공지 요약이 게시되었습니다.
-   V1.1(2013년 7월 10일): MS13-055에서 CVE-2013-3163의 악용 가능성 인덱스에 대한 악용 가능성 평가가 개정되었습니다. Microsoft는 Internet Explorer 8을 통해 이 취약점을 악용하려는 일정한 공격에 대한 보고를 받았습니다. 이 변경 사항은 정보에만 해당됩니다.
-   V2.0(2013년 8월 14일): MS13-052에서 2840628, 2840632, 2840642, 2844285, 2844286, 2844287 및 2844289 업데이트를 다시 릴리스하기 위해 공지가 개정되었습니다. MS13-057에서 Windows 7 및 Windows 2008 R2에 대한 2803821 업데이트를 다시 릴리스하기 위해 공지가 개정되었습니다. 고객은 시스템에 적용되는 다시 릴리스된 업데이트를 설치해야 합니다. 자세한 내용은 각각의 공지를 참조하십시오.
-   V3.0(2013년 8월 28일): MS13-057에서 Windows XP, Windows Server 2003, Windows Vista, Windows Server 2008에 대한 보안 업데이트 2803821, Windows XP 및 Windows Server 2003에 대한 보안 업데이트 2834902, Windows XP에 대한 보안 업데이트 2834903, Windows XP 및 Windows Server 2003에 대한 보안 업데이트 2834904, Windows XP에 대한 2834905를 다시 릴리스하기 위해 공지가 개정되었습니다. Windows XP, Windows Server 2003, Windows Vista, 및 Windows Server 2008 사용자는 시스템에 적용되는 다시 릴리스된 업데이트를 설치해야 합니다. 자세한 내용은 보안 공지를 참조하십시오.

*Built at 2014-04-18T12:27:44Z-07:00*
