# DECISIONS.md — Architecture Decision Records

## ADR-001: Static HTML/CSS/JS (No Framework)

- **Date**: 2026-03-07
- **Decision**: Use plain HTML/CSS/JS instead of a framework (React, Next.js, etc.)
- **Rationale**: PRD specifies a static site for simplicity, performance (<2s load), and easy developer updates. No dynamic content or CMS needed.
- **Consequences**: Fast load times, minimal hosting cost, but content updates require developer intervention.

## ADR-002: Combined Playschool & Daycare Page

- **Date**: 2026-03-07
- **Decision**: Merge playschool and daycare into a single page for clarity.
- **Rationale**: Per PRD, these programs serve the same age group (1.5–5) and operate during the same hours (9am–5pm). A combined page avoids redundancy.
- **Consequences**: Simpler navigation; parents see all relevant info in one place.

## ADR-003: Generated Images for Program Pages

- **Date**: 2026-03-07
- **Decision**: Use AI-generated images as placeholders following PRD photo suggestions, to be replaced with real photos when available.
- **Rationale**: No real photos provided yet. Generated images allow full development without blocking on content delivery.
- **Consequences**: Site launches with high-quality visuals immediately; real photos can be swapped in later.
