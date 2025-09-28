# 04. Comprendre l’open source

## Objectifs de la séance

- Connaître les fondements du logiciel libre et open source.
- Comprendre les différents types de licences et leurs implications.

---

## 1. Historique et grands mouvements

### Les origines

- **Années 1980** : Richard Stallman lance le **projet GNU** et fonde la **Free Software Foundation (FSF)**.  
  Objectif : garantir les “quatre libertés” fondamentales du logiciel libre : exécuter, étudier, modifier, redistribuer.
- **Années 1990** : apparition du noyau **Linux** (Linus Torvalds, 1991) qui combiné avec GNU devient GNU/Linux.

### La naissance du terme “Open Source”

- En 1998, l’initiative **Open Source Initiative (OSI)** popularise l’expression *open source* pour élargir l’adoption
  dans l’industrie, perçue comme moins “idéologique” que “logiciel libre”.
- L’OSI définit l’**Open Source Definition**, un ensemble de critères (redistribution libre, accès au code source,
  non-discrimination…).

### Grands mouvements actuels

- **Logiciels majeurs open source** : navigateurs (Firefox, Chromium), systèmes d’exploitation (Linux, Android),
  frameworks (Django, Symfony, React).
- **Fondations** : Apache Software Foundation, Linux Foundation, Eclipse Foundation, CNCF (Cloud Native Computing
  Foundation).
- **Nouvelles tendances** : open source dans l’intelligence artificielle (Hugging Face, Stable Diffusion, Mistral).

---

## 2. Licences (MIT, GPL, Apache)

Une licence open source définit les conditions d’utilisation, de modification et de redistribution.

### Licence MIT

- Très courte et permissive.
- Autorise tout (usage privé, commercial, modification, redistribution), à condition de conserver la mention de
  copyright.
- Avantage : flexibilité maximale.
- Inconvénient : pas de garantie que les modifications restent ouvertes.

### Licence GPL (GNU General Public License)

- Licence **copyleft** : toute redistribution d’un logiciel dérivé doit se faire sous GPL.
- Avantage : assure que le code reste libre.
- Inconvénient : contraignante pour l’intégration dans des projets propriétaires.

### Licence Apache 2.0

- Licence permissive comme MIT, mais plus détaillée.
- Introduit une clause explicite sur la **protection contre les brevets**.
- Avantage : adoption massive dans l’industrie (Google, Apache, Android).

---

## 3. Exemples de projets phares

- **Linux** (GPL) : cœur de l’open source, utilisé dans les serveurs, les smartphones, le cloud.
- **Apache HTTP Server** (Apache 2.0) : l’un des serveurs web les plus utilisés au monde.
- **React** (MIT) : bibliothèque JavaScript développée par Meta, largement adoptée dans l’industrie.
- **PostgreSQL** (licence PostgreSQL, proche de MIT) : base de données relationnelle puissante et open source.
- **Kubernetes** (Apache 2.0) : orchestrateur de conteneurs initié par Google, aujourd’hui piloté par la CNCF.

---

## 4. Mini-atelier

- Étudier trois projets open source différents.
- Identifier leur licence.
- Vérifier ce que cette licence autorise ou contraint (usage commercial, redistribution, modification).

---

## 5. Livrable de la séance

**Une fiche comparative de 3 licences open source (1 page).**

Elle doit contenir :

- Le nom de chaque licence.
- Les permissions accordées (utilisation, modification, redistribution).
- Les obligations (mention copyright, copyleft éventuel, clauses spécifiques).
- Les projets phares qui l’utilisent.

---

## 6. Pour aller plus loin

- *Free Software Foundation* : https://www.gnu.org
- *Open Source Initiative* : https://opensource.org/licenses
- *Choose a License* : https://choosealicense.com
- *The Cathedral and the Bazaar* (Eric S. Raymond) : essai fondateur sur le modèle open source.

---

## 7. Mini-FAQ

- **GPL et MIT sont-elles compatibles ?**
  > Pas directement : le code GPL impose le copyleft, alors que MIT est permissive. On peut inclure du MIT dans un
  projet GPL, mais pas l’inverse.

- **Puis-je mettre une licence perso sur mon projet ?**
  > Techniquement oui, mais il est préférable d’utiliser une licence reconnue pour être compris et accepté par la
  communauté.

- **Pourquoi Apache 2.0 est-elle très utilisée ?**
  > Parce qu’elle est permissive tout en protégeant contre les litiges liés aux brevets.
