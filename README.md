# Monster Garage 83 — Site vitrine

Site vitrine multi-pages pour Monster Garage 83 (marchand auto sport/luxe/supercar, La Crau).
Conçu & développé par PMC Marketing — https://www.agence-pmc-marketing.com/

## Pages
- `index.html`      — Accueil
- `vehicules.html`  — Nos véhicules (grille + filtres + fiche détaillée)
- `a-propos.html`   — Le garage (à propos, engagements, stats)
- `blog.html`       — Actualités (5 articles, lecture plein écran)
- `contact.html`    — Contact (formulaire + coordonnées + plan)

Site 100% statique, images intégrées dans les fichiers (aucune dépendance, aucun build).

## Mettre à jour le site en ligne (depuis ce dossier)
```bash
git add .
git commit -m "Ajout pages Le garage, Actualités et Contact"
git push
```
Vercel redéploie automatiquement à chaque push.

## À brancher en production (démo pour l'instant)
- Formulaire de contact → email / Formspree / CRM
- Stock véhicules → Supabase (table + back-office) quand le client signe
