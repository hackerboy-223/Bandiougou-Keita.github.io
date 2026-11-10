# Bandiougou Keita — Portfolio

Portfolio personnel de Bandiougou Keita, jeune diplômé en Génie Minier.

## Direction artistique
- Interface éditoriale premium, minimaliste et lumineuse.
- Typographie expressive, grands espaces et palette ivoire / graphite / bronze.
- Animations au scroll via IntersectionObserver et transitions CSS natives.
- Navigation mobile, barre de progression et prise en charge de `prefers-reduced-motion`.
- Mise en page responsive étendue : desktop large, ordinateurs portables, tablettes et petits mobiles.
- Grilles fluides, typographie adaptative et espacements progressifs selon la largeur disponible.
- Aucun framework ni dépendance JavaScript externe.

## Contenu
- Profil et présentation.
- Parcours au Lycée Technique de Bamako et baccalauréat — session de juin 2026, mention Bien.
- Prix d'Excellence du Président de la Transition.
- Projet de cycle d'ingénieur en Russie et ambition de contribuer au Mali.
- Contact téléphonique.

## Lancer en local
Ouvrir simplement `index.html` dans un navigateur ou lancer :
```bash
python3 -m http.server 8000
```
Puis visiter `http://localhost:8000`.

## Compatibilité responsive
Les règles CSS s'adaptent progressivement aux écrans larges, tablettes (960 px et moins), mobiles (800 px et moins), petits mobiles (640 px et moins) et formats compacts (390 px et moins). Ces seuils servent de points de transition du contenu, pas de cibles exclusives pour des modèles de téléphones.

## Qualité et référencement
- Métadonnées canonical, Open Graph, Twitter Cards et auteur.
- Nom exact « Bandiougou Keita » placé dans le titre SEO et le titre principal visible.
- Données structurées Schema.org `ProfilePage` reliées à une entité `Person`.
- Sitemap XML pour faciliter la découverte du portfolio par les moteurs de recherche.
- Rendu de secours si JavaScript ou `IntersectionObserver` est indisponible.
- Navigation mobile accessible au clavier (Échap pour fermer).
- Les images principales et secondaires utilisent des priorités de chargement adaptées.
- Les références techniques et critères de validation sont documentés dans [`REFERENCES.md`](REFERENCES.md).

## Déploiement GitHub Pages
Dans `Settings → Pages`, sélectionner `Deploy from a branch`, puis `main` et `/(root)`. Le fichier `index.html` doit rester à la racine. Après publication, vérifier le site depuis le bouton `Visit site`.

## Indexation Google
Le sitemap du site est publié à [`sitemap.xml`](https://hackerboy-223.github.io/Bandiougou-Keita.github.io/sitemap.xml). La balise HTML de vérification fournie par le propriétaire est intégrée dans le `<head>` de `index.html`. Après publication, retourner dans [Google Search Console](https://search.google.com/search-console), cliquer sur « Vérifier », puis soumettre le sitemap `sitemap.xml`, inspecter l'URL d'accueil et demander son indexation.

L'ajout au sitemap aide Google à découvrir l'URL mais ne garantit ni son indexation ni sa position. La propriété Search Console doit être vérifiée par le propriétaire du site.

## Médias
Les médias du portfolio sont attendus dans `assets/` :
- `bandiougou-keita.webp` — portrait.
- `prix-excellence.webp` — diplôme.
