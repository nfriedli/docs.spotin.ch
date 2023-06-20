# Site statique avec Hugo

L’*association Spot in* a développement son propre modèle de site statique pour le déploiement de sites spécifiques. Elle a décidé de rendre ses sources publiques sous licence XXX. Ainsi il est possible à toute organisation de disposer d’un *template* de départ.

En pratique, 3 utilisations sont possibles.

## Développement et maintenance tierce

L’*association Spot in* travaille avec des entreprises web spécialisées en sites statiques. Elles s’occupent du développement, de l’intégration des contenus, du déploiement et de la maintenance de sites statiques.

La gestion complète d’un site statique est une offre de Spot in, chiffrée lors de l’établissement du devis.

## Développement externe

Les entreprises qui collaborent avec l’*association Spot in* peuvent développer, intégrer les contenus et déployer un site statique. Elles laissent ensuite la maintenance des contenus au client.

Cette démarche demande certaines compétences au client:

- gestion des sources sur GitHub (en *markdown*)
- gestion des déploiements sur sont propre FTP ou sur un CDN

!!! note

    Comme les sites statiques sont très pérennes, il est possible de ne pas modifier le contenu d’un site durant plusieurs années sans demander aucune maintenance.

La développement site statique est une offre de Spot in, chiffrée lors de l’établissement du devis.

## Gestion autonome

Enfin, il est possible de reprendre le template Hugo proposé, de le modifier et de le gérer de manière autonome.

La réutilisation du *template* est libre et gratuite, mais l’*association Spot in* n’assure aucune maintenance.

## Détails du modèle Hugo

XXX à suivre, les infos sur le *template*: possibilités, avantages et inconvénients, etc.

## Pour tester en local

### Logiciels

- [Hugo](https://gohugo.io/)
- [Git](https://git-scm.com/) pour la gestion des sources
- un bon éditeur de texte, par exemple [Visual Studio](https://code.visualstudio.com/)

### Téléchargement des sources

Reprise des sources par Git:

    git clone https://github.com/nfriedli/strandboden.git

Si c'est impossible, se rendre sur la [page Git du projet](https://github.com/nfriedli/strandboden), puis bouton «Code», puis «Download ZIP».

### Installation d'Hugo

Pour des tests ou pour travailler avec une version précise, placer l'exécutable dans le répertoire des sources.

Validée pour ce projet: la version [Hugo 0.111.3 extended](https://github.com/gohugoio/hugo/releases/tag/v0.111.3)

Pour Windows, télécharger la version: https://github.com/gohugoio/hugo/releases/download/v0.111.3/hugo_extended_0.111.3_windows-amd64.zip

### Utilisation locale

Pour lancer un server, dans un terminal ou Power Shell:

    hugo.exe server

Il est alors visible dans son navigateur, à une adresse du genre (visible dans la console):

    localhost:1313

Pour compiler le site:

    hugo.exe