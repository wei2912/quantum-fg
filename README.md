Quantum Focus Group [![CircleCI](https://circleci.com/gh/wei2912/quantum-fg.svg?style=svg)](https://circleci.com/gh/wei2912/quantum-fg)
======

A collection of notes on various topics in quantum-related fields.

# Build Instructions

The book is structured with a main file `book.tex` and the chapters listed in
sequential order. References are located in `references.bib` and written in
BibTeX format. To build the book, run these commands:

```bash
latex book.tex
bibtex book.aux
latex book.tex
latex book.tex
```

LaTeX needs to be runned multiple times, due to the limitations of BibTeX. If
you'd like to generate a PDF file, just replace `latex` with `pdflatex` in the
last command.
