# HW01 — Interactive Story (HTML + CSS)

Create and publish a multi-page **interactive story** built with plain HTML (and optional light JavaScript) and styled with CSS. Your story must branch at least **three** times, use common HTML elements (headings, paragraphs, images, lists, tables, links, etc.), and be deployed on **GitHub Pages**.&#x20;

---

## 📦 Required repo & deploy

**You must host your project in a public GitHub repo and enable GitHub Pages.** Use this exact layout:

```
your-repo/
├─ index.html           # landing page (introduces the story, links into /game)
├─ game/                # all game HTML/CSS/JS and assets (scenes, images, audio, video)
│  ├─ scenes/           # optional organization for your pages
│  ├─ styles/           # CSS files
│  ├─ scripts/          # minimal JS (if any)
│  └─ assets/           # images, audio, video, icons
├─ docs/                # documentation (e.g., flowchart of room/scene connections)
│  ├─ flowchart.png or .pdf
│  └─ design_notes.md
└─ readme.md            # this assignment README
```

### GitHub Pages checklist

1. Push your repo to GitHub (public).
2. **Settings → Pages**: Source = “Deploy from a branch”, Branch = `main` (or `master`) / root.
3. Visit the Pages URL it gives you (usually `https://<user>.github.io/<repo>/`).

---

## 🎯 Assignment objectives

* **Author an interactive story in HTML** that showcases headings, paragraphs, images, lists, tables, hyperlinks, and multi-page navigation. Include **≥ 3 branch points** in the narrative.&#x20;
* **Style the experience with CSS** using cohesive colors and typography to create an attractive, readable UI across all pages.&#x20;

> Why this? You’ll practice real page composition, navigation, and presentation choices in HTML/CSS; it also makes a solid portfolio piece you can show recruiters.&#x20;

---

## ✅ Minimum requirements (what to build)

1. **Landing page (`index.html`)**

   * Title, short premise, and a clear “Play” entry into `/game/`.
   * Attribution/footer as appropriate.
   * Favicon optional but encouraged.&#x20;

2. **Game pages (`/game`)**

   * **Multiple scenes** as separate HTML files.
   * **≥ 3 branches** in the story (choices that lead to different pages/outcomes).&#x20;
   * Use a **variety of HTML elements** (e.g., images, lists, tables, links; optional audio/video).&#x20;
   * **Navigation** between scenes via links/buttons.
   * **CSS styling** applied across pages (external stylesheets preferred).&#x20;

3. **Docs (`/docs`)**

   * A **flowchart** of your scene/room graph (PNG or PDF) showing how pages connect (see *Goal 0* flowchart example in the lab, **page 5**).&#x20;
   * Short notes (if needed) describing any special mechanics/riddles.

4. **readme.md**

   * Project title & pitch, how to play, your Pages URL, tech used, credits.

> Tip: The **Lab 01** handout walks you through building a similar multi-page story step-by-step (index, scenes, inventory/iframe, simple inputs, etc.). Use it as a model.&#x20;

---

## 🧑‍🏫 Grading rubric

* **Part 1 – \[Write] Story Flowchart** (branches & riddles) — **20%**&#x20;
* **Part 2 – \[Show] Story Text, Media & Visuals** — **20%**&#x20;
* **Part 3 – \[Controls] Story Inputs & Player Choices** — **20%**&#x20;
* **Part 4 – \[Beautify] CSS Styles** — **40%**&#x20;
* **Part 5 – \[Bonus] Outstanding Submission** — **0–20%** (novelty/polish).&#x20;

---

## 🚀 Submission

Turn in **two links** on Moodle:

1. Your **GitHub repo URL**.
2. Your **GitHub Pages URL** (the live game).

> Historically, zipping and uploading was allowed, but for this assignment you must deploy on GitHub Pages and provide links. (The original homework also discusses zip submissions; we’re standardizing on Pages for the showcase requirement.)&#x20;

---

## 🌟 Showcase demos (play these for inspiration)

* Flasked Interactive — [https://scalemailted.github.io/FlaskedInteractive/](https://scalemailted.github.io/FlaskedInteractive/)
* Mystic Manor — [https://scalemailted.github.io/MysticManor/](https://scalemailted.github.io/MysticManor/)
* Castle Maven — [https://scalemailted.github.io/CastleMaven/](https://scalemailted.github.io/CastleMaven/)

You can also browse interactive-fiction examples for ideas.&#x20;

---

## 🧭 Design & implementation tips

* **Start with structure.** Sketch your scene graph first (flowchart). Keep scope tight; **less is more**. &#x20;
* **Keep pages scannable.** Break text into short blocks; use sub-headers, lists, and images to avoid “walls of text.”&#x20;
* **Cohesive styling.** Limit yourself to \~**3 colors** and **2 fonts** for consistency—break rules only for clear story reasons (e.g., different character voices).&#x20;
* **Be creative. Don’t over-polish. Use Google.** You’re aiming for a complete, playable draft.&#x20;
* **Optional mechanics from the lab:** simple inputs, basic state via query strings/iframes, small combat/riddle gates. See Lab sections on inventory, overworld links, shop/goblin examples (*Goals 3–11*).&#x20;

---

## 🔍 What to include in your README (template)

```md
# <Your Story Title>

Live demo: https://<yourname>.github.io/<repo>/
Repo: https://github.com/<yourname>/<repo>

## Pitch
1–2 sentences about the premise and tone.

## How to Play
- Click “Start” on the landing page.
- Make choices to explore different branches (≥ 3).
- Optional: mention any puzzles, codes, or endings.

## Tech
- HTML (multi-page), CSS (external stylesheets)
- Optional: Minimal JS for simple interactions

## Repo Layout
- `index.html` — landing & start
- `/game` — scenes, styles, scripts, assets
- `/docs` — `flowchart.png` or `.pdf`, notes

## Credits
Art/audio sources, attributions, classmates, etc.
```

---

## 📚 Resources

* **Homework 1: HTML + CSS** — requirements, rubric, and styling guidance.&#x20;
* **Lab 01: HTML Frontend** — step-by-step interactive-story walkthrough (including the **flowchart on page 5** and multi-page navigation examples).&#x20;

Good luck, have fun, and build something you’d be proud to show in a portfolio!
