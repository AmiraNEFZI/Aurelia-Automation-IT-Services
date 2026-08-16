# Aurelia Automation & IT Services — Site Vitrine

Site web vitrine professionnel pour **Aurelia Automation & IT Services**, société spécialisée en solutions informatiques pour entreprises.

## Stack Technique

- **Framework** : [Astro 7](https://astro.build) — rendu statique (SSG)
- **CSS** : [Tailwind CSS 4](https://tailwindcss.com) + [Preline UI](https://preline.co)
- **Fonts** : DM Sans + Work Sans (Google Fonts)
- **Formulaires** : [Formspree](https://formspree.io)
- **Hébergement recommandé** : [Cloudflare Pages](https://pages.cloudflare.com)

## Pages

| Page | Route | Description |
|------|-------|-------------|
| Accueil | `/` | Hero, services, workflow, valeurs, CTA |
| Services | `/services` | 6 services détaillés avec features |
| À propos | `/about` | Histoire, statistiques, expertise, valeurs |
| Contact | `/contact` | Formulaire de contact + coordonnées |
| 404 | `/404` | Page d'erreur personnalisée |

## Démarrage rapide

```bash
# Installer les dépendances
npm install --legacy-peer-deps

# Lancer le serveur de développement
npm run dev

# Build de production
npm run build

# Prévisualiser le build
npm run preview
```

## Configuration avant déploiement

1. **`astro.config.mjs`** — Remplacez `site` par votre domaine réel
2. **`ContactForm.astro`** + **`FooterForm.astro`** — Remplacez `VOTRE_FORMSPREE_ID` par votre ID [Formspree](https://formspree.io)
3. **`Footer.astro`** + **`contact.astro`** — Mettez à jour le téléphone et l'email

## Déploiement

Consultez le fichier **`guide-deploiement.html`** à la racine du projet pour le guide complet avec analyse Vercel vs Cloudflare Pages.

---

&copy; 2020–2026 Aurelia Automation & IT Services. Tous droits réservés.
