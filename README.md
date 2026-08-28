# Fernando Sanchez — CV / Portfolio

A single self-contained `index.html`: a dark, modern developer portfolio for GitHub Pages that doubles as a one-page, print-ready CV (great for job applications and as a LinkedIn "Featured" PDF).

## View it

Open `index.html` in any browser — no build step, no dependencies.

To publish on GitHub Pages: push this folder to a repo and enable Pages on the `main` branch (root), or rename this repo to `nandosanchez14.github.io` for a personal domain.

## Get the PDF

Click **Download CV** (top-right / hero button) or press `Ctrl+P` — the print stylesheet swaps in a clean, ATS-friendly one-page A4 layout automatically. Save as PDF from the print dialog.

## Editing content

- All text lives in the `translations` object near the bottom of `index.html` (search for `var translations = {`). Each entry has an `en` and `es` value — edit either and the on-screen copy updates for that language.
- Language toggle preference is remembered per-browser via `localStorage`.

## Adding real projects

The **Selected Projects** section (`id="projects"`) currently has 3 placeholder cards. Replace each `.project-empty` block with a real card: project name, one-line impact statement, tech stack tags, and a link to the live repo/demo.

## Updating the photo

Replace `assets/foto.jpg` with a new image (keep the same filename, or update the `src` in the `.hero-photo img` tag).
