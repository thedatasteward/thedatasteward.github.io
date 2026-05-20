# thedatasteward.github.io

Live site for **The Data Steward** — data governance, in plain English.

🌐 **Live at:** [thedatasteward.github.io](https://thedatasteward.github.io)

## Structure

```
index.html                          ← Homepage
assets/styles.css                   ← Shared styles (nav, header, footer)

games/                              ← Interactive games
├── index.html                      ← Games hub (lists all games)
├── quiz/index.html                 ← "Data Steward: The Quiz" — 8 scenarios
├── lineage/index.html              ← "Lineage Hunt" — GDPR puzzle, 3 levels
└── incident/index.html             ← "Incident Comms Simulator" — 7-msg crisis sim

library/                            ← Downloadable docs & PDFs
├── index.html                      ← Library hub (lists all docs)
└── starter-kit/
    ├── index.html                  ← Starter Kit landing page
    └── Data_Governance_Starter_Kit.pdf
```

### Adding a new game

1. Create `games/<your-game>/index.html`
2. Add a card to `games/index.html`
3. (Optional) Feature it on the homepage `index.html`

### Adding a new document / PDF

1. Create `library/<your-doc>/index.html` (landing page) + drop the PDF in the same folder
2. Add a card to `library/index.html`
3. (Optional) Feature it on the homepage `index.html`

## Updating the site

Edit files directly on GitHub (pencil icon) or locally:

```bash
git add .
git commit -m "Describe your change"
git push
```

GitHub Pages redeploys automatically in ~1 minute.

## Branch naming convention

All work happens on a branch off `main`, merged via PR. Use a `type/short-kebab-description` slug.

| Prefix    | Use for                                                  | Example                              |
|-----------|----------------------------------------------------------|--------------------------------------|
| `feat/`   | New games, new docs, new pages, new sections             | `feat/lineage-hunt-game`             |
| `fix/`    | Bug fixes — broken links, layout glitches, typos in copy | `fix/quiz-answer-shuffle`            |
| `content/`| Copy-only changes (rewording, new captions, blurbs)      | `content/homepage-tagline`           |
| `docs/`   | README / internal docs only                              | `docs/branch-naming`                 |
| `chore/`  | Repo housekeeping — restructure, gitignore, deps         | `chore/site-restructure`             |
| `style/`  | Visual-only tweaks (colors, fonts, spacing)              | `style/library-hub-cards`            |

Rules:
- Lowercase, dash-separated, no spaces.
- Keep it short — 2 to 5 words after the prefix.
- One branch = one logical change. Don't pile unrelated work into one branch.
- Delete the branch after merge.

## Source materials

Drafts, scripts, brand assets, and deployment notes live in the private companion repo
`thedatasteward/content-source`.
