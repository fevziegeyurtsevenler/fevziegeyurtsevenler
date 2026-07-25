<p align="center">
  <img src="assets/hero.svg" width="100%" alt="Fevzi Ege Yurtsevenler — LLM & AI Security · AI Red Team">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=1200&color=FF2B2B&center=true&vCenter=true&width=780&lines=AI+Red+Teamer+%E2%80%94+I+break+LLMs+so+you+don't+get+broken.;16+open-source+security+tools.+T%C3%BCrk%C3%A7e-first.;Prompt+injection+%C2%B7+MCP+%C2%B7+agent+supply+chain;uncloak+%C2%B7+skills-in-the-wild+%C2%B7+ai-honeypot" alt="typing">
</p>

<p align="center">
  <a href="https://genai.owasp.org/"><img src="https://img.shields.io/badge/OWASP_GenAI-Contributor-FF2B2B?style=flat-square&labelColor=0a0a0a"></a>
  <a href="https://doi.org/10.5281/zenodo.20681557"><img src="https://img.shields.io/badge/Zenodo-DOI-FF2B2B?style=flat-square&labelColor=0a0a0a"></a>
  <a href="https://orcid.org/0009-0008-6518-8944"><img src="https://img.shields.io/badge/ORCID-0009--0008--6518--8944-FF2B2B?style=flat-square&labelColor=0a0a0a"></a>
  <img src="https://img.shields.io/badge/OpenAI-Bug_Bounty_researcher-FF2B2B?style=flat-square&labelColor=0a0a0a">
  <img src="https://komarev.com/ghpvc/?username=fevziegeyurtsevenler&color=FF2B2B&style=flat-square&label=profile+views">
</p>

---

### `> whoami`

**Türkiye'nin yapay zekâ güvenliği alanını kuran araştırmacılardan.** Klasik siber
güvenlik mühendisliğinden geldim; 2024'ten beri tek odağım **dil modellerini ve
ajanları kırmak — ve savunmak.** 2025'te Türkiye'nin yalnızca AI güvenliğine odaklı
ilk şirketi **[AltaySec](https://altaysec.com.tr)**'i kurdum.

I red-team language models and AI agents: **prompt injection, MCP / tool poisoning,
RAG attacks, and the invisible-Unicode supply chain.** Then I ship the open-source
tools to defend against them — **Turkish-first, because non-English attacks walk
right through English-only filters.**

---

### ⚡ Live — try it right now

| | |
|---|---|
| 🕵️ **[uncloak — in your browser](https://fevziegeyurtsevenler.github.io/uncloak/)** | Paste a `SKILL.md` / MCP config and watch a hidden instruction appear. Zero install. |
| 🍯 **[ai-honeypot — live attack console](https://fevziegeyurtsevenler.github.io/ai-honeypot/)** | A dashboard of attacks sent to a decoy AI agent. |
| 🧪 **[Açık Kaynak Lab](https://altaysec.com.tr/acik-kaynak)** | All 16 tools, one page. |

---

### 🗡️ The arsenal — 16 open-source tools

**Tools & data**
| Repo | What it does for you |
|---|---|
| **[uncloak](https://github.com/fevziegeyurtsevenler/uncloak)** | Reveal hidden prompt injection in Skills / MCP / rules files. Multilingual, SARIF, zero-dep. |
| **[skills-in-the-wild](https://github.com/fevziegeyurtsevenler/skills-in-the-wild)** | Open audit of **3,168** real agent extensions — dataset + findings + method. |
| **[ai-honeypot](https://github.com/fevziegeyurtsevenler/ai-honeypot)** | A decoy that captures & classifies attacks on AI agents (+ live dashboard). |
| **[prompt-injection-corpus](https://github.com/fevziegeyurtsevenler/prompt-injection-corpus)** | Multilingual injection techniques — each paired with its defense. |
| **[prompt-injection-detection-rules](https://github.com/fevziegeyurtsevenler/prompt-injection-detection-rules)** | 20 portable detection rules (regex+YAML) for guardrails/WAFs. |
| **[agent-security-ci](https://github.com/fevziegeyurtsevenler/agent-security-ci)** | Drop uncloak into CI — scan extensions, upload SARIF. |

**Skills, labs & playbooks**
| Repo | What it does for you |
|---|---|
| **[llm-security-skills](https://github.com/fevziegeyurtsevenler/llm-security-skills)** | 7 Agent Skills that turn your coding agent into an LLM security reviewer. |
| **[damn-vulnerable-agent-skill](https://github.com/fevziegeyurtsevenler/damn-vulnerable-agent-skill)** | 8 deliberately-vulnerable scenarios to learn agent attacks hands-on. |
| **[llm-red-team-playbook](https://github.com/fevziegeyurtsevenler/llm-red-team-playbook)** | Scope → threat model → OWASP LLM Top 10 test matrix → report. |

**Guides, compliance & curation**
| Repo | What it does for you |
|---|---|
| **[mcp-security-checklist](https://github.com/fevziegeyurtsevenler/mcp-security-checklist)** · **[owasp-agentic-skills-top10-tr](https://github.com/fevziegeyurtsevenler/owasp-agentic-skills-top10-tr)** | Harden MCP; OWASP Agentic Skills Top 10 in Turkish. |
| **[kvkk-ai-compliance-kit](https://github.com/fevziegeyurtsevenler/kvkk-ai-compliance-kit)** · **[eu-ai-act-technical-checklist](https://github.com/fevziegeyurtsevenler/eu-ai-act-technical-checklist)** | KVKK + EU AI Act, as engineering checklists. |
| **[ai-security-glossary](https://github.com/fevziegeyurtsevenler/ai-security-glossary)** · **[awesome-agent-supply-chain-security](https://github.com/fevziegeyurtsevenler/awesome-agent-supply-chain-security)** · **[awesome-turkish-ai-security](https://github.com/fevziegeyurtsevenler/awesome-turkish-ai-security)** | Bilingual glossary + two curated lists. |

---

### 🎖️ Verifiable credentials

- **[OWASP GenAI Security Project](https://genai.owasp.org/)** — Contributor; Turkish prompt-injection & data-exfiltration test cases **merged** into the GenAI Data Security Initiative dataset (2026).
- **Zenodo** — [DOI 10.5281/zenodo.20681557](https://doi.org/10.5281/zenodo.20681557) · *AltayDuel: a Turkish-first arena & open dataset for multi-turn LLM prompt-injection red-teaming* (CC-BY-4.0). **[ORCID 0009-0008-6518-8944](https://orcid.org/0009-0008-6518-8944)**.
- **OpenAI Bug Bounty** — accepted researcher.
- **Türkiye Siber Vatan** (2 terms) — Ministry-of-Industry-and-Technology-verified national cyber talent program · **BlueDot Impact** — *Future of AI* certificate (2026).
- Gave **Türkiye's first university-level LLM Security course** (Gazi University, Computer Engineering — as AltaySec).

---

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=fevziegeyurtsevenler&show_icons=true&hide_border=true&title_color=FF2B2B&icon_color=FF2B2B&text_color=b9a9a9&bg_color=050406" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fevziegeyurtsevenler&layout=compact&hide_border=true&title_color=FF2B2B&text_color=b9a9a9&bg_color=050406" />
</div>

<p align="center">
  <a href="https://altaysec.com.tr"><img src="https://img.shields.io/badge/AltaySec-altaysec.com.tr-FF2B2B?style=flat-square&labelColor=0a0a0a"></a>
  <a href="https://www.linkedin.com/in/fevziege"><img src="https://img.shields.io/badge/LinkedIn-fevziege-FF2B2B?style=flat-square&labelColor=0a0a0a"></a>
  <a href="mailto:ege@altaysec.com.tr"><img src="https://img.shields.io/badge/mail-ege@altaysec.com.tr-FF2B2B?style=flat-square&labelColor=0a0a0a"></a>
</p>

<p align="center"><sub>Kırmızı takım kurar, mavi takım için savunur. · Ankara, Türkiye</sub></p>
