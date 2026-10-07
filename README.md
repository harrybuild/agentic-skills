# Agentic Skills & The Everything Index

[![Live Site](https://img.shields.io/badge/Live%20Arena-tutorhero.me-10b981.svg)](https://tutorhero.me)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Indexed Skills](https://img.shields.io/badge/Indexed%20Skills-200%20Verified-blue.svg)](https://tutorhero.me/skills_data.json)
[![LLM Native](https://img.shields.io/badge/Agent%20Manifest-llms.txt-emerald.svg)](https://tutorhero.me/llms.txt)

> **"In the AI era, we are all students."**  
> TutorHero is the empirical Everything Index for agentic learning—indexing 200+ open-source heroes, Cloudflare edge runtimes, and autonomous agent loops.

---

## ⚡ The Thesis

TutorHero is not about traditional 1-on-1 school tutoring or human mentorship middlemen. In the intelligence era, education is no longer confined to static syllabi or credentialed gatekeepers. 

With models advancing weekly, **we are all students**. We learn by building with and studying the **open-source heroes** who architect the frontier:

1. **Open-Source as Curriculum**: The code repository is the modern lecture hall. True mastery comes from studying real diffs, reading production agent harnesses, and evaluating test-time reasoning compute.
2. **Empirical Indexing**: We benchmark tools on verifiable metrics: weekly star velocity, Arena ELO ratings, web traffic mindshare, and sub-30ms execution latencies.
3. **Orchestration Over Syntax**: Knowledge work is shifting rapidly from writing manual boilerplate (-68% time spent) toward system architecture, agent orchestration, and automated verification (+340% time surge, referenced in a16z Enterprise AI benchmarks).

---

## 📊 Live Arena Leaderboard

Explore the live interactive leaderboard at **[tutorhero.me](https://tutorhero.me)**:
- **Leaderboard**: [tutorhero.me](https://tutorhero.me)
- **Market Pulse**: [tutorhero.me/#market-pulse](https://tutorhero.me/#market-pulse)
- **Thesis & Macro Trends**: [tutorhero.me/thesis](https://tutorhero.me/thesis)
- **Open Access & Pricing**: [tutorhero.me/pricing](https://tutorhero.me/pricing)
- **Machine Manifest**: [tutorhero.me/llms.txt](https://tutorhero.me/llms.txt)
- **Public Dataset**: [tutorhero.me/skills_data.json](https://tutorhero.me/skills_data.json)

---

## 🧭 The 6 Disciplines of Modern Builders

| Discipline | Persona Tag | Hero Repositories Indexed |
| :--- | :--- | :--- |
| **Autonomous SWE** | `#SWE` | Cline, Roo Code, OpenHands, Aider, Goose, Agent Zero, SWE-bench |
| **Reasoning & STEM** | `#STEM` | DeepSeek-R1, Karpathy AutoResearch, Apple MLX, DSPy, Torchtune, Lean 4 |
| **Local Inference** | `#Inference` | Ollama, vLLM, SGLang, Open WebUI, Jan Offline, GPT4All, Whisper.cpp |
| **Memory, RAG & Data** | `#RAG` | RAGFlow, Letta (MemGPT), Mem0, Haystack, Vanna SQL, SQLGlot, LanceDB |
| **Edge & Audio Creators** | `#Audio` | Cloudflare Agents SDK, MCP Hub, Demucs Audio, Kokoro TTS, Fish Speech |
| **Founders & 0-to-1** | `#Founders` | Supabase, Bolt.diy, Garry Tan Founder Playbooks, YC Hackathon Starters |

---

## 🤖 Machine-Readable Endpoints (Agent Native)

If you are building an autonomous agent or crawler (Claude Desktop, Cursor, LangChain, CrewAI), access our un-gated, edge-cached endpoints:

```bash
# Agent markdown manifest
curl -s https://tutorhero.me/llms.txt

# Complete 200 skills dataset in JSON
curl -s https://tutorhero.me/skills_data.json

# Discovery and schema metadata
curl -s https://tutorhero.me/content.json
```

---

## 📈 Benchmarking Methodology

Rankings on TutorHero are deterministically evaluated:
1. **Weekly Star Surge (`wGrowth`)**: Velocity of new developer adoption over 7-day rolling windows.
2. **Arena ELO (`elo`)**: Comparative head-to-head match scoring evaluated via Cloudflare Clef edge models against developer tasks.
3. **Execution Latency (`latency`)**: Mean response and token synthesis latency measured across edge V8 isolates.
4. **Traffic Mindshare (`traffic`)**: Monthly active developer queries and registry downloads.

**Zero Sponsored Rankings**: No project can pay for rank priority. All evaluations are derived from verifiable open metrics.

---

## 🤝 How to Contribute

We welcome contributions from open-source creators and developers!

### Submit a New Skill
1. Fork this repository.
2. Add your repository entry to `skills_data.json` following the schema:
```json
{
  "id": "your-skill-id",
  "name": "Skill Name",
  "repo": "owner/repo",
  "author": "owner",
  "persona": "Autonomous Software Engineers",
  "targetRole": "Full-Stack AI Engineers",
  "stars": 15000,
  "wGrowth": 12.5,
  "mGrowth": 45,
  "website": "https://yoursite.com",
  "desc": "Precise one-sentence description of the capability.",
  "useCase": "What production problem this solves.",
  "arch": "Key architectural components.",
  "tags": ["tag1", "tag2"]
}
```
3. Open a Pull Request. Our automated CI verifies the repository license, public activity, and schema formatting.

---

## 📜 License

Released under the [MIT License](LICENSE).
Built with passion for the open-source community by **[harrybuild](https://github.com/harrybuild)**.
