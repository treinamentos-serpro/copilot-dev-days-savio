🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎱 Soc Ops

### Social Bingo for in-person mixers — powered by GitHub Copilot

Find people who match the prompts. Get five in a row. Win the room.

[![Play the Game](https://img.shields.io/badge/🎮%20Play%20the%20Game-blue?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![View Lab Guide](https://img.shields.io/badge/📚%20Lab%20Guide-gray?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)

</div>

---

## What is this?

**Soc Ops** is a hands-on workshop disguised as a party game. You start with a working Social Bingo app built in **Blazor WebAssembly + .NET 10**, then use **VS Code Agent Mode** and **GitHub Copilot** to transform it — redesigning the UI, generating custom quiz content, and shipping new features with multi-agent workflows.

By the end, you'll have shipped a personalized version of the game *and* a new set of skills for agentic development.

> ⏱ About 1 hour · Intermediate level · C# / .NET 10 / Blazor

---

## 🗺 Lab Overview

| Part | Topic | What you'll do |
|------|-------|----------------|
| [**00 — Overview**](workshop/00-overview.md) | Orientation & checklist | Verify your environment and understand the arc of the lab |
| [**01 — Setup**](workshop/01-setup.md) | Context engineering | Teach Copilot about your codebase with AGENTS.md and custom instructions |
| [**02 — Design**](workshop/02-design.md) | Design-first frontend | Prompt Copilot to reimagine the UI with a distinctive visual theme |
| [**03 — Quiz Master**](workshop/03-quiz-master.md) | Custom agents | Build a Quiz Master agent that generates bingo prompts on demand |
| [**04 — Multi-Agent**](workshop/04-multi-agent.md) | TDD + parallel agents | Add new game features using test-driven development with background agents |

> 💡 Lab steps are also hosted online — links in each workshop file.

---

## ✨ Skills you'll build

- **Context Engineering** — shape AI behaviour by describing your codebase and conventions
- **Agentic Workflows** — background agents, cloud agents, and custom skill definitions
- **Design-First Development** — guide Copilot to iterate on UI while you set creative direction
- **Test-Driven Development** — TDD agents that write tests before implementation

---

## 🚀 Quick Start

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or higher
- VS Code v1.107+ with GitHub Copilot (Pro, Business, or Enterprise)

### Run locally

```bash
cd SocOps
dotnet run
```

### Open in GitHub Codespaces

The repo ships with a devcontainer — zero local setup required:

1. Fork or use this template repo on GitHub
2. Click **Code → Codespaces → Create codespace on main**
3. Wait for setup, then run:
   ```bash
   cd SocOps
   dotnet run
   ```

### Build

```bash
cd SocOps
dotnet build
```

Deploys automatically to GitHub Pages on every push to `main`.
