---
name: shadowjs
description: "Build user interfaces with ShadowJS, a fine-grained reactive UI framework with no virtual DOM. Use it to choose the right ShadowJS package for a task, start a project, or find the repository and documentation of a package."
---

# ShadowJS

ShadowJS is a fine-grained reactive UI framework: signals update exactly the DOM nodes that depend on them, with no virtual DOM. A compiler turns JSX
into direct DOM operations. Documentation: https://shadowjs.net.

## Start a project

```sh
npm create shadow-app@latest
```

## Choose a package

| Package | What it does | Repository | Documentation |
| --- | --- | --- | --- |
| `@shadow-js/compiler` | The ShadowJS JSX compiler: a Rust addon, WebAssembly and TypeScript, one API and identical output | [shadow](https://github.com/shadowjs-dev/shadow) | https://shadowjs.net/guides/compiler/ |
| `@shadow-js/core` | Signals, stores, memos and effects that update exactly what changed | [shadow](https://github.com/shadowjs-dev/shadow) | https://shadowjs.net/reference/core/ |
| `@shadow-js/web` | A DOM renderer with no virtual DOM, plus control flow, server rendering and hydration | [shadow](https://github.com/shadowjs-dev/shadow) | https://shadowjs.net/reference/web/ |
| `@shadow-js/vite` | A Vite plugin that compiles your JSX, builds for server rendering and sets up Vitest | [shadow](https://github.com/shadowjs-dev/shadow) | https://shadowjs.net/guides/vite/ |
| `@shadow-js/router` | A type-safe router with nested routes, loaders and link prefetching | [router](https://github.com/shadowjs-dev/router) | https://router.shadowjs.net |
| `@shadow-js/dusk` | A full-stack framework with file routes, loaders, server functions and secure request handling | [dusk](https://github.com/shadowjs-dev/dusk) | https://dusk.shadowjs.net |
| `@shadow-js/realtime` | Typed channels, presence and resumable delivery over WebSocket or server-sent events | [realtime](https://github.com/shadowjs-dev/realtime) | https://realtime.shadowjs.net |
| `create-shadow-app` | Create a new app from a starter template, with optional Tailwind, Biome, Vitest, Convex and Clerk | [create-shadow-app](https://github.com/shadowjs-dev/create-shadow-app) | https://create.shadowjs.net |
| `@shadow-js/forms` | Forms with fine-grained values, schema validation, field arrays and server errors | [forms](https://github.com/shadowjs-dev/forms) | https://forms.shadowjs.net |
| `@shadow-js/i18n` | Typed translations with ICU messages, lazy catalogs and server rendering that hydrates cleanly | [i18n](https://github.com/shadowjs-dev/i18n) | https://i18n.shadowjs.net |
| `@shadow-js/query` | Fetch, cache and update server data with queries, mutations and optimistic updates | [query](https://github.com/shadowjs-dev/query) | https://query.shadowjs.net |
| `@shadow-js/table` | A headless data table with sorting, filtering, pagination, selection and grouping | [table](https://github.com/shadowjs-dev/table) | https://table.shadowjs.net |
| `@shadow-js/virtual` | Headless list and grid virtualization that renders only the rows in view | [virtual](https://github.com/shadowjs-dev/virtual) | https://virtual.shadowjs.net |
| `@shadow-js/motion` | Tween and spring values, exit animations and animated list reordering, driven by signals | [motion](https://github.com/shadowjs-dev/motion) | https://motion.shadowjs.net |
| `@shadow-js/primitives` | Unstyled, accessible building blocks such as dialog, popover, menu, select and tabs | [primitives](https://github.com/shadowjs-dev/primitives) | https://primitives.shadowjs.net |
| `@shadow-js/ui` | shadcn-style components you add to your project with a CLI, styled with Tailwind v4 | [ui](https://github.com/shadowjs-dev/ui) | https://ui.shadowjs.net |
| `@shadow-js/testing` | Testing helpers to render components, query the DOM like a user, fire events and test hooks | [testing](https://github.com/shadowjs-dev/testing) | https://testing.shadowjs.net |
| `@shadow-js/devtools` | A development panel that shows the components, signals, effects and updates of a running app | [devtools](https://github.com/shadowjs-dev/devtools) | https://devtools.shadowjs.net |
| `@shadow-js/eslint-plugin` | ESLint rules for reactivity, ownership and security, and for migrating code from React or Solid | [eslint-plugin](https://github.com/shadowjs-dev/eslint-plugin) | https://eslint.shadowjs.net |
| `@shadow-js/convex` | Use Convex from your app with live queries, mutations, pagination, auth and server rendering | [convex](https://github.com/shadowjs-dev/convex) | https://convex.shadowjs.net |
| `@shadow-js/clerk` | Clerk authentication for your app, with a provider, hooks, UI components and server helpers | [clerk](https://github.com/shadowjs-dev/clerk) | https://clerk.shadowjs.net |

Each repository has a `SKILL.md` with the install command, the import paths and a quick start of its package. Read that one before changing code
that uses the package. To change a package itself, read the `AGENTS.md` of its repository. All packages share one version number.
