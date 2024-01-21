Projet de Microservices : Générateur et Lecteur de Codes QR
Aperçu

Ce projet est une application basée sur des microservices développés avec Spring Boot pour le backend, React JS pour le frontend, et diverses technologies pour les fonctionnalités de support. Il inclut des services de génération et de lecture de codes QR, utilise Spring Cloud Consul pour la découverte de services, est conteneurisé avec Docker, et intègre une intégration et un déploiement continus avec Jenkins. La qualité du code est maintenue et analysée avec SonarQube et SonarCloud. La documentation des API est disponible via Swagger.
Technologies Utilisées

    Backend :
        # Spring Boot
        # Spring Cloud Consul pour la découverte de services
        # Spring Cloud OpenFeign pour la communication entre microservices
        # Swagger pour la documentation des API
        # SonarQube et SonarCloud pour l'analyse de la qualité du code
        # Jenkins pour l'intégration et le déploiement continus

    Frontend :
        # React JS

    Conteneurisation :
        # Docker

Microservices

    Service de Génération de Codes QR :
        Génère des codes QR en fonction des informations fournies.
        Utilise Spring Cloud Consul pour la découverte de services.
        Expose des points de terminaison REST pour la génération de codes QR.

    Service de Lecture de Codes QR :
        Lit les informations encodées dans les codes QR.
        Utilise Spring Cloud Consul pour la découverte de services.
        Expose des points de terminaison REST pour la lecture de codes QR.

Frontend

    Formulaire de Génération de Codes QR :
        Développé avec React JS.
        Fournit une interface utilisateur pour saisir des informations et générer des codes QR.
        Communique avec le Service de Génération de Codes QR.

    Lecteur de Codes QR :
        Permet aux utilisateurs de télécharger des images de codes QR pour les décoder.
        Communique avec le Service de Lecture de Codes QR.

Découverte de Services

    Spring Cloud Consul :
        Utilisé pour la découverte et l'enregistrement de services.

Conteneurisation

    Docker :
        L'ensemble de l'application est conteneurisé pour un déploiement facile.

Intégration et Déploiement Continus

    Jenkins :
        Automatise les processus de build et de déploiement.
        S'intègre avec Docker pour la conteneurisation.

Analyse de la Qualité du Code

    SonarQube et SonarCloud :
        Assure la qualité du code et identifie les problèmes.
        Intégré dans le flux de travail de développement pour une amélioration continue.

Documentation des API

    Swagger :
        Fournit une documentation complète des API pour une intégration et une utilisation faciles.

Structure du Projet

    backend/ : Contient les microservices Spring Boot et les configurations associées.
    frontend/ : Contient l'application React JS pour les interfaces utilisateur.
    docker/ : Inclut les fichiers Docker et les configurations pour la conteneurisation.
    jenkins/ : Contient les scripts de pipeline Jenkins et les configurations.

Mise en Route

    Cloner le Dépôt :

    bash

    git clone (https://github.com/SAYOUT-Ahmed/JenkinsMicroService/new/main)

    Build et Exécution des Services :
        Suivre les instructions dans le README de chaque microservice pour les construire et les exécuter.

    Build et Exécution du Frontend :
        Se rendre dans le répertoire frontend/ et suivre le README pour configurer l'application React JS.

    Déploiement avec Docker :
        Utiliser les fichiers Docker et les configurations dans le répertoire docker/ pour déployer l'application avec Docker.

    Intégration Jenkins :
        Configurer Jenkins avec les scripts de pipeline fournis dans le répertoire jenkins/.

    Analyse de la Qualité du Code :
        Intégrer votre projet avec SonarQube ou SonarCloud pour une analyse continue de la qualité du code.

    Documentation Swagger :
        Accéder à la documentation Swagger pour des informations détaillées sur les API.

Contribution

N'hésitez pas à contribuer en ouvrant des issues, en fournissant des retours ou en soumettant des pull requests. Vos contributions sont les bienvenues et appréciées !

Bon codage !
