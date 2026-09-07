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
| [prove-your-test-can-fail](https://github.com/vorluno/prove-your-test-can-fail) | Two green suites, and only one is worth having — plus the half nobody checks: a mutation that comes back green may simply have missed |
| [exit-code-after-the-pipe](https://github.com/vorluno/exit-code-after-the-pipe) | The same failing gate, four ways. Three report success, and the error is printed inside the green job |
| [one-gate-one-question](https://github.com/vorluno/one-gate-one-question) | One signal doing two jobs is correct about everything except the file the gate was built for |
| [idempotency-of-the-effect](https://github.com/vorluno/idempotency-of-the-effect) | Key it by the turn and the second legitimate action disappears; check it after the effect and the retry duplicates while the audit says it happened once |
| [typed-refusals](https://github.com/vorluno/typed-refusals) | Six situations needing six different people to do six different things, compressed into one bit — and a block that leaves no trace |
| [search-terms-not-identifiers](https://github.com/vorluno/search-terms-not-identifiers) | Let a model emit an id and a hostile message decides which record you act on. Let it emit search terms and the forgery does not compile |
| [append-only-that-blocked-itself](https://github.com/vorluno/append-only-that-blocked-itself) | The rule is right, and it is what stands between you and a correction everybody agrees with. The fix is another entry |
| [ledger-invariants-in-the-database](https://github.com/vorluno/ledger-invariants-in-the-database) | Your balance check is correct, and the migration script never asks it. Real Postgres inside the test, no Docker |
| [pii-gate-default-deny](https://github.com/vorluno/pii-gate-default-deny) | A registry cannot see the module that forgot to register — which is the only one you needed it to find. It reports green while an address survives an erasure |
| [deprecation-vs-pending-approvals](https://github.com/vorluno/deprecation-vs-pending-approvals) | A clean removal, and a live Approve button that can never work. Then the obvious patch issues four thousand dollars where forty were asked for |

They are meant to be copied, and the licence says so.

*Previously: `agora-mcp`, `batuta-mcp` and the `mcp-s` index — three MCP servers for coordinating parallel
coding agents, now retired and archived because Claude Code does that itself.*

## How we work

One call → a one-week scope → a plan with a price. The engineer who scopes your product is the engineer
who ships it. [How it runs →](https://vorluno.dev/#process)

<div align="center">

`// shipped, not staged.`

</div>
