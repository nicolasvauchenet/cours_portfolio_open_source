# Fiche 4 — Publier et entretenir son espace professionnel

---

## Introduction

Un portfolio qui dort sur un disque dur n’a aucun impact.  
Le publier, le maintenir et l’améliorer font partie intégrante de la posture professionnelle du développeur moderne.

Cette fiche aborde la **mise en ligne**, la **mise à jour** et la **valorisation continue** de votre espace
professionnel — trois gestes simples qui transforment un projet personnel en véritable vitrine publique de votre
savoir-faire.

---

## 1. Publier son portfolio

### 1.1 Pourquoi publier ?

Publier, c’est :

- **assumer** ce que l’on a produit ;
- **rendre visible** ses compétences ;
- **inviter aux retours** et aux opportunités.

Votre portfolio devient un **point d’ancrage professionnel** : tout recruteur, formateur ou partenaire doit pouvoir y
accéder facilement.

### 1.2 Choisir sa solution d’hébergement

Options courantes et gratuites :

- **GitHub Pages** : simple, automatique, idéal pour les sites statiques.
- **Netlify** ou **Vercel** : déploiement continu depuis un dépôt Git.
- **Render**, **Firebase Hosting** ou **Railway** : pour les projets dynamiques ou API.
- **Nom de domaine personnel** : option payante mais professionnelle (ex. *prenomnom.dev*).

### 1.3 Préparer le déploiement

Avant publication :

- Testez la lisibilité sur mobile et tablette.
- Vérifiez les liens internes et externes.
- Supprimez les fichiers inutiles ou confidentiels.
- Ajoutez un **fichier `.gitignore`** et un **`README.md`** explicatif.
- Intégrez un fichier `LICENSE` si votre code est public.

> Un site propre et lisible reflète un esprit organisé.

---

## 2. Maintenir et faire évoluer son portfolio

### 2.1 Mettre à jour régulièrement

- Ajoutez vos nouveaux projets ou missions.
- Corrigez les erreurs, liens morts, versions de framework obsolètes.
- Actualisez votre stack technique (ex : “Symfony 7” → “Symfony 7.1”).
- Mettez à jour votre biographie et vos objectifs professionnels.
- Archivez les projets trop anciens ou non représentatifs.

La cohérence de votre portfolio est un **reflet de votre rigueur**.

### 2.2 Organiser le suivi des modifications

- Utilisez Git pour tracer les changements.
- Tenez un petit **changelog** (même informel) :
    - “Ajout du projet API Booking System – juin 2025”
    - “Refonte de la page d’accueil – novembre 2025”
- Conservez vos versions antérieures dans des branches ou tags.
- Testez avant chaque publication pour éviter les régressions.

### 2.3 Automatiser la maintenance

- Mettez en place un déploiement automatique (CI/CD) :
    - à chaque *commit* sur `main`, Netlify ou Vercel reconstruit votre site.
- Planifiez une revue trimestrielle :
    - 1h pour vérifier la cohérence des projets,
    - 1h pour ajuster les textes,
    - 1h pour nettoyer les dépôts.
- Automatisez la génération des pages via un script ou CMS statique si nécessaire.

---

## 3. Valoriser son espace professionnel

### 3.1 Rendre votre portfolio visible

- Ajoutez le lien dans votre signature mail, votre CV et votre profil LinkedIn.
- Partagez-le lors d’événements ou dans vos candidatures.
- Citez-le comme référence dans vos discussions techniques ou articles.
- Personnalisez l’URL (ex. *votrenom.dev* plutôt que *username.github.io*).

### 3.2 Partager vos projets et apprentissages

- Publiez un court billet : “Refonte de mon portfolio – retour d’expérience.”
- Mettez en avant vos choix techniques sur les réseaux professionnels.
- Rejoignez des communautés de développeurs pour échanger sur vos retours d’expérience.
- Mettez à disposition vos modèles ou composants réutilisables : ils deviendront vos meilleures références.

### 3.3 Soigner votre image de professionnel en veille

- Faites évoluer la présentation selon les standards de design actuels.
- Ajoutez une page “veille” ou “ressources” (liens techniques, lectures).
- Montrez que votre portfolio vit au rythme de votre apprentissage.

---

## 4. Activités pratiques

### Atelier 1 — Déploiement en ligne

- Hébergez votre portfolio sur GitHub Pages, Netlify ou Vercel.
- Testez la compatibilité mobile et la vitesse de chargement.
- Vérifiez l’accessibilité et la lisibilité du contenu.

### Atelier 2 — Maintenance planifiée

- Créez un petit **changelog** retraçant vos mises à jour récentes.
- Planifiez trois dates de révision du portfolio pour l’année à venir.
- Définissez une routine de maintenance simple : test, correction, ajout, publication.

### Atelier 3 — Diffusion professionnelle

- Intégrez le lien de votre portfolio à vos signatures numériques.
- Rédigez une courte présentation pour l’accompagner (1 à 2 phrases).
- Publiez une annonce de mise en ligne sur votre réseau professionnel.

---

## Livrables attendus

- **Portfolio publié** (URL accessible en ligne).
- **Changelog ou plan de maintenance** documenté.
- **Présentation synthétique** du site (texte court ou fiche projet).

---

## Évaluation

| Critère                      | Description                                  | Pondération |
|------------------------------|----------------------------------------------|-------------|
| Publication fonctionnelle    | Portfolio accessible, complet et lisible     | 40 %        |
| Maintenance et mise à jour   | Plan clair, cohérent, pertinent              | 40 %        |
| Valorisation professionnelle | Capacité à présenter et diffuser son travail | 20 %        |

---

## Pour aller plus loin

- Lire : *Web Eco-Design – Bonnes pratiques d’écoconception numérique* (Collectif Green IT).
- Découvrir les outils de mesure :
    - **Google Lighthouse** pour la performance et l’accessibilité,
    - **EcoIndex.fr** pour l’impact environnemental.
- Explorer les modèles de CI/CD pour sites statiques (GitHub Actions, Netlify CLI).
- Réfléchir à la notion de “portfolio durable” : un site sobre, rapide, lisible et mis à jour régulièrement.

---

## Message clé

> Publier, c’est s’engager.  
> Chaque ligne de votre portfolio vous représente : faites-en un espace vivant, cohérent et responsable.  
> Un portfolio maintenu est la meilleure preuve que vous prenez votre métier au sérieux.
