# Toprak Thesis v9 - Overleaf

This repository is the Overleaf-ready LaTeX edition of `Toprak Thesis v9.docx`.
The thesis text, equations, reported results, table values, graph captions, and
references are preserved from the Word source.

## Compile

The project uses XeLaTeX because the thesis uses an OpenType text and math font.
Overleaf reads `latexmkrc` automatically, so `main.tex` can be compiled without
changing the compiler in the project settings.

## Project structure

- `main.tex`: complete thesis source and the Overleaf main document.
- `figures/`: vector PDF graphs regenerated from the current R outputs, plus the
  University of Amsterdam logo used on the title page.
- `source/Toprak Thesis v9.docx`: unchanged Word source retained for comparison.
- `latexmkrc`: reproducible XeLaTeX build configuration.

Tables are native LaTeX `booktabs`/`longtable` tables rather than screenshots or
Word grid tables. Graphs are vector PDF exports generated from the same R scripts
and result files used for the Word thesis.
