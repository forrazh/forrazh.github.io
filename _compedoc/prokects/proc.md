---
title: Accélérateur matériel pour calcul de Pi
icon: fa-book 
year: feb 2024 - mar 2024
order: 8
author: [Gaylor Doisy, Hugo Forraz]
categories: [Projet, Cours]
tag: [vhdl, projects, cours, iot]
git: 
    author: Hugo Forraz
    name: master-hardware-courses
    link: https://gitlab.com/forrazh/master-hardware-courses/
meta_compétences: [Apprentissage] 
compétences_transférables: [Veille, Langues, Informatique]
qualités: [Autonomie, Rigueur]
expertise_scientifique: Monodisciplinaire 
compétences_sociales: [Curiosité]
compétences_transférables: [Capacité d'analyse, Élaborer des solutions]
---

Dans le cadre du master IoT, nous avons suivi des cours de **Hardware Design** où l'on a appris comment "programmer" un processeur. Ce module était composé de 2 cours durant chacun 24h. Lors du deuxième, nous avons développé un processeur en **VHDL** avec une accélération matérielle afin de faire le calcul du nombre PI à l'aide de la méthode **Monte-Carlo**.

Notre objectif final avec mon binome était de reussir à paralléliser le calcul en minimisant la place nécessaire sur la carte pour encore accelerer le calcul sans perdre en précision dans notre calcul.
On a réussi à monter jusque 16 coeurs avec un systeme en cascade, on a malheureusement manqué de temps pour passer sur un système en pyramide pour arriver à 32 ou 64 coeurs.

> Dans le cadre de ce cours, notre enseignant nous avait prêté une carte [Basys3](https://add_link.com) que nous avions programmé à l'aide de Vivado.
{: .prompt-info }

