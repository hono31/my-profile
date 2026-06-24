# AGENTS

## Project type
Static personal profile site built with plain HTML and Tailwind CSS via CDN.

## Key facts for AI agents
- No JavaScript bundler, no npm/yarn, no build system.
- Pages are authored as standalone HTML files: `index.html`, `week03.html`, `week04.html`, `week3.html`, `minidril.html`, plus `omg2/` and image assets under `img/`.
- Tailwind CSS is loaded directly from `https://cdn.tailwindcss.com`.
- The repo includes Japanese text and simple layout content; preserve language and semantic structure.

## When making changes
- Prefer updating existing HTML pages rather than adding new frameworks or build tools.
- Keep styling in HTML through Tailwind utility classes unless the user explicitly requests a different approach.
- Preserve relative paths for images and links.
- Maintain valid HTML structure and close tags properly.
- Avoid adding external dependencies beyond the current Tailwind CDN usage.

## Useful file references
- `index.html` — main profile page
- `week03.html`, `week04.html`, `week3.html`, `minidril.html` — additional project pages
- `img/` — images referenced by HTML pages
- `README.md` — repository description

## Notes for code generation
- This workspace is best served by small, static HTML/CSS updates.
- There are no automated tests or build commands to run; validate changes by opening HTML files in a browser.
- If asked to improve accessibility or structure, use semantic HTML elements and maintain the existing visual style.
