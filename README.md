To build the book, run the following commands in order once you've ensured that
the packages listed in `book.tex` have been installed on your system.

```bash
latex book.tex
bibtex book.aux
latex book.tex
latex book.tex
```

The `latex` command is repeated thrice due to the limitations of the `bibtex`
package.

