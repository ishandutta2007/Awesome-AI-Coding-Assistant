# Awesome-AI-Coding-Assistant

## Top AI Coding Assistant Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on AI Pair Programming, Inline Completion, Agentic Editing, Codebase Chat & Local/Private Coding Agents*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Coding Assistants**. These tools help developers write, edit, review, and understand code through autocomplete, chat, multi-file agents, and terminal-based pair programming.



**Examples** include GitHub Copilot, Cursor, Codeium / Windsurf (Devin Desktop), Tabnine, Sourcegraph Cody, JetBrains AI Assistant, Amazon Q Developer, Continue, and Replit AI (the category leaders).



**Open-source emphasis**: AI coding assistants have a vibrant open ecosystem. **Continue**, **Aider**, **Tabby**, **Cline**, and related projects let you bring your own models (including fully local via Ollama) and keep code private. This section is heavily expanded with these tools.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description & Key Focus | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[GitHub Copilot](https://github.com/features/copilot)** | Widely adopted AI pair programmer integrated across VS Code, JetBrains, Visual Studio, and Neovim. | **$10/month** ($100/year for Copilot Pro individual) | **Free Plan**: 2,000 code completions/month and 50 chat & agent requests/month (auto-model selection). |
| **[Cursor](https://cursor.com/)** | AI-native code editor built for agentic, multi-file editing and codebase-aware chat. | **$20/month** (Pro plan) / **₹649/month** (Cursor Start) | **Hobby Plan**: 14-day Pro trial (unlimited features), followed by 2,000 Tab completions/month & limited agent requests. |
| **[Codeium / Windsurf (Devin Desktop)](https://codeium.com/)** | AI coding assistant & agentic IDE with Cascade agent and multi-file workflows. | **$20/month** (Pro plan) | **Free Plan**: Unlimited Tab autocomplete & inline edits; light daily and weekly Cascade agent usage quotas. |
| **[Tabnine](https://www.tabnine.com/)** | AI code completion focused on privacy, team models, and on-premises / VPC deployments for regulated environments. | **$39/user/month** (Code Assistant plan, billed annually) | **90-Day Free Trial**: Full access to Code Assistant features, chat, and context engine during the 90 days (no permanent free tier). |
| **[Sourcegraph Cody](https://sourcegraph.com/cody)** | AI coding assistant with deep codebase context and search, leveraging Sourcegraph’s code intelligence. | **$19/user/month** (Enterprise Starter plan) | **30-Day Free Trial**: Full enterprise trial with code graph search and context-aware chat (individual free tier retired). |
| **[JetBrains AI Assistant](https://www.jetbrains.com/ai/)** | AI features integrated across the JetBrains IDE family (IntelliJ, PyCharm, WebStorm, etc.) for completion, chat, and refactoring. | **$10/month** ($100/year for AI Pro individual) | **30-Day Free Trial**: Full AI Pro access; **AI Free plan**: Unlimited local code completion + 3 cloud AI credits per 30 days. |
| **[Amazon Q Developer](https://aws.amazon.com/q/developer/)** | AWS-oriented AI coding assistant for completion, chat, security scans, and cloud transformation workflows. | **$19/user/month** (Pro tier) | **Free Tier**: 50 agentic requests/month, 1,000 lines of Java code transformation/month, and core IDE code suggestions. |
| **[Continue (cloud / enterprise options)](https://www.continue.dev/)** | Commercial hub, centralized configuration, and team governance built on the Continue coding agent. | **$10/developer/month** (Team / Hub plan) | **Free Forever**: Open-source core with unlimited local model/BYO-API usage; **14-Day Free Trial** for Team/Hub features. |
| **[Replit AI](https://replit.com/)** | AI assistance and autonomous Agent embedded in the Replit cloud IDE for building full-stack apps in the browser. | **$20/month** (Core plan, includes $20/mo AI credits) | **Starter Plan**: Free daily resetting Agent credits, basic AI completion, and 1 published app. |



## Open-Source GitHub Projects

- **[Continue](https://github.com/continuedev/continue)**  

  Open-source AI coding agent for VS Code and JetBrains — bring any model (cloud or local via Ollama/vLLM), customizable context providers, chat, edit, and autocomplete.



- **[Aider](https://github.com/Aider-AI/aider)**  

  Open-source AI pair programming in the terminal — edits your git repo with strong repo mapping, auto-commits, and multi-file changes.



- **[Tabby](https://github.com/TabbyML/tabby)**  

  Self-hosted AI coding assistant with a dedicated inference server — strong for teams that want on-prem fill-in-the-middle (FIM) completion.



- **[Cline and related VS Code agents](https://github.com/)**  

  Open agentic coding extensions that can plan, edit, and run commands inside the editor with configurable LLM backends.



- **[OpenCode and terminal coding agents](https://github.com/)**  

  Fast-growing open terminal-native coding agents that support many LLM providers and local models.



- **[Ollama + local model stacks](https://ollama.com/)**  

  Run open coding models locally and connect them to Continue, Aider, Tabby, or custom clients for fully private assistance.



- **[Sourcegraph Cody (open components)](https://github.com/sourcegraph/cody)**  

  Open portions of Cody and related code intelligence that can be self-hosted or extended.



- **[GPT-Pilot and autonomous coding experiments](https://github.com/)**  

  Open projects exploring more autonomous, multi-step software generation from high-level goals.



- **[Code completion open servers](https://github.com/)**  

  Self-hosted FIM and completion servers compatible with editor plugins for offline or air-gapped use.



- **[Awesome lists of coding agents](https://github.com/)**  

  Community-curated rankings and comparisons of open AI coding agents and IDE extensions.



### Additional Strong Open-Source Options

- **Continue + Ollama** for a private, model-flexible IDE assistant in VS Code/JetBrains.

- **Aider** for terminal-centric, git-native pair programming with clear commit history.

- **Tabby** when a team needs a shared self-hosted completion server.

- Combining local models with retrieval over your own codebase for better context without sending code to third parties.

- Using open agents in CI for automated refactor suggestions or test generation (with human review).

- Evaluating model licenses carefully when using open weights for commercial projects.



**Frameworks for building custom systems**: Run **Ollama** (or vLLM) locally, connect **Continue** in the IDE and/or **Aider** in the terminal, optionally add **Tabby** for team-wide completion, and keep all code and prompts on infrastructure you
