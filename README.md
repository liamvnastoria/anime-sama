# Anime Sama

Anime Sama est une plateforme de diffusion et de découverte d’anime inspirée des grandes plateformes comme Crunchyroll, mais pensée pour **mettre les créateurs originaux au centre**. Elle propose une interface moderne et intuitive tout en respectant les principes historiques des créateurs : **pas de comptes utilisateur, stockage local des préférences et historique**.

---

## Objectif du projet

* Offrir une **nouvelle version de la plateforme existante** aux créateurs pour améliorer l’expérience des utilisateurs.
* Respecter les choix fondamentaux des créateurs : **pas de gestion de comptes, confidentialité maximale**.
* Moderniser l’interface et les fonctionnalités tout en restant **fidèle à l’esprit original**.

---

## Fonctionnalités principales

### Pour les utilisateurs

* Lecture d’anime en streaming directement dans le navigateur.
* Historique et favoris stockés **localement** via le cache du navigateur.
* Personnalisation de l’expérience : thèmes, sous-titres, langue.
* Navigation fluide entre genres, saisons et créateurs.

### Pour les créateurs

* Tableau de bord simple pour uploader et gérer les contenus.
* Statistiques anonymes et agrégées sur les vues et l’engagement.
* Possibilité de monétiser via abonnements ou contenus exclusifs.

---

## Architecture technique

* **Stockage côté client** : localStorage ou IndexedDB pour l’historique, favoris et préférences.
* **Streaming** : lecture en HTML5 avec support multi-langues.
* **Interface moderne** : responsive, mobile-first, design simple et intuitif.
* **Statistiques anonymes** : collecte d’informations globales sans identifier les utilisateurs.

---

## Installation et utilisation

> Note : Anime Sama est conçue pour fonctionner sans inscription. Tout se passe côté navigateur pour les utilisateurs.

1. Cloner le projet :

```bash
git clone https://github.com/liamvnastoria/anime-sama.git
```

2. Ouvrir `index.html` dans un navigateur moderne.
3. Pour les créateurs : accéder au tableau de bord via `/admin` et uploader les contenus.

---

## Contribution

Anime Sama est un projet collaboratif. Les contributions sont les bienvenues :

* Amélioration de l’interface utilisateur.
* Optimisation du stockage local et des performances.
* Ajout de nouvelles fonctionnalités respectant les principes de confidentialité.

---

## Licence

Anime Sama est distribué sous licence Apache 2.0 . Vous êtes libre de l’utiliser, le modifier et le partager.
