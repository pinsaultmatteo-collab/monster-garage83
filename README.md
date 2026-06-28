# Monster Garage 83 — Site vitrine

Site vitrine multi-pages — Monster Garage 83 (marchand auto sport/luxe/supercar, La Crau).
Conçu & développé par PMC Marketing — https://www.agence-pmc-marketing.com/

## Pages
- index.html                              Accueil
- vehicules.html                          Liste des véhicules (filtres + galerie à flèches sur les cartes)
- vehicule-ferrari-roma.html              Fiche Ferrari Roma
- vehicule-audi-rs-q8.html                Fiche Audi RS Q8
- vehicule-aston-martin-v8-vantage.html   Fiche Aston Martin V8 Vantage
- vehicule-ducati-959-panigale.html       Fiche Ducati 959 Panigale
- a-propos.html / blog.html / contact.html
- sitemap.xml / robots.txt                (référencement)

## SEO
Chaque fiche véhicule a son URL propre, un <title>/meta dédiés, un fil d'Ariane et
des données structurées JSON-LD (schema.org Car/Motorcycle + Offer) pour Google.

## Mettre à jour le site (depuis ce dossier)
    git add -A
    git commit -m "Fiches vehicules + galeries + SEO"
    git push

## Note images véhicules
Photos chargées depuis le CDN Leboncoin (annonces Monster Garage 83). Pour une robustesse
totale, prévoir un hébergement propre des images (ou via Supabase) en production.
