# Oxford report template
This is a template for writing generic reports (e.g. transfer of status) adapted to the Department of Computer Science.

I recommend `latexmk` to compile:
```sh
latexmk -synctex=1 -interaction=nonstopmode -file-line-error -pdf -outdir=out main

```
The PDF will be produced in `out/main.pdf`.

The template uses `biblatex/biber` for the bibliography; this can be adapted (or changed to `bibtex`) in `main.tex`.