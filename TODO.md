# TODO — Portfolio Bandiougou Keita

## Structure & contenu
- [x] Initialiser le dépôt et la page d'accueil.
- [x] Construire les sections Profil, Parcours, Distinction, Vision et Contact.
- [x] Intégrer les informations biographiques fournies.
- [x] Ajouter le contact téléphonique au format international Mali.
- [x] Définir les métadonnées SEO et Open Graph.
- [x] Ajouter les deux médias optimisés dans `assets/` (portrait et diplôme) — fichiers désormais présents sur `main`.
- [ ] Vérifier le rendu visuel avec les médias réels sur desktop et mobile (validation réelle sur appareils encore nécessaire).
- [x] Audit initial du dépôt et vérification des chemins médias ; les deux images sont désormais présentes dans `assets/`.
- [x] Corriger l'URL absolue de l'image Open Graph.
- [x] Corriger l'affichage flex du bouton de menu mobile.
- [x] Vérifier la présence des deux fichiers dans `assets/` : portrait 181 757 octets, diplôme 337 555 octets.
- [ ] Contrôler le chargement HTTP, l'affichage public et le rendu sur appareils (validation navigateur réelle encore nécessaire).

## Expérience & qualité
- [x] Navigation responsive.
- [x] Révélations progressives au scroll.
- [x] Barre de progression de lecture.
- [x] Respect de `prefers-reduced-motion`.
- [x] Prévoir un affichage complet si JavaScript ou IntersectionObserver est indisponible.
- [x] Améliorer les métadonnées canonical, Open Graph et Twitter Cards.
- [x] Améliorer les attributs d'accessibilité du menu mobile et de la barre de progression.
- [x] Ajouter fermeture du menu par Échap et au redimensionnement desktop.
- [ ] Mesurer Lighthouse (Performance, Accessibility, Best Practices, SEO) sur le site publié.
- [ ] Obtenir un nouveau jeton HTML Search Console pour la propriété `https://bandiougou-keita.vercel.app/` (l'ancien jeton concernait l'URL GitHub Pages).
- [ ] Soumettre `https://bandiougou-keita.vercel.app/sitemap.xml` dans Google Search Console.
- [ ] Inspecter `https://bandiougou-keita.vercel.app/` et demander son indexation.
- [x] Vérifier le workflow GitHub Pages : build et déploiement terminés avec succès (run 42731455430, commit `963b6a4`).
- [ ] Contrôler les performances et l'accessibilité après intégration des médias.
- [x] Corriger les trois références erronées à la session de juillet : le baccalauréat est celui de juin 2026.
- [x] Élargir la mise en page desktop sans étirer excessivement les lignes de texte.
- [x] Repenser les points de rupture tablette, mobile et petit mobile.
- [x] Adapter les grilles, les images, les boutons, le contact et les espacements aux petits écrans.
- [x] Ajouter le décodage asynchrone des images.
- [x] Réduire les requêtes tierces en supprimant les polices distantes au profit des polices système.
- [x] Ajouter un lien d'évitement, un focus clavier visible et des données structurées Person.
- [x] Ajouter `REFERENCES.md` avec les sources officielles et les critères de QA.
- [x] Ajouter le nom exact « Bandiougou Keita » au titre SEO et au titre principal visible.
- [x] Ajouter les métadonnées auteur, robots et og:site_name.
- [x] Remplacer le schéma Person isolé par un schéma ProfilePage avec mainEntity Person.
- [x] Publier un sitemap XML avec l'URL canonique du portfolio.

## Vérification Search Console
- [x] Intégrer la balise HTML Google `google-site-verification` fournie par le propriétaire dans le `<head>` de `index.html`.
- [ ] Confirmer la propriété dans Search Console une fois la dernière version publiée.
- [ ] Soumettre le sitemap et demander l'indexation de l'URL d'accueil.

- [x] Ajouter `robots.txt` : exploration autorisée et sitemap déclaré.

## Migration vers Vercel
- [x] Définir `https://bandiougou-keita.vercel.app/` comme URL canonique.
- [x] Mettre à jour Open Graph, Twitter Cards et toutes les URL du schéma ProfilePage/Person.
- [x] Rebaser `sitemap.xml` et `robots.txt` sur le domaine Vercel.
- [x] Mettre à jour le README et les instructions Search Console pour Vercel.
- [ ] Ajouter le nouveau jeton Search Console pour la propriété Vercel et confirmer la propriété.
- [ ] Vérifier le rendu HTTP public sur le domaine Vercel et les deux médias.

## Correction sitemap Vercel
- [x] Ajouter `vercel.json` avec `outputDirectory: "."` pour publier les fichiers statiques à la racine.
- [ ] Vérifier dans Vercel que le projet pointe vers ce dépôt, la branche `main` et `Root Directory: ./`.
- [ ] Tester les réponses HTTP 200 et les types MIME de `/sitemap.xml`, `/robots.txt` et des deux WebP après déploiement.
- [ ] Vérifier le sitemap dans Google Search Console après retour HTTP valide.
