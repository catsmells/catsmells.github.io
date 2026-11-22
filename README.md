# The M&M Stats Guide

A study guide for STAT1000 Midterm 2 (Fall 2026). Every concept on the exam is
shown with M&Ms and solved with algebra. It also has the midterm worked out, a
full practice test, a cheat sheet and a z-table.

It's a static site: one self-contained `index.html` (no build step, no
dependencies; fonts load from Google Fonts) plus a printable `cheat-sheet.pdf`.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole guide: chapters, interactive diagrams, practice test, z-table |
| `cheat-sheet.pdf` | One-page letter-size cheat sheet, linked from the guide |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Live site

https://catsmells.github.io/ is served by GitHub Pages from the root of the
`main` branch. To update it: edit, commit, `git push`. Pages rebuilds in about
a minute.

The site that was here before this guide is still in the git history (last
commit `d1ac445`). `git checkout d1ac445 -- .` brings its files back.

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder
and visit http://localhost:8000.
