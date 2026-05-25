# Repo Rules

## Core writing philosophy
- everything in the repo is canonical
- pages describe reality, records, and events that canonically exist
- scale determines where content lives
- celestial bodies link directly to maps
- maps are mostly travel areas
- regions are mostly local clusters
- places are mostly single owned sites
- time determines when content is relevant, visible, or true in context
- subpages handle specificity, not uncertainty
- formatting should stay lightweight and minimal
- structure should be readable by humans, agents, and future tools

## Canon-facing folders
Use canon-facing folders for in-universe writing only.
Keep pages factual, scale-bound, and time-bound.

## Canon page voice
- canon pages are reader-facing, not writer-facing
- write as if describing the world to someone learning it, not as planning notes to ourselves
- lead with what a traveler, resident, or listener would notice first
- keep classification and scaffolding language out of prose when possible
- use `meta/` for writer-facing notes like routing, uncertainty, TODOs, or implementation framing

### Nutshell style
- the `nutshell` should read like a short setting introduction
- it should be evocative first and structural second
- prefer concrete world-facing language over organizer language
- good `nutshell` text tells the reader what the place feels like, what defines it, and why it matters
- put raw reference facts in detail rows, not in stiff summary prose

### Avoid in canon prose
- "this page contains"
- "this map contains"
- "written settlement"
- "broad travel and trade space"
- other repo-facing or implementation-facing phrasing unless truly necessary

## `meta/`
Use `meta/` for non-public work.
This is the messy planning zone.

Allowed in `meta/`:
- plans
- schema notes
- spitballs
- sorted buckets
- refinement drafts
- migration work

Use these subfolders:
- `docs/` : locked internal repo rules
- `plans/` : active implementation plans
- `design/` : schema and structure thinking
- `migration/` : lore being prepared for canon folders
- `todo/` : future topics, questions, and loose targets

## Working flow
- spitball into `todo/` or a working note
- sort and shape in `migration/`
- refine
- place into the repo

## Agent rule
Agents should not invent lore.
They should help organize, question, evaluate, and maintain the repo.
