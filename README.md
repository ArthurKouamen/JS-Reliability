# JS-Reliability
Ce dépôt regroupe l'implémentation de fonctionnalités JavaScript interactives et leur suite de tests automatisés. Nous utilisons Jest pour valider la logique des formulaires et Cypress pour simuler les interactions réelles des utilisateurs. Ce flux de travail vise à assurer la livraison d'un système stable et documenté pour le 20 mai 2026

🛡️ JS-Reliability : Implémentation & Automatisation de Tests JS
Ce projet a été réalisé dans le cadre du module de développement web. Il vise à démontrer l'intégration de fonctionnalités JavaScript interactives et la mise en place d'une stratégie de tests rigoureuse pour garantir la fiabilité du système (validation de formulaires et parcours utilisateurs).
🚀 Fonctionnalités implémentées
• Validation dynamique : Contrôle des saisies utilisateurs en temps réel sur les formulaires (Email, mot de passe, champs requis).
• Logique métier : Intégration des scripts de calcul et de traitement des données fournis.
• Interface interactive : Gestion des retours d'erreurs et des succès de soumission sans rechargement de page.
🛠️ Stack Technique
• Langage : JavaScript (ES6+)
• Tests Unitaires : Jest
• Tests E2E (End-to-End) : Cypress
📦 Installation et Configuration

1. Cloner le projet
   git clone https://github.com/votre-compte/votre-repo.git
cd votre-repo

2. Installer les dépendances
Assurez-vous d'avoir Node.js installé.
npm install

3. Lancer le projet
   Ouvrez simplement le fichier index.html dans votre navigateur ou utilisez une extension type "Live Server".

   🧪 Stratégie de Tests
1. Tests Unitaires (Jest)
Nous utilisons Jest pour valider la logique isolée de nos fonctions, notamment la validation des formulaires.
Lancer les tests : npm test
Fichiers concernés : tests/unit/*.test.js

2. Tests de bout en bout (Cypress)
Cypress nous permet de simuler le comportement d'un utilisateur réel sur l'application.

Ouvrir l'interface Cypress :npx cypress open
Lancer les tests en ligne de commande :npx cypress run

📂 Structure du Projet
├── assets/
│   ├── css/           # Feuilles de style
│   └── js/            # Scripts JavaScript (logique métier + validation)
├── cypress/
│   └── e2e/           # Tests End-to-End
├── tests/
│   └── unit/          # Tests unitaires Jest
├── index.html         # Page principale
├── package.json       # Dépendances et scripts
└── README.md          # Documentation du projet

Date de rendu : 20 Mai 2026
