  ---

  # NoctuaDB Studio

  A desktop database client focused on simplicity.
  Built with [Wails](https://wails.io/) (Go + Svelte 5).

  ![NoctuaDB Studio](https://raw.githubusercontent.com/iuribrito/noctuadb-studio/appicon.png)

  ## Features

  - **Multi-connection** — manage multiple database connections simultaneously, each with its own color and isolated session
  - **Query editor** — CodeMirror 6 with MySQL syntax highlighting, schema-aware autocomplete, and SQL formatter
  - **Table browser** — paginated table view with inline editing, visual filter builder, and virtual scrolling
  - **SSH tunnel** — connect to databases behind SSH bastions using key or password authentication
  - **Schema explorer** — view and edit tables, indexes, triggers, foreign keys, views, and stored procedures/functions
  - **Admin panel** — server status, process list, user management, and variables viewer
  - **Query history** — searchable log of all executed queries with duration and row count
  - **Import** — CSV and JSON import with column mapping
  - **Export** — CSV and JSON export with streaming for large datasets

  ## Download

  Go to the [Releases](../../releases) page and download the file for your platform:

  | Platform | File |
  |---|---|
  | Linux x86_64 | `NoctuaDB-Studio-<version>-linux-x86_64.AppImage` |
  | macOS Apple Silicon (M1/M2/M3) | `NoctuaDB-Studio-<version>-macos-arm64.dmg` |
  | Windows x86_64 (installer) | `NoctuaDB-Studio-<version>-windows-x86_64-installer.exe` |
  | Windows x86_64 (portable) | `NoctuaDB-Studio-<version>-windows-x86_64.exe` |

  ### Linux

  Requires `libwebkit2gtk-4.1` installed on the system:

  ```bash
  # Ubuntu / Debian
  sudo apt install libwebkit2gtk-4.1-0

  # Fedora
  sudo dnf install webkit2gtk4.1

  # Arch Linux
  sudo pacman -S webkit2gtk-4.1

  After downloading, make the AppImage executable and run it:

  chmod +x NoctuaDB-Studio-*.AppImage
  ./NoctuaDB-Studio-*.AppImage

  macOS

  Open the .dmg, drag the app to Applications, and run it.
  On first launch macOS may block the app — go to System Settings → Privacy & Security and click Open Anyway.

  Windows

  Run the installer (recommended) or the portable .exe directly.

  Supported Databases

  ┌─────────────────┬──────────────┐
  │    Database     │    Status    │
  ├─────────────────┼──────────────┤
  │ MySQL / MariaDB │ ✅ Supported │
  ├─────────────────┼──────────────┤
  │ PostgreSQL      │ 🚧 Planned   │
  ├─────────────────┼──────────────┤
  │ SQLite          │ 🚧 Planned   │
  ├─────────────────┼──────────────┤
  │ MongoDB         │ 🚧 Planned   │
  ├─────────────────┼──────────────┤
  │ Redis           │ 🚧 Planned   │
  └─────────────────┴──────────────┘

  License

  MIT

  ---
