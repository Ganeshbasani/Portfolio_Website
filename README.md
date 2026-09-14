# Basani Ganesh — Personal Portfolio

A premium, single-file developer portfolio. No build step, no dependencies — just open `index.html` in a browser or deploy the folder anywhere static (GitHub Pages, Netlify, Vercel, Render).

## Files
| File | Purpose |
|---|---|
| `index.html` | The complete website (HTML + CSS + JS in one file) |
| `og-image.png` | Social share preview image (set an absolute URL in the `og:image` meta tag when deploying) |
| `Basani-Ganesh-Resume.pdf` | One-page resume — wired to every Resume / Download button |

## Customize in 1 minute
Open `index.html` and find the `CONFIG` block at the top of the `<script>` section:

```js
var CONFIG = {
  email: "",          // your email — activates the "Email Me" button
  linkedin: "",       // your LinkedIn URL — activates the LinkedIn button
  github: "https://github.com/Ganeshbasani",
  resumeUrl: ""       // e.g. "resume.pdf" — activates all Resume / Download buttons
};
```

- Buttons for links you haven't set are **hidden automatically** — nothing fake is ever shown.
- Add your `resume.pdf` next to `index.html` and set `resumeUrl: "resume.pdf"`.
- When deploying, replace `og-image.png` in the meta tag with the absolute URL, e.g.
  `https://yourdomain.com/og-image.png`.

## Editing content
All project detail text lives in the `PROJECTS` object in the same script block — edit plain text, no markup needed. Sections are plain HTML with clear comments (`<!-- ============ ABOUT ============ -->`).

## Features
- Dark / light mode (remembers choice, respects system preference)
- Project filtering (Software / AI-ML / Data / Cloud / Web / Other)
- Project detail modals (Esc / backdrop to close, focus management)
- Scroll-reveal animations, magnetic buttons, animated CSS project art
- Fully responsive, keyboard accessible, semantic HTML, SEO meta + JSON-LD
- Zero external requests — works offline, loads instantly
