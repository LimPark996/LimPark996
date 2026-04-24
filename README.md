<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hi,%20I'm%20Yumi%20👋&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6B8AF7&center=true&vCenter=true&random=false&width=600&lines=AI+Engineer;RAG+%7C+Video+Retrieval+%7C+Multimodal+AI;%22Making+complex+things+work%22" alt="Typing SVG" /></a>

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
  - Wrote technical deep-dives on VQGAN, Transformer, BERT source code (byumm315.tistory.com)
```

---

## Featured Projects

### VideoRAG — AI-Powered Video Retrieval & Synthesis
> Hybrid retrieval pipeline combining BM25 + InternVideo2 + ColBERT. Selected for government R&D funding (1st round pass).

`InternVideo2` `FAISS` `ColBERT` `BM25` `Runway` `DINOv2` `C2PA` `Gradio`

- Indexed 7,010 MSR-VTT videos with hybrid search: BM25 · Dense · WRRF fusion · ColBERT · ITM reranking
- MSR-VTT 1k-A benchmark: ITC dense alone R@1 3.5% → **R@1 44.4%** after full ITM (paper: 51.9%; −10.6%p gap attributed to unresolved ITC collapse)
- Scene Graph → 2-path routing (USE_AS_IS / TRANSFORM) PD workstation
- DINOv2 transition scoring + DreamColour 3D LUT color grading + C2PA ES256 provenance signing

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/LimPark996/VideoRAG-Public)
[![demo](https://img.shields.io/badge/github-demo-brightgreen)](https://limpark996.github.io/VideoRAG-Public/)

---

### Construction Law RAG Chatbot
> AI chatbot over 9 construction regulation PDFs · Samsung C&T AI Academy project · Team lead

`Python` `FAISS` `BM25` `bge-reranker` `GPT-4o-mini` `Streamlit`

- FAISS + BM25 hybrid retrieval with bge-reranker for precision improvement
- 7-type query classification via GPT-4o-mini with per-type response strategy branching
- Designed step-by-step implementation notebooks for non-developer teammates

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/LimPark996/cntchatbot_pjt1)

---

### Metal Defect Synthesis
> Image synthesis PoC to address manufacturing defect data scarcity

`VQGAN` `MaskGIT` `PyTorch` `HuggingFace` `Gradio`

- v1 (taming VQGAN + custom MaskGIT) → v2 (LlamaGen VQGAN + Halton-MaskGIT): architecture migration driven by codebook incompatibility — Halton-MaskGIT (ICLR 2025) is built for LlamaGen VQGAN and cannot be combined with taming VQGAN; pretrained weights available only for LlamaGen made the switch the practical choice
- Merged 3 datasets including NEU-DET; 2,659 images → 8× augmentation
- VQGAN fine-tuning: Edge IoU +10.6%, PSNR +3.1%, SSIM +0.73%
- MaskGIT training loss 6.77 (target ~4.0) → convergence failure — structural limitation of 69M-param model on 21K data
- Deployed Gradio inpainting demo on HuggingFace Spaces

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/LimPark996/metal-defect-synthesis)
[![Demo](https://img.shields.io/badge/🤗%20HuggingFace-FFD21E?style=flat-square)](https://huggingface.co/Yumi-Park996)

---

### Term Search System
> Hybrid search engine for construction standard terminology

`Python` `FAISS` `ColBERT` `OpenAI API`

- Weighted fusion: OpenAI Embedding semantic similarity (60%) + ColBERT token-level MaxSim (40%)
- Achieved accurate standard term retrieval from colloquial queries
- Circuit Breaker + Rate Limiting for API failure resilience

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/LimPark996/term-search-system-ver1)

---

### Ticketmon — Concert Ticketing Platform
> High-concurrency ticketing system · Bootcamp final project · Team lead

`Spring Boot` `Redis` `MySQL` `React` `Docker` `AWS`

- Designed and implemented AI review summarization feature (Together AI → OpenAI migration)
- Refactored seat management from section-based to grade-based architecture
- Implemented dynamic seat layout rendering based on venue scale (small / medium / large)

[![Backend](https://img.shields.io/badge/Backend-181717?style=flat-square&logo=github)](https://github.com/LimPark996/Ticketing-Website_BE)

---

## Work Experience

| Period | Role | Key Work |
|--------|------|----------|
| 2025.08–11 | AI Instructor, Samsung C&T AI Academy (Elice) | Generative AI curriculum & RAG chatbot training for construction industry professionals |
| 2023.09–2024.12 | Research Team, Woongjin ThinkBig AI Labs | CatBoost difficulty prediction model for exam items (R²=0.57), ALP system reverse analysis |

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
[![Blog](https://img.shields.io/badge/Tech%20Blog-FF5722?style=for-the-badge&logo=tistory&logoColor=white)](https://byumm315.tistory.com/)

</div>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>
