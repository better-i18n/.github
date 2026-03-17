<p align="center">
  <a href="https://better-i18n.com">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://better-i18n.com/brand/logo-dark.svg">
   <img src="https://better-i18n.com/brand/logo-light.svg" alt="Better i18n" width="240">
 </picture>
  </a>
</p>

<h3 align="center">Localization platform built for developers</h3>

<p align="center">
  AI-powered translation management with GitHub sync, CDN delivery, and TypeScript-first SDKs.
  <br />
  <a href="https://better-i18n.com"><strong>Website</strong></a> · <a href="https://docs.better-i18n.com"><strong>Docs</strong></a> · <a href="https://status.better-i18n.com"><strong>Status</strong></a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@better-i18n/cli"><img src="https://img.shields.io/npm/v/@better-i18n/cli?label=%40better-i18n%2Fcli&color=0284c7" alt="npm"></a>
  <a href="https://www.npmjs.com/package/@better-i18n/next"><img src="https://img.shields.io/npm/v/@better-i18n/next?label=%40better-i18n%2Fnext&color=0284c7" alt="npm"></a>
  <a href="https://github.com/better-i18n/oss/blob/main/LICENSE"><img src="https://img.shields.io/github/license/better-i18n/oss?color=0284c7" alt="License"></a>
</p>

---

### What is Better i18n?

Better i18n is a **translation management platform** designed for engineering teams who want to ship multilingual apps without the pain. Instead of juggling JSON files, spreadsheets, or clunky dashboards, you get a developer-native workflow:

- **GitHub Sync** — translations live in your repo. Changes create PRs, reviews happen where your code lives.
- **AI Translation** — translate with context-aware AI (Google Gemini), not word-by-word machine translation.
- **CDN Delivery** — serve translations from the edge with [Cloudflare](https://cloudflare.com). No build step needed for translation updates.
- **TypeScript SDKs** — first-class integrations for [Next.js](https://nextjs.org), [React](https://react.dev), [Expo](https://expo.dev) / [React Native](https://reactnative.dev), and more.
- **MCP Server** — let AI agents manage translations through the [Model Context Protocol](https://modelcontextprotocol.io/).

### Repositories

| Repository | Description |
|---|---|
| **[oss](https://github.com/better-i18n/oss)** | Open-source SDKs, CLI, MCP server — `@better-i18n/next`, `@better-i18n/cli`, `@better-i18n/expo` |
| **[skills](https://github.com/better-i18n/skills)** | AI agent skills for i18n best practices and workflow automation |
| **[status.better-i18n.com](https://github.com/better-i18n/status.better-i18n.com)** | Open-source status page built with [TanStack Start](https://tanstack.com/start) |
| **[og.better-i18n.com](https://github.com/better-i18n/og.better-i18n.com)** | Edge OG image generation with Rust WASM on Cloudflare Workers |

### Quick Start

```bash
npm install @better-i18n/cli
npx @better-i18n/cli init
npx @better-i18n/cli scan
npx @better-i18n/cli sync
```

### Integrations

Better i18n works with the tools you already use:

[Next.js](https://nextjs.org) · [React](https://react.dev) · [Expo](https://expo.dev) · [React Native](https://reactnative.dev) · [TanStack](https://tanstack.com) · [next-intl](https://next-intl-docs.vercel.app) · [use-intl](https://www.npmjs.com/package/use-intl) · [Cloudflare Workers](https://workers.cloudflare.com) · [GitHub Actions](https://github.com/features/actions)

### Links

- [Website](https://better-i18n.com) — product overview and pricing
- [Documentation](https://docs.better-i18n.com) — guides, API reference, SDK docs
- [Blog](https://better-i18n.com/blog) — tutorials, best practices, release notes
- [Status](https://status.better-i18n.com) — real-time uptime monitoring
- [npm](https://www.npmjs.com/org/better-i18n) — all published packages
