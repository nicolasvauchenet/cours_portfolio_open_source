# Fiche 1 — Inclusion et accessibilité numérique

---

## Introduction

L’accessibilité numérique, c’est **le droit pour chacun d’utiliser le web**,  
quelle que soit sa situation : handicap visuel, auditif, moteur, cognitif, temporaire ou contextuel.  
Concevoir un site ou une application inclusive n’est donc pas un simple confort d’usage,  
c’est une **obligation légale**, mais surtout **un acte de justice numérique**.

Cette fiche vise à comprendre les **principes**, les **normes** et les **bonnes pratiques**  
qui permettent de concevoir des expériences accessibles à tous, tout en améliorant la qualité générale du produit.

---

## 1. Comprendre les enjeux de l’accessibilité

### 1.1 Une question de droit

En France et en Europe, l’accessibilité numérique est encadrée par :

- la **loi du 11 février 2005** sur l’égalité des droits et des chances,
- le **RGAA** (Référentiel Général d’Amélioration de l’Accessibilité),
- la **directive européenne (UE 2016/2102)** sur l’accessibilité des sites publics.

Tout service numérique public doit être accessible, et les acteurs privés y sont de plus en plus incités.  
Le non-respect de ces obligations peut entraîner des sanctions, mais surtout une **exclusion d’usagers**.

### 1.2 Une question d’usage

L’accessibilité ne concerne pas uniquement les personnes en situation de handicap permanent :

- une connexion lente,
- un écran fissuré,
- un utilisateur fatigué ou distrait,  
  sont autant de contextes d’usage où un design accessible améliore l’expérience de tous.

### 1.3 Une question de qualité

Un produit accessible est souvent :

- plus ergonomique,
- plus performant,
- mieux référencé,
- et plus maintenable à long terme.  
  L’accessibilité n’est donc pas un surcoût, mais un **facteur de qualité logicielle**.

---

## 2. Les référentiels et normes

### 2.1 WCAG — Web Content Accessibility Guidelines

Norme internationale publiée par le **W3C**.  
Les **WCAG 2.1** (en cours d’évolution vers 2.2) s’appuient sur quatre grands principes (acronyme **POUR**) :

| Principe           | Signification                                    | Exemple                              |
|--------------------|--------------------------------------------------|--------------------------------------|
| **Perceptible**    | L’information doit être visible ou audible.      | Texte alternatif pour les images.    |
| **Opérable**       | L’utilisateur doit pouvoir naviguer facilement.  | Navigation clavier, focus visible.   |
| **Compréhensible** | Le contenu et la structure doivent être clairs.  | Libellés explicites, langage simple. |
| **Robuste**        | Le code doit être compatible avec divers outils. | Respect du HTML sémantique.          |

### 2.2 RGAA — Référentiel Général d’Amélioration de l’Accessibilité

Version française des WCAG adaptée au contexte réglementaire hexagonal.  
Il définit **106 critères** regroupés par thèmes : images, liens, formulaires, scripts, etc.  
Les niveaux de conformité sont :

- **A** (base minimale),
- **AA** (niveau recommandé),
- **AAA** (excellence, rarement exigé).

### 2.3 Autres standards complémentaires

- **ARIA (Accessible Rich Internet Applications)** :  
  attributs permettant d’améliorer la compatibilité avec les lecteurs d’écran.
- **ISO 9241-210** : ergonomie des interactions homme-machine.
- **Section 508** : équivalent américain pour les administrations publiques.

---

## 3. Bonnes pratiques de conception inclusive

### 3.1 Structure et contenu

- Utiliser une **hiérarchie claire des titres** (`<h1>`, `<h2>`, `<h3>`).
- Fournir des **textes alternatifs** (`alt`) pertinents pour les images.
- Décrire les **liens et boutons** de façon explicite (“Voir le profil” plutôt que “Cliquez ici”).
- Utiliser des **listes et tableaux sémantiques**.

### 3.2 Couleur et contraste

- Vérifier le contraste entre texte et fond (minimum 4.5:1 pour le niveau AA).
- Ne pas transmettre une information uniquement par la couleur.
- Utiliser des **indicateurs visuels complémentaires** (icônes, soulignements, labels).

### 3.3 Navigation et clavier

- Tous les éléments interactifs doivent être accessibles au **clavier seul** (tabulation, espace, entrée).
- Le **focus visible** doit être conservé.
- Les menus déroulants, modales et carrousels doivent être pilotables sans souris.

### 3.4 Médias et contenus dynamiques

- Fournir des **sous-titres** pour les vidéos.
- Proposer une **transcription textuelle** pour les contenus audio.
- Utiliser des balises **`aria-live`** pour les messages dynamiques (ex : alertes, notifications).

### 3.5 Formulaires

- Associer chaque champ à un label clair.
- Prévoir des messages d’erreur explicites.
- Indiquer les champs obligatoires et proposer une aide à la saisie.

---

## 4. Tester et mesurer l’accessibilité

### 4.1 Outils de test

- **Lighthouse (Chrome DevTools)** : audit automatique incluant une section “Accessibility”.
- **axe DevTools** ou **Accessibility Insights** : extensions pour Chrome/Edge.
- **Wave** (WebAIM) : outil en ligne rapide pour visualiser les erreurs.
- **NVDA / VoiceOver** : lecteurs d’écran pour tester la compatibilité.

### 4.2 Méthodes de vérification

- Faire tester par **plusieurs profils d’utilisateurs**.
- Alterner tests manuels et automatiques.
- Utiliser des checklists WCAG ou RGAA simplifiées.
- Documenter les problèmes et leur résolution dans un **rapport d’accessibilité**.

---

## 5. Activités pratiques

### Atelier 1 — Mini-audit d’accessibilité

- Choisissez un site ou une page web existante.
- Évaluez :
    - la structure sémantique,
    - le contraste,
    - la navigation clavier,
    - la présence de textes alternatifs.
- Rédigez une courte fiche “constats et pistes d’amélioration”.

### Atelier 2 — Refonte inclusive d’une page

- Reprenez une page de votre propre projet.
- Corrigez les éléments problématiques repérés :
    - ajout de labels,
    - correction de contrastes,
    - amélioration du focus.
- Comparez le score Lighthouse avant et après.

---

## Livrables attendus

- Fiche d’audit d’accessibilité (1 page).
- Capture ou lien vers une version corrigée d’une page web.
- Rapport synthétique sur les améliorations effectuées (5 à 10 lignes).

---

## Évaluation

| Critère                                     | Description                                             | Pondération |
|---------------------------------------------|---------------------------------------------------------|-------------|
| Compréhension des principes d’accessibilité | Identification correcte des problèmes et critères       | 40 %        |
| Mise en œuvre technique                     | Qualité des corrections et respect des bonnes pratiques | 40 %        |
| Clarté du rapport                           | Organisation, pertinence des explications, présentation | 20 %        |

---

## Pour aller plus loin

- Consulter le site officiel : [https://accessibilite.numerique.gouv.fr](https://accessibilite.numerique.gouv.fr).
- Lire : *Accessibilité web – Normes et bonnes pratiques* (Eyrolles, 2022).
- Explorer : [WebAIM – WCAG Quick Reference](https://webaim.org/standards/wcag/).
- S’intéresser aux outils de design inclusif : *Colorable*, *Contrast Checker*, *Stark* (Figma plugin).

---

## Message clé

> L’accessibilité n’est pas un bonus, c’est un **fondement éthique et technique**.  
> Concevoir pour tous, c’est rendre le numérique **plus juste, plus robuste et plus humain**.
