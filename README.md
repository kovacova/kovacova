# Hi, I'm Tina

**Generative AI / LLM Engineer · Data Scientist · MBA** 

What I care about: building AI that's honest about what it knows, respects your data, and still works when nobody is watching it. 

**Highlights:**
- **NLP & NLU Engineering:** Built the first fully localized production voice assistant ever released in Slovakia at [CerenceAI](https://www.cerence.com/).
- **Data Safety & Privacy:** Improved Ad safety, privacy and moderation for Google Search and YouTube in Czechia, plus PII and compliance work at Meta. I also tuned the tunes at [Apple Music Canada](https://music.apple.com/ca/).
- **Product Data Science:** [Influence Mobile's](https://www.influencemobile.com/rewarded-play) first data scientist, leading DS work on a rewards app with 30M+ installs and $50M+ paid out to players.
- **Mentorship:** Helping people grow and strengthen their data skillset at [Kaggle](https://www.kaggle.com/), Pathrise & [Canada Learning Code](https://www.canadalearningcode.ca/). 

I also teach Gen AI and LLMOps in executive programs at [Great Learning](https://www.mygreatlearning.com/), where we intentionally break a lot of systems, and then make them much stronger. It's my favourite vibe job :)  

[LinkedIn](https://www.linkedin.com/in/kovacova/) · [kovacova.ca](https://kovacova.ca) · [Kaggle](https://www.kaggle.com/tinakovacova) · tina@kovacova.ca

---

## What I'm building

### [The Hollow](https://hollow.kovacova.ca/) · Privacy-first macOS personal AI and data hub

The Hollow has three layers - your notes in plain markdown, a series of third-party APIs connecting all your external data sources, and an LLM + MCP layer powered by on-device or remote ZDR models. 

- **MCP server** AI agents can read notes, with tiered permissions set by launch flag: read-only, capture-only, or revision-fenced edits; nothing can delete
- **Privacy by design:** Apple Intelligence and Ollama stay on-device; before any remote LLM call the app shows exactly what would be sent and waits for confirmation; retrieved notes are fenced as untrusted data
- **Stack:** Swift, Python, JavaScript, LLMs (OpenRouter, Ollama, Apple Intelligence)

### [MealThyme](https://mealthyme.ai) · AI nutrition coaching 

Snap a meal and get a vision-model nutrition breakdown with coaching, or ask **Swan**, a streaming chat agent with memory and RAG over Health Canada and USDA guidance.

- **Multi-provider AI** behind one interface: Gemini for vision, Claude for premium analysis and chat, OpenAI embeddings, hot-swappable without code changes
- **RAG** on PostgreSQL + pgvector; SSE streaming with cancel; per-message feedback
- **Production ops:** per-tier rate limits and daily AI cost caps, admin dashboards for SRE metrics, costs, security logs and model evals, Sentry and PostHog
- **Stack:** FastAPI, SQLAlchemy, React 19, TypeScript, Tailwind · AWS EC2 (Graviton), RDS, S3, SES, Amplify · Docker Compose, Traefik blue-green deploys, GitHub Actions
- Self-hosted auth with OAuth and 2FA

### [Self-stopping Minecraft server on AWS](https://github.com/kovacova/minecraft-server)

Terraform for a game server that shuts itself down after 15 idle minutes, backs up on every stop, has no SSH port, and starts from a Discord slash command that verifies Ed25519 signatures. Terraform, EC2 Graviton, Lambda, API Gateway, S3, SSM.

## Teaching

Looking for course materials? You can find all repos here: **[kovacova-teaching](https://github.com/kovacova-teaching)**
