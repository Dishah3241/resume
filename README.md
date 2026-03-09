# Resume

Resume and versions, deployed via GitHub Pages.

## Structure

- `versions/resume.html` - Current resume (HTML)
- `versions/resume.tex` - LaTeX source

## Generating PDF

Requires a LaTeX installation. Install via Homebrew if needed:

```bash
brew install --cask mactex-no-gui
```

Then compile:

```bash
pdflatex versions/resume.tex
```

Output: `resume.pdf` in the current directory.

Alternatively, upload `versions/resume.tex` to [Overleaf](https://overleaf.com) and compile online.

## Deployment

GitHub Pages can serve this repo. Enable in **Settings > Pages** and choose the branch (e.g. `main`) and folder (`/` or `/versions`).

## Remote

```
https://github.com/Dishah3241/resume.git
```
