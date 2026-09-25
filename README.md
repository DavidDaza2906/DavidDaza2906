<div align="center">

# David Daza

**Computer Science student at Universidad Nacional de Colombia (Bogotá).**
I like to work on LLM agents, AI safety and research, low-level development and full-stack development :)

<br>

[![UNAL](https://img.shields.io/badge/Universidad_Nacional_de_Colombia-Computer_Science-0B6E4F?style=for-the-badge&logo=googlescholar&logoColor=white)](https://unal.edu.co)
[![Focus](https://img.shields.io/badge/Focus-LLM_agents_%26_AI_safety-4B0082?style=for-the-badge)](#-what-im-working-on)
[![Full-stack](https://img.shields.io/badge/Full--stack-Next.js_·_Python_·_Postgres-000000?style=for-the-badge&logo=vercel&logoColor=white)](#toolbox)
[![Low-level](https://img.shields.io/badge/Low--level-Rust_·_Linux-000000?style=for-the-badge&logo=rust&logoColor=white)](#toolbox)

[![JamBox](https://img.shields.io/badge/%E2%96%B6_Live-jamboxacademy.com-EA4AAA?style=for-the-badge&logo=musicbrainz&logoColor=white)](https://jamboxacademy.com)
[![Email](https://img.shields.io/badge/Email-daviddaza2906%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daviddaza2906@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-daviddaza2906-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/daviddaza2906/)

</div>

---

## 🎧 What I'm working on

**JamBox** — [jamboxacademy.com](https://jamboxacademy.com) — an online music academy with real
students and real payments flowing through it. I design, build and run the platform end to end:
product, database, billing, notifications, deploys.

- 🎼 Next.js 16 (App Router) · Supabase/Postgres · Wompi payment links **and recurring charges** ·
  Resend · web push · Playwright E2E — 53 pages, 36 migrations, dev and prod kept honest by sha.
- 🧾 Everything a paid product needs and demos never show: trials, subscription state, group theory
  sessions, didactic resources, a per-student subscribable calendar that publishes cancellations
  **as cancellations**, and notices written in each person's language.
- 🔒 Source is private (client product, JAMBOX ACADEMY S.A.S.); the product itself is public.

Alongside that:

- 🤖 **LLM agent safety research.** Co-author of *Rare Once It Costs Anything: Costly Cooperation
  Between LLM Agents* — a preregistered study (AI Incident Response Sprint, Apart Research,
  September 2026) where helping is strictly dominated. 127 runs, six tool-using agents, a
  hash-chained event log, and an aggregator that refuses to trust each run's own summary.
- 🔎 **Retrieval that can be audited.** RAG over Colombian legal documents with automatic quality
  evaluation, and a self-assessment tool for SMEs with layered anti-hallucination design and
  verifiable generated artifacts.
- ⚙️ **Low-level and full-stack side by side.** Neural networks and renderers written from scratch in
  Rust, next to Flask APIs with `Decimal` money arithmetic.

## Selected work

| Project | What it is |
|---|---|
| 🎧 **JamBox** · [live](https://jamboxacademy.com) | Subscription platform for an online music academy, in production with paying students: Next.js 16 + Supabase + Wompi recurring billing, bilingual site, E2E suite at 127 passing / 2 skipped / 0 failing. Private repository. |
| 🧪 [rare-once-it-costs-anything-costly-cooperation-between-llm-agents](https://github.com/DavidDaza2906/rare-once-it-costs-anything-costly-cooperation-between-llm-agents) | Paper, harness and data. When delivering a useless key was free ~47% of agents did it; when it cost anything, 23.9% did — and quadrupling the price moved delivery only 7.4 points. Rates are stated as upper bounds, with a validity checker that flags harness defects instead of hiding them. |
| 🏛️ [ai-saas-playbook](https://github.com/DavidDaza2906/ai-saas-playbook) | Self-assessment for AI governance in SMEs, mapped against NIST AI RMF, ISO 42001 and the consolidated UNESCO/OECD principles. Deterministic three-dimensional diagnostic vector, prioritised recommendations, RAG that produces verifiable artifacts. Global South AI Safety Hackathon 2026, Track 1. |
| ⚖️ [rag-legal-colombia](https://github.com/DavidDaza2906/rag-legal-colombia) | RAG over Colombian court rulings and statutes: semantic chunking, `multilingual-e5-base` + ChromaDB retrieval, cited answers, and automatic scoring of faithfulness, relevance and context quality with RAGAS. |
| 👕 [retail-image-classifier](https://github.com/DavidDaza2906/retail-image-classifier) | MobileNetV3-Small fine-tuned on DeepFashion InShop (17.7K studio photos), 78.5% accuracy over 12 garment categories, exported to ONNX and served in the browser through ONNX Runtime Web with the preprocessing pipeline shown step by step. |
| 💳 [roda-backend](https://github.com/DavidDaza2906/roda-backend) · [roda-frontend](https://github.com/DavidDaza2906/roda-frontend) | Simulation and application API for electric-mobility credit: Pydantic validation, `Decimal` arithmetic for money, explicit business rules, plus a small front end that consumes it. |
| 🦀 [MNIST-Rust](https://github.com/DavidDaza2906/MNIST-Rust) · [3d_cube_rust](https://github.com/DavidDaza2906/3d_cube_rust) | Rust for fundamentals: a digit recogniser written without ML frameworks and a software-rendered 3D cube. |

## Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

## Before this

**Database responsible — Instituto Nacional de Salud** (2024): data governance and quality control
models, validation of large datasets, SQL query optimisation, automation of recurring reports.
Before that, freelance data analysis since 2023 — cleaning and filtering multi-million-row
databases so people could actually search them.

## How I try to work

- Preregister the analysis, then report the confidence interval — including the unflattering one.
- Automate the check, not the conclusion: the run loop writes a hash-chained log and the
  aggregator independently recomputes what the run claims.
- Say what a number is a bound for. "Upper bound" belongs in the sentence, not in a footnote.

<div align="center">

📬 [daviddaza2906@gmail.com](mailto:daviddaza2906@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/daviddaza2906/)

</div>
