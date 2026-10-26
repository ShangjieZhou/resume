# Resume

LaTeX source for Shangjie Zhou's resume. `main.tex` is the only source file.

## Build

With [tectonic](https://tectonic-typesetting.github.io/):

```sh
tectonic main.tex
```

With a TeX Live install:

```sh
pdflatex main.tex
```

The preamble guards the pdfTeX-only `glyphtounicode` calls, so both engines work.
Overleaf (pdfLaTeX) also compiles it as is.
