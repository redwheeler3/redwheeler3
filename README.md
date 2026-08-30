## Hi, I'm Jeff Oriecuia

I'm a product manager based in Vancouver, BC. I work on cloud platforms, APIs, and developer-facing products, and I build and operate my own software to stay close to how products actually get made.

The repos here are personal projects built around real problems for me and the people around me. I take them from problem definition and product decisions through implementation, production, and iteration. I use AI coding agents heavily, while treating model behaviour, evals, guardrails, observability, cost, and human accountability as product requirements rather than demo polish.

### What you'll find here

- **[penta-application-screener](https://github.com/redwheeler3/penta-application-screener)** — Production React and FastAPI system used by the Penta Housing Co-op to run its application lifecycle, from public intake and eligibility screening through committee review, applicant outcomes, and retention. Its AI pipeline discovers pool-specific criteria and extracts evidence-backed scores, while deterministic ranking math and committee-controlled weights keep decisions human-owned. Content-addressed caching, up-front spend caps, prompt versioning, per-call traces, and live-model evals make model quality and cost inspectable.
- **[investment-rebalancer](https://github.com/redwheeler3/investment-rebalancer)** — Python tool that rebalances Questrade brokerage accounts. Talks to Questrade's token-based API, handles OAuth refresh automatically, aggregates accounts into one portfolio view, and generates trade and FX recommendations.
- **[google-official-mcp-oauth](https://github.com/redwheeler3/google-official-mcp-oauth)** — A small adapter that connects MCP clients like Claude Code, Codex, and Cline to Google's official Gmail, Calendar, and Drive MCP servers. It handles the OAuth token lifecycle and protocol translation between local stdio and remote HTTP. Not a full server, just the plumbing that closes a real interop gap.
- **[penta-coop-website](https://github.com/redwheeler3/penta-coop-website)** — Public Eleventy site for Penta Housing Co-Op with responsive pages, vacancy notifications, application-service integration, GA4 analytics, and GitHub Pages deployment. Live at [pentacoop.com](https://pentacoop.com).
- **[jeffo-website](https://github.com/redwheeler3/jeffo-website)** — My personal site and portfolio hub. Live at [jeffo.net](https://www.jeffo.net).

### Elsewhere

- Site: [jeffo.net](https://jeffo.net)
- LinkedIn: [in/jefforiecuia](https://www.linkedin.com/in/jefforiecuia/)
