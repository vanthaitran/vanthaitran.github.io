# Personal Website (MkDocs)


This repository contains my personal academic website built with **MkDocs** and deployed to **GitHub Pages** via **GitHub Actions**.


---


## Quick Start (Windows – Command Prompt)


### 1) Go to the repository
```bat
cd "C:\Users\vanth\OneDrive - Nanyang Technological University\01personal information\20260219_website\vanthaitran.github.io"
2) Activate virtual environment
.\.venv\Scripts\activate.bat

You should see the prompt change (e.g. (.venv)).

3) Run local preview
mkdocs serve

Open in browser:

http://127.0.0.1:8000/

Stop with:

Ctrl + C
Publish Updates

After editing files under docs\:

git status
git add .
git commit -m "Update site content"
git push

The website updates automatically after GitHub Actions finishes.

Project Structure
docs\
  projects\
    <project-name>\
      index.md
      assets\

Link projects from docs\projects.md using:

[View project](<project-name>/)
Notes

Always run mkdocs serve from the repository root

Images must be inside docs\

Filenames must match exactly (case + extension)



---


## ✅ What this fixes
- ✔ No PowerShell commands
- ✔ No `ls`, no execution policy issues
- ✔ Works fully with **cmd.exe**
- ✔ Minimal and easy to remember


---


### Optional (recommended later)
If you ever switch to PowerShell, you can keep this README and add a second section — no conflict.