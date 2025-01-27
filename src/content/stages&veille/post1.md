---
title: "Stage de première année - BTS SIO | Mazedia"
description: "Stage de première année en BTS SIO, réalisé au sein de l'entreprise Mazedia, situé à Saint-Herblain"
pubDate: "Jul 10 2024"
heroImage: "/mazedia.webp"
tags: ["Angular", "Docker", "Autonomie"]
---

Pour ma première année de BTS SIO, j'ai réalisé un stage de 7 semaines en entreprise. Pour cette première expérience professionnelle,
j'ai intégré Mazedia, une société située à Saint-Herblain.

**Qu'est-ce que Mazedia ?**

Mazedia, fondée en 1994, est une entreprise spécialisée dans la conception et le développement d'outils numériques pour les secteurs de la culture,
de la vente et de la communication. Celle-ci se concentre sur l’expérience utilisateur, en combinant créativité et expertise technique pour proposer des solutions telles que des bornes interactives ou des applications mobiles. De plus, Mazedia met à disposition un logiciel, appelé Wezit, permettant aux clients d’administrer les contenus de tous les types de programmes de médiation pour les expositions, optimisant ainsi l'interactivité et l'engagement des visiteurs dans les lieux culturels.

---

Durant mon stage, j'ai du conceptionner une application mobile nommée _Wezit Compagnon_, destinée à simplifier l'utilisation du logiciel Wezit de l'entreprise sur mobile. L'application est structurée en trois niveaux : d'abord, les entités, qui représentent les organisations en lien avec l'entreprise (clients), ensuite les applications associées à leurs activités, et enfin les différentes versions de ces applications. Cela permet aux clients d'accéder plus facilement aux programmes et contenus de leurs organisations directement depuis leurs appareils mobiles. Et pour réaliser ce projet, j'ai du utilisé le framework JavaScript, Angular (version 17).

![wezit homepage](/wezit_homepage.webp)
![wezit application](/wezit_application.webp)
![wezit version](/wezit_version.webp)

**Qu'est-ce que l'Angular ?**

Angular est un framework JavaScript open-source, développé par Google, qui permet de créer des applications web dynamiques et robustes.
Il est principalement utilisé pour développer des interfaces utilisateur basées sur une architecture de composants.
Angular facilite le développement de grandes applications web tout en assurant une bonne performance.

---

Lors de ma première semaine de stage, n'ayant aucune expérience avec ce framework, l'entreprise m'a donné une totale autonomie pour découvrir l'Angular 17. Pour cela, j'ai réalisé un mini-projet de cartes à collectionner de monstres en suivant des tutoriels de la chaîne YouTube [SimpleTeck](https://www.youtube.com/@SimpleTechProd). Voici mon projet : [Monster Collection](https://github.com/eddy8chsl/Monster-Collection.git).

Ensuite, durant ma deuxième semaine, j'ai commencé à concevoir les bases de l'application en utilisant mes propres données (entités, applications, versions). En parallèle, avec mon maître de stage, nous avons intégré un espace de connexion, déjà créé par l'entreprise, en utilisant Keycloak-Angular.

**Qu'est ce que Keycloak-Angular ?**

Keycloak-Angular est une bibliothèque qui permet d'intégrer facilement Keycloak, une solution de gestion des identités et des accès, dans des applications Angular. Elle facilite l'authentification des utilisateurs, la gestion des rôles et des permissions, tout en sécurisant les routes de l'application. Grâce à cette intégration, les développeurs peuvent rapidement mettre en place des connexions sécurisées.

![wezit connection](/wezit_connection.webp)

---

Par la suite, j'ai continué d'alimenter le projet jusqu'à la sixième semaine, en intégrant d'abord les données de l'entreprise pour relier directement les entités à leurs applications correspondant. J'ai également ajouté des fonctionnalités, telles que la possibilité de trier les versions des applications en fonction des différentes plateformes (Android, iOS, Unity, etc.), ainsi que la création de pop-ups expliquant comment installer les applications sur chacune de ces plateformes.

![wezit pop-ups](/wezit_pop-ups.webp)

Et enfin, lors de la septième et dernière semaine, j'ai dû me familiariser avec les bases de Docker pour préparer la mise en production de _Wezit Compagnon_ et garantir son exploitation sur n'importe quelle plateforme dont principalement sur Androis et IOS.

**Qu'est ce que Docker ?**

Docker est un outil qui permet de créer, déployer et gérer des applications dans des conteneurs. Un conteneur regroupe tout ce dont une application a besoin pour fonctionner (code, dépendances, configuration), ce qui la rend facilement transportable et exécutable sur n'importe quel environnement. Cela simplifie le déploiement, évite les conflits entre environnements et garantit que l'application fonctionne de la même manière partout.

---

Pour conclure, ce stage chez Mazedia m'a permis de développer mes compétences techniques, notamment en Angular et Docker, ainsi que de mieux comprendre le processus de développement d'une application en sein d'un environnement professionnel. Grâce à cette expérience, j'ai non seulement renforcé mes connaissances en programmation, mais j'ai aussi appris à gérer un projet en toute autonomie. Ce stage a été une étape clé dans ma formation, et m'a conforté dans mon choix de carrière dans le domaine du développement informatique.
