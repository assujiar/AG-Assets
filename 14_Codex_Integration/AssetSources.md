# Asset Sources

Acquisition date: 2026-11-26. Every pack below was downloaded and extracted locally; counts are production files in this library.

## Sources successfully accessed

| Source | Access result | Used for |
|---|---|---|
| quaternius.com (pack pages) | OK (HTML) | License verification (CC0 / QAL) and download-link discovery |
| opengameart.org | OK | Official uploads by Quaternius and Kenney accounts + community CC0/CC BY assets |
| github.com (git clone of public repos) | OK | KayKit official repos, Scitizia People, Vuena characters |
| itch.io (kaylousberg / quaternius / dreamerh) | OK (free/no-payment option) | KayKit Animations, Forest, Spooktober, Mixed Bags; Quaternius Universal Base Characters, Downtown City MegaKit, Farm Buildings; DreamKit Monsters (free) |
| api.polyhaven.com / dl.polyhaven.org / cdn.polyhaven.com | OK | Curated CC0 models, textures, HDRIs, thumbnails |
| kaylousberg.com | OK | KayKit license/preview verification |

## Sources that failed or were excluded

| Source | Status | Reason |
|---|---|---|
| Quaternius official Google Drive folders (all packs, incl. Animated Men, Animated Women, Ultimate Monsters, Zombie Apocalypse Kit, Ultimate Modular Men/Women, Ultimate Animated Animals, Ultimate Furniture, glTF exports of the Ultimate Animated Character Pack) | DOWNLOAD_FAILED | Folder listing worked, but every file request returned Google Drive "Quota exceeded" (also for small License.txt files). Not retried in a loop. Packs that Quaternius also publishes on OpenGameArt/itch.io were taken from there instead. |
| kenney.nl direct downloads | DOWNLOAD_FAILED | HTTP 403 from the site for automated requests. Kenney's official OpenGameArt uploads (CC0) were used instead (some are older versions than kenney.nl; e.g. no "Mini Market" beyond Mini Shop 2.1). |
| Poly Pizza | DOWNLOAD_FAILED | Cloudflare browser challenge (HTTP 403, cf-mitigated: challenge). Not bypassed. Most Poly Pizza low-poly models are by Quaternius/Kenney, which were acquired from their official channels. |
| Sketchfab | NOT_ATTEMPTED | Downloads require a logged-in account; no credentials requested per brief. |
| KayKit Mystery Monthly Series 4/5/6, DreamKit Pastel City / Witch's Brew / Pumpkin Party | EXCLUDED_PAID | Paid packs (itch.io returned "you must buy this game to download"). |
| DreamKit Everyday Interiors (OFFICE) | EXCLUDED_LICENSE | No free upload listed and license text forbids standalone redistribution; not CC0. |
| Quaternius Bestiary - Dungeon Monsters Kit, Characters - Fantasy Races | LICENSE_REVIEW_REQUIRED | Published under "QAL" (Quaternius Asset License), not CC0; excluded until reviewed. |
| OpenGameArt CC BY-SA only items (Zombie Survivor, Flare NPCs, Cartoon Helicopter, Roach) | EXCLUDED_LICENSE | Share-alike only; excluded to keep the library CC0/CC BY. |

## Packs in the library

| Pack code | Pack | Creator | Official page | Acquired from | Method | Files |
|---|---|---|---|---|---|---|
| DK-MONSTERS | DreamKit Character Pack: Monsters (FREE version) | DreamerH (DreamKit) | https://dreamerh.itch.io/dreamkit-character-pack-monsters | https://dreamerh.itch.io/dreamkit-character-pack-monsters | Official itch.io free download (no-payment option) | 5 |
| KK-ADVENT | Character Pack: Adventurers 1.0 | Kay Lousberg (KayKit) | https://kaylousberg.com/game-assets | https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Adventures-1.0 @ 672074b73ba276876a19e8816ecdc5241817ab47 | Official GitHub repository (git clone --depth 1) | 33 |
| KK-ANIMS | Character Animations 1.1 (free) | Kay Lousberg (KayKit) | https://kaylousberg.itch.io/kaykit-character-animations | https://kaylousberg.itch.io/kaykit-character-animations | Official itch.io free download (no-payment option) | 16 |
| KK-CITY | City Builder Bits 1.0 | Kay Lousberg (KayKit) | https://kaylousberg.com/game-assets | https://github.com/KayKit-Game-Assets/KayKit-City-Builder-Bits-1.0 @ 63976910ca04d16f0fc531b9c614244be8128713 | Official GitHub repository (git clone --depth 1) | 41 |
| KK-DUNGEON | Dungeon Remastered 1.0 | Kay Lousberg (KayKit) | https://kaylousberg.com/game-assets | https://github.com/KayKit-Game-Assets/KayKit-Dungeon-Remastered-1.0 @ b0ca9bd96a8072ab36a3a5464f00ed1e06a16d07 | Official GitHub repository (git clone --depth 1) | 203 |
| KK-FOREST | Forest Nature Pack 1.0 (free) | Kay Lousberg (KayKit) | https://kaylousberg.itch.io/kaykit-forest | https://kaylousberg.itch.io/kaykit-forest | Official itch.io free download (no-payment option) | 105 |
| KK-FURN | Furniture Bits 1.0 | Kay Lousberg (KayKit) | https://kaylousberg.com/game-assets | https://github.com/KayKit-Game-Assets/KayKit-Furniture-Bits-1.0 @ 96d5930a8dbdb363409bbc2d3341718b00e17c9c | Official GitHub repository (git clone --depth 1) | 53 |
| KK-HALLOW | Halloween Bits 1.0 | Kay Lousberg (KayKit) | https://kaylousberg.com/game-assets | https://github.com/KayKit-Game-Assets/KayKit-Halloween-Bits-1.0 @ 6dc69bf6b2fa766a985754f35ec6a0324090e6c6 | Official GitHub repository (git clone --depth 1) | 63 |
| KK-MIXBAG1 | Mixed Bag 1 (free) | Kay Lousberg (KayKit) | https://kaylousberg.itch.io/mixed-bag-1 | https://kaylousberg.itch.io/mixed-bag-1 | Official itch.io free download (no-payment option) | 41 |
| KK-MIXBAG2 | Mixed Bag 2 (free) | Kay Lousberg (KayKit) | https://kaylousberg.itch.io/mixed-bag-2 | https://kaylousberg.itch.io/mixed-bag-2 | Official itch.io free download (no-payment option) | 30 |
| KK-RESTO | Restaurant Bits 1.0 | Kay Lousberg (KayKit) | https://kaylousberg.com/game-assets | https://github.com/KayKit-Game-Assets/KayKit-Restaurant-Bits-1.0 @ 153c8a7535b48237854cb54ff6890679f8c574d1 | Official GitHub repository (git clone --depth 1) | 144 |
| KK-SKEL | Character Pack: Skeletons 1.0 | Kay Lousberg (KayKit) | https://kaylousberg.com/game-assets | https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Skeletons-1.0 @ 15b62b9bad122f72926c10fb14d622c73819fa54 | Official GitHub repository (git clone --depth 1) | 17 |
| KK-SPOOK | Spooktober Seasonal Pack 1.1 (legacy) | Kay Lousberg (KayKit) | https://kaylousberg.itch.io/kaykit-spooktober | https://kaylousberg.itch.io/kaykit-spooktober | Official itch.io free download (no-payment option) | 48 |
| KN-ANIMCHAR | Animated Characters 1/2/3 (shared rig + skins) | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/animated-characters-1 | OpenGameArt official upload (direct file download) | 4 |
| KN-BLOCKY | Blocky Characters 2.0 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/blocky-characters | OpenGameArt official upload (direct file download) | 18 |
| KN-BUILDING | Building Kit | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/building-kit | OpenGameArt official upload (direct file download) | 79 |
| KN-CARS | Car Kit 3.1 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/car-kit | OpenGameArt official upload (direct file download) | 50 |
| KN-CAVE | Modular Cave Kit 1.0 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/modular-cave-kit | OpenGameArt official upload (direct file download) | 40 |
| KN-CITYCOM | City Kit (Commercial) 2.1 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/city-kit-commercial | OpenGameArt official upload (direct file download) | 41 |
| KN-CITYIND | City Kit (Industrial) 2.0 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/city-kit-industrial | OpenGameArt official upload (direct file download) | 37 |
| KN-CUBEPETS | Cube Pets 1.0 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/cube-pets | OpenGameArt official upload (direct file download) | 15 |
| KN-DUNGEON | Modular Dungeon Kit 2.0 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/modular-dungeon-kit | OpenGameArt official upload (direct file download) | 39 |
| KN-FACTORY | Factory Kit 3.0 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/factory-kit | OpenGameArt official upload (direct file download) | 143 |
| KN-FOOD | Food Kit | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/food-kit | OpenGameArt official upload (direct file download) | 200 |
| KN-FURN | Furniture Kit (legacy FBX) | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/furniture-kit | OpenGameArt official upload (direct file download) | 120 |
| KN-GRAVE | Graveyard Kit 5.0 | Kenney (kenney.nl) | https://kenney.nl/assets/graveyard-kit | https://opengameart.org/content/graveyard-kit | OpenGameArt official upload (direct file download) | 91 |
| KN-MINICHAR | Mini Characters 2.0 | Kenney (kenney.nl) | https://kenney.nl/assets/mini-characters | https://opengameart.org/content/mini-characters | OpenGameArt official upload (direct file download) | 43 |
| KN-MINIDUN | Mini Dungeon 2.0 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/mini-dungeon | OpenGameArt official upload (direct file download) | 30 |
| KN-MINIFOR | Mini Forest 1.0 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/mini-forest | OpenGameArt official upload (direct file download) | 22 |
| KN-MINISHOP | Mini Shop 2.1 (mini market) | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/mini-shop | OpenGameArt official upload (direct file download) | 30 |
| KN-MODBLD | Modular Buildings | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/modular-buildings | OpenGameArt official upload (direct file download) | 108 |
| KN-NATURE | Nature Kit 2.1 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/nature-kit | OpenGameArt official upload (direct file download) | 329 |
| KN-RETROURB | Retro Urban Kit | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/retro-urban-kit | OpenGameArt official upload (direct file download) | 124 |
| KN-ROADS | City Kit (Roads) 2.2 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/city-kit-roads | OpenGameArt official upload (direct file download) | 95 |
| KN-SUBURB | City Kit (Suburban) 2.0 | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/city-kit-suburban | OpenGameArt official upload (direct file download) | 40 |
| KN-SURVIVAL | Survival Kit | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/survival-kit | OpenGameArt official upload (direct file download) | 80 |
| KN-TRAIN | Train Kit | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/train-kit | OpenGameArt official upload (direct file download) | 103 |
| KN-WATERCRAFT | Watercraft Kit | Kenney (kenney.nl) | https://opengameart.org/users/kenney | https://opengameart.org/content/watercraft-kit | OpenGameArt official upload (direct file download) | 46 |
| PH | Poly Haven models (curated) | Poly Haven contributors | https://polyhaven.com/models | https://api.polyhaven.com (glTF 1k files) | Official Poly Haven public API + dl.polyhaven.org | 83 |
| QT-AHUMAN | Animated Human | Quaternius | https://quaternius.com/packs/animatedman.html | https://opengameart.org/content/animated-human-low-poly | OpenGameArt official upload (direct file download) | 1 |
| QT-ANIM1 | Animals Pack | Quaternius | https://quaternius.com/ | https://opengameart.org/content/5-low-poly-animals | OpenGameArt official upload (direct file download) | 5 |
| QT-ANIM2 | Animal Pack Vol.2 | Quaternius | https://quaternius.com/packs/ultimateanimatedanimals.html | https://opengameart.org/content/animated-animales-low-poly | OpenGameArt official upload (direct file download) | 5 |
| QT-BLD1 | Buildings Pack | Quaternius | https://quaternius.com/packs/buildings.html | https://opengameart.org/content/lowpoly-buildings | OpenGameArt official upload (direct file download) | 10 |
| QT-CARS1 | Car Pack (vol.1) | Quaternius | https://quaternius.com/packs/cars.html | https://opengameart.org/content/low-poly-cars-0 | OpenGameArt official upload (direct file download) | 3 |
| QT-CARS2 | Car Pack (vol.2) | Quaternius | https://quaternius.com/packs/cars.html | https://opengameart.org/content/lowpoly-cars | OpenGameArt official upload (direct file download) | 6 |
| QT-CROPS | Nature Crops Pack (Jan 2020) | Quaternius | https://quaternius.com/packs/ultimatecrops.html | https://opengameart.org/content/lowpoly-crops-pack | OpenGameArt official upload (direct file download) | 102 |
| QT-CUTEMON | Cute Animated Monsters (Aug 2020) | Quaternius | https://quaternius.com/packs/cutemonsters.html | https://opengameart.org/content/textured-cute-monster-pack | OpenGameArt official upload (direct file download) | 21 |
| QT-DOWNTOWN | Downtown City MegaKit [Standard] | Quaternius | https://quaternius.com/packs/downtowncitymegakit.html | https://quaternius.itch.io/downtown-city-megakit | Official itch.io free download (no-payment option) | 153 |
| QT-DUNGEON | Modular Dungeon (May 2019) | Quaternius | https://quaternius.com/packs/modulardungeon.html | https://opengameart.org/content/lowpoly-modular-dungeon-pack | OpenGameArt official upload (direct file download) | 48 |
| QT-FARMANI | Farm Animals | Quaternius | https://quaternius.com/packs/farmanimal.html | https://opengameart.org/content/lowpoly-animated-farm-animal-pack | OpenGameArt official upload (direct file download) | 7 |
| QT-FARMBLD | Farm Buildings | Quaternius | https://quaternius.com/packs/farmbuildings.html | https://quaternius.itch.io/lowpoly-farm-buildings | Official itch.io free download (no-payment option) | 13 |
| QT-FISH | Animated Fish Pack | Quaternius | https://quaternius.com/packs/animatedfish.html | https://opengameart.org/content/animated-fish | OpenGameArt official upload (direct file download) | 7 |
| QT-FOOD | Ultimate Food Pack (Oct 2019) | Quaternius | https://quaternius.com/packs/ultimatefood.html | https://opengameart.org/content/low-poly-food-pack | OpenGameArt official upload (direct file download) | 103 |
| QT-FPROPS | Fantasy Props MegaKit [Standard] | Quaternius | https://quaternius.com/packs/fantasypropsmegakit.html | https://opengameart.org/content/fantasy-props-megakit | OpenGameArt official upload (direct file download) | 94 |
| QT-FURN1 | Furniture Pack | Quaternius | https://quaternius.com/packs/furniture.html | https://opengameart.org/content/furniture-low-poly | OpenGameArt official upload (direct file download) | 23 |
| QT-FURN2 | Furniture Pack Vol.2 | Quaternius | https://quaternius.com/packs/furniture.html | https://opengameart.org/content/low-poly-furniture-1 | OpenGameArt official upload (direct file download) | 8 |
| QT-HOUSEINT | Ultimate House Interior Pack (Jun 2020) | Quaternius | https://quaternius.com/packs/ultimatehomeinterior.html | https://opengameart.org/content/lowpoly-house-interior-pack | OpenGameArt official upload (direct file download) | 123 |
| QT-MEDVIL | Medieval Village MegaKit [Standard] | Quaternius | https://quaternius.com/packs/medievalvillagemegakit.html | https://opengameart.org/content/medieval-village-megakit | OpenGameArt official upload (direct file download) | 176 |
| QT-MONST | Animated Monster Pack | Quaternius | https://quaternius.com/packs/animatedmonster.html | https://opengameart.org/content/lowpoly-animated-monsters | OpenGameArt official upload (direct file download) | 4 |
| QT-NATMEGA | Stylized Nature MegaKit [Standard] | Quaternius | https://quaternius.com/packs/stylizednaturemegakit.html | https://opengameart.org/content/stylized-nature-megakit | OpenGameArt official upload (direct file download) | 68 |
| QT-NATURE | Ultimate Nature Pack (Jun 2019) | Quaternius | https://quaternius.com/packs/ultimatenature.html | https://opengameart.org/content/low-poly-nature-pack-1 | OpenGameArt official upload (direct file download) | 150 |
| QT-POSED | Posed Background Characters | Quaternius | https://quaternius.com/packs/backgroundposedhumans.html | https://opengameart.org/content/lowpoly-posed-humans | OpenGameArt official upload (direct file download) | 28 |
| QT-RPGCHAR | RPG Characters (Nov 2020) | Quaternius | https://quaternius.com/packs/rpgcharacters.html | https://opengameart.org/content/lowpoly-rpg-characters | OpenGameArt official upload (direct file download) | 12 |
| QT-SCIESS | Sci-Fi Essentials Kit | Quaternius | https://quaternius.com/packs/scifiessentialskit.html | https://opengameart.org/content/sci-fi-essentials-kit | OpenGameArt official upload (direct file download) | 37 |
| QT-SCIFI | Modular Sci-Fi MegaKit [Standard] | Quaternius | https://quaternius.com/packs/modularscifimegakit.html | https://opengameart.org/content/modular-sci-fi-megakit | OpenGameArt official upload (direct file download) | 162 |
| QT-SHIPS | Ships | Quaternius | https://quaternius.com/packs/ships.html | https://opengameart.org/content/lowpoly-ship-pack | OpenGameArt official upload (direct file download) | 6 |
| QT-STREET | Modular Street Pack | Quaternius | https://quaternius.com/packs/modularstreets.html | https://opengameart.org/content/lowpoly-modular-street-pack | OpenGameArt official upload (direct file download) | 25 |
| QT-SURVIVAL | Survival Pack (Sep 2020) | Quaternius | https://quaternius.com/packs/survival.html | https://opengameart.org/content/lowpoly-survival-pack | OpenGameArt official upload (direct file download) | 53 |
| QT-TEXBLD | Ultimate Textured Building Pack (Dec 2019) | Quaternius | https://quaternius.com/packs/ultimatetexturedbuildings.html | https://opengameart.org/content/lowpoly-buildings-pack | OpenGameArt official upload (direct file download) | 76 |
| QT-TRANSIT | Public Transport | Quaternius | https://quaternius.com/packs/publictransport.html | https://opengameart.org/content/lowpoly-public-transport | OpenGameArt official upload (direct file download) | 12 |
| QT-TREES | Textured Stylized Trees (May 2020) | Quaternius | https://quaternius.com/packs/stylizedtree.html | https://opengameart.org/content/lowpoly-textured-trees | OpenGameArt official upload (direct file download) | 45 |
| QT-UACP | Ultimate Animated Character Pack (Nov 2019) | Quaternius | https://quaternius.com/packs/ultimatedanimatedcharacter.html | https://opengameart.org/content/animated-characters-pack | OpenGameArt official upload (direct file download) | 52 |
| QT-UAL1 | Universal Animation Library [Standard] | Quaternius | https://quaternius.com/packs/universalanimationlibrary.html | https://opengameart.org/content/universal-animation-library | OpenGameArt official upload (direct file download) | 1 |
| QT-UAL2 | Universal Animation Library 2 [Standard] | Quaternius | https://quaternius.com/packs/universalanimationlibrary2.html | https://opengameart.org/content/universal-animation-library-2 | OpenGameArt official upload (direct file download) | 2 |
| QT-UBC | Universal Base Characters [Standard] | Quaternius | https://quaternius.com/packs/universalbasecharacters.html | https://quaternius.itch.io/universal-base-characters | Official itch.io free download (no-payment option) | 10 |
| GH-VUENA | Free Low-Poly Characters (8 blocky rigged characters) | Vuena (GitHub/itch.io) | https://github.com/Vuena/free-low-poly-characters-cc0 | https://github.com/Vuena/free-low-poly-characters-cc0 @ 860f5a0c1c8da4341dd019337f79d9ce2761d1ee | Official GitHub repository (git clone --depth 1) | 8 |
| OGA-HALLOWKIT | Low-Poly Halloween Kit | assetquest (OpenGameArt user) | https://opengameart.org/content/low-poly-halloween-kit | https://opengameart.org/content/low-poly-halloween-kit | OpenGameArt upload (direct file download) | 74 |
| OGA-BEAST | Beast 02 | atmostatic (OpenGameArt user) | https://opengameart.org/content/beast-02 | https://opengameart.org/content/beast-02 | OpenGameArt upload (direct file download) | 1 |
| OGA-RESCUEHELI | Rescue Helicopter (low poly) | brylie (OpenGameArt user) | https://opengameart.org/content/rescue-helicopter-low-poly | https://opengameart.org/content/rescue-helicopter-low-poly | OpenGameArt upload (direct file download) | 1 |
| OGA-WEREWOLF | LOW POLY WEREWOLF | byzmod3d (OpenGameArt user) | https://opengameart.org/content/low-poly-werewolf | https://opengameart.org/content/low-poly-werewolf | OpenGameArt upload (direct file download) | 2 |
| OGA-JETTY | Jetty | cheb-gonaz (OpenGameArt user) | https://opengameart.org/content/jetty | https://opengameart.org/content/jetty | OpenGameArt upload (direct file download) | 1 |
| OGA-HORRORMON | 3D Horror Game Monster | city-building-game-art (OpenGameArt user) | https://opengameart.org/content/3d-horror-game-monster | https://opengameart.org/content/3d-horror-game-monster | OpenGameArt upload (direct file download) | 6 |
| OGA-FISHBOAT | Fishing Boat - low poly | crookedmouth (OpenGameArt user) | https://opengameart.org/content/fishing-boat-low-poly | https://opengameart.org/content/fishing-boat-low-poly | OpenGameArt upload (direct file download) | 1 |
| OGA-HORRORMAP | Horror sci-fi 3d map kit | dogchicken (OpenGameArt user) | https://opengameart.org/content/horror-sci-fi-3d-map-kit | https://opengameart.org/content/horror-sci-fi-3d-map-kit | OpenGameArt upload (direct file download) | 15 |
| OGA-NECROPOLY | Free NecroPoly Graveyard Halloween Exterior Kit | emaceart (OpenGameArt user) | https://opengameart.org/content/free-necropoly-graveyard-halloween-exterior-kit | https://opengameart.org/content/free-necropoly-graveyard-halloween-exterior-kit | OpenGameArt upload (direct file download) | 75 |
| OGA-OCEANTRIO | Ocean Trio | fleurman (OpenGameArt user) | https://opengameart.org/content/ocean-trio | https://opengameart.org/content/ocean-trio | OpenGameArt upload (direct file download) | 1 |
| OGA-FIRSTAID | First Aid Kit 3D | ggbotnet (OpenGameArt user) | https://opengameart.org/content/first-aid-kit-3d | https://opengameart.org/content/first-aid-kit-3d | OpenGameArt upload (direct file download) | 1 |
| OGA-DIVEHELM | Divers Helmet | jerd (OpenGameArt user) | https://opengameart.org/content/divers-helmet | https://opengameart.org/content/divers-helmet | OpenGameArt upload (direct file download) | 1 |
| OGA-GHOSTLADY | Ghost lady model (UNTEXTURED) | kabrolkin (OpenGameArt user) | https://opengameart.org/content/ghost-lady-model-untextured | https://opengameart.org/content/ghost-lady-model-untextured | OpenGameArt upload (direct file download) | 1 |
| GH-SCITIZIA | Scitizia: People (55 low-poly characters) | kayquer (GitHub) / kkyqr (itch.io) | https://github.com/kayquer/scitizia-pessoas-64 | https://github.com/kayquer/scitizia-pessoas-64 @ a6e3d4f14851a95c4df51ba508bd9efd7275688d | Official GitHub repository (git clone --depth 1) | 55 |
| OGA-DOCKS | Modular Wooden Docks | loafbrr1 (OpenGameArt user) | https://opengameart.org/content/modular-wooden-docks | https://opengameart.org/content/modular-wooden-docks | OpenGameArt upload (direct file download) | 140 |
| OGA-HALLOWPROPS | Halloween Props | loafbrr1 (OpenGameArt user) | https://opengameart.org/content/halloween-props | https://opengameart.org/content/halloween-props | OpenGameArt upload (direct file download) | 127 |
| OGA-APOCBLD | 3D Apocalyptic Building / City (CC0) | majadroid (OpenGameArt user) | https://opengameart.org/content/3d-apocalyptic-building-city-cc0 | https://opengameart.org/content/3d-apocalyptic-building-city-cc0 | OpenGameArt upload (direct file download) | 10 |
| OGA-BONEGOLEM | Bone Golem | mophs (OpenGameArt user) | https://opengameart.org/content/bone-golem | https://opengameart.org/content/bone-golem | OpenGameArt upload (direct file download) | 2 |
| OGA-IMP | Imp | mophs (OpenGameArt user) | https://opengameart.org/content/imp-0 | https://opengameart.org/content/imp-0 | OpenGameArt upload (direct file download) | 1 |
| OGA-COFFIN | Coffin | paul-wortmann (OpenGameArt user) | https://opengameart.org/content/coffin-0 | https://opengameart.org/content/coffin-0 | OpenGameArt upload (direct file download) | 3 |
| OGA-VEHICLES | Free Low Poly Vehicles Pack | rgsdev (OpenGameArt user) | https://opengameart.org/content/free-low-poly-vehicles-pack | https://opengameart.org/content/free-low-poly-vehicles-pack | OpenGameArt upload (direct file download) | 21 |
| OGA-CITYZOMBIE | Male City Zombie, Ready for use in Game Engines. | rikindle3d (OpenGameArt user) | https://opengameart.org/content/male-city-zombie-ready-for-use-in-game-engines | https://opengameart.org/content/male-city-zombie-ready-for-use-in-game-engines | OpenGameArt upload (direct file download) | 12 |
| OGA-GHOST | Low Poly Ghost | robin-lamb (OpenGameArt user) | https://opengameart.org/content/low-poly-ghost-0 | https://opengameart.org/content/low-poly-ghost-0 | OpenGameArt upload (direct file download) | 1 |
| OGA-CEMETERY | Cemetery | savino (OpenGameArt user) | https://opengameart.org/content/cemetery | https://opengameart.org/content/cemetery | OpenGameArt upload (direct file download) | 6 |
| OGA-MOTO | fancy motorcycle | tehbucket (OpenGameArt user) | https://opengameart.org/content/fancy-motorcycle | https://opengameart.org/content/fancy-motorcycle | OpenGameArt upload (direct file download) | 1 |
| OGA-CZOMBIE | Cartoon Zombie Rigged | vinrax (OpenGameArt user) | https://opengameart.org/content/cartoon-zombie-rigged | https://opengameart.org/content/cartoon-zombie-rigged | OpenGameArt upload (direct file download) | 1 |
| OGA-HELI | Simple helicopter | whitaker (OpenGameArt user) | https://opengameart.org/content/simple-helicopter | https://opengameart.org/content/simple-helicopter | OpenGameArt upload (direct file download) | 1 |
| OGA-ROWBOAT | Simple Rowboat | willy56 (OpenGameArt user) | https://opengameart.org/content/simple-rowboat | https://opengameart.org/content/simple-rowboat | OpenGameArt upload (direct file download) | 1 |
| OGA-STONECOFFIN | Stone coffin | yughues (OpenGameArt user) | https://opengameart.org/content/stone-coffin | https://opengameart.org/content/stone-coffin | OpenGameArt upload (direct file download) | 1 |

Materials: Poly Haven textures/HDRIs (https://polyhaven.com, via public API), Kenney Retro Textures (Liminal) and Skyboxes (OpenGameArt, Kenney account).

Blender-only community downloads (Tier D, kept only in 10_Source_Archives) are listed under `unsupported` in AssetRegistry.json.
