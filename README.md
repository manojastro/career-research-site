# Career Research Site

A small single-page site presenting an **AI career-transition roadmap for India (September 2026)**: from
enterprise operations to production AI, in three stages (foundation, portfolio, transition) plus a "start this week" list.
The full source report is in [`report-source.md`](report-source.md).

> Personal content: the page addresses its author by first name. Treat it as a personal project, not a product.

## Stack

React 19 with [vinext](https://www.npmjs.com/package/vinext) (Vite-based Next.js-compatible app router),
TypeScript, a shadcn-style component set under `components/ui`, `oxlint` and `oxfmt`. Hosting config for
Cloudflare Workers (`wrangler`) is included.

## Run

```bash
npm install          # Node >= 22.13
npm run dev
npm run build
npm run lint
```

## Status

The landing page is complete; the page itself says the full study plan, project briefs and job shortlist were still being added.
There are no tests.
