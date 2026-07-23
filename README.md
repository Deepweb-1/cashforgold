# CashForGoldCanada Clone

Ce dépôt contient le clone exact du site `cashforgoldcanada.com` ainsi que ses sous-pages principales. Il a été préparé spécifiquement pour être hébergé sur **GitHub Pages**.

## Comment le mettre en ligne sur GitHub Pages ?

1. Créez un nouveau dépôt vide sur votre compte GitHub (par exemple `CashForGoldCanada-Site`).
2. Poussez le contenu de ce dossier vers votre nouveau dépôt avec les commandes suivantes :
   ```bash
   git remote add origin https://github.com/VOTRE_NOM/CashForGoldCanada-Site.git
   git branch -M main
   git push -u origin main
   ```
3. Une fois les fichiers en ligne, allez dans l'onglet **Settings** de votre dépôt GitHub.
4. Dans le menu de gauche, cliquez sur **Pages**.
5. Dans la section **Build and deployment**, sous "Source", sélectionnez **Deploy from a branch**. Sous "Branch", choisissez `main` (ou `master`) et laissez le dossier sur `/ (root)`. Cliquez sur **Save**.
6. Attendez quelques minutes : GitHub va publier votre site et vous fournira l'URL (par exemple `https://votrenom.github.io/CashForGoldCanada-Site/`).

## Remarques techniques
- Un fichier `.nojekyll` est inclus pour s'assurer que GitHub Pages n'ignore aucun sous-dossier de ressources (comme les répertoires contenant un tiret bas `_` s'il y en a).
- Tous les liens et sources (`<script>`, `<link>`, `<img>`, `<a>`) ont été rendus relatifs pour fonctionner parfaitement, peu importe le nom de domaine sur lequel ce code est hébergé.
