### 📜 Projet : Chat de Réseau Social (Client/Serveur)

#### Participants
- **Nganga**
- **Ronaldo**
- **Adam**

#### Objectif
Le projet consiste à réaliser une application **client/serveur** de type **chat de réseau social**. L'application utilise des fonctions communicantes et conçoit un protocole applicatif au-dessus de la pile de communication **TCP/IP**.

- **Langage de programmation** : Java
- **IDE** : NetBeans
- **Protocole utilisé** : TCP, choisi pour sa fiabilité et sa capacité à assurer un transfert de données robuste et sécurisé entre les appareils distants.

#### Description de l'application

Cette application de réseau social permet aux utilisateurs de :
- Se connecter
- Échanger des messages en temps réel

Les messages suivent le format suivant :

Le serveur indique la réponse avec "serveur". L'authentification se fait par login et mot de passe, assurant la sécurité des utilisateurs. L'application prend en charge la gestion des messages pour les utilisateurs **hors ligne** et gère la communication en temps réel avec une architecture **client-serveur**.

#### Fonctionnalités principales

1. **Interface Utilisateur** : Interface graphique permettant une interaction facile avec les utilisateurs.
2. **Authentification sécurisée** : Authentification via login et mot de passe.
3. **Messagerie instantanée** : Permet d'échanger des messages en temps réel.
4. **Gestion des amis** : Ajouter, supprimer ou gérer les amis dans l'application.
5. **Stockage des Messages** : Enregistrement des messages pour les utilisateurs qui ne sont pas connectés.

#### Approche des Sockets pendant le projet

La gestion des **sockets** a été un élément fondamental du développement de l'application. 

**Phase de Recherche** :
- Étude des concepts clés des **sockets**, y compris les différences entre les types de sockets et les protocoles de communication comme **TCP** et **UDP**.
- Compréhension des défis et des avantages liés à chaque approche.

**Implémentation Pratique** :
- Création d'un système de **sockets** efficace et robuste.
- Exploration de la communication **synchrone** et **asynchrone** pour répondre aux exigences du projet.

**Défis surmontés** :
- Gestion des délais et des exceptions.
- Amélioration de la **scalabilité** pour gérer un nombre plus élevé d'utilisateurs.
- Résolution des problèmes liés à la **stabilité** et à la **performance** du système.

#### Qu'est-ce que sont les Sockets ?
Les **sockets** sont un mécanisme permettant la communication entre différentes machines via un réseau. Ils permettent à un programme d'envoyer et de recevoir des données par l'intermédiaire de la pile de communication **TCP/IP**, ce qui est essentiel pour la mise en œuvre de notre application de chat de réseau social.

