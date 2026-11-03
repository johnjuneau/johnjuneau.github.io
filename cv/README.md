# CV and private résumé sources

Place the LaTeX source for the CV in this directory (for example, `cv.tex`).

This template requires XeLaTeX because it uses `fontspec` and bundled OpenType/TrueType fonts. Compile it from this directory with:

```sh
latexmk -xelatex juneau_01_13_2025.tex
```

When compiled, copy the finished PDF to `../files/John_Juneau_CV.pdf` so it can be served at `/files/John_Juneau_CV.pdf` on the website.

The private-sector résumé is `jjuneau_resume.tex`. Build it from this directory
with:

```sh
latexmk -xelatex jjuneau_resume.tex
```

Both `jjuneau_resume.tex` and `jjuneau_resume.pdf` are explicitly excluded from
the Jekyll build in `_config.yml`, so the résumé can remain in this repository
without being published on the website.

The consulting CV is `consulting_CV.tex`. Build it with:

```sh
latexmk -xelatex consulting_CV.tex
```

Its source and PDF are also explicitly excluded from the Jekyll build.
