##Accessibilité et utilisabilités : astuces d'intégrateur pour webdesigners *Véronique Lapierre*
Pourquoi s'occuper d'accessibilité ? Elle ne concerne pas que les personnes handicapées pour qui elle est _**indispensable**_ mais elle peut concerner tous les utilisateurs à qui elle sera _**utile**_ - 6 à 8% souffrent de troubles cognitifs à titre d'exemple. En plus de ça, en France on a une population vieillissante.  
Il ne s'agit surtout pas de corriger en rajoutant des couches d'accessibilité mais il faut bien plus **concevoir tout de suite les choses de manière accessible**.
####Couleurs
Le contraste ---> [How the web became unreadable](https://backchannel.com/how-the-web-became-unreadable-a781ddc711b6#.6a6bjaowy) par Kevin Marks
Le ratio préférable est 3;1 dès 24px et 4.5:1 pour en-dessous. Des outils peuvent s'en charger comme *color contrast checker* sur le site WebAIM et pour les images on peut se référer à [*text on background image*](http://www.brandwood.com/a11y/) sur a11y. 
Vert et rouge ne suffisent pas pour indiquer une chose correcte ou incorrecte. En particulier lorsqu'on parle d'erreurs, il faut ajouter du texte pour spécifier le problème -- cela fera double effet car on remarquera mieux un texte en rouge qu'une bête ligne rouge tout en étant plus précis.
####Textes
Il faut une taille de texte suffisante : 16-18px sont à la mode et c'est tant mieux. Certains utilisateurs augmentent jusqu'à 200% leur page, il faut donc tester sur navigateur (pas sur Photoshop...) les polices tip-top-chouette téléchargées mais qui bavent en 32px. Il faut également soigner les libellés, surtout s'ils sont répétés sur une même page ou sur tout le site -- quarante "En savoir +" sur une page ne sont le signe de rien de particulier car ils sont trop nombreux.
####La navigation au clavier
C'est un gros morceau mais un bon début est de commencer par afficher le focus clavier (les petits rectangles voire les éléments surlignés permettant de repérer où l'on est). 
####Les zones réactives
Il s'agit des boutons, zones à cocher, etc. Sur mobile c'est une évidence car c'est une nécessité mais il faut également penser à ceux qui ont du mal à être précis avec une souris. Pour ce faire on agrandit les éléments tout en préservant les espaces - 26pt/2.2em d'espacement en règle général.
####Les carrousels et trucs qui bougent
Prévoir des boutons play/pause pour les slideshows à défilement automatique. 

**Voir** Notices AcceDe Web (société Atalan) notamment [notice d'accessibilité pour la conception fonctionnelle et graphique](http://www.accede-web.com/notices/graphique/) et l'écosystème Opquast (société Temesis) qui propose des check-lists et en version papier "Qualité Web". 