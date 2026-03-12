<div align="center">

# Jörg Michno

**Software Developer · GenAI & AI Security**

[![GitHub](https://img.shields.io/badge/GitHub-joergmichno-181717?style=flat&logo=github)](https://github.com/joergmichno)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jörg_Michno-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jörg-michno-6a3899245)
[![Location](https://img.shields.io/badge/Hannover-Germany-blue?style=flat&logo=googlemaps&logoColor=white)](https://github.com/joergmichno)
[![Shield](https://img.shields.io/badge/ClawGuard_Shield-Live_Demo-brightgreen?style=flat&logo=rocket&logoColor=white)](https://prompttools.co/shield)

</div>

---

I build security tools for AI agents, working at the intersection of **Generative AI** and **Cybersecurity**. My focus: making autonomous AI agents safer — from prompt injection detection and security scanning APIs to EU AI Act compliance reports and MCP integrations for Claude Desktop & Cursor.

## Projects

<table>
<tr>
<td width="50%">

### 🛡️ [ClawGuard](https://github.com/joergmichno/clawguard)
**Security Scanner for AI Agents**

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)](https://github.com/joergmichno/clawguard)
[![PyPI](https://img.shields.io/pypi/v/clawguard?style=flat&logo=pypi&logoColor=white)](https://pypi.org/project/clawguard/)
[![Tests](https://img.shields.io/badge/Tests-71_passed-brightgreen?style=flat&logo=pytest&logoColor=white)](https://github.com/joergmichno/clawguard)
[![License](https://img.shields.io/github/license/joergmichno/clawguard?style=flat)](https://github.com/joergmichno/clawguard/blob/main/LICENSE)

Real-time detection of prompt injection, code obfuscation, social engineering and data exfiltration. 42+ detection patterns across 5 categories, adversarial red-teaming, available as PyPI package.

</td>
<td width="50%">

### 🔒 [ClawGuard Shield](https://github.com/joergmichno/clawguard-shield)
**Security Scanning REST API (SaaS)** · [**Live Demo →**](https://prompttools.co/shield)

[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)](https://github.com/joergmichno/clawguard-shield)
[![Tests](https://img.shields.io/badge/Tests-93_passed-brightgreen?style=flat&logo=pytest&logoColor=white)](https://github.com/joergmichno/clawguard-shield)
[![Live API](https://img.shields.io/badge/API-Live-brightgreen?style=flat&logo=rocket&logoColor=white)](https://prompttools.co/shield)

REST API for AI agent security: 10 endpoints, 42+ patterns, PDF compliance reports with EU AI Act mapping. Stripe payments, tier-based rate limiting, Docker-deployed on VPS.

</td>
</tr>
<tr>
<td width="50%">

### 🐍 [Shield Python SDK](https://github.com/joergmichno/clawguard-shield-python)
**`pip install clawguard-shield`**

[![PyPI](https://img.shields.io/pypi/v/clawguard-shield?style=flat&logo=pypi&logoColor=white)](https://pypi.org/project/clawguard-shield/)
[![Tests](https://img.shields.io/badge/Tests-37_passed-brightgreen?style=flat&logo=pytest&logoColor=white)](https://github.com/joergmichno/clawguard-shield-python)
[![License](https://img.shields.io/github/license/joergmichno/clawguard-shield-python?style=flat)](https://github.com/joergmichno/clawguard-shield-python/blob/main/LICENSE)

3 lines of code to scan any prompt. Dataclass results, full type hints, ready-made integration for FastAPI & LangChain.

</td>
<td width="50%">

### 🔌 [ClawGuard MCP Server](https://github.com/joergmichno/clawguard-mcp)
**`pip install clawguard-mcp`**

[![PyPI](https://img.shields.io/pypi/v/clawguard-mcp?style=flat&logo=pypi&logoColor=white)](https://pypi.org/project/clawguard-mcp/)
[![MCP](https://img.shields.io/badge/MCP-Compatible-8A2BE2?style=flat)](https://github.com/joergmichno/clawguard-mcp)

MCP server for Claude Desktop, Cursor & Windsurf — security scanning directly in your editor. 5 tools, FastMCP + async.

</td>
</tr>
</table>

### Ecosystem

| Repo | Description | |
|------|-------------|---|
| ⚡ [Shield Scan Action](https://github.com/joergmichno/clawguard-scan-action) | GitHub Action for CI/CD security scanning — smart prompt detection, PR summaries, configurable severity thresholds. | [![Tests](https://img.shields.io/badge/Tests-25_passed-brightgreen?style=flat&logo=pytest&logoColor=white)](https://github.com/joergmichno/clawguard-scan-action) |
| 📦 [Shield JS SDK](https://github.com/joergmichno/clawguard-shield-js) | `npm install clawguard-shield` — Zero deps, ESM+CJS+TS, 50 tests. Full TypeScript support. | [![Tests](https://img.shields.io/badge/Tests-50_passed-brightgreen?style=flat&logo=jest&logoColor=white)](https://github.com/joergmichno/clawguard-shield-js) |
| 🧪 [Prompt Lab](https://prompttools.co) | Interactive web app for testing prompt injection attacks — 48 patterns, 12 example attacks, JSON API. Powered by ClawGuard. | [![Live](https://img.shields.io/badge/Live-Online-brightgreen?style=flat&logo=rocket&logoColor=white)](https://prompttools.co) |
| 📚 [DocQA](https://github.com/joergmichno/docqa) | RAG-based document Q&A CLI with TF-IDF vectorization + cosine similarity. Modular pipeline, optional LLM integration. | [![Tests](https://img.shields.io/badge/Tests-33_passed-brightgreen?style=flat&logo=pytest&logoColor=white)](https://github.com/joergmichno/docqa) |

### 🤖 Buddy — Autonomous AI Agent

<table>
<tr>
<td>

**Self-hosted AI Agent on VPS with Telegram Integration**

[![Docker](https://img.shields.io/badge/Docker-Deployed-2496ED?style=flat&logo=docker&logoColor=white)](#)
[![Telegram](https://img.shields.io/badge/Telegram-Bot-26A5E4?style=flat&logo=telegram&logoColor=white)](#)

Autonomous AI agent on a Hostinger VPS: Docker-based, Telegram bot with multilingual voice output (ElevenLabs TTS), shared memory system, ClawGuard integration as security skill.

</td>
</tr>
</table>

## Tech Stack

<div align="center">

**AI & Security**

![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-FF6F00?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4A154B?style=for-the-badge&logoColor=white)
![LLM Security](https://img.shields.io/badge/LLM_Security-DC143C?style=for-the-badge&logoColor=white)
![Red Teaming](https://img.shields.io/badge/Red_Teaming-8B0000?style=for-the-badge&logoColor=white)
![API Security](https://img.shields.io/badge/API_Security-FF4500?style=for-the-badge&logoColor=white)

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**DevOps & Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=joergmichno&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=joergmichno&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top Languages" height="165" />

</div>

## What Drives Me

> Autonomous AI agents will transform how we work — but only if we can make them secure.

I combine hands-on agent development with security research because both go hand in hand. From prompt injection detection to EU AI Act compliance reports to red teaming: I build the tools that make AI agents trustworthy.

---

<div align="center">

[![Email](https://img.shields.io/badge/Email-michno.jrg@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:michno.jrg@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jörg-michno-6a3899245)
[![Shield](https://img.shields.io/badge/ClawGuard_Shield-Try_It-brightgreen?style=flat&logo=rocket&logoColor=white)](https://prompttools.co/shield)

*Building AI agents — and the tools to keep them safe.* 🛡️

</div>
