# Parcours Tech 🚀

Un tableau de bord gamifié pour le suivi de ton apprentissage technique au quotidien. 

## 📖 À propos du projet
**Parcours Tech** est une application web (Single-Page Application) conçue pour t'aider à structurer ton apprentissage technique dans divers domaines complexes (DevOps, Machine Learning, Web Performance & Sécurité). 
L'application propose une progression étape par étape avec des leçons courtes, des exercices pratiques concrets, et valide les acquis via des quiz pour débloquer les modules suivants et gagner de l'expérience (XP).

## ✨ Fonctionnalités
- **Curriculum Structuré :** Des modules d'apprentissage organisés par "Tracks" (pistes d'apprentissage).
- **Gamification :** 
  - Gains de XP pour chaque module complété.
  - Système de badges pour valider visuellement les acquis.
  - Suivi des jours consécutifs (*Streaks*) pour encourager la régularité.
- **Quiz Interactifs :** Chaque module nécessite de réussir un petit quiz (minimum 2/3) pour avancer.
- **Rappels Quotidiens :** 
  - Notifications système intégrées au navigateur.
  - Bouton pour générer directement une récurrence dans Google Calendar.
- **Sauvegarde de Progression :** La progression est automatiquement persistée.

## 🛠️ Stack Technique
L'application est construite de manière très légère sans aucun framework lourd :
- **HTML5 :** Structure sémantique.
- **CSS3 :** Variables CSS pour le thème (nuances de rouge, interface épurée), flexbox, animations fluides.
- **JavaScript (Vanilla ES6+) :** Logique de l'application, gestion de l'état, manipulation du DOM dynamique et validation des quiz.

## 📂 Structure actuelle
Pour le moment, l'ensemble de l'application est condensé de manière autonome dans un fichier unique `parcours-tech.html` contenant :
- Le balisage HTML.
- Les styles CSS.
- Les données textuelles d'apprentissage (le fameux objet `CURRICULUM`).
- La logique métier et l'interface utilisateur en JavaScript.

## 🚀 Comment l'utiliser
1. Ouvre le fichier `parcours-tech.html` dans un navigateur web (Google Chrome, Firefox, Safari, etc.) — *Attention : certaines API de stockage ou notifications peuvent nécessiter un environnement spécifique ou un serveur local*.
2. Sur le tableau de bord, découvre ta **mission du jour**.
3. Ouvre le module déverrouillé, lis la leçon, et exécute les exercices.
4. Passe le quiz pour valider le module et débloquer le prochain badge !
