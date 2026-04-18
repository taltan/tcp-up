# Guide complet de l’étiquetage TCP/UP

Version 1.0 - Avril 2026

## Table des matières

- [Introduction : pourquoi étiqueter ?](#introduction--pourquoi-étiqueter-)
- [1. Analyser son processus créatif - L’arbre de décision (la règle des 30s)](#1-analyser-son-processus-créatif---larbre-de-décision-la-règle-des-30s)
- [2. Sélectionner le label TCP/UP](#2-sélectionner-le-label-tcpup)
- [3. Apposer les labels](#3-apposer-les-labels)
  - [3.1 Signature visuelle (badge)](#31-signature-visuelle-badge)
  - [3.2 Signature textuelle](#32-signature-textuelle)
  - [3.3 Signature technique (métadonnées)](#33-signature-technique-métadonnées)
    - [3.3.1 La méthode simple (recommandée)](#331-la-méthode-simple-recommandée)
    - [3.3.2 Pourquoi aller plus loin (perspectives futures)](#332-pourquoi-aller-plus-loin-perspectives-futures)
- [4. Cas critiques et arbitrage](#4-cas-critiques-et-arbitrage)
  - [4.1 Introduction](#41-introduction)
  - [4.2 Analyse des scénarios et cas limites](#42-analyse-des-scénarios-et-cas-limites)
    - [4.2.1 Traduction par IA avec relecture humaine](#421-traduction-par-ia-avec-relecture-humaine)
    - [4.2.2 Reformulation avec “hallucination créative”](#422-reformulation-avec-hallucination-créative)
    - [4.2.3 Contenu généré puis lourdement restructuré par l’humain](#423-contenu-généré-puis-lourdement-restructuré-par-lhumain)
    - [4.2.4 Brainstorming IA et rédaction humaine autonome](#424-brainstorming-ia-et-rédaction-humaine-autonome)
    - [4.2.5 Code informatique : Génération, débogage et optimisation](#425-code-informatique--génération-débogage-et-optimisation)
    - [4.2.6 Prompt Engineering Avancé (Mega‑prompts)](#426-prompt-engineering-avancé-mega-prompts)
    - [4.2.7 Publication sans relecture complète (Le cas “Blind Output”)](#427-publication-sans-relecture-complète-le-cas-blind-output)
    - [4.2.8 Pipeline “Multi‑IA” et contenus composites](#428-pipeline-multi-ia-et-contenus-composites)
    - [4.2.9 Révisions successives et reclassification](#429-révisions-successives-et-reclassification)
    - [4.2.10 Travail collaboratif et attribution collective](#4210-travail-collaboratif-et-attribution-collective)
  - [4.3 Principes généraux d’arbitrage](#43-principes-généraux-darbitrage)
  - [4.4 Granularité technique du label ACE (usage interne)](#44-granularité-technique-du-label-ace-usage-interne)
  - [4.5 Limites et clause de bonne foi](#45-limites-et-clause-de-bonne-foi)

---



## Introduction : pourquoi étiqueter ?

Dans un environnement numérique saturé de contenus générés ou assistés par intelligence artificielle, la transparence n’est plus une option, c’est un gage de confiance. Le protocole **TCP/UP** (**Transparent Content Protocol / User-Powered**) permet de **déclarer clairement** le rôle de l’humain et de l’IA dans la production d’un contenu, de manière simple, lisible et responsable.

Ce guide vous accompagne pas à pas dans l’application du protocole, de l’analyse de votre processus créatif à l’intégration des signatures visuelles et techniques, en passant par le choix du bon label.

> **Important**  
> TCP/UP est un protocole déclaratif de transparence sur l’usage de l’IA. Il ne constitue ni une preuve technique, ni une certification tierce, ni un avis juridique. Il vise à rendre le processus éditorial plus lisible pour le public.

> **Note :** Cette charte est une initiative citoyenne basée sur la déclaration de bonne foi et la responsabilité des auteurs.

## 1. Analyser son processus créatif - L’arbre de décision (la règle des 30s)

Avant d’apposer un label, déterminez où se situe votre travail dans le spectre humain / IA grâce à ce flux logique. Besoin d’aide ? [Trouvez votre label en 30s avec l’assistant de choix](/pages/wizard.html)

**1. L’IA a‑t‑elle généré, reformulé ou corrigé une partie du contenu ?**

- → NON → `[TCP/UP: HUC]` (aucune IA utilisée)
- → OUI → passer à la question 2

**2. L’IA a‑t‑elle modifié le sens ou la structure des idées (reformulation, restructuration, apport d’idées nouvelles) ?**

- → NON (intervention limitée à l’orthographe/grammaire) → `[TCP/UP: HCA]`
- → OUI → passer à la question 3

**3. Le fond du contenu (intention, structure, argumentaire) est-il resté entièrement conçu par l’humain ?**

- → Oui, le fond est humain et l’IA n’a aidé qu’à formuler ou structurer l’expression → `[TCP/UP: HCE]`
- → Non, l’IA a contribué au plan, aux idées, à l’angle ou à la structure du contenu → passer à la question 4

**4. Le contenu a-t-il été co-construit avec l’IA ou principalement généré par elle ?**

- → Co-construction avec intervention humaine substantielle → `[TCP/UP: ACE]`
- → Génération majoritairement déléguée à l’IA, avec validation ou sélection humaine limitée → `[TCP/UP: AIC]`

> **Variante :** Si vous avez fourni un prompt très détaillé décrivant déjà l’architecture intellectuelle, les arguments et le ton, **HCE peut être envisagé**. Par prudence, si l’IA a néanmoins influencé l’organisation finale, introduit des angles nouveaux ou orienté la structure du texte, **ACE reste préférable**.

> **Principe de prudence :** Si vous hésitez entre deux labels, choisissez celui qui accorde la plus grande part à l’IA. La transparence prime sur l’orgueil.

## 2. Sélectionner le label TCP/UP

| Label | Fond | Forme | Définition | Quand l’utiliser |
|-------|------|-------|------------|------------------|
| **HUC** | Humain | Humaine | Aucune IA utilisée dans le processus de création | texte, image ou document créé sans assistance IA |
| **HCA** | Humain | Humaine avec correction technique | IA limitée à la correction orthographique, grammaticale ou syntaxique | correction de texte sans reformulation |
| **HCE** | Humain | Assistée par IA | Fond humain, formulation ou mise en forme assistée | reformulation, adaptation de ton, traduction relue |
| **ACE** | Hybride | Hybride | L’IA a contribué au fond du contenu aux côtés de l’humain | plan suggéré par IA, brainstorming, co-rédaction |
| **AIC** | Majoritairement IA ou délégué | Générée par IA | Contenu majoritairement ou intégralement généré par IA | génération brute, résumé automatique, traduction non relue |

### Exemples concrets par label

- **HUC** : un manuscrit littéraire tapé sans aucune assistance ; un éditorial dont chaque mot est choisi manuellement ; un dessin numérique réalisé à la main sans filtres IA.
- **HCA** : une thèse relue par un correcteur IA sans que le style ne soit modifié ; un contrat juridique passé en revue pour les fautes de frappe.
- **HCE** : des notes de réunion transformées en compte rendu structuré ; un email interne reformulé pour être plus diplomatique.
- **ACE** : un article SEO généré à 50% par IA, puis réécrit et enrichi d’expertise humaine ; un business plan dont l’IA a fourni la structure, rempli par l’humain.
- **AIC** : un logo généré par prompt ; un script Bash créé entièrement par IA ; la traduction brute d’un manuel technique.

> **Cas particuliers :** Pour des situations plus ambiguës (traduction, code, brainstorming, méga‑prompt…), consultez la section Cas critiques et arbitrage (section 4 de la documentation complète).

## 3. Apposer les labels

TCP/UP offre trois niveaux de signatures, à utiliser selon le contexte de publication.

### 3.1 Signature visuelle (badge)

Téléchargez les badges officiels dans la [section ressources](./download.html). Insérez‑les dans votre contenu de manière visible, par exemple en haut ou en bas de l’article, à côté du titre, ou dans le pied de page.

> **Bonnes pratiques :** Lien du badge vers la charte TCP/UP pour expliquer le label. Respectez les couleurs et proportions originales. Évitez de modifier les badges (redimensionnement autorisé).

### 3.2 Signature textuelle

Pour les environnements où une image ne peut être insérée (flux RSS, documentation technique, métadonnées), utilisez la forme textuelle : `[TCP/UP: XXX]` (remplacer XXX par HUC, HCA, HCE, ACE, AIC).

> `[TCP/UP: HCE]` - Fond humain, formulation assistée par IA.

### 3.3 Signature technique (métadonnées)

Pour aller plus loin dans la transparence, vous pouvez intégrer la signature directement dans le code source de votre page. Cette approche est aujourd’hui facultative, mais elle prépare le terrain pour de futurs outils (moteurs de recherche, assistants IA, archives) qui pourraient reconnaître et exploiter ces métadonnées.

#### 3.3.1 La méthode simple (recommandée)

Insérez une ou plusieurs balises `<meta>` dans l’en‑tête (`<head>`) de votre page HTML. C’est simple, universel, et cela rend l’information accessible à quiconque inspecte le code.

```html
<head>							
    <meta name="tcp-up:label" content="[TCP/UP: HCE]">
    <meta name="tcp-up:content-origin" content="human">
    <meta name="tcp-up:ai-role" content="formulation assistée">
</head>
```

Vous pouvez ainsi indiquer le label, l’origine du fond, et une courte description du rôle de l’IA. Utilisez les valeurs qui correspondent à votre déclaration. Le préfixe `tcp-up:` est une convention libre - vous pouvez l’adapter à vos besoins.

#### 3.3.2 Pourquoi aller plus loin (perspectives futures)

Aujourd’hui, aucun navigateur ou moteur de recherche ne lit spécifiquement ces balises personnalisées. Mais à mesure que la transparence deviendra un enjeu central, il est probable que des standards émergent. D’autres formats plus riches comme **JSON‑LD** (utilisé par Schema.org) ou des attributs `data-*` pourraient alors être adoptés par les grandes plateformes. En attendant, une simple balise `<meta>` suffit à :

- → Rendre votre engagement plus lisible en laissant une trace déclarative dans le code source
- → Faciliter une éventuelle vérification manuelle
- → Anticiper une évolution de l’écosystème sans avoir à retravailler l’ensemble de vos contenus

> **Conseil** : si vous publiez du contenu dans des environnements techniques (bases de données, flux RSS), vous pouvez également ajouter la signature textuelle `[TCP/UP: XXX]` dans un champ dédié (par exemple une catégorie ou un tag). Cela rend l’information exploitable par vos propres outils.

## 4. Cas critiques et arbitrage

### 4.1 Introduction

L’hybridation des flux de travail entre l’intelligence humaine (IH) et l’intelligence artificielle (IA) crée parfois des situations où la frontière entre le **Fond (Content)** et la **Forme (Form)** devient subtile. La crédibilité du protocole TCP/UP repose sur la capacité à lever ces ambiguïtés avec bon sens et cohérence. Cette section propose des repères pour guider l’auteur dans les cas les plus fréquents, sans chercher à épuiser toutes les situations.

> **Rappel :** TCP/UP est une initiative citoyenne, un langage commun fondé sur la bonne foi. Il ne s’agit ni d’une certification officielle, ni d’un outil de preuve technique. L’objectif est de fournir une grille de lecture honnête pour le lecteur, en responsabilisant l’auteur.

### 4.2 Analyse des scénarios et cas limites

#### 4.2.1 Traduction par IA avec relecture humaine

- **Description :** Un texte original d’origine humaine est traduit vers une autre langue par une IA, puis révisé par l’auteur pour en vérifier la fidélité.
- **Analyse C/F :** Le Fond (C) reste intégralement humain. La Forme (F) est générée par l’IA et validée par l’humain.
- **Label recommandé :** **HCE** (Human‑Centric Editing).
- **Justification :** L’idée est humaine, mais la structure syntaxique et le choix lexical de la langue cible sont produits par l’algorithme.
- **Recommandation :** Tout changement de langue de production via un outil automatisé exclut généralement les labels HUC et HCA (réservés à une forme non assistée).

#### 4.2.2 Reformulation avec “hallucination créative”

- **Description :** L’auteur demande à une IA de reformuler un paragraphe. L’IA introduit une nouvelle métaphore ou un argument non présent initialement, que l’auteur décide de conserver.
- **Analyse C/F :** L’IA a influencé le Fond (C) en injectant de nouveaux concepts ou angles d’approche.
- **Label recommandé :** **ACE** (AI‑Centric Editing).
- **Justification :** L’intention initiale a été modifiée par l’apport suggestionnel de l’IA.
- **Recommandation :** Lorsque l’IA apporte un élément conceptuel non prévu par l’auteur et que celui-ci est conservé, le contenu relève plus fidèlement de la **série A**, car l’IA a contribué au fond.

#### 4.2.3 Contenu généré puis lourdement restructuré par l’humain

- **Description :** Un utilisateur génère un texte complet par IA, puis en modifie une grande partie pour y injecter son style, ses sources et corriger les erreurs.
- **Analyse C/F :** Le Fond (C) est une co‑construction (structure IA, enrichissement humain). La Forme (F) est majoritairement humaine.
- **Label recommandé :** **ACE** (AI‑Centric Editing).
- **Justification :** L’étincelle initiale et l’architecture première proviennent de la machine. L’humain agit comme un éditeur curateur.
- **Principe :** La logique de la “page blanche” reste ici déterminante : si l’IA a fourni la première structure intellectuelle du contenu, un retour vers la série H n’est généralement pas le choix le plus transparent.

#### 4.2.4 Brainstorming IA et rédaction humaine autonome

- **Description :** L’auteur utilise l’IA pour générer un plan ou des idées, puis ferme l’outil et rédige intégralement le texte sans assistance.
- **Analyse C/F :** Le Fond (C) est hybride (idées partagées). La Forme (F) est d’origine humaine.
- **Label recommandé :** **ACE** (AI‑Centric Editing).
- **Justification :** La structure intellectuelle a été assistée, même si l’exécution est humaine.
- **Recommandation :** L’assistance au Fond (plan, thèses, structure) conduit à utiliser ACE pour une transparence totale sur la genèse des idées.

#### 4.2.5 Code informatique : Génération, débogage et optimisation

- **Description :** Un développeur génère une fonction via IA, puis la corrige, l’optimise et l’intègre.
- **Analyse C/F :** La logique algorithmique (C) est partagée. La syntaxe (F) est générée par l’IA.
- **Label recommandé :** **ACE** (AI‑Centric Editing).
- **Justification :** En programmation, Fond et Forme sont souvent indissociables. La correction ne suffit pas à occulter la génération initiale.
- **Recommandation :** Pour le code, lorsqu’un bloc logique est généré par IA puis adapté par l’humain, **ACE constitue en général le label le plus fidèle**.

#### 4.2.6 Prompt Engineering Avancé (Mega‑prompts)

- **Description :** L’humain rédige un prompt exhaustif (souvent plus de 500 mots) qui structure précisément l’architecture de la pensée : idées directrices, arguments détaillés, sources spécifiques, ton souhaité. L’IA exécute la mise en mots intégrale.
- **Analyse C/F :** **Fond (C) : Humain** (substance intellectuelle) | **Forme (F) : IA** (syntaxe, rédaction).
- **Label recommandé :** **HCE** (Human‑Centric Editing) peut être envisagé. Par prudence, si l’IA a néanmoins influencé l’organisation finale, introduit des angles nouveaux ou orienté la structure du texte, **ACE reste préférable**.

> **Point de vigilance, le risque du « prompt-washing » :** Revendiquer HCE pour un contenu généré via méga-prompt est légitime SI ET SEULEMENT SI le prompt contient déjà l'intégralité de l'architecture intellectuelle (thèse, arguments, structure, ton). Un prompt de 500 mots qui dit « écris-moi un article sur X » n'est PAS un méga-prompt. C'est une instruction de génération → AIC.

> **Test de sincérité :** Pourriez-vous publier votre prompt seul comme un plan détaillé ? Si oui → HCE possible. Si non → ACE ou AIC.

#### 4.2.7 Publication sans relecture complète (Le cas “Blind Output”)

- **Description :** L’utilisateur génère un contenu complet via une IA et le publie sans relecture critique exhaustive, ni vérification des faits.
- **Analyse C/F :** Le Fond (C) et la Forme (F) sont délégués à l’automate.
- **Label recommandé :** **AIC** (AI Content).
- **Justification :** Sans validation humaine point par point, l’auteur ne peut garantir l’intégrité du contenu. Le processus est alors purement génératif.
- **Recommandation :** En l’absence de relecture active et de validation substantielle, **AIC est le label le plus cohérent**.

#### 4.2.8 Pipeline “Multi‑IA” et contenus composites

- **Description :** Un projet utilise plusieurs IA spécialisées (texte, image, code, etc.) dont les résultats sont intégrés.
- **Label recommandé :** **ACE** (global) ou **étiquetage modulaire**.
- **Justification :** Si le projet est perçu comme une unité, le label global devrait refléter le composant le plus automatisé.

#### 4.2.9 Révisions successives et reclassification

- **Description :** Un contenu initialement labellisé AIC est retravaillé sur plusieurs versions jusqu'à être substantiellement modifié.
- **Règle d'arbitrage :** Le label reflète l'état actuel, pas l'historique. Toutefois, une mention de l'évolution est encouragée.
- **Formulation suggérée :** « Version actuelle : [TCP/UP: HCE] (évolution depuis AIC, voir historique) »
- **Recommandation :** Un changelog de transparence PEUT être maintenu pour les documents évolutifs.

#### 4.2.10 Travail collaboratif et attribution collective

- **Description :** Un document produit par plusieurs contributeurs avec des usages IA hétérogènes.
- **Règle d'arbitrage :** Le label global DEVRAIT refléter le composant le plus automatisé (principe de prudence).
- **Alternative :** Étiquetage par section avec mention des contributeurs.
- **Recommandation :** En cas de publication collective, désigner un « responsable de transparence » qui valide le label final.

### 4.3 Principes généraux d’arbitrage

- **1. Principe de prudence (conservatisme) :** En cas d’hésitation entre deux labels, l’auteur devrait choisir le label accordant la plus grande part à l’IA.
- **2. Règle de la page blanche :** Si l’IA a fourni la première structure logique (plan, architecture), le contenu devrait éviter les labels de la série H.
- **3. Audit de sincérité :** La validation humaine “en diagonale” est généralement insuffisante pour justifier un label ACE ou HCE. Une relecture active est encouragée.
- **4. Indivisibilité du code :** Pour le code, lorsqu’un bloc logique est généré par IA puis adapté par l’humain, **ACE constitue en général le label le plus fidèle**.

### 4.4 Granularité technique du label ACE (usage interne)

Ces sous‑catégories sont facultatives et destinées à un usage interne ou documentaire. Elles ne modifient pas le label public affiché.

| Sous‑label | Nom | Description indicative |
|------------|-----|------------------------|
| **ACE‑L** | *Light Intent* | L’IA aide sur le fond mais l’humain dirige environ les trois quarts de la structure. |
| **ACE‑B** | *Balanced* | Équilibre réel. Co‑écriture fluide entre l’humain et l’outil. |
| **ACE‑D** | *Dominant AI* | L’IA génère la majorité du fond et de la forme, l’humain intervient en curateur. |

**Recommandation d’implémentation :** Ces distinctions peuvent être intégrées dans des attributs de données (ex. `data-tcpup-sub="ACE-B"`), mais le badge visuel affiché doit rester le label standard **ACE**.

### 4.5 Limites et clause de bonne foi

- **Auto‑déclaration :** TCP/UP est un système déclaratif basé sur l’honneur. Il ne constitue pas une preuve technique cryptographique.
- **Déclaration et bonne foi :** Le standard repose sur l’auto‑déclaration responsable de l’auteur. Il privilégie la transparence assumée plutôt que l’illusion d’une détection parfaite.
- **Responsabilité :** L’apposition d’un label TCP/UP engage la crédibilité de l’auteur. La mauvaise foi manifeste nuit à la confiance collective.

> Cette section constitue un guide d’arbitrage, non une contrainte absolue. Elle évoluera avec les retours d’usage et les pratiques de la communauté.

---

