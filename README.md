# MUTUSANTÉ — Starter statique (Netlify / Cloudflare Pages)

Site statique prêt à déployer avec **bilingue FR/EN**, **formulaire Netlify Forms**, **simulateur indicatif**, **bouton WhatsApp**, et **charte** (bleu #0077B6 / vert #00A86B).

## 🚀 Déploiement rapide (Netlify — gratuit)
1. Créez un compte sur https://app.netlify.com (plan Free).
2. Cliquez **New site from Git** → Importez ce dossier dans un repo GitHub → Connectez-le.
3. Laissez `publish = "."` (netlify.toml) → **Deploy**.  
4. Activez **Forms** (le formulaire `adhesion` est auto-détecté).

## 🚀 Alternative (Cloudflare Pages — gratuit)
1. Créez un compte sur Cloudflare.
2. Pages → **Create a project** → Connect to Git → importez ce dépôt.  
3. Build command: *none*, Output directory: `/`.

## 🔧 Personnalisation
- Modifier `index.html` (textes FR/EN, numéros WhatsApp).
- Styles dans `assets/styles.css`.
- Sécurité (CSP, headers) dans `netlify.toml`.

## 📲 Paiements MoMo/TMoney (étape suivante)
Sur un hébergement gratuit statique, les paiements nécessitent un backend (ex. **Supabase Edge Functions** ou **Cloudflare Workers**). On pourra ajouter un bouton « Payer » qui redirige vers une page de paiement, puis gérer le webhook côté fonction serverless.

## ℹ️ Licence
Usage interne MUTUSANTÉ.
