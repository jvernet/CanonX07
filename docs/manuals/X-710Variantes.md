# Les variantes de la X-710 et les commandes

___
## Introduction

Le but ici est de donner un tableau des imprimantes équivalante à la X-710.\
En effet il s'agit d'imprimante issue de ALPS en marque blanche.

La mécanique et le fonctionnement est le même.\
La différences peut être dans les mots clés pour faire les tracés.

___
## Tableau

| Nom   | Marque | Année | Commentaire |
|-------|--------|-------|-------------|
| X-710 | Canon  | 1983  |             |


Tandy, commodore, ...

___
## Commandes

L'idée est de donner un résumé efficace des commandes pour ce type de traceur.

TO DO.

Tous passe par LPRINT. 

### Mode TEXTE

Valeur décimale

| Commande | Action |
|----------|---------|
| CHR$(8)  | 1 caractère vers la gauche |
| CHR$(10) | Passe à la ligne |
| CHR$(11) | Ligne précédente |
| CHR$(13) | Revient tout à gauche |

Taille et couleur des caractères :

LPRINT [I,J],"Hello World!"

I : Taille du caractère [1,16]\
J : Couleur [0:noir, 1:bleu, 2:vert, 3:rouge] - sauf si vous avez mis les stylots ailleurs.

Par défaut : 2,0

### Mode GRAPHIQUE

LPRINT CHR$(18)

| Commande | Action | Paramètre |
|----------|--------|-----------|
| L        |        |
| A        |        |
| H        |        |
| I        |        |
| D        |        |
| J        |        |
| M        |        |
| R        |        |
| C        |        |
| S        |        |
| Q        |        |
| P        |        |
| F        |        |

TO DO






___
