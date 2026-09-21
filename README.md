# Family Quest 🎮
Application familiale gamifiée pour Maé & Alix.

## Lancer en local
npm install
npm run dev

## Déployer sur GitHub Pages
1. Créer un dépôt GitHub et y copier ce projet.
2. `npm install && npm run build`
3. Configurer GitHub Pages / GitHub Actions pour publier le dossier `dist`.

## Firebase
Publier le contenu de `firestore.rules` dans Firebase Console > Firestore Database > Rules.
Anonymous Authentication doit être activée.

Important : la règle fournie exige une authentification anonyme mais toute personne connaissant l'URL de l'app peut créer une session anonyme. Pour un contrôle familial plus strict, passez ensuite à Firebase Auth Email/Password ou Google et limitez les UID autorisés.
