HNR CONSULTING — ÉVÉNEMENT FORMATION ANGLAIS — OCTOBRE 2026

CONTENU À INTÉGRER
==================

1. REMPLACER LE index.html RACINE
---------------------------------
Utiliser le fichier `index.html` de ce package à la racine du dépôt GitHub.
Il reprend V24 et ajoute uniquement le lien « Événements » dans le FOOTER.
Le menu principal/header n’est pas modifié pour ajouter Événements.

2. AJOUTER / REMPLACER LE DOSSIER events/
------------------------------------------
Copier intégralement `events/` dans la racine du dépôt.
La page sera disponible à : /wpa/events/

Fichiers image :
- events/assets/formation-anglais-octobre-2026.webp : HERO, classe de formation.
- events/assets/conference-hnr-anglais.webp : section Objectifs.
- events/assets/equipe-multiculturelle-hnr.webp : section Organisateur.
- events/assets/event-og.jpg : Open Graph / partage social (1200×630).

Les trois images fournies ont été optimisées en WebP et redimensionnées pour
les usages web. Le fichier OG est optimisé en JPEG.

3. POLICE ET LOGO
-----------------
Conserver dans `events/assets/` :
- hnr-logo.webp
- montserrat.ttf

4. URL D’INSCRIPTION
--------------------
Dans `events/index.html`, tous les CTA d’inscription utilisent :
const INSCRIPTION_URL = "/wpa/inscription/";
Modifier uniquement cette constante si l’URL change.

5. COORDONNÉES ET LIEU
----------------------
Téléphone : +241 74 14 70 51
Email : contact.hnrconsulting@gmail.com
Lieu : Carrefour Boulingui, près de l’ANUTTC — Libreville, Gabon
Aucune coordonnée GPS n’est ajoutée.

6. SITEMAP
----------
Le `sitemap.xml` fourni contient /wpa/events/. Si le dépôt possède déjà un
sitemap officiel, fusionner cette seule URL au lieu de remplacer le sitemap.

7. IMPORTANT
------------
Ne pas déplacer les fichiers du dossier `events/assets/`.
Ne pas créer de formulaire ou de paiement sur la page événement.
