<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=6E40C9&center=true&vCenter=true&width=650&lines=Hey%2C+I'm+Tejas+%F0%9F%91%8B;AI-native+product+engineer;Apache+Airflow+%C2%B7+Apple+contributor" alt="Typing SVG" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-tejas--portfolio--ivory.vercel.app-6E40C9?style=for-the-badge&logo=vercel&logoColor=white)](https://tejas-portfolio-ivory.vercel.app)
[![GitHub followers](https://img.shields.io/github/followers/itej13?label=Follow&style=social)](https://github.com/itej13)

</div>

---

## Who I am

CS undergrad at **Delhi Technological University** (class of 2029). I build with AI and own the parts it gets wrong: architecture, review, and the failure paths. I've had code merged into **Apache Airflow** and **Apple's swift-collections**, and everything below is live, so you can click and use it.

> *AI writes lines. I own the thinking.*

---

## 🌍 Open source: merged upstream

| Project | PR | What it fixed |
|---------|----|---------------|
| **Apache Airflow** | [#69083](https://github.com/apache/airflow/pull/69083) | FTP hook leaked file handles when a transfer raised |
| **Apache Airflow** | [#69084](https://github.com/apache/airflow/pull/69084) | S3 `download_file` leaked its handle after a download or failure |
| **Apple swift-collections** | [#679](https://github.com/apple/swift-collections/pull/679) | `@inlinable deinit` broke builds with library evolution enabled (HashTree / Sorted storage) |
| **csv-pipe** | [#50](https://github.com/martsinlabs/csv-pipe/pull/50) · [#51](https://github.com/martsinlabs/csv-pipe/pull/51) · [#52](https://github.com/martsinlabs/csv-pipe/pull/52) · [#53](https://github.com/martsinlabs/csv-pipe/pull/53) | Streaming, edge-route, Bun and delimiter examples and docs |

Both Airflow fixes are about resources left open on error paths, the kind of bug that slips through when nobody tests the failure case.

---

## 🚀 Projects

| Project | What it does | Stack | Live |
|---------|-------------|-------|------|
| **SIH26034** | Smart India Hackathon 2026 label-compliance checker for the Legal Metrology rules. Gets real millimetre scale from a printed ArUco card, attaches an uncertainty band to every measurement, and returns *indeterminate* instead of guessing when that band crosses the legal limit | Next.js · Python · OpenCV · Supabase | [▶ Demo](https://sih26034-roan.vercel.app) · [code](https://github.com/itej13/sih26034) |
| **ClaimShield** | Audits Indian health-insurance claim rejections against IRDAI rules. The AI only reads the document; a fixed rule engine makes the call and cites the regulation, then the app builds an Ombudsman-ready dossier | Next.js · TypeScript · Gemini | [▶ Demo](https://claimshield-iota.vercel.app) |
| **Big-O Odyssey** | Level-gated Data Structures + DAA game: 62 levels with visualisers and a C++ recall dojo. 173 tests, and all 70 C++ snippets are compiled under ASan/UBSan and checked against the TypeScript engines | React · TypeScript · Vite | [▶ Play](https://ptr-game.vercel.app) · [code](https://github.com/itej13/ptr-game) |
| **F.R.I.D.A.Y.** | AI codebase mentor. Ask any GitHub repo a question and get answers with **cited sources** (RAG: embeddings → vector store → grounded answers) | Next.js · Gemini · ChromaDB | [▶ Demo](https://friday-brown.vercel.app) · [code](https://github.com/itej13/F.R.I.D.A.Y.) |
| **UniBuddy** | Multi-tenant SaaS that pulls **Google Classroom** into one dashboard (attendance, submissions, timetable) with each user's data kept separate | Next.js 16 · Prisma · Supabase · NextAuth | [▶ Demo](https://uni-buddy-kappa.vercel.app) · [code](https://github.com/itej13/UniBuddy) |
| **SafeRoute** | Women's safety map of Delhi. Scores routes using NCRB crime data plus crowd ratings, with a live heatmap and one-tap SOS | React · TypeScript · Supabase · Leaflet | [▶ Demo](https://saferoute-eosin.vercel.app) · [code](https://github.com/itej13/SafeRoute) |
| **Rain Atlas: Uganda** | Hourly rain forecasts for 16 towns, an animated Meteosat cloud feed, and an experimental rainfall model with its results published | TypeScript · Vite · Vercel Functions | [▶ Demo](https://uganda-rain-atlas.vercel.app) · [code](https://github.com/itej13/uganda-rain-atlas) |
| **ReplayIQ** | Finds sports-video highlights from audio, motion and face-reaction signals, and every highlight can be explained | Python · Streamlit · OpenCV | [▶ Demo](https://replayiq-blush.vercel.app) · [code](https://github.com/itej13/replayiq) |

---

## 🏆 Hackathons

- **Smart India Hackathon 2026**: *SIH26034*, Dept. of Consumer Affairs problem statement. Six-person team, DTU internal round, September 2026
- **Cosmicathon**: *ClaimShield*. Two overnight rounds, five timed challenges built into the live product, August 2026
- **Vihaan 9 × GoAlgo**: *★ PTR*, a puzzle-platformer where you play as the memory pointer ([code](https://github.com/itej13/ptr-game)). "Game Up Your DSA" track, April 2026
- **Vihaan 9.0, DTU Delhi**: *SafeRoute*. Women's Safety track, April 2026

---

## 💼 Experience

- **Machine Learning Intern**, Corizo, Jan–Feb 2026
- **AI Intern**, Corizo (associated with IIT Bombay Mood Indigo), Oct–Nov 2025
- **Coursework**: Supervised Machine Learning (Andrew Ng, Stanford / DeepLearning.AI) · Kaggle Intro + Intermediate ML

---

## 🛠️ Tech I build with

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Also:** RAG / LLM app patterns (Gemini, vector search) · computer vision & measurement uncertainty · Postgres RLS · ARKit / LiDAR · ESP32 BLE firmware

---

## 📫 Reach me

[![Portfolio](https://img.shields.io/badge/Portfolio-6E40C9?style=flat-square&logo=vercel&logoColor=white)](https://tejas-portfolio-ivory.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tejas-das-679504373)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:itej1310@gmail.com)

<div align="center">
<sub>AI-native · merged upstream · shipped in production</sub>
</div>
