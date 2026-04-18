# Détails Label AIC - TCP/UP

## Table des matières

- [Label AIC](#label-aic)
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



## Label AIC

**L'automatisation totale**  
*AI Content*

### Badge simple

**Couleur (_co)**  
![Badge AIC Couleur](../img/badges/svg/badge_aic_co.svg)

**Transp. Couleur (_tr_co)**  
![Badge AIC Transparent Couleur](../img/badges/svg/badge_aic_tr_co.svg)

### Badge complet

Déclaration : **[TCP/UP: AIC]** (AI Content)  
Fond : généré majoritairement ou intégralement par IA | Forme : générée par IA  
Contenu produit par IA avec intervention humaine limitée

### Version texte pur

```
[TCP/UP: AIC]
```

### Bloc signature

```
Déclaration : [TCP/UP: AIC] (AI Content)
> Fond : généré majoritairement ou intégralement par IA | Forme : générée par IA
> Contenu produit par IA avec intervention humaine limitée
```

### Métadonnées HTML

```html
<head>
    <meta name="tcp-up:label" content="[TCP/UP: AIC]">
    <meta name="tcp-up:content-origin" content="synthetic">
    <meta name="tcp-up:ai-role" content="generation">
</head>
```

Besoin d'une variante Noir & Blanc ou d'un format spécifique ?  
[Voir toutes les variantes](download.html)

> TCP/UP est un protocole déclaratif. Le label affiché correspond à l’auto-déclaration de l’auteur sur son processus de création

![Logo AIC](../img/logo_aic.webp)

## Philosophie

L'automatisation totale.

> « 100% synthétique. L'humain a défini le besoin, la machine a exécuté la création. »

## Définition

Ce contenu a été généré majoritairement ou intégralement par une intelligence artificielle. L’intervention humaine se limite principalement à l’instruction, à la sélection, à l’assemblage ou à la diffusion.

## Cas d’usage

Illustration, prototypage rapide, traduction de masse, data-visualisation, résumés automatiques, génération de code, etc.

## Exemples concrets

**Illustration**  
Générer une image de logo.

**Traduction brute**  
Traduire un manuel technique de 200 pages pour un usage interne immédiat (sans relecture).

**Génération de code**  
Demander à l'IA de générer un script Bash complet pour surveiller le taux d'occupation d'une partition de logs et envoyer une alerte.

**Résumé automatique**  
Demander à un outil de résumer un rapport de 50 pages en 3 paragraphes sans intervention humaine.

## Cas limites fréquents

**« J'ai sélectionné le meilleur parmi trois textes générés par IA. C'est AIC ? »**  
Oui. Votre intervention se limite à de la sélection, pas à de la co‑création sur le fond ou la forme. Le contenu reste intégralement généré.

**« J'ai changé trois mots dans un texte généré. Puis-je passer à ACE ? »**  
Non. Une modification cosmétique ne constitue pas une co‑construction substantielle. Pour revendiquer ACE, votre intervention doit avoir influencé le fond ou la structure de manière significative.

**« J'ai donné un prompt très détaillé (500 mots) décrivant exactement ce que je voulais. AIC ou ACE ? »**  
Si votre prompt contient déjà toute l'architecture intellectuelle (thèse, arguments, structure), vous pouvez envisager HCE. Si l'IA a néanmoins introduit des angles ou des formulations qui influencent le sens final, ACE reste plus prudent. Un simple prompt, même long, qui dit "fais‑moi un article sur X" relève d'AIC.

*Plus de détails sur les cas critiques et les arbitrages [ici](/pages/documentation.html#dc-4)*

## Exemples de Prompt

**Prompt 1 :**  
« Génère une image de bureau moderne sous la pluie, style cinématographique, format 16:9 »

**Prompt 2 :**  
« Écris un script Bash qui vérifie si la partition /var/log dépasse 90% d'utilisation et envoie un mail d'alerte à l'admin si c'est le cas »

**Prompt 3 :**  
« Résume ce rapport annuel de 50 pages en un paragraphe de 5 lignes, en te concentrant uniquement sur les chiffres clés. »

**Prompt 4 :**  
« Génère un poème dans le style de Baudelaire sur le thème de la mer et de la mélancolie. »
