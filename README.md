# Personal Website (MkDocs)


This repository contains my personal academic website built with **MkDocs** and deployed to **GitHub Pages** via **GitHub Actions**.


---


## Quick Start (Windows / PowerShell)


### 1) Go to the repository
```powershell
cd "C..20260219_website\vanthaitran.github.io"
2) Activate virtual environment
.\.venv\Scripts\Activate.ps1
3) Run local preview
mkdocs serve

Open:

http://127.0.0.1:8000/

Stop with Ctrl + C.

Publish Updates

After editing files under docs/:

git add .
git commit -m "Update site content"
git push

The site updates automatically after GitHub Actions finishes.

Project Structure
docs/
  projects/
    <project-name>/
      index.md
      assets/

Link projects from docs/projects.md using:

[View project](<project-name>/)
Notes

Always run mkdocs serve from the repo root

Images must be inside docs/

Filenames must match exactly (case + extension)