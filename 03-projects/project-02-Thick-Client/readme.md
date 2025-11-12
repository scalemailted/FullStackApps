# PROJECT (Module-02) — Thick-Client SPA (Local-First + REST)

Build a **single-page application** (SPA) where the **compute, rendering, and state live in the browser**. Read public data with `fetch` (**GET**) and write a small public artifact (**PUT/POST**) to a course-approved service (e.g., JSONBin). Persist personal state locally so the app **relaunches offline**. Choose **one** track: Productivity • Analytics • Games.

---

## 🎯 What you’ll build (at a glance)

- **Rendering stack (pick one)**:  
  DOM/Components (Vanilla, Web Components, Lit, React, Vue) **or** Canvas/WebGL (Phaser, Canvas, PixiJS, p5, Three.js) **or** Viz/Maps (D3, Plotly, Chart.js, ECharts, Leaflet, MapLibre). **You own orchestration**: state → render, lifecycles, effects (not just helper calls).
- **Architecture**: single HTML shell with router/view-manager; **≥ 6 ES modules** and **≥ 3 meaningful classes** (model, system/controller, renderer/view). 
- **Networking**: at least one **public GET** (open API / published CSV/JSON) with loading/empty/error states + TTL cache; at least one **cloud write (PUT/POST)** of a non-sensitive artifact (e.g., preset/run/leaderboard row).
- **Local-first**: autosave and restore from `localStorage`/IndexedDB; app boots from local state before network. (Export/Import JSON recommended.) 

---

## 🗓️ Timeline (21 days, three sprints)

- **Sprint 1 (Days 1–2): Plan** — pitch, architecture sketch, endpoints plan, roadmap, board.  
- **Sprint 2 (Days 3–10): MVP** — vertical slice: input → state → render → **GET** → **PUT/POST**.  
- **Sprint 3 (Days 11–21): Full + Polish** — complete features, interaction depth, responsiveness, docs + deploy. 

---

## ✅ Minimum requirements

1) **Architecture**
- Single HTML shell + client router/view-manager  
- **≥ 6** top-level ES modules; **≥ 3** domain classes  
- Clear responsibilities (model • system/controller • renderer/view) 

2) **Rendering**
- Deep integration of your chosen stack (composition, dataflow, lifecycles)  
- Meaningful interactions (buttons, keyboard/touch, timers/loops) → **state change → re-render**  
- Resize gracefully for laptop (≥1280×720) and tablet (≥768px). If constrained (e.g., keyboard + landscape), show a **Requirements/Not-supported** screen. 

3) **Networking & Local-first**
- **Public GET** with `async/await`, loading/empty/error + TTL cache  
- **Cloud write** (PUT/POST) for a small, non-sensitive artifact (e.g., preset/run)  
- Restore on launch from local storage, then merge network changes

> **Implementation notes** (align with labs): prefer `GET /latest` + `PUT` for JSONBin; cache GETs 30–60 min (TTL); describe a simple merge policy (e.g., last-write-wins via `updated_ts`) in your README.

---

## 📦 Repo & deploy

**Required layout** (adapt as needed for your stack):

```

your-spa/
├─ index.html            # single HTML shell
├─ src/                  # ES modules (≥6)
│  ├─ state/             # central store / models
│  ├─ services/          # publicApi / cloud / local
│  ├─ ui/                # components / views
│  ├─ routes/            # router or view manager
│  ├─ engine|viz/        # renderer, scenes, charts, maps
│  └─ utils/
├─ docs/                 # pitch, roadmap, sketches, DoDs
│  ├─ pitch.md
│  ├─ roadmap.md
│  ├─ architecture\_sketch.md
│  ├─ endpoints.md / jsonbin\_schema.md
│  ├─ dod-sprint1.md / dod-sprint2.md / dod-sprint3.md
│  └─ media/
└─ readme.md             # product-facing (see below)

```

**Deploy**: GitHub Pages (use **hash routing** or a 404 redirect so deep links work). Provide a local run fallback (e.g., `npm run dev` or `npx http-server .`). 

---

## 🧪 Definitions of Done (DoD)

**Sprint 1 — Plan (Days 1–2)**  
- Pitch, public data source, JSONBin plan, architecture sketch, and roadmap in `/docs/`  
- Project board with **8–12** Sprint-2 issues (title, brief AC, labels, size, assignee); board link in README 

**Sprint 2 — MVP (Days 3–10)**  
- From a clean clone, app runs; vertical slice: **input → state → render → GET → PUT/POST**  
- UI states for network; console clean; `/src/` has **≥6 modules** & **≥3 classes**; 30–60s GIF of the flow 

**Sprint 3 — Full + Polish (Days 11–21)**  
- All planned features delivered; multiple input paths; responsive layouts; requirements screen if needed  
- Final README (product-facing) + dev docs; GH Pages deploy or bullet-proof local run; release tag `v1.0-full` 

---

## 📝 README (product-facing) — include:

- **Product name & one-liner**, features, screenshots/GIF or short video  
- **Live demo URL** (Pages) + **Install/Run** steps  
- **How it works** (rendering stack, architecture sketch in 2–3 bullets, local-first behavior)  
- **Data & Networking** (public GET source + tiny response; what you PUT/POST + tiny payload; note TTL + merge policy)  
- **Credits/Licenses**; **Developer docs links** (`/docs/...`) 

---

## 🧑‍🏫 Grading (overview)

- **Sprint 1 — Plan** (20%)  
- **Sprint 2 — MVP** (40%)  
- **Sprint 3 — Full + Polish** (40%)  
Bonus: Showcase-worthy submissions may receive extra credit. (See full rubric in the Module-02 PDF.) 

---

## 🚀 Submission

Submit **three links** on Moodle:
1. **GitHub repo URL**  
2. **GitHub Pages URL** (live app)  
3. **Board filter link** for the current sprint (or release tag link)

---

## 📚 Resources

- **Lab 04 — JS Basics** (`Lab04-JS-Basics.pdf`)  
- **Lab 05 — Phaser Dodger Game** (`Lab05-Phaser-Dodger-Game.pdf`)  
- **Lab 06 — REST Client** (`Lab06-REST-Client.pdf`)  
- **Module-02 Project Spec** — full requirements, tracks, timeline, rubrics. 

> Tip: Start with Sprint-1 docs (pitch, endpoints plan, architecture sketch). In Sprint-2, ship the smallest end-to-end slice first, then iterate.

