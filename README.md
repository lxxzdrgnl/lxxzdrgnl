# Hi there, I'm Rheon Lee 👋

### A Curious Developer Who Thrives on Challenges

I am a student developer passionate about **Web Development** and **AI Technologies**.
I enjoy building distributed systems and exploring ways to integrate AI models into real-world applications.

[![LeetCode Stats](https://leetcard.jacoblin.cool/pung4905?border=0&radius=20)](https://leetcode.com/pung4905)

---

### Projects

#### [blueming — LoRA Community Platform](https://github.com/lxxzdrgnl/Lora-community)
> **A Comprehensive Platform for Training, Sharing, and Generating AI LoRA Models.**

> **Live:** [blueming.rheon.kr](https://blueming.rheon.kr/) · **API:** [api-blueming.rheon.kr/swagger-ui](https://api-blueming.rheon.kr/swagger-ui.html)

A platform where users can train, share, and generate images using custom LoRA models built on Stable Diffusion. Includes a full training pipeline with data preprocessing, serverless GPU inference via Modal, and a community gallery for sharing results.

| Component | Stack |
| :--- | :--- |
| **Backend** | [![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)](https://github.com/lxxzdrgnl/Lora-community) Spring Boot · OAuth2/JWT · MySQL |
| **AI Serving** | [![FastAPI](https://img.shields.io/badge/FastAPI-005571?logo=fastapi&logoColor=white)](https://github.com/lxxzdrgnl/Lora-training-api) FastAPI · Stable Diffusion · Modal (Serverless GPU) |
| **Frontend** | [![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white)](https://github.com/lxxzdrgnl/LoRA-Platform-Front) Vue.js · Tailwind CSS |
| **Infra** | Docker · Nginx · AWS → Self-hosted |

---

#### [sajuguri — AI Fortune Reading Service](https://github.com/lxxzdrgnl/SajuNara)
> **Your personal fortune, not a category — a conclusion.**

> **Live:** [sajuguri.rheon.kr](https://sajuguri.rheon.kr) · **API:** [api-sajuguri.rheon.kr/docs](https://api-sajuguri.rheon.kr/docs)

Korean traditional four-pillar astrology reimagined with AI. Instead of generic labels like "average wealth luck", the system cross-analyzes your birth chart and real concern to generate insights written only for you. A **RAG + multi-agent pipeline**: a pure Python calculation engine (12-step) feeds a ChromaDB knowledge base of 105 curated documents, which a Planner → Critic → Writer agent chain transforms into a structured 10-tab report.

| Component | Stack |
| :--- | :--- |
| **Backend** | [![FastAPI](https://img.shields.io/badge/FastAPI-005571?logo=fastapi&logoColor=white)](https://github.com/lxxzdrgnl/SajuNara) FastAPI · LangChain (LCEL) · OpenAI GPT-4o |
| **AI / RAG** | ChromaDB · Gemini embedding-001 · Strategy Pattern (GPT-4o / Gemini / Claude) |
| **Frontend** | [![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white)](https://github.com/lxxzdrgnl/SajuNara) Nuxt.js 3 · Pinia · Tailwind CSS |
| **Infra** | PostgreSQL · Docker · Google OAuth2 + JWT |

---

#### [under-line — AI Lyrics Interpretation Service](https://github.com/lxxzdrgnl/under-line)
> **Discover the hidden meaning behind every lyric, line by line.**

> **Live:** [underline.rheon.kr](https://underline.rheon.kr) · **API:** [underline.rheon.kr/docs](https://underline.rheon.kr/docs)

A line-by-line lyrics interpretation service. Search any song, and GPT-4o streams back translations, slang decoding, cultural references, and hidden meanings — per line. Spotify integration lets you import playlists and jump straight from NowPlaying to lyrics.

| Component | Stack |
| :--- | :--- |
| **Full-stack** | [![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white)](https://github.com/lxxzdrgnl/under-line) Next.js 16 (App Router) · TypeScript · Tailwind CSS v4 |
| **AI** | OpenAI GPT-4o (NDJSON streaming) · GPT-4o-mini (translation) |
| **Data** | PostgreSQL · Prisma 7 · Genius API (search, scraping, annotations) |
| **Integration** | Spotify Web API (NowPlaying, playlist import) · Google & Spotify OAuth (PKCE) |
| **Infra** | Docker Compose · Nginx · Swagger UI |

---

### In Progress

#### [RoyaleLog — Clash Royale Analytics Platform](https://github.com/lxxzdrgnl/RoyaleLog-api)
> **Automated battle log collection, card tier lists, and AI-powered matchup predictions.**

A full-stack Clash Royale analytics platform. The backend collects and processes **10M+ battle logs** via BFS expansion from top-ranked players, generates daily card tier lists, and delegates win-rate predictions to a FastAPI ML service. The frontend provides player search, match history, deck analysis, and stat visualizations.

| Component | Stack |
| :--- | :--- |
| **Backend** | [![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)](https://github.com/lxxzdrgnl/RoyaleLog-api) Spring Boot 3 · Java 21 (Virtual Threads) · Spring Batch · Redis |
| **ML Serving** | FastAPI · Matchup prediction model · Statistical fallback |
| **Frontend** | [![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white)](https://github.com/lxxzdrgnl/RoyaleLog-front) Vue 3 · TypeScript · Vite · Pinia |
| **Infra** | PostgreSQL · Redis · Docker / K3s · Prometheus + Micrometer |

---

### Creative Projects

#### AI Voice Conversion (RVC)
> **Showcasing practical AI application skills through content creation.**
> Created a G-Dragon AI cover using RVC (Retrieval-based Voice Conversion) technology, garnering over **570K+ views** on YouTube.

[![GD AI Cover](http://img.youtube.com/vi/QxKxegbUzS4/0.jpg)](https://www.youtube.com/watch?v=QxKxegbUzS4)

---

### Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Backend & AI**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Modal](https://img.shields.io/badge/Modal-Serverless_GPU-5D3FD3?style=for-the-badge)

**Frontend**
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Nuxt.js](https://img.shields.io/badge/Nuxt.js-00DC82?style=for-the-badge&logo=nuxtdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

**Infrastructure & Database**
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kubuntu](https://img.shields.io/badge/Kubuntu-0079C1?style=for-the-badge&logo=kubuntu&logoColor=white)
