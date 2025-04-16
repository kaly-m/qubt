---
title: Développement sur STM32
subtitle: "À bas l'obsolescence ! :lightning:"
summary: L'obsolescence est un sujet controversé dans le monde de l'informatique. Une nouveauté peut se faire éclipser par une autre en l'espace d'un instant, tandis que des produits robustes ont su quant à eux, évoluer avec leur temps..

date: 2025-04-15
cardimage: HC11.JPG
featureimage: HC11.JPG
caption: "Microcontrôleurs MC68HC11"
---

## Contexte 

L'**obsolescence** est un sujet controversé dans le monde de l'informatique. En effet, d'un côté, les **avancées technologiques** sont telles qu'une nouveauté peut se faire éclipser par une autre en l'espace d'un instant. D'un autre côté, il existe des produits **robustes** qui ont su évoluer avec leur temps. Ces produits dits "robustes" ne sont cependant pas à l'abri d'un **arrêt de production** si l'entreprise n'en trouve plus l'utilité.

C'est le cas du **microcontrôleur** MC68HC11. Ce microcontrôleur a vu le jour dans les années 1980 / 1990. Produit par Motorola à ses débuts, il a ensuite été racheté par de nombreuses entreprises pour finir entre les mains de NXP Semiconductors. NXP a cependant annoncé la fin de production de ce microcontrôleur en **juin 2022**. Cela le rend donc indisponible à la vente.

Cette annonce à surement dû bouleverser plus d'une entreprise, l'une d'entre elles, dénommée HORIBA, possédait en effet plusieurs machines en production avec le microcontrôleur MC68HC11 sur leurs cartes. Cette problématique à donc constitué le sujet de mon stage de seconde année de BUT Informatique. Stage durant lequel j'ai du effectuer le développement d'une solution de remplacement du MC68HC11 sur le Pentra 80 (un automate produit par HORIBA).

La solution de remplacement choisie est le STM32, et plus précisément, le modèle G0B1RE. Il a fallu donc porter du code assembleur vers du code en C, le tout avec des problématiques microélectroniques. En effet, développer une solution de remplacement nécessite de coller à l'existant. Le STM32 étant nettement plus performant qu'un HC11, il a fallu le brider pour obtenir les mêmes performances.

Ce projet a été réalisé dans un **cadre professionnel** sur une durée de **10 semaines** (mi-janvier / mars). J'ai pu travailler tout du long de mon stage avec mon maître de stage, Christophe Domergue, avec l'équipe de développement embarqué ainsi qu'avec l'équipe d'électroniciens. De ce fait, j'ai pu aborder plusieurs aspect d'un point de vue métier (Développement / Microélectronique).

## Méthodes de travail

Concernant les méthodes de travail, nous travaillons selon des **points hebdos** réalisés chaque semaine avec l'équipe de **développeurs embarqués**. Ces points hebdos consistaient à tenir informé l'équipe des **avancements** de chacun ainsi qu'a **mettre en commun** pour **prendre du recul** sur les projets nécessitant du **soutien**.

{{< figArray subfolder="images" figCaption="Environnement de laboratoire" >}}

Comme vu sur la figure ci-dessus, l'environnement de travail était un **environnement de laboratoire**. HORIBA développe des **automates d'analyse sanguine**, les tests étaient donc réalisés dans l'environnement adéquat avec le port de la **blouse** et des **gants** en nitrile.

Le projet à été versionné via le **GitLab** de l'entreprise, RedLab.

## Compétences travaillées

Durant ce projet j'ai pu développer mes compétences en **C** mais aussi en **microélectronique**.

J'ai notamment dû : 
- Développer du bas niveau, savoir s’interfacer avec une machine en C.
- Optimiser la gestion de la mémoire ainsi que le fonctionnement du code.
- Concevoir en prenant en compte les contraintes logicielles mais aussi les contraintes matérielles.
- Développer sur STM32.
- Développer avec registres.
- Appréhender un environnement électronique ainsi que souder des composants sur une carte.

 Ce projet fut très enrichissant de par les nombreuses compétences abordées. En effet, deux perspectives métiers ont été abordées durant ces 10 semaines ainsi qu'une toute nouvelle technologie pour ma part : STM32.

 Pour plus d'informations concernant le projet réalisé ↴.

 <center>
 <a href="Rapport_de_Stage-HORIBA.pdf" download style="
   display: inline-block;
   padding: 12px 24px;
   background-color: #5d6d7e;
   color: white;
   text-decoration: none;
   border-radius: 6px;
   font-weight: bold;
   font-family: sans-serif;
 ">
   📥 Télécharger mon rapport de stage
 </a>
 </center>