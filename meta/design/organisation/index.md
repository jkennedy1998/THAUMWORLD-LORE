# organization
> how the repo is organized

> > scale : design
> > age : meta
> > ages : meta
> > facets :
      facet_example : <https://www.thaumworld.world/meta/design/organisation/facet_example>

---

## nutshell
Files are organized by scale.
Canon-facing folders hold in-universe writing.
`meta/` holds planning, notes, and non-public work.

Each folder is a page through its local `index.md`.
If a page gets too dense, split detail into facet files or child folders.

---

## scale_ladder
- universe
- galaxy
- solar_system
- celestial_body
- map
- region
- place

All scales may have child folders.
Celestial bodies link directly to maps.
Maps contain regions.
Regions contain places.
A thing should live at the smallest scale that meaningfully owns it.

---

## file_header
The header of each `index.md` gives page context.
Use it to declare scale, age, child ages, and linked facets.

---

## facets
Facets are sibling markdown files used to split content by type.
Use the canonical facet list:

- geography.md
- culture.md
- life.md
- technology.md
- thaumatry.md
- characters.md
- places.md
- science.md

Not every page needs every facet.
Use facets only when they improve readability.

---

## scale_use
- `map` : mostly a travel area
- `region` : mostly a local cluster
- `place` : mostly a single owned site

## promotion
A thing grows like this:
- mention
- list entry
- promoted page

Parent pages summarize and link.
Child pages hold detail.
