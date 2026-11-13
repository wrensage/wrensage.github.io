# Wren Sage — Portfolio & Journal

A custom, responsive static website for Wren Sage, textile artist and crochet pattern designer.

The live site is [https://wrensage.github.io/](https://wrensage.github.io/). It is published from the `main` branch with GitHub Pages. Saving a file to `main` updates the site after a minute or two. No extra software, paid account, or separate build service is required.

## Add a journal entry

Each journal entry is **one file** in the `_posts` folder. That file holds the English text and the Japanese text. GitHub Pages adds it to the Journal page and gives it its own link.

1. Open the `_posts` folder.
2. Copy `_template.md`.
3. Rename the copy so it starts with the date, then a short title, with hyphens between words. Example: `2026-12-01-trying-a-new-yarn.md`. The date is year-month-day.
4. At the top of the file, between the `---` lines, edit three things:
   - `title` — the English title
   - `date` — the same date as the file name
   - `eyebrow` — a short label, such as `Process note` or `Pattern release`
5. Under that, write the English entry. Leave a blank line between paragraphs.
6. Leave this line exactly as it is: `<!-- japanese -->`
7. Under that line, write the Japanese entry. Leave a blank line between paragraphs.
8. Save the file on the `main` branch.

The newest entry shows first on [the Journal page](https://wrensage.github.io/journal.html). It also has its own page, so you can share or save that link.

You can do this on the GitHub website (Add file → Create new file) or on your computer (copy the template, edit it, and upload it into `_posts`).

Keep a dated copy of each published version and your original pattern materials for your professional records.

## Add or replace photographs

Photographs belong in `assets/images/`. These three are already on the site:

- `solly-feature.jpg` — homepage (Solly sitting, slight angle)
- `solly.jpg` — Designs page (Solly sitting, straight on)
- `solly-cover.jpg` — Patterns page (large Solly next to small Solly)

To replace one, upload a new photo **with the same file name**, including `.jpg`. You do not need to edit the page. Before you upload, resize the photo so the long side is about 1600 pixels and save it as a JPG. Large phone photos make the site slow.

To show a photo in a new place, put the file in `assets/images/`, then add it on the page:

```html
<img src="assets/images/your-photo.jpg" alt="A short description of what is in the photo.">
```

Write that description in English. Where the page also has a Japanese version, add the Japanese description in the same `alt` text, after the English sentence.

## Update your shop and pattern links

The Etsy links currently point to `https://www.etsy.com/shop/oddlyknotted`.
The Ravelry links are placeholders pointing to Ravelry's homepage. Replace them with the exact Solly pattern URL once you have it.

## Color palette

- Background: `#FEF8E1`
- Lime accent: `#D4DF5E`
- Pink accent: `#EF659C`
- Lavender accent: `#B18CBE`
- Text: `#170B1B`
- Rat ear: `#F1A7AA`
- Rat fur: `#A38B8A`
- Rat belly: `#FCF4E1`
- Rat ear/tail shadows: `#A6405C`
- Rat Poison colorway: `#BBDD5C`, `#F048BE`, `#6637AC`, `#02020E`

## Notes

- This site is plain HTML, CSS, and JavaScript, plus journal files that GitHub Pages builds for you. It does not need a paid service, a database, or a build step you run yourself.
- Keep `_config.yml` in the repository. It turns off GitHub's default theme so visitors see the cream background and these colors, not GitHub's white page with blue links. Do not delete that file, and do not move `assets/css/style.css`.
- The Japanese copy is intentionally simple. Please review and refine it as your Japanese develops before treating it as a polished translation.
- The site is designed to be an artist portfolio and public record of work, not a promise of immigration eligibility.
