# Hi there, I'm Nelson 🙌

Computer Science student (Software Engineering) at Arizona State University, minoring in Economics.

## 🧭 About Me

CS student at **Arizona State University (Ira A. Fulton Schools of Engineering)** building full-stack, AI-integrated applications. I like taking projects past the demo stage — real test coverage, real evaluation metrics, real architecture decisions, not just a working prototype.

- 🔧 Currently working on:
  - **[Driftline](https://github.com/Nelly444/Drifitline)** — subscription tracker that detects recurring charges from Plaid transaction data using DBSCAN clustering and Holt-Winters forecasting, with real-time drift alerts over WebSocket
- 📌 Seeking **Software Engineering internships** for **Summer 2027**
- 🏛️ Community Officer @ **SoDA (Software Developers Association)** · District Secretary @ **Circle K International** · Secretary @ **ASU Circle K Club**

## ⚙️ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**AI & Data**

![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Cloud & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 💡 Featured Projects

### 📉 [Driftline](https://github.com/Nelly444/Drifitline) — Subscription Tracking & Anomaly Detection

Connects to a bank account via Plaid and automatically detects recurring subscriptions in transaction history, flagging price changes in real time.

- Verified the clustering/drift pipeline via a synthetic evaluation harness (F1 = 0.857, ARI = 0.765)
- Diagnosed and fixed an N+1 query pattern in SQLAlchemy, cutting sync latency from 60s+ to ~3s
- Assembled a FastAPI + React app (~4K LOC, 13 REST + 1 WebSocket endpoint) validated by 44 pytest tests
- Applied DBSCAN clustering and Holt-Winters forecasting to detect subscription price drift in real time

**Tech:** `React` `TypeScript` `FastAPI` `PostgreSQL` `scikit-learn` `Plaid API`

---

### 🌱 [Empact](https://github.com/Nelly444/Empact) — AI-Powered Charity Discovery

Matches a plain-English cause description to real GlobalGiving charity projects using semantic search, not keyword matching.

- Engineered semantic search over ~20 GlobalGiving projects via pgvector, tuned to a 0.25 relevance floor
- Cached AI-generated project summaries via Anthropic Claude, avoiding repeated calls on every page load
- Optimized AI API costs by rate-limiting search endpoints to 12 req/min, an 80% cut from the general limit
- Confirmed reliability of a 6-endpoint FastAPI backend with 104 passing tests across 22 test files

**Tech:** `React` `TypeScript` `FastAPI` `PostgreSQL` `pgvector` `OpenAI API` `Anthropic API`

---

### 🥘 [PantryChef](https://github.com/Nelly444/pantryChef) — Recipe Matching from Your Pantry

Matches users to recipes based on their available pantry ingredients using the Spoonacular API, with nutrition facts included for each result. Built for people with dietary restrictions, or anyone who'd rather not scroll through endless videos to find a recipe.

- Built a full-stack recipe app matching pantry ingredients to recipes via the Spoonacular API
- Designed a weighted ranking algorithm combining ingredient match % with expiration urgency
- Developed a 6-endpoint FastAPI REST API with full test coverage on core matching and caching logic
- Maintained a 129-test suite (pytest + Vitest) across ~3,100 lines of production code

*Note: backend is hosted on Render's free tier and may take 30–60 seconds to spin up on first load.*

**Tech:** `Python` `FastAPI` `React` `Tailwind CSS` `Spoonacular API`

## 🔗 Let's Connect

- ✉️ Email: nelsonsupriyasilp111@gmail.com
- 🔷 LinkedIn: [linkedin.com/in/nelson-supriyasilp](https://linkedin.com/in/nelson-supriyasilp)
- 💻 GitHub: [github.com/Nelly444](https://github.com/Nelly444)
