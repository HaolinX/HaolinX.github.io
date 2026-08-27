# HaolinX.github.io

My personal website — live at **https://haolinx.github.io**

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme, and deployed automatically to GitHub Pages.

## How it deploys

Every push to the `main` branch triggers the **Deploy site** GitHub Action
(`.github/workflows/deploy.yml`), which builds the site and pushes the result to
the `gh-pages` branch. GitHub Pages then serves `gh-pages` at the domain root.

One-time setup (in this repo's **Settings**):
1. **Settings → Actions → General → Workflow permissions** → select **Read and write permissions** → Save.
2. Push the code (the Action runs and creates the `gh-pages` branch).
3. **Settings → Pages → Build and deployment → Source** → **Deploy from a branch** → branch **`gh-pages`**, folder **`/ (root)`** → Save.

After the first successful run the site is live at https://haolinx.github.io.

## Where to edit things

| What | File |
| --- | --- |
| Name, site title, description, keywords, URL | `_config.yml` |
| Homepage bio + intro | `_pages/about.md` |
| Profile photo (replace the placeholder) | `assets/img/prof_pic.png` |
| CV content | `assets/json/resume.json` |
| Downloadable CV PDF | `assets/pdf/cv.pdf` |
| Projects | `_projects/*.md` (+ cover images in `assets/img/`) |
| Publications | `_bibliography/papers.bib` |
| News / updates on the homepage | `_news/*.md` |
| Social links (email, GitHub, LinkedIn, …) | `_data/socials.yml` |
| Featured GitHub repos | `_data/repositories.yml` |

## Running locally (optional)

Requires Ruby + Bundler. From the repo root:

```bash
bundle install
npm install
bundle exec jekyll serve
```

Then open http://localhost:4000.

---

Theme: [al-folio](https://github.com/alshedivat/al-folio) (MIT License). See `LICENSE`.
