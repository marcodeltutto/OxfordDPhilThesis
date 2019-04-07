# OxfordDPhilThesis

## To build the document

Run the following commands to build the document, they run latex, biber for the bibliography, and mpost for the Feynman graphs.

```
pdflatex --file-line-error --synctex=1 main.tex

biber main

mpost fgraphs
mpost fgraphs2
mpost fyW
mpost fyZ
mpost fyW_a
mpost fyW_b
mpost fyDeltaPlus
mpost fyCoh
mpost fyDIS

pdflatex --file-line-error --synctex=1 main.tex
```
