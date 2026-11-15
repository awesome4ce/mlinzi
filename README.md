# Mlinzi


Live demo: https://mlinzi-seven.vercel.app
Clickable product demo for **Mlinzi** (Swahili for "guardian"): a premium health wearable plus a remote care team (AI monitoring, nurse follow-up, doctor escalation) for affluent Kenyans, partnered with private insurers.

Class project for GENE 225, Stanford, Fall 2026, by Ethan Seung and Steven Diaz. All people, readings, and pilot figures are fictional.

## Editing

The whole site is one file: `index.html` (HTML, CSS, and vanilla JS, no build step).

1. Edit `index.html`.
2. Open it in a browser to check.
3. Commit and push to `main`. Vercel redeploys automatically.

Views are routed by URL hash: `#member`, `#care`, `#insurer`, `#compare`.

## Design tooling

The repo includes the [Impeccable](https://impeccable.style) design skill for Claude Code in `.claude/`. To get its engine and hooks on your machine, run `npx impeccable install --project --providers=claude` in the repo, then `/impeccable` in Claude Code.
