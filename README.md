# Deus Proxima Wiki

This repository contains the **Deus Proxima** worldbuilding wiki and its MkDocs-based publishing setup.

## Local preview

### Windows

Run:

```bat
start-wiki-windows.bat
```

### macOS / Linux

Run:

```bash
./start-wiki-macos-linux.sh
```

## Build

Install dependencies:

```bash
pip install -r requirements.txt
```

Build the site:

```bash
mkdocs build
```

The generated site is written to the `site/` directory.

## GitHub Pages

The repository includes a GitHub Actions workflow at:

```text
.github/workflows/deploy-pages.yml
```

It builds and deploys the MkDocs site to GitHub Pages whenever changes are pushed to `main`.

## Content structure

- `docs/setting/` — setting foundations and core concepts
- `docs/history/` — chronology and major historical events
- `docs/factions/` — political powers, organisations, and adversaries
- `docs/technology/` — travel, vessels, and strategic technologies
- `docs/places/` — locations and worlds
- `docs/meta/` — canon tracking, open questions, assets, and change history
- `source/` — source material and generated concept images
