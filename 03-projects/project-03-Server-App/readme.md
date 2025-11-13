# PROJECT (Module-03) — Thick-Server App (REST API + Thin Client)

Build an **authoritative, server-first application** where the **compute, logic, and state live in Node.js**. Expose a REST API with Express, persist data to a file-backed JSON DB, and serve a **thin client** that only issues requests and renders results. Choose **one** track: API Portal (Public API) • Thin UI (Private API).

---

## 🎯 What you’ll build (at a glance)

- **Server Stack**:
  Node.js, `npm`, **Express** for all routing, and integrated middleware for **request parsing, logging, sessions, and error handling**.
- **Architecture**: A layered server with a `src/` directory containing at least four distinct layers: `db/` (persistence), `services/` (core logic), `api/` (routes), and `middleware/`.
- **API**: **Full CRUD support** for at least one primary resource, plus **at least one relational endpoint** (e.g., `GET /users/:id/tasks`). All business logic must reside on the server.
- **Persistence**: A **file-backed JSON database** you implement, featuring atomic writes (`.tmp` → `rename`) and durability across server restarts.

---

## 🗓️ Timeline (21 days, four sprints)

- **Sprint 1 (Days 1–3): Database** — Refactor the browser DB to run in Node.js and pass all tests.
- **Sprint 2 (Days 4–6): Plan** — Pitch, architecture sketch, API endpoint design, roadmap, and project board.
- **Sprint 3 (Days 7–14): MVP** — Build a vertical slice: a working API and thin client for one full CRUD flow.
- **Sprint 4 (Days 15–21): Full + Polish** — Complete all features, polish the client, and finalize all documentation.

---

## ✅ Minimum requirements

1) **Architecture & Server Logic**
- Layered `src/` directory: `db`, `services`, `api`, `middleware`.
- Route handlers in the `api` layer must contain **no business logic**; they only validate requests and call the `services` layer.
- All application rules, state changes, and logic must reside in the `services` layer.

2) **API & Networking**
- Use correct RESTful methods (`GET`, `POST`, `PUT`/`PATCH`, `DELETE`) and status codes (`200`, `201`, `204`, `400`, `404`).
- Implement a centralized error handler that returns a consistent JSON error envelope.
- Implement session management to identify a client across multiple stateless requests.

3) **Persistence & Thin Client**
- The file-backed database must pass all provided tests, demonstrating durability.
- The thin client must remain **lean**, containing no business logic.
- The client must clearly show **feedback states** for all network actions (loading, success, error, empty).

> **Implementation notes**: The server is the single source of truth; re-validate all data sent from the client. Serve your client from the same origin as your server to avoid CORS. Use a `GET /health` endpoint for easy session debugging.

---

## 📦 Repo & Running

**Required layout** (adapt as needed for your stack):

```
your-server-app/
├─ data/                 # Your JSON database files
├─ public/               # Your thin client (HTML, CSS, JS)
├─ src/                  # ALL server-side modules (≥4 layers)
│  ├─ db/                # Persistence Layer
│  ├─ services/          # Domain Logic Layer (the "brain")
│  ├─ api/               # API/Routing Layer
│  └─ middleware/        # Session management, error handling
├─ docs/                 # pitch, roadmap, sketches, DoDs
│  ├─ pitch.md
│  ├─ roadmap.md
│  ├─ architecture_sketch.md
│  ├─ api_endpoints.md
│  └─ dod-sprint1.md ...
├─ server.js             # Entry point: creates Express app
└─ readme.md             # Product-facing (see below)
```

**Running**: The project must be runnable from a clean clone with standard Node.js commands. Provide clear, bulletproof `npm` scripts. Example: `npm install`, then `npm start`.

---

## 🧪 Definitions of Done (DoD)

- **Sprint 1 — Database:** The DB module is refactored for Node.js and **passes all provided test scripts**.
- **Sprint 2 — Plan:** All planning documents (`pitch`, `roadmap`, `architecture`, `api_endpoints`) are complete in `/docs/`. The GitHub Project board is created and linked in the main `README.md`.
- **Sprint 3 — MVP:** A full end-to-end CRUD flow for **one resource** is demonstrably working between the API and the thin client.
- **Sprint 4 — Full + Polish:** All features from the roadmap are delivered, including relational endpoints. The client is polished and the final `README.md` is complete with a demo GIF.

---

## 📝 README (product-facing) — include:

- **Product name & one-liner**, what it does, screenshots/GIF or short video.
- **Install & Run** steps (e.g., `npm install`, `npm start`).
- **How it works** (brief description of the thick-server architecture and tech stack).
- **API Usage Examples** (2-3 `curl` or `fetch` snippets for key endpoints).
- **Developer docs links** (`/docs/...`).

---

## 🧑‍🏫 Grading (overview)

- **Sprint 1 — Database** (20%)
- **Sprint 2 — Plan** (15%)
- **Sprint 3 — MVP** (35%)
- **Sprint 4 — Full + Polish** (30%)
Bonus: Showcase-worthy submissions may receive extra credit. (See full rubric in the Module-03 PDF.)

---

## 🚀 Submission

Submit **two links** on Moodle for each sprint deadline:
1.  **GitHub repo URL**
2.  **GitHub Project board filter link** showing the completed issues for that sprint.

---

## 📚 Resources

- **Lab 07 — Mock DB in Browser** (The code to be refactored for Part 1)
- **MUD Example Codebase** (Reference architecture)
- **Module-03 Project Spec** — full requirements, tracks, timeline, rubrics.

> Tip: Get your database tests passing in Sprint 1 first. A solid, reliable data layer is the foundation for the entire application.