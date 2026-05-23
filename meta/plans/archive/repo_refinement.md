# Repo Refinement

The repo already has the core scale-first shape and a live GitHub Pages flow. This plan exists to lock the lean internal docs before heavy lore transfer begins, so humans and agents can read the repo once, understand the rules, and route future content cleanly. Current blocker: the standards we locked in chat are not yet written into files.

## Status key
- `[ ]` not done
- `[+]` implemented
- `[#]` tested

## Phase 1 — write the lean internal docs
- [+] Create `README.md` at repo root for human repo entry, with a short explanation of canon, scale, time, and navigation.
- [+] Create `AGENTS.md` at repo root for agent behavior, including: do not invent lore, organize by scale, use time context, ask questions to develop missing areas, and use `meta/` as the messy planning zone.
- [+] Create `meta/docs/index.md` as the one place to send humans or agents for internal repo rules.
- [+] Create `meta/docs/repo_rules.md` for the core writing philosophy and what belongs in canon-facing folders vs `meta/`.
- [+] Create `meta/docs/structure.md` for scales, facets, promotion, ownership, and linking rules.

## Phase 2 — write the locked standards into docs
- [+] Write the core writing philosophy into `meta/docs/repo_rules.md`.
- [+] Write the canonical scale ladder into `meta/docs/structure.md`: universe, galaxy, solar_system, celestial_body, region, place.
- [+] Write the canonical facet list into `meta/docs/structure.md`: geography, culture, life, technology, thaumatry, characters, places, science.
- [+] Write the ownership rule into `meta/docs/structure.md`: a thing lives at the smallest scale that meaningfully owns it.
- [+] Write the promotion rule into `meta/docs/structure.md`: mention -> list entry -> promoted page.
- [+] Write the linking rule into `meta/docs/structure.md`: parent summarizes and links downward, child owns detail and links upward.

## Phase 3 — update existing repo guidance to match the new rules
- [+] Update `meta/design/organisation/index.md` to add `place` as a formal scale and align the organization notes to the new scale ladder.
- [+] Update `meta/design/organisation/facet_example.md` or replace its role so it reflects the canonical facet vocabulary.
- [+] Update `meta/design/sample_formatting/index.md` only if needed so its examples match the current structure language.
- [+] Review `index.md` at repo root and keep it website-facing, but make sure it does not conflict with the new internal docs.

## Phase 4 — update scale-bound canon pages where structure language is stale
- [+] Review `thaum world/index.md` for stale structure words or facet language that conflicts with the locked standards.
- [+] Review `thaum world/the great violet spiral/index.md` for stale structure words or child-scale wording.
- [+] Review `thaum world/the great violet spiral/lux/index.md` for stale structure words or child-scale wording.
- [+] Review `thaum world/the great violet spiral/lux/gorath/index.md` for region/place wording, child links, and facet wording that should reflect the new standards.
- [+] Add `place` expectations only where they matter now, without creating empty lore structure just to satisfy the schema.

## Phase 5 — define the working `meta/` pipeline
- [+] Create a lean `meta` intake flow in docs: spitball -> sort into buckets -> refine -> place in repo.
- [+] Decide the subfolders needed under `meta/` for active use, keeping them minimal.
- [+] Reserve `meta/plans/` for active implementation plans only.
- [+] Keep non-public writing, schema work, and messy progress files inside `meta/`.

## Phase 6 — test the structure with real navigation and one small content pass
- [#] Verify that a new agent could start from `README.md`, `AGENTS.md`, and `meta/docs/index.md` without extra chat context.
- [#] Verify that the structure docs are lean and non-redundant.
- [#] Verify that the scale and facet rules are enough to route a sample lore note without ambiguity.
- [+] After docs are stable, begin the first small lore migration through the `meta` pipeline instead of writing directly into canon folders.
