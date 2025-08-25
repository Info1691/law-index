# law-index

Public, read-only artifact store for legal texts.

- `catalogs/ingest-catalog.json` – list of available items (title, urls, types)
- `texts/…` – cleaned TXT for search/citation
- `page-maps/…` – JSON per-PDF (PDF p. → book p., bbox for highlights, etc.)

Artifacts are pushed here by:
- `lex-ingest-local` (private) – from your local PDFs/TXTs
- `lex-ci-harvest` (public) – from approved public sources

This repo uses GitHub Pages to serve files.
