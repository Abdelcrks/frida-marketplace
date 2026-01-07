This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
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
