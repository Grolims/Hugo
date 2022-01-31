---
title: "L’accessibilité à quoi ça ressemble ?"
date: 2019-02-12T23:39:06-06:00
category: "test"
tags: [Accessibilité, Web, Jeu vidéo, application, développement]
toc: false
---

# L’accessibilité à quoi ça ressemble ?
Maintenant que nous avons déterminé ce qu’est l’accessibilité et quels en sont les bénéfices, il est temps de s’intéresser à comment la mettre en place.

## Sur le web
Sur le web l’accessibilité ne concerne pas uniquement les personnes présentant un handicap mais aussi les différentes plateformes mobiles, télévisions, montres connectées ou encore les connexions internet lentes ou ayant une bande passante limitée.


### Son et image
Il est important de savoir que les personnes malvoyantes utilisent, par exemple des lecteurs d’écran ou des liseuses en braille. Il est donc nécessaire de mettre en place des alternatives textuelle pour les images et les logos (attribut ARIA). Idem pour les fichiers audios pour les personnes malentendantes ou l’ajout d’une transcription textuelle est nécessaire. De plus tous les champs du site web doivent être décrits afin d’être retranscrits via un lecteur de site.

### Structure
La mise en place du site doit être structurée de manière sémantique avec les bons titres (h1 h2) ainsi que des listes ou des lignes, colonnes pour les tableaux et des labels pour les formulaires. Dans le but de faciliter le parcours du site avec un lecteur d’écran.

### Saisie au clavier
Certains handicaps moteurs empêchent les personnes de naviguer de manière conventionnelle sur un site ou une application web, il est donc essentiel que le site soit complètement navigable au clavier.

### Contraste
Il est très important que le contenu textuel soit lisible et facilement compréhensible. Le but est de jouer sur les contrastes afin de distinguer les différents contenus du site, par exemple une bonne synergie de couleur de texte / couleur de fond, un contraste pour le texte sur des images et une reconnaissance des liens (souligné, avec un changement de pointeur).

### Récapitulatif
Afin de se rappeler les points principaux de l’accessibilité sur le web, voici cinq grandes catégories qui doivent être respectées et appliquées dans le développement d’un site web le principe P.O.U.R:

* **Perceivable:** les informations doivent être présentées afin d’être visibles pour chaque utilisateur.
* **Operable:** tous les utilisateurs doivent être capables de naviguer sur le site.
* **Understandable:** les informations et le fonctionnement de l'interface utilisateur doivent être facilement compréhensibles (lisibilité, prévisibilité et aide à la saisie).
* **Robust:** le contenu doit être adapté pour de nombreuses technologies (smartphone, lecteur écran, tv).
* **Conformance:** le contenu doit toujours être accessible malgré l’évolution des technologies, par exemple compatibilité avec les technologies d’assistance.

D’autre recommandations plus spécifiques sont disponibles sur le site du W3C dans le document « [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)»


## Dans les jeux vidéo
Pour les jeux vidéo c’est plus difficile, malgré l’existence de sites comme « Can in play that » qui fournit des guides articles et témoignages sur l’accessibilité dans jeux vidéo. L’accessibilité dans les jeux n’est pas autant normée que sur le web. Il existe cependant un guide sur lequel je vais m’appuyer pour cet article, les « [Game accessibility guidelines](https://gameaccessibilityguidelines.com/) »

### Son et image
Ce sont des recommandations similaires que celles misent en place pour les sites web. Les contrastes, la taille de la police visible et aucune information essentielle transmise seulement par l’image ou le son, notamment pour les éléments qui demandent une interaction. La mise en place de sous-titres et de gestion de volume séparée est aussi nécessaire.

### Contrôle
En plus des traditionnels claviers et souris, certains jeux se jouent via une manette, ce qui n’est pas nécessairement accessible et simple à utiliser pour tout le monde. Il est donc nécessaire de pouvoir reconfigurer les touches et la sensibilité des commandes avec la prise en charge de plusieurs dispositifs d’entrée (périphériques de jeux spécifiques pour certains handicaps moteurs).

### Cognitive
L’aspect cognitif dans un jeu est plus important que sur un site web, pour cette raison, certaines règles doivent être obligatoirement appliquées comme la mise en place de tutoriel pour apprendre les mécaniques du jeu et l’affichage de différents astuces, aides et conseils pendant la durée de la partie. Mettre en place un moyen de s'entraîner sans échec comme un mode entrainement est également recommandé.

## Bien appliqué ?
Pour les jeux vidéo nous reviendrons plus en détail dans un [article spécifique]({{< ref "/post/article 4" >}} "art4") qui démontre l’évolution de l’accessibilité et comment elle est appliquée de nos jours dans les grandes licences.

Concernant le web ce n’est pas encore ça, en Suisse pour 20% de la population l’utilisation d’internet est limitée et de nombreux sites restent difficiles d’accès comme le montre l’étude sur « L’accessibilité des boutiques en ligne » réalisée en 2020 par l’association « Accès pour tous » en partenariat avec la Confédération suisse (bureau fédéral de légalité). L’examen était basé sur les lignes directrices internationalement acceptées pour les contenus Web accessibles [WCAG 2.1](https://www.w3.org/TR/WCAG21/).

Seulement 10 boutiques sur 41 sont totalement accessibles pour les personnes en situation de handicap et 14 boutiques en ligne, soit 34 %, excluent totalement les personnes handicapées de l’utilisation. 

Les problèmes récurrents sont :

* L’utilisabilité du clavier pour naviguer sur le site où différentes catégories ne sont plus accessibles et certaines options seulement applicables avec la souris.
 
* L’assistance aux interactions avec des informations de retour non accessibles pour les saisies incorrectes de formulaires.
 
* Le contenu non textuel images ou logos ne possède pas de texte alternatif.

### Conclusion
Malgré des règles spécifiques bien règlementées, on peut voir que l’accessibilité n’est pas une préoccupation majeure des différents sites de vente en ligne. Il est préoccupant de constater que de nombreux site sont difficiles, voire impossibles d’accès pour des personnes présentant un handicap. J’espère que grâce à ce genre d’étude les différents acteurs seront sensibilisés et prendront conscience de cette problématique afin de mettre en place les outils nécessaires dans le but de donner accès aux ressources numériques pour tous, indépendamment du handicap physique, mental ou sensoriel.



Sources : 

[Etude suisse sur l'accessibilité](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiZpZvY48j1AhUBhP0HHT3-DV4QFnoECAUQAQ&url=https%3A%2F%2Fwww.access-for-all.ch%2Fimages%2FAccessibilty_Studie%2F2020%2Fzfa-studie-onlinehopping-2020-f-web.pdf&usg=AOvVaw2QqJtrE2W_SQ_o87UEnYgO)

[WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/)

[Accessible design](https://www.nngroup.com/articles/accessible-design-for-users-with-disabilities/)
