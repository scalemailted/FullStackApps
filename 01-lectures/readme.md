# 📺 FullStackApps Course Videos

This repository contains links to lecture, lab, and project advice videos for the **Developing Advanced Web Applications (FullStackApps)** course.

---

## 🎓 Lecture Videos (Legacy)
**YouTube Playlist:**  
[Lecture Playlist](https://www.youtube.com/playlist?list=PL30Wd5ZPaqMP_2Qlm6tCUakku2OS3zjBf)

### Frontend
- Lecture 01: Introductions & HTML  
- Lecture 02: CSS  
- Lecture 03: Browser Tools  
- Lecture 04: Bootstrap  
- Lecture 05: JavaScript – Basics  
- Lecture 06: JavaScript – Data Structures (Part 1)  
- Lecture 07: JavaScript – Data Structures (Part 2)  
- Lecture 08: JavaScript – OOP  
- Lecture 09: JavaScript – Standard Objects  
- Lecture 09A: JavaScript – DOM (Part 1)  
- Lecture 09B: JavaScript – DOM (Part 2)  
- Lecture 10: JavaScript – Events  
- Lecture 11: HTTP – Client  
- Lecture 12: JavaScript – Asynchronous  
- Lecture 13: JavaScript – Modules  

### Backend
- Lecture 14: Backend Overview  
- Lecture 15: Node – Basics  
- Lecture 16: Node – Core Modules  
- Lecture 17: NPM – Basics  
- Lecture 18: Express  
- Lecture 19: HTTP – Server  
- Lecture 20: Authentication  
- Lecture 21: MongoDB – Basics (Part 1)  
- Lecture 22: MongoDB – Basics (Part 2)  
- Lecture 23: MongoDB – Basics (Part 3)  
- Lecture 24: REST API & Microservices  
- Lecture 25: Web Sockets  
- Lecture 26: React – JSX, Components, Props  
- Lecture 27: React – Functional Programming & Hooks  
- Lecture 28: React – OOP & Classes  

---

## 🛠️ Lab Videos (Legacy)
**YouTube Playlist:**  
[Lab Playlist](https://www.youtube.com/playlist?list=PL30Wd5ZPaqMNC91jXmyl8RxH07RYwdszc)

### Frontend
- Lab 0: Introductions  
- Lab 1: HTML – Interactive Game (Part 1)  
- Lab 1: HTML – Interactive Game (Part 2)  
- Lab 2: CSS – Crash Course  
- Lab 3: Bootstrap – Portfolio Site  
- Lab 4: JS OOP – Platform Game (Part 1)  
- Lab 4: JS OOP – Platform Game (Part 2)  
- Lab 4: JS OOP – Platform Game (Part 3)  
- Lab 4: JS OOP – Platform Game (Part 4)  
- Lab 5: DOM + Events – HiLo Game (Part 1)  
- Lab 5: DOM + Events – HiLo Game (Part 2)  
- Lab 6: HTTP Post + Form Submits – Contact Page  
- Lab 7: Async JS + Modules – Quiz Game with Leaderboard (Part 1)  
- Lab 7: Async JS + Modules – Quiz Game with Leaderboard (Part 2)  

### Backend
- Lab 8: Node + NPM – Static Web Server  
- Lab 9: Express – Dynamic Web Server  
- Lab 10: REST API Server – Multiplayer HiLo  
- Lab 11: REST API Client – Multiplayer HiLo  
- Lab 11: Bug Fix!  
- Lab 12: Passport + Sessions – User Auth (Part 1)  
- Lab 12: Passport + Sessions – User Auth (Part 2)  
- Lab 13: WebSockets + Socket.IO – Chatroom  
- Lab 14: MongoDB University  
- Lab 15: MongoDB CRUD + JWT App  
- Lab 16: React + JSX – Quiz Game with Leaderboard  

---

## 💡 Project Advice (Legacy)
**YouTube Playlist:**  
[Project Advice Playlist](https://www.youtube.com/playlist?list=PL30Wd5ZPaqMOYdu2COwuydM8YwD-Iz7sH)

- Part 0: (2021)  
- Part 1: (2022)  
- Part 2: (2022)  

---


# 📖 Lecture Slide Summaries

Below is a complete account of all lecture slide decks (Lectures 1–28).  
Each lecture includes **Motivation (Why)** and **Contents (You’ll learn)**.


---

## Frontend Lectures (1–11)

### Lecture 1 — Web Clients & HTML Crash Course  
**Why:** HTML is the foundation of the web. Understanding its role as the “content layer” prepares you to build structured, accessible web pages before adding styling or logic.  

**You’ll learn:**  
- What a web application is and how browsers process requests.  
- Anatomy of an HTML document: elements, attributes, nesting.  
- Block vs inline elements.  
- Separation of content (HTML) vs presentation (CSS).  
- Basic workflow: create and open your own `.html` file in a browser.  

---

### Lecture 2 — CSS Crash Course  
**Why:** HTML alone cannot handle design; CSS defines the presentation and enables maintainable, reusable styling. It separates structure from design and supports the DRY principle.  

**You’ll learn:**  
- What CSS is and why it exists.  
- How to import CSS into HTML (`<link>`).  
- CSS syntax: selectors and declaration blocks.  
- CSS selectors (element, class, id; plus cascade rules).  
- Colors: RGB, HEX, HSL, alpha transparency, named colors.  
- Fonts: families, properties, Google Fonts, pairing guidelines.  
- Spacing: box model (content, padding, border, margin), width/height.  
- Backgrounds: color, images, repeat, positioning.  
- Common element customizations (links, lists, tables, buttons).  
- Layout: Flexbox and Grid basics for alignment and responsive design.  

---

### Lecture 3 — Browser Tools (DevTools)  
**Why:** The browser is not just a viewer — it’s your debugging and development environment. Mastering DevTools accelerates testing, debugging, and iteration.  

**You’ll learn:**  
- Difference between “View Source” and the live DOM.  
- Elements panel: inspecting and editing DOM and styles.  
- Console panel: running JavaScript, debugging logs.  
- File URLs vs HTTP serving.  
- Running a local server.  
- Hosting static files with GitHub Pages.  

---

### Lecture 4 — Bootstrap Crash Course  
**Why:** CSS frameworks accelerate design with prebuilt responsive components. Bootstrap introduces layout grids, utilities, and styled components that simplify development.  

**You’ll learn:**  
- Containers, rows, and responsive grid system.  
- Spacing utilities (margin, padding).  
- Text, icons, and colors.  
- Lists, tables, and images.  
- Navbars, cards, carousels.  
- When Bootstrap requires JS (e.g., collapsible components).  

---

### Lecture 5 — JavaScript Basics  
**Why:** JavaScript adds interactivity and logic to the web. This lecture builds the foundation for programming in the browser.  

**You’ll learn:**  
- Data types: primitives vs reference.  
- Variables: `var`, `let`, `const` and scope rules.  
- Operators and control flow.  
- Functions: declarations, expressions, arrow functions.  
- Closures and lexical scope.  
- Hoisting and function behavior.  
- Loose vs strict equality (`==` vs `===`).  

---

### Lecture 6 & 7 — JavaScript Data Structures  
**Why:** Managing collections and transforming data is core to application logic. Modern JS emphasizes functional methods and clean data handling.  

**You’ll learn:**  
- Arrays: creation, mutation, spread/destructuring.  
- Common methods: `splice`, `slice`, `concat`.  
- Search and iteration: `map`, `filter`, `reduce`, `every`, `some`.  
- Sets: uniqueness and transformations.  
- Maps: key–value pairs, conversion to/from objects and arrays.  
- Iterators: `keys`, `values`, `entries`, `next()`.  
- Destructuring and rest parameters for concise code.  

---

### Lecture 8 — JavaScript Objects & Classes  
**Why:** Objects model real-world data, and classes provide structure and reuse. Mastering OOP prepares you for scalable front-end applications.  

**You’ll learn:**  
- Objects: properties, methods, access/mutation.  
- Copying: shallow vs deep.  
- Classes: fields, constructors, methods.  
- Private fields (`#`) and encapsulation.  
- `this` binding and pitfalls.  
- Static vs instance methods.  
- Inheritance: `extends`, `super`, overrides.  
- Prototype chain and `instanceof`.  

---

### Lecture 9 — Document Object Model (DOM)  
**Why:** The DOM connects JavaScript with HTML, letting code dynamically read and manipulate page content.  

**You’ll learn:**  
- DOM vs BOM, tree of nodes.  
- Query methods: `getElement*`, `querySelector*`, `closest`.  
- Live vs static node collections.  
- Node properties: `innerHTML`, `textContent`, `hidden`.  
- Modifying DOM: create, insert, replace, remove, clone.  
- `insertAdjacentHTML` for efficient updates.  
- Styling with `classList`, inline styles, computed styles.  
- Measuring element/window sizes and coordinates.  

---

### Lecture 10 — Events  
**Why:** Events make apps interactive. Understanding the event model enables responsive UI without hacks.  

**You’ll learn:**  
- Event loop basics.  
- Handler registration: inline, property, `addEventListener`.  
- Event object properties.  
- Bubbling vs capturing, `stopPropagation`.  
- Event delegation for efficient listeners.  
- Mouse, keyboard, and touch events.  
- Form and input events.  
- Timers and animation: `setTimeout`, `setInterval`, `requestAnimationFrame`.  
- Custom events.  

---

### Lecture 11 — HTTP (Client Perspective)  
**Why:** All web apps rely on HTTP. Understanding requests and responses is key to integrating APIs and backends.  

**You’ll learn:**  
- Client–server architecture, stateless requests.  
- URL anatomy: scheme, host, port, path, query, hash.  
- Request structure: methods, headers, body.  
- Response structure: headers, status codes, body.  
- Safety and idempotency of HTTP verbs.  
- Built-in HTML requests: `<a>`, `<form>`.  
- Fetch API: `fetch()`, `Request`, `Response`, `Headers`, `Body`.  
- Tools: curl, Postman/Hoppscotch, DevTools Network panel.  

---

## Backend Lectures (12–20)

### Lecture 12 — Asynchronous JavaScript  
**Why:** Modern web apps rely on non-blocking operations. Asynchronous JS avoids freezing the UI and enables calls to servers, APIs, and databases without halting execution.  

**You’ll learn:**  
- Promises: states (pending, fulfilled, rejected), chaining, error handling.  
- Consumers: `.then`, `.catch`, `.finally`.  
- Promise API (`all`, `allSettled`, `race`, `any`, `resolve`, `reject`).  
- Async/Await syntax for cleaner async code.  
- Using `fetch` for network requests.  
- Axios as an alternative for HTTP requests.  

---

### Lecture 13 — JavaScript Modules (Browser)  
**Why:** Large apps need modular code. Modules promote maintainability, namespacing, and reusability, avoiding the pitfalls of a giant global script.  

**You’ll learn:**  
- What a module is (one file = one module).  
- Benefits of modules: encapsulation, avoiding namespace pollution, reusability.  
- Technical module loading process.  
- Using `<script type="module">` in HTML.  
- Exporting: named vs default exports.  
- Importing: named, renamed, namespace (`*`), default.  
- Combining default + named exports.  
- Aggregating modules.  

---

### Lecture 14 — Backend Overview  
**Why:** Frontend alone is insufficient — backends handle persistence, sessions, authentication, and communication with clients. This lecture frames the backend ecosystem you’ll build.  

**You’ll learn:**  
- Node.js/npm basics.  
- HTTP responses from the server perspective.  
- Web server fundamentals: routing.  
- Express.js and middleware.  
- REST endpoints.  
- Sessions and authentication (Passport).  
- Template engines.  
- WebSockets.  
- MongoDB & data persistence.  
- Deployment and testing.  

---

### Lecture 15 — Node.js Basics  
**Why:** Node.js runs JS outside the browser, enabling server-side applications. It powers scalable, event-driven servers that handle massive concurrency.  

**You’ll learn:**  
- What Node.js is: event-driven, non-blocking I/O model.  
- Command line basics: install, run scripts, arguments.  
- Node REPL console.  
- Console I/O: `console.log`, timing, tracing, input with `readline`.  
- Modules: `require`, `exports`, `module.exports`.  
- Event loop: call stack, queues, timers.  
- EventEmitter API.  
- Async in Node: callbacks, promises, async/await.  
- Streams & buffers.  
- Error handling.  

---

### Lecture 16 — Node.js Core Modules  
**Why:** Node comes with powerful built-in modules that eliminate the need for many external packages. Mastering them makes apps efficient and avoids reinventing the wheel.  

**You’ll learn:**  
- Core modules overview (events, fs, http, path, url, crypto, os, process).  
- Using `require()` to include modules.  
- EventEmitter usage.  
- `fs` for file system operations.  
- `os` for system info.  
- `path` utilities.  
- `url` parsing.  
- `http` module basics.  
- `child_process` spawning.  

---

### Lecture 17 — Node Package Manager (npm)  
**Why:** npm drives the Node.js ecosystem, providing a central registry and tooling to manage project dependencies.  

**You’ll learn:**  
- What npm is and how it works.  
- Installing packages: local vs global.  
- `package.json` structure: metadata, scripts, dependencies.  
- Semantic versioning.  
- Running tasks with `npm run`.  
- Updating/uninstalling packages.  
- `npx` for running executables.  
- Best practices for dependency management.  

---

### Lecture 18 — Express.js  
**Why:** Express is the most widely used Node.js framework. It simplifies building REST APIs and web servers with middleware, routing, and extensibility.  

**You’ll learn:**  
- Express basics and setup.  
- HTTP methods: GET, POST, PUT, DELETE, PATCH.  
- Request & response objects.  
- Parameters: query, body, cookies, headers.  
- Responses: `send`, `json`, `status`, `redirect`.  
- Routing: static, parameterized, regex.  
- Middleware: global, per-route, prebuilt.  
- Static files with `express.static`.  
- Template engines.  
- Sessions.  
- Input validation & sanitization.  
- File handling (uploads).  

---

### Lecture 19 — HTTP Server  
**Why:** Behind frameworks like Express lies the raw HTTP server. Understanding it is crucial to know how requests and responses are processed.  

**You’ll learn:**  
- What an HTTP server is.  
- Responsibilities: listen, respond, manage state, define source of truth.  
- Static vs dynamic servers.  
- Request/response objects.  
- Routes and handlers.  
- Status codes: 200, 301, 403, 404, 500.  
- MIME types.  
- HTTP headers: authentication, caching, cookies, redirects.  
- Sessions and authentication.  
- CORS (Cross-Origin Resource Sharing).  

---

### Lecture 20 — Authentication: Sessions & Tokens  
**Why:** Authentication underpins secure web applications. Because HTTP is stateless, sessions and tokens are used to persist identity across requests.  

**You’ll learn:**  
- Authentication (identity) vs authorization (permissions).  
- Sessions: cookies, session IDs, server-side storage.  
- Cookie attributes & security flags.  
- CSRF attacks and mitigation.  
- Tokens (JWTs): structure, signing, verification.  
- JWT pros/cons vs sessions.  
- SPA/API authentication models.  
- Node modules: `express-session`, `jsonwebtoken`, `passport.js`.  
- Extra measures: 2FA, IP checks, throttling.  

---

## Backend & Fullstack Lectures (21–28)

### Lecture 21–23 — MongoDB Basics  
**Why:** Modern applications require flexible, scalable databases. MongoDB is a leading NoSQL document database that integrates naturally with JavaScript.  

**You’ll learn:**  
- MongoDB fundamentals: collections, documents, NoSQL model.  
- MongoDB Atlas: cloud hosting.  
- Mongo Shell basics.  
- JSON vs BSON formats.  
- CRUD operations.  
- Query operators: comparison, logic, arrays, sub-documents.  
- Indexing and aggregation pipelines.  
- Data modeling principles.  
- Upserts (update or insert).  
- Atlas tools: Data Explorer, Charts, Compass.  

---

### Lecture 24 — REST API & Microservices  
**Why:** REST APIs power communication between clients and servers. Microservices extend this by structuring large systems into smaller, independently deployable services.  

**You’ll learn:**  
- REST constraints and design.  
- REST + HTTP methods and status codes.  
- Issues: misuse of GET, lack of documentation, state.  
- Monolithic vs microservice architectures.  
- Advantages: scalability, fault isolation.  
- Challenges: complexity, testing, deployment.  

---

### Lecture 25 — WebSockets  
**Why:** HTTP is request–response only. For real-time apps (chat, games, notifications), we need two-way communication. WebSockets provide persistent, bidirectional connections.  

**You’ll learn:**  
- HTTP limitations and workarounds.  
- WebSockets basics.  
- Browser API (`WebSocket`, events).  
- Node.js servers with `ws`.  
- Protocol handshake.  
- Socket.io abstraction.  
- Event-driven communication.  
- Real-world demos.  

---

### Lecture 26 — React: JSX, Components & Properties  
**Why:** React introduces a declarative, component-based way of building UIs, replacing manual DOM manipulation with predictable state-driven rendering.  

**You’ll learn:**  
- What React is.  
- Event-driven vs declarative programming.  
- JSX basics.  
- Rendering elements with ReactDOM.  
- Embedding expressions.  
- Components: reusable building blocks.  
- Props: passing data.  
- Return values: JSX outputs.  

---

### Lecture 27 — React: Functional Components & Hooks  
**Why:** Hooks modernize React, allowing state and lifecycle features in functional components without needing classes.  

**You’ll learn:**  
- Hooks overview.  
- `useState`: state in functions.  
- `useEffect`: lifecycle + side effects.  
- Stateful logic sharing.  
- Rules of Hooks.  
- Custom hooks.  
- DRY benefits and readability.  

---

### Lecture 28 — React: Class Components  
**Why:** Class components were the original way to handle state and lifecycle in React. Understanding them is key for working with legacy code.  

**You’ll learn:**  
- Class component syntax.  
- Constructor, `super()`, state, props.  
- `setState` usage.  
- Props as read-only data.  
- Composition patterns.  
- Lifecycle phases: mounting, updating, unmounting.  

---



