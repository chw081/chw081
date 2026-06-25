# Christine Wu

![](https://komarev.com/ghpvc/?username=chw081)
![GitHub stars](https://img.shields.io/github/stars/chw081?style=social)
![GitHub followers](https://img.shields.io/github/followers/chw081?style=social)

Software Engineer focused on AI applications, developer tools, and full-stack systems. Recently shipped production features at startups and currently building a Personal Email Agent to explore AI-powered personal productivity systems.

San Jose, CA · B.S. Mathematics & Computer Science, UC San Diego

---

## What I'm Building

**[Personal Email Agent](https://github.com/chw081/Personal-Email-Agent)** — A full-stack system for managing and understanding large inboxes (22,000+ emails). Built to turn email overload into structured, actionable context.

**Architecture:** Next.js frontend → FastAPI backend → service layer (Gmail sync, classification, analysis) → SQLAlchemy/SQLite persistence.

**Current stack:** Python, FastAPI, Pydantic, SQLAlchemy, Next.js, TypeScript, Tailwind CSS, Google Gmail API, OpenAI SDK.

**Engineering decisions:**
- Layered architecture with stable API contracts so mock data, rule-based classifiers, and future LLM analysis can swap without frontend rewrites
- Gmail OAuth + read-only sync service separated from analysis logic
- Typed schemas between frontend and backend for email, analysis, and Gmail payloads

**Direction:** Evolve from inbox analysis into a personal operating system — priority detection, summarization, reply drafts, follow-up tracking, and agent workflows with humans in the loop.

---

## Experience Highlights

### HerPower AI · Software Developer
*Sep 2025 – Dec 2025 · Silicon Valley, CA*

- Shipped production features on the startup web platform in a fast-paced environment, working directly with the tech lead on new functionality and data persistence
- Owned end-to-end development of **HerCommunity** — forum discussions, events, and stories with full user and admin workflows (CRUD, auth, role-based access, data integrity)
- Debugged TypeScript backend services and REST APIs against PostgreSQL; improved reliability through manual regression testing across feature iterations

### UC San Diego Health · AI Research Assistant
*Sep 2024 – Jun 2025 · San Diego, CA*

- Optimized deep learning models (EfficientNet, Fast-SCNN, MobileUNet, UNet) for real-time quantitative ultrasound image segmentation using PyTorch, TensorFlow, and Keras
- Built preprocessing pipelines for multi-format ultrasound datasets — normalization, augmentation, resizing, and sampling — to improve training efficiency and model performance
- Integrated PySide6 GUI, Blender-based 3D probe visualization, and Clarius Cast API for live ultrasound capture and real-time analysis workflows

### Convoloo · Software Development Engineer
*Jan 2025 – Mar 2025 · San Francisco, CA*

- Built a full-stack AI storytelling web app with Streamlit, LangChain, and OpenAI GPT — users generate multi-page personalized children's books with dynamic characters and adaptive illustrations
- Designed prompt pipelines with RunnableSequences and DALL·E 3; optimized backend architecture and API performance to improve text-to-image coherence and cut response latency by 28%
- Delivered the product from early MVP to deployment, managing technical documentation and phased releases for a production-ready LLM application

---

## Selected Projects

### [Personal Email Agent](https://github.com/chw081/Personal-Email-Agent)

**Problem:** Large inboxes are hard to triage — important messages get buried and context is scattered across threads.

**Stack:** FastAPI, SQLAlchemy, Next.js, TypeScript, Gmail API, OpenAI SDK

**Decisions:** Service-layer separation for Gmail ingestion vs. classification vs. analysis; Pydantic schemas as the contract boundary; modular routers so AI analysis can replace rule-based classifiers incrementally.

---

### AI Storytelling Application *(Convoloo)*

**Problem:** Parents and educators need personalized, illustrated children's books without manual layout or illustration work.

**Stack:** Streamlit, LangChain, OpenAI GPT, DALL·E 3, RunnableSequences, Requests, PIL

**Decisions:** Chained LLM + image generation pipeline with prompt engineering for character consistency across pages; backend optimizations that reduced end-to-end latency by 28% while maintaining illustration coherence.

---

### UCSD Course AI Assistant

**Problem:** Course-specific questions are poorly served by generic chatbots that lack access to lecture materials, assignments, and syllabus context.

**Stack:** Python, LLM APIs, RAG over course documents, web UI

**Decisions:** Retrieval-grounded responses scoped to instructor-provided materials; structured prompt design to keep answers tied to course content rather than open-ended generation.

---

### AI Image Generation App

**Problem:** Text-to-image workflows need controlled prompts, batch generation, and post-processing — not just a single API call.

**Stack:** Python, OpenAI DALL·E, PIL, REST APIs

**Decisions:** Prompt template system for consistent visual style; image post-processing pipeline for sizing and format normalization; async request handling to manage API rate limits and latency.

---

## Technical Areas

**Languages**
Python · TypeScript · JavaScript · Java · C++ · SQL · Bash

**Backend**
FastAPI · Node.js · REST APIs · PostgreSQL · SQLAlchemy · SQLite

**Frontend**
React · Next.js · Tailwind CSS · Streamlit

**AI / LLM**
PyTorch · TensorFlow · Keras · LangChain · OpenAI API · DALL·E · RAG pipelines

**Data**
NumPy · scikit-learn · data preprocessing · feature engineering · model evaluation

**Cloud & DevOps**
AWS · Docker · Vercel · GitHub Actions · CI/CD · Linux

---

## GitHub Stats

[![GitHub Streak](https://streak-stats.demolab.com/?user=chw081&theme=default)](https://git.io/streak-stats)

[![Christine's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=chw081&theme=minimal&hide_border=true)](https://github.com/chw081)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=chw081&layout=compact&hide_border=true)

---

## Contact

- **LinkedIn:** [linkedin.com/in/christine-wu-2bab27243](https://linkedin.com/in/christine-wu-2bab27243)
- **Email:** [cwu20210923@gmail.com](mailto:cwu20210923@gmail.com)
