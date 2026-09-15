HNR CONSULTING — SITE UNIFIÉ FINAL
================================

ARCHITECTURE
-------------
Le fichier /index.html est désormais la source unique du site : header, navigation, recherche, footer, CSS commun et contenus des pages y sont centralisés.

Les dossiers secondaires contiennent uniquement des points d’entrée très légers qui redirigent vers la page intégrée correspondante. Ils ne contiennent ni copie du header/footer ni assets.

INSTALLATION SUR GITHUB PAGES
------------------------------
Si l’ancien dépôt est supprimé, téléversez TOUT le contenu de ce package à la racine du dépôt. Ne créez pas de dossier assets.

Structure :
  index.html
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

Les images et la police nécessaires au rendu sont intégrées directement dans index.html. Aucun dossier assets n’est requis.

ÉVÉNEMENTS
----------
URL d’entrée : /wpa/events/
Titre SEO de la page : Formation anglais — HNR Consulting
La page est intégrée comme #page-events dans le même document que toutes les autres pages.

INSCRIPTION
-----------
Les CTA d’inscription utilisent le mécanisme déjà présent dans le site et pointent vers /wpa/inscription/.

MENU
----
« Événements » est caché dans le menu horizontal desktop et apparaît dans le menu hamburger mobile/tablette. Dans le footer, il est placé juste au-dessus de FAQ.
