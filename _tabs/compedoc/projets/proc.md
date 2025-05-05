## Calcul de PI sur du hardware

Repo : https://gitlab.com/forrazh/master-hardware-courses/-/tree/main?ref_type=heads

### Description de l’activité

Contexte dans lequel vous avez exercé cette activité (entreprise, institution, association, secteur, taille, etc.) : Académique

Dans quel but avez-vous exercé cette activité ? : Projet dans le cadre d'un cours

Décrivez de façon détaillée cette activité (il ne s’agit pas de décrire ce que vous auriez dû faire mais ce que vous avez fait réellement) : Developpement d'un processeur en VHDL avec une accélération matériel afin de faire le calcul du nombre PI à l'aide de la méthode Monte-Carlo.

Moyens (matériels, financiers, humains), outils, instruments, procédures, méthodes, techniques utilisés: 
- materiels : Basys3, Vivado, VHDL, cours
- humains : binome

Pouvez-vous expliquer une situation-problème que vous avez eu à résoudre et la manière dont vous avez procédé ? 
Reussir à paralléliser le calcul en minimisant la place nécessaire sur la carte pour encore accelerer le calcul sans perdre en précision.
On a réussi à monter jusque 16 coeurs avec un systeme en cascade, on a malheureusement manqué de temps pour passer sur un système en pyramide pour arriver à 32 ou 64 coeurs.

### Auto-évaluation
Qu’avez-vous particulièrement réussi ? Qu’avez-vous aimé ? : 
- La decouverte de ce milieu (j'en ai hésité à faire ma thèse sur ce domaine)
- la réalisation de ce projet au global 

Qu’est-ce qui vous a posé difficulté ? Que n’avez-vous pas aimé ? : 
- Rien

Que changeriez-vous si vous deviez recommencer ? : La mise en place de certains IP qui aurait pu faire gagner beaucoup de temps sur les differents developpements

