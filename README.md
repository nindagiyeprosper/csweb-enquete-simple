# Enquete simple sur terrain avec CSPro 
 
Serveur **CSWeb** install‚ localement sous **XAMPP** pour synchroniser les questionnaires **CSEntry** (Android) lors d'enquˆtes sur le terrain au Burundi. 
 
## Fonctionnalités actuelles (mars 2026) 
- Synchronisation des donn‚es depuis CSEntry (Android) vers le serveur local 
- Gestion des roles utilisateurs : admin, superviseur, controleur, agent enqueteur 
- Capture GPS optionnelle (latitude, longitude, altitude, précision en mètres + noms administratifs : province, commune, zone, colline/quartier) 
- Téléchargement des données en .csv / .dat / .zip depuis l'interface CSWeb 
- Test réussi : 1 cas synchronis‚ (mars 2026) 
 
## Prérequis 
- Windows (test‚ sur Windows 10) 
- XAMPP (Apache + MySQL + PHP 8+) 
- CSPro 8.0+ install‚ 
- CSEntry install‚ sur les téléphones Android des enqueteurs 
 
## Installation rapide (local sur PC) 
1. Télécharger et installer **XAMPP** : https://www.apachefriends.org/fr/index.html 
2. Démarrer XAMPP  lancer Apache et MySQL 
3. Copier le dossier `csweb` dans : `C:\xampp\htdocs\csweb` 
4. Ouvrir dans le navigateur : http://localhost/csweb/setup/setup.php 
5. Suivre l'assistant : base `csweb_db`, utilisateur `root`, mot de passe vide 
6. Connexion … l'interface : http://localhost/csweb/ (admin + mot de passe) 
 
## Connexion des enquˆteurs (depuis leurs t‚l‚phones Android) 
Tous les téléphones doivent ˆtre sur le **meme réseau Wi-Fi** que l'ordinateur serveur. 
URL dans CSEntry : http://adresse ip ou le nom du domaine/csweb/ (remplace par l'IP actuelle via ipconfig) 
 
## Auteur & contact 
**Prosper Nindagiye** <br>
Bujumbura, Burundi 
Mars 2026<br>
nindagiyeprosper@gmail.com<br>
+25767895912
