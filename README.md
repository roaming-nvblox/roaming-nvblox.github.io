# ROAMing project page

Static project page in the style of weave-rl.github.io (Academic Project Page Template, Bulma via CDN).

## Deploy on GitHub Pages
1. Create a repository named `<org-or-user>.github.io` (e.g. `roaming-mapping.github.io`), or any repo with Pages enabled on the `main` branch root.
2. Copy `index.html`, `static/` into the repo root and push.
3. In the repo settings, Pages -> Source: "Deploy from a branch", branch `main`, folder `/ (root)`.

## Things to fill in
- `index.html`: replace `href="#"` on the arXiv button with the arXiv URL once available; point the Code and Dataset buttons at the repos and remove the `is-soon` class.
- `static/roaming_corl2026.pdf`: the camera-ready PDF (currently the submission version).
- Optional: add a video/GIF of the mapper running (the WeaveRL page uses GIFs in the method section) under `static/images/` and a `<video>`/`<img>` block in the Method section.
