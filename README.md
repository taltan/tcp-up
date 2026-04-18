# TCP/UP

> Protocole déclaratif de transparence sur le rôle de l’humain et de l’IA dans la création de contenu.

[![Statut](https://img.shields.io/badge/statut-brouillon_public-blue)](#statut-du-projet)
[![Version](https://img.shields.io/badge/version-0.1.0-black)](#statut-du-projet)
[![Licence](https://img.shields.io/badge/licence-CC_BY_4.0-green)](#licence)

TCP/UP vise à rendre lisible, de bonne foi, la part respective de l’intention humaine et de l’assistance algorithmique dans un contenu publié.

---

## Ce dépôt

Ce dépôt GitHub est le **lieu de travail documentaire** du protocole TCP/UP.

Le cœur contributif du projet se trouve dans le dossier [`docs/`](./docs), en particulier :

- `docs/manifeste.md`
- `docs/logique-labels.md`
- `docs/documentation.md`
- `docs/faq.md`
- `docs/ethique.md`
- `docs/labels/label-huc.md`
- `docs/labels/label-hca.md`
- `docs/labels/label-hce.md`
- `docs/labels/label-ace.md`
- `docs/labels/label-aic.md`

Les ressources visuelles de référence peuvent être conservées dans `assets/` si elles servent la documentation, les badges ou l’identité du projet.

C’est **principalement sur ces fichiers** que les contributions sont attendues, via **issues** et **pull requests**.

---

## Ce qu’est TCP/UP

- Un protocole public de labellisation
- Un langage commun de transparence
- Un cadre déclaratif fondé sur la bonne foi
- Une initiative documentaire, critique et évolutive

## Ce que TCP/UP n’est pas

- Un détecteur d’IA
- Une certification officielle
- Un avis juridique
- Une preuve technique d’origine

---

## Les 5 labels

| Label | Signification | Usage typique |
|---|---|---|
| **HUC** | 100 % humain, sans IA | Création entièrement humaine |
| **HCA** | Humain + correction technique IA | Orthographe, grammaire, nettoyage formel |
| **HCE** | Fond humain, formulation assistée par IA | Reformulation, ton, traduction relue |
| **ACE** | Co-construction humain / IA | Plan, idées, structure partagée |
| **AIC** | Contenu majoritairement généré par IA | Génération brute, sélection ou validation légère |

---

## Comment contribuer

La meilleure façon de contribuer est de :

1. lire les documents dans `docs/`,
2. signaler un cas ambigu ou une contradiction via une issue,
3. proposer une clarification de formulation,
4. ouvrir une pull request ciblée si vous avez une proposition de modification.

Merci de lire [`CONTRIBUTING.md`](./CONTRIBUTING.md) avant de contribuer.

---

## Structure du dépôt

```text
.
├── README.md
├── SPECIFICATION.md
├── CASES.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
├── CHANGELOG.md
├── LICENSE
├── SECURITY.md
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── protocol-case.md
├── docs/
│   ├── manifeste.md
│   ├── logique-labels.md
│   ├── documentation.md
│   ├── faq.md
│   ├── ethique.md
│   └── labels/
│       ├── label-huc.md
│       ├── label-hca.md
│       ├── label-hce.md
│       ├── label-ace.md
│       └── label-aic.md
└── assets/
    ├── badges/
    │   ├── badge_huc_co.svg
    │   ├── badge_huc_tr_co.svg
    │   ├── badge_hca_co.svg
    │   ├── badge_hca_tr_co.svg
    │   ├── badge_hce_co.svg
    │   ├── badge_hce_tr_co.svg
    │   ├── badge_ace_co.svg
    │   ├── badge_ace_tr_co.svg
    │   ├── badge_aic_co.svg
    │   └── badge_aic_tr_co.svg
    ├── icons/
    │   ├── icon_tcp-up.webp
    │   ├── icon_huc.webp
    │   ├── icon_hca.webp
    │   ├── icon_hce.webp
    │   ├── icon_ace.webp
    │   └── icon_aic.webp
    └── logos/
        ├── logo_tcp-up.webp
        ├── logo_huc.webp
        ├── logo_hca.webp
        ├── logo_hce.webp
        ├── logo_ace.webp
        └── logo_aic.webp
```

---

## Rôle des fichiers racine

- `README.md` : point d’entrée du dépôt
- `SPECIFICATION.md` : synthèse normative courte du protocole
- `CASES.md` : cas d’usage transversaux et arbitrages
- `CONTRIBUTING.md` : règles de contribution
- `GOVERNANCE.md` : mode d’évolution du projet
- `CHANGELOG.md` : historique des changements
- `LICENSE` : cadre de réutilisation
- `SECURITY.md` : politique de signalement des vulnérabilités, expositions sensibles et usages problématiques liés au dépôt ou à ses ressources

---

## Statut du projet

**Version actuelle :** 0.1.0  
**Maturité :** brouillon public  
**Mode de contribution privilégié :** issues et pull requests sur les documents de `docs/`

---

## Assets

Les ressources visuelles de référence sont conservées dans [`assets/`](./assets) : badges SVG, icônes WebP, logos WebP.  
Les contributions visuelles utiles à la documentation peuvent être proposées via issue ou pull request lorsqu’elles améliorent la lisibilité du protocole.

---

## Sécurité

Si vous devez signaler une vulnérabilité, une exposition involontaire d’information sensible, un problème lié à un snippet, à un asset officiel ou à un usage trompeur susceptible d’induire le public en erreur, merci de consulter [`SECURITY.md`](./SECURITY.md).

---

## Site web

- Site : [https://tcp-up.org](https://tcp-up.org)
- Contact : [contact@tcp-up.org](mailto:contact@tcp-up.org)

---

## Licence

Le contenu documentaire du dépôt est publié sous **CC BY 4.0**, sauf mention contraire.  
Les logos, badges, la marque et l’identité visuelle restent exclus par défaut.
