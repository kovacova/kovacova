# Tina Kovacova

**Generative AI / LLM Engineer · Data Scientist** · Canada (open to remote)

I build LLM products that hold up in production: retrieval, agents, evaluation, guardrails, and the infrastructure and monitoring around them. Six years in data science and ML, ten in total across EdTech, marketing, music and gaming. I also teach LLMOps and MLOps to working professionals and mentor data scientists.

[LinkedIn](https://www.linkedin.com/in/kovacova/) · [kovacova.ca](https://kovacova.ca) · [Kaggle](https://www.kaggle.com/tinakovacova) · tina@kovacova.ca

---

## What I'm building

### [MealThyme](https://mealthyme.ai) · AI nutrition coaching · [live app](https://mealthyme.ai) (one-click demo mode)

Snap a meal and get a vision-model nutrition breakdown with coaching, or ask **Swan**, a streaming chat agent with memory and RAG over Health Canada and USDA guidance.

- **Multi-provider AI** behind one interface: Gemini for vision, Claude for premium analysis and chat, OpenAI embeddings, hot-swappable without code changes
- **RAG** on PostgreSQL + pgvector; SSE streaming with cancel; per-message feedback
- **Production ops:** per-tier rate limits and daily AI cost caps, admin dashboards for SRE metrics, costs, security logs and model evals, Sentry and PostHog
- **Stack:** FastAPI, SQLAlchemy, React 19, TypeScript, Tailwind · AWS EC2 (Graviton), RDS, S3, SES, Amplify · Docker Compose, Traefik blue-green deploys, GitHub Actions
- Self-hosted auth with OAuth and 2FA

### The Hollow · local-first notes app for macOS · *private repo, demo on request*

A native Swift app over a folder of Markdown files, with search, an "Up next" stream that ranks to-dos, mail, calendar, GitHub issues and failed workflow runs, and a chat that answers from your notes.

- **MCP server** so AI agents can read notes, with tiered permissions set by launch flag: read-only, capture-only, or revision-fenced edits; nothing can delete
- **Privacy by design:** Apple Intelligence and Ollama stay on-device; before any remote LLM call the app shows exactly what would be sent and waits for confirmation; retrieved notes are fenced as untrusted data
- **Stack:** Swift, Python, JavaScript, n8n webhooks, ntfy push

### [Self-stopping Minecraft server on AWS](https://github.com/kovacova/minecraft-server)

Terraform for a game server that shuts itself down after 15 idle minutes, backs up on every stop, has no SSH port, and starts from a Discord slash command that verifies Ed25519 signatures. Terraform, EC2 Graviton, Lambda, API Gateway, S3, SSM.

## Teaching

I lead LLMOps and MLOps sessions for Great Learning programs, including *Generative AI for Business with Microsoft Azure*. Selected demos:

- [**Visual search RAG with GenAIOps**](https://github.com/kovacova/visual-search-rag-genaiops): GPT-4o image captioning + Azure AI Search, with prompt-injection and PII guardrails, MLflow tracing and evals
- [**Azure ML churn pipeline with CI/CD**](https://github.com/kovacova/azureml-churn-cicd): training to managed endpoint, driven by GitHub Actions
- [**LLMOps: monitoring, CI/CD and governance**](https://github.com/kovacova/gen-ai-msft-w14-monitoring-cicd-gov): taking a RAG app from prototype to a governed service

## Highlights

- Contractor for **Google** (YouTube and Search ad safety, Czechia), **Apple** (Apple Music Canada recommender evaluation and editorial review) and **Meta** (PII and privacy).
- Helped ship a production **automotive voice assistant** (NLP/NLU) for the Slovak market.
- Founded and ran an education business for 5+ years.
- Advise YC-backed founders and CTOs on data strategy, modeling and infrastructure.
- Data mentor at **Kaggle**, **Pathrise** (YC W18) and **BloomTech** (YC S17).

## Skills

**LLMs & GenAI:** RAG, agents and MCP, prompt engineering, evaluation, guardrails, fine-tuning (LoRA, QLoRA, PEFT), vector databases (pgvector, Azure AI Search, Chroma) · OpenAI, Anthropic and Google APIs, LangChain, Hugging Face
**ML:** PyTorch, TensorFlow/Keras, scikit-learn, NLP/NLU, recommender systems, computer vision
**Engineering:** Python, FastAPI, SQL, TypeScript, React, Swift
**MLOps / Infra:** MLflow, Azure ML, GitHub Actions, Docker, Terraform, Traefik · AWS, Azure, GCP (Vertex AI, BigQuery)
**Data:** PySpark, dbt, PostgreSQL · Tableau, Looker, Metabase, Plotly
