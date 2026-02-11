# 2 Fils en Aiguilles

**2 Fils en Aiguilles** est une application web de gestion pour un atelier de couture, permettant de gérer des cours et la location de matériel.

## Installation en local

Suivez ces étapes pour faire fonctionner le projet sur votre ordinateur.

### Prérequis

- **Serveur local** : [Laragon](https://laragon.org/), [XAMPP](https://www.apachefriends.org/) ou [MAMP](https://www.mamp.info/).
- **PHP** : Version 8.2 minimum.
- **Composer** : [Télécharger Composer](https://getcomposer.org/).
- **Base de données** : MySQL.

### Étapes d'installation

1. **Récupérer le projet** :
   ```bash
   git clone https://github.com/melindaland/2Fils-en-Aiguilles.git
   cd 2Fils-en-Aiguilles
   ```

2. **Installer les dépendances** :
   ```bash
   composer install
   ```

3. **Base de données** :
   - Ouvrez **phpMyAdmin**.
   - Créez une nouvelle base de données nommée `sae301`.
   - Importez le fichier `sae301.sql` qui se trouve à la racine du projet.

4. **Configuration du site** :
   - Allez dans le dossier `include/`.
   - Copiez le fichier `config.php.example` et renommez-le en `config.php`.
   - Modifiez les identifiants à l'intérieur si nécessaire (par défaut configuré pour MAMP/Laragon).

5. **Accès au site** :
   - Placez le dossier du projet dans votre répertoire `www` ou `htdocs`.
   - Ouvrez votre navigateur sur : `http://localhost/2Fils-en-Aiguilles/visiteur.php`.

## Identifiants

- **login admin** : `admin24!`
- **login professionnel** : `pro24!`


## Technologies utilisées

- **Langage** : PHP 8.2
- **Moteur de templates** : Twig 3
- **Base de données** : MySQL (PDO)
- **Design** : CSS3 & Bootstrap

---
*Projet réalisé dans le cadre de la SAE 301 - Développement Web.*