# Carnet des Baronnies · Web Libre

Site statique de huit pages consacré aux Baronnies provençales, avec Nyons comme point de départ. Textes originaux, liens contextuels vers Vivre à Nyons et références officielles.

## Pages

- Accueil : `/`
- Nyons : `/nyons/`
- Villages : `/villages/`
- Balades : `/balades/`
- Patrimoine : `/patrimoine/`
- Terroir : `/terroir/`
- À table : `/a-table/`
- Séjour : `/sejour/`

## Fonctionnement

HTML et CSS sans compilation ni dépendance externe. Le menu mobile utilise l’élément HTML `details`. Les illustrations SVG sont originales. Aucun outil de suivi ni formulaire n’est intégré.

Les chemins de navigation et d’assets sont relatifs : le site fonctionne sous le préfixe GitHub Pages `/web-libre/` comme sur un domaine personnalisé. Les URL canoniques, le sitemap et `robots.txt` utilisent l’adresse GitHub Pages fournie pour ce projet. Si une autre adresse devient l’adresse publique principale, mettre à jour ces trois éléments ensemble.

Le fichier `CNAME` et le déploiement GitHub Pages existants sont conservés. Une modification sur `main` déclenche le déploiement du workflow `.github/workflows/static.yml`.

## Mise à jour

Les textes, liens et métadonnées se modifient dans les huit fichiers `index.html`. Le style commun est dans `assets/style.css`. Les conseils sont éditoriaux ; les disponibilités, horaires et conditions d’accès se vérifient auprès des organismes et établissements concernés.

Références : Parc naturel régional des Baronnies provençales, Ville de Nyons, Office de tourisme des Sources du Buëch, Syndicat de l’Olive de Nyons AOP et Météo-France. Mise à jour : 5 octobre 2026.
