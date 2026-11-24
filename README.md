### Hi, I'm Andrea 👋

**Full-stack & AI engineer · TypeScript / React / Next.js / Node.js**  
Florence, Italy · fully remote, CET with flexible overlap on US hours · open to new roles

11 years shipping production web software. Until November 2026 I worked at [Routescan](https://routescan.io) on the frontend of [Snowtrace](https://snowtrace.io) and its sibling explorers, serving **millions of monthly users** across **dozens of chains**, with **hundreds of transactions per second** of live data. There I also built the frontend of the streaming chat assistant that answers questions about live on-chain data through tool calls. Before that I was VP of Engineering at Avascan.

These days most of my side work is about **AI agents**: making them useful, and making them safe to let loose.

### What I'm good at

- **LLM products.** Streaming chat with tool calls, page-aware context, saved conversations and answer feedback; resumable token streams; MCP servers.
- **Agents you can trust.** Human approval for agent actions, policy firewalls, spending limits, and knowing which prompt wrote which line.
- **Data-heavy frontends at scale.** Server-rendered Next.js (App Router, RSC), caching and revalidation, Core Web Vitals, pagination for datasets too large to fetch eagerly.
- **Owning the whole loop.** Node.js and Postgres backends, Jest and Playwright in CI, preview deploys, Sentry in production. At Avascan I led the engineering team and reviewed every pull request.

### AI and agents

| Project | What it is |
|---|---|
| [**a2h-gateway**](https://github.com/AndreaAcanfora/a2h-gateway) | Self-hosted gateway for the Agent-to-Human protocol: agents ask people for approval over email, Telegram or push, and get a signed answer with passkey proof. In the official MCP registry. Pairs with [**nod**](https://github.com/AndreaAcanfora/nod), the Flutter app to approve from your phone. |
| [**agentfence**](https://github.com/AndreaAcanfora/agentfence) | A policy firewall for Claude Code: blocks `git push --force`, `rm -rf ~`, secret reads and `curl \| sh` before they run. Real shell parser, readable rules, policy unit tests. On npm. |
| [**prompt-blame**](https://github.com/AndreaAcanfora/prompt-blame) | `git blame` for AI code: hover any line in VS Code to see the Claude Code prompt and conversation behind it. On the VS Code Marketplace and Open VSX. |
| [**rewind**](https://github.com/AndreaAcanfora/rewind) | Resumable Stream Protocol: LLM token streams that survive dropped connections, page reloads and multiple tabs. Open spec over SSE, TypeScript and Python packages, conformance suite. |
| [**onchain-copilot**](https://github.com/AndreaAcanfora/onchain-copilot) | Paste a transaction hash and read what actually happened. The AI narrates, the code does the math. Next.js, Vercel AI SDK, Viem. [Live](https://onchain-copilot.vercel.app) |
| [**claude-cloud-browser**](https://github.com/AndreaAcanfora/claude-cloud-browser) | Claude Code plus an always-on Chrome on your own VPS, driven from your phone over SSH. Playwright MCP over CDP, noVNC over Tailscale, one idempotent installer. |

More: [unjailable](https://github.com/AndreaAcanfora/unjailable) (an agent wallet with on-chain spending limits and an MCP server) · [distillo](https://github.com/AndreaAcanfora/distillo) (lectures and podcasts distilled to timestamped key points, on Gemini/Groq or offline) · [raygpt](https://github.com/AndreaAcanfora/raygpt) (voice assistant for Ray-Ban Meta glasses on GPT-Live)

### Other things you can open and run

- [**hyperliquid-quant-stack**](https://github.com/AndreaAcanfora/hyperliquid-quant-stack): the open-source half of the trading bot I run with real capital on Hyperliquid, now becoming [Botely](https://botely.trade). [Live demo](https://hyperliquid-quant-stack.vercel.app)
- **Systems:** [doubledip](https://github.com/AndreaAcanfora/doubledip) (reproduces race conditions on Postgres) · [crepa](https://github.com/AndreaAcanfora/crepa) (cut the network in docker compose, count lost writes) · [loomkv](https://github.com/AndreaAcanfora/loomkv) (Redis-compatible server in Java 25) · [ordito](https://github.com/AndreaAcanfora/ordito) (Raft you can break)
- **Built for fun, playable in the browser:** [mattone](https://andreaacanfora.github.io/mattone/) (Game Boy emulator in 27 KB of WebAssembly) · [sabbia](https://andreaacanfora.github.io/sabbia/) (falling sand in Rust + wasm) · [iron-arena](https://andreaacanfora.github.io/iron-arena/) (3D fighting game) · [dama](https://andreaacanfora.github.io/dama/) (Italian draughts with online play)

### Stack

- **AI:** OpenAI · Anthropic Claude · Gemini · Vercel AI SDK · streaming and tool calls · MCP · Claude Code
- **Frontend:** TypeScript · React · Next.js (App Router, RSC) · Tailwind · TanStack Query · Jotai
- **Backend:** Node.js · PostgreSQL · Prisma · MongoDB · Redis
- **Web3:** Viem · Wagmi · RainbowKit · SIWE · EVM chains
- **Quality:** Jest · Playwright · GitHub Actions · Sentry

### Where I've been

- **Botely** · Founder, algorithmic trading on Hyperliquid · 2026 - now
- **Routescan** · Web3 frontend engineer, AI assistant on Snowtrace · 2024 - 2026
- **Equixly** · Frontend lead, AI-driven API security · 2023 - 2024, 2026
- **Rogue Waves** · Frontend for computer-vision and OCR products · 2025
- **Avascan** · VP of Engineering and frontend lead · 2022 - 2024
- **ShippyPro** · Full stack developer · 2019 - 2022

### Get in touch

Open to remote full-stack and AI engineering roles.  
📫 [LinkedIn](https://www.linkedin.com/in/andrea-acanfora-988179a8/) · [acanfora.andrea@gmail.com](mailto:acanfora.andrea@gmail.com)
