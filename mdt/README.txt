# OREN MDT — version HTML statique

Cette archive contient un site HTML/CSS/JavaScript que vous pouvez déposer sur un hébergement statique (GitHub Pages, Netlify, Cloudflare Pages ou hébergement web classique).

## Mise en ligne
1. Décompressez l'archive.
2. Envoyez `index.html`, `style.css` et `app.js` à la racine du site via le gestionnaire de fichiers ou FTP.
3. Ouvrez l'adresse de votre site.

## Important — limites de l'HTML statique
Cette version est une maquette interactive côté navigateur. Les données sont stockées dans le `localStorage` du navigateur et ne sont pas partagées entre policiers ou appareils. La connexion Discord est un écran de présentation uniquement. **Une connexion Discord OAuth2 avec whitelist ne peut pas être sécurisée en HTML seul** : il faut un backend ou une fonction serverless pour garder le secret Discord et valider les autorisations. Ne publiez jamais un Client Secret dans un fichier HTML/JavaScript.

Pour la version multi-utilisateur avec véritable Discord OAuth2, base de données et whitelist serveur, utilisez la version Node.js du projet ou ajoutez un backend serverless.


VERSION SANS CONNEXION DISCORD
Cette version ouvre directement le MDT, sans écran ni bouton de connexion Discord. Les données restent enregistrées localement dans le navigateur (localStorage) et ne sont pas partagées entre visiteurs.
