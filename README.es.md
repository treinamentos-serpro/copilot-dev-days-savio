<!-- l10n-sync: source-file="README.md" -->

<div align="center">

# 🎱 Soc Ops

### Social Bingo para quienes quieren conocer gente de verdad

**Rompe el hielo. Encuentra tu tribu. Gana en el mixer.**

[![Jugar Ahora](https://img.shields.io/badge/🎮_Jugar_Ahora-4F46E5?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![Guía del Lab](https://img.shields.io/badge/📚_Guía_del_Lab-0EA5E9?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)

</div>

---

## ¿Qué es Soc Ops?

Soc Ops es un juego de **Social Bingo** diseñado para eventos y encuentros presenciales. En lugar de números en tu tarjeta, recibes *preguntas sobre personas* — encuentra a alguien que encaje en cada casilla, escribe su nombre y corre a completar 5 en línea.

También es un **laboratorio práctico con GitHub Copilot**: construirás y extenderás esta app Blazor WebAssembly usando técnicas de desarrollo asistido por IA — ingeniería de contexto, design-first, agentes personalizados y flujos multi-agente.

---

## 🧩 Cómo Jugar

1. **Cada jugador recibe una tarjeta 5×5 única** con preguntas sociales
2. **Circula por la sala** — encuentra personas reales que encajen en cada casilla y escribe su nombre
3. **¡Grita "Soc Ops!"** al completar 5 en línea (horizontal, vertical o diagonal)
4. Sin necesidad de teléfono — solo conversación ✨

---

## 🛠️ Guía del Lab

Este repositorio es el punto de partida de un **workshop Copilot de 4 partes**. Cada parte enseña una habilidad diferente de desarrollo asistido por IA.

| # | Parte | Qué vas a construir |
|---|-------|---------------------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Descripción General & Lista Rápida | Orientación y configuración del entorno |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuración & Ingeniería de Contexto | AGENTS.md, `.github/copilot-instructions.md`, creación de prompts |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First | UI refinada guiada por prompts de diseño de Copilot |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | Un agente Copilot especializado para generar prompts |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desarrollo Multi-Agent | Orquestación de múltiples agentes en la misma base de código |

> 📝 Todas las guías también están disponibles sin conexión en la carpeta [`workshop/es/`](workshop/es/).

---

## 🚀 Primeros Pasos

### Requisitos Previos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) o superior
- [GitHub Copilot](https://github.com/features/copilot) (para las partes del lab)

### Opción A — GitHub Codespaces (sin configuración)

Después de hacer fork o usar esta plantilla:

1. Haz clic en **Code → Codespaces → Create codespace on main**
2. Espera a que el devcontainer termine
3. Ejecuta:
   ```bash
   cd SocOps && dotnet run
   ```
4. Abre el puerto redirigido en tu navegador

### Opción B — Ejecutar localmente

```bash
git clone <url-de-tu-fork>
cd copilot-dev-days-savio/SocOps
dotnet run
```

### Solo compilar

```bash
cd SocOps
dotnet build
```

---

## 🌐 Deploy

La app se publica automáticamente en **GitHub Pages** con cada push a `main`. No se necesita configuración adicional.

---

## 🤝 Contribuir

¡Los comentarios y PRs son bienvenidos! Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para las directrices.

---

<div align="center">

Hecho con ❤️ en .NET + Blazor WebAssembly · Desarrollado con GitHub Copilot

</div>
