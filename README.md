# 🧅 JSON Peeler

A zero-install, browser-only tool for developers to read messy JSON.

**Live:** https://sushantdhumal.github.io/json-peeler/

## Features
- **Peel** – unwraps stringified (and multiply-stringified) JSON, including nested stringified values, and pretty-prints it with folding and search (⌘F).
- **Compare** – paste JSON A and JSON B to see every difference, highlighted line by line and listed by JSONPath (Different / Only in A / Only in B). Key order is ignored; types are compared strictly (`20` ≠ `"20"`).
- Wrap long lines, collapse/expand all, copy or download the output or a diff report.

## Privacy
Everything runs locally in your browser. The JSON you paste is never sent anywhere.

## Development
It's a single `index.html` file. Edit it, commit and push to `main`; GitHub Pages redeploys automatically.

Built by Sushant Dhumal. Feedback and suggestions are welcome via Issues.
