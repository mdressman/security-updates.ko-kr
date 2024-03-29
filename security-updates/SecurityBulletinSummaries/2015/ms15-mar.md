---
TOCTitle: 'MS15-MAR'
Title: 2015년 3월 Microsoft 보안 공지 요약
ms:assetid: 'ms15-mar'
ms:contentKeyID: 64978243
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms15-mar(v=Security.10)'
---

2015년 3월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2015년 3월 10일

**버전:** 1.0

이 공지 요약 목록에는 2015년 3월 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://technet.microsoft.com/ko-kr/security/dd252948.aspx)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 절을 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향을 받는 소프트웨어에 대한 자세한 내용은 다음 항목 **영향을 받는 소프트웨어**를 참조하십시오.

<p> </p>
<table style="border:1px solid black;">
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
및 취약점 영향</strong></td>
<td style="border:1px solid black;"><strong>다시 시작 요구 사항</strong></td>
<td style="border:1px solid black;"><strong>알려진<br />
문제</strong></td>
<td style="border:1px solid black;"><strong>영향을 받는<br />
소프트웨어</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 누적 보안 업데이트(3032359)</strong><br />
이 보안 업데이트는 Internet Explorer에서 발견된 취약점을 해결합니다. 이 중에서 가장 심각한 취약점은 사용자가 Internet Explorer를 사용하여 특수하게 조작된 웹 페이지를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 권한을 얻을 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
업데이트 포함)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-019">MS15-019</a></td>
<td style="border:1px solid black;"><strong>VBScript 스크립팅 엔진의 취약점으로 인한 원격 코드 실행 문제(3040297)</strong> <br />
이 보안 업데이트는 Microsoft Windows의 VBScript 스크립팅 엔진의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 웹 사이트를 방문할 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우, 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-020">MS15-020</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows의 취약성으로 인한 원격 코드 실행 문제(3041836) </strong><br />
이 보안 업데이트는 Microsoft Windows에서 발견된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 웹 사이트를 탐색하도록 또는 특수하게 조작된 파일을 열거나 특수하게 조작된 DLL 파일이 포함된 작업 디렉토리의 파일을 열도록 사용자를 성공적으로 유인하는 경우 원격 코드가 실행될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;"><strong>Adobe 글꼴 드라이버의 취약점으로 인한 원격 코드 실행 문제(3032323)</strong> <br />
이 보안 업데이트는 Microsoft Windows에서 발견된 취약점을 해결합니다. 이 중에서 가장 심각한 취약점으로 인해 사용자가 특수하게 조작된 파일 또는 웹 사이트를 볼 경우 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템에 대해 완벽히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office의 취약점으로 인한 원격 코드 실행 문제(3038999)</strong> <br />
이 보안 업데이트는 Microsoft Office에서 발견된 취약점을 해결합니다. 이 중에서 가장 심각한 취약점으로 인해 사용자가 특수하게 조작된 Microsoft Office 파일을 열면 원격 코드 실행이 허용될 수 있습니다. 이러한 취약점 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">긴급</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3038999/ko">3038999</a></td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;"><strong>커널 모드 드라이버의 취약점으로 인한 권한 상승 문제(3034344) </strong><br />
이 보안 업데이트는 Microsoft Windows에서 발견된 취약점을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 시스템에 로그온하여 권한을 상승시키도록 설계된 특수하게 조작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제하거나, 모든 관리자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-024">MS15-024</a></td>
<td style="border:1px solid black;"><strong>PNG 처리의 취약점으로 인한 정보 공개 문제(3035132)</strong> <br />
이 보안 업데이트는 Microsoft Windows에서 발견된 취약점을 해결합니다. 공격자가 특수하게 조작된 PNG 이미지가 포함된 웹 사이트를 방문하도록 사용자를 유인하는 경우 이 취약점으로 인해 정보가 공개될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
정보 공개</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-025">MS15-025</a></td>
<td style="border:1px solid black;"><strong>Windows 커널의 취약점으로 인한 권한 상승 문제점(3038680)</strong><br />
이 보안 업데이트는 Microsoft Windows에서 발견된 취약점을 해결합니다. 가장 위험한 취약점으로 인해 공격자가 영향을 받는 시스템에 로그온하여 특수하게 조작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다. 이 취약점 악용에 성공한 공격자는 영향을 받는 시스템에 로그온한 다른 사용자 계정의 보안 컨텍스트에서 임의 코드를 실행할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제하거나, 잠재적으로 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3038680/ko">3038680</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server의 취약점으로 인한 권한 상승 문제(3040856)</strong> <br />
이 보안 업데이트는 Microsoft Exchange Server에서 발견된 취약점을 해결합니다. 이 중에서 가장 심각한 취약점으로 인해 사용자가 특수하게 조작된 URL을 클릭하여 대상 Outlook Web App 사이트로 유인되는 경우 권한 상승 문제가 발생할 수 있습니다. 공격자는 강제로 사용자가 특수하게 조작된 웹 사이트를 방문하도록 만들 수 없습니다. 대신 공격자는 사용자가 인스턴트 메신저 또는 전자 메일 메시지의 링크를 클릭하여 공격자의 웹 사이트를 방문하고 특수하게 조작된 URL을 클릭하도록 유인하는 것이 일반적입니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
권한 상승</td>
<td style="border:1px solid black;">재 시작할 필요 없음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-027">MS15-027</a></td>
<td style="border:1px solid black;"><strong>NETLOGON의 취약점으로 인한 스푸핑 허용 문제(3002657)</strong><br />
이 보안 업데이트는 Microsoft Windows에서 발견된 취약점을 해결합니다. 도메인 참여 시스템에 로그온한 공격자가 가장된 사용자 또는 시스템으로 다른 도메인 참여 시스템과 연결을 설정할 수 있도록 특수하게 조작된 응용 프로그램을 실행하는 경우 이 취약점으로 인해 스푸핑이 발생할 수 있습니다. 공격자가 도메인 참여 시스템에 로그온하고 네트워크 트래픽을 관찰할 수 있어야 합니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
스푸핑</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-028">MS15-028</a></td>
<td style="border:1px solid black;"><strong>Windows 작업 스케줄러 취약점으로 인한 보안 기능 우회(3030377) </strong><br />
이 보안 업데이트는 Microsoft Windows에서 발견된 취약점을 해결합니다. 이 취약점으로 인해 권한이 제한된 사용자가 영향을 받는 시스템에서 작업 스케줄러를 이용하여 실행할 권한이 없는 파일을 실행할 수 있습니다. 이 취약점을 성공적으로 악용한 공격자는 ACL 확인을 우회하고 권한 있는 실행 파일을 실행할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-029">MS15-029</a></td>
<td style="border:1px solid black;"><strong>Windows 사진 디코더 구성 요소의 취약점으로 인한 정보 공개 문제(3035126)</strong> <br />
이 보안 업데이트는 Microsoft Windows에서 발견된 취약점을 해결합니다. 이 취약점으로 인해 사용자가 특수하게 조작된 JPEG XR(.JXR) 이미지가 포함된 웹 사이트를 탐색할 경우 정보가 공개될 수 있습니다. 이 취약점으로 인해 공격자가 직접 코드를 실행하거나 해당 사용자 권한을 상승시킬 수는 없지만 영향을 받는 시스템의 손상을 악화시키는 데 사용할 수 있는 정보를 얻을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
정보 공개</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-030">MS15-030</a></td>
<td style="border:1px solid black;"><strong>원격 데스크톱 프로토콜의 취약성으로 인한 서비스 거부 문제(3039976) </strong><br />
이 보안 업데이트는 Microsoft Windows에서 발견된 취약점을 해결합니다. 이 취약점으로 인해 공격자가 메모리의 개체를 제대로 해제하지 못하는 여러 RDP(원격 데스크톱 프로토콜) 세션을 만드는 경우 서비스 거부가 발생할 수 있습니다. 기본적으로 RDP는 모든 Windows 운영 체제에서 사용되도록 설정되지 않습니다. RDP가 사용 가능하지 않는 시스템은 취약하지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-031">MS15-031</a></td>
<td style="border:1px solid black;"><strong>Schannel의 취약성으로 인한 보안 기능 우회 문제(3046049) <br />
</strong>이 보안 업데이트는 Windows 운영 체제만이 아닌 업계 전반의 문제인 공개된 FREAK 기술이 악용되도록 하는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 메시지 가로채기(man-in-the-middle) 공격자가 TLS 연결에서 RSA 키의 키 길이를 EXPORT 등급 길이로 강제로 다운그레이드할 수 있습니다. 안전하지 않은 암호 그룹으로 원격 TLS 서버에 연결하는 데 Schannel을 사용하는 모든 Windows 운영 체제가 영향을 받습니다.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ko-kr/security/gg309177.aspx">중요</a> <br />
보안 기능 우회</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3046049/ko">3046049</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
<span id="sectionToggle1"></span>
다음 표에는 이달에 해결한 각 취약점의 악용 가능성 평가가 나와 있습니다. 취약점은 공지 ID 및 CVE ID 순으로 나열되어 있습니다. 공지에서 심각도가 긴급 또는 중요인 취약점만 포함됩니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 설치해야 할 수 있는 각 보안 업데이트에 대한 보안 공지 발표 후 30일 이내의 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토하십시오. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.
  
아래 열에서 "최신 소프트웨어 릴리스"는 관련 소프트웨어를 나타내며 "이전 소프트웨어 릴리스"는 공지의 "영향을 받는 소프트웨어" 및 "영향을 받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.
  
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>공지 ID</strong></td>
<td style="border:1px solid black;"><strong>취약점 제목</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>최신 소프트웨어 릴리스에 대한<br />
악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>이전 소프트웨어 릴리스에 대한<br />
악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>서비스 거부<br />
악용 가능성 평가</strong></td>
<td style="border:1px solid black;"><strong>주요 정보</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">VBScript 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0032">CVE-2015-0032</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0056">CVE-2015-0056</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0072">CVE-2015-0072</a></td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">0- 악용 검색됨</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이 취약점은 공개적으로 보고되었습니다.<br />
<br />
이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0099">CVE-2015-0099</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0100">CVE-2015-0100</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1622">CVE-2015-1622</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1623">CVE-2015-1623</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1624">CVE-2015-1624</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1625">CVE-2015-1625</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 공개적으로 보고되었습니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1626">CVE-2015-1626</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 권한 상승 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1627">CVE-2015-1627</a></td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">2 - 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약성입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-018">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1634">CVE-2015-1634</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-019">MS15-019</a></td>
<td style="border:1px solid black;">VBScript 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0032">CVE-2015-0032</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-020">MS15-020</a></td>
<td style="border:1px solid black;">WTS 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0081">CVE-2015-0081</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-020">MS15-020</a></td>
<td style="border:1px solid black;">DLL 플랜팅 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0096">CVE-2015-0096</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 글꼴 드라이버 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0074">CVE-2015-0074</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 글꼴 드라이버 정보 공개 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0087">CVE-2015-0087</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이는 정보 공개 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 글꼴 드라이버 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0088">CVE-2015-0088</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 글꼴 드라이버 정보 공개 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0089">CVE-2015-0089</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 정보 공개 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 글꼴 드라이버 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0090">CVE-2015-0090</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 글꼴 드라이버 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0091">CVE-2015-0091</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 글꼴 드라이버 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0092">CVE-2015-0092</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-021">MS15-021</a></td>
<td style="border:1px solid black;">Adobe 글꼴 드라이버 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0093">CVE-2015-0093</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft Office 구성 요소 해제 후 사용 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0085">CVE-2015-0085</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft Office 메모리 손상 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0086">CVE-2015-0086</a></td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">1- 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft Word 로컬 영역 원격 코드 실행 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0097">CVE-2015-0097</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">(없음)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft SharePoint XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1633">CVE-2015-1633</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-022">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft SharePoint XSS 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1636">CVE-2015-1636</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 메모리 정보 공개 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0077">CVE-2015-0077</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 정보 공개 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;">Win32k 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0078">CVE-2015-0078</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 메모리 정보 공개 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0094">CVE-2015-0094</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 정보 공개 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-023">MS15-023</a></td>
<td style="border:1px solid black;">Microsoft Windows 커널 메모리 정보 공개 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0095">CVE-2015-0095</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">영구</td>
<td style="border:1px solid black;">이는 정보 공개 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-024">MS15-024</a></td>
<td style="border:1px solid black;">변형된 PNG 구문 분석 정보 공개 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0080">CVE-2015-0080</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 정보 공개 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-025">MS15-025</a></td>
<td style="border:1px solid black;">레지스트리 가상화 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0073">CVE-2015-0073</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-025">MS15-025</a></td>
<td style="border:1px solid black;">가장 수준 검사 권한 상승 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0075">CVE-2015-0075</a></td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">OWA 수정된 카나리아 매개 변수 사이트 간 스크립팅 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1628">CVE-2015-1628</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">ExchangeDLP 사이트 간 스크립팅 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1629">CVE-2015-1629</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">감사 보고서 사이트 간 스크립팅 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1630">CVE-2015-1630</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">Exchange 위조된 모임 요청 스푸핑 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1631">CVE-2015-1631</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이 취약점은 스푸핑 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-026">MS15-026</a></td>
<td style="border:1px solid black;">Exchange 오류 메시지 사이트 간 스크립팅 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1632">CVE-2015-1632</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">4 - 영향을 받지 않음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 권한 상승 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-027">MS15-027</a></td>
<td style="border:1px solid black;">NETLOGON 스푸핑 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0005">CVE-2015-0005</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이 취약점은 스푸핑 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-028">MS15-028</a></td>
<td style="border:1px solid black;">작업 스케줄러 보안 기능 우회 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0084">CVE-2015-0084</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 보안 기능 우회 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-029">MS15-029</a></td>
<td style="border:1px solid black;">JPEG XR 파서 정보 공개 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0076">CVE-2015-0076</a></td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">2- 악용 가능성 낮음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이는 정보 공개 취약점입니다.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-030">MS15-030</a></td>
<td style="border:1px solid black;">RDP(원격 데스크톱 프로토콜) 서비스 거부 취약점</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0079">CVE-2015-0079</a></td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">3- 악용 불가능</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이 취약점은 서비스 거부 취약점입니다.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ko-kr/library/security/ms15-031">MS15-031</a></td>
<td style="border:1px solid black;">Schannel 보안 기능 우회 취약성</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1637">CVE-2015-1637</a></td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">1 - 악용 가능성 높음</td>
<td style="border:1px solid black;">해당 없음</td>
<td style="border:1px solid black;">이 취약성은 공개적으로 보고되었습니다.<br />
<br />
이는 보안 기능 우회 취약성입니다.</td>
</tr>
</tbody>
</table>
 

영향을 받는 소프트웨어
----------------------

<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.

**참고** 단일 취약점에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 번호로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

### Windows 운영 체제 및 구성 요소(표 1/2)

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/ko-kr/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/ko-kr/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/ko-kr/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/ko-kr/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/ko-kr/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/ko-kr/library/security/ms15-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                             

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                           

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2                

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
(보통)  
Internet Explorer 7  
(3032359)  
(보통)  
Internet Explorer 8  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3030403)  
(보통)  
VBScript 5.7  
(3030398)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3033889)  
(긴급)  
Windows Server 2003 서비스 팩 2  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
(보통)  
Internet Explorer 7  
(3032359)  
(보통)  
Internet Explorer 8  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3030403)  
(보통)  
VBScript 5.7  
(3030398)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3033889)  
(긴급)  
Windows Server 2003 x64 Edition 서비스 팩 2  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
(보통)  
Internet Explorer 7  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3030403)  
(보통)  
VBScript 5.7  
(3030398)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3033889)  
(긴급)  
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/ko-kr/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/ko-kr/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/ko-kr/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/ko-kr/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/ko-kr/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/ko-kr/library/security/ms15-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(긴급)  
Internet Explorer 8  
(3032359)  
(긴급)  
Internet Explorer 9  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3033889)  
(긴급)  
Windows Vista 서비스 팩 2  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(긴급)  
Internet Explorer 8  
(3032359)  
(긴급)  
Internet Explorer 9  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3033889)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/ko-kr/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/ko-kr/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/ko-kr/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/ko-kr/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/ko-kr/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/ko-kr/library/security/ms15-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(보통)  
Internet Explorer 8  
(3032359)  
(보통)  
Internet Explorer 9  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3033889)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(보통)  
Internet Explorer 8  
(3032359)  
(보통)  
Internet Explorer 9  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3033889)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3033889)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/ko-kr/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/ko-kr/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/ko-kr/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/ko-kr/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/ko-kr/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/ko-kr/library/security/ms15-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(긴급)  
Internet Explorer 9  
(3032359)  
(긴급)  
Internet Explorer 10  
(3032359)  
(긴급)  
Internet Explorer 11  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3033889)  
(긴급)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(긴급)  
Internet Explorer 9  
(3032359)  
(긴급)  
Internet Explorer 10  
(3032359)  
(긴급)  
Internet Explorer 11  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3033889)  
(긴급)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/ko-kr/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/ko-kr/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/ko-kr/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/ko-kr/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/ko-kr/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/ko-kr/library/security/ms15-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(보통)  
Internet Explorer 9  
(3032359)  
(보통)  
Internet Explorer 10  
(3032359)  
(보통)  
Internet Explorer 11  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3033889)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3033889)  
(긴급)  
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/ko-kr/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/ko-kr/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/ko-kr/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/ko-kr/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/ko-kr/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/ko-kr/library/security/ms15-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3033889)  
(긴급)  
Windows 8(32비트 시스템용)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3033889)  
(긴급)  
Windows 8(x64 기반 시스템용)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3033889)  
(긴급)  
Windows 8.1(32비트 시스템용)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3033889)  
(긴급)  
Windows 8.1(x64 기반 시스템용)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/ko-kr/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/ko-kr/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/ko-kr/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/ko-kr/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/ko-kr/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/ko-kr/library/security/ms15-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3033889)  
(긴급)  
Windows Server 2012  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3033889)  
(긴급)  
Windows Server 2012 R2  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/ko-kr/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/ko-kr/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/ko-kr/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/ko-kr/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/ko-kr/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/ko-kr/library/security/ms15-024)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3033889)  
(긴급)  
Windows RT  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3033889)  
(긴급)  
Windows RT 8.1  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/ko-kr/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/ko-kr/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/ko-kr/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/ko-kr/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/ko-kr/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/ko-kr/library/security/ms15-024)

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
[**보통**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3033889)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3033889)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
VBScript 5.8  
(3030630)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3033889)  
(긴급)  
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3033889)  
(긴급)  
Windows Server 2012(Server Core 설치)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3035132)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3033889)  
(긴급)  
Windows Server 2012 R2(Server Core 설치)  
(3039066)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3032323)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3034344)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3035132)  
(중요)

</td>
</tr>
</table>
 
**MS15-018, MS15-019, MS15-020, MS15-021 및 MS15-023 참고 사항**

Windows Technical Preview 및 Windows Server Technical Preview가 영향을 받습니다. 해당 운영 체제를 실행하는 고객은 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)를 통해 이 업데이트를 적용하는 것이 좋습니다. 

 

### Windows 운영 체제 및 구성 요소(표 2/2)

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/ko-kr/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/ko-kr/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/ko-kr/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/ko-kr/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/ko-kr/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/ko-kr/library/security/ms15-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                            

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                            

</td>
<td style="border:1px solid black;">
**없음**                                        

</td>
<td style="border:1px solid black;">
**없음**                                        

</td>
<td style="border:1px solid black;">
**없음**                                        

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)                                 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2                

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3033395)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2  
(3002657)  
(중요)

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
Windows Server 2003 서비스 팩 2  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3033395)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2  
(3002657)  
(중요)

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
Windows Server 2003 x64 Edition 서비스 팩 2  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3033395)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3002657)  
(중요)

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
Windows Server 2003 SP2(Itanium 기반 시스템용)  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/ko-kr/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/ko-kr/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/ko-kr/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/ko-kr/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/ko-kr/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/ko-kr/library/security/ms15-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/ko-kr/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/ko-kr/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/ko-kr/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/ko-kr/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/ko-kr/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/ko-kr/library/security/ms15-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/ko-kr/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/ko-kr/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/ko-kr/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/ko-kr/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/ko-kr/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/ko-kr/library/security/ms15-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3035017)  
(중요)  
Windows 7(32비트 시스템용) 서비스 팩 1  
(3036493)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3035017)  
(중요)  
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3036493)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/ko-kr/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/ko-kr/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/ko-kr/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/ko-kr/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/ko-kr/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/ko-kr/library/security/ms15-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 및 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/ko-kr/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/ko-kr/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/ko-kr/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/ko-kr/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/ko-kr/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/ko-kr/library/security/ms15-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3035017)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(32비트 시스템용)  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3035017)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8(x64 기반 시스템용)  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3035017)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3035017)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/ko-kr/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/ko-kr/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/ko-kr/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/ko-kr/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/ko-kr/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/ko-kr/library/security/ms15-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035017)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035017)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 및 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/ko-kr/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/ko-kr/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/ko-kr/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/ko-kr/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/ko-kr/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/ko-kr/library/security/ms15-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035126)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/ko-kr/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/ko-kr/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/ko-kr/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/ko-kr/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/ko-kr/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/ko-kr/library/security/ms15-031)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3002657)  
(중요)

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
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3002657)  
(중요)

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
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3035017)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(3046049)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3035131)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3002657)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3030377)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3035017)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(3046049)  
(중요)

</td>
</tr>
</table>
 
**MS15-031 참고 사항:**

Windows Technical Preview 및 Windows Server Technical Preview가 영향을 받습니다. 해당 운영 체제를 실행하는 고객은 [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)를 통해 이 업데이트를 적용하는 것이 좋습니다.

 

### Microsoft Server 소프트웨어

<p> </p>
<table style="border:1px solid black;">
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
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/ko-kr/library/security/ms15-026)

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
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

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
(3040856)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 7

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 7  
(3040856)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/ko-kr/library/security/ms15-026)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(32비트 에디션)  
(2881068)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 에디션)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3(64비트 에디션)  
(2881068)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 3(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 3(32비트 버전)  
(2881068)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 3(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 서비스 팩 3(64비트 버전)  
(2881068)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/ko-kr/library/security/ms15-026)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 서비스 팩 2(wssloc)  
(2956208)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2(wssloc)  
(2956208)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/ko-kr/library/security/ms15-026)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013(sts)  
(2956175)  
(중요)  
Microsoft SharePoint Foundation 2013(wssloc)  
(2956183)  
(중요)  
Microsoft SharePoint Foundation 2013(smsloc)  
(2760508)  
(중요)  
Microsoft SharePoint Server 2013(acsrvloc)  
(2956180)  
(중요)  
Microsoft SharePoint Server 2013(coreserverloc)  
(2956153)  
(중요)  
Microsoft SharePoint Server 2013(eduloc)  
(2760554)  
(중요)  
Microsoft SharePoint Server 2013(ifsloc)  
(2880473)  
(중요)  
Microsoft SharePoint Server 2013(lpsrvloc)  
(2737989)  
(중요)  
Microsoft SharePoint Server 2013(ppsmaloc)  
(2881078)  
(중요)  
Microsoft SharePoint Server 2013(vsrvloc)  
(2956181)  
(중요)  
Microsoft SharePoint Server 2013(wasrvloc)  
(2760361)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 서비스 팩 1(sts)  
(2956175)  
(중요)  
Microsoft SharePoint Foundation 2013 서비스 팩 1(wssloc)  
(2956183)  
(중요)  
Microsoft SharePoint Foundation 2013 서비스 팩 1(smsloc)  
(2760508)  
(중요)  
Microsoft SharePoint Server 2013 서비스 팩 1(acsrvloc)  
(2956180)  
(중요)  
Microsoft SharePoint Server 2013 서비스 팩 1(coreserverloc)  
(2956153)  
(중요)  
Microsoft SharePoint Server 2013 서비스 팩 1(eduloc)  
(2760554)  
(중요)  
Microsoft SharePoint Server 2013 서비스 팩 1(ifsloc)  
(2880473)  
(중요)  
Microsoft SharePoint Server 2013 서비스 팩 1(lpsrvloc)  
(2737989)  
(중요)  
Microsoft SharePoint Server 2013 서비스 팩 1(ppsmaloc)  
(2881078)  
(중요)  
Microsoft SharePoint Server 2013 서비스 팩 1(vsrvloc)  
(2956181)  
(중요)  
Microsoft SharePoint Server 2013 서비스 팩 1(wasrvloc)  
(2760361)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 
**MS15-022 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 절의 다른 표를 확인하십시오.

 

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
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(2984939)  
(중요)  
Microsoft Excel 2007 서비스 팩 3  
(2956103)  
(중요)  
Microsoft PowerPoint 2007 서비스 팩 3  
(2899580)  
(중요)  
Microsoft Word 2007 서비스 팩 3  
(2956109)  
(긴급)

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
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2956076)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(2956138)  
(긴급)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)(oart)  
(2883100)  
(중요)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)(oartconv)  
(2889839)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(32비트 버전)  
(2956142)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(32비트 에디션)  
(2920812)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(2956139)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(2956076)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(2956138)  
(긴급)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)(oart)  
(2883100)  
(중요)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)(oartconv)  
(2889839)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(64비트 버전)  
(2956142)  
(중요)  
Microsoft PowerPoint 2010 서비스 팩 2(64비트 에디션)  
(2920812)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(2956139)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 및 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(32비트 버전)  
(2956151)  
(중요)  
Microsoft Word 2013(32비트 버전)  
(2956163)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013(64비트 버전)  
(2956151)  
(중요)  
Microsoft Word 2013(64비트 버전)  
(2956163)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)  
(2956151)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(2956163)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)  
(2956151)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(2956163)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2956151)  
(중요)  
Microsoft Word 2013 RT  
(2956163)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1  
(2956151)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(2956163)  
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
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2956188)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2956189)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3(wordconv)  
(2956107)  
(긴급)  
Microsoft Office 호환 기능 팩 서비스 팩 3(xlconv)  
(2956106)  
(중요)

</td>
</tr>
</table>
 
**MS15-022 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 절의 다른 표를 확인하십시오.

 

### Microsoft Office Services 및 Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Word Automation Services(wdsrv)  
(2956136)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Excel Services(xlsrvloc)  
(2956143)  
(중요)  
Word Automation Services(wdsrvloc)  
(2920731)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Excel Services(xlsrvloc)  
(2956143)  
(중요)  
Word Automation Services(wdsrvloc)  
(2920731)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 서비스 팩 2(wacloc2010)  
(2956069)  
(긴급)  
Microsoft Office Web Apps Server 2010 서비스 팩 2(wacloc2010)  
(2956069)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/ko-kr/library/security/ms15-022)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급**](http://technet.microsoft.com/ko-kr/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(wacserver2013)  
(2956158)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(wacserver2013)  
(2956158)  
(긴급)

</td>
</tr>
</table>
 
**MS15-022 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향을 받는 소프트웨어를 확인하려면 이 절의 다른 표를 확인하십시오.

 

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
Microsoft는 신뢰할 수 있는 취약점 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/dn903755.aspx)을 참조하십시오.

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 공지 릴리스에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 릴리스에서 제공되지 않습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/kb/894199/ko): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services용으로 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/windowsserver/bb332157.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 재출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://technet.microsoft.com/ko-kr/security/dn467918)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드](http://technet.microsoft.com/ko-kr/library/bb466251.aspx)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

**기타 보안 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 제공됩니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://www.microsoft.com/ko-kr/download/search.aspx?q=security%20update)에서 다운로드할 수 있으며 "보안 업데이트"라는 키워드 검색을 수행하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ko-kr)에서 제공됩니다.
-   이달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/kb/913086/ko)를 참조하십시오.

**IT 전문가 보안 커뮤니티**

[IT 전문가 보안 커뮤니티](http://technet.microsoft.com/ko-kr/security/cc136632.aspx)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간](http://go.microsoft.com/fwlink/?linkid=21742)을 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/ko-kr/security/bb980617)

Windows 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ko)

지역별 지원 정보: [국가별 지원](http://support.microsoft.com/common/international.aspx?ln=ko)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation 또는 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2015년 3월 10일): 공지 요약이 게시되었습니다.

*2015-03-10 9:05Z-07:00에 페이지가 생성되었습니다.*
