# JOBLOG
<img> 메인 사진 들어갈 예정

## 목차
[1️. 개요](#1️⃣-개요)<br>
[2. 팀원 소개](#2️⃣-팀원-소개)<br>
[3. 개발 환경](#3️⃣-개발-환경)<br>
[4. 서비스 화면](#4️⃣-서비스-화면)<br>
[5. 주요 기능](#5️⃣-주요-기능)<br>
[6. 기술 소개](#6️⃣-기술-소개)<br>
[7. 설계 문서](#7️⃣-설계-문서)<br>
<br><br>

# 1️⃣ 개요
### JOBLOG는 청년이 주체적으로 취업 과정을 준비해나갈 수 있도록 취업 전반의 과정을 케어해주는 종합 취업지원 웹 서비스입니다<br>

### 💡 한곳에 모아, 한눈에 볼 수 있는 내 정보
- 이력서 작성 자동화
- 자기소개서 문항별 커스텀 카테고리화
- 나의 취준캘린더

### 💡 정보의 재사용성 극대화
- 사용자 지원 현황 트래킹을 통한 데이터 수집
- 스크랩 공고의 전형별 리뷰작성과 현직자의 기업리뷰

### 💡 개인 맞춤 연결형 지원 서비스
- 희망 직무 기반의 채용공고 추천
- 취업 궁금증을 해결할 현직자와의 실시간 화상 커피챗
<br><br>

# 2️⃣ 팀원 소개
|![정휘원](/uploads/22a5a783edead303fbcd7ced34249136/정휘원.png)|![김보경](/uploads/24414d1039e5ef0f00cacc36ac4fc20f/김보경.png)|![박시연](/uploads/db4e69215316ef52b10a202cdc77996d/박시연.png)|![방소영](/uploads/d005208653bd789b73784afca51939de/방소영.png)|![이현영](/uploads/93fb371a9278fcf97c02548a73357848/이현영.png)|![이희병](/uploads/5d7201d3ce00122a9f8c7c46156a52fd/이희병.png)|
|:--:|:--:|:--:|:--:|:--:|:--:|
|정휘원|김보경|박시연|방소연|이현영|이희병|
|FrontEnd & Leader|BackEnd|FrontEnd|BackEnd|BackEnd|BackEnd|
|Data Binding<br>Function|CRUD<br>Function|Design<br>UCC|Infra<br>WebRTC|Entity<br>Batch|Certification<br>Kafka|

<br><br>

# 3️⃣ 개발 환경
<div style="display:flex; flex-direction:column; align-items:flex-start;">
    <p><strong>⚡ Management Tool</stron-g></p>
    <div>
        <img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"> 
        <img src="https://img.shields.io/badge/gitlab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white">  
        <img src="https://img.shields.io/badge/mattermost-0058CC?style=for-the-badge&logo=mattermost&logoColor=white"> 
        <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"> 
       <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
    </div>
    <br>
    <p><strong>⚡ IDE</strong></p>
    <div>
        <img src="https://img.shields.io/badge/vscode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"> 
        <img src="https://img.shields.io/badge/intellij-000000?style=for-the-badge&logo=intellijidea&logoColor=white">  
    </div>
    <br>
    <p><strong>⚡ Infra</strong></p>
    <div>
        <img src="https://img.shields.io/badge/amazon ec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> 
        <img src="https://img.shields.io/badge/amazon s3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"> 
        <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
        <img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
    </div>
    <br>
    <!-- Frontend -->
    <p><strong>⚡ Frontend</strong></p>
    <div>
        <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
        <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
        <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
        <img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white">
        <img src="https://img.shields.io/badge/vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=white">
    </div>
    <br>
    <!-- Backend -->
    <p><strong>⚡ Backend</strong></p>
    <div>
        <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white"> 
        <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=spring boot&logoColor=white">
       <img src="https://img.shields.io/badge/spring jpa-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
       <img src="https://img.shields.io/badge/spring batch-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
       <img src="https://img.shields.io/badge/spring security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
       <img src="https://img.shields.io/badge/jwt-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
       <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white">
       <img src="https://img.shields.io/badge/apache kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white">
    </div>
    <br>
    <!-- Database -->
    <p><strong>⚡ Database</strong></p>
    <div>
        <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
    </div>
    <br>
    <!-- Server -->
    <p><strong>⚡ Server</strong></p>
    <div>
        <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black">
    </div>
    <br>
    <!-- Others -->
    <p><strong>⚡ Code review</strong></p>
    <div>
        <img src="https://img.shields.io/badge/gerrit-EEEEEE?style=for-the-badge&logo=gerrit&logoColor=black"> 
    </div>
    <br>
</div>
<br><br>

# 4️⃣ 서비스 화면
<img> 화면 사진 들어갈 예정
<br><br>

# 5️⃣ 주요 기능
### 📌 개인 맞춤 채용일정 관리
- 스크랩 공고 전형 일정 캘린더 연동
- 외부 전형 관리
- 개인 일정 관리
- 전형 리뷰 다이어리 작성

### 📌 이력서 자소서 통합 관리/내보내기
- 이력서 자동 완성
- 자소서 맞춤법 검사
- 이력서 자소서 통합 관리
- PDF 내보내기 

### 📌 현직자-취준생 커피챗
- WebRTC 활용 실시간 화상 커피챗
- 현직자-취준생 커넥션 생성
- 추가 질문 Q&A 게시판 이용

### 📌 실시간 알림 기능
- 커피챗 신청, 수락 및 거절 알림
- 금일 개인 일정 알림
- 마감 임박 전형 일정 알림
- 지원 현황 및 복기 알림

### 📌 OpenAI 면접 예상질문 제공
- 자소서 기반 모의면접
- Chat GPT Open API 활용 예상질문 추천
<br><br>

# 6️⃣ 기술 소개
### 📂 취준 캘린더
- FullCalendar를 활용하여 사용자의 맞춤형 경험 제공

### 📂 실시간 화상 커피챗
- WebRTC를 활용한 텍스트 및 화상 채팅 기능으로 뛰어난 사용자 경험 제공

### 📂 소셜 로그인
- Spring Security와 OAuth2.0을 활용하여 로그인 및 회원가입 절차 최소화

### 📂 채용 공고
- Spring Batch와 사람인 API를 활용하여 정확하고 방대한 채용 공고 제공

### 📂 실시간 알림
- Kafka와 SSE를 활용한 알림 기능으로 일정 관리의 편의성 제공

<br><br>

# 7️⃣ 설계 문서
## Swagger
![JOBLOG_SWAGGER](/uploads/05374104564a44f82a3a720905c54ea4/JOBLOG_SWAGGER.PNG)

## ERD
![JOBLOG_ERD](/uploads/ec59e000d92562feeccac88c31605502/JOBLOG_ERD.png)

## 서비스 아키텍처
![아키텍처](/uploads/d44811c0ee260fe0e1ee7809ca5a1446/아키텍처.png)
