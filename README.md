# Gestion des Plantes/Parcelles

Description detailée du projet

Le projet ambitionne de créer une solution de gestion agricole visant à simplifier les tâches de suivi et de gestion des exploitations agricoles. Centrée sur la gestion approfondie des parcelles, des cultures et des variétés de plantes, cette application s'engage à fournir une interface conviviale et accessible, facilitant ainsi l'optimisation de l'efficacité des pratiques agricoles pour tout utilisateur souhaitant utiliser l'application.


# Fonctionnalités

Gestion des Fermes

 - Cruds: Ajout, modification et suppression de fermes.
 - Voir au niveau de la liste les details de chaque ferme.

Gestion des Parcelles

 - Cruds: Ajout, modification et suppression de fermes.
 - Notation de la superficie de chaque parcelle.

Gestion du Plantage

 - Ajout, modification et suppression de plantes.
 - Chronologie des plantations (avec la date de chaque plantation) .

Gestion des types de plantes

 - Ajout, modification et suppression des types de plantes.
 - Attribution de types de plantes à des plantations.



# Technologies Utilisées

# Langages de Programmation

- Java: Utilisé pour le développement de l'application backend. Java est un langage orienté objet robuste et largement utilisé dans le développement d'applications d'entreprise.

- HTML, CSS: Utilisés pour le développement de l'interface utilisateur frontend. HTML définit la structure de la page web, CSS stylise la présentation.

# Frameworks et Bibliothèques

 - Java EE (Enterprise Edition) :** Plateforme utilisée pour le développement d'applications d'entreprise Java. Elle fournit des spécifications pour les services tels que la gestion des transactions, la sécurité, et la persistance des données.

 - JavaServer Faces (JSF) : Framework Java pour la construction d'interfaces utilisateur. Il simplifie le développement des composants d'interface utilisateur réutilisables.

 - EJB (Enterprise JavaBeans) : Utilisé pour la programmation côté serveur. EJB fournit un modèle de composants pour la création d'applications d'entreprise distribuées.

 - PrimeFaces : Bibliothèque de composants JSF pour une interface utilisateur riche. PrimeFaces simplifie la création d'interfaces utilisateur avancées avec des composants prêts à l'emploi.

# Base de Données

 - MySQL: Système de gestion de base de données relationnelle utilisé pour stocker les données de l'application. MySQL est un choix populaire pour sa fiabilité et ses performances.

# Serveur d'Application : 

 - GlassFish :Serveur d'application Java EE utilisé pour déployer et exécuter l'application. GlassFish offre un support complet pour les spécifications Java EE.


# Installation de Docker :
Installer Docker Desktop depuis de site officiel : 

https://docs.docker.com/desktop/install/windows-install/

# Utilisation:

La version Docker de notre application permet une installation rapide et sans souci. Suivez ces étapes simples pour exécuter l'application dans un conteneur Docker :

 1) Clonez ce lien Github: 
[// lien github//](https://github.com/Samia-Kouame/projet-Gestion-des-fermes)

 2) Pour construire l'image Docker , runner cette commande :
docker build -t gestion_ferme:tag .

Cette commande utilise le fichier Dockerfile pour créer une image Docker qui inclut toutes les dépendances nécessaires pour exécuter votre application.

 3)Executez le conteneur Docker:
docker run -p 8082:8080 gestion_ferme:tag

 4)Accédez à l'application :
Ouvrir le navigateur web et tappez : http://localhost:8080 pour afficher l'application.




# Docker Desktop:
![5add033e-c849-4c3a-b26a-874ed4d143c5](https://github.com/Samia-Kouame/projet-Gestion-des-fermes/assets/147660832/a9abbee3-d880-4a7a-9c64-a846949fa460)






https://github.com/Samia-Kouame/projet-Gestion-des-fermes/assets/147660832/8ccbac5d-580f-4143-ab23-6f523b2b2db1

