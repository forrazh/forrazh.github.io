---
title: Triangulation par WiFi
icon: fa-book 
year: 2024
order: 3
author: [Gaylor Doisy, Hugo Forraz, Maximilien Weinmann ]
categories: [Projets, Cours]
tag: [rust, cours, iot, networking]
git: 
    author: forrazh
    name: wifi-triangulation
    link: https://gitlab.com/forrazh/wifi-triangulation
meta_skills: [apprentissage, adaptabilité] 
transf_skills: [Communication Orale, Planification, Langues, Informatique]
qualities: [autonomie, rigueur, créativité, ouverture d'esprit]
scientific_expertise: Monodisciplinaire
social_skills: [curiosité, persévérance, confiance en soi]
transv_skills: [Remise en question, Travailler en équipe, Capacité d'analyse, Capacité d'innovation, Formuler un problème, Elaborer des solutions]
---

Dans le cadre de mon master, nous avons suivi un cours sur les **réseaux de capteurs**, qui est une thématique assez importante pour l'IoT. Dans les objectifs de ce cours, nous devions réaliser un projet libre en groupe.
Avec mes deux camarades, nous avons choisi de modéliser un système permettant de trianguler un appareil servant de hotspot Wi-Fi.

L'une des difficultés principales de ce projet a été de réussir à faire coexister du codes pour 3 cartes différentes et ayant des chaines de compilation différentes. À l'origine, on trouvait aussi un peu plus intéressant l'idée de réaliser ce projet sur du bluetooth mais les temps de développement nécessaires étaient trop élevés ce qui nous a fait revoir nos ambitions à la baisse.

> Les cartes utilisées étaient un Raspberry Pico et 2 esp32. Comme pour le [projet manette](https://forrazh.github.io/compedoc/controller/), la librairie Rust utilisée ne permettait pas encore à ce moment là d'utiliser le bluetooth sur nos cartes. 
{: .prompt-info }

La version rendue de notre projet consistait à montrer à l'aide de LEDs où un téléphone servant de point d'accès wifi se situe dans un couloir de quelques mètres.
