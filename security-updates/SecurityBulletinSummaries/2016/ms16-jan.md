---
TOCTitle: 'MS16-JAN'
Title: 2016년 1월 Microsoft 보안 공지 요약
ms:assetid: 'ms16-jan'
ms:contentKeyID: 72150200
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms16-jan(v=Security.10)'
---

2016년 1월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2016년 1월 13일

**버전:** 1.0

이 공지 요약에는 2016년 1월 발표된 보안 공지가 나와 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/ko-kr/security/dd252948.aspx)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 절을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향받는 소프트웨어에 대한 자세한 내용은 **영향받는 소프트웨어**라는 다음 절을 참조하십시오.

<p> </p>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717999">MS16-001</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(3124903)</strong> <br />
이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 보다 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우, 이 취약성 악용에 성공한 공격자는 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718002">MS16-002</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(3124904) <br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 취약성은 사용자가 특수 제작된 웹 페이지를 Microsoft Edge를 사용하여 보는 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718004">MS16-003</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 JScript 및 VBScript에 대한 누적 보안 업데이트(3125540) <br />
</strong>이 보안 업데이트는 Microsoft Windows의 VBScript 스크립팅 엔진의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우, 이 취약성 악용에 성공한 공격자는 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717998">MS16-004</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Microsoft Office에 대한 보안 업데이트(3124585)</strong> <br />
이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Visual Basic</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718001">MS16-005</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Windows 커널 모드 드라이버용 보안 업데이트(3124584)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 보다 심각한 취약성은 사용자가 악성 웹 사이트를 방문하는 경우 원격 코드 실행을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717994">MS16-006</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Silverlight에 대한 보안 업데이트(3126036)</strong> <br />
이 보안 업데이트는 Microsoft Silverlight의 취약성을 해결합니다. 사용자가 특수 제작된 Silverlight 응용 프로그램이 포함된 공격에 노출된 웹 사이트를 방문할 경우 이 취약성으로 인해 원격 코드 실행이 허용될 수 있습니다. 공격자는 강제로 사용자가 공격에 노출된 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 일반적으로 공격자의 웹 사이트로 유인하는 전자 메일 또는 인스턴트 메시지의 링크를 사용자가 클릭하도록 하여 해당 웹 사이트를 방문하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작할 필요 없음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718006">MS16-007</a></td>
<td style="border:1px solid black;"><strong>원격 코드 실행을 해결하기 위한 Microsoft Windows에 대한 보안 업데이트(3124901)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 공격자가 대상 시스템에 로그온하고 특수 제작된 응용 프로그램을 실행할 수 있는 경우 원격 코드 실행을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/en-us/kb/3124266">3124266</a><br />
<a href="https://support.microsoft.com/en-us/kb/3124263">3124263</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718007">MS16-008</a></td>
<td style="border:1px solid black;"><strong>권한 상승을 해결하기 위한 Windows 커널에 대한 보안 업데이트(3124605)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 공격자가 영향받는 시스템에 로그온한 후 특수 제작된 응용 프로그램을 실행하는 경우 이 취약성으로 인해 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717997">MS16-010</a></td>
<td style="border:1px solid black;"><strong>스푸핑을 해결하기 위한 Microsoft Exchange Server의 보안 업데이트(3124557)</strong> <br />
이 보안 업데이트는 Microsoft Exchange Server의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 OWA(Outlook Web Access)가 적절히 웹 요청을 처리하고 사용자 입력 및 전자 메일 콘텐츠를 삭제하지 못하는 경우 스푸핑을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a>(영문) <br />
스푸핑</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표에는 이달에 해결된 각 취약성의 악용 가능성 평가가 나와 있습니다. 취약성은 공지 ID 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약성만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 할 수 있는 각 보안 업데이트에 대한 보안 공지 발표 후 30일 내 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토하십시오. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 릴리스"는 관련 소프트웨어를 나타내며 "이전 소프트웨어 릴리스"는 공지의 "영향받는 소프트웨어" 및 "영향받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

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
[**MS16-001: Internet Explorer용 누적 보안 업데이트(3124903)**](http://go.microsoft.com/fwlink/?linkid=717999)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0002(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0002)

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
[CVE-2016-0005(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0005)

</td>
<td style="border:1px solid black;">
Internet Explorer 권한 상승 취약성

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
[**MS16-002: Microsoft Edge용 누적 보안 업데이트(3124904)**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0003(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0003)

</td>
<td style="border:1px solid black;">
Microsoft Edge 메모리 손상 취약성

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
[CVE-2016-0024(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0024)

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
[**MS16-003: 원격 코드 실행을 해결하기 위한 JScript 및 VBScript에 대한 누적 보안 업데이트(3125540)**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0002(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0002)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

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
<td style="border:1px solid black;" colspan="5">
[**MS16-004: 원격 코드 실행을 해결하기 위한 Microsoft Office에 대한 보안 업데이트(3124585)**](http://go.microsoft.com/fwlink/?linkid=717998)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6117(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6117)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint 보안 기능 우회 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

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
[CVE-2016-0010(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0010)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

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
[CVE-2016-0011(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0011)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint 보안 기능 우회 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

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
[CVE-2016-0012(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0012)

</td>
<td style="border:1px solid black;">
Microsoft Office ASLR 우회

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
[CVE-2016-0035(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0035)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

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
[**MS16-005: 권한 상승을 해결하기 위한 Windows 커널 모드 드라이버에 대한 보안 업데이트(3124584)**](http://go.microsoft.com/fwlink/?linkid=718001)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0008(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0008)

</td>
<td style="border:1px solid black;">
Windows GDI32.dll ASLR 우회 취약성

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
[CVE-2016-0009(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0009)

</td>
<td style="border:1px solid black;">
Win32k 원격 코드 실행 취약성

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
<td style="border:1px solid black;" colspan="5">
[**MS16-006: 원격 코드 실행을 해결하기 위한 Silverlight에 대한 보안 업데이트(3126036)**](http://go.microsoft.com/fwlink/?linkid=717994)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0034(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0034)

</td>
<td style="border:1px solid black;">
Silverlight 런타임 원격 코드 실행 취약성

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
[**MS16-007: 원격 코드 실행을 해결하기 위한 Microsoft Windows에 대한 보안 업데이트(3124901)**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0014(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0014)

</td>
<td style="border:1px solid black;">
DLL 로드 권한 상승 취약성

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
[CVE-2016-0015(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0015)

</td>
<td style="border:1px solid black;">
DirectShow 힙 손상 원격 코드 실행 취약성

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
[CVE-2016-0016(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0016)

</td>
<td style="border:1px solid black;">
DLL 로드 원격 코드 실행 취약성

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
[CVE-2016-0018(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0018)

</td>
<td style="border:1px solid black;">
DLL 로드 원격 코드 실행 취약성

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
[CVE-2016-0019(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0019)

</td>
<td style="border:1px solid black;">
Windows 원격 데스크톱 프로토콜 보안 우회 취약성

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
<td style="border:1px solid black;">
[CVE-2016-0020(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0020)

</td>
<td style="border:1px solid black;">
MAPI DLL 로드 권한 상승 취약성

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
<td style="border:1px solid black;" colspan="5">
[**MS16-008: 권한 상승을 해결하기 위한 Windows 커널에 대한 보안 업데이트(3124605)**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0006(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0006)

</td>
<td style="border:1px solid black;">
Windows 탑재 지점 권한 상승 취약성

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
[CVE-2016-0007(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0007)

</td>
<td style="border:1px solid black;">
Windows 탑재 지점 권한 상승 취약성

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
[**MS16-010: 스푸핑을 해결하기 위한 Microsoft Exchange Server의 보안 업데이트(3124557)**](http://go.microsoft.com/fwlink/?linkid=717997)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0029(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0029)

</td>
<td style="border:1px solid black;">
Exchange 스푸핑 취약성

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
<td style="border:1px solid black;">
[CVE-2016-0030(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0030)

</td>
<td style="border:1px solid black;">
Exchange 스푸핑 취약성

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
[CVE-2016-0031(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0031)

</td>
<td style="border:1px solid black;">
Exchange 스푸핑 취약성

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
<td style="border:1px solid black;">
[CVE-2016-0032(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0032)

</td>
<td style="border:1px solid black;">
Exchange 스푸핑 취약성

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
</table>
 

영향받는 소프트웨어
-------------------

<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.

**참고** 단일 취약성에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 ID로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

 

### Windows 운영 체제 및 구성 요소(표 1/2)

<p> </p>
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
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=717999)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/ko-kr/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                         

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7                                       
(3124275)  
(긴급)  
Internet Explorer 8  
(3124275)  
(긴급)  
Internet Explorer 9  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음                                                

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3124000)  
(긴급)  
Windows Vista 서비스 팩 2  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
(긴급)  
Internet Explorer 8  
(3124275)  
(긴급)  
Internet Explorer 9  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3124000)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(3124001)  
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
[**MS16-001**](https://technet.microsoft.com/ko-kr/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/ko-kr/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
(보통)  
Internet Explorer 8  
(3124275)  
(보통)  
Internet Explorer 9  
(3124275)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3124000)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
(보통)  
Internet Explorer 8  
(3124275)  
(보통)  
Internet Explorer 9  
(3124275)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3124000)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3124275)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3124624)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3124000)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3124001)  
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
[**MS16-001**](https://technet.microsoft.com/ko-kr/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/ko-kr/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(긴급)  
Internet Explorer 9  
(3124275)  
(긴급)  
Internet Explorer 10  
(3124275)  
(긴급)  
Internet Explorer 11  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3124000)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(긴급)  
Internet Explorer 9  
(3124275)  
(긴급)  
Internet Explorer 10  
(3124275)  
(긴급)  
Internet Explorer 11  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3124000)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3124001)  
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
[**MS16-001**](https://technet.microsoft.com/ko-kr/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/ko-kr/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(보통)  
Internet Explorer 9  
(3124275)  
(보통)  
Internet Explorer 10  
(3124275)  
(보통)  
Internet Explorer 11  
(3124275)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3124000)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3124000)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/ko-kr/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/ko-kr/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3124001)  
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
[**MS16-001**](https://technet.microsoft.com/ko-kr/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/ko-kr/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](https://technet.microsoft.com/ko-kr/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/ko-kr/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3124001)  
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
[**MS16-001**](https://technet.microsoft.com/ko-kr/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/ko-kr/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124266)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124266)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3124266)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124266)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124266)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3124266)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124263)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124263)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3124263)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124263)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124263)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3124263)  
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
[**MS16-001**](https://technet.microsoft.com/ko-kr/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](https://technet.microsoft.com/ko-kr/library/security/ms15-135)

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
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
VBScript 5.7  
(3124624)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3124000)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3124001)  
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
VBScript 5.7  
(3124624)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3124000)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3124001)  
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
VBScript 5.8  
(3124625)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3124000)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3124001)  
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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3124001)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)

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
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3124001)  
(중요)

</td>
</tr>
</table>
 
 

### Windows 운영 체제 및 구성 요소(표 2/2)

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3121918)  
(중요)  
Windows Vista 서비스 팩 2  
(3109560)  
(중요)  
Windows Vista 서비스 팩 2  
(3110329)  
(중요)  
Windows Vista 서비스 팩 2  
(3108664)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3121918)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(3109560)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(3110329)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(3108664)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3121918)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3109560)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3110329)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3108664)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3121918)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3109560)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3110329)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3108664)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3121918)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3109560)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3110329)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3108664)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3121918)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3109560)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3110329)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3121461)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3108664)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3121918)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3109560)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3110329)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3121461)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3108664)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3121918)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3109560)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3110329)  
(중요)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3108664)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3121918)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3109560)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3110329)  
(중요)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3108664)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3121918)  
(중요)  
Windows 8(32비트 시스템용)  
(3109560)  
(중요)  
Windows 8(32비트 시스템용)  
(3110329)  
(중요)  
Windows 8(32비트 시스템용)  
(3121461)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3121918)  
(중요)  
Windows 8(x64 기반 시스템용)  
(3109560)  
(중요)  
Windows 8(x64 기반 시스템용)  
(3110329)  
(중요)  
Windows 8(x64 기반 시스템용)  
(3121461)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3121918)  
(중요)  
Windows 8.1(32비트 시스템용)  
(3109560)  
(중요)  
Windows 8.1(32비트 시스템용)  
(3110329)  
(중요)  
Windows 8.1(32비트 시스템용)  
(3121461)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3121918)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(3109560)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(3110329)  
(중요)  
Windows 8.1(x64 기반 시스템용)  
(3121461)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3121918)  
(중요)  
Windows Server 2012  
(3109560)  
(중요)  
Windows Server 2012  
(3110329)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3121918)  
(중요)  
Windows Server 2012 R2  
(3109560)  
(중요)  
Windows Server 2012 R2  
(3110329)  
(중요)  
Windows Server 2012 R2  
(3121461)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3121918)  
(중요)  
Windows RT  
(3110329)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3121918)  
(중요)  
Windows RT 8.1  
(3110329)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3124266)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(3124266)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3124266)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(3124266)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3124263)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(3124263)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3124263)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(3124263)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3121918)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3121918)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3121918)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3121918)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
(3121212)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3121918)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
(3121212)  
(중요)

</td>
</tr>
</table>
 
 

### Microsoft Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2881067)  
(중요)  
Microsoft Office 2007 서비스 팩 3  
(3114541)  
(긴급)  
Microsoft Excel 2007 서비스 팩 3  
(3114540)  
(중요)  
Microsoft PowerPoint 2007 서비스 팩 3  
(3114429)  
(중요)  
Microsoft Visio 2007 서비스 팩 3  
(3114421)  
(중요)  
Microsoft Word 2007 서비스 팩 3  
(3114549)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2881029)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3114553)  
(긴급)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3114554)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(32비트 버전)  
(3114564)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(32비트 버전)  
(3114396)  
(중요)  
Microsoft Visio 2010 서비스 팩 2(32비트 버전)  
(3114402)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(3114557)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3114553)  
(긴급)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3114554)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3114564)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(64비트 버전)  
(3114564)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(64비트 버전)  
(3114396)  
(중요)  
Microsoft Visio 2010 서비스 팩 2(64비트 버전)  
(3114402)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(3114557)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(3039794)  
(중요)  
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(3114486)  
(긴급)  
Microsoft Excel 2013 서비스 팩 1(32비트 버전)  
(3114504)  
(중요)  
Microsoft PowerPoint 2013 서비스 팩 1(32비트 버전)  
(3114482)  
(중요)  
Microsoft Visio 2013 서비스 팩 1(32비트 버전)  
(3114489)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(3114494)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(3114486)  
(긴급)  
Microsoft Excel 2013 서비스 팩 1(64비트 버전)  
(3114504)  
(중요)  
Microsoft PowerPoint 2013 서비스 팩 1(64비트 버전)  
(3114482)  
(중요)  
Microsoft Visio 2013 서비스 팩 1(64비트 버전)  
(3114489)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(3114494)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1  
(3114486)  
(긴급)  
Microsoft Excel 2013 RT 서비스 팩 1  
(3114504)  
(중요)  
Microsoft PowerPoint 2013 RT 서비스 팩 1  
(3114482)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(3114494)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016(32비트 버전)  
(2920727)  
(중요)  
Microsoft Office 2016(32비트 버전)  
(3114527)  
(긴급)  
Microsoft Excel 2016(32비트 버전)  
(3114520)  
(중요)  
Microsoft PowerPoint 2016(32비트 버전)  
(3114518)  
(중요)  
Microsoft Visio 2016(32비트 버전)  
(3114511)  
(중요)  
Microsoft Word 2016(32비트 버전)  
(3114526)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)  
(3114527)  
(긴급)  
Microsoft Office 2016(64비트 버전)  
(3114520)  
(중요)  
Microsoft Excel 2016(64비트 버전)  
(3114520)  
(중요)  
Microsoft PowerPoint 2016(64비트 버전)  
(3114518)  
(중요)  
Microsoft Visio 2016(64비트 버전)  
(3114511)  
(중요)  
Microsoft Word 2016(64비트 버전)  
(3114526)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3133699)  
(긴급)  
Microsoft PowerPoint for Mac 2011  
(3133699)  
(긴급)  
Microsoft Word for Mac 2011  
(3133699)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3133711)  
(긴급)  
Mac용 Microsoft PowerPoint 2016  
(3133711)  
(긴급)  
Mac용 Microsoft Word 2016  
(3133711)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**기타 Office 소프트웨어**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3114546)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114547)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114569)  
(긴급)

</td>
</tr>
</table>
 
**MS16-004 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Microsoft 개발자 도구 및 소프트웨어

<p> </p>
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
[**MS16-006**](http://go.microsoft.com/fwlink/?linkid=717994)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**                                                     

</td>
<td style="border:1px solid black;">
[**긴급**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Mac에 설치된 Microsoft Silverlight 5  
(3126036)  
(긴급)  
Mac에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3126036)  
(긴급)  
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5  
(3126036)  
(긴급)  
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3126036)  
(긴급)  
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5  
(3126036)  
(긴급)  
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5 Developer 런타임  
(3126036)  
(긴급)

</td>
</tr>
</table>
 
 

### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 서비스 팩 1  
(3114503)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 서비스 팩 1  
(3124557)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 10  
(3124557)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 11  
(3124557)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016  
(3124557)  
(중요)

</td>
</tr>
</table>
 
**MS16-004 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

### Microsoft Visual Basic 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Visual Basic 6.0 Runtime**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](https://technet.microsoft.com/ko-kr/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**(영문)](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Basic 6.0 Runtime

</td>
<td style="border:1px solid black;">
Visual Basic 6.0 Runtime  
(3096896)  
(중요)

</td>
</tr>
</table>
 
**MS16-004 참고 사항**

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
Microsoft는 신뢰할 수 있는 취약성 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/dn903755.aspx)(영문)을 참조하십시오.

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 릴리스에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services 및 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 릴리스에서 제공되지 않습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft Update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/ko-kr/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services용으로 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/windowsserver/bb332157.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 재출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약성 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://technet.microsoft.com/ko-kr/security/dn467918)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://technet.microsoft.com/ko-kr/library/bb466251.aspx)(영문)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

**기타 보안 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 제공됩니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/ko-kr/download/search.aspx?q=security%20update)에서 제공됩니다. "보안 업데이트"라는 키워드 검색을 수행하면 가장 쉽게 찾을 수 있습니다.
-   소비자 플랫폼용 업데이트는 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)에서 제공됩니다.
-   이달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 긴급 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/ko-kr/kb/913086)을 참조하십시오.

**IT 전문가 보안 커뮤니티**

[IT 전문가 보안 커뮤니티](http://technet.microsoft.com/ko-kr/security/cc136632.aspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 알아보고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향받는 소프트웨어는 테스트를 거쳐 영향받는 버전이 확인되었습니다. 다른 버전은 지원 주기가 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 주기를 확인하려면 [Microsoft 지원 주기](https://support.microsoft.com/ko-kr/lifecycle)를 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/ko-kr/security/bb980617)

Windows 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ko)

각 지역의 국가별 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx?ln=ko)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한이 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2016년 1월 13일): 공지 요약이 게시되었습니다.

*2016-01-07 13:56-08:00에 페이지가 생성되었습니다.*
