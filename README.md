# Ilya Semenov

I'm a software engineer working mostly with TypeScript/Node.js, PostgreSQL, and Vue/Nuxt. Most of my open-source libraries and tools grew out of problems I encountered in real projects.

Here's what I've built:

## TypeScript and Node.js

### General-purpose libraries

- [`ripple-di`](https://github.com/IlyaSemenov/ripple-di) — Next-generation DI for TypeScript with async scopes, transitive overrides, and automatic resource cleanup.
- [`async-dedupe`](https://github.com/IlyaSemenov/async-dedupe) — Deduplicate concurrent calls to an async function.
- [`json-mark`](https://github.com/IlyaSemenov/json-mark) — Serialize custom JSON types using tagged strings.
- [`intl-formats`](https://github.com/IlyaSemenov/intl-formats) — Functional wrappers around `Intl.DateTimeFormat` and `Intl.NumberFormat`.
- [`valibotx`](https://github.com/IlyaSemenov/valibotx) — Tree-shakeable extensions for Valibot.

<details>
<summary><strong>Earlier work</strong></summary>

- [`node-data-cleaner`](https://github.com/IlyaSemenov/node-data-cleaner) (`data-cleaner`, `data-cleaner-koa`) — **Abandoned.** Async validation and transformation toolkit, superseded in my projects by Valibot and `valibotx`.
- [`node-unpickle`](https://github.com/IlyaSemenov/node-unpickle) — Read Python 3 pickle data from Node.js.
- [`dayjs-isodate`](https://github.com/IlyaSemenov/dayjs-isodate) — Add `toISODate()` to Day.js.

</details>

### Backend, PostgreSQL, and GraphQL

- [`pg-event-bus`](https://github.com/IlyaSemenov/pg-event-bus) — Typed real-time events over PostgreSQL `LISTEN`/`NOTIFY` for cache invalidation and live updates.
- [`pg-advisory-lock`](https://github.com/IlyaSemenov/pg-advisory-lock) — Coordinate exclusive work across application instances with PostgreSQL session-level advisory locks.
- [`graphile-worker-tasks`](https://github.com/IlyaSemenov/graphile-worker-tasks) — Organize, collect, and test Graphile Worker tasks.
- [`graphile-worker-orchid`](https://github.com/IlyaSemenov/graphile-worker-orchid) — Use Graphile Worker with Orchid ORM.
- [`orchid-pagination`](https://github.com/IlyaSemenov/orchid-pagination) — Page-number and cursor pagination helpers for Orchid ORM.
- [`graphql-orm`](https://github.com/IlyaSemenov/graphql-orm) (`objection-graphql-resolver`, `orchid-graphql`) — Resolve GraphQL queries against Objection.js or Orchid ORM tables and relations.
- [`graphql-define-resolvers`](https://github.com/IlyaSemenov/graphql-define-resolvers) — Collect strongly typed GraphQL query and mutation resolvers across modules.
- [`h3-errors`](https://github.com/IlyaSemenov/h3-errors) — Assertion and error helpers for HTTP 4xx/5xx responses in H3.
- [`h3-jwt-auth`](https://github.com/IlyaSemenov/h3-jwt-auth) — Basic JWT authentication helpers for H3 and Nuxt.
- [`h3-websocket-request`](https://github.com/IlyaSemenov/h3-websocket-request) — H3 WebSocket handlers that can request additional client-side data while processing a request.

<details>
<summary><strong>Earlier work</strong></summary>

- [`objection-reorder`](https://github.com/IlyaSemenov/objection-reorder) — Reorder PostgreSQL-backed rows through Objection.js.
- [`koa-mount-final`](https://github.com/IlyaSemenov/koa-mount-final) — Prevent matched but unhandled Koa sub-routes from falling through to later middleware.

</details>

### Vue and Nuxt

- [`vue-form-submit`](https://github.com/IlyaSemenov/vue-form-submit) — Small Vue 3 composables for form submission and optional Standard Schema validation.
- [`vue-router-navigation`](https://github.com/IlyaSemenov/vue-router-navigation) — Navigation helpers for deeply nested Vue Router paths.
- [`orpc-nuxt`](https://github.com/IlyaSemenov/orpc-nuxt) — oRPC integration for Nuxt with TanStack Vue Query composables.
- [`nuxt-request-context`](https://github.com/IlyaSemenov/nuxt-request-context) — Provide typed request-specific data to Nuxt before the initial render.
- [`nuxt3-class-component`](https://github.com/IlyaSemenov/nuxt3-class-component) — Class-component support for Nuxt 3/4 and a migration path from `nuxt-property-decorator`.
- [`nuxt-update`](https://github.com/IlyaSemenov/nuxt-update) — Detect deployed Nuxt application updates and notify or refresh clients.
- [`nuxt-vite-legacy`](https://github.com/IlyaSemenov/nuxt-vite-legacy) — Legacy-browser support for Nuxt 3 through Vite's legacy plugin.

<details>
<summary><strong>Earlier work</strong></summary>

- [`nuxt-stash`](https://github.com/IlyaSemenov/nuxt-stash) — Expose server-generated Nuxt context to Vue components without a full Vuex setup.
- [`vue-observable-persist`](https://github.com/IlyaSemenov/vue-observable-persist) — Persist Vue observable state to `localStorage` or compatible storage.
- [`ream-typescript`](https://github.com/IlyaSemenov/ream-typescript) — TypeScript support for Ream.js.

</details>

### Telegram libraries

- [`grammy-scenes`](https://github.com/IlyaSemenov/grammy-scenes) — Scene-based conversations for grammY.
- [`grammy-pseudo-update`](https://github.com/IlyaSemenov/grammy-pseudo-update) — Inject manually generated `Update` objects into grammY middleware.

### Solana

- [`h3-websocket-anchor-wallet-request`](https://github.com/IlyaSemenov/h3-websocket-anchor-wallet-request) — Request client-side Anchor Wallet transaction signing from an H3 server handler.

## Applications and integrations

- [`git-telegram-bot`](https://github.com/IlyaSemenov/git-telegram-bot) — Forward GitHub and GitLab webhook events to Telegram, including workflows, pipelines, and branch filtering.
- [`terneo-ha`](https://github.com/IlyaSemenov/terneo-ha) — Local Home Assistant integration for Terneo thermostats, without a cloud dependency.
- [`wikipedia-word-frequency`](https://github.com/IlyaSemenov/wikipedia-word-frequency) — Generate multilingual word-frequency datasets from Wikipedia dumps.

## Tooling and automation

### Development tooling

- [`bunlock-dedupe`](https://github.com/IlyaSemenov/bunlock-dedupe) — Analyze and deduplicate dependencies in `bun.lock`.
- [`vite-plugin-module-boundaries`](https://github.com/IlyaSemenov/vite-plugin-module-boundaries) — Fail Vite builds when imports cross configured filesystem boundaries.
- [`eslint-config`](https://github.com/IlyaSemenov/eslint-config) — Reusable ESLint configuration for projects I develop or oversee.
- [`eslint-plugin-import-remap`](https://github.com/IlyaSemenov/eslint-plugin-import-remap) — Remap imports with ESLint autofixes.
- [`stylelint-config`](https://github.com/IlyaSemenov/stylelint-config) — Reusable Stylelint configuration for projects I develop or oversee.
- [`tsconfig-vite-node`](https://github.com/IlyaSemenov/tsconfig-vite-node) — Opinionated TSConfig for Node applications run with `vite-node` or built with Vite.
- [`npm-package-starter`](https://github.com/IlyaSemenov/npm-package-starter) — Scaffold and synchronize production TypeScript npm packages from reusable conventions.

### Agent skills

- [`agent-review-skill`](https://github.com/IlyaSemenov/agent-review-skill) — Iterative code, diff, and plan reviews through another CLI coding agent.
- [`pi-transcript-skill`](https://github.com/IlyaSemenov/pi-transcript-skill) — Extract clean conversational transcripts from pi.dev session files.

### Infrastructure and deployment

- [`gitlab-ci-git-push`](https://github.com/IlyaSemenov/gitlab-ci-git-push) — Push repository changes from GitLab CI.

<details>
<summary><strong>Earlier work</strong></summary>

- [`dokku-static-site`](https://github.com/IlyaSemenov/dokku-static-site) — Static-site deployment on Dokku.
- [`dokku-refuse-unknown-domains`](https://github.com/IlyaSemenov/dokku-refuse-unknown-domains) — Reject unknown hostnames in Dokku.
- [`dokku-solr`](https://github.com/IlyaSemenov/dokku-solr) — Solr service integration for Dokku.
- [`nfs-provisioner-chart`](https://github.com/IlyaSemenov/nfs-provisioner-chart) — Helm chart for an NFS provisioner.

</details>

## Python, Django, and aiohttp

<details>
<summary><strong>Earlier work</strong></summary>

- [`django-modelsettings`](https://github.com/IlyaSemenov/django-modelsettings) — Database-backed, typed application settings editable through Django admin.
- [`django-templates-admin`](https://github.com/IlyaSemenov/django-templates-admin) — Manage editable templates through Django admin.
- [`django-everlasting-sessions`](https://github.com/IlyaSemenov/django-everlasting-sessions) — Long-lived Django sessions.
- [`django-sequential-pagination`](https://github.com/IlyaSemenov/django-sequential-pagination) — Sequential pagination helpers for Django.
- [`django-minimal-abstract-user`](https://github.com/IlyaSemenov/django-minimal-abstract-user) — Minimal abstract Django user model with admin and permissions support.
- [`django-object-utils`](https://github.com/IlyaSemenov/django-object-utils) — Race-safe helpers for reloading, updating, and locking Django model objects.
- [`django-uuid-upload`](https://github.com/IlyaSemenov/django-uuid-upload) — UUID-based upload paths for Django.
- [`python-edost`](https://github.com/IlyaSemenov/python-edost) — Python integration for the eDost delivery service.
- [`aiohttp_session_flash`](https://github.com/IlyaSemenov/aiohttp_session_flash) — Flash messages for aiohttp sessions.

</details>
