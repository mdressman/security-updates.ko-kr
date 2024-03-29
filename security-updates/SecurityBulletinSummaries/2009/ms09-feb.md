---
TOCTitle: 'MS09-FEB'
Title: 2009 년 2 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-feb'
ms:contentKeyID: 61230711
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-feb(v=Security.10)'
---


2009 년 2 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2009년 2월 10일 화요일 | 업데이트된 날짜: 2009년 2월 26일 목요일

**버전:** 2.1

이 공지 요약 목록에는 2009년 2월 발표된 보안 공지가 포함되어 있습니다.

2009년 2월 공지 발표와 함께 이 공지 요약이 2009년 2월 5일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2009년 2월 11일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [2월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395122). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<th style="border:1px solid black;" >최대 심각도 및 보안 영향</th>
<th style="border:1px solid black;" >다시 시작 요구 사항</th>
<th style="border:1px solid black;" >영향을 받는 소프트웨어</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-002">MS09-002</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트 (961260)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점들은 모두 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-003">MS09-003</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange의 취약점으로 인한 원격 코드 실행 문제점 (959239)</strong><br />
<br />
이 보안 업데이트는 Microsoft Exchange Server에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 첫 번째 취약점은 특수하게 조작된 TNEF 메시지가 Microsoft Exchange Server에 전달될 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약점 악용에 성공한 공격자는 Exchange Server 서비스 계정 권한을 사용하여 영향을 받는 시스템을 완전히 제어할 수 있습니다. 두 번째 취약점은 특수하게 조작된 MAPI 명령이 Microsoft Exchange Server에 전달될 경우 서비스 거부 문제를 일으킬 수 있습니다. 이 취약점 악용에 성공한 공격자는 Microsoft Exchange System Attendant 서비스와 EMSMDB32 공급자를 사용하는 기타 서비스가 응답을 중지하도록 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-004">MS09-004</a></td>
<td style="border:1px solid black;"><strong>Microsoft SQL Server의 취약점으로 인한 원격 코드 실행 문제점 (959420)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft SQL Server의 취약점을 해결합니다.신뢰할 수 없는 사용자가 영향을 받는 시스템에 액세스하거나 영향을 받는 시스템에 SQL 주입 공격이 발생할 경우 이 취약점으로 인해 원격 코드가 실행될 수 있습니다. SQL Server 7.0 서비스 팩 4, SQL Server 2005 서비스 팩 3 및 SQL Server 2008이 설치된 시스템은 이 문제의 영향을 받지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-005">MS09-005</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Visio의 취약점으로 인한 원격 코드 실행 문제점 (957634)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 세 가지 취약점을 해결합니다. 사용자가 특수하게 조작된 Visio 파일을 열면 이 Microsoft Office Visio 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 공지 번호 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 공지 제목                                                              | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                                                |  
|---------------------------------------------------------------------|------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|  
| [MS09-002](http://technet.microsoft.com/security/bulletin/ms09-002) | Internet Explorer 누적 보안 업데이트(961260)                           | [CVE-2009-0075 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0075) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능          | 일관적인 악용 코드를 쉽게 조작할 수 있습니다.                                                                            |  
| [MS09-002](http://technet.microsoft.com/security/bulletin/ms09-002) | Internet Explorer 누적 보안 업데이트(961260)                           | [CVE-2009-0076 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0076) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능          | 일관적인 악용 코드를 쉽게 조작할 수 있습니다.                                                                            |  
| [MS09-003](http://go.microsoft.com/fwlink/?linkid=136636)           | Microsoft Exchange의 취약점으로 인한 원격 코드 실행 문제점(959239)     | [CVE-2009-0098 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0098) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS09-003](http://technet.microsoft.com/security/bulletin/ms09-003) | Microsoft Exchange의 취약점으로 인한 원격 코드 실행 문제점(959239)     | [CVE-2009-0099 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0099) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 이 취약점은 서비스 거부 취약점입니다. 이 취약점을 악용하는 공격은 서비스 거부만 가능하며 원격 코드 실행은 불가능합니다.  |  
| [MS09-004](http://technet.microsoft.com/security/bulletin/ms09-004) | Microsoft SQL Server의 취약점으로 인한 원격 코드 실행 문제점(959420)   | [CVE-2008-5416 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-5416) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 사후 인증, 기능 악용 코드가 발견되었습니다.                                                                              |  
| [MS09-005](http://technet.microsoft.com/security/bulletin/ms09-005) | Microsoft Office Visio의 취약점으로 인한 원격 코드 실행 문제점(957634) | [CVE-2009-0095 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0095) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS09-005](http://technet.microsoft.com/security/bulletin/ms09-005) | Microsoft Office Visio의 취약점으로 인한 원격 코드 실행 문제점(957634) | [CVE-2009-0096 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0096) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |  
| [MS09-005](http://technet.microsoft.com/security/bulletin/ms09-005) | Microsoft Office Visio의 취약점으로 인한 원격 코드 실행 문제점(957634) | [CVE-2009-0097 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0097) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                                                   |
  
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
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
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
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8cd902ec-e018-4b61-80f9-825d973f998e&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dd3e2236-9cc0-478e-a46c-981ef685c0e3)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e52aa1fd-e694-4322-b3ff-6abc1b4a16fe&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine(WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=218809d6-a9fb-408b-a34d-ab2ac786994c)  
(KB960082)  
(중요)  
[Windows Internal Database(WYukon) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e&displaylang=ko)  
(KB960089)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=edbf1566-b96b-4c7d-98fe-b15f8e766792&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine(WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=218809d6-a9fb-408b-a34d-ab2ac786994c&displaylang=ko)  
(KB960082)  
(중요)  
[Windows Internal Database(WYukon) x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67&displaylang=ko)  
(KB960089)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ce78797-d1c0-40d4-84e1-1004389833be)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 및 Windows Vista 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5f9fa4b6-85a4-43bc-b84f-6bd847799650&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e9a8c94b-b9d2-4d64-855f-b5f02ce3dfb5&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2491dbf2-7cd3-44f1-bfad-77e6f760a25c&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Internal Database(WYukon) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e&displaylang=ko)\*  
(KB960089)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=794373cc-2dce-4ef5-af50-7804c622c230&displaylang=ko)\*\*  
(보통)
</td>
<td style="border:1px solid black;">
[Windows Internal Database(WYukon) x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67&displaylang=ko)\*  
(KB960089)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=11985325-4b33-4077-82cf-6afc7a71c510)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
</table>
 
**Windows Server 2008 참고 사항**

**\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** 지원 대상인 Windows Server 2008 에디션에 대해 이 업데이트의 심각도는 Windows Server 2008에 Server Core 설치 옵션의 사용 여부와 상관없이 동일하게 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

**\*\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 Windows Server 2008이 설치된 경우 이 업데이트에서 해결하는 취약점은 지원되는 모든 Windows Server 2008 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

**MS09-004 참고 사항**

추가적인 업데이트 파일은 다음 섹션 **Microsoft 서버 소프트웨어**를 참조하십시오. 이 공지는 Windows 운영 체제 및 구성 요소와 Microsoft Server 소프트웨어에 모두 적용됩니다.

#### Microsoft Server 소프트웨어

 
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
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-003**](http://technet.microsoft.com/security/bulletin/ms09-003)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**전체 심각도**
</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange 2000 Server
</td>
<td style="border:1px solid black;">
[2004년 8월에 릴리스된 업데이트 롤업이 설치된 Microsoft Exchange 2000 Server 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=805dc856-ea60-477d-be40-6ac535a7e7e5)  
(KB959897)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1d9f0956-88bd-4e13-a86b-b1c8d4782f71&displaylang=ko)\*  
(KB959897)  
(긴급)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=93cb3f66-ae72-4356-bdbf-35029cff6df1&displaylang=ko)\*\*  
(KB959241)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server MAPI Client and Collaboration Data Objects 1.2.1
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server MAPI Client and Collaboration Data Objects 1.2.1](http://www.microsoft.com/downloads/details.aspx?familyid=e17e7f31-079a-43a9-bff2-0a110307611e&displaylang=ko)\*\*  
(긴급)
</td>
</tr>
</table>
 
**MS09-003 참고 사항**

\*서버가 Exchange 서비스의 활성 인스턴스도 실행하는 경우Exchange Server 2003용 Microsoft Exchange System Management Tools 포함

\*\*32비트 및 x64 기반 에디션 포함

\*\*\*Microsoft Exchange Server MAPI Client에 취약한 코드가 포함되어 있습니다. MS09-003에서 설명한 취약점으로부터 보호하기 위해 Microsoft Exchange Server MAPI Client를 실행하는 고객은 MAPI Client의 버전을 6.5.8069로 업데이트해야 합니다.

 
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
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://technet.microsoft.com/security/bulletin/ms09-004)
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
SQL Server 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c&displaylang=ko)  
(KB960082)  
(중요)  
QFE 업데이트:  
[SQL Server 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a&displaylang=ko)  
(KB960083)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2000 Itanium 기반 에디션 서비스 팩 4
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2000 Itanium 기반 에디션 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(중요)  
QFE 업데이트:  
[SQL Server 2000 Itanium 기반 에디션 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e&displaylang=ko)  
(KB960089)  
(중요)  
QFE 업데이트:  
[SQL Server 2005 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a&displaylang=ko)  
(KB960090)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e&displaylang=ko)  
(KB960089)  
(중요)  
QFE 업데이트:  
[SQL Server 2005 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a&displaylang=ko)  
(KB960090)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(중요)  
QFE 업데이트:  
[SQL Server 2005 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Desktop Engine(MSDE 2000) 서비스 팩 4
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[Microsoft SQL Server 2000 Desktop Engine(MSDE 2000) 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c&displaylang=ko)  
(KB960082)  
(중요)  
QFE 업데이트:  
[Microsoft SQL Server 2000 Desktop Engine(MSDE 2000) 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a&displaylang=ko)  
(KB960083)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Express Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[SQL Server 2005 Express Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e&displaylang=ko)  
(KB960089)  
(중요)  
QFE 업데이트:  
[SQL Server 2005 Express Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a&displaylang=ko)  
(KB960090)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
고급 서비스가 포함된 SQL Server 2005 Express Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
GDR 업데이트:  
[고급 서비스가 포함된 SQL Server 2005 Express Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e&displaylang=ko)  
(KB960089)  
(중요)  
QFE 업데이트:  
[고급 서비스가 포함된 SQL Server 2005 Express Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a&displaylang=ko)  
(KB960090)  
(중요)
</td>
</tr>
</table>
 
**MS09-004 참고 사항**

추가적인 업데이트 파일은 **Windows 운영 체제 및 구성 요소** 섹션을 참조하십시오. 이 공지는 Windows 운영 체제 및 구성 요소와 Microsoft Server 소프트웨어에 모두 적용됩니다.

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
Microsoft Office Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-005**](http://technet.microsoft.com/security/bulletin/ms09-005)
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
Microsoft Office Visio 2002
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a30cef3f-9eaf-45bd-9a25-4b65302362cb&displaylang=ko)  
(KB955654)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Visio 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=c9cb589e-1a37-485d-8402-7f42bcd7a1a9&displaylang=ko)  
(KB955655)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=4b711e89-8de2-4f17-8afc-691e0604ff82&displaylang=ko)  
(KB957831)  
(중요)
</td>
</tr>
</table>
 

검색, 배포 도구 및 지침
-----------------------

**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center](http://technet.microsoft.com/ko-kr/updatemanagement/default.aspx)를 참조하십시오. [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://www.microsoft.com/korea/protect/default.mspx)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.

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

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명
-   [Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)

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

-   MS09-002에서 설명한 문제점을 보고해 주신 [TippingPoint (영문)](http://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)
-   MS09-002에서 설명한 문제점을 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/) 및 [TippingPoint (영문)](http://www.tippingpoint.com/)와 협력하여 보고해 주신 Sam Thomas([http://eshu.co.uk/ (영문)](http://eshu.co.uk/))
-   MS09-003의 문제점을 보고해 주신 [VoIPshield Systems (영문)](http://www.voipshield.com)의 Bogdan Materna
-   MS09-004의 문제점을 보고해 주신 [SEC Consult Vulnerability Lab (영문)](http://www.sec-consult.com/)의 Bernhard Mueller
-   MS09-005에서 설명한 여러 문제점을 보고해 주신 Fortinet, [FortiGuard Global Security Research Team (영문)](http://www.fortiguardcenter.com/)의 Bing Liu

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 1577-9700을 통해 [Microsoft 고객 지원 센터](http://go.microsoft.com/fwlink/?linkid=21131)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 2월 11일): 공지 요약이 게시되었습니다.
-   V2.0(2009년 2월 17일): Microsoft Exchange Server MAPI Client가 MS09-003에 영향을 받는 소프트웨어로 추가되었습니다.
-   V2.1(2009년 2월 26일): MS09-003의 Exchange Server 2003용 Exchange System Management Tools와 관련된 참고가 추가되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
