# Kibologic

> **"We got tired of waiting for someone else to build it."**

We build the software infrastructure for precision applications — starting with **SwissJS**, a TypeScript-first web framework with its own compiler, dev server, and component model.

Built in Africa 🌍. Shipped to the world.

---

## What We Build

| Repo | What it is |
|---|---|
| [swiss-lib](https://github.com/kibologic/swiss-lib) | SwissJS Framework — components, compiler, reactivity, context, routing |
| [swite](https://github.com/kibologic/swite) | Swite — development server & build tool (our Vite) |
| [.github](https://github.com/kibologic/.github) | Org-wide docs: contributing, security, code of conduct |

---

## The Stack

- **Language**: TypeScript — always
- **File types**: `.ui` for logic, `.uix` for components (think `.ts` + `.tsx` but Swiss)
- **Package scopes**: `@swissjs/*` for framework, `@sws/*` for app packages
- **Build**: [Swite](https://github.com/kibologic/swite) — esbuild under the hood, HMR included
- **Package manager**: pnpm workspaces

---

## Philosophy

We just wanted fast software. No extra runtime magic. No framework-within-a-framework.

- **Precision-First** — every API has a reason
- **Integrated by Design** — framework, build tool, and devtools from the same org
- **Capability-Based Security** — components declare what they need, nothing more

---

## Contributing

We welcome contributors. Read [CONTRIBUTING.md](CONTRIBUTING.md) to get started.

Questions? Open an issue in the relevant repo or reach us at `themba@kibologic.dev`.

---

*© 2024–2025 Kibologic. MIT Licensed.*
