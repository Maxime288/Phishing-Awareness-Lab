# 🛡️ Phishing Awareness Lab : Simulations de Pages de Connexion

![Security
Badge](https://img.shields.io/badge/Security-Educational-red) 
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

Chaques fichiers contient une reproduction fidèle (HTML/CSS) et une photo ou vidéo
de démonstration :

-   **`/Google-Login`** : Simulation de la page de connexion Google
-   **`/Google-Login-2FA`** : Simulation de la page de connexion Google 2FA
-   **`/Alerte-Google`** : Simulation d'un mail d'une alerte Google
-   **`/Nouvelle-Connexion-Google`** : Simulation d'un mail d'une nouvelle connexion Google
-   **`/Facebook-Login`** : Simulation de la page de connexion Facebook
-   **`/Microsoft-365-Login`** : Simulation de la page de connexion Microsoft-365
-   **`/Netflix-Login`** : Simulation de la page de connexion Netflix
-   **`/PayPal-Login`** : Simulation de la page de connexion PayPal
-   **`/Amazon-login`** : Simulation de la page de connexion Amazon
-   **`/Caisse-Epargne-login`** : Simulation de la page de connexion Caisse d'épargne
-   **`/Instagram-login`** : Simulation de la page de connexion Instagram
-   **`/Linkedin-login`** : Simulation de la page de connexion Linkedin


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

## 🎓 Compétences démontrées

Ce projet met en œuvre plusieurs compétences techniques et méthodologiques :

- **Analyse d'interfaces web** : étude des éléments visuels et ergonomiques des plateformes populaires.
- **Reproduction fidèle d'interfaces utilisateurs** : conception de simulations réalistes à des fins pédagogiques.
- **Développement Web (HTML, CSS, JavaScript)** : création d'interfaces interactives et gestion des événements côté client.
- **Sensibilisation à l'ingénierie sociale** : compréhension des mécanismes psychologiques exploités lors des attaques de phishing.
- **Compréhension des vecteurs d'attaque liés au phishing** : identification des techniques utilisées pour tromper les utilisateurs et des moyens de s'en protéger.
- **Conception de supports pédagogiques en cybersécurité** : création d'un environnement de démonstration destiné à la formation et à la prévention.

------------------------------------------------------------------------
## 🛡️ Mesures de Protection Recommandées

-   **Activer l'A2F (Authentification à deux facteurs)**\
-   **Gestionnaires de mots de passe**\
-   **Vérification du domaine et du certificat HTTPS**

------------------------------------------------------------------------

## 🧠 Objectif global

Former, sensibiliser et réduire les risques liés au phishing grâce à une
approche concrète et visuelle.

------------------------------------------------------------------------

*Projet maintenu dans un but de sécurité collective.*
