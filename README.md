# SAE4-Refactor
Projet universitaire dans le but de Refactor / Améliorer un code fourni de base, pour le rendre insensible aux attaques, améliorer la hiérarchie de code, l'esthétisme et l'ergonomie générale du site internet.


# 📦 SAE 4.01 – Amélioration du site (Groupe 10)

## 👥 Membres du groupe
- Mathéo BESNARD  
- Ewen PICHOFF  
- Mathis LE NÔTRE  
- Baptiste DELHAYE  

## 📅 Mars 2025

## 📝 Objectif du projet
Ce projet a été réalisé dans le cadre de la SAE 4.01. L’objectif était d’améliorer un site web existant à travers des corrections de bugs, des optimisations ergonomiques et des ajouts fonctionnels, tout en respectant les bonnes pratiques de sécurité.

---

## 🔧 Fonctionnalités ajoutées / améliorées

- 🔐 **Connexion** : correction du problème des tentatives de connexion négatives.
- 🔓 **Déconnexion** et 🔑 **Création de compte** : refonte des méthodes.
- 📦 **Gestion des stocks** : les produits ne sont plus supprimés à stock nul, mais affichés comme en rupture.
- 🛒 **Gestion des produits** : support des valeurs décimales + refonte ergonomique.
- ⚠️ **Sécurité** :
  - Double confirmation à la suppression.
  - Protection contre les injections SQL & XSS (ex : messagerie, modification).
- 👤 **Ajout photo de profil** : nouvelle interface plus claire (fonctionne uniquement en local).
- 📬 **Messagerie** :
  - Entre utilisateurs.
  - Pour signalement de dysfonctionnement côté admin.
- 🔍 **Recherche dynamique** : recherche sans clic sur bouton.
- 🎨 **Refontes UX/UI** :
  - Header avec menu déroulant.
  - Pages : Accueil, Achats, Commandes, Panel Admin, Broadcast.
  - Boutons plus accessibles et esthétiques.

---

## 🧠 Priorisation et gestion
Chaque amélioration a été évaluée selon :
- Sa **complexité**
- Son **importance**
- Le **temps estimé**

Une valeur de complexité **Fibonacci** a été attribuée à chaque tâche.

---

## ⚠️ Limitations
- L’upload de photo de profil fonctionne uniquement **en local** à cause de problèmes de droits sur le serveur.
- Certaines modifications esthétiques ne sont pas visibles sans les données de production.

---

## ✅ Résultat
Le site a gagné en **ergonomie**, **sécurité** et **fonctionnalité**. Il est désormais plus intuitif, moderne et robuste face aux erreurs utilisateurs ou potentielles attaques.
