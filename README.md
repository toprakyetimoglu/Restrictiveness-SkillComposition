# Toprak Thesis V23 - Overleaf

This repository is the Overleaf-ready LaTeX edition of `Toprak Thesis V23.docx`.
Version 23 is the sole source of truth for the thesis text, equations, reported
results, table values, graph captions, appendix, and references.

## Compile

`main.tex` is the main document. The included `latexmkrc` selects XeLaTeX,
which is the preferred Overleaf compiler for the Pagella text and math fonts.

## Project structure

- `main.tex`: complete thesis source and Overleaf main document.
- `figures/`: the four high-resolution graphs embedded in Version 23, plus the
  University of Amsterdam logo.
- `source/Toprak Thesis V23.docx`: canonical Word source used for this rebuild.
- `latexmkrc`: reproducible XeLaTeX build configuration.

Tables are native LaTeX `booktabs`/`longtable` tables rather than screenshots.
Graphs match the images embedded in Version 23 exactly.
