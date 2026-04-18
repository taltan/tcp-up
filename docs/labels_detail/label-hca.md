# Détails Label HCA - TCP/UP

## Table des matières

- [Label HCA](#label-hca)
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



## Label HCA

**L'humain écrit, l'IA nettoie**  
*Human-Centric Assistance*

### Badge simple

**Couleur (_co)**  
![Badge HCA Couleur](../img/badges/svg/badge_hca_co.svg)

**Transp. Couleur (_tr_co)**  
![Badge HCA Transparent Couleur](../img/badges/svg/badge_hca_tr_co.svg)

### Badge complet

Déclaration : **[TCP/UP: HCA]** (Human-Centric Assistance)  
Fond : humain | Forme : humaine avec correction technique  
IA utilisée exclusivement pour la correction orthographique, grammaticale ou syntaxique.

### Version texte pur

```
[TCP/UP: HCA]
```

### Bloc signature

```
Déclaration : [TCP/UP: HCA]
> Fond : humain | Forme : humaine avec correction technique 
> IA utilisée exclusivement pour la correction orthographique, grammaticale ou syntaxique
```

### Métadonnées HTML

```html
<head>
    <meta name="tcp-up:label" content="[TCP/UP: HCA]">
    <meta name="tcp-up:content-origin" content="human">
    <meta name="tcp-up:ai-role" content="correction technique">
</head>
```

Besoin d'une variante Noir & Blanc ou d'un format spécifique ?  
[Voir toutes les variantes](download.html)

> TCP/UP est un protocole déclaratif. Le label affiché correspond à l’auto-déclaration de l’auteur sur son processus de création

![Logo HCA](../img/logo_hca.webp)

## Philosophie

L'humain écrit, l'IA nettoie (orthographe et syntaxe).

> « L'IA est mon correcteur. Elle garantit la propreté du texte sans jamais toucher à ma substance grise. »

## Définition

Ce contenu est d’origine humaine. L’IA est intervenue exclusivement pour la correction technique (orthographe, grammaire, ponctuation ou syntaxe), sans reformulation du fond ni modification de l’intention.

## Cas d’usage

Documents officiels, travaux académiques, expertises juridiques ou médicales, mail pro, article de presse, rapport d'expertise, etc.

## Exemples concrets

**Thèse ou Mémoire**  
Le texte est le fruit de vos recherches, l'IA vérifie la concordance des temps et les accords complexes.

**Contrat juridique**  
Rédigé par un avocat, passé au correcteur pour éviter toute coquille fatale.

**Mail pro**  
Un contenu original dont on veut simplement garantir le « zéro faute ».

**Code informatique**  
Un script écrit par un développeur et passé dans un « linter » pour nettoyer la syntaxe.

## Cas limites fréquents

**« J'ai laissé l'IA reformuler une phrase maladroite. C'est HCA ? »**  
Non. Dès que l'IA intervient sur le style ou la formulation, même sur une seule phrase, le label HCE devient plus approprié. HCA est strictement limité à la correction technique (orthographe, grammaire, ponctuation).

**« J'ai utilisé l'IA pour vérifier l'accord d'un participe passé complexe. HCA ? »**  
Oui. La vérification grammaticale ponctuelle entre dans le cadre de la correction technique. Vous restez maître du choix final et l'IA n'a pas modifié votre style.

**« Mon correcteur a automatiquement remplacé des doubles espaces. HCA ? »**  
Oui. Ce type de nettoyage purement formel, sans impact sur le sens ou la structure, relève bien du label HCA.

*Plus de détails sur les cas critiques et les arbitrages [ici](/pages/documentation.html#dc-4)*

## Exemples de Prompt

**Prompt 1 :**  
« Corrige uniquement les fautes d'orthographe et de grammaire du texte suivant sans modifier mon style ni mes tournures de phrases : [Texte] »

**Prompt 2 :**  
« Relis ce rapport juridique et signale-moi les éventuelles répétitions ou erreurs de ponctuation, mais ne reformule aucune phrase »

**Prompt 3 :**  
« Vérifie la cohérence des temps et des accords dans ce paragraphe, mais ne change aucun mot. »

**Prompt 4 :**  
« Signale les éventuelles fautes de frappe ou erreurs de ponctuation dans ce mail professionnel, sans en altérer le ton. »
