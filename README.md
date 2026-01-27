# Site CV / Portfolio pour GitHub Pages

Ce dépôt contient un site statique simple (HTML / CSS) pour présenter ton CV et ton portfolio, prêt à être hébergé sur **GitHub Pages**.

## Structure

- `index.html` – Page principale (CV / portfolio)
- `styles.css` – Styles du site

## Personnalisation

1. Ouvre `index.html` dans un éditeur :
   - Remplace **Ton Nom** par ton vrai nom
   - Mets à jour :
     - le poste cible, la ville, le pays
     - l’email, le téléphone
     - les liens **LinkedIn** et **GitHub**
   - Adapte les sections :
     - **À propos**
     - **Compétences**
     - **Expérience**
     - **Projets** (titres, descriptions, liens GitHub, etc.)
2. Si tu veux changer les couleurs ou la mise en page, modifie `styles.css`.

## Tester en local

Tu peux simplement ouvrir `index.html` dans ton navigateur (double-clic sur le fichier) pour voir le résultat.

## Mise en ligne sur GitHub Pages

1. Crée un nouveau dépôt sur GitHub (par exemple `mon-portfolio`).
2. Dans ce dossier (`github`), initialise Git :

   ```bash 
   git init
   git remote add origin https://github.com/<ton-compte>/mon-portfolio.git
   git add .
   git commit -m "Initialisation de mon CV / portfolio"
   git push -u origin main
   ```

3. Sur GitHub, va dans :
   - **Settings** > **Pages**
   - Dans **Source**, choisis la branche `main` (root / racine du projet)
   - Enregistre.

4. GitHub va générer ton site. L’URL ressemblera à :

   ```text
   https://<ton-compte>.github.io/mon-portfolio/
   ```

Tu peux ensuite partager ce lien sur ton CV ou tes réseaux.

