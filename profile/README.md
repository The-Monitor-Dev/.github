## ERD

<img width="1122" alt="erd-the-moni" src="https://github.com/user-attachments/assets/a99906ff-382f-4dae-9c87-9aa1a3231009">

## API 명세서
노션에서 확인 부탁드립니다!

[https://valley-tenor-1ca.notion.site/API-4f03316c133a40a48c0dc4412e9925dd?pvs=4](https://www.notion.so/API-4f03316c133a40a48c0dc4412e9925dd?pvs=21)

## 아키텍처

![더모니터 아키텍처](https://github.com/user-attachments/assets/e7df8644-5637-448d-96b3-6eb276d51be8)

> **MVP 포함 핵심 기능**
> 

<aside>
1️⃣

**회원가입**

![회원](https://github.com/user-attachments/assets/5fad631a-854c-46d3-8bb3-dcf285aa7777)

📍 메일주소 사칭 방지를 위한 메일 인증 기능을 포함한 회원가입

📍 대표 메일로 로그인 후, 관리자가 추후 어드민 페이지에서 각 고객사 별 담당자에게 권한 부여 가능

</aside>

<aside>
2️⃣

**고객사 추가**

![고객사](https://github.com/user-attachments/assets/c7b0993d-0345-4cad-96c4-c3d1cdf783c3)
📍 간단한 정보 입력 플로우를 통해 고객사 워크스페이스 생성 가능

📍  자사/경쟁사/업계에 대한 모니터링 키워드 및 수신인 메일 사전 등록

</aside>

<aside>
3️⃣

**데일리 모니터링 [MVP]**

![데일리 모니터링](https://github.com/user-attachments/assets/391aed13-858d-4e68-9c43-084163caf16c)

📍 키워드에 따른 기사를 보여주고, 원하는 기사를 골라 보고서에 추가할 수 있는 The Monitor의 **가장 핵심적인 기능** 

</aside>

<aside>
4️⃣

**보고서 편집**

![편집](https://github.com/user-attachments/assets/de86ec24-f9b4-4780-83f5-0182433ea2eb)
📍 데일리 모니터링에서 스크랩한 기사의 제목, 헤드라인, URL, 기자명 등을 하나하나 기록할 필요 없이 클릭 한 번으로 보고서 형식에 바로 반영

📍 로고, 제목, 색상, 카테고리 등을 커스텀하여 통일된 보고서 형식에서 베리에이션 추가

📍 보고서 편집 후 고객사 담당자에게 빠른 메일 전송

</aside>

<aside>
5️⃣

**보고서 관리**

![관리](https://github.com/user-attachments/assets/dbf5001e-4198-43eb-b669-a115c1c458cf)

📍 최대 1년 간의 모니터링 보고서를 모아볼 수 있도록 하는 기능

📍 이전에 작업한 보고서도 편집 가능하며, 스크랩한 내역도 함께 저장

</aside>

> **경쟁사와의 차별점을 만들 기능**
> 

<aside>
6️⃣

**뉴스 분석**

📍 **AI 활용 업계 동향 분석**

[보고서 관리] 에 저장된 모니터링 결과물을 바탕으로 유저가 설정한 기간 동안 가장 유의미했던 업계 이슈와 경쟁사의 PR 이슈를 AI를 통해 도출하는 기능

📍 **빠른 2차 산출물 제작할 수 있는 기능**

데일리 모니터링 보고서를 바탕으로 대행사에서는 **[위클리 리포트], [먼슬리 리포트], [분기 리포트]** 를 작성함. 리포트 작성에 들어가는 업무 리소스를 줄일 수 있도록 **모니터링 결과물에서 자동으로 성과 분석 그래프와 표를 도출**해주는 기능

</aside>
