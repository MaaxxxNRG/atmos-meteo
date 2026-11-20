# Atmos

Météo interactive en temps réel pour n'importe quelle commune de France (recherche par nom ou code postal, « Ma position », villes favorites) : un cadran à faire glisser pour avancer dans la semaine, tranche par tranche (nuit, matin, après-midi, soir).

Interface (nov. 2026) : cartes en verre dépoli sur un fond en dégradés doux qui suit l'heure, la météo et la température ; typo Geist ; mesures détaillées (ressenti, pluie, vent, humidité, nuages, pression, UV, soleil).

- `index.html` : toute l'application (HTML, CSS, JavaScript, sans framework)
- « Normal pour la saison ? » : la pastille sous la météo compare le jour affiché aux 35 dernières années (archive ERA5) ; touche-la pour le visuel complet
- Pollen : la pastille n'apparaît que quand il y a du pollen (niveau moyen ou plus) ; détail par plante sur 5 jours
- Recherche des communes : [API Découpage Administratif](https://geo.api.gouv.fr/decoupage-administratif)
- Données : [Open-Meteo](https://open-meteo.com/), chargées à l'ouverture puis toutes les 30 minutes

En ligne : https://maaxxxnrg.github.io/atmos-meteo/
