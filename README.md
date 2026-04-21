# Duncan Gaurat - Portfolio Développeur d'applications
Développeur orienté conception logicielle et outils métiers, spécialisé en Python et en conception d'applications robustes, maintenables et structurées. 

---

## À propos

Issu d’un parcours en conception de produits industriels, j’ai développé une forte capacité d’analyse, de modélisation et de structuration des processus techniques.

Au fil de mon expérience, j’ai conçu et automatisé plusieurs outils internes afin d’optimiser des flux métiers. Cette appétence pour la logique, la conception et la résolution de problématiques complexes m’a naturellement orienté vers le développement logiciel.

Je me spécialise aujourd’hui en développement d’applications Python, avec une attention particulière portée à :
- l’architecture logicielle
- la qualité de code (PEP8, linting)
- la maintenabilité
- la structuration orientée objet
- l’automatisation de processus

Objectif : intégrer un poste de développeur logiciel junior afin de concevoir des applications utiles, robustes et évolutives.

---

## Compétences techniques

### Langages de programmation
- Python (avancé)
- JavaScript (bases)
- SQL (bases)
- VBA (bases)

### Outils & Frameworks
- Git
- VS Code / PyCharm
- Django
- PySide
- TinyDB
- Flake8
- W3C Validator
- SolidWorks avancé (CAO)
- CEGID PMI (ERP)
- Excel (avancé)

### Concepts
- Programmation Orientée Objet (POO)
- Séparation des responsabilités
- Conception de bases de données
- Manipulation d'API REST
- Automatisation de processus
- Logging et gestion d'erreurs

### Méthodes 
- Analyse fonctionnelle
- Développement agile
- Tests et validation
- Documentation technique

---

## Mes projets éducatifs


### Books_to_scrape

Repository : https://github.com/duncan-g-hub/P2_Books_to_scrape.git

Objectif : 
Développer un système automatisé de surveillance des prix capable d’extraire, transformer et structurer les données d’un site e-commerce.
Le projet repose sur la mise en place d’un pipeline complet d’extraction et de traitement de données.


Implémentation d’un pipeline de type ETL simplifié :
- Extract : récupération des pages et des données produits
- Transform : nettoyage et normalisation (stock, notation, noms de fichiers)
- Load : génération automatique de fichiers CSV et téléchargement des images
Les données sont organisées dynamiquement par catégorie dans une arborescence dédiée.

Compétences développées :
- Gestion des requêtes HTTP et gestion d'erreurs réseau
- Parsing HTML avec BeautifulSoup
- Nettoyage et normalisation de données
- Téléchargement et gestion de fichiers images
- Export structuré en CSV
- Gestion des chemins avec Pathlib
- Respect des conventions PEP8

Technologies utilisées : 
- Python 3
- Requests
- BeautifulSoup4
- CSV
- Pathlib
- re

Ce projet met en avant ma capacité à concevoir un outil automatisé robuste et structuré.

---


### Chess_Tournament

Repository : https://github.com/duncan-g-hub/P4_Chess_Tournament.git

Objectif :
Développer une application locale permettant la gestion complète d’un tournoi d’échecs sans connexion internet.

Architecture MVC (Model-View-Controller) clairement séparée :
- Models : entités métier (Player, Tournament, Match, Turn) et logique applicative
- Views : interface en ligne de commande
- Controllers : coordination et gestion des flux applicatifs
Persistance locale via fichiers JSON.

Compétences développées :
- Modélisation orientée objet
- Séparation des responsabilités
- Gestion de flux applicatif complexe
- Implémentation d’un système de génération automatique des matchs
- Validation du code avec flake8 et génération de rapports

Technologies utilisées : 
- Python 3
- Librairies standards : random, datetime, pathlib, json
- flake8
- flake8-html

Ce projet illustre ma capacité à concevoir une application métier structurée avec une architecture claire.

---


### Front-end_JustStreamIt

Repository : https://github.com/duncan-g-hub/P6_Front-end_JustStreamIt.git

Objectif : 
Développer une application web dynamique affichant en temps réel un classement de films à partir d’une API REST locale.

Architecture modulaire avec séparation des responsabilités :
- HTML : structure
- CSS : mise en forme responsive 
- JavaScript : appels API, logique métier et manipulation du DOM
Interaction dynamique avec l’API via fetch et gestion asynchrone des données.

Compétences développées :
- Utilisation d’API REST
- Manipulation dynamique du DOM
- Gestion d’événements utilisateur
- Structuration modulaire JavaScript
- Responsive design (mobile-first)

Technologies utilisées : 
- API OC-Movies-API : https://github.com/OpenClassrooms-Student-Center/OCMovies-API-EN-FR
- HTML5 
- CSS3 
- JavaScript (ES2021)
- W3C Validator (validation HTML/CSS)

Ce projet démontre ma compréhension des architectures web et des échanges client/serveur.

---


### LITRevu_web_app

Repository : https://github.com/duncan-g-hub/P9_LITRevu_web_app.git

Objectif : 
Développer une application web communautaire permettant la publication et la consultation de critiques de livres et d'articles.

Le projet repose sur une architecture MVT (Model-View-Template) divisée en deux applications Django distinctes :
- authentication : gestion de l'inscription, connexion et déconnexion
- review_app : logique métier autour des tickets, critiques et abonnements

Fonctionnalités principales :
- Système d'authentification complet (inscription, connexion, déconnexion)
- Publication, modification et suppression de tickets (demandes de critique) et de critiques
- Système de suivi d'utilisateurs avec un fil d'actualité personnalisé
- Accès au site conditionné à l'authentification

Compétences développées :
- Conception d'une application web avec le framework Django
- Modélisation de base de données et utilisation de l'ORM Django
- Gestion de l'authentification et des permissions
- Upload et gestion de fichiers médias avec Pillow
- Gestion des variables d'environnement pour la sécurisation des données sensibles
- Respect des conventions PEP8 avec flake8

Technologies utilisées :
- Python 3
- Django
- Pillow
- CSS3
- flake8


Ce projet illustre ma capacité à concevoir une application web full-stack structurée autour d'une architecture MVT et d'interactions utilisateurs complexes.

---


### SoftDesk_Support

Repository : https://github.com/duncan-g-hub/P10_SoftDesk_Support.git

Objectif :
Développer une API RESTful sécurisée permettant la remontée et le suivi de problèmes techniques liés à des projets logiciels, dans un contexte B2B.

Le projet repose sur une architecture REST divisée en deux applications Django distinctes :
- `accounts` : gestion des utilisateurs, authentification JWT, consentements RGPD
- `projects` : gestion des projets, contributeurs, issues et commentaires

Fonctionnalités principales :
- Authentification JWT (access/refresh token)
- Contrôle d'accès par rôle (auteur, contributeur)
- Gestion des projets avec suivi des issues (priorité, statut, balise)
- Commentaires identifiés par UUID
- Validation de l'âge minimum (15 ans) à l'inscription
- Suppression des données personnelles conformément au RGPD
- Pagination des résultats

Compétences développées :
- Conception d'une API REST avec Django REST Framework
- Authentification et sécurisation avec Simple JWT
- Gestion de permissions personnalisées par rôle
- Routage imbriqué avec drf-nested-routers
- Modélisation de base de données relationnelle
- Application des principes RGPD (droit à l'oubli)
- Respect des conventions PEP8 avec flake8

Technologies utilisées :
- Python 3
- Django / Django REST Framework
- Simple JWT
- drf-nested-routers
- python-decouple
- flake8

Ce projet illustre ma capacité à concevoir une API RESTful sécurisée, structurée et conforme aux bonnes pratiques de gestion des données personnelles.

---


## Mes projets personnels


### ToDoList_App

Repository : https://github.com/duncan-g-hub/ToDoList_App.git

Objectif : 
Concevoir une application desktop autonome de gestion de tâches avec persistance locale.
Projet orienté développement logiciel, avec séparation entre interface graphique et logique métier.

Architecture séparée en deux couches principales :
- Interface graphique (PySide6) : gestion des interactions utilisateur
- Logique métier et persistance : gestion des tâches et stockage local
Stockage des données en JSON via TinyDB.

Compétences développées :
- Développement d’interface graphique avec PySide6
- Gestion d’événements UI
- Séparation logique / interface
- Persistance locale de données
- Structuration modulaire de l’application

Technologies utilisées : 
- Python 3
- Librairies standards : datetime, pathlib, json, logging
- tinydb
- PySide6

Ce projet reflète clairement mon orientation vers le développement d’applications logicielles complètes en Python.

---

### Website portfolio (à venir)
Développement d’un site vitrine personnel présentant mes projets, compétences et parcours de manière interactive.

---

## Ce que mes projets démontrent globalement
- Capacité à concevoir une architecture logicielle claire
- Structuration orientée objet
- Respect des bonnes pratiques Python
- Création d’outils métiers autonomes
- Manipulation de données
- Développement d’interfaces (CLI, GUI, Web)

---

## Contact

Duncan GAURAT 

duncan.dev@outlook.fr
📍 Franche-Comté, France
