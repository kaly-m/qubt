---
title: Raspberry Pi 5
subtitle: "Un pied dans l'embarqué :zap:"
summary: Un raspberry Pi c'est quoi ? C'est un ordinateur portatif qui tourne sur une carte de circuit imprimé nous permettant de réaliser pas mal de petit projets intéressants, comme héberger un serveur web.
date: 2024-12-03
cardimage: raspbery.jpg
featureimage: raspbery.jpg
caption: Raspberry Pi 5
---

## Contexte

Ce projet est intimement lié au développement de mon [serveur en C](../post2/). En effet, mon **serveur** en C développé, il me fallait maintenant un moyen pour le **déployer** et le **rendre disponible** au "grand" public (constitué de mes camarades de classe). Je me suis alors renseigné. Lors de mes recherches, je suis tombé sur le **raspberry Pi**, ordinateur portatif qui semblait parfait pour faire aboutir mon projet. 

J'ai alors passé le cap et passé commande tout en continuant de m'**informer** sur les possibles utilisations de celui-ci. Je me suis alors rendu compte que le raspberry Pi était la porte ouverte pour les **systèmes embarqués**, discipline pour laquelle je suis tombé amoureux étant donné mon intéressement envers la robotique. Je tenais la ma porte d'entrée vers un métier qui semblait me correspondre : **Développeur Système embarqué**.

J'ai donc réalisé l'entièreté de ce projet **seul** étant donné que c'est un projet personnel qui s'est vu naître miraculeusement en poursuivant des recherches qui étaient à la base pour un autre projet. Je compte en faire un stockage externe accessible via Internet qui serait sensiblement identique à un **cloud storage**. J'ai récemment acheté un micro, qui va me permettre d'en faire un **assistant vocal** pour contrôler mes leds par la voix. Je trouve toujours une nouvelle utilisation pour mon raspberry Pi 5 et cela est **fascinant**.

## Méthodes de travail

{{< figArray subfolder="images" >}}
En l'occurrence, mon plus grand ami fut Internet. Mes seules connaissances sur le sujet étaient que je devais lui adresser une adresse **ip publique** si je voulais le rendre accessible. J'ai alors du chercher le reste en **autodidacte**. J'ai donc effectué des tests, répété certaines manipulations et j'ai fini par trouver ce qu'il me fallait.

## Compétences travaillées

Durant ce projet, j'ai beaucoup appris côté *hardware* et **protocoles de communication**.

J'ai notamment dû : 
- Flasher une carte sd avec raspberry PI OS dessus.
- Monter et installer le raspberry Pi 5, cela consiste à faire des branchements, installer la pate thermique, installer le ventilo, monter le boitier.
- adresser une adresse ip publique à mon raspberry Pi (j'ai rencontré des complications car mon FAI n'en fournissaient pas, j'ai du changer de FAI avant de pouvoir continuer mon projet..)
- Me connecter et manipuler mon raspberry via les commandes ssh (un peu d'administration système pour créer des users etc.).

Pour conclure, j'ai abordé de nombreuses compétences qui ne sont pas forcément vues dans ma formation. Ce projet m'a grandement enrichi et je ne compte pas m'arrêter là.