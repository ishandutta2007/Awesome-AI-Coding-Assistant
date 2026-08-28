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

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[GitHub Copilot](https://github.com/features/copilot)**  

  Widely adopted AI pair programmer integrated across VS Code, JetBrains, Neovim, and more — strong enterprise adoption and broad IDE coverage.



- **[Cursor](https://cursor.com/)**  

  AI-native code editor built for agentic, multi-file editing and codebase-aware chat — popular for refactoring and complex changes from natural language.



- **[Codeium / Windsurf (Devin Desktop)](https://codeium.com/)**  

  AI coding assistant and agentic IDE experience with a strong free tier and multi-file editing capabilities (branding evolved under Cognition).



- **[Tabnine](https://www.tabnine.com/)**  

  AI code completion focused on privacy, team models, and on-premises options for regulated environments.



- **[Sourcegraph Cody](https://sourcegraph.com/cody)**  

  AI coding assistant with deep codebase context and search, leveraging Sourcegraph’s code intelligence.



- **[JetBrains AI Assistant](https://www.jetbrains.com/ai/)**  

  AI features integrated across the JetBrains IDE family (IntelliJ, PyCharm, etc.) for completion, chat, and refactoring.



- **[Amazon Q Developer](https://aws.amazon.com/q/developer/)**  

  AWS-oriented AI coding assistant for completion, chat, and cloud development workflows.



- **[Continue (cloud / enterprise options)](https://www.continue.dev/)**  

  Commercial offerings and hosted options built on the open-source Continue coding agent.



- **[Replit AI](https://replit.com/)**  

  AI assistance embedded in the Replit cloud IDE for building and iterating on projects in the browser.



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
