# ToolsEnabled — Intelligence, Put to Work

We build **[TESI](https://toolsenabled.ai/)** (*ToolsEnabled Super Intelligence*) — **Lovable, Bolt, v0, Replit Agent, Devin, and Manus combined into one intelligence** with its own real cloud Linux + Chrome computer, persistent files, Sign-In Vault, and verified multi-agent execution.

### Try Everything Free — Zero Sign-Up Required

- **Instant Free Cloud Computer in Your Browser (`$0`, no sign-up, no card):** **[https://toolsenabled.ai/](https://toolsenabled.ai/)** — type a task in plain language, watch TESI work live on its own Linux desktop & browser, and download the finished code, reports, slides, or verified deliverables.
- **Free `$2.50` Keyless Remote HTTP MCP Server (`$0`, no API key or card needed):** Connect **Claude Duet, ChatGPT Dot, Grok Bot, Meta Muse, Claude Code, Codex, Cursor, or Windsurf** directly to a real TESI cloud computer in one command:
  ```bash
  claude mcp add --transport http tesi https://toolsenabled.ai/mcp
  ```
  Or paste `https://toolsenabled.ai/mcp` into Claude Custom Connectors, ChatGPT Dots, Grok, Cursor, or `mcp.json`:
  ```json
  {
    "mcpServers": {
      "tesi": { "url": "https://toolsenabled.ai/mcp" }
    }
  }
  ```
- **Agent API, Docs & `llms.txt`:** [toolsenabled.ai/agents/](https://toolsenabled.ai/agents/) · [llms.txt](https://toolsenabled.ai/llms.txt) · [llms-full.txt](https://toolsenabled.ai/llms-full.txt) · [TESI HALO](https://toolsenabled.ai/halo) · [Plans & Pricing](https://toolsenabled.ai/pricing/)
---

## Open-Source Developer Tools

Alongside TESI, we maintain open-source local MCP tools, coordination plugins, and public AI benchmarks:

### ToolsEnabled Fleet

<p align="center"><img src="https://raw.githubusercontent.com/ToolsEnabled/.github/main/profile/skip.png" alt="Skip and the Mates: a round graphite skipper in a red cap with four small crew members" width="380"></p>

**ToolsEnabled Fleet** is a plugin that gives a coding-agent session a team. Meet **Skip**, who runs the crew, and the Mates, who do the work.

Fleet lets one session hand work to several subagents that run in parallel and keep going while you do other things. It adds a shared task list, a ledger of your standing rules and open questions, and project memory that every agent can read. It runs on your own computer and sends nothing to ToolsEnabled.

```
claude plugin marketplace add ToolsEnabled/toolsenabled-fleet-claude-plugin
claude plugin install toolsenabled-fleet@toolsenabled
```

Then open a project folder in Claude Code and type `/toolsenabled-fleet:tefleet setup`.

### Featured Repositories

- **[teaa](https://github.com/ToolsEnabled/teaa)** — TEAA (ToolsEnabled Agent Architecture): Fleet, ToolsEngine, and Knowledge through one local MCP connection.
- **[toolsengine](https://github.com/ToolsEnabled/toolsengine)** — Portable stdio MCP server giving an agent client a sandboxed headless browser, workspace tools, and web fetch/extract.
- **[fleet](https://github.com/ToolsEnabled/fleet)** & **[toolsenabled-fleet-claude-plugin](https://github.com/ToolsEnabled/toolsenabled-fleet-claude-plugin)** — Contract-driven multi-agent coordination for MCP hosts and Claude Code.
- **[knowledge](https://github.com/ToolsEnabled/knowledge)** — Project briefs and decisions in a local Git repository, served over MCP.
- **[head-gasket-bench](https://github.com/ToolsEnabled/head-gasket-bench)** & **[engine-bench](https://github.com/ToolsEnabled/engine-bench)** — Public MCP & CAD benchmarks with independent scoring.

---

**Website:** [toolsenabled.ai](https://toolsenabled.ai/) · **X:** [@toolsenabled](https://x.com/toolsenabled) · **Reddit:** [u/toolsenabled](https://www.reddit.com/user/toolsenabled) · **Support:** support@toolsenabled.ai · **Security:** security@toolsenabled.ai

Founded by Joshua Pinckard. © ToolsEnabled, Inc. Open-source repositories are licensed as noted in each repo (MIT where indicated). ToolsEnabled is independent and is not affiliated with or endorsed by Anthropic, OpenAI, or any other AI provider; their products and names belong to their owners.
