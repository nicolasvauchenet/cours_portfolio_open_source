# Fiche 2 — Licences et droits d’usage dans le logiciel libre

---

## Introduction

Le logiciel libre repose sur un principe simple mais fondamental :  
**la liberté d’utiliser, d’étudier, de modifier et de redistribuer le code.**

Mais cette liberté ne va pas de soi : elle doit être **protégée juridiquement**.  
C’est le rôle des **licences libres**, véritables contrats entre le créateur et les utilisateurs.  
Elles garantissent que le code reste ouvert, accessible et partageable — tout en précisant les conditions d’usage.

Comprendre les licences est donc essentiel pour tout développeur :  
c’est ce qui permet de **travailler, publier et collaborer légalement** dans l’écosystème open source.

---

## 1. Les fondements juridiques du logiciel libre

### 1.1 Le droit d’auteur

En droit français comme international, **tout code source est automatiquement protégé** par le droit d’auteur dès sa
création.  
Cela signifie que :

- sans licence, **le code n’est pas libre** ;
- toute réutilisation, copie ou modification sans autorisation est une **violation légale**.

Une licence libre est donc **un acte de permission**, accordé par l’auteur.

### 1.2 Les quatre libertés fondamentales

Définies par la *Free Software Foundation*, elles constituent la base du mouvement du logiciel libre :

1. **Liberté d’exécuter** le programme pour tout usage.
2. **Liberté d’étudier** le fonctionnement du programme (accès au code source).
3. **Liberté de modifier** le code et d’adapter le programme à ses besoins.
4. **Liberté de redistribuer** des copies, avec ou sans modification.

Ces libertés font du logiciel libre **un bien commun** et non un simple produit.

### 1.3 Libre ≠ Gratuit

Un logiciel libre peut être **vendu, distribué, ou monétisé**.  
Ce qui le distingue, c’est que **l’utilisateur reste libre d’en disposer** selon les conditions définies par la
licence.  
Le code reste ouvert, quelle que soit sa valeur commerciale.

---

## 2. Les grandes familles de licences libres

### 2.1 Licences permissives

Les plus souples.  
Elles autorisent la réutilisation, la modification et la redistribution, y compris dans des logiciels propriétaires.

Exemples :

- **MIT** : très courte et simple, elle permet presque tout.  
  → utilisée par React, Vue.js, Rails.
- **BSD** : proche de MIT, avec quelques clauses de citation.
- **Apache 2.0** : ajoute une clause anti-brevet, très utilisée dans l’industrie (Android, Kubernetes).

**Avantage** : grande compatibilité et adoption large.  
**Limite** : le code peut être repris sans contribution en retour.

---

### 2.2 Licences copyleft

Elles imposent que tout dérivé du logiciel conserve la même liberté :  
si vous modifiez le code, vous devez publier vos modifications sous la même licence.

Exemples :

- **GPLv3 (General Public License)** : emblématique du mouvement libre (Linux, WordPress).
- **AGPL (Affero GPL)** : protège aussi les versions déployées en ligne (Nextcloud, Mattermost).
- **LGPL (Lesser GPL)** : plus souple pour les bibliothèques (permet de lier du code propriétaire).

**Avantage** : garantit que le code reste libre dans le temps.  
**Limite** : moins compatible avec des projets commerciaux fermés.

---

### 2.3 Licences hybrides ou sectorielles

Certaines licences s’appliquent à des contenus non logiciels :

- **Creative Commons (CC)** : pour les textes, images, vidéos, documentations.
    - **CC-BY** : libre avec attribution obligatoire.
    - **CC-BY-SA** : libre et partage à l’identique (copyleft).
    - **CC0** : mise dans le domaine public.
- **MPL (Mozilla Public License)** : licence intermédiaire, utilisée pour Firefox.
    - Permet un équilibre entre ouverture et intégration industrielle.

---

## 3. Choisir la bonne licence pour son projet

### 3.1 Questions à se poser

Avant de publier un projet :

- Souhaitez-vous **que d’autres réutilisent librement** votre code ?
- Voulez-vous **obliger** à redistribuer les modifications ?
- Votre projet est-il **indépendant ou intégré** dans un écosystème existant ?
- Le code contient-il **des dépendances** soumises à d’autres licences ?

Ces éléments déterminent le type de licence à adopter.

### 3.2 Bonnes pratiques

- Ajoutez toujours un **fichier `LICENSE`** à la racine du dépôt.
- Indiquez la licence dans le `README.md`.
- Mentionnez la licence des dépendances (notamment npm, composer, pip).
- Respectez les mentions légales obligatoires : attribution, copyright, lien vers la licence.

### 3.3 Outils utiles

- **[choosealicense.com](https://choosealicense.com)** — guide officiel de GitHub pour choisir sa licence.
- **[tldrlegal.com](https://tldrlegal.com)** — résumés clairs des droits et obligations.
- **[spdx.org/licenses](https://spdx.org/licenses)** — liste standardisée d’identifiants de licences.

---

## 4. Activités pratiques

### Atelier 1 — Identifier les licences

- Parcourez les dépôts GitHub de trois projets open source (ex : Symfony, React, Blender).
- Notez pour chacun :
    - la licence utilisée ;
    - les obligations qu’elle impose ;
    - le type de licence (permissive ou copyleft).
- Comparez les différences de philosophie et d’usage.

### Atelier 2 — Choisir une licence pour son projet

- Choisissez un de vos projets personnels.
- Déterminez la licence la plus adaptée selon vos objectifs :
    - **MIT** : ouverture maximale.
    - **GPL** : protection de la liberté du code.
    - **Apache** : équilibre entre ouverture et sécurité juridique.
- Créez le fichier `LICENSE` correspondant et mentionnez-le dans votre README.

---

## Livrables attendus

- Tableau comparatif des licences étudiées (3 projets).
- Fichier `LICENSE` et section licence ajoutés à un projet personnel.
- Court texte justificatif (5 lignes) expliquant votre choix de licence.

---

## Évaluation

| Critère                             | Description                                                        | Pondération |
|-------------------------------------|--------------------------------------------------------------------|-------------|
| Compréhension des types de licences | Capacité à distinguer les logiques et obligations                  | 40 %        |
| Application correcte d’une licence  | Choix cohérent et respect des règles de publication                | 40 %        |
| Qualité du raisonnement             | Clarté de l’argumentaire et cohérence avec les objectifs du projet | 20 %        |

---

## Pour aller plus loin

- Lire : *Guide du Logiciel Libre* (April, 2022).
- Étudier les licences utilisées dans vos frameworks préférés (Symfony, React, Laravel).
- Explorer les licences spécifiques aux données (Open Database License, Data Commons).
- Observer comment les grandes entreprises (Google, Red Hat, Elastic) articulent leurs politiques de licences.

---

## Message clé

> Les licences libres ne limitent pas, elles libèrent.  
> En choisissant la bonne licence, vous **protégez votre travail** tout en **garantissant sa transmission**.  
> La liberté du code est une question de confiance… et de rigueur juridique.
