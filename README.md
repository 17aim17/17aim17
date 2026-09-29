# Ashish Kumar

Senior engineer at **Addepar**, previously **Twilio**. I work across frontend product and the web platform under it, and I build full stack in TypeScript.

- **Product:** React features end to end, from role-based access control for Twilio Flex to integrating virtual agents, with bot-to-agent handoff, into the Flex contact center.
- **Platform:** microfrontends on Module Federation 2.0, shared data-fetching and caching, build performance (60%+ faster local rebuilds for 100+ engineers), Backstage scaffolding, and CI/CD.
- **Full stack:** Node.js, GraphQL BFFs, Postgres with Prisma, and deploying what I build.

## Featured

**[Biscotti](https://github.com/17aim17/biscotti-platform)**: multi-tenant online ordering for restaurants, with a branded storefront, live kitchen screen and dashboard per restaurant. Tenant data is isolated with Postgres row-level security, prices are computed on the server, and payments are verified through signed webhooks so an order is marked paid exactly once. Next.js, Supabase Postgres, Prisma, Turborepo.<br>
Live: [demo](https://biscotti-sigma.vercel.app)

**[svelte-microfrontend-router](https://github.com/17aim17/svelte-microfrontend-router)**: path-based routing for Svelte 5 microfrontends inside any host framework, keeping the host's router in sync with no hash URLs or global patching. Demo: the same Svelte remote inside React and Vue dashboards, loaded through Module Federation 2.0.<br>
Live: [React host](https://svelte-mfe-react.vercel.app/admin/users) · [Vue host](https://svelte-mfe-vue.vercel.app/admin/users) · [Svelte remote alone](https://svelte-mfe-admin.vercel.app/users)

## Open source

At Twilio, as [@ashishkumarTWLO](https://github.com/ashishkumarTWLO):

- **[twilio-taskrouter.js](https://github.com/twilio/twilio-taskrouter.js)**, the JavaScript SDK for Twilio TaskRouter: made it more resilient and easier to consume. Added retries with exponential backoff and status-code-aware retry, region and edge support that stays backward compatible with existing configs, and TypeScript types generated from JSDoc so the published types stay in sync with the code. Also moved its test and build pipelines (Jenkins, then Buildkite) and handled several releases.
- **[twilio-webchat-react-app](https://github.com/twilio/twilio-webchat-react-app)**: added region support to the web chat's session init and token refresh, upgraded the app and its CI from Node 14 to 18, and made the end-to-end suite run across regions.

## Stack

TypeScript, React, Next.js, TanStack Router, Svelte, Vue, Node.js, GraphQL, Postgres, Prisma, Supabase, Module Federation, Vite, Webpack, pnpm, Turborepo, GitHub Actions, Docker

[LinkedIn](https://linkedin.com/in/ashish17kumar) · ashishkumar87856@gmail.com
