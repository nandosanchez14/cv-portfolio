# Fernando Sanchez — Portfolio & CV

Tech Lead · .NET / C# · ASP.NET Core · SQL Server

**Live:** https://nandosanchez14.github.io/cv-portfolio/

A single self-contained `index.html` (no build step, no dependencies) that serves as a bilingual (EN/ES) portfolio and doubles as a one-page, print-ready A4 CV.

## Get the PDF

Click **Download CV** or press `Ctrl+P` — the print stylesheet swaps in the one-page CV layout. Save as PDF from the print dialog.

Force a language with `?lang=en` or `?lang=es`, e.g. to export each version:

```
chrome --headless --no-pdf-header-footer --print-to-pdf=CV_EN.pdf "index.html?lang=en"
```

## Editing content

- All copy lives in the `translations` object at the bottom of `index.html` (`en` and `es` entries). The portfolio and the printable CV (`#print-cv`) share the same keys, so they stay in sync.
- The phone number is intentionally not published on the site. The private PDF build injects it at the `<!--PHONE-->` marker.
- Photo: `assets/foto.jpg`.

## Related repositories

- [employee-management-api](https://github.com/nandosanchez14/employee-management-api) — HR REST API, .NET 9, role-based JWT, reports, xUnit + CI
- [ai-smart-notes-api](https://github.com/nandosanchez14/ai-smart-notes-api) — Notes API with GPT-4o summaries, classification and tagging
- [task-management-api](https://github.com/nandosanchez14/task-management-api) — Task API, .NET 9, JWT, layered architecture
