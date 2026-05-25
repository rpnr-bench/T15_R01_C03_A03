# Product Documentation Portal

A Docusaurus documentation portal for product setup guides, installation notes, and maintenance documentation.

## Project layout

- `docs/` — Documentation pages rendered by Docusaurus.
- `docusaurus.config.js` — Site configuration.
- `sidebars.js` — Sidebar navigation.
- `package.json` — Node scripts and dependencies.

## Quick start

```bash
make validate
```
```bash
npm install
```
```bash
npm run build
```

## Documentation workflow

1. Add or update Markdown pages under `docs/`.
2. Keep `sidebars.js` synchronized with new pages.
3. Validate JavaScript config before opening a PR.
4. Run a full Docusaurus build before release.

## Maintenance notes

Use the sidebar configuration when adding or moving documentation pages.

## Contributing

Keep changes focused, update documentation when behavior changes, and run the validation commands before submitting a pull request.
