# MotJuste - première version

Application web installable (PWA), pensée pour mobile.

## Tester
Ouvrir `index.html` dans un navigateur permet de tester l'interface, mais l'installation PWA nécessite un hébergement HTTPS ou localhost.

## Mettre en ligne gratuitement avec GitHub Pages
1. Créer un compte GitHub.
2. Créer un dépôt public nommé `motjuste`.
3. Ajouter les fichiers `index.html`, `manifest.json`, `sw.js` et `icon.svg` à la racine.
4. Dans Settings > Pages, choisir Deploy from a branch, puis `main` et `/ (root)`.
5. Ouvrir l'adresse fournie par GitHub Pages sur Safari iPhone.
6. Dans Safari : bouton Partager > Sur l'écran d'accueil > Ajouter.

## Fonctionnement et limites
- Les informations lexicales sont demandées au Wiktionnaire via son API publique.
- Les suggestions utilisent la recherche du Wiktionnaire. Elles proposent des résultats proches, mais ne constituent pas un correcteur orthographique avancé.
- La détection du genre repose sur les modèles présents dans les pages du Wiktionnaire. Certains mots rares, mots à plusieurs sens ou pages complexes peuvent ne pas être interprétés correctement.
- Une connexion internet est nécessaire pour les recherches.
- Cette version est un prototype fonctionnel à améliorer, pas un dictionnaire exhaustif garanti.
