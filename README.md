<h1 align="center">Hi, I'm Sudhanshu Singh 👋</h1>

<h3 align="center">Backend Developer | Python · FastAPI · PostgreSQL · Redis</h3>

<p align="center">
Final-year BCA student (2024–2027) who builds production-style backend systems: secure auth, atomic checkouts, rate limiting, tested APIs and CI gates. Currently looking for SDE / backend internships.
</p>

<p align="center">
  <a href="shudhanshu2708/shudhanshu2708.github.io"><img src="https://img.shields.io/badge/Portfolio-FF7139?style=for-the-badge&logo=firefox&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/sudhanshuisingh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://leetcode.com/u/Sudhanshu9035/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
  <a href="https://www.codechef.com/users/sudhanshu9035"><img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white"/></a>
  <a href="mailto:sudhanshu9035@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

## 🚀 Featured Projects

### 🛡️ [AI Guardrails Gateway](https://github.com/shudhanshu2708/AI-guardrails-gateway)
Prompt-injection defense for tool-using LLM agents. Six layered defenses: injection detection, quarantine of untrusted content, tool privilege levels, human approval, and secret-leak filtering.
- Attack success fell from **100% to 0%** in a 25-attack red-team suite, while **94%** of legitimate tasks still completed
- **40 pytest tests**, plus a GitHub Actions gate that fails the build if attack success rises above 5%

`FastAPI` `React` `PostgreSQL` `SQLAlchemy` `Docker` `GitHub Actions`

### 🛒 [Vendly](https://github.com/shudhanshu2708/vendly)
Full-stack e-commerce app with **24 REST endpoints** across auth, catalog, cart and orders.
- JWT auth with 15-minute access tokens and single-use refresh tokens stored in Redis
- Customer/admin roles through reusable FastAPI dependencies
- **Atomic checkout:** stock check, order creation and inventory update in one PostgreSQL transaction, rolled back on any failure

`FastAPI` `React` `PostgreSQL` `Redis` `Alembic` `Docker`

### 🏆 [Real-Time Leaderboard](https://github.com/shudhanshu2708/realtime-leaderboard-backend)
Live ranking app where players submit scores and see their rank update instantly.
- Redis sorted sets for fast ranking, MySQL as the permanent record (Redis rebuilt from MySQL on startup)
- Live top-10 updates with Server-Sent Events
- JWT auth and per-IP rate limiting

`FastAPI` `React` `Redis` `MySQL` `SSE` `Docker`

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend & Frameworks**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Jinja2](https://img.shields.io/badge/Jinja2-B41717?style=flat-square&logo=jinja&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Databases & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

**AI / ML & RAG**

**AI / ML & LLM**

![LLMs](https://img.shields.io/badge/LLM_Apps-412991?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![Prompt Injection Defense](https://img.shields.io/badge/Prompt_Injection_Defense-B71C1C?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Naive Bayes](https://img.shields.io/badge/Naive_Bayes-4CAF50?style=flat-square)
---

## 📊 Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shudhanshu2708&show_icons=true&theme=radical" height="160"/>
</p>
