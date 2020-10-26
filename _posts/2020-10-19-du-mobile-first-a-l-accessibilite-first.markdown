---
layout: post
title:  "Du Mobile First à l'Accessibility First"
date:   2020-10-19 18:00:00 +0100
---


Bonjour à tous et bienvenue sur le premier post de mon blog dédié à l'accessibilité web. J'avais envie depuis pas mal de temps de créer ce blog **pour pouvoir partager et vulgariser mes connaissances autour de l'accessibilité**.

J'ai récemment réalisé deux MOOCs avec [OpenClassrooms](https://openclassrooms.com/) dédié à l'accessibilité (ça, c'est pour la partie auto-promotion et self branding) et je me suis dit que c'était le bon moment pour se lancer.

**Pour ce premier post**, je ne vais pas réellement rentrer dans le concret mais m'intéresser à **théoriser un concept** qui me tient à coeur. Cela dit, dès le prochain post, on rentrera dans le vif du sujet et je vous parlerais de contraste.


## 1. L'influence du Mobile First dans la culture web

Bon, je pense que la majeure partie d'entre vous connaisse le concept de Mobile First et des idées véhiculées par ce concept. D'ailleurs, même si vous n'êtes pas développeur, mais chef de projet ou designer, les concepts de Mobile first et de Responsive Web Design ne vous sont sûrement pas étrangers.

Pour faire simple, le Mobile First est un concept qui est né il y a maintenant quelques années (en 2011 par Luke Wroblewski selon les internets) avec l’essor du web sur smartphone.

L'idée étant de dire que **les concepteurs de site web**, qu'ils ou elles soient designers ou développeurs, **doivent penser la conception mobile dès le début d'un projet et non essayer de l'adapter en cours de route**. Autrement dit, cela veut dire concevoir et créer la version mobile, puis concevoir et créer la version desktop : les usages de ces supports étant foncièrement différents.

D'ailleurs, côté code, on va d'abord développer la version mobile, qui est souvent plus simple en terme de "layout". Puis, on va adapter le côté, notamment la partie CSS, pour la partie desktop. Cette dernière étant souvent plus complexe que le mobile en terme de layout.

**En  bref : l'expérience utilisateur doit donc être optimal et native aussi bien sur mobile que sur tablette et desktop**. À aucun moment, l'utilisateur ne doit se sentir freiné par des défauts de conception.


## 2. L'accessibilité web

Si vous êtes en train de lire ce post, c'est certainement, du moins je l'espère, parce que vous souhaitez en apprendre plus sur l'accessibilité web. Cela dit, il est possible que ce terme soit encore un peu nébuleux. Alors, concrètement, qu'est-ce que ça veut dire ?

Selon [Wikipedia](https://fr.wikipedia.org/wiki/Accessibilit%C3%A9_du_web), "***L'accessibilité du web est la problématique de l'accès aux contenus et services web par les personnes handicapées (déficients visuels, sourds, malentendants, etc.) et plus généralement par tous les utilisateurs, quels que soient leurs dispositifs d’accès (mobile, tablette, etc.) ou leurs conditions d’environnement (niveau sonore, éclairement, etc.).***"

Je vous invite vraiment à lire l'article en entier sur Wikipedia. Je pense qu'on peut difficilement faire plus complet comme définition dans le sens où elle permet de comprendre que :
- Oui, l'accessibilité web permet aux utilisateurs souffrants de déficiences visuelles ou de motricité d'utiliser votre site comme tout le monde.
- Non, l'accessibilité web ne se résume pas qu'aux utilisateurs souffrants d'handicapes. Les populations étrangères, des réfugiés par exemple, peuvent souffrir de freins à l'accessibilité.
- Oui, il est certainement probable que vous ayez déjà bénéficié de ces technologies pour votre utilisation personnelle sans en avoir conscience. Par exemple, en affichant les sous-titres d'une vidéo.

**En bref, l'accessibilité web, c'est permettre que votre site web soit utilisable et consultable par tous les utilisateurs du monde entier, quel que soit leur pays, leur langue et leurs contraintes**. Selon moi, l'accessibilité est l'un des principes les plus importants du web.


**Il existe aujourd'hui deux canaux de communication liés à l'accessibilité : le contenu et la technique.**

- L'accessibilité par le contenu correspond tant aux textes qui composent votre site qu'à son design. C'est un sujet très vaste qui comprend aussi la typographie, les couleurs utilisés, les textes, les vidéos, etc. C'est ce qui rend votre site unique et c'est ce pour quoi les visiteurs vont sur votre site.
- L'accessibilité par la technique permet de communiquer ces informations aux technologies d'assistances. Je ne vais pas trop m'étendre dessus, je ferais un post dédié à ça prochainement. Si vous souhaitez en savoir plus dès à présent, vous trouverez en bas de ce post des liens vers de la doc.


## 3. Le Mobile First et l'Accessibiliy First

Mais alors pourquoi avoir parlé de Mobile First en premier puis d'accessibilité après ? Quel est le rapport entre ces deux éléments ? C'est le moment de raccrocher les wagons !

**En fait, le Mobile First part d'une contrainte : concevoir dès le début un site utilisable aussi bien sur smartphone que sur ordinateur sans niveler l'expérience utilisateur vers le bas. La même chose peut être réalisée avec l'accessibilité.**

Bien souvent l'accessibilité n'est prise en compte qu'à la fin d'un projet et non dès le début. Le plus souvent, le site a déjà été mis en production et a ses premiers utilisateurs et on essaye d'ajouter une démarche d'accessibilité au forceps.

Il en résulte des expériences déceptives et dégradées qui donnent une mauvaise image de l'accessibilité. Ce défaut de démarche d'accessibilité n'est pas fait sciemment par les équipes mais est plus dû à un manque de connaissances sur le sujet.

Or, intégrer une démarche d'accessibilité dans la conception d'un site n'est pas aussi compliqué que cela en a l'air. Il y a quelques connaissances à avoir certes mais il existe des ressources pour vous former !

En fait, plus tôt vous intégrez une démarche accessible dans votre site, plus les gains de productivité et les impacts sur l'accessibilité seront importants Votre site pourra donc être utilisable quel que soit le support et par n'importe qui. Imaginez l'audience à laquelle vous allez pouvoir vous ouvrir en réalisant un site accessible.

**Si nous, concepteurs de site, avons été capable de mettre en place le principe du Mobile First et de le suivre, il est tout à fait réalisable de faire pareil pour l'accessibilité. Mieux même, il est tout à fait possible de réaliser des expériences riches et complexes tout en restant accessible.**


## 4. Le plein de ressources

Avant de conclure, voici quelques ressources qui vont vous permettre d'aller un peu plus loin sur le sujet :

- Mon MOOC sur l'accessibilité côté **contenu** : [Concevez un contenu web accessible](https://openclassrooms.com/fr/courses/6691346-concevez-un-contenu-web-accessible)
- Mon MOOC sur l'accessibilité côté **code** : [Codez un site web accessible avec HTML & CSS](https://openclassrooms.com/fr/courses/6691451-codez-un-site-web-accessible-avec-html-css)
- Ce livre commence à dater un peu (notamment sur la partie JavaScript) mais peut valoir le coup (disponible en anglais et en français) : [Adaptive Web Design](https://www.amazon.fr/Adaptive-Web-Design-Experiences-Progressive-ebook/dp/B018BI07OQ/ref=sr_1_3?__mk_fr_FR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=adaptive+web+design&qid=1603554862&sr=8-3)


Merci pour votre lecture.

Si vous avez une question, un feedback ou que vous voulez écrire un article ou proposer une ressource, n'hésitez surtout pas à me contacter par mail.

Le prochain article sera axé design et parlera des couleurs.

À bientôt !
