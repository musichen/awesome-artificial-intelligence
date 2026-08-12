# Awesome Artificial Intelligence

An opinionated, actively maintained collection of resources for software developers learning to build and ship generative AI and agentic systems.

![Artificial intelligence](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGtqbWIxYXJxNmphN2l2d2F5ZWZjdjd1YWF0cmN5OGwxYmd0eHlkbCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/ABVK96HgZvWI9SBbXr/giphy.gif)

This list is for developers who want to:

- understand the foundations behind modern AI systems;
- build applications with language models, retrieval, tools, and agents;
- evaluate, observe, and deploy AI systems in production;
- use coding agents to improve software engineering work.

This is not a comprehensive directory of AI products. Every entry must clear an absolute quality bar for technical depth, practical value, evidence, and distinctiveness. Categories are not quotas, and a short category is better than one padded with weak choices.

The list is reviewed weekly by an evidence-backed automation that independently reviews, validates, and merges small changes. See [how resources are evaluated](CURATION.md).

## Learn

### Books

- [Artificial Intelligence: A Modern Approach](https://aima.cs.berkeley.edu/): The broad reference for classical AI, including search, reasoning, planning, learning, and robotics.
- [Reinforcement Learning: An Introduction](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf): Sutton and Barto's foundational treatment of reinforcement learning concepts and algorithms.
- [Machine Learning Bookcamp](https://www.manning.com/books/machine-learning-bookcamp): A project-based introduction to building and deploying machine learning systems by Alexey Grigorev.
- [Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/): Scalable, maintainable machine learning systems by Chip Huyen.
- [AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/): Building applications with foundation models by Chip Huyen.
- [Build a Large Language Model from Scratch](https://www.manning.com/books/build-a-large-language-model-from-scratch): Implement transformers in PyTorch with Sebastian Raschka.
- [Hands-On Large Language Models](https://www.llm-book.com/): A visual and practical guide by Jay Alammar and Maarten Grootendorst.
- [LLM Engineer's Handbook](https://www.packtpub.com/en-us/product/llm-engineers-handbook-9781836200079): LLMOps, fine-tuning, serving, and production workflows.
- [The 100-Page Language Models Book](https://www.thelmbook.com/): A concise, technical introduction by Andriy Burkov.
- [Deep Learning](https://www.deeplearningbook.org/): Mathematical foundations by Ian Goodfellow, Yoshua Bengio, and Aaron Courville.
- [Deep Learning: Foundations and Concepts](https://www.bishopbook.com/): A probability-grounded treatment by Christopher and Hugh Bishop.
- [Understanding Deep Learning](https://udlbook.github.io/udlbook/): Theory, intuition, and practical notebooks by Simon Prince.
- [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/): The continuously updated NLP reference by Dan Jurafsky and James Martin.

### Courses

- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/chapter1/1): Transformers, fine-tuning, datasets, and modern NLP tooling.
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/): The full lifecycle of building and shipping AI products.
- [Fast.ai Practical Deep Learning](https://course.fast.ai/): A code-first introduction to deep learning.
- [Karpathy's Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ): Build neural networks and language models from first principles.
- [Stanford CS336: Language Modeling from Scratch](https://cs336.stanford.edu/): Build language models from data preparation through evaluation and deployment.
- [MIT 6.S191: Introduction to Deep Learning](https://introtodeeplearning.com/): Deep learning foundations and applications.
- [Google Generative AI Learning Path](https://www.cloudskillsboost.google/paths/118): An introductory path through generative AI concepts and Google Cloud tooling.
- [DeepLearning.AI Short Courses](https://learn.deeplearning.ai/): Focused courses on current generative AI engineering techniques.
- [Made With ML](https://madewithml.com/): An open course on designing, developing, deploying, and iterating on production ML systems.

### Foundational papers

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762): Introduced the Transformer architecture.
- [Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361): Explored relationships between model performance, data, and compute.
- [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556): Showed how model size and training data should scale together under a compute budget.
- [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165): Demonstrated in-context learning at scale.
- [Retrieval-Augmented Generation](https://arxiv.org/abs/2005.11401): Combined parametric language models with external retrieval for knowledge-intensive tasks.
- [LoRA](https://arxiv.org/abs/2106.09685): Introduced low-rank adaptation for parameter-efficient model fine-tuning.
- [Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155): Established the instruction tuning and RLHF recipe used by InstructGPT.
- [ReAct](https://arxiv.org/abs/2210.03629): Combined reasoning traces with actions for tool-using language-model agents.
- [Constitutional AI](https://arxiv.org/abs/2212.08073): A method for training helpful and harmless AI assistants using written principles.
- [Direct Preference Optimization](https://arxiv.org/abs/2305.18290): Reframed preference alignment as a simple classification objective without explicit reward modelling.

## Build AI systems

### Guides and playbooks

- [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents): Anthropic's practical patterns and tradeoffs for agentic systems.
- [A Practical Guide to Building Agents](https://cdn.openai.com/business-guides-and-resources/a-practical-guide-to-building-agents.pdf): OpenAI's guide to models, tools, instructions, orchestration, and guardrails.

### LLM application engineering

- [OpenAI Cookbook](https://cookbook.openai.com/): Code examples for structured outputs, tool use, retrieval, evals, and other LLM application patterns.
- [Anthropic Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview): Techniques for defining success criteria, testing prompts, and improving model behaviour.
- [Effective Context Engineering for AI Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents): How to select, structure, and manage the context available to long-running agents.
- [12-Factor Agents](https://github.com/humanlayer/12-factor-agents): Practical principles for building controllable LLM applications around deterministic software.
- [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/): Risks and mitigations for developing and deploying generative AI applications.

### Protocols and interoperability

- [Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28): The open specification for connecting AI applications to external tools, data sources, prompts, and interactive apps.
- [Agent2Agent Protocol](https://a2a-protocol.org/latest/specification/): A vendor-neutral specification for agent discovery, task delegation, streaming, asynchronous updates, and cross-platform communication.
- [Agent Skills](https://agentskills.io/specification): An open specification for defining and sharing agent skills, enabling portable capabilities across coding agents.

### Codebase documentation

- [Google CodeWiki](https://codewiki.google): An AI-powered codebase documentation tool that generates and maintains living documentation from source code.

### Agent frameworks

- [Pydantic AI](https://ai.pydantic.dev/): Typed agent development built around Pydantic.
- [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview): Low-level orchestration for long-running, stateful agents.
- [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/): A small SDK for tools, handoffs, guardrails, tracing, and agent orchestration.
- [Google Agent Development Kit](https://google.github.io/adk-docs/): Google's framework for developing and evaluating agents.
- [Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/overview/): Microsoft's successor to AutoGen and Semantic Kernel for agents and graph-based workflows.

### Durable and asynchronous agents

- [Effective Harnesses for Long-Running Agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents): Patterns for agents that make progress across multiple context windows and recover from failure.
- [Running Agents](https://openai.github.io/openai-agents-python/running_agents/): Lifecycle, session, exception, and durable-execution patterns in the OpenAI Agents SDK.
- [Human-in-the-Loop](https://openai.github.io/openai-agents-python/human_in_the_loop/): Pause, inspect, approve, reject, and resume tool calls without losing agent state.
- [Gemini and Temporal Durable Agent](https://ai.google.dev/gemini-api/docs/temporal-example): A concrete implementation of durable execution, retries, and human approval for an agent workflow.

### Retrieval and data

- [LlamaIndex](https://docs.llamaindex.ai/): Data ingestion, indexing, retrieval, and agent workflows.
- [Haystack](https://docs.haystack.deepset.ai/): Modular pipelines for retrieval and generative AI applications.
- [Docling](https://github.com/docling-project/docling): Document parsing and conversion for AI applications.

### Agent memory systems

Memory and context persistence layers for AI agents, spanning local SQLite stores, knowledge graphs, and cloud platforms.

- [Holographic](https://vectorize.io/articles/hermes-agent-memory-explained): Hermes' built-in local-first memory with SQLite, FTS5 full-text search, trust scoring, and HRR algebra, requiring no API keys or external services.
- [Hindsight](https://github.com/vectorize-io/hindsight): An advanced agent memory system with a knowledge graph, entity resolution, multi-strategy retrieval, reflection, and synthesis, supporting local embedded PostgreSQL.
- [Mem0](https://github.com/mem0ai/mem0): A universal memory layer for AI agents with user, session, and agent memory, personalization, semantic retrieval, and broad SDK integrations.
- [Zep](https://github.com/getzep/zep): An end-to-end context engineering platform for agents with memory, knowledge graphs, and retrieval.
- [Letta](https://github.com/letta-ai/letta): A platform for building stateful agents with advanced memory that can learn and self-improve over time.
- [Cognee](https://github.com/topoteretes/cognee): A knowledge engine for AI agent memory with graph-based retrieval in a few lines of code.
- [Claude Mem](https://github.com/thedotmack/claude-mem): A memory system for Claude Code and other coding agents with search, corpora, and knowledge graph capabilities.
- [MemPalace](https://github.com/MemPalace/mempalace): A high-scoring AI memory system with semantic search, knowledge graph, and cross-wing knowledge organisation.
- [OpenClaw Memory](https://docs.openclaw.ai/concepts/memory): OpenClaw's native built-in memory with quick memory dump, Honcho integration, and memory search.
- [OpenViking](https://github.com/volcengine/OpenViking): A self-hosted context database for agents using structured hierarchy, tiered memory loading, and a viking://-style knowledge filesystem.
- [Logseq](https://github.com/logseq/logseq): A privacy-first, open-source knowledge management and collaboration platform useful as an agent knowledge base frontend.

### LLM knowledge bases

Techniques and tools for using LLMs to build, maintain, and query personal knowledge bases from source documents, papers, and repos.

- [Karpathy's LLM Wiki Pattern](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f): A method for building and querying personal knowledge bases by using LLMs to compile markdown wikis from source documents, with Obsidian as the frontend.
- [LLM Wiki](https://github.com/nashsu/llm_wiki): An implementation of the Karpathy pattern for LLM-driven knowledge base construction and maintenance.
- [Any to Markdown](https://any-to-markdown.com): A tool for converting web articles, documents, and other formats to markdown for LLM knowledge base ingestion.

### Codebase graph and structural understanding

Tools that parse repositories into queryable knowledge graphs, giving AI coding agents and developers a shared structural mental model of large codebases.

- [Graphify](https://github.com/Graphify-Labs/graphify): Open-source local knowledge-graph skill with tree-sitter AST parsing across 36 languages, god-node detection, community clustering, and MCP integration.
- [GitNexus](https://github.com/abhigyanpatwari/GitNexus): A zero-server code intelligence engine with Leiden community clustering, execution-flow tracing, 17 MCP tools, and built-in GraphRAG chat.
- [Codebase Memory MCP](https://github.com/DeusData/codebase-memory-mcp): A persistent structural code knowledge graph with tree-sitter parsing, caller and callee path queries, embedded 3D graph visualization, and MCP integration.
- [Code Review Graph](https://github.com/tirth8205/code-review-graph): A local-first tree-sitter knowledge graph in SQLite with blast-radius analysis, MCP, and a GitHub Action for PR review comments.
- [Understand Anything](https://github.com/Egonex-AI/Understand-Anything): A multi-agent and static-analysis pipeline for building interactive dependency graphs of files, functions, and classes in unfamiliar repositories.
- [CodeGraph](https://github.com/colbymchenry/codegraph): A high-performance pre-indexed code knowledge graph in Rust with auto-sync, MCP, call paths, and blast-radius analysis.
- [Graphiti](https://github.com/getzep/graphiti): A temporal knowledge-graph infrastructure for AI agents, combining source code, commits, sessions, and decisions over time.
- [dependency-cruiser](https://github.com/sverweij/dependency-cruiser): Validates and visualizes JavaScript and TypeScript module dependencies against custom rules, with DOT, SVG, and Mermaid graph output.
- [Madge](https://github.com/pahen/madge): A developer utility for generating visual module dependency graphs and detecting circular references in JavaScript and TypeScript projects.
- [Joern](https://github.com/joernio/joern): A mature Code Property Graph engine combining AST, data-flow, control-flow, and call information for deep structural analysis.
- [Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail): The classic interactive source-code graph explorer and navigator, archived but still an important UX reference for codebase visualisation.
- [Codeflow](https://github.com/braedonsaunders/codeflow): A browser-only architecture map from GitHub URLs or local files with blast-radius and ownership views.
- [CodeCharta](https://github.com/MaibornWolff/codecharta): An open-source 3D code city visualisation from static analysis metrics, rendering architecture, hotspots, and technical debt interactively.
- [RepoWise](https://github.com/repowise-dev/repowise): A self-hostable codebase intelligence platform with tree-sitter graphs, git analytics, auto-wiki, code health, dead-code detection, and MCP tools.
- [Neo4j LLM Graph Builder](https://github.com/neo4j-labs/llm-graph-builder): A generic documents-to-knowledge-graph system useful for combining source code, documentation, and tickets into one project graph.
- [Code2flow](https://github.com/scottrogowski/code2flow): Generates function and call graphs from source code for execution-flow understanding.
- [Emerge](https://github.com/glato/emerge): A browser-based interactive codebase and dependency visualisation tool for multiple languages with code-quality and graph metrics.
- [GRASP](https://github.com/ashfordeOU/grasp): An architecture and code intelligence system with dependency graphs, knowledge graphs, git change-impact analysis, ORM relationships, and MCP integration.
- [Code-Graph-RAG](https://github.com/vitali87/code-graph-rag): A Tree-sitter and Memgraph repository knowledge graph with GraphRAG, combining deterministic static analysis with semantic AI reasoning.
- [RepoGraph](https://github.com/ozyyshr/RepoGraph): A research-oriented repository graph designed to give AI software-engineering agents repo-level structural context.
- [RepoBrain](https://github.com/study8677/repobrain): A persistent codebase intelligence layer targeting Claude Code, Cursor, Codex, Windsurf, and similar agents.
- [Cortex](https://github.com/pedropacheco95/cortex): A Tree-sitter and TypeScript knowledge graph for persistent repository understanding, preventing agents from rediscovering structure every session.
- [CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext): An MCP server and CLI with tree-sitter and SCIP indexing into a graph database, queryable by AI coding assistants.
- [CodeGraphMCPServer](https://github.com/nahisaho/CodeGraphMCPServer): A lightweight zero-config MCP server with tree-sitter graphs and GraphRAG community detection.
- [Arkit](https://github.com/dyatko/arkit): A static analysis tool generating architecture diagrams in SVG, PNG, and PlantUML for JavaScript, TypeScript, Vue, and Nuxt projects.
- [Gephi](https://github.com/gephi/gephi): An open-source graph visualisation and interactive network analysis platform for complex dataset mapping.

### Evals and reliability

- [Demystifying Evals for AI Agents](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents): A practical method for building task suites, graders, transcripts, and evaluation harnesses.
- [OpenAI Evals](https://github.com/openai/evals): An open-source framework and registry for evaluating language models and systems.
- [Promptfoo](https://www.promptfoo.dev/docs/): Test cases, assertions, model comparisons, and red-team checks for LLM applications.
- [Ragas](https://docs.ragas.io/): Evaluation and experimentation for retrieval and generative AI applications.

### Deployment and observability

- [Langfuse](https://langfuse.com/docs): Tracing, evaluation, prompt management, and metrics for LLM applications.
- [vLLM](https://docs.vllm.ai/): An inference and serving engine for language models.
- [LiteLLM](https://docs.litellm.ai/): A model gateway and unified interface for multiple model providers.

### Speech and audio

- [FunASR](https://github.com/modelscope/FunASR): Speech recognition toolkit with streaming ASR, VAD, punctuation, speaker diarization, and OpenAI-compatible serving for voice AI applications.

## Agentic software engineering

Coding agents help developers plan, implement, review, test, and debug software. For independent capability comparisons, see [SWE-bench](https://www.swebench.com/) and [Terminal-Bench](https://www.tbench.ai/leaderboard/terminal-bench/2.1).

### Coding agents

- [Claude Code](https://code.claude.com/): A terminal agent with hooks, subagents, skills, and repository-level instructions.
- [Codex CLI](https://github.com/openai/codex): An open-source terminal agent with sandbox and approval controls.
- [Gemini CLI](https://github.com/google-gemini/gemini-cli): An open-source terminal agent built around Gemini and extensible tools.
- [Cursor CLI](https://cursor.com/cli): A terminal agent connected to Cursor's editor and cloud workflows.
- [GitHub Copilot coding agent](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent): An asynchronous agent that works from GitHub issues and opens pull requests.
- [Aider](https://aider.chat/): An open-source pair programmer with Git integration and broad model support.
- [OpenCode](https://opencode.ai/): An open-source, provider-independent terminal agent with a client-server architecture.
- [OpenHands](https://docs.all-hands.dev/): An open-source platform for running software development agents locally or in the cloud.
- [Cline](https://github.com/cline/cline): An open-source coding agent available as an editor extension, CLI, and SDK.
- [Continue](https://www.continue.dev/): Open-source coding agents for IDE and CI workflows with source-controlled configuration.
- [Pi](https://pi.dev): A terminal coding agent with an open extension system, subagents, PTY emulation, and multi-agent coordination.
- [OpenHuman](https://github.com/tinyhumansai/openhuman): An open-source agent from TinyHumans designed for autonomous task execution and coding workflows.
- [Hermes Agent](https://github.com/nousresearch/hermes-agent): An open-source terminal agent from Nous Research with built-in memory, plugins, a web dashboard, and extensive community resources.
- [ElizaOS](https://github.com/elizaOS/eliza): An agentic operating system and framework for building, deploying, and managing autonomous AI agents.
- [Goose](https://github.com/aaif-goose/goose): Block's open-source local agent with desktop and CLI modes, MCP tools, coding, automation, and research capabilities.
- [Qwen Code](https://github.com/QwenLM/qwen-code): Alibaba's terminal coding agent optimised for Qwen-Coder with large codebase understanding and shell tools.
- [Roo Code](https://github.com/RooCodeInc/Roo-Code): A Cline-family editor agent with Code, Architect, Ask, Debug, and Orchestrator modes for multi-agent-style workflows.
- [Kilo Code](https://github.com/kilo-org/kilocode): An agentic engineering platform with CLI and editor modes, Architect and Orchestrator roles, and an MCP marketplace.
- [Tabby](https://github.com/TabbyML/tabby): A self-hosted open-source coding assistant with private autocomplete and chat for enterprise and local codebases.
- [Kimi Code CLI](https://github.com/MoonshotAI/kimi-cli): Moonshot's terminal coding agent with code edits, shell commands, web search, and planning workflows.
- [Mistral Vibe](https://github.com/mistralai/mistral-vibe): Mistral's lightweight CLI coding assistant for terminal workflows with Mistral models.
- [DeepSeek Deep Code](https://github.com/lessweb/deepcode-cli): A DeepSeek-focused terminal coding assistant for reasoning-heavy code tasks and shell operations.
- [DeepSeek-TUI](https://github.com/Hmbown/DeepSeek-TUI): A DeepSeek-first terminal TUI agent with shell, file edits, git, web search, MCP, and sub-agent features.
- [VT Code](https://github.com/vinhnx/vtcode): A Rust semantic terminal coding agent with Tree-sitter, ast-grep, shell safety, multi-provider fallback, and Zed ACP integration.
- [crow](https://github.com/crow-cli/crow-cli): A minimal ACP-native Python coding agent serving as a reference implementation for the Agent Client Protocol architecture.
- [Kobolds Agent](https://kobolds.run): A lightweight coding agent built with Bun, Elysia, and Pi Agent Core.

### Coding agent extensions

Extensions and plugins that extend coding agents with additional tools, workflows, and integrations. These examples from the Pi extension ecosystem are installable via `pi install`.

- [pi-interactive-shell](https://pi.dev/packages/pi-interactive-shell): Run interactive CLIs in an observable overlay with full PTY emulation and user takeover.
- [pi-subagents](https://pi.dev/packages/pi-subagents): Delegate to child agents with chains, parallel execution, and async dispatch.
- [pi-messenger](https://pi.dev/packages/pi-messenger): Multi-agent coordination through the filesystem with task claiming, file reservation, and messaging.
- [pi-intercom](https://pi.dev/packages/pi-intercom): Direct one-to-one messaging between Pi sessions on the same machine.
- [pi-mcp-adapter](https://pi.dev/packages/pi-mcp-adapter): A single proxy tool that discovers MCP servers on demand instead of loading all tool definitions upfront.
- [pi-web-access](https://pi.dev/packages/pi-web-access): Web search and content extraction with Chrome cookies, Perplexity, or Gemini API backends.
- [pi-boomerang](https://pi.dev/packages/pi-boomerang): Token-efficient task execution with automatic context collapse.
- [pi-prompt-template-model](https://pi.dev/packages/pi-prompt-template-model): Prompt templates with model, skill, and thinking frontmatter that auto-switch and inject skills.
- [pi-design-deck](https://pi.dev/packages/pi-design-deck): Multi-slide visual decision decks in the browser for comparing code, diagrams, and UI mockups.
- [pi-powerline-footer](https://pi.dev/packages/pi-powerline-footer): Powerline-style status bar with token usage, cost, model, and thinking level.
- [pi-rewind-hook](https://pi.dev/packages/pi-rewind-hook): Git-backed checkpoints for AI coding sessions with file state browsing and restore.
- [pi-annotate](https://pi.dev/packages/pi-annotate): Visual annotation mode for Chrome with CSS selectors and box model information.
- [pi-model-switch](https://pi.dev/packages/pi-model-switch): Lets the agent switch its own model mid-session.
- [pi-skill-palette](https://pi.dev/packages/pi-skill-palette): Command palette for selecting which skill to inject with the next message.
- [pi-discord](https://pi.dev/packages/pi-discord): Discord bot for Pi with persistent sessions per channel, slash commands, and full tool access.
- [pi-side-chat](https://pi.dev/packages/pi-side-chat): Fork conversations into side chats while the main agent keeps working.
- [surf-cli](https://pi.dev/packages/surf-cli): A CLI for controlling Chrome from any agent, with screenshots, navigation, and element interaction.
- [visual-explainer](https://pi.dev/packages/visual-explainer): An agent skill that generates rich HTML pages for visual diff reviews, architecture overviews, and data tables.

### Software factories and agent orchestration

- [Harness Engineering](https://openai.com/index/harness-engineering/): OpenAI's field report on building software with coding agents, repository constraints, automated checks, and human steering.
- [Codex Orchestration with Symphony](https://openai.com/index/open-source-codex-orchestration-symphony/): A reference architecture that turns project work into isolated, observable coding-agent runs.
- [How We Built Our Multi-Agent Research System](https://www.anthropic.com/engineering/multi-agent-research-system): Production lessons on orchestrator-worker agents, parallel search, evaluation, and operational reliability.

### Agentic development environments (ADEs)

Desktop and terminal workspaces for running, supervising, and coordinating one or more coding agents.

- [Orca](https://github.com/stablyai/orca): A desktop fleet orchestrator for running many CLI agents in isolated Git worktrees across repositories.
- [Superset](https://github.com/superset-sh/superset): An Electron coding-agent workspace with parallel CLI agents, worktrees, terminals, editor panes, diff review, ACP, and local persistence.
- [Coder Mux](https://github.com/coder/mux): An AGPL Electron multiplexer with local worktrees, SSH and remote environments, ACP, multi-model routing, and its own coding-agent loop.
- [AionUi](https://github.com/iOfficeAI/AionUi): A cross-platform desktop interface for Gemini, Claude Code, Codex, OpenCode, Hermes, Cursor, and other agents, with automation and remote access.
- [OpenHands Agent Canvas](https://github.com/OpenHands/agent-canvas): A self-hosted multi-agent web workspace backed by an agent server for running and supervising coding agents from one platform.
- [Yolium Desktop](https://github.com/cpotech/yolium-desktop): An MIT Electron orchestrator using Docker and worktrees for Plan, Code, Verify, and specialist agents, with memory, scheduling, Kanban, and cost tracking.
- [Klaussy Desktop](https://github.com/steph-dove/klaussy-desktop): A multi-agent Electron workspace with worktree isolation, multi-repo sessions, commit review gates, and structured cross-agent handoffs.
- [Xuanpu](https://github.com/slicenferqin/xuanpu): An MIT Electron agent workbench with structured event capture, layered memory, automatic field-context injection, checkpoints, and a planned context protocol.
- [Parallel Code](https://github.com/johannesjo/parallel-code): An MIT Electron and SolidJS app for running Claude, Codex, and Gemini side by side in isolated worktrees with Monaco, terminals, and diff review.
- [OpenCovibe](https://github.com/AnyiWang/OpenCovibe): A Tauri and Svelte desktop cockpit that wraps existing coding agents and provides session history, visual tool cards, diffs, replay, and provider switching.
- [Nimbalyst](https://github.com/Nimbalyst/nimbalyst): An agent-neutral Electron workspace for Claude, Codex, OpenCode, and Copilot with visual editing, tasks, session management, and ACP support.
- [Crystal](https://github.com/stravu/crystal): An MIT Electron manager for multiple Claude Code and Codex instances using Git worktrees, persistent sessions, terminals, and local review workflows.
- [OpenCove](https://github.com/DeadWaveWave/opencove): An Electron infinite-canvas workspace that organizes agents, terminals, tasks, files, notes, and knowledge spatially.
- [Simple Code GUI](https://github.com/DonutsDelivery/simple-code-gui): A desktop manager for discovering, resuming, and organizing Claude, Gemini, Codex, and OpenCode sessions across projects.
- [Claude Squad](https://github.com/smtg-ai/claude-squad): A TUI for running Claude Code, Codex, Gemini, OpenCode, and similar agents in parallel tmux sessions and Git worktrees.
- [Agents Deck](https://agents-deck.com): A TUI-oriented dashboard for supervising many Claude, Codex, Cursor, Kimi, and multi-repository agent sessions.
- [Claude Deck](https://claudedeck.org): A local command centre for Claude Code and Codex configuration, reusable agent teams, context requests, and handoffs.
- [Herdr](https://herdr.dev): A terminal-first agent command centre that detects active CLI agents, tracks working, idle, and blocked states, and helps users supervise many persistent sessions.
- [Wave Terminal](https://github.com/wavetermdev/waveterm): An Apache-2.0 Electron AI-native terminal with xterm, Monaco, rich blocks, remote workflows, and extensible workspace panes.
- [TUICommander](https://github.com/sstraus/tuicommander): A Tauri, Rust, and SolidJS terminal workspace with sessions, Git, editor tools, MCP, automation, and multi-agent foundations.
- [Zellij](https://github.com/zellij-org/zellij): A terminal workspace and multiplexer with batteries included, widely used in agent workflows.
- [Control Deck](https://ctrldeck.dev): A terminal workspace that works with the agent CLIs you already run, competing in the same space as Orca.
- [Codefleet](https://codefleet.app): A desktop workspace for coordinating coding agents across projects and sessions.
- [Toad](https://github.com/batrachianai/toad): A unified terminal UI for coding agents using Agent Client Protocol, controlling Claude, Codex, Gemini, OpenHands, and others from one TUI.
- [Agent Deck](https://github.com/asheshgoplani/agent-deck): A tmux-based terminal session manager for AI coding agents with grouping, search, notifications, git worktrees, and session switching.
- [Agent of Empires](https://github.com/njbrake/agent-of-empires): A Linux and macOS session manager for AI coding agents with a TUI, web dashboard, tmux, Docker sandboxing, and git worktrees.
- [1Code](https://github.com/21st-dev/1code): An open-source coding agent client for running Claude Code, Codex, and similar agents locally or in the cloud with worktree-based background runs.
- [Vibe Kanban](https://github.com/BloopAI/vibe-kanban): An agent workspace and task board with per-workspace branches, terminals, dev servers, diff review, and built-in browser preview.

### Agent forks and derivatives

Lightweight reimplementations and variants of popular coding agents, targeting specific platforms or resource constraints.

- [PicoClaw](https://picoclaw.io): An independent Go reimplementation of OpenClaw by Sipeed, running on $10 hardware with under 10 MB RAM, including Android via Termux.
- [NanoBot](https://github.com/HKUDS/nanobot): A lightweight alternative to OpenClaw and similar agents for resource-constrained environments.
- [KimiClaw](https://www.kimi.com/resources/kimi-claw-introduction): A Kimi-flavoured variant of the OpenClaw agent pattern with native Kimi model integration.

### Meta-harnesses and software factories

Frameworks and platforms that coordinate multiple agents, manage policies and budgets, and turn project work into isolated, observable agent runs.

- [Omnigent](https://github.com/omnigent-ai/omnigent): An Apache-2.0 meta-harness by Databricks for mixing Claude Code, Codex, OpenCode, Hermes, and custom agents with policies, budgets, sandboxing, cloud execution, and collaboration.
- [Gas Town](https://github.com/gastownhall/gastown): A multi-agent development factory for coordinating Claude, Gemini, Codex, Cursor, OpenCode, and others across tasks, tmux sessions, and workspaces.
- [Factory / Droid](https://factory.ai): A commercial coding-agent platform spanning CLI, desktop, remote computers, GitHub Actions, code review, and enterprise integrations.
- [Droid Action](https://github.com/Factory-AI/droid-action): A GitHub Action for running Factory's Droid coding agent in CI/CD and repository workflows.
- [Oh My Pi](https://github.com/can1357/oh-my-pi): An open-source coding harness with agents, skills, subagents, worktree isolation, and repository-level instructions.
- [ClockCode](https://github.com/Clockcode): A commercial software factory with deterministic delivery cycles, parallel agent execution, and senior architectural oversight for zero-failure environments.
- [Oh My OpenAgent](https://github.com/code-yeongyu/oh-my-openagent): An open-source agent factory from OMO.dev with Ultrawork for fully autonomous execution and Prometheus plus Atlas for strategic plan-then-execute workflows.
- [OpenHive](https://github.com/aden-hive/hive): A multi-agent coordination platform for running and managing coding agents at scale.
- [Sandcastle](https://github.com/mattpocock/sandcastle): A TypeScript library for orchestrating coding agents in isolated sandboxes with branch and worktree strategies for software-factory pipelines.
- [Archon](https://github.com/coleam00/Archon): An open-source deterministic workflow engine for AI coding agents with YAML-defined development pipelines spanning planning, implementation, validation, and review.
- [bolt.diy](https://github.com/stackblitz-labs/bolt.diy): An open-source community version of the Bolt full-stack AI app builder, giving agents control over filesystem, terminal, package manager, and browser preview.

### Agent tools and utilities

Session viewers, history browsers, task managers, and observability tools that complement coding-agent workflows.

- [Claude Code History Viewer](https://github.com/jhlee0409/claude-code-history-viewer): An offline cross-agent session viewer supporting Claude Code, Gemini, Codex, Cursor, Cline, Aider, OpenCode, and other histories.
- [Claude Code UI](https://github.com/siteboon/claudecodeui): A responsive web and mobile interface for remotely accessing Claude Code, Cursor CLI, Codex, and Gemini sessions.
- [Agentify Desktop](https://github.com/agentify-sh/desktop): A desktop control centre that lets agents operate logged-in browser sessions for ChatGPT, Claude, Gemini, Grok, and other services through MCP.
- [Traces](https://traces.com): A cross-agent session capture and publishing platform that normalizes coding-agent conversations into searchable and shareable traces.
- [Latitude](https://github.com/latitude-dev/latitude-llm): An open-source observability platform for agent traces, tool calls, multi-turn sessions, issue detection, search, and evaluation.
- [Backlog.md](https://github.com/MrLesk/Backlog.md): An MIT Markdown-native task and specification manager with acceptance criteria, plans, decisions, CLI, MCP, terminal Kanban, and local web UI.
- [Agentic Stack](https://github.com/codejunkie99/agentic-stack): A portable `.agent/` folder with memory, skills, and protocols that plugs into Claude Code, Cursor, Windsurf, OpenCode, and other harnesses while keeping knowledge across switches.
- [ADL CLI](https://github.com/inference-gateway/adl-cli): An Agent Definition Language CLI for defining and managing agent configurations and workflows.
- [Awesome Hermes Agent](https://github.com/0xNyk/awesome-hermes-agent): A curated list of Hermes Agent plugins, resources, and community contributions.
- [Hermes WebUI](https://github.com/nesquena/hermes-webui): A custom web dashboard for Hermes Agent with enhanced session management.
- [Hermes Workspace](https://github.com/outsourc-e/hermes-workspace): A native desktop workspace application for Hermes Agent.
- [Hermes Control Interface](https://github.com/xaspx/hermes-control-interface): An alternative web control interface for Hermes, inspired by the native dashboard.
- [Hermes on Android](https://github.com/AbuZar-Ansarii/Hermes-Agent-On-Android): A guide and tooling for running Hermes Agent locally on Android via Termux, with no root required.
- [Hermes Paperclip Adapter](https://github.com/NousResearch/hermes-paperclip-adapter): An adapter for running Hermes Agent as a managed employee in a Paperclip company.
- [Autonovel](https://github.com/NousResearch/autonovel): An autonomous novel-writing pipeline powered by Hermes Agent.
- [Cua.ai](https://cua.ai): A cloud desktop platform that gives every agent a browser-accessible environment, built for Claude Code, Codex, OpenClaw, and computer-use agents.
- [ShopClawMart](https://www.shopclawmart.com): A skills marketplace and ready-made setups for OpenClaw, including the Content Machine package.
- [Claude Code Leaks](https://www.ccleaks.com): A community resource cataloguing Claude Code system prompts, internal tools, and configuration patterns.
- [Composio](https://composio.dev): A tooling platform for connecting AI agents to external APIs, services, and actions.
- [Robobun](https://github.com/robobun): A fork of Bun.js rewritten from Zig to Rust using coding agents, demonstrating large-scale agent-driven language migration.
- [DS4](https://github.com/antirez/ds4): A packaged, locally runnable DeepSeek V4 Flash model for private inference.
- [Vercel Agent Browser](https://github.com/vercel-labs/agent-browser): A Rust browser automation CLI for agents, useful as a tool component for coding and browser-control agents.
- [Claudable](https://github.com/opactorai/Claudable): An open-source Lovable-like builder using local CLI agents such as Claude Code, Codex, Gemini, Qwen, and Cursor.
- [Vibe Tools](https://github.com/eastlondoner/vibe-tools): An extra tool layer for Cursor and agent workflows with GitHub integrations and multi-agent helper commands.
- [ACP Bridge](https://github.com/allvegetable/acp-bridge): An ACP bridge for connecting different coding agents and clients, useful for custom unified agent UIs.

### Protocols and integration

- [Agent Client Protocol](https://agentclientprotocol.com): An open protocol for structured communication between editors and coding agents, serving as an integration rail across tools.

## Contributing

Suggestions are welcome, but this list is intentionally selective. Read [the curation policy](CURATION.md) before opening an issue or pull request.

A proposed resource should:

- serve software developers learning or practising AI engineering;
- provide technical or practical value beyond a product homepage;
- be current and maintained, unless its value is foundational and durable;
- add something meaningfully different from the existing entries;
- use a factual description supported by a primary source.

Explain which developer problem the resource solves and why it clears the rubric. If it overlaps an existing entry, explain why it is materially better. Disclose any affiliation with the resource.
