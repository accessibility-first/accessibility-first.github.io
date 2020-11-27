---
layout: post
title:  "Couleur et constrate"
date:   2020-11-20 11:00:00 +0100
---

Avant mon prochain blog post qui sera accès beaucoup plus tech et développement, j'ai décidé de consacrer l'actuel au design et plus particulièrement au contraste.

En effet, c'est un peu l'un des premiers sujets à connaître niveau accessibilité et c'est aussi l'un des plus simples à appréhender. Pourtant, je suis toujours étonné de voir des designers qui ne prennent pas en compte ces best practices.

Cela me semble tellement essentiel et tellement basique que je trouve assez logique de l'aborder le plus tôt possible.
Ainsi, vous n'aurez plus d'excuses pour bien gérer le contraste dans vos projets !


## 1. Couleur et constrate : les généralités.

## 2. Perception des couleurs et public visé.

## 3. Les bons outils de derrière les fagots à connaître

### 3.1. [Constrat Ratio](https://contrast-ratio.com/)


## 4. Le petit plus : le Storybook

Je n'ose pas terminé ce post sans vous présenter cet outil : le  [Storybook](https://storybook.js.org/).
Cet outil, c'est un peu le bazooka côté développement front-end :
- Les développeurs peuvent l'utiliser lorsqu'ils intégrent les maquettes. Je trouve que le code a en plus tendance à être beaucoup plus clean.
- Les designers peuvent le consulter pour vérifier que les maquettes ont bien été intégrées.
- Le produit et le QA peuvent s'en servir pour vérifier que les comportements ont bien été respectés.

Grâce au storybook, vous pouvez tendre vers un site qui est le plus pixel perfect possible et qui évite toutes les mauvaises surprises que vous pouvez avoir dans un processus de développement côté front. Je reviendrais prochainement sur tous les avantages du Storybook en vous donnant mon retour d'expérience dessus.

Mais pour l'instant, on va se concentrer sur la partie accessibilité du storybook.

Un peu plus haut dans cet article, j'ai mentionné des extensions que vous pouviez installer pour vous aider avec le contraste. Grâce à Storybook et quelques extensions, vous n'avez plus forcément besoin de passer par ces dernières. Alors, certes, Vous allez avoir besoin d'installer quelques extensions complémentaires mais ces dernières vont vous permettre de simuler des déficiences visuelles et de voir en live si votre contraste est suffisant.

![Choix d'une déficience visuelle depuis le storybook](/assets/storybook-choice.png){:class=""}

Ci-dessus : l'extension permettant justement de choisir la déficience visuelle que vous souhaitez tester. La bonne nouvelle côté produit ou design, c'est que tout est directement intégré à cet outil. Il n'y a pas d'installation compliqué à réaliser.


![Choix d'une déficience visuelle depuis le storybook](/assets/storybook-example-1.png){:class=""}

![Choix d'une déficience visuelle depuis le storybook](/assets/storybook-example-2.png){:class=""}

Ci-dessus : j'ai simulé de deux maladies. Comme vous pouvez le constater, cela n'a rien de très compliqué une fois les extensions installées et réglages réalisées.


## 5. Le plein de ressources

Voilà, vous arrivez au terme de ce blog post. Comme pour la dernière fois, je vous ai préparé quelques ressources complémentaires pour aller un peu plus loin sur le sujet :

Merci pour votre lecture.

Le prochain article sera entièrement consacré au Storybook. Je vous montrerais comment en paramétrer un, quels problèmes j'ai déjà pu rencontrés et quelles extensions installées pour l'accessibilité.

À bientôt !
