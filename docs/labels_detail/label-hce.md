# Détails Label HCE - TCP/UP

## Table des matières

- [Label HCE](#label-hce)
  - [Badge simple](#badge-simple)
  - [Badge complet](#badge-complet)
  - [Version texte pur](#version-texte-pur)
  - [Bloc signature](#bloc-signature)
  - [Métadonnées HTML](#métadonnées-html)
- [Philosophie](#philosophie)
- [Définition](#définition)
- [Cas d’usage](#cas-dusage)
- [Exemples concrets](#exemples-concrets)
- [Cas limites fréquents](#cas-limites-fréquents)
- [Exemples de Prompt](#exemples-de-prompt)

---



## Label HCE

**L'humain pense, l'IA polit**  
*Human-Centric Editing*

### Badge simple

**Couleur (_co)**  
![Badge HCE Couleur](../img/badges/svg/badge_hce_co.svg)

**Transp. Couleur (_tr_co)**  
![Badge CHE Transparent Couleur](../img/badges/svg/badge_hce_tr_co.svg)

### Badge complet

Déclaration : **[TCP/UP: HCE]** (Human-Centric Editing)  
Fond : humain | Forme : assistée par IA  
L’intention, les idées et la structure sont humaines, l’IA a aidé à la formulation ou à la mise en forme

### Version texte pur

```
[TCP/UP: HCE]
```

### Bloc signature

```
Déclaration : [TCP/UP: HCE] (Human-Centric Editing)
> Fond : humain | Forme : assistée par IA
> L’intention, les idées et la structure sont humaines, l’IA a aidé à la formulation ou à la mise en forme
```

### Métadonnées HTML

```html
<head>
    <meta name="tcp-up:label" content="[TCP/UP: HCE]">
    <meta name="tcp-up:content-origin" content="human">
    <meta name="tcp-up:ai-role" content="formulation assistee">
</head>
```

Besoin d'une variante Noir & Blanc ou d'un format spécifique ?  
[Voir toutes les variantes](download.html)

> TCP/UP est un protocole déclaratif. Le label affiché correspond à l’auto-déclaration de l’auteur sur son processus de création

![Logo HCE](../img/logo_hce.webp)

## Philosophie

L'humain pense, l'IA polit.

> « L'IA est mon artisan. Elle façonne la matière brute que je lui fournis pour lui donner sa forme finale. »

## Définition

Ce contenu repose sur un fond intellectuel d’origine humaine. L’IA est intervenue pour aider à la formulation, à la reformulation, à l’adaptation du ton ou à la mise en forme, sans être à l’origine du fond

## Cas d’usage

Productivité bureautique, transformation de formats, communication d'entreprise, articles, billet de blog, rapports, mails pro complexe, post LinkedIn, etc.

## Exemples concrets

**Compte rendu**  
Transformer 15 minutes de notes de réunion désordonnées en un compte rendu structuré (Action/Décision/Info).

**Réécriture de ton**  
Transformer un email interne un peu sec en un message diplomatique et professionnel pour un client.

**Vulgarisation**  
Prendre un texte technique complexe et demander à l'IA de le simplifier pour un public de néophytes.

**Script vidéo**  
Transformer un article de blog écrit par vos soins en un script dynamique pour une vidéo YouTube.

## Cas limites fréquents

**« J'ai utilisé l'IA pour traduire, puis j'ai relu. C'est HCE ? »**  
Oui, si vous avez vérifié la fidélité de la traduction sans la réécrire entièrement.

**« J'ai dicté mes idées à l'IA qui les a mises en forme. C'est HCE ? »**  
Oui, c'est l'essence même du label HCE : intention humaine, exécution assistée.

**« L'IA a suggéré une meilleure structure. Je l'ai acceptée. HCE ? »**  
Non, passez à ACE. L'IA a contribué au fond (structure).

*Plus de détails sur les cas critiques et les arbitrages [ici](/pages/documentation.html#dc-4)*

## Exemples de Prompt

**Prompt 1 :**  
« Voici mes notes de réunion prises à la volée : [Notes]. Transforme-les en un compte rendu propre avec un résumé des décisions, une liste des actions à mener et une structure par points clés »

**Prompt 2 :**  
« Reformule cet email pour le rendre plus chaleureux et empathique, tout en conservant les informations factuelles suivantes : [Détails] »

**Prompt 3 :**  
« À partir de ce plan détaillé que j'ai rédigé [insérer plan], rédige une introduction fluide et un développement structuré en conservant exactement l'ordre de mes arguments. »

**Prompt 4 :**  
« Voici une série de messages vocaux retranscrits [texte]. Réorganise-les en un article de blog cohérent, avec une introduction et une conclusion, sans ajouter d'idées nouvelles. »
