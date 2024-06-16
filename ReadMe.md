# Projet 3 (OpenClassrooms - Développeur d'application JavaScript React)
## Dynamisez une page web avec des animations CSS - Création du site Ohmyfood

**Pièces jointes :**  
•	[Maquettes mobile et desktop du site Ohmyfood](https://www.figma.com/file/t4449fzDnwGYmzuwQdu87V/Projet-3-FR---Ohmyfood?node-id=0%3A1)  
•	[Prototype du site](https://www.figma.com/proto/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?node-id=25368-591&scaling=scale-down&page-id=0%3A1&starting-point-node-id=25368%3A591&show-proto-sidebar=1)  
•	[Fichiers sources (images et textes)](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Images+et+textes+Ohmyfood.zip)  
•	[Brief créatif](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Brief+cr%C3%A9atif+site+Ohmyfood.pdf)  

**Identité graphique :**  
_Polices:_  
Logo et titres : Shrikhand  
Texte : Roboto  
_Couleurs:_  
Primaire &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Secondaire &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Tertiaire  
`#9356DC` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	`#FF79DA` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	`#99E2D0`

## Contenu des pages

**Page d’accueil (x1)**  
● Affichage de la localisation des restaurants. À terme, il sera possible de choisir sa
localisation pour trouver des restaurants proches d’un certain lieu.
● Une courte présentation de l’entreprise.
● Une section contenant les 4 menus sous forme de cartes. Au clic sur la carte,
l’utilisateur est redirigé vers la page du menu.

**Pages de menu (x4)**  
● 4 pages contenant chacune le menu d’un restaurant.

**Footer**  
● Le footer est identique sur toutes les pages.
● Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

**Header**  
● Le header est présent sur toutes les pages.
● Sur la page d’accueil, il contient le logo du site.
● Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.


## Effets graphiques et animations

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie. Pour toutes les animations, afin de soigner le rendu du site, il est important que lorsque nous avons un effet au hover ou lors d’un clic, nous ayons l’effet inverse lorsque l’on quitte le survol.

**Boutons**  
● Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
L’ombre portée devra également être plus visible.
● À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
bouton "J’aime" en forme de coeur est présent sur la maquette. Au clic, il devra se
remplir progressivement. Pour cette première version, l’effet peut apparaître au
survol sur desktop au lieu du clic.

**Page d’accueil**  
● Quand l’application aura plus de menus, un “loader” sera nécessaire. Sur cette
maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3
secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
graphique du site.

**Pages de menu**  
● À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
décalage dans le temps. Ils pourront apparaître soit un par un, soit par groupe
“Entrée”, “Plat” et “Dessert”.
● Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension.
