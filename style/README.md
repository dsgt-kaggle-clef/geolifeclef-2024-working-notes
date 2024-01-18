# LaTeX user template and guide

To compile user guide:

1. `pdflatex sample-1col`
2. `bibtex sample-1col`
3. `pdflatex sample-1col`
4. `pdflatex sample-1col`

and

1. `pdflatex sample-2col`
2. `bibtex sample-2col`
3. `pdflatex sample-2col`
4. `pdflatex sample-2col`

or

use the makefile:

`make`


For the "minted" versions:

1. `pdflatex -shell-escape sample-1col+minted`
2. `pdflatex -shell-escape sample-2col+minted`


