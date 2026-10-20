# Conjugueur FR

Petit conjugueur de verbes français, utilisable hors ligne dans le navigateur.

## Fichiers

- `index.html` : page d’accueil, prête pour GitHub Pages.
- `style.css` : styles indépendants du HTML.
- `data/conjugaison.js` : données locales de verbes et modèles.
- `COPYING` : texte de la licence GPLv2.

## Publier avec GitHub Pages

1. Ajouter ces fichiers à un dépôt GitHub.
2. Dans **Settings → Pages**, choisir **Deploy from a branch**.
3. Sélectionner la branche `main` et le dossier `/ (root)`, puis enregistrer.

La page est publiée à l’adresse affichée dans les paramètres Pages. Aucun build ni serveur n’est nécessaire.

## Licence et source des données

Les données de conjugaison proviennent de [Verbiste](https://github.com/allan-simon/verbiste-cordova/tree/f829bc037d48bccf9450ec6f45888c9df0cace41/data) et sont sous licence GPL version 2 ou ultérieure. Voir `COPYING` et l’en-tête de `data/conjugaison.js`.
