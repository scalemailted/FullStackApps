# CSCI 4208 — Labs

This folder contains the **required labs** for the course and a **supplemental-labs** section with optional/legacy exercises for extra practice.

## Required Labs

1. **Lab 01 — HTML Frontend (Interactive Story)**
   Build a multi-page HTML “choose-your-path” story; practice elements, attributes, links, tables, media, and simple state via query strings and inline javscript via HTML script elements.&#x20;

2. **Lab 02 — CSS Crash Course**
   Style pages with selectors, colors, fonts, spacing, sizing, backgrounds, and responsive alignment (flexbox & grid).&#x20;

3. **Lab 03 — Bootstrap Frontend (Portfolio Site)**
   Create a responsive portfolio using Bootstrap components: containers, grid, cards, carousel, and a collapsible navbar.&#x20;

4. **Lab 04 — JavaScript + DOM + Events (Hi-Lo Game)**
   Implement a browser SPA that evolves from MVP to MVC, handling DOM updates, events, and timed interactions.&#x20;

5. **Lab 05 — JavaScript OOP + Phaser (✳️ choose ONE)**  
   You will complete **one** of the two Phaser labs below. Both use OOP patterns and scenes.
   - **Lab 05A — Dodger Game (Phaser 3)**  
     Movement, enemies, collisions, scoring, projectiles, power-ups, and scenes.
   - **Lab 05B — Platformer Game (Phaser 3)**  
     Tilemap + gravity + collisions, hazards/collectibles/enemies, win/lose conditions, title screen.
   > Pick either **Dodger** or **Platformer**. Keep both folders if you like, but only one is required for credit.

6. **Lab 06 — REST Client (Fetch + ES Modules)**  
   Build a browser app (Quiz Game) that performs real HTTP requests (e.g., GET from a public API and PUT/POST to a simple backend or JSON bin). Organize code with **ES modules** and handle loading/empty/error states.

7.  **Lab 07 — Browser Data Layer (Mock Document DB)**  
    Implement a storage-agnostic, client-side data layer that mimics a Mongo-style document database. Students will build swappable **persistence adapters** for **LocalStorage** (local) and **JSONBin** (cloud), learning to manage application state, handle `async` operations, and structure code around a clean, reusable CRUD API.


## Optional / Legacy 
* **(Optional) Lab 05 — Phaser Explorer - Complete Reference Build + Instructions**  
  A **fully working Phaser 3 “Explorer” game** (scenes, tilemap, collisions, UI) with a **step-by-step walkthrough** explaining setup, file structure, and how to extend features. Use it as a reference implementation or compare against your own build.



* **(Legacy) Lab 05 — JS OOP + Canvas API (Platformer)**
  A physics-based platformer using raw Canvas API with an OOP architecture (blocks, hazards, exit, animation). Great for extra practice or comparison with Phaser.&#x20;


* **(Optional) Lab 06 — HTTP + Async Frontend: Contact Form (Google Forms backend)**  
  Build a portfolio **contact form** that **POSTs** to a **Google Form** backend. Start with vanilla HTML `<form>` submission, then progressively refactor to **DOM-driven attributes**, **query-string encoding**, and a pure **async/await + fetch** implementation (no server code required). Suggested structure:  
  `supplemental-labs/lab-06-contact-form/` with `index.html`, `scripts/form-model.js`, `scripts/form-controller.js`. 

> ✅ **Reminder:** Only the labs listed under “Required Labs” are due for credit. `supplemental-labs/` are **optional**.

---

## How to submit each required lab

1. Create a subfolder per lab (e.g., `lab-01/`, `lab-02/`, …) under this directory.
2. Put **all source files** needed to run/review your work in that subfolder (assets, code, etc.).
3. Add a short `README.md` inside your lab folder with:

   * **How to run/review** (e.g., open `index.html`, start local server, etc.)
   * A screenshot or GIF (optional but encouraged)
4. Commit & push.
5. Open/Update the corresponding **Lab Issue** on your project board and check off the acceptance/deliverables for that lab.

---

