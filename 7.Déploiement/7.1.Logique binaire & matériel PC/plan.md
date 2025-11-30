Excellent 👌 tu veux **garder la structure et les intitulés d’origine** :

> **UA 7.1.U3 – OS & services**
> • Chap. 7.1.5 : Démarrage (BIOS/UEFI), processus & services
> • Chap. 7.1.6 : Fichiers, droits de base & hygiène

…mais **réécrire le contenu complètement**, pour que cette UA se limite **aux bases nécessaires au déploiement d’une application sur une machine** (pas d’administration système avancée).

Voici la **nouvelle version adaptée** 👇

---

### 🔹 **UA 7.1.U3 — OS & services essentiels au déploiement**

**🎯 Objectif :**
Acquérir les **bases du fonctionnement d’un système d’exploitation** et des **services essentiels** afin de pouvoir **installer, exécuter et maintenir une application web** sur une machine (locale ou serveur).

L’apprenant découvre comment un système démarre, gère ses processus et services, organise ses fichiers et contrôle les droits d’accès.

---

### 🧭 **Chap. 7.1.5 — Démarrage (BIOS/UEFI), processus & services**

**Objectif :** Comprendre comment un ordinateur charge son système d’exploitation et lance les services nécessaires au fonctionnement d’une application.

**Contenu :**

* **BIOS / UEFI** : rôle dans la séquence de démarrage et reconnaissance du matériel.
* **Boot du système** : chargement du noyau (kernel) puis des services de base.
* **Processus** : programmes en cours d’exécution ; identifier les plus utilisés.

  * Windows : `Gestionnaire des tâches` → onglet “Processus”
  * Linux : `ps aux`, `top`, `htop`
* **Services essentiels au déploiement** :

  * Serveur web : **Apache** ou **Nginx**
  * Base de données : **MySQL / MariaDB**
  * Interface réseau : **SSH**
* Commandes utiles :

  * Linux : `systemctl start apache2`, `systemctl status mysql`
  * Windows : `services.msc`, `net start mysql`
* Vérifier qu’un service fonctionne (port 80, 443, 3306, 22).

  * `netstat -tuln` / `ss -lnt` / `telnet localhost 80`

**Mini-exercice :**

> Démarre le service Apache, puis vérifie qu’il est bien actif sur le port 80.

---

### 🧭 **Chap. 7.1.6 — Fichiers, droits de base & hygiène**

**Objectif :** Savoir manipuler les fichiers d’un projet web, attribuer les bons droits et adopter une hygiène système minimale pour éviter les erreurs au déploiement.

**Contenu :**

* **Arborescence système simplifiée** :

  * Linux : `/home`, `/etc`, `/var/www/html`, `/usr/bin`
  * Windows : `C:\Program Files`, `C:\xampp\htdocs`
* **Commandes de base** :

  * `cd`, `ls`, `pwd`, `mkdir`, `cp`, `rm`, `cat`, `echo`
* **Droits et permissions** :

  * Lecture (r), écriture (w), exécution (x)
  * Exemples : `chmod 755 monapp`, `chown www-data monapp`
  * Ne pas exécuter les commandes en **root** sans nécessité.
* **Hygiène système** :

  * Organiser les projets dans un dossier dédié (`/var/www/html/monapp`).
  * Sauvegarder avant toute modification (`cp fichier.conf fichier.conf.bak`).
  * Nettoyer les fichiers inutiles (`rm *.log ` obsolètes).
  * Vérifier l’espace disque et la charge (`df -h`, `top`).

**Mini-exercice :**

> Crée un dossier `monapp`, copie un fichier `index.php`, donne les droits de lecture et exécution à Apache.

---

### **📦 Livrables attendus**

* Fiche mémo : “Commandes et services de base pour le déploiement”
* Capture d’écran d’un service démarré + vérification de port
* Journal de manipulation (`commands.txt` ou `README`)

---

### **✅ Critères d’évaluation**

* Compréhension du rôle du BIOS/UEFI et du démarrage système
* Capacité à identifier et gérer les services nécessaires au déploiement
* Bonne maîtrise des commandes de base et des droits
* Organisation claire et respect des bonnes pratiques d’hygiène système

---

Souhaites-tu que je t’intègre directement cette version reformulée dans le **fichier complet “C7.1 Logique binaire & matériel PC”** (en remplaçant la section actuelle de UA 7.1.U3) ?
