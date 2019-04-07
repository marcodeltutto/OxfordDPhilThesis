# OxfordDPhilThesis

## To build the document

Run the following commands to build the document, they run latex, biber for the bibliography, and mpost for the Feynman graphs.

```
latex main.tex

biber bibliography

mpost fgraphs
mpost fgraphs2
mpost fyW
mpost fyZ
mpost fyW_a
mpost fyW_b
mpost fyDeltaPlus
mpost fyCoh
mpost fyDIS

latex main.tex
```
