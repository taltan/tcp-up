# Spécification TCP/UP

**Version :** 0.1.0  
**Statut :** brouillon public

## 1. Objet

TCP/UP est un protocole déclaratif de transparence destiné à rendre visible la part respective de l’humain et de l’intelligence artificielle dans la création d’un contenu.

Son objectif est de fournir une grille de lecture simple, intelligible et publiquement exploitable pour décrire la méthode de production d’un contenu, sans réduire cette méthode à une opposition binaire entre "humain" et "IA".

TCP/UP repose sur la bonne foi déclarative de l’auteur ou du responsable de publication.

---

## 2. Finalité

Le protocole poursuit plusieurs finalités :

- améliorer la lisibilité des conditions de production d’un contenu ;
- permettre au lecteur, au public ou au destinataire de mieux comprendre le rôle joué par l’humain et l’IA ;
- préserver la valeur du travail intellectuel humain dans des environnements de publication hybrides ;
- offrir un langage commun de description, simple à adopter et simple à interpréter.

TCP/UP n’a pas pour finalité de détecter automatiquement l’IA, de certifier un contenu ou de trancher à lui seul des questions juridiques.

---

## 3. Périmètre

TCP/UP peut être utilisé pour décrire la production de contenus numériques, notamment :

- textes ;
- documents ;
- images ;
- audio ;
- vidéo ;
- code ;
- contenus composites ou multimodaux.

Le protocole peut être utilisé dans des contextes variés : publication éditoriale, documentation, communication institutionnelle, création indépendante, formation, production technique ou contenus diffusés en ligne.

---

## 4. Principe général

TCP/UP distingue deux dimensions d’analyse :

- le **Fond** : l’intention, les idées, l’architecture intellectuelle, le raisonnement, le plan, la structure et les choix de sens ;
- la **Forme** : la mise en mots, le style, la formulation, le rendu, l’exécution technique, la présentation ou la matérialisation finale.

Cette distinction permet de mieux décrire les situations dans lesquelles l’humain conserve la maîtrise intellectuelle du contenu tout en recourant à une assistance sur la forme, ou au contraire les situations dans lesquelles l’IA intervient aussi sur la structuration du fond.

---

## 5. Nature déclarative du protocole

TCP/UP est un protocole déclaratif.

Cela signifie que :

- le label résulte d’une déclaration assumée ;
- le protocole repose sur la sincérité méthodologique ;
- il ne constitue pas une preuve technique autonome ;
- il n’implique pas de mécanisme natif de vérification automatique.

Le protocole a pour fonction première d’éclairer le lecteur, non de se substituer à un audit, à une expertise technique ou à une procédure de conformité.

---

## 6. Les 5 labels

TCP/UP repose sur cinq labels principaux.

### 6.1 HUC

**HUC - Human User Content**

Le contenu est conçu et rédigé sans recours à l’intelligence artificielle, ni pour le fond, ni pour la forme.

Usage typique :
- rédaction intégralement humaine ;
- création manuelle sans assistance IA ;
- élaboration autonome du contenu, de sa structure et de sa formulation.

### 6.2 HCA

**HCA - Human-Centric Assistance**

Le fond du contenu est entièrement humain. L’IA n’intervient que dans une fonction de correction technique ou de nettoyage formel, sans transformation éditoriale substantielle.

Usage typique :
- correction orthographique ;
- correction grammaticale ;
- ajustement syntaxique mineur ;
- mise en forme légère sans altération du sens.

### 6.3 HCE

**HCE - Human-Centric Editing**

Le fond, l’intention, la structure intellectuelle et la responsabilité du contenu restent humains. L’IA intervient sur la formulation, la fluidité, le ton, la traduction, la reformulation ou certaines dimensions d’expression.

Usage typique :
- reformulation stylistique ;
- adaptation du ton ;
- traduction relue et validée ;
- amélioration de lisibilité sans transfert de la maîtrise du fond.

### 6.4 ACE

**ACE - AI-Centric Editing**

Le contenu résulte d’une co-construction substantielle entre l’humain et l’IA. L’IA intervient de manière significative dans la structuration, les propositions d’idées, l’architecture du contenu, le plan ou une partie non marginale de la production intellectuelle.

Usage typique :
- plan proposé ou fortement structuré par IA ;
- idées ou angles suggérés de manière déterminante ;
- premier jet substantiel co-construit ;
- interaction itérative avec effet réel sur le fond.

### 6.5 AIC

**AIC - AI Content**

Le contenu est majoritairement ou intégralement généré par IA. L’intervention humaine se limite principalement au prompt, à la sélection, à la validation légère, à l’assemblage ou à l’usage instrumental du résultat.

Usage typique :
- génération brute ;
- texte ou contenu largement produit par IA ;
- sélection humaine sans maîtrise intellectuelle substantielle du contenu final.

---

## 7. Logique d’interprétation

Le choix d’un label doit refléter honnêtement la réalité du processus de production.

Le protocole repose sur une logique de prudence :

- si un doute subsiste entre deux labels, il convient de retenir celui qui attribue la part la plus importante à l’IA ;
- si l’IA a joué un rôle structurant dans l’émergence du fond, le contenu ne devrait pas être présenté comme relevant d’un label de type H par simple retouche humaine ultérieure ;
- si l’intervention de l’IA modifie substantiellement la structure, l’orientation ou la formulation au point d’infléchir le sens final, un label plus impliquant pour l’IA doit être envisagé.

L’objectif n’est pas de protéger artificiellement une apparence d’humanité, mais de décrire loyalement une méthode.

---

## 8. Règle de prudence

La règle de prudence constitue un principe central de TCP/UP.

En cas d’hésitation :

- entre HCA et HCE, choisir HCE si l’IA a dépassé la simple correction technique ;
- entre HCE et ACE, choisir ACE si l’IA a contribué au plan, aux idées, à la structure ou à l’orientation du contenu ;
- entre ACE et AIC, choisir AIC si l’essentiel du contenu final provient de la génération.

Cette règle vise à protéger la lisibilité publique du protocole et à limiter les usages sous-déclarés.

---

## 9. Documents composites et usages modulaires

Un même document peut combiner plusieurs modes de production.

Dans ce cas, deux approches sont possibles :

- un **label global**, correspondant à la logique dominante du document ;
- un **étiquetage modulaire**, si plusieurs sections, médias ou composants relèvent de logiques distinctes.

L’étiquetage modulaire est particulièrement pertinent pour les contenus longs, mixtes ou techniques.

Exemples :
- un article rédigé en HCE intégrant une illustration AIC ;
- une documentation principalement HUC incluant un exemple de code ACE ;
- une page composite comprenant texte HCE, image AIC et synthèse tabulaire HCA.

---

## 10. Limites du protocole

TCP/UP comporte des limites explicites.

Le protocole :

- ne détecte pas automatiquement l’usage de l’IA ;
- ne prouve pas l’origine d’un contenu par lui-même ;
- ne remplace pas un cadre juridique ;
- ne garantit ni la véracité, ni la qualité, ni l’éthique intrinsèque d’un contenu ;
- ne constitue pas une certification officielle ;
- ne remplace pas la responsabilité de l’auteur, de l’éditeur ou du diffuseur.

TCP/UP doit être compris comme une couche déclarative de transparence, non comme une infrastructure de preuve.

---

## 11. Usages publics recommandés

Le protocole peut être rendu visible sous différentes formes :

- badge visuel ;
- signature textuelle ;
- mention intégrée à la publication ;
- métadonnée ou balisage complémentaire ;
- documentation d’accompagnement.

Exemple de mention publique :

`TCP/UP : HCE - Fond humain, formulation assistée par IA`

La forme publique retenue doit rester lisible, non trompeuse et cohérente avec le contenu concerné.

---

## 12. Compatibilité et articulation

TCP/UP peut coexister avec d’autres cadres, standards, licences ou dispositifs de description documentaire.

Il ne prétend pas se substituer :

- aux cadres juridiques applicables ;
- aux métadonnées techniques ;
- aux standards de preuve d’origine ;
- aux politiques éditoriales propres aux plateformes ou aux institutions.

Il peut être compris comme une couche sémantique, éthique et déclarative complémentaire.

---

## 13. Responsabilité

Le choix du label relève de la responsabilité de la personne ou de l’entité qui publie le contenu.

L’usage du protocole implique :

- une déclaration sincère ;
- une capacité minimale à justifier le label retenu ;
- une vigilance en cas d’évolution ultérieure du contenu ;
- une cohérence entre le label affiché et la réalité du processus.

La responsabilité humaine demeure entière, quel que soit le niveau d’assistance algorithmique.

---

## 14. Évolution de la spécification

Cette spécification est un document vivant.

Elle peut évoluer pour :

- clarifier des cas limites ;
- stabiliser certaines définitions ;
- documenter de nouveaux usages ;
- préciser les formes publiques d’intégration ;
- améliorer la cohérence d’ensemble du protocole.

Les évolutions du projet sont cadrées par `GOVERNANCE.md` et suivies dans `CHANGELOG.md`.

---

## 15. Statut du document

Cette version 0.1.0 constitue un brouillon public de référence pour le dépôt.

Elle a vocation à servir de base commune :

- à la lecture du protocole ;
- aux contributions documentaires ;
- aux arbitrages de formulation ;
- à la stabilisation progressive du cadre TCP/UP.
