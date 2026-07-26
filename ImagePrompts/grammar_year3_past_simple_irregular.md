# Grammar Comic — Year 3: Past Simple, Irregular Verbs

**ONE image containing all 8 panels.** Story: *"Last Saturday"*.

Source: Get Smart Plus 3, p.89 — the irregular past-tense box, which
lists exactly eight verbs:

```
go   → went      catch → caught
have → had       make  → made
take → took      eat   → ate
swim → swam      see   → saw
```

**One verb per panel, all eight, in the textbook's own set.** That is why
this comic has eight panels rather than any other number — the grammar
box and the layout line up exactly.

Save the approved page into **`komikgrammar/`**, never `koleksigambar/`.
Generate with:

```
python generate_image.py grammar_year3_past_simple_irregular
```

Layout and no-text rules follow `grammar_year3_present_simple.md`.

**Character:** the same boy as the pilot comic would be ideal for
continuity, but he cannot be carried across a separate generation without
drifting, so this comic uses its own clearly-described boy and does not
claim to be the same child.

---

1. **Last Saturday — 8-panel comic page** — `gram_year3_past_simple_irregular_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text between or inside the panels. Read left to right, then down. Each of the eight scenes below appears exactly once — never repeat a scene, never split a scene across two panels, and never show the boy twice inside one panel. The same boy appears in all 8 panels: a Malaysian primary-school boy about nine years old, medium brown skin, short black hair, round friendly face, big dark eyes, wearing a plain yellow t-shirt with no pattern or logo and plain blue shorts. Panel 1, row 1 left: he sits at a kitchen table eating a big breakfast of rice and eggs, looking pleased. Panel 2, row 1 right: he walks onto a sunny sandy beach carrying a bucket, with the sea behind him. Panel 3, row 2 left: he crouches on the sand pointing in surprise at a large orange crab. Panel 4, row 2 right: he swims in clear blue sea water with his arms out, splashing. Panel 5, row 3 left: he sits on the sand eating an ice cream cone and smiling. Panel 6, row 3 right: he holds up a camera taking a photograph of the sea. Panel 7, row 4 left: he kneels beside a large sandcastle he has just built, patting it with both hands. Panel 8, row 4 right: he stands in shallow water holding up a small fish inside a green net, looking delighted. Simple clean uncluttered beach and kitchen backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

---

## Draft captions and speech (for `database.json`, not for the image)

| Panel | Caption (narrator) | Speech bubble | `highlight` |
|---|---|---|---|
| 1 | Last Saturday, Danish **had** a big breakfast. | — | had |
| 2 | He **went** to the beach with his family. | "I went to the beach!" | went |
| 3 | He **saw** a big crab on the sand. | — | saw |
| 4 | He **swam** in the blue sea. | — | swam |
| 5 | He **ate** an ice cream. | — | ate |
| 6 | He **took** a photo of the sea. | — | took |
| 7 | He **made** a big sandcastle. | — | made |
| 8 | He **caught** a small fish in his net. | "I caught a fish!" | caught |

**Rule card:** *Most verbs add **-ed** for the past. But some verbs are
irregular — they change completely and you must learn them: go → went,
have → had, see → saw, eat → ate.*

**ruleExamples:** `go → went` / `have → had` / `see → saw` / `eat → ate`
/ `swim → swam` / `catch → caught`

**Check questions:**
1. Yesterday I ______ to the beach. → *went*
2. He ______ a big crab on the sand. → *saw*
3. She ______ an ice cream after lunch. → *ate*
