# Yeast Bioengineering Summer Bootcamp — website

Static site: landing page + top nav (Home, Files, Weblinks, Lectures). No
domain needed — GitHub Pages gives you a free URL like
`https://YOUR-USERNAME.github.io/yeast-bootcamp/`.

## Files in this folder

- `index.html` — landing page (hero image + intro)
- `files.html`, `weblinks.html`, `lectures.html` — the three nav sections
- `styles.css` — shared styling
- `images/`, `files/`, `lectures/` — put your actual photo/materials/slides here

## 1. Add your photo

Save your glowing-flask photo into `images/` and name it exactly
`hero-flask.jpg` (or edit the `src` in `index.html` if you'd rather use a
different filename/format). Until you add it, the page shows a placeholder.

## 2. Create a GitHub account

1. Go to **github.com/join** and sign up (free).
2. Verify your email.

## 3. Create a repository

1. Click the **+** in the top-right corner → **New repository**.
2. Name it something like `yeast-bootcamp`.
3. Set it to **Public** (required for free GitHub Pages).
4. Leave "Add a README" unchecked (we already have one) and click **Create repository**.

## 4. Upload these files (no command line needed)

1. On your new repo's page, click **Add file → Upload files**.
2. Drag in every file and folder from this `yeast-bootcamp-site` folder
   (index.html, files.html, weblinks.html, lectures.html, styles.css,
   images/, files/, lectures/).
3. Scroll down, click **Commit changes**.

## 5. Turn on GitHub Pages

1. In your repo, go to **Settings → Pages** (left sidebar).
2. Under "Build and deployment" → **Source**, choose **Deploy from a branch**.
3. Branch: **main**, Folder: **/ (root)** → **Save**.
4. Wait about a minute, then refresh — GitHub shows your live URL at the top
   of that Pages settings screen:
   `https://YOUR-USERNAME.github.io/yeast-bootcamp/`

## 6. Updating the site later

Any time you want to change content: edit the file locally, then on GitHub
click **Add file → Upload files** again (or edit the file directly in
GitHub's web editor by clicking the pencil icon on the file) and commit —
the live site updates automatically within a minute or two.

## Customizing content

- **Files page**: add real files to `files/`, then replace a `<span class="tag">add file</span>` with a link, e.g. `<a href="files/protocol.pdf">Download</a>`.
- **Weblinks page**: edit the `<div class="card">` blocks — swap URLs/titles for whatever resources you want.
- **Lectures page**: fill in the schedule table and link slide decks from `lectures/`.
