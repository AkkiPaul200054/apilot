# apilot

Learning project: clean Express API structure

Started as a weekend hack, grew on me.

## Getting started

```bash
npm install
npm run dev
```

## Features

- Request validation helpers, no framework magic
- In-memory store with optional JSON persistence
- Morgan logging and centralized error handler
- env-driven port, runs anywhere Node does
- REST endpoints: list / create / delete / search

## How to use

```bash
curl -X POST localhost:3000/api/bookmarks \
  -H 'content-type: application/json' \
  -d '{"url": "https://example.com", "tags": ["reading"]}'
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── src/
│   ├── config.js
│   ├── index.js
│   └── store.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```

## License

MIT - see [LICENSE](LICENSE).
