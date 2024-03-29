---
TOCTitle: 'MS17-MAR'
Title: 2017년 3월 Microsoft 보안 공지 요약
ms:assetid: 'ms17-mar'
ms:contentKeyID: 74430758
ms:mtpsurl: 'https://technet.microsoft.com/ko-KR/library/ms17-mar(v=Security.10)'
---

2017년 3월 Microsoft 보안 공지 요약
===================================

게시된 날짜: 2017년 3월 14일 | 업데이트된 날짜: 2017년 8월 8일

**버전:** 4.0

이 공지 요약 목록에는 2017년 3월 발표된 보안 공지가 포함되어 있습니다.

Microsoft 보안 공지가 게시될 때 자동 알림을 받는 방법은 [Microsoft 기술 보안 알림](http://go.microsoft.com/fwlink/?linkid=21163)을 참조하십시오.

Microsoft는 월별 보안 업데이트와 동일한 날짜에 발표되는 비보안 업데이트와 보안 업데이트의 우선 순위를 고객이 결정하는 데 도움이 되는 정보도 제공합니다. **기타 정보** 절을 참조하십시오.

참고로 보안 공지 대신 [보안 업데이트 가이드](https://portal.msrc.microsoft.com/ko-kr/security-guidance)가 제공될 예정입니다. 자세한 내용은 Microsoft 블로그 게시물 [보다 효율적인 보안 업데이트 제공을 위한 조치](https://blogs.technet.microsoft.com/msrc/2016/11/08/furthering-our-commitment-to-security-updates/)(영문)를 참조하십시오.

요약
----

<span id="sectionToggle0"></span>
다음 표에는 이번 달의 보안 공지가 심각도 순으로 요약되어 있습니다.

영향받는 소프트웨어에 대한 자세한 내용은 **영향받는 소프트웨어**라는 다음 절을 참조하십시오.

<p></p>
<table style="width:100%;">
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
및 취약성 영향</strong></td>
<td style="border:1px solid black;"><strong>다시 시작 요구 사항</strong></td>
<td style="border:1px solid black;"><strong>알려진<br />
문제</strong></td>
<td style="border:1px solid black;"><strong>영향받는 소프트웨어</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842208">MS17-006</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer용 누적 보안 업데이트(4013073)<br />
</strong>이 보안 업데이트는 Internet Explorer의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 Internet Explorer를 사용하여 특수 제작된 웹 페이지를 볼 경우 원격 코드 실행을 허용할 수 있습니다. 이 취약성 악용에 성공한 공격자는 현재 사용자와 동일한 사용자 권한을 얻을 수 있습니다. 현재 사용자가 관리자 권한으로 로그온한 경우, 이 취약성 악용에 성공한 공격자는 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842207">MS17-007</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge용 누적 보안 업데이트(4013071)<br />
</strong>이 보안 업데이트는 Microsoft Edge의 취약성을 해결합니다. 이 취약성은 사용자가 특수 제작된 웹 페이지를 Microsoft Edge를 사용하여 보는 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 영향받는 시스템을 제어할 수 있습니다. 이렇게 되면 공격자가 프로그램을 설치하거나, 데이터를 보거나 변경하거나 삭제하거나, 모든 사용자 권한이 있는 새 계정을 만들 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842215">MS17-008</a></td>
<td style="border:1px solid black;"><strong>Windows Hyper-V용 보안 업데이트(4013082)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 게스트 운영 체제의 인증된 공격자가 Hyper-V 호스트 운영 체제에서 임의의 코드를 실행하게 하는 특수 제작된 응용 프로그램을 실행할 경우 원격 코드 실행을 허용할 수 있습니다. Hyper-V 역할을 사용하지 않는 고객은 영향을 받지 않습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839436">MS17-009</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows PDF 라이브러리용 보안 업데이트(4010319)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 특수 제작된 PDF 콘텐츠를 온라인으로 보거나 특수 제작된 PDF 문서를 열 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=843149">MS17-010</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows SMB Server용 보안 업데이트(4013389)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성으로 인해 공격자가 Microsoft SMBv1(서버 메시지 블록 1.0) 서버에 특수 제작된 메시지를 보낼 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842211">MS17-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft Uniscribe용 보안 업데이트(4013076)<br />
</strong>이 보안 업데이트는 Microsoft Uniscribe의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 웹 사이트를 방문하거나 특수 제작된 문서를 열 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842212">MS17-012</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows용 보안 업데이트(4013078)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성으로 인해 공격자가 iSNS Server에 연결한 후 서버에 대해 악성 요청을 실행하는 특수 제작된 응용 프로그램을 실행하는 경우 원격 코드 실행이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842210">MS17-013</a></td>
<td style="border:1px solid black;"><strong>Microsoft 그래픽 구성 요소용 보안 업데이트(4013075)<br />
</strong>이 보안 업데이트는 Microsoft Windows, Microsoft Office, 비즈니스용 Skype, Microsoft Lync 및 Microsoft Silverlight의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 웹 사이트를 방문하거나 특수 제작된 문서를 열 경우 원격 코드 실행을 허용할 수 있습니다. 시스템에서 더 낮은 사용자 권한을 가지도록 구성된 계정의 사용자는 관리자 권한으로 작업하는 사용자보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br />
Microsoft Office,<br />
비즈니스용 Skype,<br />
Microsoft Lync,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842278">MS17-014</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office용 보안 업데이트(4013241)</strong><br />
이 보안 업데이트는 Microsoft Office의 취약성을 해결합니다. 이 중에서 가장 심각한 취약성은 사용자가 특수 제작된 Microsoft Office 파일을 열 경우 원격 코드 실행을 허용할 수 있습니다. 이러한 취약성 악용에 성공한 공격자는 현재 사용자의 컨텍스트에서 임의의 코드를 실행할 수 있습니다. 시스템에 대한 사용자 권한이 적게 구성된 계정의 고객은 관리자 권한으로 작업하는 고객보다 영향을 덜 받을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 할 수 있음</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Office Services 및 Web Apps,<br />
Microsoft Server 소프트웨어,<br />
Microsoft 통신 플랫폼 및 소프트웨어</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842279">MS17-015</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server용 보안 업데이트(4013242)<br />
</strong>이 보안 업데이트는 Microsoft Exchange OWA(Outlook Web Access)의 취약성을 해결합니다. 이 취약성은 공격자가 특수 제작된 첨부 파일이 포함된 전자 메일을 취약한 Exchange Server에 전송할 경우 Exchange Server에서 원격 코드 실행을 허용할 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842209">MS17-016</a></td>
<td style="border:1px solid black;"><strong>Windows IIS용 보안 업데이트(4013074)<br />
</strong>이 보안 업데이트는 Microsoft IIS(Internet Information Services)의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 영향받은 Microsoft IIS Server에서 호스트되는 특수 제작된 URL을 클릭하는 경우 권한 상승이 허용될 수 있습니다. 이 취약성 악용에 성공한 공격자는 사용자의 브라우저에서 스크립트를 실행하여 웹 세션에서 정보를 가져올 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842216">MS17-017</a></td>
<td style="border:1px solid black;"><strong>Windows 커널용 보안 업데이트(4013081)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 공격자가 특수 제작된 응용 프로그램을 실행할 경우 이 취약성으로 인해 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842217">MS17-018</a></td>
<td style="border:1px solid black;"><strong>Windows 커널 모드 드라이버용 보안 업데이트(4013083)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이러한 취약성으로 인해 공격자가 영향받는 시스템에 로그온하여 취약성을 악용하고 영향받는 시스템을 제어할 수 있는 특수 제작된 응용 프로그램을 실행할 경우 권한 상승이 허용될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
권한 상승</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839438">MS17-019</a></td>
<td style="border:1px solid black;"><strong>Active Directory Federation Services용 보안 업데이트(4010320)<br />
</strong>이 보안 업데이트는 ADFS(Active Directory Federation Services)의 취약성을 해결합니다. 이 취약성으로 인해 공격자가 ADFS 서버에 특수 제작된 요청을 전송하여 대상 시스템의 중요한 파일을 읽을 수 있게 되는 경우 정보가 유출될 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=836272">MS17-020</a></td>
<td style="border:1px solid black;"><strong>Windows DVD Maker용 보안 업데이트(3208223)<br />
</strong>이 보안 업데이트는 Windows DVD Maker의 정보 유출 취약성을 해결합니다. 공격자는 이 취약성을 통해 대상 시스템을 추가로 손상시킬 수 있는 정보를 얻을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839434">MS17-021</a></td>
<td style="border:1px solid black;"><strong>Windows DirectShow용 보안 업데이트(4010318)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 Windows DirectShow가 악의적인 웹 사이트에서 호스팅되는 특수 제작된 미디어 콘텐츠를 여는 경우 정보가 유출될 수 있습니다. 이 취약성 악용에 성공한 공격자는 대상 시스템을 더 손상시킬 수 있는 정보를 얻을 수 있습니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839435">MS17-022</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services용 보안 업데이트(4010321)<br />
</strong>이 보안 업데이트는 Microsoft Windows의 취약성을 해결합니다. 이 취약성으로 인해 사용자가 악의적인 웹 사이트를 방문할 경우 정보가 유출될 수 있습니다. 하지만 어떠한 경우에도 공격자는 강제로 사용자가 특수 제작된 링크를 클릭하도록 만들 수 없습니다. 공격자는 일반적으로 전자 메일 또는 인스턴트 메신저 메시지에서 유인물을 이용하여 사용자가 이 링크를 클릭하도록 유도해야 합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">중요(영문)</a> <br />
정보 유출</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=844066">MS17-023</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player용 보안 업데이트(</strong>4014329)<br />
이 보안 업데이트는 지원되는 모든 버전의 Windows 8.1, Windows Server 2012, Windows Server 2012 R2, Windows RT 8.1, Windows 10 및 Windows Server 2016에 설치된 Adobe Flash Player의 취약성을 해결합니다.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">긴급(영문)</a> <br />
원격 코드 실행</td>
<td style="border:1px solid black;">다시 시작해야 함</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

악용 가능성 인덱스
------------------

<span id="sectionToggle1"></span>
다음 표에는 이달에 해결된 각 취약성의 악용 가능성 평가가 나와 있습니다. 취약성은 공지 ID, CVE ID 순으로 나열되어 있습니다. 공지에서 심각도 등급이 긴급 또는 중요인 취약성만 포함되어 있습니다.

**이 표를 어떻게 사용합니까?**

이 표를 사용하여 설치해야 할 수 있는 각 보안 업데이트에 대한 보안 공지 발표 후 30일 내 코드 실행 및 서비스 거부 악용 가능성에 대해 자세히 알아볼 수 있습니다. 이달의 업데이트 배포의 우선 순위를 정하려면 사용자의 특정 구성에 따라 아래의 각 평가를 검토하십시오. 이러한 등급의 의미와 등급이 결정되는 방법에 대한 자세한 내용은 [Microsoft 악용 가능성 인덱스](http://technet.microsoft.com/ko-kr/security/cc998259)를 참조하십시오.

아래 열에서 "최신 소프트웨어 릴리스"는 관련 소프트웨어를 나타내며 "이전 소프트웨어 릴리스"는 공지의 "영향받는 소프트웨어" 및 "영향받지 않는 소프트웨어" 표에 나열된 지원 대상인 관련 소프트웨어의 모든 이전 릴리스를 나타냅니다.

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**취약성 제목**

</td>
<td style="border:1px solid black;">
**최신 소프트웨어 릴리스에 대한  
악용 가능성 평가**

</td>
<td style="border:1px solid black;">
**이전 소프트웨어 릴리스에 대한  
악용 가능성 평가**

</td>
<td style="border:1px solid black;">
**서비스 거부  
악용 가능성 평가**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-006: Internet Explorer용 누적 보안 업데이트(4013073)**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0008(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0008)

</td>
<td style="border:1px solid black;">
Internet Explorer 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0009(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0009)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0012(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0012)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0018(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0018)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0033(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0033)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0037(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0037)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0040(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0040)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0049(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0049)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0059(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0059)

</td>
<td style="border:1px solid black;">
Internet Explorer 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0130(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0130)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0149(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0149)

</td>
<td style="border:1px solid black;">
Internet Explorer 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0154(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0154)

</td>
<td style="border:1px solid black;">
Internet Explorer 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-007: Microsoft Edge용 누적 보안 업데이트(4013071)**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0009(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0009)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0010(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0010)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0011(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0011)

</td>
<td style="border:1px solid black;">
Microsoft Edge 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0012(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0012)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0015(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0015)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0017(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0017)

</td>
<td style="border:1px solid black;">
Microsoft Edge 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0023(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0023)

</td>
<td style="border:1px solid black;">
Microsoft PDF 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0032(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0032)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0033(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0033)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 스푸핑 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0034(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0034)

</td>
<td style="border:1px solid black;">
Microsoft Edge 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0035(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0035)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0037(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0037)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0065(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0065)

</td>
<td style="border:1px solid black;">
Microsoft 브라우저 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0066(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0066)

</td>
<td style="border:1px solid black;">
Microsoft Edge 보안 기능 우회 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0067(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0067)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0068(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0068)

</td>
<td style="border:1px solid black;">
Microsoft Edge 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0069(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0069)

</td>
<td style="border:1px solid black;">
Microsoft Edge 스푸핑 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0070(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0070)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0071(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0071)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0094(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0094)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0131(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0131)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0132(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0132)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0133(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0133)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0134(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0134)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0135(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0135)

</td>
<td style="border:1px solid black;">
Microsoft Edge 보안 기능 우회

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0136(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0136)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0137(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0137)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0138(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0138)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0140(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0140)

</td>
<td style="border:1px solid black;">
Microsoft Edge 보안 기능 우회

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0141(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0141)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0150(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0150)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0151(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0151)

</td>
<td style="border:1px solid black;">
스크립팅 엔진 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-008: Windows Hyper-V용 보안 업데이트(4013082)**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0021(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0021)

</td>
<td style="border:1px solid black;">
Hyper-V vSMB 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0051(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0051)

</td>
<td style="border:1px solid black;">
Microsoft Hyper-V 네트워크 스위치 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0074(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0074)

</td>
<td style="border:1px solid black;">
Hyper-V 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0075(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0075)

</td>
<td style="border:1px solid black;">
Hyper-V 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0076(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0076)

</td>
<td style="border:1px solid black;">
Hyper-V 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0095(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0095)

</td>
<td style="border:1px solid black;">
Hyper-V vSMB 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0096(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0096)

</td>
<td style="border:1px solid black;">
Hyper-V 정보 유출 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0097(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0097)

</td>
<td style="border:1px solid black;">
Hyper-V 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0098(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0098)

</td>
<td style="border:1px solid black;">
Hyper-V 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0099(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0099)

</td>
<td style="border:1px solid black;">
Hyper-V 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0109(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0109)

</td>
<td style="border:1px solid black;">
Hyper-V 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-009: Microsoft Windows PDF 라이브러리용 보안 업데이트(4010319)**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0023(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0023)

</td>
<td style="border:1px solid black;">
Microsoft PDF 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-010: Microsoft Windows SMB 서버용 보안 업데이트(4013389)**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0143(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0143)

</td>
<td style="border:1px solid black;">
Windows SMB 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0144(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0144)

</td>
<td style="border:1px solid black;">
Windows SMB 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0145(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0145)

</td>
<td style="border:1px solid black;">
Windows SMB 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0146(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0146)

</td>
<td style="border:1px solid black;">
Windows SMB 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0147(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0147)

</td>
<td style="border:1px solid black;">
Windows SMB 정보 유출 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0148(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0148)

</td>
<td style="border:1px solid black;">
Windows SMB 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-011: Microsoft Uniscribe용 보안 업데이트(4013076)**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0072(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0072)

</td>
<td style="border:1px solid black;">
Uniscribe 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0083(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0083)

</td>
<td style="border:1px solid black;">
Uniscribe 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0084(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0084)

</td>
<td style="border:1px solid black;">
Uniscribe 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0085(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0085)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0086(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0086)

</td>
<td style="border:1px solid black;">
Uniscribe 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0087(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0087)

</td>
<td style="border:1px solid black;">
Uniscribe 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0088(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0088)

</td>
<td style="border:1px solid black;">
Uniscribe 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0089(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0089)

</td>
<td style="border:1px solid black;">
Uniscribe 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0090(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0090)

</td>
<td style="border:1px solid black;">
Uniscribe 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0091(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0091)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0092(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0092)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0111(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0111)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0112(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0112)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0113(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0113)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0114(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0114)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0115(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0115)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0116(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0116)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0117(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0117)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0118(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0118)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0119(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0119)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0120(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0120)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0121(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0121)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0122(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0122)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0123(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0123)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0124(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0124)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0125(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0125)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0126(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0125)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0127(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0127)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0128(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0128)

</td>
<td style="border:1px solid black;">
Uniscribe 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-012: Microsoft Windows용 보안 업데이트(4013078)**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0007(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0007)

</td>
<td style="border:1px solid black;">
Device Guard 보안 기능 우회 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0016(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0016)

</td>
<td style="border:1px solid black;">
SMBv2/SMBv3 Null 역참조 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0039(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0039)

</td>
<td style="border:1px solid black;">
Windows DLL 로드 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0057(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0057)

</td>
<td style="border:1px solid black;">
Windows DNS 쿼리 정보 유출 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0100(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0100)

</td>
<td style="border:1px solid black;">
Windows 도움말 창 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0104(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0104)

</td>
<td style="border:1px solid black;">
iSNS Server 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-013: Microsoft 그래픽 구성 요소용 보안 업데이트(4013075)**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0001(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0001)

</td>
<td style="border:1px solid black;">
Windows GDI 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0005(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0005)

</td>
<td style="border:1px solid black;">
Windows GDI 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
0– 악용 검색됨

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0014(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0014)

</td>
<td style="border:1px solid black;">
GDI+ 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0025(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0025)

</td>
<td style="border:1px solid black;">
Windows GDI 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0038(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0038)

</td>
<td style="border:1px solid black;">
Windows 그래픽 구성 요소 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0047(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0047)

</td>
<td style="border:1px solid black;">
Windows GDI 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0060(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0060)

</td>
<td style="border:1px solid black;">
GDI+ 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0061(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0061)

</td>
<td style="border:1px solid black;">
Microsoft 색 관리 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0062(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0062)

</td>
<td style="border:1px solid black;">
GDI+ 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0063(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0063)

</td>
<td style="border:1px solid black;">
Microsoft 색 관리 정보 유출 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0073(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0073)

</td>
<td style="border:1px solid black;">
Windows GDI+ 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0108(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0108)

</td>
<td style="border:1px solid black;">
Windows 그래픽 구성 요소 원격 코드 실행 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-014: Microsoft Office용 보안 업데이트(4013241)**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0006(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0006)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0019(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0019)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0020(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0020)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0027(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0027)

</td>
<td style="border:1px solid black;">
Microsoft Office 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0029(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0029)

</td>
<td style="border:1px solid black;">
Microsoft Office 서비스 거부 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0030(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0030)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0031(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0031)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0052(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0052)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0053(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0053)

</td>
<td style="border:1px solid black;">
Microsoft Office 메모리 손상 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0105(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0105)

</td>
<td style="border:1px solid black;">
Microsoft Office 정보 유출 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0107(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0107)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint XSS 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0129(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0129)

</td>
<td style="border:1px solid black;">
Mac용 Microsoft Lync 인증서 유효성 검사 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-015: Microsoft Exchange Server용 보안 업데이트(4013242)**](https://go.microsoft.com/fwlink/?linkid=842279)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0110(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0110)

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 권한 상승 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-016: Windows IIS용 보안 업데이트(4013074)**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0055(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0055)

</td>
<td style="border:1px solid black;">
Microsoft IIS Server XSS 권한 상승 취약성(영문)

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-017: Windows 커널용 보안 업데이트(4013081)**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0050(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0050)

</td>
<td style="border:1px solid black;">
Windows 커널 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0101(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0101)

</td>
<td style="border:1px solid black;">
Windows 권한 상승 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0102(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0102)

</td>
<td style="border:1px solid black;">
Windows 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0103(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0103)

</td>
<td style="border:1px solid black;">
Windows 레지스트리 권한 상승 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-018: Windows 커널 모드 드라이버용 보안 업데이트(4013083)**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0024(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0024)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0026(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0026)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0056(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0056)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0078(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0078)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0079(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0079)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0080(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0080)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
영구

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0081(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0081)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0082(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0082)

</td>
<td style="border:1px solid black;">
Win32k 권한 상승 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
1 - 악용 가능성 높음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-019: Active Directory Federation Services용 보안 업데이트(4010320)**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0043(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0043)

</td>
<td style="border:1px solid black;">
Microsoft Active Directory Federation Services 정보 공개 취약성

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
임시

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-020: Windows DVD Maker용 보안 업데이트(3208223)**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0045(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0045)

</td>
<td style="border:1px solid black;">
Windows DVD Maker 교차 사이트 요청 위조 취약성

</td>
<td style="border:1px solid black;">
4 - 영향을 받지 않음

</td>
<td style="border:1px solid black;">
3 - 악용 불가능

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-021: Windows DirectShow용 보안 업데이트(4010318)**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0042(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0042)

</td>
<td style="border:1px solid black;">
Windows DirectShow 정보 유출 취약성

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
2 - 악용 가능성 낮음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-022: Microsoft XML Core Services용 보안 업데이트(4010321)**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0022(영문)](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0022)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 정보 유출 취약성

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
0- 악용 검색됨

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-023: Adobe Flash Player용 보안 업데이트(4014329)**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB17-07](http://helpx.adobe.com/kr/security/products/flash-player/apsb17-07.html)

</td>
<td style="border:1px solid black;">
취약성 심각도 및 업데이트 우선 순위 등급은 Adobe 보안 공지 [APSB17-07](http://helpx.adobe.com/kr/security/products/flash-player/apsb17-07.html)을 참조하십시오.

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 

영향받는 소프트웨어
-------------------

<span id="sectionToggle2"></span>
다음 표에는 주요 소프트웨어 범주 및 심각도 순으로 공지가 나열되어 있습니다.

이 표를 사용하여 설치해야 하는 보안 업데이트를 알 수 있습니다. 나열된 각 소프트웨어 프로그램 또는 구성 요소를 검토하여 설치에 관련된 보안 업데이트가 있는지 확인할 수 있습니다. 소프트웨어 프로그램이나 구성 요소가 나열되어 있으면, 소프트웨어 업데이트의 심각도도 표시되어 있습니다.

**참고** 단일 취약성에 대해 보안 업데이트를 여러 개 설치해야 할 수 있습니다. 나열된 각 공지 ID로 전체 열을 검토하여 시스템에 설치된 프로그램 또는 구성 요소에 따라 설치해야 할 업데이트를 확인하십시오.

### Windows 운영 체제 및 구성 요소(표 1/2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(긴급)  
Microsoft 인터넷 메시징 API  
(3218362)  
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
Windows Vista 서비스 팩 2  
(4012598)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(4012583)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3217587)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(4017018)  
(긴급)  
Windows Vista 서비스 팩 2  
(4012584)  
(중요)  
Windows Vista 서비스 팩 2  
(4012497)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(긴급)  
Microsoft 인터넷 메시징 API  
(3218362)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3211306)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(4012598)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(4012583)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3217587)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(4017018)  
(긴급)  
Windows Vista x64 Edition 서비스 팩 2  
(4012584)  
(중요)  
Windows Vista x64 Edition 서비스 팩 2  
(4012497)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(보통)  
Microsoft 인터넷 메시징 API  
(3218362)  
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
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(4012598)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(4012583)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3217587)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(4012021)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(4017018)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(4012584)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(4012497)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(보통)  
Microsoft 인터넷 메시징 API  
(3218362)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3211306)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(4012598)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(4012583)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3217587)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(4012021)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(4017018)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(4012584)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(4012497)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(4012598)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(4012583)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3217587)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(4017018)  
(긴급)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(4012584)  
(중요)  
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(4012497)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(긴급)

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
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
(긴급)

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
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
보안 전용

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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012212)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
월별 롤업

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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012215)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012213)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012216)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4012204)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4012217)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
보안 전용

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(보통)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
월별 롤업

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012606)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025338)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(4012606)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(4012606)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(4012606)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012606)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025338)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013198)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025344)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(4013198)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(4013198)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(4013198)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013198)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025344)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025339)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(4013429)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025339)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1703(32비트 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025342)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

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
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1703(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025342)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

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
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**보통(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
(보통)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4013429)  
(보통)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

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
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(4012598)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(4012583)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(3217587)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(4017018)  
(긴급)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(4012584)  
(중요)  
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(4012497)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3211306)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(4012598)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(4012583)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(3217587)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(4017018)  
(긴급)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(4012584)  
(중요)  
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(4012497)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012212)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012212)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012215)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012215)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012214)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012214)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012214)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012214)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012217)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012217)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012217)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012217)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012213)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012213)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012216)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012216)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)  
(4013429)  
(긴급)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)  
(4013429)  
(긴급)

</td>
</tr>
</table>
 
**MS17-013 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Windows 운영 체제 및 구성 요소(표 2/2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(4012373)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(4011981)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(4012497)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3205715)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista 서비스 팩 2  
(3214051)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(4012373)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(4011981)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(4012497)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3205715)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition 서비스 팩 2  
(3214051)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(4012373)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(4011981)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(4012497)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3217882)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(3214051)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(4012373)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(4011981)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(4012497)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3217882)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(3214051)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(4012373)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(4011981)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(4012497)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3217882)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008(Itanium 기반 시스템용) 서비스 팩 2  
(3214051)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(32비트 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 7(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(Itanium 기반 시스템용) 서비스 팩 1  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(32비트 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 8.1(x64 기반 시스템용)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 및 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4015548)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4015551)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(32비트 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10(x64 기반 시스템용)  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012606)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(32비트 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1511(x64 기반 시스템용)  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013198)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(32비트 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows 10 버전 1607(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1703(32비트 시스템용)

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
해당 없음

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
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 버전 1703(x64 기반 시스템용)

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
해당 없음

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
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Server Core 설치 옵션**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(4012373)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(4011981)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(32비트 시스템용) 서비스 팩 2(Server Core 설치)  
(4012497)  
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
Microsoft XML Core Services 3.0  
(3216916)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(4012373)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(4011981)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008(x64 기반 시스템용) 서비스 팩 2(Server Core 설치)  
(4012497)  
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
Microsoft XML Core Services 3.0  
(3216916)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012212)  
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
Microsoft XML Core Services 3.0  
(4012212)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2(x64 기반 시스템용) 서비스 팩 1(Server Core 설치)  
(4012215)  
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
Microsoft XML Core Services 3.0  
(4012215)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012214)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012(Server Core 설치)  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012217)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
보안 전용

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core 설치)  
월별 롤업

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2(Server Core 설치)  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
Windows Server 2016(x64 기반 시스템용)  
(Server Core 설치)  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
</table>
 
 

### Microsoft Office 제품군 및 소프트웨어

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 서비스 팩 3  
(3127945)  
(긴급)  
Microsoft Office 2007 서비스 팩 3  
(3141535)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 서비스 팩 3  
(3178676)  
(중요)  
Microsoft Word 2007 서비스 팩 3  
(3178683)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3127958)  
(긴급)  
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3178688)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(32비트 버전)  
(3178686)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(32비트 버전)  
(3178690)  
(중요)  
Microsoft Word 2010 서비스 팩 2(32비트 버전)  
(3178687)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3127958)  
(긴급)  
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3178688)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 서비스 팩 2(64비트 버전)  
(3178686)  
(중요)  
Microsoft Excel 2010 서비스 팩 2(64비트 버전)  
(3178690)  
(중요)  
Microsoft Word 2010 서비스 팩 2(64비트 버전)  
(3178687)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(32비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(32비트 버전)  
(3172542)  
(중요)  
Microsoft Word 2013 서비스 팩 1(32비트 버전)  
(3172464)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 서비스 팩 1(64비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 서비스 팩 1(64비트 버전)  
(3172542)  
(중요)  
Microsoft Word 2013 서비스 팩 1(64비트 버전)  
(3172464)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT 서비스 팩 1

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT 서비스 팩 1  
(3172542)  
(중요)  
Microsoft Word 2013 RT 서비스 팩 1  
(3172464)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016(32비트 버전)  
(3178673)  
(중요)  
Microsoft Word 2016(32비트 버전)  
(3178674)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016(64비트 버전)  
(3178673)  
(중요)  
Microsoft Word 2016(64비트 버전)  
(3178674)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Mac용 Microsoft Excel 2011  
(3198809)  
(중요)  
Mac용 Microsoft Excel 2011  
(3212218)  
(중요)  
Mac용 Microsoft Word 2011  
(3198809)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Mac용 Microsoft Office 2016  
(중요)  
Mac용 Microsoft Excel 2016  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**기타 Office 소프트웨어**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3178677)  
(중요)  
Microsoft Office 호환 기능 팩 서비스 팩 3  
(3178682)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3178680)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3178693)  
(긴급)  
Microsoft Word Viewer  
(3178653)  
(긴급)

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3178694)  
(중요)

</td>
</tr>
</table>
 
**MS17-013 및 MS17-014 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Microsoft Office Services 및 Web Apps

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Excel Services(32비트 버전)  
(3178678)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 서비스 팩 3

</td>
<td style="border:1px solid black;">
Excel Services(64비트 버전)  
(3178678)  
(중요)

</td>
</tr>
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3178685)  
(중요)  
Word Automation Services  
(3178684)  
(중요)

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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Excel Services  
(3172431)  
(중요)

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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 서비스 팩 2  
(3178689)  
(중요)

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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 서비스 팩 1  
(3172457)  
(중요)

</td>
</tr>
</table>
 
**MS17-014 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Microsoft Server 소프트웨어

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**사용 안 함**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 서비스 팩 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 서비스 팩 1  
(3172540)  
(중요)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Exchange Server 2013 Service Pack 1  
(4012178)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 14

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 누적 업데이트 14  
(4012178)  
(중요)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 누적 업데이트 3

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 누적 업데이트 3  
(4012178)  
(중요)

</td>
</tr>
</table>
 
**MS17-014 및 MS17-015 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Microsoft 통신 플랫폼 및 소프트웨어

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**비즈니스용 Skype 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(32비트 버전)  
(3178656)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(32비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(32비트 버전)  
(3178656)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype 2016(64비트 버전)  
(3178656)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(64비트 버전)

</td>
<td style="border:1px solid black;">
비즈니스용 Skype Basic 2016(64비트 버전)  
(3178656)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype)  
(3172539)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(32비트)  
(비즈니스용 Skype Basic)  
(3172539)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype)  
(3172539)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 서비스 팩 1(64비트)  
(비즈니스용 Skype Basic)  
(3172539)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(32비트)  
(4010299)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010(64비트)  
(4010299)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(사용자 수준 설치)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(사용자 수준 설치)  
(4010300)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(관리자 수준 설치)  
(4010301)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 콘솔**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 콘솔

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 콘솔  
(4010303)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 추가 기능**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**없음**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 추가 기능

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 추가 기능  
(4010304)  
(긴급)

</td>
<td style="border:1px solid black;">
해당 없음

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Mac용 Microsoft Lync**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
**없음**

</td>
<td style="border:1px solid black;">
[**중요(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Mac 2011용 Microsoft Lync

</td>
<td style="border:1px solid black;">
해당 없음

</td>
<td style="border:1px solid black;">
Mac 2011용 Microsoft Lync  
(4012487)  
(중요)

</td>
</tr>
</table>
 
**MS17-013 및 MS17-014 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

### Microsoft 개발자 도구 및 소프트웨어

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**공지 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**전체 심각도**

</td>
<td style="border:1px solid black;">
[**긴급(영문)**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5  
(4013867)  
**(**긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5 Developer 런타임

</td>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 클라이언트에 설치된 Microsoft Silverlight 5 Developer 런타임  
(4013867)  
**(**긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5  
(4013867)  
**(**긴급)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5 Developer 런타임

</td>
<td style="border:1px solid black;">
지원되는 모든 릴리스의 Microsoft Windows 서버에 설치된 Microsoft Silverlight 5 Developer 런타임  
(4013867)  
**(**긴급)

</td>
</tr>
</table>
 
**MS17-013 참고 사항**

이 공지는 둘 이상의 소프트웨어 범주에 해당합니다. 기타 영향받는 소프트웨어를 확인하려면 이 절의 다른 표를 참조하십시오.

 

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
Microsoft는 신뢰할 수 있는 취약성 공개를 통해 고객을 보호하는 데 도움을 주는 보안 커뮤니티의 공로를 기립니다. 자세한 내용은 [감사의 말](https://technet.microsoft.com/ko-kr/library/security/mt745121.aspx)(영문)을 참조하십시오.

기타 정보
---------

<span id="sectionToggle5"></span>
### Microsoft Windows 악성 소프트웨어 제거 도구

매월 둘째 주 화요일마다 발표하는 보안 공지에서 Microsoft는 Windows Update, Microsoft Update, Windows Server Update Services 및 다운로드 센터를 통해 업데이트된 버전의 Microsoft Windows 악성 소프트웨어 제거 도구를 출시했습니다. Microsoft Windows 악성 소프트웨어 제거 도구의 업데이트 버전은 부정기 보안 공지 릴리스에서 제공되지 않습니다.

### MU, WU 및 WSUS의 비보안 업데이트

Windows Update 및 Microsoft Update의 비보안 릴리스에 대한 자세한 내용은 다음을 참조하십시오.

-   [Microsoft 기술 자료 문서 894199](https://support.microsoft.com/ko-kr/kb/894199): 변경된 Software Update Services 및 Windows Server Update Services 내용에 대한 설명. 모든 Windows 콘텐츠 포함.
-   [Windows Server Update Services용으로 지난 몇 달간 배포된 업데이트](http://technet.microsoft.com/ko-kr/wsus/bb456965)(영문). Microsoft Windows가 아닌 Microsoft 제품용 신규, 개정 및 재출시 업데이트를 전부 표시합니다.

### MAPP(Microsoft Active Protections Program)

고객을 위한 보안을 강화하기 위해 Microsoft는 각각의 월별 보안 업데이트를 발표하기 전에 주요 보안 소프트웨어 제공업체에 취약성 정보를 제공합니다. 보안 소프트웨어 제공업체는 이 취약점 정보를 사용하여 바이러스 백신, 네트워크 기반 침입 탐지 시스템 또는 호스트 기반 침임 방지 시스템 등 자사의 보안 소프트웨어나 장치를 통해 업데이트된 보호 기능을 고객에게 제공할 수 있습니다. 보안 소프트웨어 제공업체가 활성 보호 기능을 제공하는지 확인하려면 [Microsoft MAPP(Active Protections Program) 파트너](http://go.microsoft.com/fwlink/?linkid=215201)(영문)에 나열된 프로그램 파트너가 제공하는 활성 보호 기능 웹 사이트를 참조하십시오.

### 보안 전략 및 커뮤니티

**업데이트 관리 전략**

[업데이트 관리를 위한 보안 가이드(중요)](http://go.microsoft.com/fwlink/?linkid=21168)(영문)는 보안 업데이트 적용에 대해 Microsoft가 권장하는 모범 사례와 관련한 추가 정보를 제공합니다.

**기타 보안 업데이트 받기**

기타 보안 문제 관련 업데이트는 다음 사이트에서 제공됩니다.

-   보안 업데이트는 [Microsoft 다운로드 센터](http://go.microsoft.com/fwlink/?linkid=21129)에서 제공됩니다. "보안 업데이트"라는 키워드 검색을 수행하면 가장 쉽게 찾을 수 있습니다.
-   소비자 플랫폼용 업데이트는 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)에서 제공됩니다.
-   이달에 제공되는 보안 업데이트는 Windows Update를 통해서 또는 다운로드 센터에서 제공되는 보안 및 긴급 릴리스 ISO CD 이미지 파일로 받을 수 있습니다. 자세한 내용은 [Microsoft 기술 자료 문서 913086](https://support.microsoft.com/ko-kr/kb/913086)을 참조하십시오.

**IT Pro Security Community(IT 전문가 보안 커뮤니티)**

[IT 전문가 보안 커뮤니티](http://go.microsoft.com/fwlink/?linkid=21164)에서는 보안을 강화하고 IT 인프라를 최적화하는 방법에 대해 알아보고 보안 항목에 대한 정보를 다른 IT 전문가와 공유할 수 있습니다.

### 지원

나열된 영향받는 소프트웨어는 테스트를 거쳐 영향받는 버전이 확인되었습니다. 다른 버전은 지원 기간이 끝났습니다. 사용 중인 소프트웨어 버전에 대한 지원 기간을 확인하려면 [Microsoft 지원 주기](http://go.microsoft.com/fwlink/?linkid=21742)를 참조하십시오.

IT 전문가용 보안 솔루션: [TechNet 보안 문제 해결 및 지원](http://technet.microsoft.com/ko-kr/security/bb980617)

Windows가 실행되는 컴퓨터를 바이러스 및 맬웨어로부터 보호: [바이러스 솔루션 및 보안 센터](http://support.microsoft.com/ko-kr/contactus/cu_sc_virsec_master)

지역별 지원 정보: [국가별 지원](http://support.microsoft.com/ko-kr/common/international.aspx)

### 고지 사항

Microsoft 기술 자료에서 제공되는 정보는 어떠한 보증도 없이 "있는 그대로" 제공됩니다. Microsoft는 상품성과 특정 목적에 대한 적합성의 보증을 포함하여 명시적이거나 묵시적인 모든 보증을 부인합니다. Microsoft Corporation 또는 그 공급자는 모든 직접적, 간접적, 부수적, 파생적 손해 또는 영업 이익 손실 또는 특수한 손실에 대하여 어떠한 경우에도 책임을 지지 않으며, 이는 Microsoft Corporation과 그 공급자가 그와 같은 손해의 가능성을 사전에 알고 있던 경우에도 마찬가지입니다. 일부 지역에서는 파생적 또는 부수적 손해에 대한 책임의 배제 또는 제한을 허용하지 않으므로 위 제한이 적용되지 않을 수도 있습니다.

### 수정 내역

-   V1.0(2017년 3월 14일): 공지 요약이 게시되었습니다.
-   V2.0(2017년 4월 11일): 다음 업데이트를 알리기 위해 수정된 공지 요약입니다.
    -   MS17-013에 대한 Windows Vista 및 Windows Server 2008용 업데이트 4017018의 발표. 이 업데이트는 취약성을 포괄적으로 해결하기 위해 CVE-2017-0038용 업데이트 4012583만 대체합니다. 이 영향받는 소프트웨어를 실행하는 고객은 이 공지에 설명된 취약성으로부터 시스템을 완벽하게 보호할 수 있도록 보안 업데이트를 설치하는 것이 좋습니다. 자세한 내용은 [Microsoft 기술 자료 문서 4017018](https://support.microsoft.com/ko-kr/kb/4017018)을 참조하세요.
    -   MS17-014의 경우 Office for Mac 2011용 CVE-2017-0027만 포괄적으로 해결하기 위해 Microsoft는 보안 업데이트 3212218을 발표했습니다. Office for Mac 2011을 실행하는 고객의 경우 이 취약성으로부터 완벽하게 보호받으려면 업데이트 3212218을 설치하는 것이 좋습니다. 자세한 내용은 [Microsoft 기술 자료 문서 3212218](https://support.microsoft.com/ko-kr/kb/3212218)을 참조하세요.
    -   MS17-021의 경우 이제 Windows Server 2012용 CVE-2017-0042에 적용되는 보안 업데이트가 출시되었습니다. Windows Server 2012를 실행하는 고객은 업데이트 4015548(보안 전용) 또는 4015551(월별 롤업)을 설치해야 이 취약성으로부터 완전히 보호받을 수 있습니다. 다른 버전의 Microsoft Windows를 실행하는 고객은 조치를 취할 필요가 없습니다.
-   악용 가능성 인덱스를 0 - 악용 검색됨으로 업데이트하기 위해 수정된 V2.1(2017년 4월 14일) CVE-2017-0022입니다. 이 변경 사항은 정보 제공용입니다.
-   V3.0(2017년 5월 9일): MS17-013의 경우 Microsoft는 영향받는 버전의 Windows Server 2008을 대상으로 보안 업데이트 4017018을 다시 발표했습니다. 이러한 재릴리스는 보안 업데이트로 다시 분류되었습니다. CVE-2017-0038로부터 완벽하게 보호받으려는 고객은 업데이트 4017018을 설치하는 것이 좋습니다. 업데이트를 이미 설치한 고객은 추가 조치를 취할 필요가 없습니다.
-   V4.0(2017년 8월 8일): MS17-007의 경우 Microsoft는 CVE-2017-0071을 포괄적으로 해결하기 위해 모든 버전의 Windows 10을 대상으로 7월 보안 업데이트를 발표했습니다. Windows 10(32비트 시스템), Windows 10(x64 기반 시스템), Windows 10 버전 1703(32비트 시스템) 및 Windows 10 버전 1703(x64 기반 시스템)은 이러한 취약성의 영향을 받기 때문에 영향을 받는 제품 표에 추가되었습니다. 2017년 7월 보안 업데이트를 아직 설치하지 않은 고객의 경우 이 취약성으로부터 완전히 보호받으려면 업데이트를 설치해야 합니다.

*2017년 8월 2일 12:34-07:00에 페이지가 생성되었습니다.*