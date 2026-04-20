# Instruqt Platform Tour

A self-guided, lead-gen-focused landing page for the Instruqt platform tour. Single-file HTML — no build step, no framework, no dependencies.

**Live preview:** https://tyler793.github.io/instruqt-platform-tour/

## What's inside

- `index.html` — the entire landing page. Styles and markup in one file for maximum portability.
- `.github/workflows/deploy.yml` — GitHub Actions workflow that publishes `index.html` to GitHub Pages on every push to `main`.

## Brand notes

The page is built around Instruqt's visual system and voice:

- **Palette:** deep plum (`#1A0B36`), coral (`#FF4F5E`), and sunflower (`#FFD84C`) accents on warm off-white paper sections.
- **Voice:** conversational, educational, technical. Leans on Instruqt's own phrases — "your tech deserves to shine," "learn by doing," "hands-on product experiences."
- **Product vocabulary:** Tracks, Challenges, Sandboxes, embed/kiosk mode.

## Messaging pillars

The page is structured around the three core Instruqt pillars:

1. Drive more qualified leads through hands-on product experiences.
2. Get to value and close deals faster with higher-quality demos and POCs.
3. Improve retention with real-world, scalable experiences.

## Lead gen without a form

Every CTA on the page routes to the tour itself or to a use-case page — never to a form. The final CTA block calls this out explicitly so visitors feel in control.

## Local preview

```bash
# Any static server works. Python 3:
python3 -m http.server 8080
# or
npx serve .
```

Then open `http://localhost:8080`.

## Deploying to GitHub Pages

The included workflow auto-deploys on every push to `main`. Make sure **Settings → Pages** has **Source** set to **GitHub Actions**.

## License

MIT — see `LICENSE`.
