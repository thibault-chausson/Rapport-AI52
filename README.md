# Rapport sur l'utilisation de différentes métaheuristiques

Le rapport est disponible [ici](./rapport.pdf).

## Objectifs

Nous avons souhaité résoudre un problème d'ordonnancement (la création d'emplois du temps) en utilisant différentes métaheuristiques. Nous avons réalisé à la main quelques itérations de chaque algorithme : 
- Recuit simulé
- Recherche taboue
- Algorithme génétique
- Colonie de fourmis
- Essaim particulaire

## Résultats

En analysant les performances de ces cinq métaheuristiques, il est notable que les algorithmes à population (comme l'algorithme génétique), la recherche taboue et le recuit simulé sont particulièrement efficaces pour ce type de problème.
Cette efficacité s'explique en grande partie par la facilité à modéliser le problème de façon similaire aux emplois du temps courants, mais aussi une exploration efficacement l'espace des solutions et d'obtenir rapidement de bons résultats.

Concernant l'approche par colonie de fourmis, bien que nous ayons adapté le problème des emplois du temps sous forme de graphe pour le rapprocher du problème du voyageur de commerce (où cet algorithme excelle), les améliorations apportées à la solution restent limitées, ne faisant pas de cette méthode la plus efficace pour notre cas.
Quant à l'essaim particulaire, nous n'avons pas réussi à trouver une modélisation adaptée à ce problème.

En résumé, pour la résolution de problèmes d'emploi du temps, les méthodes les plus efficaces s'avèrent être l'algorithme génétique, la recherche taboue et le recuit simulé.
Pour améliorer encore cette solution, nous pouvons créer avec l'algorithme génétique une très bonne solution et l'améliorer avec une recherche taboue ou un recuit simulé.

## Collaborateurs

- CHAUSSON Thibault : [GitHub](https://github.com/thibault-chausson) - [LinkedIn](https://www.linkedin.com/in/thibault-chausson/)
- GUINOT Jossua : [GitHub](https://github.com/UnTabouret) - [LinkedIn](https://www.linkedin.com/in/jossua-guinot-283342176/)
- VIGUIER Léo : [GitHub](https://github.com/LeoViguier) - [LinkedIn](https://www.linkedin.com/in/léo-viguier-aa42941b0/)