# Contributing

**This is the organization-wide default. A repository that says something different in its own
`CONTRIBUTING.md` overrides everything here.**

Vorluno publishes two kinds of repository, and what gets merged depends on which one you are looking
at. The repository's own first line tells you; if it has none, assume the first.

**Packages** — code we maintain and run in production.

- **Bug fixes with a failing test.** The test comes first: it proves the bug was real and stops it
  from coming back.
- **Documentation that corrects something wrong**, a wrong example most of all.
- **New capabilities are a conversation before they are a pull request.** Open an issue describing
  the problem, not the solution you have in mind — we may already have decided against it, and the
  reason will be there.

**Demonstrations** — written to show how something is done, in the smallest amount of code that shows
it. Corrections are welcome and matter more here than anywhere, because a broken demonstration
teaches the wrong thing. Features are not: each one makes it worse at its only job. If you need it in
production, copy it — the licence is Apache-2.0 precisely so you can.

## In both cases

1. **One change per pull request.** A fix bundled with a refactor is a fix nobody can review.
2. **Run whatever checks the repository has**, and if one is red for a reason you believe is
   unrelated, say so in the description rather than silencing it.
3. **A closed pull request comes with the reason.** One closed without a reason is a bug in how we
   work, and you are welcome to say so.

## Security

Never in an issue. **security@vorluno.dev** — see [SECURITY.md](./SECURITY.md), where the 72-hour
acknowledgement is the one response time we commit to.

## Licence of contributions

By opening a pull request you agree that your contribution is licensed under the licence of that
repository. There is no separate contributor agreement to sign — we do not want one.
