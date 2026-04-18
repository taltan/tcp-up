# Cas d’usage et arbitrages TCP/UP

## Objet

Ce document rassemble des cas d’usage transversaux, des situations limites et des arbitrages d’interprétation relatifs au protocole TCP/UP.

Il complète `SPECIFICATION.md` en apportant des exemples concrets de qualification. Son rôle n’est pas de remplacer la spécification, mais d’aider à l’appliquer de manière plus lisible, plus cohérente et plus prudente.

En cas de contradiction apparente, `SPECIFICATION.md` prévaut.

---

## Principe de lecture

Les cas ci-dessous doivent être lus comme des repères d’interprétation.

Ils ont pour but :

- d’éclairer les situations ambiguës ;
- de réduire les sous-déclarations ;
- d’aider à distinguer le rôle du fond et celui de la forme ;
- d’encourager une application prudente et sincère du protocole.

Chaque cas présente :

- une situation ;
- un label généralement recommandé ;
- une justification courte.

Les cas ne couvrent pas toutes les variantes possibles. En cas de doute, la règle de prudence s’applique.

---

## Règle de prudence

Lorsque plusieurs labels paraissent défendables, il convient de retenir celui qui attribue la part la plus importante à l’IA.

Cette règle s’applique en particulier :

- lorsque l’IA a contribué au plan ou à la structure ;
- lorsque la frontière entre reformulation et co-construction devient floue ;
- lorsque l’humain valide surtout un résultat déjà fortement produit ;
- lorsque la présentation publique risquerait d’exagérer la part humaine.

---

## Cas liés à l’écriture

### Cas 1 - Texte entièrement rédigé sans IA

**Situation**  
L’auteur conçoit, structure et rédige son texte sans recourir à un outil d’intelligence artificielle.

**Label recommandé**  
`HUC`

**Justification**  
Le fond et la forme relèvent entièrement d’un travail humain.

---

### Cas 2 - Correction orthographique ou grammaticale uniquement

**Situation**  
L’auteur rédige seul son texte, puis utilise une IA uniquement pour corriger l’orthographe, la grammaire ou quelques détails de syntaxe, sans transformation éditoriale substantielle.

**Label recommandé**  
`HCA`

**Justification**  
Le fond reste humain et l’intervention de l’IA demeure strictement technique.

---

### Cas 3 - Reformulation stylistique

**Situation**  
L’auteur a conçu seul le fond, mais demande à une IA d’améliorer la fluidité, le ton ou la formulation du texte.

**Label recommandé**  
`HCE`

**Justification**  
Le fond reste humain, mais la forme est assistée de manière réelle.

---

### Cas 4 - Traduction avec relecture humaine

**Situation**  
Un texte pensé et structuré par un humain est traduit avec l’aide d’une IA, puis relu et validé.

**Label recommandé**  
`HCE`

**Justification**  
L’intention et le fond restent humains, mais la formulation finale dépend d’une assistance sur la forme.

---

### Cas 5 - Plan proposé par IA avant rédaction

**Situation**  
L’auteur demande à une IA de proposer un plan, une structure ou une organisation des idées, puis rédige lui-même le contenu final.

**Label recommandé**  
`ACE`

**Justification**  
Dès lors que l’IA intervient dans l’architecture intellectuelle du contenu, elle participe au fond.

---

### Cas 6 - Premier jet généré puis réécrit en partie

**Situation**  
Une IA produit un premier jet substantiel, que l’auteur retravaille, corrige et améliore ensuite.

**Label recommandé**  
`ACE`  
ou `AIC` dans les cas les plus fortement générés

**Justification**  
Le premier jet constitue déjà une contribution structurante. Une réécriture humaine ultérieure ne suffit pas automatiquement à faire revenir le contenu dans la série H.

---

### Cas 7 - Résumé d’un texte personnel par IA

**Situation**  
L’auteur fournit son propre texte à une IA pour obtenir un résumé, puis publie ce résumé après relecture.

**Label recommandé**  
`HCE`

**Justification**  
Le fond initial est humain, mais la forme résumée est produite par l’IA.

---

### Cas 8 - Méga-prompt très détaillé

**Situation**  
L’auteur donne des instructions extrêmement précises à une IA afin d’obtenir un texte proche de son intention initiale.

**Label recommandé**  
`HCE` ou `ACE` selon le degré réel de marge laissé à l’IA

**Justification**  
Si l’IA se contente d’exécuter une intention déjà totalement structurée, `HCE` peut être défendable. Si elle arbitre réellement la structure, les formulations-clés ou le développement, `ACE` est plus prudent.

---

## Cas liés au code

### Cas 9 - Correction légère d’un code humain

**Situation**  
Le développeur écrit seul son code et utilise l’IA pour repérer des fautes mineures, améliorer une syntaxe ou corriger des détails locaux.

**Label recommandé**  
`HCA` ou `HCE` selon la nature de l’intervention

**Justification**  
Une correction purement technique peut relever de `HCA`. Une reformulation plus large, une refactorisation ou une aide plus significative sur l’expression du code relèvent plutôt de `HCE`.

---

### Cas 10 - Fonction générée par IA puis adaptée

**Situation**  
L’IA génère une fonction, une logique métier ou une portion substantielle de code, ensuite corrigée ou optimisée par un humain.

**Label recommandé**  
`ACE`

**Justification**  
Lorsque l’IA produit une partie structurante du comportement ou de la logique, elle contribue au fond du code.

---

### Cas 11 - Code largement généré puis validé

**Situation**  
L’essentiel du code provient de l’IA, l’humain sélectionnant, testant ou ajustant légèrement le résultat.

**Label recommandé**  
`AIC`

**Justification**  
La génération domine le processus. La validation humaine ne suffit pas à rétablir une maîtrise intellectuelle substantielle sur l’ensemble du contenu.

---

## Cas liés aux images

### Cas 12 - Image créée sans IA

**Situation**  
Une image est conçue et produite sans recours à un générateur IA.

**Label recommandé**  
`HUC`

**Justification**  
La création relève entièrement d’un processus humain.

---

### Cas 13 - Image générée par IA avec retouches mineures

**Situation**  
Une image est générée par IA puis légèrement recadrée, nettoyée ou ajustée.

**Label recommandé**  
`AIC`

**Justification**  
Des retouches mineures ne changent pas la logique principale de production.

---

### Cas 14 - Image générée par IA puis profondément retravaillée

**Situation**  
Une image issue d’une génération IA fait ensuite l’objet d’une intervention humaine importante : recomposition, ajout d’éléments, modification significative du sujet ou reconstruction visuelle.

**Label recommandé**  
`ACE`

**Justification**  
L’image résulte alors d’une co-construction substantielle.

---

## Cas liés aux documents composites

### Cas 15 - Article avec texte humain et image IA

**Situation**  
Un article est rédigé par un humain, mais l’illustration principale est générée par IA.

**Label recommandé**  
`HUC`, `HCA`, `HCE` ou `ACE` pour le texte selon le cas, et `AIC` pour l’image

**Justification**  
Un étiquetage modulaire est préférable lorsque plusieurs composants du document relèvent de logiques différentes.

---

### Cas 16 - Document mixte avec plusieurs méthodes de production

**Situation**  
Un document combine, par exemple, une introduction humaine, un tableau reformulé par IA et une image générée.

**Label recommandé**  
Étiquetage modulaire recommandé  
ou label global prudent si un seul label doit être affiché

**Justification**  
Pour les contenus hétérogènes, un seul label global peut masquer la réalité du processus. Si un label unique est imposé, il doit rester prudent.

---

### Cas 17 - Choix d’un label global unique

**Situation**  
Le support de publication ne permet d’afficher qu’un seul label pour un document dont les composants ont été produits différemment.

**Label recommandé**  
Le label global le plus prudent compatible avec l’ensemble

**Justification**  
Il vaut mieux simplifier avec prudence que donner une image faussement plus humaine du processus réel.

---

## Cas liés au travail collectif

### Cas 18 - Travail d’équipe avec usages IA différents

**Situation**  
Plusieurs personnes contribuent au même document, avec des niveaux d’usage de l’IA différents selon les sections ou les rôles.

**Label recommandé**  
Étiquetage modulaire si possible  
sinon label global prudent

**Justification**  
Le protocole décrit un processus de production. Si les méthodes divergent selon les parties, un affichage différencié est plus fidèle.

---

### Cas 19 - Validation humaine d’un contenu très généré

**Situation**  
Une équipe humaine relit, approuve et publie un contenu largement généré par IA.

**Label recommandé**  
`AIC`

**Justification**  
La validation humaine ne transforme pas à elle seule un contenu majoritairement généré en contenu intellectuellement humain.

---

## Frontières d’interprétation importantes

### HCA ou HCE ?

Choisir `HCA` si l’IA reste cantonnée à une correction technique sans effet notable sur le style, le ton ou la formulation.

Choisir `HCE` si l’IA améliore réellement l’expression, reformule, traduit, fluidifie ou réécrit certains segments.

---

### HCE ou ACE ?

Choisir `HCE` si l’humain conserve seul le fond, le plan, l’intention et la structure intellectuelle.

Choisir `ACE` dès que l’IA intervient de manière significative sur le plan, l’angle, la hiérarchisation des idées, le premier jet structurant ou la construction du raisonnement.

---

### ACE ou AIC ?

Choisir `ACE` si l’humain garde un rôle fort de pilotage, de transformation et de co-construction.

Choisir `AIC` si l’IA produit l’essentiel du contenu final et que l’intervention humaine se limite principalement à demander, choisir, valider ou ajuster légèrement.

---

## Cas à documenter ultérieurement

Cette section peut être enrichie au fil du projet. Des développements complémentaires pourront porter sur :

- l’audio ;
- la vidéo ;
- les présentations ;
- les supports pédagogiques ;
- les contenus interactifs ;
- les usages en entreprise ;
- les usages institutionnels ;
- les métadonnées et formes d’intégration publique.

---

## Méthode de mise à jour

Les nouveaux cas peuvent être proposés :

- via une issue ;
- via une pull request ;
- via un retour d’usage documenté ;
- via une contradiction observée dans la documentation existante.

Merci de consulter `CONTRIBUTING.md` avant de proposer une modification.

---

## Remarque finale

Ce document n’a pas vocation à épuiser tous les cas possibles. Il sert à stabiliser des repères d’interprétation dans l’esprit de TCP/UP : sincérité déclarative, prudence, lisibilité publique et responsabilité humaine.
