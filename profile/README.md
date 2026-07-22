<div align="center">

<img src="./banner.svg" alt="Create Vlang App" width="100%" />

# Create Vlang App

**One command. Any V stack.**

> The scaffolding toolkit for the [V programming language](https://vlang.io) — by a V core team member, built alongside [Create Node App](https://github.com/Create-Node-App).

</div>

---

## What is this?

`Create Vlang App` brings the composition-first scaffolding philosophy of [create-awesome-node-app](https://github.com/Create-Node-App/create-node-app) to the V language ecosystem.

Pick a template. Layer extensions. Bootstrap production-ready V projects without the usual setup overhead.

```bash
# coming soon
v install create-vlang-app
create-vlang-app my-project
```

---

## About the author

This project is maintained by [Ulises Jeremias](https://github.com/ulises-jeremias), a **V language core team member** and author of several foundational libraries in the V ecosystem:

| Project | Description |
|---------|-------------|
| [vlang/vsl](https://github.com/vlang/vsl) | V Scientific Library — linear algebra, stats, optimization |
| [vlang/vtl](https://github.com/vlang/vtl) | V Tensor Library — n-dimensional tensors for V |
| [ulises-jeremias/rxv](https://github.com/ulises-jeremias/rxv) | Reactive Extensions for V |
| [vlang/setup-v](https://github.com/vlang/setup-v) | GitHub Action to set up V in CI workflows |

---

## Available Templates

| Template | Stack | Status |
|----------|-------|--------|
| Web Server | vweb / vibe | Available |
| CLI App | os + flag modules | Available |
| Library Starter | modules, docs, tests | Available |
| Systems App | low-level, no GC | Available |

---

## Available Extensions

- **Testing** — built-in `v test`, coverage
- **Tooling** — `v fmt`, `v vet`, GitHub Actions with [setup-v](https://github.com/vlang/setup-v)
- **Database** — ORM, SQLite, PostgreSQL
- **Deployment** — Docker, static binaries, cross-compilation targets

---

## Status

This project is in actively developed. V's tooling ecosystem is young — this aims to be the standard scaffolding layer for it.

If you're a V developer and want to contribute, open an issue or watch this org.

The Node.js counterpart is production-ready today:

→ **[create-awesome-node-app.vercel.app](https://create-awesome-node-app.vercel.app)**

---

## Part of the Create Awesome App ecosystem

| Org | Stack | Status |
|-----|-------|--------|
| [Create-Node-App](https://github.com/Create-Node-App) | Node.js, TypeScript | ✅ Production |
| [Create-Python-App](https://github.com/Create-Python-App) | Python | 🧪 Beta |
| [Create-Vlang-App](https://github.com/Create-Vlang-App) | V language | ✅ Available |


## Status

CLI and cva-templates are on GitHub; first VPM/release track is Wave 2 (`create-vlang-app@0.1.0`).
