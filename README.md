# UWSeattle-Metropolis-Theme

[University of Washington Seattle](https://www.washington.edu/) color scheme for [Metropolis](https://www.ctan.org/pkg/beamertheme-metropolis) LaTeX beamer theme.

- Colors extracted from [Colors](https://www.washington.edu/brand/graphic-elements/primary-color-palette/).

## Usage

1. Copy `UWMetropolis.sty` to your project.
2. In your `main.tex`, set up Metropolis and load the package.
```tex
% Preamble
\documentclass[10pt]{beamer}
\usetheme[progressbar=frametitle]{metropolis}
\usepackage{appendixnumberbeamer}
\usepackage[small,bf]{caption}
\usepackage{UWMetropolis} 
```
3. Enjoy your presentation!