# MonSite

Deux outils autonomes, utilisables directement dans le navigateur : un conjugueur français et un convertisseur de masse et de volume.

## Fichiers

- `index.html` : page d’accueil avec les liens vers les deux outils.
- `conjugueur/index.html` : conjugueur français.
- `convertisseur/index.html` : convertisseur de masse et de volume.
- `style.css` et `data/conjugaison.js` : styles et données du conjugueur.
- `COPYING` : texte de la licence GPLv2.

## Publier avec GitHub Pages

1. Dans **Settings → Pages**, choisir **Deploy from a branch**.
2. Sélectionner la branche `main` et le dossier `/ (root)`, puis enregistrer.

Les adresses seront `https://<utilisateur>.github.io/<depot>/conjugueur/` et `https://<utilisateur>.github.io/<depot>/convertisseur/`. La page d’accueil du dépôt propose les deux liens. Aucun build ni serveur n’est nécessaire.

## Licence et source des données

Les données de conjugaison proviennent de [Verbiste](https://github.com/allan-simon/verbiste-cordova/tree/f829bc037d48bccf9450ec6f45888c9df0cace41/data) et sont sous licence GPL version 2 ou ultérieure. Voir `COPYING` et l’en-tête de `data/conjugaison.js`.
