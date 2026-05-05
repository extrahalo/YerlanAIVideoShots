# Aizhan shotlist site

This folder contains the public web pages for the rough-edit shotlist and character approval board of the film "Aizhan. Mura".

## Files

- `index.html` — the rough-edit shotlist page.
- `characters.html` — the character approval page with generated concept images and browser-saved comments.
- `assets/characters-github/` — lightweight generated character previews used by the public page.

## Publishing workflow

Recommended setup:

1. Create a GitHub repository named `aizhan-shotlist`.
2. Upload `index.html` from this folder.
3. Enable GitHub Pages:
   - Settings
   - Pages
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/root`
4. The public page will be available at:
   `https://<github-username>.github.io/aizhan-shotlist/`

## Update workflow with Codex

When the shotlist changes:

1. Ask Codex to update the page.
2. Codex edits `shotlist-site/index.html`.
3. The updated file is pushed or uploaded to the same GitHub repository.
4. GitHub Pages refreshes the same public link.
