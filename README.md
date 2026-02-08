<div align="center">

# HTML Stuffs

**A curated collection of beautiful, functional HTML/CSS/JS components, animations, and mini-projects.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![GitHub Pages](https://img.shields.io/badge/demo-live-blue.svg)](https://vasugupt07676-creator.github.io/html-stuffs/)

[Live Demo](https://vasugupt07676-creator.github.io/html-stuffs/) · [Report Bug](https://github.com/vasugupt07676-creator/html-stuffs/issues) · [Request Feature](https://github.com/vasugupt07676-creator/html-stuffs/issues)

</div>

---

## About

HTML Stuffs is a growing collection of self-contained, zero-dependency web components and animations. Every piece is crafted with intentional aesthetics and is ready to copy into your own projects.

**Philosophy:**
- **Design-First** — Every component has a distinct visual identity
- **Zero Dependencies** — Pure HTML, CSS, and vanilla JavaScript
- **Accessible** — Semantic markup with keyboard & screen reader support
- **Responsive** — Adapts gracefully from mobile to ultrawide

## The Collection

| Component | Description | Tags |
|-----------|-------------|------|
| [**Gradient Generator**](demos/gradient-generator.html) | Interactive mesh gradient builder with real-time preview and CSS export | `CSS` `Interactive` |
| [**Glassmorphism Cards**](demos/glassmorphism.html) | Frosted glass UI with layered blur, floating orbs, and hover effects | `CSS` `HTML` |
| [**CSS Loaders**](demos/css-loaders.html) | 12 beautiful pure CSS loading spinners and animations | `CSS` `Animation` |
| [**Interactive Cards**](demos/interactive-cards.html) | Tilt-responsive 3D cards with parallax depth and spotlight tracking | `JS` `CSS` `3D` |
| [**Morphing Shapes**](demos/morphing-shapes.html) | Organic blob animations with smooth border-radius morphing | `CSS` `Animation` |
| [**Typewriter Effect**](demos/typewriter.html) | Customizable typewriter text with cursor blink, speed control, and loops | `JS` `CSS` |
| [**Starfield Parallax**](demos/starfield.html) | Immersive starfield with mouse-tracking parallax depth layers | `JS` `CSS` `Canvas` |
| [**CSS Tooltips**](demos/tooltips.html) | Zero-JS tooltip system with 4 directions, 6 themes, and bouncy animations | `CSS` `HTML` |

## Quick Start

No build tools, no npm install. Just clone and open:

```bash
git clone https://github.com/vasugupt07676-creator/html-stuffs.git
cd html-stuffs
open index.html
```

Or use any local server:

```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve .
```

## Using a Component

Every component is self-contained in a single HTML file. To use one in your project:

1. **Open the demo** — Browse the collection and find what you need
2. **View the source** — Each demo includes the complete code
3. **Copy what you need** — Take the HTML, CSS, and JS you want
4. **Customize** — Adjust colors, sizes, and animations to fit your design

```html
<!-- Example: Adding a tooltip to any element -->
<button data-tooltip="Hello!" class="tooltip-accent">
  Hover me
</button>
```

## Project Structure

```
html-stuffs/
├── index.html              # Landing page & collection showcase
├── demos/
│   ├── gradient-generator.html
│   ├── glassmorphism.html
│   ├── css-loaders.html
│   ├── interactive-cards.html
│   ├── morphing-shapes.html
│   ├── typewriter.html
│   ├── starfield.html
│   └── tooltips.html
├── README.md
├── CONTRIBUTING.md
├── LICENSE
└── .gitignore
```

## Contributing

Contributions are welcome! Whether it's a new component, bug fix, or design improvement — check out [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details. Use these components freely in personal and commercial projects.
