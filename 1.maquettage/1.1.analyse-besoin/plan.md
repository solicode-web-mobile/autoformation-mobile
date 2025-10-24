# 🎓 Autoformation C1.1 – Analyse du besoin *(version simplifiée)*

> 💡 **But** : apprendre à réfléchir avant de coder.  
> Savoir **pour qui** on développe, **pourquoi** et **comment** notre application aidera l’utilisateur.

---

## 🧭 L’analyse du besoin et le Design Thinking

Cette autoformation est une **introduction simplifiée au Design Thinking**, la méthode utilisée par les grandes équipes de conception pour créer des produits utiles.

Le **Design Thinking** repose sur 5 étapes :  
1️⃣ **Comprendre** l’utilisateur (*Empathize*)  
2️⃣ **Définir** son problème (*Define*)  
3️⃣ **Imaginer** des solutions (*Ideate*)  
4️⃣ **Dessiner / prototyper** les écrans (*Prototype*)  
5️⃣ **Tester / valider** les idées (*Test*)

👉 Dans ce tutoriel, tu vas suivre **exactement ce même parcours**, mais en version courte et concrète pour ton projet fil rouge :

| Étape Design Thinking | Étape ici | Objectif concret |
| ---------------------- | ---------- | ---------------- |
| 👂 **Comprendre** | Étape 1 – Identifier l’utilisateur | Savoir pour qui on crée |
| 💬 **Définir** | Étape 2 – Décrire le problème | Exprimer le besoin principal |
| 💡 **Imaginer** | Étape 3 – Lister les fonctionnalités + UC | Choisir les fonctions utiles |
| ✏️ **Prototyper** | Étape 4 – Dessiner les écrans | Visualiser le produit |
| ✅ **Tester** | Étape 5 – Relier besoins ↔ écrans | Vérifier que tout a du sens |

> 💬 En résumé :  
> L’analyse du besoin, c’est du **Design Thinking pour développeurs** :  
> on réfléchit comme un designer avant de coder comme un programmeur.

---

## 🎯 Objectif global

À la fin de cette autoformation, tu sauras :

1. Identifier **ton utilisateur principal**.  
2. Décrire **le problème qu’il rencontre**.  
3. Choisir **les fonctionnalités les plus utiles** et formuler les **cas d’utilisation**.  
4. Dessiner **3 écrans simples** pour ton futur site ou app.  
5. Relier **chaque écran à un besoin concret**.

---

## 🧩 Étapes de travail

### Étape 1 – 👤 Identifier l’utilisateur principal
🕒 *Durée : 1 h*

**Objectif :** savoir pour qui tu crées ton projet.

1. Donne un **nom** à ton utilisateur (ex : Meryem, lectrice pressée).  
2. Décris-le en **3 phrases** : âge, situation, habitudes.  
3. Écris **3 besoins** et **1 frustration** qu’il rencontre.  

📄 **Livrable :** une mini fiche “Mon utilisateur principal”.

---

### Étape 2 – 💬 Décrire le problème à résoudre
🕒 *Durée : 1 h*

**Objectif :** exprimer le besoin principal en une seule phrase.

> 🧠 Modèle à compléter :
> “Mon utilisateur a du mal à **[faire quoi ?]**,  
> parce que **[pourquoi ?]**,  
> je veux l’aider à **[résultat souhaité]**.”

📄 **Livrable :** une phrase “Problème → Solution”.

---

### Étape 3 – ⚙️ Lister les fonctionnalités principales et leurs cas d’utilisation (UC)
🕒 *Durée : 1 h 30*

**Objectif :** décider ce que ton application doit faire et représenter *qui fait quoi*.

---

#### 1️⃣ Lister les fonctionnalités
Note toutes les idées de fonctions (afficher, chercher, liker, etc.).  
Classe-les ensuite dans 3 catégories :  
- 🟥 **Must** : indispensables  
- 🟧 **Should** : utiles  
- 🟩 **Could** : bonus

📄 **Livrable partiel :** un tableau ou une photo de ton tri.

---

#### 2️⃣ Formuler les cas d’utilisation (UC)
Pour chaque fonctionnalité importante, décris un **cas d’utilisation** :

> “En tant que **[acteur]**, je veux **[action]** afin de **[objectif]**.”

💡 **Exemples (Blog Laravel + App Mobile)** :
- UC1 — En tant que lecteur, je veux voir la liste des articles pour parcourir les nouveautés.  
- UC2 — En tant que lecteur, je veux ouvrir un article pour lire son contenu complet.  
- UC3 — En tant que lecteur, je veux enregistrer un article pour le relire plus tard.  
- UC4 — En tant qu’administrateur, je veux publier un article pour le rendre visible.

---

#### 3️⃣ Créer un mini diagramme de cas d’utilisation UML
🕒 *Durée : 45 min*

Le **diagramme de cas d’utilisation** permet de visualiser les **interactions entre les acteurs et le système**.

##### Exemple : Blog Laravel + App Mobile

**Acteurs :**
- 👩‍💻 Lecteur  
- 🧑‍💼 Admin

**Cas d’utilisation :**
- UC1 : Lire un article  
- UC2 : Sauvegarder un article  
- UC3 : Partager un article  
- UC4 : Gérer les articles (Admin)

```text
         +-----------------------+
         |       Blog App        |
         | (Laravel + Mobile)    |
         +-----------------------+
          /        |        \
      Lire   Sauvegarder   Partager
       |         |           |
     [Lecteur] [Lecteur]   [Lecteur]
                  |
               Gérer articles
                  |
               [Admin]
````

📄 **Livrable :**

* Un tableau de fonctionnalités + UC
* Un mini diagramme de cas d’utilisation (papier ou draw.io)

---

### Étape 4 – 🖼️ Dessiner les écrans principaux

🕒 *Durée : 2 h*

**Objectif :** imaginer à quoi ressemblera ton produit.

1. Dessine **3 écrans maximum** (Accueil, Détail, Formulaire ou Profil).
2. Relie-les avec des **flèches** pour montrer la navigation.
3. Indique sous chaque écran à quoi il sert.

📄 **Livrable :** une mini-maquette papier ou Figma simple.

---

### Étape 5 – 🔗 Relier besoins, UC et écrans

🕒 *Durée : 30 min*

**Objectif :** vérifier que chaque écran répond à un vrai besoin.

> Exemple :
> “Besoin : Trouver rapidement un article” → UC1 → Page d’accueil
> “Besoin : Lire un article complet” → UC2 → Page de détail
> “Besoin : Sauvegarder pour plus tard” → UC3 → Page favoris”

📄 **Livrable final (analyse complète)**

1. Fiche utilisateur
2. Phrase problème
3. Tableau fonctionnalités + UC
4. Diagramme de cas d’utilisation
5. Maquettes d’écrans
6. Tableau besoins ↔ UC ↔ écrans

---

## 🧾 Résumé

> L’analyse du besoin, c’est **réfléchir avant de coder** :
>
> * Qui va utiliser mon site ?
> * Pourquoi en a-t-il besoin ?
> * Quelles sont les fonctions clés à implémenter ?
> * Comment ces fonctions s’enchaînent-elles dans l’application ?

Et c’est exactement la logique du **Design Thinking** :
👉 comprendre → définir → imaginer → prototyper → tester.

---

## 🧪 Évaluation rapide

| Niveau | Compétence observée | Critère                                                              |
| ------ | ------------------- | -------------------------------------------------------------------- |
| N1     | Compréhension       | L’utilisateur et son problème sont bien identifiés                   |
| N2     | Structuration       | Les besoins, UC et écrans sont cohérents                             |
| N3     | Autonomie           | Les livrables (persona, UC, maquettes) sont complets et exploitables |

---

## 📄 Livrable final attendu

Un **document d’analyse complet** (1 page ou 3 slides max) contenant :

1. Une **fiche utilisateur simple**
2. Une **phrase problème / solution**
3. Un **tableau de fonctionnalités + UC**
4. Un **diagramme de cas d’utilisation**
5. **3 écrans dessinés** avec navigation
6. Une **table de correspondance besoin → UC → écran**

---

## 💡 Fil rouge : Blog Laravel + App Mobile

Tu t’appuies sur le **fil rouge** de l’année :

> un **Blog Laravel (Web)** et une **App Mobile Android** pour lire et classer les articles.

Cette analyse prépare les prochaines étapes :

* **C1.2 – Maquettage** : wireframes et styles de base.
* **C2.1 – Conception technique** : diagramme de classes et schéma relationnel.

---

## 🧠 À retenir

> Une bonne analyse du besoin répond à trois questions :
> 1️⃣ **Qui** utilise le produit ?
> 2️⃣ **Quel besoin** ou problème veut-il résoudre ?
> 3️⃣ **Comment** l’application y répond (UC + écrans) ?

Et pour visualiser ces réponses, on utilise le **diagramme de cas d’utilisation UML** 🎯

