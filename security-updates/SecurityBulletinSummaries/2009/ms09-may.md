---
TOCTitle: 'MS09-MAY'
Title: 2009 년 5 월 Microsoft 보안 공지 요약
ms:assetid: 'ms09-may'
ms:contentKeyID: 61230716
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms09-may(v=Security.10)'
---


2009 년 5 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2009년 5월 13일 수요일 | 업데이트된 날짜: 2009년 6월 10일 수요일

**버전:** 2.0

이 공지 요약 목록에는 2009년 5월 발표된 보안 공지가 포함되어 있습니다.

2009년 5월 공지 발표와 함께 이 공지 요약이 2009년 5월 7일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2009년 5월 13일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [5월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032395223). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점 (967340)</strong><br />
<br />
이 보안 업데이트는 일반에 공개된 취약점 한 가지와 비공개적으로 보고된 몇 가지 취약점을 해결합니다. 사용자가 특수하게 조작된 PowerPoint 파일을 열면 이 Microsoft Office PowerPoint 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 중 어느 것이든 성공적으로 악용한 경우 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">긴급</a><br />
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

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >공지 번호</th>
<th style="border:1px solid black;" >공지 제목</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >악용 가능성 인덱스 평가</th>
<th style="border:1px solid black;" >주요 정보</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0220">CVE-2009-0220</a></td>
<td style="border:1px solid black;">/GS를 사용하지 않고 컴파일된 Office 버전:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">Office 2003 서비스 팩 3 이상의 Office를 컴파일할 때 /GS 보호 기능을 사용하는 것은 해당 시스템에 대한 위험을 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 악용 코드 기능 불가능 수준으로 크게 줄이는 이 취약점에 대한 완화 요소입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0221">CVE-2009-0221 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2 (영문)</strong></a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0222">CVE-2009-0222 (영문)</a></td>
<td style="border:1px solid black;">/GS를 사용하지 않고 컴파일된 Office 버전:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">Office 2003 서비스 팩 3 이상의 Office를 컴파일할 때 /GS 보호 기능을 사용하는 것은 해당 시스템에 대한 위험을 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능 수준으로 크게 줄이는 이 취약점에 대한 완화 요소입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0223">CVE-2009-0223 (영문)</a></td>
<td style="border:1px solid black;">/GS를 사용하지 않고 컴파일된 Office 버전:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">Office 2003 서비스 팩 3 이상의 Office를 컴파일할 때 /GS 보호 기능을 사용하는 것은 해당 시스템에 대한 위험을 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능 수준으로 크게 줄이는 이 취약점에 대한 완화 요소입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0224">CVE-2009-0224 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2 (영문)</strong></a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0225">CVE-2009-0225 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2 (영문)</strong></a> - 비일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0226">CVE-2009-0226 (영문)</a></td>
<td style="border:1px solid black;">/GS를 사용하지 않고 컴파일된 Office 버전:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">Office 2003 서비스 팩 3 이상의 Office를 컴파일할 때 /GS 보호 기능을 사용하는 것은 해당 시스템에 대한 위험을 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능 수준으로 크게 줄이는 이 취약점에 대한 완화 요소입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0227">CVE-2009-0227 (영문)</a></td>
<td style="border:1px solid black;">/GS를 사용하지 않고 컴파일된 Office 버전:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">Office 2003 서비스 팩 3 이상의 Office를 컴파일할 때 /GS 보호 기능을 사용하는 것은 해당 시스템에 대한 위험을 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능 수준으로 크게 줄이는 이 취약점에 대한 완화 요소입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0556">CVE-2009-0556 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;"><strong>이 취약점은 현재 인터넷 생태계에서 악용되고 있습니다.</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점 (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1128">CVE-2009-1128 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점 (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1129">CVE-2009-1129 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점 (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1130">CVE-2009-1130 (영문)</a></td>
<td style="border:1px solid black;">/GS를 사용하지 않고 컴파일된 Office 버전:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">Office 2003 서비스 팩 3 이상의 Office를 컴파일할 때 /GS 보호 기능을 사용하는 것은 해당 시스템에 대한 위험을 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능 수준으로 크게 줄이는 이 취약점에 대한 완화 요소입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1131">CVE-2009-1131 (영문)</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-017">MS09-017</a></td>
<td style="border:1px solid black;">Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1137">CVE-2009-1137 (영문)</a></td>
<td style="border:1px solid black;">/GS를 사용하지 않고 컴파일된 Office 버전:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1 (영문)</strong></a> - 일관적인 악용 코드 가능</td>
<td style="border:1px solid black;">Office 2003 서비스 팩 3 이상의 Office를 컴파일할 때 /GS 보호 기능을 사용하는 것은 해당 시스템에 대한 위험을 <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3 (영문)</strong></a> - 악용 코드 기능 불가능 수준으로 크게 줄이는 이 취약점에 대한 완화 요소입니다.</td>
</tr>
</tbody>
</table>
  
영향을 받는 소프트웨어 및 다운로드 위치  
---------------------------------------
  
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.
  
**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.
  
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
Microsoft Office 제품군, 시스템 및 구성 요소  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://technet.microsoft.com/security/bulletin/ms09-017)
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
Microsoft Office 2000 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2000 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=f443312a-ac74-4ebc-a4ac-7a756aa67894&displaylang=ko)  
(KB957790)  
(긴급)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=a24ec7ab-c1c7-4ddb-8b6e-107f1af67f49&displaylang=ko)  
(KB957781)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=ccfa978b-3340-40db-a45d-c880ba36b106&displaylang=ko)  
(KB957784)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System 서비스 팩 1 및 2007 Microsoft Office System 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2007 서비스 팩 1 및 Microsoft Office PowerPoint 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=11f8380f-ffb6-4c22-a89c-3dc55d0f9834&displaylang=ko)\*  
(KB957789)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://technet.microsoft.com/security/bulletin/ms09-017)
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
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550)  
(KB969661)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58)  
(KB971822)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6)  
(KB971824)  
(중요)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
기타 Office 소프트웨어
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://technet.microsoft.com/security/bulletin/ms09-017)
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
PowerPoint Viewer
</td>
<td style="border:1px solid black;">
[PowerPoint Viewer 2003](http://www.microsoft.com/downloads/details.aspx?familyid=6a57e6ed-bd24-406f-87bb-117391e083e0&displaylang=ko)  
(KB969615)  
(중요)  
[PowerPoint Viewer 2007 서비스 팩 1 및 PowerPoint Viewer 2007 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=141b8338-5c52-4326-a9e4-d2f2d8940d9c&displaylang=ko)  
(KB970059)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word, Excel, PowerPoint 2007 파일 형식용 Microsoft Office 호환 기능 팩
</td>
<td style="border:1px solid black;">
[Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 1용 Microsoft Office 호환 기능 팩 및 Word, Excel, PowerPoint 2007 파일 형식 서비스 팩 2용 Microsoft Office 호환 기능 팩](http://www.microsoft.com/downloads/details.aspx?familyid=e1d3a4c3-538a-4f98-8d60-250803a80e2a&displaylang=ko)  
(KB969618)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](http://www.microsoft.com/downloads/details.aspx?familyid=628280fe-e035-4274-85f2-393d9bad543c)  
(KB967043)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=f6fa110e-45c6-450f-ae47-c89a06e3f762)  
(KB967044)  
(중요)
</td>
</tr>
</table>
 
**MS09-017 참고 사항**

Microsoft는 Microsoft Office 2004 for Mac, Microsoft Office 2008 for Mac, Open XML File Format Converter for Mac, Microsoft Works 8.5 및 Microsoft Works 9에 대한 보안 업데이트 패키지를 제공하기 위해 MS09-017을 릴리스했습니다. 위 소프트웨어가 설치된 고객은 이 업데이트를 즉시 적용해야 합니다.

MS09-017이 처음 릴리스되었을 때 이들 보안 업데이트 패키지는 아직 개발 중이었습니다. 당시 Microsoft는 대부분의 고객을 위험으로부터 보호하는 전체 제품 라인에 대한 업데이트 패키지가 정기적인 보안 공지 발표 주기에 맞춰 준비되었기 때문에 MS09-017을 릴리스했습니다. 이 최신 MS09-017 릴리스는 이 공지에서 언급된 취약점의 영향을 받는 소프트웨어에 대한 모든 업데이트를 포함하고 있습니다.

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

-   MS09-017에서 설명한 문제점을 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)와 협력하여 보고해 주신 익명 연구자
-   MS09-017에서 설명한 두 가지 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Sean Larsson
-   MS09-017에서 설명한 문제점을 보고해 주신 [VUPEN Security (영문)](http://www.vupen.com/)의 Nicolas Joly
-   MS09-017에서 설명한 여러 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Marsu Pilami
-   MS09-017에서 설명한 문제점을 보고해 주신 [VUPEN Security (영문)](http://www.vupen.com/)의 Nicolas Joly
-   MS09-017에서 설명한 문제점을 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Marsu Pilami
-   MS09-017에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 [team509 (영문)](http://www.team509.com/)의 Ling 및 Wushi와 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Sean Larsson
-   MS09-017에서 설명한 문제점을 보고해 주신 [Secunia (영문)](http://secunia.com/)의 Carsten H. Eiram

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2009년 5월 13일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 5월 14일): 지원되는 Microsoft Office PowerPoint 2007 버전에 대한 보안 업데이트 KB969618 및 KB957789와 관련하여 잘못된 MS09-017 참고 사항이 제거되었습니다.
-   V2.0(2009년 6월 10일): Microsoft Office 2004 for Mac, Microsoft Office 2008 for Mac, Open XML File Format Converter for Mac, Microsoft Works 8.5 및 Microsoft Works 9에 대한 보안 업데이트 패키지를 제공하기 위해 MS09-017이 릴리스되었으며 이를 알리기 위해 공지가 개정되었습니다. 위 소프트웨어가 설치된 고객은 이 업데이트를 즉시 적용해야 합니다.

*Built at 2014-04-18T12:27:44Z-07:00*
