# CoC2 Parser Formatter

This project builds its local CodeMirror browser bundle from npm packages.

## Features

- **Format** — expands and indents bracket structures (`[` and `{`) for readability
- **Compress** — collapses formatted syntax back to a single line
- **Bracket depth highlighting** — 32 colors indicate nesting depth at a glance
- **Find & Replace** — literal search with case, whole-word, and regex options
- **Word / char / bracket counts** — live counts with unbalanced bracket warnings
- **Light & dark theme**
- **Indent style toggle** — spaces, tabs, or none
- **Font size control** — adjustable editor font size

## Build

```sh
npm install
npm run build
```

The build writes `dist/cm6-bundle.js`, which is imported by `CoC2-Parser-Formatter.js`.

Open `index.html` using a web server after building.
