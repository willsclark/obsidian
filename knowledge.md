A repository of my learnings, studies, and coursework.

Organization:

Notes:
- concepts : _atoms_
- maps :  _topical entry points_
- lit : _one note per source_
- problems: _worked exercises_

Source: _PDFs_
Templates: _one per note archetype_

Start here: [[map-index]]

---

## Conventions

**One note, one idea.** An atom is one thing you could be quizzed on. If a
note needs "and" in its title, it's two notes.

**No subject folders.** Subject lives in tags and maps, because the
interesting concepts have several legitimate parents — spectral clustering is
linear algebra *and* graph theory *and* probability. Folders force one choice;
`concepts/` stays flat.

**Four archetypes**, one template each:

| Archetype  | Holds                              | The section that matters                 |
| ---------- | ---------------------------------- | ---------------------------------------- |
| definition | one definition                     | the **non-example**                      |
| theorem    | one statement                      | **what breaks** if you drop a hypothesis |
| object     | a thing you keep meeting           | **where it shows up** (grows for years)  |
| bridge     | two things that are the same thing | **what transfers**                       |

**Typed links, in the body not the frontmatter**, so they render clickable and
Dataview can query them:

- `requires::` — prerequisite. This graph is the review-what-I-forgot map.
- `generalizes::` / `specializes::`
- `tension-with::` — results that pull against each other
- `connects::` — bridge notes only
- `source::` — `[[lit-note]]` §x.y plus `[[file.pdf#page=N]]`

**Words before symbols.** State the idea in prose first, since notation differs.

**Creating a note.** Templater applies a template by folder, so just make the
file in the right place — `Cmd+N` inside `concepts/` prompts for the archetype,
`lit/` `problems/` `maps/` each stamp their one template automatically. Never
link `[[theorem]]` from a concept note; the archetype is recorded as
`type:` in the frontmatter, which is the queryable version.

**Lit notes are disposable.** They follow the book's order so atoms don't have
to. Read sequentially into `lit/`, then extract. Maps never link into `lit/`.

Established: _18 August, 2026_
