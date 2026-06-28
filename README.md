# Monster Garage 83 — Site vitrine (version optimisée)

Site vitrine multi-pages — Monster Garage 83, La Crau. Par PMC Marketing.

## Pages
index.html · vehicules.html · 4 fiches vehicule-*.html · a-propos.html · blog.html · contact.html
+ sitemap.xml / robots.txt

## Optimisations de fluidité (ce build)
- Grain de film sans "mix-blend-mode" (recompositait tout l'écran à chaque frame)
- Suppression des flous "backdrop-filter" (nav, filtres, lecteur) → fonds opaques
- Parallaxe limitée au hero (GPU), suppression de la parallaxe coûteuse sur les images
- Nettoyage des "will-change" inutiles

## Mettre à jour le site (depuis ce dossier)
    git add -A
    git commit -m "Version optimisee (fluidite scroll)"
    git push
