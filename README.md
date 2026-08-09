# Lucas Costa

I build developer tools and web products, end to end, mostly in TypeScript.

I work across the stack: backend services, CLIs, and the web layer around them, usually inside a single pnpm monorepo with CI wired in from the first commit. I care about software that stays honest about what it does and does not do yet.

## Featured project: OpenLimiter

An open source, cross platform, local first quota meter for AI coding subscriptions. It reads quota state already sitting on your machine (a Claude Code statusline payload, an OpenRouter credits response, or a document you hand it) and turns it into one bounded snapshot your agent can read.

- Six read only connectors, every one marked UNVERIFIED and failing closed to unknown, covering Claude, OpenRouter, Codex, Antigravity, OpenCode, and manual entry.
- A Claude Code adapter that injects bounded budget state and routing advice inside an explicit untrusted data boundary. It advises; it never routes automatically.
- Zero telemetry, no provider file mutation, 100 tests, CI on Windows and Linux.

Repo: https://github.com/lucaswebsystems/openlimiter
Site: https://openlimiter.com

## What I work with

TypeScript, Node.js, Next.js, React, Tailwind CSS, pnpm monorepos, GitHub Actions, CLI and developer tooling.

## Get in touch

- OpenLimiter site: https://openlimiter.com
- LinkedIn: https://www.linkedin.com/in/lucas-costa-t/
- GitHub: https://github.com/lucaswebsystems
