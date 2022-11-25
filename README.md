# Chalmers/GU beamer theme

A fork of [simonpf/chalmers_beamer_theme](https://github.com/simonpf/chalmers_beamer_theme)
that tries to imitate the most recent presentation templates from University of
Gothenburg (GU) and Chalmers

## Installation

Copy the folder containing the repository to the `tex/latex/` subtree of your
`texmf` folder. On unix systems this usually boils down to the following:

```
cp -r chalmers_beamer_theme ~/texmf/tex/latex/
```

## Usage

After installation, the package can be used by simply calling the `\usetheme` command:

```
\documentclass[presentation]{beamer}
...
\usetheme{chalmers}
...
```
## Options

Options `gu`, `chalmers`, and `gu_chalmers` set up the title graphic and logo.
These may be customized, as the template now honours the Beamer commands
`\logo{}` and `\titlegraphic{}`.

Option `simple_logo`, when used with `chalmers`, loads a logo without the
"Avancez" emblem. It has no effect when used with `gu` or `gu_chalmers`.

Option `copper` uses "Chalmers copper" as the main colour; the default is to
use a shade of dark blue coming from GU and Chalmers PowerPoint templates.
