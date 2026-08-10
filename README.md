# fedge2o.com

Public site for **FEDGE 2.O** — the AI command ecosystem by Eclat Universe.

**Live:** https://fedge2o.com

## Why this repo exists

The main [FEDGE-2.O](https://github.com/cryptofedge/FEDGE-2.O) repo is private and
its git history contains credentials that must not be republished. GitHub Pages
does not run on a private repo without a paid plan, so the site is served from
this separate public repo instead. Nothing sensitive lives here.

## Contents

| Path | What it is |
|---|---|
| `index.html` | The site — single file, inline CSS and JS |
| `assets/logo.png` | FEDGE 2.O / Eclat É mark |
| `assets/e-logo.png` | Eclat Universe mark |
| `assets/fedge-character.png` | FEDGE 2.O Glitch Edition character |
| `assets/fedge-bg.mp4` | Looping silent universe backdrop (2.6 MB) |
| `command-center/index.html` | Snapshot of the Command Center dashboard |
| `CNAME` | Custom domain — `fedge2o.com` |

## Notes

- **The Command Center is a snapshot.** It is copied from
  [fedge-command-center](https://github.com/cryptofedge/fedge-command-center) so
  the launch button stays on `fedge2o.com` instead of leaving for `github.io`.
  Pushes to that repo do **not** propagate here — re-copy `index.html` to update.
- **Store buttons are in a pending state.** The Play listing for
  `com.eclatuniverse.fedge2o` is not published yet, so neither store button is a
  link. See the comment above `.store-row` in `index.html` for the exact swap.
- The background video is muted, looped and `playsinline`, and pauses entirely
  under `prefers-reduced-motion`.

---

Built by Rafael Fellito Rodriguez Jr. · © 2026 Eclat Universe · All Rights Reserved
