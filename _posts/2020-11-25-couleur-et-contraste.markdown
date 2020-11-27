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

Première porte ouverte : les couleurs sont partout sur le web.

Deuxième porte ouverte : Ce sont les couleurs, entre autres, qui permettent de transmettre des messages aux utilisateurs.

Ces dernières peuvent par exemple : 
- Vous indiquez que vous avez bien ou mal rempli un formulaire et vous mettre en évidence les éléments à modifier.
- Mettre en valeur une publicité (ahhhh le web et la pub...) ou une offre promotionnelle.


## 2. Perception des couleurs et public visé.

Ok, maintenant que vous en savez un peu plus sur les notions de couleur et constrate, nous allons nous parler un peu des publics visés.

Avant de toute chose, voici une vérité : il est très très fortement problable que vous connaissiez quelqu'un souffrant d'une déficience visuelle.

Bien entendu, cette dernière peut être plus ou moins grave. En effet, on a souvent tendance à penser aux maladies les plus graves comme les glocommes ou les personnes aveugles. Le daltonisme est, par exemple, l'une des formes les plus répandues et pourtant c'est une aussi des moins bien prises en compte côté accessibilité.

Il est très fréquent que des publics souffrant d'une forme plus ou moins grave de daltonismes ne puissent pas pleinement profiter d'un service.

exemple d'un certicode : 


Mais il y a aussi autre chose : le sens des couleurs et le message qu'elles transmettent.


## 3. Les bons outils de derrière les fagots à connaître

### 3.1. Le site [Constrat Ratio](https://contrast-ratio.com/)

Vous souhaitez un outil rapide et facile pour mesurer le contraste ou alors vous souhaitez challenger votre designer en lui montrant que son contraste n'est pas bon, cet outil est fait pour vous.

Grâce à ce site, vous pouvez rapidement mesurer le niveau d'accessibilité de votre contraste. 

J'ai fait le test : je suis allé sur Github et j'ai regardé le niveau de contraste du bouton "Sign In for Github".

![Choix d'une déficience visuelle depuis le storybook](/assets/blog-post-contrast/github-normal-cta.png){:class=""}


Et voilà le résultat sur le site.

![Choix d'une déficience visuelle depuis le storybook](/assets/blog-post-contrast/constrat-ratio.png){:class=""}



### 3.2. L'extension [sdsd]()


## 4. Le petit plus : le Storybook

Je n'ose pas terminé ce post sans vous présenter cet outil : le  [Storybook](https://storybook.js.org/).
Cet outil, c'est un peu le bazooka côté développement front-end :
- Les développeurs peuvent l'utiliser lorsqu'ils intégrent les maquettes. Je trouve que le code a en plus tendance à être beaucoup plus clean.
- Les designers peuvent le consulter pour vérifier que les maquettes ont bien été intégrées.
- Le produit et le QA peuvent s'en servir pour vérifier que les comportements ont bien été respectés.

Grâce au storybook, vous pouvez tendre vers un site qui est le plus pixel perfect possible et qui évite toutes les mauvaises surprises que vous pouvez avoir dans un processus de développement côté front. Je reviendrais prochainement sur tous les avantages du Storybook en vous donnant mon retour d'expérience dessus.

Mais pour l'instant, on va se concentrer sur la partie accessibilité du storybook.

Un peu plus haut dans cet article, j'ai mentionné des extensions que vous pouviez installer pour vous aider avec le contraste. Grâce à Storybook et quelques extensions, vous n'avez plus forcément besoin de passer par ces dernières. Alors, certes, Vous allez avoir besoin d'installer quelques extensions complémentaires mais ces dernières vont vous permettre de simuler des déficiences visuelles et de voir en live si votre contraste est suffisant.

![Choix d'une déficience visuelle depuis le storybook](/assets/blog-post-contrast/storybook-choice.png){:class=""}

Ci-dessus : l'extension permettant justement de choisir la déficience visuelle que vous souhaitez tester. La bonne nouvelle côté produit ou design, c'est que tout est directement intégré à cet outil. Il n'y a pas d'installation compliqué à réaliser.


![Choix d'une déficience visuelle depuis le storybook](/assets/blog-post-contrast/storybook-example-1.png){:class=""}

![Choix d'une déficience visuelle depuis le storybook](/assets/blog-post-contrast/storybook-example-2.png){:class=""}

Ci-dessus : j'ai simulé de deux maladies. Comme vous pouvez le constater, cela n'a rien de très compliqué une fois les extensions installées et réglages réalisées.


## 5. Le plein de ressources

Voilà, vous arrivez au terme de ce blog post. Comme pour la dernière fois, je vous ai préparé quelques ressources complémentaires pour aller un peu plus loin sur le sujet :

- **EN** - [Une ressource particulièrement complète sur l'accessibilité et le contraste.](https://webaim.org/articles/contrast/)
- **EN** - [L'essentiel à retenir en moins 200 mots](https://a11y-101.com/design/contrast)
- **EN** - Plutôt destiné aux designeurs, [cet article](https://xd.adobe.com/ideas/principles/web-design/color-contrast-considerations-accessibility-design/) permet d'aller plus loin sur l'intégration de l'accessibilité dans son design.

Merci pour votre lecture.

Le prochain article sera entièrement consacré au Storybook. Je vous montrerais comment en paramétrer un, quels problèmes j'ai déjà pu rencontrés et quelles extensions installées pour l'accessibilité.

À bientôt !
