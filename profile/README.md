<p align="center">
  <img src="https://raw.githubusercontent.com/snugprotocol/.github/main/profile/org-profile-banner.png" alt="Snug — MCP connects agents to tools. Snug connects agents to apps. Two repositories: snugprotocol/snug, the reference implementation; snugprotocol/spec, the protocol specification." width="800" />
</p>

<h1 align="center">The Snug Protocol</h1>

<p align="center"><strong>MCP connects agents to tools. Snug connects agents to apps.</strong></p>

<p align="center">
  Snug is an open protocol (MIT) for tiny, user-built apps that <em>think through their host's AI agent at runtime</em> —<br />
  and live, code and data and chats, in <strong>one portable file the user owns</strong>.
</p>

<p align="center">
  <a href="https://snugprotocol.org"><strong>snugprotocol.org</strong></a> ·
  <a href="https://playground.snugprotocol.org">Try the Playground</a> ·
  <a href="https://snugprotocol.org/docs/">Docs</a> ·
  <a href="https://snugprotocol.org/docs/spec/">Spec 1.0</a> ·
  <a href="https://snugprotocol.org/download/">Download for macOS</a>
</p>

---

### Why it's different

1. **The app's brain is the host agent.** A Snug chess game doesn't embed a chess engine — it sends the board to the LLM over a standard envelope and animates the reply. The app is a *body*; the agent is the *mind*.
2. **Users own their apps and their data** — everything lives in one portable `.snug` file (real SQLite), exportable, movable, optionally passphrase-sealed.
3. **It's embeddable and secure by construction** — any product can drop in the runner + SDK; apps run in a hard sandbox with no network of their own, and credentials never enter the app, the LLM, or anyone's cloud.

### The repositories

| Repository | What it is |
|---|---|
| [`snug`](https://github.com/snugprotocol/snug) | The reference implementation — protocol bindings, sandboxed runner, SDK, portable database, agent adapters, the Playground, the macOS desktop app, and starter apps |
| [`spec`](https://github.com/snugprotocol/spec) | **Specification 1.0** (normative) — the spec, JSON schemas for every message type, and the whitepaper |

### Start here

- **Curious?** [What is Snug?](https://snugprotocol.org/docs/get-started/what-is-snug/) → [try it in five minutes](https://snugprotocol.org/docs/get-started/quickstart/)
- **Building a product?** [Implementor quickstart](https://snugprotocol.org/docs/get-started/implementors/) — let your users build micro apps against *your* assistant
- **Security-minded?** [The whitepaper](https://snugprotocol.org/docs/whitepaper/) — design rationale, threat model, security properties

<p align="center">Security contact: <a href="mailto:security@snugprotocol.org">security@snugprotocol.org</a> · MIT</p>
