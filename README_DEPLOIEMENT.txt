HNR CONSULTING — ÉVÉNEMENT FORMATION ANGLAIS — OCTOBRE 2026

FICHIERS À AJOUTER / REMPLACER

1) Remplacer le index.html actuel à la racine du dépôt par :
   index.html
   Cette version est basée sur V24 et ajoute uniquement le lien « Événements »
   dans le footer. Le menu principal n'est pas modifié.

2) Ajouter le dossier :
   events/
   avec :
   events/index.html
   events/assets/hnr-logo.webp
   events/assets/montserrat.ttf
   events/assets/formation-anglais-octobre-2026.webp
   events/assets/formation-anglais-equipe.webp
   events/assets/hnr-consulting-equipe.webp
   events/assets/event-og.jpg

3) sitemap.xml : remplacer le sitemap actuel si vous souhaitez indexer immédiatement
   la nouvelle URL /wpa/events/.

URL DE LA PAGE
https://hnrconsulting.github.io/wpa/events/

VARIABLE PRINCIPALE
Dans events/index.html :
const INSCRIPTION_URL = "/wpa/inscription/";
Modifier cette constante si l'URL de la page Inscription change.
Tous les CTA d'inscription sont reliés à cette constante.

IMAGES
Les images sont des versions optimisées issues des visuels déjà présents dans V24.
Elles sont stockées localement dans events/assets/ afin d'éviter les dépendances
à des services d'image externes.

COORDONNÉES
Les coordonnées affichées dans la page sont :
+241 74 14 70 51
contact.hnrconsulting@gmail.com

LIEU
Carrefour Boulingui, près de l'ANUTTC — Libreville, Gabon.
Le bouton « Voir l'itinéraire » utilise une recherche Google Maps textuelle ; aucune
coordonnée GPS n'est inventée.

NOTES
- La page événement est autonome et ne crée aucun formulaire ni paiement parallèle.
- Le lien « Événements » n'est pas ajouté au header : il reste uniquement dans le footer,
  conformément au cahier des charges.
- Le CTA mobile fixe disparaît lorsque la section finale d'inscription entre dans le viewport.
