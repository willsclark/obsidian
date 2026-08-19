<%*
// Router for notes/concepts. Folder templates map one folder to one template,
// but concepts/ is flat and holds four archetypes -- so ask, then delegate.
const kind = await tp.system.suggester(
  ["Definition  — one definition, plus its non-example",
   "Theorem     — one statement, plus what breaks without each hypothesis",
   "Object      — a thing you keep meeting; grows for years",
   "Bridge      — two things that are secretly the same"],
  ["definition", "theorem", "object", "bridge"],
  false,
  "What kind of atom is this?"
);
if (kind) {
  tR += await tp.file.include("[[" + kind + "]]");
} else {
  tR += "";  // cancelled -- leave the note empty rather than guessing
}
_%>
