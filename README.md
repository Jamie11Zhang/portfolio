# Personal Portfolio

A clean, single-page portfolio for graduate applications in Design Ops, Research Ops, Product Ops, and AI-enabled product innovation.

Built with plain HTML, CSS, and a small amount of vanilla JavaScript — no build step, no dependencies.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Page structure and content (Hero, About, FMOP case study, Experience, Contact). |
| `styles.css` | All styling: design tokens, layout, responsive rules, the CSS workflow diagram. |
| `script.js` | Mobile nav toggle, active-section highlighting, footer year. |
| `README.md` | This file. |

## Run it locally

It's a static site, so you can just open `index.html` in a browser.

For nav/scroll behaviour to work exactly like production, serve it over a local server:

```bash
# Option A — Python (usually preinstalled)
python3 -m http.server 8000

# Option B — Node
npx serve .
```

Then visit <http://localhost:8000>.

## Deploy later

Any static host works — GitHub Pages, Netlify, Vercel, or Cloudflare Pages. Just upload these files (no build command needed).

## Placeholders to customise

Search for text in square brackets `[ ]` — those are meant to be edited:

- `[Your Name]` — brand/logo in the header, footer, and page title.
- Hero headline and intro — tune the wording to your voice.
- **FMOP case study** — the `[Editable: ...]` notes in Context, Challenge, Approach, Solution, Impact (metrics), and Reflection.
- Experience cards — the `[Editable: ...]` lines for TikTok and UCL.
- Contact — `[your-email@example.com]` (in the `mailto:` link and visible text) and `[your-linkedin-url]` / `[linkedin.com/in/your-handle]`.

## Notes

- Responsive from mobile to desktop.
- Respects `prefers-reduced-motion`.
- Accessible: semantic landmarks, skip link, visible focus states, keyboard-friendly nav.
- Fonts (Fraunces + Inter) load from Google Fonts; swap or self-host anytime.
