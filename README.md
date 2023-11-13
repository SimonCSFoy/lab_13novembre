# Les tableaux 1D - Laboratoire du 13 novembre 2023

## Exercice 1 - Affichage d'un tableau
Produisez un programme qui affiche __tous les éléments__ d'un tableau d'entiers __accompagnés de leurs index__ à la console. La gestion de l'affichage doit se faire dans une __fonction__ dont je vous laisse choisir le nom. Prenez le temps de choisir un __nom approprié__.
Voici à quoi devrait ressembler la sortie du programme pour le tableau `int[] tableau = {2, 4, 8, 9, 0}` : 
```console
Index 0 : 2
Index 1 : 4
Index 2 : 8
Index 3 : 9
Index 4 : 0
```

## Exercice 2 - Comparaison de tableaux
### Exercice 2.1
Produisez un programme qui compare deux tableaux d'entiers de __même dimension__ afin de déterminer s'ils sont égaux. Votre programme devrait faire l'utilisation d'au __minimum une fonction__.
Voici à quoi devrait ressembler la sortie du programme pour les tableaux `int[] tableau1 = {1, 2, 3, 4, 5}` et `int[] tableau2 = {1, 2, 3, 4, 5}` :
```console
Les deux tableaux sont égaux.
```
Voici à quoi devrait ressembler la sortie du programme pour les tableaux `int[] tableau1 = {1, 2, 3, 4, 5}` et `int[] tableau2 = {1, 2, 0, 4, 5}` :
```console
Les deux tableaux ne sont pas égaux.
```
### Exercice 2.2
Améliorez le programme du numéro 2.1 afin qu'il puisse __comparer deux tableaux d'entiers de tailles différentes__. Lorsque les deux tableaux sont de tailles différentes ils ne sont automatiquement pas égaux!
Voici à quoi devrait ressembler la sortie du programme pour les tableaux `int[] tableau1 = {1, 2, 3, 4}` et `int[] tableau2 = {1, 2, 3, 4, 5}` :
```console
Les deux tableaux ne sont pas égaux.
```

## Exercice 3 - Création, affichage et comparaison
Ce programme permettra à l'utilisateur de __comparer deux tableaux de son choix__. Le contenu de chaque tableau doit être affiché ainsi que le résultat de leur comparaison. 
Vous pouvez __assumer que l'utilisateur entre toujours des données valides__ (Par exemple, si le programme demande d'entrer un entier, il n'entrera pas de lettres). N'oubliez pas de séparer votre programme en fonctions! Évidemment, pensez à réutiliser les fonctions programmées aux numéros précédents.
Voici à quoi ressemble une exécution du programme lorsque l'utilisateur entre __deux tableaux égaux__ (`int[] tableau1 = {1, 2, 3, 4, 5}` et `int[] tableau2 = {1, 2, 3, 4, 5}`) : 
```console
Entrez la taille du tableau #1 : 5
Entrez l'élément à mettre à l'index 0 du tableau 1 : 1
Entrez l'élément à mettre à l'index 1 du tableau 1 : 2
Entrez l'élément à mettre à l'index 2 du tableau 1 : 3
Entrez l'élément à mettre à l'index 3 du tableau 1 : 4
Entrez l'élément à mettre à l'index 4 du tableau 1 : 5

Entrez la taille du tableau #1 : 5
Entrez l'élément à mettre à l'index 0 du tableau 2 : 1
Entrez l'élément à mettre à l'index 1 du tableau 2 : 2
Entrez l'élément à mettre à l'index 2 du tableau 2 : 3
Entrez l'élément à mettre à l'index 3 du tableau 2 : 4
Entrez l'élément à mettre à l'index 4 du tableau 2 : 5

## Tableau 1 ##
Index 0 : 1
Index 1 : 2
Index 2 : 3
Index 3 : 4
Index 4 : 5

## Tableau 2 ##
Index 0 : 1
Index 1 : 2
Index 2 : 3
Index 3 : 4
Index 4 : 5

Les deux tableaux sont égaux.
```

Voici à quoi ressemble une exécution du programme lorsque l'utilisateur entre deux tableaux __qui ne sont pas égaux__ (`int[] tableau1 = {1, 2, 3, 4, 5}` et `int[] tableau2 = {1, 2, 3, 4}`) : 
```console
Entrez la taille du tableau #1 : 5
Entrez l'élément à mettre à l'index 0 du tableau 1 : 1
Entrez l'élément à mettre à l'index 1 du tableau 1 : 2
Entrez l'élément à mettre à l'index 2 du tableau 1 : 3
Entrez l'élément à mettre à l'index 3 du tableau 1 : 4
Entrez l'élément à mettre à l'index 4 du tableau 1 : 5

Entrez la taille du tableau #1 : 4
Entrez l'élément à mettre à l'index 0 du tableau 2 : 1
Entrez l'élément à mettre à l'index 1 du tableau 2 : 2
Entrez l'élément à mettre à l'index 2 du tableau 2 : 3
Entrez l'élément à mettre à l'index 3 du tableau 2 : 4

## Tableau 1 ##
Index 0 : 1
Index 1 : 2
Index 2 : 3
Index 3 : 4
Index 4 : 5

## Tableau 2 ##
Index 0 : 1
Index 1 : 2
Index 2 : 3
Index 3 : 4

Les deux tableaux ne sont pas égaux.
```
