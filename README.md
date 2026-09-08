# Mahaboob Ashraf

### Software Engineer · Applied AI · Backend & Reliable Systems

I'm a Computer Science undergraduate building software at the intersection of **AI systems, backend engineering, reliability, and applied machine learning**.

I like projects where the interesting part isn't just getting a demo to work — it's deciding **what the AI is allowed to control, what deterministic software must guarantee, what happens when dependencies fail, and how the system can prove that it behaved correctly.**

Currently focused on:
- building production-minded AI and backend systems;
- applied AI / ML research;
- distributed systems and reliability;
- data structures, algorithms, and competitive programming.

---

## Selected Work

### [Amana — Agentic Commerce Gateway](https://github.com/Mahaboob-Ashraf/Agentic-Commerce-Gateway)

**Turning existing merchants into businesses that AI agents can transact with safely.**

Built a merchant-agentization pipeline and Safe AI Buyer where AI handles unstructured intent and diagnosis, while deterministic software controls transaction authority and payment truth.

`Java` `Spring Boot` `Next.js` `PostgreSQL` `pgvector` `Gemini` `Razorpay`

Highlights:
- agentizes existing merchant APIs through inspect → map → test → diagnose → repair;
- immutable proposal → authorization → execution payment authority;
- Razorpay Test Mode with webhook verification and reconciliation;
- deterministic fail-closed safety checks;
- 250-case adversarial safety proof.

**Principle:** *AI handles meaning. Deterministic software controls truth, authority, and money.*

---

### [RepoPilot](https://github.com/Mahaboob-Ashraf/Repo-Pilot)

**A local-first coding-agent platform built to understand repositories before changing them.**

RepoPilot is being developed around structure-aware repository indexing, retrieval, local inference, bounded execution, and human approval.

`Python` `FastAPI` `tree-sitter` `BM25` `Ollama`

Currently implemented:
- repository discovery and ingestion;
- Python structure-aware parsing and semantic code chunks;
- source provenance and lexical code retrieval;
- Ollama provider boundary;
- automated retrieval, parser, pipeline, and API tests.

The longer-term goal is an inspectable:

`retrieve → plan → approve → patch → test → critique`

workflow rather than an unrestricted autonomous coding bot.

---

### [HookRelay](https://github.com/Mahaboob-Ashraf/HookRelay)

**Reliable webhook delivery when “just POST it” is no longer enough.**

A backend reliability system built around explicit failure handling and at-least-once delivery semantics.

`TypeScript` `Fastify` `PostgreSQL` `Redis` `BullMQ`

Includes:
- durable delivery state;
- HMAC-SHA256 signed requests;
- bounded retries and failure classification;
- idempotent ingestion;
- persisted attempt history;
- dead-letter handling;
- manual replay;
- PostgreSQL as source of truth.

---

### [VoteReady](https://github.com/Mahaboob-Ashraf/VoteReady)

**A citizen-first household navigator for India's SIR voter process.**

Built around a real public-service usability problem: different household members can have different voter-status situations, legacy-record issues, notices, and required next actions.

`Next.js` `TypeScript` `Gemini` `Supabase` `PostgreSQL`

Includes:
- household-level guidance;
- multilingual legacy-electoral-record extraction;
- deterministic candidate matching;
- human confirmation before consequential decisions;
- hearing-rescue flows;
- synthetic demo identities and privacy-safe test data.

[Live demo](https://voteready-alpha.vercel.app)

---

### [PS-Prep](https://github.com/Mahaboob-Ashraf/ps-prep)

**A programming-prep platform built for students at my college — and improved after they actually used it.**

I built PS-Prep when preparation material for our Project School selection test was scattered across old class resources, coding environments, solutions, and chat tools.

I shared it across multiple classes during exam season, where it was used by roughly **100+ students**.

`React` `Vite` `Supabase` `Gemini` `Monaco Editor`

The platform combines:
- curated programming questions;
- browser-based Python execution;
- solutions and explanations;
- contextual AI tutoring;
- topic-based preparation;
- a LeetCode-style coding playground.

One of the first user-reported problems was the inability to provide input to programs using `input()`. I added a dedicated stdin workflow based directly on that feedback.

**Build → ship → get feedback → fix the real problem.**

---

### [Skin Lesion Classification](https://github.com/Mahaboob-Ashraf/skin-lesion-classification)

**Error-driven deep-learning experimentation on the HAM10000 dataset.**

Started with a custom TensorFlow CNN, analyzed severe minority-class failures, then redesigned the training pipeline around weighted ResNet50 transfer learning.

`PyTorch` `TensorFlow` `ResNet50` `Grad-CAM`

Results on the project test split:
- custom CNN: **57.29% accuracy**
- weighted ResNet50: **84.76% accuracy**
- melanoma recall: **71%**
- basal cell carcinoma recall: **84%**

The project focuses on **class imbalance, per-class error analysis, transfer learning, and interpretability** rather than treating aggregate accuracy as the whole story.

---

## Research

Alongside engineering projects, I'm involved in applied research spanning:

- **Computer Vision** — research work through IIIT-H / iHub-Data;
- **Computational Biology / ML** — bispecific-antibody manufacturability research with Drugparadigm.

I’m especially interested in work where ML systems have to survive contact with **messy data, limited labels, evaluation constraints, and real domain assumptions**.

---

## How I Like to Build

```text
Understand the failure modes
        ↓
Build the smallest correct system
        ↓
Make authority boundaries explicit
        ↓
Test the uncomfortable cases
        ↓
Measure what actually happened
        ↓
Iterate
```

A few themes show up repeatedly in my work:

**AI with boundaries**  
Models handle ambiguity and reasoning; deterministic code owns irreversible decisions.

**Reliability before claims**  
Retries, idempotency, reconciliation, failure states, and recovery paths are part of the design — not afterthoughts.

**Evaluation over demos**  
I prefer measured behavior, failure analysis, and reproducible proof over “it worked once.”

**Build for real problems**  
The best projects usually start with somebody actually needing the thing.

---

## Core Stack

**Languages**

`Java` · `C++` · `Python` · `TypeScript` · `JavaScript`

**Backend & Systems**

`Spring Boot` · `FastAPI` · `Fastify` · `PostgreSQL` · `Redis` · `BullMQ` · `Docker`

**AI / ML**

`PyTorch` · `TensorFlow` · `Gemini` · `Ollama` · `tree-sitter` · `pgvector`

**Frontend**

`React` · `Next.js` · `Vite`

---

## Currently

- building deeper backend, AI-systems, and reliability projects;
- working on research;
- practicing DSA and competitive programming;
- contributing to open source;
- looking toward **Software Engineering / Applied AI internships**.

---

## Connect

[LinkedIn](https://www.linkedin.com/in/mohammad-mahaboob-ashraf-a0b17b321/) ·
[GitHub](https://github.com/Mahaboob-Ashraf)

> I’m particularly interested in engineering problems involving **AI systems, backend infrastructure, reliability, developer tooling, and applied ML**.
