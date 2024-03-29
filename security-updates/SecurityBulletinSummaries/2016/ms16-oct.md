---
TOCTitle: 'MS16-OCT'
Title: 2016년 10월 Microsoft 보안 공지 요약
ms:assetid: 'ms16-oct'
ms:contentKeyID: 74109915
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms16-oct(v=Security.10)'
---


2016년 10월 Microsoft 보안 공지 요약
====================================

게시된 날짜: 2016년 10월 11일 화요일 | 업데이트된 날짜: 2016년 10월 27일 목요일

**버전:** 2.0

이 공지 요약 목록에는 2016년 10월에 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 절을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향받는 소프트웨어에 대한 자세한 내용은 **영향받는 소프트웨어**라는 다음 절을 참조하십시오.

<p></p>
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 ID</strong></td>
<td style="border:1px solid black;"><strong>공지 제목 및 요약</strong></td>
<td style="border:1px solid black;"><strong>최대 심각도<br />
및 취약성 영향</strong></td>
<td style="border:1px solid black;"><strong>다시 시작 요구 사항</strong></td>
<td style="border:1px solid black;"><strong>알려진<br />
문제</strong></td>
<td style="border:1px solid black;"><strong>영향받는 소프트웨어</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827591">MS16-118</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3192887)<br />
</strong>이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우 공격자가 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827592">MS16-119</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(3192890)<br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Microsoft Edge를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 고객은 관리자 권한이 있는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827590">MS16-120</a></td>
<td style="border:1px solid black;"><strong>Microsoft 그래픽 구성 요소용 보안 업데이트(3192884)<br />
</strong>이 보안 업데이트는 Microsoft Windows, Microsoft .NET Framework, Microsoft Office, 비즈니스용 Skype, Silverlight 및 Microsoft Lync의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 웹 사이트를 방문하거나 특수 제작된 문서를 열 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework,<br />
Microsoft Office, 비즈니스용 Skype<br />
및 Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=828158">MS16-121</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office용 보안 업데이트(3194063)<br />
</strong>이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. Microsoft Office 소프트웨어가 RTF 파일을 제대로 처리하지 못하는 경우 Office 소프트웨어에 Office RTF 원격 코드 실행 취약성이 존재합니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Office Services 및 Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=829051">MS16-122</a></td>
<td style="border:1px solid black;"><strong>Microsoft 비디오 컨트롤용 보안 업데이트(3195360)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Microsoft 비디오 컨트롤이 메모리에서 개체를 적절하게 처리하지 못하는 경우 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 하지만 공격자는 사용자가 특수 제작된 파일 또는 웹 페이지나 전자 메일 메시지의 프로그램을 열도록 먼저 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827595">MS16-123</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버용 보안 업데이트(3192892)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이러한 취약성 중 더 위험한 취약성으로 인해 공격자가 영향받는 시스템에 로그온하여 취약성을 악용하고 영향받는 시스템을 제어할 수 있는 특수 제작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827821">MS16-124</a></td>
<td style="border:1px solid black;"><strong>Windows 레지스트리용 보안 업데이트(3193227)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 공격자가 중요한 레지스트리 정보에 액세스할 수 있는 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=827822">MS16-125</a></td>
<td style="border:1px solid black;"><strong>진단 허브용 보안 업데이트(3193229)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 공격자가 영향받는 시스템에 로그온한 후 특수 제작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=829052">MS16-126</a></td>
<td style="border:1px solid black;"><strong>Microsoft 인터넷 메시징 API용 보안 업데이트(3196067)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. Microsoft 인터넷 메시징 API가 메모리의 개체를 부적절하게 처리하는 경우 정보 유출 취약성이 존재합니다. 이 취약성 악용에 성공한 공격자는 디스크의 파일 유무를 테스트할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">보통(영문)</a> <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3185614">3185614</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3185611">3185611</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3188966">3188966</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=829053">MS16-127</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player용 보안 업데이트(3194343)<br />
</strong>이 보안 업데이트는 지원되는 모든 버전의 Windows 8.1, Windows Server 2012, Windows Server 2012 R2, Windows RT 8.1 및 Windows 10에 설치된 Adobe Flash Player의 취약성을 해결합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=832634">MS16-128</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player용 보안 업데이트(3201860)</strong><br />
이 보안 업데이트는 지원되는 모든 버전의 Windows 8.1, Windows Server 2012, Windows Server 2012 R2, Windows RT 8.1 및 Windows 10에 설치된 Adobe Flash Player의 취약성을 해결합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

악용 가능성 인덱스
------------------

<span id="sectionToggle1"></span>
다음 표에는 이달에 해결된 각 취약성의 악용 가능성 평가가 나와 있습니다. 취약성은 공지 ID, CVE ID 순으로 나열되어 있습니다. 공지에서 심각도 등급이 긴급 또는 중요인 취약성만 포함되어 있습니다.

**이 표를 어떻게 사용합니까?**

이 표를 사용하여 설치해야 할 수 있는 각 보안 업데이트에 대한 보안 공지 발표 후 30일 내 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토하십시오. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.

아래 열에서 "최신 소프트웨어 릴리스"는 관련 소프트웨어를 나타내며 "이전 소프트웨어 릴리스"는 공지의 "영향받는 소프트웨어" 및 "영향받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**취약성 제목**

</td>
<td style="border:1px solid black;">
**최신 소프트웨어 릴리스에 대한  
악용 가능성 평가**

</td>
<td style="border:1px solid black;">
**이전 소프트웨어 릴리스에 대한  
악용 가능성 평가**

</td>
<td style="border:1px solid black;">
**서비스 거부  
악용 가능성 평가**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-118: Internet Explorer용 누적 보안 업데이트(3192887)**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3267(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3267)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3298(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3298)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3331(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3331)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3382(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3382)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3383(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3383)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3384(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3384)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3385(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3385)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3387(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3387)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3388(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3388)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3390(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3390)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3391(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3391)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-119: Microsoft Edge용 누적 보안 업데이트(3192890)**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3267(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3267)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3331(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3331)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3382(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3382)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3386(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3386)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3387(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3387)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3388(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3388)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3389(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3389)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3390(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3390)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3391(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3391)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3392(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3392)

</td>
<td style="border:1px solid black;">
Microsoft Edge 보안 기능 우회

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7189(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7189)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7190(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7190)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7194(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7194)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-120: Microsoft 그래픽 구성 요소용 보안 업데이트(3192884)**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3209(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3209)

</td>
<td style="border:1px solid black;">
트루타입 글꼴 구문 분석 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3262(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3262)

</td>
<td style="border:1px solid black;">
GDI+ 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3263(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3263)

</td>
<td style="border:1px solid black;">
GDI+ 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
임시

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3270(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3270)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3393(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3393)

</td>
<td style="border:1px solid black;">
Windows 그래픽 구성 요소 RCE 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3396(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3396)

</td>
<td style="border:1px solid black;">
GDI+ 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7182(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7182)

</td>
<td style="border:1px solid black;">
트루타입 글꼴 구문 분석 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-121: Microsoft Office용 보안 업데이트(3194063)**](http://go.microsoft.com/fwlink/?linkid=828158)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7193(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7193)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-122: Microsoft 비디오 컨트롤용 보안 업데이트(3195360)**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0142(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0142)

</td>
<td style="border:1px solid black;">
Microsoft 비디오 컨트롤 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-123: Windows 커널 모드 드라이버용 보안 업데이트(3192892)**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3266(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3266)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3341(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3341)

</td>
<td style="border:1px solid black;">
Windows 트랜잭션 관리자 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3376(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3376)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7185(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7185)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7211(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7211)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-124: Windows 레지스트리용 보안 업데이트(3193227)**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0070(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0070)

</td>
<td style="border:1px solid black;">
Windows 커널 로컬 권한 상승

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0073(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0073)

</td>
<td style="border:1px solid black;">
Windows 커널 로컬 권한 상승

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0075(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0075)

</td>
<td style="border:1px solid black;">
Windows 커널 로컬 권한 상승

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0079(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0079)

</td>
<td style="border:1px solid black;">
Windows 커널 로컬 권한 상승

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-125: 진단 허브용 보안 업데이트(3193229)**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7188(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7188)

</td>
<td style="border:1px solid black;">
Windows 진단 허브 권한 상승

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-126: Microsoft 인터넷 메시징 API용 보안 업데이트(3196067)**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3298(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3298)

</td>
<td style="border:1px solid black;">
Internet Explorer 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-127: Adobe Flash Player용 보안 업데이트(3194343)**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-32](http://helpx.adobe.com/kr/security/products/flash-player/apsb16-32.html)

</td>
<td style="border:1px solid black;">
취약성 심각도 및 업데이트 우선 순위 등급은 Adobe 보안 공지 [APSB16-32](http://helpx.adobe.com/kr/security/products/flash-player/apsb16-32.html)를 참조하십시오.

</td>
<td style="border:1px solid black;">
-------------

</td>
<td style="border:1px solid black;">
-------------

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-128: Adobe Flash Player용 보안 업데이트(3201860)**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-36](https://helpx.adobe.com/ko-kr/security/products/flash-player/apsb16-36)

</td>
<td style="border:1px solid black;">
취약성 심각도 및 업데이트 우선 순위 등급은 Adobe 보안 공지 [APSB16-32](http://helpx.adobe.com/kr/security/products/flash-player/apsb16-32.html)를 참조하십시오.

</td>
<td style="border:1px solid black;">
-------------

</td>
<td style="border:1px solid black;">
-------------

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 

영향받는 소프트웨어
-------------------

<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.

**참고** 단일 취약성에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 ID로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

### Windows 운영 체제 및 구성 요소(표 1/2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3191492)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3191203)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3190847)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3191203)  
(중요)  
Windows Vista 서비스 팩 2  
(3183431)(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3191492)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3191203)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3190847)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3191203)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(3183431)(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3191492)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3191203)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3191203)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3183431)(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3191492)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3191203)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3191203)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3183431)(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3191203)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3191203)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3183431)(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192391)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3192391)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3192391)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3192391)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185330)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3185330)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3185330)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3185330)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192391)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3192391)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3192391)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3192391)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185330)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3185330)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3185330)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3185330)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192391)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3192391)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3192391)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185330)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3185330)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3185330)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3192391)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3192391)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3185330)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3185330)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192392)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3192392)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3192392)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3192392)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3185331)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192392)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3192392)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3192392)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3192392)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3185331)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3192393)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3192393)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3192393)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3185332)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3185332)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3185332)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192392)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3192392)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3192392)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185331)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3185331)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185331)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192440)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3192440)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3192440)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3192440)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3192440)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192440)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3192440)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3192440)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3192440)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3192440)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192441)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3192441)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3192441)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3192441)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3192441)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3192441)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3192441)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3192441)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3192441)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3192441)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3194798)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3194798)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3194798)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3194798)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-118**](http://go.microsoft.com/fwlink/?linkid=827591)

</td>
<td style="border:1px solid black;">
[**MS16-119**](http://go.microsoft.com/fwlink/?linkid=827592)

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-122**](http://go.microsoft.com/fwlink/?linkid=829051)

</td>
<td style="border:1px solid black;">
[**MS16-123**](http://go.microsoft.com/fwlink/?linkid=827595)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3191203)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3191203)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3183431)(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3191203)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3191203)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3183431)(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3192391)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3192391)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3185330)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3185330)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3192393)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3192393)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3185332)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3185332)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3192392)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3192392)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3185331)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3185331)  
(중요)

</td>
</tr>
</table>
 
### Windows 운영 체제 및 구성 요소(표 2/2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3191256)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3193515)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3191256)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3193515)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**낮음(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3191256)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3193515)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3191256)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3193515)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3191256)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3193515)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3192391)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3192391)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3185330)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3185330)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3192391)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3192391)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3185330)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3185330)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**낮음(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3192391)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3192391)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3185330)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3185330)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3192391)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3192391)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3185330)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3185330)  
(낮음)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3192392)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(긴급)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3185331)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3192392)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(긴급)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3185331)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3192393)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(보통)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3185332)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3192392)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(보통)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(보통)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3185331)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3185331)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(긴급)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3192440)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3192440)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(긴급)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3192440)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3192440)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(긴급)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3192441)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3192441)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(긴급)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3192441)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3192441)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(긴급)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(긴급)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3194343)  
(긴급)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3201860)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-124**](http://go.microsoft.com/fwlink/?linkid=827821)

</td>
<td style="border:1px solid black;">
[**MS16-125**](http://go.microsoft.com/fwlink/?linkid=827822)

</td>
<td style="border:1px solid black;">
[**MS16-126**](http://go.microsoft.com/fwlink/?linkid=829052)

</td>
<td style="border:1px solid black;">
[**MS16-127**](http://go.microsoft.com/fwlink/?linkid=829053)

</td>
<td style="border:1px solid black;">
[**MS16-128**](http://go.microsoft.com/fwlink/?linkid=832634)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3191256)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3191256)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3192391)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3185330)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3192393)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3185332)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3192392)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3185331)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 
 

### Microsoft .NET Framework – 보안 전용 릴리스

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Vista  
Vista 및 Server 2008용 Microsoft .NET Framework 3.0, 4.5.2, 4.6 업데이트 (KB3188736)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 서비스 팩 2  
(3188726)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189039)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189040)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 서비스 팩 2  
(3188726)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189039)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189040)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008  
Vista 및 Server 2008용 Microsoft .NET Framework 3.0, 4.5.2, 4.6 업데이트 (KB3188736)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 서비스 팩 2  
(3188726)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189039)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189040)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 서비스 팩 2  
(3188726)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189039)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189040)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188730)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188730)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188730)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188730)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188732)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188732)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188731)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188732)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3192440)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3192440)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3192441)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3192441)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3194798)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188730)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188731)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188732)  
(중요)

</td>
</tr>
</table>
 
 

### Microsoft .NET Framework – 월별 롤업 릴리스

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Vista  
Vista 및 Server 2008용 Microsoft .NET Framework 3.0, 4.5.2, 4.6 업데이트 (KB3188744)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 서비스 팩 2  
(3188735)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189051)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189052)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 서비스 팩 2  
(3188735)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189051)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189052)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008  
Vista 및 Server 2008용 Microsoft .NET Framework 3.0, 4.5.2, 4.6 업데이트 (KB3188744)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 서비스 팩 2  
(3188735)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189051)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189052)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.0 서비스 팩 2  
(3188735)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3189051)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3189052)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188740)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188740)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188740)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188740)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188743)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188743)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188741)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188743)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3192440)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3192440)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3192441)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3192441)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3194798)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3194798)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3188740)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188741)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3188743)  
중요

</td>
</tr>
</table>
 
 

### Microsoft 통신 플랫폼 및 소프트웨어

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**비즈니스용 Skype 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(32비트 버전)  
(3118327)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(32비트 버전)  
(3118327)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(64비트 버전)  
(3118327)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(64비트 버전)  
(3118327)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype)  
(3118348)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1 (32비트)  
(비즈니스용 Skype Basic)  
(3118348)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype)  
(3118348)  
중요

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1 (32비트)  
(비즈니스용 Skype Basic)  
(3118348)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)  
(3188397)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)  
(3188397)  
(중요)

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
(3188399)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)  
(3188400)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007 콘솔**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 콘솔

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 콘솔  
(3189647)  
(중요)

</td>
</tr>
</table>
 
 

### Microsoft 개발자 도구 및 소프트웨어

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5  
(3193713)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5 Developer 런타임

</td>
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3193713)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5  
(3193713)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5 Developer 런타임

</td>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3193713)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5  
(3193713)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5 Developer 런타임

</td>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3193713)  
(중요)

</td>
</tr>
</table>
 
 

### Microsoft Office 제품군 및 소프트웨어

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(3118301)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 서비스 팩 3  
(3118308)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3118317)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3118311)  
(긴급)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(3118312)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3118317)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3118311)  
(긴급)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(3118312)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(3118345)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(3118345)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT 서비스 팩 1  
(3118345)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Word 2016(32비트 버전)  
(3118331)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Word 2016(64비트 버전)  
(3118331)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3193442)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3193438)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**기타 Office 소프트웨어**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-120**](http://go.microsoft.com/fwlink/?linkid=827590)

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3118307)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3118394)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3127898)  
(긴급)

</td>
</tr>
</table>
 
 

### Microsoft Office Services 및 Web Apps

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3118377)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3118352)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2  
(3118384)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-121**](http://go.microsoft.com/fwlink/?linkid=828158)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(3118360)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3127897)  
(긴급)

</td>
</tr>
</table>
 
 

검색, 배포 도구 및 지침
-----------------------

<span id="sectionToggle3"></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 있습니다.

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트와 일반적인 보안 구성 오류를 검색할 수 있습니다.

관리자는 WSUS(Windows Server Update Services), SMS(Systems Management Server) 및 System Center Configuration Manager를 통해 보안 업데이트를 배포할 수 있습니다.

ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](http://technet.microsoft.com/ko-kr/security/cc297183)를 참조하십시오. 

감사의 말
---------

<span id="sectionToggle4"></span>
Microsoft는 신뢰할 수 있는 취약성 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/mt674627.aspx)(영문)을 참조하십시오.

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 보안 공지에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services 및 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 릴리스에서 제공되지 않습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft Update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/ko-kr/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services용으로 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/wsus/bb456965)(영문). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 재출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 발표하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드(중요)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

**기타 보안 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 제공됩니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 제공됩니다. "보안 업데이트"라는 키워드 검색을 수행하면 가장 쉽게 찾을 수 있습니다.
-   소비자 플랫폼용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 제공됩니다.
-   이달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 긴급 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/ko-kr/kb/913086)을 참조하십시오.

**IT 전문가 보안 커뮤니티**

[IT 전문가 보안 커뮤니티](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 알아보고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향받는 소프트웨어는 테스트를 거쳐 영향받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 주기](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/ko-kr/security/bb980617)

Windows가 실행되는 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](http://support.microsoft.com/ko-kr/contactus/cu_sc_virsec_master)

지역별 지원 정보: [국가별 지원](http://support.microsoft.com/ko-kr/common/international.aspx)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한이 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2016년 10월 11일): 공지 요약이 게시되었습니다.
-   V1.1(2016년 10월 12일 수요일): MS16-121의 심각도를 긴급으로 변경하도록 공지 요약이 수정되었습니다. 본 공지는 변경된 정보를 알리는 용도로만 제공됩니다.
-   V2.0(2016년 10월 27일 목요일): Flash MS16-128에 대한 새 공지를 추가하도록 공지 요약이 수정되었습니다.
-   V3.0(2017년 9월 12일): MS16-123의 경우 Windows 10 버전 1703(32비트 시스템용) 및 Windows 10 버전 1703(x64 기반 시스템용)이 CVE-2016-3376의 영향을 받으므로 이러한 운영 체제를 포함하도록 Windows 운영 체제 및 구성 요소 영향받는 소프트웨어 표를 수정했습니다. Windows 10 버전 1703을 실행하는 고객의 경우 이 취약성으로부터 보호받으려면 업데이트 4038788을 설치하는 것이 좋습니다.

*2016-10-27 10:20-07:00에 페이지가 생성되었습니다.*
