# Plan de Migration Design - Style SXE Consulting

## 🎯 Objectif
Adapter le design actuel d'Aurelia Automation pour qu'il ressemble au site SXE Consulting tout en conservant **TOUT le contenu actuel**.

---

## 🎨 Palette de Couleurs SXE

### Couleurs Principales
```css
/* AVANT (Aurelia actuel) */
--brand-700: #0369a1 (bleu cyan)
--teal-600: #0d9488 (teal)

/* APRÈS (Style SXE) */
--navy: #0f172a (bleu marine très foncé)
--accent: #f59e0b (orange/ambre)
--secondary: #3b82f6 (bleu clair pour accents)
```

### Backgrounds
```css
--bg-primary: #ffffff (blanc)
--bg-secondary: #f8fafc (gris très clair)
--bg-dark: #0f172a (navy pour sections sombres)
```

### Textes
```css
--text-primary: #0f172a (presque noir)
--text-secondary: #64748b (gris moyen)
--text-light: #cbd5e1 (gris clair)
```

---

## 📋 Changements par Section

### ✅ 1. Tailwind Config
- Ajouter couleurs custom (navy, accent-orange)
- Garder les couleurs brand existantes comme fallback

### ✅ 2. Navbar
**Style SXE :**
- Background blanc avec ombre légère
- Texte navy/noir
- Hover avec soulignement orange
- Logo à gauche, menu centré, CTA à droite

**Actions :**
- Changer couleurs links
- Modifier hover states
- Ajuster CTA button (orange au lieu de bleu)

### ✅ 3. Hero Section (Homepage)
**Style SXE :**
- Titre noir/navy avec un mot en orange
- Sous-titre gris
- Chiffres clés en gros (format +XX%, −XX%)
- CTA orange proéminent
- Pas d'image de fond, fond blanc/gris clair

**Actions :**
- Simplifier le hero
- Ajouter KPIs en grand
- Changer couleurs CTA

### ✅ 4. Sections Services
**Style SXE :**
- Numérotation 01, 02, 03... en gros gris clair
- Cards blanches avec bordure subtile
- Titre en navy
- Icône ou badge simple
- Flèche "En savoir plus →"

**Actions :**
- Ajouter numérotation
- Simplifier cards
- Retirer gradients complexes
- Ajouter flèches de navigation

### ✅ 5. Page Services
**Style SXE :**
- Liste numérotée claire
- Descriptions concises
- Chiffres/résultats en évidence
- Sections alternées blanc/gris clair

**Actions :**
- Restructurer avec numéros
- Simplifier design
- Mettre résultats en avant

### ✅ 6. About / À propos
**Style SXE :**
- Photos fondateurs en rond ou carré simple
- Texte sur fond blanc
- Expertise listée avec puces
- Pas de gradients

**Actions :**
- Simplifier layout fondateurs
- Enlever gradients brand
- Ajuster espacement

### ✅ 7. Actualités
**Style SXE :**
- Cards simples blanches
- Badge catégorie sobre
- Pas d'images immenses
- Focus sur le texte

**Actions :**
- Réduire taille images
- Simplifier layout
- Badges plus sobres

### ✅ 8. Footer
**Style SXE :**
- Background navy foncé
- Texte blanc/gris clair
- Liens avec hover orange
- Layout simple en colonnes

**Actions :**
- Changer background en navy
- Ajuster couleurs liens
- Simplifier structure

### ✅ 9. CTA Sections
**Style SXE :**
- Background navy avec texte blanc
- CTA orange proéminent
- Texte centré
- Icônes simples (téléphone, email)

**Actions :**
- Background navy au lieu de brand
- Boutons orange
- Simplifier design

---

## 🔄 Ordre d'Implémentation

### Phase 1 : Configuration
1. Mettre à jour `tailwind.config.js` avec nouvelles couleurs
2. Créer classes utility pour navy/orange

### Phase 2 : Composants Globaux
1. Navbar
2. Footer
3. Boutons/CTA

### Phase 3 : Pages Principales
1. Homepage (Hero + sections)
2. Services
3. About
4. Actualités

### Phase 4 : Ajustements Finaux
1. Espacement
2. Typographie
3. Responsive
4. Tests cross-browser

---

## ⚠️ Points d'Attention

### À CONSERVER
- ✅ **Tout le contenu textuel**
- ✅ **Toutes les images des fondateurs, partenaires**
- ✅ **Toutes les pages existantes**
- ✅ **Toute la structure de navigation**
- ✅ **Les posts LinkedIn intégrés**

### À SIMPLIFIER
- ❌ Gradients complexes → backgrounds unis
- ❌ Couleurs vives multiples → navy + orange
- ❌ Cards avec ombres multiples → ombres simples
- ❌ Animations complexes → transitions simples

---

## 📐 Grille Typographique SXE

```
H1: text-5xl/6xl font-bold text-navy
H2: text-3xl/4xl font-bold text-navy
H3: text-2xl font-bold text-navy
Body: text-base text-slate-600
Small: text-sm text-slate-500
Numbers: text-4xl/5xl font-bold text-accent (orange)
```

---

## 🎯 Résultat Attendu

Un site qui :
- Ressemble visuellement à SXE (couleurs, structure, minimalisme)
- Garde TOUT le contenu d'Aurelia
- Est plus épuré et professionnel
- Met en avant les résultats/chiffres
- Est facile à lire et naviguer

---

**Prêt pour l'implémentation ! 🚀**
