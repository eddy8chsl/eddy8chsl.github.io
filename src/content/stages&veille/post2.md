---
title: "Stage de deuxième année - BTS SIO | Casier Judiciaire National"
description: "Stage de dexième année en BTS SIO, réalisé au sein du pôle informatique du Casier Judiciaire National, situé à Nantes"
pubDate: "Apr 18 2025"
heroImage: "/casier_judiciaire.webp"
tags:
  [
    "PHP 8.3",
    "HTML 5",
    "CSS 3",
    "Laravel 12",
    "JavaScript 8",
    "Tom Select",
    "TailwindCSS 3",
    "Boostrap 5",
    "LiveWire",
    "Pest",
    "Playwright",
    "Laragon 7",
    "NGINX 1.27",
    "Debian 12",
    "PostgreSQL 17.2",
    "DBeaver 25",
    "Visual Studio Code",
    "GitLab 17",
    "Windows 10",
  ]
---

Pour ma deuxième année de BTS SIO, j'ai réalisé un stage de 7 semaines. Pour cette seconde expérience professionnelle,
j'ai intégré le _Casier Judiciaire National_, une institution gouvernementale situé à Nantes, au sein du pôle assistance technique et fonctionnelle (PATF).

**Qu'est-ce que le Casier Judiciaire National ?**

Cette organisme est en charge de la gestion du casier judiciaire en France. Il centralise et conserve les condamnations pénales et certaines décisions de justice concernant les personnes physiques et morales.
Celle-ci enregistre les condamnations pénales, certaines décisions administratives et judiciaires, ainsi que les interdictions légales prononcées par les tribunaux.

---

Dans le cadre de mon stage au PATF du _Casier Judiciaire National_, j'ai eu pour mission, d'optimiser le processus d’authentification de l’intranet de l’organisation, **Nova**. Concrètement, j’ai été chargé de concevoir un formulaire de demande permettant aux utilisateurs de l'intranet d'être reconnu par leur session windows(SSO), au lieu de saisir des identifiants spécifiques à **Nova**.
De plus, j'ai dû réaliser une fonctionnalité tier afin d’approuver ou de refuser ces demandes d’accès avec un tableau de bord, à l'équipe informatique du _Casier Judiciaire_.
Cette solution, nommée **Cerber**, permet alors de simplifier l'accès des agents à l'intranet en utilisant une solution plus adaptative et ergonomique.
Pour mener à bien ma tâche, j’ai dû appréhender un nouveau FrameWork PHP, Laravel.

**Qu'est-ce que Laravel ?**

Laravel est un framework PHP open-source, conçu pour le développement d’applications web structurées et évolutives. Il se repose notamment sur une architecture MVC (Modèle-Vue-Contrôleur) et propose un écosystème complet facilitant la gestion des bases de données, l’authentification, le routage et le rendu des vues. Son interface intuitive et ses nombreuses fonctionnalités intégrées, permettent d’optimiser le développement tout en garantissant une sécurité et une évolutivité adaptées aux exigences des projets web.

Également, afin de suivre mon avancement et celle de l'équipe, j'ai assisté chaque jeudi au réunion du PATF. Ces rassemblements permettent de suivre l’avancement de chacun et d’avoir une vision globale des projets en cours, notamment à travers des démonstrations techniques entre les développeurs et supports. Par la suite, au fur et à mesure de l’avancement de ma mission, j’ai eu l’occasion de participer à ces réunions en réalisant des démonstrations de mon projet, ce qui m'a permis de m'intégrer plus facilement au sein du pôle.

![trombinocospe](/trombinocospe.webp)

---

Pour ma première semaine de stage, n'ayant aucune expérience avec Laravel, mon maître de stage m'a laissé en totale autonomie pour découvrir le framework via [Laracasts](https://laracasts.com), une plateforme dédiée à l'apprentisage et à l'évolution de celui-ci. Grâce aux nombreux cours disponibles, réalisés par des développeurs passionnés, j’ai pu appréhender les bases de Laravel, notamment avec le podcast de Jeffrey Way : [30 Days to Learn Laravel](https://laracasts.com/series/30-days-to-learn-laravel-11).

Dans un premier temps, j'ai développé un premier projet afin de mieux appréhender les bases techniques de Laravel dont les policies, le CRUD (Create, Read, Update, Delete), les relations, les factories, les seeders, etc.

[**_Project Example_**](https://github.com/eddy8chsl/example.git)

![example index jobs](/example_index_jobs.webp)
![example create job](/example_create_job.webp)
![example show job](/example_show_job.webp)
![example edit job](/example_edit_job.webp)
![example login](/example_login.webp)
![example register](/example_register.webp)

Ensuite, j'ai réalisé un deuxième projet en Laravel. Mais, cette fois-ci, me concentrant principalement sur l'aspect graphique, en utilisant le CSS avec [Tailwind CSS](https://tailwindcss.com).

[**_Project Pixel-Position_**](https://github.com/eddy8chsl/pixel-position.git)

![pixel position](/pixel-position.webp)

**Qu'est-ce que Tailwind CSS ?**

Tailwind CSS est un framework CSS utilitaire qui permet de concevoir rapidement des interfaces modernes et réactives. Celui-ci n'impose pas de styles prédéfinis mais propose une multitude de classes utilitaires permettant de personnaliser entièrement le design sans écrire de CSS personnalisé. Cela facilite la création de designs responsifs et optimisés, en réduisant la quantité de code.

---

Ultérieurement, pour ma deuxième semaine, je me suis lancé dans la réalisation de ma mission donnée avec tout d'abord les fonctionnalités du CRUD. C'est-à-dire, une page dédiée à la création des demandes, à la visualisation des requêtes (tableau de bord) et leurs détails, ainsi qu'à la possibilité d'éditer et supprimer une requête spécifique.

**_Gestion du projet Cerber_**

![cerber gestion](/cerber_gestion.webp)

De plus, à côté de ma tâche pricipal, j'ai pu integrer un meilleur aspect graphique pour l'application avec [Bootstrap](https://getbootstrap.com), afin d'améliorer le rendu visuel.

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

![PI planning](/pi_planning.webp)

---

Par la suite, lors de ma quatrième semaine, avec mon maître de stage, nous avons mis en place un système de reconnaissance avec des sessions windows des agents. Cette solution permet, dans un premier temps, de vérifier si un agent a déjà soumis une demande de connexion. Et si cela est le cas, au lieu d’initier une nouvelle requête, il sera automatiquement redirigé vers la page récapitulative de sa demande existante.

![cerber recap](/cerber_recap.webp)

De plus, afin d'améliorer la fluidité de l'application, je me suis initié au [Livewire](https://laravel-livewire.com), une extension pour le framework Laravel.

**Qu'est-ce que LiveWire ?**

Livewire est un framework full-stack pour Laravel qui permet de créer des interfaces utilisateur dynamiques sans avoir besoin de JavaScript. Il permet de gérer des composants interactifs directement en PHP, en synchronisant les mises à jour de l'interface avec le serveur de manière fluide via AJAX (effectuer des requêtes sans avoir afficher une nouvelle page complète).

---

En continuant avec Livewire, lors de ma cinquième semaine de stage, j’ai pu optimiser la fluidité des requêtes au sein de mon projet **Cerber**.
Notamment en améliorant l’affichage de la disponibilité des cartes d’agents, dès qu'un agent met à jour son statut, inoccupé ou bien indisponible, son changement sera effectué sans le besoin nécessaire de recharger la page concernée.
De plus, j'ai bonifié le système de filtrage, permettant à l'équipe du PATF d’affiner leurs recherches plus rapidement.
Enfin, pour alléger l’affichage en cas de nombreuses demandes, j’ai intégré une pagination dynamique. Cela garantit ainsi une meilleure lisibilité et une navigation plus fluide au sein du tableau de bord.

![cerber pagination](/cerber_pagination.webp)

---

Ensuite, pour ma sixième et avant-dernière semaine de stage, j'ai ajouté une page dédiée à l'attribution des rôles auxquels la personne concernée aura accès sur l'intranet **NOVA**, lorsque celle-ci est acceptée par l'administrateur. Pour réaliser cette tâche, on m'a demandé d'expérimenter un framework JavaScript, jamais utiliser auparavant par l'équipe du PATF, [Tom Select](https://tom-select.js.org).

**Qu'est-ce que Tom Select ?**

Tom Select est une bibliothèque JavaScript qui améliore les éléments de liste déroulante (balise `<select>`) en les rendant plus interactifs. Elle offre des fonctionnalités avancées telles que la recherche en temps réel via des API, la sélection multiple d'éléments et l'ajout dynamique d'options. Son intégration améliore considérablement l'ergonomie des formulaires et des interfaces utilisateur.

Dans mon projet, j'ai cherché à établir une communication entre deux listes déroulantes : l'une contenant la liste des agents du _Casier Judiciaire_ et l'autre affichant les rôles d'accès à **Nova** (données en JSON). L'objectif est de mettre à jour automatiquement la liste des rôles associés à une requête lorsqu'un agent est sélectionné, afin d'attribuer et d'afficher les mêmes rôles en temps réel, avec la possibilité d'en ajouter ou d'en supprimer.

![cerber check](/cerber_check.webp)

---

Enfin, durant ma dernière semaine au sein du Casier Judiciaire National, j'ai été chargé d'effectuer des tests pour le projet **Cerber**, en utilisant notamment les technologies Pest (avec LiveWire) et Playwright.

**Qu'est-ce que Pest et Playwright ?**

Pest est un framework de tests conçu pour les applications PHP, facilitant la vérification du bon fonctionnement du back-end. Cette partie inclut la logique métier, la gestion des bases de données et les interactions côté serveur.
Playwright, quant à lui, est un outil destiné à tester l'interface utilisateur des applications web. Il permet d'automatiser des actions courantes telles que cliquer sur des boutons, remplir des formulaires ou naviguer entre les pages. Cela garantit la qualité et la fiabilité du front-end de l'application, grâce à la simulation.

Dans un premier temps, j'ai utilisé Playwright pour tester l'interface utilisateur de l'application. Cela implique la création d'une requête, sa visualisation sur le tableau de bord, puis son édition et, enfin, sa suppression, en suivant les étapes du processus CRUD. En complément, j'ai effectué un autre test, cette fois pour vérifier la disponibilité des agents.
Ensuite, Même déroulement avec Pest, mais cette fois du côté back-end, en vérifiant la gestion de mes tables "requêtes" ainsi que celle de "agents". Enfin, j'ai utilisé LiveWire Test, afin de réalisé des tests similaires couvrant à la fois le back-end et le front-end. Ces tests consistent à actionner un élément externe afin de vérifier l'affichage d'un élément sur l'interface utilisateur. Cette démarche a été particulièrement utile pour vérifier mon système de filtrage de mon tableau de bord.

![cerber playwright](/cerber_playwright.webp)
![cerber pest](/cerber_pest.webp)

---

Pour conclure, ce stage au _Casier Judiciaire National_ m'a offert une occasion précieuse de renforcer mes compétences en découvrant et en maîtrisant diverses technologies telles que Laravel, LiveWire, Tom Select, Playwright, et bien d'autres. De plus, cette expérience m'a offert l'opportunité de travailler dans un environnement unique, distinct de celui d'une entreprise classique, ce qui m'a permis d'appréhender des dynamiques professionnelles différentes et de m'adapter à un cadre de travail atypique.
