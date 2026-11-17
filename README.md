# Architecture Decisions

A living showcase of my architecture work — ADRs, diagrams, reference
architectures, and articles — published one piece at a time.

Each ADR documents the context, options considered, decision, and
consequences, including what I'd reconsider today. Client-specific details
are generalized. The reasoning is real.

**Ahmed Nemreen** · [nemreen.info](https://nemreen.info)

## What's here

| Path | Purpose |
|------|---------|
| [`adr/`](adr/) | Decision records (English) |
| [`adr/ar/`](adr/ar/) | Arabic versions (same numbering) |
| [`diagrams/`](diagrams/) | Mermaid sources and exported images |
| [`reference-architectures/`](reference-architectures/) | End-to-end reference architectures |
| [`articles/`](articles/) | Long-form pieces or links to LinkedIn / nemreen.info |

## Index

| # | Decision | Status | Domain |
|---|----------|--------|--------|
| [001](adr/001-cms-umbraco-to-directus.md) | CMS selection: Umbraco to Directus | Draft | Platform |

## Format

Each ADR follows: Context → Options → Decision → Consequences → Links.

New records start from [`adr/000-template.md`](adr/000-template.md).

### Naming

- English: `adr/NNN-short-slug.md` (e.g. `001-cms-umbraco-to-directus.md`)
- Arabic twin: `adr/ar/NNN-short-slug.md` (same number and slug)
- Diagrams: `diagrams/NNN-short-name.mmd` (+ optional `.png` export)
