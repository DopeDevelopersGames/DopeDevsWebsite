# DopeDevsWebsite

Static site for **Dope Developers**, rebuilt from the original Framer site as plain HTML/CSS for GitHub Pages. No build step and no dependencies.

## Structure

```
index.html       Home / hero
about.html       Team cards
projects.html    Game list with Play links
404.html         Not-found page (GitHub Pages serves it automatically)
styles.css       All styling (colours and fonts are CSS variables at the top)
assets/          Logo, favicon, team portraits, project covers
.nojekyll        Tells Pages to serve files as-is
```

Fonts: Jersey 25 (headings/UI) and Google Sans (project body text), both loaded from Google Fonts.

## Deploy on GitHub Pages

1. Repo → **Settings → Pages**
2. Source: **Deploy from a branch** → Branch: `main`, folder: `/ (root)` → Save
3. The site goes live at `https://dopedevelopersgames.github.io/DopeDevsWebsite/` within a minute or two

To use your own domain (e.g. `dopedevelopers.com`), add it under **Settings → Pages → Custom domain** and point the domain's DNS at GitHub Pages.

## Editing

- **Add a team member:** copy one `<li class="member">…</li>` block in `about.html` and drop a 64×64 PNG in `assets/team/`.
- **Add a project:** copy one `<article class="project">…</article>` block in `projects.html` and put its cover in `assets/projects/`.
