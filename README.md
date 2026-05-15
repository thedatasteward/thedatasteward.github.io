# 🔑 The Data Steward — Instagram Project

> **Account:** [@thedatasteward](https://instagram.com/thedatasteward) (TBD — claim during setup)
> **Topic:** Data Governance, in plain English
> **Audience:** Data professionals (engineers, analysts, DPOs)
> **Tone:** Friendly & educational
> **Cadence:** 3 posts every 2 days (~21 posts/2 weeks)

---

## 📂 Project structure

```
the_data_steward_project/
├── README.md                              ← you are here
│
├── 00_setup/
│   ├── setup_playbook.md                  ← step-by-step account setup
│   ├── starter_kit_hosting_guide.md       ← Google Drive instructions
│   └── launch_checklist.md                ← final pre-launch checklist
│
├── 01_brand/
│   ├── brand_guidelines.md                ← colors, fonts, voice
│   ├── bio.md                             ← finalized bio
│   └── profile_picture_the_key.png        ← chosen profile picture
│
├── 02_content/
│   ├── content_calendar.md                ← 2-week, 21-post calendar
│   └── ready_to_post_captions.md          ← copy-paste captions for the 4 produced posts
│
├── 03_assets/                              ← ready-to-post visuals
│   ├── carousels/
│   │   ├── 01_demystified/                ← 6 slides, "Data Governance Demystified"
│   │   └── 02_data_quality/               ← 8 slides, "6 Dimensions of Data Quality"
│   ├── reels/
│   │   ├── REEL_PUBLISHING_GUIDE.md       ← ⚠️ READ BEFORE PUBLISHING
│   │   └── reel_mgmt_vs_governance.mp4    ← 30 sec kinetic typography
│   └── single_images/
│       └── stat_post_12_9M.png            ← $12.9M Gartner stat post
│
├── 04_starter_kit/
│   └── Data_Governance_Starter_Kit.pdf    ← 10-page lead magnet
│
├── 05_source_scripts/                     ← Python scripts (re-run to regenerate)
│   ├── generate_carousel_1.py
│   ├── generate_carousel_2.py
│   ├── generate_reel_1.py
│   ├── generate_stat_post.py
│   ├── generate_starter_kit.py
│   └── generate_profile_pics_v2.py
│
├── 06_game/                               ← interactive game (single-file version)
│   ├── GAME_README.md                     ← hosting + promo guide
│   └── data_steward_game.html             ← the playable game (one HTML file)
│
└── 07_website/                            ← full website hub (deploy to GitHub Pages)
    ├── DEPLOYMENT_GUIDE.md                ← how to put it online
    ├── index.html                         ← homepage
    ├── assets/styles.css                  ← shared design system
    ├── game/index.html                    ← game with site nav
    └── starter-kit/                       ← landing page + PDF download
        ├── index.html
        └── Data_Governance_Starter_Kit.pdf
```

---

## 🚀 Quick start

If you're opening this for the first time, follow this order:

1. **Read** `00_setup/setup_playbook.md` — walks you through Instagram account creation
2. **Deploy the website** — follow `07_website/DEPLOYMENT_GUIDE.md` to put your hub online via GitHub Pages (free, ~30 min)
3. **Schedule** the 4 produced posts using `02_content/ready_to_post_captions.md` (copy-paste captions)
4. **Before publishing the Reel** → read `03_assets/reels/REEL_PUBLISHING_GUIDE.md` (it's silent by design — you need to add audio)
5. **Reference** `02_content/content_calendar.md` for the next 17 posts to produce
6. **Track progress** with `00_setup/launch_checklist.md`

**Time to launch from zero:** ~2 hours (account setup + site deployment + scheduling)

---

## ✅ What's done vs. what's left

### ✅ Done
- Brand identity (name, profile pic, bio, color palette)
- 4 ready-to-post pieces (2 carousels + 1 single image + 1 Reel)
- 10-page PDF lead magnet
- Setup playbook
- Content calendar (21 posts mapped out)

### ⏳ Not yet done
- Instagram account creation (do this manually following the playbook)
- Meta Business Suite connection
- Google Drive hosting for the starter kit
- 17 of the 21 posts in the calendar (templates exist; visuals need creation)
- Highlight cover icons (only matter once you have stories worth grouping)
- Custom link-in-bio page (Linktree free tier is fine to start)

---

## 🔄 How to regenerate assets

All visual assets were generated with Python (PIL + ffmpeg). The source scripts are in `05_source_scripts/`. If you want to:

- **Tweak a color or text** → edit the relevant script, rerun it
- **Build a new carousel** → copy `generate_carousel_2.py` as a template, modify content
- **Update brand voice** → see `01_brand/brand_guidelines.md`

Requirements: `pip install pillow` and `apt install ffmpeg` (for Reels).

---

## 📞 Need help?

When you want to come back and continue building:

- **Highlight cover icons** — generate 5 covers matching your brand
- **Week 2 content** — produce the next batch of 3 posts
- **Custom link-in-bio page** — branded page hosted free on Netlify/GitHub Pages
- **Analytics review** — once you have 2+ weeks of data
- **Email capture upgrade** — when downloads justify it

Just ask.
