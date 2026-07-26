# Grammar Comic — Year 3: Present Simple (third person *-s*)

**PILOT COMIC — ONE image containing all 8 panels.** Story: *"Ravi's Busy
Morning"*.

One prompt produces one comic page laid out as a grid of 8 small panels.
Not eight separate files. Because the whole page is drawn in a single
pass, Ravi is the same boy in every panel by construction — which is the
biggest quality problem with comics, solved for free.

Save the approved page into **`komikgrammar/`** — **NOT**
`koleksigambar/`. That folder is read-only, and its
`basic_<level>_<topic>_<word>` filenames drive automatic vocab
generation, so a comic page dropped there would be misread as a
dictionary entry. The `gram_` prefix is the second layer of protection.

Generate with the existing script, unchanged:

```
python generate_image.py grammar_year3_present_simple
```

The image lands in `koleksigambar_new/` for review first, as usual.

## The image must contain no text at all

Not even empty speech balloons. Every caption and line of dialogue lives
in `database.json` and is drawn over the art by the app — that is what
lets it be translated into Bahasa Melayu / Chinese / Iban and spoken
aloud by TTS. Text painted into a PNG can do neither.

There is a practical reason too: models asked to draw speech balloons
almost always fill them with nonsense lettering. The 8-separate-panel
test run proved the risk is real — one panel came back with gibberish on
its book spines, so the prompt below explicitly calls out blank spines.

If the page comes back with any lettering in it, regenerate.

## Layout — verified against the accepted page

- **4 rows × 2 columns.** Reading order: left to right, then down.
- Measured output: **1200×896**, slicing into 8 panels of **560×207/208**
  — uniform to within one pixel. Confirmed by cropping, not just by
  measuring: every panel comes out cleanly with its border intact and no
  bleed from its neighbours.
- That means the app **can** slice the page and show one panel at a time,
  rather than being stuck displaying the whole sheet.

### The wording that made it work

The first attempt at a single page produced **~12 panels with duplicates**
(three brushing-teeth panels, two bag-packing panels) on an uneven grid.
Four additions fixed it, and should be reused for every other comic:

1. **"EXACTLY EIGHT panels and no more"** — in capitals.
2. **State the arithmetic**: "4 rows with exactly 2 panels in each row, so
   4 rows times 2 columns equals 8 panels in total."
3. **"Every panel is exactly the same width and exactly the same height"**
   — this is what makes the result sliceable.
4. **"Each scene appears exactly once — never repeat a scene, never split
   a scene across two panels, and never show the boy twice inside one
   panel."** This is what killed the duplicates.

Positions are given per panel as *"row N left"* / *"row N right"* rather
than "top left"/"bottom right", which the model read more reliably.

### Gutters must be measured per page, not assumed

The gutter positions above belong to *this* page. Another generated comic
will land its gutters a few pixels differently, so the database step
should **detect** them (scan for near-white rows/columns) and store the 8
panel rectangles as fractions of the image, rather than hardcoding a
uniform 4×2 split.

## Clothing is specified as PLAIN on purpose

The 8-separate-panel test drifted badly on clothing — three different
pyjama patterns across three consecutive panels, a crest badge on one
shirt, a Malaysian flag on another, a floral backpack in the last one.
The cause was loose wording: *"light blue pyjamas"* invites the model to
invent a pattern, and it invented a new one each time.

Every garment below is therefore pinned as **plain, no pattern, no badge,
no logo**. Plain reproduces far more reliably than any print.

## The grammar being taught

Every caption describes Ravi in the third person, so the *-s* ending
lands nine times: **wakes, brushes, eats, packs, walks, leaves, runs,
arrives, smiles**. Panel 5 is the teaching moment — Ravi's own line is
*"I walk to school every day!"* while the caption reads *"He walks to
school."* That contrast between *I walk* and *he walks* **is** the rule,
shown before it is ever stated.

---

1. **Ravi's Busy Morning — 8-panel comic page** — `gram_year3_present_simple_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page containing EXACTLY EIGHT panels and no more. The layout is a strict regular grid of 4 rows with exactly 2 panels in each row, so 4 rows times 2 columns equals 8 panels in total. Every panel is exactly the same width and exactly the same height as every other panel, separated by even white gutters and thin dark borders. Read left to right, then down. Each of the eight scenes below appears exactly once — never repeat a scene, never split a scene across two panels, and never show the boy twice inside one panel. The same boy appears in all 8 panels: a Malaysian primary-school boy about nine years old, medium brown skin, short neat black hair, round friendly face, big dark eyes. In panels 1 to 3 he wears plain light blue pyjamas with no pattern. In panels 4 to 8 he wears a plain white school shirt with a dark blue collar and no badge or logo, plain dark blue shorts, and a plain red backpack. Panel 1, row 1 left: he wakes up in bed stretching his arms sleepily while a round alarm clock rings on the bedside table. Panel 2, row 1 right: he brushes his teeth at a bathroom sink in front of a mirror. Panel 3, row 2 left: he sits at a kitchen table eating roti canai with a glass of milk while his mother places a bowl beside him. Panel 4, row 2 right: he kneels on the living room floor packing books into his open red backpack. Panel 5, row 3 left: he walks cheerfully along a neighbourhood pavement waving one hand, with trees and small houses behind him. Panel 6, row 3 right: he stops with a shocked worried face staring at his wristwatch while a yellow school bus drives away in the distance. Panel 7, row 4 left: he runs as fast as he can along the road with a determined face and cartoon motion lines behind him. Panel 8, row 4 right: he arrives at an open school gate out of breath but smiling, greeted by a friendly female teacher wearing a headscarf. Simple clean uncluttered backgrounds, and any books shown must have completely blank plain spines. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

---

## Draft captions and speech (for `database.json`, not for the image)

English source lines only — ms/zh/iba get authored at the database step.

| Panel | Caption (narrator) | Speech bubble | `highlight` |
|---|---|---|---|
| 1 | Every morning, Ravi **wakes** up at six o'clock. | — | wakes |
| 2 | He **brushes** his teeth. | — | brushes |
| 3 | He **eats** roti canai for breakfast. | — | eats |
| 4 | He **packs** his books into his bag. | — | packs |
| 5 | He **walks** to school. | "I walk to school every day!" | walks |
| 6 | Oh no! The bus **leaves** without him. | "I am late!" | leaves |
| 7 | He **runs** very fast. | — | runs |
| 8 | He **arrives** just in time. His teacher **smiles**. | "Good morning, Ravi!" | arrives |

**Rule card (shown after panel 8):** *When we talk about one other person
— he, she, or it — we add **-s** to the verb. I walk → He walk**s**. I
eat → He eat**s**.*

**Check questions (3):** to be drafted at the database step, once the
page is approved.
