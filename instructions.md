# Instructions

Le but de l'exercice est de créer une représentation graphique des résultats du premier tour des élections présidentielles 2022 à Poitiers.

Dans un **canvas**, pour chaque candidat : placer forme géométrique pleine (de couleur distinctes) dont la surface est proportionelle à son score au premier tour.

Les formes géométriques représentants les scores ne doivents pas se chevaucher et doivent remplir la totalité de l'espace disponible dans le canvas.

On affichera à un autre endroit de la page web (en dehors du canvas) la liste des candidat ordonée par leur score obtenu. 

- l'exercice sera réalisé avec des technologies web au sein d'un seul fichier html ;
- votre canvas aura l'`id` `shapesCanvas`
- les données seront récupérées par le client à chaque chargement de la page depuis l'API open data de Grand Poitiers sur le jeu de données [Citoyenneté - Election Présidentielle - Poitiers 2022 - 1er tour - Résultats](https://data.grandpoitiers.fr/explore/dataset/resultats_election_fichier_eirel_definitif/information/?dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6InJlc3VsdGF0c19lbGVjdGlvbl9maWNoaWVyX2VpcmVsX2RlZmluaXRpZiIsIm9wdGlvbnMiOnt9fSwiY2hhcnRzIjpbeyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoiY29sdW1uIiwiZnVuYyI6IkFWRyIsInlBeGlzIjoiYW5uZWUiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiIjOTYxNDU0In1dLCJ4QXhpcyI6ImJ1cmVhdV92b3RlIiwibWF4cG9pbnRzIjo1MCwic29ydCI6IiJ9XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D) ;
- le rendu sera dynamique et prendra en compte les données fraîches reçues depuis l'open data ;
- vous utiliserez l'API canvas ou webGL pour dessiner dans le canvas ;
- vous devrez implémenter vous-même votre fonction de tri et la methode `Array.sort()` est donc bannie ;
- le code doit être déposé sur git sur la plateforme de votre choix, vous nous ferez parvenir le lien vers votre projet.

Voici un exemple de rendu qui respecte les règles (les proportions et les scores sont totalement érronées) :

*Note : d'autres types de représentations sont possibles, tant que les règles sont respéctées*

![exemple de rendu](https://i.ibb.co/hYPGymd/Exo-de-code.png)
