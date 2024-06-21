# TP_Docker_MERN

# Objectif
L'objectif de ce TP est de déployer une application web MERN complète utilisant docker compose.
Configurez et déployez les services MongoDB (administré par mongo-express) pour la base de
données, Express pour l'API backend, React pour le frontend, et Nginx pour servir l'application
React et faire du reverse proxy vers l'API Express.

# Depot Git
Pour commencer, nous allons cloner le depot git avec la commande *git clone https://github.com/yassin312/TP_Docker_MERN/* et y accéder avec cd <TP_Docker_MERN>

# Lancement des conteneurs
Pour la création des conteneurs, il suffira de lancer la commande docker-compose up (-d) afin de build les différents conteneurs (Front, Back, BD et nginx)

# Accès application
Pour accéder à l'application, lancer un navigateur (/!\ tous les navigateurs n'ont pas les websockets nécessaire, l'application ne fonctionne donc pas sur tous les navigateurs) et rechercher dans l'url 
* *localhost* pour la partie frontend
* ou
* *localhost/api* pour la partie backend

(pas besoin de ports grâce à nginx)

# Screen

Frontend : 
![image](https://github.com/yassin312/TP_Docker_MERN/assets/78078665/faded651-de14-4018-b2c2-7781a64502a5)

Backend : 
![image](https://github.com/yassin312/TP_Docker_MERN/assets/78078665/b50eab08-a1e9-46b2-8756-5a8ee89ff664)
