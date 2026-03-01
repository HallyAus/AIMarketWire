# Task Tracking

> Quick reference for current work priorities. For detailed issue tracking use Beads (`bd list`).
> This file is for high-level planning; Beads handles granular task management.

## In Progress

_None currently._

## Up Next

### Immediate — Operations
- [ ] Run ingestion batches to clear ~97 unprocessed article backlog
- [ ] Delete `LLM_PROVIDER` env var from Vercel dashboard (has hidden newline)
- [ ] Tune relevance threshold after more data (currently 40)

### Short Term — Enhancements
- [ ] Add search functionality
- [ ] Upgrade to Vercel Pro for hourly cron (currently daily)
- [ ] Set up monitoring/alerting for ingestion failures
- [ ] GitHub release notes for v1.0.0
- [ ] Consider Proxmox worker for more frequent ingestion

### Medium Term — Growth
- [ ] Pagination on homepage and category pages
- [ ] Email newsletter / alerts
- [ ] Ticker detail pages
- [ ] Performance optimisation (target <200ms)
- [ ] Analytics integration

## Blocked

_None currently._

## Done (Recent)

- [x] Versioning system: semver, git tags, CHANGELOG, version badge in footer — 2026-03-01
- [x] Shared Footer component replacing 6 duplicated footers — 2026-03-01
- [x] Security headers (HSTS, X-Frame-Options, etc.) + redirects — 2026-03-01
- [x] Expanded LLM summary prompt (4-6 sentences) — 2026-03-01
- [x] Fix LLM_PROVIDER trailing newline bug — 2026-03-01
- [x] Fix git remote (AI-News → AIMarketWire for Vercel auto-deploy) — 2026-03-01
- [x] SEO-friendly slug URLs replacing UUIDs — 2026-02-28
- [x] Full SEO audit and fix: canonical, OG images, JSON-LD, RSS, sitemap — 2026-02-28
- [x] Article detail, category, about, privacy, terms, 404 pages — 2026-02-28
- [x] Dynamic OG image generation — 2026-02-28
- [x] Deploy to Vercel + Neon, connect aimarketwire.ai domain — 2026-02-27
- [x] Polished dark editorial frontend — 2026-02-27
- [x] First ingestion: 137 articles fetched, 11 published — 2026-02-27
- [x] RSS ingestion pipeline, AI scoring, summary generation — 2026-02-25
- [x] API routes (articles feed + detail with filters) — 2026-02-25
- [x] Next.js 16 scaffold, Drizzle schema, LLM abstraction — 2026-02-25
- [x] Project setup, PRD, 30-day plan, ADRs — 2026-02-25
