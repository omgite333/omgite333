<h1 align="center">Hey, I'm Om Gite 👋</h1>
<h3 align="center">AI/LLM Developer — building agentic systems that don't fall over</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=58A6FF&center=true&vCenter=true&width=520&lines=Multi-agent+pipelines+with+LangGraph;Sandboxed%2C+guardrailed+tool-use;Crash-recovery+%26+distributed+workers;Real-time+systems+with+Redis+Streams" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://x.com/ommiee2805"><img src="https://img.shields.io/badge/X-@ommiee2805-000000?style=flat&logo=x&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=omgite333&color=58A6FF&style=flat&label=Profile+views" alt="Profile views" />
</p>

---

### About me

- 🎓 B.Tech Electronics Engineering @ **Walchand College of Engineering, Sangli** (Class of 2028)
- 💼 Ex **Full Stack Developer Intern** @ Reoxide Technologies — React · TypeScript · Node.js · AI-powered ESG features
- 🔭 I build systems where the interesting part isn't "call an LLM" — it's what surrounds the call: recovery when a worker dies mid-job, guardrails when an agent gets write access to a filesystem, fallback when a provider goes down mid-request
- 🌱 Currently deep in LangGraph orchestration, MCP tool integration, and async job pipelines (BullMQ/Redis)
- 📫 Reach me on [X](https://x.com/ommiee2805)

---

### Featured projects

<table>
<tr>
<td width="33%" valign="top">

**🤖 [Merg](https://github.com/omgite333/Merg)**

AI GitHub PR reviewer. A LangGraph pipeline runs specialist review agents (security, bugs, performance) in parallel per file, then merges overlapping findings onto the same line instead of dumping duplicate comments. Multi-provider LLM fallback (Groq → Gemini → OpenAI) means one provider outage doesn't kill a review. Workers hold a heartbeat/lease on each session, so a crashed worker's in-flight review gets safely reclaimed and retried instead of stuck forever.

`TypeScript` `LangGraph` `BullMQ` `Prisma` `Turborepo`

</td>
<td width="33%" valign="top">

**⌨️ [CloseCode](https://github.com/omgite333/CLOSECODE)**

Agentic terminal coding assistant — the same read-decide-act loop as Claude Code or OpenCode, built from scratch on LangGraph, with any model via OpenRouter. Plan mode literally never binds write/shell tools to the model, so exploration can't have side effects. Four guardrail layers block destructive commands (`rm -rf /`, fork bombs, `curl | sh`) before they run. Every file write is snapshotted for `/undo`, sessions persist in SQLite, and git tooling comes through MCP.

`Python` `LangGraph` `MCP` `Textual TUI`

</td>
<td width="33%" valign="top">

**📈 [Exness](https://github.com/omgite333/Exness)**

Real-time perpetual futures trading platform — BTC/ETH/SOL with leverage, against live Binance price feeds. A custom in-memory matching engine talks to the API over Redis Streams as a command bus (not direct calls), so order placement and the engine can scale independently. Price ticks fan out over Redis PubSub to a WebSocket layer for live UI updates, and the engine auto-liquidates positions that cross the margin threshold.

`Turborepo` `Redis Streams` `PostgreSQL` `MongoDB` `WebSockets`

</td>
</tr>
</table>

---

### Tech stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white" alt="Next.js" />
  <br/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/MCP-000000?style=flat&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" />
</p>

> Trimmed this down from the original to what's actually load-bearing in Merg / CloseCode / Exness. If you're regularly shipping in C++, Rust, AWS, or Kubernetes elsewhere, add those back — just worth being able to back each badge with a repo if someone asks.

---

### GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=omgite333&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=omgite333&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=omgite333&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>
