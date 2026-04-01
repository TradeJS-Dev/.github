# TradeJS

TradeJS is an open-source TypeScript trading framework for:

- strategy authoring
- backtesting
- live signal generation
- optional auto-trading
- AI and ML-assisted workflows

It supports two first-class authoring paths:

- TypeScript strategies built with `StrategyAPI`
- Pine Script strategies embedded as standalone strategy modules

## Public Resources

- Website: [tradejs.dev](https://tradejs.dev)
- Documentation: [docs.tradejs.dev](https://docs.tradejs.dev)
- npm organization: [npmjs.com/org/tradejs](https://www.npmjs.com/org/tradejs)

## Repositories

- [`TradeJS`](https://github.com/TradeJS-Dev/TradeJS) — main monorepo with the core framework, app package, CLI, built-in plugins, infra adapters, and sandbox example
- [`tradejs-site`](https://github.com/TradeJS-Dev/tradejs-site) — public marketing site for `tradejs.dev`
- [`tradejs-docs`](https://github.com/TradeJS-Dev/tradejs-docs) — public external-user documentation for `docs.tradejs.dev`
- [`.github`](https://github.com/TradeJS-Dev/.github) — organization profile and shared GitHub metadata

## Main Package Areas

- `@tradejs/app` — installable Next.js UI for dashboards, backtests, and runtime data
- `@tradejs/cli` — operational CLI for infra setup, backtests, signals, bots, and AI/ML flows
- `@tradejs/core` — browser-safe public API for config, strategy authoring, indicators, and shared helpers
- `@tradejs/node` — Node runtime for strategies, backtests, Pine loading, and plugin registries
- `@tradejs/infra` — server-only adapters for Redis, Timescale, ML, logging, and IO

## Current Structure

Public web surfaces are maintained in separate repositories:

- `tradejs-site` for `tradejs.dev`
- `tradejs-docs` for `docs.tradejs.dev`

The framework source of truth remains in the main [`TradeJS`](https://github.com/TradeJS-Dev/TradeJS) repository.
