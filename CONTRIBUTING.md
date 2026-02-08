# Contributing to HTML Stuffs

Thanks for your interest in contributing! Here's how to get started.

## Adding a New Component

1. **Fork & clone** the repository
2. **Create** a new HTML file in the `demos/` directory
3. **Follow the conventions** below
4. **Open a PR** with a description and screenshot

## Conventions

Every component should be:

- **Self-contained** — A single HTML file with inline CSS and JS (no external dependencies)
- **Beautiful** — Intentional design choices, not just functional
- **Responsive** — Works on mobile, tablet, and desktop
- **Accessible** — Uses semantic HTML elements and supports keyboard navigation
- **Documented** — Includes a clear title, description, and usage examples within the demo

### File Template

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Component Name — HTML Stuffs</title>
  <!-- Google Fonts: Instrument Serif + DM Sans -->
  <style>
    /* Use the shared design tokens */
    :root {
      --bg: #0a0a0b;
      --surface: #141416;
      --border: #2a2a30;
      --text: #f0ede8;
      --muted: #8a8690;
      --accent: #e8ff59;
    }
    /* Your styles here */
  </style>
</head>
<body>
  <a href="../index.html" class="back">← Back to Collection</a>
  <!-- Your component here -->
</body>
</html>
```

### Design Tokens

Please use the existing design tokens for consistency:

| Token | Value | Usage |
|-------|-------|-------|
| `--bg` | `#0a0a0b` | Page background |
| `--surface` | `#141416` | Card backgrounds |
| `--border` | `#2a2a30` | Borders |
| `--text` | `#f0ede8` | Primary text |
| `--muted` | `#8a8690` | Secondary text |
| `--accent` | `#e8ff59` | Accent / highlight |

### Fonts

- **Instrument Serif** — Headings and display text
- **DM Sans** — Body text
- **JetBrains Mono** — Code snippets

## Reporting Bugs

Open an [issue](https://github.com/vasugupt07676-creator/html-stuffs/issues) with:

1. Which component is affected
2. What browser and device you're using
3. A screenshot or recording if possible
4. Steps to reproduce the issue

## Questions?

Feel free to open a discussion or issue. We're happy to help!
