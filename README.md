# Hi, I'm Carlos

Backend and ML infrastructure engineer from Rio de Janeiro, building production systems for 15+ years. These days that means GPU job scheduling, inference pipelines and LLM platforms, the plumbing that takes a model from a dev machine to something that runs all day without anyone babysitting it.

Some of the recent work, most of it in private repos:

- **Sortium** — Principal Engineer on a generative AI platform for game assets, diffusion-based PBR textures up to full 3D assets, running on a 16× RTX 4090 cluster behind a queue and scheduler I designed. Cut multi-material asset generation from about a minute to under 10 seconds.
- **Phood** — MLOps contract, took a custom computer-vision model from a single dev machine to reproducible container deployments on AWS GPU instances, with a CI/CD pipeline that ships it in minutes.
- **HealthForge** — founding engineer on a HIPAA-compliant telehealth platform, including an LLM gateway that masks patient data before any prompt reaches a model provider.

Before all that, 13 years at Dataprev, Brazil's federal IT company, from Java developer to managing a division of nearly 60 architects, and leading the R&D of bCPF, the permissioned blockchain that Receita Federal uses to share the CPF registry with 800+ government partners.

## Public projects

- [**micro-queue-starter**](https://github.com/jctosta/micro-queue-starter) — small GPU job scheduler in Python (FastAPI, Celery, Redis): one job per GPU, prefetch 1 with late acks, separate short and long queues, and a load test that shows why. The README explains each decision.
- [**skizo**](https://github.com/jctosta/skizo) — a small language for coding agents to sketch UIs, with a checker that reports every error in one pass, an offline preview and shadcn/React export. [Docs](https://jctosta.github.io/skizo/).
- [**toolbox**](https://github.com/jctosta/toolbox) — my Claude Code and pi plugins: a spec-first workflow, lint and prose quality gates, and a llama.cpp slot keeper for subagent calls.
- [**agent-inbox**](https://github.com/jctosta/agent-inbox) — a persistent inbox of what your coding agents are waiting on you for, shared between Claude Code and pi.

Stack I reach for: Python, Go, TypeScript and Rust, with Celery, Redis, PostgreSQL and SQLite on the backend, Azure and AWS for the cloud bits, and LiteLLM, Presidio, OpenCV and YOLO on the AI side.

Open to backend, ML infrastructure and applied AI roles, remote. Best way to reach me is [LinkedIn](https://www.linkedin.com/in/carlostosta/) or jctosta86@gmail.com.

Off the clock, I'm usually up for a Monster Hunter hunt on Steam (@astot).
