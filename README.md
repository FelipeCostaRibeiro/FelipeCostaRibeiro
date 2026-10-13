🇺🇸 [English](README.md) | 🇧🇷 [Português](README.pt-BR.md)
# Hi, I'm Felipe 👋

**Software Developer** focused on back end and LLM-powered applications. Based in Rio Grande do Sul, Brazil.

I build APIs and data pipelines that connect LLMs to real business data, from semantic search with RAG to real-time chat services and AI agents that can safely use tools.

## 🛠️ What I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

- **Back end:** Python, FastAPI, REST APIs, WebSockets, asyncio, SQLAlchemy
- **Data & AI:** PostgreSQL + pgvector, Supabase, Retrieval-Augmented Generation (RAG), LLMs, tool calling / agents, streaming, intent classification
- **Security:** authentication, access control, rate/abuse protection, PII filtering with Microsoft Presidio, command-execution guardrails for AI agents
- **Tooling:** Docker, Git/GitHub, unit testing

## 🚀 Featured work

### [Desktop Assistant](https://github.com/FelipeCostaRibeiro/Desktop-Assistant) — in progress
A personal AI assistant that can run terminal commands on its own, with safety layers. Python backend + React/TypeScript frontend.
- **Adaptive reasoning:** every message is classified by tool calling into four complexity levels, and the level sets the model's reasoning effort to balance cost, speed and quality
- **Agent loop with tool calling:** the LLM can call a terminal tool over multiple steps, using each command's output (status, exit code, stdout, stderr) to decide what to do next
- **Safety policy:** destructive commands (`rm -r`, `sudo`, `git push --force`, `git reset --hard`, etc.) require user confirmation; execution is restricted to an allowed working directory, with timeouts and output truncation
- Async streaming responses, cross-platform shell (PowerShell on Windows, `/bin/sh` on Linux/macOS) and multi-model access through OpenRouter

`Python` `asyncio` `OpenAI SDK` `LangChain` `OpenRouter` `DeepSeek` `Pydantic` `React` `TypeScript` `Vite`

### AI Shopping Chatbot (RAG) — private repository
Built with a team for a real client during the TIC55 Residency (Unisinos / BRISA).
- Designed and implemented FastAPI endpoints, including a WebSocket chat route that streams user messages to the LLM
- Semantic product search over catalog chunks stored in PostgreSQL with pgvector (Supabase), routed by intent detection
- Admin panel API to read, update and reset the chatbot prompt
- Wrote unit tests; worked alongside the team on authentication, anti-abuse controls and sensitive-data filtering

*Source code is private (client project).*

### [Technical Drawing Automation App](https://github.com/FelipeCostaRibeiro/app-automacao-desenho-tecnico)
A calculation helper for technical drawing, built with Godot Engine (GDScript) while studying Industrial Technical Drawing.

### 3D CAD AI Assistant
Virtual assistant that runs SolidWorks macros (GDScript) through natural-language commands.

## 🎓 Education & certifications
- Associate Degree in Software Analysis and Development: Unisinos (in progress)
- Industrial Technical Drawing: SENAI-RS
- QUALIFIC.AÍ, Professional Qualification in Artificial Intelligence: SENAI-RS (180h)
- TIC55 Residency: UNISINOS / BRISA
- TOEIC certified (2025)

## 📫 Get in touch
- LinkedIn: [felipe-costa-ribeiro](https://www.linkedin.com/in/felipe-costa-ribeiro/)
- Email: felipecribeiro909@gmail.com
