<div align="center">

<!-- Animated header with typing effect via SVG -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&multiline=true&width=750&height=100&lines=Hi+there%2C+I'm+AfifAljav+%F0%9F%91%8B;Builder+of+Lean%2C+Mean+Self-Hosted+Stacks" alt="Typing SVG" />

<br/>

<!-- Badges row -->
![Profile Views](https://komarev.com/ghpvc/?username=AfifAljav&color=00d9ff&style=flat-square&label=PROFILE+VIEWS)
[![GitHub followers](https://img.shields.io/github/followers/AfifAljav?style=flat-square&color=00d9ff&label=FOLLOWERS)](https://github.com/AfifAljav?tab=followers)
[![GitHub Repos](https://img.shields.io/badge/REPOS-36-00d9ff?style=flat-square)](https://github.com/AfifAljav?tab=repositories)

<br/>

<!-- Trophies -->
[![trophy](https://github-profile-trophy.vercel.app/?username=AfifAljav&theme=algolia&no-frame=true&row=1&column=4)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 🧠 About Me

> *"Good infrastructure should be cheap to run, easy to own, and impossible to outgrow."*

I build and curate **ultra-lean self-hosted tools**, **LLM prompt engineering resources**, and **local AI stacks** — all designed to run on hardware most people already have (or can afford for $5/month).

```yaml
focus:
  - Self-Hosted Infrastructure  # ≤512MB RAM constraint
  - LLM & Prompt Engineering    # benchmarks across 5 models
  - Local AI Stacks             # no API key, no cloud
  - Open Source Curation        # machine-readable data indexes

philosophy: "If it needs more than 512MB idle RAM, it doesn't belong on a $5 VPS."
currently_building: "awesome-selfhosted-lite v2 + CLI tool"
```

---

## 🚀 Featured Projects

<div align="center">

| 🏠 Project | 📝 What It Does | ⚡ Stack |
|:---:|:---|:---:|
| [**awesome-selfhosted-lite**](https://github.com/AfifAljav/awesome-selfhosted-lite) | Curated list of 80+ self-hosted apps that run on ≤512MB RAM — with real resource data & ready `docker-compose.yml` | `Markdown` `JSON` `Docker` |
| [**llm-prompt-patterns**](https://github.com/AfifAljav/llm-prompt-patterns) | Catalog of LLM prompt engineering patterns with templates, benchmarks across 5 models, and machine-readable `PATTERNS.json` | `Markdown` `JSON` `LLM` |
| [**local-ai-stack**](https://github.com/AfifAljav/local-ai-stack) | Full local AI stack in one command — LLM + Chat UI + Vector DB + Embeddings via Docker Compose. Zero API key, zero cloud | `Shell` `Docker` `AI` |
| [**shortlink-generator**](https://github.com/AfifAljav/shortlink-generator) | Minimal self-hosted URL shortener | `JavaScript` |

</div>

---

## 🗂️ awesome-selfhosted-lite — App Map

> **80 apps** across **8 categories** — all verified idle RAM ≤ 512MB

<details>
<summary><b>📁 File & Storage (10 apps)</b></summary>

| App | RAM | License |
|-----|-----|---------|
| Alist | ~80MB | AGPL-3.0 |
| Caddy File Server | ~30MB | Apache-2.0 |
| Dufs | ~20MB | MIT |
| Filebrowser | ~50MB | Apache-2.0 |
| FilePizza | ~30MB | MIT |
| Gokapi | ~50MB | EUPL-1.2 |
| ProjectSend | ~100MB | GPL-2.0 |
| PsiTransfer | ~40MB | BSD-2-Clause |
| SFTPGo | ~80MB | AGPL-3.0 |
| Syncthing | ~40MB | MPL-2.0 |

</details>

<details>
<summary><b>💬 Communication (10 apps)</b></summary>

| App | RAM | License |
|-----|-----|---------|
| Apprise | ~30MB | BSD-2-Clause |
| Chatwoot | ~250MB | MIT |
| Conduit | ~50MB | Apache-2.0 |
| Element Web | ~30MB | Apache-2.0 |
| Gotify | ~20MB | MIT |
| Listmonk | ~50MB | AGPL-3.0 |
| Memos | ~50MB | MIT |
| Novu | ~200MB | MIT |
| Ntfy | ~20MB | Apache-2.0 |
| Typebot | ~150MB | AGPL-3.0 |

</details>

<details>
<summary><b>📊 Monitoring (10 apps)</b></summary>

| App | RAM | Standout Feature |
|-----|-----|-----------------|
| Beszel | **~10MB** | Lightest monitor on the list |
| Dozzle | ~50MB | Real-time Docker log viewer |
| Gatus | ~30MB | Beautiful health dashboards |
| Glances | ~80MB | Terminal + web UI combo |
| Grafana | ~200MB | Dashboard powerhouse |
| Healthchecks | ~100MB | Cron job dead-man switch |
| Monitoror | ~30MB | TV wallboard aggregator |
| Netdata | ~150MB | Zero-config metrics |
| Changedetection.io | ~150MB | Website change alerts |
| Uptime Kuma | ~120MB | Beautiful status pages |

</details>

<details>
<summary><b>✅ Productivity (12 apps)</b></summary>

BookStack · Excalidraw · Flatnotes · FreshRSS · HedgeDoc · Homepage · Linkding · Miniflux · Stirling-PDF · Trilium Notes · Vikunja · Wallabag

</details>

<details>
<summary><b>🎵 Media (10 apps)</b></summary>

Audiobookshelf · Calibre-web · Immich · Kavita · Navidrome · PeerTube · Pinchflat · Podgrab · Stump · Tube Archivist

</details>

<details>
<summary><b>🛠️ Developer Tools (12 apps)</b></summary>

Coder · Dokemon · Forgejo · Gitea · Hoppscotch · IT-Tools · OneDev · Portainer · Registry · Snippet Box · Woodpecker CI · Yacht

</details>

<details>
<summary><b>🔐 Security (8 apps)</b></summary>

AdGuard Home · Authelia · CrowdSec · Headscale · Nginx Proxy Manager · Pi-hole · Vaultwarden · WireGuard

</details>

<details>
<summary><b>📈 Analytics (8 apps)</b></summary>

Ackee · Aptabase · Countly CE · GoAccess · Kuzzle Analytics · Shynet · Swetrix · Umami

</details>

---

## 🤖 llm-prompt-patterns — Quick Reference

```
PATTERNS.json  ←  machine-readable index (great for tooling)
├── chain-of-thought
├── few-shot
├── role-prompting
├── tree-of-thought
├── self-consistency
├── react-prompting
└── ... (benchmarked across GPT-4, Claude, Gemini, Mistral, Llama)
```

Each pattern includes:
- ✅ Template with variable slots
- 📊 Benchmark scores across 5 LLM families
- 💡 When to use / when to avoid
- 🔗 Machine-readable `PATTERNS.json` for building tools on top

---

## 🧱 local-ai-stack — One Command, Full Stack

```bash
git clone https://github.com/AfifAljav/local-ai-stack
cd local-ai-stack
docker compose up -d   # CPU profile (default)
# or
docker compose --profile gpu up -d  # GPU profile
```

Includes: **LLM** (Ollama) + **Chat UI** (Open WebUI) + **Vector DB** (Qdrant) + **Embeddings** — no API key, no cloud, no tracking.

---

## 📊 GitHub Stats

<div align="center">

<img height="160em" src="https://github-readme-stats.vercel.app/api?username=AfifAljav&show_icons=true&theme=algolia&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AfifAljav&layout=compact&theme=algolia&hide_border=true&langs_count=6"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=AfifAljav&theme=algolia&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)](https://git.io/streak-stats)

</div>

---

## 🏅 Achievements

<div align="center">

| 🧠 Galaxy Brain | ⚡ YOLO | 🎯 Quickdraw | 🦈 Pull Shark |
|:---:|:---:|:---:|:---:|
| Insightful answers | Ship it! | Fast responder | Merged PRs |

</div>

---

## 🤝 Contribute

All three main repos welcome contributions:

```
awesome-selfhosted-lite  →  New app? Check CRITERIA.md → CONTRIBUTING.md → PR
llm-prompt-patterns      →  New pattern? Add to PATTERNS.json + benchmark
local-ai-stack           →  New service? One docker-compose profile per service
```

**The single rule across all repos:** *It must work on a $5/month VPS.*

---

## 📬 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-AfifAljav-181717?style=for-the-badge&logo=github)](https://github.com/AfifAljav)

</div>

---

<div align="center">

<sub>All repos licensed CC0 1.0 or MIT — use freely, no attribution required.</sub>

<br/>

![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red?style=flat-square)
![Self-Hosted](https://img.shields.io/badge/100%25-Self--Hosted-00d9ff?style=flat-square)
![No Cloud](https://img.shields.io/badge/Zero-Cloud%20Required-success?style=flat-square)

</div>
