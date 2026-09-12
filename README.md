# react-utility-hooks

A handful of React hooks I keep copy-pasting between projects

Built for my own use; public in case it helps someone.

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Getting started

```bash
npm install
npm test
```

## Features

- useDebounce with leading/trailing options
- useLocalStorage with JSON serialization
- useMediaQuery SSR-safe
- Tiny: no dependencies besides React

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
└── package.json
```
