# Fiche 3 — Ressources ouvertes et mutualisation

---

## Introduction

L’innovation ouverte repose sur une idée simple : **partager les ressources pour créer plus vite, mieux et ensemble**.  
Ces ressources peuvent être du **code**, des **données**, des **API**, des **standards** ou des
**outils collaboratifs**.  
Elles constituent le carburant de la créativité numérique.

Mais pour en tirer parti, il faut comprendre **comment les utiliser, les citer et les valoriser** sans trahir leur
esprit : celui de la transparence et de la coopération.

---

## 1. Qu’est-ce qu’une ressource ouverte ?

Une ressource ouverte est tout élément **librement accessible, réutilisable et modifiable**, sous réserve du respect de
sa **licence d’usage**.  
Cela inclut :

- les **jeux de données** ouverts (open data),
- les **interfaces de programmation** (API publiques),
- les **logiciels et bibliothèques open source**,
- les **documents, schémas, référentiels, ou formats ouverts**.

> En somme : tout ce qui peut être partagé pour permettre à d’autres de bâtir dessus.

---

## 2. Les API publiques

### 2.1 Définition

Une **API (Application Programming Interface)** permet à un programme d’en interroger un autre.  
Une **API publique** offre cet accès à tous, sans accord contractuel spécifique.

### 2.2 Objectifs

- Favoriser la réutilisation des services numériques existants.
- Éviter de “réinventer la roue”.
- Permettre la création d’écosystèmes (ex : applications tierces, extensions, data visualisation).

### 2.3 Exemples notables

| Domaine          | API                                                                                        | Description                              |
|------------------|--------------------------------------------------------------------------------------------|------------------------------------------|
| **Transport**    | [Transport.data.gouv.fr](https://transport.data.gouv.fr)                                   | Horaires, lignes, arrêts, temps réel     |
| **Météo**        | [OpenWeatherMap](https://openweathermap.org/api)                                           | Données météo et prévisions mondiales    |
| **Culture**      | [API Culture](https://data.culture.gouv.fr)                                                | Données du ministère de la Culture       |
| **Cartographie** | [Mapbox](https://www.mapbox.com), [OpenStreetMap](https://wiki.openstreetmap.org/wiki/API) | Cartes et géolocalisation                |
| **Langue & IA**  | [HuggingFace API](https://huggingface.co)                                                  | Modèles de traitement du langage naturel |

**Exemple concret :**  
Créer une application qui affiche les concerts à venir en croisant l’API *transport.data.gouv.fr* (trajets) avec l’API
*OpenWeather* (météo prévue).

---

## 3. L’open data : les données partagées

### 3.1 Définition et principes

L’**open data** (donnée ouverte) désigne toute information publique ou privée publiée selon trois principes :

1. **Libre accès** (pas de barrière d’usage ou de coût),
2. **Format exploitable** (CSV, JSON, GeoJSON, XML…),
3. **Licence claire** (Creative Commons, ODbL, etc.).

### 3.2 Exemples de portails

| Portail                                          | Origine       | Contenu                                          |
|--------------------------------------------------|---------------|--------------------------------------------------|
| [Data.gouv.fr](https://data.gouv.fr)             | France        | Données publiques (transport, éducation, santé…) |
| [European Data Portal](https://data.europa.eu)   | UE            | Données ouvertes européennes                     |
| [World Bank Data](https://data.worldbank.org)    | Monde         | Indicateurs économiques mondiaux                 |
| [OpenFoodFacts](https://world.openfoodfacts.org) | Communautaire | Données sur les produits alimentaires            |
| [DataTourisme](https://www.datatourisme.fr)      | France        | Données géographiques et culturelles             |

### 3.3 Usages possibles

- Visualisation de données (graphiques, cartes).
- Analyse statistique et économique.
- Création d’outils citoyens (mobilité, santé, environnement).
- Développement d’applications éducatives ou participatives.

---

## 4. Outils et formats de mutualisation

### 4.1 Outils de travail collaboratif

- **GitHub / GitLab** : versionnement, partage de code et documentation.
- **Notion / Obsidian / HackMD** : documentation et coordination d’équipe.
- **OpenAPI / Swagger** : description normalisée des API.
- **Datasets.fr / Fruggr** : publication et suivi de jeux de données responsables.

### 4.2 Formats ouverts et standards

| Format         | Type                              | Exemple d’usage               |
|----------------|-----------------------------------|-------------------------------|
| **JSON / CSV** | Données tabulaires ou structurées | APIs, tableurs, analyses      |
| **GeoJSON**    | Données géographiques             | Cartographie                  |
| **Markdown**   | Documentation simple et portable  | README, guides, fiches projet |
| **YAML**       | Configuration lisible par humain  | Pipelines CI/CD, schémas API  |
| **Schema.org** | Balises de description sémantique | SEO, métadonnées enrichies    |

### 4.3 Licences et partage équitable

Toute ressource ouverte reste protégée par une **licence**.  
Quelques exemples :

- **Creative Commons (CC-BY, CC0)** : textes, images, données.
- **ODbL (Open Database License)** : jeux de données.
- **MIT / Apache 2.0 / GPL** : logiciels et bibliothèques.

**Règle d’or :**
> On peut réutiliser, mais on doit créditer.

---

## 5. Bonnes pratiques de réutilisation

1. **Lire et comprendre la licence** : éviter les usages interdits (ex : exploitation commerciale).
2. **Citer la source d’origine** (nom, lien, licence).
3. **Documenter votre réutilisation** : expliquer le contexte, les transformations effectuées.
4. **Partager en retour** vos améliorations (open source, pull request, publication).
5. **Contribuer à la fiabilité** : signaler les erreurs, proposer des mises à jour.

> Réutiliser sans citer, c’est piller.  
> Réutiliser en documentant, c’est enrichir la communauté.

---

## 6. Activités pratiques

### Atelier 1 — Exploration de données ouvertes

- Sélectionnez un jeu de données sur [data.gouv.fr](https://data.gouv.fr)
  ou [European Data Portal](https://data.europa.eu).
- Identifiez :
    - la source et sa licence,
    - le format,
    - les informations exploitables.
- Proposez un **usage possible** (ex : carte, tableau de bord, outil pédagogique).

### Atelier 2 — Intégration d’une API ouverte

- Choisissez une API libre d’accès (transport, météo, culture…).
- Réalisez une **requête simple** via un script ou un outil comme Postman.
- Documentez :
    - les paramètres utilisés,
    - la réponse reçue,
    - une idée de réutilisation.

---

## Livrables attendus

- Fiche d’analyse d’un jeu de données ou d’une API (1 page).
- Proposition d’usage ou d’application illustrée (texte ou schéma).
- Documentation courte (README ou Markdown) mentionnant la source et la licence.

---

## Évaluation

| Critère                               | Description                                             | Pondération |
|---------------------------------------|---------------------------------------------------------|-------------|
| Compréhension des ressources ouvertes | Identification correcte des formats, licences et usages | 40 %        |
| Qualité de l’analyse                  | Pertinence du choix et rigueur de la documentation      | 40 %        |
| Créativité de la proposition          | Originalité, valeur ajoutée et faisabilité              | 20 %        |

---

## Pour aller plus loin

- Explorer : [https://opendatahandbook.org](https://opendatahandbook.org)
- Lire : *L’économie de la donnée ouverte*, Insee / Etalab (2023)
- Tester : *Postman*, *Insomnia*, *Swagger Editor*
- Découvrir : les jeux de données “Green Tech” (ADEME, Transport Data Hub, etc.)

---

## Message clé

> Les ressources ouvertes sont le langage commun de l’innovation.  
> Chaque API, chaque dataset, chaque format partagé est une **porte d’entrée** vers la créativité collective.  
> Les utiliser, c’est déjà contribuer à les faire vivre.
