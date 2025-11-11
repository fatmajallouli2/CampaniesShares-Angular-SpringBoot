# Notes: L'application n'est pas encore terminée et doit être améliorée

# Description du projet: 

Portfolio’s Shares est une application web intelligente qui aide les investisseurs à suivre et prédire la fluctuation du cours des actions d’entreprises.
Elle combine une analyse sémantique et web scraping pour extraire des informations financières à partir de sites spécialisés et de réseaux sociaux.
Grâce à un modèle sémantique de prédiction, elle calcule un score de confiance basé sur la fréquence des mots-clés financiers et des indicateurs économiques (TMM, taux d’inflation, cours des devises, etc.), afin d’aider l’utilisateur à prendre des décisions d’achat ou de vente d’actions.

# Objectifs

* Offrir un outil moderne pour le suivi du portefeuille d’actions.

* Exploiter les informations disponibles sur le web pour enrichir les prévisions.

* Fournir un tableau de bord interactif pour visualiser les tendances et rapports.

* Intégrer un système d’authentification sécurisée et une gestion des utilisateurs (admin, membre).

# Architecture

L’application est basée sur une architecture 3-tiers :

Frontend : Angular (interfaces utilisateur, MVC côté client)

Backend : Spring Boot (API REST, logique métier)

Base de données : MySQL

IA & Web Scraping : Python (analyse sémantique, calcul du score)

# Technologies utilisées

Frontend:	Angular, HTML5, CSS3, Bootstrap
Backend:	Java, Spring Boot, Tomcat
Base de données: MySQL
Intelligence Artificielle & Scraping:	Python, BeautifulSoup, NLTK, NumPy
Outils de développement: Visual Studio Code, Eclipse, Postman, Overleaf, WhiteStarUML

# Fonctionnalités principales

* Authentification et gestion des utilisateurs (Admin / Membre)

* Web scraping d’actualités et de données boursières

* Calcul automatique d’un score de prédiction basé sur des facteurs financiers

* Visualisation des rapports via Power BI

* Suggestion et validation de nouvelles sources web par les utilisateurs
