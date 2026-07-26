# Grammar Comic — Year 3: Adverbs of Frequency (always / sometimes / never)

**ONE image containing all 8 panels.** Story: *"Mira's Week"*.

Source: Get Smart Plus 3, p.17 — the *always / sometimes / never* grammar
box ("I **always** do my homework. He **sometimes** combs his hair. You
**never** brush your teeth.").

Save the approved page into **`komikgrammar/`**, never `koleksigambar/`.
Generate with:

```
python generate_image.py grammar_year3_adverbs_frequency
```

Layout, no-text rule, and the wording recipe that makes the grid come out
as exactly 8 even panels are documented once in
`grammar_year3_present_simple.md` — this file follows it verbatim.

**Character note:** a girl this time, so the Year 3 set doesn't become
eight comics about the same boy. Clothing is pinned as **plain, no
pattern** for the same reason as the pilot: loose wording makes the model
invent a new print in every panel.

**The grammar:** each caption carries one of the three adverbs, and the
adverb always sits **before the main verb** — that position is the rule.
The mix is deliberate: 3 × *always*, 3 × *sometimes*, 2 × *never*.

---

1. **Mira's Week — 8-panel comic page** — `gram_year3_adverbs_frequency_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page containing EXACTLY EIGHT panels and no more. The layout is a strict regular grid of 4 rows with exactly 2 panels in each row, so 4 rows times 2 columns equals 8 panels in total. Every panel is exactly the same width and exactly the same height as every other panel, separated by even white gutters and thin dark borders. Read left to right, then down. Each of the eight scenes below appears exactly once — never repeat a scene, never split a scene across two panels, and never show the girl twice inside one panel. The same girl appears in all 8 panels: a Malaysian primary-school girl about nine years old, medium brown skin, long straight black hair tied in a single ponytail with a plain red hair tie, round friendly face, big dark eyes, wearing a plain white school blouse with no badge or logo and a plain dark blue skirt. Panel 1, row 1 left: she drinks a glass of milk at the kitchen table, smiling, with a plate of toast in front of her. Panel 2, row 1 right: she makes her bed neatly in a tidy bedroom. Panel 3, row 2 left: she rides a bicycle along a leafy neighbourhood road on a sunny morning. Panel 4, row 2 right: she walks to school chatting happily with two friends carrying school bags. Panel 5, row 3 left: she sits at a desk at home writing in an exercise book with a pencil, concentrating. Panel 6, row 3 right: she stands in a kitchen helping her mother stir a pot on the stove. Panel 7, row 4 left: she shakes her head firmly and pushes away a plate of sweets on a dining table before dinner. Panel 8, row 4 right: she lies in bed asleep with a small lamp switched off and a clock on the bedside table. Simple clean uncluttered backgrounds, and any books shown must have completely blank plain spines. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

---

## Draft captions and speech (for `database.json`, not for the image)

| Panel | Caption (narrator) | Speech bubble | `highlight` |
|---|---|---|---|
| 1 | Mira **always** drinks milk in the morning. | — | always |
| 2 | She **always** makes her bed. | — | always |
| 3 | She **sometimes** rides her bicycle to school. | "I sometimes ride my bicycle!" | sometimes |
| 4 | She **sometimes** walks with her friends. | — | sometimes |
| 5 | Mira **always** does her homework after school. | — | always |
| 6 | She **sometimes** helps her mother cook. | — | sometimes |
| 7 | She **never** eats sweets before dinner. | "I never eat sweets before dinner!" | never |
| 8 | Mira **never** sleeps late on a school night. | — | never |

**Rule card:** *Words like always, sometimes and never tell us how often
we do something. They go **before** the main verb. always = every time.
sometimes = now and then. never = not at any time.*

**ruleExamples:** `always → She always reads.` / `sometimes → She
sometimes sings.` / `never → She never shouts.`

**Check questions:**
1. Mira ______ eats sweets before dinner. She does not like them. → *never*
2. He ______ walks to school. He walks every single day. → *always*
3. I ______ ride my bicycle. I ride it on some days. → *sometimes*
