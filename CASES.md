# CASES - Cas d’usage et arbitrages transversaux

Ce document rassemble des cas types pour aider à interpréter le protocole TCP/UP.

Il complète les documents du dossier [`docs/`](./docs), qui constituent le cœur contributif du projet. Les visuels de référence éventuellement associés peuvent être conservés dans [`assets/`](./assets).

## Rôle de ce fichier

`CASES.md` a vocation à :

- documenter des arbitrages fréquents,
- pointer des zones de tension entre labels,
- orienter les discussions ouvertes en issue,
- servir de passerelle entre les principes généraux et les fichiers détaillés de `docs/`.

Les propositions de nouveaux cas peuvent donner lieu ensuite à des mises à jour dans :

- `docs/documentation.md`
- `docs/faq.md`
- `docs/logique-labels.md`
- `docs/labels/*.md`

---

## 1. Correction orthographique uniquement

**Situation**  
Un texte humain est relu par un correcteur automatique qui corrige uniquement orthographe, accords ou ponctuation.

**Label recommandé**  
**HCA**

**Pourquoi**  
Le fond et la forme éditoriale restent humains. L’IA ne joue qu’un rôle de correction technique.

---

## 2. Reformulation de style

**Situation**  
L’auteur demande une reformulation plus fluide, diplomatique ou lisible, sans changement intentionnel du fond.

**Label recommandé**  
**HCE**

**Pourquoi**  
Le fond reste humain mais la formulation finale est assistée par IA.

---

## 3. Traduction avec relecture humaine

**Situation**  
Un texte d’origine humaine est traduit par IA puis relu et validé par son auteur.

**Label recommandé**  
**HCE**

**Pourquoi**  
L’idée reste humaine, mais la forme dans la langue cible est produite par l’outil.

---

## 4. Plan proposé par IA

**Situation**  
L’IA suggère un plan ou une structure avant une rédaction entièrement humaine.

**Label recommandé**  
**ACE**

**Pourquoi**  
L’IA a contribué à l’architecture intellectuelle initiale.

---

## 5. Brouillon généré puis fortement réécrit

**Situation**  
L’IA génère un texte complet, ensuite largement repris, restructuré et enrichi par un humain.

**Label recommandé**  
**ACE**

**Pourquoi**  
Même retravaillée, la première impulsion structurelle vient de l’IA.

---

## 6. Sélection parmi plusieurs sorties IA

**Situation**  
L’utilisateur génère plusieurs textes et choisit le meilleur sans réécriture substantielle.

**Label recommandé**  
**AIC**

**Pourquoi**  
La sélection seule ne constitue pas une co-construction forte.

---

## 7. Mega-prompt très détaillé

**Situation**  
Le prompt contient déjà l’architecture intellectuelle, les arguments, le ton et les contraintes du texte.

**Label recommandé**  
**HCE** ou **ACE** selon influence réelle de l’IA

**Pourquoi**  
Si l’IA ne fait que mettre en mots une structure déjà entièrement pensée, HCE peut se défendre. Si elle réoriente la structure ou ajoute des angles non prévus, ACE est plus prudent.

---

## 8. Publication sans relecture substantielle

**Situation**  
Le contenu généré par IA est publié sans validation critique approfondie.

**Label recommandé**  
**AIC**

**Pourquoi**  
L’humain ne peut pas revendiquer une responsabilité éditoriale forte sans relecture réelle.

---

## 9. Code généré puis optimisé

**Situation**  
Du code est généré par IA, puis corrigé et intégré par un développeur.

**Label recommandé**  
**ACE**

**Pourquoi**  
Dans le code, la logique et sa forme sont étroitement liées.

---

## 10. Projet composite

**Situation**  
Un projet comprend différents composants, par exemple texte HCE, image AIC et code ACE.

**Label recommandé**  
**Label global prudent** ou **labellisation par composant**

**Pourquoi**  
Le composant le plus automatisé ne doit pas être invisibilisé.

---

## 11. Cas avec support visuel

**Situation**  
Un contenu textuel est humain, mais il utilise des badges, logos, icônes ou éléments visuels issus des ressources du projet pour clarifier sa labellisation.

**Label recommandé**  
Le label du contenu principal ne change pas du seul fait de l’usage d’un asset visuel de référence.

**Pourquoi**  
Les assets de [`assets/`](./assets) servent à représenter ou communiquer le protocole ; ils ne modifient pas à eux seuls la nature du processus de création du contenu principal.

---

## 12. Asset généré ou retravaillé par IA

**Situation**  
Un badge, une icône ou un visuel documentaire est créé ou modifié avec assistance IA pour illustrer le protocole.

**Label recommandé**  
À documenter si le visuel devient substantiel dans l’explication publique, sans confondre le statut de l’asset avec celui du protocole lui-même.

**Pourquoi**  
Un asset peut avoir son propre mode de production. Il faut éviter d’en déduire mécaniquement la qualification du contenu doctrinal qui l’accompagne.

---

## Contribuer à ce fichier

Si vous souhaitez proposer un nouveau cas :

1. ouvrez une issue,
2. décrivez précisément le workflow,
3. expliquez le point d’ambiguïté,
4. proposez un label et une justification,
5. indiquez quel fichier de `docs/` devrait idéalement être mis à jour,
6. mentionnez l’asset concerné si le cas implique un élément visuel de `assets/`.
