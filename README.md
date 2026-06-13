# NoctuaDB Studio

A desktop database client focused on simplicity.

![License](https://img.shields.io/github/license/iuribrito/noctuadb-studio)
![Release](https://img.shields.io/github/v/release/iuribrito/noctuadb-studio)
![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20macOS%20%7C%20Windows-blue)

---

## Supported Databases

| Database | Features |
|---|---|
| **MySQL / MariaDB** | Query editor, table browser, schema editor, triggers, procedures, functions, admin panel, ER diagram, import/export, dump/restore |
| **PostgreSQL** | Query editor, table browser, schema editor, ER diagram, import/export |
| **SQLite** | Query editor, table browser, schema editor (supported ALTER subset), import/export |
| **MongoDB** | Document browser, aggregation pipeline editor, index management, schema inference |
| **Redis** | Key browser (all types), CLI REPL, TTL management, database selector |

---

## Features

- **Multi-connection** — manage multiple connections simultaneously, each with its own color and tab set
- **Query editor** — CodeMirror 6 with syntax highlighting, schema-aware autocomplete, and SQL formatter
- **Table browser** — virtual scroll, inline editing, visual filter builder, server-side pagination, column manager
- **Schema administration** — visual table editor, trigger/routine modals, structure viewer, ER diagram
- **Query history** — last 500 queries with search, per-connection
- **SSH tunnel** — password or key-based auth for all database types
- **SSL/TLS** — skip-verify, require, verify-ca, verify-full modes
- **Import / Export** — CSV and JSON import with column mapping; streaming export (O(1) memory)
- **Dump / Restore** — SQL dump with table selection and SQL restore with execution log
- **Schema diff** — side-by-side comparison between two databases
- **Charts** — bar, line, and pie charts from query results
- **Command palette** — Ctrl+P quick-jump to any table or collection
- **Snippets** — categorized SQL snippet library
- **Dark and light themes** — Catppuccin Mocha / Latte

---

## Installation

Download the latest release for your platform from the [Releases](https://github.com/iuribrito/noctuadb-studio/releases) page.

### Linux

```bash
chmod +x noctuadb-studio
./noctuadb-studio
```

> **Requirement:** `webkit2gtk` must be installed.
>
> Debian / Ubuntu:
> ```bash
> sudo apt install libwebkit2gtk-4.1-0
> ```
> Arch:
> ```bash
> sudo pacman -S webkit2gtk-4.1
> ```

### macOS

Open the `.dmg`, drag **NoctuaDB Studio** to Applications, then open it. If macOS blocks the app on first launch, go to **System Settings → Privacy & Security** and click **Open Anyway**.

### Windows

Run the `.exe` installer and follow the setup wizard.

---

## License

[MIT](LICENSE)
