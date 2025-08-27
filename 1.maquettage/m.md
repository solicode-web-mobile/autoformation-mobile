```yaml
---
title: 1. Persona prioritaire
permalink: /analyse-besoin/persona-prioritaire/
code: 1.1.1
competence: C1
autoformation: "C1.1"
ua: "1.1.U1"
duree_h: 1.5
objectif: "Produire une fiche persona d’une page qui cadre qui on sert en premier, pourquoi, dans quelles conditions et comment mesurer le succès."
notions_nouvelles: ["MVP", "User story", "GWT (Given/When/Then)", "UC (Cas d’utilisation UML)", "Métrique de succès"]
fil_rouge: "Blog Laravel + App Mobile (lecture & ranking)"
livrable_chapitre: "Fiche persona prioritaire (≤ 1 page) avec 3 scénarios GWT et 2–3 métriques de succès"
alimentation_prototype: "Oriente la priorisation des fonctionnalités (filtre 'Populaire', favoris, partage rapide) du prototype MVP"
alimentation_miniprojet: "Structure le backlog MVP et les critères de validation du mini-projet Blog"
---
```



```yaml
---
title: 2. Problem statement & métriques de succès
permalink: /analyse-besoin/problem-statement-metrics/
code: 1.1.2
competence: C1
autoformation: "C1.1"
ua: "1.1.U1"
duree_h: 1.5
objectif: "Rédiger un problem statement relié au persona prioritaire et définir 2–3 métriques SMART (dont 1 NSM) pour juger le succès du MVP."
notions_nouvelles: ["Problem statement", "KPI / métrique de succès", "North Star Metric (NSM)", "SMART", "Baseline"]
fil_rouge: "Blog Laravel + App Mobile (lecture & ranking)"
livrable_chapitre: "Deux fichiers : problem-statement.md (≤ 6 lignes) et success-metrics.md (tableau complet, versionnés)"
alimentation_prototype: "Guide l’instrumentation (événements/mesures) et le choix des fonctionnalités mesurables du prototype N2"
alimentation_miniprojet: "Fournit les indicateurs de succès et les cibles chiffrées à suivre dans le mini-projet N3"
---
```



```yaml
---
title: 3. User stories au format GWT
permalink: /analyse-besoin/user-stories-gwt/
code: 1.1.3
competence: C1
autoformation: "C1.1"
ua: "1.1.U2"
duree_h: 1.5
objectif: "Rédiger 5 à 8 user stories claires et testables pour le fil rouge, chacune avec au moins 1 scénario GWT."
notions_nouvelles: ["Critères d’acceptation (AC)", "INVEST", "DoR/DoD"]
fil_rouge: "Blog Laravel + App Mobile (lecture & ranking)"
livrable_chapitre: "docs/backlog/user-stories.md (IDs stables US-xxx + scénarios GWT)"
alimentation_prototype: "Fournit les cas de test (GWT) servant de DoD pour le prototype N2"
alimentation_miniprojet: "Alimente le backlog et la traçabilité des tests d’acceptation du mini-projet N3"
---
```



```yaml
---
title: 4. Backlog MVP priorisé (MoSCoW)
permalink: /analyse-besoin/backlog-mvp-moscow/
code: 1.1.4
competence: C1
autoformation: "C1.1"
ua: "1.1.U2"
duree_h: 1.5
objectif: "Constituer un backlog MVP clair et priorisé avec MoSCoW à partir des stories et produire une sélection exécutable en local."
notions_nouvelles: ["MoSCoW", "Epic / Story", "Estimation rapide (T-shirt / points)"]
fil_rouge: "Blog Laravel + App Mobile (lecture & ranking)"
livrable_chapitre: "docs/backlog/backlog-mvp.md (table MoSCoW + sélection MVP v0.1)"
alimentation_prototype: "Fige le périmètre Must du prototype v0.1 (parcours minimal Web + Mobile)"
alimentation_miniprojet: "Donne la feuille de route N3 (items Should/Could/Won’t reportés en itérations)"
---
```



```yaml
---
title: 5. Acteurs & 3 UC principaux
permalink: /analyse-besoin/acteurs-uc/
code: 1.1.5
competence: C1
autoformation: "C1.1"
ua: "1.1.U3"
duree_h: 1.5
objectif: "Identifier les acteurs et produire 3 cas d’utilisation centraux avec fiches courtes et première traçabilité vers les stories."
notions_nouvelles: ["Acteur", "Système", "UC (Cas d’utilisation)", "Scénario principal", "Pré/Post-conditions", "Traçabilité"]
fil_rouge: "Blog Laravel + App Mobile (lecture & ranking)"
livrable_chapitre: "docs/uml/acteurs-uc.md (acteurs, diagramme ASCII, 3 fiches UC) + extrait de matrice de traçabilité"
alimentation_prototype: "Définit les UC et écrans brique-de-base à implémenter dans le prototype (liste, détail, toggle admin)"
alimentation_miniprojet: "Stabilise le périmètre fonctionnel et la documentation UC pour le mini-projet N3"
---
```



```yaml
---
title: 6. Mini-matrice stories ↔ UC ↔ écrans
permalink: /analyse-besoin/matrice-stories-uc-ecrans/
code: 1.1.6
competence: C1
autoformation: "C1.1"
ua: "1.1.U3"
duree_h: 1.5
objectif: "Produire une matrice compacte prouvant la couverture du MVP par les 3 UC principaux et des écrans/URLs concrets."
notions_nouvelles: ["Traçabilité", "Couverture", "IDs stables (US-xxx, UC-xx, SCR-xxx)"]
fil_rouge: "Blog Laravel + App Mobile (lecture & ranking)"
livrable_chapitre: "docs/trace/matrice-stories-uc-ecrans.md + docs/trace/matrice-stories-uc-ecrans.csv"
alimentation_prototype: "Sert de checklist de démo et de vérification de couverture pour le prototype N2"
alimentation_miniprojet: "Documente la traçabilité complète (Stories↔UC↔Écrans/Endpoints) exigée au N3"
---
```



> Repérage UA par chapitre conforme au référentiel C1.1 (U1: 1.1.1–1.1.2, U2: 1.1.3–1.1.4, U3: 1.1.5–1.1.6).&#x20;
