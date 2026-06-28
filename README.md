# Monster Garage 83 — Site vitrine

Site vitrine + page "Nos véhicules" pour Monster Garage 83 (marchand auto sport/luxe/supercar, La Crau).
Conçu & développé par PMC Marketing — https://www.agence-pmc-marketing.com/

## Contenu
- `index.html` — page d'accueil (hero, collection, à bord, services, avis, contact)
- `vehicules.html` — page "Nos véhicules" (grille + filtres + fiche détaillée)

Site 100% statique, images intégrées dans les fichiers (aucune dépendance, aucun build).

## Déploiement
1. Pousser ce dossier sur GitHub (voir commandes ci-dessous).
2. Sur https://vercel.com → **Add New… > Project** → importer le repo `monster-garage83`.
3. Framework Preset : **Other** (site statique). Aucune commande de build. Output : racine.
4. **Deploy**. `index.html` est servi sur `/`, la page véhicules sur `/vehicules.html`.

## Pousser sur GitHub (depuis le dossier site-internet)
```bash
git init
git add .
git commit -m "Mise en ligne site Monster Garage 83"
git branch -M main
git remote add origin https://github.com/pinsaultmatteo-collab/monster-garage83.git
git push -u origin main
```
Si le repo contient déjà des fichiers : `git pull origin main --allow-unrelated-histories` avant le push.

## Étape suivante (quand le client signe)
Brancher `vehicules.html` sur Supabase (table véhicules + back-office) pour une gestion de stock autonome.
