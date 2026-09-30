# Anonim — Poster Design

A single-page portfolio website (plain HTML + CSS, no build step, no dependencies).

## Files
- `index.html` — the whole website
- `.nojekyll` — tells GitHub Pages to serve the files as they are
- `README.md` — this guide

## How to publish on GitHub Pages (step by step)

### 1. Create a GitHub account
Go to https://github.com and sign up (skip if you already have one).

### 2. Create a new repository
1. Click the **+** icon (top right) > **New repository**.
2. Repository name: `anonim-portfolio` (or `YOURUSERNAME.github.io` for a shorter address).
3. Set it to **Public**.
4. Click **Create repository**.

### 3. Upload the files
1. On the new repository page, click **uploading an existing file**.
2. Unzip `anonim-portfolio.zip` on your device, then drag `index.html`, `.nojekyll` and `README.md` into the upload box.
   (`.nojekyll` is a hidden file. If you cannot see it, enable "show hidden files" on your device. The site still works without it.)
3. Click **Commit changes**.

### 4. Turn on GitHub Pages
1. Open the repository **Settings** tab.
2. Click **Pages** in the left sidebar.
3. Under **Build and deployment > Source**, choose **Deploy from a branch**.
4. Under **Branch**, choose `main` and folder `/ (root)`, then click **Save**.

### 5. Open your website
Wait 1–2 minutes and refresh the Pages settings. A green box appears with your address:
- `https://YOURUSERNAME.github.io/anonim-portfolio/`
- or `https://YOURUSERNAME.github.io/` if the repository is named `YOURUSERNAME.github.io`.

### Editing later
Open `index.html` in the repository, click the pencil icon, edit, then **Commit changes**. The site updates in about a minute.
