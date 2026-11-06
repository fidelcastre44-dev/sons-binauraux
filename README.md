# Sons binauraux

Outil de méditation dans le navigateur : sons binauraux avec transition progressive, paysage sonore génératif (nappe, halo, basse, carillons) et enregistrements de nature superposables. Tout le son est généré en direct avec la Web Audio API ; seuls les sons de nature sont des fichiers.

## Fonctionnalités

- Six voyages prêts (Sommeil, Méditation, Détente, Focus, Créativité, Profondeur) : l'écart binaural glisse de la fréquence de départ vers la cible.
- Quatre harmonies (Aube, Nuit, Brume, Abysse), accordées sur la fréquence de base.
- Huit sons de nature en boucle sans couture : pluie, orage, vagues, ruisseau, vent, oiseaux, grillons, feu de bois.
- Guide de respiration (cohérence cardiaque, 4-6, carré, 4-7-8), la nappe peut suivre le souffle.
- Pause, extinction douce, gongs de début et de fin, réglages et statistiques gardés dans le navigateur.

## Lancer

Ouvrir `index.html` via un serveur local (les sons de nature sont chargés avec `fetch`) :

```sh
python3 -m http.server
```

puis aller sur http://localhost:8000. Écoute au casque pour l'effet binaural.

## Crédits des sons

Enregistrements issus du projet libre [Blanket](https://github.com/rafaelmardojai/blanket) ([licences](https://github.com/rafaelmardojai/blanket/blob/master/SOUNDS_LICENSING.md)), montages de Porrumentzio, normalisés et convertis en AAC.

| Fichier | Auteur | Licence |
|---|---|---|
| rain.mp4 | [alex36917](https://freesound.org/people/alex36917/sounds/524605/) | CC BY |
| storm.mp4 | [Digifish music](https://freesound.org/people/digifishmusic/sounds/41739/) | CC BY |
| waves.mp4 | [Luftrum](https://freesound.org/people/Luftrum/sounds/48412/) | CC BY |
| stream.mp4 | [gluckose](https://freesound.org/people/gluckose/sounds/333987/) | CC0 |
| wind.mp4 | [felix.blume](https://freesound.org/people/felix.blume/sounds/217506/) | CC0 |
| birds.mp4 | [kvgarlic](https://freesound.org/people/kvgarlic/sounds/156826/) | CC0 |
| summer-night.mp4 | [Lisa Redfern](https://soundbible.com/2083-Crickets-Chirping-At-Night.html) | Domaine public |
| fireplace.mp4 | [ezwa](https://soundbible.com/1543-Fireplace.html) | Domaine public |

Pratique de relaxation sans effet médical garanti. Ne pas utiliser en conduisant.
