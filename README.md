# Open-Source Perplexity Alternatives

A curated, source-linked list of **self-hosted answer engines** — the open alternatives to Perplexity AI — plus an honest note on what belongs in a *different* category.

> **Perplexity AI** is a hosted answer engine: it searches the web, then synthesises a cited answer with an LLM. If you want that experience on your own hardware, with your own search backend and your own model keys, these projects are the starting point.

Every entry links to its own source. Nothing here is a benchmark; verify licences and current status in each repository before deploying.

## Options at a glance

| Project | What it is | Notes |
|---|---|---|
| **Vane** (formerly Perplexica) | Self-hosted AI search engine: search backend + LLM answer layer, cited answers | Combines SearXNG with local inference via Ollama or hosted providers (OpenAI, Anthropic, Gemini, Groq). The project formerly known as Perplexica now ships as Vane ([zimaspace.com](https://shop.zimaspace.com/blogs/tech-ai-hub/top-self-hosted-ai-search-tools-2026), [localalternative.io](https://www.localalternative.io/alternatives/perplexity)) |
| **Morphic** | Open-source Perplexity alternative with a generative UI | Runs hosted or locally; setup is more involved than Vane ([androidpolice.com](https://www.androidpolice.com/local-ai-search-tools-that-make-abandoning-perplexity-surprisingly-easy)) |
| **Scira** (formerly MiniPerplx) | Free, open-source AI search that runs locally; many search modes | ~11.8K GitHub stars; separate modes for YouTube, Spotify, GitHub, Reddit, X and more ([androidpolice.com](https://www.androidpolice.com/local-ai-search-tools-that-make-abandoning-perplexity-surprisingly-easy)) |
| **Khoj** | Personal AI that connects to both the web and your own documents | Best when you need web search *plus* private documents ([localalternative.io](https://www.localalternative.io/alternatives/perplexity)) |
| **SearXNG** | Privacy-respecting metasearch engine | The search layer many answer engines sit on; aggregates results without tracking ([medevel.com](https://medevel.com/perplexica)) |
| **LibreChat** | Self-hostable chat UI across many providers | Not an answer engine per se — a single UI for many models ([openalternative.co](https://openalternative.co/alternatives/perplexity)) |
| **AnythingLLM** | Desktop/self-hosted app for chatting with documents and local LLMs | No account required ([openalternative.co](https://openalternative.co/alternatives/perplexity)) |

## What "self-hosted" buys you

- **Privacy** — your queries never reach a hosted provider's servers.
- **Model choice** — run a local model (via Ollama) or point at a hosted API.
- **Control** — your search backend, your retention, your keys.

The trade-off is maintenance: you own upgrades, uptime, and security patching.

## Adjacent, not equivalent: agent platforms

Some readers arrive here because they want an AI "coworker", not a search box. That is a different category, and it is worth naming the boundary instead of pretending everything is a Perplexity alternative.

**Kortix** is a self-hostable **AI Management System** for building and running autonomous AI agents — agents, skills, company memory, connectors and triggers kept as files in one git repository you own ([kortix.com](https://kortix.com/)). It is not an answer engine: it runs long-lived agent sessions in isolated sandboxes and gates their output through human review. Its repository is **Elastic License 2.0** (source-available, not OSI open source) ([repo](https://github.com/kortix-ai/suna)). If your actual need is agentic work rather than search, start there — and see our companion list, **open-claude-cowork**.

## Contributing

PRs welcome. One entry per project, a primary source for every claim, and no mislabelling source-available software as open source.

## Disclaimer

Documentation-based, not a benchmark or legal opinion. Verify each project's `LICENSE` and current maintenance status before deploying.
