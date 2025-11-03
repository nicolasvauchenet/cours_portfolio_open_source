# Fiche 4 — Gouvernance et contribution dans les projets open source

---

## Introduction

Le logiciel libre n’existe que parce qu’il est **co-écrit, corrigé et amélioré collectivement**.  
Cette intelligence distribuée repose sur des communautés structurées, des processus transparents et une culture du
respect mutuel.

Contribuer à un projet open source ne se limite pas à “pousser du code” :  
c’est aussi **communiquer, documenter, tester, traduire, organiser**.  
Cette fiche présente les règles, les rôles et les bonnes pratiques pour comprendre et rejoindre efficacement une
communauté open source.

---

## 1. Comprendre la gouvernance des projets open source

### 1.1 Des structures adaptées à chaque projet

Les communautés libres ne sont pas anarchiques : elles reposent sur une **gouvernance explicite**, souvent documentée
dans le dépôt.

Quelques modèles types :

- **BDFL (Benevolent Dictator For Life)** : un leader historique fixe la vision et arbitre les décisions (ex. Linus
  Torvalds pour Linux).
- **Comité central ou Core Team** : un groupe élu ou coopté maintient le projet (ex. Symfony, Django).
- **Gouvernance fondation** : le projet est administré par une structure juridique neutre (ex. Apache Software
  Foundation, Mozilla Foundation).
- **Modèle communautaire ouvert** : décisions collectives, votées via issues ou RFC (ex. Rust, Vue.js).

### 1.2 Les rôles typiques

| Rôle                           | Description                                                         |
|--------------------------------|---------------------------------------------------------------------|
| **Contributeur**               | Toute personne proposant une amélioration (code, doc, design).      |
| **Mainteneur**                 | Responsable de la revue et de l’intégration du code.                |
| **Core team**                  | Groupe chargé de la direction technique et de la feuille de route.  |
| **Reviewer**                   | Personne validant la qualité et la conformité d’une contribution.   |
| **Community manager / triage** | Facilite les échanges, catégorise les issues, répond aux questions. |

Un projet libre bien gouverné repose sur une **répartition claire des responsabilités**.

---

## 2. Le processus de contribution

### 2.1 Les outils et pratiques communes

- **Issues** : discussion ou signalement d’un bug, d’une idée ou d’une amélioration.
- **Fork** : copie du dépôt sur son propre compte pour travailler sans affecter l’original.
- **Branch** : création d’une branche dédiée pour une modification spécifique.
- **Pull Request (PR)** : proposition d’intégration du code modifié dans le dépôt principal.
- **Review** : lecture et commentaires du code par les mainteneurs.
- **Merge** : validation et intégration dans la branche principale.

### 2.2 Étapes typiques d’une contribution

1. Identifier une tâche ou un problème (issue).
2. Lire les consignes dans `CONTRIBUTING.md`.
3. Créer un fork, une branche, et effectuer la modification.
4. Tester localement et décrire les changements dans un commit clair.
5. Soumettre une pull request, attendre la revue, ajuster si nécessaire.
6. Suivre la discussion jusqu’à l’intégration ou la clôture.

> La qualité d’une contribution ne se mesure pas à sa taille, mais à sa clarté et à sa justesse.

---

## 3. Les bonnes pratiques de collaboration

### 3.1 Documentation et transparence

- Maintenir un `README.md` à jour.
- Décrire les étapes d’installation et de contribution dans `CONTRIBUTING.md`.
- Lister les auteurs et leurs rôles (`AUTHORS`, `MAINTAINERS`).
- Documenter les changements (`CHANGELOG.md`).

Une documentation claire permet d’accueillir de nouveaux contributeurs sans dépendre des anciens.

### 3.2 Le code de conduite

- La plupart des projets incluent un **`CODE_OF_CONDUCT.md`** définissant les comportements attendus.
- Il garantit un espace respectueux, inclusif et sans harcèlement.
- Les modérateurs peuvent rappeler ou appliquer ces règles en cas d’abus.

**Exemple :**
> “Be kind, be respectful, assume good faith.”

### 3.3 Communication bienveillante

- Poser des questions plutôt que donner des ordres.
- Expliquer un refus de contribution de manière constructive.
- Valoriser les nouveaux arrivants et les contributions mineures.
- Adopter un ton neutre, clair et respectueux (surtout en anglais).

La qualité du dialogue fait la réputation du projet autant que la qualité du code.

---

## 4. Contribuer concrètement : la première étape

### 4.1 Types de contributions possibles

- **Code** : corrections, nouvelles fonctionnalités, tests unitaires.
- **Documentation** : amélioration du README, tutoriels, exemples d’usage.
- **Traduction** : adaptation des textes ou messages d’erreur.
- **Design / accessibilité** : maquettes, refontes graphiques.
- **Organisation** : gestion des issues, tri, réponses, animation communautaire.

Chaque projet libre a besoin de **plus que du code**.

### 4.2 Identifier une première contribution

- Explorer la section “Good first issue” sur GitHub.
- Commencer par des corrections simples : fautes de frappe, liens cassés, exemples obsolètes.
- Participer à des événements comme **Hacktoberfest** (octobre, chaque année).
- Lire la documentation avant toute proposition : c’est un signe de respect pour le projet.

### 4.3 Bonnes pratiques de contribution

- Faire des **commits clairs et atomiques** : un changement = un message.
- Toujours décrire la modification dans la pull request.
- Vérifier les tests et le formatage avant de soumettre.
- Accepter la revue comme une **collaboration**, pas une évaluation.

---

## 5. Activités pratiques

### Atelier 1 — Cartographie d’un projet open source

- Choisissez un dépôt open source actif (Symfony, Blender, Nextcloud, etc.).
- Repérez :
    - les rôles visibles dans le projet (core, mainteneurs, contributeurs) ;
    - les documents de gouvernance (`CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `README.md`).
- Présentez la structure du projet sous forme de schéma ou carte mentale.

### Atelier 2 — Première contribution

- Identifiez une issue ouverte et accessible.
- Réalisez une contribution simple (documentation, correction, amélioration).
- Décrivez votre démarche : recherche, fork, PR, échanges éventuels.

---

## Livrables attendus

- Schéma ou fiche de gouvernance d’un projet open source.
- Rapport de contribution (1 à 2 pages ou capture du processus GitHub).

---

## Évaluation

| Critère                         | Description                                  | Pondération |
|---------------------------------|----------------------------------------------|-------------|
| Compréhension de la gouvernance | Capacité à identifier les rôles et processus | 40 %        |
| Qualité de la contribution      | Pertinence, clarté, respect des conventions  | 40 %        |
| Attitude collaborative          | Communication, respect du code de conduite   | 20 %        |

---

## Pour aller plus loin

- Lire : *Open Source Guides – How to Contribute to Open Source* (GitHub).
- Étudier la gouvernance des fondations open source (Apache, Linux, Mozilla).
- Participer à **Hacktoberfest** ou à un sprint communautaire.
- Suivre les conférences **FOSDEM** ou **LibrePlanet**.

---

## Message clé

> Le code libre vit grâce à celles et ceux qui le maintiennent.  
> Contribuer, ce n’est pas seulement écrire du code,  
> c’est **prendre part à une communauté qui construit le savoir commun**.
