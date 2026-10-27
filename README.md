# MonSite

Deux sites autonomes, utilisables directement dans le navigateur : un conjugueur français et un convertisseur de masse et de volume. Chaque dossier de site contient tout ce qui est nécessaire à son fonctionnement et peut être déployé séparément sur un hébergeur statique.

## Fichiers

- `conjugueur/` : site du conjugueur français, avec sa feuille de style, ses données et sa licence GPLv2.
- `convertisseur/` : site du convertisseur de masse et de volume, autonome dans son fichier `index.html`.
- La racine `MonSite/` sert de dossier parent aux différents sites et ne contient pas de page d’accueil.

## Publier avec GitHub Pages

1. Dans **Settings → Pages**, choisir **Deploy from a branch**.
2. Sélectionner la branche `main` et le dossier `/ (root)`, puis enregistrer.

Avec la publication actuelle du dépôt, les sites restent accessibles à `https://<utilisateur>.github.io/<depot>/conjugueur/` et `https://<utilisateur>.github.io/<depot>/convertisseur/`. Chaque dossier `conjugueur` ou `convertisseur` peut aussi être publié séparément comme site indépendant. Aucun build ni serveur n’est nécessaire.

## Licence et source des données

Les données de conjugaison proviennent de [Verbiste](https://github.com/allan-simon/verbiste-cordova/tree/f829bc037d48bccf9450ec6f45888c9df0cace41/data) et sont sous licence GPL version 2 ou ultérieure. Voir `conjugueur/COPYING` et l’en-tête de `conjugueur/data/conjugaison.js`.
