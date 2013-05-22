#bpi-html
Le dépôt bpi-html met à disposition le gabarit HTML détaillé dans le livre [Intégration web - les bonnes pratiques](http://www.eyrolles.com/Informatique/Livre/integration-web-les-bonnes-pratiques-9782212133707) publié aux Éditions Eyrolles.

##Base HTML
Les fichiers `base-full` contiennent une structure HTML dotée des rôles ARIA adéquats. À l'inverse, les fichiers `base-empty` proposent une base HTML vide de toute structure.

##Détail des fichiers
Les templates HTML sont disponibles en deux versions distinctes.  
Chaque version permet de cibler les différentes versions d'Internet Explorer, selon les besoin :

* `base-full.html` et `base-empty.html` permettent de cibler : 
  * IE 7 et 8 au moyen de la classe `.old-ie` ;
  * IE 7 par le biais de `.ie7`.
  * et IE 8 grâce à `.ie8` ;

* `base-full-ie6.css` et `base-empty-ie6.css` ajoutent le support d'IE 6. Ces fichiers permettent donc de cibler : 
  * IE 6, 7 et 8 au moyen de la classe `.old-ie`.
  * IE 6 par l'intermédiaire de la classe `.ie6` ;
  * IE 7 via `.ie7` ;
  * et IE 8 grâce à `.ie8` ;

##Utilisation
Suivant le contexte projet (quelles versions d'IE devez-vous supporter) et vos préférences personnelles (préférez-vous partir d'une base vide ou pré-remplie), choisissez simplement le gabarit HTML qui vous convient le mieux.
