---
type: map
tags: [map]
---
# Map index

Entry point for the vault. Maps are **hand-curated and opinionated** — an
ordered reading path through `concepts/`, not an auto-generated file listing.
A note can and should appear on several maps. That's the reason these exist
instead of subject folders.

## Subject maps
- [[map-linear-algebra]]
- [[map-real-analysis]]
- [[map-probability]]
- [[map-convex-optimization]]
- [[map-statistical-learning]]

## Not yet split out
These will earn their own map once there are enough atoms to order. Until
then their notes live on the maps above, tagged.

- kernel methods / RKHS — `#kernels`
- graphical models & inference — `#graphical-models`
- concentration & generalization bounds — `#concentration`
- graph algorithms — `#graphs`

> [!tip] When to add a map
> When you catch yourself unable to find a note you know you wrote, or when
> one map's section grows past ~15 entries. Not before.

## Sources
- [[younes-intro-to-ml]]

## Unmapped notes

```dataview
LIST
FROM "notes/concepts"
WHERE !contains(file.inlinks.file.folder, "notes/maps")
SORT file.name ASC
```
