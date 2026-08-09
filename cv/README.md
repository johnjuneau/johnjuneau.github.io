# CV source

Place the LaTeX source for the CV in this directory (for example, `cv.tex`).

This template requires XeLaTeX because it uses `fontspec` and bundled OpenType/TrueType fonts. Compile it from this directory with:

```sh
latexmk -xelatex juneau_01_13_2025.tex
```

When compiled, copy the finished PDF to `../files/John_Juneau_CV.pdf` so it can be served at `/files/John_Juneau_CV.pdf` on the website.
