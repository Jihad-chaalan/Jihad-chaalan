
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=Hey%2C+I'm+Jihad+Chaalan+%F0%9F%91%8B;Full-Stack+%26+AI+Engineer+In+Progress..." alt="Typing SVG" />

<br/>

**Full-stack developer** transitioning into AI engineering — building deployable systems with LLMs, RAG pipelines, and autonomous agents on top of solid Laravel & FastAPI backends.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jihadchaalan-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/jihadchaalan)
[![Gmail](https://img.shields.io/badge/Email-chaalan2004%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:chaalan2004@gmail.com)

</div>

---

## 🧠 What I'm Building

- **RAG systems** — document retrieval pipelines with ChromaDB + LangChain
- **AI Agents** — multi-step reasoning workflows using LangGraph
- **Production backends** — FastAPI & Laravel APIs with clean auth & DB design
- **React frontends** — connecting it all into usable interfaces

---

## 🛠️ Tech Stack

### AI & LLMs
<p>
  <img src="https://cdn.simpleicons.org/langchain/00A67E" width="40" height="40" title="LangChain" />
  &nbsp;
  <img src="https://avatars.githubusercontent.com/u/139895814?s=200&v=4" width="40" height="40" title="ChromaDB" />
  &nbsp;
  <img src="https://img.icons8.com/fluency/48/workflow.png" width="40" height="40" title="LangGraph" />
  &nbsp;
  <img src="https://registry.npmmirror.com/@lobehub/icons-static-png/latest/files/dark/langsmith-color.png" width="40" height="40" title="LangSmith" />
</p>

`LangChain` `LangGraph` `ChromaDB` `LangSmith`

### Backend
<p>
  <img src="https://skillicons.dev/icons?i=fastapi,laravel,python,php" />
</p>

`FastAPI` `Laravel` `Python` `PHP`

### Frontend
<p>
  <img src="https://skillicons.dev/icons?i=react,javascript" />
</p>

`React.js` `JavaScript`

### Database & DevOps
<p>
  <img src="https://skillicons.dev/icons?i=mysql,docker,git,github" />
</p>

`MySQL` `Docker` `Git` `GitHub`

---

## 📌 Featured Projects

### 📰 AI Daily News

A fully automated AI news platform that researches, ranks, summarises, illustrates, and publishes the **5 most important AI stories every day** at 8 PM. Built with **LangGraph**, **Next.js**, and **Supabase**.

- **Orchestration** – LangGraph agentic workflow (research → dedupe → rank → summary → image → validate → publish).
- **Research** – Fetches from multiple news APIs (APITube, NewsData.io) with AI‑related keywords.
- **Deduplication** – Semantic clustering using sentence‑transformers + cosine similarity.
- **Ranking** – LLM‑based scoring (Groq) on impact, novelty, and audience interest.
- **Summarisation** – AI‑generated summary, "why it matters", and 3 key points per story.
- **Image Generation** – Cloudflare Workers AI (with Pollinations.ai fallback) + Supabase Storage.
- **Publishing** – Website (Next.js) + Telegram (separate messages with clickable sources).
- **7‑Day Retention** – Automatic cleanup of old briefings and images.
- **Admin Panel** – Full CRUD with image upload, protected by `iron‑session`.

🌐 **Website:** [ai-daily-news.vercel.app](https://ai-daily-news.vercel.app)  
📱 **Telegram:** [Join our group](https://t.me/+R6JQYLw8FbNlYmE0)  
🔗 **Code:** [github.com/Jihad-chaalan/ai-news](https://github.com/Jihad-chaalan/ai-news)

---

### 🏢 Enterprise RAG

Secure Multi-Tenant Enterprise RAG — a production-style AI knowledge assistant that answers questions over internal enterprise documents using hybrid retrieval, cross-encoder reranking, and an AI security layer. Built with FastAPI, React (TypeScript + Vite), Qdrant Cloud, and Groq (Llama 3.3/3.1).

- **Retrieval:** Hybrid search combining Vector Search + BM25, merged with Reciprocal Rank Fusion (RRF) and refined with Cross-Encoder reranking for precision.
- **Multi-Tenancy:** Department and role-based document isolation enforced through Qdrant payload filtering and tenant-aware BM25 indexes.
- **Security:** LLM-based prompt injection, jailbreak, and cross-tenant access detection with full security event logging and an admin dashboard.
- **Observability:** Per-request latency breakdown, token usage tracking, and cost estimation across retrieval, reranking, and generation stages.
- **DevOps:** Dockerized backend/frontend, GitHub Actions CI with golden dataset validation, deployed on Heroku.

👉 **Live Demo:** [enterprise-rag-574f275953cb.herokuapp.com](https://enterprise-rag-574f275953cb.herokuapp.com/)  
🔗 **Code:** [github.com/Jihad-chaalan/secure-multitenant-rag](https://github.com/Jihad-chaalan/secure-multitenant-rag)

---

### 📄 Resume ATS Predictor

An end-to-end MLOps project that simulates how an Applicant Tracking System (ATS) screens resumes. Trained from scratch on 6,000 resumes using XGBoost and deployed with a fully automated CI/CD pipeline to Hugging Face Spaces.

- **Model:** XGBoost (trained from scratch) with TF-IDF text features + engineered semantic similarity penalty.
- **MLOps:** GitHub Actions CI/CD pipeline with automated performance testing (accuracy & F1 gatekeepers).
- **Explainability:** Gradio UI with keyword gap analysis and semantic similarity visualization.
- **Versioning:** Git for code + model artifacts; MLflow for experiment tracking (parameters, metrics).

🌐 **Live Demo:** [huggingface.co/spaces/jiha-d/resume-ats-predictor](https://huggingface.co/spaces/jiha-d/resume-ats-predictor)  
🔗 **Code:** [github.com/Jihad-chaalan/resume-ats-predictor](https://github.com/Jihad-chaalan/resume-ats-predictor)

---

### 🎓 Internship Management System

Multi-role Laravel app (Admins, Companies, Job Seekers, Universities) with Sanctum API authentication and React frontend.

🔗 **Code:** [github.com/Jihad-chaalan/internship-management-system](https://github.com/Jihad-chaalan/internship-management-system)
---

## 📈 GitHub Stats

<div align="center">
  
<img src="https://streak-stats.demolab.com?user=Jihad-chaalan&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak" />
  
 <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Jihad-chaalan&layout=compact&theme=tokyonight" />
 
</div>
---

## 🌐 Connect

<p align="center">
  <a href="https://linkedin.com/in/jihadchaalan" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" />
  </a>
  &nbsp;
  <a href="mailto:chaalan2004@gmail.com">
    <img src="https://img.icons8.com/fluency/48/gmail-new.png" width="45" height="45" />
  </a>
</p>

---

<div align="center">
  <sub>Always a Learner</sub>
</div>
