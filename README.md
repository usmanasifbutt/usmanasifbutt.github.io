# usmanasifbutt.github.io

Source for my personal portfolio site, live at **[usmanasifbutt.github.io](https://usmanasifbutt.github.io/)**.

## What it is

A single-page portfolio that introduces who I am, my experience, tech stack, projects and how to get in touch. It's the link I share in my GitHub profile, LinkedIn and résumé.

## Why this repo

GitHub Pages serves a repository named `<username>.github.io` at the root of `https://<username>.github.io/`, so this repo gives the site a short, clean URL. My GitHub profile README lives separately in [usmanasifbutt/usmanasifbutt](https://github.com/usmanasifbutt/usmanasifbutt).

## How it's built and deployed

- Plain static HTML/CSS — no framework or build step.
- `.nojekyll` tells GitHub Pages to serve the files as-is instead of running Jekyll.
- Every push to `main` is deployed automatically by GitHub Pages.

```
index.html            # the whole site
assets/profile.jpeg   # profile photo
.nojekyll             # skip Jekyll processing
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.
