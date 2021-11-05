# VueCalc

![](https://gitlab.com/ticketchainer/vuecalc/-/raw/main/vuecal.png)

## Intro:

VueCal est une calculatrice vous permettant de réaliser des opérations de calculs arithmétique pour deux variables données. Elle comporte aussi une fonctionnalité qui permettra à l’utilisateur de garder en favoris les résultats de ses calculs.

L'interface de VueCal est divisée en deux parties: 

1. Le formulaire de calcul
 
ce dernier comporte  3 champs (inputs) :

* Type de l'opération :  (+ addition), (- soustraction), (* multiplication) et (/ division)
* Variable 1 (à gauche)
* Variable 2 (à droite)

Le résultat doit être affiché instantanément en fonction de la valeur des 3 derniers champs.

En plus : 

Un bouton "réinitialiser" permet de remettre à zéro tous les champs du formulaire.
Un bouton "Ajouter aux favoris" qui permet d'ajouter l'opération et le résultat dans la liste de favoris.


2. Liste des opérations favoris


Comme indiqué dans la section précédente, une fois que l'utilisateur clique sur le bouton d'ajout aux favoris, une nouvelle ligne doit être rajoutée dans la liste avec les informations suivants:

- Date et heure de l'opération
- Opération
- Résultat
- un bouton "poubelle" pour supprimer la ligne des favoris.

Il faut noter que l’affichage des résultats est par ordre antéchronologique.


## Travail demandé

Pour cet exercice, il est demandé de réaliser ce projet avec le framework **Vue.js version 3** + **Typescript** ainsi que **VueX** et  **composition api**

## Compétences évaluées


* Nommage des structures de données
* Organisation du code
* Respect des bests practices de Vue
* Utilisation d'un framework css telque Bootstrap, Vuetify , Tailwind ou autres.


## Modalités pour le rendu de l'exercice

Le résultat de l'exercice doit être livré dans un dépôt de code public sur Github, Gitlab ou Bitbucket.


