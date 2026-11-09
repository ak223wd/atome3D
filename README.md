# ⚛ Atomes en 3D

Visualisation 3D interactive des atomes pour les élèves de collège.

On choisit un élément dans le tableau périodique, et l’atome apparaît en animation avec ses **protons (+)**, ses **neutrons (0)** et ses **électrons (−)** répartis sur les couches. On peut ensuite retirer ou ajouter des électrons pour former des **ions**.

## Fonctionnalités

- Tableau périodique complet (118 éléments), coloré par famille
- Atome en 3D : noyau, couches électroniques, charges visibles
- Compteurs de particules et calcul de la charge totale
- Ions : ajout ou retrait d’électrons, message de stabilité (couche externe pleine)
- Bouton pause pour compter les électrons tranquillement
- Utilisable sur iPhone, iPad et ordinateur, en portrait ou en paysage
- Liens directs vers un atome : `…/#Na`, `…/#O`, `…/#Fe`

## Utilisation

Ouvrir la page (voir le lien GitHub Pages dans la description du dépôt). Aucune installation n’est nécessaire.

En local, ouvrir simplement `index.html` dans un navigateur (une connexion internet est requise pour charger Three.js).

## Limites pédagogiques

- Les électrons sont répartis par couches selon un modèle simplifié (type Bohr). Quelques exceptions de la configuration réelle (chrome, cuivre…) ne sont pas prises en compte.
- Le nombre de neutrons est calculé à partir de la masse atomique arrondie (isotope le plus courant).

## Technologies

HTML, CSS et JavaScript dans un seul fichier, avec [Three.js](https://threejs.org/) (licence MIT) et la police [Nunito](https://fonts.google.com/specimen/Nunito) (licence OFL).

## Licence

MIT, voir le fichier `LICENSE`.
