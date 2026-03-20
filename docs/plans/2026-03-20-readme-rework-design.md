# README Rework Design — 2026-03-20

## Goal

Replace the current GitHub profile README with a recruiter-optimized version targeting Junior AI/Automation Engineer and Data Science roles.

## Approach

Full replacement (Option A from brainstorming). Clean break — no incremental patching.

## Structure

### 1. Header (`<div align="center">`)
- Name: David Papp
- Subtitle: "AI Engineering Student · VU Amsterdam"
- 2-line value prop mentioning LLM tools built and consulting achievement (~40% API cost reduction)
- Links: Portfolio (davidpapp.dev) · LinkedIn · Email (contact@davidpapp.dev)

### 2. About Section
Five bullet points:
- 2nd-year BSc AI at VU Amsterdam
- Consulting work: LLM backend restructure + prompt injection hardening
- Team leadership in hackathons/rapid-build teams
- Location (Rotterdam, NL) + job intent
- Python primary, TypeScript working proficiency

### 3. Projects Table
| Project | Description | Stack |
|---------|-------------|-------|
| MCP Sentinel | Agent observability proxy | TypeScript · Supabase · Upstash Redis |
| Training Pipeline | AST-aware codebase→LoRA fine-tuning | Python · HuggingFace · LoRA/PEFT |
| RAG + 3D Chat | Document Q&A with pgvector + Three.js | Next.js · OpenAI API · pgvector |

Links: `https://davidpapp.dev/mcp`, `/training`, `/chat` (domain being configured)

### 4. Tech Stack
- **Languages:** Python, TypeScript, JavaScript (skillicons)
- **AI/ML:** OpenAI, HuggingFace, LangChain, CrewAI (shields.io badges)
- **Backend & Data:** Django, FastAPI, Postgres, Redis, Docker (skillicons) + AWS Lambda, DynamoDB (shields.io) — **FastAPI kept per user preference**
- **Frontend & Infra:** React, Next.js, Tailwind, Vercel, Supabase (skillicons) + Cloudflare, Hetzner (shields.io) — **Hetzner kept per user preference**
- Badge height: 28 (reduced from 48)

### 5. GitHub Stats
Two cards side-by-side at height=150, tokyonight theme, purple color scheme. No streak card, no snake animation, no profile view counter.

## What's Removed
- Profile view counter badge
- Typing SVG animation + "Building the future, one model at a time" slogan
- C# and .NET badges
- Streak stats card
- Snake contribution graph section
- Stale portfolio URL (portfolio-platform-mocha.vercel.app)

## What's Added
- VU Amsterdam identification
- Consulting achievement as value prop
- Projects table with live links
- Django, AWS Lambda, DynamoDB, LangChain, CrewAI, Cloudflare badges
- Email contact link
