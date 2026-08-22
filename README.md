# Carte de chasse de Kliff

Carte interactive de Red Dead Redemption 2, pensée pour le jeu de rôle.
Plusieurs personnes annotent la même carte, en direct.

## Outils

- Repères typés : planque, ranch, braquage, conflit, danger, rendez-vous,
  commerce, camp
- Croix, tracés à main levée, traits, flèches, zones de territoire
- Écriture libre sur la carte
- Notes partagées, en bas du registre
- Quadrillage de coordonnées A–O / 1–20, pour se donner rendez-vous
- Zoom jusqu'à 500 %, export en image PNG

Clic droit sur la carte pour poser un repère. `G` affiche le quadrillage,
`0` recadre, `Ctrl+Z` annule.

## Comment ça marche

Chaque groupe a sa carte, désignée par un identifiant tiré au sort placé
dans le lien, après le `#` :

    https://<utilisateur>.github.io/<depot>/#r=XxYyZz...

Ouvre la page une première fois : l'identifiant est créé tout seul.
Envoie ensuite **le lien complet** à tes amis — sans la partie après le
`#`, ils tomberaient sur une carte vierge.

Tout ce qui est posé part aussitôt vers la base et arrive chez les autres
sans rechargement. Il n'y a pas de bouton « enregistrer ».

## À savoir

**Toute personne qui a le lien peut lire et modifier la carte.**
L'identifiant aléatoire est la seule barrière : ne diffuse le lien qu'aux
personnes à qui tu acceptes de laisser la main.

Les données vivent dans une Firebase Realtime Database. L'adresse inscrite
dans la page est un identifiant public, prévu pour cela ; elle ne donne
accès à rien sans un identifiant de salon valide.

## Crédits

Fond de carte : Red Dead Redemption 2, © Rockstar Games.
Reproduit ici pour un usage privé entre joueurs.
