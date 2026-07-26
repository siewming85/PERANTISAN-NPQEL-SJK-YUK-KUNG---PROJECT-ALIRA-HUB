# Grammar Comics — Year 2 (Super Minds 1, Units 5–9)

Four comics, each **ONE image containing all 8 panels**. Generate with:

```
python generate_image.py grammar_year2
```

Approved pages go into **`komikgrammar/`**, never `koleksigambar/`.

## Why only four

This project splits Super Minds 1 across two years — `image_prompts/year1.md`
covers **Units 0–4** and `image_prompts/year2.md` covers **Units 5–9**. Four
Year 2 comics already exist, because they were built in the Year 1 batch
before that split was noticed, and have since been reassigned to `year2`:

| Unit | Grammar | Comic |
|---|---|---|
| 6 The old house | There's a / There are / Is there / Are there | already built |
| 7 Get dressed | this / these | already built |
| 8 The robot | can / can't | already built |
| 9 At the beach | Let's / Where's / Where are | already built |

The four below fill what the book's own "Map of the book" still lists for
Units 5–7:

| Unit | Grammar | Comic |
|---|---|---|
| 5 Free time | I (watch TV) on (Sundays) | 1 |
| 5 Free time | Do you (play football)? Yes, I do. / No, I don't. | 2 |
| 6 The old house | How many (cars) are there? | 3 |
| 7 Get dressed | (Olivia)'s wearing… Is he/she wearing…? | 4 |

Captions stay short (4–7 words) — Year 2 learners are seven and eight.

## The recipe

Unchanged from the batches that worked. Every clause below exists because
dropping it broke a page: **"EXACTLY EIGHT panels and no more"** in capitals;
the arithmetic (**4 rows × 2 per row = 8**) plus **"TALL PORTRAIT … do not
use 4 columns"**; **"each panel's artwork fills its whole panel edge to
edge"**; and **"no blank boxes, empty strips, caption bars or spaces for
text"** with **all signs and boards completely blank**.

Comic 3 depends on exact counts, which image models get wrong — so its
numbers are kept small and stated twice per panel.

---

1. **My Week — I watch TV on Sundays** — `gram_year2_days_page.png`
   > Bright children's textbook illustration, friendly cartoon style, simple and clear for young children. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text, and any signs, boards or calendars must be completely blank with no writing on them. Read left to right, then down. The same Malaysian boy about eight years old with short black hair, wearing a plain orange t-shirt and plain blue shorts, appears in every panel. Panel 1, row 1 left: he sits on a sofa watching a television, smiling. Panel 2, row 1 right: he kicks a football on a grassy field. Panel 3, row 2 left: he sits in a comfy chair reading an open book. Panel 4, row 2 right: he swims in a blue swimming pool. Panel 5, row 3 left: he rides a bicycle along a sunny path. Panel 6, row 3 right: he helps his mother carry shopping bags in a kitchen. Panel 7, row 4 left: he plays a board game at a table with a friend. Panel 8, row 4 right: he plays happily on a swing in a park. Simple clean uncluttered backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

2. **Do You...? — questions and short answers** — `gram_year2_do_you_page.png`
   > Bright children's textbook illustration, friendly cartoon style, simple and clear for young children. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns and do not make the page landscape. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Never divide a panel into smaller sub-panels, and never show the same moment twice. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text, and any signs or boards must be completely blank. Read left to right, then down. Two Malaysian children about eight recur in every panel: a girl with a black ponytail in a plain green t-shirt who asks the questions, and a boy with short black hair in a plain blue t-shirt who answers. Panel 1, row 1 left: the girl holds out a football towards the boy with a curious open-mouthed expression. Panel 2, row 1 right: the boy smiles broadly and gives a clear thumbs up with one hand. Panel 3, row 2 left: the girl points at a television with a curious open-mouthed expression. Panel 4, row 2 right: the boy has both palms raised flat in front of him and his eyebrows lowered, looking reluctant. Panel 5, row 3 left: the girl holds up an open book with a curious open-mouthed expression. Panel 6, row 3 right: the boy smiles broadly hugging the closed book against his chest with both arms. Panel 7, row 4 left: the girl stands in a garden holding up a pair of blue swimming goggles with a curious open-mouthed expression. Panel 8, row 4 right: a completely separate indoor scene in a plain bedroom, where the boy sits on the edge of a bed with one hand rubbing the back of his neck and a reluctant expression. Each of the eight panels is its own separate closed rectangle; never let two neighbouring panels share one continuous background or merge into a single wide picture. Simple clean uncluttered backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no thought bubbles, no captions, no sound effects, no written words of any kind and no panel numbers anywhere in the image. Emotions must be shown only through faces, hands and body posture, never through written words.

3. **How Many? — counting in the old house** — `gram_year2_how_many_page.png`
   > Bright children's textbook illustration, friendly cartoon style, simple and clear for young children. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text, and any signs or boards must be completely blank. Read left to right, then down. Every panel is inside the same friendly old house. The number of objects in each panel is very important and must be exact, with the objects clearly separated and easy to count. Panel 1, row 1 left: a Malaysian girl about eight in a plain purple t-shirt pointing with a questioning face at a group of cats. Panel 2, row 1 right: exactly 3 cats sitting in a row on a rug, three cats and no more. Panel 3, row 2 left: the same girl pointing with a questioning face at a doorway. Panel 4, row 2 right: exactly 1 wooden door, one door and no more. Panel 5, row 3 left: the same girl pointing with a questioning face at a bookshelf. Panel 6, row 3 right: exactly 5 books standing side by side on a shelf, five books and no more. Panel 7, row 4 left: the same girl pointing upwards with a questioning face at a wooden beam. Panel 8, row 4 right: exactly 2 small bats hanging from a wooden beam, two bats and no more. Simple clean uncluttered old-house backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

4. **What Are They Wearing? — He's / She's wearing** — `gram_year2_wearing_page.png`
   > Bright children's textbook illustration, friendly cartoon style, simple and clear for young children. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text, and any signs or boards must be completely blank. Read left to right, then down. Two Malaysian children about eight recur: a girl with long black hair called Olivia and a boy with short black hair called Ben, shown full length so their clothes are clearly visible. Panel 1, row 1 left: the girl standing and smiling, wearing a plain red sweater and a plain grey skirt. Panel 2, row 1 right: the boy standing and smiling, wearing plain blue jeans and a plain white t-shirt. Panel 3, row 2 left: the girl standing with a plain blue sun hat on her head, another child pointing at the hat with a questioning face. Panel 4, row 2 right: a close view of the girl smiling and touching the same blue sun hat on her head, nodding. Panel 5, row 3 left: the boy standing in plain trainers with bare ankles, another child pointing at his feet with a questioning face. Panel 6, row 3 right: the boy shaking his head, standing beside a pair of brown boots on the floor that he is not wearing. Panel 7, row 4 left: the girl standing and twirling happily in a plain yellow dress. Panel 8, row 4 right: the boy standing and smiling in a plain green jacket. Simple clean uncluttered backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

---

## Captions, rules and check questions

### 1. days — I (watch TV) on (Sundays)
1 I watch TV on **Sundays**. *(speech: "I watch TV on Sundays.")*
2 I play football on **Mondays**.
3 I read books on **Tuesdays**.
4 I swim on **Wednesdays**.
5 I ride my bike on **Thursdays**.
6 I help my mother on **Fridays**.
7 I play games on **Saturdays**.
8 I go to the park at the **weekend**. *(speech: "I love the weekend!")*
Rule: *Say what you do on a day with **on** and the day: I watch TV **on** Sundays. Days of the week always start with a capital letter.*
Examples: `day → on Monday` / `day → on Sunday` / `two days → at the weekend`
Check: `I play football ______ Mondays.` (**on**/in) · `I watch TV on ______.` (**Sundays**/sunday) · `I go out at the ______.` (**weekend**/weekends)

### 2. do_you — Do you…? Yes, I do. / No, I don't.
1 **Do** you play football? *(speech: "Do you play football?")*
2 Yes, I **do**.
3 **Do** you watch TV?
4 No, I **don't**.
5 **Do** you read books?
6 Yes, I **do**.
7 **Do** you swim on Sundays?
8 No, I **don't**. *(speech: "No, I don't.")*
Rule: *Start a question with **Do you**. Answer with **Yes, I do** or **No, I don't**. Don't is short for do not.*
Examples: `ask → Do you swim?` / `yes → Yes, I do.` / `no → No, I don't.`
Check: `______ you play football?` (**Do**/Does) · `Yes, I ______.` (**do**/does) · `No, I ______.` (**don't**/doesn't)

### 3. how_many — How many…are there?
1 **How** many cats are there? *(speech: "How many cats are there?")*
2 There are **three** cats.
3 **How** many doors are there?
4 There is **one** door.
5 **How** many books are there?
6 There are **five** books.
7 **How** many bats are there?
8 There are **two** bats. *(speech: "There are two bats!")*
Rule: *Ask **How many … are there?** to count things. Answer **There is one…** for one, and **There are…** for more than one.*
Examples: `ask → How many cats are there?` / `one → There is one door.` / `many → There are three cats.`
Check: `______ many cats are there?` (**How**/What) · `There ______ three cats.` (is/**are**) · `There ______ one door.` (**is**/are)

### 4. wearing — He's / She's wearing
1 Olivia's **wearing** a red sweater. *(speech: "I'm wearing a red sweater.")*
2 Ben's **wearing** blue jeans.
3 **Is** she wearing a hat?
4 Yes, she **is**.
5 **Is** he wearing boots?
6 No, he **isn't**.
7 She's **wearing** a yellow dress.
8 He's **wearing** a green jacket. *(speech: "He's wearing a green jacket.")*
Rule: *Say what someone has on now with **is wearing**: She's **wearing** a hat. Ask **Is he/she wearing…?** and answer **Yes, he/she is** or **No, he/she isn't**.*
Examples: `she → She's wearing a dress.` / `he → He's wearing a jacket.` / `ask → Is she wearing a hat?`
Check: `She ______ wearing a red sweater.` (**is**/are) · `Is he wearing boots? No, he ______.` (is/**isn't**) · `Ben's ______ blue jeans.` (wear/**wearing**)
