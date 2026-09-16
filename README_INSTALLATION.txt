HNR CONSULTING — SITE UNIFIÉ FINAL V28
=====================================

ARCHITECTURE
-------------
Le fichier /index.html est la source unique du site : header, navigation, recherche, footer, CSS commun et contenus des pages y sont centralisés.

Les dossiers secondaires sont de petits points d’entrée qui redirigent vers la page intégrée correspondante. Ils ne contiennent ni copie du header/footer ni assets applicatifs.

INSTALLATION SUR GITHUB PAGES
------------------------------
Si l’ancien dépôt est supprimé, téléversez TOUT le contenu de ce package à la racine du dépôt. Ne créez pas de dossier assets.

Structure :
  index.html
  og-image.jpg
  robots.txt
  sitemap.xml
  README_INSTALLATION.txt
  formation/index.html
  traduction/index.html
  manager/index.html
  contact/index.html
  inscription/index.html
  devis/index.html
  faq/index.html
  admin/index.html
  verify/index.html
  events/index.html

Les images et la police nécessaires au rendu applicatif restent intégrées directement dans index.html. L’image og-image.jpg est conservée à la racine comme image Open Graph publique accessible aux crawlers sociaux et utilisée par toutes les pages, y compris Événements.

ÉVÉNEMENTS
----------
URL d’entrée : /wpa/events/
Titre SEO : Session Octobre 2026 | HNR Consulting
Titre hero : Formation certifiante en anglais
La page est intégrée comme #page-events dans le même document que toutes les autres pages.

Le CTA sticky est limité à la page Événements et aux smartphones : il apparaît après la sortie du hero et disparaît à l’approche/à l’affichage du CTA final « Votre prochaine étape commence ici. ».

SEO / OPEN GRAPH
----------------
Les titres suivent le format « [Tag du hero] | HNR Consulting ». La page Événements utilise « Session Octobre 2026 | HNR Consulting ».
Les descriptions sont adaptées à chaque page.
L’image Open Graph standard /og-image.jpg est utilisée par toutes les pages, y compris Événements. L’ancienne image Open Graph spécifique à Événements a été supprimée.
Les métadonnées canoniques, Open Graph, Twitter Cards, robots, sitemap et données structurées sont incluses.

POP-UP PÔLE TRADUCTION
----------------------
Une version JPEG optimisée de l’image promotionnelle fournie (1280 × 853 px, 194 580 octets) est intégrée directement dans index.html. Sur la page Pôle Traduction, le pop-up s’ouvre 3 secondes après l’ouverture de la page, avec une animation de glissement depuis le haut. Le bouton X apparaît 3 secondes après l’ouverture du pop-up. Seul ce bouton ferme le pop-up, avec une animation de retour vers le haut. Un clic sur l’image ouvre la page Devis.

INSCRIPTION / DEVIS
-------------------
Les moteurs de génération PDF existants restent dans index.html. Les formulaires d’inscription et de devis conservent leurs comportements et leurs téléchargements PDF.

MENU
----
« Événements » est caché dans le menu horizontal desktop et apparaît dans le menu hamburger mobile/tablette. Dans le footer, il est placé juste au-dessus de FAQ.

ESPACE ADMINISTRATEUR
---------------------
/admin/ est exclu de l’indexation par les métadonnées robots et par robots.txt.
