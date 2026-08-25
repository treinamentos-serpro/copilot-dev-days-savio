🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎱 Soc Ops

### Social Bingo for People Who Actually Want to Meet People

**Break the ice. Find your people. Win at the mixer.**

[![Play Now](https://img.shields.io/badge/🎮_Play_Now-4F46E5?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![Lab Guide](https://img.shields.io/badge/📚_Lab_Guide-0EA5E9?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)

</div>

---

## What is Soc Ops?

Soc Ops is a **Social Bingo** web game designed for in-person events and mixers. Instead of numbers on your bingo card, you get *people prompts* — find someone who matches each square, get their name, and race to 5 in a row.

It's also a **GitHub Copilot hands-on lab**: you'll build and extend this Blazor WebAssembly app using AI-assisted coding techniques — context engineering, design-first development, custom agents, and multi-agent workflows.

---

## 🧩 How to Play

1. **Every player gets a unique 5×5 bingo card** filled with social prompts
2. **Mingle** — find real people who match each square and write their name in
3. **Shout "Soc Ops!"** when you complete 5 in a row (horizontal, vertical, or diagonal)
4. No phone required — just conversation ✨

---

## 🛠️ Lab Guide

This repo is the starting point for a **4-part Copilot workshop**. Each part teaches a different AI-assisted development skill.

| # | Part | What You'll Build |
|---|------|-------------------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Checklist | Orient yourself and set up your workspace |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup & Context Engineering | AGENTS.md, `.github/copilot-instructions.md`, prompt crafting |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend | Polished UI driven by Copilot design prompts |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master | A specialized Copilot agent for prompt generation |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development | Orchestrating multiple agents on the same codebase |

> 📝 All guides are also available offline in the [`workshop/`](workshop/) folder.

---

## 🚀 Getting Started

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or later
- [GitHub Copilot](https://github.com/features/copilot) (for the lab portions)

### Option A — GitHub Codespaces (zero setup)

After forking or using this template:

1. Click **Code → Codespaces → Create codespace on main**
2. Wait for the devcontainer to finish
3. Run:
   ```bash
   cd SocOps && dotnet run
   ```
4. Open the forwarded port in your browser

### Option B — Run locally

```bash
git clone <your-fork-url>
cd copilot-dev-days-savio/SocOps
dotnet run
```

### Build only

```bash
cd SocOps
dotnet build
```

---

## 🌐 Deployment

The app deploys automatically to **GitHub Pages** whenever you push to `main`. No extra configuration needed.

---

## 🤝 Contributing

Feedback and PRs welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

<div align="center">

Built with ❤️ on .NET + Blazor WebAssembly · Powered by GitHub Copilot

</div>
