# Jigsaw Atelier museum

Pictures and catalog for the museum rooms of Jigsaw Atelier.

- **18 rooms of contemporary photos** (pets, horses, birds, flowers, gardens, coffee and food, mountains, ships, coasts,
  winter, autumn, night, Venice, cities, rivers, fields, skies and farm animals). Every photo is CC0 1.0 (public domain),
  found through the [Openverse](https://openverse.org) API and taken from the WordPress Photo Directory, and each one was
  checked by eye before it went in. Each work's `url` in `catalog.json` links to the photo's own page and `artist` names
  the photographer.
- **2 rooms of classic art** (Japan and Impressionists), public-domain works from The Metropolitan Museum of Art and
  The Cleveland Museum of Art Open Access programs (CC0).

`img/<id>.jpg` is the puzzle picture (long side 2048 px) and `thumb/<id>.jpg` the 480 px thumbnail. Files are only ever
added: older pictures stay in place because saved puzzles and players' galleries still point at them.

Built by `store/museum/build_photos.py` (photo rooms; the choice of photos and their titles is in
`store/museum/photo_picks.json`) and `store/museum/build.py` (classic art) in the STAR apps repository.
