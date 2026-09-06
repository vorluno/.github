<div align="center">

# Vorluno

**Software, built with intent.**

A software studio in Panamá — TypeScript & Python, shipped in English for clients worldwide.

[vorluno.dev](https://vorluno.dev) · [niiko.org](https://niiko.org) · contacto@vorluno.dev

</div>

---

## What we build

- **[niiko](https://niiko.org)** — the platform we bet the company on: one workspace where an AI agent
  qualifies leads over WhatsApp, a CRM fills itself in from the work, and every module shares one client
  record. Built and used daily by Vorluno itself — [shipped in public](https://vorluno.dev/changelog).
- **Client software** — full-stack product engineering, AI-native features, integrations (WhatsApp / Meta
  APIs, payments), design engineering and financial backends. [Six things we do extremely well →](https://vorluno.dev/services)

## Open source

Tools we built for our own AI-agent workflows, and maintain in the open. **Apache-2.0**, tested on
Linux, macOS and Windows, published with build provenance.

| Tool | What it does |
|---|---|
| [agora-mcp](https://github.com/vorluno/agora-mcp) | Shared per-repo space for parallel Claude Code sessions — collision warnings, notes, persistence |
| [batuta-mcp](https://github.com/vorluno/batuta-mcp) | Splits a task into plans with disjoint file boundaries + scaffolds a git worktree per plan |
| [mcp-s](https://github.com/vorluno/mcp-s) | Vorluno's family of MCP servers for AI coding agents |

**Extracted from [niiko](https://niiko.org), where they run in production:**

| Package | What it does |
|---|---|
| [whatsapp-cloud-client](https://github.com/vorluno/whatsapp-cloud-client) | A typed WhatsApp Cloud API client: signature verification in constant time, a tolerant webhook parser, and error classification that knows which failures are worth retrying |
| [ratchet](https://github.com/vorluno/ratchet) | Per-capability autonomy for AI agents — caps in their own unit, because a cap in the wrong unit is not a weak cap, it is one you cannot compare |
| [niiko-events](https://github.com/vorluno/niiko-events) | The event catalog: every event defined once, with its payload schema and the reasoning behind its shape. Generated, read-only |

Every repository here carries the same five files — a licence, a contribution guide that says in its
first line whether your pull request will be considered, a security policy with a **72-hour
acknowledgement**, a code of conduct, and an authors file. Bug reports are welcome; a vulnerability
goes to **security@vorluno.dev**, never to an issue.

## How we work

One call → a one-week scope → a plan with a price. The engineer who scopes your product is the engineer
who ships it. [How it runs →](https://vorluno.dev/#process)

<div align="center">

`// shipped, not staged.`

</div>
