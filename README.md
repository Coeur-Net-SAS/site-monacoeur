# site_monacoeur

Page "en construction" pour **monacoeur.fr** — authentification biométrique par le cœur. Hébergée sur GitHub Pages.

## Déploiement sur GitHub Pages

1. Poussez ce dépôt sur GitHub (ex. `monacoeur.fr` ou `site_monacoeur`).
2. Dans les paramètres du dépôt : **Settings → Pages**.
3. Sous **Build and deployment**, choisissez **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`.
4. Si vous utilisez un domaine personnalisé (`monacoeur.fr`), ajoutez-le dans **Settings → Pages → Custom domain**, puis créez un fichier `CNAME` à la racine contenant :

   ```
   monacoeur.fr
   ```

   et configurez les enregistrements DNS chez votre registrar (A records vers les IP de GitHub Pages, ou un CNAME vers `<utilisateur>.github.io`).

## Développement local

Ouvrez simplement `index.html` dans un navigateur — aucune dépendance, aucune étape de build.
