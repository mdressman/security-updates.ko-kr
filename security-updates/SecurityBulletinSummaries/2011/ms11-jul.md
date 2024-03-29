---
TOCTitle: 'MS11-JUL'
Title: 2011 년 7 월 Microsoft 보안 공지 요약
ms:assetid: 'ms11-jul'
ms:contentKeyID: 61230737
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms11-jul(v=Security.10)'
---


2011 년 7 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2011년 7월 13일 수요일

**버전:** 1.0

이 공지 요약 목록에는 2011년 7월에 발표된 보안 공지가 포함되어 있습니다.

2011년 7월 보안 공지 발표와 함께 이 공지 요약이 2011년 7월 7일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2011년 7월 13일 수요일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [7월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032487855&eventcategory=4). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://go.microsoft.com/fwlink/?linkid=217214) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

요약
----

다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어 및 다운로드 위치** 를 참조하십시오.

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-053">MS11-053</a></td>
<td style="border:1px solid black;"><strong>Bluetooth 스택의 취약점으로 인한 원격 코드 실행 문제점(2566220)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Windows Bluetooth 스택의 취약점을 해결합니다. 공격자가 영향을 받는 시스템에 특수하게 조작된 일련의 Bluetooth 패킷을 보낼 경우 이 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 이 취약점은 Bluetooth 기능을 사용하는 시스템에만 영향을 줍니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-054">MS11-054</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버의 취약점으로 인한 권한 상승 문제점(2555917)</strong>  <br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 15건을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 시스템에 로컬로 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-056">MS11-056</a></td>
<td style="border:1px solid black;"><strong>Windows CSRSS(Client/Server Runtime Subsystem)의 취약점으로 인한 권한 상승 문제점(2507938)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 CSRSS(Microsoft Windows Client/Server Run-time Subsystem)의 취약점 5건을 해결합니다. 공격자가 사용자의 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 이 취약점으로 인해 권한 상승이 허용될 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-055">MS11-055</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio의 취약점으로 인한 원격 코드 실행 문제점(2560847)</strong><br />
<br />
이 보안 업데이트는 Microsoft Visio의 공개된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 라이브러리 파일과 동일한 네트워크 디렉터리에 있는 합법적인 Visio 파일을 열 경우 원격 코드 실행이 허용될 수 있습니다. 취약점 악용에 성공한 공격자는 로그온한 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이 달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/security/cc998259.aspx)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 버전"은 관련 소프트웨어를 나타내며 "이전 소프트웨어 버전"은 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 버전을 나타냅니다.
  
| 공지 번호                                                           | 취약점 제목                                            | CVE ID                                                                                  | 최신 소프트웨어 버전에 대한 코드 실행 악용 가능성 평가                               | 이전 소프트웨어 버전에 대한 코드 실행 악용 가능성 평가                               | 서비스 거부 악용 가능성 평가 | 주요 정보                                                                                                                 |  
|---------------------------------------------------------------------|--------------------------------------------------------|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|------------------------------|---------------------------------------------------------------------------------------------------------------------------|  
| [MS11-053](http://technet.microsoft.com/security/bulletin/ms11-053) | Bluetooth 스택 취약점                                  | [CVE-2011-1265 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1265) | [2](http://technet.microsoft.com/security/cc998259.aspx) – 비일관적인 악용 코드 가능 | [2](http://technet.microsoft.com/security/cc998259.aspx) – 비일관적인 악용 코드 가능 | 영구                         | 이 취약점은 Bluetooth 기능을 사용하는 클라이언트 시스템(지원 대상인 Windows Vista 및 Windows 7 릴리스)에만 영향을 줍니다. |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 해제 후 사용 취약점                             | [CVE-2011-1874 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1874) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 해제 후 사용 취약점                             | [CVE-2011-1875 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1875) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 해제 후 사용 취약점                             | [CVE-2011-1876 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1876) | [2](http://technet.microsoft.com/security/cc998259.aspx) – 비일관적인 악용 코드 가능 | [2](http://technet.microsoft.com/security/cc998259.aspx) – 비일관적인 악용 코드 가능 | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 해제 후 사용 취약점                             | [CVE-2011-1877 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1877) | [2](http://technet.microsoft.com/security/cc998259.aspx) – 비일관적인 악용 코드 가능 | [2](http://technet.microsoft.com/security/cc998259.aspx) – 비일관적인 악용 코드 가능 | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 해제 후 사용 취약점                             | [CVE-2011-1878 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1878) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 해제 후 사용 취약점                             | [CVE-2011-1879 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1879) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 포인터 역참조 취약점                       | [CVE-2011-1880 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1880) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 포인터 역참조 취약점                       | [CVE-2011-1881 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1881) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 해제 후 사용 취약점                             | [CVE-2011-1882 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1882) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 해제 후 사용 취약점                             | [CVE-2011-1883 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1883) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 해제 후 사용 취약점                             | [CVE-2011-1884 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1884) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 포인터 역참조 취약점                       | [CVE-2011-1885 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1885) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k 잘못된 매개 변수로 인한 정보 유출 취약점        | [CVE-2011-1886 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1886) | [3](http://technet.microsoft.com/security/cc998259.aspx) – 악용 코드 기능 불가능     | [3](http://technet.microsoft.com/security/cc998259.aspx) – 악용 코드 기능 불가능     | 영구                         | 이는 정보 유출 취약점입니다.                                                                                              |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 포인터 역참조 취약점                       | [CVE-2011-1887 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1887) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-054](http://technet.microsoft.com/security/bulletin/ms11-054) | Win32k Null 포인터 역참조 취약점                       | [CVE-2011-1888 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1888) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-055](http://technet.microsoft.com/security/bulletin/ms11-055) | Microsoft Visio의 안전하지 않은 라이브러리 로드 취약점 | [CVE-2010-3148 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3148) | 영향 받지 않음                                                                       | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 해당 사항 없음               | 이 취약점은 공개되었습니다.                                                                                               |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 로컬 EOP AllocConsole 취약점                     | [CVE-2011-1281 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1281) | [3](http://technet.microsoft.com/security/cc998259.aspx) – 악용 코드 기능 불가능     | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 해당 사항 없음               | (없음)                                                                                                                    |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 로컬 EOP SrvSetConsoleLocalEUDC 취약점           | [CVE-2011-1282 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1282) | [3](http://technet.microsoft.com/security/cc998259.aspx) – 악용 코드 기능 불가능     | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 로컬 EOP SrvSetConsoleNumberOfCommand 취약점     | [CVE-2011-1283 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1283) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 로컬 EOP SrvWriteConsoleOutput 취약점            | [CVE-2011-1284 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1284) | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |  
| [MS11-056](http://technet.microsoft.com/security/bulletin/ms11-056) | CSRSS 로컬 EOP SrvWriteConsoleOutputString 취약점      | [CVE-2011-1870 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1870) | [3](http://technet.microsoft.com/security/cc998259.aspx) – 악용 코드 기능 불가능     | [1](http://technet.microsoft.com/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 영구                         | (없음)                                                                                                                    |
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
#### Windows 운영 체제 및 구성 요소

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=d7a47370-f415-46ea-9a82-a943f743c8b6&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=425c705e-94f2-4fa6-9df2-dc71897215fa&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=db89d88f-d0d4-4ed6-8589-bf27557c0304)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c389fa20-677e-49b6-af44-781e5522d08b)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7a26a437-a705-4d48-8389-50f159a39891&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=dff4c67a-8c8b-4d7d-84c7-57429becf0ff&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=95393f89-0b05-4243-95ed-17bcdad24bfb&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1615a995-9a04-440a-ae52-5917738f0ecb&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3b094bdb-4150-44f2-a638-afd5f41b00a3)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=a81c011d-eeea-4383-9efb-df70515ab357)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=6bff74ac-45f3-4585-92da-316921b458fa&displaylang=ko)<sup>[1]</sup>
(KB2561109)  
(긴급)  
[Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a1e5aa7d-5f38-4ce2-9575-4b4cb7520160&displaylang=ko)  
(KB2532531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c1fe1e53-34d5-497e-8ba2-50caa8dc1158&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a5e192af-dae5-47ef-a9d0-f761a8caa974&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=849d2694-c8b3-4670-8203-912661bccabf&displaylang=ko)<sup>[1]</sup>
(KB2561109)  
(긴급)  
[Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4287eeb4-ab29-4727-83f2-260d838b44d4&displaylang=ko)  
(KB2532531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7bc0a285-cc32-4c6b-abee-d92130d459b7&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1007f5d3-9be1-4f03-a3f0-12ddb555653c&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b88d0471-4427-4835-9446-db71116481f0&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=36e3dbaf-36f5-4c74-8f11-ecbef46f58e1&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d3df6184-3e3c-4949-a1ee-293ec68f8149&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b43d2ab5-e281-4c6b-bb37-1f1b5d86ac82&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9e021d69-7f0c-457f-af86-07e760d8f421)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b70209f2-1c51-45af-b3c4-3473aebcdb35)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
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
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7f811b75-c3ff-411a-aaa9-126dce34cc01&displaylang=ko)  
(KB2532531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=41db1b2f-f862-43bb-89bc-4b97737e5cb9&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용) 및 Windows 7(32비트 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac3b435c-8caf-40cc-8f13-b52261b3b9e6&displaylang=ko)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=90b2da71-18f9-46ee-9e3d-b08620ca06aa&displaylang=ko)  
(KB2532531)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=211abdc6-40c7-4bfc-8c2d-be72981f311e&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용) 및 Windows 7(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=64e5f889-fa46-4884-9b22-3ba4e2fba1b9&displaylang=ko)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://technet.microsoft.com/security/bulletin/ms11-053)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://technet.microsoft.com/security/bulletin/ms11-054)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://technet.microsoft.com/security/bulletin/ms11-056)
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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=4f54e498-3825-407d-a036-1900a65d34f1&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용) 및 Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=b99a40cf-8a31-43d9-bd0b-a458a533068b&displaylang=ko)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=e7ae39e8-1154-4a13-8598-29d4a6358762)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용) 및 Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=784efc20-3a41-42ab-b48d-51fd59d71523)  
(중요)
</td>
</tr>
</table>
 
**Windows Server 2008 및 Windows Server 2008 R2 참고 사항**

**\*Server Core 설치가 영향을 받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 TechNet 문서, [Server Core 설치 관리](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)(영문) 및 [Server Core 설치 서비스](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)(영문)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션에 따른 버전 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오.

**MS11-053 참고 사항**

<sup>[1]</sup>Windows Vista 서비스 팩 1은 선택적인 Windows Vista Feature Pack for Wireless가 설치되어 있을 때만 영향을 받습니다.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office 제품군 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS11-055**](http://technet.microsoft.com/security/bulletin/ms11-055)
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
Microsoft Visio 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=1c7b2a5b-4aa6-4006-90bf-89f8b2b7becd&displaylang=ko)  
(KB2493523)  
(중요)
</td>
</tr>
</table>
 

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

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services (영문)](http://technet.microsoft.com/en-us/wsus/default.aspx)를 참조하십시오.

**System Center Configuration Manager 2007**

Configuration Manager 2007 소프트웨어 업데이트 관리는 기업 전체의 IT 시스템에 대한 복잡한 업데이트 제공 및 관리 작업을 단순화합니다. Configuration Manager 2007을 사용하면 IT 관리자가 데스크톱, 랩톱, 서버 및 모바일 장치를 비롯한 다양한 장치에 Microsoft 제품의 업데이트를 제공할 수 있습니다.

Configuration Manager 2007의 자동화된 취약점 평가를 통해 업데이트 및 권장 조치에 대한 보고 필요성을 확인할 수 있습니다. Configuration Manager 2007의 소프트웨어 업데이트 관리는 전세계 IT 관리자에게 친숙한 테스트된 업데이트 인프라인 Microsoft WSUS(Windows Software Update Services)를 기반으로 합니다. 관리자가 Configuration Manager 2007을 사용하여 업데이트를 배포하는 방법에 대한 자세한 내용은 [소프트웨어 업데이트 관리](http://www.microsoft.com/systemcenter/ko/kr/configuration-manager/cm-software-update-management.aspx)를 참조하십시오. Configuration Manager에 대한 자세한 내용을 보려면 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/ko/kr/configuration-manager.aspx)를 방문하십시오.

**Systems Management Server 2003**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다.

**참고** System Management Server 2003은 2010년 1월 12일자로 메인스트림 지원이 종료되었습니다. 제품 지원 기간에 대한 자세한 내용을 보려면 [Microsoft 지원 기간](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) 웹 사이트를 참조하십시오. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다(이전 섹션의 **System Center Configuration Manager 2007** 참조).

관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [Microsoft Systems Management Server 2003의 시나리오 및 절차: 소프트웨어 배포 및 패치 관리](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)를 참조하십시오. SMS에 대한 자세한 내용을 보려면 [Microsoft Systems Management Server TechCenter (영문)](http://technet.microsoft.com/systemcenter/bb545936.aspx)를 방문하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet.microsoft.com/library/cc766043(ws.10).aspx) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트 (영문)](http://technet.microsoft.com/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](http://go.microsoft.com/fwlink/?linkid=215201)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS11-054에서 설명한 14개의 문제점을 보고해 주신 [Norman (영문)](http://www.norman.com)의 Tarjei Mandt
-   MS11-054에서 설명한 문제점을 보고해 주신 [Department of Information Security, Beijing University (영문)](http://www.ss.pku.edu.cn/en/)의 Mr. Liang Yin, Prof. Sihan Qing 및 Weiping Wen, Mr. Husheng Zhou
-   MS11-056에서 설명한 5가지 문제점을 보고해 주신 [Hispasec (영문)](http://www.hispasec.com/)[Virustotal (영문)](http://www.virustotal.com/)의 Matthew ''j00ru' Jurczyk

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원 (영문)](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2011년 7월 13일): 공지 요약이 게시되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
