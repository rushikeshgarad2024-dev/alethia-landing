<div align="center">
  <a href="https://rushikeshgarad2024-dev.github.io/alethia-landing/">
    <img src="assets/preview.jpg" alt="Alethia — ocean conservation intelligence" width="100%" />
  </a>
</div>

<div align="center">

# Alethia — Ocean Intelligence

**A cinematic climate-tech experience, re-themed for ocean conservation.**

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-Open_site-06070a?style=for-the-badge&logo=googlechrome&logoColor=8be9ff)](https://rushikeshgarad2024-dev.github.io/alethia-landing/)
[![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)

</div>

---

## The idea

Alethia turns ecosystem science into enterprise strategy. This version re-themes the original environmental-intelligence hero for **ocean conservation** — deep navy, electric blue, wave gradients, and marine data storytelling.

The experience is built around a scroll-scrubbed film: native scroll sets a target, a `requestAnimationFrame` loop eases the playhead, and fixed overlays reveal the headline, evidence HUD, and narrative sections in sequence.

## Highlights

- **Scroll-scrubbed video** — the background plate advances with scroll position, not autoplay.
- **Cinematic HUD** — impact markers, evidence labels, crosshairs, and technical annotations layered over the film.
- **Three narrative scenes** — hero, vision, and ecosystem-level accounting.
- **Ocean re-theme** — custom blue palette, wave gradients, and marine-conservation copy.
- **Self-contained assets** — local fonts and hero plate, so the page no longer depends on missing remote files.
- **Responsive flow mode** — fixed overlays become readable scroll sections on tablet and mobile.

## Tech

| Layer | Choice |
| :--- | :--- |
| Markup | Semantic HTML5 |
| Styling | Modern CSS, custom properties, fluid type |
| Motion | Vanilla JS, scroll-scrubbed video, rAF easing |
| Type | Local Alethia Mono / Inter variable fonts |
| Build | None |

## Run locally

```bash
# from the project root
python -m http.server 8000
```

Then open <http://localhost:8000>. A local server is recommended so the video and font assets load correctly.

## Structure

```text
.
├── index.html          # page, styles, scroll engine inline
└── assets/
    ├── alethia-mark.woff2
    ├── alethia-mono.woff2
    ├── hero-plate.webp
    ├── inter-full.woff2
    ├── inter-variable.woff2
    ├── mono-full.woff2
    └── preview.jpg
```

## Credits

Ocean re-theme and build by **[Rushikesh Garad](https://github.com/rushikeshgarad2024-dev)**.
Original Alethia concept and design by **[MahumSamar](https://github.com/MahumSamar/alethia-landing)** — adapted here as a portfolio piece.
