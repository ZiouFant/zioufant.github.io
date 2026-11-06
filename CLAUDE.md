# zioufant.github.io — règles du dépôt

Site GitHub Pages statique (`.nojekyll`) qui héberge les **politiques de confidentialité** des
applications de ZiouFa, une par dossier : `carreaudujour/privacy.html`, `ricoshot/privacy.html`.
Ces URL sont déclarées dans les fiches des stores (Google Play) : ne jamais les déplacer ni les
renommer.

## Règles

- Une page de confidentialité décrit ce que l'application fait **réellement**, ni plus ni moins.
  Elle se met à jour **avant** la publication de toute version de l'application qui change la
  collecte ou l'envoi de données.
- **Ressources externes** : avant de modifier une page, consulter `RESSOURCES.md` (catalogue
  [public-apis/public-apis](https://github.com/public-apis/public-apis) et outils de contrôle).
  Si une application intègre une API (prise dans public-apis ou ailleurs), un SDK de publicité ou un
  service tiers, sa page doit nommer ce service, les données qu'il reçoit, et renvoyer vers sa propre
  politique de confidentialité.
- HTML et CSS seuls, sans script, sans police ni ressource tierce : une page de confidentialité ne
  doit elle-même rien collecter.
- Pages en français, date d'effet à jour à chaque modification.
- Travailler sur une branche dédiée et passer par une pull request ; `main` est publiée
  automatiquement par GitHub Pages.
