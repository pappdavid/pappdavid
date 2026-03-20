<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D1A,50:7C3AED,100:06B6D4&height=120&section=header" width="100%" />

<div align="center">

# David Papp

**AI Engineering Student · VU Amsterdam**

Building production-quality LLM tools: agent observability, fine-tuning pipelines, retrieval systems.
Consulted for an AI-first startup to cut LLM API costs by ~40% and harden safety controls.

[Portfolio](https://davidpapp.dev) · [LinkedIn](https://www.linkedin.com/in/d%C3%A1vid-papp) · [Email](mailto:contact@davidpapp.dev)

<br/>

[![Jokes Card](https://readme-jokes.vercel.app/api?theme=dark&hideBorder=true&bgColor=%230D0D1A&textColor=%23C4B5FD&questionColor=%23A78BFA&answerColor=%2306B6D4)](https://github.com/ABSphreak/readme-jokes)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:06B6D4&height=2" width="100%" />

### About

- 🎓 2nd-year BSc Artificial Intelligence at **Vrije Universiteit Amsterdam**
- 🔧 Consulted for an AI-first startup: restructured LLM backend architecture, hardened prompt injection defenses
- 🏗️ Lead technical delivery in 4–5 person hackathon and rapid-build teams
- 📍 Based in Rotterdam, NL — looking for junior AI/automation or data science roles
- 🐍 Strongest in Python; working proficiency in TypeScript

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:06B6D4&height=2" width="100%" />

### Projects

| Project | What it does | Stack |
|---------|-------------|-------|
| [**MCP Sentinel**](https://davidpapp.dev/mcp) | Agent observability proxy — logs, guards, and audits every LLM tool call | TypeScript · Supabase · Upstash Redis |
| [**Training Pipeline**](https://davidpapp.dev/training) | AST-aware codebase→LoRA fine-tuning with ~3x better data quality | Python · HuggingFace · LoRA/PEFT |
| [**RAG + 3D Chat**](https://davidpapp.dev/chat) | Document Q&A with pgvector search, reranking, and Three.js rendering | Next.js · OpenAI API · pgvector |

<div align="center">

[![MCP Sentinel snippet](https://carbon.now.sh/svg?bg=rgba(13%2C13%2C26%2C1)&t=one-dark&wt=none&l=application%2Ftypescript&ds=false&wc=false&wa=true&pv=16px&ph=16px&ln=false&fl=1&fm=Fira%20Code&fs=14px&lh=133%25&si=false&es=1x&wm=false&code=proxy.on(%27tool_call%27%2C%20async%20(call)%20%3D%3E%20%7B%0A%20%20await%20logger.record(%7B%20tool%3A%20call.name%2C%20args%3A%20call.args%20%7D)%3B%0A%20%20if%20(await%20guard.isBlocked(call))%20throw%20new%20GuardError(call)%3B%0A%20%20return%20upstream.forward(call)%3B%0A%7D)%3B)](https://davidpapp.dev/mcp)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:06B6D4&height=2" width="100%" />

### Tech Stack

**Languages**
<p>
  <img src="https://skillicons.dev/icons?i=py,ts,js&theme=dark" height="28" />
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
  <img src="https://skillicons.dev/icons?i=django,fastapi,postgres,redis,docker&theme=dark" height="28" />
  <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white" height="28" />
</p>

**Frontend & Infra**
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vercel,supabase&theme=dark" height="28" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/Hetzner-D50C2D?style=flat-square&logo=hetzner&logoColor=white" height="28" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:06B6D4&height=2" width="100%" />

### GitHub Stats

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=pappdavid&theme=darkhub&no-frame=true&no-bg=true&column=6&margin-w=4)](https://github.com/ryo-ma/github-profile-trophy)

<img src="https://github-readme-stats.vercel.app/api?username=pappdavid&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D0D1A&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD" height="150" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pappdavid&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D0D1A&title_color=A78BFA&text_color=C4B5FD" height="150" />

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:06B6D4&height=2" width="100%" />

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pappdavid/pappdavid/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/pappdavid/pappdavid/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/pappdavid/pappdavid/output/github-contribution-grid-snake.svg" />
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:7C3AED,100:0D0D1A&height=120&section=footer" width="100%" />
