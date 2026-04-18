# Spécification TCP/UP

Version : 0.1.0  
Statut : brouillon public

## 1. Objet

TCP/UP est un protocole déclaratif de transparence destiné à rendre visible le rôle respectif de l’humain et de l’intelligence artificielle dans la création d’un contenu.

Cette spécification constitue une **synthèse courte** du protocole.  
Les développements détaillés, exemples, arbitrages, formulations éditoriales et renvois visuels sont maintenus dans le dossier [`docs/`](./docs), avec des ressources graphiques éventuelles dans [`assets/`](./assets).

## 2. Périmètre

TCP/UP peut s’appliquer à :

- des textes,
- des images,
- des contenus audio,
- des contenus vidéo,
- du code,
- des contenus composites ou multimodaux.

TCP/UP n’est ni un outil de détection, ni une preuve technique, ni une certification officielle.

## 3. Modèle conceptuel

TCP/UP distingue deux dimensions :

- **Fond** : idées, intention, raisonnement, structure, angle, argumentation
- **Forme** : rédaction, formulation, rendu, exécution, habillage final

## 4. Labels

### HUC - Human Content
Aucune IA n’intervient dans la création du contenu, ni pour le fond ni pour la forme.

### HCA - Human-Centric Assistance
Le contenu reste humain. L’IA intervient uniquement pour une correction technique sans modification éditoriale.

### HCE - Human-Centric Editing
Le fond, l’intention et l’architecture intellectuelle sont humains. L’IA aide à la formulation, au ton, à la reformulation, à la traduction ou à la présentation.

### ACE - AI-Centric Editing
L’humain et l’IA co-construisent de manière substantielle le contenu. L’IA participe au plan, aux idées, à l’angle, à la structure ou à un premier brouillon significatif.

### AIC - AI Content
Le contenu est principalement ou entièrement généré par IA. L’humain se limite au cadrage, à la sélection ou à une validation légère.

## 5. Règles d’arbitrage

### Règle de prudence
En cas d’hésitation entre deux labels, choisir le label attribuant la plus grande part à l’IA.

### Règle de la page blanche
Si l’IA a fourni la première structure intellectuelle significative, le contenu ne devrait normalement pas revenir vers la série H.

### Règle de bonne foi
TCP/UP repose sur une auto-déclaration honnête et responsable du publieur.

## 6. Limites

TCP/UP :

- ne remplace pas une analyse juridique,
- ne garantit pas l’exactitude factuelle,
- ne prouve pas techniquement l’origine d’un contenu,
- ne vaut pas certification tierce.

## 7. Référentiel contributif

Le dossier [`docs/`](./docs) constitue l’espace principal de travail et de contribution du protocole ; [`assets/`](./assets) peut contenir les visuels de référence utiles à la documentation.

Les contributions sont particulièrement attendues sur :

- `docs/logique-labels.md`
- `docs/documentation.md`
- `docs/faq.md`
- `docs/ethique.md`
- `docs/labels/`

## 8. Ressources visuelles

Le dossier [`assets/`](./assets) peut notamment contenir :

- les badges des labels,
- les logos de référence,
- les icônes associées au protocole,
- des visuels de documentation ou de démonstration.

Ces ressources ne remplacent pas la spécification textuelle, mais peuvent en faciliter la lecture, l’appropriation et la diffusion.

## 9. Documents liés

- [`README.md`](./README.md)
- [`CASES.md`](./CASES.md)
- [`CONTRIBUTING.md`](./CONTRIBUTING.md)
- [`GOVERNANCE.md`](./GOVERNANCE.md)
