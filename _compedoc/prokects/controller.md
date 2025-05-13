---
title: Oxyded metal game controller
icon: fa-book 
year: avr 2023
order: 10
author: Hugo Forraz
categories: [Projet, Cours]
tag: [rust, projects, embassy, cours]
git: 
    author: forrazh
    name: Oxyded metal game controller
    link: https://gitlab.com/forrazh/oxyded-metal-game-controller

meta_skills: [apprentissage, adaptabilité] 
transf_skills: [Communication écrite, Planification, Veille, Valorisation, Informatique]
qualities: [autonomie, rigueur, créativité]
scientific_expertise: Monodisciplinaire 
social_skills: [curiosité,  persévérance]
transv_skills: [Remise en question, Capacité d'analyse, Capacité d'innovation, Formuler un problème, Elaborer des solutions, Esprit critique]
---

Le master informatique à Lille a une UE projet à valider chaque année lorsque l'on n'est pas alternant. Pour cette UE, nous avons la possibilité de proposer notre propre projet. 
J'avais depuis maintentenant quelques temps l'envie de réaliser un projet sur de l'embarqué et de le faire en Rust, un langage de programmation bas niveau que j'ai commencé à apprendre au début de mon M1 sur mon temps libre.
Ce langage ayant le vent en poupe depuis maintenant quelques années, on trouve de plus en plus de projets open source permettant de faire de plus en plus de choses à l'aide de ce langage. 

L'envie de faire une manette plutot qu'un autre appareil est arrivée lors d'une soirée jeux vidéos chez un ami qui m'a prêté une manette que je n'avais jamais essayé au par avant et m'a donné envie de comprendre un peu mieux comment ces appareils fonctionnent.
Le professeur m'encadrant était lui aussi assez intérressé par ce projet par envie de changer le module de développement embarqué d'un cours que l'on reçoit en master en rajoutant du Rust sur le dernier TP qui lui semblait être un choix plus pertinent pour l'avenir du domaine.

Après un mois de recherches, de tests, de petites galères, j'ai réussi à proposer quelque chose qui était réutilisable pour proposer une base de projet pour les futurs étudiants. Malheureusement, je n'ai pas eu le temps à ce moment là de rajouter le bluetooth sur cette manette étant donné que c'était quelque chose d'assez neuf sur le microcontrolleur utilisé. En effet, le module permettant d'utiliser le bluetooth sur le firmware est sorti 2 semaines après le début de mon projet et donc pas encore adapté à être utilisé de partout, quelque soit le langage. 

Ce projet m'a aussi permis de refaire un petit peu d'électronique, chose que l'on a assez peu l'occasion de faire en développement.


<!-- ### Description de l’activité

Contexte dans lequel vous avez exercé cette activité (entreprise, institution, association, secteur, taille, etc.) : Academique

Dans quel but avez-vous exercé cette activité ? : Valider un projet universitaire + Finir de se former au Rust + decouverte sur de l'embarqué

Décrivez de façon détaillée cette activité (il ne s’agit pas de décrire ce que vous auriez dû faire mais ce que vous avez fait réellement) : Realisation du programme d'une manette permettant de jouer à des jeux vidéos

Moyens (matériels, financiers, humains), outils, instruments, procédures, méthodes, techniques utilisés: 
- materiels : Raspberry Pi 4, Raspberry Pico, Rust, Git, Embassy, imprimante 3D (coque de la manette)
- humains : encadrement par un professeur
- techniques : retroingénierie de manettes, suivi des bonnes pratiques de developpement pour mon materiel

Pouvez-vous expliquer une situation-problème que vous avez eu à résoudre et la manière dont vous avez procédé ? Reussir à flasher correctement la board. Pour regler ces difficultés, il a fallu beaucoup travailler sur la chaine de compilation et sortir un Raspberry Pi servant d'intermediaire.

### Auto-évaluation

Qu’avez-vous particulièrement réussi ? Qu’avez-vous aimé ? : 
- La decouverte du milieu
- Un projet qui me faisait assez envie
- Donner envie à mon encadrant de passer ce projet dans un cours

Qu’est-ce qui vous a posé difficulté ? Que n’avez-vous pas aimé ? : 
- Trouver le temps de mettre en place le bluetooth qui était à ce moment là encore assez neuf pour cette carte.

Que changeriez-vous si vous deviez recommencer ? : Les discussions préliminaires qui sont arrivées trop tard et qui m'ont fait bacler la fin du projet à cause du début de mon stage -->