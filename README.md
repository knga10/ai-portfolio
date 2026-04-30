# AI Projects Portfolio

Personal portfolio site showcasing AI projects — built with HTML/CSS, no dependencies.

**Live site:** https://[your-username].github.io/[repo-name]

## Structure

```
├── index.html          # Main page
├── style.css           # All styles (rust/beige/sage palette)
├── .github/
│   └── workflows/
│       └── deploy.yml  # Auto-deploys on push to main
└── README.md
└── casestudy/
    ├── case-study.css
    ├── recycling-finder.html
    ├── khmer-flashcard.html
    ├── entertainment-engine.html
    └── hotel-tracker.html
```

## Customising

1. **Projects** — edit the `<article class="project-card">` blocks in `index.html`
2. **About** — update the `.about` section with your details
3. **Links** — replace `href="#"` with real URLs to your projects or GitHub repos
4. **Name/contact** — update the nav, footer, and about section

## Deployment

This repo deploys automatically via GitHub Actions on every push to `main`.
