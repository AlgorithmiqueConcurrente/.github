# Algorithmique des Structures de Données Concurrentes

Cette organisation contient les ressources et projets liés au cours **Programmation Distribuée** de Nantes Université.

## Description du module

Ce cours est destiné à des étudiants de M1 en Informatique, ainsi qu'à toute personne s'intéressant à la synchronisation des systèmes répartis.

Le responsable du module est Matthieu Perrin.

Les volumes horaires dédiés à ce cours à Nantes Université (séances de 1h20) sont les suivants :
- Cours magistraux : 12h
- Travaux dirigés : 12h

### Contenu
- Modèles et primitives de synchronisation
  - asynchronisme et pannes
  - instructions atomiques
- Conception et analyse des structures non-bloquantes
  - conditions de progression : lock-freedom et wait-freedom
  - algorithmes de structures de données non-bloquantes : piles, files, compteurs
- Résultats fondamentaux
  - impossibilité du consensus
  - hiérarchie de Herlihy

### Résultats d'apprentissage
À la fin de ce cours, un étudiant doit être capable de :
- Identifier la condition de progression (lock-freedom, wait-freedom) d’un algorithme concurrent donné.
- Concevoir une structure de données non-bloquante simple en respectant les principes de progression.
- Identifier et expliciter les hypothèses nécessaires à la conception d’une structure de données concurrente.
- Mettre en œuvre un algorithme de structure de données non-bloquante dans un langage de programmation orienté objet.

### Bibliographie
- M. Raynal. **Concurrent Programming – Algorithms, Principles, and Foundations**, Springer, 2013.

## Dépôts principaux
Organisation en construction : les ressources ne sont pas encore disponiblae.  
- [**CM**](https://github.com/AlgorithmiqueConcurrente/CM) — Slides de cours.
  - [Slides](https://AlgorithmiqueConcurrente.github.io/CM/slides.pdf): version PDF avec animations
  - [Handout](https://AlgorithmiqueConcurrente.github.io/CM/handout.pdf): version PDF sans animation
- [**TD**](https://github.com/AlgorithmiqueConcurrente/TD) — Énoncés et corrections de TD.
  - Dépôt privé accessible aux enseignants sur demande

## Cours liés
Ce cours a été conçus comme la deuxième partie sur trois d'un cours sur la synchronisation des systèmes répartis : 
- [**Programmation Concurrente en Multi-Thread**](https://github.com/ProgrammationMultiThread) — Programmation multi-threads bloquante en mémoire partagée.
- [**Programmation Distribuée**](https://github.com/AlgorithmiqueConcurrente) — Algorithmique concurrente non-bloquante en mémoire partagée.
- [**Services de Communication et Systèmes Distribués**](https://github.com/DistributedComputing) — Algorithmique tolérante aux pannes en passage de messages.

## Licence
Sauf mention contraire, les contenus sont sous licence
- [Creative Commons Attribution - ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) pour les sources LaTeX.
- [MIT](https://opensource.org/licenses/MIT) pour les projets Java.
