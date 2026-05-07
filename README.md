# FNCK GUM — Site Vitrine Complet

Site vitrine statique multi-pages pour FNCK GUM (The Functional Kick).

## Pages

| Page | Fichier | Description |
|------|---------|-------------|
| **Home** | `index.html` | Hero, 4 produits, manifesto, investors preview |
| **Our Story** | `story.html` | Story de marque, founder, philosophie |
| **The Science** | `science.html` | Ingrédients clés, études, transparence |
| **FOCUS** | `focus.html` | Fiche produit complète + ingrédients |
| **BOOST** | `boost.html` | Fiche produit complète + ingrédients |
| **RESET** | `reset.html` | Fiche produit complète + ingrédients |
| **SPARK** | `spark.html` | Fiche produit complète + ingrédients |
| **Investors** | `investors.html` | Pitch deck, chiffres, round |
| **FAQ** | `faq.html` | Questions fréquentes |
| **Contact** | `contact.html` | Formulaire + emails |

## Design

- **Couleurs :** Terre, mat, cream/chocolate/sage/caramel/slate/bordeaux
- **Typography :** Playfair Display (serif) + Inter (sans-serif)
- **Style :** Premium artisan, Aesop-inspired, zero pharmacie
- **Responsive :** Mobile + desktop

## Images

Toutes les images générées par IA sont dans `images/`.

## Utilisation

```bash
# Ouvrir en local
open index.html

# Ou lancer un serveur local
python3 -m http.server 8000
# Puis aller sur http://localhost:8000
```

## Déployer

### GitHub Pages
```bash
git init
git add .
git commit -m "Site vitrine FNCK GUM"
git remote add origin https://github.com/USERNAME/fnck-gum-site.git
git push -u origin main
```

Puis activer GitHub Pages dans Settings → Pages.

---

*Site vitrine — pas de backend, pas de paiement, 100% statique.*
