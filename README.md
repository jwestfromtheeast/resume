# Resume

Personal resume built with LaTeX using Helvetica (TeX Gyre Heros) font.

## Versions

- `resume.tex` — general-purpose resume (skills summarized at the bottom).
- `resume-ironstead.tex` — tailored for Ironstead (Sep 2026): adds a `Tech stack:` line under each role via the `\resumeStack{...}` macro, which is also defined in `resume.tex` for future tailored copies.

Tailored copies should stay on one page; `resume-ironstead.tex` trims top/bottom margins to 0.45in to fit.

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
pdflatex resume.tex            # or: pdflatex resume-ironstead.tex
```

Output: `resume.pdf` (or `resume-ironstead.pdf`)
