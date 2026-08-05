# Hi there, I'm Nelson 🙌
 
Computer Science student (Software Engineering) at Arizona State University, minoring in Economics.
 
## 🧭 About Me
 
CS student at **Arizona State University (Ira A. Fulton Schools of Engineering)** building full-stack, AI-integrated applications. I like taking projects past the demo stage — real test coverage, real evaluation metrics, real architecture decisions, not just a working prototype.
 
- 🔧 Currently working on:
  - **[Driftline](#)** — subscription tracker that detects recurring charges from Plaid transaction data using DBSCAN clustering and Holt-Winters forecasting, with real-time drift alerts over WebSocket
  - **[Empact](#)** — semantic search over real GlobalGiving charity projects using pgvector and OpenAI embeddings, with cached AI-generated summaries via Anthropic Claude
  - **[PantryChef](#)** — recipe matching app with a custom weighted ranking algorithm combining ingredient overlap and expiration urgency
- 📌 Seeking **Software Engineering internships** for **Summer 2027**
- 🏛️ Community Officer @ **SoDA (Software Developers Association)** · District Secretary @ **Circle K International** · Secretary @ **ASU Circle K Club**
## ⚙️ Tech Stack
 
**Languages**
`Java` `Python` `JavaScript` `TypeScript` `SQL`
 
**Backend**
`FastAPI` `Flask` `Node.js`
 
**Frontend**
`React` `Tailwind CSS`
 
**AI & Data**
`Anthropic API` `OpenAI API` `PostgreSQL` `pgvector`
 
**Cloud & Tools**
`Docker` `GitHub Actions` `Render` `Vercel` `Git` `pytest`
 
## 💡 Featured Projects
 
### 📉 [Driftline](#) — Subscription Tracking & Anomaly Detection
 
Connects to a bank account via Plaid and automatically detects recurring subscriptions in transaction history, flagging price changes in real time.
 
- Verified the clustering/drift pipeline via a synthetic evaluation harness (F1 = 0.857, ARI = 0.765)
- Diagnosed and fixed an N+1 query pattern in SQLAlchemy, cutting sync latency from 60s+ to ~3s
- Assembled a FastAPI + React app (~4K LOC, 13 REST + 1 WebSocket endpoint) validated by 44 pytest tests
- Applied DBSCAN clustering and Holt-Winters forecasting to detect subscription price drift in real time
**Tech:** `React` `TypeScript` `FastAPI` `PostgreSQL` `scikit-learn` `Plaid API`
 
---
 
### 🌱 [Empact](#) — AI-Powered Charity Discovery
 
Matches a plain-English cause description to real GlobalGiving charity projects using semantic search, not keyword matching.
 
- Engineered semantic search over ~20 GlobalGiving projects via pgvector, tuned to a 0.25 relevance floor
- Cached AI-generated project summaries via Anthropic Claude, avoiding repeated calls on every page load
- Optimized AI API costs by rate-limiting search endpoints to 12 req/min, an 80% cut from the general limit
- Confirmed reliability of a 6-endpoint FastAPI backend with 104 passing tests across 22 test files
**Tech:** `React` `TypeScript` `FastAPI` `PostgreSQL` `pgvector` `OpenAI API` `Anthropic API`
 
---
 
### 🥘 [PantryChef](#) — Recipe Matching from Your Pantry
 
Matches users to recipes based on their available pantry ingredients using the Spoonacular API.
 
- Built a full-stack recipe app matching pantry ingredients to recipes via the Spoonacular API
- Designed a weighted ranking algorithm combining ingredient match % with expiration urgency
- Developed a 6-endpoint FastAPI REST API with full test coverage on core matching and caching logic
- Maintained a 129-test suite (pytest + Vitest) across ~3,100 lines of production code
**Tech:** `Python` `FastAPI` `React` `Tailwind CSS` `Spoonacular API`
 
## 📈 GitHub Stats
 
<!-- Replace YOUR_USERNAME below with your GitHub username -->
[![Nelson's GitHub stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=dark)](https://github.com/Nelly444)
 
## 🔗 Let's Connect
 
- ✉️ Email: nelsonsupriyasilp111@gmail.com
- 🔷 LinkedIn: [linkedin.com/in/nelson-supriyasilp](https://linkedin.com/in/nelson-supriyasilp)
- 💻 GitHub: [github.com/Nelly444](https://github.com/Nelly444)
