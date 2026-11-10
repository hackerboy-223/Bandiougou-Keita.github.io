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

## Hébergement et domaine officiel
Le site public est hébergé sur Vercel : [bandiougou-keita.vercel.app](https://bandiougou-keita.vercel.app/). Le dépôt GitHub sert de source au projet Vercel ; les changements poussés sur la branche de production liée déclenchent un nouveau déploiement. Vérifier le dernier déploiement depuis le tableau de bord Vercel.

## Indexation Google
Le sitemap est publié à [`/sitemap.xml`](https://bandiougou-keita.vercel.app/sitemap.xml). Le fichier [`/robots.txt`](https://bandiougou-keita.vercel.app/robots.txt) autorise l'exploration et indique ce sitemap. La balise actuellement conservée dans le HTML a été fournie pour l'ancienne adresse GitHub Pages ; elle ne doit pas être considérée comme une validation du nouveau domaine Vercel. Créer une propriété de type Préfixe de l'URL pour `https://bandiougou-keita.vercel.app/`, choisir la méthode Balise HTML et remplacer/ajouter le nouveau jeton après l'avoir obtenu. Ensuite, cliquer sur « Vérifier », soumettre `sitemap.xml`, inspecter l'URL d'accueil et demander son indexation.

L'ajout au sitemap aide Google à découvrir l'URL mais ne garantit ni son indexation ni sa position. La propriété Search Console doit être vérifiée par le propriétaire du site.

## Médias
Les médias du portfolio sont attendus dans `assets/` :
- `bandiougou-keita.webp` — portrait.
- `prix-excellence.webp` — diplôme.
