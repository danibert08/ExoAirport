# Le Projet 

Cet exercice permet d'exploiter en grande partie les langages découverts en saison 1 et saison 2, soit HTML, CSS, et PHP.


## exo : 

Votre client est un aéroport qui vous sollicite pour créer un site très simple.

Une page principale qui doit afficher les vols annoncés au départ et à l'arrivée selon la maquette jointe : [images/rendu.png]. 

Dans un premier temps les images  [images/plane-arrival.svg] et [images/plane-departure.svg] pourront être ignorées.

Cette page sera affichée en permanence sur les écrans des halls départ et arrivée, afin d'informer les voyageurs.

Les images et un tableau des vols vous sont fournis.

Le tableau qui sera afficher à l'écran doit être dynamiquement alimenté à partir du tableau fourni dans [treatment/data.php].

les couleur utilisées sont aquamarine, blue, red, black et  lightslategray et la font est par défaut.

Il faudra faire des dossiers et des templates afin que le code soit bien organisé pour l'avenir.

**Le client souhaite que l'on se rapproche le plus de la maquette**.

Concernant le bas du header, vous pouvez cependant le faire droit. Pour faire la vague , si vous le souhaitez, vous pouvez visiter ce site : [https://www.shapedivider.app/]

Bon courage ....

## Bonus 1 : 

A ce stade, il faut tenter d'ajouter les images [images/plane-arrival.svg] et [images/plane-departure.svg] comme sur la maquette en s'assurant bien que l'image arrival correspond à une arrivée ( donc 'A' dans les sous-tableaux indexés) et que l'image departure correspond à un départ (donc 'D' dans la première colonne des sous-tableaux indexés)


## Bonus 2 :

Satisfait de notre première collaboration, le client nous rappelle pour développer son site. Il souhaite créer un formulaire qui permettra à l'agent exploitant de saisir de temps en temps un nouveau vol, qui viendra s'afficher sur la page principale en bas de tableau.

Pas de soucis pour les halls, les écrans sont figés et les voyageurs ne verront en permanence que la page d'accueil présentant le tableau des vols.

Cependant, en local, vous aurez besoins d'accéder à une page formulaire, afin de permettre à l'exploitant de saisir de nouveaux vols.


Mais il n'est pas possible d'afficher un menu sur la page principale pour accéder au formulaire car ce menu serait visible également sur les écrans voyageurs et ça ferait désordre... Il faudra donc créer un accès discret en positionnant un lien invisible sur le M du nom de l'aéroport. 

Toutefois pour rassurer l'exploitant, un changement d'affichage au "hover" sera opéré selon ce modèle : [images/hover.png], le client à demandé de mettre le M en blanc dans un cercle bleu , le tout étant de 30% plus grand que la lettre.

Ce formulaire doit permettre d'ajouter un vol au tableau et redirrigera vers la page principale qui affichera le nouveau vol à la suite en bas de page.



