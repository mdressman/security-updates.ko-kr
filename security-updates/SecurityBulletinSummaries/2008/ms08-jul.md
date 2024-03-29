---
TOCTitle: 'MS08-JUL'
Title: 2008 년 7 월 Microsoft 보안 공지 요약
ms:assetid: 'ms08-jul'
ms:contentKeyID: 61230701
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms08-jul(v=Security.10)'
---

2008 년 7 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2008년 7월 8일 화요일 | 업데이트된 날짜: 2009년 2월 11일 수요일

**버전:** 1.1

이 공지 요약 목록에는 2008년 7월 발표된 보안 공지가 포함되어 있습니다.

2008년 7월 공지 발표와 함께 이 공지 요약이 2008년 7월 3일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2008년 7월 9일 수요일(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [7월 보안 공지 웹캐스트에 지금 등록하십시오](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374629&eventcategory=4&culture=ko-kr&countrycode=kr). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://www.microsoft.com/korea/technet/security/current.mspx) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

#### 요약

이번 달의 보안 공지는 다음과 같습니다(심각도 순).

중요(4)
-------



| 공지 번호                  | Microsoft 보안 공지 MS08-040                                                                                                                                                                                                                                                                                                             |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft SQL Server의 취약점으로 인한 권한 상승 문제점 (941203)**](http://technet.microsoft.com/security/bulletin/ms08-040)                                                                                                                                                                                                          |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고된 취약점 4건을 해결합니다. 이러한 취약점은 공격자가 코드를 실행하여 영향을 받는 시스템을 완전히 제어할 수 있다는 점에서 심각합니다. 이렇게 되면 인증된 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 전체 관리자 권한이 있는 새 계정을 만들 수도 있습니다. |
| **최대 심각도**            | [중요](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                            |
| **취약점으로 인한 영향**   | 권한 상승                                                                                                                                                                                                                                                                                                                                |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 할 수 있습니다.                                                                                                                                                                        |
| **영향을 받는 소프트웨어** | **Microsoft Windows, Microsoft SQL Server.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                  |

| 공지 번호                  | Microsoft 보안 공지 MS08-038                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Windows 탐색기의 취약점으로 인한 원격 코드 실행 문제점 (950582)**](http://technet.microsoft.com/security/bulletin/ms08-038)                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **요약**                   | 이 보안 업데이트는 공개적으로 보고된 취약점 1건을 해결합니다. 사용자가 특수하게 조작된 검색 조건 저장 파일을 열고 저장하면 이 Windows 탐색기 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 사용자가 관리자 권한으로 로그온한 경우, 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [중요](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 설치하려면 다시 시작해야 합니다.                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |

| 공지 번호                  | Microsoft 보안 공지 MS08-037                                                                                                                                                                                                                                                                                           |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**DNS의 취약점으로 인한 스푸핑 허용 문제점 (953230)**](http://technet.microsoft.com/security/bulletin/ms08-037)                                                                                                                                                                                                       |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고되었으며 스푸핑을 허용할 수 있는 DNS(Windows Domain Name System)의 취약점 2건을 해결합니다. 이 취약점은 DNS 클라이언트와 DNS 서버에 모두 존재합니다. 이 취약점을 통해 원격 공격자가 인터넷을 통해 시스템에 대한 네트워크 트래픽을 공격자 자신의 시스템으로 리디렉션할 수 있습니다. |
| **최대 심각도**            | [중요](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                          |
| **취약점으로 인한 영향**   | 스푸핑                                                                                                                                                                                                                                                                                                                 |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 설치하려면 다시 시작해야 합니다.                                                                                                                                                                     |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                      |

| 공지 번호                  | Microsoft 보안 공지 MS08-039                                                                                                                                                                                                                                                                                                                         |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Exchange Server용 Outlook Web Access의 취약점으로 인한 권한 상승 문제점 (953747)**](http://technet.microsoft.com/security/bulletin/ms08-039)                                                                                                                                                                                                      |
| **요약**                   | 이 보안 업데이트는 Microsoft Exchange Server용 OWA(Outlook Web Access)에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점 악용에 성공한 공격자는 개별 OWA 클라이언트의 세션 데이터에 액세스하여 권한을 상승시킬 수 있습니다. 그런 다음 공격자가 개별 클라이언트의 OWA 세션에서 사용자가 수행 가능한 모든 작업을 수행할 수 있습니다. |
| **최대 심각도**            | [중요](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                        |
| **취약점으로 인한 영향**   | 권한 상승                                                                                                                                                                                                                                                                                                                                            |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 할 수 있습니다.                                                                                                                                                                                    |
| **영향을 받는 소프트웨어** | **Microsoft Windows.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                    |

영향을 받는 소프트웨어 및 다운로드 위치
---------------------------------------


**이 표를 어떻게 사용합니까?**  

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 필요한 보안 업데이트가 있는지 확인합니다. 소프트웨어 프로그램 또는 구성 요소가 나열되어 있는 경우 사용할 수 있는 소프트웨어 업데이트의 하이퍼링크와 해당 소프트웨어 업데이트의 심각도가 함께 나열됩니다.

**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

#### Windows 운영 체제

 
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
<th colspan="4">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
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
해당 사항 없음
</td>
<td style="border:1px solid black;">
DNS 클라이언트 업데이트:  
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=269c219c-9d6b-4b12-b621-c70cd07cdd22)  
(중요)  
DNS 서버 업데이트:  
[Microsoft Windows 2000 Server 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=332aa92f-a1ad-42a0-87d0-485d2d41335b)  
(중요)
</td>
</tr>
<tr>
<th colspan="4">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**최대 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
DNS 클라이언트 업데이트:  
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=ed989a33-7a9e-4423-93a8-b38907467cdf)  
(중요)  
해당 DNS 서버 업데이트 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
DNS 클라이언트 업데이트:  
[Windows XP Professional x64 Edition 및 Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=a2b016fa-b108-4e8e-b41b-4ca89002907b)  
(중요)  
해당 DNS 서버 업데이트 없음
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine(WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=1c0ae18b-1f17-44b3-a337-b36e7de437a7)  
(KB948110)  
(중요)  
[Windows Internal Database(WYukon) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf)  
(KB948109)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
DNS 클라이언트 업데이트:  
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=4ef5033c-9843-4e0b-bfad-fcaf05d7dab9)  
(중요)  
DNS 서버 업데이트:  
[Windows Server 2003 서비스 팩 1 및 Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d1fcb794-e6a5-4c28-b3b3-9cd88f468a42)  
(중요)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine(WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=1c0ae18b-1f17-44b3-a337-b36e7de437a7)  
(KB948110)  
(중요)  
[Windows Internal Database(WYukon) x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf)  
(KB948109)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
DNS 클라이언트 업데이트:  
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=66624a1f-38bf-4af7-936d-3131474ffe1f)  
(중요)  
DNS 서버 업데이트:  
[Windows Server 2003 x64 Edition 및 Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=040a1ba8-21b0-439e-bf21-1acd1c43b162)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
DNS 클라이언트 업데이트:  
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=facc80da-61d6-49c5-872d-a1980b66ae3e)  
(중요)  
DNS 서버 업데이트:  
[Windows Server 2003 SP1(Itanium 기반 시스템용) 및 Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c63e3ee6-6055-4313-b0f1-fec7408886bb)  
(중요)
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
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
[Windows Vista 및 Windows Vista 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=06739ca6-7368-4acb-bb67-7e8146071a29)  
(중요)
</td>
<td style="border:1px solid black;">
해당 DNS 클라이언트 업데이트 없음  
해당 DNS 서버 업데이트 없음
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
[Windows Vista x64 Edition 및 Windows Vista x64 Edition 서비스 팩 1](http://www.microsoft.com/downloads/details.aspx?familyid=74ea0893-7c2f-4fad-ad27-588ad953b046)  
(중요)
</td>
<td style="border:1px solid black;">
해당 DNS 클라이언트 업데이트 없음  
해당 DNS 서버 업데이트 없음
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 최대 심각도**
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Internal Database(WYukon) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf)\*  
(KB948109)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=189a4170-b495-4904-9cbd-209e7494d303)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 DNS 클라이언트 업데이트 없음  
DNS 서버 업데이트:  
[Windows Server 2008(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=1fcea8f4-b233-42e1-b913-c4fcae276c7b)\*  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Internal Database(WYukon) x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf)\*  
(KB948109)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=85d8701d-f8c7-4079-8a21-a3a9d5ba71ce)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 DNS 클라이언트 업데이트 없음  
DNS 서버 업데이트:  
[Windows Server 2008(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=afac5bbc-71fa-457b-8b0a-f5902d37bfd0)\*  
(중요)
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
[Windows Server 2008(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b30ee4f0-850f-4ff3-86a4-663603a0a802)  
(중요)
</td>
<td style="border:1px solid black;">
해당 DNS 클라이언트 업데이트 없음  
해당 DNS 서버 업데이트 없음
</td>
</tr>
</table>
 
**\*Windows Server 2008 Server Core 설치는 영향을 받지 않습니다.** 지원 대상인 Windows Server 2008 에디션에 대해 이 업데이트의 심각도는 Windows Server 2008에 Server Core 설치 옵션의 사용 여부와 상관없이 동일하게 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 [Server Core (영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)를 참조하십시오. 참고: Server Core 설치 옵션은 Windows Server 2008의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교(영문)](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)를 참조하십시오.

#### Microsoft Server 소프트웨어

 
<p></p>
<table style="border:1px solid black;">
<caption>Microsoft SQL Server</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-040"><strong>MS08-040</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지 최대 심각도</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 7.0 서비스 팩 4</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0">SQL Server 7.0 서비스 팩 4</a><br />
(KB948113)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0">SQL Server 7.0 서비스 팩 4</a><br />
(KB948113)<br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQL Server 2000 서비스 팩 4</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4fd1f86a-94a2-43d8-9b0a-774c81426d9e">SQL Server 2000 서비스 팩 4</a><br />
(KB948110)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8316bc5e-8c2d-4710-8acc-b815ccc81cd4">SQL Server 2000 서비스 팩 4</a><br />
(KB948111)<br />
(중요)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2000 Itanium 기반 에디션 서비스 팩 4</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4fd1f86a-94a2-43d8-9b0a-774c81426d9e">SQL Server 2000 Itanium 기반 에디션 서비스 팩 4</a><br />
(KB948110)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8316bc5e-8c2d-4710-8acc-b815ccc81cd4">SQL Server 2000 Itanium 기반 에디션 서비스 팩 4</a><br />
(KB948111)<br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQL Server 2005 서비스 팩 2</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">SQL Server 2005 서비스 팩 2</a><br />
(KB948109)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">SQL Server 2005 서비스 팩 2</a><br />
(KB948108)<br />
(중요)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005 x64 Edition 서비스 팩 2</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">SQL Server 2005 x64 Edition 서비스 팩 2</a><br />
(KB948109)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">SQL Server 2005 x64 Edition 서비스 팩 2</a><br />
(KB948108)<br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQL Server 2005 SP2(Itanium 기반 시스템용)</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">SQL Server 2005 SP2(Itanium 기반 시스템용)</a><br />
(KB948109)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">SQL Server 2005 SP2(Itanium 기반 시스템용)</a><br />
(KB948108)<br />
(중요)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Data Engine(MSDE) 1.0 서비스 팩 4</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0">Microsoft Data Engine(MSDE) 1.0 서비스 팩 4</a><br />
(KB948113)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0">Microsoft Data Engine(MSDE) 1.0 서비스 팩 4</a><br />
(KB948113)<br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft SQL Server 2000 Desktop Engine(MSDE 2000) 서비스 팩 4</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4fd1f86a-94a2-43d8-9b0a-774c81426d9e">Microsoft SQL Server 2000 Desktop Engine(MSDE 2000) 서비스 팩 4</a><br />
(KB948110)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8316bc5e-8c2d-4710-8acc-b815ccc81cd4">Microsoft SQL Server 2000 Desktop Engine(MSDE 2000) 서비스 팩 4</a><br />
(KB948111)<br />
(중요)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft SQL Server 2005 Express Edition 서비스 팩 2</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">Microsoft SQL Server 2005 Express Edition 서비스 팩 2</a><br />
(KB948109)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">Microsoft SQL Server 2005 Express Edition 서비스 팩 2</a><br />
(KB948108)<br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">고급 서비스가 포함된 Microsoft SQL Server 2005 Express Edition 서비스 팩 2</td>
<td style="border:1px solid black;">GDR 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">고급 서비스가 포함된 Microsoft SQL Server 2005 Express Edition 서비스 팩 2</a><br />
(KB948109)<br />
(중요)<br />
<br />
QFE 업데이트:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">고급 서비스가 포함된 Microsoft SQL Server 2005 Express Edition 서비스 팩 2</a><br />
(KB948108)<br />
(중요)</td>
</tr>
</tbody>
</table>
 

 
<p></p>
<table style="border:1px solid black;">
<caption>Microsoft Exchange Server</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 번호</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-039"><strong>MS08-039</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>공지 최대 심각도</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>중요</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Server 2003 서비스 팩 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e099c1d1-5af6-4d6c-b735-9599412b3131">Microsoft Exchange Server 2003 서비스 팩 2</a><br />
(중요)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Exchange Server 2007</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=086a2a13-a1de-4b1d-bd12-b148bfd2dafa">Microsoft Exchange Server 2007</a><br />
(중요)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Server 2007 서비스 팩 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=63e7f26c-92a8-4264-882d-f96b348c96ab">Microsoft Exchange Server 2007 서비스 팩 1</a><br />
(중요)</td>
</tr>
</tbody>
</table>
 

검색, 배포 도구 및 지침
-----------------------


**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center(영문)](http://go.microsoft.com/fwlink/?linkid=69903)를 참조하십시오. [TechNet Security Center](http://www.microsoft.com/korea/technet/security/default.mspx)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://www.microsoft.com/korea/athome/security/default.mspx)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 및 [Office 업데이트](http://go.microsoft.com/fwlink/?linkid=21135)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://go.microsoft.com/fwlink/?linkid=96155)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://go.microsoft.com/fwlink/?linkid=97900)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), ESUIT(Extended Security Update Inventory Tool) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](http://support.microsoft.com/kb/910723)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer(영문)](http://go.microsoft.com/fwlink/?linkid=21134)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007(영문)](http://technet.microsoft.com/en-us/library/bb735860.aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service Feature Pack(영문)](http://go.microsoft.com/fwlink/?linkid=33340)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포(영문)](http://go.microsoft.com/fwlink/?linkid=33341)를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack(영문)](http://go.microsoft.com/fwlink/?linkid=33387) 및 [SMS 2.0 Administration Feature Pack(영문)](http://go.microsoft.com/fwlink/?linkid=21161)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

**UCE(Update Compatibility Evaluator) 및 ACT(Application Compatibility Toolkit)**

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit) 5.0 (영문)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator) (영문)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 2008년에 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명
-   [Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트(영문)](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://www.microsoft.com/korea/technet/security/topics/patchmanagement.mspx)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서 다운로드할 수 있으며"security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://www.microsoft.com/korea/communities/default.mspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://technet.microsoft.com/security/bulletin/policy)드립니다.

-   MS08-037에서 설명한 문제점을 보고해 주신 [IOActive (영문)](http://www.ioactive.com/)의 Dan Kaminsky
-   MS08-039에서 설명한 문제점 2건을 보고해 주신 [Context Information Security (영문)](http://www.contextis.co.uk/)의 Michael Jordan
-   MS08-040에서 설명한 문제점을 보고해 주신 익명 발견자
-   MS08-040에서 설명한 문제점을 보고해 주신 익명 발견자
-   MS08-040에서 설명한 문제점을 보고하고 [iDefense VCP (영문)](http://labs.idefense.com/)와 협력해 주신 [Insomnia Security (영문)](http://www.insomniasec.com/)의 Brett Moore
-   MS08-040에서 설명한 문제점을 보고해 주신 익명 발견자

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 1577-9700을 통해 [Microsoft 고객 지원 센터](http://go.microsoft.com/fwlink/?linkid=21131)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0 (2008년 7월 8일): 공지 요약이 게시되었습니다.
-   V1.1(2009년 2월 12일): MS08-040의 Windows 운영 체제의 영향을 받는 소프트웨어 및 다운로드 위치 표에서 Microsoft Windows 2000 서비스 팩 4의 Microsoft SQL Server 2000 Desktop Engine(WMSDE)에 대한 잘못된 참조가 제거되었습니다

*Built at 2014-04-18T12:27:44Z-07:00*
