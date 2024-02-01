# Humanités numériques : données ouvertes (HNU6055-A-H24)

On travail toujours avec des données, mais on s'en occupe peu.   
Dans les sciences humaines et les contextes culturels en particulier, on peut rapidement tomber sur des données sensibles. La voie la plus simple n'est pas forcément la meilleure et ce n'est pas parce que l'on peut théoriquement tirer quelque chose des données qu'il faut les utiliser sans les soumettre à un regard critique. Les données ne reflètent qu'une partie, par exemple une société qui a intériorisé la discrimination. Si l'on travaille ensuite avec les données, le résultat est également affecté par cette discrimination.

Shield : [![CC BY 4.0][cc-by-shield]][cc-by]

Cette œuvre est mise à disposition selon les termes de la
[licence Creative Commons Attribution 4.0 International][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: https://creativecommons.org/licenses/by/4.0/deed.fr
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

---

# Documentation
Ce référentiel est créé dans le contexte du cours Données ouvertes (HNU6055-A-H24). Il contient des résultats des exercices de ce cours. Il s’agit donc pas d’un projet de recherche, mais d’un projet pour apprendre des compétences à travailler avec des données ouvertes. 

## Source de données:
Documents publiés au Québec

[L]e jeu de données regroupe l'ensemble des documents (partitions musicales, publications officielles, livres, programmes de spectacles...) porteurs d'un ISBN qui ont été publiés au Québec depuis 2010 et acquis par dépôt légal, achat ou don.

Bibliothèque et Archives nationales du Québec (BAnQ) - Direction de l'Expérience et de la Transformation Numérique (DETN), Attribution (CC-BY 4.0)

https://www.donneesquebec.ca/recherche/dataset/documents_publies_quebec

# Prétraitement des données
Aucun prétraitement des données jusqu'à ce moment.

# Dossiers
Nomenclature utilisé dans ce projet:   
date(yyyymmdd)_contributeur_nomdeprojet_corpus_typededonnées_nomdefichier   

Abréviation des contributeurs:   
Juliane Benson: JB   

ex: 20240124_JB_donnee_ouvertes_docpubqc_histogram_freqlang.png  
date: 20240124  
contributeur: JB (Juliane Benson)  
nomdeprojet: donnee_ouvertes   
corpus: docpubqc (Documents publiés au Québec)   
typededonnées: histogram   
nomdefichier: freqlang (fréquence des langues)   

## Donnees
contient des tableaux de données.

**20240124_JB_donneesouvertes_docpubqc_table_donbrutes.zip** contient une table(.csv) avec la liste des documents publiées dès 2010 au Québec qui ont un ISBN ensemble avec des caractéristiques comme titre, createur, sujet, maison de livre, date, genre et langue. (accédé le 24 janvier 2024)

## Figures
inclut les figures/ visualisations générés.

**20240124_JB_donneesouvertes_docpubqc_histogram_freqlang.png** contient un histogram montrant la fréquence des langues du jeu de donnée documents publié au au Québec.

## Resultats
comprend des tableaux d'analyse et des données d'entrée pour générer les chiffres.

**20240124_JB_donneesouvertes_docpubqc_table_freqlang.csv** contient un table de fréquence des langues du jeu de donnée documents publié au au Québec.

## Scripts (pas existant)
Aucun code jusqu'à ce moment.
