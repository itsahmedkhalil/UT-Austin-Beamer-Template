# UTAustin-Metropolis-Theme

[University of Texas at Austin](https://www.utexas.edu/) color scheme for [Metropolis](https://www.ctan.org/pkg/beamertheme-metropolis) LaTeX beamer theme.

- Colors extracted from [Colors - On Brand](https://diversity.utexas.edu/brand/colors/)

## Usage

1. Copy `UTMetropolis.sty` to your project.
2. In your `main.tex`, set up Metropolis and load the package.
```tex
% Preamble
\documentclass[10pt]{beamer}
\usetheme[progressbar=frametitle]{metropolis}
\usepackage{appendixnumberbeamer}
\usepackage[small,bf]{caption}
\usepackage{UTMetropolis} 
```
3. Enjoy your presentation!