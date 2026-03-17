# Hi there, I'm Rheon Lee 👋

### A Curious Developer Who Thrives on Challenges

I am a student developer passionate about **Web Development** and **AI Technologies**.
I enjoy building distributed systems and exploring ways to integrate AI models into real-world applications.

[![LeetCode Stats](https://leetcard.jacoblin.cool/pung4905?border=0&radius=20)](https://leetcode.com/pung4905)

---

### Projects

#### [사주구리 — AI 사주 상담 서비스](https://github.com/lxxzdrgnl/SajuNara)
> **Your personal fortune, not a category — a conclusion.**

> **Live:** [sajuguri.rheon.kr](https://sajuguri.rheon.kr) · **API:** [api-sajuguri.rheon.kr/docs](https://api-sajuguri.rheon.kr/docs)

Korean traditional four-pillar astrology (사주팔자) reimagined with AI. Instead of generic labels like "average wealth luck", the system cross-analyzes your birth chart and real concern to generate insights written only for you — *"In your mid-30s, wealth will surge like water bursting through rock cracks."*

Technically, a **RAG + multi-agent pipeline**: a pure Python calculation engine (12-step) feeds a ChromaDB knowledge base of 105 curated astrology documents, which a Planner → Critic → Writer agent chain transforms into a structured 10-tab report.

| Component | Stack |
| :--- | :--- |
| **Frontend** | [![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white)](https://github.com/lxxzdrgnl/SajuNara) Nuxt.js 3 · Pinia · Tailwind CSS |
| **Backend** | [![FastAPI](https://img.shields.io/badge/FastAPI-005571?logo=fastapi&logoColor=white)](https://github.com/lxxzdrgnl/SajuNara) LangChain (LCEL) · OpenAI GPT-4o |
| **AI / RAG** | ChromaDB · Gemini embedding-001 · Strategy Pattern (GPT-4o / Gemini / Claude) |
| **Infra** | PostgreSQL · Docker · Google OAuth2 + JWT |

---

#### [LoRA Community Platform](https://github.com/lxxzdrgnl/Lora-community)
> **A Comprehensive Platform for Training, Sharing, and Generating AI LoRA Models.**

> **Live Demo:** [Visit the Website](https://blueming.rheon.kr/)

| Component | Stack | Description |
| :--- | :--- | :--- |
| **Core Backend** | [![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)](https://github.com/lxxzdrgnl/Lora-community) | User Auth (OAuth2/JWT), Business Logic, Database Management **(Deployed on AWS Elastic Beanstalk -> self hosted)** |
| **AI Serving** | [![FastAPI](https://img.shields.io/badge/FastAPI-005571?logo=fastapi&logoColor=white)](https://github.com/lxxzdrgnl/Lora-training-api) | **Data Preprocessing**, **Stable Diffusion-based AI Training & Generation** powered by **Modal (Serverless GPU)** |
| **Frontend** | [![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white)](https://github.com/lxxzdrgnl/LoRA-Platform-Front) | Responsive Web UI hosted on **AWS S3 -> self hosted** |

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
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Modal](https://img.shields.io/badge/Modal-Serverless_GPU-5D3FD3?style=for-the-badge)

**Frontend**
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Nuxt.js](https://img.shields.io/badge/Nuxt.js-00DC82?style=for-the-badge&logo=nuxtdotjs&logoColor=white)

**Infrastructure & Database**
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Kubuntu](https://img.shields.io/badge/Kubuntu-0079C1?style=for-the-badge&logo=kubuntu&logoColor=white)
