HNR CONSULTING — V45 — RESPONSIVE HERO, TAGS, RECHERCHE DESKTOP ET CLOCHE

FICHIERS DU PACKAGE
- index.html : fichier HTML principal à la racine du dépôt. Il contient le site complet et la page Clubs d’anglais.
- Les dossiers formation/, traduction/, manager/, contact/, inscription/, devis/, faq/, admin/, verify/, events/ et clubs-anglais/ contiennent chacun un index.html léger qui redirige vers la route correspondante de l’application principale.
- clubs-anglais/academic-illustration.webp : illustration Academic existante, conservée.
- clubs-anglais/professional-illustration.webp : illustration Professional existante, conservée.

MODIFICATIONS V45
- Les titres et textes de hero utilisent des retours à la ligne naturels et ne coupent pas les mots.
- Les tags de hero s’ajustent à leur texte au lieu de s’étirer sur la colonne.
- À partir de 981 px, la loupe de recherche est affichée au début du menu horizontal. Sous 981 px, la recherche mobile est utilisée.
- La cloche du bandeau d’annonce n’a ni transition ni animation/zoom.
- Les autres contenus et fonctions du site sont conservés à partir de la V44.

DÉPLOIEMENT GITHUB PAGES
1. Téléchargez et décompressez le ZIP.
2. Dans le dépôt hnrconsulting/wpa, remplacez le fichier racine index.html par celui du package.
3. Remplacez les index.html des dossiers de pages par les wrappers fournis dans le ZIP. Conservez les deux illustrations WebP de clubs-anglais/.
4. Ne supprimez aucun autre dossier ou fichier du dépôt (notamment les bibliothèques PDF et les ressources existantes).
5. Committez les changements et attendez la fin du déploiement GitHub Pages.
6. Vérifiez https://hnrconsulting.github.io/wpa/ puis les URL /formation/, /traduction/, /events/ et /clubs-anglais/. Chaque wrapper doit rediriger vers sa page dans l’application principale.
7. Vérifiez sur ordinateur aux largeurs 981 px, 1024 px, 1280 px et 1440 px, puis sur mobile. Actualisez sans cache si nécessaire.

ARCHITECTURE
Le site reste un seul index.html principal contenant les pages de l’application. Les sous-dossiers de pages utilisent des wrappers index.html qui redirigent vers la route intégrée. Cela évite les copies concurrentes de plusieurs Mo et conserve l’architecture du site.

VALIDATION
Contrôles statiques effectués sur les sélecteurs, le wrapper et la présence des ressources. Le déploiement GitHub Pages et le rendu en navigateur réel ne sont pas effectués depuis ce package.
