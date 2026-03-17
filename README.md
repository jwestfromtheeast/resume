# Resume

Personal resume built with LaTeX using Helvetica (TeX Gyre Heros) font.

## Prerequisites

Install BasicTeX via Homebrew:

```bash
brew install --cask basictex
```

Restart your terminal (or run `eval "$(/usr/libexec/path_helper)"`), then install required packages:

```bash
sudo tlmgr install titlesec enumitem fancyhdr helvetic tex-gyre
```

## Compile

```bash
pdflatex resume.tex
```

Output: `resume.pdf`
