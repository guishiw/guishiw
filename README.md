<div align="center">
  <img src="./assets/hero.svg" width="100%" alt="Guishi Wang — AI Engineering, LLM Applications and Intelligent Systems" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=0EA5E9&center=true&vCenter=true&width=680&lines=Building+reliable+LLM+applications;Exploring+RAG%2C+agents+%26+document+intelligence;Turning+AI+ideas+into+useful+systems" alt="Typing introduction" />
</div>

<p align="center">
  <a href="https://github.com/guishiw?tab=followers"><img src="https://img.shields.io/github/followers/guishiw?label=Followers&style=flat&color=0EA5E9&labelColor=0F172A" alt="GitHub followers" /></a>
  <img src="https://komarev.com/ghpvc/?username=guishiw&label=Profile%20views&color=0EA5E9&style=flat" alt="Profile views" />
</p>

## 👋 About Me

Hi, I'm **Guishi Wang**. I build practical **AI systems** across LLM applications, retrieval, agent workflows, document intelligence, and computer vision. I care less about isolated demos and more about turning model capabilities into systems that are reusable, maintainable, and verifiable. I also contribute focused fixes to open-source projects, taking issues from root-cause analysis through regression coverage and compatibility checks.

- 🤖 Building LLM applications, model gateways, and agent workflows
- 🔎 Exploring Chinese semantic retrieval, reranking, and document intelligence
- 👁️ Applying computer vision to object detection, similarity, and image understanding
- 🧱 Engineering for reliability, observability, and clear system boundaries
- 🛠️ Contributing regression-tested fixes across AI tooling, runtimes, compilers, databases, and developer infrastructure

## 🧭 Capability Architecture

```text
AI Applications
   │
   ├── LLM Gateway       routing · rate limits · resilience · audit
   ├── Knowledge & RAG   embeddings · retrieval · reranking
   ├── Agents & Skills   tool use · workflows · reusable capabilities
   └── Vision & Docs     parsing · similarity · object detection
   │
   ▼
Engineering Systems
   │
   ├── Services          FastAPI · Next.js · Java
   ├── Data & Runtime    MySQL · Redis · vector stores · Docker
   └── Operations        observability · security · maintainability
   │
   ▼
Applied Scenarios
       knowledge work · procurement & compliance · developer productivity
```

## 🚀 Featured Projects

- **[Guishi-Skills](https://github.com/guishiw/Guishi-Skills)** — A growing collection of reusable Codex skills for data analysis, publishing, presentations, research, and codebase understanding.
- **[model-switch](https://github.com/guishiw/model-switch)** — An OpenAI-compatible LLM gateway with multi-provider routing, rate limiting, circuit breaking, queues, auditing, and an admin console.
- **[terms-rag](https://github.com/guishiw/terms-rag)** — An offline RAG system for Chinese tender clauses, powered by BGE embeddings, reranking, ChromaDB, and FastAPI.

## 🧩 Recent Open Source Work

Lately, I've been contributing focused fixes across AI tooling, runtimes, language tooling, databases, and developer infrastructure. I usually start from the root cause, keep the implementation narrow, and validate the concurrency, compatibility, security, or performance edge cases around it.

- **Distributed reliability & media pipelines** — implemented Redis-leased global task slots, atomic repair of corrupted video caches, and consistent enum defaults in MoneyPrinterTurbo ([#1742](https://github.com/harry0703/MoneyPrinterTurbo/pull/1742), [#1743](https://github.com/harry0703/MoneyPrinterTurbo/pull/1743), [#1744](https://github.com/harry0703/MoneyPrinterTurbo/pull/1744)); fixed Electron edge cases around failed upload streams and pre-aborted message boxes ([#55520](https://github.com/electron/electron/pull/55520), [#55519](https://github.com/electron/electron/pull/55519)).
- **AI model & runtime compatibility** — improved InvokeAI calibration retry isolation and LoRA/LyCORIS handling for DoRA, Diffusers Anima, and factorized layouts ([#10077](https://github.com/invoke-ai/InvokeAI/pull/10077), [#10075](https://github.com/invoke-ai/InvokeAI/pull/10075), [#10076](https://github.com/invoke-ai/InvokeAI/pull/10076), [#10060](https://github.com/invoke-ai/InvokeAI/pull/10060)); fixed Codex routing, reasoning-effort, output-token, and usage-metering behavior in cc-switch ([#8998](https://github.com/farion1231/cc-switch/pull/8998), [#8999](https://github.com/farion1231/cc-switch/pull/8999), [#9001](https://github.com/farion1231/cc-switch/pull/9001)).
- **Compilers, SDKs & type systems** — corrected async policy chains and emitter option/server parameter handling in TypeSpec ([#12448](https://github.com/microsoft/typespec/pull/12448), [#12447](https://github.com/microsoft/typespec/pull/12447), [#12446](https://github.com/microsoft/typespec/pull/12446)); fixed cross-namespace models, binary response types, and nullable enum generation in Kiota ([#8517](https://github.com/microsoft/kiota/pull/8517), [#8516](https://github.com/microsoft/kiota/pull/8516), [#8515](https://github.com/microsoft/kiota/pull/8515)); and repaired narrowing and generator-expression behavior in Pyright ([#11952](https://github.com/microsoft/pyright/pull/11952), [#11951](https://github.com/microsoft/pyright/pull/11951), [#11950](https://github.com/microsoft/pyright/pull/11950)).
- **Developer tools & data platforms** — isolated ECC observer scopes, removed duplicate Git status work, and reduced hook false positives ([#3817](https://github.com/affaan-m/ECC/pull/3817), [#3818](https://github.com/affaan-m/ECC/pull/3818), [#3819](https://github.com/affaan-m/ECC/pull/3819)); added Unicode SQL, wrapped ClickHouse type, and PostgreSQL partition fixes to DBeaver ([#42637](https://github.com/dbeaver/dbeaver/pull/42637), [#42638](https://github.com/dbeaver/dbeaver/pull/42638), [#42639](https://github.com/dbeaver/dbeaver/pull/42639)); and contributed targeted fixes to [Playwright](https://github.com/microsoft/playwright/pulls?q=is%3Apr+author%3Aguishiw), [RustDesk](https://github.com/rustdesk/rustdesk/pulls?q=is%3Apr+author%3Aguishiw), [Neovim](https://github.com/neovim/neovim/pulls?q=is%3Apr+author%3Aguishiw), and [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/pulls?q=is%3Apr+author%3Aguishiw).

<p align="center">
  <a href="https://github.com/pulls?q=is%3Apr+author%3Aguishiw"><strong>View all pull requests →</strong></a>
</p>

## 🧰 Tech Stack

### Languages

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827" alt="JavaScript" />
</p>

### AI, Backend & Infrastructure

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=111827" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

## 📊 GitHub Stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=guishiw&amp;show_icons=true&amp;hide_border=true&amp;theme=github_dark&amp;rank_icon=github" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=guishiw&amp;show_icons=true&amp;hide_border=true&amp;theme=default&amp;rank_icon=github" />
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=guishiw&amp;show_icons=true&amp;hide_border=true&amp;theme=default&amp;rank_icon=github" alt="Guishi Wang's GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=guishiw&amp;layout=compact&amp;hide_border=true&amp;theme=github_dark&amp;langs_count=8" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=guishiw&amp;layout=compact&amp;hide_border=true&amp;theme=default&amp;langs_count=8" />
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=guishiw&amp;layout=compact&amp;hide_border=true&amp;theme=default&amp;langs_count=8" alt="Guishi Wang's top languages" />
  </picture>
</p>

## 🤝 Let's Connect

If you are interested in **LLM engineering, RAG, agents, document intelligence, or computer vision**, feel free to connect and exchange ideas through GitHub.

<p>
  <a href="https://github.com/guishiw"><img src="https://img.shields.io/badge/GitHub-guishiw-181717?style=for-the-badge&logo=github" alt="GitHub profile" /></a>
</p>

<div align="center">
  <sub>Build useful things. Keep learning. Stay curious.</sub>
</div>
