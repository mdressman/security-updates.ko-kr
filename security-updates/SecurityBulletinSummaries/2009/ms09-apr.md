---
TOCTitle: 'MS09-APR'
Title: 2009 년 4 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-apr'
ms:contentKeyID: 61230708
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-apr(v=Security.10)'
---


2009 년 4 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2009년 4월 15일 수요일 | 업데이트된 날짜: 2009년 4월 17일 금요일

**버전:** 1.1

이 공지 요약 목록에는 2009년 4월 발표된 보안 공지가 포함되어 있습니다.

2009년 4월 공지 발표와 함께 이 공지 요약이 2009년 4월 9일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2009년 4월 15일 수요일(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [4월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395126). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-010">MS09-010</a></td>
<td style="border:1px solid black;"><strong>WordPad 및 Office 텍스트 변환기의 취약점으로 인한 원격 코드 실행 문제점 (960477)</strong><br />
<br />
이 보안 업데이트는 Microsoft WordPad 및 Microsoft Office 텍스트 변환기의 공개된 취약점 2건과 비공개로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 사용자가 WordPad 또는 Microsoft Office Word에서 특수하게 조작된 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 영향을 받는 WordPad 또는 Microsoft Office Word 버전을 사용하여 신뢰할 수 없는 출처의 Microsoft Office, RTF, Write 또는 WordPerfect 파일을 열지 마십시오.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-013">MS09-013</a></td>
<td style="border:1px solid black;"><strong>Windows HTTP Services의 취약점으로 인한 원격 코드 실행 문제점 (960803)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows HTTP Services(WinHTTP)의 공개된 취약점 1건과 비공개로 보고된 취약점 2건을 해결합니다. 가장 위험한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-011">MS09-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow의 취약점으로 인한 원격 코드 실행 문제점 (961373)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft DirectX의 취약점을 해결합니다. 취약점으로 인해 사용자가 특수하게 조작된 MJPEG 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-014">MS09-014</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트 (963027)</strong><br />
<br />
이 보안 업데이트는 Internet Explorer에 대해 비공개적으로 보고된 취약점 4건과 공개된 취약점 2건을 해결합니다. 이 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 보거나 HTTP 프로토콜을 사용하여 공격자의 서버에 연결할 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-009">MS09-009</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel의 취약점으로 인한 원격 코드 실행 문제점 (968557)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 1건과 공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 Excel 파일을 열면 원격 코드 실행이 발생할 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템에 대해 완벽히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-012">MS09-012</a></td>
<td style="border:1px solid black;"><strong>Windows의 취약점으로 인한 권한 상승 문제점 (959454)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 공개적으로 보고된 네 가지 취약점을 해결합니다. 이 취약점으로 인해 공격자가 시스템에 로그온하고 특수하게 조작된 응용 프로그램을 실행할 경우 권한 상승이 발생할 수 있습니다. 공격자가 이 취약점을 악용하려면 로컬 컴퓨터에서 코드를 실행할 수 있어야 합니다. 이러한 취약점을 성공적으로 악용한 경우 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-016">MS09-016</a></td>
<td style="border:1px solid black;"><strong>Microsoft ISA Server 및 Forefront Threat Management Gateway(Medium Business Edition)의 취약점으로 인한 서비스 거부 문제점 (961759)</strong><br />
<br />
이 보안 업데이트는 Microsoft ISA(Internet Security and Acceleration) Server 및 Microsoft Forefront TMG(Threat Management Gateway), MBE(Medium Business Edition)에 대해 비공개적으로 보고된 취약점과 일반에 공개된 취약점을 해결합니다. 이러한 취약점으로 인해 공격자는 영향을 받는 시스템에 특수하게 조작된 네트워크 패킷을 보내 서비스 거부를 유발할 수 있으며 사용자가 악의적인 URL을 클릭하거나 공격자가 제어하는 콘텐츠가 포함된 웹 사이트를 방문하는 경우 정보 유출이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Forefront Edge Security</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-015">MS09-015</a></td>
<td style="border:1px solid black;"><strong>SearchPath의 혼합 보안 위협 취약점으로 인한 권한 상승 문제점 (959426)</strong><br />
<br />
이 보안 업데이트는 Windows SearchPath 기능에서 발견되어 일반에 공개된 취약점을 해결합니다. 사용자가 특수하게 조작된 파일을 특정 위치에 다운로드한 후에 특정 상황에서 해당 파일을 로드할 수 있는 응용 프로그램을 여는 경우 권한 상승을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">보통</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 공지 제목                                                                                                                         | CVE ID                                                                                      | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                                                                                                                                                |  
|---------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-009](http://technet.microsoft.com/security/bulletin/ms09-009) | Microsoft Office Excel의 취약점으로 인한 원격 코드 실행 문제점(968557)                                                            | [CVE-2009-0100 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0100)     | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                   |  
| [MS09-009](http://technet.microsoft.com/security/bulletin/ms09-009) | Microsoft Office Excel의 취약점으로 인한 원격 코드 실행 문제점(968557)                                                            | [CVE-2009-0238 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0238)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.**                                                                                                                                                                |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | WordPad 및 Office 텍스트 변환기의 취약점으로 인한 원격 코드 실행 문제점(960477)                                                   | [CVE-2008-4841 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4841)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.**                                                                                                                                                                |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | WordPad 및 Office 텍스트 변환기의 취약점으로 인한 원격 코드 실행 문제점(960477)                                                   | [CVE-2009-0087 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0087)     | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 이는 여러 코드 경로로 인해 발생하는 복합 취약점입니다. 대부분의 악용 코드는 비일관적인 결과를 반환합니다. 기본 완화 요소가 이 공격 경로를 방지합니다.                                                                    |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | WordPad 및 Office 텍스트 변환기의 취약점으로 인한 원격 코드 실행 문제점(960477)                                                   | [CVE-2009-0088 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0088)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 취약점은 악용되고 있지만 이전 버전의 특수 파일 형식에만 영향을 줍니다. 2007 Microsoft Office System 및 Microsoft Office 2003 서비스 팩 3과 같은 최신 버전은 영향을 받지 않습니다.                                     |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | WordPad 및 Office 텍스트 변환기의 취약점으로 인한 원격 코드 실행 문제점(960477)                                                   | [CVE-2009-0235 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0235)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 메모리 손상 취약점은 쉽게 악용할 수 있습니다.                                                                                                                                                                         |  
| [MS09-011](http://technet.microsoft.com/security/bulletin/ms09-011) | Microsoft DirectShow의 취약점으로 인한 원격 코드 실행 문제점(961373)                                                              | [CVE-2009-0084 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0084)     | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                   |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Windows의 취약점으로 인한 권한 상승 문제점(959454)                                                                                | [CVE-2008-1436 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-1436)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.**                                                                                                                                                                |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Windows의 취약점으로 인한 권한 상승 문제점(959454)                                                                                | [CVE-2009-0078 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0078)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.**                                                                                                                                                                |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Windows의 취약점으로 인한 권한 상승 문제점(959454)                                                                                | [CVE-2009-0079 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0079)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.**                                                                                                                                                                |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Windows의 취약점으로 인한 권한 상승 문제점(959454)                                                                                | [CVE-2009-0080 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0080)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.**                                                                                                                                                                |  
| [MS09-013](http://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP Services의 취약점으로 인한 원격 코드 실행 문제점(960803)                                                             | [CVE-2009-0086 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0086)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 이 기술은 널리 유포되어 있으므로 공격자는 여러 공격 경로 및 악용 기회를 통해 메모리 취약점을 손쉽게 제어할 수 있습니다.                                                                                                  |  
| [MS09-013](http://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP Services의 취약점으로 인한 원격 코드 실행 문제점(960803)                                                             | [CVE-2009-0089 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0089)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (None)                                                                                                                                                                                                                   |  
| [MS09-013](http://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP Services의 취약점으로 인한 원격 코드 실행 문제점(960803)                                                             | [CVE-2009-0550 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)\*\* | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 악용 코드가 일반에 공개되었습니다.                                                                                                                                                                                       |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 누적 보안 업데이트(963027)                                                                                      | [CVE-2008-2540 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 공격 세부 사항이 일반에 공개되었지만 이 문제에 대해 현재 알려진 공격 경로는 없습니다 이 취약점의 악용에 성공하려면 공격자와 사용자가 데스크톱에 특정 파일을 저장하는 것을 포함하는 일련의 복잡한 단계를 수행해야 합니다. |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 누적 보안 업데이트(963027)                                                                                      | [CVE-2009-0550 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)\*\* | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 악용 코드가 일반에 공개되었습니다.                                                                                                                                                                                       |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 누적 보안 업데이트(963027)                                                                                      | [CVE-2009-0551 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0551)     | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                                                                                                                   |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 누적 보안 업데이트(963027)                                                                                      | [CVE-2009-0552 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0552)     | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | Internet Explorer 7에 대한 완화 요소가 코드 실행을 방지합니다. Internet Explorer 6 및 이전 버전의 경우 모든 보안 업데이트를 최신으로 유지하지 않으면 악용 가능성이 높습니다.                                             |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 누적 보안 업데이트(963027)                                                                                      | [CVE-2009-0553 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0553)     | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | (없음)                                                                                                                                                                                                                   |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 누적 보안 업데이트(963027)                                                                                      | [CVE-2009-0554 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0554)     | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                                                                                                                                                   |  
| [MS09-015](http://technet.microsoft.com/security/bulletin/ms09-015) | SearchPath의 혼합 보안 위협 취약점으로 인한 권한 상승 문제점(959426)                                                              | [CVE-2008-2540 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 공격 세부 사항이 일반에 공개되었지만 이 문제에 대해 현재 알려진 공격 경로는 없습니다 이 취약점의 악용에 성공하려면 공격자와 사용자가 데스크톱에 특정 파일을 저장하는 것을 포함하는 일련의 복잡한 단계를 수행해야 합니다. |  
| [MS09-016](http://technet.microsoft.com/security/bulletin/ms09-016) | Microsoft ISA Server 및 Forefront Threat Management Gateway(Medium Business Edition)의 취약점으로 인한 서비스 거부 문제점(961759) | [CVE-2009-0077 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0077)     | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 서비스 기반 서비스 거부 공격 가능성이 높습니다. 그로나 코드 실행은 불가능합니다.                                                                                                                                         |  
| [MS09-016](http://technet.microsoft.com/security/bulletin/ms09-016) | Microsoft ISA Server 및 Forefront Threat Management Gateway(Medium Business Edition)의 취약점으로 인한 서비스 거부 문제점(961759) | [CVE-2009-0237 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-0237)          | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 정보 유출이 가능합니다. 코드 실행은 거의 불가능합니다.                                                                                                                                                                   |
  
\*두 보안 업데이트에서 동일한 CVE 번호가 지정된 이 두 취약점을 해결합니다. 자세한 내용은 각각의 보안 공지를 참조하십시오.
  
\*\*두 보안 업데이트에서 동일한 CVE 번호가 지정된 이 두 취약점을 해결합니다. 자세한 내용은 각각의 보안 공지를 참조하십시오.
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
(심각도 없음)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=552d322a-5282-42c7-9c1e-1d8c494a7318&displaylang=ko)  
(KB923561)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=39d5468e-5733-4c3e-9e75-3adac8ac8cb9&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 8.1](http://www.microsoft.com/downloads/details.aspx?familyid=0ec5b7c7-13d3-467a-b24e-3cc6fb47adf6&displaylang=ko)  
(긴급)  
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=8b98ed5c-a3ab-45a7-a61e-349eae304bc6&displaylang=ko)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=7799fd05-5b26-449f-8a14-50227c9164d1&displaylang=ko)  
(긴급)  
[Microsoft Internet Explorer 6 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=87f0c380-5c31-4099-a6a9-c12f9d69b03b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=52b756e7-636f-4d9e-8a17-dbf467bfbe4d&displaylang=ko)  
(KB952004)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=c4e408d7-6716-4a12-ad3a-8029667f5c84&displaylang=ko)  
(심각도 없음)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=50a8519a-503e-43dd-a78a-c1bc764fd213&displaylang=ko)  
(KB923561)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=35af4151-1858-4c9a-85e4-9ff45feca1a4&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=feb5d821-f210-40e8-b1aa-2ca3170df8df&displaylang=ko)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=052c29fc-e8df-402c-9ab1-1079bc738e1b&displaylang=ko)  
(긴급)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=55d6729a-9f96-4da4-b564-676c0a0c9390&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=90fe715e-8190-43e9-9c43-df5be564d923&displaylang=ko)  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=73d2324f-be59-4b0c-b1ac-9876a13c2c03&displaylang=ko)  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=3de0684d-605c-489b-bdc7-08bce9b2d4f6&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c)  
(KB923561)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=49b16f0f-f6c3-4ca8-8041-392f4f7b5bbb)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f1be8b7c-4874-4342-99b3-76ff725fbb9a)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=84c62211-2e82-4ccc-9f9b-26462b026d86)  
(긴급)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=191c2f20-89ae-4e1c-bdd4-24b4abfe6b6c)  
(긴급)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a794c32a-9a0c-47d9-9c57-ff5d4a8e4944)  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b2f12ae5-0e46-47e1-ac5b-93550d030189)  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b743a7fe-7bf4-420d-a72e-39471e5659fa)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2233a4d2-7c8a-4c89-b020-100d9afb43c8&displaylang=ko)  
(KB923561)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=42509f5a-d0f9-444a-9445-5eabdb555011&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=c1b4cd76-1dd6-43fa-bb9a-20c428985bfd&displaylang=ko)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f73a3669-c17f-4b18-8456-96cb7d52ed86&displaylang=ko)  
(중요)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6a45dbd0-0520-4d9b-b76e-3f5109dd310d&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=25adec10-db8c-4cac-bf74-2c784678150a&displaylang=ko)  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=42aba890-8b76-4c5a-8fb6-609797d19831&displaylang=ko)  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=992bb0cd-fbc7-4a7c-9088-f7f9d9a3ead0&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c&displaylang=ko)  
(KB923561)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7373ea32-bc2e-49f1-8b9f-4eeda5acc74c&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f0e1e1db-94a5-451c-ab11-6b431fa065f1&displaylang=ko)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=03a9d581-2bd5-4151-9826-17b96e16f606&displaylang=ko)  
(중요)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=60ccc1d6-ea31-420c-b630-d7878a8dc527&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b014c399-f404-4cb2-8f9d-864df382efeb&displaylang=ko)  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0609f65-82d9-4d82-9f48-f3266e8de123&displaylang=ko)  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f0a58e8c-7d63-4d7d-ba95-b3787cf408f0&displaylang=ko)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=e840b9cb-f1f4-482a-aa07-eb6b42b477c4)  
(KB923561)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=05e33cc5-cff6-4c71-be71-285f66a95e01)  
(긴급)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=8f36c215-fa8a-40c2-b680-6b1fece03b8d)\*\*\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=53d13c07-80b0-4f05-b372-a2dac17e6157)  
(중요)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0abaa2fb-7c4f-4149-993d-1575888bfc84)  
(중요)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=6ada372b-ba17-433e-b022-d2c57b35af8a)  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=fda8837c-e5d2-4489-9b44-4c24a1102e77)  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=00c6479d-f81f-445d-b8e4-7b71d77d540a)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
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
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 및 Windows Vista 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista 및 Windows Vista 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=f071d770-3b6b-4040-9911-d4de8cde4c68&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d743849d-f3b5-4114-adef-ade2716d55ac&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows Vista 및 Windows Vista 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=f111b99a-e555-4f29-8d1f-e9ec03d5cf1f&displaylang=ko)  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows Vista 및 Windows Vista 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=d0ea1598-45cb-4c79-8945-caae98969675&displaylang=ko)  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista 및 Windows Vista 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=2b672d45-f33b-4edc-9f22-2f2c8c726a8b&displaylang=ko)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7ceef2d0-f316-48d1-aecc-d74f91cc5e1f&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d191c8dc-a965-4a6a-b6d8-1470505eb55f&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=fa153bdc-6b48-4df2-9e5e-abacd6da782c&displaylang=ko)  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=6dd82f4b-bb33-41ec-90a7-9ef91329b240&displaylang=ko)  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=7576e7d5-5bb1-4a53-b568-1ee0500ce721&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="7">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
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
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=4c36548f-c8c9-4318-91e2-9e0501339548&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e2c6313c-3ba9-4f7c-b259-b4582a390146&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows Server 2008(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=9e3c7b52-65a7-42fb-beb5-1b374934737f&displaylang=ko)\*  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows Server 2008(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=d58702af-bbf8-4f1b-ae72-ced9ef23d581&displaylang=ko)\*  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=6b73cf5e-66fe-4b7d-95fc-91a1c262c1e5&displaylang=ko)\*  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=1c3f0997-a8a9-4340-ae0c-2c4d6792c65c&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ebbade9d-704c-440b-8796-6d64225ac01a&displaylang=ko)\*\*  
(중요)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows Server 2008(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=eebb4d4d-29d2-4247-8cbb-63a3b17585ec&displaylang=ko)\*  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows Server 2008(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=20bf4e9b-909b-4bc3-ae43-322d74a4f1c3&displaylang=ko)\*  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=7e60847c-b341-4c38-bc25-2e3cf2d4ae14&displaylang=ko)\*  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=0885b3b0-b78e-4980-902d-dff3886bcaac)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1b04aa6f-b787-4122-bf82-0d150618fe7a)  
(중요)
</td>
<td style="border:1px solid black;">
MSDTC 트랜잭션 기능 업데이트:  
[Windows Server 2008(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=cc383c24-b0f6-47c1-9e89-6a378b09e82f)  
(KB952004)  
(중요)  
Windows 서비스 격리 업데이트:  
[Windows Server 2008(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=bcc2b18f-67db-4109-a9f4-764f985423ee)  
(KB956572)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=de1c2b4b-af47-4b9a-8363-720e5527573c)  
(보통)
</td>
</tr>
</table>
 
**Windows Server 2008 참고 사항**

**\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** 지원 대상인 Windows Server 2008 에디션에 대해 이 업데이트의 심각도는 Windows Server 2008에 Server Core 설치 옵션의 사용 여부와 상관없이 동일하게 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

**\*\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 Windows Server 2008이 설치된 경우 이 업데이트에서 해결하는 취약점은 지원되는 모든 Windows Server 2008 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

**MS09-010 참고 사항**

추가적인 업데이트 파일은 **Microsoft Office Suites 및 소프트웨어** 섹션을 참조하십시오. 이 공지는 Windows 운영 체제 및 구성 요소와 Microsoft Office 제품군 및 Server 소프트웨어에 모두 적용됩니다.

**MS09-011 참고 사항**

\*\*\*DirectX 9.0의 업데이트는 DirectX 9.0a, DirectX 9.0b, DirectX 9.0c에도 적용됩니다.

#### Microsoft Office 제품군 및 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office 제품군, 시스템 및 구성 요소
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://technet.microsoft.com/security/bulletin/ms09-009)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=95876927-e612-414c-bdec-3632a3100415&displaylang=ko)  
(KB921606)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=3dc8b670-25a5-4f46-b7de-12bc693b628a&displaylang=ko)  
(KB959964)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=e1db55c6-78fb-498d-89a5-9ad54d971546&displaylang=ko)  
(KB933399)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=9a52bf4b-05f6-4b73-94b9-28ed7e20f86c&displaylang=ko)  
(KB959988)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=d9dbfa63-c0cb-4c84-9b8a-6e52568045b0&displaylang=ko)  
(KB959995)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System 서비스 팩 1
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=50d8630b-1365-4007-81a0-18c0d6d4b86e&displaylang=ko)\*  
(KB959997)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://technet.microsoft.com/security/bulletin/ms09-009)
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
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=52271140-89be-4b9c-baa2-cea09097d703)  
(KB968695)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=f6e407eb-11a5-433f-8006-4b822953ca98)  
(KB968694)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
기타 Office 소프트웨어
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://technet.microsoft.com/security/bulletin/ms09-009)
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
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=c72e6087-b48f-4d2d-8366-01d9f5ff6b6c&displaylang=ko)  
(KB959993)  
(중요)  
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=58b3929c-5373-47a4-aa97-66d179758792&displaylang=ko)  
(KB960000)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=05f7c517-e551-4dcd-b24a-5d548f2d09cf&displaylang=ko)  
(KB960003)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 변환 팩
</td>
<td style="border:1px solid black;">
[Microsoft Office 변환 팩](http://www.microsoft.com/downloads/details.aspx?familyid=d763fae3-b2af-47f9-a554-ec786766b3c3)  
(KB960476)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**MS09-010 참고 사항**

추가적인 업데이트 파일은 **Windows 운영 체제 및 구성 요소** 섹션을 참조하십시오. 이 공지는 Windows 운영 체제 및 구성 요소와 Microsoft Server 소프트웨어에 모두 적용됩니다.

**MS09-009 참고 사항**

\*Microsoft Office Excel 2007 서비스 팩 1을 사용하는 고객의 경우 이 보안 공지에서 설명한 취약점으로부터 보호하기 위해 Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩 서비스 팩 1용 보안 업데이트를 설치해야 합니다.

#### Microsoft Server and Security Software

 
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
Microsoft Forefront
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-016**](http://technet.microsoft.com/security/bulletin/ms09-016)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Threat Management Gateway
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Threat Management Gateway, Medium Business Edition](http://www.microsoft.com/downloads/details.aspx?familyid=6abf9fb4-42d0-4c67-935f-8dc67850148b&displaylang=ko)\*  
(KB968075)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Internet Security and Acceleration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-016**](http://technet.microsoft.com/security/bulletin/ms09-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=adf623fa-2d74-4f2a-9835-4b8debdb0e1b)\*\*  
(KB960995)  
(중요)  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=d1d55ab6-3de5-4811-9693-8d43f49f5fe8)  
(KB960995)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770&displaylang=ko)  
(KB968078)  
(중요)  
[Microsoft Internet Security and Acceleration Server 2006 지원 업데이트](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770&displaylang=ko)  
(KB968078)  
(중요)  
[Microsoft Internet Security and Acceleration Server 2006 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770&displaylang=ko)  
(KB968078)  
(중요)
</td>
</tr>
</table>
 
**MS09-016 참고 사항**

\*Microsoft Forefront Threat Management Gateway, Medium Business Edition은 독립 실행형 제품으로 공급되거나 Windows Essential Business Server 2008의 구성 요소로 공급됩니다.

\*\*Microsoft ISA Server 2004 Standard Edition은 독립 실행형 제품으로 공급됩니다. Microsoft ISA Server 2004 Standard Edition은 Windows Small Business Server 2003 Enterprise Edition 서비스 팩 1 및 Windows Small Business Server 2003 R2 Enterprise Edition의 구성 요소로 공급됩니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://technet.microsoft.com/ko-kr/updatemanagement/default.aspx)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://www.microsoft.com/korea/protect/default.mspx)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 및 [Office 업데이트](http://go.microsoft.com/fwlink/?linkid=21135)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), ESUIT(Extended Security Update Inventory Tool) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](http://support.microsoft.com/kb/910723)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](http://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/dd573344.aspx)

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드 (영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security%20update)에서 다운로드할 수 있으며"security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://technet.microsoft.com/security/bulletin/policy)드립니다.

-   ms09-009에서 설명한 문제점을 보고해 주신 Fortinet, [FortiGuard Global Security Research Team (영문)](http://www.fortiguardcenter.com/)의 Haifei Li
-   MS09-010에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Sean Larsson 및 Jun Mao
-   MS09-010에서 설명한 문제점을 보고해 주신 Fortinet, [FortiGuard Global Security Research Team (영문)](http://www.fortiguardcenter.com/)의 연구자
-   MS09-010에서 설명한 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 연구자
-   MS09-011에서 설명한 문제점을 보고해 주신 [Kryptos Logic (영문)](http://www.kryptoslogic.com/)의 Piotr Bania
-   MS09-012에서 설명한 문제점을 보고해 주신 [Argeniss (영문)](http://www.argeniss.com/)의 Cesar Cerrudo
-   MS09-013에서 설명한 문제점을 보고해 주신 [iSIGHT Partners (영문)](http://www.isightpartners.com/)의 Greg MacManus
-   MS09-013에서 설명한 문제점을 보고해 주신 [Google Inc. (영문)](http://www.google.com/)의 Wan-Teh Chang 및 Cem Paya
-   MS09-014에서 설명한 문제점을 보고해 주신 [Aviv Raff (영문)](http://aviv.raffon.net/)
-   MS09-014에서 설명한 문제점을 보고해 주신 [Google Inc. (영문)](http://www.google.com/)의 Michal Zalewski
-   MS09-014에서 설명한 문제점을 보고해 주신 [iSIGHT Partners Labs (영문)](http://www.isightpartners.com/)의 Ivan Fratric
-   MS09-014에서 설명한 문제점을 보고해 주신 [Google Inc. (영문)](http://www.google.com/)의 Skylined
-   MS09-014에서 설명한 문제점을 보고해 주신 [VenusTech (영문)](http://www.venustech.com.cn/)의 ADLab
-   MS09-015에서 설명한 문제점을 보고해 주신 [Aviv Raff (영문)](http://aviv.raffon.net/)
-   MS09-016에서 설명한 문제점을 보고해 주신 New York State CIO/OFT

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 4월 15일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 4월 17일): 악용가능성지표 갱신: CVE-2009-0089가 삭제 되었으며, MS09-014와 MS09-015를 위한 CVE-2008-2540가 변경 되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
