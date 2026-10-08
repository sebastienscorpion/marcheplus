# MarchéPlus – E-commerce React (Vite)

## Installation
1. Installer Node.js 18+ : https://nodejs.org
2. Dans ce dossier :
   npm install
   npm run dev
3. Ouvrir http://localhost:5173

## Mise en ligne
npm run build   -> dossier `dist/` à glisser sur Netlify / Vercel / GitHub Pages

## Structure
src/data.js (produits) · src/store.jsx (état global : auth, panier, favoris, commandes)
src/components (Header, Card, Stars) · src/pages (Home, Detail, Cart, Checkout, Orders, Auth, Wish, Profile)

Code promo de test : BIENVENUE10
Note : données stockées dans le navigateur (localStorage). Pour la production, ajoutez un back-end + paiement réel.
