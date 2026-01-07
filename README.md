# 🛍️ Ada Market Place — Adaverse 2.0

Plateforme de **marketplace moderne** développée dans le cadre de la formation **Ada Tech School – Promo Frida**.  
Ada Market Place permet aux utilisateurs de publier, gérer et commenter des produits, avec un **système d’authentification sécurisé**, une **gestion avancée des rôles**, et une **interface responsive**.

---

## 🚀 Stack Technique

- **Next.js** (App Router)
- **TypeScript**
- **Better Auth** (authentification & gestion des rôles)
- **Drizzle ORM** + PostgreSQL
- **Tailwind CSS**
- **Zod** (validation des données)
- **Cloudinary** (upload & stockage d’images)
- **OAuth** : Google & GitHub

---

## 🔐 Authentification & Sécurité

- Authentification via **email / mot de passe**
- Connexion avec **Google** et **GitHub**
- Gestion sécurisée des sessions
- Validation des formulaires avec **Zod**
- Séparation claire entre **authentification** et **logique applicative**

---

## 👤 Rôles & Permissions

### 🛠️ Administrateur
- Accès à tous les utilisateurs
- Accès à tous les produits
- Possibilité de :
  - Bannir un utilisateur
  - Débannir un utilisateur
  - Superviser l’ensemble de la plateforme

### 🙋 Utilisateur
- Modifier :
  - Nom
  - Email
  - Mot de passe
- Ajouter des produits
- Modifier ses propres produits
- Supprimer ses propres produits
- Ajouter une image à un produit via **Cloudinary**
- Commenter les produits

---

## 🗂️ Produits & Catégories

- Catégories dynamiques
- Produits associés à une catégorie
- Upload d’image **optionnel**
- Interface **responsive** :
  - 📱 Mobile
  - 💻 Desktop

---

## 💬 Système de Commentaires

- Ajout de commentaire **uniquement si connecté**
- Chaque utilisateur peut :
  - Modifier son propre commentaire
  - Supprimer son propre commentaire
- Relation utilisateur ↔ produit ↔ commentaire respectée en base de données

---

## 🖼️ Gestion des Images (Cloudinary)

- Upload d’images lors de la création/modification d’un produit
- Stockage sécurisé
- Optimisation automatique des images
- Pas de stockage local côté serveur

---

## 🧱 Architecture & Bonnes Pratiques

- ORM typé avec **Drizzle**
- Relations SQL claires (users, products, categories, comments)
- Séparation :
  - UI
  - Logique métier
  - Accès base de données
- Code lisible, maintenable et scalable
- Commits clairs et réguliers

---

## 👥 Équipe du Projet

Projet réalisé en **travail d’équipe** avec :

- **Abdel Berkat**  
- **Nasra** — [GitHub](https://github.com/Naloee)
- **Salem** — [GitHub](https://github.com/Slim31000)
- **Meriem** — [GitHub](https://github.com/meriemmehdi472-coder)

---

## 📦 Repository du Projet

➡️ **Repo GitHub (projet collectif avec tout l’historique des commits)**  
🔗 https://github.com/adatechschool/frida-adaverse-2-0-nasra-meriem-salem-abdel

---

## 🏗️ Statut du Projet

🚧 **Work in progress**  
De nouvelles fonctionnalités pourront être ajoutées :
- Likes / favoris
- Dashboard admin avancé
- Recherche & filtres
- Amélioration UX/UI

---

## 📜 Licence

Projet éducatif réalisé dans le cadre de la formation **Ada Tech School**.

---

✨ *Ada Market Place — apprendre, construire, collaborer.*
