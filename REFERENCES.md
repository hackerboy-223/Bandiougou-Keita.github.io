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
