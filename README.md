### Hi, I am IRmsk 👋

I build tools for **Minecraft server administration**, **LLM infrastructure**, and **automation** — mostly in Python and Rust, mostly on Linux.

#### 🔧 Main Projects

**Minecraft tooling**

| Project | What it does |
|---|---|
| [**mc-scanner-v3**](https://github.com/IRmsk/mc-scanner-v3) | Server scanner & probe — port scan, SLP detection, auth-mode identification, observer bots, Web dashboard. Multi-version codec (41+ protocols), 215+ tests, GPL-3.0. |
| [**auto-mlg**](https://github.com/IRmsk/auto-mlg) | Forge mod for 1.20.1 — automatic water-bucket MLG on fall. No item consumption, no OP required. |

**LLM & automation**

| Project | What it does |
|---|---|
| [**IRmAPI**](https://github.com/IRmsk/IRmAPI) | OpenAI-compatible gateway with multi-provider routing (Doubao / DeepSeek / Qwen / ARK), streaming SSE, and cost guardrails. Docker, desktop and Android builds. |
| [**cidaren-ultimate**](https://github.com/IRmsk/cidaren-ultimate) | Vocabulary-drill framework — multi-source answer fusion, self-learning question bank, mock-server E2E tests. Web console + CLI. |
| [**stepdeck**](https://github.com/IRmsk/stepdeck) | Local step-count console — multi-account, daily scheduled submission, SQLite storage, standard-library HTTP server (no framework). |

**Fitness & geodata**

| Project | What it does |
|---|---|
| [**pace-forge**](https://github.com/IRmsk/pace-forge) | 运动世界校园 client — pure Rust, local Geetest solver, seven-step payload self-check, 250 tests. |

#### 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000?logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Minecraft](https://img.shields.io/badge/Minecraft-Protocol-62B47A)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

- **Minecraft protocol**: multi-version packet codec (41+ protocol versions), asyncio, encryption handshake
- **LLM ops**: provider abstraction, streaming, rate limiting, cost tracking
- **Rust**: binary envelopes (RSA + AES-CBC), local captcha solving, byte-exact golden vectors
- **Security**: default-deny design, capability gates, credential hygiene

#### 📦 Retired

- `mc-scanner` · `mc-scanner-v2` — archived, superseded by **mc-scanner-v3**
- `PCL` — mirror of [Meloong-Git/PCL](https://github.com/Meloong-Git/PCL), not my work

> 📫 Open source by default. Security research only — use responsibly.
