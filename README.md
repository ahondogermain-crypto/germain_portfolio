# Portfolio de Germain Simadou Ahondo

Site statique responsive : HTML, CSS et JavaScript côté navigateur. Il est publiable sur GitHub Pages sans PHP, base de données ni secret serveur. La direction visuelle associe Playfair Display pour les titres éditoriaux, Manrope pour le texte courant, IBM Plex Mono pour les repères, et une palette chaleureuse d’ivoire, de vert profond et de terre cuite.

```text
portofolio/
├── index.html
├── merci.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── cv-germain-simadou.pdf
    ├── images/
    │   ├── photo.jpg
    │   ├── 1787517393072.png
    │   ├── IMG-20260926-WA9236.jpg
    │   ├── entrepot.svg
    │   └── port-lome.svg
    └── videos/
        └── Snapchat-1600736017.mp4
```

## Tester localement

Ouvrez `index.html` dans un navigateur ou servez le dossier avec un petit serveur statique. Le site ne nécessite pas Laragon, PHP ou MySQL. La vidéo de la galerie est chargée depuis `assets/videos/Snapchat-1600736017.mp4`.

## Publier sur GitHub Pages

1. Créez un dépôt GitHub. Pour obtenir l’adresse `https://VOTRE-NOM.github.io/`, nommez-le `VOTRE-NOM.github.io`. Sinon, le site sera disponible à `https://VOTRE-NOM.github.io/NOM-DU-DEPOT/`.
2. Ajoutez les fichiers du projet à la racine du dépôt et publiez-les sur la branche `main`.
3. Dans le dépôt, ouvrez **Settings → Pages**, choisissez **Deploy from a branch**, sélectionnez `main` et le dossier `/ (root)`, puis enregistrez.
4. Attendez la fin du déploiement et ouvrez l’adresse affichée dans **Settings → Pages**.

Le dépôt peut être public ou privé selon les possibilités de votre compte et de GitHub Pages. Tout contenu publié sur le site sera visible publiquement. Ne téléversez aucun mot de passe, aucune clé privée ni document que vous ne souhaitez pas rendre public.

## Contact

Le formulaire a été retiré. Les visiteurs peuvent contacter Germain directement par e-mail (`mailto:ahondogermain@gmail.com`) ou par téléphone au `+228 70 30 15 51`.

## Assistant

La bulle est une FAQ à réponses prédéfinies exécutée entièrement dans `script.js`. Elle peut répondre aux sujets connus sur Germain et renvoie les autres demandes vers son adresse e-mail. Ce n’est pas une IA générative : un assistant qui appelle un modèle d’IA exige un serveur ou un service tiers, et une clé API ne doit jamais être placée dans un site statique.

## Personnaliser les médias

- Les liens de démonstration des projets se trouvent dans `index.html`, sous chaque description. Modifiez l’attribut `href` du lien « Voir la démonstration » pour remplacer une adresse.
- Le portrait est `assets/images/photo.jpg`.
- La photo de Germain au port et près du chariot est `assets/images/1787517393072.png`.
- Les SVG `port-lome.svg` et `entrepot.svg` sont des placeholders de galerie ; remplacez-les par vos vraies photos lorsque vous en aurez, en mettant à jour `src`, `data-src` et les textes alternatifs dans `index.html`.
- La vidéo de galerie actuelle est `assets/videos/Snapchat-1600736017.mp4`. Pour la remplacer, mettez à jour `data-src` du bouton vidéo dans `index.html`.
- Remplacez `assets/cv-germain-simadou.pdf` par le CV définitif lorsque nécessaire.
