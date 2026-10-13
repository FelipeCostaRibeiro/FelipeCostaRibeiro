# Olá, sou o Felipe 👋

**Desenvolvedor de Software** com foco em back end e aplicações com LLMs. Do Rio Grande do Sul, Brasil.


Construo APIs e pipelines de dados que conectam LLMs a dados reais de negócio, de busca semântica com RAG a serviços de chat em tempo real e agentes de IA que usam ferramentas com segurança.


## 🛠️ Com o que trabalho


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


- **Back end:** Python, FastAPI, APIs REST, WebSockets, asyncio, SQLAlchemy
- **Dados & IA:** PostgreSQL + pgvector, Supabase, Retrieval-Augmented Generation (RAG), LLMs, tool calling / agentes, streaming, classificação de intenção
- **Segurança:** autenticação, controle de acesso, proteção contra abuso/rate limiting, filtragem de PII com Microsoft Presidio, guardrails de execução de comandos para agentes de IA
- **Ferramentas:** Docker, Git/GitHub, testes unitários


## 🚀 Trabalhos em destaque


### [Desktop Assistant](https://github.com/FelipeCostaRibeiro/Desktop-Assistant) — em andamento
Um assistente de IA pessoal que executa comandos de terminal por conta própria, com camadas de segurança. Backend em Python + frontend em React/TypeScript.
- **Raciocínio adaptativo:** cada mensagem é classificada via tool calling em quatro níveis de complexidade, e o nível define o esforço de raciocínio do modelo para equilibrar custo, velocidade e qualidade
- **Loop de agente com tool calling:** a LLM pode chamar uma ferramenta de terminal em múltiplos passos, usando a saída de cada comando (status, exit code, stdout, stderr) para decidir o próximo passo
- **Política de segurança:** comandos destrutivos (`rm -r`, `sudo`, `git push --force`, `git reset --hard`, etc.) exigem confirmação do usuário; a execução é restrita a um diretório de trabalho permitido, com timeouts e truncamento de saída
- Respostas assíncronas em streaming, shell multiplataforma (PowerShell no Windows, `/bin/sh` no Linux/macOS) e acesso a múltiplos modelos via OpenRouter


`Python` `asyncio` `OpenAI SDK` `LangChain` `OpenRouter` `DeepSeek` `Pydantic` `React` `TypeScript` `Vite`


### Chatbot de Compras com IA (RAG) — repositório privado
Desenvolvido em equipe para um cliente real durante a Residência TIC55 (Unisinos / BRISA).
- Projetei e implementei endpoints FastAPI, incluindo uma rota de chat via WebSocket que transmite as mensagens do usuário para a LLM
- Busca semântica de produtos sobre chunks de catálogo armazenados no PostgreSQL com pgvector (Supabase), roteada por detecção de intenção
- API de painel administrativo para ler, atualizar e resetar o prompt do chatbot
- Escrevi testes unitários; atuei junto à equipe em autenticação, controles anti-abuso e filtragem de dados sensíveis


*Código-fonte privado (projeto de cliente).*


### [Aplicativo de Automação de Desenho Técnico](https://github.com/FelipeCostaRibeiro/app-automacao-desenho-tecnico)
Um auxiliar de cálculos para desenho técnico, construído com Godot Engine (GDScript) durante os estudos de Desenho Técnico Industrial.


### Assistente de IA para CAD 3D
Assistente virtual que executa macros do SolidWorks (GDScript) por meio de comandos em linguagem natural.


## 🎓 Formação & certificações
- Tecnólogo em Análise e Desenvolvimento de Software: Unisinos (em andamento)
- Desenho Técnico Industrial: SENAI-RS
- QUALIFIC.AÍ, Qualificação Profissional em Inteligência Artificial: SENAI-RS (180h)
- Residência TIC55: UNISINOS / BRISA
- Certificação TOEIC (2025)


## 📫 Contato
- LinkedIn: [felipe-costa-ribeiro](https://www.linkedin.com/in/felipe-costa-ribeiro/)
- Email: felipecribeiro909@gmail.com
