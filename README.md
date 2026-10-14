# Aides Techniques - Autour de la Maison

Site web interactif présentant ~108 fiches d'aides techniques pour l'autonomie (cuisine, salle de bain, transferts, déplacements, etc.).

## Fichiers

- `index.html` : page principale du site (version en ligne)
- `products.json` : données structurées de toutes les fiches (facile à éditer)
- `images/` : dossier contenant les photos des produits
- `aides-techniques-standalone.html` : version unique (tout en un seul fichier, ~8 Mo) pour envoi par email

## Hébergement en ligne (recommandé)

### Sur GitHub Pages (gratuit et simple)

1. Créez un nouveau dépôt GitHub (ou utilisez un existant comme `pierreg78-maker.github.io`).
2. Uploadez les fichiers : `index.html`, `products.json` et le dossier `images/`.
3. Dans les settings du dépôt → Pages → Source : branch `main` / root (ou `/docs`).
4. Le site sera accessible en quelques minutes à l'adresse `https://votre-username.github.io/nom-du-repo/`

**Avantage** : vous pouvez facilement mettre à jour une fiche en éditant `products.json` et en ajoutant une image, puis en poussant le changement.

### Version hors-ligne / email

Envoyez le fichier `aides-techniques-standalone.html` aux utilisateurs. Ils l'ouvrent directement dans un navigateur (Chrome, Firefox, Edge, Safari). Aucune installation nécessaire. Tous les textes et photos sont inclus.

## Ajouter ou modifier une fiche

1. Ouvrez `products.json` dans un éditeur de texte.
2. Copiez un objet produit existant et modifiez les champs :
   - `name` : nom du produit
   - `zone` : Cuisine, Salle de bain, Chambre, WC / Toilettes, Transferts, Déplacements, Confort & Aides diverses
   - `descriptions`, `permet`, `ideal`, `caracteristiques`
   - `images` : `["images/nom-de-votre-image.jpg"]`
3. Placez la nouvelle image dans le dossier `images/`.
4. Sauvegardez et redéployez (ou ouvrez `index.html` localement pour tester).

## Filtres disponibles

- Recherche libre par mot-clé
- Filtre par zone de l'habitation
- Filtre par besoin / fonction (préhension, stabilité, transfert, mobilité, hygiène, etc.)

---

Créé à partir des fiches PowerPoint fournies. Les textes originaux ont été conservés.
