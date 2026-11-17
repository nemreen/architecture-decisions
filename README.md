# Architecture Decisions

A living showcase of my architecture work — published one project at a time.
Each project holds its own ADRs and diagrams. Client-specific details are
generalized. The reasoning is real.

**Ahmed Nemreen** · [nemreen.info](https://nemreen.info)

## Projects

| Project | Focus | Status |
|---------|--------|--------|
| [CMS: Umbraco → Directus](projects/cms-umbraco-to-directus/) | Platform CMS selection | Draft ADR |
| [DGA UI Angular](projects/dga-ui-angular/) | DGA UI (Angular) | Coming soon |
| [Hisn](projects/hisn/) | Hisn | Coming soon |
| [Loopwell](projects/loopwell/) | Loopwell | Coming soon |

## Layout

```
projects/<slug>/
  README.md
  adr/           # decisions for this project (NNN-short-slug.md)
  adr/ar/        # Arabic twins (same numbering)
  arc42/         # full architecture documentation (12 sections)
  diagrams/      # Mermaid sources and exports
```

## Templates

| Template | Path |
|----------|------|
| ADR | [`templates/adr.md`](templates/adr.md) |
| arc42 | [`templates/arc42/`](templates/arc42/) |

ADR numbering is per project. New projects can copy `templates/arc42` into `projects/<slug>/arc42`.
