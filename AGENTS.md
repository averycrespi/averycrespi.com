# AGENTS.md

## Project Context

- This is Avery Crespi's personal website repository.
- The site is a small static site published with GitHub Pages.
- GitHub Pages is configured outside the local repo to deploy automatically from the `main` branch to <https://averycrespi.com>.
- Keep changes simple and appropriate for a public personal website unless Avery asks for a larger redesign or framework migration.

## Repository Shape

- `index.html` is the current homepage.
- `CNAME` configures the custom domain for GitHub Pages and should remain `averycrespi.com` unless Avery explicitly asks to change it.
- The site uses Vite as a lightweight dev server/build tool. Prefer plain HTML/CSS/JavaScript for small changes.

## Public Repo and Sensitive Information

- This repository is public. Do not add secrets, credentials, API keys, tokens, private config, unpublished addresses, financial details, private contact details, or other sensitive information.
- Personal information that Avery intentionally wants published on the website is allowed. This can include bio content, public contact links, work history, projects, photos, writing, and other public-facing details Avery provides or approves.
- If a requested change appears to expose sensitive information unintentionally, pause and flag it before committing it to the repo.

## Development Guidelines

- Read existing files before editing them.
- Make small, focused changes and avoid introducing new dependencies unless there is a clear reason.
- Preserve accessibility basics: semantic HTML, meaningful link text, alt text for images, keyboard-friendly interactions, and sufficient color contrast.
- Keep pages lightweight and fast; avoid unnecessary JavaScript.
- Use relative paths for local assets so the site works correctly on GitHub Pages.
- When adding assets, use descriptive filenames and keep file sizes reasonable.

## Verification

- For local development, run `npm install` once and `npm run dev` for Vite's live-reloading server.
- For HTML/CSS/JavaScript changes, run `npm run build` and, when possible, open or serve the page locally to check rendering and browser console output.
- Before reporting work complete, check `git status --short` and summarize changed files.

## Git and Deployment Notes

- Do not commit or push unless Avery explicitly asks.
- Changes merged or pushed to `main` will be deployed by GitHub Pages to <https://averycrespi.com>.
- Be extra careful with anything merged to `main` because it becomes public-facing automatically.
