# Gilberto Miranda — Portfolio Site

Professional portfolio site for job search and freelance opportunities.
Built with Jekyll and the Minimal Mistakes theme, deployed automatically via GitHub Pages.

## Live URL

`https://beto-agent.github.io/portfolio/`

## File Structure

```
.
├── _config.yml            # Site config (theme, nav, social links)
├── _data/navigation.yml   # Navigation entries
├── _posts/                # Blog posts (project notes)
├── .github/workflows/     # Jekyll build & deploy workflow
├── assets/css/style.scss  # Theme style overrides
├── index.md               # Home
├── about.md               # About
├── projects.md            # Projects
├── resume.md              # Resume
├── blog.md                # Blog index
├── data/profile.json      # Structured profile data
└── README.md              # This file
```

## How to Update Content

Content lives in Markdown files (`index.md`, `about.md`, `projects.md`, `resume.md`) with Jekyll front matter. Pushing to `main` rebuilds and deploys the site automatically via `.github/workflows/jekyll.yml`.

- **Structured data:** edit `data/profile.json` (contact, experience, skills).
- **Styles:** edit `assets/css/style.scss` (theme overrides).

## TODO

| Item | Status |
|------|--------|
| PDF resume link | ❌ Needed — upload PDF and update link |
| 5th project | ❌ Open — candidate: job-search automation flow (in progress) |
| Recent certifications | ❌ Optional — AI cert (AI-901 study plan offered, not started) |
| GitHub username/URL | ✅ Done (`https://github.com/beto-agent`) |
| Professional email | ✅ Done (`gmiranda.tito.pr@gmail.com`) |
| LinkedIn URL | ✅ Done (`linkedin.com/in/gmd-tito`) |
| Phone number | ✅ Omitido por decisión del dueño — no publicar teléfono |

## License

Content: © 2026 Gilberto Miranda. All rights reserved.
