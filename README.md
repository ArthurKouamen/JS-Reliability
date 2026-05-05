# 🛡️ JS-Reliability

Implémentation & Automatisation de Tests JavaScript

Ce dépôt regroupe l'implémentation de fonctionnalités JavaScript interactives et leur suite de tests automatisés. Nous utilisons Jest pour valider la logique des formulaires et Cypress pour simuler le comportement réel des utilisateurs.

---

## 📋 Description du Projet

Ce projet a été réalisé dans le cadre du module de développement web. Il vise à démontrer l'intégration de fonctionnalités JavaScript interactives et la mise en place d'une stratégie de test robuste.

---

## 🚀 Fonctionnalités implémentées

- **Validation dynamique** : Contrôle des saisies utilisateurs en temps réel sur les formulaires (Email, mot de passe, champs requis)
- **Logique métier** : Intégration des scripts de calcul et de traitement des données
- **Interface interactive** : Gestion des retours d'erreurs et des succès de soumission sans rechargement de page

---

## 🛠️ Stack Technique

- **Langage** : JavaScript (ES6+)
- **Tests Unitaires** : Jest
- **Tests E2E** : Cypress

---

## 📦 Installation et Configuration

### 1. Cloner le projet

```bash
git clone https://github.com/ArthurKouamen/JS-Reliability.git
cd JS-Reliability
```

### 2. Installer les dépendances

Assurez-vous d'avoir Node.js installé.

```bash
npm install
```

### 3. Lancer le projet

Ouvrez simplement le fichier `index.html` dans votre navigateur ou utilisez une extension type "Live Server".

---

## 🧪 Stratégie de Tests

### Tests Unitaires (Jest)

Nous utilisons Jest pour valider la logique isolée de nos fonctions, notamment la validation des formulaires.

```bash
# Lancer les tests
npm test
```

**Fichiers concernés** : `tests/unit/*.test.js`

### Tests de bout en bout (Cypress)

Cypress nous permet de simuler le comportement d'un utilisateur réel sur l'application.

```bash
# Ouvrir l'interface Cypress
npx cypress open

# Lancer les tests en ligne de commande
npx cypress run
```

---

## 📂 Structure du Projet

```
├── assets/
│   ├── css/                # Feuilles de style
│   └── js/                 # Scripts JavaScript (logique métier + validation)
├── cypress/
│   └── e2e/                # Tests End-to-End
├── tests/
│   └── unit/               # Tests unitaires Jest
├── index.html              # Page principale
├── package.json            # Dépendances et scripts
└── README.md               # Documentation du projet
```

---

## 📅 Date de rendu

**20 Mai 2026**
