<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hi,%20I'm%20Yumi%20👋&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6B8AF7&center=true&vCenter=true&random=false&width=600&lines=AI+Engineer;RAG+%7C+Video+Retrieval+%7C+Data+Pipeline;%22%EB%B3%B5%EC%9E%A1%ED%95%9C+%EA%B2%83%EC%9D%84+%EC%9E%91%EB%8F%99%ED%95%98%EA%B2%8C+%EB%A7%8C%EB%93%A0%EB%8B%A4%22" alt="Typing SVG" /></a>

</div>

---

## About Me

```yaml
name: Yumi Park
location: Seoul, Korea
education: M.S. Statistics, Dongguk University
focus: RAG Systems · Video Retrieval · Data Pipelines

background:
  - Designed and built RAG systems for enterprise document search
  - Built Video RAG prototype for gov't R&D project (1st round pass)
  - ML modeling at EdTech company (Woongjin ThinkBig AI Labs)
  - Taught generative AI to non-developers at Samsung C&T AI Academy
```

---

## Featured Projects

### VideoRAG — AI-Powered Video Retrieval & Synthesis
> BM25 + InternVideo2 + ColBERT 하이브리드 검색 파이프라인. 정부 R&D 과제 1차 통과.

`InternVideo2` `FAISS` `ColBERT` `BM25` `Runway` `DINOv2` `C2PA` `Gradio`

- 7,010개 MSR-VTT 영상 인덱싱 + 하이브리드 검색(BM25·Dense·WRRF 융합·ColBERT 리랭킹)
- Scene Graph → 3경로 분기(USE_AS_IS / TRANSFORM / GENERATE) PD 워크스테이션
- MSR-VTT 1k-A 벤치마크 평가 파이프라인 구축 중 (Dense R@1 논문 기준선 51.9 대조)
- DINOv2 전환 효과 + DreamColour LUT 색보정 + C2PA ES256 출처 서명

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/LimPark996/VideoRAG-Public)

---

### Construction Law RAG Chatbot
> 건설 법규 9개 PDF 기반 AI 챗봇 · 삼성물산 AI Academy 교육 프로젝트 (팀 리더)

`Python` `FAISS` `BM25` `bge-reranker` `GPT-4o-mini` `Streamlit`

- FAISS + BM25 하이브리드 검색 + bge-reranker 정밀도 향상
- GPT-4o-mini로 질의 7가지 유형 분류 후 유형별 응답 전략 분기
- 비전공자 팀원이 직접 구현할 수 있는 단계별 실습 ipynb 설계

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/LimPark996/cntchatbot_pjt1)

---

### Metal Defect Synthesis
> 제조업 결함 데이터 부족 문제 해결을 위한 이미지 합성 PoC

`VQGAN` `MaskGIT` `PyTorch` `HuggingFace` `Gradio`

- LlamaGen VQGAN + Halton-MaskGIT (ICLR 2025) 파이프라인 설계
- NEU-DET 등 3종 데이터셋 통합, 2,659장 → 8배 증강, VQGAN 파인튜닝 Edge IoU +10.6%
- Weighted sampling으로 클래스 불균형 보정, Gradio inpainting 데모 배포

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/LimPark996/metal-defect-synthesis)
[![Demo](https://img.shields.io/badge/🤗%20HuggingFace-FFD21E?style=flat-square)](https://huggingface.co/Yumi-Park996)

---

### Term Search System
> 건설 표준 용어 하이브리드 검색 엔진

`Python` `FAISS` `ColBERT` `OpenAI API`

- OpenAI Embedding(의미 유사도 60%) + ColBERT 토큰별 최대 유사도(40%) 가중 결합
- 구어체 질의 → 정확한 표준 용어 검색 달성
- Circuit Breaker + Rate Limiting API 장애 대응 구조 설계

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/LimPark996/term-search-system-ver1)

---

### Ticketmon — Concert Ticketing Platform
> 대규모 동시접속 티켓팅 시스템 · 부트캠프 파이널 프로젝트 (팀장)

`Spring Boot` `Redis` `MySQL` `React` `Docker` `AWS`

- AI 리뷰 요약 기능 설계 및 CRUD 구현 (Together AI → OpenAI 모델 전환 포함)
- 좌석 파트 리팩토링 — 구역(section) 기반에서 등급(grade) 기반 좌석 관리로 전환
- 공연장 규모(small/medium/large)에 따른 좌석 배치도 동적 조정 구현

[![Backend](https://img.shields.io/badge/Backend-181717?style=flat-square&logo=github)](https://github.com/LimPark996/Ticketing-Website_BE)

---

## Work Experience

| 기간 | 역할 | 주요 내용 |
|------|------|-----------|
| 2025.08–11 | 삼성물산 AI Academy 강사 (엘리스) | 건설업 실무진 대상 생성형 AI 교육, RAG 챗봇 커리큘럼 설계 |
| 2023.09–2024.12 | 웅진씽크빅 AI Labs 연구팀 | 국어 문항 난이도 예측 CatBoost 모델 (R²=0.57), ALP 시스템 역추적 분석 |

---

## Skills

<div align="center">

#### AI / RAG / Search
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00A4EF?style=for-the-badge&logo=meta&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗%20HuggingFace-FFD21E?style=for-the-badge)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)

#### ML / Data
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

#### Backend / Infra
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%EC%9C%A0%EB%AF%B8-%EB%B0%95-4a766828a/)
[![HuggingFace](https://img.shields.io/badge/🤗%20HuggingFace-FFD21E?style=for-the-badge)](https://huggingface.co/Yumi-Park996)

</div>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>
