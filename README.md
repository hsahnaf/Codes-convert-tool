# Codes Convert Tool

A production-grade web application for converting between code, formats, encodings, colors, and more. Built with **React + Vite + TypeScript**. Responsive, accessible, and packed with features.

## Features

- **Multi-format conversion:** JSON/XML/YAML/CSV, Markdown/HTML/JSX, Color, Units, and more.
- **Encoders/decoders:** Base64, URLs, HTML entities, Hex, Binary, ASCII, JWT decoder.
- **Utilities:** Hashing, AES demo, text case, Unix timestamp/date, code beautify/minify.
- **Modern UI:** Sidebar tools, keyboard shortcuts, dark/light theme, search/filter, Prism.js syntax highlighting.
- **Actions:** Convert, Validate, Clear, Copy, Download – with toast notifications.
- **Robust engineering:** TypeScript, tests, error handling, ESLint + Prettier.
- **CI/CD:** GitHub Actions for test & deploy.

## Getting Started

### Prerequisites

- Node.js >= 18, npm >= 9

### Install

```bash
git clone https://github.com/your-username/codes-convert-tool.git
cd codes-convert-tool
npm install
```

### Development

```bash
npm run dev
```

App will run at `http://localhost:5173`.

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Test

```bash
npm test
```

## Deployment

This app is automatically deployed to GitHub Pages via GitHub Actions on every push to `main`. To deploy manually:

```bash
npm run deploy
```

## Security Note

**AES encryption/decryption is provided for demonstration only and is NOT secure for production or sensitive data. Use audited, server-side libraries for real cryptography!**

## License

This project is licensed under the MIT License.

---

## Tools & Sample Inputs

| Tool | Example Input |
|---|---|
| **JSON ↔ XML ↔ YAML ↔ CSV** | `{ "foo": 1, "bar": [2, 3] }` |
| **Base64** | `hello world` |
| **URL Encode/Decode** | `foo=bar&baz=qux` |
| **Hex/Bin/ASCII/Dec** | `48656c6c6f` |
| **Markdown/HTML/JSX** | `# Hello <b>world</b>` |
| **HTML Entities** | `5 < 10 & 10 > 5` |
| **JWT Decoder** | `eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.ey...` |
| **Hash** | `password123` |
| **AES Demo** | Plaintext + password |
| **Color** | `#FF8800` or `rgb(255,136,0)` |
| **Units** | `16px` or `1rem` |
| **Unix Timestamp** | `1694851200` |
| **Text Case** | `hello_world_example` |
| **CSS/SCSS** | `.foo { color: red; }` |
| **JS/HTML/CSS Beautify/Minify** | Minified or formatted code |

---

## Folder Structure

```
codes-convert-tool/
├── src/
│   ├── components/
│   │   ├── tools/
│   │   ├── layout/
│   │   ├── ui/
│   ├── lib/
│   ├── hooks/
│   ├── App.tsx
│   └── main.tsx
├── public/
├── tests/
├── .github/
│   └── workflows/
│       └── ci.yml
├── package.json
├── tsconfig.json
├── vite.config.ts
├── tailwind.config.js
├── postcss.config.js
├── .eslintrc.cjs
├── .prettierrc
├── LICENSE
└── README.md
```

---