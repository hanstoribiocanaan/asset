# Generation IX icon provenance

Source: https://github.com/PokeAPI/sprites
Pinned upstream commit: `1b3b7c0a538dd2226ae08d0d2f8955125075bbd4`.

Original PNGs come from `sprites/pokemon/versions/generation-ix/{scarlet-violet,legends-za,champions}/icons/` plus exactly 182 normal and 182 shiny base-species files from `sprites/pokemon/other/home/` for species absent in all three Generation IX packs. No transformation or resizing was applied. Filenames, game names, and variant subdirectories are preserved. Every source entry is verified against the upstream Git blob SHA-1 and has its own content SHA-256 in `manifest.json`.

- Pokémon sprites for all games from Pokémon: Let’s Go Pikachu & Let’s Go Eevee onward were rendered by [FallenDeity](https://github.com/FallenDeity) from original game assets.

The upstream `LICENCE.txt` is reproduced byte-for-byte as `LICENCE.upstream.txt`. It states that image contents are Copyright The Pokémon Company and distributes the repository under CC0 1.0 Universal. These notices must remain distinct.

The manifest retains all 3,565 upstream file identities. Exact byte duplicates are stored once; `assetPath` and `aliasOf` identify that original PNG. `path` records the original game/icons pathname under this pack. Consumers must use `assetPath`.

The source preference is Scarlet/Violet, then Legends Z-A, then Champions, then generic HOME fallback for the 182 missing base species. Numeric filenames are PokéAPI Pokémon identifiers, including alternate Pokémon IDs; they are not PKHeX form indices. Species/form, sex, sweet, and shiny matching requires an independently verified mapping. Missing or ambiguous identities require HOME or generic fallback. The three Generation IX packs cover 843 base species; the 182 absent base species receive explicitly marked generic HOME fallback. HOME fallback does not prove a native form, sex, or sweet identity.

After publication, image URLs must use `https://raw.githubusercontent.com/hanstoribiocanaan/asset/<full-commit-sha>/<assetPath>`. A mutable branch URL is not an approved application reference.
