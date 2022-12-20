# FAS1002_projet-final

[![](https://img.shields.io/badge/Licence-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/deed.fr)

Rapport réalisé pour le cours [FAS1002 - Initiation à la programmation en sciences sociales](https://admission.umontreal.ca/cours-et-horaires/cours/fas-1002/) qui est offert dans le cadre du [Microprogramme de 1er cycle en analyse des mégadonnées en sciences humaines et sociales](https://admission.umontreal.ca/programmes/microprogramme-de-1er-cycle-en-analyse-des-megadonnees-en-sciences-humaines-et-sociales/structure-du-programme/). Ce rapport se focalise sur les relations existantes entre le PIB par habitant, l'espérance de vie à la naissance et les émissions de CO2 et de gaz à effet de serre.

## Importation

Le projet se base sur deux banques de données différentes : [CO2 and Greenhouse Gas Emssions, Our World in Data](https://github.com/owid/co2-data) et [Life Expectancy at Birth, Gapminder](https://www.gapminder.org/tag/life-expectancy/)

## Structure du répertoire

``` bash
├── 404.qmd
├── a-propos.qmd
├── assets
│   ├── img
│   │   └── FAS1002.png
│   └── scss
│       ├── styles.css
│       └── styles-dark.scss
├── data
│   ├── processed
│   └── raw
├── exploration.qmd
├── FAS1002_projet-final.Rproj
├── figures
├── _freeze
│   └── ...
│      └── contenu des computations
├── import.qmd
├── index.qmd
├── intro.qmd
├── LICENSE
├── _quarto.yml
├── R
├── README.md
└── references.bib

33 directories, 46 files
```

## Principaux documents regroupant l'analyse

-   L'**import.qmd** présentes des informations complémentaires sur les banques de données importées et leur provenance.
-   L'**index.qmd** présente le sujet du projet et met en contexte le lecteur.
-   L'**intro.qmd** apporte une analyse plus profonde et met en lien les différentes variables des deux tables de données combinés.
-   L'**exploration.qmd** offre des analyses descriptives sur les banques de données individuelles.

## Principaux packages R utilisés dans ce site:

-   R Core Team (2020). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. <https://www.R-project.org/>

-   H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2016. <https://ggplot2.tidyverse.org>

-   C. Sievert. Interactive Web-Based Data Visualization with R, plotly, and shiny. Chapman and Hall/CRC. Florida, 2020. <https://plotly-r.com>

-   H. Wickham, J. Bryan, RStudio, M. Kalicinski, K. Valery, C. Leitienne, B. Colbert, D. Hoerl, E. Miller. Import excel files into R. R package version 1.4.1.<https://cran.r-project.org/package=readxl>

-   V. Spinu, G. Grolemund, H. Wickham, D. Vaughan, I. Lyttle, I. Costigan, J. Law, D. Mitarotonda, J. Larmarange, J. Boiser, C. Hee Lee. Functions to work with date-times and time-spans: fast and user friendly parsing of date-time data, extraction and updating of components of a date-time, algebraic manipulation on date-time and time-span objects. R package version 1.9.0.<https://cran.r-project.org/package=lubridate>

-   Vincent Arel-Bundock, CJ Yetman, Nils Enevoldsen, Samuel Meichtry. Standardize country names, convert them into one of 40 different coding schemes, convert between coding schemes, and assign region descriptors. R package version 1.4.0. <https://cran.r-project.org/package=countrycode>

-   T. Wei, V. Simko, M. Levy, Y. Xie, Y. Jin, J. Zemla, M. Freidank, J. Cai, T. Protivinsky. Provides a visual exploratory tool on correlation matrix that supports automatic variable reordering to help detect hidden patterns among variables. R package version 0.92. <https://cran.r-project.org/package=corrplot>

## Licence

Cette œuvre est mise à disposition selon les termes de la [licence Creative Commons Attribution - Partage dans les Mêmes Conditions 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/deed.fr).

[![](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/deed.fr)
