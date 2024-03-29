---
TOCTitle: 'MS10-FEB'
Title: 2010 년 2 월 Microsoft 보안 공지 요약
ms:assetid: 'ms10-feb'
ms:contentKeyID: 61230723
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms10-feb(v=Security.10)'
---


2010 년 2 월 Microsoft 보안 공지 요약
=====================================

게시된 날짜: 2010년 2월 10일 수요일 | 업데이트된 날짜: 2010년 2월 11일 목요일

**버전:** 1.1

이 공지 요약 목록에는 2010년 2월 발표된 보안 공지가 포함되어 있습니다.

2010년 2월 공지 발표와 함께 이 공지 요약이 2010년 2월 4일 게시된 공지 사전 알림을 대체합니다. 공지 사전 알림 서비스에 대한 자세한 내용은 [Microsoft 보안 공지 사전 알림](http://technet.microsoft.com/security/bulletin/advance)을 참조하십시오.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 2010년 2월 10일 오전 11:00(태평양 표준시, 미국 및 캐나다)에 이 공지에 대한 고객 문의 사항에 답변을 제공하는 웹캐스트를 진행할 예정입니다. [2월 보안 공지 웹캐스트에 지금 등록하십시오 (영문)](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032427679&culture=en-us). 이 날짜 이후 이 웹캐스트는 주문형으로 제공됩니다. 자세한 내용은 [Microsoft 보안 공지 요약 (영문)](http://technet.microsoft.com/security/bulletin/summary) 및 웹캐스트를 참조하십시오.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-006">MS10-006</a></td>
<td style="border:1px solid black;"><strong>SMB 클라이언트의 취약점으로 인한 원격 코드 실행 문제점(978251)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 2건을 해결합니다. 이 취약점으로 인해 공격자가 특수하게 조작된 SMB 응답을 클라이언트가 시작한 SMB 요청에 보낼 경우 원격 코드 실행이 발생할 수 있습니다. 이 취약점을 악용하려면 공격자는 사용자가 악의적인 SMB 서버에 SMB 연결을 시작하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-007">MS10-007</a></td>
<td style="border:1px solid black;"><strong>Windows 셸 처리기의 취약점으로 인한 원격 코드 실행 문제점(975713)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows 2000, Windows XP 및 Windows Server 2003에서 발견되어 비공개적으로 보고된 취약점 1건을 해결합니다. 다른 Windows 버전은 이 보안 업데이트의 영향을 받지 않습니다. 이 취약점으로 인해 웹 브라우저 같은 응용 프로그램이 특수하게 조작된 데이터를 ShellExecute API 함수로 Windows 셸 처리기를 통해 전달할 경우 원격 코드 실행이 발생할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-008">MS10-008</a></td>
<td style="border:1px solid black;"><strong>ActiveX 킬(Kill) 비트 누적 보안 업데이트(978262)</strong><br />
<br />
이 보안 업데이트는 Microsoft 소프트웨어에서 발견되어 비공개적으로 보고된 취약점을 해결합니다. 이 보안 업데이트의 심각도는 지원 대상인 모든 Microsoft Windows 2000 및 Windows XP 버전에 대해 긴급, 지원되는 모든 Windows Vista 및 Windows 7 버전에 대해 중요, 지원 대상인 모든 Windows Server 2003에 대해 보통, 그리고 지원 대상인 모든 Windows Server 2008 및 Windows Server 2008 R2에 대해 낮음입니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-009">MS10-009</a></td>
<td style="border:1px solid black;"><strong>Windows TCP/IP의 취약점으로 인한 원격 코드 실행 문제점(974145)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 취약점 4건을 해결합니다. 가장 위험한 취약점으로 인해 IPv6를 사용하는 컴퓨터로 특수하게 조작된 패킷이 전송될 경우 원격 코드 실행이 허용될 수 있습니다. 공격자는 특수하게 조작된 ICMPv6 패킷을 만들어 IPv6를 사용하는 시스템에 보내는 방법으로 취약점 악용을 시도할 수 있습니다. 이 취약점은 공격자가 링크에 있는 경우에만 악용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-013">MS10-013</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow의 취약점으로 인한 원격 코드 실행 문제점(977935)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft DirectShow의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 AVI 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-003">MS10-003</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office(MSO)의 취약점으로 인한 원격 코드 실행 문제점(978214)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 취약점 1건을 해결합니다. 사용자가 특수하게 조작된 Office 파일을 열면 이 Microsoft Office 취약점을 통해 원격 코드 실행이 허용될 수 있습니다. 이 취약점을 악용한 공격자는 영향을 받는 시스템을 완전히 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-004">MS10-004</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office PowerPoint의 취약점으로 인한 원격 코드 실행 문제점(975416)</strong><br />
<br />
이 보안 업데이트는 Microsoft Office PowerPoint에서 발견되어 비공개적으로 보고된 6건의 취약점을 해결합니다. 이러한 취약점으로 인해 사용자가 특수하게 조작된 PowerPoint 파일을 열 경우 원격 코드 실행이 발생할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치할 수 있을 뿐 아니라 데이터를 보거나 변경하거나 삭제할 수 있고 모든 사용자 권한이 있는 새 계정을 만들 수도 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-010">MS10-010</a></td>
<td style="border:1px solid black;"><strong>Windows Server 2008 Hyper-V의 취약점으로 인한 서비스 거부 문제점(977894)</strong><br />
<br />
이 보안 업데이트는 Windows Server 2008 Hyper-V 및 Windows Server 2008 R2 Hyper-V에서 발견되어 비공개적으로 보고된 취약점을 해결합니다. 이 취약점으로 인해 Hyper-V 서버에서 호스팅하는 게스트 가상 컴퓨터 중 하나의 인증된 사용자가 잘못된 형식의 컴퓨터 명령 시퀀스를 실행할 경우 서비스 거부가 발생할 수 있습니다. 공격자가 이 취약점을 악용하려면 유효한 로그온 자격 증명을 가지고 게스트 가상 컴퓨터에 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-011">MS10-011</a></td>
<td style="border:1px solid black;"><strong>Windows Client/Server Run-time Subsystem의 취약점으로 인한 권한 상승 문제점(978037)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows 2000, Windows XP 및 Windows Server 2003의 CSRSS(Microsoft Windows Client/Server Run-time Subsystem)에서 발견되어 비공개적으로 보고된 취약점 1건을 해결합니다. 다른 버전의 Windows는 영향을 받지 않습니다. 이 취약점으로 인해 공격자가 시스템에 로그온하여 공격자가 로그아웃한 후에도 계속 실행되도록 특수하게 조작된 응용 프로그램을 시작할 경우 권한 상승이 발생할 수 있습니다. 이 취약점을 악용하려면 공격자가 유효한 로그온 자격 증명을 가지고 로컬로 로그온할 수 있어야 합니다. 익명 사용자는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-012">MS10-012</a></td>
<td style="border:1px solid black;"><strong>SMB 서버의 취약점으로 인한 원격 코드 실행 문제점(971468)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows에서 발견되어 비공개적으로 보고된 여러 취약점을 해결합니다. 이 중 가장 심각한 취약점으로 인해 공격자가 특수하게 조작된 SMB 패킷을 만들어 영향을 받는 시스템에 보내는 방법으로 원격 코드 실행이 발생할 수 있습니다. 방화벽 구성 모범 사례와 표준 기본 방화벽 구성을 이용하면 기업 경계 외부에서 이 취약점을 악용하려는 공격으로부터 네트워크를 보호할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-014">MS10-014</a></td>
<td style="border:1px solid black;"><strong>Kerberos의 취약점으로 인한 서비스 거부 문제점(977290)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Windows의 취약점을 해결합니다. 이 취약점으로 인해 신뢰할 수 있는 비-Windows Kerberos 영역의 인증된 사용자로부터 특수하게 조작된 티켓 갱신 요청이 Windows Kerberos 도메인으로 보내질 경우 서비스 거부가 허용될 수 있습니다. 서비스 거부는 도메인 컨트롤러가 다시 시작될 때까지 지속될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
서비스 거부</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-015">MS10-015</a></td>
<td style="border:1px solid black;"><strong>Windows 커널의 취약점으로 인한 권한 상승 문제점(977165)</strong><br />
<br />
이 보안 업데이트는 Microsoft Windows의 공개된 취약점 1건과 비공개적으로 보고된 취약점 1건을 해결합니다. 이 취약점으로 인해 공격자가 시스템에 로그온한 후 특수하게 조작한 응용 프로그램을 실행할 경우 권한 상승을 허용할 수 있습니다. 공격자가 이러한 취약점을 악용하려면 유효한 로그온 자격 증명을 사용하여 로컬로 로그온할 수 있어야 합니다. 익명의 사용자에 의해서나 원격으로는 이 취약점을 악용할 수 없습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요</a><br />
권한 상승</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-005">MS10-005</a></td>
<td style="border:1px solid black;"><strong>Microsoft Paint의 취약점으로 인한 원격 코드 실행 문제점(978706)</strong><br />
<br />
이 보안 업데이트는 비공개적으로 보고된 Microsoft Paint의 취약점을 해결합니다. 이 취약점으로 인해 사용자가 Microsoft Paint를 사용하여 특수하게 조작된 JPEG 이미지 파일을 볼 경우 원격 코드 실행이 발생할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자에 비해 영향을 적게 받습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">보통</a><br />
원격 코드 실행</td>
<td style="border:1px solid black;">재시작 필요</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
악용 가능성 인덱스  
------------------
  
다음 표는 이달에 해결한 각 취약점의 악용 가능성 평가입니다. 취약점은 악용 가능성 평가 수준 내림차순 및 CVE ID 순으로 나열되어 있습니다.
  
**이 표를 어떻게 사용합니까?**
  
이 표를 사용하여 30일 이내의 설치해야 하는 각 보안 업데이트에 발표된 기능 악용 코드의 가능성에 대해 자세히 알아볼 수 있습니다. 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토해야 합니다. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스 (영문)](http://technet.microsoft.com/en-us/security/cc998259.aspx)를 참조하십시오.
  
| 공지 번호                                                           | 취약점 제목                                                          | CVE ID                                                                                  | 악용 가능성 인덱스 평가                                                                               | 주요 정보                                                                                    |  
|---------------------------------------------------------------------|----------------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|  
| [MS10-006](http://technet.microsoft.com/security/bulletin/ms10-006) | SMB 클라이언트 경쟁 조건 취약점                                      | [CVE-2010-0017 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0017) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 원격 공격 경로로 인해 DoS가 발생할 수 있으며 로컬 공격 경로로 인해 EoP가 발생할 수 있습니다. |  
| [MS10-011](http://technet.microsoft.com/security/bulletin/ms10-011) | CSRSS 로컬 권한 상승 취약점                                          | [CVE-2010-0023 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0023) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | 공격자와 대상 사용자가 동일한 콘솔에 로그온해야 합니다.                                      |  
| [MS10-007](http://technet.microsoft.com/security/bulletin/ms10-007) | URL 유효성 검사 취약점                                               | [CVE-2010-0027 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                       |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint LinkedSlideAtom 힙 오버플로 취약점                        | [CVE-2010-0030 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0030) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                       |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint OEPlaceholderAtom 'placementId' 잘못된 배열 인덱싱 취약점 | [CVE-2010-0031 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0031) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                       |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint OEPlaceholder Atom Use After Free 취약점                  | [CVE-2010-0032 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0032) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                       |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint Viewer TextBytesAtom 레코드 스택 오버플로 취약점          | [CVE-2010-0033 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0033) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | PowerPoint Viewer 2003만 이 취약점의 영향을 받습니다.                                        |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | Office PowerPoint Viewer TextCharsAtom 레코드 스택 오버플로 취약점   | [CVE-2010-0034 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0034) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | PowerPoint Viewer 2003만 이 취약점의 영향을 받습니다.                                        |  
| [MS10-012](http://technet.microsoft.com/security/bulletin/ms10-012) | SMB NTLM 인증 엔트로피 부족 취약점                                   | [CVE-2010-0231 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0231) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                       |  
| [MS10-015](http://technet.microsoft.com/security/bulletin/ms10-015) | Windows 커널 예외 처리기 취약점                                      | [CVE-2010-0232 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0232) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                       |  
| [MS10-003](http://technet.microsoft.com/security/bulletin/ms10-003) | MSO.DLL 버퍼 오버플로 취약점                                         | [CVE-2010-0243 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0243) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                       |  
| [MS10-013](http://technet.microsoft.com/security/bulletin/ms10-013) | DirectShow 힙 오버플로 취약점                                        | [CVE-2010-0250 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0250) | [**1 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 일관적인 악용 코드 가능   | (없음)                                                                                       |  
| [MS10-006](http://technet.microsoft.com/security/bulletin/ms10-006) | SMB 클라이언트 풀 손상 취약점                                        | [CVE-2010-0016 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0016) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                       |  
| [MS10-012](http://technet.microsoft.com/security/bulletin/ms10-012) | SMB 경로 이름 오버플로 취약점                                        | [CVE-2010-0020 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0020) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                       |  
| [MS10-012](http://technet.microsoft.com/security/bulletin/ms10-012) | SMB 메모리 손상 취약점                                               | [CVE-2010-0021 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0021) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                       |  
| [MS10-005](http://technet.microsoft.com/security/bulletin/ms10-005) | MS 그림판 정수 오버플로 취약점                                       | [CVE-2010-0028 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0028) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 이 취약점을 악용하려면 많은 사용자 조작이 필요합니다.                                        |  
| [MS10-004](http://technet.microsoft.com/security/bulletin/ms10-004) | PowerPoint 파일 경로 처리 버퍼 오버플로 취약점                       | [CVE-2010-0029 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0029) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                       |  
| [MS10-015](http://technet.microsoft.com/security/bulletin/ms10-015) | Windows 커널 Double Free 취약점                                      | [CVE-2010-0233 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0233) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | (없음)                                                                                       |  
| [MS10-009](http://technet.microsoft.com/security/bulletin/ms10-009) | ICMPv6 라우터 알림 취약점                                            | [CVE-2010-0239 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0239) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 이 취약점을 악용하려면 공격자가 대상 호스트에 연결되어 있어야 합니다.                        |  
| [MS10-009](http://technet.microsoft.com/security/bulletin/ms10-009) | 헤더 MDL 단편화 취약점                                               | [CVE-2010-0240 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0240) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 이 취약점을 악용하려면 타사 네트워크 드라이버가 있어야 합니다.                               |  
| [MS10-009](http://technet.microsoft.com/security/bulletin/ms10-009) | ICMPv6 라우팅 정보 취약점                                            | [CVE-2010-0241 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0241) | [**2 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 비일관적인 악용 코드 가능 | 이 취약점을 악용하려면 공격자가 대상 호스트에 연결되어 있어야 합니다.                        |  
| [MS10-012](http://technet.microsoft.com/security/bulletin/ms10-012) | SMB Null 포인터 취약점                                               | [CVE-2010-0022 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0022) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | (없음)                                                                                       |  
| [MS10-010](http://technet.microsoft.com/security/bulletin/ms10-010) | Hyper-V 명령 설정 유효성 검사 취약점                                 | [CVE-2010-0026 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0026) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 이 취약점으로 인해 DoS만 발생할 수 있습니다.                                                 |  
| [MS10-014](http://technet.microsoft.com/security/bulletin/ms10-014) | Kerberos Null 포인터 역참조 취약점                                   | [CVE-2010-0035 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0035) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | 기본 구성이 아닌 도메인 컨트롤러에서만 DoS가 발생할 수 있습니다.                             |  
| [MS10-009](http://technet.microsoft.com/security/bulletin/ms10-009) | TCP/IP 선택적 승인 취약점                                            | [CVE-2010-0242 (영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0242) | [**3 (영문)**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 악용 코드 기능 불가능     | (없음)                                                                                       |
  
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
<th style="border:1px solid black;" colspan="12">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 서비스 팩 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=80b49bab-6c2f-48a8-a901-ca3f76e4fe6b&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=92234237-a8eb-4ce4-bc5e-cd86feb7dbd3&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=543dc6a7-fa76-4ba9-81e4-25fdf2013548&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AVI 필터](http://www.microsoft.com/downloads/details.aspx?familyid=ba110440-10ce-40a0-884a-8b9afd45a3e3&displaylang=ko)  
(KB977914)  
(긴급)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=16787c93-2c95-4c13-8492-be1db9d18146&displaylang=ko)  
(KB975560)  
(긴급)  
[DirectX 9.0의 Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=59a8bc19-02bb-4800-bac1-464f59e1cb7b&displaylang=ko)<sup>[1]</sup>
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=456185b5-57d1-4fa5-a4a9-5b2006ede3ad&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=267ce982-54a0-418f-ad52-e4963610f714&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=56a9afba-a6ee-4fb9-ba85-e51d9f94de27&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=ed8ac6a5-c8bb-4ed4-8994-810e9a1863c3&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 서비스 팩 4](http://www.microsoft.com/downloads/details.aspx?familyid=e5861705-8f49-45cb-8a92-cf052ccf4134&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="12">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=f6c4472e-385c-4412-bda9-c2e615e50713&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=b8e7bf17-a037-4200-9ae2-2280b19766a4&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=7bcf3945-0552-478e-b7f3-bbca97dd1b5d&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AVI 필터](http://www.microsoft.com/downloads/details.aspx?familyid=a9beb2bd-e5f6-43f9-bbcc-a2afee5e5ceb&displaylang=ko)  
(KB977914)  
(긴급)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7ab53be3-3f42-4e61-a2bc-3ed41d8736ff&displaylang=ko)  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=b9234b40-1b1c-498b-90d4-0bff347b36ee&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=8f7adee3-e68e-41b3-b835-d84691774f31&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=e2b348f5-ec8d-4782-bb03-5de550adea77&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP 서비스 팩 2 및 Windows XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=b2e70df6-7728-4fc3-8df7-8ddb9ba5202f&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=63e15ff0-73b3-46c9-96f8-c18977d35a10)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8d83f30-9cd7-4d6b-b2b9-65d0a483cb9c)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=25ef97e8-e76e-44c2-953c-f94cbac552cf)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AVI 필터](http://www.microsoft.com/downloads/details.aspx?familyid=dedc3010-a989-45f7-b9d4-f7079db3e572)  
(KB977914)  
(긴급)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7543e819-cd36-4e89-9850-60f00c50999d)  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1f83bf7a-e16c-404a-89bd-f65843938299)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=91ee57f2-81e5-49bd-bdfc-d3e385efc8a5)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=e534d00c-6ddc-4eb3-9464-5db6e90afa3e)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f8c4acc8-c2f4-41f7-9b32-e7bd791e0155)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="12">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**보통**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=feb8c145-7c30-45fa-a6f0-8b6453ddd521&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5cb2e203-18fb-4887-a1c9-289d86b8ba11&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=29ff72f7-1663-4f35-a794-2dfe3c17b39c&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AVI 필터](http://www.microsoft.com/downloads/details.aspx?familyid=cc5150d7-070e-4a87-9c02-d050a8cb2204&displaylang=ko)  
(KB977914)  
(긴급)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=983c5484-6321-4765-97ec-8d42d42d1f70&displaylang=ko)  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2c8c4eec-255e-41d5-b1e6-f0204edcb46f&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3d18cbc4-ac48-458c-8aa3-90708fd854ff&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=738e2fda-96fc-413d-a5c7-74b1fac1d6b3&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=defd8603-ed9b-42f9-a539-2b6a690e9575&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=c1efbe73-fc87-4e6a-8b36-81f125a27aec&displaylang=ko)  
(보통)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=36d88c1b-814c-4371-9ed2-d4576f419fc3&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=90360537-9311-45e2-8047-9a971f90c3c3&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=d4a97bb7-4f74-4884-9a6e-7a4df9c540fb&displaylang=ko)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AVI 필터](http://www.microsoft.com/downloads/details.aspx?familyid=db13e99b-2f2a-4474-8d6e-271b025bd07f&displaylang=ko)  
(KB977914)  
(긴급)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7dc20252-6091-407b-befc-c25e8f5d3fb0&displaylang=ko)  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=de0186f6-27a2-4226-b8eb-f2912710f072&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d63c95e-311a-446f-8852-dffd217a89f6&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f8ad539d-8191-4864-977b-ad4e31c04ba0&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9873c962-9d3d-46ef-b54b-2a50696fb6b2&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9143e435-f0d6-464b-9273-4d1f38f8ff3a&displaylang=ko)  
(보통)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=622442b0-cffe-4fc2-94a8-edff9d71ecd3)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=d695ca9f-a1db-4c0f-94b6-7112861c28da)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b84f0be4-6d11-4b07-bb3c-2c76ae9ceea8)  
(보통)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[AVI 필터](http://www.microsoft.com/downloads/details.aspx?familyid=aec66173-e2c6-4c39-8d60-8fbef6d7b764)  
(KB977914)  
(중요)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=b1a7533a-913f-4054-b579-489a257bae5f)  
(KB975560)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=87732f7a-9339-43bc-a4e8-3da849f35b70)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ee7f8cc4-f7fd-4dc7-808c-436204ee80cb)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=d549c927-add7-4d83-bfc7-15dc35663dfb)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=c3c21225-8534-4c7f-96b6-20a743dcea74)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ee603435-26af-4ab9-9f22-92734346dc0a)  
(보통)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="12">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1902fc93-0f4b-4261-9da3-17d1931daf2e&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2c897ddd-f441-41d4-b5b4-d794cfc96e6b&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=71f03946-622c-4403-b94f-f6a3de18a8c3&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7130ce0f-df38-4c96-ac54-cdbff35f03e7&displaylang=ko)  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=16494dac-553a-4de9-b751-0d6b51cb43f0&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista 서비스 팩 1 및 Windows Vista 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=2761c7b4-d472-4f00-949b-af3ebafdc08d&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7c2f89b5-a3b3-42cd-857d-923fe8b8f1da&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f349f7aa-d020-4e0d-a35f-518a63ec92df&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=519815fd-707d-476f-9e29-7b03b7a17af5&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=de7b7c8f-bd0a-4e13-bd58-d95507a6274b&displaylang=ko)  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=cec582b3-e37f-448e-a5c3-6abdcee9e57c&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition 서비스 팩 1 및 Windows Vista x64 Edition 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=38b40dab-6b4d-434b-9997-12ef70d6bbcc&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="12">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
<td style="border:1px solid black;">
[**낮음**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=09e19263-18ba-495e-bcf7-719e957204a7&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a85b1bf-7427-47d0-9e1b-21dbe824a62c&displaylang=ko)\*\*  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc451228-3de4-427c-b42f-91f204c708b8&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=5ac0a948-0bdc-4c10-9b88-16a5d7092e47&displaylang=ko)\*\*  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=597b2310-2cd8-4d0f-8248-781eb8b7450a&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=75327470-0f14-4cdd-bcb7-64684c61c267&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(32비트 시스템용) 및 Windows Server 2008(32비트 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=21e87558-9bd2-4aa9-aaa5-7fd26a5b60e6&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=180c2313-5e3e-4d84-87cd-64048f51e0f6&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=fde218c3-90ab-4664-852d-25ca55835054&displaylang=ko)\*\*  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3a889152-5d7c-4a3e-b4f1-c6507b739ca0&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=362fea40-649b-4471-aad7-db29edd0ac10&displaylang=ko)\*\*  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=3463a63c-e88a-4036-ab60-f84d4bf4191a&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=67119fb6-e517-46f4-ab0b-2351cdc3d670&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d0f8f81-fc10-450a-a653-06f89acba9fa&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(x64 기반 시스템용) 및 Windows Server 2008(x64 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=0b93047d-f2c6-403b-9200-c251898bc1e0&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=614eaf7e-95aa-4f8f-910c-1980e1f14d11)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=5b6e9451-df38-4626-bb1d-4fc160d7a40e)  
(낮음)
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=1cd1882b-8e55-47ea-a82a-68bb59a500a7)  
(긴급)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=effa638b-cfc1-4777-8219-7b433ed5e717)  
(KB975560)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=f90fc0c8-babe-4224-be07-614ea7ddf102)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008(Itanium 기반 시스템용) 및 Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2](http://www.microsoft.com/downloads/details.aspx?familyid=cd6b234b-8e96-4128-a77a-645a0882996a)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="12">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
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
Windows 7(32비트 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=a589431a-93dc-42cd-a74e-d9c1e3452fef&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ec6d996f-dffa-45ad-9467-e96a4ac63e5f&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=4ec49aa2-81df-4e65-80da-6201394c4089&displaylang=ko)  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=122fc003-0651-4ad2-a5c8-a21536defad8&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(32비트 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=66f14bb4-40fc-4ae3-9baf-429b7106cd91&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3c1edcf8-d304-45c4-9818-1cd86383b3fe&displaylang=ko)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=b3265576-04c1-48b1-8ce9-128843c58cf5&displaylang=ko)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=a8a2519c-3b89-4987-9473-920adafc78cb&displaylang=ko)  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows 7(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3e096468-db6c-45c6-bee5-eaeaa63500b5&displaylang=ko)  
(중요)
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
</tr>
<tr>
<th style="border:1px solid black;" colspan="12">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**공지 번호**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://technet.microsoft.com/security/bulletin/ms10-015)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://technet.microsoft.com/security/bulletin/ms10-005)
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
없음
</td>
<td style="border:1px solid black;">
[**낮음**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**긴급**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
[**중요**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
<td style="border:1px solid black;">
없음
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=ecb06350-47a7-48eb-825f-3e8f89c5ca8e&displaylang=ko)\*  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=cda31c54-8b81-4185-a623-64480ad4b73c&displaylang=ko)\*\*  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=a9811baa-1500-4c73-940b-57f8c5456891&displaylang=ko)\*\*  
(KB975560)  
(긴급)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=3214b347-d901-4aac-85ce-676e4602de87&displaylang=ko)\*  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(x64 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=dc757b6d-f0f8-4e71-ab6f-1417233eedf9&displaylang=ko)\*  
(중요)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=badd6cab-7738-4401-a68c-c15414388601)  
(긴급)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=43fa4e26-160f-4aa3-a03d-b98a79666a18)  
(낮음)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=2ed23bf5-6217-413c-a7ba-eccc82139d68)  
(KB975560)  
(중요)
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2(Itanium 기반 시스템용)](http://www.microsoft.com/downloads/details.aspx?familyid=d5b0b1eb-24f3-47ec-aba1-c1b95400189e)  
(중요)
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
</tr>
</table>
 
**MS10-013 참고 사항**

<sup>[1]</sup>DirectX 9.0의 업데이트는 Microsoft Windows 2000의 DirectX 9.0a, DirectX 9.0b 및 DirectX 9.0c에도 적용됩니다.

**Windows Server 2008 및 Windows Server 2008 R2 참고 사항**

**\*Server Core 설치가 영향을 받습니다.** 이 업데이트는 Server Core 설치 옵션의 사용 여부에 관계없이 동일한 심각도로 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2에 적용됩니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오

**\*\*Server Core 설치는 영향을 받지 않습니다.** Server Core 설치 옵션을 사용하여 설치한 경우 이 업데이트에서 해결하는 취약점은 지원 대상인 Windows Server 2008 또는 Windows Server 2008 R2 에디션에 영향을 주지 않습니다. 이 설치 옵션에 대한 자세한 내용은 MSDN 문서, [Server Core(영문)](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) 및 [Windows Server 2008 R2용 Server Core(영문)](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)를 참조하십시오. Server Core 설치 옵션은 Windows Server 2008 및 Windows Server 2008 R2의 특정 에디션에 적용되지 않습니다. [Server Core 설치 옵션 비교](http://www.microsoft.com/windowsserver2008/ko/kr/compare-core-installation.aspx)를 참조하십시오

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
[**MS10-003**](http://technet.microsoft.com/security/bulletin/ms10-003)
</td>
<td style="border:1px solid black;">
[**MS10-004**](http://technet.microsoft.com/security/bulletin/ms10-004)
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=47553f45-fa10-40e5-8267-9d42ff560a62)  
(KB977896)  
(중요)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=cfc697b4-2ceb-4030-86c5-be9bc8bfd07c)  
(KB973143)  
(중요)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
해당 사항 없음
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 서비스 팩 3](http://www.microsoft.com/downloads/details.aspx?familyid=2291ae24-fa39-4ad8-a7d0-12726b68ad96)  
(KB976881)  
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
[**MS10-003**](http://technet.microsoft.com/security/bulletin/ms10-003)
</td>
<td style="border:1px solid black;">
[**MS10-004**](http://technet.microsoft.com/security/bulletin/ms10-004)
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
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Mac용 Microsoft Office 2004](http://www.microsoft.com/downloads/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8)<sup>[1]</sup>
(KB979674)  
(중요)
</td>
<td style="border:1px solid black;">
[Mac용 Microsoft Office 2004](http://www.microsoft.com/downloads/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8)<sup>[1]</sup>
(KB979674)  
(중요)
</td>
</tr>
</table>
 
**Microsoft Office for Mac 참고 사항**

<sup>[1]</sup>Microsoft Office 2004 for Mac의 누적 서비스 모델이므로 이 업데이트는 동일합니다.

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

업데이트는 응용 프로그램을 실행하는 데 필요한 같은 파일 및 레지스트리 설정에 기록하는 경우가 많습니다. 이에 따라 비호환성이 발생하고 보안 업데이트 배포 시간이 길어질 수 있습니다. [ACT(Application Compatibility Toolkit)](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)에 포함된 [UCE(Update Compatibility Evaluator)](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) 구성 요소를 사용하면 설치된 응용 프로그램에 대한 Windows 업데이트 테스트 및 유효성 검사를 능률화할 수 있습니다.

ACT(Application Compatibility Toolkit)에는 Microsoft Windows Vista, Windows Update, Microsoft 보안 업데이트 또는 Windows Internet Explorer의 새 버전을 사용자 환경에 배포하기 전에 응용 프로그램 호환성 문제점을 평가 및 완화하는 데 필요한 도구와 설명서가 들어 있습니다.

### 기타 정보

#### Microsoft Windows 악성 소프트웨어 제거 도구

Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services, 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다.

#### MU, WU 및 WSUS의 비보안 중요 업데이트

Windows Update 및 Microsoft update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](http://support.microsoft.com/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services를 위해 지난 몇 달간 배포된 업데이트 (영문)](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 출시 업데이트를 전부 표시합니다.

#### MAPP(Microsoft Active Protections Program)

고객에 대한 보안을 강화하기 위해 Microsoft는 월별 보안 업데이트를 배포하기 전에 주요 보안 소프트웨어 제공업체에 취약점 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 안티바이러스, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너 (영문)](http://www.microsoft.com/security/msrc/mapp/partners.mspx)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

#### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드(영문)](http://go.microsoft.com/fwlink/?linkid=21168)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 최선의 방법과 관련 정보를 제공합니다.

**기타 보안 관련 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 구할 수 있습니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 다운로드할 수 있으며 "security update"라는 키워드를 사용하여 쉽게 찾을 수 있습니다.
-   일반 사용자용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 사용할 수 있습니다.
-   이 달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 중요 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](http://support.microsoft.com/kb/913086)을 참조하십시오.

**IT Pro Security Zone Community(IT 전문가 보안 영역 커뮤니티)**

[IT Pro Security Community(IT 전문가 보안 커뮤니티)](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 배우고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

#### 감사의 말

고객 보호를 위해 협력해 주신 다음 분들께 [감사](http://go.microsoft.com/fwlink/?linkid=21127)드립니다.

-   MS10-003에서 설명한 문제점을 보고해 주신 [Core Security Technologies (영문)](http://www.coresecurity.com/)의 Damian Frizza
-   MS10-004에서 설명한 문제점을 보고해 주신 [Secunia (영문)](http://secunia.com/)의 Carsten Eiram
-   MS10-004에서 설명한 세 가지 문제점을 보고해 주신 [VeriSign iDefense Labs (영문)](http://labs.idefense.com/)의 Sean Larsson
-   MS10-004에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/)의 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 SkD
-   MS10-004에서 설명한 문제점을 보고해 주신 [TippingPoint DVLabs (영문)](http://dvlabs.tippingpoint.com/)의 Cody Pierce
-   MS10-005에서 설명한 문제점을 [Secunia (영문)](http://secunia.com/)와 협력하여 보고해 주신 ICST-ERCIS(Info Security의 Engineering Research Center, Institute of Computer Science & Technology, Peking University/중국)의 Tielei Wang
-   MS10-006에서 설명한 두 가지 문제점을 보고해 주신[stratsec (영문)](http://www.stratsec.net/)의 Laurent Gaffié
-   MS10-007에서 설명한 문제점을 [TippingPoint (영문)](http://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)와 협력하여 보고해 주신 Brett Moore
-   MS10-007에서 설명한 문제점을 보고해 주신 [Lostmon Lords (영문)](http://lostmon.blogspot.com/)
-   MS10-008에서 설명한 문제점을 보고해 주신 [NGS Software (영문)](http://www.ngssoftware.com/)의 Shaun Colley
-   MS10-009에서 설명한 세 가지 문제점을 보고해 주신 [Google Security Team](http://www.google.com/)의 Sumit Gwalani, Drew Hintz 및 Neel Mehta
-   MS10-010에서 설명한 문제점을 보고해 주신 Jan Bottorff
-   MS10-011에서 설명한 문제점을 보고해 주신 [Hispasec (영문)](http://www.hispasec.com/)의 Matthew 'j00ru' Jurczyk 및 Gynvael Coldwind
-   MS10-012에서 설명한 문제점을 보고해 주신 [Codenomicon (영문)](http://www.codenomicon.com/)의 Joshua Morin
-   MS10-012에서 설명한 문제점을 보고해 주신 [BSI (영문)](http://www.bsi.bund.de/)의 Florian Rienhardt
-   MS10-012에서 설명한 문제점을 보고해 주신 Hernan Ochoa
-   MS10-013에서 설명한 문제점을 보고해 주신 [TippingPoint (영문)](http://www.tippingpoint.com/) 및 [Zero Day Initiative (영문)](http://www.zerodayinitiative.com/)
-   MS10-015에서 설명한 문제점을 보고해 주신 [Google Inc.](http://www.google.com/)의 Tavis Ormandy

#### 지원

-   나열된 영향을 받는 소프트웨어는 테스트를 거쳐 영향을 받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 기간 정책 웹 사이트](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.
-   기술 지원은 [보안 지원](http://go.microsoft.com/fwlink/?linkid=21131) 또는 1577-9700을 통해 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원 통화는 무료입니다. 사용 가능한 지원 옵션을 자세히 보려면 [Microsoft 도움말 및 지원](http://support.microsoft.com/) 웹 사이트를 참조하십시오.
-   기타 지역에 거주하는 고객은 해당 Microsoft 지사에서 지원을 받을 수 있습니다. 보안 업데이트와 관련된 기술 지원은 무료입니다. Microsoft 지원 부서에 연락하는 방법에 대한 자세한 내용은 [국가별 지원](http://go.microsoft.com/fwlink/?linkid=21155)에 나와 있습니다.

#### 부인

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성 및 특정 목적에의 적합성에 대한 보증을 포함하여 명시적이거나 묵시적인 어떤 보증도 하지 않습니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한은 귀하에게 적용되지 않을 수도 있습니다.

#### 개정 내역

-   V1.0(2010년 2월 10일): 공지 요약이 게시되었습니다.
-   V1.1(2010년 2월 11일): MS10-005의 다시 시작 요구 사항이 수정되었습니다.

*Built at 2014-04-18T12:27:44Z-07:00*
