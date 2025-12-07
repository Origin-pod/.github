<div align="center">

# 🌀 Origin

### Systems for learning, design, and automation — built in public.

_Design systems, AI-powered learning pipelines, knowledge gardens, and systems experiments — all stitched into one ecosystem._

<br/>

</div>

---

## 🌌 What is Origin?

Origin is not just a set of repositories — it's the **unified expression of everything I learn, build, think about, and try to become**.

It is where I practice being:

- a **designer** exploring aesthetics (minimal → rough, 2D → 3D),  
- a **builder** crafting AI-native workflows,  
- a **systems thinker** experimenting with infra and Rust,  
- a **writer** shaping thoughts into clarity,  
- a **filmmaker & creative** exploring storytelling,  
- a **student** who never stops learning,  
- and ultimately, a **creator** trying to find her most original voice.

### 🧭 The Philosophy

Origin is:

- **where learning starts** — raw curiosity → structured understanding.  
- **where creative energy lives** — from design systems to short films.  
- **where ideas converge** — engineering, aesthetics, writing, systems, research.  
- **where originality is practiced** — not repeating what exists, but discovering my own thinking.  
- **where personal knowledge compounds** — through automation, reflection, and iteration.

It’s a living ecosystem that grows with me, evolving as I evolve.  
Origin is everything I am — expressed through software.

---

## 🧱 Repositories

### 🎨 `OriginArt` — Design Systems & UI Experiments

> _“A melting pot of design systems, 2D–3D experiments, and components with configurable themes.”_

- **What it is**
  - A **monorepo** of design systems and UI primitives built with **React + TypeScript**.
  - Multiple aesthetics: **Minimal** vs **Rough / hand-drawn**, bound by a shared **token + theme engine**.
  - Component library split into:
    - `@origin-art/ui-primitive` – low-level, theme-aware primitives.
    - `@origin-art/ui-core` – higher-level components + theme controls.
  - Storybook-driven, with a **playground app** for exploring themes live.

- **Highlights**
  - Clean architecture: **tokens → theme-engine → primitives → core → apps**.
  - Typed, token-driven styling using **CSS custom properties**.
  - A sandbox for experimenting with multiple design languages under one system.

---

### 🧠 `OriginSublime` — AI-Powered Learning Pipeline

> _“A fully automated, AI-powered content curation and action generation system.”_

Runs daily at **6 AM UTC** and performs an end-to-end workflow:

1. **Scraper**  
   - Pulls 50–100 articles from:
     - Hacker News  
     - Reddit (e.g., `/r/rust`, `/r/cpp`)  
     - GitHub Trending  
     - RSS feeds  
   - Deduplicates and organizes content.

2. **AI Curator (Claude 3.5 Sonnet)**  
   - Scores relevance (0–100) based on interest profiles.  
   - Summarizes in a “builder friend” tone.  
   - Tags, clusters, and extracts actionable elements.

3. **Action Generator**  
   Converts curated content into:
   - **Code exercises** (starter code, TODOs, tests).  
   - **Project templates** (scaffolding + guidance).  
   - **AI challenges** (“100 Days of Building with AI”).  
   - **Reflection prompts** for self-help/philosophy topics.

4. **API & Scheduler**
   - Fastify REST API: `/api/articles`, `/api/exercises`, `/api/challenges/today`.  
   - Cron-based daily job orchestration.

5. **Integrations**
   - Notion sync for knowledge dashboards.  
   - GitHub automation for challenge repos and activity logs.

**Stack:** Node.js, TypeScript, Fastify, node-cron, Claude 3.5 Sonnet.

---

### 📚 `OriginByte` — Learning Dump & Knowledge Garden

> _“Learning Dump — but with structure.”_

- A **Docusaurus-powered knowledge base**.  
- Contains:
  - Blogs  
  - Notes  
  - Documentation  
  - Experiments  
  - Build logs  
- Serves as the **human-facing interface** for Origin — the place for reflection and knowledge revisiting.

#### Bonus: X / Twitter Bookmark Scraper

- Playwright-based automation:
  - Logs into X  
  - Scrolls  
  - Exports bookmarks to JSON with:
    - author, handle  
    - timestamp  
    - text, images, videos  
- Useful for:
  - Learning queues  
  - Reading lists  
  - Feeding into OriginSublime workflows  

---

### 🕸️ `OriginSystems` — Systems & Rust Experiments

> _“Everything systems.”_

- A compact Rust playground for:
  - Networking  
  - Concurrency  
  - Streaming  
  - Systems-level prototypes  
- Includes examples like an **Iggy-based streaming demo**.  
- Serves as the low-level foundation for future Origin infrastructure.

---

## 🧩 How It All Fits Together

Think of Origin as a personal operating system:

