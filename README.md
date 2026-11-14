# Personal Website

My personal academic website, built from the [Sciencefolio](https://github.com/tuannguyen8390/sciencefolio) template: plain HTML, no build step, nothing to install. It is deployed to **GitHub Pages** via **GitHub Actions** on every push to `main`.

Live at https://vanthaitran.github.io/


## Preview locally

Double-click `index.html` to open it in a browser. Refresh after editing.


## Publish updates (Command Prompt)

```bat
cd "C:\Users\vanth\OneDrive - Nanyang Technological University\01personal information\20260219_website\vanthaitran.github.io"
git status
git add .
git commit -m "Update site content"
git push
```

The website updates automatically a minute or two after GitHub Actions finishes.


## Where things live

| To change | Edit |
| --- | --- |
| Name, one-line statement, profile links, research interests, selected publications, contact | `index.html` |
| Bio and education | `about.html` |
| Research focus and projects | `research.html` |
| Publication list | `work.html` (the page is labelled "Publications") |
| ZnO photodetector project page | `projects/zno-uv-photodetector/index.html` |
| Accent color, heading weights | `css/tokens.css` |
| Type pack (grotesk or serif) | `js/theme.js` |

- The nav bar and footer are repeated on every page; change them everywhere at once.
- To add a publication, copy an `<article class="entry">` block in `work.html`. Its `data-type` must be `journal`, `conference`, `thesis` or `patent` so the filter buttons work.
- To add a project, copy a `<article class="chapter">` block in `research.html`. For a detail page, copy the `projects/zno-uv-photodetector/` folder.
- Images go in `images/` or the project's `assets/` folder. Filenames must match exactly (case + extension).
- `AGENTS.md` holds the template's design rules, for AI assistants and humans.
