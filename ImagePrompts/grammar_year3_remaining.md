# Grammar Comics — Year 3: Remaining 10 Topics

Ten comics in one file, each **ONE image containing all 8 panels**.
Generate the whole batch with:

```
python generate_image.py grammar_year3_remaining
```

Approved pages go into **`komikgrammar/`**, never `koleksigambar/`.

## The recipe (proven over 5 generations, ~1 in 3 needs a retry)

Every prompt below repeats the same four instructions, because dropping
any one of them has produced a broken page before:

1. **"EXACTLY EIGHT panels and no more"** — in capitals.
2. **State the arithmetic**: "4 rows with exactly 2 panels in each row, so
   4 rows times 2 columns equals 8 panels in total." Also **"TALL PORTRAIT
   … do not use 4 columns"** — one page came back 2×4 without it.
3. **"Every panel is the same size… each panel's artwork fills its whole
   panel edge to edge"** — without the fill clause, one page wasted ~40%
   of every panel on empty background.
4. **"Do not add any blank boxes, empty strips, caption bars, speech
   balloons or spaces for text"** — one page invented four empty blue
   caption bars.

Plus the standing rules: positions given as *"row N left/right"* (reads
more reliably than "top left"), all clothing pinned as **plain, no
pattern, no badge, no logo**, and **absolutely no text anywhere** — every
caption and bubble comes from `database.json` so it can be translated and
spoken.

Grammar scope confirmed against *Get Smart Plus 3* by reading the book's
grammar boxes (see the page references on each comic).

---

1. **Nia's Family — have got / has got** — `gram_year3_have_got_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. Each scene appears exactly once. The same girl appears in panels 1, 4 and 8: a Malaysian primary-school girl about nine years old, medium brown skin, short black bobbed hair, round friendly face, wearing a plain green t-shirt and plain dark blue skirt. Panel 1, row 1 left: the girl smiling and holding up a big plain red schoolbag. Panel 2, row 1 right: a boy about twelve with short black hair standing and smiling in a living room. Panel 3, row 2 left: a smaller girl about six kneeling on a rug cuddling a white pet rabbit. Panel 4, row 2 right: the same girl standing in a small tidy garden with green plants and a watering can. Panel 5, row 3 left: a father in a plain shirt standing proudly beside a plain blue car. Panel 6, row 3 right: three children standing beside three new bicycles on a path. Panel 7, row 4 left: a close view of a ginger cat with bright green eyes sitting on a windowsill. Panel 8, row 4 right: the same girl standing happily between two friends with their arms around each other's shoulders. Simple clean uncluttered backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

2. **Sports Day — can / can't** — `gram_year3_can_cant_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. Each scene appears exactly once. Two children recur: a Malaysian boy about nine with short black hair in a plain blue t-shirt and plain black shorts, and a Malaysian girl about nine with a black ponytail in a plain orange t-shirt and plain black shorts. Panel 1, row 1 left: the boy swimming confidently in a blue swimming pool, smiling. Panel 2, row 1 right: the boy standing beside a brown horse looking nervous and holding up both hands. Panel 3, row 2 left: the girl sitting on a stool playing an acoustic guitar and smiling. Panel 4, row 2 right: the girl puckering her lips trying to whistle with a puzzled frown and no sound. Panel 5, row 3 left: a chubby baby in a plain white romper taking its first steps on a rug. Panel 6, row 3 right: the same baby sitting on the rug with its mouth open crying, unable to speak. Panel 7, row 4 left: the boy and girl running fast together on a school running track. Panel 8, row 4 right: the boy and girl standing on grass with their arms stretched out like wings looking up at a bird in the sky. Simple clean uncluttered backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

3. **The Class Survey — Do / Does questions** — `gram_year3_present_simple_questions_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. Each scene appears exactly once. In every panel the same Malaysian primary-school girl about nine years old with a black ponytail, wearing a plain white school blouse and plain dark blue skirt, is holding a plain clipboard and asking a question. Panel 1, row 1 left: she asks a boy who is holding a football in a schoolyard. Panel 2, row 1 right: she points at a photograph of an older boy while a classmate looks at it. Panel 3, row 2 left: she watches two children walking towards a school gate carrying bags. Panel 4, row 2 right: she asks a girl who is holding an ice cream cone. Panel 5, row 3 left: she stands in an art classroom beside a desk covered with paintbrushes, paint pots and colourful abstract paintings, with a completely blank empty noticeboard on the wall behind her. Panel 6, row 3 right: she asks a boy standing beside a bicycle. Panel 7, row 4 left: she stands at the edge of a swimming pool where two friends are swimming. Panel 8, row 4 right: she stands at a window looking out at heavy rain falling on a garden. Simple clean uncluttered school backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image. Any signs, posters, timetables, noticeboards, newspapers or shop fronts shown must be completely blank with no writing, letters or symbols on them.

4. **Right Now at the Park — present continuous** — `gram_year3_present_continuous_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. Each scene appears exactly once, all in the same sunny park. Panel 1, row 1 left: a Malaysian boy about nine in a plain blue t-shirt kicking a football hard. Panel 2, row 1 right: a Malaysian girl about nine with a ponytail in a plain yellow t-shirt sitting on the grass drawing in a sketchbook. Panel 3, row 2 left: two girls skipping together with a long skipping rope. Panel 4, row 2 right: a man sitting on a park bench reading a large open newspaper. Panel 5, row 3 left: two boys sitting on the grass eating ice cream cones. Panel 6, row 3 right: a small brown dog running after a large butterfly. Panel 7, row 4 left: a group of four children standing in a row singing with their mouths open happily. Panel 8, row 4 right: the same yellow-shirted girl standing under a tree watching everyone in the park with a big smile. Simple clean uncluttered park backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

5. **Where Is the Cat? — prepositions of place** — `gram_year3_prepositions_place_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. The same ginger tabby cat with white paws appears in all 8 panels, in a different place each time, always clearly visible. Panel 1, row 1 left: the cat sitting on top of a green sofa cushion. Panel 2, row 1 right: the cat lying underneath a wooden dining table. Panel 3, row 2 left: the cat sitting inside an open cardboard box. Panel 4, row 2 right: the cat peeping out from behind a half-open wooden door. Panel 5, row 3 left: the cat sitting on the floor directly in front of a switched-off television. Panel 6, row 3 right: the cat sitting on the floor right next to a tall terracotta flowerpot. Panel 7, row 4 left: the cat sitting on a mat exactly between two shoes, one shoe on each side. Panel 8, row 4 right: the cat curled up asleep on a neatly made bed in an upstairs bedroom with a window. Simple clean uncluttered home backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

6. **In the Kitchen — some / any** — `gram_year3_some_any_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. The same Malaysian boy about nine years old with short black hair, wearing a plain light green t-shirt, appears in every panel in the same bright kitchen. Panel 1, row 1 left: he opens a fridge door and points at a full bottle of milk inside. Panel 2, row 1 right: he looks at a bowl of brown eggs on a kitchen table. Panel 3, row 2 left: he searches a shelf with an empty questioning shrug, hands turned up. Panel 4, row 2 right: he holds up an empty bread basket with nothing in it, looking disappointed. Panel 5, row 3 left: he pours white flour from a bag into a mixing bowl. Panel 6, row 3 right: he opens a vegetable drawer and looks inside with a questioning face. Panel 7, row 4 left: he holds an empty wire basket where onions should be, looking puzzled. Panel 8, row 4 right: he stands proudly beside a tray of freshly baked round biscuits, smiling. Simple clean uncluttered kitchen backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

7. **At the Farm — plurals** — `gram_year3_plurals_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. Each scene appears exactly once and the number of animals must be exactly right in each panel. Panel 1, row 1 left: exactly three white ducks swimming on a farm pond. Panel 2, row 1 right: exactly two brown goats eating green grass. Panel 3, row 2 left: exactly six black and white cows standing in a field. Panel 4, row 2 right: exactly four brown horses running across a meadow. Panel 5, row 3 left: exactly three grey wolves standing among dark forest trees. Panel 6, row 3 right: exactly two small grey mice nibbling a wedge of yellow cheese on a wooden floor. Panel 7, row 4 left: exactly ten white sheep standing together on a green hill. Panel 8, row 4 right: exactly five Malaysian children in plain colourful t-shirts playing together in a farmyard. Simple clean uncluttered farm backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

8. **School Rules — imperatives and don't** — `gram_year3_imperatives_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. Malaysian primary-school children in plain white school shirts and plain dark blue shorts or skirts appear throughout, with a friendly female teacher in a plain blue baju kurung and headscarf in some panels. Panel 1, row 1 left: a girl sitting quietly reading in a library with a finger raised to her lips. Panel 2, row 1 right: a boy running down a classroom aisle while the teacher holds up a flat palm to stop him. Panel 3, row 2 left: a boy lowering a camera in a museum gallery while a guard raises a flat palm. Panel 4, row 2 right: a girl dropping a crumpled paper into a rubbish bin. Panel 5, row 3 left: a boy about to bite a sandwich at his classroom desk while the teacher shakes her head. Panel 6, row 3 right: a girl switching off a mobile phone and putting it into her bag in a cinema. Panel 7, row 4 left: a boy holding a ball indoors while the teacher holds up a flat palm to stop him throwing it. Panel 8, row 4 right: four children sitting attentively at their desks looking at the teacher who is speaking at the front. Simple clean uncluttered school backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

9. **Where Were You Yesterday? — was / were** — `gram_year3_was_were_page.png`
   > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. The same Malaysian girl about nine years old with long black hair in a plain purple t-shirt and plain jeans appears in panels 1, 2, 3, 5, 6 and 8. Panel 1, row 1 left: the girl standing inside a bright shopping centre with shops behind her. Panel 2, row 1 right: the girl walking beside her mother, who wears a plain pink baju kurung and headscarf, inside the shopping centre, where every shop sign and board is completely blank with no writing on it. Panel 3, row 2 left: the girl and her mother walking past shop windows in bright morning light. Panel 4, row 2 right: a very crowded shopping centre walkway full of many shoppers. Panel 5, row 3 left: the girl sitting in a dark cinema seat looking up at a glowing screen. Panel 6, row 3 right: the girl laughing happily in the cinema seat with popcorn on her lap. Panel 7, row 4 left: three children playing on swings and a slide in a sunny park. Panel 8, row 4 right: the girl at home in bed at night smiling contentedly with a lamp glowing softly. Simple clean uncluttered backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image. Any signs, posters, timetables, noticeboards, newspapers or shop fronts shown must be completely blank with no writing, letters or symbols on them.

10. **Record Breakers — superlatives** — `gram_year3_superlatives_page.png`
    > Bright children's textbook illustration, friendly cartoon style. One single comic page in TALL PORTRAIT shape containing EXACTLY EIGHT panels and no more, arranged as 4 rows stacked vertically with exactly 2 panels side by side in each row, so 4 rows times 2 columns equals 8 panels in total. Do not use 4 columns. Every panel is the same size and roughly square, separated by even white gutters and thin dark borders, and each panel's artwork fills its whole panel edge to edge. Do not add any blank boxes, empty strips, caption bars, speech balloons or spaces for text. Read left to right, then down. Each scene appears exactly once. Panel 1, row 1 left: one enormous elephant towering over a small deer and a small goat standing together beside it. Panel 2, row 1 right: a cheetah sprinting far ahead of a running horse and a running dog. Panel 3, row 2 left: one very tall rocky mountain with clouds around its peak, much taller than two smaller hills beside it. Panel 4, row 2 right: a bright glowing orange planet in space with two smaller cooler blue planets nearby. Panel 5, row 3 left: a tiny hummingbird hovering beside a much larger parrot and a much larger owl on a branch. Panel 6, row 3 right: three Malaysian children in plain t-shirts standing in a row, the girl in the middle laughing with a huge joyful smile while the other two only smile a little. Panel 7, row 4 left: three cakes on a table, the middle chocolate cake much larger and more beautifully decorated than the two plain ones beside it. Panel 8, row 4 right: three fish of clearly different lengths lying side by side on a market table, one very long, one medium and one short. Simple clean uncluttered backgrounds. Absolutely no text, no letters, no numbers, no speech bubbles, no captions and no panel numbers anywhere in the image.

---

## Captions, rules and check questions (for `database.json`)

English source lines only — ms/zh/iba authored at the database step.

### 1. have got / has got (Get Smart Plus 3, p.5–9)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | I **have** got a big red schoolbag. | "I have got a big red schoolbag!" | have |
| 2 | My brother **has** got short black hair. | — | has |
| 3 | My sister **has** got a pet rabbit. | — | has |
| 4 | We **have** got a small garden. | — | have |
| 5 | My father **has** got a blue car. | — | has |
| 6 | My friends **have** got new bicycles. | — | have |
| 7 | The cat **has** got green eyes. | — | has |
| 8 | I **have** got two good friends. | "I have got two good friends!" | have |

Rule: *Use **have got** with I, you, we and they. Use **has got** with he,
she and it.*
Examples: `I → I have got` / `We → We have got` / `He → He has got` / `She → She has got`
Check: `My sister ______ got a rabbit.` (have/**has**) · `We ______ got a garden.` (**have**/has) · `The cat ______ got green eyes.` (have/**has**)

### 2. can / can't (p.11)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | Ravi **can** swim very well. | "I can swim!" | can |
| 2 | He **can't** ride a horse. | — | can't |
| 3 | Aina **can** play the guitar. | — | can |
| 4 | She **can't** whistle. | — | can't |
| 5 | The baby **can** walk now. | — | can |
| 6 | The baby **can't** talk yet. | — | can't |
| 7 | We **can** run fast. | — | can |
| 8 | We **can't** fly like a bird. | "We can't fly!" | can't |

Rule: *Use **can** to say what someone is able to do, and **can't** for
what they are not able to do. The verb after can never changes.*
Examples: `can → She can swim.` / `can't → She can't fly.`
Check: `A fish ______ swim.` (**can**/can't) · `A baby ______ drive a car.` (can/**can't**) · `Birds ______ fly.` (**can**/can't)

### 3. Do / Does questions (p.19–21)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | **Do** you play football? | "Do you play football?" | Do |
| 2 | **Does** your brother play too? | — | Does |
| 3 | **Do** they walk to school? | — | Do |
| 4 | **Does** she like ice cream? | — | Does |
| 5 | **Do** we have art today? | — | Do |
| 6 | **Does** he ride a bicycle? | — | Does |
| 7 | **Do** your friends swim? | — | Do |
| 8 | **Does** it rain here every day? | "Does it rain here every day?" | Does |

Rule: *To ask a question, start with **Do** for I, you, we and they, and
**Does** for he, she and it. The main verb stays the same — never add -s
after Does.*
Examples: `you → Do you play?` / `they → Do they walk?` / `he → Does he ride?` / `she → Does she like?`
Check: `______ she like ice cream?` (Do/**Does**) · `______ they walk to school?` (**Do**/Does) · `______ he ride a bicycle?` (Do/**Does**)

### 4. present continuous (p.27–31)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | Danish is **kicking** a football. | — | kicking |
| 2 | Aina is **drawing** a picture. | "I am drawing a picture!" | drawing |
| 3 | Two girls are **skipping**. | — | skipping |
| 4 | A man is **reading** a newspaper. | — | reading |
| 5 | Two boys are **eating** ice cream. | — | eating |
| 6 | A dog is **chasing** a butterfly. | — | chasing |
| 7 | The children are **singing**. | — | singing |
| 8 | I am **watching** everyone in the park. | "I am watching everyone!" | watching |

Rule: *For something happening right now, use **am**, **is** or **are**
with the verb plus **-ing**. I am playing. He is playing. They are
playing.*
Examples: `I → I am playing` / `He → He is playing` / `They → They are playing`
Check: `She ______ drawing a picture.` (is/are → **is**) · `They ______ singing.` (is/are → **are**) · `A dog is ______ a butterfly.` (chase/**chasing**)

### 5. prepositions of place (p.47)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | The cat is **on** the sofa. | — | on |
| 2 | The cat is **under** the table. | — | under |
| 3 | The cat is **in** the box. | "The cat is in the box!" | in |
| 4 | The cat is **behind** the door. | — | behind |
| 5 | The cat is in **front** of the television. | — | front |
| 6 | The cat is **next** to the flowerpot. | — | next |
| 7 | The cat is **between** two shoes. | — | between |
| 8 | The cat is **upstairs** on the bed. | "Now the cat is upstairs!" | upstairs |

Rule: *Words like in, on, under, behind, between and in front of tell us
**where** something is.*
Examples: `on → on the sofa` / `under → under the table` / `behind → behind the door` / `between → between two shoes`
Check: `The cat is ______ the box. It is inside.` (on/**in**) · `The ball is ______ the table. It is below it.` (**under**/on) · `She sits ______ Ali and Siti.` (**between**/behind)

### 6. some / any (p.57–59)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | There is **some** milk in the fridge. | — | some |
| 2 | There are **some** eggs on the table. | — | some |
| 3 | Is there **any** cheese? | "Is there any cheese?" | any |
| 4 | There isn't **any** bread. | — | any |
| 5 | We need **some** flour. | — | some |
| 6 | Are there **any** tomatoes? | — | any |
| 7 | There aren't **any** onions. | — | any |
| 8 | Let's make **some** biscuits! | "Let's make some biscuits!" | some |

Rule: *Use **some** in sentences that say yes. Use **any** in questions
and in sentences that say no.*
Examples: `yes → There is some milk.` / `question → Is there any cheese?` / `no → There isn't any bread.`
Check: `There is ______ milk in the fridge.` (**some**/any) · `Is there ______ cheese?` (some/**any**) · `There aren't ______ onions.` (some/**any**)

### 7. plurals (p.69)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | There are three **ducks** in the pond. | — | ducks |
| 2 | Two **goats** are eating grass. | — | goats |
| 3 | The farmer has six **cows**. | — | cows |
| 4 | Four **horses** are running. | — | horses |
| 5 | Three **wolves** live in the forest. | "Look at the wolves!" | wolves |
| 6 | Two **mice** are eating cheese. | — | mice |
| 7 | Ten **sheep** are on the hill. | — | sheep |
| 8 | Five **children** are playing. | "The children are playing!" | children |

Rule: *Most nouns add **-s** for more than one. Some change in a special
way: wolf becomes wolves, mouse becomes mice, child becomes children —
and sheep does not change at all.*
Examples: `duck → ducks` / `wolf → wolves` / `mouse → mice` / `sheep → sheep` / `child → children`
Check: `One mouse, two ______.` (mouses/**mice**) · `One sheep, ten ______.` (**sheep**/sheeps) · `One child, five ______.` (childs/**children**)

### 8. imperatives and don't (p.71)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | **Be** quiet in the library. | — | Be |
| 2 | **Don't** run in the classroom. | "Don't run!" | Don't |
| 3 | **Don't** take photos in the museum. | — | Don't |
| 4 | **Put** the rubbish in the bin. | — | Put |
| 5 | **Don't** eat in class. | — | Don't |
| 6 | **Turn** off your mobile phone. | — | Turn |
| 7 | **Don't** throw the ball inside. | — | Don't |
| 8 | **Listen** to your teacher. | "Listen to your teacher!" | Listen |

Rule: *To tell someone what to do, start with the verb: Sit down. To tell
someone **not** to do it, start with **Don't**: Don't run. Don't is short
for do not.*
Examples: `do it → Be quiet.` / `do it → Put it in the bin.` / `do not → Don't run.` / `do not → Don't shout.`
Check: `______ run in the classroom. It is dangerous.` (**Don't**/Do) · `______ quiet in the library.` (**Be**/Are) · `______ take photos in the museum.` (**Don't**/Not)

### 9. was / were (p.77–81)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | Yesterday I **was** at the shopping centre. | "I was at the shopping centre!" | was |
| 2 | My mother **was** with me. | — | was |
| 3 | We **were** there in the morning. | — | were |
| 4 | The shops **were** very busy. | — | were |
| 5 | In the afternoon I **was** at the cinema. | — | was |
| 6 | The film **was** very funny. | — | was |
| 7 | My friends **were** at the park. | — | were |
| 8 | It **was** a very good day. | "It was a very good day!" | was |

Rule: *Was and were are the past of **be**. Use **was** with I, he, she
and it. Use **were** with you, we and they.*
Examples: `I → I was` / `He → He was` / `We → We were` / `They → They were`
Check: `Yesterday I ______ at the park.` (**was**/were) · `My friends ______ very happy.` (was/**were**) · `The film ______ funny.` (**was**/were)

### 10. superlatives (p.101)
| # | Caption | Speech | highlight |
|---|---|---|---|
| 1 | The elephant is the **biggest** animal here. | — | biggest |
| 2 | The cheetah is the **fastest** of them all. | "The cheetah is the fastest!" | fastest |
| 3 | That is the **tallest** mountain. | — | tallest |
| 4 | Venus is the **hottest** planet. | — | hottest |
| 5 | The hummingbird is the **smallest** bird. | — | smallest |
| 6 | Aina is the **happiest** girl today. | — | happiest |
| 7 | This chocolate cake is the **best**. | "This cake is the best!" | best |
| 8 | That fish is the **longest** of the three. | — | longest |

Rule: *To compare **three or more** things, use **the** with the adjective
plus **-est**. tall → the tallest. Some change spelling: big → the
biggest, happy → the happiest. A few are irregular: good → the best.*
Examples: `tall → the tallest` / `big → the biggest` / `happy → the happiest` / `good → the best`
Check: `An elephant is the ______ animal here.` (bigger/**biggest**) · `Venus is the ______ planet.` (hotter/**hottest**) · `This cake is the ______.` (gooder/**best**)
