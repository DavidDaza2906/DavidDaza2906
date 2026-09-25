# David Daza

**Computer Science student at Universidad Nacional de Colombia (Bogotá).**
I work on LLM agents, retrieval systems, and the measurement problem between them — most of my
recent work is building the instrument and evaluating what the models actually do, not just
demoing what they can be coaxed into.

---

## What I'm working on

- **LLM agent safety research.** Co-author of *Rare Once It Costs Anything: Costly Cooperation
  Between LLM Agents* — a preregistered study (AI Incident Response Sprint, Apart Research,
  September 2026) where helping is strictly dominated. 127 runs, six tool-using agents, a
  hash-chained event log, and an aggregator that refuses to trust each run's own summary.
- **Retrieval that can be audited.** RAG over Colombian legal documents with automatic quality
  evaluation, and a self-assessment tool for small businesses with layered anti-hallucination
  design and verifiable generated artifacts.
- **Plain engineering, deployed.** Flask + PostgreSQL APIs with decimal money arithmetic, Next.js
  front ends, CNN inference shipped as a single ONNX file that runs in the browser, and a
  self-hosted Linux homelab that is my daily driver.

## Selected work

| Project | What it is |
|---|---|
| [rare-once-it-costs-anything-costly-cooperation-between-llm-agents](https://github.com/DavidDaza2906/rare-once-it-costs-anything-costly-cooperation-between-llm-agents) | Paper, harness and data. When delivering a useless key was free ~47% of agents did it; when it cost anything, 23.9% did — and quadrupling the price moved delivery only 7.4 points. Rates are stated as upper bounds, with a validity checker that flags harness defects instead of hiding them. |
| [ai-saas-playbook](https://github.com/DavidDaza2906/ai-saas-playbook) | Self-assessment for AI governance in SMEs, mapped against NIST AI RMF, ISO 42001 and the consolidated UNESCO/OECD principles. Deterministic three-dimensional diagnostic vector, prioritised recommendations, RAG that produces verifiable artifacts. Global South AI Safety Hackathon 2026, Track 1. |
| [rag-legal-colombia](https://github.com/DavidDaza2906/rag-legal-colombia) | RAG over Colombian court rulings and statutes: semantic chunking, `multilingual-e5-base` + ChromaDB retrieval, cited answers, and automatic scoring of faithfulness, relevance and context quality with RAGAS. |
| [retail-image-classifier](https://github.com/DavidDaza2906/retail-image-classifier) | MobileNetV3-Small fine-tuned on DeepFashion InShop (17.7K studio photos), 78.5% accuracy over 12 garment categories, exported to ONNX and served in the browser through ONNX Runtime Web with the preprocessing pipeline shown step by step. |
| [roda-backend](https://github.com/DavidDaza2906/roda-backend) · [roda-frontend](https://github.com/DavidDaza2906/roda-frontend) | Simulation and application API for electric-mobility credit: Pydantic validation, `Decimal` arithmetic for money, explicit business rules, plus a small front end that consumes it. |
| [MNIST-Rust](https://github.com/DavidDaza2906/MNIST-Rust) · [3d_cube_rust](https://github.com/DavidDaza2906/3d_cube_rust) | Rust for fundamentals: a digit recogniser written without ML frameworks and a software-rendered 3D cube. |
| [homelab](https://github.com/DavidDaza2906/homelab) | The compose files behind my home server — the machine I actually work on. |

## Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
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

## Contact

- Email: [daviddaza2906@gmail.com](mailto:daviddaza2906@gmail.com)
- LinkedIn: [in/daviddaza2906](https://www.linkedin.com/in/daviddaza2906/)
