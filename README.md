
---

# 🌗Lab 9 – Hooks React Native thème clair / sombre avec *useColorScheme* (React Native)

## 🧾 Présentation du TP

Ce travail pratique vise à développer un écran d’accueil React Native capable de s’adapter **automatiquement au thème du système** (clair ou sombre) grâce au hook `useColorScheme`.
L’interface met à jour ses couleurs en temps réel lors du changement de thème, sans dépendance externe ni connexion Internet.

---

## 🎯 Compétences visées

* Utiliser le hook `useColorScheme`.
* Mettre en place un système de thème simple.
* Gérer dynamiquement les styles selon le mode clair / sombre.
* Tester la compatibilité Android & iOS.

---

## 🗺️ Déroulement du TP

* Création d’un projet React Native avec Expo.
* Ajout d’un écran `WelcomeScreen` générique.
* Importation du hook `useColorScheme`.
* Définition d’une palette de couleurs pour les deux thèmes.
* Application de styles conditionnels.
* Ajout d’un bandeau d’accent et d’un en-tête.
* Test de la bascule du thème sur émulateurs.
* Vérification du contraste et de la lisibilité.
* Ajout d’un affichage de debug (optionnel).

---

## 📚 Concepts essentiels

| Terme                | Description                                                     |
| -------------------- | --------------------------------------------------------------- |
| Hook                 | Fonction React permettant d’accéder à l’état et au cycle de vie |
| useColorScheme       | Permet de lire le thème système (light / dark)                  |
| Styles conditionnels | Combinaison de styles fixes et dynamiques                       |
| Contraste            | Lisibilité entre le texte et le fond                            |

---

## 🎨 Charte graphique

| Mode   | Fond      | Texte     |
| ------ | --------- | --------- |
| Clair  | `#EDEFEE` | `#333333` |
| Sombre | `#333333` | `#EDEFEE` |
| Accent | `#EE9972` | —         |

---

## 🏗️ Objectif technique

Créer un écran `WelcomeScreen` capable de :

* Détecter automatiquement le thème du système.
* Adapter ses couleurs en temps réel.
* Utiliser un logo local fonctionnant hors-ligne.


---

## ▶️ Exécution

<img width="643" height="477" alt="image" src="https://github.com/user-attachments/assets/4cafbb5e-7494-4760-889f-72beba830937" />

<img width="959" height="474" alt="Lab9 3" src="https://github.com/user-attachments/assets/0a0fde4f-4c18-4942-8cca-9dc4a4bf98cd" />

---

## 🌞 Mode clair

<img width="959" height="468" alt="Lab9 Light" src="https://github.com/user-attachments/assets/bcb2862d-8292-487b-9844-8944eb39737a" />

---

## 🌙 Mode sombre

<img width="959" height="470" alt="Lab9 Dark" src="https://github.com/user-attachments/assets/df28aa3a-c444-433c-8638-9a15d050fbc3" />

---

## 👩‍💻 Réalisation

* **Étudiante :** HASSAOUI Aya
* **Encadrant :** Pr. Mohamed Lachgar

---


