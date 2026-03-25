<div align="center">

# Miguel Beltran

**Computer Science @ UC Davis | Class of 2027**

Grew up competing in games and building the PCs to run them. Now I engineer the software.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miguel-j-beltran/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://migueljbeltran.github.io/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:migueljoaquinbeltran@gmail.com)

</div>

---

## About Me

I've been tearing apart hardware and exploring game systems since I was a kid. That curiosity -- wanting to know *how things actually work* under the hood -- is what pulled me into computer science. I have too many hobbies, so I build software around the things I actually care about -- games, tools, and platforms that aren't boring.

**I'm actively seeking Summer 2026 software engineering internships** in full-stack development, gaming, or systems. Authorized to work in the US via CPT (no sponsorship required).

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat&logo=leaflet&logoColor=white)
![Mapbox GL JS](https://img.shields.io/badge/Mapbox_GL_JS-000000?style=flat&logo=mapbox&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=flat&logo=fastapi&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat&logo=firebase&logoColor=black)

**ML**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006400?style=flat&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**DevOps & Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)

---

## Featured Projects

### [dltracker](https://github.com/migueljbeltran/deadlock-tracker)

Full-stack analytics platform for Deadlock (Valve's MOBA shooter) with player search, hero/item win rates, leaderboards, and match scoreboards.

- Built a 10-page, 45-component analytics platform consuming Steam and Deadlock APIs, featuring player search via vanity URL resolution, hero/item win rates across rank brackets, 5-region leaderboards with a 3-signal identity disambiguation algorithm, and match scoreboards with per-player item builds
- Achieved production-grade reliability with IP-based rate limiting (10 req/60s via Upstash Redis), Zod input validation, Sentry error tracking, and 6-tier ISR caching (60s--24h) including an in-memory cache to handle a 2.5MB API response

`Next.js` `TypeScript` `Tailwind CSS` `Prisma` `PostgreSQL` `Redis`

---

### [Song Popularity Predictor](https://github.com/Rytham1/song-popularity-predictor)

ML pipeline that benchmarks 5 models on 32,000+ Spotify tracks to predict hit classification.

- Benchmarked 5 models on 32,000+ Spotify tracks; pivoted from regression (R² ≈ 0.20) to binary hit classification after raw audio features alone explained minimal variance in popularity
- Engineered artist average popularity and one-hot encoded genre/subgenre features with GridSearchCV tuning, boosting Random Forest to 80% accuracy (AUC 0.79), a 12-point gain over baseline Logistic Regression

`Python` `TensorFlow` `XGBoost` `scikit-learn` `Pandas` `NumPy`

---

### [Kitch](https://github.com/migueljbeltran/Kitch)

Full-stack kitchen management app with a Spring Boot REST API and React frontend.

- Designed a full-stack kitchen management app with a 15-endpoint Spring Boot REST API across 3 controllers, 3-layer MVC architecture, a normalized 3-table schema with cascading deletes, and a global exception handler
- Eliminated N+1 queries with JPQL fetch joins and built a transactional batch operation to auto-migrate zero-stock inventory items to the shopping list

`Java` `Spring Boot` `React` `Tailwind CSS` `H2`

---

### [Questify](https://github.com/migueljbeltran/Questify)

Medieval guild-themed gamified task app for roommates — turn chores into quests and climb the ranks.

- Built a gamification engine with XP progression, level thresholds, and achievements using Supabase Realtime for async state sync across sessions
- Implemented row-level security (RLS) policies and a GitHub Actions CI/CD pipeline, reducing deployments from manual steps to fully automated releases

`Next.js` `TypeScript` `React` `Supabase` `PostgreSQL` `Tailwind CSS` `Playwright` `GitHub Actions`

---

### [8-Bit CPU](https://github.com/migueljbeltran/8bit-cpu)

Custom 8-bit processor designed from the ground up in Logisim.

- Designed a 5-stage pipelined 8-bit CPU with data forwarding and hazard detection, correctly executing 20+ custom ISA instructions with zero pipeline stalls on forwarded operands

`Logisim` `Digital Logic` `Computer Architecture`

---

## Experiences

| Role | Organization | Period |
|------|-------------|--------|
| **Assistant Technical Director** | ASUCD Picnic Day | Nov 2025 -- Present |
| **Software Engineer** | Include | Oct 2025 -- Present |
| **Software Engineer** | Google Developer Student Club | Oct 2024 -- June 2025 |

---

<div align="center">

Open to collaborations, internships, and interesting technical conversations.

**Always building, always learning.**

</div>
