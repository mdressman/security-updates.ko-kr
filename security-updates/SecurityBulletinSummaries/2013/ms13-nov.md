---
TOCTitle: 'MS13-NOV'
Title: 2013 년 11 월 Microsoft 보안 공지 요약
ms:assetid: 'ms13-nov'
ms:contentKeyID: 61230766
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms13-nov(v=Security.10)'
---

2013 년 11 월 Microsoft 보안 공지 요약
======================================

게시된 날짜: 2013년 11월 13일 수요일

**버전:** 1.0

이 공지 요약 목록에는 2013년 11월에 발표된 보안 공지가 포함되어 있습니다.

2013년 11월 보안 공지 발표와 함께 이 공지 요약이 2013년 11월 8일에 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://go.microsoft.com/fwlink/?linkid=217213)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2013년 11월 13일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행합니다. [11월 보안 공지 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557383&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 누적 보안 업데이트(2888505)<br />
<br />
이 보안 업데이트는 Internet Explorer에서 발견되어 비공개적으로 보고된 취약점 10건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 가장 위험한 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325390">MS13-089</a></td>
<td style="border:1px solid black;">Windows 그래픽 장치 인터페이스의 취약점으로 인한 원격 코드 실행 문제점(2876331)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 WordPad에서 특수하게 조작된 Windows Write 파일을 보거나 열 경우 원격 코드 실행이 발생할 수 있습니다. 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329834">MS13-090</a></td>
<td style="border:1px solid black;">ActiveX 킬(Kill) 비트 누적 보안 업데이트(2900986)<br />
<br />
이 보안 업데이트는 현재 악용되고 있는 비공개적으로 보고된 취약점 1건을 해결합니다. InformationCardSigninHelper Class ActiveX 컨트롤에 취약점이 존재합니다. 이 취약점으로 인해 사용자가 Internet Explorer를 사용하여 ActiveX 컨트롤의 인스턴스를 만드는 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 발생할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점(2885093)<br />
<br />
이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 3건을해결합니다. 취약점으로 인해 영향을 받는 Microsoft Office 소프트웨어 버전에서 특수하게 조작된 WordPerfect 문서 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 가장 위험한 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324692">MS13-092</a></td>
<td style="border:1px solid black;">Hyper-V의 취약점으로 인한 권한 상승 문제점(2893986)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 기존의 실행 중인 가상 컴퓨터에서 하이퍼바이저로 Hypercall의 특수하게 조작된 함수 매개 변수를 전달할 경우 권한 상승이 허용될 수 있습니다. 또한 이 취약점으로 인해 공격자가 기존의 실행 중인 가상 컴퓨터에서 하이퍼바이저로 Hypercall의 특수하게 조작된 함수 매개 변수를 전달할 경우 Hyper-V 호스트에서 서비스 거부가 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325391">MS13-093</a></td>
<td style="border:1px solid black;">Windows Ancillary Function Driver의 취약점으로 인한 정보 유출 문제점(2875783)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 공격자가 영향을 받는 시스템에 로컬 사용자로 로그온하고 시스템에서 더 높은 권한을 가진 계정으로부터 정보를 얻을 수 있도록 설계된 특수하게 조작된 응용 프로그램을 실행할 경우 정보 유출이 발생할 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324873">MS13-094</a></td>
<td style="border:1px solid black;">Microsoft Outlook의 취약점으로 인한 정보 유출 문제점(2894514)<br />
<br />
이 보안 업데이트는 Microsoft Outlook의 공개된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 영향을 받는 Microsoft Outlook 에디션에서 특수하게 조작된 전자 메일 메시지를 열거나 미리 볼 때 정보가 유출될 수 있습니다. 이 취약점 악용에 성공한 공격자는 대상 시스템 및 대상 시스템과 네트워크를 공유하는 다른 시스템에서 IP 주소 및 열린 TCP 포트와 같은 시스템 정보를 확인할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
정보 유출</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320632">MS13-095</a></td>
<td style="border:1px solid black;">디지털 서명의 취약점으로 인한 서비스 거부 문제점(2868626)<br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 영향을 받는 웹 서비스가 특수하게 조작된 X.509 인증서를 처리할 때 서비스 거부가 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3871">CVE-2013-3871</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3908">CVE-2013-3908</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3909">CVE-2013-3909</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3910">CVE-2013-3910</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3911">CVE-2013-3911</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3912">CVE-2013-3912</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3914">CVE-2013-3914</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3915">CVE-2013-3915</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3916">CVE-2013-3916</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3917">CVE-2013-3917</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - 악용 코드를 작성하기 어려움</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325390">MS13-089</a></td>
<td style="border:1px solid black;">그래픽 장치 인터페이스 정수 오버플로 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3940">CVE-2013-3940</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329834">MS13-090</a></td>
<td style="border:1px solid black;">InformationCardSigninHelper 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3918">CVE-2013-3918</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">Microsoft는 이 취약점을 악용하려는 제한적이며 대상이 일정한 공격에 대한 보고를 받았습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">WPD 파일 형식 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0082">CVE-2013-0082</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Word 스택 버퍼 덮어쓰기 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1324">CVE-2013-1324</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Word 힙 덮어쓰기 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1325">CVE-2013-1325</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324692">MS13-092</a></td>
<td style="border:1px solid black;">주소 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3898">CVE-2013-3898</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - 악용 코드 가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325391">MS13-093</a></td>
<td style="border:1px solid black;">Ancillary Function Driver 정보 유출 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3887">CVE-2013-3887</a></td>
<td style="border:1px solid black;">영향 받지 않음</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324873">MS13-094</a></td>
<td style="border:1px solid black;">S/MIME AIA 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3905">CVE-2013-3905</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">해당 사항 없음</td>
<td style="border:1px solid black;">이는 정보 유출 취약점입니다.<br />
<br />
이 취약점은 공개되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320632">MS13-095</a></td>
<td style="border:1px solid black;">디지털 서명 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3869">CVE-2013-3869</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 악용 코드 불가능</td>
<td style="border:1px solid black;">임시</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
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
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
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
없음[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(긴급)  
Internet Explorer 7   
(2888505)  
(긴급)  
Internet Explorer 8   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(긴급)  
Internet Explorer 7   
(2888505)  
(긴급)  
Internet Explorer 8   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2  
(2868626)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(중요)  
Internet Explorer 7  
(2888505)  
(중요)  
Internet Explorer 8  
(2888505)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(중요)  
Internet Explorer 7  
(2888505)  
(중요)  
Internet Explorer 8  
(2888505)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(2868626)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2888505)  
(중요)  
Internet Explorer 7  
(2888505)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(2868626)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
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
없음[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(긴급)  
Internet Explorer 8  
(2888505)  
(긴급)  
Internet Explorer 9   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(2868626)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(긴급)  
Internet Explorer 8  
(2888505)  
(긴급)  
Internet Explorer 9   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(2868626)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(중요)  
Internet Explorer 8  
(2888505)  
(중요)  
Internet Explorer 9   
(2888505)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(2868626)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(중요)  
Internet Explorer 8  
(2888505)  
(중요)  
Internet Explorer 9   
(2888505)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(2868626)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
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
없음[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(긴급)  
Internet Explorer 9   
(2888505)  
(긴급)  
Internet Explorer 10   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(긴급)  
Internet Explorer 9   
(2888505)  
(긴급)  
Internet Explorer 10   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(2868626)  
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
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(중요)  
Internet Explorer 9   
(2888505)  
(중요)  
Internet Explorer 10   
(2888505)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(2868626)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows 8 및 Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(Pro 및 Enterprise 에디션에만 적용)  
(2893986)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(2868626)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(2868626)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2012 및 Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
전체 심각도
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[긴급](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[보통](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2888505)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Standard 및 Datacenter 에디션, Hyper-V Server 2012에만 적용)  
(2893986)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2888505)  
(보통)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2900986)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2868626)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows RT 및 Windows RT 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
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
없음[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows RT  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows RT  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows RT  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2888505)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2900986)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2868626)  
(중요)
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
[MS13-088](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[MS13-089](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[MS13-090](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[MS13-092](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[MS13-093](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[MS13-095](http://go.microsoft.com/fwlink/?linkid=320632)
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
<td style="border:1px solid black;">
없음[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[중요](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
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
(2876331)  
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(2868626)  
(중요)
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
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(2868626)  
(중요)
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
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(2868626)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2876331)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2893986)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2875783)  
(중요)
</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(2868626)  
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
Windows Server 2012 R2(Server Core 설치)  
(2876331)  
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
Windows Server 2012 R2(Server Core 설치)  
(2868626)  
(중요)
</td>
</tr>
</table>
 

#### Microsoft Office 제품군 및 소프트웨어

<p> </p>
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-091](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[MS13-094](http://go.microsoft.com/fwlink/?linkid=324873)
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
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3  
(파일 형식 변환기)  
(2760494)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-091](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[MS13-094](http://go.microsoft.com/fwlink/?linkid=324873)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(파일 형식 변환기)  
(2760415)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2007 서비스 팩 3  
(2825644)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-091](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[MS13-094](http://go.microsoft.com/fwlink/?linkid=324873)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(파일 형식 변환기)  
(2553284)  
(중요)  
Microsoft Office 2010 서비스 팩 1(32비트 에디션)  
(맞춤법 검사 도구)  
(2760781)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 서비스 팩 1(32비트 에디션)  
(2837597)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 에디션)  
(파일 형식 변환기)  
(2553284)  
(심각도 없음)  
Microsoft Office 2010 서비스 팩 2(32비트 에디션)  
(맞춤법 검사 도구)  
(2760781)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 서비스 팩 2(32비트 에디션)  
(2837597)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(파일 형식 변환기)  
(2553284)  
(중요)  
Microsoft Office 2010 서비스 팩 1(64비트 에디션)  
(맞춤법 검사 도구)  
(2760781)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 서비스 팩 1(64비트 에디션)  
(2837597)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 에디션)  
(파일 형식 변환기)  
(2553284)  
(심각도 없음)  
Microsoft Office 2010 서비스 팩 2(64비트 에디션)  
(맞춤법 검사 도구)  
(2760781)  
(심각도 없음)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 서비스 팩 2(64비트 에디션)  
(2837597)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
공지 번호
</td>
<td style="border:1px solid black;">
[MS13-091](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[MS13-094](http://go.microsoft.com/fwlink/?linkid=324873)
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
[중요](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 에디션)  
(파일 형식 변환기)  
(2768005)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013(32비트 에디션)  
(2837618)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 에디션)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 에디션)  
(파일 형식 변환기)  
(2768005)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013(64비트 에디션)  
(2837618)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(파일 형식 변환기)  
(2768005)  
(중요)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 RT   
(2837618)  
(중요)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------

<span></span>
관리자가 보안 업데이트를 배포하는 데 도움이 되는 다양한 리소스가 존재합니다.

-   관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 구성 오류를 검색할 수 있습니다.
-   WSUS(Windows Server Update Services), SMS(Systems Management Server), System Center Configuration Manager는 관리자가 보안 업데이트를 배포하는 데 도움이 됩니다.
-   ACT(Application Compatibility Toolkit)에 포함되어 있는 UCE(Update Compatibility Evaluator) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사가 간소화됩니다.

여기에 나온 도구 및 사용 가능한 기타 도구에 대한 자세한 내용은 [보안 도구](http://technet.microsoft.com/security/cc297183)를 참조하십시오.

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

MS13-088

-   Internet Explorer 메모리 손상 취약점(CVE-2013-3871)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 Simon Zuckerbraun
-   Internet Explorer 정보 유출 취약점(CVE-2013-3908)을 보고해 주신 Masato Kinugawa
-   Internet Explorer 정보 유출 취약점(CVE-2013-3909)을 보고해 주신 Sergey Markov
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3910)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Corelan](http://www.corelangcv.com/)(영문)의 Peter 'corelanc0d3r' Van Eeckhoutte
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3911)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 [Harmony Security](http://www.harmonysecurity.com/)(영문)의 Stephen Fewer
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3912)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의[Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 lokihardt@ASRT
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3914)을 [VeriSign iDefense Labs](http://labs.idefense.com)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3915)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3916)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3917)을 [HP](http://www8.hp.com/kr/ko/software-solutions/software.html?compuri=1214365)의 [Zero Day Initiative](http://www.zerodayinitiative.com/)(영문)와 협력하여 보고해 주신 익명 연구자
-   Internet Explorer 메모리 손상 취약점(CVE-2013-3917)을 보고해 주신 [Palo Alto Networks](http://www.paloaltonetworks.com/)(영문)의 Bo Qu

MS13-089

-   그래픽 장치 인터페이스 정수 오버플로 취약점(CVE-2013-3940)을 보고해 주신 [Secunia Research](http://secunia.com/)(영문)의 Hossein Lotfi

MS13-090

-   InformationCardSigninHelper 취약점(CVE-2013-3918)을 보고해 주신 [Cyber Defense Institute, Inc.](http://www.cyberdefense.jp/)(일문)의 ucq 및 Daiki Fukumori
-   InformationCardSigninHelper 취약점(CVE-2013-3918)에 대해 Microsoft와 협력해 주신 [iSIGHT Partners](http://www.isightpartners.com/)(영문)
-   InformationCardSigninHelper 취약점(CVE-2013-3918)에 대해 Microsoft와 협력해 주신 [FireEye](http://www.fireeye.com/)(영문)의 Dan Caselden 및 Xiaobo Chen

MS13-091

-   WPD 파일 형식 메모리 손상 취약점(CVE-2013-0082)을 보고해 주신 Merliton
-   Word 스택 버퍼 덮어쓰기 취약점(CVE-2013-1324)을 보고해 주신 [CERT/CC](http://www.cert.org/)(영문)의 Will Dormann
-   Word 힙 덮어쓰기 취약점(CVE-2013-1325)을 보고해 주신 [CERT/CC](http://www.cert.org/)(영문)의 Will Dormann

MS13-092

-   주소 손상 취약점(CVE-2013-3898)을 Bundesamt für Sicherheit in der Informationstechnik(BSI, German Federal Office for Information Security) 대신 보고해 주신 thinktecture([www.thinktecture.com](http://www.thinktecture.com)) 및 ERNW([www.ernw.de](http://www.ernw.de), Felix Wilhelm)

MS13-094

-   S/MIME AIA 취약점(CVE-2013-3905)을 보고해 주신 [n.runs professionals GmbH](https://www.nruns.com/)(영문)의 Alexander Klink

MS13-095

-   디지털 서명 취약점(CVE-2013-3869)을 보고해 주신 [Context Information Security](http://www.contextis.com/)(영문)의 James Forshaw

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   IT 전문가를 위한 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/security/bb980617)
-   Windows를 실행하는 컴퓨터를 바이러스와 맬웨어로부터 보호: [바이러스 및 보안 솔루션 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   국가별 현지 지원: [국가별 지원](http://support.microsoft.com/common/international.aspx)

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2013년 11월 13일): 공지 요약이 게시되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
