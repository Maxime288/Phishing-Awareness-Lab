# 🛡️ Phishing Awareness Lab : Simulations de Pages de Connexion

![Security
Badge](https://img.shields.io/badge/Security-Educational-red)\
![Status](https://img.shields.io/badge/Status-In_Development-yellow)

## 📖 Description

Ce dépôt est une bibliothèque de **Preuves de Concept (PoC)**
reproduisant les interfaces de connexion de services populaires (Google,
Facebook, Microsoft, etc.).

**L'objectif est pédagogique :** démontrer la facilité avec laquelle une
interface peut être clonée pour sensibiliser les utilisateurs aux
dangers de l'ingénierie sociale et du vol d'identifiants.

------------------------------------------------------------------------

## ⚠️ AVERTISSEMENT LÉGAL

> **Usage strictement préventif et éducatif.**\
> Ce code est mis à disposition pour aider les professionnels de la
> cybersécurité et les formateurs.\
> Toute utilisation à des fins malveillantes, de vol de données ou sur
> des cibles sans leur consentement est illégale et punie par la loi.\
> L'auteur décline toute responsabilité.

------------------------------------------------------------------------

## 🏗️ Contenu du Laboratoire

Chaques fichiers contient une reproduction fidèle (HTML/CSS) et un script
de démonstration :

-   **`/Google-Login`** : Simulation de la mire de connexion Google
-   **`/Facebook-Login`** : Simulation de la page de connexion Facebook
-   **`/Microsoft-365-Login`** : Simulation de la page de connexion Microsoft-365
-   **`/Netflix-Login`** : Simulation de la page de connexion Netflix
-   **`/PayPal-Login`** : Simulation de la page de connexion PayPal

------------------------------------------------------------------------

## 🔍 Comment ce projet aide à la prévention ?

Chaque simulation intègre un mode **"Analyse"** (accessible via
`script.js`) qui intercepte la soumission du formulaire pour afficher un
message d'alerte pédagogique au lieu d'envoyer les données à un serveur.

### Points de vigilance illustrés :

1.  **L'URL trompeuse :** Apprendre à lire la barre d'adresse\
2.  **Le Favicon :** Vérifier si l'icône de l'onglet est présente et
    correcte\
3.  **Les Liens Morts :** Souvent, sur une page de phishing, seuls les
    champs "Email" et "Password" fonctionnent ; les liens "Aide" ou
    "Conditions d'utilisation" sont inactifs

------------------------------------------------------------------------

## 🛡️ Mesures de Protection Recommandées

-   **Activer l'A2F (Authentification à deux facteurs)**\
-   **Gestionnaires de mots de passe**\
-   **Vérification HTTPS**

------------------------------------------------------------------------

## 🧠 Objectif global

Former, sensibiliser et réduire les risques liés au phishing grâce à une
approche concrète et visuelle.

------------------------------------------------------------------------

*Projet maintenu dans un but de sécurité collective.*
