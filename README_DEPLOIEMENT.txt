HNR CONSULTING — V25 / SESSION OCTOBRE 2026
==============================================

BASE : V24 + package événement V2, avec intégration native de la page Événements.

1) REMPLACER À LA RACINE
-------------------------
Remplacer le index.html actuel par :
    index.html

Cette version conserve V24 et ajoute/modifie :
- suppression de l'affichage du téléphone dans la ligne du header desktop ;
- lien « Événements » dans le hamburger sur smartphone/tablette ;
- lien « Événements » dans le footer, immédiatement au-dessus de FAQ ;
- indexation dans la recherche interne des titres/sections et contenus clés de la page Événements ;
- ajustements de « Le mot du Manager Général » : tag sur une ligne, titre limité à 2 lignes sur mobile/tablette et image en paysage presque pleine largeur.

2) AJOUTER LE DOSSIER EVENTS
----------------------------
Ajouter :
    events/index.html
    events/assets/formation-anglais-octobre-2026.webp
    events/assets/conference-hnr-anglais.webp
    events/assets/equipe-multiculturelle-hnr.webp
    events/assets/event-og.jpg
    events/assets/montserrat.ttf

AUCUN hnr-logo.webp n'est nécessaire dans events/assets/.
Le logo du header/footer de la page Événements est repris du même logo embarqué dans le code V24.

3) PAGE ÉVÉNEMENT
-----------------
URL : https://hnrconsulting.github.io/wpa/events/

Le header et le footer de events/index.html reprennent le balisage du site HNR.
Le lien « Événements » du menu principal est caché sur ordinateur et visible dans le hamburger sur mobile/tablette.

4) SEO
-------
<title>, og:title et twitter:title :
    Formation anglais — HNR Consulting

La page conserve son canonical /wpa/events/ et ses données structurées Event.

5) STICKY CTA
-------------
Le CTA persistant est uniquement mobile.
Il est masqué dans le Hero, apparaît après le Hero et disparaît à l'approche du CTA final.
Son fond blanc a été réduit (semi-transparent et moins épais).

6) HORAIRES
-----------
Les heures « 09h00 – 11h00 » et « 15h00 – 17h00 » utilisent la même classe de style (bleu, gras).
Les intitulés « Anglais conversationnel » et « Anglais professionnel » utilisent la même classe normale.

7) LIEU
--------
Le bloc de disclaimer « La page n'intègre pas de coordonnées GPS non fournies » a été supprimé.
Aucune coordonnée GPS n'est inventée.

8) IMAGE APRÈS LE BLOC LIEU
----------------------------
L'illustration de l'équipe est affichée dans un cadre 4:5 avec object-fit: contain afin de conserver la vue entière.

9) SITEMAP
----------
Le sitemap.xml fourni conserve les URLs du sitemap V2 et inclut /wpa/events/.

10) IMPORTANT
-------------
Les CTA d'inscription de la page Événements utilisent :
    /wpa/inscription/

Aucun formulaire d'inscription ou paiement parallèle n'est présent sur la page Événements.
