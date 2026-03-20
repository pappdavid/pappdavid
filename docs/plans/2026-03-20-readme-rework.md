# README Rework Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Replace the GitHub profile README with a recruiter-optimized version for Junior AI/Automation and Data Science roles.

**Architecture:** Single file replacement — `README.md` is overwritten wholesale with the new content defined in the design doc. No tests (it's a markdown file). Verify visually via GitHub after push.

**Tech Stack:** Markdown, shields.io badges, skillicons.dev icons, github-readme-stats

---

### Task 1: Write the new README.md

**Files:**
- Modify: `README.md`

**Step 1: Overwrite README.md with the following content**

```markdown
<div align="center">

# David Papp

**AI Engineering Student · VU Amsterdam**

Building production-quality LLM tools: agent observability, fine-tuning pipelines, retrieval systems.
Consulted for an AI-first startup to cut LLM API costs by ~40% and harden safety controls.

[Portfolio](https://davidpapp.dev) · [LinkedIn](https://www.linkedin.com/in/dávid-papp) · [Email](mailto:contact@davidpapp.dev)

</div>

---

### About

- 🎓 2nd-year BSc Artificial Intelligence at **Vrije Universiteit Amsterdam**
- 🔧 Consulted for an AI-first startup: restructured LLM backend architecture, hardened prompt injection defenses
- 🏗️ Lead technical delivery in 4–5 person hackathon and rapid-build teams
- 📍 Based in Rotterdam, NL — looking for junior AI/automation or data science roles
- 🐍 Strongest in Python; working proficiency in TypeScript

---

### Projects

| Project | What it does | Stack |
|---------|-------------|-------|
| [**MCP Sentinel**](https://davidpapp.dev/mcp) | Agent observability proxy — logs, guards, and audits every LLM tool call | TypeScript · Supabase · Upstash Redis |
| [**Training Pipeline**](https://davidpapp.dev/training) | AST-aware codebase→LoRA fine-tuning with ~3x better data quality | Python · HuggingFace · LoRA/PEFT |
| [**RAG + 3D Chat**](https://davidpapp.dev/chat) | Document Q&A with pgvector search, reranking, and Three.js rendering | Next.js · OpenAI API · pgvector |

---

### Tech Stack

**Languages**
<p>
  <img src="https://skillicons.dev/icons?i=py,ts,js&theme=dark" />
</p>

**AI / ML**
<p>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" height="28" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/CrewAI-000?style=flat-square&logoColor=white" height="28" />
</p>

**Backend & Data**
<p>
  <img src="https://skillicons.dev/icons?i=django,fastapi,postgres,redis,docker&theme=dark" />
  <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white" height="28" />
</p>

**Frontend & Infra**
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vercel,supabase&theme=dark" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/Hetzner-D50C2D?style=flat-square&logo=hetzner&logoColor=white" height="28" />
</p>

---

### GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=pappdavid&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D0D1A&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD" height="150" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pappdavid&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D0D1A&title_color=A78BFA&text_color=C4B5FD" height="150" />
</div>
```

**Step 2: Commit**

```bash
git add README.md
git commit -m "rework: replace README with recruiter-optimized version"
```

**Step 3: Push to GitHub**

```bash
git push origin main
```

**Step 4: Verify on GitHub**

Open `https://github.com/pappdavid` and confirm:
- No typing SVG animation
- No C#, .NET, FastAPI removed — wait, FastAPI stays
- No Hetzner removed — wait, Hetzner stays
- No streak card
- No snake animation section
- No profile view counter
- VU Amsterdam in About
- Consulting achievement in header
- Projects table visible
- Portfolio link points to davidpapp.dev
