# ÉLOQUENCE AI — Code source

Prototype d'application web responsive, sans serveur ni compte.

## Lancer sur son ordinateur

1. Installer Python 3 si nécessaire.
2. Ouvrir un terminal dans ce dossier.
3. Exécuter : `python -m http.server 8000` (ou `python3 -m http.server 8000`).
4. Ouvrir http://localhost:8000 dans un navigateur.

Il est aussi possible d'ouvrir `index.html` directement, mais certaines fonctions du navigateur peuvent être limitées.

## Publier sur Internet

Créer un dépôt GitHub, y ajouter les fichiers de ce dossier, puis activer GitHub Pages (Settings > Pages > Deploy from a branch, branche main, dossier /root). L'application sera accessible par une URL HTTPS.

## Limitations

- Les questions proviennent de scénarios prédéfinis : ce n'est pas encore un agent IA conversationnel.
- Les notes sont heuristiques et indicatives.
- Le micro dépend des autorisations et de la reconnaissance vocale du navigateur. Celle-ci peut recourir à des services tiers.
- L'import PDF/DOCX charge des bibliothèques depuis un CDN et nécessite Internet.
- Les notes sont stockées localement dans le navigateur.
- Ne pas saisir de données confidentielles dans ce prototype.

## Étape suivante

Pour un simulateur réellement intelligent, créer un backend sécurisé qui reçoit le texte du projet et les réponses, appelle une API IA, puis renvoie une question contextualisée et des retours pédagogiques. Ne jamais mettre une clé API dans index.html.
