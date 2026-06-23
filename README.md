# Jeu de classement — IA et empreinte environnementale

Application web pédagogique autonome pour classer des modèles d'IA sur une frise selon leur empreinte environnementale estimée.

## Contenu

- `index.html` : application complète avec HTML, CSS et JavaScript intégrés.
- `.nojekyll` : fichier vide recommandé pour GitHub Pages.

## Déploiement avec GitHub Pages

1. Créer un nouveau dépôt GitHub.
2. Déposer les fichiers de cette archive à la racine du dépôt.
3. Aller dans **Settings > Pages**.
4. Dans **Build and deployment**, choisir :
   - **Source** : Deploy from a branch
   - **Branch** : main
   - **Folder** : /root
5. Enregistrer.
6. Attendre quelques instants : GitHub fournira une URL publique du type :
   `https://votre-identifiant.github.io/nom-du-depot/`

## Modification des cartes

Les cartes sont modifiables directement dans le tableau `cards`, situé dans la balise `<script>` du fichier `index.html`.
