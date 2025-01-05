---
title: Recoder Discord en C ?
subtitle: "Avoir un serveur privé ça en jette ! :dizzy:"
summary: J'ai toujours trouvé ça frustrant que peu importe la méthode utilisée, nos discussions sont écoutées. J'ai alors créé mon propre serveur privé où je pourrai communiquer avec les personnes concernées sur une connexion sécurisée... par moi même.
date: 2024-11-10
cardimage: discord.jpg
featureimage: discord.jpg
caption: "Discord Or Noir"
---

## Contexte

J'ai toujours voulu avoir mon propre système de **communication**. En effet, de nos jours, peu importe le mode de communication (informatique) employé, les **données** sont susceptibles d'êtres **écoutées** ou **réutilisées** par une personne tierce. Suite à un exercice académique optionnel qui consistait à développer un chat **broadcast** simple en C, j'ai décidé de poursuivre dans l'idée pour créer mon propre **serveur privé**.

J'ai alors développé le serveur seul en essayant de suivre les **bonnes pratiques** pour rendre cela **professionnel**. Des fonctionnalités ont été rajoutées comme des refacto ont eu lieu et petit à petit le projet prend forme. Il n'est actuellement pas terminé, il y a toujours quelque chose à rajouter dans ce genre de projets assez conséquents, mais il est en **bonne voie**.

## Méthodes de travail

**Internet** est mon ami, mais le **cours** aussi. En effet, pour réaliser ce projet, j'avais non seulement Internet, mais aussi le support de cours car le projet pars à la base d'un **exercice** qui consiste à manipuler les **sockets** TCP en C. J'ai donc parcouru toutes les ressources mises à ma disposition pour trouver les informations qu'il me fallait. 

Durant ce projet, j'ai pu travailler avec le logiciel de versionning tant connu : **GIT**. Je travaille donc via des **branches spécifiques** qui ont chacune leur utilité comme une branche réfacto, une branche dev, une branche feature/... par fonctionnalité développée, les **bonnes pratiques** de git.

Pour ce qui est des **tests**, je me contente d'opérer des tests dans le **terminal** et de regarder les erreurs qui se créent pour pouvoir les **corriger**, je n'hésite pas à faire tester l'application par des **personnes tierces** qui font souvent des actions différentes de celles que je fais et qui me permettent d'avoir un autre **angle de vue** quant à son utilisation.

## Compétences travaillées

{{< figArray subfolder="images" figCaption="Fonction de filtrage des pseudos" >}}

Durant ce projet j'ai pu développer mes compétences en **C** mais aussi en compréhension du fonctionnement des **sockets** via les **protocoles TCP/IP**.

J'ai notamment dû :
- Manipuler les sockets en C
- faire du multithreading pour le serveur et le client
- développer une gestion des signaux pour ne pas faire planter le serveur
- manipuler le logiciel de versionning GIT(LAB)

Tout du long, j'ai essayé d'implémenter l'entièreté de ce que nous avons vu durant nos cours en C dans mon projet. Cela m'a permis de faire une grosse **révision** et un bon point sur toutes ces **compétences** qui sont maintenant **acquises**. Cela m'a aussi permis de les utiliser dans un cadre **personnel, concret** et non dans un cadre académique comme on a l'habitude de le faire.