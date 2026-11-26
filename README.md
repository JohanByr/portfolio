# Portfolio — Johan Boyer

Portfolio personnel de Johan Boyer, étudiant en 2<sup>e</sup> année de BTS SIO option SLAM au lycée Marie Curie (Tarbes), basé à Toulouse.

**Site en ligne :** https://johanbyr.github.io/portfolio/

## Aperçu

- **Accueil** : un carrousel 3D qui présente les projets. On défile à la molette, avec les flèches du clavier ou en glissant sur mobile, et on clique sur un projet pour ouvrir sa page détaillée.
- **Pages projet** : contexte, fonctionnalités, technologies et rôle, avec une ouverture en bulle.
- **Index** : la liste de tous les projets.
- **Rubriques** (Compétences et Profil, qui contient le CV, le stage, les certifications et la charte graphique) : elles s'ouvrent en pleine page, avec un anneau 3D chromé qui s'agrandit comme transition.
- Fond noir avec un sol quadrillé en perspective.
- Le CV (`cv-johan-boyer.pdf`) et la présentation de veille (`veille-informatique-spatiale.pdf`) sont téléchargeables. Les deux fichiers PDF doivent rester à côté de `index.html`.

## Technologies

- HTML, CSS et JavaScript, sans framework
- [Three.js](https://threejs.org/) (r128, chargé depuis cdnjs) pour l'anneau 3D
- Polices Google Fonts : Syne et Hanken Grotesk

## Lancer le site en local

Le site tient dans un seul fichier, `index.html`.

1. Télécharge ou clone le dépôt.
2. Ouvre `index.html` dans ton navigateur (Chrome, Edge ou Firefox).

Une connexion internet est nécessaire pour charger les polices et Three.js.

## Modifier le contenu

Tout se trouve dans `index.html` :

- **Projets** : le tableau `P` au début du script (titre, année, description, technologies, lien, fonctionnalités).
- **Profil et liens** : le bloc `ov-profil` (texte de présentation, email, LinkedIn, GitHub).
- **Compétences** : le bloc `ov-competences`.
- **Couleurs** : les variables CSS au début de la balise `<style>` (`--bg`, `--ink`, `--acc`...).

## Déploiement

Le site est publié avec GitHub Pages, depuis la branche `main` et le dossier racine (`/`).

## Projets présentés

- [Depanne31](https://johanbyr.github.io/Depanne31/) : application web de dépannage à Toulouse (HTML, CSS, JavaScript et Supabase), réalisée pendant mon stage. [Code source](https://github.com/JohanByr/Depanne31).
- [OMS Rénovation](https://johanbyr.github.io/Oms-Renovations/) : site vitrine d'une entreprise de rénovation à Toulouse (HTML, CSS, JavaScript et Supabase), réalisé pendant mon stage. [Code source](https://github.com/JohanByr/Oms-Renovations).
- [Casse-briques](https://github.com/levygrd/cassebriques) : jeu en Java réalisé à trois, avec Lucas et Lévy (projet de groupe réalisé à l'école).
- **Veille technologique** : l'informatique spatiale (réalité augmentée et interfaces 3D), réalisée à l'école.

## Contact

Email : johanboyer09@gmail.com
