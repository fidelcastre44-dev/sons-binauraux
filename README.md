# Sons binauraux

Outil de méditation dans le navigateur : sons binauraux avec transition progressive, paysage sonore génératif (nappe, halo, basse, carillons) et enregistrements de nature superposables. Tout le son est généré en direct avec la Web Audio API ; seuls les sons de nature sont des fichiers.

## Fonctionnalités

- Battement binaural fixe de 4 Hz, la fréquence utilisée par Tom Campbell et Bob Monroe : 108 Hz à gauche, 112 Hz à droite (le La en accord 432 Hz le plus proche de 100 Hz).
- Quatre harmonies (Aube, Nuit, Brume, Abysse) accordées sur ce La : nappe, halo, basse et carillons génératifs.
- Une voix lointaine en trois couleurs (cuivrée façon CS-80, thérémine, analogique filtrée), avec un réglage de fréquence d'apparition.
- Huit sons de nature superposables, en boucle sans couture.
- Séances de 20 min par défaut, extinction douce, gongs de début et de fin, lecture écran verrouillé.

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
