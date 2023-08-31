# Projet_MontageSon

Bienvenue sur mon projet Montage Son !

### :headphones: Le projet

J'ai souhaité proposer une expérience de montage son à l'utilisateur, en lui permettant de manipuler des familles de son, que l'on appelle "Stem" dans le cinéma. 

De cette manière, l'utilisateur va pouvoir interagir avec les pistes audio en choisissant de les activer, de les isoler ou de toutes les jouer. L'utilisateur peut ainsi écouter la séquence en comprenant les différents étages qui vont composer le résultat.

### :wrench: Comment fonctionne la page ?

:triangular_flag_on_post: Sous la vidéo, sont disposées des pistes par Stem : 
- :sound: le Stem "Voix directes" ne comprend que les voix du tournage
- :sound: le Stem Post-Synchros" ne contient que les voix ré-enregistrées en studio
- :sound: le Stem "Ambiances" contient toute l'atmosphère du film (le vent, les groupes de gens, la neige, l'eau, etc...)
- :sound: le Stem "Effets" contient tous les sons ponctuels : passages de voiture, hélicos, aboiements...
- :sound: le Stem "Bruitage" contient les bruitages crées en studio, ce sont des sons interprétés par un bruiteur, qui concernent les comédiens : les pas, les vêtements, les mouvements, etc...
- :sound: le Stem "Musique" qui provient du compositeur

<br/>

![cover](https://github.com/clem0316/Projet_MontageSon/blob/cb6dc07f9e32fe23849bcd32f323a29c075d0e09/img/Screen3.jpg)

<br/>

:triangular_flag_on_post: Il est possible, à la fin de chaque piste, de muter :mute: ou demuter :sound: les pistes individuellement :arrow_double_down:

<br/>

![cover](https://github.com/clem0316/Projet_MontageSon/blob/4e87798d37707695550246b24bc0965627d91893/img/Screen5.jpg)

<br/>

:triangular_flag_on_post: Mais une autre manière consite à directement isoler une famille. Par exemple, si je ne souhaite écouter que les ambiances du film :arrow_double_down:

<br/>

![cover](https://github.com/clem0316/Projet_MontageSon/blob/4e87798d37707695550246b24bc0965627d91893/img/Screen4.jpg)

<br/>

### :ledger: Difficultés rencontrées et futurs Objectifs : 

:date: A court terme : 
- Le code peut-être optimisé par des méthodes apprises depuis, qui simplifieraient et réduiraient mon document js
- Le slider de contrôle de volume doit être retravaillé visuellement
- La gestion de la synchro entre les éléments audio et la vidéo n'est pas encore optimale (pratiquement 250ms et reste un peu flottante). Plusieurs pistes ont été étudiées sans obtenir pleine satisfaction. La resynchro régulière (toutes les 3000ms) donnait des vrais résultats au niveau synchronisation pure mais créait des artefacts et des "clicks" sonores peu esthétiques.

:date: A moyen terme : 
- Il est envisagé de passer en techno REACT
- Le but est de pouvoir choisir parmi plusieurs films différents

