# Toprak Thesis v12 - Overleaf

This repository is the Overleaf-ready LaTeX edition of `Toprak Thesis v12.docx`.
The thesis text, equations, reported results, table values, graph captions, and
references are preserved from the Word source.

## Compile

`main.tex` is the main document and compiles with Overleaf's default pdfLaTeX
setting. XeLaTeX remains the preferred compiler because it reproduces the
OpenType Pagella text and math fonts used in the original conversion. The
engine-aware preamble selects the closest Pagella-compatible fallback when
pdfLaTeX is used, so a fresh GitHub import compiles without a settings change.

## Project structure

- `main.tex`: complete thesis source and the Overleaf main document.
- `figures/`: vector PDF graphs regenerated from the current R outputs, plus the
  University of Amsterdam logo used on the title page.
- `latexmkrc`: reproducible XeLaTeX build configuration.

Tables are native LaTeX `booktabs`/`longtable` tables rather than screenshots or
Word grid tables. Graphs are vector PDF exports generated from the same R scripts
and result files used for the Word thesis.
