# Toprak Thesis v20 - Overleaf

This repository is the Overleaf-ready LaTeX edition of `Toprak Thesis v20.docx`.
Version 20 is the sole source of truth for the thesis text, equations, reported
results, table values, graph captions, appendix, and references.

## Compile

`main.tex` is the main document. The included `latexmkrc` selects XeLaTeX,
which is the preferred Overleaf compiler for the Pagella text and math fonts.

## Project structure

- `main.tex`: complete thesis source and Overleaf main document.
- `figures/`: vector PDF graphs generated from the thesis R outputs, plus the
  University of Amsterdam logo.
- `source/Toprak Thesis v20.docx`: canonical Word source used for this rebuild.
- `latexmkrc`: reproducible XeLaTeX build configuration.

Tables are native LaTeX `booktabs`/`longtable` tables rather than screenshots.
Graphs use vector PDFs that match the images embedded in version 20.
