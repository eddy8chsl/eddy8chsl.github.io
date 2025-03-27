---
title: "Stage de deuxième année - BTS SIO | Casier Judiciaire National"
description: "Stage de dexième année en BTS SIO, réalisé au sein du pôle informatique du Casier Judiciaire National, situé à Nantes"
pubDate: "Apr 18 2025"
heroImage: "/casier_judiciaire.webp"
tags:
  [
    "PHP",
    "HTML",
    "CSS",
    "Laravel",
    "TailwindCSS",
    "Boostrap",
    "LiveWire",
    "Laragon",
    "NGINX",
    "PostgreSQL",
    "DBeaver",
    "Visual Studio Code",
    "GitLab",
  ]
---

Pour ma deuxième année de BTS SIO, j'ai réalisé un stage de 7 semaines. Pour cette seconde expérience professionnelle,
j'ai intégré le _Casier Judiciaire National_, une institution gouvernementale à Nantes.

**Qu'est-ce que le Casier Judiciaire National ?**

Cette organisme est en charge de la gestion du casier judiciaire en France. Il centralise et conserve les condamnations pénales et certaines décisions de justice concernant les personnes physiques et morales.
Celle-ci enregistre les condamnations pénales, certaines décisions administratives et judiciaires, ainsi que les interdictions légales prononcées par les tribunaux.

---

Dans le cadre de mon stage au pôle assistance technique et fonctionnelle (PATF) du _Casier Judiciaire National_, j'ai eu pour mission, d'optimiser le processus d’authentification de l’intranet de l’organisation, **Nova**. Concrètement, j’ai été chargé de concevoir un formulaire de demande permettant aux utilisateurs de l'intranet de s’authentifier avec leur Kerberos, l'identifiant des postes informatiques personnels des agents, au lieu des identifiants spécifiques à **Nova**.
De plus, j'ai dû réaliser une fonctionnalité tier afin d’approuver ou de refuser ces demandes d’accès avec un tableau de bord, à l'équipe informatique du _Casier Judiciaire_.
Cette solution, nommée **Cerber**, permet alors de simplifier l'accès des agents à l'intranet en utilisant une solution plus adaptative et ergonomique.
Pour mener à bien ma tâche, j’ai dû appréhender un nouveau FrameWork PHP, Laravel.

**Qu'est-ce que Laravel ?**

Laravel est un framework PHP open-source, conçu pour le développement d’applications web structurées et évolutives. Il se repose notamment sur une architecture MVC (Modèle-Vue-Contrôleur) et propose un écosystème complet facilitant la gestion des bases de données, l’authentification, le routage et le rendu des vues. Son interface intuitive et ses nombreuses fonctionnalités intégrées, permettent d’optimiser le développement tout en garantissant une sécurité et une évolutivité adaptées aux exigences des projets web.

Également, afin de suivre mon avancement et celle de l'équipe, j'ai assisté chaque jeudi au réunion PATF. Ces rassemblements permettent de suivre l’avancement de chacun et d’avoir une vision globale des projets en cours, notamment à travers des démonstrations techniques. Par la suite, au fur et à mesure de l’avancement de ma mission, j’ai eu l’occasion de participer à ces réunions en réalisant des démonstrations de mon projet.

---

Pour ma première semaine de stage, n'ayant aucune expérience avec Laravel, mon maître de stage m'a laissé en totale autonomie pour découvrir le framework via [Laracasts](https://laracasts.com), une plateforme dédiée à l'apprentisage et à l'évolution de celui-ci. Grâce aux nombreux cours disponibles, réalisés par des développeurs passionnés, j’ai pu appréhender les bases de Laravel, notamment avec le podcast de Jeffrey Way : [30 Days to Learn Laravel](https://laracasts.com/series/30-days-to-learn-laravel-11).

Dans un premier temps, j'ai développé un premier projet afin de mieux appréhender les bases techniques de Laravel dont les policies, le CRUD (Create, Read, Update, Delete), les relations, les factories, les seeders, etc.

**_Project Example_**

![example index jobs](/example_index_jobs.webp)
![example create job](/example_create_job.webp)
![example show job](/example_show_job.webp)
![example edit job](/example_edit_job.webp)
![example login](/example_login.webp)
![example register](/example_register.webp)

Ensuite, j'ai réalisé un deuxième projet en Laravel. Mais, cette fois-ci, me concentrant principalement sur l'aspect graphique, en utilisant le CSS avec Tailwind.

**_Project Pixel-Position_**

![pixel position](/pixel-position.webp)

**Qu'est-ce que Tailwind CSS ?**

Tailwind CSS est un framework CSS utilitaire qui permet de concevoir rapidement des interfaces modernes et réactives. Celui-ci n'impose pas de styles prédéfinis mais propose une multitude de classes utilitaires permettant de personnaliser entièrement le design sans écrire de CSS personnalisé. Cela facilite la création de designs responsifs et optimisés, en réduisant la quantité de code.

---

Ultérieurement, pour ma deuxième semaine, je me suis lancé dans la réalisation de ma mission donnée avec tout d'abord les fonctionnalités du CRUD. C'est-à-dire, une page dédiée à la création des demandes, à la visualisation des requêtes (tableau de bord) et leurs détails, ainsi qu'à la possibilité d'éditer et supprimer une requête spécifique.

**_Gestion du projet Cerber_**

![cerber gestion](/cerber_gestion.webp)

De plus, à côté de ma tâche pricipal, j'ai pu integrer un meilleur aspect graphique pour l'application avec Bootstrap, afin d'améliorer le rendu visuel.

**Qu'est-ce que Boostrap ?**

Bootstrap est un framework CSS open-source qui permet de créer des interfaces web réactives et attrayantes de manière rapide et efficace. Il fournit notamment une collection de composants préconçus (boutons, formulaires, cartes, menus, etc.) ainsi qu'un système de grille flexible pour organiser le contenu sur différentes tailles d'écran. Celui-ci est similaire à Tailwind CSS.

**_Formulaire utilisateur (public)_**

![cerber index](/cerber_index.webp)
![cerber create public](/cerber_create_public.webp)

**_Formulaire administrateur (avec Karberos, vu plus tard)_**

![cerber create](/cerber_create.webp)

![cerber tableau](/cerber_tableau.webp)
![cerber show](/cerber_show.webp)
![cerber edit](/cerber_edit.webp)

---

Ensuite, lors de ma troisième semaine, j'ai enrichi le système de gestion des demandes en ajoutant de nouvelles fonctionnalités visant à optimiser son utilisation. J'ai notamment développé une page dédiée à la gestion des disponibilités des agents informatiques, permettant de recevoir ou non les notifications par e-mail concernant les demandes d'accès. D'un autre côté, j'ai mis en place un filtre sur le tableau de bord, permettant de trier les demandes en fonction de leur degré d'urgence, du nom des demandeurs et de leur date de création.

![cerber agents](/cerber_agents.webp)

**_Filtrage par requête urgente et prénom par odre alphabétique_**
![cerber filter](/cerber_filter.webp)

Par ailleurs, j'ai également eu la chance d'assister à une réunion appelée PI PLanning au _Rubix_, une annexe du _Casier Judiciaire National_ qui travaille sur des projets nationaux et internationaux, notamment au niveau de l'Union Européenne, portés par le _Casier Judiciaire National_. Parmi ces projets figure **Astréa**, un logiciel permettant de référencer et de visualiser l’ensemble des documents judiciaires sur le territoire français.
Ce rassemblement permet à l'ensemble des équipes de synchroniser, planifier les travaux, identifier les risques et s'engager sur la réalisation d'un résultat commun jusqu'au prochain PI Planning qui à lieu tous les trois mois.

---

Par la suite, lors de ma quatrième semaine, avec mon maître de stage, nous avons mis en place un système de reconnaissance avec le Kerberos, l'identifiant des appareils informatiques des agents. Cette solution permet, dans un premier temps, de vérifier si un agent a déjà soumis une demande de connexion. Et si cela est le cas, au lieu d’initier une nouvelle requête, il sera automatiquement redirigé vers la page récapitulative de sa demande existante.

![cerber recap](/cerber_recap.webp)

De plus, afin d'améliorer la fluidité de l'application, je me suis initié au Livewire, une extension pour le framework Laravel.

**Qu'est-ce que LiveWire ?**

Livewire est un framework full-stack pour Laravel qui permet de créer des interfaces utilisateur dynamiques sans avoir besoin de JavaScript. Il permet de gérer des composants interactifs directement en PHP, en synchronisant les mises à jour de l'interface avec le serveur de manière fluide via AJAX.

---
