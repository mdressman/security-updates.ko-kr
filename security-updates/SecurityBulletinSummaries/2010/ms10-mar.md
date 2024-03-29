---
TOCTitle: 'MS10-MAR'
Title: 2010 년 3 월 Microsoft 보안 공지 요약
ms:assetid: 'ms10-mar'
ms:contentKeyID: 61230727
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms10-mar(v=Security.10)'
---


2010 년 3 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2010년 3월 10일 수요일 | 업데이트된 날짜: 2010년 8월 12일 목요일

**버전:** 3.1

이 공지 요약 목록에는 2010년 3월 발표된 보안 공지가 포함되어 있습니다.

2010년 3월 공지 발표와 함께 이 공지 요약이 2010년 3월 4일 게시된 공지 사전 알림을 대체합니다. 공지 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2010년 3월 10일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [3월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427711&eventcategory=4&culture=en-us&countrycode=us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

Microsoft는 2010년 3월 30일 오후 1:00(태평양 표준시, 미국 및 캐나다)에 이 공지 요약의 버전 2.0에 추가된 부정기 보안 공지인 MS10-018에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [3월 30일 오후 1:00 웹캐스트에 지금 등록하십시오](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032448112&culture=en-us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-018">MS10-018</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(980182)</strong> <br />
<br />
이 보안 업데이트는 Internet Explorer에 대해 비공개적으로 보고된 취약점 9건과 공개된 취약점 1건을 해결합니다. 가장 위험한 취약점으로 인해 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-016">MS10-016</a></td>
<td style="border:1px solid black;"><strong>Windows Movie Maker의 취약점으로 인한 원격 코드 실행 문제점 (975561)</strong><br />
<br />
이 보안 업데이트는 Windows Movie Maker 및 Microsoft Producer 2003에서 발견되어 비공개적으로 보고된 취약점을 해결합니다. Windows Vista 및 Windows 7에서 사용할 수 있는 Windows Live Movie Maker는 이 취약점의 영향을 받지 않습니다. 이 취약점으로 인해 공격자가 특수하게 조작된 Movie Maker 또는 Microsoft Producer 프로젝트 파일을 전송하고 특수하게 조작된 파일을 열도록 사용자를 유도한 경우 원격 코드 실행이 발생할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-017">MS10-017</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel의 취약점으로 인한 원격 코드 실행 문제점 (980150)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office Excel에서 발견되어 비공개적으로 보고된 취약점 7건을 해결합니다. 사용자가 특수하게 조작된 Excel 파일을 열면 이러한 취약점으로 인해 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 하나를 성공적으로 악용한 공격자는 로컬 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 악용 가능성 평가 수준 내림차순 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 취약점 제목                                                             | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                 |  
|---------------------------------------------------------------------|-------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel 레코드 메모리 손상 취약점                        | [CVE-2010-0257 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0257) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel MDXTUPLE 레코드 힙 오버플로 취약점               | [CVE-2010-0260 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0260) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel MDXSET 레코드 힙 오버플로 취약점                 | [CVE-2010-0261 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0261) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel XLSX 파일 구문 분석 코드 실행 취약점             | [CVE-2010-0263 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0263) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel DbOrParamQry 레코드 구문 분석 취약점             | [CVE-2010-0264 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0264) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-016](http://technet.microsoft.com/security/bulletin/ms10-016) | Movie Maker 및 Producer 버퍼 오버플로 취약점                            | [CVE-2010-0265 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0265) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                    |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | HTML 개체 메모리 손상 취약점                                            | [CVE-2010-0491](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0491)        | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능          | (없음)                                                    |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | HTML 개체 메모리 손상 취약점                                            | [CVE-2010-0492](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0492)        | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능          | (없음)                                                    |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | HTML 요소 도메인 간 취약점                                              | [CVE-2010-0494](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0494)        | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능          | Windows 2000에서만 코드 실행이 가능합니다.                |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 초기화되지 않은 메모리 손상 취약점                                      | [CVE-2010-0806](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0806)        | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능          | **이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.** |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | HTML 렌더링 메모리 손상 취약점                                          | [CVE-2010-0807](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0807)        | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능          | (없음)                                                    |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel 시트 개체 유형 혼란 취약점                       | [CVE-2010-0258 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0258) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel FNGROUPNAME 레코드 초기화되지 않은 메모리 취약점 | [CVE-2010-0262 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0262) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                    |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 경쟁 조건 메모리 손상 취약점                                            | [CVE-2010-0489](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0489)        | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능        | (없음)                                                    |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 메모리 손상 취약점                                                      | [CVE-2010-0805](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0805)        | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능        | (없음)                                                    |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 초기화되지 않은 메모리 손상 취약점                                      | [CVE-2010-0267](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0267)        | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능            | (없음)                                                    |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 인코딩 후 정보 유출 취약점                                              | [CVE-2010-0488](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0488)        | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능            | (없음)                                                    |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 초기화되지 않은 메모리 손상 취약점                                      | [CVE-2010-0490](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0490)        | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능            | (없음)                                                    |
  
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
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=389da7a9-e0a3-4b5d-801e-0a38fc55dcec&displaylang=ko)  
(긴급)  
[Internet Explorer 6 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=daf199c4-da56-4a7f-80e6-3936ce5c267b&displaylang=ko)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Movie Maker 2.1](http://www.microsoft.com/downloads/details.aspx?familyid=6301e462-02be-4b9a-bae9-7c4821b42d2d&displaylang=ko)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2f2caa01-5cd1-45cb-9995-e34d933920d4&displaylang=ko)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=167ed896-d383-4dc0-9183-cd4cb73e17e7&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=46172617-293a-44c7-95b6-18202ab06a41&displaylang=ko)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Movie Maker 2.1](http://www.microsoft.com/downloads/details.aspx?familyid=cae81585-d0df-41b8-9277-ca02f1265056)<sup>[1]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6c711387-6853-477c-917e-820a97613cf9)  
(긴급)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=aadb1d97-5cec-45ed-9967-aaf41a0bcdac)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=284d70ea-24a3-4e67-a2a8-e9f272f728db)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=dc77f1c9-8240-42d9-aee9-30ac4f33bde7&displaylang=ko)  
(중요)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e957a7cf-e5ca-454d-b199-ec8fe6a6a2bf&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=53fc3285-63c4-487f-ad9a-7e1673aeffc7&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2be85462-28ec-4184-a326-0459554b7213&displaylang=ko)  
(중요)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=cb0e39f8-9730-4454-a0e3-479b610b1591&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5201a0c5-8162-4809-b9d1-0e972b0f0066&displaylang=ko)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=04abea55-ea2f-423f-b410-5536ea184ea3)  
(중요)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7ebd99b4-da6b-4dff-9f89-6a86d275a3da)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=ae2e9b75-1616-4fe3-91bb-e2e28252ff1c&displaylang=ko)<sup>[1]</sup>
(중요)  
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=ca2d1118-ca64-419d-86af-9396e61b90b0&displaylang=ko)<sup>[2]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=511aba0e-6f15-42cf-9c5d-b2f3e215b5a8&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c9584689-5196-4840-927c-23c8038f3382&displaylang=ko)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e27f353e-deb6-4d61-8808-c751d20a42a1&displaylang=ko)<sup>[1]</sup>
(중요)  
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=6a1f4126-97f2-4aee-bfe1-05bd13a0667b&displaylang=ko)<sup>[2]</sup>
(중요)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c8933a45-62a7-4c19-be30-02e3a461f081&displaylang=ko)  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=50809cc3-6baa-41b4-ba0a-596a1dd846ed&displaylang=ko)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=42f8c1f2-ee55-47af-b113-8d9f4bd40c8f&displaylang=ko)\*\*  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c69a6dfe-66b1-4426-96a5-d64000296e76&displaylang=ko)\*\*  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=769043b5-df52-4446-9bd8-dc37d9fa00df&displaylang=ko)\*\*  
(긴급)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e16c10d2-896d-48f3-bc76-5fa70881396a&displaylang=ko)\*\*  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c1c2309d-22db-4dbf-ad95-3219847cd42d)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c0145563-428e-47b6-b245-b59dce88ac0e&displaylang=ko)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6172dbec-6bfc-40bd-a0d4-67c39fb41b87&displaylang=ko)  
(긴급)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
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
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8b7c664b-8612-458f-bd0a-cf28b67f8374&displaylang=ko)\*\*  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=82fa6f47-002f-4943-888c-2e852675e76e)  
(보통)
</td>
</tr>
</table>
 
**Windows Server 2008 및 Windows Server 2008 R2 참고 사항**

**\*\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오

**MS10-016 참고 사항**

<sup>[1]</sup>이러한 Windows Movie Maker 버전은 표시된 운영 체제와 함께 제공됩니다.

<sup>[2]</sup>Windows Movie Maker 2.6은 표시된 운영 체제에 설치할 수 있는 선택적 다운로드입니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

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
[**MS10-017**](http://technet.microsoft.com/security/bulletin/ms10-017)
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=e0136f62-60ce-4ebd-8660-be81eba29ae8&displaylang=ko)  
(KB978471)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=7e42793e-747b-48da-968a-1ec29ea37151&displaylang=ko)  
(KB978474)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 서비스 팩 1 및 Microsoft Office Excel 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=03429f8a-8aab-4a59-97e4-7ce047f100a5&displaylang=ko)<sup>[1]</sup>
(KB978382)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-017**](http://technet.microsoft.com/security/bulletin/ms10-017)
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ae5936f8-fe3f-4d23-a37c-d80f228e475e)  
(KB980837)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=e0ed1569-ab2f-407c-b728-4eddc463c385)  
(KB980839)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=4c5487d5-c912-4087-8c83-769e3fb78ea9)  
(KB980840)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
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
[**MS10-017**](http://technet.microsoft.com/security/bulletin/ms10-017)
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
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
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 서비스 팩 1 및 Microsoft Office Excel Viewer 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=010d0a4d-02a4-4142-963b-a38cd06cc897&displaylang=ko)  
(KB978383)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](http://www.microsoft.com/downloads/details.aspx?familyid=314f076e-8f9d-46c2-b666-86599a02bf15&displaylang=ko)  
(KB978380)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007(32비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 1 및 Microsoft Office SharePoint Server 2007 서비스 팩 2(32비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=94ddf6ef-3392-4d77-a02b-3bc0470721cd&displaylang=ko)<sup>[2]</sup>
(KB979439)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007(64비트 에디션)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 서비스 팩 1 및 Microsoft Office SharePoint Server 2007 서비스 팩 2(64비트 에디션)](http://www.microsoft.com/downloads/details.aspx?familyid=06f6bffb-3fad-4fb5-878b-39550812e9b5&displaylang=ko)<sup>[2]</sup>
(KB979439)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Producer 2003
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Producer 2003](http://www.microsoft.com/downloads/details.aspx?familyid=1b3c76d5-fc75-4f99-94bc-784919468e73)<sup>[3]</sup>
(중요)
</td>
</tr>
</table>
 
**MS10-017 참고 사항**

<sup>[1]</sup>Microsoft Office Excel 2007 서비스 팩 1 및 Microsoft Office Excel 2007 서비스 팩 2를 사용하는 고객은 이 보안 공지에서 설명한 취약점으로부터 보호하기 위해 보안 업데이트 패키지 KB978382과 함께 [Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](http://www.microsoft.com/downloads/details.aspx?familyid=314f076e-8f9d-46c2-b666-86599a02bf15)(KB978380)에 대한 보안 업데이트를 설치해야 합니다.

<sup>[2]</sup>이 업데이트는 Microsoft Office SharePoint Server 2007 Enterprise 및 Microsoft Office SharePoint Server 2007 For Internet Sites와 같이 Excel Services가 설치된 서버에 적용됩니다. Microsoft Office SharePoint Server 2007 Standard에는 Excel Services가 포함되지 않습니다.

**MS10-016 참고 사항**

<sup>[3]</sup>이 다운로드는 설치된 Microsoft Producer 2003을 새로운 버전의 Microsoft Producer로 업그레이드합니다. Microsoft Producer는 영어로만 제공됩니다.

동일한 공지 ID의 추가 업데이트 파일에 대해서는 영향을 받는 소프트웨어 및 다운로드 위치 섹션의 다른 소프트웨어 범주를 참조하십시오. 이 공지는 둘 이상의 소프트웨어 범주에 해당합니다.

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://go.microsoft.com/fwlink/?linkid=85102)을 방문하거나 "최신 보안 업데이트"를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 및 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)를 통해 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**참고** 2009년 8월 1일부터 Microsoft는 Office 업데이트와 Office 업데이트 인벤토리 도구에 대한 지원을 중단합니다. 계속해서 Microsoft Office 제품에 필요한 최신 업데이트를 받으려면 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)를 사용하십시오. 자세한 내용은 [Microsoft Office 업데이트 정보: 자주 제기되는 질문 사항(FAQ)](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx)을 참조하십시오.

**검색 및 배포 지침**

Microsoft는 보안 업데이트를 위한 검색 및 배포 지침을 제공합니다. 이 지침에는 IT 전문가가 다양한 도구를 사용하여 보안 업데이트를 검색하고 배포하는 방법을 이해하는 데 도움이 되는 권장 사항과 정보가 포함되어 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 961747](http://support.microsoft.com/kb/961747)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Microsoft Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Microsoft Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 빠르고 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](http://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://go.microsoft.com/fwlink/?linkid=22939)를 참조하십시오. SMS 2.0 사용자는 SUIT(Security Update Inventory Tool)을 사용하여 보안 업데이트 배포를 지원할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer를 사용하여 보안 공지 업데이트 검색 및 배포에 대한 다양한 지원을 제공합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2.0 Administration Feature Pack (영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

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

-   MS10-016에서 설명한 문제점을 보고해 주신 [Core Security Technologies (영문)](http://www.coresecurity.com/)의 Damián Frizza
-   MS10-017에서 설명한 문제점을 보고해 주신 [VUPEN Vulnerability Research Team (영문)](http://www.vupen.com/)의 Nicolas Joly
-   MS10-017에서 설명한 네 가지 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Sean Larsson
-   MS10-017에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS10-017에서 설명한 문제점을 보고해 주신 [Core Security Technologies (영문)](http://www.coresecurity.com/)의 Damián Frizza
-   MS10-018에서 설명한 문제점을 해결하기 위해 협력해 주신 [Secunia (영문)](http://secunia.com)
-   MS10-018에서 설명한 문제점을 보고해 주신 [Cyber Defense Institute Inc. (영문)](http://www.cyberdefense.jp/)의 Daiki Fukumori
-   MS10-018에서 설명한 문제점을 보고해 주신 [Red Database Security (영문)](http://www.red-database-security.com/)의 Alexander Kornbrust
-   MS10-018에서 설명한 문제점을 보고해 주신 [iSIGHT Partners (영문)](http://www.isightpartners.com/) Global Vulnerability Partnership의 Ivan Fratric
-   MS10-018에서 설명한 문제점을 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)와 협력하여 보고해 주신 [team509 (영문)](http://www.team509.com/)의 Wushi
-   MS10-018에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Simon Zuckerbraun
-   MS10-018에서 설명한 문제점을 보고해 주신 [Context Information Security (영문)](http://www.contextis.co.uk/)의 Paul Stone
-   MS10-018에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 익명 연구자
-   MS10-018에서 설명한 두 가지 문제점을 보고해 주신 [VenusTech](http://www.venustech.com.cn/)의 ADLab

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2010년 3월 10일): 공지 요약이 게시되었습니다.
-   V2.0(2010년 3월 31일): Microsoft 보안 공지 MS10-018, Internet Explorer 누적 업데이트(980182)가 추가되었습니다. 또한 이 부정기 보안 업데이트에 대한 공지 웹캐스트 링크가 추가되었습니다.
-   V3.0(2010년 5월 4일): MS10-016과 관련된 Microsoft Producer 다운로드 출시를 발표했습니다.
-   V3.1(2010년 8월 12일): MS10-016에서 Windows 7의 Windows Movie Maker 2.6이 영향을 받는 구성 요소에서 제거되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
