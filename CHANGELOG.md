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

## [0.2.0] - 2026-04-25

### Ajouté
- Logique des métadonnées avec clés de contenu variables et suffixes figés (`content-origin`, `form-origin`, `ai-role`).
- Tableau des origines par label (Fond/Forme) et tableau des Content Keys pour les types de contenu.
- Exemples concrets de blocs de métadonnées pour un contenu unique et un contenu composite.
- Lien vers le générateur de métadonnées dans la section Signature technique.

### Modifié
- Mise à jour du guide de l’étiquetage (version 1.1) avec la nouvelle structure de métadonnées.
- Enrichissement de la section 3.3 pour détailler la logique des métadonnées et les valeurs normalisées.

### Clarifié
- Distinction entre Fond et Forme dans les métadonnées via les suffixes `content-origin` et `form-origin`.

## [0.1.0] - 2026-04-18

### Ajouté
- Mise en place du dépôt documentaire initial de TCP/UP.
- Création des fichiers racine : `README.md`, `SPECIFICATION.md`, `CASES.md`, `CONTRIBUTING.md`, `GOVERNANCE.md`, `CHANGELOG.md`, `SECURITY.md` et `LICENSE`.
- Définition d’un modèle d’issue pour les cas limites dans `.github/ISSUE_TEMPLATE/protocol-case.md`.
- Définition d’un modèle d’issue de question dans `.github/ISSUE_TEMPLATE/question.md`.
- Ajout du fichier `.github/ISSUE_TEMPLATE/config.yml`.
- Structuration du cœur contributif du projet dans `docs/`.
- Intégration d’un espace `assets/` pour les ressources visuelles de référence.
- Ajout d’une politique de sécurité documentaire et de signalement dans `SECURITY.md`.

### Modifié
- Positionnement du dépôt comme lieu de travail documentaire du protocole.
- Orientation explicite des contributions vers `docs/` via issues et pull requests.
- Prise en compte des badges, logos, icônes et autres assets dans les fichiers racine.
- Mise à jour du `README.md` pour intégrer `SECURITY.md` dans la structure du dépôt, le rôle des fichiers racine et les consignes de signalement.
- Harmonisation éditoriale et typographique de `README.md`.
- Harmonisation éditoriale et structurelle de `CONTRIBUTING.md`.
- Harmonisation éditoriale et structurelle de `GOVERNANCE.md`.
- Harmonisation éditoriale, de périmètre et de signalement de `SECURITY.md`.
- Harmonisation doctrinale et structurelle de `SPECIFICATION.md`.
- Harmonisation des cas d’usage et arbitrages dans `CASES.md`.
- Harmonisation du cadrage de réutilisation dans `LICENSE`.
- Mise à jour du régime de licence documentaire du dépôt de `CC BY 4.0` vers `CC BY-SA 4.0`.

### Clarifié
- Distinction entre le rôle des fichiers racine et celui des documents du dossier `docs/`.
- Statut contributif principal de `docs/` par rapport à `assets/`.
- Différence entre contenu documentaire ouvert et identité visuelle protégée.
- Nature non certifiante et déclarative de TCP/UP.
- Place de `SECURITY.md` dans le socle racine du dépôt.
- Distinction entre signalement public ordinaire et signalement sensible.
- Périmètre documentaire, contributif et déclaratif de `SPECIFICATION.md`.
- Rôle interprétatif de `CASES.md` par rapport à la spécification.
- Rôle de gouvernance légère, mainteneur-centrée et évolutive du projet.
- Conditions de réutilisation des badges, logos, icônes et éléments d’identité.

### Documenté
- Cas d’usage transversaux dans `CASES.md`.
- Règles de contribution dans `CONTRIBUTING.md`.
- Gouvernance légère et mainteneur-centrée dans `GOVERNANCE.md`.
- Répartition entre textes, badges, logos et assets dans `LICENSE`.
- Politique de signalement responsable dans `SECURITY.md`.
- Structure harmonisée du socle racine du dépôt.
- Articulation entre documentation, gouvernance, sécurité, cas d’usage et licence.
- Caractère partage à l’identique de la licence documentaire applicable aux contenus ouverts du dépôt.

## Format utilisé

Quand une nouvelle version est publiée, les changements peuvent être classés dans l’une des catégories suivantes :

- **Ajouté** : nouveau contenu, nouveau document, nouvelle ressource
- **Modifié** : évolution d’un contenu existant
- **Clarifié** : précision doctrinale, éditoriale ou terminologique
- **Corrigé** : erreur supprimée ou incohérence résolue
- **Retiré** : contenu ou élément supprimé
- **Déprécié** : élément conservé temporairement mais destiné à évoluer ou disparaître
