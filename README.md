# Sazba textu české lidové písně „Když jsem já sloužil“ pomocí modulu l3seq jazyka expl3

Tento repozitář obsahuje zdrojový kód článku *Sazba textu české lidové písně
„Když jsem já sloužil“ pomocí modulu l3seq jazyka expl3* ze Zpravodaje CSTUGu
2023/3–4.

PDF dokument [`main.pdf`][1] s textem článku vysázíme následujím příkazem:

``` bash
latexmk -lualatex -shell-escape main.tex
```

Jako vedlejší produkt sazby vznikne soubor [`kdyz-jsem-ja-slouzil.sty`][2]
s LaTeXovým balíčkem pro sazbu textu písně, který jsme v článku vyvinuli,
a soubor [`priklad-latex.tex`][3] s ukázkou použití balíčku.

Jako vedlejší produkt sazby vznikne také soubor [`kdyz-jsem-ja-slouzil.opm`][4]
s OpTeXovým balíčkem pro sazbu textu písně, který jsme v článku také vyvinuli,
a soubor [`priklad-optex.tex`][5] s ukázkou použití balíčku.

 [1]: https://github.com/Witiko/typesetting-czech-folksong-with-l3seq/releases/download/latest/main.pdf
 [2]: https://github.com/Witiko/typesetting-czech-folksong-with-l3seq/releases/download/latest/kdyz-jsem-ja-slouzil.sty
 [3]: https://github.com/Witiko/typesetting-czech-folksong-with-l3seq/releases/download/latest/priklad-latex.tex
 [4]: https://github.com/Witiko/typesetting-czech-folksong-with-l3seq/releases/download/latest/kdyz-jsem-ja-slouzil.opm
 [5]: https://github.com/Witiko/typesetting-czech-folksong-with-l3seq/releases/download/latest/priklad-optex.tex

## Citace

Pro citování tohoto článku použijte následující kód pro BibLaTeX:

``` bib
@article{starynovotny2023sazba,
  title = {Sazba textu české lidové písně „Když jsem já sloužil“ pomocí modulu l3seq jazyka expl3},
  author = {Starý Novotný, Vít},
  journal = {Zpravodaj \CSTUG u},
  issn = {1211-6661},
  year = {2023},
  volume = {33},
  number = {3--4},
  doi = {10.5300/2023-3-4/153},
  pages = {153-164},
}
```
