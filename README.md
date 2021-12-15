# M1_carto
Cours de cartographie et statistiques Paris 1 (UFR de Géographie M1)

## Mode d'emploi 
1. Installer git R et Rstudio
2. Faire un git clone du repository L3_AD : git clone https://github.com/fbxyz/M1_carto.git
4. Installer les packages R knitr et xaringan. D'autres packages peuvent également être demandés en fonction de la configuration initiale de Rstudio
5. Ouvrir les fichiers .rmd dans Rstudio
6. Le fichier .env contient des variables communes à l'ensemble des documents, notamment l'année
7. Faire un Knit (Ctrl+shif+k) pour obtenir le cours en version HTML
8. Pour obtenir un fichier pdf, ouvrez le fichier HTML dans **Chromium ou Chrome** et imprimer en PDF. 

## N.B.
- Tous les packages ont été installés sous un environnement Linux. 
- La version de R utilisée est la 3.6
- La fonction PackageFacile() doit installer manuellement la plupart des packages. Dans le cas contraire, installer manuellement le package manquant
- Les documents HTML peuvent être ouvert directement en loca, à condition d'avoir téléchargé les dossiers libs et assets

## Organisation des diapositives
- Les cours sont construits avec xaringan https://github.com/yihui/xaringan
- Une nouvelle diapositive se déclare avec --- , une apparition sur une diapo avec --
- Le texte d'une diapositive est en Markdown 
- Le contenu des blocs de code R sont identifiables par cette syntaxe : ```{r echo=FALSE, out.width="100%"}  LE CODE R ``` 
- Les images de la présentation sont généralement intégrées avec le code R knitr::include_graphics("./assets/images/chemin_vers_l'image")
- Les class: en début de diapositive ou les blocs .class[] sont des éléments css. Les class s'appliquent à toutes la diapositive, les blocs aux élements entre les crochets. Par exemple .pull-left[XXXX] va justifier à gauche le contenu XXXX. .pull-left[] est défini dans /assets/css/theme_flo.css

