
<h1 align="center">bydev.ai – AI solutions, <em>by developers.</em></h1>

<p align="center">
  <strong>Plug-and-play AI modules that turn everyday business workflows into automated, data-driven experiences.</strong>
</p>

<p align="center">
  <a href="https://www.bydev.ai"><img src="https://img.shields.io/badge/website-bydev.ai-4B8BF5.svg?style=flat-square" alt="Website"></a>
  <a href="https://www.linkedin.com/company/bydev-ai"><img src="https://img.shields.io/badge/LinkedIn-follow-blue.svg?style=flat-square" alt="LinkedIn"></a>
  <a href="https://github.com/bydev-ai"><img src="https://img.shields.io/github/last-commit/bydev-ai/.github.svg?style=flat-square" alt="Last commit"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-green.svg?style=flat-square" alt="License: MIT"></a>
</p>

---

## 📚 Table of Contents
1. [About Us](#about-us)
2. [Projects](#projects)
3. [Tech Stack](#tech-stack)
4. [Quick Start](#quick-start)
5. [Contributing](#contributing)
6. [Community & Support](#community--support)
7. [License](#license)

---

## About Us
We’re a Kamloops,BC-based, small team of engineers on a mission to **democratize practical AI** for small- and mid-size businesses.  
Our modular approach lets companies add production-ready AI—voice, chat, analytics—without hiring an entire ML department.

---

## Projects
| Repo | Description | Status |
|------|-------------|--------|
| **[`caller-ai`](https://github.com/bydev-ai/caller-ai)** | AI-powered phone agent that answers, routes, and books appointments 24/7. | Alpha |
| **[`chatbot-kit`](https://github.com/bydev-ai/chatbot-kit)** | Plug-and-play web chat widget with vector DB knowledge-base search. | Beta |
| **[`booking-api`](https://github.com/bydev-ai/booking-api)** | REST & GraphQL API for calendar management and payment-integrated bookings. | Alpha |
| **[`data-pipelines`](https://github.com/bydev-ai/data-pipelines)** | Reusable pipeline templates (Airbyte → dbt → Supabase) for AI analytics. | Planning |

*Looking for something specific? Open an issue or send us an email.*

---

## Tech Stack
- **Languages:** TypeScript · Python (🔥 FastAPI) · SQL
- **Frontend:** Next.js · Tailwind · shadcn/ui
- **AI/ML:** OpenAI o3 · LangChain · Ollama · Supabase PGVector
- **Infra:** Docker · Fly.io · Railway · GitHub Actions

---

## Quick Start

Clone any repo and run the dev stack with **Docker Compose**:

```bash
git clone https://github.com/bydev-ai/caller-ai.git
cd caller-ai
cp .env.example .env        # add your keys
docker compose up --build
