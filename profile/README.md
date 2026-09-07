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

Everything we publish is Apache-2.0 and carries the same five
files: a licence, a contribution guide that says in its first line whether your pull request will be
considered, a security policy with a **72-hour acknowledgement**, a code of conduct, and an authors
file. Bug reports are welcome; a vulnerability goes to **security@vorluno.dev**, never to an issue.

**Extracted from [niiko](https://niiko.org), where they run in production:**

| Package | What it does |
|---|---|
| [whatsapp-cloud-client](https://github.com/vorluno/whatsapp-cloud-client) | A typed WhatsApp Cloud API client: signature verification in constant time, a tolerant webhook parser, and error classification that knows which failures are worth retrying |
| [ratchet](https://github.com/vorluno/ratchet) | Per-capability autonomy for AI agents — caps in their own unit, because a cap in the wrong unit is not a weak cap, it is one you cannot compare |
| [niiko-events](https://github.com/vorluno/niiko-events) | The event catalog: every event defined once, with its payload schema and the reasoning behind its shape. Generated, read-only |
| [niiko-cookbook](https://github.com/vorluno/niiko-cookbook) | Integration recipes you copy and run — every one with no credentials and no network, because a recipe that does not run teaches the wrong thing twice |

**Demonstrations — each one shows a single failure, with a test that would be red without the fix:**

| | Its thesis |
|---|---|
| [per-capability-autonomy](https://github.com/vorluno/per-capability-autonomy) | Autonomy belongs to the capability, not to the agent — two capabilities, one policy table, and only one degrades |
| [caps-in-the-right-unit](https://github.com/vorluno/caps-in-the-right-unit) | A cap in the wrong unit is not one you forgot to check; it is one you cannot compare. The test is a counter that stays at zero |
| [freeze-the-arguments](https://github.com/vorluno/freeze-the-arguments) | Human approval is not a defence. The broken version passes every test you would think to write, and then charges ten times what was shown |
| [the-wall-is-in-the-data-layer](https://github.com/vorluno/the-wall-is-in-the-data-layer) | The prompt loses to four words; the wall does not care. And a fifth origin breaks the build until somebody decides about it |
| [boundary-gate-blind-three-ways](https://github.com/vorluno/boundary-gate-blind-three-ways) | Your open-core boundary check is blind three ways, and the tree it approves does not compile |
| [crypto-shredding-erasure](https://github.com/vorluno/crypto-shredding-erasure) | A soft delete satisfies the right to restrict, not the right to be forgotten. The test is the restore — and the trap is where the keys live |
| [rls-per-request](https://github.com/vorluno/rls-per-request) | Row-level security leaks when the connection is pooled: it compiles, the unit tests pass, and the data is crossed |

They are meant to be copied, and the licence says so.

*Previously: `agora-mcp`, `batuta-mcp` and the `mcp-s` index — three MCP servers for coordinating parallel
coding agents, now retired and archived because Claude Code does that itself.*

## How we work

One call → a one-week scope → a plan with a price. The engineer who scopes your product is the engineer
who ships it. [How it runs →](https://vorluno.dev/#process)

<div align="center">

`// shipped, not staged.`

</div>
