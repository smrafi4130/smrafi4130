# Rafi

**Angular-focused frontend engineer.** I build maintainable, accessible, well-tested web applications, and I care about the parts of frontend work that decide whether a codebase stays changeable: component architecture, state ownership, module boundaries, API contracts and testing strategy.

Angular is my primary stack; I also work across the broader frontend ecosystem (React/Next.js, TypeScript tooling), and the projects below show both.

## Angular

| Project | What it demonstrates |
|---|---|
| [**angular-enterprise**](https://github.com/smrafi4130/angular-enterprise) | Angular 19 issue tracker: standalone components, **signals** for state, **RxJS** for data flow + optimistic updates, typed reactive forms, **functional guards & HTTP interceptors**, a permission-based structural directive, lazy-loaded routes, role-based access. Karma tests + CI. |
| [**angular-ui-kit**](https://github.com/smrafi4130/angular-ui-kit) | Accessible component library (`@smrafi/ui`): standalone components on **Angular CDK**, token-driven light/dark theming, packaged with **ng-packagr**, documented in **Storybook** (a11y addon), Karma tests + CI. |
| [**angular-ngrx**](https://github.com/smrafi4130/angular-ngrx) | **NgRx** state management done idiomatically: entity adapter, action groups, pure reducer, **memoized selectors** + derived state, **effects** isolating async work. Reducer/selector/effects tests + CI. |
| [**music-school-web**](https://github.com/smrafi4130/music-school-web) | Earlier Angular application (Angular 7) — longer-standing Angular experience. |

## Broader frontend (React / Next.js / TypeScript)

| Project | What it demonstrates |
|---|---|
| [**feedback-board**](https://github.com/smrafi4130/feedback-board) | Full-stack Next.js App Router app: Server Components + Server Actions, Postgres via Drizzle, cookie auth, tag-based caching; unit, DB-integration and Playwright E2E tests. |
| [**enterprise-react-app**](https://github.com/smrafi4130/enterprise-react-app) | React + TypeScript app: feature-based structure with lint-enforced boundaries, permission-based RBAC, typed API client with token refresh, three test layers. |
| [**react-design-system**](https://github.com/smrafi4130/react-design-system) | Design tokens + accessible primitives, Storybook, Playwright visual regression, Changesets versioning. |
| [**performance-lab**](https://github.com/smrafi4130/performance-lab) | Measured performance case study: the same dashboard naive vs optimized, with reproducible Lighthouse + bundle before/after results. |

## Engineering writing
[**frontend-architecture**](https://github.com/smrafi4130/frontend-architecture) — case studies and ADRs on app architecture, rendering strategies, caching, Core Web Vitals, frontend security, real-time and observability (framework-agnostic).

## How I work
- **Decisions are written down.** Non-obvious choices get an ADR with alternatives and consequences.
- **Accessibility is tested** — keyboard flows, ARIA wiring, axe — not assumed.
- **Boundaries and quality are enforced by tooling**, not convention (lint rules, typecheck, CI on every repo).
- Each repository's README states what is implemented, what is not, and the trade-offs made.

## Contact
<!-- Add your preferred public contact (LinkedIn, website, email) here. -->
