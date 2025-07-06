# Application de Gestion de Produits Spring Boot

Une application web complète construite avec Spring Boot pour la gestion de produits, incluant une authentification sécurisée, des opérations CRUD et une interface web moderne.

## 🚀 Fonctionnalités

- **Gestion de Produits** : Créer, lire, mettre à jour et supprimer des produits
- **Authentification Utilisateur** : Système de connexion sécurisé avec accès basé sur les rôles
- **Design Responsive** : Interface utilisateur basée sur Tailwind qui fonctionne sur tous les appareils
- **Sécurité** : Intégration Spring Security avec rôles utilisateur

## 🛠️ Technologies Utilisées

- **Spring Boot** : Framework d'application
- **Spring Data JPA** : Persistance des données
- **Hibernate** : Implémentation ORM
- **Spring Security** : Authentification et autorisation
- **Base de données H2** : Base de données en mémoire pour le développement
- **Tailwind** : Framework frontend

## 🔐 Configuration de Sécurité

L'application inclut Spring Security avec les fonctionnalités suivantes :

- **Authentification Utilisateur** : Fonctionnalité de connexion/déconnexion
- **Accès Basé sur les Rôles** : Différents niveaux d'accès pour les administrateurs et utilisateurs réguliers
- **Encodage de Mot de Passe** : Hachage de mot de passe BCrypt

### Utilisateurs par Défaut

- **Utilisateur Administrateur** :
  - Nom d'utilisateur : `admin`
  - Mot de passe : `azerty123a`
  - Rôle : `ADMIN`

- **Utilisateur Régulier** :
  - Nom d'utilisateur : `user`
  - Mot de passe : `azerty123`
  - Rôle : `USER`

### Captures d'écran

- Image de l'interface de connexion : `images/login.png`
- Images de l'interface administrateur : `images/admin-1.png`, `images/admin-2.png`
- Images de l'interface utilisateur : `images/user-1.png`