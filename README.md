# Base de données Topographiques du systèmes karstiques du massif du Charmant Som (Saint Pierre de Chartreuse, 38, France)



## Overview

Ce dépôt contient les données topographiques et les dessins associés des cavités du massif du Charmant Som à Saint Pierre de Chartreuse (73, France). 

Cela comprend :

- le réseau Ded
- le Trou qui pique 
- La résurgence de la porte de l’Enclos
- des prospections.

## Description

Ce dépôt sauvegarde les données topographiques et de dessin. Ces fichiers sont Therion (data + dessins).

Uniquement les fichiers sources sont sauvegardés pour des raisons de taille  :

> - .thc, .th, .th2 et .thconfig pour le logiciel Therion

<!--Cette base de données est hierarchisée en systèmes hydrologiques, puis par zone, puis par cavités, et enfin, pour les cavités importantes, par petits réseaux. Pour obtenir les topographies en plan, coupe et/ou 3D de chaque élément, il faut compiler les différents fichiers Therion thconfig. Pour obtenir les topographies en plan et/ou 3D de l'ensemble d'un système ou de la base de données, il faut compiler les fichiers Therion thconfig parents. Il n'est pas nécessaire d'avoir compilé chaque petite entité auparavant.-->

<!--Aussi, cette base de données topographique est à la base de projets SIG, que ce soit pour la production de cartes propres, ou pour la mise en place d'une application portable sur appareils Android ou iOS. Pour générer ou mettre à jour les différents champs non produits directement par Therion, il faut lancer dans un Terminal le script shell Build-Samoens-SIG.sh. Il faut alors être un peu patient ! Ce script shell fait appel à des scripts Python, qui utilisent le module Fiona, Shapely et alive_progress qui sont à installer préalablement.-->

<!--Une convention a aussi été mise en place pour la gestion des points d'interrogation, avec la définition de différents champs :-->

> - <!--le champ "Code" qui décrit le type de terminus. Il peut prendre les valeurs :-->
>
> 	> - <!--A : il suffit d'y aller et de continuer, pas d'obstacles-->
> 	> - <!--D : Désobstruction nécessaire,-->
> 	> - <!--E : Escalade nécessaire,-->
> 	> - <!--P : Puits non descendu,-->
> 	> - <!--Q : non renseigné sur les topographies anciennes, c'est à voir/vérifier,-->
> 	> - <!--S : Siphon à plonger,-->
> 	> - <!--T : Trémie à désobstruer-->
>
> - <!--le champ "Cavite" qui donne le nom de la cavité en question,-->
>
> - <!--le champ "Reseau" qui indique la partie de la cavité où se situe le point d'interrogation (pour pouvoir le retrouver plus rapidement sur les topographies),-->
>
> - <!--le champ "CA" qui est rempli si présence de courant d'air, avec éventuellement des remarques/commentaires.-->



## Licence

- L'ensemble de ces données est publié sous la licence libre Creative Commons Attribution-ShareAlike-NonCommercial (Attribution, partage à l'identique et non commerciale) :

	http://creativecommons.org/licenses/by-nc-sa/4.0/



## Auteur de la base de données

Benoît Urruty (b.urruty77@gmail.com)



## How to cite



## Contact

[responsable.speleo@gucem.fr](responsable.speleo@gucem.fr )
