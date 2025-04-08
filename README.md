# competence-ms
# 🧩 Architecture de Microservices avec Spring Boot, Eureka et API Gateway

Ce projet est une démonstration d’une architecture microservices basée sur **Spring Boot**, **Spring Cloud Eureka** (pour la découverte de services) et **Spring Cloud Gateway** (pour le routage). Il est conçu pour être modulaire, évolutif et facile à maintenir. Il comprend les trois microservices suivants :

- 🎯 **Eureka** : Serveur de découverte des services.
- 🚪 **API Gateway** : Point d’entrée unique pour toutes les requêtes, agissant comme un routeur intelligent.
- 🧠 **Competence** : Service métier exemple de gestion des compétences, connecté à une base de données MySQL.

---

## 🔧 Technologies utilisées

- Java 17  
- Spring Boot 3.4.x  
- Spring Cloud 2024.0.x  
- Spring Cloud Gateway  
- Eureka Server & Eureka Client  
- MySQL  
- Maven  

---

## 📁 Organisation du projet

```plaintext
.
├── Eureka/               --> Serveur de découverte
├── API_GATEWAY/          --> Passerelle d’API (Gateway)
└── competence/           --> Service microservice (gestion des compétences)
 Lancement du projet
Démarrer le serveur Eureka (port 8761) : ./mvnw spring-boot:run (dans le dossier Eureka)
Démarrer le service API Gateway (port 8093) : ./mvnw spring-boot:run (dans le dossier API_GATEWAY)
Démarrer le microservice Competence (port 8084) : ./mvnw spring-boot:run (dans le dossier competence)
Exemple de fonctionnement: http://localhost:8093/competences
 Fonctionnalités couvertes
 Découverte de services avec Eureka

Routage dynamique via API Gateway

 Connexion avec une base de données MySQL

 Architecture évolutive en microservices 

