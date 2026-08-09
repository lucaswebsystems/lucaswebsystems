<h1 align="center">Lucas Costa</h1>

<p align="center">
  <strong>Senior Web Developer and AI Systems Architect</strong><br>
  I build developer tools and production web products end to end, mostly in TypeScript.
</p>

<p align="center">
  <a href="https://openlimiter.com">Site</a> ·
  <a href="https://www.linkedin.com/in/lucas-costa-t/">LinkedIn</a> ·
  <a href="https://github.com/lucaswebsystems">GitHub</a>
</p>

---

I work across the whole stack: core engines, command line tools, APIs, and the interfaces around them, usually in a single monorepo with continuous integration wired in from the first commit. Lately most of my work sits where AI systems meet real products: agent integrations, context design, and the plumbing that keeps them honest and bounded.

I care about software that is truthful about what it does and does not do yet. That means failing closed instead of guessing, treating anything a model or a provider hands you as untrusted, and never shipping a claim the code cannot back.

## Featured project

### [OpenLimiter](https://github.com/lucaswebsystems/openlimiter)

[![CI](https://github.com/lucaswebsystems/openlimiter/actions/workflows/ci.yml/badge.svg)](https://github.com/lucaswebsystems/openlimiter/actions/workflows/ci.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/lucaswebsystems/openlimiter/blob/main/LICENSE)

An open source, cross platform, local first quota meter for AI coding subscriptions. When you hold several at once, the scarce resource stops being money and becomes quota. OpenLimiter reads what is already on your machine and hands your coding agent a bounded picture of the budget it has left.

- **Agent native.** A statusline for you and a bounded context block for the agent, wrapped in an explicit untrusted data boundary. Enum codes, numbers and timestamps only, never provider prose.
- **Honest by construction.** Every connector ships labelled, and missing or malformed input becomes unknown, never a fabricated zero.
- **Zero third party runtime dependencies**, zero telemetry, no accounts, no server. TypeScript monorepo, continuous integration on Windows and Linux.

Site: [openlimiter.com](https://openlimiter.com) · Docs: [openlimiter.com/docs](https://openlimiter.com/docs)

## What I work with

**Languages and runtime:** TypeScript, JavaScript, Node.js
**Web:** Next.js, React, Tailwind CSS
**Tooling and delivery:** pnpm monorepos, GitHub Actions, Vitest, Playwright, CLI and developer tooling
**AI systems:** agent integrations, context and prompt boundaries, provider integration, evaluation harnesses

## Get in touch

Open to conversations about senior engineering and AI systems work.

- Site: [openlimiter.com](https://openlimiter.com)
- LinkedIn: [lucas-costa-t](https://www.linkedin.com/in/lucas-costa-t/)
- GitHub: [@lucaswebsystems](https://github.com/lucaswebsystems)
