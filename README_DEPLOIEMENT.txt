HNR CONSULTING — V25 / SESSION OCTOBRE 2026
==============================================

BASE : V24 + package événement V2.

FICHIERS À REMPLACER
--------------------
1. Racine du dépôt : remplacer index.html par celui de ce package.
   Cette version conserve V24 et ajoute :
   - lien « Événements » dans le hamburger uniquement sur smartphone/tablette ;
   - lien « Événements » dans le footer, immédiatement au-dessus de FAQ ;
   - recherche du site enrichie avec les titres/sections de la page Événements ;
   - suppression du téléphone du header desktop ;
   - ajustements de la page « Mot du Manager Général » sur mobile/tablette et image paysage.

2. Ajouter events/index.html et tout events/assets/.

IMPORTANT : aucun hnr-logo.webp n'est requis dans events/assets/. Le logo du header/footer est celui embarqué dans le code V24, comme demandé.

URL PAGE ÉVÉNÉMENT : https://hnrconsulting.github.io/wpa/events/

IMAGES EVENT :
- formation-anglais-octobre-2026.webp : Hero
- conference-hnr-anglais.webp : objectifs
- equipe-multiculturelle-hnr.webp : organisateur, affichage 4:5 sans recadrage
- event-og.jpg : Open Graph 1200x630

SEO : titre <title>, og:title et twitter:title = « Formation anglais — HNR Consulting ».

STICKY CTA : uniquement smartphone, invisible dans le hero et masqué à l'approche de la section finale.

LIEU : le bloc « Carrefour Boulingui... La page n'intègre pas... » a été supprimé.

HORAIRES : les deux créneaux horaires partagent la même classe de style (bleu + gras), et les intitulés de parcours partagent une classe normale.

INSCRIPTION : les CTA utilisent /wpa/inscription/ et aucun formulaire parallèle n'est créé.


V26 — CORRECTION HEADER / MOBILE / RECHERCHE
---------------------------------------------
La page events/index.html a été corrigée pour reprendre le comportement du header HNR :
- loupe confinée dans le panneau de recherche ;
- icônes de contact/réseaux confinées dans le menu mobile ;
- lien Événements masqué sur desktop et visible dans le hamburger sur mobile/tablette ;
- aucun téléphone/réseau social affiché sur la ligne horizontale desktop.
