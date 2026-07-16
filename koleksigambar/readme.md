# How Filenames Work in This Folder

Every image in this folder is named so that its **level**, **topic**, and
(for the remedial set) **word class** can be read directly off the filename
— no guessing required. This README explains how to decode an existing
filename, and how to name a new one correctly when adding images from
`image_prompts/`.

⚠️ This folder is **read-only** for automated tooling — images are only
ever added here manually (see `image_prompts/README.md` for how to generate
them). Nothing in this folder should be deleted, renamed, or edited by
scripts.

## The two filename patterns

### 1. Remedial set — `basic_kata_<class>_<word>.ext`

```
basic_kata_nama_kucing.png
   │    │    │      └─ the word itself, in Bahasa Melayu (lowercase,
   │    │    │          underscores instead of spaces, e.g. papan_putih)
   │    │    └──────── word class:
   │    │                nama      = noun
   │    │                kerja     = verb
   │    │                adjektif  = adjective
   │    └───────────── literally "kata" (Malay for "word") — fixed
   └────────────────── literally "basic" — marks this as the remedial set
```

- Level is always **remedial** (Year 1–3 level content for weaker learners).
- Topic is always `"vocabulary"`.
- Example: `basic_kata_nama_kucing.png` → level=remedial, wordClass=noun
  (kucing = cat).

### 2. Mainstream sets — `basic_year<N>_<topic>_<word_or_phrase>.ext`

```
basic_year4_animals_elephant.png
   │    │      │          └─ the word or short phrase (lowercase,
   │    │      │              underscores instead of spaces)
   │    │      └──────────── topic: the DSKP/textbook theme this word
   │    │                    belongs to (see topic lists below)
   │    └─────────────────── year level: 1, 2, 3, 4, 5, or 6
   └──────────────────────── literally "basic" — fixed prefix
```

- `year1`–`year3` = real KSSR Year 1/2/3 syllabus content (Super Minds 1 /
  Get Smart Plus 3). No word-class in the filename for these.
- `year4`–`year6` = mainstream KSSR Year 4/5/6 syllabus content. No
  word-class in the filename for these either.
- Example: `basic_year3_farm_goat.png` → level=year3, topic=farm.

Known topics per year (not exhaustive — new topics can appear as content
expands, always check `image_prompts/year<N>.md` for the authoritative
current list):

| Year | Example topics |
|---|---|
| 1 | greetings, numbers, colours, school, toys, animals, food, shapes |
| 2 | week, free_time, home, clothes, body, beach, animals, materials, weather |
| 3 | appearance, transport, jobs, chores, celebrations, home, food, sports, school, animals, places, hobbies, outdoors, feelings, farm |
| 4 | hobbies, school_subjects, housework, ancient_egypt, celebrations, food, transport, street_safety, camping, recycling, animals, sports, health, safety_home |
| 5 | hobbies, places, adjectives, events, wildlife, school, food, sports, people, life, holiday, weather |
| 6 | emergency, history, adventure, careers, transport, crafts, music, storytelling, lifestyle, mystery |

## How to tell level and topic just by looking at a filename

1. Does it start with `basic_kata_`? → remedial set. The next segment
   (`nama`/`kerja`/`adjektif`) is the word class; everything after that is
   the word (in Malay).
2. Does it start with `basic_year1_` … `basic_year6_`? → that number is the
   level. The segment right after it, up to the last word/phrase segment,
   is the topic.
3. If a filename doesn't match either pattern, it's non-standard — don't
   guess its level/topic from the name; the content-generation step falls
   back to looking at the image itself and logs a note in
   `output/skipped.txt`.

## Adding new images

When you generate a new image from one of the `image_prompts/year<N>.md`
files, use the **exact filename given in that prompt entry** — don't invent
your own. The prompt files already follow the two patterns above, so as
long as you copy the filename exactly, level/topic parsing works
automatically. See `image_prompts/README.md` for the full generation
workflow.

## File format

`.png`, `.jpg`, `.jpeg`, and `.webp` are all accepted — the extension
doesn't affect level/topic parsing, only the base filename does.
