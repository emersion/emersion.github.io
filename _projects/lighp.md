---
title: "Lighp"
subtitle: "Un peu plus qu'un framework web."
date: 2015-01-24 22:22:11
category: computing
website: https://github.com/lighp/lighp
excerpt: "Lighp est un petit framework web, dont le but principal est la simplicité. Il est également doté d'un gestionnaire de paquets et d'une interface d'administration efficace."
---

Le projet est un petit framework web, d'où son nom (Lighp pour Light PHP : quand on n'a pas d'inspiration...).

Son but premier reste la simplicité, il donc donc été inspiré du mini-framework du tutoriel sur la POO en PHP : un framework pour débutants est forcément le plus simple possible. Il a néanmoins subi quelques modifications mineures, mais dans l'ensemble le fonctionnement reste le même. Le wiki pourra apporter une aide précieuse a ceux qui voudront en savoir plus sur le projet (de l'installation au fonctionnement interne, en passant par des exemples de modules).

Lighp est en effet doté d'un système de paquets (une sorte de logithèque), comme sur la plupart des systèmes GNU/Linux. Non seulement les modules comme un portfolio ou une page de contact sont mis dans les dépôts, mais aussi tout le reste du framework. Cela permet de gagner énormément en flexibilité et en sécurité. Certains paquets sont déjà disponibles (par ex. un portfolio et une page de contact), d'autres sont a venir prochainement. A l'avenir, Lighp devra fonctionner un peu comme Archlinux : rien d'installé par défaut, a part le strict minimum, et chacun ajoute ce qu'il souhaite et configure comme il veut.

Une deuxième fonctionnalité de Lighp est son espace d'administration simple et fonctionnel. Tout est découpé en actions (créer un article, modifier une news...), regroupées par modules (blog, portfolio...). Leur accès est accéléré par une possibilité de filtrage sur toutes les actions disponibles.

Autre particularité : il est possible de choisir ce qui va être stocké dans une base de données, dans des fichiers JSON ou autre. Le module du portfolio ne supporte pour l'instant que JSON, mais le reste viendra en temps voulu. La traduction du site est également aisée : des fichiers YAML contiennent les différents textes.

Dernier point : Lighp s'appuie sur des outils puissants comme le système de templates Mustache et le fameux Twitter Bootstrap.

Le tout est (bien sûr !) sous licence libre GPLv3. Voici le lien Github : [http://github.com/lighp/lighp](http://github.com/lighp/lighp).

Ce projet se distingue vraiment des autres frameworks : ce n'est pas une usine a gaz (la bibliothèque interne est relativement pauvre, considérant que celle de PHP est déjà suffisamment riche ; tous les modules sont facilement installables et désinstallables ; par défaut il n'y a que le strict minimum). Son organisation n'est sûrement pas parfaite, mais vraisemblablement suffisante pour arriver a rester simple mais fonctionnelle (contrairement a certains frameworks qui ont des milliards de dossiers et sous-dossiers...). Ce but de simplicité est central : le framework doit pouvoir être contrôlable par un codeur en peu de temps. La flexibilité est aussi très importante : le framework doit pouvoir s'adapter à à peu près tous types de sites web.

Le but du projet n'est pas lucratif, il restera gratuit et libre.

Le but n'est pas de concurrencer les gros frameworks comme Symphony ou Cake PHP, mais d'offrir une alternative simple a taille humaine. Et aussi : _just for fun_ !