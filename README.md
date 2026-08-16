# Harshita Lila — Academic Website

Personal academic homepage for **Harshita Lila**, Ph.D. student in Computer Science at the
University of Utah (Kahlert School of Computing).

Built with static HTML/CSS — no build step. Hosted on GitHub Pages at
https://harshitaleela.github.io/

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure

- `index.html` — single-page site: hero, research interests, research experience,
  research directions, publications/outputs, research journey, projects, experience,
  education, skills, awards, leadership, about, contact
- `assets/style.css` — design system (Inter / JetBrains Mono, Utah-inspired accent)
- `assets/Harshita-Lila-CV.pdf` — downloadable CV (mirror of resume PDF)

## Updating

- Content lives inline in `index.html` sections; add new publications under
  "Publications & Research Outputs" and new projects under "Selected Projects".
- Replace `assets/Harshita-Lila-CV.pdf` to update the CV.
- Deploy: `git add -A && git commit -m "..." && git push` (GitHub Actions workflow in
  `.github/workflows/pages.yml` rebuilds the site).
