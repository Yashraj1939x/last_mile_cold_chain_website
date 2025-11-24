# Last-Mile Cold Chain System — Static Website

This is a simple static website package for the "Last-Mile Cold Chain System for Vaccines" project.
The project PDF (uploaded by you) is included in `assets/`.

## What is included
- `index.html` — homepage summarizing the project
- `styles.css` — minimal styling
- `assets/Green White Aesthetic Group Project Presentation.pdf` — the original PDF (copied)
- `.gitignore` — useful ignores

## How to publish to GitHub Pages (step-by-step)

### 1) Create a new GitHub repository
1. Go to https://github.com and sign in.
2. Click **New** (top-right) to create a repository.
3. Set repository name (e.g., `cold-chain-project`), description (optional).
4. Choose **Public** (so GitHub Pages will work without authentication).
5. Do **not** initialize with a README if you plan to push an existing repo; either way works.

### 2) Initialize locally and push files (on your computer)
Open a terminal in the folder where you downloaded this website package and run:

```
git init
git add .
git commit -m "Initial commit — project website"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Replace `<your-username>` and `<repo-name>`.

### 3) Enable GitHub Pages
1. On GitHub, open your repository settings.
2. In **Pages** (or "Pages" tab), choose the branch `main` and folder `/ (root)` as the source.
3. Save—GitHub will provide a site URL like `https://<your-username>.github.io/<repo-name>/`.
4. Wait a minute; the site should be live.

### 4) Updating site
- Make edits locally, `git add`, `git commit -m "..."`, and `git push`.
- GitHub Pages will automatically redeploy the site.

## Local testing
Open `index.html` in a browser locally to preview.

## Notes
- If you want to use a custom domain or advanced Jekyll features, GitHub Pages settings can be configured accordingly.
- To keep the PDF private, don't use a public repo — instead use a private repo (but public GitHub Pages won't host from private repos without special setup).

