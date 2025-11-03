# Fiche 2 — Sobriété et écoconception numérique

---

## Introduction

Chaque clic, chaque requête, chaque image chargée a un coût énergétique.  
Loin d’être virtuel, le numérique repose sur des infrastructures matérielles :  
serveurs, réseaux, terminaux, data centers — tous consommateurs d’électricité et producteurs de chaleur.

L’écoconception numérique vise à **réduire l’empreinte environnementale du code** sans nuire à la qualité d’usage.  
C’est une démarche à la fois **technique, éthique et stratégique**, qui s’inscrit dans une logique de sobriété :  
*faire mieux avec moins.*

---

## 1. Comprendre l’impact environnemental du numérique

### 1.1 Quelques ordres de grandeur

- Le numérique représente environ **4 % des émissions mondiales de CO₂**, et cette part augmente chaque année.
- En moyenne, **un site web classique consomme 1,76 g de CO₂ par page vue** (source : Website Carbon).
- La **vidéo en ligne** représente près de **80 % du trafic Internet mondial**.
- Les applications lourdes, dépendantes et non optimisées multiplient les requêtes et les traitements inutiles.

### 1.2 Les trois pôles d’impact

| Pôle            | Description                                | Leviers d’action                                |
|-----------------|--------------------------------------------|-------------------------------------------------|
| **Fabrication** | Production des terminaux et serveurs       | Prolonger la durée de vie du matériel           |
| **Utilisation** | Énergie consommée pour afficher et traiter | Optimiser le code, réduire la charge            |
| **Fin de vie**  | Gestion des déchets électroniques          | Réutiliser, recycler, réduire le renouvellement |

### 1.3 La responsabilité du développeur

Le code n’est pas neutre : chaque ligne inutile a un coût.  
Le rôle du développeur est de **concilier performance, accessibilité et sobriété**,  
en privilégiant la simplicité et l’efficacité.

---

## 2. Principes de l’écoconception logicielle

### 2.1 Les grands principes (selon le collectif GreenIT.fr)

1. **Réduire les transferts de données** : éviter le superflu.
2. **Alléger les interfaces** : limiter scripts, animations et effets.
3. **Optimiser le code** : refactoriser, supprimer les dépendances inutiles.
4. **Mutualiser les ressources** : hébergement partagé, caches communs.
5. **Mesurer et améliorer en continu** : instrumentation, audit, suivi.

### 2.2 Les 4 piliers du web éco-conçu

| Pilier          | Objectif                           | Exemples                                     |
|-----------------|------------------------------------|----------------------------------------------|
| **Performance** | Réduire les temps de chargement    | Lazy loading, compression GZIP               |
| **Efficience**  | Diminuer le poids global des pages | Minification CSS/JS, sprites                 |
| **Simplicité**  | Supprimer le non essentiel         | Suppression d’animations superflues          |
| **Pérennité**   | Assurer la longévité du code       | Technologies stables, maintenance simplifiée |

---

## 3. Leviers techniques de sobriété

### 3.1 Optimisation des médias

- Redimensionner les images avant import.
- Utiliser des formats modernes : **WebP**, **AVIF**, **SVG**.
- Compresser sans perte perceptible.
- Préférer les polices système aux polices externes.
- Charger les vidéos **à la demande** (lazy loading).

### 3.2 Alléger le front-end

- Supprimer les **frameworks lourds** s’ils ne sont pas indispensables.
- Privilégier **le CSS pur** ou des micro-librairies ciblées.
- Éviter les **animations CSS/JS** non fonctionnelles.
- Réduire le nombre de **requêtes HTTP** (sprites, bundles, cache).
- Mettre en place un **cache navigateur** efficace.

### 3.3 Réduire les traitements côté serveur

- Optimiser les requêtes SQL (indexation, pagination).
- Utiliser la mise en cache des pages et fragments (Redis, Varnish).
- Gérer les logs et tâches cron avec modération.
- Minimiser les dépendances dans le back-end (packages, SDK).

### 3.4 Hébergement responsable

- Privilégier un **hébergeur vert** (alimenté en énergies renouvelables).
- Mutualiser plutôt que dédier.
- Surveiller la **consommation CPU et RAM** des serveurs.
- Déployer automatiquement uniquement lorsque nécessaire (CI/CD raisonnée).

---

## 4. Outils de mesure et de suivi

| Outil                                | Fonction                                              | Utilisation                                |
|--------------------------------------|-------------------------------------------------------|--------------------------------------------|
| **EcoIndex**                         | Analyse la performance et l’impact carbone d’une page | Score de A à G, avec indicateurs détaillés |
| **Website Carbon**                   | Estime le CO₂ par page vue                            | Simple et visuel                           |
| **GreenIT Analysis**                 | Audit complet du cycle de vie d’un site               | Rapport global                             |
| **Lighthouse (section Performance)** | Indique les optimisations possibles                   | Intégré à Chrome DevTools                  |

**Conseil :** suivez l’évolution de votre score au fil des refontes,  
et intégrez un **audit de sobriété** à votre process qualité.

---

## 5. Sobriété et expérience utilisateur

### 5.1 UX et éthique

Un site sobre ne doit pas être austère.  
L’enjeu est de **concilier fluidité, esthétique et responsabilité** :

- hiérarchiser l’information,
- alléger les parcours,
- simplifier les formulaires,
- éviter la sursollicitation (pop-ups, tracking excessif).

### 5.2 Design frugal

- Valoriser l’espace blanc et les interfaces calmes.
- Réduire la densité visuelle et les animations agressives.
- Mettre l’utilisateur au centre, pas la machine.

### 5.3 Sobriété comportementale

La sobriété ne dépend pas seulement du code, mais aussi des pratiques :

- désactiver les notifications inutiles,
- limiter les envois automatiques d’e-mails,
- regrouper les mises à jour et builds.

---

## 6. Activités pratiques

### Atelier 1 — Évaluer son empreinte numérique

- Choisissez un site que vous utilisez régulièrement.
- Mesurez son score avec **EcoIndex** et **Website Carbon**.
- Identifiez les causes principales de surconsommation (images, scripts, vidéos…).
- Rédigez une courte fiche diagnostic.

### Atelier 2 — Optimiser une page web

- Sélectionnez une page de votre projet.
- Appliquez trois optimisations concrètes :
    1. Compression des médias,
    2. Minification du code,
    3. Réduction du nombre de dépendances.
- Comparez les scores avant et après optimisation.

---

## Livrables attendus

- Fiche d’évaluation de l’impact environnemental d’un site ou projet.
- Version optimisée d’une page web (lien ou capture).
- Rapport synthétique (5 à 10 lignes) sur les résultats obtenus.

---

## Évaluation

| Critère                      | Description                                | Pondération |
|------------------------------|--------------------------------------------|-------------|
| Compréhension des enjeux     | Capacité à identifier les sources d’impact | 30 %        |
| Pertinence des optimisations | Choix cohérent et efficacité mesurable     | 40 %        |
| Clarté du rapport            | Présentation structurée et lisible         | 30 %        |

---

## Pour aller plus loin

- Lire : *Écoconception web, les 115 bonnes pratiques* (Collectif GreenIT.fr, 2023).
- Explorer : [https://ecoindex.fr](https://ecoindex.fr), [https://websitecarbon.com](https://websitecarbon.com).
- Découvrir : *The Sustainable Web Manifesto* (2020).
- Suivre : *Fruggr* et *Numérique Responsable* (INR).

---

## Message clé

> Le code le plus responsable n’est pas celui qui fait plus,  
> mais celui qui fait **juste ce qu’il faut**.  
> La sobriété numérique, c’est l’art de coder avec discernement :  
> chaque octet économisé est un geste pour la planète.
