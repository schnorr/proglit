## TD6: Le paradoxe du Duc de Toscane

À la cour de Florence, de nombreux jeux de société étaient alors
pratiqués. Parmi ceux-ci, l’un faisait intervenir la somme des numéros
sortis lors du lancer de trois dés. Le Duc de Toscane, qui avait sans
doute observé un grand nombre de parties de ce jeu, avait constaté que
la somme 10 était obtenue légèrement plus souvent que la somme 9. Le
paradoxe, que le Duc avait exposé à Galilée, réside dans le fait qu’il
y a autant de façons d’écrire 10 que 9 comme sommes de trois entiers
compris entre 1 et 6.

Pour avoir 9:
- 1+2+6, 1+3+5, 1+4+4, 2+2+5, 2+3+4, 3+3+3 (soit 6 possibilités)

Pour avoir 10:
- 1+3+6, 1+4+5, 2+2+6, 2+3+5, 2+4+4, 3+3+4 (soit 6 possibilités _aussi_)

### Quoi faire pour ce TD?

1. Faites une expérience pour démontrer que les sommes de 10
apparaissent plus fréquemment que les sommes de 9. Utilisez le langage
R pour exécuter l'expérience et dplyr pour faire les statistiques,
traçant les résultats avec ggplot2.
 - Faites une fonction R qui simule un dés de F faces
 - Faites une fonction R qui simule N expériences de lancer trois dés de F faces
 - Utilizer dplyr pour calculer la somme de trois dès
 - Compter le nombre de fois que chaque somme des trois dés apparaissent

2. Combien de répétitions expérimentales doivent être effectuées pour
s'assurer que la différence entre les sommes de 10 est statistiquement
significative par rapport aux sommes de 9?

3. Pourquoi les sommes de 10 sont plus fréquentes que les sommes de 9?
