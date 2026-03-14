# 🏎️ Audi Twin Cup - Master Trainer

Ce projet est un simulateur de quiz interactif conçu pour la préparation intensive des techniciens et conseillers techniques au concours **Audi Twin Cup**. Il est optimisé pour tester les connaissances sur les architectures complexes, les systèmes de propulsion électrique (PPE, e-tron), les technologies thermiques (TFSI, TDI) et les systèmes d'aide à la conduite.

## 🚀 Fonctionnalités
* **Base de données robuste :** Supporte jusqu'à 250 questions au format JSON.
* **Logique d'apprentissage :** Système de "Rationale" (justification technique) pour chaque question, favorisant la compréhension plutôt que le par cœur.
* **Design immersif :** Interface sobre aux couleurs de la charte graphique Audi (Noir, Rouge, Gris).
* **Support technique :** Intégration de balises de schémas techniques pour visualiser les systèmes complexes.
* **Responsive :** Fonctionne directement dans n'importe quel navigateur sans installation.

## 🛠️ Installation & Utilisation
1. Télécharge ou clone ce dépôt sur ta machine.
2. Ouvre le fichier `quiz.html` dans ton navigateur (Chrome, Firefox ou Edge recommandés).
3. C'est tout ! Aucune dépendance externe n'est requise.

## 🧠 Organisation des questions
Le quiz couvre trois niveaux de complexité :
* **Niveau Standard :** Histoire de la marque et bases mécaniques.
* **Niveau Expert :** Systèmes de transmission (Quattro), gestion boîte S tronic, aides à la conduite.
* **Niveau Expert/Hard :** Architecture 800V, gestion thermique intégrée de la plateforme PPE, onduleurs, et protocoles E³.

## 📊 Références Techniques Clés
Le simulateur facilite l'accès aux concepts critiques via les systèmes suivants :
* 
* 
* 
* 

## 📝 Contribuer au contenu
Pour ajouter ou modifier des questions, édite simplement le tableau `const questions` dans le fichier `quiz.html` en respectant ce format JSON :

```json
{
  "q": "Ta question ici ?",
  "o": ["Option A", "Option B", "Option C", "Option D"],
  "a": "La bonne réponse",
  "r": "Explication technique détaillée."
}
