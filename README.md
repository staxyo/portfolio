# Page simple CV + Portfolio (GitHub Pages)

Ce dépôt contient une **seule page** très simple pour :

- afficher ton **CV (PDF)** ;
- présenter quelques **projets de portfolio**.

## Fichiers

- `index.html` – la page d’accueil (CV + portfolio)
- `styles.css` – le style du site
- `cv.pdf` – **à ajouter toi-même** (voir ci-dessous)

## Ajouter ton CV

1. Prends ton CV au format **PDF**.
2. Renomme-le exactement en **`cv.pdf`**.
3. Copie ce fichier `cv.pdf` dans le même dossier que `index.html` et `styles.css`.
4. Quand tu ouvriras `index.html` dans ton navigateur, le bouton **“Ouvrir mon CV (PDF)”** fonctionnera
   et l’aperçu intégré s’affichera.

## Modifier le texte

Ouvre `index.html` et adapte :

- **Ton Nom** et le sous-titre (poste, spécialisation, etc.).
- Les textes du bloc **Portfolio** :
  - titres des projets (`Projet 1`, `Projet 2`, `Projet 3`…),
  - les descriptions,
  - les liens (`href="#"`) vers tes dépôts GitHub, sites en ligne, etc.

Tu peux dupliquer ou supprimer les `<article class="portfolio-item">` selon le nombre de projets.

## Tester en local

Double-clique simplement sur `index.html` pour l’ouvrir dans ton navigateur.

## Mise en ligne sur GitHub Pages

1. Crée un nouveau dépôt sur GitHub (par ex. `cv-portfolio`).
2. Dans ce dossier, exécute (dans PowerShell) :

   ```bash
   git init
   git add .
   git commit -m "Ajout de ma page CV + portfolio"
   git branch -M main
   git remote add origin https://github.com/<ton-compte>/cv-portfolio.git
   git push -u origin main
   ```

3. Sur GitHub, va dans **Settings → Pages** :
   - Source : choisis la branche `main`,
   - Dossier : `/ (root)` si l’option existe.

4. GitHub va générer ton site à une adresse du type :

   ```text
   https://<ton-compte>.github.io/cv-portfolio/
   ```

Tu pourras ensuite partager ce lien dans ton vrai CV PDF, sur LinkedIn, etc.

