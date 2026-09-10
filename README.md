# use-fluent

Small typed hooks: debounce, localStorage, media query, toggle

## Getting started

```bash
npm install
npm test
```

## What it does

- useDebounce with leading/trailing options
- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization
- Tiny: no dependencies besides React

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## License

MIT - see [LICENSE](LICENSE).
