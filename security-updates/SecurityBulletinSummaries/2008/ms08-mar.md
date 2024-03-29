---
TOCTitle: 'MS08-MAR'
Title: 2008 년 3 월 Microsoft 보안 공지 요약
ms:assetid: 'ms08-mar'
ms:contentKeyID: 61230703
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms08-mar(v=Security.10)'
---

2008 년 3 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2008년 3월 12일 수요일 | 업데이트된 날짜: 2008년 4월 17일 목요일

**버전:** 2.0

이 공지 요약 목록에는 2008년 3월 발표된 보안 공지가 포함되어 있습니다.

2008년 3월 공지 발표와 함께 이 공지 요약은 2008년 3월 7일 게시된 공지 사전 알림을 대체합니다. 보안 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/security/bulletin/notify)을 참조하십시오.

Microsoft는 2008년 3월 13일 목요일(대한민국 표준시)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [3월 보안 공지 웹캐스트에 지금 등록하십시오](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357217&eventcategory=4&culture=ko-kr&countrycode=kr). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약](http://www.microsoft.com/korea/technet/security/current.aspx) 및 웹캐스트를 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안, 중요 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 섹션을 참조하십시오.

### 공지 정보

#### 요약

이번 달의 보안 공지는 다음과 같습니다(심각도 순).

긴급 (4)
--------


| 공지 번호                  | Microsoft 보안 공지 MS08-014                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Excel의 취약점으로 인한 원격 코드 실행 문제점(949029)**](http://technet.microsoft.com/security/bulletin/ms08-014)                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **요약**                   | 이 보안 업데이트는 Microsoft Office Excel에서 발견되어 비공개적으로 또는 공개적으로 보고된 여러 건의 취약점을 해결합니다. 사용자가 특수하게 조작된 Excel 파일을 열면 이 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템에 대해 완벽히 제어할 수 있습니다. 공격자가 프로그램을 설치하거나 데이터를 보고, 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 적용하기 위해 다시 시작할 필요는 없습니다.                                                                                                                                                                                                                                                                                                                                                                                             |
| **영향을 받는 소프트웨어** | **Microsoft Office.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

| 공지 번호                  | Microsoft 보안 공지 MS08-015                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Outlook의 취약점으로 인한 원격 코드 실행 문제점(949031)**](http://technet.microsoft.com/security/bulletin/ms08-015)                                                                                                                                                                                                                                                                                                                                                                                                    |
| **요약**                   | 이 보안 업데이트는 비공개적으로 보고된 Microsoft Office Outlook의 취약점을 해결합니다. 특수하게 조작된 mailto URI가 Outlook에 전달될 때 이 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 공격자가 프로그램을 설치하거나 데이터를 보고, 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. 단순히 Outlook 미리 보기 창에서 전자 메일을 보는 경우에는 이 취약점이 악용되지 않습니다. |
| **최대 심각도**            | [긴급](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 적용하기 위해 다시 시작할 필요는 없습니다.                                                                                                                                                                                                                                                                                                                                                                        |
| **영향을 받는 소프트웨어** | **Microsoft Office.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                                                    |

| 공지 번호                  | Microsoft 보안 공지 MS08-016                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Office의 취약점으로 인한 원격 코드 실행 문제점(949030)**](http://technet.microsoft.com/security/bulletin/ms08-016)                                                                                                                                                                                                                                                                                                                                                                                 |
| **요약**                   | 이 보안 업데이트는 Microsoft Office에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 사용자가 조작된 Office 파일을 열면 이 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 공격자가 프로그램을 설치하거나 데이터를 보고, 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 이 업데이트를 적용하기 위해 다시 시작할 필요는 없습니다.                                                                                                                                                                                                                                                                                                                                                    |
| **영향을 받는 소프트웨어** | **Microsoft Office.** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                                |

| 공지 번호                  | Microsoft 보안 공지 MS08-017                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **공지 제목**              | [**Microsoft Office Web Components의 취약점으로 인한 원격 코드 실행 문제점(933103)**](http://technet.microsoft.com/security/bulletin/ms08-017)                                                                                                                                                                                                                                                                                                                                                                                      |
| **요약**                   | 이 긴급 업데이트는 Microsoft Office Web Components에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점은 사용자가 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 공격자가 프로그램을 설치하거나 데이터를 보고, 변경하거나 삭제하고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다. |
| **최대 심각도**            | [긴급](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **취약점으로 인한 영향**   | 원격 코드 실행                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **검색**                   | Microsoft Baseline Security Analyzer로 컴퓨터를 검색하여 이 업데이트가 필요한지 확인할 수 있습니다. 업데이트를 적용한 다음 컴퓨터를 다시 시작해야 할 수 있습니다.                                                                                                                                                                                                                                                                                                                                                                   |
| **영향을 받는 소프트웨어** | **Microsoft Office Web Components** 자세한 내용은 영향을 받는 소프트웨어 및 다운로드 위치 섹션을 참조하십시오.                                                                                                                                                                                                                                                                                                                                                                                                                      |

검색, 배포 도구 및 지침
-----------------------


**보안 센터**

해당 조직에서 서버, 데스크톱, 모바일 컴퓨터에 적용해야 하는 소프트웨어 및 보안 업데이트를 관리합니다. 자세한 내용은 [TechNet Update Management Center (영문)](http://technet.microsoft.com/ko-kr/updatemanagement/default(en-us).aspx)를 참조하십시오. [TechNet Security Center](http://www.microsoft.com/korea/technet/security/default.mspx)는 Microsoft 제품의 보안에 대한 추가 정보를 제공합니다. 일반 사용자는 [가정의 보안](http://www.microsoft.com/korea/athome/security/default.mspx)을 방문하거나 “최신 보안 업데이트”를 클릭하여 이 정보를 볼 수도 있습니다.

보안 업데이트는 [Microsoft Update](http://update.microsoft.com/microsoftupdate/), [Windows Update](http://update.microsoft.com/) 및 [Office 업데이트](http://office.microsoft.com/ko-kr/downloads/)에서 제공됩니다. 보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서도 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.

마지막으로, 보안 업데이트는 [Microsoft Update 카탈로그](http://catalog.update.microsoft.com/)에서 다운로드할 수 있습니다. Microsoft Update 카탈로그는 보안 업데이트, 드라이버, 서비스 팩을 포함하여 Windows Update 및 Microsoft Update에서 제공하는 콘텐츠의 검색 가능한 목록입니다. 보안 공지 번호(예: "MS07-036")를 사용하여 검색하면 적용 가능한 모든 업데이트(다른 언어의 업데이트 포함)를 장바구니에 추가하고, 선택한 업데이트를 로컬 폴더에 다운로드할 수 있습니다. Microsoft Update 카탈로그에 대한 자세한 내용은 [Microsoft Update 카탈로그 FAQ](http://catalog.update.microsoft.com/v7/site/faq.aspx)를 참조하십시오.

**검색 및 배포 지침**

Microsoft는 이 달의 보안 업데이트를 위한 검색 및 배포 지침을 제공하였습니다. 이 지침은 IT 전문가가 Windows Update, Microsoft Update, Office 업데이트, MBSA(Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server(SMS), ESUIT(Extended Security Update Inventory Tool) 등의 다양한 도구를 사용하여 보안 업데이트를 용이하게 배포하는 방법을 이해하는 데 도움이 됩니다. 자세한 내용은 [Microsoft 기술 자료 문서 910723](http://support.microsoft.com/kb/910723)을 참조하십시오.

**Microsoft Baseline Security Analyzer**

관리자는 MBSA(Microsoft Baseline Security Analyzer)를 사용하여 로컬 및 원격 시스템에서 누락된 보안 업데이트 및 일반적인 보안 설정 오류를 검색할 수 있습니다. MBSA에 대한 자세한 내용을 보려면 [Microsoft Baseline Security Analyzer (영문)](http://www.microsoft.com/technet/security/tools/mbsahome.mspx)를 방문하십시오.

**Windows Server Update Services**

관리자는 WSUS(Windows Server Update Services)를 사용하여 Windows 2000 이상 운영 체제, Office XP 이상, Exchange Server 2003 그리고 Windows 2000 이상 운영 체제에 설치된 SQL Server 2000에 최신 중요 업데이트 및 보안 업데이트를 신속하게 안정적으로 배포할 수 있습니다.

Windows Server Update Services를 사용하여 이 보안 업데이트를 신속하게 배포하는 방법에 대한 자세한 내용은 [Windows Server Update Services](http://www.microsoft.com/korea/windowsserversystem/updateservices/evaluation/overview.mspx)를 참조하십시오.

**Systems Management Server**

Microsoft Systems Management Server(SMS)는 기업에서 업데이트 관리를 효율적으로 구성할 수 있는 솔루션입니다. 관리자는 SMS를 사용하여 보안 업데이트가 필요한 Windows 기반 시스템을 확인하고, 사용자의 업무 중단을 최소화하면서 기업 전체에 업데이트를 효율적으로 배포할 수 있습니다. SMS의 차기 릴리스인 System Center Configuration Manager 2007을 지금 사용할 수 있습니다([System Center Configuration Manager 2007 (영문)](http://technet.microsoft.com/ko-kr/library/bb735860(en-us).aspx) 참조). 관리자가 SMS 2003을 사용하여 보안 업데이트를 배포하는 방법에 대한 자세한 내용은 [SMS 2003 보안 패치 관리](http://www.microsoft.com/korea/smserver/evaluation/capabilities/patch.mspx)를 참조하십시오. SMS 2.0 사용자는[Software Updates Service Feature Pack (영문)](http://technet.microsoft.com/ko-kr/sms/bb676802(en-us).aspx)을 사용하여 보안 업데이트를 배포할 수도 있습니다. SMS에 대한 자세한 내용은 [Microsoft Systems Management Server](http://www.microsoft.com/korea/smserver/default.mspx)를 참조하십시오.

**참고** SMS는 Microsoft Baseline Security Analyzer와 Microsoft Office 검색 도구를 사용하여 보안 공지 업데이트 검색 및 배포와 관련된 다양한 기능을 지원합니다. 일부 소프트웨어 업데이트는 이러한 도구로 검색하지 못할 수도 있습니다. 이러한 경우 관리자는 SMS의 인벤토리 기능을 사용하여 특정 시스템을 대상으로 업데이트를 수행할 수 있습니다. 이 절차에 대한 자세한 내용은 [SMS 소프트웨어 배포 기능을 사용한 소프트웨어 업데이트 배포 (영문)](https://technet.microsoft.com/ko-KR/library///www.microsoft.com/technet/sms/2003/patchupdate.mspx(v=Security.10))를 참조하십시오. 일부 보안 업데이트 작업을 수행하려면 관리자 권한이 필요하며 컴퓨터를 다시 시작해야 할 수 있습니다. 관리자는 [SMS 2003 Administration Feature Pack (영문)](http://technet.microsoft.com/ko-kr/sms/bb676767(en-us).aspx) 및 [SMS 2.0 Administration Feature Pack (영문)](http://technet.microsoft.com/ko-kr/sms/bb676800(en-us).aspx)에서 제공되는 Elevated Rights Deployment Tool을 사용하여 이러한 업데이트를 설치할 수 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

이달의 업데이트:

-   Microsoft는 Microsoft Update(MU) 및 Windows Server Update Services(WSUS)를 통해 2개의 **비보안**, 중요 업데이트를 릴리스했습니다.
-   Microsoft는 Windows Update(WU) 및 WSUS를 통해 Windows용 **비보안**, 중요 업데이트 3건을 발표했습니다.


이 정보는 보안 공지 요약과 같은 날짜에 Microsoft Update, Windows Update, Windows Server Update Services를 통해 발표된 **비보안**, 중요 업데이트에만 해당됩니다. 다른 날짜에 발표된 **비보안** 업데이트 관련 정보는 제공되지 않습니다.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://www.microsoft.com/korea/technet/security/topics/patchmanagement.mspx)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/downloads/results.aspx?displaylang=ko&freetext=security_patch)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://update.microsoft.com/microsoftupdate/)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://www.microsoft.com/korea/communities/default.mspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://technet.microsoft.com/security/bulletin/policy)드립니다.

-   MS08-014에서 설명한 문제점을 보고해 주신 [SAIC (영문)](http://www.saic.com/)의 Mike Scott
-   MS08-014에서 설명한 문제점을 보고해 주신 [VeriSign (영문)](http://www.verisign.com/)의 Matt Richard
-   MS08-014에서 설명한 문제점을 보고해 주신 [iDefense Labs (영문)](http://labs.idefense.com/)의 Greg MacManus
-   MS08-014에서 설명한 문제점을 보고해 주신[JFE Systems (영문)](http://www.jfe-systems.com/)의 Yoshiya Sasaki
-   MS08-014에서 설명한 문제점을 보고해 주신 [Fortinet (영문)](http://www.fortinet.com/)의 Bing Liu
-   MS08-014에서 설명한 문제점을 보고해 주신[iDefense Labs (영문)](http://labs.idefense.com/)
-   MS08-014에서 설명한 문제점을 보고해 주신 [TippingPoint DVLabs (영문)](http://dvlabs.tippingpoint.com/)의 Cody Pierce
-   MS08-014에서 설명한 문제점을 보고해 주신 [Websense Security Labs (영문)](http://www.websense.com/)의 Moti Joseph 및 Dan Hubbard
-   MS08-015에서 설명한 문제점을 보고해 주신 [iDefense Labs (영문)](http://labs.idefense.com/)의 Greg MacManus
-   MS08-016에서 설명한 문제점을 보고해 주신 [Zero Day Initiative(ZDI) (영문)](http://www.zerodayinitiative.com/)의 Arnaud Dovi
-   MS08-016에서 설명한 문제점을 보고해 주신 익명 발견자
-   MS08-017에서 설명한 문제점을 보고해 주신 [VigilantMinds Inc. (영문)](http://www.vigilantminds.com/)의 Chris Ries
-   MS08-017에서 설명한 문제점을 보고해 주신 [NCNIPC (영문)](http://www.nipc.org.cn/)의 Xiao Hui
-   MS08-017에서 설명한 문제점을 보고해 주신 [Finjan (영문)](http://www.finjan.com/)의 Golan Yosef
-   MS08-017에서 설명한 문제점을 보고해 주신 [Finjan (영문)](http://www.finjan.com/)의 Yuval Ben-Itzhak

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle)를 참조하십시오.
-   기술 지원은 1577-9700을 통해 [Microsoft 고객 지원 센터](http://support.microsoft.com/)에서 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://support.microsoft.com/common/international.aspx)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0 (2008년 3월 12일): 공지 요약이 게시되었습니다.
-   V1.1 (2008년 3월 13일): BizTalk Server 2000 및 2002용 Microsoft Office Web Components 2000의 새로운 다운로드 링크를 반영하여 공지 요약이 업데이트되었습니다.
-   V1.2 (2008년 3월 27일): MS08-017 발견자를 추가하여 공지 요약이 업데이트되었습니다.
-   V2.0 (2008년 4월 17일): Microsoft Office Word Viewer 2003 및 Microsoft Office Word Viewer 2003이 MS08-016에 영향을 받는 소프트웨어로 추가되어 공지 요약이 업데이트되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*  
