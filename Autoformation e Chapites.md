# 🎓 1.1. Analyse du besoin 

Le maquettage constitue la **première étape essentielle** dans la conception d’un site ou d’une application web. Avant même d’écrire une ligne de code, il permet de **visualiser et structurer les idées** sous forme de schémas simples (wireframes), facilitant ainsi la communication entre les différentes parties prenantes (client, chef de projet, designer, développeur).

## Pourquoi apprendre le maquettage ?
- **Clarifier les besoins** : Le maquettage permet d’organiser les contenus et fonctionnalités d’un site de manière logique.  
- **Gagner du temps** : En validant rapidement une structure, on évite des retouches coûteuses au stade du développement.  
- **Améliorer l’ergonomie** : En réfléchissant à la navigation et à l’expérience utilisateur dès le début, on conçoit des interfaces plus intuitives.

## Objectifs de l’autoformation
Cette autoformation vise à :  
1. **Découvrir les bases du maquettage** et son rôle dans un projet web.  
2. **Apprendre à créer un wireframe** simple, représentant la structure d’une page.  
3. **Se familiariser avec des outils modernes** tels que Figma pour transformer une idée en maquette interactive.

## À qui s’adresse ce module ?
Aux **débutants en développement web** ou en **design d’interfaces**, souhaitant acquérir une première approche structurée pour concevoir des pages web avant le passage au code.

---

## 📘 Unités d’apprentissage (UAs) couvertes

### UA 1.1.1 – Identifier le rôle du maquettage (2h)
- **Chapitre 1** : Qu’est-ce qu’un wireframe ? (1h)  
- **Chapitre 2** : Cycle de vie d’un projet web (1h)

### UA 1.1.2 – Découvrir les outils de maquettage (4h)
- **Chapitre 3** : Outils de maquettage (1h)  
- **Chapitre 4** : S’initier à Figma (1h)  
- **Chapitre 5** : Créer une maquette simple (2h)



# 1.2. Conception UI & maquettes

La **conception UI** (interface utilisateur) transforme un besoin fonctionnel en **écrans clairs, cohérents et utilisables**. Elle s’appuie sur l’**architecture de l’information** (quels contenus ? où ?), la **navigation** (comment on s’y déplace ?) et des **wireframes low→mid** pour valider rapidement les choix avant le développement.  
Objectif : **réduire les aller-retours** en posant un **style v1** (typo, grille, espaces, composants) et un **parcours utilisateur** fluide.

## Pourquoi travailler la conception UI ?
- **Structurer les contenus** : organiser l’information pour que l’utilisateur trouve vite ce qu’il cherche.  
- **Sécuriser la navigation** : cartographier les écrans et les flux (web/mobile) pour éviter les impasses.  
- **Aligner l’équipe** : des maquettes low→mid et un **style v1** servent de référence commune (handoff plus net).

## Objectifs de l’autoformation
À l’issue de ce module, vous serez capable de :  
1. **Cartographier les écrans** et formaliser un **flux de navigation** web/mobile.  
2. Produire des **wireframes low→mid** (écrans clés + états).  
3. Définir un **style v1** (typo, grille, espaces, composants courants).  
4. Poser un **diagramme de classes minimal** (4–6 classes métier) pour guider le futur modèle de données.

## À qui s’adresse ce module ?
Aux **débutants** en UI/UX et **développeurs** souhaitant cadrer l’interface avant de coder (Blog Laravel + App Mobile).  
*(Pré-requis conseillé : Autoformation C1.1 — Analyse du besoin.)*

---

## 📘 Unités d’apprentissage (UAs) couvertes

### UA 1.2.U1 – Architecture de l’info & navigation *(≈3h)*
- **Chapitre 1.2.1** : **Carte des écrans** (List, Detail, Admin…) *(≈1h)*  
- **Chapitre 1.2.2** : **Flux de navigation** web/mobile (schéma) *(≈2h)*

### UA 1.2.U2 – Wireframes & styles de base *(≈4h)*
- **Chapitre 1.2.3** : **Wireframes low→mid** (écrans clés + états) *(≈2h)*  
- **Chapitre 1.2.4** : **Style v1** (typo, grille, espaces, composants) *(≈2h)*

### UA 1.2.U3 – Diagramme de classes (minimal) *(≈2h)*
- **Chapitre 1.2.5** : **4–6 classes** métier (Article, Tag, User…) + associations *(≈2h)*

---

## 📦 Livrables attendus (N1)
- **Carte des écrans** (PNG/SVG)  
- **User flow** (schéma)  
- **Wireframes low→mid** (Figma)  
- **Style v1** (typo, grille, composants)  
- **Diagramme de classes minimal** (image/Mermaid)

> Ces livrables serviront de base directe au **prototype HTML/CSS** et au **handoff** (Autoformation C1.3).


---
title: 2.1. Schéma & Eloquent
permalink: /schema-eloquent-bases/
layout: home
nav_order: 1
parent: 2. Base-de-données
has_children: true
---

# 🗄️ Comprendre le **schéma** & **Eloquent**

Avant toute fonctionnalité, une application repose sur un **modèle de données solide**. Cette autoformation vous apprend à **concevoir un schéma relationnel** (PK/FK, contraintes), à le **versionner avec des migrations**, à **générer des jeux de données** (seeders/factories) et à **manipuler ces données** via **Eloquent** (CRUD & relations).

## Pourquoi apprendre ces notions ?
- **Structurer correctement** les données : clés primaires/étrangères, **unicité**, **contraintes**.
- **Fiabiliser l’évolution** du schéma avec des **migrations versionnées** (reproductible sur tous les postes).
- **Prototyper vite** grâce à des **seeders/factories** cohérents (mêmes données pour toute la classe).
- **Coder plus lisible** : **Eloquent** simplifie CRUD et **relations** (1-n, n-n, pivot).
- **Préparer la suite** : API, pagination, filtres et application Mobile s’appuieront sur ces bases.

## Objectifs de l’autoformation
À la fin, vous saurez :
1. **Modéliser** un mini-schéma (ex. *Article*, *Tag*, *User*) avec **PK/FK** et **index** utiles.  
2. Écrire et exécuter des **migrations** et **seeders** (réutilisation d’un `articles.seed.json` si disponible).  
3. Créer un **modèle Eloquent** et réaliser un **CRUD** simple.  
4. Déclarer des **relations** 1-n (*User → Article*) et n-n (*Article ↔ Tag*) avec **table pivot** et méthodes `attach/sync`.  
5. Mettre en place quelques **bonnes pratiques** (nomenclature, timestamps, soft deletes — aperçu).

## À qui s’adresse ce module ?
Aux **débutants en bases de données & Laravel** souhaitant partir sur des **fondations propres** avant l’API et le Mobile. Aisance minimale en **PHP/Composer** conseillée.

---

## 🔗 Fil rouge (Blog Laravel)
Vous appliquerez ces notions au **Blog Laravel** :  
- Tables **articles**, **tags** (+ **article_tag**), **users** ;  
- **Migrations** reproductibles ; **seeders/factories** pour données de test ;  
- **Eloquent** pour lister, créer, mettre à jour et associer **tags ↔ articles**.

---

## 📘 Unités d’apprentissage (UAs) couvertes

### UA 2.1.U1 – Schéma par migrations *(≈ 4 h)*
- **Chapitre 2.1.1** : **Création de tables** avec **PK/FK** et **contraintes** *(≈ 2 h)*  
- **Chapitre 2.1.2** : **Seeders** & **jeux de données** de test *(≈ 2 h)*

### UA 2.1.U2 – Eloquent débutant *(≈ 6 h)*
- **Chapitre 2.1.3** : **CRUD basique** avec un **modèle simple** *(≈ 3 h)*  
- **Chapitre 2.1.4** : **Relations 1-n et n-n** (pivots, `attach/sync`) *(≈ 3 h)*

---

## 📂 Livrables attendus (Niveau 1)
- **Migrations** et **seeders** exécutables (`php artisan migrate`, `php artisan db:seed`).  
- Au moins **un modèle** Eloquent fonctionnel (ex. `Article`) + **factory**.  
- **Relations** configurées et **données associées** (ex. `article_tag`).  
- Mini-README : **commandes** pour (re)créer la base et semer les données.

---

## 🧭 Pistes de vérification rapide
- Les **FK** empêchent la suppression incohérente (intégrité référentielle).  
- Les **seeders** produisent des données **cohérentes et suffisantes**.  
- Les **relations** retournent les bons jeux (ex. `Article::first()->tags`).  

---
---
title: 2.2. Eloquent avancé
permalink: /eloquent-avance/
layout: home
nav_order: 2
parent: 2. Base-de-données
has_children: true
---

# 🧩 Eloquent avancé, intégrité & sécurité

Après les bases (migrations, seeders, CRUD), place à l’**optimisation** et à la **robustesse** : écrire des requêtes plus **expressives et performantes**, protéger la **cohérence** avec des **transactions**, raisonner **index** & `EXPLAIN`, et adopter de bons réflexes **sécurité** (sauvegardes, comptes & privilèges).

## Pourquoi apprendre ces notions ?
- **Lisibilité & maintenabilité** : `scopes`, `with()`, `withCount()` clarifient l’intention métier.  
- **Performance** : éviter le **N+1**, choisir des **index** pertinents, interpréter un `EXPLAIN`.  
- **Fiabilité** : transactions **ACID** avec `commit/rollback` pour des écritures atomiques.  
- **Sécurité & exploitation** : **sauvegarde/restauration**, import/export **CSV**, **GRANT/REVOKE** (principe du moindre privilège).

## Objectifs de l’autoformation
À la fin, vous saurez :
1. Créer des **scopes locaux/globaux** et écrire des **requêtes imbriquées** propres.  
2. Utiliser `with`, `load`, `withCount`, `whereHas` pour **optimiser** les accès.  
3. Encapsuler des opérations critiques dans des **transactions** (`DB::transaction`).  
4. Choisir/valider des **index** et **lire un `EXPLAIN`** simple pour diagnostiquer.  
5. **Sauvegarder/restaurer** la base (via `mysqldump`), **importer/exporter** des CSV.  
6. Créer des **utilisateurs MySQL** dédiés et gérer leurs **privilèges**.

## À qui s’adresse ce module ?
Aux apprenants ayant terminé **C2.1** (migrations, seeders, CRUD, relations) et souhaitant **industrialiser** leurs pratiques (API, projets d’équipe, production).

---

## 🔗 Fil rouge (Blog Laravel)
Vous ferez évoluer le **Blog Laravel** :  
- listes filtrées/triées via **scopes**,  
- chargements **eager** maîtrisés,  
- **transactions** lors de créations multiples,  
- **index** ciblés (slug, FK, composites),  
- **dump/restore** et rôle **lecture/écriture** séparé côté MySQL.

---

## 📘 Unités d’apprentissage (UAs) couvertes

### UA 2.2.U1 – Eloquent avancé
- **Chapitre 2.2.1** : **Scopes** et requêtes complexes  
- **Chapitre 2.2.2** : Relations **imbriquées** & bonnes pratiques de requêtes

### UA 2.2.U2 – Transactions & performance
- **Chapitre 2.2.3** : **Transactions ACID**, `commit/rollback`  
- **Chapitre 2.2.4** : **Index** ciblés & lecture d’un **`EXPLAIN`** simple

### UA 2.2.U3 – Exploitation & sécurité
- **Chapitre 2.2.5** : **Sauvegarde/restauration** (`mysqldump`), **import/export CSV**  
- **Chapitre 2.2.6** : **Comptes & privilèges** MySQL (**GRANT/REVOKE**)

---

## 🧾 Livrables attendus
- Scopes Eloquent réutilisables (`scopePublished`, `scopeSearch`, `scopeFilter`…),  
- Pages/lists **sans N+1** (preuve : `->with()` et `->withCount()`),  
- Script/section **transactionnelle** testée (rollback contrôlé),  
- Jeu d’**index** justifié + capture **`EXPLAIN`** sur 1 requête clé,  
- **Dump** SQL + **procédure** de restauration,  
- Script/notes **GRANT/REVOKE** pour un utilisateur applicatif.

---

## 🧭 Pistes de vérification rapide
- Les listes chargent **constant-time** (pas d’explosion de requêtes).  
- Un échec volontaire en milieu d’opération **n’insère rien** (rollback).  
- `EXPLAIN` utilise un **index** (colonne `key` non nulle, `rows` raisonnable).  
- Compte MySQL applicatif **non-root** avec **privilèges minimaux**.

---

## ⚠️ Pièges fréquents
- **N+1** silencieux → oublier `with()` sur les relations affichées.  
- **Transactions** absentes sur des créations multiples.  
- **Index** manquants sur colonnes de **jointure** / **WHERE** / **tri**.  
- Compte base de données **trop permissif** (risque d’altération involontaire).

> Prochaine étape : démarrez par **2.2.1 – Scopes & requêtes complexes**.
---
title: 3.0. Rappel PHP & POO
layout: home
nav_order: 0
has_children: true
parent: 3. Back-end
permalink: /php-poo/
---

# 🎓 Autoformation C3.0 — Rappel PHP & POO

Cette autoformation remet à niveau les bases **PHP 8.x** et **Programmation Orientée Objet** indispensables pour réussir la suite du module Back-end (Laravel).  
Au programme : **scripts en ligne de commande (CLI)**, **manipulation de fichiers/JSON**, **gestion des erreurs**, et **organisation du code** avec **Composer** (autoload **PSR-4**, scripts).

## Pourquoi (re)voir PHP & POO ?
- **Écrire du code robuste** : typage, exceptions, gestion des erreurs.  
- **Structurer la logique** : classes, interfaces, traits, namespaces.  
- **Automatiser** : scripts CLI pour préparer des données (seed JSON).  
- **Préparer Laravel** : adopter les conventions **Composer/PSR-4** réutilisées dans C3.1 → C3.4.

## 🎯 Objectifs pédagogiques
À l’issue de C3.0, vous serez capable de :
1. Utiliser les **fonctionnalités modernes de PHP** (types, opérateurs utiles, arrays & fonctions).  
2. **Modéliser en POO** (encapsulation, interfaces, traits, namespaces).  
3. Écrire un **script CLI** qui **lit/écrit** des fichiers **JSON**.  
4. Initialiser un projet **Composer** avec **autoload PSR-4** et **scripts** (`start`, `seed`).  

## 👥 Public visé
Apprenants ayant des bases en **HTML/CSS/JS** et **PHP**, souhaitant consolider la **POO** et les **outils** du back-end avant d’attaquer **Laravel**.

---
title: 3.1. CRUD avec Laravel
layout: home
nav_order: 1
has_children: true
parent: 3. Back-end
permalink: /laravel-crud/
---

# 🎓 3.1. CRUD avec Laravel

Cette autoformation vous guide pour **installer un projet Laravel**, comprendre l’**architecture MVC**, puis réaliser un **CRUD complet “Article”** avec **validation** et **pagination**.  
Elle s’appuie sur les acquis de **C3.0 (PHP & POO)** et prépare l’**API v1** de C3.2.

---

## 📒 Glossaire minute
- **Artisan** : CLI Laravel (`php artisan`) pour générer et piloter le projet.  
- **Eloquent** : ORM de Laravel pour manipuler la base via des **modèles**.  
- **Migration / Seeder** : scripts pour **créer** le schéma et **insérer** des données.  
- **Blade** : moteur de **templates** (vues) de Laravel.  
- **FormRequest** : classe dédiée à la **validation** des formulaires.  
- **Flash message** : message **temporaire** (succès/erreur) stocké en session.

---

## 🎯 Objectifs pédagogiques
À la fin de C3.1, vous saurez :
1. **Créer & configurer** un projet Laravel propre (env, app key, locale/timezone).  
2. Mettre en place la **structure MVC** : routes, contrôleurs, **vues Blade** (layout/partials).  
3. Concevoir le **modèle Article** + **migrations/seeders** (réutiliser `articles.seed.json`).  
4. Réaliser un **CRUD** complet avec **FormRequest** (règles + messages), **flash messages** et **pagination**.  
5. Respecter des **conventions de code & routes nommées** pour préparer l’API.

---

## 🧱 Pré-requis & outillage
- **PHP ≥ 8.2**, **Composer**, **MySQL 8+**  
- Bases de **Git** (init, commits)  
- Avoir généré si possible `storage/seeds/articles.seed.json` (C3.0.8)

---

## 🗺️ Plan & UAs couvertes

### UA 3.1.U1 — Mise en route Laravel
- **Chapitre 3.1.1** : **Installation & configuration** (clé d’app, `.env`, timezone/locale)  
- **Chapitre 3.1.2** : **MVC** (routes, contrôleurs, **Blade** : layout/partials)

### UA 3.1.U2 — Formulaires & validation
- **Chapitre 3.1.3** : **Formulaires**, CSRF, **flash messages** (sessions)  
- **Chapitre 3.1.4** : **Validation avec `FormRequest`** (règles, messages, redirections)

### UA 3.1.U3 — Eloquent & CRUD
- **Chapitre 3.1.5** : Modèle **Article** + **migrations/seeders** (import depuis `articles.seed.json`)  
- **Chapitre 3.1.6** : **CRUD** (index/create/edit/delete) + **pagination**

> **Fil rouge** : “**Blog v1**” (Accueil/Liste + CRUD Article minimal).

---

## 🧩 Arborescence cible (à la fin de l’autoformation)
```

blog-solicode/
├─ app/
│  ├─ Http/Controllers/ArticleController.php
│  ├─ Http/Requests/StoreArticleRequest.php
│  └─ Models/Article.php
├─ database/
│  ├─ migrations/xxxx\_xx\_xx\_create\_articles\_table.php
│  └─ seeders/ArticleSeeder.php
├─ resources/views/
│  ├─ layouts/app.blade.php
│  ├─ articles/index.blade.php
│  ├─ articles/create.blade.php
│  ├─ articles/edit.blade.php
│  └─ articles/\_form.blade.php
├─ routes/web.php
└─ storage/seeds/articles.seed.json   (si généré en C3.0)

```

---

## 🧪 Livrables attendus (Niveau 1 — Imitation)
- Projet **Laravel** exécutable (`php artisan serve`) avec **Accueil** et **Liste des articles**.  
- **CRUD Article** fonctionnel : création, édition, suppression, **validation** via `FormRequest`, **flash messages**.  
- **Pagination** sur la liste, **tri simple** optionnel.  
- **Seeder** qui lit `storage/seeds/articles.seed.json` (si présent).  
- **README** clair (prérequis, commandes, comptes de test si besoin).

---

## ✅ Critères de réussite
- Routes **nommées** (`articles.index`, `articles.create`, `articles.store`, …) et **contrôleur resource**.  
- Règles de **validation** correctes (ex. `title` requis, `views` entier ≥ 0).  
- **Messages d’erreur** affichés au bon endroit + **old input** préservé.  
- **Layout Blade** factorisé (header/nav/footer) + partial `_form.blade.php`.  
- **Migration/Seeder** rejouables sans casser la base (idempotence raisonnable).

---

## ⚠️ Erreurs fréquentes
- Oublier `php artisan key:generate` après la copie du `.env`.  
- Mélanger **logique métier** et **vue** (mettre les calculs côté contrôleur/modèle).  
- Ne pas gérer les **messages d’erreur** côté formulaire (affichage `@error`).  
- Seeder qui **écrase** systématiquement tout au lieu d’**upserter** (`updateOrCreate`).

---

## 🔗 Suite du parcours
- **C3.2 — API REST & Normalisation** : exposer `/api/articles` (liste/détail) avec **Resource/Collection**, **pagination** & **filtres**.  
- **C3.3 — Sécurité minimale, Auth & erreurs** : **middlewares**, **policies**, **handler** d’exceptions & **logs**.

> Prêt ? Commencez par **3.1.1 — Installation & configuration**, puis enchaînez sur **3.1.2 — MVC (routes/contrôleurs/Blade)** avant d’attaquer **Eloquent + CRUD**.
---
title: 3.2. API REST
layout: home
nav_order: 2
parent: 3. Back-end
permalink: /api-rest/introduction/
---

# 🔌 API REST Laravel & normalisation JSON

Exposer l’API **/api/articles** (liste et détail), ajouter **pagination** et **filtres**, puis **normaliser** les réponses avec `Resource` et `ResourceCollection`.

## 🎯 Objectif
Produire une **API propre et stable** prête pour une app **Mobile** ou un front web.

---

## 📘 Unités d’apprentissage (UAs) couvertes

### UA 3.2.U1 — API Laravel de base
- **Chapitre 3.2.1** : Routes API et JSON — codes et erreurs, structure de réponse  
- **Chapitre 3.2.2** : Pagination et filtres — query `q`, `tag`, `sort`

### UA 3.2.U2 — Normalisation et contrat
- **Chapitre 3.2.3** : `Resource` et `ResourceCollection` — formatage cohérent  
- **Chapitre 3.2.4** : Contrat API minimal et documentation Postman ou Insomnia

> **Fil rouge** : **API v1 – Articles** (GET liste et détail).
---
title: 3.3. Sécurité
permalink: /securite-auth-erreurs/
layout: home
nav_order: 3
parent: 3. Back-end
has_children: true
---

# 🔐 Sécuriser une application Laravel

Une application **utile** est avant tout une application **sûre** et **prévisible**. Cette autoformation pose les **fondamentaux de sécurité côté Laravel** :  
contrôle d’accès (**authentification** + **policies**), **middlewares** essentiels (auth, **throttle**, **CORS**), et **gestion centralisée des erreurs** (formats JSON pour l’API, pages web propres) avec des **logs** exploitables.

👉 Pré-requis conseillés : avoir réalisé un **CRUD Article** (C3.1) et exposé une **API GET** minimale (C3.2).

## Pourquoi apprendre la sécurité minimale ?
- **Protéger les données** et respecter les rôles (ex. auteur vs visiteur).  
- **Limiter les abus** : anti-bruteforce/anti-spam via **rate limiting** (throttle).  
- **Ouvrir/contrôler l’accès API** proprement (**CORS**) sans fragiliser le système.  
- **Standardiser les erreurs** pour une **meilleure DX** (messages clairs, codes HTTP cohérents).  
- **Tracer les incidents** (logs, niveaux) et **accélérer le diagnostic**.

## Objectifs de l’autoformation
Cette autoformation vise à :  
1. **Activer et configurer** les **middlewares clés** (auth, throttle, CORS).  
2. **Définir une Policy** sur la ressource **Article** (droits CRUD selon l’utilisateur).  
3. **Unifier les réponses d’erreur** (API JSON vs pages web) via le **Handler**.  
4. **Configurer les logs** (canaux Monolog, niveaux, rotation) pour le suivi en équipe.  
5. Livrer un **“Dashboard auteur” sécurisé** + un **format d’erreur JSON** stable pour l’API.

## À qui s’adresse ce module ?
Aux **débutants en back-end Laravel** ayant terminé **C3.1 → C3.2**, ainsi qu’aux apprenants qui s’apprêtent à exposer des **endpoints protégés** et souhaitent **professionnaliser** la gestion des erreurs et des journaux.

---

## 📘 Unités d’apprentissage (UAs) couvertes

### UA 3.3.U1 — Authentification & autorisation *(≈ 3 h)*
- **Chapitre 3.3.1** : *Middlewares clés* (**auth**, **throttle**, **CORS**) *(~1 h 30)*  
- **Chapitre 3.3.2** : *Policy* **Article** (droits CRUD par utilisateur) *(~1 h 30)*

### UA 3.3.U2 — Gestion des erreurs & logs *(≈ 3 h)*
- **Chapitre 3.3.3** : **Handler** d’exceptions (formats **JSON/API** + pages web) *(~1 h 30)*  
- **Chapitre 3.3.4** : **Logs** centralisés (canaux Monolog, niveaux, rotation) *(~1 h 30)*

---

## 🎯 Livrables attendus (fin d’autoformation)
- **Dashboard auteur sécurisé** (liste/édition restreintes à l’auteur).  
- **Contrat d’erreur JSON** uniforme (structure, champs, codes).  
- **Journalisation** lisible (fichier du jour, niveaux INFO/ERROR) et mini-checklist de diagnostic.
---
title: 4.1. Git & GitFlow
permalink: /git-gitflow/
layout: home
nav_order: 1
parent: 4. Collaboration
has_children: true
---

# 🎓 Comprendre Git & GitFlow

Git est l’outil de **gestion de versions** incontournable pour travailler **en équipe**. Couplé à un **processus simple de branches** (GitFlow minimal), il permet de **structurer le dépôt**, garder un **historique propre**, ouvrir des **pull requests** (PR) claires, et **fusionner** le code sans casse.

## Pourquoi apprendre Git & GitFlow ?
- **Collaborer efficacement** : organiser le travail via *issues → branches → PR → merge*.  
- **Assurer la traçabilité** : commits clairs, messages normalisés, historique lisible.  
- **Éviter les conflits** : règles simples de synchronisation (`pull --rebase`) et résolution propre.  
- **Livrer proprement** : *squash merge*, tags/releases optionnels, scripts de démarrage standardisés.

## Objectifs de l’autoformation
Cette autoformation vise à :  
1. **Structurer un dépôt professionnel** (README, `.gitignore`, `env.example`, LICENSE, scripts).  
2. **Adopter un GitFlow minimal** : `main`, `develop`, `feature/*`, `hotfix/*`.  
3. **Conduire une PR de bout en bout** : description, checklist, revue, merge propre (squash).  
4. **Gérer un conflit simple** et synchroniser correctement `develop/main`.

## À qui s’adresse ce module ?
Aux **débutants** ou **équipes pédagogiques** qui veulent mettre en place des **conventions de travail pro** dès les premiers projets (solo, binôme ou petit groupe).

---

## 📘 Unités d’apprentissage (UAs) couvertes

### UA 4.1.U1 – Repo propre & conventions
- **Chapitre 4.1.1** : Initialiser le dépôt (README.md, `.gitignore`, `env.example`, LICENSE)  
- **Chapitre 4.1.2** : Conventions d’équipe (branches, commits, EditorConfig, lint/format)  
- **Chapitre 4.1.3** : Scripts & setup (dev/build/test, doc d’installation)

### UA 4.1.U2 – GitFlow minimal : branches & cycle feature
- **Chapitre 4.1.4** : Stratégie de branches (`main`, `develop`, `feature/…`, `release/…`, `hotfix/…`)  
- **Chapitre 4.1.5** : Cycle « issue → feature → PR » (petits commits, lien issue)  
- **Chapitre 4.1.6** : Sync propre (`pull --rebase`, garder `develop/main` à jour)

### UA 4.1.U3 – PR, review, merge & conflits
- **Chapitre 4.1.7** : Ouvrir une PR (description, checklist, captures, lien issue)  
- **Chapitre 4.1.8** : Revue de code (commentaires factuels, suggestions, DoD)  
- **Chapitre 4.1.9** : Conflit simple & merge (résolution locale, *squash merge*, tag/release optionnel)

--- 

👉 À la fin, tu auras un **workflow Git reproductible**, des **PR lisibles**, et un dépôt **propre et prêt** pour les mini-projets.

---
title: 4.2. Agile & Scrum
permalink: /agile-scrum/
layout: home
nav_order: 2
parent: 4. Collaboration
has_children: true
---

# 🎓 Comprendre Agile (Scrum basique)

Scrum est un **cadre léger** pour organiser le travail d’équipe en **sprints courts**, livrer de la **valeur rapidement** et **améliorer en continu**. Au lieu d’un long cycle en cascade, on avance par **itérations** avec des objectifs clairs, un **backlog** priorisé et des **rituels** réguliers (Planning, Daily, Review, Rétro).

## Pourquoi apprendre Scrum ?
- **Aligner l’équipe** sur un **objectif de sprint** réaliste.  
- **Prioriser par la valeur** via un backlog clair et ordonné.  
- **Réduire les risques** grâce à des livraisons fréquentes et testées.  
- **Améliorer en continu** avec une rétrospective courte et actionnable.  

## Objectifs de l’autoformation
Cette autoformation vise à :  
1. **Comprendre les rôles et cérémonies** d’un Scrum **allégé**.  
2. **Rédiger des User Stories** avec critères **Given/When/Then**.  
3. **Planifier un sprint d’1 semaine** (capacité, WIP, DoR/DoD).  
4. **Suivre l’exécution** sur un **Kanban minimal** et conduire **Review/Rétro**.

## À qui s’adresse ce module ?
Aux **équipes pédagogiques** et **apprenants** qui veulent organiser un **mini-projet** sur 1 semaine en appliquant des **pratiques Agiles simples** (sans outillage complexe).

---

## 📘 Unités d’apprentissage (UAs) couvertes

### UA 4.2.U1 – Cadre Scrum & artefacts
- **Chapitre 4.2.1** : Sprint 1 semaine & rôles (PO, SM, Dev) + cérémonies (Planning, Daily, Review, Rétro)  
- **Chapitre 4.2.2** : Artefacts & définitions (Product/Sprint Backlog, DoR, DoD)  
- **Chapitre 4.2.3** : Planning de sprint (objectif, capacité, WIP limité)  

### UA 4.2.U2 – Backlog → issues (GWT) & estimation
- **Chapitre 4.2.4** : User stories & critères (format Story + Given/When/Then)  
- **Chapitre 4.2.5** : Estimation rapide (T-shirt S/M/L ou 1–3 pts)  
- **Chapitre 4.2.6** : Déclinaison en tâches (tech tasks liées, critères d’acceptation)  

### UA 4.2.U3 – Exécution : Kanban, Daily, Review/Rétro
- **Chapitre 4.2.7** : Kanban minimal (To-Do → In-Progress → Review → Done, règles, WIP)  
- **Chapitre 4.2.8** : Daily 5 min (Fait / À faire / Blocage, mise à jour du board)  
- **Chapitre 4.2.9** : Review & Rétro (démo, feedback, 2 actions d’amélioration)  

---

👉 À la fin, vous saurez **lancer un mini-sprint**, **prioriser**, **suivre l’avancement** et **capitaliser** sur les apprentissages via une rétrospective concise.
---
title: 5.1. Bien démarrer le Mobile
permalink: /mobile-onboarding/
layout: home
nav_order: 1
parent: 5. Mobile
has_children: true
---

# 🎓 Autoformation C5.1 — Bien démarrer le Mobile

Bienvenue dans l’univers **Android + Kotlin**. Cette autoformation vous guide de **zéro** jusqu’à un **APK** installable, via une mini-app Compose “**Hello + Compteur**”. L’objectif est de valider tout le **pipeline outillage → projet → build → installation** avec des **bonnes pratiques** dès le départ.

## Pourquoi apprendre Android (Compose) ?
- **Rapidité** : démarrer une app **écran unique** en quelques minutes.  
- **Simplicité** : **Jetpack Compose** pour une UI déclarative, claire et testable.  
- **Professionnalisation** : dépôt Git propre, livrables reproductibles (**APK + README + captures**).

## Objectifs pédagogiques
À la fin de ce module, vous serez capable de :
1. **Installer & configurer** Android Studio, SDK, émulateur et ADB (device réel).  
2. **Créer un projet Compose** (Empty Activity) et comprendre l’**arborescence** Android.  
3. **Construire un APK debug** et l’installer sur émulateur / téléphone.  
4. Réaliser une mini-app **“Hello + Compteur”** avec **états** et **Material 3**.

## À qui s’adresse ce module ?
Aux **débutants** en mobile et aux développeurs web souhaitant **valider l’environnement Android** avant d’aborder des écrans multi-pages, l’architecture et le réseau.

## 🔧 Pré-requis
- PC Windows/macOS/Linux, **8 Go RAM** minimum (recommandé **16 Go**), **15–20 Go** libres.  
- Android Studio (JDK inclus), connexion Internet stable.  
- (Optionnel) Smartphone Android avec **Options développeur + Débogage USB** activés.

---

## 📦 Livrables attendus
- **Dépôt Git** propre (`README.md`, `.gitignore` Android, premiers commits).  
- **APK (debug)** généré + **captures d’écran** d’exécution (émulateur ou device).  
- Mini-app **Compose** “Hello + Compteur” fonctionnelle (états, accessibilité).

## ✅ Definition of Done (autoformation)
- [ ] Android Studio et SDK installés, **émulateur** ou **device** ADB reconnus.  
- [ ] Projet **Empty Compose Activity** créé, **Gradle Sync OK**.  
- [ ] **APK debug** généré et **installé**.  
- [ ] Mini-app “Hello + Compteur” conforme (UI + états + M3 + `strings.xml`).  
- [ ] README avec **pas de build**, **captures**, et infos d’appareil/emulateur.

---

## 📘 Unités d’apprentissage & chapitres

### UA 5.1.U1 – Outils & workspace
- **Chapitre 5.1.1** : Installer Android Studio & SDK, configurer émulateur/appareil (ADB)  
- **Chapitre 5.1.2** : Créer un projet *Empty Compose Activity* (package, minSdk, Gradle Sync)  
- **Chapitre 5.1.3** : Lire l’arborescence : `app/`, `manifests/`, `java|kotlin/`, `res/`, `build.gradle.kts`

### UA 5.1.U2 – Gestion de versions & livrables
- **Chapitre 5.1.4** : Initialiser Git, `.gitignore` Android, premiers commits propres  
- **Chapitre 5.1.5** : Générer l’**APK debug**, installer sur device, structurer les livrables (README, captures)

### UA 5.1.U3 – Mini-app « Hello + Compteur » (écran unique, offline)
- **Chapitre 5.1.6** : UI de base (TextField “Prénom”, bouton “Dire bonjour”, zone message, bloc compteur − / valeur / +)  
- **Chapitre 5.1.7** : États & interactions avec `rememberSaveable` (name, greeting, `count ≥ 0`, bouton désactivé si champ vide)  
- **Chapitre 5.1.8** : Finitions : Material 3 par défaut, `strings.xml`, accessibilité (`contentDescription`), build APK

---

## 🧭 Ce que vous allez construire (mini-app)
- **Accueil** : champ **Prénom** + bouton **Dire bonjour** → affiche “Bonjour, *Prénom* !”.  
- **Compteur** : boutons **− / +** avec règle `count ≥ 0` (désactiver “−” à 0).  
- **États** via `rememberSaveable`, **Material 3** (thème par défaut), **accessibilité** soignée.

---

## 💡 Conseils de démarrage
- **Un émulateur** à la fois (économie RAM).  
- Commencez par **APK debug** ; la signature **release** viendra plus tard.  
- Pensez **petits commits** et un README **copiable** (setup en 5 lignes).

> Prochaine étape : **5.1.1 — Installer Android Studio & SDK, configurer émulateur/appareil (ADB)**.
---
title: 5.2. Kotlin essentiel pour Android
permalink: /kotlin-essentiel-android/
layout: home
nav_order: 2
parent: 5. Mobile
has_children: true
---

# 🎓 Autoformation C5.2 — Kotlin essentiel pour Android

Kotlin est le **langage officiel** d’Android. Ce module concentre l’essentiel pour écrire un **code sûr, lisible et idiomatique** dans vos écrans Compose : **null-safety**, **fonctions concises**, **data classes** et **collections** avec les opérations usuelles.

## Pourquoi apprendre Kotlin (version “essentiel Android”) ?
- **Sécurité** : éviter les crashs avec la **null-safety** (`?`, `?:`, `let`, `?.`), bannir `!!`.  
- **Lisibilité** : **fonctions courtes**, paramètres nommés, valeurs par défaut.  
- **Modélisation** : **`data class`**, `copy`, déstructuration → états UI clairs.  
- **Expressivité** : `map/filter/sumOf` pour manipuler les listes sans boucles verbeuses.

## Objectifs pédagogiques
À la fin de cette autoformation, vous saurez :
1. Maîtriser la **syntaxe de base** et la **null-safety** sans recourir à `!!`.  
2. Écrire des **fonctions idiomatiques** (pures, petites, testables).  
3. Modéliser des **états** avec `data class` et les **copier** proprement.  
4. Utiliser les **collections** et leurs opérations clés (`map`, `filter`, `sumOf`, etc.).  
5. Appliquer des **bonnes pratiques** : immutabilité par défaut, KISS, noms explicites.

## À qui s’adresse ce module ?
Aux débutants Android (ou développeurs venant du web) qui veulent **solidifier Kotlin** avant d’attaquer MVVM, la navigation et le réseau.

## 🔧 Pré-requis
- Avoir terminé **C5.1** (Android Studio opérationnel).  
- Projet Android **Compose** minimal prêt à exécuter (APK debug OK).

---

## 📦 Livrables attendus
- Un **fichier Kotlin** (ou petit module) avec des **fonctions pures** et des **tests unitaires** simples (ou `@Preview` de vérification).  
- Exemples de **null-safety** correcte (sans `!!`) et d’usage de **collections**.  
- Courte **note README** résumant les idiomes utilisés.

## ✅ Definition of Done (autoformation)
- [ ] Zéro `!!` dans le code — préférer `?.`, `?:`, `let`, `requireNotNull` au bon endroit.  
- [ ] Fonctions **pures** et **courtes** (≤ 15–20 lignes), noms clairs.  
- [ ] `data class` + `copy` pour gérer un **UI state** simple.  
- [ ] Au moins **5 opérations** de collections (`map`, `filter`, `sortedBy`, `groupBy`, `sumOf` …).  
- [ ] README listant **règles de style** appliquées (immutabilité, KISS).

---

## 📘 Unités d’apprentissage & chapitres

### UA 5.2.U1 – Syntaxe & null-safety
- **Chapitre 5.2.1** : `val/var`, types, conditions, boucles  
- **Chapitre 5.2.2** : Null-safety (`?`, `?:`, `let`, `?.`, usage raisonné de `!!`)  

### UA 5.2.U2 – Fonctions & données
- **Chapitre 5.2.3** : Fonctions, paramètres nommés, valeurs par défaut, lambdas simples  
- **Chapitre 5.2.4** : `data class`, `copy`, déstructuration  

### UA 5.2.U3 – Collections & style
- **Chapitre 5.2.5** : `List/Set/Map`, itérations, opérations usuelles (`map/filter/sumOf`)  
- **Chapitre 5.2.6** : Bonnes pratiques : immutabilité, petites fonctions pures, KISS  

---

## 💡 Conseils
- **`val` par défaut**, `var` seulement si nécessaire.  
- Préférer **expressions** à la place de `if/when` verbeux.  
- Écrire d’abord des **fonctions purées** testables, brancher ensuite à l’UI Compose.  

> Prochaine étape : **5.2.1 — `val/var`, types, conditions, boucles**.

---
title: 5.3. Android avec Compose
permalink: /android-compose-mvvm/
layout: home
nav_order: 3
parent: 5. Mobile
has_children: true
---

# 🎓 Autoformation C5.3 — Android avec Jetpack Compose

Compose permet de créer des **interfaces déclaratives, réactives et testables**. Ce module vous amène d’écrans simples à une architecture **MVVM légère** : l’UI observe un **état immuable**, le **ViewModel** orchestre la logique et expose des **intents** clairs.

## Pourquoi apprendre Compose + MVVM ?
- **Clarté** : UI = fonction de l’**état** (moins de bugs d’affichage).  
- **Séparation** : **ViewModel** pour la logique & la persistance d’état.  
- **Évolutivité** : navigation simple & composants réutilisables.  
- **Testabilité** : UI state en `data class`, fonctions pures, `@Preview`.

## Objectifs pédagogiques
À la fin, vous saurez :
1. Construire des écrans Compose (composables de base, thèmes **Material 3**, layouts).  
2. Gérer l’**état local** avec `remember` / `rememberSaveable` et le *state hoisting*.  
3. Implémenter un **MVVM minimal** : `ViewModel` + **UI state** immuable + **intents**.  
4. Ajouter une **navigation basique** (2 écrans, arguments simples).  

## À qui s’adresse ce module ?
Aux apprenants ayant un projet Android **opérationnel** et des bases Kotlin, souhaitant produire des écrans **maintenables** avant d’aborder le réseau.

## 🔧 Pré-requis
- Avoir terminé **C5.1** (environnement/APK) et **C5.2** (Kotlin essentiel).  
- Projet **Compose** qui build (Gradle Sync OK).

---

## 📦 Livrables attendus
- Un mini-projet Compose avec **2 écrans** (ex. Liste + À propos).  
- **ViewModel** exposant un **UI state** (`data class`) + **intents** (actions utilisateur).  
- **Préviews** et **accessibilité** de base (`contentDescription`, tailles tappables).

## ✅ Definition of Done (autoformation)
- [ ] Composables de base + **Material 3** appliqué (thème/typographie/espacement).  
- [ ] **État local** géré proprement (`rememberSaveable`, *state hoisting*).  
- [ ] **ViewModel** avec `UiState` **immutables** + fonctions d’intent.  
- [ ] **Navigation** entre 2 écrans (arguments simples si besoin).  
- [ ] `strings.xml` pour textes, **a11y** minimale, `@Preview` affichables.

---

## 📘 Unités d’apprentissage & chapitres

### UA 5.3.U1 – Compose de base
- **Chapitre 5.3.1** : Composables essentiels (`Text`, `Button`, `TextField`, `Image`), `@Preview`  
- **Chapitre 5.3.2** : Layouts (Row/Column/Box), thèmes Material 3, espacement & typographie  

### UA 5.3.U2 – État & TODO locale (offline)
- **Chapitre 5.3.3** : `remember` / `rememberSaveable`, *state hoisting*  
- **Chapitre 5.3.4** : `LazyColumn` pour la TODO locale (ajouter, compléter, supprimer)  

### UA 5.3.U3 – MVVM léger & navigation
- **Chapitre 5.3.5** : `ViewModel`, état immuable (UI state) et *intents* d’actions  
- **Chapitre 5.3.6** : Navigation basique (écran Liste + écran « À propos »)  

---

## 💡 Conseils
- **Découpez** l’UI : petits composables, *single source of truth* pour l’état.  
- **Immutabilité** du `UiState` (copie via `.copy()`), éviter la logique dans les composables.  
- Utilisez des **préviews** pour itérer vite et garder un style cohérent (M3).

> Prochaine étape : **5.3.1 — Composables essentiels & `@Preview`**.

---
title: 5.4. Consommer une API
permalink: /android-api-retrofit/
layout: home
nav_order: 4
parent: 5. Mobile
has_children: true
---

# 🎓 Autoformation C5.4 — Consommer une API publique (HTTP/JSON + Retrofit)

Dans ce module, vous allez brancher votre app **Compose** sur une **API publique** avec **Retrofit + Coroutines**, afficher les **états UI** (*loading / empty / error*), et rendre l’expérience robuste (timeouts, déconnexions, **retry**). Vous pratiquerez aussi les écritures (**POST/PATCH/DELETE**) avec **mise à jour optimiste** et rollback en cas d’échec.

## Pourquoi apprendre Retrofit + Coroutines ?
- **Données réelles** : votre UI n’est plus figée — elle vit au rythme du réseau.  
- **Robustesse** : gestion **claire** des erreurs, feedback utilisateur (snackbar/toast).  
- **Lisibilité** : mapping JSON **typé** (Moshi/Gson), `suspend` pour un code fluide.  
- **Séparation** : API client, **Repository**, et **UiState** bien découpés → testable.

## Objectifs pédagogiques
À la fin du module, vous saurez :
1. Configurer **Retrofit + OkHttp (logging)**, **Moshi/Gson**, `baseUrl` via **`BuildConfig`**.  
2. Charger des listes avec **GET** et afficher **loading / empty / error** + **Retry**.  
3. Implémenter **POST/PATCH/DELETE** avec **mise à jour optimiste** + **rollback**.  
4. Traiter les erreurs réseau (timeouts, offline) et exposer un **UiState** clair (sealed).  

## À qui s’adresse ce module ?
Aux apprenants ayant déjà des bases **Compose/MVVM** (C5.3) et souhaitant **connecter** leur app à des **données distantes** sans complexifier l’architecture.

## 🔧 Pré-requis
- Avoir terminé **C5.1–C5.3** (environnement + Compose + MVVM léger).  
- Connaissances Kotlin de base (fonctions/collections, `data class`, null-safety).  
- Connexion Internet ; un émulateur ou device Android opérationnel.

---

## 📦 Livrables attendus
- **APK** + **courte vidéo** (≤ 60s) démontrant *loading / empty / error / retry*.  
- Petite **collection Postman/Insomnia** (ou `curl`) des endpoints utilisés.  
- **README** (setup API, `BuildConfig`, captures) et notes d’erreurs gérées.

## ✅ Definition of Done (autoformation)
- [ ] **GET** liste OK avec **UiState** : *Loading*, *Success(data vide / non vide)*, *Error* + **Retry**.  
- [ ] **POST/PATCH/DELETE** : mise à jour **optimiste** + **rollback** si échec.  
- [ ] **Erreurs réseau** : offline/timeout → messages clairs + action utilisateur.  
- [ ] `baseUrl` en **`BuildConfig`**, **OkHttp logging** actif en *debug* seulement.  
- [ ] Code structuré : **API service** + **Repository** + **ViewModel (UiState)**.

---

## 📘 Unités d’apprentissage & chapitres

### UA 5.4.U1 – HTTP/JSON & outillage réseau
- **Chapitre 5.4.1** : Rappels HTTP (GET/POST/PATCH/DELETE), codes, schéma JSON de l’API choisie  
- **Chapitre 5.4.2** : Retrofit + OkHttp (logging) + Moshi/Gson, `suspend` + Coroutines, `baseUrl` via `BuildConfig`  

### UA 5.4.U2 – Lecture (GET) avec états UI
- **Chapitre 5.4.3** : Charger la liste depuis `/todos` (ou équivalent)  
- **Chapitre 5.4.4** : Afficher *loading / empty / error* + bouton **Retry**  

### UA 5.4.U3 – Écritures simples & robustesse
- **Chapitre 5.4.5** : **POST** (ajouter), **PATCH** (compléter), **DELETE** (supprimer) — *mise à jour optimiste* + rollback en cas d’échec  
- **Chapitre 5.4.6** : Gestion d’erreurs réseau (déconnexions, dépassements de délai), toasts/snackbars, messages clairs  

---

## 🧭 Architecture minimale conseillée
- **ApiService (Retrofit)** : endpoints `suspend`.  
- **Repository** : appelle l’API, **mappe** vers modèles UI, renvoie `Result<T>`/`Either`.  
- **ViewModel** : expose un **`UiState` (sealed class / data class)** et des **intents**.  
- **UI Compose** : rend *loading / empty / error / success* + boutons **Retry**/**Undo**.

```kotlin
sealed interface UiState<out T> {
  object Loading : UiState<Nothing>
  data class Success<T>(val data: T) : UiState<T>
  data class Error(val message: String, val retry: () -> Unit) : UiState<Nothing>
}
````

---

## 💡 Conseils

* **Timeouts** raisonnables (ex. 10–15 s) et messages utilisateurs **concrets**.
* **Log réseau** en *debug* uniquement (`HttpLoggingInterceptor`).
* Toujours prévoir un **chemin offline** : placeholder, *empty state*, **Retry**.
* Tester vos flux avec **erreurs simulées** (mode avion, couper réseau, fausses URLs).

> Prochaine étape : **5.4.1 — Rappels HTTP & schéma JSON** puis **5.4.2 — Retrofit + OkHttp + Moshi/Gson**.


---
title: 6.1.Tests unitaires & d’intégration
permalink: /tests-laravel/
layout: home
nav_order: 1
parent : 6. Tests
has_children: true
---

# 🎓 Tests unitaires & d’intégration (Laravel)

Les tests automatisés constituent un **filet de sécurité** pour votre application. Ils permettent de **décrire le comportement attendu**, de **prévenir les régressions** lors des refactorings et de **documenter** les fonctionnalités de manière vivante. Avec **Pest/PHPUnit**, Laravel fournit un environnement de test productif (helpers HTTP, base de données éphémère, *fakes* de framework).

## Pourquoi apprendre les tests ?
- **Confiance & qualité** : repérer rapidement les bugs et les changements involontaires.
- **Refactorings sereins** : oser simplifier le code grâce à un **filet de tests**.
- **Documentation exécutable** : des exemples vivants plutôt que des specs obsolètes.
- **Intégration continue** : automatiser l’exécution des tests à chaque *commit*.

## Objectifs de l’autoformation
Cette autoformation vise à :  
1. **Initialiser Pest/PHPUnit**, comprendre la structure `tests/` et exécuter `php artisan test`.  
2. Écrire des tests **clairs** en convention **AAA** (Arrange/Act/Assert) pour fonctions/services.  
3. Tester des **routes web/API** (GET/POST…) avec assertions sur **status**, **views** et **JSON**.  
4. Manipuler la **DB de test** : `.env.testing`, `RefreshDatabase`, **Factories** et **seed** minimal.  
5. Utiliser les **fakes** du framework (**Mail**, **Notification**, **Event**, **Storage**) pour isoler les effets.

## À qui s’adresse ce module ?
Aux développeurs **Laravel débutants/intermédiaires** qui souhaitent **fiabiliser** un projet (ex. Blog fil rouge) côté **web** et **API** sans complexifier l’architecture.

---

## 📘 Unités d’apprentissage (UAs) couvertes

### UA 6.1.U1 – Fondamentaux des tests (Pest/PHPUnit)
- **Chapitre 6.1.1** : Organisation de `tests/`, première exécution (`php artisan test`), Pest vs PHPUnit  
- **Chapitre 6.1.2** : Convention **AAA** (Arrange/Act/Assert), assertions courantes (`assertTrue/Equals/Json`)  
- **Chapitre 6.1.3** : Hooks & utilitaires (`setUp` / `beforeEach`), datasets Pest, helpers de tests

### UA 6.1.U2 – Tests HTTP + base de données
- **Chapitre 6.1.4** : Environnement `.env.testing`, `RefreshDatabase`, **sqlite in-memory** (optionnel)  
- **Chapitre 6.1.5** : Tests **HTTP** (routes web/API) : `get/post`, `assertStatus`, `assertViewHas`, `assertJson`  
- **Chapitre 6.1.6** : **Model Factories** & seed minimal : `Model::factory()`, relations, états, `HasFactory`

### UA 6.1.U3 – Doubles & fakes du framework
- **Chapitre 6.1.7** : **Mail::fake()**, **Notification::fake()**, **Event::fake()** + vérifications  
- **Chapitre 6.1.8** : **Storage::fake()**, `UploadedFile::fake()` : upload d’images testé proprement  
- **Chapitre 6.1.9** : Espionnage/mocks légers via le **container** (binding d’un service, *stub* minimal)
---
title: 7.1. Logique binaire & matériel PC
permalink: /deploiement/binaire-matériel/
layout: home
nav_order: 1
has_children: true
parent : 7. Déploiement
---

# 🔌 Introduction — C7.1 Logique binaire & matériel PC

Avant de déployer un site ou une appli, il faut comprendre **comment la machine pense** (le **binaire**) et **sur quoi elle tourne** (le **matériel**). Cette introduction pose les bases : conversions binaire/hex, opérations logiques, et tour d’horizon des composants d’un poste/serveur (CPU, RAM, stockage, carte réseau) — avec un **pont vers le réseau** (masques, ports) qui sera approfondi en C7.2.

---

## 🎯 Objectifs pédagogiques
- Expliquer la **représentation des données** (binaire ↔ décimal ↔ hexadécimal).
- Manipuler des **opérations logiques** simples (ET, OU, XOR, décalages, masques).
- Identifier les **composants clés** d’un PC/serveur et comprendre leurs **rôles/performances**.
- Relier ces notions au **réseau** (masque, MTU, ports) en vue du **déploiement Web**.

## 👥 Public & prérequis
- **Public** : débutants en **déploiement** / **admin système** / **dev web**.
- **Prérequis** : savoir naviguer dans un OS (fichiers, installation basique), notions générales d’informatique.

## 🧪 Livrables attendus
- **Fiche mémo** de conversions (binaire ↔ décimal ↔ hex).
- **Tableau comparatif** des composants (CPU, RAM, SSD/HDD, NIC) avec usages/recommandations.
- **Mini-quiz** de validation (conversions & masques).

---

## 🧩 Activités par niveaux (EPP)
- **N1 – Imitation** : conversions guidées, tables de vérité, repérage des composants sur une fiche technique.
- **N2 – Adaptation** : estimer la config d’un poste (usage bureautique vs. dev), lire un **masque** en binaire.
- **N3 – Transposition** : mini-étude d’un poste réel (Windows/Linux) : relever CPU/RAM/SSD/NIC, proposer un **plan d’upgrade** justifié.

## 🛠️ Outils & ressources suggérés
- Calculatrice (mode programmeur), **Gestionnaire des tâches** / **htop**, `lscpu`, `lsblk`, `ipconfig`/`ifconfig`.
- Fiches techniques fabricants (CPU, RAM, SSD) pour lecture des **spécifications**.

---

## 🔗 UAs couvertes (rappel)
- **UA 7.1.U1 – Logique binaire essentielle**  
  * Chap. 7.1.1 :* Numération binaire/hex et conversions • 
  * Chap. 7.1.2 :* Opérateurs (ET/OU/XOR), décalages et **masques**
- **UA 7.1.U2 – Matériel d’un ordinateur**  
  * Chap. 7.1.3 :* CPU, RAM, disque/SSD, bus & performances • 
  * Chap. 7.1.4 :* Carte réseau (NIC), câblage, duplex, **MTU** (aperçu)
- **UA 7.1.U3 – OS & services (aperçu)**  
  * Chap. 7.1.5 :* Démarrage (BIOS/UEFI), processus & services 
  * Chap. 7.1.6 :* Fichiers, droits de base & hygiène

---

## ✅ Critères d’évaluation (barème indicatif)
- **20% – N1** : exactitude des conversions et compréhension des opérateurs.
- **30% – N2** : lecture/argumentation d’une configuration et d’un **masque binaire**.
- **50% – N3** : mini-étude complète d’un poste + recommandations cohérentes.

## 🏁 Checklist de fin d’intro
- [ ] Je convertis **décimal ↔ binaire ↔ hex** sans table externe.  
- [ ] Je sais expliquer **CPU/RAM/SSD/NIC** et leurs impacts sur les performances.  
- [ ] Je lis un **masque** (ex. `/26`) et je dis ce qu’il implique.  
- [ ] Je relie ces notions au **déploiement Web** (C7.2 → réseau, C7.3 → HTTP, C7.4 → Apache).

> **Étape suivante :** passe à **C7.1.U1** pour pratiquer les conversions et opérations logiques avant d’aborder le matériel.
---
title: 7.2. LAN & adressage IP
permalink: /deploiement/lan-adressage-ip/
layout: home
nav_order: 2
has_children: true
parent : 7. Déploiement
---

# 🌐 Introduction — C7.2 LAN & adressage IP

Construire et exploiter un **réseau local (LAN)** : comprendre les **équipements** (switch/routeur), concevoir un **plan d’adressage IPv4** (masque, CIDR, passerelle, DNS, DHCP) et **diagnostiquer** la connectivité avec les bons outils. Ce module fait le lien entre la **machine** (C7.1) et les **services Web** (C7.3–C7.4).

---

## 🎯 Objectifs pédagogiques
- Concevoir un **plan d’adressage IPv4** cohérent (CIDR, passerelle, DNS, DHCP).
- Expliquer les rôles d’un **switch** et d’un **routeur** (et la **segmentation** VLAN — aperçu).
- **Configurer** : IP statique, passerelle, DNS, bail DHCP ; vérifier la **connectivité**.
- **Diagnostiquer** une panne réseau (couche 3/4) avec les commandes usuelles.

## 👥 Public & prérequis
- **Public** : débutants en **déploiement** / **admin système** / **dev web**.
- **Prérequis** : **C7.1** (logique binaire & matériel), bases terminal (cmd/PowerShell/Bash).

## 🧪 Livrables attendus
- **Plan d’adressage** (CSV/MD) : réseaux, CIDR, passerelles, plages DHCP, DNS.
- **Schéma LAN** (Mermaid ou image) annoté : équipements, ports, liaisons.
- **Journal de diagnostic** : commandes exécutées + observations + conclusion.

---

## 🧩 Activités par niveaux (EPP)
- **N1 – Imitation** : relever l’IP, le masque, la passerelle et le DNS d’un poste ; tester `ping` interne/externe.
- **N2 – Adaptation** : proposer un **plan d’adressage** pour 2–3 sous-réseaux à partir d’un `/24` (ex. `/26` + `/27`), configurer une **IP statique** + DNS, valider la **route** et la **résolution**.
- **N3 – Transposition** : mini-lab (2 réseaux) : un **DHCP**, un **statique**, test **DNS**, **tracé de route** et **test de port** (`curl`), rapport d’incident synthétique.

## 🛠️ Outils & ressources suggérés
- Windows : `ipconfig`, `tracert`, `nslookup`, `netstat`.
- Linux/macOS : `ip a`, `ip route`, `ping`, `tracepath/traceroute`, `dig`, `ss`, `curl`.
- Optionnel : **Wireshark** (capture ICMP/DNS), machine virtuelle (VirtualBox/VM).

---

## 🔗 UAs couvertes (rappel)
- **UA 7.2.U1 – LAN & équipements**  
  * Chap. 7.2.1* : Switch vs routeur, topologies, câblage RJ45 
  * Chap. 7.2.2* : Segmentation (VLAN — aperçu) & notions de port
- **UA 7.2.U2 – Adressage IP**  
  * Chap. 7.2.3* : IPv4, masque, CIDR, passerelle & DNS (aperçu) 
  * Chap. 7.2.4* : DHCP statique/dynamique ; IPv6 (aperçu)
- **UA 7.2.U3 – Outils & diagnostic**  
  * Chap. 7.2.5* : `ping`, `tracert/tracepath`, `ipconfig/ifconfig`
  * Chap. 7.2.6* : `netstat/ss`, test de port (`telnet`/`curl`), pare-feu de base

---

## ✅ Critères d’évaluation (barème indicatif)
- **20% – N1** : restitution des notions (LAN, CIDR, passerelle, DNS) + commandes de base.
- **30% – N2** : plan d’adressage correct et configuration statique fonctionnelle (preuves).
- **50% – N3** : mini-lab cohérent (DHCP + statique) + **diagnostic argumenté** et actions correctives.

## 🏁 Checklist de fin d’intro
- [ ] Mon **plan d’adressage** (CIDR, passerelle, DNS) couvre tous les sous-réseaux.  
- [ ] Une **IP statique** est configurée sans conflit et je **ping** la passerelle/Internet.  
- [ ] La **résolution DNS** fonctionne (`nslookup/dig`) et je teste un **port** (`curl -I`).  
- [ ] Mon **schéma LAN** correspond à l’architecture réelle (équipements/ports/liaisons).

> **Étape suivante :** attaquez **7.2.1** (équipements & topologies), puis **7.2.3** (adressage IPv4/CIDR) pour pratiquer la conception d’un LAN complet.
---
title: 7.3. Serveur Web
permalink: /deploiement/http-principes/
layout: home
nav_order: 3
has_children: true
parent : 7. Déploiement
---


# 🌍 Introduction — C7.3 Serveur Web : principes & HTTP

Ce module explique **comment un serveur Web répond aux clients** via **HTTP/HTTPS**, les **méthodes** (`GET`, `POST`…), les **codes de statut** (`2xx/3xx/4xx/5xx`), les **en-têtes** (cache, CORS, auth) et la différence **statique vs dynamique** (ex. PHP/FPM). Il relie votre **réseau (C7.2)** aux **services applicatifs** et prépare la **mise en ligne (C7.4)**.

---

## 🎯 Objectifs pédagogiques
- Décrire le **cycle d’une requête HTTP** et interpréter les **codes de statut** courants.  
- Inspecter/Tester des réponses : **en-têtes**, **MIME**, **redirections**, **corps**.  
- Lire des **journaux serveur** (access/error) et diagnostiquer une panne.  
- Distinguer **contenu statique** et **contenu dynamique** (ex. PHP/FPM — aperçu).  

## 👥 Public & prérequis
- **Public** : débutants en **déploiement**, **admin système** ou **dev web**.  
- **Prérequis** : **C7.2** (LAN, IP, DNS) + bases terminal (`curl`, `ping`).  

## 🧪 Livrables attendus
- Capture et analyse d’une réponse `curl -I` (**headers**, **code HTTP**, **MIME**).  
- Tableau **codes HTTP** (≥ 10) avec cas d’usage.  
- Extraits **access.log** / **error.log** annotés (IP, date, méthode, statut, UA).  
- Mini-rapport **“Traçage d’une requête”** (symptôme → hypothèses → vérifs → cause → correctif).

---

## 🧩 Activités par niveaux (EPP)
- **N1 – Imitation** : exécuter `curl -I`, identifier `200/301/404/500`, lister 5 headers.  
- **N2 – Adaptation** : suivre une **redirection** (`-L`), envoyer un **POST JSON**, expliquer un `403/415`.  
- **N3 – Transposition** : corréler `access.log` & `error.log` sur un incident réel et proposer un **correctif** (config, route, permission, MIME).

## 🛠️ Outils & ressources suggérés
- **Ligne de commande** : `curl`, `wget`, `openssl s_client` (aperçu TLS).  
- **Navigateurs** : DevTools (onglet **Network**).  
- **Serveurs** : Apache/Nginx (fichiers **access/error logs**).  

---

## 🔗 UAs couvertes (rappel)
- **UA 7.3.U1 – HTTP/HTTPS en pratique**  
  * Chap. 7.3.1* : Méthodes, codes, en-têtes, **MIME** 
  * Chap. 7.3.2* : **TLS/HTTPS** (certificats — aperçu)  
- **UA 7.3.U2 – Architecture serveur Web**  
  * Chap. 7.3.3* : **Statique vs dynamique** (PHP/FPM — aperçu)
  * Chap. 7.3.4* : Processus, service, port, sécurité de base  
- **UA 7.3.U3 – Journaux & observation**  
  * Chap. 7.3.5* : **Logs** d’accès/erreurs, rotation & lecture
  * Chap. 7.3.6* : **Traçage** client → serveur

---

## ✅ Critères d’évaluation (barème indicatif)
- **20% – N1** : restituer notions HTTP, exécuter `curl -I`, reconnaître familles **2xx/3xx/4xx/5xx**.  
- **30% – N2** : suivre redirections, POST JSON valide, expliquer un cas d’erreur **4xx/5xx**.  
- **50% – N3** : traçage bout-à-bout (logs + hypothèses + vérifs + correctif) bien argumenté.

## 🏁 Checklist de fin d’intro
- [ ] Je lis **headers** et **code** avec `curl -I` / DevTools.  
- [ ] Je distingue **statique** vs **dynamique** et l’impact sur la perf.  
- [ ] Je sais où trouver et comment lire **access.log** / **error.log**.  
- [ ] Je relie HTTP à mon **LAN/DNS** (C7.2) et j’anticipe la **mise en ligne** (C7.4).

> **Étape suivante :** enchaîner avec **Chapitre 7.3.1** (méthodes, codes, en-têtes, MIME) puis **7.3.5** (lecture des logs) pour s’exercer au diagnostic.
---
title: 7.4. Apache
permalink: /deploiement/apache-vhosts/
layout: home
nav_order: 4
has_children: true
parent : 7. Déploiement
---

# 🛠️ Introduction — C7.4 Apache : installation, vhosts & mise en ligne

Objectif : **installer** et **piloter** Apache, créer des **VirtualHosts** (plusieurs sites sur une même machine), configurer les **répertoires/permissions**, activer la **réécriture d’URL** et réaliser une **mise en ligne** basique (site statique + page PHP). Ce module prolonge **C7.2 (réseau/IP)** et **C7.3 (HTTP)** vers l’**hébergement concret**.

---

## 🎯 Objectifs pédagogiques
- Installer Apache (Windows **WAMP/XAMPP** ou **Linux**) et gérer le **service** (`systemctl`, `apachectl`).
- Comprendre l’**arborescence de configuration** et tester la **santé** (`apachectl -t`).
- Créer et activer un **VirtualHost** (DocumentRoot, logs, index, alias).
- Activer **mod_rewrite** et vérifier les **règles** (.htaccess ou conf).
- Déployer un **mini-site** (statique + `index.php`) avec **permissions** correctes.

## 👥 Public & prérequis
- **Public** : débutants en **déploiement** / **admin système** / **dev web**.  
- **Prérequis** : **C7.2** (LAN, IP, DNS), **C7.3** (HTTP), notions terminal (cmd/PowerShell/Bash).

## 🧪 Livrables attendus
- Fichier **vhost** final (nom de domaine local, DocumentRoot, logs).  
- **Arborescence** du site (captures) + preuve d’accès HTTP.  
- Test **mod_rewrite** (URL propre → `index.php`).  
- Mini‐rapport : étapes, commandes, problèmes rencontrés, correctifs.

---

## 🧩 Activités par niveaux (EPP)
- **N1 – Imitation** : installation, page par défaut, démarrage/arrêt du service, test `apachectl -t`.  
- **N2 – Adaptation** : création d’un **vhost** `site.local`, activation **mod_rewrite**, test `.htaccess`.  
- **N3 – Transposition** : déploiement d’un mini‐site (assets + `index.php`), **logs** dédiés, permissions sûres, check liste de mise en ligne.

## 🛠️ Outils & ressources suggérés
- **Linux (Debian/Ubuntu)** : `apt`, `systemctl`, `a2ensite`/`a2dissite`, `a2enmod rewrite`.  
- **Linux (RHEL/CentOS/Alma)** : `dnf`/`yum`, `systemctl`, conf sous `/etc/httpd/`.  
- **Windows** : **WAMP/XAMPP**, **Services.msc**.  
- **Commun** : `apachectl -t`, fichiers **logs** (`access.log`, `error.log`), éditeur texte, `/etc/hosts`.

---

## 🔗 UAs couvertes (rappel)
- **UA 7.4.U1 – Installer & piloter Apache**  
  * Chap. 7.4.1* : Installation (Windows/Linux), `service/systemctl`
  * Chap. 7.4.2* : Arborescence de conf, test de santé  
- **UA 7.4.U2 – VirtualHosts & répertoires**  
  * Chap. 7.4.3* : Vhost (DocumentRoot, logs)
  * Chap. 7.4.4* : Droits/permissions, index, alias, **mod_rewrite**  
- **UA 7.4.U3 – Mise en ligne basique & hygiène**  
  * Chap. 7.4.5* : Déployer un mini‐site (statique + PHP)
  * Chap. 7.4.6* : Bonnes pratiques (sauvegarde conf, logs, HTTPS – aperçu)

---

## 🔧 Cheatsheet — commandes utiles

### Debian/Ubuntu
```bash
# Installer & démarrer
sudo apt update && sudo apt install -y apache2
sudo systemctl enable --now apache2

# Vérifier configuration
sudo apachectl -t

# Activer mod_rewrite
sudo a2enmod rewrite
sudo systemctl reload apache2

# Créer/activer un vhost
sudo nano /etc/apache2/sites-available/site.local.conf
sudo a2ensite site.local
sudo systemctl reload apache2