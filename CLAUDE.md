# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Rules

- Never run git commands that change anything: no `git add`, `commit`, `push`, `pull`, `merge`, `reset`, `checkout`, etc. Read-only commands (`git status`, `git log`, `git diff`, `git show`) are fine. The user stages, commits and pushes themselves.
- Keep replies short and in plain English.

## What this is

A static marketing site for the "Spicy Couples Game" mobile app (adults 18+). It's plain HTML and CSS, with no build step, no dependencies and no tests. It is hosted on GitHub Pages at `https://elizmatsen.github.io/spicy-couples-site/` (repo `ElizMatsen/spicy-couples-site`, branch `main`, root folder).

- `index.html`: the landing page.
- `privacy.html`, `terms.html`: the legal pages. The app links to these URLs, so keep the file names unchanged.
- `style.css`: the one stylesheet that all pages share.
- `.nojekyll`: stops GitHub Pages from running Jekyll. Keep it.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
