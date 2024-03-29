---
TOCTitle: 'MS14-SEP'
Title: 2014년 9월 Microsoft 보안 공지 요약
ms:assetid: 'ms14-sep'
ms:contentKeyID: 62841307
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms14-sep(v=Security.10)'
---

2014년 9월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2014년 9월 10일

**버전:** 1.0

이 공지 요약 목록에는 2014년 9월에 발표된 보안 공지가 포함되어 있습니다.

2014년 9월 보안 공지 발표와 함께 이 공지 요약이 2014년 9월 4일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2014년 9월 10일 오전 11시(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. 월간 웹캐스트를 보고 추가 보안 공지 웹캐스트에 대한 링크를 확인하려면 [Microsoft 보안 공지 웹캐스트](http://technet.microsoft.com/security/dn756352)를 참조하십시오.

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
<th style="border:1px solid black;" >공지 제목 및 요약</th>
<th style="border:1px solid black;" >최대 심각도 및 취약점 영향</th>
<th style="border:1px solid black;" >다시 시작 요구 사항</th>
<th style="border:1px solid black;" >영향을 받는 소프트웨어</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(2977629)<br />
<br />
</strong>이 보안 업데이트는 Internet Explorer의 공개된 취약점 1건과 비공개로 보고된 취약점 36건을 해결합니다. 가장 심각한 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507670">MS14-053</a></td>
<td style="border:1px solid black;"><strong>.NET Framework의 취약점으로 인한 서비스 거부 문제점(2990931)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft .NET Framework의 취약점 한 가지를 해결합니다. 이 취약점으로 인해 공격자가 소수의 특수하게 조작된 요청을 영향을 받는 .NET 기반 웹 사이트로 보낼 경우 서비스 거부가 발생할 수 있습니다. 지원되는 Microsoft Windows 에디션에 Microsoft .NET Framework가 설치된 경우 ASP.NET는 기본적으로 설치되지 않습니다. 이 취약점의 영향을 받으려면 고객은 수동으로 설치하고 이를 IIS에 등록하여 ASP.NET을 활성화해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요할 수 있음</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507672">MS14-054</a></td>
<td style="border:1px solid black;"><strong>Windows 작업 스케줄러의 취약점으로 인한 권한 상승 문제점(2988948)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 영향을 받는 시스템에 로그온한 후 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;"><strong>Microsoft Lync Server의 취약점으로 인한 서비스 거부 문제점(2990928)</strong><br />
<br />
이 보안 업데이트는 Microsoft Lync Server에서 발견되어 비공개적으로 보고된 취약점 3건을 해결합니다. 이 중 가장 심각한 취약점으로 인해 공격자가 특수하게 조작된 요청을 Lync Server에 보내는 경우 서비스 거부 문제점이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">Microsoft Lync Server</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 리소스 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-7331">CVE-2013-7331</a></td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이 취약점은 공개되었습니다. Microsoft는 이 취약점을 악용하려는 제한적인 활성 공격에 대한 보고를 받았습니다.<br />
이는 정보 유출 취약점입니다. 공격자는 로컬 드라이브에서 파일의 존재 여부를 추측할 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2799">CVE-2014-2799</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4059">CVE-2014-4059</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4065">CVE-2014-4065</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4079">CVE-2014-4079</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4080">CVE-2014-4080</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4081">CVE-2014-4081</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4082">CVE-2014-4082</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4083">CVE-2014-4083</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4084">CVE-2014-4084</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4085">CVE-2014-4085</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4086">CVE-2014-4086</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4087">CVE-2014-4087</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4088">CVE-2014-4088</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4089">CVE-2014-4089</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4090">CVE-2014-4090</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4091">CVE-2014-4091</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4092">CVE-2014-4092</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4093">CVE-2014-4093</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4094">CVE-2014-4094</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4095">CVE-2014-4095</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4096">CVE-2014-4096</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4097">CVE-2014-4097</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4098">CVE-2014-4098</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4099">CVE-2014-4099</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 메모리 손상 취약점은 서비스 거부를 유발할 수 있습니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4100">CVE-2014-4100</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4101">CVE-2014-4101</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4102">CVE-2014-4102</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4103">CVE-2014-4103</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4104">CVE-2014-4104</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4105">CVE-2014-4105</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4106">CVE-2014-4106</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4107">CVE-2014-4107</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4108">CVE-2014-4108</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4109">CVE-2014-4109</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4110">CVE-2014-4110</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4111">CVE-2014-4111</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507670">MS14-053</a></td>
<td style="border:1px solid black;">.NET Framework 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4072">CVE-2014-4072</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507672">MS14-054</a></td>
<td style="border:1px solid black;">작업 스케줄러 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4074">CVE-2014-4074</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;">Lync 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4068">CVE-2014-4068</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;">Lync XSS 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4070">CVE-2014-4070</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;">Lync 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4071">CVE-2014-4071</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
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
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2977629)  
(보통)  
Internet Explorer 7  
(2977629)  
(보통)  
Internet Explorer 8  
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 서비스 팩 1  
(2972207)  
(중요)  
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972214)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2973115)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)

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
(2977629)  
(보통)  
Internet Explorer 7  
(2977629)  
(보통)  
Internet Explorer 8  
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972214)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2973115)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
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
Internet Explorer 6  
(2977629)  
(보통)  
Internet Explorer 7  
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2972214)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(긴급)  
Internet Explorer 8  
(2977629)  
(긴급)  
Internet Explorer 9  
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2974268)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2974269)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
(긴급)  
Internet Explorer 8  
(2977629)  
(긴급)  
Internet Explorer 9  
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2974268)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2974269)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(보통)  
Internet Explorer 8  
(2977629)  
(보통)  
Internet Explorer 9  
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2974268)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2974269)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
(보통)  
Internet Explorer 8  
(2977629)  
(보통)  
Internet Explorer 9  
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2974268)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2974269)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 서비스 팩 2  
(2974268)  
(중요)  
Microsoft .NET Framework 3.0 서비스 팩 2  
(2974269)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
(긴급)  
Internet Explorer 9  
(2977629)  
(긴급)  
Internet Explorer 10  
(2977629)  
(긴급)  
Internet Explorer 11  
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
(긴급)  
Internet Explorer 9  
(2977629)  
(긴급)  
Internet Explorer 10  
(2977629)  
(긴급)  
Internet Explorer 11  
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
(보통)  
Internet Explorer 9  
(2977629)  
(보통)  
Internet Explorer 10  
(2977629)  
(보통)  
Internet Explorer 11  
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(중요)

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
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 사항 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(중요)  
Microsoft .NET Framework 3.5  
(2973113)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2988948)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(중요)  
Microsoft .NET Framework 3.5  
(2973113)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2988948)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(중요)  
Microsoft .NET Framework 3.5  
(2973114)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2988948)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(중요)  
Microsoft .NET Framework 3.5  
(2973114)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2988948)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(중요)  
Microsoft .NET Framework 3.5  
(2973113)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2988948)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(중요)  
Microsoft .NET Framework 3.5  
(2973114)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2988948)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(2988948)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2988948)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
Microsoft .NET Framework 3.5.1  
(2972211)  
(중요)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(중요)  
Microsoft .NET Framework 4  
(2972215)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(중요)

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
Microsoft .NET Framework 3.5  
(2972212)  
(중요)  
Microsoft .NET Framework 3.5  
(2973113)  
(중요)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2988948)  
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
Microsoft .NET Framework 3.5  
(2972213)  
(중요)  
Microsoft .NET Framework 3.5  
(2973114)  
(중요)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(2988948)  
(중요)

</td>
</tr>
</table>
 
 

**Microsoft 통신 플랫폼 및 소프트웨어**

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="2">
**Microsoft Lync Server**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**

</td>
<td style="border:1px solid black;">
[**MS14-055**](http://go.microsoft.com/fwlink/?linkid=507669)

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
Microsoft Lync Server 2010

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2010  
(서버)  
(2982385)  
(심각도 없음) <sup>[1]</sup>
Microsoft Lync Server 2010  
(응답 그룹 서비스)  
(2982388)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(서버)  
(2986072)  
(중요)  
Microsoft Lync Server 2013  
(응답 그룹 서비스)  
(2982389)  
(중요)  
Microsoft Lync Server 2013  
(핵심 구성 요소)  
(2992965)  
(중요)  
Microsoft Lync Server 2013  
(Web Components Server)  
(2982390)  
(중요)

</td>
</tr>
</table>
 
**MS14-055 참고 사항**

<sup>[1]</sup>지정된 소프트웨어에 대한 이 업데이트에는 심각도가 적용되지 않습니다. 그러나 나중에 발생 가능한 새로운 경로를 방지하기 위한 심층 보안 대응책으로 이 소프트웨어의 고객은 이 보안 업데이트를 적용하는 것이 좋습니다.

 

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

**MS14-052**

-   Internet Explorer 메모리 손상 취약점(CVE-2014-2799)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4059)을 보고해 주신 [Adlab of Venustech](http://www.venustech.com.cn/)(중문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4065)을 보고해 주신 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4079)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 56e7aec02099b976120abfda31254b05
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4080)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4081)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4081)을 보고해 주신 [Adlab of Venustech](http://www.venustech.com.cn/)(중문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4082)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4082)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4083)을 보고해 주신 [Adlab of Venustech](http://www.venustech.com.cn/)(중문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4084)을 보고해 주신 [Adlab of Venustech](http://www.venustech.com.cn/)(중문)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4085)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Sky
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4086)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4087)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4087)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Zhibin Hu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4088)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4089)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4090)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Garage4Hackers
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4091)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4092)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4092)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 A3F2160DCA1BDE70DA1D99ED267D5DC1EC336192
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4092)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Jason Kratzer
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4093)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4094)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4095)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Trend Micro](http://www.trendmicro.com/)(영문)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4096)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 cloudfuzzer
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4096)을 보고해 주신 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4097)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Trend Micro](http://www.trendmicro.com/)(영문)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4097)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4098)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4099)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 SkyLined
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4100)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4101)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4101)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Yenteasy의 José A. Vázquez
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4102)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Liu Long
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4103)을 보고해 주신 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4104)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Liu Long
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4105)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Trend Micro](http://www.trendmicro.com/)(영문)의 Yuki Chen
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4106)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4107)을 보고해 주신 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)의 AbdulAziz Hariri
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4108)을 [HP](http://www.hpenterprisesecurity.com/products)(영문)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4109)을 보고해 주신 John Villamil(@day6reak)
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4110)을 보고해 주신 Heige
-   Internet Explorer 메모리 손상 취약점(CVE-2014-4111)을 보고해 주신 [Qihoo 360](http://www.360.cn/)(중문)의 Yujie Wen
-   이 공지에 포함된 심층 보안 변경 사항에 대해 협력해 주신 Masato Kinugawa 및 [Google Security Team](http://www.google.com/)

**MS14-053**

-   .NET Framework 서비스 거부 취약점(CVE-2014-4072)을 보고해 주신 [Cynops GmbH](http://www.cynops.de/)(영문)의 Alexander Klink

**MS14-054**

-   작업 스케줄러 취약점(CVE-2014-4074)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw

**MS14-055**

-   Lync 서비스 거부 취약점(CVE-2014-4068)을 보고해 주신 [Telecommunication Software GmbH](http://www.telecomsoftware.com/)(영문)의 Peter Schraffl
-   Lync XSS 정보 유출 취약점(CVE-2014-4070)을 Beyond Security의 [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html)(영문) 팀과 협력하여 보고해 주신 Noam Rathaus

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

-   V1.0(2014년 9월 10일): 공지 요약이 게시되었습니다.

*2014년 9월 11일 10:22Z-07:00에 페이지가 생성되었습니다.*
