# Wren Sage — Portfolio & Journal

A custom, responsive static website for Wren Sage, textile artist and crochet pattern designer.

## Before publishing

1. Confirm your GitHub username. If it is `wrensage`, create a **public** repository named `wrensage.github.io`.
2. Upload the contents of this folder to the repository's root. Do not upload the enclosing `wren-sage-portfolio` folder itself.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose **main** and **/(root)**, then save.
6. Wait for GitHub Pages to publish. Your site should appear at `https://wrensage.github.io/`.

If your GitHub username is not `wrensage`, name the repository `YOURUSERNAME.github.io` and use `https://YOURUSERNAME.github.io/`.

## Add your photographs

Replace the placeholder images in `assets/images/` with your own photographs. Keep the filenames the same:

- `solly-feature.jpg` — homepage featured image
- `solly.jpg` — Solly design page
- `solly-cover.jpg` — pattern page cover

Use clear, well-lit photographs that show the actual finished work. You can use JPG, PNG, or WebP, but if you change the extension, update the matching image path in the HTML.

## Update your shop and pattern links

The Etsy links currently point to `https://www.etsy.com/shop/OddlyKnotted`.
The Ravelry links are placeholders pointing to Ravelry's homepage. Replace them with the exact Solly pattern URL once you have it.

## Add a journal post

The journal page currently includes your Solly pattern announcement. To add another entry, copy the `<article class="journal-entry">...</article>` block in `journal.html`, update the date, title, text, and Japanese section, and paste it above the journal footer note.

Keep a dated copy of each published version and your original pattern materials for your professional records.

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

- This is a static HTML/CSS/JavaScript site; it does not require a paid service, a database, or a build step.
- The Japanese copy is intentionally simple. Please review and refine it as your Japanese develops before treating it as a polished translation.
- The site is designed to be an artist portfolio and public record of work, not a promise of immigration eligibility.
