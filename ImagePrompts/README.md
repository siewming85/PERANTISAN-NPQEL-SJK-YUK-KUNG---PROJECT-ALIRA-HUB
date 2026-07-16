# How to Generate Images From These Prompts

This folder (`year1.md` … `year6.md`) contains ready-to-use image prompts
for the picture-dictionary collection. Nothing here is automated — **you
generate each image yourself** using an AI image tool of your choice, then
save the result into `koleksigambar/`. Once enough images exist there,
Claude Code runs the content-generation step to produce the matching
vocab/phrase/sentence JSON.

## Overview of the workflow

1. Open one of the `.md` files (e.g. `year1.md`).
2. For each numbered entry, copy the prompt text (the line starting with `>`).
3. Paste it into an AI image generator (ChatGPT, Gemini, or any other tool —
   see below) and generate the image.
4. Download the result and rename the file to **exactly** the filename shown
   for that entry (in backticks, right after the word/bold label).
5. Move the renamed file into `koleksigambar/`.
6. Repeat for as many entries as you want to add in this batch — you don't
   have to do a whole file in one sitting.
7. When you're done with a batch, tell Claude Code (e.g. "I've added the
   year4 images, please generate the content") and the content-generation
   step will pick them up.

You do not need to do the files in order, and you don't need to finish a
whole file before moving to the next — partial batches are fine.

## Reading a prompt entry

Each entry looks like this:

```
3. **three** — `basic_year1_numbers_three.png`
   > Bright children's textbook illustration, friendly cartoon style: exactly
   > three red balloons floating against a plain sky-blue background.
   > Nothing else in the picture. No text, letters, or numbers in the image.
```

- The **bold word** is just a human-readable label — not part of the prompt.
- The text after `` ` `` in backticks is the **exact filename** you must save
  the image as.
- The text after `>` is the **prompt** — copy it exactly (or close to it) into
  the image tool.

## Filename rules — read this carefully

- The filename must match **exactly**, including underscores and spelling.
  This is how the content-generation step links the image back to the right
  word/topic/level — a mismatched filename means that entry gets silently
  skipped.
- `.png` or `.jpg` are both fine. If your tool only gives you `.jpg` and the
  prompt file says `.png` (or vice versa), just change the file extension
  when saving — don't rename the rest of the filename.
- Don't add suffixes like `(1)`, `-copy`, or ` (edited)` — browsers and
  image tools often auto-append these on download. Strip them before moving
  the file into `koleksigambar/`.
- Save straight into `koleksigambar/` (no subfolders).

## Keeping the style consistent

Every prompt already includes the shared style phrase — "Bright children's
textbook illustration, friendly cartoon style" — and ends with "No text,
letters, or numbers in the image." Keep both of these as-is so every image
in the gallery looks like it belongs to the same set. If a tool adds text,
labels, or watermarks into the image anyway (some do), regenerate it — don't
save a version with text baked in.

Suggested settings, where the tool offers them:
- **Aspect ratio**: square (1:1) if given a choice — matches how the
  gallery displays thumbnails.
- **Style**: illustration/cartoon, not photorealistic.

## Using ChatGPT (DALL·E)

1. Go to chatgpt.com and start a chat with image generation enabled (any
   plan/model that supports image generation works).
2. Paste one prompt at a time and ask it to generate the image.
3. Download the image (hover the image → download icon).
4. Rename it to the exact filename from the prompt entry and move it into
   `koleksigambar/`.

Tip: if ChatGPT's output drifts from the plain-background/no-text style
after several images in the same chat, start a fresh chat — long chats can
gradually bias the model toward stylistic details from earlier images.

## Using Google Gemini

1. Go to gemini.google.com (or the Gemini app) and use a prompt that
   supports image generation ("Nano Banana"/Imagen-backed prompts).
2. Paste the prompt text and generate.
3. Download the image, rename it to the exact filename, move it into
   `koleksigambar/`.

Gemini sometimes generates multiple variations — pick the one that best
matches "simple background, no text" and discard the rest.

## Using other tools

Any image generator works the same way — Midjourney, Bing Image Creator,
Adobe Firefly, Leonardo.Ai, local Stable Diffusion, etc. The process is
identical: paste the prompt, generate, download, rename to the exact
filename, save into `koleksigambar/`. If a tool has a "no text in image"
negative-prompt field, use it — it helps enforce the "no text/letters/
numbers" requirement some models otherwise ignore.

## Quality check before moving on

Before saving each image into `koleksigambar/`, quickly check:

- [ ] Filename matches the prompt entry exactly (including extension case)
- [ ] Subject matches what the word/label expects (e.g. "three" really
      shows three of the item, not two or four)
- [ ] No text, letters, numbers, or watermarks baked into the image
- [ ] Background is simple/uncluttered, one clear subject
- [ ] Nothing inappropriate or inconsistent with a children's-textbook look

If an image doesn't pass, just regenerate it — there's no limit on retries.

## What NOT to do

- Don't edit or delete anything already inside `koleksigambar/` — it's a
  read-only source once images are in there (per the project's own rules).
- Don't invent new filenames — only use the ones listed in the `.md` files.
  If you want a new word added, ask Claude Code to add a new prompt entry
  first (so it goes through the duplicate-checking step) rather than
  generating an image for a word that isn't listed.
- Don't worry about generating every single entry in one go — add images in
  whatever batch size is convenient, and run content generation as often as
  you like.
