# Journal des modifications

Toutes les évolutions notables de TCP/UP sont documentées dans ce fichier.

Ce journal est tenu pour des lecteurs humains.  
Il suit une logique simple : une section par version, les versions les plus récentes en haut, et des changements regroupés par type.

## [Non publié]

### Prévu
- Harmoniser l’ensemble des fichiers de `docs/` avec la structure contributive du dépôt.
- Ajouter de nouveaux cas limites dans `CASES.md`.
- Renforcer les renvois croisés entre `CASES.md`, `SPECIFICATION.md` et `docs/labels/`.
- Stabiliser le rôle documentaire de `assets/` dans la présentation publique du protocole.
- Ajouter éventuellement un index interne du dossier `docs/`.

### En discussion
- Clarification plus fine de la frontière entre `HCE` et `ACE`.
- Modalités de qualification des contenus composites.
- Place exacte des assets visuels dans l’économie générale du protocole.
- Possibilité d’une labellisation plus modulaire par section ou par composant.

## [0.1.0] - 2026-04-18

### Ajouté
- Mise en place du dépôt documentaire initial de TCP/UP.
- Création des fichiers racine : `README.md`, `SPECIFICATION.md`, `CASES.md`, `CONTRIBUTING.md`, `GOVERNANCE.md`, `CHANGELOG.md` et `LICENSE`.
- Définition d’un modèle d’issue pour les cas limites dans `.github/ISSUE_TEMPLATE/protocol-case.md`.
- Structuration du cœur contributif du projet dans `docs/`.
- Intégration d’un espace `assets/` pour les ressources visuelles de référence.

### Modifié
- Positionnement du dépôt comme lieu de travail documentaire du protocole.
- Orientation explicite des contributions vers `docs/` via issues et pull requests.
- Prise en compte des badges, logos, icônes et autres assets dans les fichiers racine.

### Clarifié
- Distinction entre le rôle des fichiers racine et celui des documents du dossier `docs/`.
- Statut contributif principal de `docs/` par rapport à `assets/`.
- Différence entre contenu documentaire ouvert et identité visuelle protégée.
- Nature non certifiante et déclarative de TCP/UP.

### Documenté
- Cas d’usage transversaux dans `CASES.md`.
- Règles de contribution dans `CONTRIBUTING.md`.
- Gouvernance légère et mainteneur-centrée dans `GOVERNANCE.md`.
- Répartition entre textes, badges, logos et assets dans `LICENSE`.

## Format utilisé

Quand une nouvelle version est publiée, les changements peuvent être classés dans l’une des catégories suivantes :

- **Ajouté** : nouveau contenu, nouveau document, nouvelle ressource
- **Modifié** : évolution d’un contenu existant
- **Clarifié** : précision doctrinale, éditoriale ou terminologique
- **Corrigé** : erreur supprimée ou incohérence résolue
- **Retiré** : contenu ou élément supprimé
- **Déprécié** : élément conservé temporairement mais destiné à évoluer ou disparaître
