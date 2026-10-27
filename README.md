<div align="center">

# Tejas Das

**Product engineer · CS at Delhi Technological University · Contributor to Apache Airflow and Apple's swift-collections**

I build AI products that know where their limits are, and I check the failure paths before I ship.

[![Portfolio](https://img.shields.io/badge/Portfolio-6E40C9?style=flat-square&logo=vercel&logoColor=white)](https://tejas-portfolio-ivory.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tejas-das-679504373)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:itej1310@gmail.com)

</div>

---

### Open to internships

Product engineering and applied AI roles. I can work from Delhi NCR, Bangalore, Mumbai or Hyderabad, or remotely. The fastest way to reach me is [email](mailto:itej1310@gmail.com).

---

## How I build

Everything below follows from four rules. Each one came out of a real project, and each project shows it.

**1. The model reads; plain code decides.**
In tools where a confident wrong answer does real harm, I keep the language model to *reading*: pulling text out of a document and sorting it into fields. The verdict, and every legal citation behind it, comes from a deterministic engine that a person can read, test and correct. That makes the output testable offline, means a bug gets fixed once in a file instead of chased through prompts, and lets an expert check the logic rather than spot-check generated text. *Used in ClaimShield and SIH26034.*

**2. "Indeterminate" is better than wrong.**
A verdict needs an honest error bar. When a measurement's uncertainty crosses the legal limit, my label checker says *indeterminate*. A guess that looks precise would be worse. *Used in SIH26034.*

**3. Test the path where things go wrong.**
The interesting bugs live in error paths: a file that never gets closed when a transfer fails, or C++ that behaves differently from the code it was meant to mirror. Both of my merged Airflow fixes are this kind of bug. Big-O Odyssey compiles every one of its C++ snippets with memory and undefined-behaviour checks turned on, and compares the output against its TypeScript engines.

**4. Build for the person who has to keep using it.**
For a family business, I made Google Sheets the backend, so the owner can keep working even if the app breaks. A real business runs on it.

---

## Open source: merged upstream

| Project | Pull request | What it fixed |
|---|---|---|
| **Apache Airflow** | [#69083](https://github.com/apache/airflow/pull/69083) | The FTP hook left file handles open when a transfer raised an error |
| **Apache Airflow** | [#69084](https://github.com/apache/airflow/pull/69084) | S3 `download_file` left its handle open after a download, or after a failure |
| **Apple swift-collections** | [#679](https://github.com/apple/swift-collections/pull/679) | `@inlinable deinit` broke builds that enable library evolution |
| **csv-pipe** | [#50](https://github.com/martsinlabs/csv-pipe/pull/50) · [#51](https://github.com/martsinlabs/csv-pipe/pull/51) · [#52](https://github.com/martsinlabs/csv-pipe/pull/52) · [#53](https://github.com/martsinlabs/csv-pipe/pull/53) | Examples and docs for streaming, edge routes, Bun and custom delimiters |

---

## Featured work

### SIH26034: packaging label compliance checker
*Smart India Hackathon 2026 · Department of Consumer Affairs problem statement · 6-person team*

The Legal Metrology rules set minimum print sizes in millimetres, but a photo has no scale. A checker that compares pixel heights is really measuring how close the phone was held. Ours recovers real-world scale from a printed calibration card, reports every measurement with an uncertainty band, and returns *indeterminate* instead of a verdict it can't support. Before the feature freeze, the team ran an internal audit: 23 findings, 22 fixed.

`Next.js` `Python` `OpenCV` `Supabase` · [Live demo](https://sih26034-roan.vercel.app) · [Code](https://github.com/itej13/sih26034)

### ClaimShield: health-insurance claim rejection audit
*Built across two overnight rounds at Cosmicathon, August 2026*

It reads a rejected claim, checks it against IRDAI regulations, and produces a printable dossier ready to send to the Insurance Ombudsman. Gemini only extracts the facts. A fixed rule engine decides which regulation applies, and every citation comes from a file a human maintains, never from the model. Five timed challenges were added to the live product during the event.

`Next.js` `TypeScript` `Gemini` · [Live demo](https://claimshield-iota.vercel.app)

### Big-O Odyssey: a game for learning data structures and algorithms
*Built around my own DTU Data Structures and DAA coursework*

62 levels in 13 worlds. Each level has a lesson, step-by-step visualisers and a test, and the next one unlocks only when you score 80% or more **and** can write the level's C++ from memory with no errors. It has 173 tests, and all 70 C++ snippets are compiled with memory-error and undefined-behaviour checks and compared against the game's TypeScript engines.

`React` `TypeScript` `C++` · [Play](https://ptr-game.vercel.app) · [Code](https://github.com/itej13/ptr-game)

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it does | Links |
|---|---|---|
| **F.R.I.D.A.Y.** | Ask questions about any GitHub repo and get answers that cite the source files (RAG over embeddings and a vector store) | [Demo](https://friday-brown.vercel.app) · [Code](https://github.com/itej13/F.R.I.D.A.Y.) |
| **UniBuddy** | Multi-tenant SaaS that pulls Google Classroom into one dashboard, with each user's data kept separate | [Demo](https://uni-buddy-kappa.vercel.app) · [Code](https://github.com/itej13/UniBuddy) |
| **SafeRoute** | Safety-scored walking routes across Delhi, built from NCRB crime data and crowd ratings, with one-tap SOS | [Demo](https://saferoute-eosin.vercel.app) · [Code](https://github.com/itej13/SafeRoute) |
| **Rain Atlas: Uganda** | Hourly rain forecasts for 16 towns, live Meteosat cloud imagery, and an experimental model with its results published | [Demo](https://uganda-rain-atlas.vercel.app) · [Code](https://github.com/itej13/uganda-rain-atlas) |
| **ReplayIQ** | Finds sports highlights from audio, motion and crowd-reaction signals, and shows why each clip was picked | [Demo](https://replayiq-blush.vercel.app) · [Code](https://github.com/itej13/replayiq) |
| **★ PTR** | Puzzle-platformer where you play as a memory pointer. Built for Vihaan 9 × GoAlgo | [Code](https://github.com/itej13/ptr-game) |

</details>

---

## Hackathons

| Event | Project | When |
|---|---|---|
| Smart India Hackathon 2026 (DTU internal round) | SIH26034 | Sep 2026 |
| Cosmicathon | ClaimShield | Aug 2026 |
| Vihaan 9 × GoAlgo, "Game Up Your DSA" track | ★ PTR | Apr 2026 |
| Vihaan 9.0, DTU, Women's Safety track | SafeRoute | Apr 2026 |

## Experience

- **Machine Learning Intern**, Corizo · Jan–Feb 2026
- **AI Intern**, Corizo (associated with IIT Bombay Mood Indigo) · Oct–Nov 2025

## Toolbox

**Languages:** TypeScript, Python, C++, Swift, SQL
**Product:** Next.js, React, Tailwind, Vite
**Data & AI:** RAG pipelines, Gemini, vector search, OpenCV, measurement uncertainty
**Backend & infra:** Supabase, PostgreSQL row-level security, Prisma, Vercel
**Hardware:** ESP32 BLE, ARKit / LiDAR

I build with AI coding tools daily. What I'm responsible for is the architecture, the review, and knowing when the output is wrong.
