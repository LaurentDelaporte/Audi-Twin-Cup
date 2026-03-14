# 🏁 Audi Twin Cup - Ultimate Training Simulator

Ce projet est un simulateur d'entraînement interactif (Quiz) dédié à la préparation technique et culturelle pour l'**Audi Twin Cup 2026**. Il permet aux participants de tester leurs connaissances sur la Formule 1, les technologies Audi et les concepts futuristes de la marque.



## 📋 Table des matières
1. [Fonctionnalités](#-fonctionnalités)
2. [Structure du projet](#-structure-du-projet)
3. [Utilisation](#-utilisation)
4. [Ajout de questions](#-ajout-de-questions)
5. [Technos utilisées](#-technos-utilisées)

---

## ✨ Fonctionnalités
* **Mode Session :** 30 questions aléatoires par partie pour une préparation intensive.
* **Chronomètre :** 30 secondes par question pour s'entraîner à la prise de décision rapide.
* **Feedback instantané :** Correction immédiate avec une explication détaillée (rationale) pour chaque question.
* **Barre de progression :** Visualisation en temps réel de l'avancement.
* **Design immersif :** Interface sombre (Dark Mode) aux codes couleurs d'Audi Sport.

---

## 🏗 Structure du projet
Le projet est un fichier unique (`index.html`) facilitant le déploiement. Il regroupe :
* **HTML5 :** Structure sémantique de l'interface.
* **CSS3 :** Mise en page flexible (Flexbox/Grid) et responsive.
* **JavaScript :** Gestion de l'état du quiz, mélange des questions, gestion du temps et calcul des scores.

---

## 🚀 Utilisation
Aucune installation n'est requise.
1. Téléchargez le fichier `index.html`.
2. Ouvrez-le simplement dans votre navigateur web préféré.
3. Cliquez sur "Nouvelle session" pour lancer l'entraînement.

---

## ✏ Ajout de questions
La base de données est située dans la constante `questionsData`. Pour enrichir le quiz, ajoutez un objet dans le tableau en suivant ce format :

```javascript
{ 
  cat: "Catégorie", 
  q: "Votre question ?", 
  o: ["Option A", "Option B", "Option C", "Option D"], 
  a: "La bonne réponse", 
  r: "Une explication courte et précise." 
}
