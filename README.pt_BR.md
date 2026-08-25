<!-- l10n-sync: source-file="README.md" -->

<div align="center">

# 🎱 Soc Ops

### Social Bingo para quem quer conhecer pessoas de verdade

**Quebre o gelo. Encontre sua turma. Vença no mixer.**

[![Jogar Agora](https://img.shields.io/badge/🎮_Jogar_Agora-4F46E5?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![Guia do Lab](https://img.shields.io/badge/📚_Guia_do_Lab-0EA5E9?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)

</div>

---

## O que é o Soc Ops?

O Soc Ops é um jogo de **Social Bingo** criado para eventos e encontros presenciais. Em vez de números no cartão, você recebe *perguntas sobre pessoas* — encontre alguém que se encaixe em cada quadrado, anote o nome dela e corra para completar 5 em linha.

É também um **laboratório prático com GitHub Copilot**: você vai construir e evoluir este app Blazor WebAssembly usando técnicas de desenvolvimento assistido por IA — engenharia de contexto, design-first, agentes customizados e fluxos multi-agente.

---

## 🧩 Como Jogar

1. **Cada jogador recebe um cartão 5×5 único** com perguntas sociais
2. **Circule pela sala** — encontre pessoas reais que se encaixem em cada quadrado e escreva o nome delas
3. **Grite "Soc Ops!"** ao completar 5 em linha (horizontal, vertical ou diagonal)
4. Sem precisar de celular — só conversa ✨

---

## 🛠️ Guia do Lab

Este repositório é o ponto de partida de um **workshop Copilot em 4 partes**. Cada parte ensina uma habilidade diferente de desenvolvimento assistido por IA.

| # | Parte | O que você vai construir |
|---|-------|--------------------------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Visão Geral & Lista Rápida | Orientação e configuração do ambiente |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuração & Engenharia de Contexto | AGENTS.md, `.github/copilot-instructions.md`, criação de prompts |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First | UI refinada guiada por prompts de design do Copilot |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | Um agente Copilot especializado para geração de prompts |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desenvolvimento Multi-Agent | Orquestração de múltiplos agentes na mesma base de código |

> 📝 Todos os guias também estão disponíveis offline na pasta [`workshop/pt_BR/`](workshop/pt_BR/).

---

## 🚀 Primeiros Passos

### Pré-requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) ou superior
- [GitHub Copilot](https://github.com/features/copilot) (para as partes do lab)

### Opção A — GitHub Codespaces (sem configuração)

Depois de fazer fork ou usar este template:

1. Clique em **Code → Codespaces → Create codespace on main**
2. Aguarde o devcontainer terminar
3. Execute:
   ```bash
   cd SocOps && dotnet run
   ```
4. Abra a porta redirecionada no navegador

### Opção B — Rodar localmente

```bash
git clone <url-do-seu-fork>
cd copilot-dev-days-savio/SocOps
dotnet run
```

### Apenas compilar

```bash
cd SocOps
dotnet build
```

---

## 🌐 Deploy

O app é publicado automaticamente no **GitHub Pages** a cada push para `main`. Nenhuma configuração adicional necessária.

---

## 🤝 Contribuindo

Feedbacks e PRs são bem-vindos! Veja [CONTRIBUTING.md](CONTRIBUTING.md) para as diretrizes.

---

<div align="center">

Feito com ❤️ em .NET + Blazor WebAssembly · Desenvolvido com GitHub Copilot

</div>
