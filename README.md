<div align="center">

🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# 🎯 Soc Ops

### Social Bingo — the icebreaker that actually works

Find people who match the clues. Get 5 in a row. Break the ice at any in-person event.

[![Play Now](https://img.shields.io/badge/🎮%20Play%20Now-Live%20Demo-brightgreen?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![Lab Guide](https://img.shields.io/badge/📚%20Lab%20Guide-Read%20Docs-blue?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)
[![Open in Codespaces](https://img.shields.io/badge/Open%20in-GitHub%20Codespaces-black?style=for-the-badge&logo=github)](https://codespaces.new/7474/agent-lab-dotnet)

</div>

---

## What is this?

**Soc Ops** is a web-based Social Bingo game built with **Blazor + .NET 10**. Players mingle through a crowd looking for real people who match prompts on their card — _"Has visited more than 3 countries"_, _"Owns a houseplant"_, _"Wakes up before 6am"_ — then claim squares until someone shouts Bingo.

This repo also serves as a **hands-on GitHub Copilot agent lab**: you'll build and extend the game using AI-assisted development workflows, custom agents, and multi-agent collaboration in VS Code.

---

## 🧪 Lab Guide

Work through the lab at your own pace, in any language:

| Step | What you'll do |
|------|----------------|
| [**00 — Overview**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Understand the project and set up your checklist |
| [**01 — Setup & Context Engineering**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Wire up instructions files that shape Copilot's behaviour |
| [**02 — Design-First Frontend**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Use Pixel Jam agent to create a polished UI |
| [**03 — Custom Quiz Master**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Build a custom agent that generates bingo prompts |
| [**04 — Multi-Agent Development**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Orchestrate TDD Red → Green → Refactor with agents |

> 📝 Offline copies of every guide live in [`workshop/`](workshop/).

---

## 🚀 Getting started

**Prerequisite:** [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or higher.

### Option A — GitHub Codespaces (zero local setup)

1. Click **Use this template** → **Create a new repository**
2. Open your repo → **Code** → **Codespaces** → **Create codespace on main**
3. Wait for the devcontainer, then:

```bash
dotnet run --project SocOps/SocOps.csproj
```

### Option B — Run locally

```bash
git clone https://github.com/7474/agent-lab-dotnet
cd agent-lab-dotnet
dotnet run --project SocOps/SocOps.csproj
```

Open `https://localhost:5000` and start playing.

---

## 🏗 Tech stack

| Layer | Technology |
|-------|-----------|
| Frontend | Blazor WebAssembly |
| Runtime | .NET 10 |
| Hosting | GitHub Pages |
| AI tooling | GitHub Copilot + VS Code Agent Mode |

---

## Contributing

Contributions are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) for how to get involved.

Deploys automatically to GitHub Pages on push to `main`.
