> 기술은 도구일 뿐, 결국 중요한 건 사람이라고 믿습니다.
> 
> 코드 한 줄도 “왜”를 설명할 수 있는 개발자이자,
>
> 분석 설계의 구조와 방향을 함께 고민하는 데이터 사이언티스트를 지향합니다.
> 
> 팀원들의 의견을 최대한 반영하고, 팀의 속도에 발맞추는 협업을 좋아합니다.
> 
> 완벽하지 않아도, 항상 더 나아지려는 방향을 선택합니다.
> 

## Skill

- **백엔드**: Spring Boot, Spring MVC, Servlet, Session 기반 인증
- **프론트엔드**: React, HTML, CSS, Javascript
- **데이터베이스**: Supabase, RDB 개념 (SQLD 보유)
- **데브옵스:** Docker, Render, GitHub Actions, CI/CD
- **언어:** Java 17, Maven
- **ETC:** JSP, MVC 구조 이해 및 구현

---
## History

### 🧩 Development Projects

**PETTY – 반려동물 동반 여행지 & 숙소 & 음식점 추천 웹서비스**

**[GitHub (코드)](https://github.com/LimPark996/PETTY) | [Service (배포)](quantumguinea.github.io/FE-BASE/)**

*JavaScript, HTML, CSS, KakaoMap API, Gemini API, Supabase, GitHub Pages*

- 부트캠프 팀 프로젝트로, **반려동물과 함께 여행할 수 있는 장소를 추천해주는 웹 서비스**
- LLM + RAG 기반의 사용자 입력 분석을 통해 맞춤형 장소를 추천하는 기능 구현
- 반려동물 사진을 분석해 우리집 반려동물 특성 리포트(“WoW Moment”) 제공
- 집사 커뮤니티 기능을 통해 반려동물 관련 정보를 자유롭게 작성하고 공유할 수 있음
- 로그인 및 회원가입 기능을 구현해 개인화된 서비스 경험 제공
- GitHub Pages를 통한 배포 진행

*issues!*

- SupaBase 연동 GitHub 계정 소멸 > 계정 재생성 및 복구 중
![_- visual selection (11)](https://github.com/user-attachments/assets/07e38214-a424-422d-b21d-31523ca6309f)
![ChatGPT Image 2025년 3월 28일 오후 03_21_52 (1)](https://github.com/user-attachments/assets/fa4326b9-d8fe-40d7-9590-d436a8da0234)
---

**AIStockGuide – AI 기반 해외 주식 투자 가이드 웹 애플리케이션**

**[GitHub (코드)](https://github.com/LimPark996/Investment-Helper) | [Service (배포)](https://investment-guides.onrender.com)**

*Java, JSP/Servlet, OpenAI API, Youtube API, Docker, Render*

- 사용자 질문을 분석해 해외 주식 투자 정보를 제공하는 웹 애플리케이션 개발
- Java 기반 백엔드와 JSP/Servlet을 활용해 서버 사이드 렌더링 구현
- OpenAI API를 연동하여 **AI 기반 투자 상담 기능** 개발
- Supabase를 사용해 투자 FAQ 및 유튜브 영상 데이터 관리, 랜덤 노출 기능과 함께 구현
- SNS 공유 시 자동으로 미리보기 카드가 생성되도록 오픈 그래프(OGTAG) 기능 구현
- Docker 및 Render를 이용해 배포 환경 구성, 실제 운영 가능한 형태로 서비스 완성
![_- visual selection (12)](https://github.com/user-attachments/assets/5e88576f-62dc-4e44-aaa9-77bfeafb0fba)
![ChatGPT Image 2025년 3월 28일 오후 03_31_01 (1)](https://github.com/user-attachments/assets/c77c46f5-d7f3-4470-8ad0-78b21eccf87c)
---

**FixBot – 증상 기반 전자제품 고장 진단 챗봇**

**[프론트엔드](https://github.com/LimPark996/FixBot-FrontEnd) | [백엔드](https://github.com/LimPark996/FixBot-BackEnd)**

**[Service (배포)](https://fixbot-backend.onrender.com)**

*React, Java Spring Boot, OpenAI API, YouTube·Google API, Gemini API, Supabase, Docker, Render*

- **자연어 입력 기반 전자제품 고장 진단 및 해결책을 제시하는 AI 챗봇 서비스**
- OpenAI API를 활용해 질문 분석, 검색어 자동 생성
- 이후, YouTube·Google API로 관련 콘텐츠 추천
- 필요 시 AI가 직접 해결책을 생성, 대화 흐름에 따라 단계적으로 증상 좁혀감
- Supabase + Vision API(Gemini)를 연동해 이미지 기반 고장 원인 추정 기능 구현
- React 프론트엔드와 Spring Boot 백엔드를 분리 개발 및 Docker + Render로 배포
![_- visual selection (14)](https://github.com/user-attachments/assets/5428de90-8499-49d5-8f72-91021a386f20)
![ChatGPT Image 2025년 3월 28일 오후 04_13_27 (1)](https://github.com/user-attachments/assets/31e472c0-b052-490d-af3a-aa7482b6de36)
---

### 📊 Data Analysis Projects at Woongjin Thinkbig

**📊 도서지수 기반 A/B 테스트 실험 기획 | 2024.10 ~ 2024.12**

- **AI 기반 콘텐츠 추천 화면에서 도서지수의 효과를 검증하기 위한 A/B 테스트 실험을 기획**
- 실험 대상 섹션(S07, S08) 정의, 실험군·대조군 구성, 도서 난이도 구간(쉬움/적정/어려움) 수립, 지표(완독률, 적정 열람률) 정의 등을 직접 수행
- SQL 기반 열람 로그 데이터를 활용하여, 실험 지표 산출 가능성을 사전에 검토
- 연령별 도서지수 분포가 유사해 실험 효과가 희석될 수 있다는 점, 고레벨 도서 부족으로 인해 콘텐츠 재구성에 제약이 있다는 현실적 조건을 분석
- 실험의 타당성과 실행 가능성을 반복적으로 점검하며, 사수와 전략을 지속적으로 조정해 나감
![_- visual selection (5)](https://github.com/user-attachments/assets/ca2dfac5-f5c3-4214-bbea-49a3db698578)
---

**🧠 문항 난이도 예측 회귀 모델 MVP 설계 | 2024.04 ~ 2024.09**

- **지문·문항 메타 데이터를 활용해 학년군 회귀 모델(MVP)을 기획하고 모델링 전 과정을 수행**
- 기존 정답률 기반 지표의 설명력 부족 문제를 보완하기 위해, 학습 이력·문항 메타·지문 특성을 반영한 해석 가능한 모델을 설계
- 사수가 작성한 기존 지표 추출 코드를 참고하되, 지표 범위를 페이지 → 지문 단위로 조정하고, 추가 변수를 정의해 데이터셋을 확장
- SQL과 Python을 활용해 문항 메타, 이력, 지문 데이터를 정제·병합하고, CatBoost 회귀 모델을 구축
- Stratified Split, 변수 중요도 분석, 예측값 해석 등을 통해 모델 구조를 점검하고, 성능보다 해석 가능성과 실무 활용성에 중점을 둠
- 실험 설계와 지표 정의 기준은 팀장 및 사수와 함께 조율하고, 결과는 주 1회 공유하며 피드백을 반영
![_- visual selection (10)](https://github.com/user-attachments/assets/45c661ff-5d3c-4a50-9fa3-753e086b8fb4)
---
**🔍 ALP 모델 분석 및 경량화 기초 설계 | 2023.12 ~ 2024.05**

- **ALP(Adaptive Learning Platform) 기반 서비스·로직·지표 구조를 분석하고, 고도화 논의의 기반이 될 수 있도록 내부 문서를 재정리**
- 기존에도 구조도와 문서화 자료는 있었으나 정리 방식이 복잡해, 실무 적용과 내부 이해에 어려움이 있었음
- R 스크립트, JAVA 소스 코드, DB 테이블을 열람하며 API 호출 흐름, Rules 기반 로직, 클러스터 레벨 지표의 활용 위치 등을 파악
- 분석한 내용을 바탕으로, 기능별 흐름과 UI 구조를 연계해 실무에서 참고 가능한 형태로 문서화
- 특히, ALP 기반 주간 학습 리포트 생성 과정을 JAVA 코드 단위에서 추적하고, 엑셀 기반 구조도로 재정리하여 팀장에게 공유
- 최종적으로 로직, 지표 정의, 호출 흐름 등을 통합해 실무 적용 가능한 정리 자료를 구축하고, 상무 보고용 요약 자료로도 가공해 팀 내 공유
![_- visual selection (9)](https://github.com/user-attachments/assets/5f9dee42-7675-4b93-a45a-4bc34b44db9d)
