---
name: salamanca-notes
description: >-
  Pull GM running notes for the La Salamanca arc (Chapters 4, 5, 6 — El Patrón,
  El Manuscrito, El Visitante) of the La Tierra Mala campaign. Use whenever Lucas
  asks for "notes", "the cheatsheet", "what happens in chapter 4/5/6", scene
  flow, key dialogue, SAN checks, or table-state reminders for these chapters —
  especially from a phone, at the table, mid-session. Optimized for quick,
  glanceable answers.
---

# La Salamanca — GM Notes (Chapters 4–6)

This skill surfaces **running notes for the La Salamanca arc** so Lucas can ask
for them from his phone while running the table. The notes already exist in the
repo — this skill's job is to read the right file and present it tight and
glanceable. **Never invent table facts.** Everything comes from the files below.

## Source of truth (read these — do not duplicate from memory)

| Need | Read |
|---|---|
| Quick running notes (default) | `02-la-salamanca/cheatsheet.md` — the relevant chapter section |
| Full scene detail / read-aloud boxes / NPC Q&A | `02-la-salamanca/chapter-04-el-patron.md` (C4) · `chapter-05-el-manuscrito.md` (C5) · `chapter-06-el-visitante.md` (C6) |
| Live table state for the whole campaign | `TABLE-STATE.md` (deprecated banner → points back to chapters) · NPC status in `REF-NPCs.md` |

Chapter → file map:

- **Chapter 4 — El Patrón** → `chapter-04-el-patron.md`
- **Chapter 5 — El Manuscrito** → `chapter-05-el-manuscrito.md`
- **Chapter 6 — El Visitante** → `chapter-06-el-visitante.md`

## How to respond

1. **Figure out the ask.** If a chapter number (4/5/6) is given, go straight to
   it. If not, ask which chapter — or, if they say "where are we", default to the
   chapter matching the live table state.
2. **Default to the cheatsheet.** For "notes", "what happens", "scene flow",
   "key dialogue", "SAN checks" → read the matching section of
   `02-la-salamanca/cheatsheet.md` and present it. This is the phone-friendly
   layer — keep it short.
3. **Drill down only when asked.** For a specific scene's read-aloud box, full
   NPC Q&A, manuscript passages, or exact mechanics → read the relevant
   `chapter-0X-*.md` and quote the specific block. Don't dump the whole file.
4. **Lead with the table state.** Every chapter file carries `[THIS TABLE]`
   flags for the C3-divergence state. Surface the relevant one *first* so Lucas
   never reads a beat that no longer runs. The standing state for this arc:
   **Kuyen, Nahuel, the whole tribe, and Concepción are dead; 2 PCs are Marked;
   the party holds only the 75% chapel stone-fragment until the 2nd San Ruiz
   pass (pre-C7); the eastern-panel asymmetry is never corrected.**
5. **Keep both languages.** The chapters are bilingual — read-aloud boxes, NPC
   answers, and setting descriptions have an English original plus an `[ES]`
   Argentine-Spanish rendering. When quoting dialogue or a box, give **both**
   unless Lucas asks for one language only. He may run the table in Spanish.

## Phone-friendly output rules

- Lead with a one-line answer, then the detail. No preamble.
- Prefer tight bullets and short quotes over prose paragraphs.
- For a chapter overview, cap it at: goal → `[THIS TABLE]` flag → scene flow →
  key dialogue → SAN checks → end beat. That's the whole glance.
- Only read the large chapter files when a specific scene/quote is requested —
  the cheatsheet covers the rest and is faster on a phone.
- If asked for a single scene's read-aloud text, quote the box verbatim
  (English + `[ES]`), then the SAN check, and stop.

## Quick reference — what each chapter is

- **C4 El Patrón** — Confront Don Eusebio, break his denial, get the manuscript;
  Silvio (the wrong-returned ranch hand) and the first Wrong Returned at the
  fence. *This table:* party returns via creek bed + cold Rosa first pass.
- **C5 El Manuscrito** — Translate Saens's manuscript, ride to the Jesuit ruins,
  find the carved dual diagram and Saens's bone chamber, plant the Reader-path
  seed (page 79 read aloud). *This table:* Kuyen's warning arrives via the
  goat / Saens's late note / La Llorona, not from Kuyen.
- **C6 El Visitante** — Aldao Quirce arrives, his agenda surfaces (binding *for
  use*, not closing), El Patrón named through him (*"Eligio Dadálah"*), the
  group assembles at the pit. *This table:* Don Eusebio sets the timeline; a
  Marked PC or Marta names the eastern asymmetry in Kuyen's place.
