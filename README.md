<p align="center">
  <img src="./assets/profile-banner.png" alt="Mahaboob Ashraf — Software Engineering, Applied AI, Reliable Systems" width="100%" />
</p>

<p align="center">
  <a href="mailto:mahaboobashraf12@gmail.com">Email</a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/mohammad-mahaboob-ashraf-a0b17b321/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://x.com/Mahaboob_Ashraf">X</a>
</p>

<p align="center">
  <strong>Building AI systems, backend infrastructure, and reliable software for real-world problems.</strong>
</p>

---

## About

I'm a Computer Science undergraduate focused on **Software Engineering, Applied AI, backend systems, and reliability**.

I’m especially interested in projects where the hard part is not just getting something to work once, but making it **correct, inspectable, failure-aware, and useful to real users**.

My work spans:

- AI systems with deterministic safety boundaries
- backend and reliability engineering
- developer tooling
- applied machine learning
- research
- data structures and algorithms

---

## Featured Projects

| Project | What it is | Stack | Highlight |
|---|---|---|---|
| **[Amana](https://github.com/Mahaboob-Ashraf/Agentic-Commerce-Gateway)** | Agentic commerce gateway that turns existing merchant systems into AI-transactable businesses and enables a safe AI buyer | Java · Spring Boot · Next.js · PostgreSQL · pgvector · Gemini · Razorpay | **250/250 deterministic safety cases passed** · fail-closed transaction authority |
| **[RepoPilot](https://github.com/Mahaboob-Ashraf/Repo-Pilot)** | Local-first coding-agent platform built to understand repositories before changing them | Python · FastAPI · tree-sitter · BM25 · Ollama | **Structure-aware repository retrieval** · local inference · human-in-the-loop architecture |
| **[HookRelay](https://github.com/Mahaboob-Ashraf/HookRelay)** | Reliable webhook delivery system built around explicit failure handling and recovery | TypeScript · Fastify · PostgreSQL · Redis · BullMQ | **Idempotency · retries · HMAC signing · DLQ · replay · at-least-once delivery** |
| **[VoteReady](https://github.com/Mahaboob-Ashraf/VoteReady)** | Citizen-first household navigator for India's SIR voter process | Next.js · TypeScript · Gemini · Supabase · PostgreSQL | **Multilingual record extraction · deterministic matching · human confirmation** |
| **[PS-Prep](https://github.com/Mahaboob-Ashraf/ps-prep)** | LeetCode-style programming-prep platform built for my college's Project School selection test | React · Vite · Supabase · Gemini · Monaco Editor | **~100+ student users** · improved from real user feedback |
| **[Skin Lesion Classification](https://github.com/Mahaboob-Ashraf/skin-lesion-classification)** | Error-driven HAM10000 skin-lesion classification study | PyTorch · TensorFlow · ResNet50 · Grad-CAM | **57.29% → 84.76% test accuracy** with class-imbalance-aware training |

---

## Project Notes

### Amana

**AI handles meaning. Deterministic software controls truth, authority, and money.**

Amana separates AI reasoning from financial authority.

The AI can understand intent, inspect merchant APIs, diagnose failures, and suggest mappings, while deterministic software owns the transaction path:

`proposal → authorization → execution → payment truth`

The system includes Razorpay Test Mode payments, webhook verification, reconciliation, bounded execution, fail-closed checks, and a deterministic adversarial safety proof.

---

### RepoPilot

RepoPilot is being built around the idea that a coding agent should **understand repository structure before attempting a patch**.

Currently implemented:

- repository discovery and ingestion
- Python structure-aware parsing
- semantic code chunks with source provenance
- lexical code retrieval
- local Ollama provider boundary
- automated parser, retrieval, pipeline, and API tests

Target direction:

```text
Repository + Issue
        ↓
Understand Structure
        ↓
Retrieve Evidence
        ↓
Plan
        ↓
Human Approval
        ↓
Patch
        ↓
Test
        ↓
Critique
```

The goal is an **inspectable engineering agent**, not an unrestricted autonomous coding bot.

---

### PS-Prep

PS-Prep started from a problem my classmates and I were actually facing.

Preparation material for our Project School selection test was scattered across old resources, coding environments, solutions, and chat tools, so I built a single platform for practice.

I shared it across multiple college classes during exam season, where it was used by roughly **100+ students**.

One of the first user-reported problems was that programs using `input()` had no convenient way to receive values. I added a dedicated stdin workflow based directly on that feedback.

**Build → ship → get feedback → fix the real problem.**

---

## Research

I'm involved in applied research across two domains:

### Computer Vision

Research work through **IIIT-H / iHub-Data**, involving computer-vision experimentation and evaluation.

### AI in Drug Discovery

Research with **Drugparadigm** on bispecific-antibody manufacturability, involving large biological sequence datasets and constrained evaluation settings.

I'm particularly interested in ML problems involving:

`messy data` · `limited labels` · `domain constraints` · `evaluation uncertainty`

---

## Engineering Focus

<table>
<tr>
<td width="50%" valign="top">

### AI with boundaries

Models are useful for ambiguity, language, diagnosis, and planning.

Deterministic software should own irreversible authority and correctness-critical decisions.

</td>
<td width="50%" valign="top">

### Reliability before claims

Retries, idempotency, reconciliation, concurrency, and recovery belong in the system design from the beginning.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Evaluation over demos

I prefer measured behavior, failure analysis, tests, and reproducible evidence over a system that only worked once.

</td>
<td width="50%" valign="top">

### Real problems over feature lists

The projects I value most usually start with somebody genuinely needing the thing.

</td>
</tr>
</table>

---

## Core Stack

### Languages

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

### Backend & APIs

<p>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" alt="Fastify" />
</p>

### Databases & Data Systems

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/BullMQ-EA4335?style=flat-square" alt="BullMQ" />
</p>

### AI / Machine Learning

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square" alt="Ollama" />
  <img src="https://img.shields.io/badge/tree--sitter-6A5ACD?style=flat-square" alt="tree-sitter" />
</p>

### Frontend

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Monaco%20Editor-007ACC?style=flat-square" alt="Monaco Editor" />
</p>

### Infrastructure & Tools

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---
## Currently

- building deeper **backend, AI-systems, and reliability** projects
- working on applied **ML research**
- practicing **DSA and competitive programming**
- preparing for **Software Engineering / Applied AI internships**

---

## Connect

[Email](mailto:mahaboobashraf12@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/mohammad-mahaboob-ashraf-a0b17b321/) ·
[X](https://x.com/Mahaboob_Ashraf)

I'm particularly interested in opportunities involving **AI systems, backend infrastructure, reliability, developer tooling, and applied machine learning**.
