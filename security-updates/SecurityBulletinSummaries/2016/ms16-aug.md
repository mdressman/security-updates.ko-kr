---
TOCTitle: 'MS16-AUG'
Title: 2016년 8월 Microsoft 보안 공지 요약
ms:assetid: 'ms16-aug'
ms:contentKeyID: 73405899
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms16-aug(v=Security.10)'
---

2016년 8월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2016년 8월 9일 | 업데이트된 날짜: 2017년 6월 13일

**버전:** 2.0

이 공지 요약 목록에는 2016년 8월에 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 절을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 **영향받는 소프트웨어** 절을 참조하십시오.


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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=821136">MS16-095</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3177356)<br />
</strong>이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우 공격자가 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3176492">3176492</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176493">3176493</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176495">3176495</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=821137">MS16-096</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(3177358)<br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Microsoft Edge를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 고객은 관리자 권한이 있는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3176492">3176492</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176493">3176493</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176495">3176495</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=821146">MS16-097</a></td>
<td style="border:1px solid black;"><strong>Microsoft 그래픽 구성 요소용 보안 업데이트(3177393)<br />
</strong>이 보안 업데이트는 Microsoft Windows, Microsoft Office, 비즈니스용 Skype 및 Microsoft Lync의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 웹 사이트를 방문하거나 특수 제작된 문서를 열 경우 원격 코드 실행이 허용될 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3176492">3176492</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176493">3176493</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176495">3176495</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office,<br />
Microsoft 통신 플랫폼 및 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=821582">MS16-098</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버용 보안 업데이트(3178466)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이러한 취약성으로 인해 공격자가 영향받는 시스템에 로그온하여 취약성을 악용하고 영향받는 시스템을 제어할 수 있는 특수 제작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a><br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3176492">3176492</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176493">3176493</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176495">3176495</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3177725">3177725</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=821165">MS16-099</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office용 보안 업데이트(3177451)<br />
</strong>이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office<br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=822552">MS16-100</a></td>
<td style="border:1px solid black;"><strong>보안 부팅용 보안 업데이트(3179577)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 공격자가 영향받는 부팅 관리자를 설치하고 Windows 보안 기능을 우회하는 경우 보안 기능 우회가 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">다시 시작할 필요 없음</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3179577">3179577</a><br />
</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=821576">MS16-101</a></td>
<td style="border:1px solid black;"><strong>Windows 인증 방법용 보안 업데이트(3178465)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 여러 가지 취약성을 해결합니다. 더 위험한 취약성으로 인해 공격자가 도메인에 연결된 시스템에서 특수 제작된 응용 프로그램을 실행하면 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3176492">3176492</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176493">3176493</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176495">3176495</a><a href="https://support.microsoft.com/ko-kr/kb/3167679">3167679</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=823207">MS16-102</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows PDF 라이브러리용 보안 업데이트(3182248)</strong><br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 PDF 콘텐츠를 온라인으로 보거나 특수 제작된 PDF 문서를 열 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우 공격자가 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3176492">3176492</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176493">3176493</a><br />
</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=823241">MS16-103</a></td>
<td style="border:1px solid black;"><strong>ActiveSyncProvider용 보안 업데이트(3182332)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성은 Universal Outlook이 보안 연결을 설정하지 못할 경우 정보 유출을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ko-kr/kb/3176492">3176492</a><br />
<a href="https://support.microsoft.com/ko-kr/kb/3176493">3176493</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
[**MS16-095: Internet Explorer용 누적 보안 업데이트(3177356)**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3288(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3288)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3289(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3289)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3290(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3290)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3293(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3293)

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
[CVE-2016-3321(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3321)

</td>
<td style="border:1px solid black;">
Internet Explorer 정보 유출 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3322(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3322)

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
[CVE-2016-3326(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3326)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3327(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3327)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3329(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3329)

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
[**MS16-096: Microsoft Edge용 누적 보안 업데이트(3177358)**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3289(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3289)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저메모리 손상 취약성

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
[CVE-2016-3293(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3293)

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
[CVE-2016-3296(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3296)

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
[CVE-2016-3319(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3319)

</td>
<td style="border:1px solid black;">
Microsoft PDF 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3322(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3322)

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
[CVE-2016-3326(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3326)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

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
[CVE-2016-3327(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3327)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3329(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3329)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-097: Microsoft 그래픽 구성 요소용 보안 업데이트(3177393)**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3301(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3301)

</td>
<td style="border:1px solid black;">
Windows 그래픽 구성 요소 RCE 취약성

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3303(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3303)

</td>
<td style="border:1px solid black;">
Windows 그래픽 구성 요소 RCE 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3304(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3304)

</td>
<td style="border:1px solid black;">
Windows 그래픽 구성 요소 RCE 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-098: Windows 커널 모드 드라이버용 보안 업데이트(3178466)**](http://go.microsoft.com/fwlink/?linkid=821582)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3308(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3308)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3309(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3309)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3310(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3310)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3311(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3311)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-099: Microsoft Office용 보안 업데이트(3177451)**](http://go.microsoft.com/fwlink/?linkid=821165)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3313(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-cve-2016-3313)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3315(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3315)

</td>
<td style="border:1px solid black;">
Microsoft OneNote 정보 유출 취약성

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
<td style="border:1px solid black;">
[CVE-2016-3316(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3316)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3317(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3317)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1- 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3318(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3318)

</td>
<td style="border:1px solid black;">
그래픽 구성 요소 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-100: 보안 부팅용 보안 업데이트(3179577)**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3320(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3320)

</td>
<td style="border:1px solid black;">
보안 부팅 보안 기능 우회 취약성

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-101: Windows 인증 방법용 보안 업데이트(3178465)**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3237(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3237)

</td>
<td style="border:1px solid black;">
Kerberos 보안 기능 우회 취약성

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3300(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3300)

</td>
<td style="border:1px solid black;">
NetLogon 권한 상승 취약성

</td>
<td style="border:1px solid black;">
4 - 해당 없음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-102: Microsoft Windows PDF 라이브러리용 보안 업데이트(3182248)**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3319(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3319)

</td>
<td style="border:1px solid black;">
Microsoft PDF 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2- 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-103: ActiveSyncProvider용 보안 업데이트(3182332)**](http://go.microsoft.com/fwlink/?linkid=823241)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3312(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3312)

</td>
<td style="border:1px solid black;">
Universal Outlook 정보 유출 취약성

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
</table>
 

영향받는 소프트웨어
-------------------

<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.

**참고** 단일 취약성에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

 

### Windows 운영 체제 및 구성 요소(표 1/2)


<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-095**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
<td style="border:1px solid black;">
[**MS16-096**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
<td style="border:1px solid black;">
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-098**](http://go.microsoft.com/fwlink/?linkid=821582)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3175443)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3175443)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-095**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
<td style="border:1px solid black;">
[**MS16-096**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
<td style="border:1px solid black;">
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-098**](http://go.microsoft.com/fwlink/?linkid=808150)

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
**없음**

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3175443)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3175443)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3177725)  
(중요)

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
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-095**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
<td style="border:1px solid black;">
[**MS16-096**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
<td style="border:1px solid black;">
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-098**](http://go.microsoft.com/fwlink/?linkid=821582)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11               
(4021558)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음                   

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4021558)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-095**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
<td style="border:1px solid black;">
[**MS16-096**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
<td style="border:1px solid black;">
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-098**](http://go.microsoft.com/fwlink/?linkid=821582)

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
**없음**

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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4021558)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-095**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
<td style="border:1px solid black;">
[**MS16-096**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
<td style="border:1px solid black;">
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-098**](http://go.microsoft.com/fwlink/?linkid=821582)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4021558)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4021558)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-095**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
<td style="border:1px solid black;">
[**MS16-096**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
<td style="border:1px solid black;">
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-098**](http://go.microsoft.com/fwlink/?linkid=821582)

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
**없음**

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4021558)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4021558)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-095**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
<td style="border:1px solid black;">
[**MS16-096**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
<td style="border:1px solid black;">
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-098**](http://go.microsoft.com/fwlink/?linkid=821582)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4021558)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3177725)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-095**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
<td style="border:1px solid black;">
[**MS16-096**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
<td style="border:1px solid black;">
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-098**](http://go.microsoft.com/fwlink/?linkid=821582)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4022727)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3176492)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3176492)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3176492)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4022727)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3176492)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3176492)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3176492)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4022714)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3176493)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3176493)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3176493)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4022714)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3176493)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3176493)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3176493)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4022715)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3176495)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3176495)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3176495)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4022715)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3176495)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3176495)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3176495)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-095**](http://go.microsoft.com/fwlink/?linkid=821136)

</td>
<td style="border:1px solid black;">
[**MS16-096**](http://go.microsoft.com/fwlink/?linkid=821137)

</td>
<td style="border:1px solid black;">
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-098**](http://go.microsoft.com/fwlink/?linkid=821582)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
**없음**

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3170455)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3170455)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3170455)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3170455)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3178034)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3170455)  
(중요)

</td>
</tr>
</table>
 
 

### Windows 운영 체제 및 구성 요소(표 2/2)


<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-100**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
<td style="border:1px solid black;">
[**MS16-101**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
<td style="border:1px solid black;">
[**MS16-102**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
<td style="border:1px solid black;">
[**MS16-103**](http://go.microsoft.com/fwlink/?linkid=823241)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3167679)  
(중요)

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
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3167679)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-100**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
<td style="border:1px solid black;">
[**MS16-101**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
<td style="border:1px solid black;">
[**MS16-102**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
<td style="border:1px solid black;">
[**MS16-103**](http://go.microsoft.com/fwlink/?linkid=823241)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3167679)  
(중요)

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

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3167679)  
(중요)

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
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3167679)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-100**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
<td style="border:1px solid black;">
[**MS16-101**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
<td style="border:1px solid black;">
[**MS16-102**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
<td style="border:1px solid black;">
[**MS16-103**](http://go.microsoft.com/fwlink/?linkid=823241)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3167679)  
(중요)

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
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3167679)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-100**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
<td style="border:1px solid black;">
[**MS16-101**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
<td style="border:1px solid black;">
[**MS16-102**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
<td style="border:1px solid black;">
[**MS16-103**](http://go.microsoft.com/fwlink/?linkid=823241)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3167679)  
(중요)

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
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3167679)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-100**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
<td style="border:1px solid black;">
[**MS16-101**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
<td style="border:1px solid black;">
[**MS16-102**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
<td style="border:1px solid black;">
[**MS16-103**](http://go.microsoft.com/fwlink/?linkid=823241)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3167679)  
(중요)  
Windows 8.1(32비트 시스템용)  
(3177108)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3175887)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3167679)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(3177108)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3175887)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-100**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
<td style="border:1px solid black;">
[**MS16-101**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
<td style="border:1px solid black;">
[**MS16-102**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
<td style="border:1px solid black;">
[**MS16-103**](http://go.microsoft.com/fwlink/?linkid=823241)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3177108)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3175887)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3167679)  
(중요)  
Windows Server 2012 R2  
(3177108)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3175887)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-100**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
<td style="border:1px solid black;">
[**MS16-101**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
<td style="border:1px solid black;">
[**MS16-102**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
<td style="border:1px solid black;">
[**MS16-103**](http://go.microsoft.com/fwlink/?linkid=823241)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3167679)  
(중요)  
Windows RT 8.1  
(3177108)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3175887)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-100**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
<td style="border:1px solid black;">
[**MS16-101**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
<td style="border:1px solid black;">
[**MS16-102**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
<td style="border:1px solid black;">
[**MS16-103**](http://go.microsoft.com/fwlink/?linkid=823241)

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
Windows 10(32비트 시스템용)  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3176492)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3176492)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3176492)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3176492)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3176492)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3176492)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3176493)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3176493)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3176493)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3176493)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3176493)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3176493)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(3176495)  
(중요)

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
Windows 10 버전 1607(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(3176495)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-100**](http://go.microsoft.com/fwlink/?linkid=822552)

</td>
<td style="border:1px solid black;">
[**MS16-101**](http://go.microsoft.com/fwlink/?linkid=821576)

</td>
<td style="border:1px solid black;">
[**MS16-102**](http://go.microsoft.com/fwlink/?linkid=823207)

</td>
<td style="border:1px solid black;">
[**MS16-103**](http://go.microsoft.com/fwlink/?linkid=823241)

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
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3167679)  
(중요)

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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3167679)  
(중요)

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

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3167679)  
(중요)

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

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3177108)  
(중요)

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

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3172729)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3167679)  
(중요)  
Windows Server 2012 R2(Server Core 설치)  
(3177108)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-099**](http://go.microsoft.com/fwlink/?linkid=821165)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(3115109)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(3114442)  
(중요)  
Microsoft Office 2007 서비스 팩 3  
(3114893)  
(중요)  
Microsoft OneNote 2007 서비스 팩 3  
(3114456)  
(중요)  
Microsoft Word 2007 서비스 팩 3  
(3115465)  
(중요)

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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-099**](http://go.microsoft.com/fwlink/?linkid=821165)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3115131)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3114400)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3114869)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3115468)  
(중요)  
Microsoft OneNote 2010 서비스 팩 2(32비트 버전)  
(3114885)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(3115471)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3115131)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3114400)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3114869)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3115468)  
(중요)  
Microsoft OneNote 2010 서비스 팩 2(64비트 버전)  
(3114885)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(3115471)  
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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-099**](http://go.microsoft.com/fwlink/?linkid=821165)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**

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
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(3114340)  
(중요)  
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(3115427)  
(중요)  
Microsoft OneNote 2013 서비스 팩 1(32비트 버전)  
(3115256)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(3115449)  
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
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(3114340)  
(중요)  
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(3115427)  
(중요)  
Microsoft OneNote 2013 서비스 팩 1(64비트 버전)  
(3115256)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(3115449)  
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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-099**](http://go.microsoft.com/fwlink/?linkid=821165)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**

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
Microsoft Office 2013 RT 서비스 팩 1  
(3114340)  
(중요)  
Microsoft Office 2013 RT 서비스 팩 1  
(3115427)  
(중요)  
Microsoft OneNote 2013 RT 서비스 팩 1  
(3115256)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(3115449)  
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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-099**](http://go.microsoft.com/fwlink/?linkid=821165)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**

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
Microsoft Office 2016(32비트 버전)  
(3115415)  
(중요)  
Microsoft OneNote 2016(32비트 버전)  
(3115419)  
(중요)  
Microsoft Word 2016(32비트 버전)  
(3115439)  
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
Microsoft Office 2016(64비트 버전)  
(3115415)  
(중요)  
Microsoft OneNote 2016(64비트 버전)  
(3115419)  
(중요)  
Microsoft Word 2016(64비트 버전)  
(3115439)  
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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-099**](http://go.microsoft.com/fwlink/?linkid=821165)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**  

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3179162)  
(중요)

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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-099**](http://go.microsoft.com/fwlink/?linkid=821165)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**사용 안 함**  

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft OneNote 2016 for Mac  
(3179163)  
(중요)  
Microsoft Word 2016 for Mac  
(3179163)  
(중요)

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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

</td>
<td style="border:1px solid black;">
[**MS16-099**](http://go.microsoft.com/fwlink/?linkid=821165)

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
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115481)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115479)  
(중요)  
Microsoft Word Viewer  
(3115480)  
(중요)

</td>
</tr>
</table>
 
**MS16-097 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

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
비즈니스용 Skype 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(32비트 버전)  
(3115408)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(32비트 버전)  
(3115408)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(64비트 버전)  
(3115408)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(64비트 버전)  
(3115408)  
(긴급)

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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

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
Microsoft Lync 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype)  
(3115431)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype Basic)  
(3115431)  
(긴급)

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
(3115431)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype Basic)  
(3115431)  
(긴급)

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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

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
Microsoft Lync 2010(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)  
(3174301)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)  
(3174301)  
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
(3174302)  
(긴급)

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
(3174304)  
(긴급)

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
[**MS16-097**](http://go.microsoft.com/fwlink/?linkid=821146)

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
Microsoft Live Meeting 2007 콘솔

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 콘솔  
(3174305)  
(긴급)

</td>
</tr>
</table>
 
**MS16-097 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

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
-   [Windows Server Update Services용으로 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/wsus/bb456965). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 재출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 발표하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://go.microsoft.com/fwlink/?linkid=21168)(영문)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

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

-   V1.0([2016년 8월 9일](https://technet.microsoft.com/ko-KR/library/bulletin+summary_publisheddate(v=Security.10))): 공지 요약이 게시되었습니다.
-   V1.1([2016년 8월 10일](https://technet.microsoft.com/ko-KR/library/bulletin+summary_publisheddate(v=Security.10))): MS16-101에 대한 공지 요약이 수정되어 CVE-2016-3237의 보안 영향이 '권한 상승'에서 '보안 기능 우회'로 변경되었습니다. 본 공지는 변경된 정보를 알리는 용도로만 제공됩니다. 업데이트를 이미 올바르게 설치한 고객은 조치를 취할 필요가 없습니다.
-   V1.2(2016년 8월 11일 목요일): Server Core 버전의 Windows Server 2012 R2는 영향을 받지 않기 때문에 영향받는 소프트웨어 표에서 Windows Server 2012 R2(Server Core 설치)를 제거하도록 MS16-102에 대한 공지 요약이 수정되었습니다. 이 변경 사항은 정보 제공용입니다. 업데이트를 이미 올바르게 설치한 고객은 조치를 취할 필요가 없습니다.
-   V1.3(2016년 8월 12일 금요일): Windows 10 버전 1607은 영향을 받지 않기 때문에 영향받는 소프트웨어 표에서 이를 제거하도록 MS16-102에 대한 공지 요약이 개정되었습니다. 본 공지는 변경된 정보를 알리는 용도로만 제공됩니다. 업데이트를 이미 올바르게 설치한 고객은 조치를 취할 필요가 없습니다.
-   V1.4(2016년 8월 18일): 실무 요약 표에 알려진 문제 참조를 추가하도록 MS16-095, MS16-096, MS16-097, MS16-098, MS16-101, MS16-102 및 MS16-103에 대한 공지 요약이 개정되었습니다. 자세한 내용은 관련 기술 자료 문서를 참조하십시오.
-   V2.0(2017년 6월 13일): Microsoft는 CVE-2016-3326을 포괄적으로 해결하기 위해 영향받는 모든 Microsoft 브라우저를 대상으로 6월 보안 업데이트를 발표합니다. 영향받는 버전의 Microsoft 브라우저를 실행하는 고객의 경우 이 취약성으로부터 완전히 보호받으려면 해당하는 6월 보안 업데이트를 설치해야 합니다. 자세한 내용은 해당하는 릴리스 정보 또는 Microsoft 기술 자료 문서를 참조하세요.

*2016년 6월 15일 15:52-07:00에 페이지가 생성되었습니다.*
