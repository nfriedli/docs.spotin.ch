# Définition d'un spot

Le principe de base: un code QR unique renvoie vers une URL finale.

Un spot n'est pas qu'une simple redirection d'URL, mais il reste un objet simple.


## ID unique

Une identification unique est attribuée à un spot à sa création. Elle est générée automatiquement et n'est pas modifiable. L'unicité du code QR est assuré par l'unicité de l'ID.

!!! note

    XXX Voir aussi les remarques dans Pérennité

## Titre

Un titre sous forme de champ textuel. Utile quand les spots disponibles sont listés sur le site Spot in ou ailleurs. Et nécessaire pour la maintenance des spots.

## Description

Un paragraphe optionnel qui permet de donner plus d'informations sur le spot. 

## Coordonnées

Latitude et longitude sous forme numérique. Spot in propose de récupérer automatiquement la localisation du smartphone lors de la première saisie du spot. Les coordonnées permettent d'automatiser la création de cartes.

## URL finale

C'est la réponse au scan du code QR. Toute URL valide peut être utilisée.

## Options

XXX À documenter:

- referenced
- configured