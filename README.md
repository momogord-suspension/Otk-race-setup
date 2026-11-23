# OTK Mini 60 Setup Manager — V14

Version web de la fiche de réglage Tony Kart Rookie Mini 60. Le projet est statique : aucun serveur ni installation n'est nécessaire.

## Publication avec GitHub Pages

1. Créer un dépôt GitHub (par exemple `otk-mini60-setup`).
2. Ajouter **tous les fichiers** de ce dossier à la racine du dépôt (`index.html`, `favicon.svg` et les éventuels fichiers d'icône/manifest).
3. Dans le dépôt, ouvrir **Settings → Pages**.
4. Dans **Build and deployment**, choisir **Deploy from a branch**.
5. Sélectionner la branche `main` et le dossier `/ (root)`, puis cliquer sur **Save**.
6. Après quelques instants, GitHub affichera l'adresse publique du site dans cette même rubrique.

## Données et sauvegardes

Les fiches enregistrées sont stockées dans le `localStorage` du navigateur et de l'appareil utilisé. Elles ne sont **pas synchronisées automatiquement** entre téléphone et ordinateur, ni entre plusieurs utilisateurs. Utiliser les boutons **Exporter sauvegarde (.json)** et **Importer (.json)** dans l'application pour transférer ou conserver les fiches. Garder une copie régulière du fichier JSON exporté.

## Personnalisation

Le bandeau et les accents reprennent une ambiance Tony Kart (bleu, jaune, blanc et bleu nuit). L'emblème est une création graphique générique de karting ; ce dépôt n'est pas officiel et n'est pas affilié à OTK/Tony Kart.

## Contenu

- `index.html` : application V14 autonome.
- `favicon.svg` : icône de l'onglet du navigateur.
- `manifest.webmanifest` et `icon-192.png` : icône/raccourci mobile si présents.
