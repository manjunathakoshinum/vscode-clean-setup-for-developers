## ⚙️ Backend VSCode Profile

### 🧠 Purpose

The **Backend Profile** is crafted for developers who value **precision, speed, and reliability** in backend development environments.
It’s not a random collection of settings — it’s an *engineered workspace* optimized for **NestJS, TypeScript, Node.js, and DevOps-grade productivity**.

Every line in this config is tuned to make backend engineering **cleaner, faster, and production-ready** — from linting discipline to smooth debugging.

---

### 🚀 Why This Profile Exists

Modern backend systems are complex — they demand a coding environment that can handle:

* Thousands of lines of TypeScript efficiently.
* Continuous linting, formatting, and type analysis without lag.
* Rapid feedback loops when debugging APIs, jobs, and microservices.
* Seamless Git integration for team workflows.

This profile **balances performance with precision** — giving you IDE intelligence without the usual VSCode slowdowns.

---

### 🧩 Key Features

#### 🧱 **TypeScript Engine Optimized**

* `typescript.tsserver.maxTsServerMemory: 8192` → Handles large enterprise codebases smoothly.
* Intelligent **import management** and **auto organization** keep files clean.
* Real-time **inlay hints** for parameter names, variable types, and return types for deeper context.

#### ⚡ **Performance-Driven Editing**

* Smart formatting with **Prettier + ESLint integration** for consistent code quality.

* On-save actions:

  ```json
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "always",
    "source.organizeImports": "always"
  }
  ```

  → Auto-fixes and sorts imports *every time you save* — zero friction.

* High file memory and scrollback capacity (`50000`) for analyzing large logs or service traces.

#### 🧰 **Debugging & DevOps Ready**

* **Auto-attach debugger** to Node processes — great for inspecting live services.
* **Preview mode** debugging for faster iteration cycles.
* Configured for long console histories and breakpoint visibility.

#### 🐙 **Git Power Tools**

* Smart commits, no sync confirmations.
* Auto-fetch and prune branches automatically.
* Clean visual workspace without distractions, with `gitlens` tuned for relevance only.

#### 🔍 **Clean Project Navigation**

* Node modules, dist folders, and logs excluded from search and watchers.
* Reduced noise = faster context switching and mental clarity.

---

### 🧑‍💻 Ideal For

This backend profile is ideal for:

* **Backend Engineers** working with NestJS / Express / Fastify / Node.js.
* **Full-stack Developers** who handle API + DB layers.
* **DevOps & Microservice developers** working across multiple repos.
* **Teams** aiming for uniform code quality and IDE discipline.

---

### 📂 Structure

```
.vscode-profiles/
└── backend/
    ├── settings.json   # Complete configuration for backend projects
    └── README.md       # This file
```
---

#### **Backend (NestJS, PostgreSQL, APIs, Debugging)**

| Purpose                 | Extension                               | ID                          |
| ----------------------- | --------------------------------------- | --------------------------- |
| Framework syntax        | **NestJS Files & Snippets**             | `ashinzekene.nestjs`        |
| Linting                 | **ESLint**                              | `dbaeumer.vscode-eslint`    |
| API testing             | **REST Client**                         | `humao.rest-client`         |
| SQL database management | **SQLTools**                            | `mtxr.sqltools`             |
| PostgreSQL driver       | **SQLTools PostgreSQL/Redshift Driver** | `mtxr.sqltools-driver-pg`   |
| JSON formatting         | **JSON Tools**                          | `eriklynd.json-tools`       |
| Code debugging          | **Debugger for JavaScript**             | `ms-vscode.js-debug`        |
| Git visualization       | **GitLens — Git supercharged**          | `eamodio.gitlens`           |
| File icons              | **Material Icon Theme**                 | `pkief.material-icon-theme` |
| Code consistency        | **Prettier - Code Formatter**           | `esbenp.prettier-vscode`    |

---
---

### 🧠 Pro Tips

* Pair this with your **.editorconfig** and **eslint + prettier configs** for consistency across teammates.
* Use this with a **TypeScript project reference workspace** to maximize intellisense accuracy.
* Combine with a **dedicated Docker profile** if your backend runs in containers.

---

### 🏁 Vision

> “A great backend isn’t just about APIs — it’s about engineering clarity at every layer.”

This VSCode profile is built to let you **focus on system logic, not IDE friction**.
Every keystroke should feel like writing with intention — structured, fast, and reliable.
