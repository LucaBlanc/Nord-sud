# Nord ou Sud ?

Jeu web et mobile : chacun départage les villes de France, une seule fois par ville, entre Nord et Sud.

- **Accueil.** On demande d'où vient le joueur, puis s'il place sa propre ville au Nord ou au Sud. Sa ville porte ensuite un drapeau sur la carte.
- **Une seule page, la carte.** Les villes déjà votées sont colorées selon les résultats, les autres restent cachées (« ? ») jusqu'à ce qu'on vote.
- **Jouer = swiper.** Le bouton « Jouer » ouvre une pile de cartes : glisser à gauche pour Nord, à droite pour Sud. On réduit la pile pour revenir à la carte.
- **Les villes qui divisent.** En plus des grandes villes, la pile met en avant les villes où le débat fait rire : Montélimar, Valence, Brive-la-Gaillarde, Orléans, Saint-Étienne, Angoulême, Le Puy-en-Velay, Lyon, Clermont-Ferrand, Limoges… Chacune a un badge « Ville qui divise » et une phrase sur le débat.
- **Esprit jeu.** Points, série de votes avec la majorité, niveaux (Touriste égaré → Cartographe du Roi).
- **Écrans de chargement** avec des citations historiques françaises absurdes, marquées vrai / rapportée / légende.

## Maquette

- Maquette interactive (canvas Design, écrans mobile et web) : https://claude.ai/artifact/LdcXS1tz8hznzNUnKZTxQ5
- `maquette/index.html` : première planche, écrans mobiles seulement. Ouvrir le fichier dans un navigateur.

Les chiffres des maquettes sont des exemples.

## Version « officielle »

Variante de la maquette : même jeu, interface sobre façon service public, portée par une institution fictive, l'« Observatoire national du Nord et du Sud ». Les cartes deviennent des dossiers à instruire, le swipe tamponne « CLASSÉ NORD / SUD », le résultat est un arrêté numéroté, les niveaux sont des grades (Agent stagiaire → Conseiller d'État) et l'accueil est un formulaire avec récépissé. Elle ne reprend aucun élément réservé à l'État (Marianne, bloc-marque « République française », système de design de l'État).

## Sources des données de la maquette

- Contour de la France, départements et régions : [france-geojson](https://github.com/gregoiredavid/france-geojson) (données IGN, Licence Ouverte).
- Rivières, massifs et contour de l'Europe : [Natural Earth](https://www.naturalearthdata.com/) (domaine public).
- Photos des villes : Wikimedia Commons, voir `maquette/photos/CREDITS.md`.
