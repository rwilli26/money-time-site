# Fingerprints

Every site you build with **scroll-craft** gets one row here, appended after it
ships. The registry exists so your next build can prove it is a different page
rather than a re-skin of one you already made.

This file is **yours**. It starts empty on purpose: the gate is about not
repeating *yourself*, so it has nothing to say until you have built something.

The rules and the gate live in the skill's
`references/uniqueness.md`. Short version:

**A new build must differ from EVERY row below on at least 4 of the 6
dimensions.** Four against each row individually, not four on average across the
table. If a planned build fails, change the plan. Never edit a row to make room
for it.

The six dimensions are: **grammar**, **nav treatment**, **hero device**,
**act-sequence shape**, **close pattern**, **signature move**.

Dimension 6 is free, because a signature move is unique by definition. So the
gate really asks for three more out of the remaining five, and a build that
changes only grammar and world will fail it.

---

## The registry

| Build | Grammar | Nav treatment | Hero device | Act-sequence shape | Close pattern | Signature move | World | Port |
|---|---|---|---|---|---|---|---|---|
| money-time/ledger (A, The Cover) | Chaptered editorial | Left-margin folio of chapter links; phone: thin top folio strip | Magazine cover, pinned 2.4vh: guilloche ground, Didone masthead, cutout cover star, cover lines; chapter I slides over as a page turn | pin cover > 5 flow chapters with hard ground cuts (bone, forest, bone, tan, bone), about 8.7vh | Colophon, CTA as running-text link | Cover lines fly off the cover and land as the folio's chapter links | Photographic cutout on engraved banknote paper | Static HTML |
| money-time/application (B, The Application) | Live surface | App chrome: dark status bar with completeness meter + section sidebar with checkboxes | Section A of a grant form already filled in; clipped photo with paper clip and RECEIVED stamp as separate planes | Single flow sheet, 7 form sections, about 4.4vh, no pinning | A real input: business name + email, submit handled in page | Typed business name set live into an approval seal | Paper form on folder-grey desk | Static HTML |
| money-time/hourglass (C, The Hourglass) | Split stage | The divider is the chrome: side labels, hourglass, row dots | 50/50 split: cold typographic left, warm gold right with rear sand, cutout, front sand | One pin, 6.2vh, 5 crossfading row pairs then collapse | Collapse: divider sweeps to the edge, Money Time takes full width, CTA in the winning side | Working hourglass on the divider pours grey sand into gold; last grain flips it and triggers the collapse | Dark warm-gold photographic | Static HTML |

Shared between rows: all three use the same cutout of Ebonie and the same CTA label ("Get the checklist"). A and C both use a pinned hero with a cutout subject; they differ on grammar, nav, sequence shape, close and signature (5 of 6). B differs from both on all six.

---

## What is taken

Add a bullet here whenever a build claims something a later build should avoid
reusing: a grammar, a nav treatment, a close pattern, a signature move, an
act-count-and-length band. The shared columns are what the next build inherits
as a constraint, so writing them down is the whole point.

- Chaptered editorial with a magazine-cover hero and cover-lines-to-folio flight (A).
- Live surface as a grant application with a live approval seal (B).
- Split stage with an hourglass divider and collapse close (C).

---

## Appending a row

After shipping, add one line to the table and one bullet to **What is taken** if
the build claimed something new. Fill every column. Say what the build shares
with existing rows.

Rows are append-only. A build that has been superseded stays in the table,
because the space it occupies is still occupied.

---

## Worked example

The skill's author kept a registry of twelve builds across eight page grammars.
If you want to see what a filled-in table looks like, and which shapes tend to
collide, read `EXAMPLES.md` in the scroll-craft repository. Treat it as
illustration only: those rows are somebody else's builds and they do **not**
constrain yours.
