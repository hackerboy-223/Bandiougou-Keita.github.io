# Bandiougou Keita — Portfolio

Portfolio personnel de Bandiougou Keita, jeune diplômé en Génie Minier.

## Direction artistique
- Interface éditoriale premium, minimaliste et lumineuse.
- Typographie expressive, grands espaces et palette ivoire / graphite / bronze.
- Animations au scroll via IntersectionObserver et transitions CSS natives.
- Navigation mobile, barre de progression et prise en charge de `prefers-reduced-motion`.
- Mise en page responsive sans dépendance JavaScript externe.

## Contenu
- Profil et présentation.
- Parcours au Lycée Technique de Bamako et baccalauréat 2026, mention Bien.
- Prix d'Excellence du Président de la Transition.
- Projet de cycle d'ingénieur en Russie et ambition de contribuer au Mali.
- Contact téléphonique.

## Lancer en local
Ouvrir simplement `index.html` dans un navigateur ou lancer :
```bash
python3 -m http.server 8000
``
Puis visiter `http://localhost:8000`.

## Qualité et référencement
- Métadonnées canonical, Open Graph et Twitter Cards.
- Rendu de secours si JavaScript ou `IntersectionObserver` est indisponible.
- Navigation mobile accessible au clavier (Échap pour fermer).
- Les images principales et secondaires utilisent des priorités de chargement adaptées.
- Les références techniques et critères de validation sont documentés dans [`REFERENCES.md`](REFERENCES.md).

## Déploiement GitHub Pages
Dans `Settings → Pages`, sélectionner `Deploy from a branch`, puis `main` et `/(root)`. Le fichier `index.html` doit rester à la racine. Après publication, vérifier le site depuis le bouton `Visit site`.

## Médias
Les médias du portfolio sont attendus dans `assets/` :
- `bandiougou-keita.webp` — portrait.
- `prix-excellence.webp` — diplôme.
