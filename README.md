# focusfolio

MV3 extension playground: page reading-time estimator

Side project, maintained when I have time.

## How to use

```bash
# click the toolbar icon to see today's reading time
```

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Features

- Popup shows today's total focus time
- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage
- Manifest V3, service worker based

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT. Do whatever you want.
