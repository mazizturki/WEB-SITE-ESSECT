# 🎓 **Site Web Dynamique pour l’ESSECT**

Bienvenue dans le projet de développement d'un **site web dynamique** pour l’**École Supérieure des Sciences Économiques et Commerciales de Tunis (ESSECT)**. Ce projet permet de moderniser l'interaction académique et administrative au sein de l’ESSECT en fournissant des fonctionnalités comme un **espace étudiant sécurisé**, un **forum collaboratif** et l'**automatisation des services administratifs**.

---

## 🚀 **Prérequis**

Avant de démarrer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

1. **[XAMPP](https://www.apachefriends.org/index.html)** ou un autre serveur local.
2. Apache et MySQL fonctionnels via XAMPP.
3. Un éditeur de texte tel que **Visual Studio Code** ou **Sublime Text** pour éditer les fichiers.

---

## 🛠️ **Installation et Configuration**

### **Étape 1 : Télécharger et Installer XAMPP**
1. Téléchargez **XAMPP** depuis [apachefriends.org](https://www.apachefriends.org/index.html).
2. Installez **XAMPP** sur votre machine.
3. Assurez-vous que les modules **Apache** et **MySQL** sont activés dans le panneau de contrôle XAMPP.

### **Étape 2 : Configuration de la Base de Données**
1. Ouvrez [phpMyAdmin](http://localhost/phpmyadmin/) dans votre navigateur.
2. Créez une nouvelle base de données, par exemple **`essect_db`**.
3. Importez la base de données SQL fournie (**`essect_db.sql`**).
4. Allez dans **Importer**, sélectionnez le fichier SQL fourni et cliquez sur **Exécuter**.

### **Étape 3 : Lancer le Projet**
1. Téléchargez le dossier du projet et placez-le dans le répertoire `htdocs` de **XAMPP** (par exemple, `C:/xampp/htdocs/ESSECT_WEB/`).
2. Lancez les modules **Apache** et **MySQL** depuis le panneau de contrôle **XAMPP**.
3. Accédez au projet via votre navigateur à l'adresse suivante :  
   `http://localhost/ESSECT_WEB/index.html`

---

## ⚙️ **Fonctionnalités**

- **Interface utilisateur interactive** : Page d’accueil dynamique et responsive accessible depuis `index.html`.
- **Gestion de la base de données** : Importez et modifiez les données via phpMyAdmin.
- **Forum collaboratif** : Permet l’interaction entre étudiants et enseignants.
- **Automatisation des services administratifs** : Gère les demandes administratives via PHP et MySQL.

---

## 📦 **Dépendances supplémentaires**

- **CSS** : Vérifiez que tous les fichiers `.css` sont dans le répertoire `css/`.
- **JS** : Vérifiez que les fichiers `.js` sont dans le répertoire `js/`.
- **PHP** : Vérifiez que les fichiers `.php` sont dans le répertoire `php/`.
- **Images** : Vérifiez que les fichiers d’images sont dans le répertoire `img/`.
- **PDF** : Vérifiez que les fichiers PDF sont dans le répertoire `pdf/`.

---

## 🔧 **Résolution des Problèmes**

### **Problème de connexion à la base de données**
- Vérifiez les informations de connexion dans le fichier **`db_config.php`**.
- Assurez-vous que le fichier **SQL** a bien été importé dans **phpMyAdmin**.

### **Problème de chargement de la page**
- Assurez-vous que les modules **Apache** et **MySQL** sont démarrés.
- Vérifiez l'URL dans votre navigateur (`http://localhost/ESSECT_WEB/index.html`).

---

## 👨‍💻 **Auteur**

Ce projet a été créé par **Mohamed Aziz TURKI** en novembre 2024.

Version **0.1** - Développée en décembre 2024 en **FR**.

---

## 📄 **Licence**

Ce projet est sous **licence MIT**.

---

### 📢 **Notes supplémentaires**:
- Assurez-vous que votre serveur local (XAMPP ou autre) est correctement configuré pour éviter les erreurs lors de l'exécution du projet.
- Pour toute question ou problème, n'hésitez pas à ouvrir une **issue** dans le dépôt.

---
