# Rahul Sharma — academic homepage

Jekyll site for GitHub Pages (based on the Minimal Light theme; see LICENSE).

## Publish
1. Create a public GitHub repo named **rsharma459.github.io**.
2. Upload everything in this folder (keep the folder structure) to the repo root.
3. Repo → Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Site appears at https://rsharma459.github.io within a few minutes.

## Edit
Search the repo for `TODO` — every placeholder is marked.

| What | File |
|---|---|
| Name, email, links (Scholar, LinkedIn, CV) | `_config.yml` |
| Bio paragraph | `index.md` |
| News / Publications / Awards / Talks / Teaching / Service | `_data/*.yml` |
| Profile photo | replace `assets/img/avatar.png` (square image, same name) |
| CV and PDFs | put in `assets/files/` |
| Remove a section | delete its `{% include ... %}` line and nav `<li>` in `_layouts/homepage.html` |
