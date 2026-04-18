# Politique de sécurité

## Objet

Ce dépôt contient la documentation, les modèles, les ressources et les éléments de gouvernance du protocole TCP/UP.

Cette politique explique comment signaler :

- une vulnérabilité technique affectant le dépôt ou ses ressources associées ;
- un usage abusif susceptible d’induire le public en erreur ;
- une exposition involontaire d’informations sensibles ;
- un problème de sécurité touchant les fichiers, assets, modèles ou mécanismes de diffusion liés au projet.

Cette politique ne transforme pas TCP/UP en service de certification, ni en dispositif de garantie générale de cybersécurité.

---

## Périmètre

Cette politique couvre en priorité :

- le dépôt GitHub TCP/UP ;
- les fichiers de documentation ;
- les modèles situés dans `.github/` ;
- les assets distribués dans le dépôt ;
- les exemples de code, snippets HTML ou métadonnées fournis dans la documentation ;
- le site public TCP/UP, lorsqu’un problème signalé est directement lié au projet.

---

## Hors périmètre

Les éléments suivants ne relèvent pas en priorité de cette politique de sécurité :

- les débats doctrinaux sur les labels ;
- les désaccords éditoriaux ordinaires ;
- les demandes générales de clarification ;
- les propositions d’évolution du protocole ;
- les faux positifs d’interprétation du protocole dans un contenu tiers ;
- les obligations légales propres à des plateformes, CMS ou services tiers.

Pour ces sujets, privilégiez les issues GitHub, `CASES.md`, la documentation ou les canaux de contribution ordinaires.

---

## Types de signalements attendus

Vous pouvez utiliser cette politique si vous découvrez, par exemple :

- une fuite accidentelle d’information sensible dans le dépôt ;
- un secret, un jeton, un mot de passe, un identifiant ou un fichier publié par erreur ;
- un snippet technique dangereux ou trompeur dans la documentation ;
- une vulnérabilité sur le site ou dans un code d’exemple fourni officiellement ;
- un asset officiel pouvant être détourné de manière trompeuse sans garde-fou ;
- un usage du nom, des badges ou des logos TCP/UP créant un risque sérieux de confusion sur une validation officielle ;
- un mécanisme d’intégration technique recommandé qui expose inutilement les utilisateurs.

---

## Ce qui ne doit pas être publié publiquement

Merci de ne pas ouvrir d’issue publique si votre signalement contient :

- des informations sensibles ;
- des identifiants ;
- des données personnelles ;
- une méthode d’exploitation détaillée avant correction ;
- un lien direct vers une charge malveillante ;
- une preuve de concept dangereuse immédiatement réutilisable.

Dans ces cas, utilisez un canal de contact direct.

---

## Comment signaler un problème

Merci d’envoyer votre signalement à :

**contact@tcp-up.org**

Objet recommandé :

`[SECURITY] Résumé court du problème`

Merci d’inclure, si possible :

- une description claire du problème ;
- le périmètre concerné : dépôt, site, fichier, asset ou snippet ;
- les étapes permettant de comprendre ou reproduire le problème ;
- l’impact estimé ;
- toute suggestion de mitigation ;
- un moyen de vous recontacter.

---

## Ce que nous ferons

Dans la mesure du possible, nous nous engageons à :

- accuser réception du signalement dans un délai raisonnable ;
- analyser le périmètre et la gravité du problème ;
- demander des précisions si nécessaire ;
- corriger, retirer, clarifier ou limiter l’élément concerné lorsque cela est justifié ;
- informer le déclarant de l’état d’avancement, dans la mesure du possible.

Aucun délai contractuel n’est garanti.

---

## Divulgation responsable

Nous demandons une divulgation responsable :

- laissez un délai raisonnable pour analyser et corriger le problème ;
- évitez la publication immédiate de détails exploitables ;
- évitez tout accès non autorisé, extraction massive ou perturbation de service ;
- n’exploitez pas la vulnérabilité au-delà de ce qui est strictement nécessaire pour la démontrer de bonne foi.

---

## Pas de programme de bug bounty

Ce projet ne propose actuellement :

- aucun bug bounty ;
- aucune récompense financière ;
- aucun engagement de réponse prioritaire ;
- aucune relation contractuelle implicite avec les personnes qui signalent un problème.

Les signalements de bonne foi sont néanmoins appréciés.

---

## Spécificité du projet TCP/UP

TCP/UP est un protocole déclaratif fondé sur la bonne foi, la transparence et la responsabilité humaine.

En conséquence, certains signalements concerneront moins une faille logicielle classique qu’un risque de confusion, de mésusage des badges, d’ambiguïté de présentation ou de faux sentiment de validation officielle.

Les signalements pertinents peuvent donc porter aussi sur :

- la présentation trompeuse d’un badge ou d’un logo officiel ;
- une formulation susceptible de faire croire à une certification formelle ;
- une recommandation technique qui contredirait la logique déclarative du protocole ;
- un asset réutilisable sans contexte, de manière dangereusement ambiguë.

---

## Versioning et correctifs

Lorsqu’un problème le justifie, la correction peut prendre plusieurs formes :

- mise à jour de la documentation ;
- retrait ou modification d’un asset ;
- clarification d’un exemple ;
- correction d’un template ;
- ajustement du site ;
- mention dans `CHANGELOG.md`.

---

## Conseils aux réutilisateurs

Si vous réutilisez des badges, labels, snippets ou formulations TCP/UP :

- ne laissez pas entendre qu’il s’agit d’une certification officielle ;
- ne modifiez pas un badge de manière à en changer le sens ;
- vérifiez vos intégrations techniques avant mise en production ;
- relisez les parties de documentation relatives à la bonne foi, à la responsabilité et aux limites du protocole.

---

## Remarque finale

Cette politique de sécurité vise à réduire les risques techniques, informationnels et réputationnels autour du dépôt et de ses ressources. Elle ne constitue ni un audit de sécurité, ni une garantie d’absence de faille, ni un avis juridique.
