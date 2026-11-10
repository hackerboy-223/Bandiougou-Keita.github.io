# Références techniques

Ce portfolio est une page statique HTML/CSS/JavaScript. Les choix de réalisation et de validation s'appuient sur les documentations officielles suivantes.

## Images et performances
- [MDN — Élément HTML `<img>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/img) : texte alternatif, dimensions intrinsèques et chargement différé.
- [MDN — Priorité de chargement `fetchpriority`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Attributes/fetchpriority) : priorité élevée réservée à l'image principale.
- [web.dev — Images responsives](https://web.dev/learn/design/responsive-images/) : chargement eager de l'image visible et lazy-loading des médias hors écran.
- [MDN — Performance HTML](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Performance/HTML) : réduction des ressources bloquantes et stratégie de chargement.

## Accessibilité
- [W3C WAI — WCAG 2.2](https://www.w3.org/TR/WCAG22/) : principes d'accessibilité, navigation clavier, focus visible et réduction des obstacles.
- [WAI-ARIA APG — Disclosure Pattern](https://www.w3.org/WAI/ARIA/apg/patterns/disclosure/) : référence pour les commandes qui affichent ou masquent un contenu de navigation.

## Référencement
- [Google Search Central — Title links](https://developers.google.com/search/docs/appearance/title-link) : titres concis et cohérents avec le contenu.
- [Google Search Central — Canonical URLs](https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls) : signal `rel="canonical"`.
- [Google Search Central — Lazy loading](https://developers.google.com/search/docs/crawling-indexing/javascript/lazy-loading) : contenu important accessible sans interaction obligatoire.

## Hébergement
- [GitHub Docs — Configurer une source de publication GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) : publication depuis `main` et la racine du dépôt.
- [GitHub Docs — Créer un site GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) : fichier d'entrée, publication et vérification du site.

## Contrôles à effectuer avant validation finale
1. Ouvrir le site publié sur un téléphone et un ordinateur.
2. Vérifier les deux images et les liens de contact.
3. Tester la navigation au clavier, le menu mobile et le mode de réduction des animations.
4. Exécuter Lighthouse et viser de bons résultats sur Performance, Accessibility, Best Practices et SEO.
5. Vérifier le statut du dernier déploiement dans l'onglet **Actions** de GitHub.

## Mise en page responsive
- [MDN — Design responsive](https://developer.mozilla.org/fr/docs/Learn_web_development/Core/CSS_layout/Responsive_Design) : grilles flexibles, points de rupture choisis selon le contenu et médias qui ne dépassent pas leur conteneur.
- [MDN — Requêtes média CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Media_queries) : adaptation conditionnelle aux dimensions et préférences de l'environnement.
- [Chrome for Developers — Responsive design](https://developer.chrome.com/docs/modern-web-guidance/guides/css/responsive-design) : unités de viewport dynamiques, aspect-ratio et typographie fluide avec `clamp()`.

## Points de contrôle responsive
- 1440 px et plus : contenu large avec largeur de lecture limitée.
- 1024 px : colonnes conservées tant que les contenus restent lisibles.
- 960 px : hero et sections complexes passent en une seule colonne si nécessaire.
- 800 px : navigation mobile et sections empilées.
- 640 px : ajustement des espacements, titres, boutons et médias.
- 390 px et moins : contrôle des petits téléphones et prévention des débordements horizontaux.

Ces valeurs sont des points de vérification pratiques ; l'adaptation suit d'abord la place réellement disponible pour le contenu.

## Visibilité dans les moteurs de recherche
- [Google Search Central — Principes fondamentaux de la recherche](https://developers.google.com/search/docs/essentials) : accessibilité du contenu, utilité, indexabilité et bonnes pratiques.
- [Google Search Central — Créer et envoyer un sitemap](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap) : format XML, découverte des URL et soumission dans Search Console.
- [Google Search Central — Demander une nouvelle exploration](https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl) : inspection d'URL et demande d'indexation par le propriétaire vérifié.
- [Google Search Central — Données structurées ProfilePage](https://developers.google.com/search/docs/appearance/structured-data/profile-page) : balisage d'une page centrée sur une personne.
- [Google Search Central — Influencer les liens de titre](https://developers.google.com/search/docs/appearance/title-link) : cohérence entre le titre HTML, le titre visible, le contenu et les liens externes.

## Suivi d'indexation
- La présence du sitemap est vérifiée dans le dépôt, mais sa lecture par Google doit être confirmée dans Search Console.
- La propriété Search Console et la demande de réexploration exigent une authentification du propriétaire ; aucune validation n'est inventée dans ce dépôt.
- L'indexation et le classement ne sont jamais garantis par un sitemap ou des données structurées.
