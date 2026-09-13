# Vymova dictionary packs

Offline dictionary packs for [Vymova](https://github.com/EvilZorge/Vymova), a fast translator for macOS.
The app reads `manifest.json` from this repository and downloads packs from the Releases page.

Each pack is a read-only SQLite database (`.dict`, compressed as `.dict.xz`) with headwords, IPA transcription,
parts of speech, senses and translation variants.

## Data source and license

All packs are derived from [Wiktionary](https://en.wiktionary.org) via the
[Wiktextract](https://github.com/tatuylonen/wiktextract) dumps published at [kaikki.org](https://kaikki.org/dictionary/).

The data is licensed under the [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
license (CC BY-SA 4.0). Wiktionary contributors are the authors; the packs are redistributed under the same license.
