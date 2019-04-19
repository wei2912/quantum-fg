Quantum Focus Group
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

# Study Points

## Chapter 1

1. Explain change-of-basis matrix.
2. Figure out intuition for Gram-Schmidt procedure
3. See how <w_j|A|v_i> for a linear operator A: V -> W and orthonormal basis
|v_i> for V and |w_j> for W represents the matrix element in the ith column and
jth row for A.

