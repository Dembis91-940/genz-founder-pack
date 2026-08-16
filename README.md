# 🚀 Gen Z Founder Starter Pack

**De l'idée à ta première vente en 30 jours, sans budget.**

Pack complet (landing + formation + templates) pour la nouvelle génération d'entrepreneurs : la Gen Z (16-27 ans) qui veut lancer sa startup mais se noie entre les idées, le syndrome de l'imposteur et un budget de 0 €.

> ⚠️ **Positionnement :** ce business est **distinct de confiance-genz** (qui aide les jeunes à décrocher un emploi). Ici, l'objectif est de **LANCER SA STARTUP** : valider une idée, construire un MVP, gagner en visibilité et encaisser sa première vente.

---

## 📦 Contenu du pack

| Fichier | Rôle |
|---|---|
| `index.html` | Landing page de vente (design néon rose/bleu, formulaire EmailJS, chatbot, SEO) |
| `chatbot.js` | Widget chatbot autonome (pattern éprouvé) — réponses préprogrammées + capture de leads |
| `chatbot-config.js` | Configuration du chatbot : accent `#ec4899`, textes & FAQ spécifiques Gen Z Founder, EmailJS |
| `formation-genz-founder.md` | LA formation niveau expert (~25 pages) : méthode 30 jours jour par jour + mindset + budget zéro + checklist finale |
| `templates/business-model-canvas-1page.md` | Ton modèle économique sur une page |
| `templates/pitch-deck-10-slides.md` | Ton pitch en 10 slides (investisseur & client) |
| `templates/pricing-2026.md` | Trouve ton prix sans avoir honte (5 étapes) |
| `templates/lancement-tiktok-7-jours.md` | Ta semaine de contenu TikTok prête à remplir |
| `templates/email-vente-premiere.md` | Le message qui transforme l'intérêt en première vente |

---

## 🎨 Design

- **Palette néon :** rose vif `#ec4899` · bleu électrique `#3b82f6` · noir profond `#0a0a0f`
- **Typographies :** Space Grotesk (titres) + Inter (texte)
- **Vibes « nouvelle génération » :** dégradés néon, glows, grille de fond, cartes glassmorphism, animations reveal au scroll
- **Unique :** aucune ressemblance avec les autres livrables (confiance-genz, ai-course-builder, etc.)

## 🧩 Sections de la landing

1. Hero — « Ta startup. Ton empire. Zéro budget. » + stats + plan de bataille 4 phases
2. Les 3 douleurs Gen Z — l'overthinking 🌀 / le syndrome de l'imposteur 🫥 / l'argent 💸
3. La méthode 30 jours — 4 phases : IDÉE → PRODUIT → VISIBILITÉ → VENTE
4. Ce que tu repartiras avec — formation + templates + checklist + accompagnement
5. Les 3 offres — Starter 19 € · Pro 39 € (⭐ le plus choisi) · Founder 79 €
6. Formulaire de contact (EmailJS)
7. FAQ (6 questions)
8. Footer

## ⚙️ EmailJS (réel, branché)

- **Service ID :** `service_cy1ytdb`
- **Template ID :** `template_xpo58cv`
- **Public Key :** `8Pui4ZEqxW2jRVF7h`
- **Payload envoyé :** `{ site, name, email, question }` — `site = "Gen Z Founder Starter Pack"`
- Utilisé par le formulaire de contact **et** par le chatbot (capture de leads).
- Zéro simulateur : l'envoi est réel, avec gestion d'erreur et confirmation visuelle.

## 🤖 Chatbot

- Fichiers : `chatbot.js` (widget) + `chatbot-config.js` (config).
- Accent `#ec4899`, nom « Gen Z Founder », ton « tutoiement startup ».
- FAQ spécifiques : pour qui, budget zéro, quel pack, méthode 30 jours, livraison, remboursement, première vente, technique, contenu.
- Question non reconnue → capture de leads (nom + email) stockée en local **et** envoyée via EmailJS.

## 🔍 SEO

- Meta description + keywords + canonical
- Open Graph (type, titre, description, locale `fr_FR`)
- Twitter Card
- **Schema.org JSON-LD** : `Product` avec les 3 offres (19 € / 39 € / 79 €)
- Sémantique HTML5 (header, nav, section, footer)

---

## 🚀 Mise en ligne

Héberger l'ensemble du dossier sur un hébergement statique (Netlify, Vercel, GitHub Pages — ou le service d'hébergement de ton choix). **Ne pas publier ce dossier sur GitHub tant que le client ne l'a pas demandé.**

1. Uploader tous les fichiers (garder l'arborescence `templates/`).
2. Ouvrir `index.html` et tester : formulaire (envoi EmailJS), chatbot, ancres, responsive mobile.
3. Vérifier que l'email de réception du template EmailJS reçoit bien `{site, name, email, question}`.
4. (Option) Remplacer l'URL canonique et les liens de paiement par ceux du client.

---

## 🛒 Paiement

La landing collecte les demandes via le formulaire EmailJS. Pour encaisser, connecter chaque bouton d'offre à un lien de paiement (Stripe Payment Link ou équivalent) — les boutons `data-pack` pré-remplissent déjà le champ « question » du formulaire pour faciliter la conversion.

---

## 📝 Notes de qualité

- Orthographe française vérifiée (relecture humaine recommandée avant publication).
- Garantie 14 jours mentionnée dans les offres et la FAQ.
- Design responsive : mobile, tablette, desktop.
- Accessibilité de base : contrastes, labels de formulaire, `prefers-reduced-motion`.

---

© 2026 Gen Z Founder — Fait avec 💗
