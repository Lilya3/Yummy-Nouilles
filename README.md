# Yummy Nouilles

Projet d’intégration web réalisé dans le cadre de la formation **Intégrateur Web d’OpenClassrooms**.

L’objectif était d’intégrer, à partir d’une maquette Figma, le site vitrine responsive de **Yummy Nouilles**, une enseigne fictive de restaurants asiatiques située à Paris.

## Présentation du projet

Le site permet aux visiteurs de découvrir l’univers de Yummy Nouilles, ses restaurants, son menu et ses informations de contact.

Il se compose de trois pages :

- **Accueil** : présentation de l’enseigne, adresses des restaurants, savoir-faire et galerie issue des réseaux sociaux ;
- **Menu** : présentation des entrées, plats, desserts et boissons ;
- **Contact** : adresses, horaires et coordonnées des différents restaurants.

## Travail réalisé

- intégration des trois pages à partir de la maquette fournie ;
- création d’une navigation commune entre les pages ;
- intégration des images, du logo et des icônes de réseaux sociaux ;
- réalisation des sections d’appel à l’action « Click & Collect » ;
- adaptation de l’affichage aux écrans mobiles avec des media queries ;
- organisation des styles CSS par composants et par pages ;
- utilisation d’une convention de nommage inspirée de la méthode BEM ;
- mise en place de variables CSS pour les couleurs et la typographie.

## Technologies utilisées

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Media queries
- Variables CSS
- Google Fonts
- Figma pour la maquette

## Organisation des branches

- **`main`** : contient le projet de départ fourni dans le cadre de la formation.
- **`branch_dev`** : contient l’intégration et les modifications que j’ai réalisées.

Pour consulter ma version du projet :

```bash
git switch branch_dev
```

## Installation et lancement

Ce projet est un site statique et ne nécessite aucune dépendance.

1. Clonez le dépôt :

```bash
git clone <URL_DU_DEPOT>
```

2. Placez-vous dans le dossier du projet :

```bash
cd Yummy-Nouilles
```

3. Sélectionnez la branche contenant la version finalisée :

```bash
git switch branch_dev
```

4. Ouvrez le fichier `index.html` dans votre navigateur.

## Structure du projet

```text
Yummy-Nouilles/
├── assets/
│   ├── icons/          # Icônes des réseaux sociaux et de localisation
│   ├── restaurant/     # Photographies des restaurants
│   ├── social/         # Images de la galerie
│   └── logo.svg        # Logo de l’enseigne
├── styles/
│   ├── modules/        # Styles des composants communs
│   ├── pages/          # Styles propres à chaque page
│   └── main.css        # Design system et import des feuilles de style
├── contact.html        # Page des adresses et coordonnées
├── index.html          # Page d’accueil
└── menu.html           # Page présentant le menu
```

## Compétences travaillées

- transformer une maquette Figma en pages web ;
- structurer le contenu avec HTML ;
- réaliser des mises en page avec Flexbox et CSS Grid ;
- créer une interface responsive pour ordinateur et mobile ;
- organiser une feuille de style en plusieurs fichiers ;
- appliquer une convention de nommage cohérente ;
- utiliser Git et travailler avec plusieurs branches.

## Contexte

Projet pédagogique réalisé dans le cadre de la formation **Intégrateur Web** d’OpenClassrooms.
