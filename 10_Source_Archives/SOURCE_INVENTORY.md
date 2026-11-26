# Source Inventory

Generated 2026-11-26. Original downloads are **not** in this repo. This file lists where every asset came from and where more can be fetched. Machine-readable: `SOURCE_INVENTORY.json`.

## How to fetch

| Host | Method |
|---|---|
| opengameart.org | direct file links, no login |
| itch.io | free packs: POST <page>/file/<upload_id>?source=view_game&as_props=1 (csrf_token from page) -> {"url": signed CDN link}; paid packs return "you must buy" |
| github.com | git clone works for public repos |
| api.polyhaven.com | public API, send a normal User-Agent |
| quaternius Google Drive | listing works (embeddedfolderview?id=<folder>) but files returned "Quota exceeded" on 2026-11-26; may work later or from a browser |
| kenney.nl | HTTP 403 for automated clients; use OpenGameArt (Kenney account) or a browser |
| poly.pizza | Cloudflare challenge; browser only |
| sketchfab.com | requires login |

## Rules for adding assets

- Use only CC0 / CC BY (attribution) / explicitly commercial-OK licenses; skip CC BY-SA-only, QAL, NC, paid.
- Verify license on the page before use; record it in AssetRegistry.json.
- Prefer GLB/glTF; FBX 7.x; OBJ+MTL for static. .blend-only = unusable without Blender (excluded).
- Run the three.js load check before adding (see 13_Metadata/threejs_load_test.json format).

## A. Sources already used (127 downloads + 9 git repos + Poly Haven)

| Source | Pack | License | Status | Files in library | Formats in download | Page |
|---|---|---|---|---|---|---|
| community/3d-apocalyptic-building-city-cc0 | 3D Apocalyptic Building / City (CC0) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 10 | blend:1, fbx:10 | https://opengameart.org/content/3d-apocalyptic-building-city-cc0 |
| community/3d-horror-game-monster | 3D Horror Game Monster | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 6 | fbx:7 | https://opengameart.org/content/3d-horror-game-monster |
| community/adolescent-female-character | Adolescent Female Character | CC BY 3.0 (dual with CC BY-SA 3.0) | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/adolescent-female-character |
| community/adventure-kid | Adventure Kid | CC BY 3.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/adventure-kid |
| community/angler-man-3d | Angler Man 3D | CC BY 3.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:2 | https://opengameart.org/content/angler-man-3d |
| community/baby-rattle-0 | Baby Rattle | CC BY 3.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/baby-rattle-0 |
| community/bartender | Bartender | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/bartender |
| community/base-human-models-low-poly | Base Human Models (Low Poly) | CC BY 3.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/base-human-models-low-poly |
| community/beast-02 | Beast 02 | CC BY 3.0 | IN_LIBRARY | 1 | obj:1 | https://opengameart.org/content/beast-02 |
| community/bone-golem | Bone Golem | CC BY 3.0 | IN_LIBRARY | 2 | obj:3 | https://opengameart.org/content/bone-golem |
| community/cartoon-zombie-rigged | Cartoon Zombie Rigged | CC BY 3.0 | IN_LIBRARY | 1 | blend:1, dae:1, fbx:1 | https://opengameart.org/content/cartoon-zombie-rigged |
| community/cemetery | Cemetery | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 6 | obj:6 | https://opengameart.org/content/cemetery |
| community/chicken-animated | Chicken (animated) | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/chicken-animated |
| community/coffin-0 | Coffin | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 3 | blend:1, obj:3 | https://opengameart.org/content/coffin-0 |
| community/creature-rat | Creature: Rat | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/creature-rat |
| community/divers-helmet | Divers Helmet | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | obj:1 | https://opengameart.org/content/divers-helmet |
| community/emotional-ghosts | Emotional Ghosts | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:2 | https://opengameart.org/content/emotional-ghosts |
| community/fancy-motorcycle | fancy motorcycle | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | blend:1, obj:1 | https://opengameart.org/content/fancy-motorcycle |
| community/first-aid-kit-3d | First Aid Kit 3D | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | blend:1, obj:1 | https://opengameart.org/content/first-aid-kit-3d |
| community/fishing-boat-low-poly | Fishing Boat - low poly | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | blend:2, dae:2, fbx:1, obj:1 | https://opengameart.org/content/fishing-boat-low-poly |
| community/forest-monster | Forest Monster | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/forest-monster |
| community/free-low-poly-vehicles-pack | Free Low Poly Vehicles Pack | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 21 | fbx:22 | https://opengameart.org/content/free-low-poly-vehicles-pack |
| community/free-necropoly-graveyard-halloween-exterior-kit | Free NecroPoly Graveyard Halloween Exterior Kit | CC BY 4.0 | IN_LIBRARY | 75 | fbx:75 | https://opengameart.org/content/free-necropoly-graveyard-halloween-exterior-kit |
| community/ghost-4 | Ghost | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/ghost-4 |
| community/ghost-lady-model-untextured | Ghost lady model (UNTEXTURED) | CC BY 4.0 | IN_LIBRARY | 1 | dae:1, fbx:1 | https://opengameart.org/content/ghost-lady-model-untextured |
| community/graveyard-and-crypt | Graveyard and Crypt | CC BY 3.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:2 | https://opengameart.org/content/graveyard-and-crypt |
| community/halloween-props | Halloween Props | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 127 | blend:1, fbx:250, gltf:2 | https://opengameart.org/content/halloween-props |
| community/horror-sci-fi-3d-map-kit | Horror sci-fi 3d map kit | CC BY 3.0 | IN_LIBRARY | 15 | obj:15 | https://opengameart.org/content/horror-sci-fi-3d-map-kit |
| community/imp-0 | Imp | CC BY 3.0 | IN_LIBRARY | 1 | blend:1, obj:1 | https://opengameart.org/content/imp-0 |
| community/jetty | Jetty | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | fbx:1 | https://opengameart.org/content/jetty |
| community/low-poly-ghost | Low poly ghost | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/low-poly-ghost |
| community/low-poly-ghost-0 | Low Poly Ghost | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | blend:1, glb:1 | https://opengameart.org/content/low-poly-ghost-0 |
| community/low-poly-halloween-kit | Low-Poly Halloween Kit | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 74 | fbx:74 | https://opengameart.org/content/low-poly-halloween-kit |
| community/low-poly-shark | Low-poly Shark | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/low-poly-shark |
| community/low-poly-werewolf | LOW POLY WEREWOLF | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 2 | fbx:2 | https://opengameart.org/content/low-poly-werewolf |
| community/lowpoly-boy-1 | Lowpoly Boy 1 | CC BY 4.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/lowpoly-boy-1 |
| community/lowpoly-girl-1 | Lowpoly Girl 1 | CC BY 4.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/lowpoly-girl-1 |
| community/lowpolykid | Lowpoly_Kid | CC BY 4.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/lowpolykid |
| community/male-city-zombie-ready-for-use-in-game-engines | Male City Zombie, Ready for use in Game Engines. | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 12 | fbx:12 | https://opengameart.org/content/male-city-zombie-ready-for-use-in-game-engines |
| community/modular-rpg-characters | Modular RPG Characters | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:4 | https://opengameart.org/content/modular-rpg-characters |
| community/modular-wooden-docks | Modular Wooden Docks | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 140 | fbx:278, glb:1 | https://opengameart.org/content/modular-wooden-docks |
| community/night-demon | Night Demon | CC BY 3.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:2 | https://opengameart.org/content/night-demon |
| community/ocean-trio | Ocean Trio | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | fbx:1 | https://opengameart.org/content/ocean-trio |
| community/old-city-couple | Old City Couple | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/old-city-couple |
| community/patrol-boat | Patrol boat | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/patrol-boat |
| community/rescue-helicopter-low-poly | Rescue Helicopter (low poly) | CC BY 4.0 | IN_LIBRARY | 1 | gltf:1 | https://opengameart.org/content/rescue-helicopter-low-poly |
| community/shark-low-poly | Shark (low poly) | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/shark-low-poly |
| community/simple-helicopter | Simple helicopter | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | fbx:1 | https://opengameart.org/content/simple-helicopter |
| community/simple-rowboat | Simple Rowboat | CC BY 4.0 | IN_LIBRARY | 1 | obj:1 | https://opengameart.org/content/simple-rowboat |
| community/simple-wood-boat | Simple Wood Boat | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/simple-wood-boat |
| community/skeleton-with-rig | Skeleton with rig | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/skeleton-with-rig |
| community/stone-coffin | Stone coffin | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | fbx:1, obj:1 | https://opengameart.org/content/stone-coffin |
| community/thin-zombie-awake-zombie-asset | Thin Zombie [ Awake Zombie Asset ] | CC BY 3.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/thin-zombie-awake-zombie-asset |
| community/undead-male | Undead male | CC BY 3.0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/undead-male |
| community/undead-squirrel-animated | Undead Squirrel (ANIMATED) | CC0 | UNSUPPORTED_BLEND_ONLY | 0 | blend:1 | https://opengameart.org/content/undead-squirrel-animated |
| community/werewolf-0 | Werewolf | CC0 | DOWNLOADED_NOT_USED | 0 | dae:1 | https://opengameart.org/content/werewolf-0 |
| dreamkit/itch-dreamkit-character-pack-monsters | DreamKit Character Pack: Monsters (FREE version) | CC0 1.0 Universal (Public Domain Dedication) (stated in itch.io description: free for personal and commercial use, no attribution required) | IN_LIBRARY | 5 | blend:1, fbx:5 | https://dreamerh.itch.io/dreamkit-character-pack-monsters |
| kaykit/itch-kaykit-character-animations | Character Animations 1.1 (free) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 16 | fbx:16, glb:16 | https://kaylousberg.itch.io/kaykit-character-animations |
| kaykit/itch-kaykit-forest | Forest Nature Pack 1.0 (free) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 105 | fbx:210, gltf:105, obj:105 | https://kaylousberg.itch.io/kaykit-forest |
| kaykit/itch-kaykit-spooktober | Spooktober Seasonal Pack 1.1 (legacy) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 48 | dae:48, fbx:48, glb:46, gltf:2, obj:56 | https://kaylousberg.itch.io/kaykit-spooktober |
| kaykit/itch-mixed-bag-1 | Mixed Bag 1 (free) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 41 | fbx:82, gltf:41, obj:69 | https://kaylousberg.itch.io/mixed-bag-1 |
| kaykit/itch-mixed-bag-2 | Mixed Bag 2 (free) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 30 | fbx:60, gltf:30, obj:41 | https://kaylousberg.itch.io/mixed-bag-2 |
| kenney/animated-characters-1 | Animated Characters 1/2/3 (shared rig + skins) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 4 | fbx:4 | https://opengameart.org/content/animated-characters-1 |
| kenney/animated-characters-2 | Animated Characters 1/2/3 (shared rig + skins) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 4 | fbx:4 | https://opengameart.org/content/animated-characters-2 |
| kenney/animated-characters-3 | Animated Characters 1/2/3 (shared rig + skins) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 4 | fbx:4 | https://opengameart.org/content/animated-characters-3 |
| kenney/blocky-characters | Blocky Characters 2.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 18 | fbx:18, glb:18, obj:18 | https://opengameart.org/content/blocky-characters |
| kenney/building-kit | Building Kit | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 79 | fbx:79, glb:79, obj:79 | https://opengameart.org/content/building-kit |
| kenney/car-kit | Car Kit 3.1 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 50 | fbx:50, glb:50, obj:50 | https://opengameart.org/content/car-kit |
| kenney/city-kit-commercial | City Kit (Commercial) 2.1 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 41 | fbx:41, glb:41, obj:41 | https://opengameart.org/content/city-kit-commercial |
| kenney/city-kit-industrial | City Kit (Industrial) 2.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 37 | fbx:37, glb:37, obj:37 | https://opengameart.org/content/city-kit-industrial |
| kenney/city-kit-roads | City Kit (Roads) 2.2 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 95 | fbx:95, glb:95, obj:95 | https://opengameart.org/content/city-kit-roads |
| kenney/city-kit-suburban | City Kit (Suburban) 2.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 40 | fbx:40, glb:40, obj:40 | https://opengameart.org/content/city-kit-suburban |
| kenney/cube-pets | Cube Pets 1.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 15 | fbx:15, glb:15, obj:15 | https://opengameart.org/content/cube-pets |
| kenney/factory-kit | Factory Kit 3.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 143 | fbx:143, glb:143, obj:143 | https://opengameart.org/content/factory-kit |
| kenney/food-kit | Food Kit | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 200 | fbx:200, glb:200, obj:200 | https://opengameart.org/content/food-kit |
| kenney/furniture-kit | Furniture Kit (legacy FBX) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 120 | fbx:120, obj:120 | https://opengameart.org/content/furniture-kit |
| kenney/graveyard-kit | Graveyard Kit 5.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 91 | fbx:91, glb:91, obj:91 | https://opengameart.org/content/graveyard-kit |
| kenney/mini-characters | Mini Characters 2.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 43 | fbx:43, glb:43, obj:43 | https://opengameart.org/content/mini-characters |
| kenney/mini-dungeon | Mini Dungeon 2.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 30 | fbx:30, glb:30, obj:30 | https://opengameart.org/content/mini-dungeon |
| kenney/mini-forest | Mini Forest 1.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 22 | fbx:22, glb:22, obj:22 | https://opengameart.org/content/mini-forest |
| kenney/mini-shop | Mini Shop 2.1 (mini market) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 30 | fbx:30, glb:30, obj:30 | https://opengameart.org/content/mini-shop |
| kenney/modular-buildings | Modular Buildings | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 108 | fbx:108, glb:108, obj:108 | https://opengameart.org/content/modular-buildings |
| kenney/modular-cave-kit | Modular Cave Kit 1.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 40 | fbx:40, glb:40, obj:40 | https://opengameart.org/content/modular-cave-kit |
| kenney/modular-dungeon-kit | Modular Dungeon Kit 2.0 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 39 | fbx:39, glb:39, obj:39 | https://opengameart.org/content/modular-dungeon-kit |
| kenney/nature-kit | Nature Kit 2.1 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 329 | dae:329, fbx:329, glb:329, obj:329 | https://opengameart.org/content/nature-kit |
| kenney/retro-textures-liminal | Retro Textures Liminal | CC0 | DOWNLOADED_NOT_USED | 0 |  | https://opengameart.org/content/retro-textures-liminal |
| kenney/retro-urban-kit | Retro Urban Kit | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 124 | fbx:124, glb:124, obj:124 | https://opengameart.org/content/retro-urban-kit |
| kenney/skyboxes-1 | Skyboxes | CC0 | DOWNLOADED_NOT_USED | 0 |  | https://opengameart.org/content/skyboxes-1 |
| kenney/survival-kit | Survival Kit | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 80 | fbx:80, glb:80, obj:80 | https://opengameart.org/content/survival-kit |
| kenney/train-kit | Train Kit | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 103 | fbx:103, glb:103, obj:103 | https://opengameart.org/content/train-kit |
| kenney/watercraft-kit | Watercraft Kit | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 46 | fbx:46, glb:46, obj:46 | https://opengameart.org/content/watercraft-kit |
| quaternius/5-low-poly-animals | Animals Pack | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 5 | blend:5, fbx:5, obj:5 | https://opengameart.org/content/5-low-poly-animals |
| quaternius/animated-animales-low-poly | Animal Pack Vol.2 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 5 | blend:5, fbx:5, obj:5 | https://opengameart.org/content/animated-animales-low-poly |
| quaternius/animated-characters-pack | Ultimate Animated Character Pack (Nov 2019) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 52 | blend:52, fbx:52, obj:52 | https://opengameart.org/content/animated-characters-pack |
| quaternius/animated-fish | Animated Fish Pack | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 7 | blend:7, fbx:7, obj:7 | https://opengameart.org/content/animated-fish |
| quaternius/animated-human-low-poly | Animated Human | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | blend:1, dae:1, fbx:1, obj:1 | https://opengameart.org/content/animated-human-low-poly |
| quaternius/fantasy-props-megakit | Fantasy Props MegaKit [Standard] | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 94 | fbx:94, gltf:94, obj:94 | https://opengameart.org/content/fantasy-props-megakit |
| quaternius/furniture-low-poly | Furniture Pack | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 23 | blend:23, fbx:23, obj:23 | https://opengameart.org/content/furniture-low-poly |
| quaternius/itch-downtown-city-megakit | Downtown City MegaKit [Standard] | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 153 | fbx:306, gltf:153 | https://quaternius.itch.io/downtown-city-megakit |
| quaternius/itch-lowpoly-farm-buildings | Farm Buildings | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 13 | blend:13, fbx:13, obj:13 | https://quaternius.itch.io/lowpoly-farm-buildings |
| quaternius/itch-universal-base-characters | Universal Base Characters [Standard] | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 10 | fbx:26, gltf:18 | https://quaternius.itch.io/universal-base-characters |
| quaternius/low-poly-cars-0 | Car Pack (vol.1) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 3 | blend:6, obj:9 | https://opengameart.org/content/low-poly-cars-0 |
| quaternius/low-poly-food-pack | Ultimate Food Pack (Oct 2019) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 103 | blend:103, fbx:103, obj:103 | https://opengameart.org/content/low-poly-food-pack |
| quaternius/low-poly-furniture-1 | Furniture Pack Vol.2 | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 8 | blend:8, obj:8 | https://opengameart.org/content/low-poly-furniture-1 |
| quaternius/low-poly-nature-pack-1 | Ultimate Nature Pack (Jun 2019) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 150 | blend:150, fbx:150, obj:150 | https://opengameart.org/content/low-poly-nature-pack-1 |
| quaternius/lowpoly-animated-farm-animal-pack | Farm Animals | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 7 | blend:7, fbx:7, obj:7 | https://opengameart.org/content/lowpoly-animated-farm-animal-pack |
| quaternius/lowpoly-animated-monsters | Animated Monster Pack | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 4 | blend:4, fbx:4, obj:4 | https://opengameart.org/content/lowpoly-animated-monsters |
| quaternius/lowpoly-buildings | Buildings Pack | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 10 | blend:10, fbx:10, obj:10 | https://opengameart.org/content/lowpoly-buildings |
| quaternius/lowpoly-buildings-pack | Ultimate Textured Building Pack (Dec 2019) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 76 | blend:102, fbx:102, obj:102 | https://opengameart.org/content/lowpoly-buildings-pack |
| quaternius/lowpoly-cars | Car Pack (vol.2) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 6 | blend:6, fbx:6, obj:6 | https://opengameart.org/content/lowpoly-cars |
| quaternius/lowpoly-crops-pack | Nature Crops Pack (Jan 2020) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 102 | blend:102, fbx:102, obj:102 | https://opengameart.org/content/lowpoly-crops-pack |
| quaternius/lowpoly-house-interior-pack | Ultimate House Interior Pack (Jun 2020) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 123 | blend:123, fbx:123, obj:123 | https://opengameart.org/content/lowpoly-house-interior-pack |
| quaternius/lowpoly-modular-dungeon-pack | Modular Dungeon (May 2019) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 48 | blend:48, fbx:48, obj:48 | https://opengameart.org/content/lowpoly-modular-dungeon-pack |
| quaternius/lowpoly-modular-street-pack | Modular Street Pack | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 25 | blend:25, fbx:25, obj:25 | https://opengameart.org/content/lowpoly-modular-street-pack |
| quaternius/lowpoly-posed-humans | Posed Background Characters | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 28 | blend:28, fbx:28, obj:28 | https://opengameart.org/content/lowpoly-posed-humans |
| quaternius/lowpoly-public-transport | Public Transport | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 12 | blend:12, fbx:12, obj:12 | https://opengameart.org/content/lowpoly-public-transport |
| quaternius/lowpoly-rpg-characters | RPG Characters (Nov 2020) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 12 | blend:11, fbx:12, obj:12 | https://opengameart.org/content/lowpoly-rpg-characters |
| quaternius/lowpoly-ship-pack | Ships | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 6 | blend:6, fbx:6, obj:6 | https://opengameart.org/content/lowpoly-ship-pack |
| quaternius/lowpoly-survival-pack | Survival Pack (Sep 2020) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 53 | blend:53, fbx:53, obj:53 | https://opengameart.org/content/lowpoly-survival-pack |
| quaternius/lowpoly-textured-trees | Textured Stylized Trees (May 2020) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 45 | blend:45, fbx:45, obj:45 | https://opengameart.org/content/lowpoly-textured-trees |
| quaternius/medieval-village-megakit | Medieval Village MegaKit [Standard] | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 176 | fbx:176, gltf:176, obj:176 | https://opengameart.org/content/medieval-village-megakit |
| quaternius/modular-sci-fi-megakit | Modular Sci-Fi MegaKit [Standard] | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 162 | fbx:378, gltf:191, obj:191 | https://opengameart.org/content/modular-sci-fi-megakit |
| quaternius/sci-fi-essentials-kit | Sci-Fi Essentials Kit | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 37 | fbx:74, gltf:37, obj:37 | https://opengameart.org/content/sci-fi-essentials-kit |
| quaternius/stylized-nature-megakit | Stylized Nature MegaKit [Standard] | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 68 | fbx:136, gltf:68, obj:68 | https://opengameart.org/content/stylized-nature-megakit |
| quaternius/textured-cute-monster-pack | Cute Animated Monsters (Aug 2020) | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 21 | blend:21, fbx:21, obj:21 | https://opengameart.org/content/textured-cute-monster-pack |
| quaternius/universal-animation-library | Universal Animation Library [Standard] | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 1 | fbx:2, glb:1 | https://opengameart.org/content/universal-animation-library |
| quaternius/universal-animation-library-2 | Universal Animation Library 2 [Standard] | CC0 1.0 Universal (Public Domain Dedication) | IN_LIBRARY | 2 | blend:1, fbx:2, glb:2 | https://opengameart.org/content/universal-animation-library-2 |

Direct file URLs, sizes and SHA-256 for every download are in `SOURCE_INVENTORY.json` → `acquired[].files`.

### Git repositories

- https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Adventures-1.0 @ `672074b73ba276876a19e8816ecdc5241817ab47` (CC0)
- https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Skeletons-1.0 @ `15b62b9bad122f72926c10fb14d622c73819fa54` (CC0)
- https://github.com/KayKit-Game-Assets/KayKit-City-Builder-Bits-1.0 @ `63976910ca04d16f0fc531b9c614244be8128713` (CC0)
- https://github.com/KayKit-Game-Assets/KayKit-Dungeon-Remastered-1.0 @ `b0ca9bd96a8072ab36a3a5464f00ed1e06a16d07` (CC0)
- https://github.com/KayKit-Game-Assets/KayKit-Furniture-Bits-1.0 @ `96d5930a8dbdb363409bbc2d3341718b00e17c9c` (CC0)
- https://github.com/KayKit-Game-Assets/KayKit-Halloween-Bits-1.0 @ `6dc69bf6b2fa766a985754f35ec6a0324090e6c6` (CC0)
- https://github.com/KayKit-Game-Assets/KayKit-Restaurant-Bits-1.0 @ `153c8a7535b48237854cb54ff6890679f8c574d1` (CC0)
- https://github.com/kayquer/scitizia-pessoas-64 @ `a6e3d4f14851a95c4df51ba508bd9efd7275688d` (CC0)
- https://github.com/Vuena/free-low-poly-characters-cc0 @ `860f5a0c1c8da4341dd019337f79d9ce2761d1ee` (CC0)

### Poly Haven (CC0)
Used: 126 items. Not yet used: {'models': 439, 'textures': 843, 'hdris': 985}. Full id lists with categories in the JSON (`polyhaven.not_used`).

## B. Candidates found but NOT downloaded

### B1. Official Quaternius / Kenney uploads on OpenGameArt (all CC0 unless stated)

| Slug | Title | Author | License | Type | Blend only |
|---|---|---|---|---|---|
| [4-trees-3-clouds-and-2-bushes](https://opengameart.org/content/4-trees-3-clouds-and-2-bushes) | 4 Trees 3 Clouds and 2 Bushes | quaternius | CC BY-SA (share-alike) | 3D Art |  |
| [5-low-poly-trees](https://opengameart.org/content/5-low-poly-trees) | 5 low poly trees | quaternius | CC0 | 3D Art |  |
| [animated-lowpoly-robot](https://opengameart.org/content/animated-lowpoly-robot) | Animated LowPoly Robot | quaternius | CC0 | 3D Art |  |
| [animated-mech-pack](https://opengameart.org/content/animated-mech-pack) | Animated Mech Pack | quaternius | CC0 | 3D Art |  |
| [blaster-kit](https://opengameart.org/content/blaster-kit) | Blaster Kit | kenney | CC0 | 3D Art |  |
| [brick-kit](https://opengameart.org/content/brick-kit) | Brick Kit | kenney | CC0 | 3D Art |  |
| [castle-kit](https://opengameart.org/content/castle-kit) | Castle Kit | kenney | CC0 | 3D Art |  |
| [coaster-kit](https://opengameart.org/content/coaster-kit) | Coaster Kit | kenney | CC0 | 3D Art |  |
| [fantasy-low-poly-trees-and-bushes](https://opengameart.org/content/fantasy-low-poly-trees-and-bushes) | Fantasy Low Poly trees and bushes | quaternius | CC0 | 3D Art |  |
| [fantasy-town-kit](https://opengameart.org/content/fantasy-town-kit) | Fantasy Town Kit | kenney | CC0 | 3D Art |  |
| [hexagon-kit](https://opengameart.org/content/hexagon-kit) | Hexagon Kit | kenney | CC0 | 3D Art |  |
| [holiday-kit](https://opengameart.org/content/holiday-kit) | Holiday Kit | kenney | CC0 | 3D Art |  |
| [low-poly-animated-guns](https://opengameart.org/content/low-poly-animated-guns) | Low Poly Animated Guns | quaternius | CC0 | 3D Art |  |
| [low-poly-desert-assets](https://opengameart.org/content/low-poly-desert-assets) | Low poly desert assets | quaternius | CC0 | 3D Art |  |
| [low-poly-guns](https://opengameart.org/content/low-poly-guns) | Low poly Guns | quaternius | CC0 | 3D Art |  |
| [low-poly-guns-pack](https://opengameart.org/content/low-poly-guns-pack) | Low Poly Guns Pack | quaternius | CC0 | 3D Art |  |
| [low-poly-houses](https://opengameart.org/content/low-poly-houses) | Low Poly Houses | quaternius | CC BY-SA (share-alike) | 3D Art |  |
| [low-poly-medieval-weapons](https://opengameart.org/content/low-poly-medieval-weapons) | Low poly medieval weapons | quaternius | CC0 | 3D Art |  |
| [low-poly-pirate-pack](https://opengameart.org/content/low-poly-pirate-pack) | Low poly pirate pack | quaternius | CC0 | 3D Art |  |
| [low-poly-rpg-pack](https://opengameart.org/content/low-poly-rpg-pack) | Low Poly RPG Pack | quaternius | CC0 | 3D Art |  |
| [low-poly-space-assets](https://opengameart.org/content/low-poly-space-assets) | Low poly space assets | quaternius | CC0 | 3D Art |  |
| [low-poly-spaceships](https://opengameart.org/content/low-poly-spaceships) | Low poly spaceships | quaternius | CC0 | 3D Art |  |
| [lowpoly-animated-knight](https://opengameart.org/content/lowpoly-animated-knight) | LowPoly Animated Knight | quaternius | CC0 | 3D Art |  |
| [lowpoly-medieval-buildings](https://opengameart.org/content/lowpoly-medieval-buildings) | LowPoly Medieval Buildings | quaternius | CC0 | 3D Art |  |
| [lowpoly-medieval-village-pack](https://opengameart.org/content/lowpoly-medieval-village-pack) | LowPoly Medieval Village Pack | quaternius | CC0 | 3D Art |  |
| [lowpoly-medieval-weapons](https://opengameart.org/content/lowpoly-medieval-weapons) | LowPoly Medieval Weapons | quaternius | CC0 | 3D Art |  |
| [lowpoly-modular-dungeon](https://opengameart.org/content/lowpoly-modular-dungeon) | LowPoly Modular Dungeon | quaternius | CC0 | 3D Art |  |
| [lowpoly-modular-sci-fi-environments](https://opengameart.org/content/lowpoly-modular-sci-fi-environments) | LowPoly Modular Sci-Fi Environments | quaternius | CC0 | 3D Art |  |
| [lowpoly-nature-pack](https://opengameart.org/content/lowpoly-nature-pack) | LowPoly Nature Pack | quaternius | CC0 | 3D Art |  |
| [lowpoly-rpg](https://opengameart.org/content/lowpoly-rpg) | LowPoly RPG | quaternius | CC0 | 3D Art |  |
| [lowpoly-spaceships-pack](https://opengameart.org/content/lowpoly-spaceships-pack) | LowPoly Spaceships Pack | quaternius | CC0 | 3D Art |  |
| [lowpoly-steampunk-turrets](https://opengameart.org/content/lowpoly-steampunk-turrets) | LowPoly Steampunk Turrets | quaternius | CC0 | 3D Art |  |
| [marble-kit](https://opengameart.org/content/marble-kit) | Marble Kit | kenney | CC0 | 3D Art |  |
| [mini-arcade](https://opengameart.org/content/mini-arcade) | Mini Arcade | kenney | CC0 | 3D Art |  |
| [mini-arena](https://opengameart.org/content/mini-arena) | Mini Arena | kenney | CC0 | 3D Art |  |
| [mini-skate](https://opengameart.org/content/mini-skate) | Mini Skate | kenney | CC0 | 3D Art |  |
| [minigolf-kit](https://opengameart.org/content/minigolf-kit) | Minigolf Kit | kenney | CC0 | 3D Art |  |
| [modular-space-kit](https://opengameart.org/content/modular-space-kit) | Modular Space Kit | kenney | CC0 | 3D Art |  |
| [pattern-pack-extra](https://opengameart.org/content/pattern-pack-extra) | Pattern Pack Extra | kenney | CC0 | Texture |  |
| [pirate-kit](https://opengameart.org/content/pirate-kit) | Pirate Kit | kenney | CC0 | 3D Art |  |
| [platformer-kit](https://opengameart.org/content/platformer-kit) | Platformer Kit | kenney | CC0 | 3D Art |  |
| [platformer-kit-0](https://opengameart.org/content/platformer-kit-0) | Platformer Kit | kenney | CC0 | 3D Art |  |
| [prototype-kit](https://opengameart.org/content/prototype-kit) | Prototype Kit | kenney | CC0 | 3D Art |  |
| [prototype-textures](https://opengameart.org/content/prototype-textures) | Prototype Textures | kenney | CC0 | Texture |  |
| [retro-medieval-kit](https://opengameart.org/content/retro-medieval-kit) | Retro Medieval Kit | kenney | CC0 | 3D Art |  |
| [retro-textures-fantasy](https://opengameart.org/content/retro-textures-fantasy) | Retro Textures Fantasy | kenney | CC0 | Texture |  |
| [space-kit-remade](https://opengameart.org/content/space-kit-remade) | Space Kit (remade) | kenney | CC0 | 3D Art |  |
| [space-station-kit](https://opengameart.org/content/space-station-kit) | Space Station Kit | kenney | CC0 | 3D Art |  |
| [tower-defense-kit](https://opengameart.org/content/tower-defense-kit) | Tower Defense Kit | kenney | CC0 | 3D Art |  |
| [toy-car-kit](https://opengameart.org/content/toy-car-kit) | Toy Car Kit | kenney | CC0 | 3D Art |  |

### B2. Community OpenGameArt items already checked (license known)

| Slug | Title | License | Blend only |
|---|---|---|---|
| [bird-animated](https://opengameart.org/content/bird-animated) | Bird - Animated | CC BY 3.0 | yes |
| [cartoon-helicopter](https://opengameart.org/content/cartoon-helicopter) | Cartoon Helicopter | CC BY-SA (share-alike) |  |
| [cute-low-poly-ghost](https://opengameart.org/content/cute-low-poly-ghost) | Cute Low Poly Ghost | CC BY 3.0 |  |
| [flare-npcs-animated-pack-1](https://opengameart.org/content/flare-npcs-animated-pack-1) | Flare Npcs animated pack 1 | CC BY-SA (share-alike) |  |
| [low-poly-retro-psx-skeleton](https://opengameart.org/content/low-poly-retro-psx-skeleton) | Low-poly Retro PSX Skeleton | CC BY 4.0 | yes |
| [nightmare-hound](https://opengameart.org/content/nightmare-hound) | Nightmare Hound | CC BY 3.0 | yes |
| [roach-game-ready-and-animated](https://opengameart.org/content/roach-game-ready-and-animated) | Roach, game-ready and animated | CC BY-SA (share-alike) |  |
| [row-boat](https://opengameart.org/content/row-boat) | row boat | CC BY 3.0 | yes |
| [shadow](https://opengameart.org/content/shadow) | Shadow | CC BY 3.0 | yes |
| [spider-animated](https://opengameart.org/content/spider-animated) | Spider - Animated | CC BY 3.0 | yes |
| [torpenwal](https://opengameart.org/content/torpenwal) | Torpenwal | CC0 |  |
| [zombie-survivor](https://opengameart.org/content/zombie-survivor) | Zombie Survivor | CC BY-SA (share-alike) | yes |

### B3. itch.io catalog status (checked 2026-11-26)

| Creator | Pack | License field | Free download | Already acquired | Uploads |
|---|---|---|---|---|---|
| kaylousberg | [KayKit : Bits Bundle 1](https://kaylousberg.itch.io/bits-bundle-1) | Creative Commons Zero v1.0 Universal | NO (paid: must buy) |  |  |
| kaylousberg | [KayKit : Bits Bundle 2](https://kaylousberg.itch.io/bits-bundle-2) | Creative Commons Zero v1.0 Universal | NO (paid: must buy) |  |  |
| kaylousberg | [KayKit : Block Bits](https://kaylousberg.itch.io/block-bits) | Creative Commons Zero v1.0 Universal | yes |  | Free  |
| kaylousberg | [KayKit : Board Game Bits](https://kaylousberg.itch.io/board-game-bits) | Creative Commons Zero v1.0 Universal | yes |  | Free  |
| kaylousberg | [KayKit : City Builder Bits](https://kaylousberg.itch.io/city-builder-bits) | Creative Commons Zero v1.0 Universal | yes | yes | Free  |
| kaylousberg | [KayKit : Fantasy Weapons Bits](https://kaylousberg.itch.io/fantasy-weapons-bits) | Creative Commons Zero v1.0 Universal | yes |  | Free  |
| kaylousberg | [KayKit : Furniture Bits](https://kaylousberg.itch.io/furniture-bits) | Creative Commons Zero v1.0 Universal | yes | yes | Free  |
| kaylousberg | [KayKit : Halloween Bits](https://kaylousberg.itch.io/halloween-bits) | Creative Commons Zero v1.0 Universal | yes | yes | Free  |
| kaylousberg | [KayKit : Holiday Bits](https://kaylousberg.itch.io/holiday-bits) | Creative Commons Zero v1.0 Universal | yes |  | Free  |
| kaylousberg | [(Legacy) KayKit - Mini Game Variety Pack](https://kaylousberg.itch.io/kay-kit-mini-game-variety-pack) | None | yes |  | KayKit Mini-Game Variety Pack 1.2.zip  |
| kaylousberg | [KayKit - Character Pack : Adventurers](https://kaylousberg.itch.io/kaykit-adventurers) | Creative Commons Zero v1.0 Universal | yes | yes | Free 2.0  |
| kaylousberg | [(Legacy) KayKit - Character Animations](https://kaylousberg.itch.io/kaykit-animations) | None | yes |  | KayKit Character Animations 1.2.zip  |
| kaylousberg | [KayKit - Character Animations](https://kaylousberg.itch.io/kaykit-character-animations) | Creative Commons Zero v1.0 Universal | yes | yes | Free 1.1  |
| kaylousberg | [The Complete KayKit](https://kaylousberg.itch.io/kaykit-complete) | Creative Commons Zero v1.0 Universal | NO (paid: must buy) |  |  |
| kaylousberg | [(Legacy) KayKit - Dungeon Pack](https://kaylousberg.itch.io/kaykit-dungeon) | None | yes |  | KayKit Dungeon Pack 1.0.zip  |
| kaylousberg | [KayKit - Dungeon Pack](https://kaylousberg.itch.io/kaykit-dungeon-pack) | Creative Commons Zero v1.0 Universal | yes | yes | Free 1.1  |
| kaylousberg | [KayKit - Forest Nature Pack](https://kaylousberg.itch.io/kaykit-forest) | Creative Commons Zero v1.0 Universal | yes | yes | Free  |
| kaylousberg | [(Legacy) KayKit - Medieval Builder Pack](https://kaylousberg.itch.io/kaykit-medieval-builder-pack) | None | yes |  | KayKit Medieval Builder Pack 1.0.zip  |
| kaylousberg | [KayKit - Medieval Hexagon Pack](https://kaylousberg.itch.io/kaykit-medieval-hexagon) | Creative Commons Zero v1.0 Universal | yes |  | Free  |
| kaylousberg | [KayKit - Platformer Pack](https://kaylousberg.itch.io/kaykit-platformer) | Creative Commons Zero v1.0 Universal | yes |  | Free  |
| kaylousberg | [KayKit - Character Pack : Mystery Monthly Series 4](https://kaylousberg.itch.io/kaykit-series-4) | Creative Commons Zero v1.0 Universal | NO (paid: must buy) |  |  |
| kaylousberg | [KayKit - Character Pack : Mystery Monthly Series 5](https://kaylousberg.itch.io/kaykit-series-5) | Creative Commons Zero v1.0 Universal | NO (paid: must buy) |  |  |
| kaylousberg | [KayKit - Character Pack : Mystery Monthly Series 6](https://kaylousberg.itch.io/kaykit-series-6) | None | NO (paid: must buy) |  |  |
| kaylousberg | [(Legacy) KayKit - Character Pack : Skeletons](https://kaylousberg.itch.io/kaykit-skeleton-pack) | None | yes |  | KayKit Character Pack - Skeletons 1.0.zip  |
| kaylousberg | [KayKit - Character Pack : Skeletons](https://kaylousberg.itch.io/kaykit-skeletons) | Creative Commons Zero v1.0 Universal | yes | yes | Free 1.1  |
| kaylousberg | [(Legacy) KayKit - Spooktober Seasonal Pack](https://kaylousberg.itch.io/kaykit-spooktober) | None | yes | yes | KayKit Spooktober Seasonal Pack 1.1.zip  |
| kaylousberg | [KayKit - Mixed Bag 1](https://kaylousberg.itch.io/mixed-bag-1) | Creative Commons Zero v1.0 Universal | yes | yes | Free  |
| kaylousberg | [KayKit - Mixed Bag 2](https://kaylousberg.itch.io/mixed-bag-2) | Creative Commons Zero v1.0 Universal | yes | yes | Free  |
| kaylousberg | [KayKit : Prototype Bits](https://kaylousberg.itch.io/prototype-bits) | Creative Commons Zero v1.0 Universal | yes |  | Free 1.1  |
| kaylousberg | [KayKit : Resource Bits](https://kaylousberg.itch.io/resource-bits) | Creative Commons Zero v1.0 Universal | yes |  | Free  |
| kaylousberg | [KayKit : Restaurant Bits](https://kaylousberg.itch.io/restaurant-bits) | Creative Commons Zero v1.0 Universal | yes | yes | Free  |
| kaylousberg | [KayKit : RPG Tools Bits](https://kaylousberg.itch.io/rpg-tools-bits) | Creative Commons Zero v1.0 Universal | yes |  | Free  |
| kaylousberg | [KayKit : Space Base Bits](https://kaylousberg.itch.io/space-base-bits) | Creative Commons Zero v1.0 Universal | yes |  | Free  |
| quaternius | [150+ LowPoly Nature Models](https://quaternius.itch.io/150-lowpoly-nature-models) | Creative Commons Zero v1.0 Universal | yes |  | Ultimate Nature Pack by Quaternius.zip  |
| quaternius | [3D Card Kit - Fantasy](https://quaternius.itch.io/3d-card-kit-fantasy) | Creative Commons Zero v1.0 Universal | yes |  | 3D Card Kit - Fantasy [Standard]  |
| quaternius | [50+ LowPoly Guns](https://quaternius.itch.io/50-lowpoly-guns) | None | yes |  | Ultimate Gun Pack by Quaternius.zip  |
| quaternius | [LowPoly Animated Easy Enemies](https://quaternius.itch.io/animated-easy-enemies) | None | yes |  | Easy Animated Enemy Pack - Jan 2019.zip  |
| quaternius | [Animated LowPoly Dinosaurs](https://quaternius.itch.io/animated-lowpoly-dinosaurs) | None | yes |  | Dinosaur Animated Pack - Dec 2018.zip  |
| quaternius | [Bestiary - Dungeon Monsters Kit](https://quaternius.itch.io/bestiary-dungeon-monsters-kit) | None | yes |  | Bestiary - Dungeon Monsters Kit[Standard].zip  |
| quaternius | [Characters - Fantasy Races](https://quaternius.itch.io/characters-fantasy-races) | None | yes |  | Characters - Fantasy Races Kit[Standard].zip  |
| quaternius | [Downtown City MegaKit](https://quaternius.itch.io/downtown-city-megakit) | Creative Commons Zero v1.0 Universal | yes | yes | Downtown City MegaKit[Standard].zip  |
| quaternius | [Fantasy Props MegaKit](https://quaternius.itch.io/fantasy-props-megakit) | Creative Commons Zero v1.0 Universal | yes |  | Fantasy Props MegaKit[Standard].zip  |
| quaternius | [LowPoly Animated Animals](https://quaternius.itch.io/lowpoly-animated-animals) | Creative Commons Zero v1.0 Universal | yes |  | Farm Animals Animated  by Quaternius.zip  |
| quaternius | [LowPoly Animated Fish](https://quaternius.itch.io/lowpoly-animated-fish) | None | yes |  | Fish Pack Animated by Quaternius.zip  |
| quaternius | [LowPoly Animated Knight](https://quaternius.itch.io/lowpoly-animated-knight) | None | yes |  | Knight Character Animated by Quaternius.zip  |
| quaternius | [LowPoly Animated Monsters](https://quaternius.itch.io/lowpoly-animated-monsters) | None | yes |  | Monster Pack Animated by Quaternius.zip  |
| quaternius | [LowPoly Cars](https://quaternius.itch.io/lowpoly-cars) | None | yes |  | Realistic Car Pack - Nov 2018.zip  |
| quaternius | [LowPoly Farm Buildings](https://quaternius.itch.io/lowpoly-farm-buildings) | None | yes | yes | Farm Buildings by Quaternius.zip  |
| quaternius | [LowPoly Medieval Weapons](https://quaternius.itch.io/lowpoly-medieval-weapons) | None | yes |  | Medieval Weapons Pack by Quaternius.zip  |
| quaternius | [LowPoly Modular Dungeon Pack](https://quaternius.itch.io/lowpoly-modular-dungeon-pack) | None | yes |  | .Updated Modular Dungeon - May 2019.zip  |
| quaternius | [LowPoly Modular Street](https://quaternius.itch.io/lowpoly-modular-street) | None | yes |  | Modular Street Pack by Quaternius.zip  |
| quaternius | [LowPoly Robot](https://quaternius.itch.io/lowpoly-robot) | None | yes |  | Animated Robot by Quaternius.zip  |
| quaternius | [LowPoly Spaceships](https://quaternius.itch.io/lowpoly-spaceships) | None | yes |  | Spaceship Pack - Jan 2018.zip  |
| quaternius | [Medieval Village MegaKit](https://quaternius.itch.io/medieval-village-megakit) | Creative Commons Zero v1.0 Universal | yes |  | Medieval Village MegaKit[Standard].zip  |
| quaternius | [Modular Character Outfits - Fantasy](https://quaternius.itch.io/modular-character-outfits-fantasy) | Creative Commons Zero v1.0 Universal | yes |  | Modular Character Outfits - Fantasy[Standard].zip  |
| quaternius | [Modular Sci-Fi MegaKit](https://quaternius.itch.io/modular-sci-fi-megakit) | Creative Commons Zero v1.0 Universal | yes |  | Modular SciFi MegaKit[Standard].zip  |
| quaternius | [LowPoly Platformer Pack](https://quaternius.itch.io/platformer-pack) | None | yes |  | Platformer Pack by Quaternius.zip  |
| quaternius | [Sci-Fi Essentials Kit](https://quaternius.itch.io/sci-fi-essentials-kit) | Creative Commons Zero v1.0 Universal | yes |  | Sci-Fi Essentials Kit[Standard].zip  |
| quaternius | [Stylized Nature MegaKit](https://quaternius.itch.io/stylized-nature-megakit) | Creative Commons Zero v1.0 Universal | yes |  | Stylized Nature MegaKit[Standard].zip  |
| quaternius | [Textured LowPoly Trees](https://quaternius.itch.io/textured-lowpoly-trees) | Creative Commons Zero v1.0 Universal | yes |  | Textured Stylized Trees - May 2020.zip  |
| quaternius | [Ultimate Platformer Pack (100+ Models)](https://quaternius.itch.io/ultimate-platformer-pack) | Creative Commons Zero v1.0 Universal | yes |  | Ultimate Platformer Pack by Quaternius.zip  |
| quaternius | [Universal Animation Library](https://quaternius.itch.io/universal-animation-library) | Creative Commons Zero v1.0 Universal | yes |  | Universal Animation Library[Standard].zip  |
| quaternius | [Universal Animation Library 2](https://quaternius.itch.io/universal-animation-library-2) | None | yes |  | Universal Animation Library 2[Standard].zip  |
| quaternius | [Universal Base Characters](https://quaternius.itch.io/universal-base-characters) | Creative Commons Zero v1.0 Universal | yes | yes | Universal Base Characters[Standard].zip  |
| dreamerh | [DreamKit - Character Pack: Monsters](https://dreamerh.itch.io/dreamkit-character-pack-monsters) | None | yes | yes | DioramaFree.zip ; Color_01.png  |
| dreamerh | [Everyday Interiors (OFFICE)— 3D Props Collection](https://dreamerh.itch.io/office-3d) | None | NO (paid/none) |  |  |
| dreamerh | [Pastel City — Modular Low Poly Asset Pack](https://dreamerh.itch.io/pastel-city) | None | NO (paid: must buy) |  |  |
| dreamerh | [Pumpkin Party – Stylized Halloween Props](https://dreamerh.itch.io/pumpkin-party-stylized-halloween-props) | None | NO (paid: must buy) |  |  |
| dreamerh | [Witch's Brew – Stylized Halloween Props 🎃](https://dreamerh.itch.io/stylized-halloween-props) | None | NO (paid: must buy) |  |  |

### B4. Quaternius website packs (license + Google Drive / itch links)

| Pack page | License | Google Drive | itch |
|---|---|---|---|
| https://quaternius.com/packs/3dcardkitfantasy.html | CC0 |  | https://quaternius.itch.io/3d-card-kit-fantasy |
| https://quaternius.com/packs/animatedalien.html | CC0 | https://drive.google.com/drive/folders/1ADdETHqjSIEUhjKjhLB9hQjeppXEqcvL |  |
| https://quaternius.com/packs/animateddinosaurs.html | CC0 | https://drive.google.com/drive/folders/1u5Fhu3ziuRlGonW6bUI7uClqBGoSNeF6 |  |
| https://quaternius.com/packs/animatedfish.html | CC0 | https://drive.google.com/drive/folders/1SvlOveJJjmhSn-FgCRyojc1T5QHjjGkF |  |
| https://quaternius.com/packs/animatedguns.html | CC0 | https://drive.google.com/drive/folders/1ICYTdMXQqhkhrh8Fzjx9D0ozJuONwtC4 |  |
| https://quaternius.com/packs/animatedman.html | CC0 | https://drive.google.com/drive/folders/1XQ3UpQezkOFDdazv6KK16qp3mBXhO9uO |  |
| https://quaternius.com/packs/animatedmech.html | CC0 | https://drive.google.com/drive/folders/1sueV_4CGMpZC8y30mWfgKK9UaT3mkHBX |  |
| https://quaternius.com/packs/animatedmen.html | CC0 | https://drive.google.com/drive/folders/17LibivOaUidsQhSkcxP3YYvDr0n7wIwu |  |
| https://quaternius.com/packs/animatedmonster.html | CC0 | https://drive.google.com/drive/folders/102H-oyUM8SGYi1mW0GOgkjEu7xSdaORA |  |
| https://quaternius.com/packs/animatedrobot.html | CC0 | https://drive.google.com/drive/folders/18MU0RtRu9G6SU6uSZ_zMQFmVkRlB4zH5 |  |
| https://quaternius.com/packs/animatedtanks.html | CC0 | https://drive.google.com/drive/folders/1tHX0RF9l4Nw4EZwxH6xWta0HsICU2h-G |  |
| https://quaternius.com/packs/animatedwoman.html | CC0 | https://drive.google.com/drive/folders/1M2jkG2WLiteK81Pj_v0QjCJoUTf2gCjp |  |
| https://quaternius.com/packs/animatedwomen.html | CC0 | https://drive.google.com/drive/folders/1c13R--fMqdR6r2MRlcKKsbPky0__T-yJ |  |
| https://quaternius.com/packs/animatedzombie.html | CC0 | https://drive.google.com/drive/folders/1AfOPRgr5Gl8gll9KfGDEUSYq_Ag7yPJG |  |
| https://quaternius.com/packs/backgroundposedhumans.html | CC0 | https://drive.google.com/drive/folders/18dWyZlA53euzsc1WobITqFYLcT5sFULz |  |
| https://quaternius.com/packs/bestiarydungeonmonsterskit.html | QAL |  | https://quaternius.itch.io/bestiary-dungeon-monsters-kit |
| https://quaternius.com/packs/buildings.html | CC0 | https://drive.google.com/drive/folders/1uWCsV9QfnAu8u_QbwkYwOfuU3McME7CA |  |
| https://quaternius.com/packs/cars.html | CC0 | https://drive.google.com/drive/folders/1fKlbDry77iY8KlEoxzUxIAZQL_XhzWlA |  |
| https://quaternius.com/packs/charactersfantasyraces.html | QAL |  | https://quaternius.itch.io/characters-fantasy-races |
| https://quaternius.com/packs/cubeworldkit.html | CC0 | https://drive.google.com/drive/folders/1Yyag0ibcOX6lOBY9a3m6iPnz8HwjwLFJ |  |
| https://quaternius.com/packs/cutefish.html | CC0 | https://drive.google.com/drive/folders/1QK5NCgIxUZ1cYGzVwaNfcfEiQhvczqUB |  |
| https://quaternius.com/packs/cutemonsters.html | CC0 | https://drive.google.com/drive/folders/1zLLO_7ZoWgUsS4uooYnVSErQYRu1VdS0 |  |
| https://quaternius.com/packs/cyberpunkgamekit.html | CC0 | https://drive.google.com/drive/folders/1GyKLypoBxrpLN6GERF9U610Wiub48v9y |  |
| https://quaternius.com/packs/downtowncitymegakit.html | CC0 |  | https://quaternius.itch.io/downtown-city-megakit |
| https://quaternius.com/packs/easyenemy.html | CC0 | https://drive.google.com/drive/folders/1VbJIslXPWK-1KybQN6yezZrfJcw608qe |  |
| https://quaternius.com/packs/fantasypropsmegakit.html | CC0 |  | https://quaternius.itch.io/fantasy-props-megakit |
| https://quaternius.com/packs/farmanimal.html | CC0 | https://drive.google.com/drive/folders/1is1ax2V0mIEDS7BbbzBV_x2Pabya1dVJ |  |
| https://quaternius.com/packs/farmbuildings.html | CC0 | https://drive.google.com/drive/folders/1gdZ39vcLML_ULU5sHirkKQ-gEkk458Ak |  |
| https://quaternius.com/packs/furniture.html | CC0 | https://drive.google.com/drive/folders/1CLWStkb7cipC1ZdTunYJXKVqEVwtXWXK |  |
| https://quaternius.com/packs/junkfood.html | CC0 | https://drive.google.com/drive/folders/127xt6nsl4Z-YRy-FZru38Sf6ElBWc8IU |  |
| https://quaternius.com/packs/knightcharacter.html | CC0 | https://drive.google.com/drive/folders/1QVyfCJkq70mAwMIh1cGq1xfHp2LN5GmK |  |
| https://quaternius.com/packs/medievaldungeon.html | CC0 | https://drive.google.com/drive/folders/13MoeF0Uy9PHqXXi6gh63tV2PLRD6YXJv |  |
| https://quaternius.com/packs/medievalvillage.html | CC0 | https://drive.google.com/drive/folders/18T92VcNldHG0ugWo1u0hSJGDLua-n7o5 |  |
| https://quaternius.com/packs/medievalvillagemegakit.html | CC0 |  | https://quaternius.itch.io/medieval-village-megakit |
| https://quaternius.com/packs/medievalweapons.html | CC0 | https://drive.google.com/drive/folders/1Z6vYiQxY8W73FXuMWzaTQAg9rzbumnOr |  |
| https://quaternius.com/packs/modularcharacteroutfitsfantasy.html | CC0 |  | https://quaternius.itch.io/modular-character-outfits-fantasy |
| https://quaternius.com/packs/modulardungeon.html | CC0 | https://drive.google.com/drive/folders/1CvofJVYHf00StUTsIWtOuyVxeV0CN3UI |  |
| https://quaternius.com/packs/modularmedievalbuildings.html | CC0 | https://drive.google.com/drive/folders/1WCmnrS1fYQLYfRwztVErgAOyWXdJiVIo |  |
| https://quaternius.com/packs/modularplatformer.html | CC0 | https://drive.google.com/drive/folders/1ku_XmbHOZ5ypgKCAjpzX6hlXaOJT7Uoq |  |
| https://quaternius.com/packs/modularscifimegakit.html | CC0 |  | https://quaternius.itch.io/modular-sci-fi-megakit |
| https://quaternius.com/packs/modularstreets.html | CC0 | https://drive.google.com/drive/folders/1-YvMpLDYBIy-0Ms7ZlFmUpChTbHku8IJ |  |
| https://quaternius.com/packs/modulartrain.html | CC0 | https://drive.google.com/drive/folders/15UgTB4JZgsSxdBDTTk0Qv1iiCbH9bdMk |  |
| https://quaternius.com/packs/piratekit.html | CC0 | https://drive.google.com/drive/folders/1KjMzhVsDcyvYMWeVjZcRfuu8auBLpNi2 |  |
| https://quaternius.com/packs/publictransport.html | CC0 | https://drive.google.com/drive/folders/1GUIE138uPVNraiQEf33dIx9wENhttZ15 |  |
| https://quaternius.com/packs/rpg.html | CC0 | https://drive.google.com/drive/folders/1BSyWiPypvgTl32qd5bZjP_iMeG_XsImT |  |
| https://quaternius.com/packs/rpgcharacters.html | CC0 | https://drive.google.com/drive/folders/1MIRQXLfTd21HMI5rwOb6Xy0rv0xv1m8b |  |
| https://quaternius.com/packs/scifiessentialskit.html | CC0 |  | https://quaternius.itch.io/sci-fi-essentials-kit |
| https://quaternius.com/packs/scifigun.html | CC0 | https://drive.google.com/drive/folders/1jaszGQ7QN2KIWFFoOVYy8y8qFe27yVL2 |  |
| https://quaternius.com/packs/scifimodularguns.html | CC0 | https://drive.google.com/drive/folders/1P5j8xZyIEmZGHjGYmIgYCev9SVmB-IHC |  |
| https://quaternius.com/packs/ships.html | CC0 | https://drive.google.com/drive/folders/1Qf31QTnGfxRzYxx8dHmlVGDT4KmIa0Vy |  |
| https://quaternius.com/packs/simplebuildings.html | CC0 | https://drive.google.com/drive/folders/1r-FcNFxC6ziN0oI3GqZJdEkdzglFQHQH |  |
| https://quaternius.com/packs/simplenature.html | CC0 | https://drive.google.com/drive/folders/18hb-5HGCLL9BS8jmxkE4h31wmHGeqfts |  |
| https://quaternius.com/packs/spaceships.html | CC0 | https://drive.google.com/drive/folders/1ZxWZ-KuSOA-9s53PA1B1-O0txRJvne2i |  |
| https://quaternius.com/packs/stylizednaturemegakit.html | CC0 |  | https://quaternius.itch.io/stylized-nature-megakit |
| https://quaternius.com/packs/stylizedtree.html | CC0 | https://drive.google.com/drive/folders/1GlrFUFcNj6KIuc4-QpVEiRcXVUzSClP2 |  |
| https://quaternius.com/packs/survival.html | CC0 | https://drive.google.com/drive/folders/1NKfC95GMWWJquy6rRzwFVkVDoZ_QP7K_ |  |
| https://quaternius.com/packs/sushirestaurantkit.html | CC0 | https://drive.google.com/drive/folders/1srOaThdSqYBtmrqq9couZShM5r0cw_bH |  |
| https://quaternius.com/packs/texturedfantasynature.html | CC0 | https://drive.google.com/drive/folders/1WKJe-QxkPs_zb8CVhxPhYT57EsY5tGD3 |  |
| https://quaternius.com/packs/toonshootergamekit.html | CC0 | https://drive.google.com/drive/folders/1-BDs_EIyd6uiF2XuoyiZEcqnMQIJrE0C |  |
| https://quaternius.com/packs/turretpack.html | CC0 | https://drive.google.com/drive/folders/1HenXNzxU2HJMDOGQj9LKRHk9eHrBgoya |  |
| https://quaternius.com/packs/ultimateanimatedanimals.html | CC0 | https://drive.google.com/drive/folders/1uJ3N5HfB7jKTseJUNQr3N4YaN0UuEtHk |  |
| https://quaternius.com/packs/ultimatecrops.html | CC0 | https://drive.google.com/drive/folders/1uhbi-NWp7pwqOGtraBZurbphyxAvoABZ |  |
| https://quaternius.com/packs/ultimatedanimatedcharacter.html | CC0 | https://drive.google.com/drive/folders/1sNi1AfenfPRrvRt5yfaj5QMMd6KKcUJ5 |  |
| https://quaternius.com/packs/ultimatefantasyrts.html | CC0 | https://drive.google.com/drive/folders/1h7sztlZyavWla-JDk3jp6KiWDdMh08yd |  |
| https://quaternius.com/packs/ultimatefood.html | CC0 | https://drive.google.com/drive/folders/1zMfN7q9VU80M7mLAbBBJyY2OdoXslbl1 |  |
| https://quaternius.com/packs/ultimatefurniture.html | CC0 | https://drive.google.com/drive/folders/1n85oUi0RN5ZUXEIMKA-AnBsPErVXWcma |  |
| https://quaternius.com/packs/ultimategun.html | CC0 | https://drive.google.com/drive/folders/12V-mHNB6bnW2WzgpJfRBQd-TG4pOO3yx |  |
| https://quaternius.com/packs/ultimatehomeinterior.html | CC0 | https://drive.google.com/drive/folders/1SNK9PwPi8xqqxmpU5xEZeiQjB26C1oX6 |  |
| https://quaternius.com/packs/ultimatemodularcharacters.html | CC0 | https://drive.google.com/drive/folders/1USAAquX2JJWuA2m6zol0KUkFe3UkZ8zX |  |
| https://quaternius.com/packs/ultimatemodularruins.html | CC0 | https://drive.google.com/drive/folders/1ETp2ldaHaP0BkS4FBmkT-g9Yf88T_cIX |  |
| https://quaternius.com/packs/ultimatemodularscifi.html | CC0 | https://drive.google.com/drive/folders/1zpr6HxVa-sCV93IHubN3A1d8HhF2wGbM |  |
| https://quaternius.com/packs/ultimatemodularwomen.html | CC0 | https://drive.google.com/drive/folders/1720N9IGyQHXYvtvZJzazhxtTTlz-y2Vf |  |
| https://quaternius.com/packs/ultimatemonsters.html | CC0 | https://drive.google.com/drive/folders/18m4KpzpEzhC9wl7jzr6dUc0N8Jozr79C |  |
| https://quaternius.com/packs/ultimatenature.html | CC0 | https://drive.google.com/drive/folders/1-Kl0L_Jg8awbh0S5T-z3zxh4mVlnxTpa |  |
| https://quaternius.com/packs/ultimateplatformer.html | CC0 | https://drive.google.com/drive/folders/1NDZn_aGnn0vfFV3M22Y8GPcDjO8BVcLs |  |
| https://quaternius.com/packs/ultimaterpg.html | CC0 | https://drive.google.com/drive/folders/1IhdL3W5XdJrjf_axqAnKvEybMaC3FwF- |  |
| https://quaternius.com/packs/ultimatespacekit.html | CC0 | https://drive.google.com/drive/folders/17F8HlI2zPTlo32aieW5YPPwOk78xo-2m |  |
| https://quaternius.com/packs/ultimatespaceships.html | CC0 | https://drive.google.com/drive/folders/1NpfT3wqe2k3Jwue2xryi7tzxP4bWzETu |  |
| https://quaternius.com/packs/ultimatestylizednature.html | CC0 | https://drive.google.com/drive/folders/1IV3bXHzkNvuNWFHPi4KPx-G4ghuxIuT- |  |
| https://quaternius.com/packs/ultimatetexturedbuildings.html | CC0 | https://drive.google.com/drive/folders/1RE3qXhbE5yGS3t-xGFJ8GmOtTgCUF3LQ |  |
| https://quaternius.com/packs/universalanimationlibrary.html | CC0 |  | https://quaternius.itch.io/universal-animation-library |
| https://quaternius.com/packs/universalanimationlibrary2.html | CC0 |  | https://quaternius.itch.io/universal-animation-library-2 |
| https://quaternius.com/packs/universalbasecharacters.html | CC0 |  | https://quaternius.itch.io/universal-base-characters |
| https://quaternius.com/packs/zombieapocalypsekit.html | CC0 | https://drive.google.com/drive/folders/1mWP6sCHun7OUMHQeDNZLrXTteXlzWg_t |  |

### B5. KayKit GitHub repos not cloned

- https://github.com/KayKit-Game-Assets/KayKit-Prototype-Bits-1.0 — prototyping blocks, doors, targets
- https://github.com/KayKit-Game-Assets/KayKit-Space-Base-Bits-1.0 — modular space base (sci-fi interiors/labs)
- https://github.com/KayKit-Game-Assets/KayKit-Medieval-Hexagon-Pack-1.0 — 200+ hexagon tiles, medieval buildings

### B6. Unscanned OpenGameArt search leads (license NOT checked yet)

- **ambulance**: [Hospital (Medical Center) from Moscow](https://opengameart.org/content/hospital-medical-center-from-moscow)
- **baby**: [Evil Giant Rat](https://opengameart.org/content/evil-giant-rat), [WcDonald's Sign](https://opengameart.org/content/wcdonalds-sign), [low poly cartoon baby cow](https://opengameart.org/content/low-poly-cartoon-baby-cow), [Low Poly Cub](https://opengameart.org/content/low-poly-cub)
- **boat**: [Superpowers assets 3D stuff](https://opengameart.org/content/superpowers-assets-3d-stuff), [Low-Poly Pirate Ship](https://opengameart.org/content/low-poly-pirate-ship), [Tiny boat](https://opengameart.org/content/tiny-boat), [32 Low Poly Models](https://opengameart.org/content/32-low-poly-models), [Low Poly Boat](https://opengameart.org/content/low-poly-boat), [Medieval Boat](https://opengameart.org/content/medieval-boat), [Shipwrecked boat model](https://opengameart.org/content/shipwrecked-boat-model), [Sailing Boat](https://opengameart.org/content/sailing-boat), [The Invertub](https://opengameart.org/content/the-invertub), [Boat](https://opengameart.org/content/boat-0)
- **child**: [Spell Book Pack](https://opengameart.org/content/spell-book-pack-0), [lava golem](https://opengameart.org/content/lava-golem), [Blender2.5 humanoid rig](https://opengameart.org/content/blender25-humanoid-rig), [Blender2.5 Human Rig](https://opengameart.org/content/blender25-human-rig), [Door](https://opengameart.org/content/door-1)
- **creature**: [Earth Elemental / Golem](https://opengameart.org/content/earth-elemental-golem), [THB-5J Thunderbird ](https://opengameart.org/content/thb-5j-thunderbird), [Iron Buckler](https://opengameart.org/content/iron-buckler), [Giant egg sack ](https://opengameart.org/content/giant-egg-sack), [Skinny Troll](https://opengameart.org/content/skinny-troll), [Skull prop](https://opengameart.org/content/skull-prop), [Dark Priest](https://opengameart.org/content/dark-priest), [Little Slime](https://opengameart.org/content/little-slime), [The Dark Priest](https://opengameart.org/content/the-dark-priest), [Uncle Fungus](https://opengameart.org/content/uncle-fungus), [Elemental Golem](https://opengameart.org/content/elemental-golem), [Big Guy](https://opengameart.org/content/big-guy), [Boar](https://opengameart.org/content/boar), [3D - Infernal Sword](https://opengameart.org/content/3d-infernal-sword), [Lava Spawn animated](https://opengameart.org/content/lava-spawn-animated)
- **doctor**: [SCP- Contaiment Breach: Scientist](https://opengameart.org/content/scp-contaiment-breach-scientist), [Medical Packaging 1](https://opengameart.org/content/medical-packaging-1), [Medical Packaging 4](https://opengameart.org/content/medical-packaging-4), [Medical Packaging 2](https://opengameart.org/content/medical-packaging-2), [Medical Packaging 3](https://opengameart.org/content/medical-packaging-3)
- **ghost**: [Ring Set - Precious Metals](https://opengameart.org/content/ring-set-precious-metals), [Animated Mage](https://opengameart.org/content/animated-mage), [FLARE Zombie Mod - Pirate Crewman Ghost](https://opengameart.org/content/flare-zombie-mod-pirate-crewman-ghost), [FLARE Zombie Mod - Pirate Officer Ghost](https://opengameart.org/content/flare-zombie-mod-pirate-officer-ghost), [Hapy ghoust](https://opengameart.org/content/hapy-ghoust), [Man Cover](https://opengameart.org/content/man-cover)
- **grandma**: [Robin Hood Hat](https://opengameart.org/content/robin-hood-hat), [Cremation Urn](https://opengameart.org/content/cremation-urn)
- **helicopter**: [Blender models for Freeciv units](https://opengameart.org/content/blender-models-for-freeciv-units), [Future Fighterjet](https://opengameart.org/content/future-fighterjet), [32 Low Poly Models](https://opengameart.org/content/32-low-poly-models), [Shamgar the killer robot](https://opengameart.org/content/shamgar-the-killer-robot), [Attack Chopper](https://opengameart.org/content/attack-chopper), [Helicopter](https://opengameart.org/content/helicopter-0), [3D RC hélicopter](https://opengameart.org/content/3d-rc-h%C3%A9licopter), [Helicopter](https://opengameart.org/content/helicopter-4), [Cartoon Helicopter](https://opengameart.org/content/cartoon-helicopter-0), [Half-finished Chopper](https://opengameart.org/content/half-finished-chopper)
- **kid**: [Key1](https://opengameart.org/content/key1), [Mac the Robot](https://opengameart.org/content/mac-the-robot), [Skateboard](https://opengameart.org/content/skateboard)
- **low poly character**: [3rd person blender sci-fi pack](https://opengameart.org/content/3rd-person-blender-sci-fi-pack), [Mini Library](https://opengameart.org/content/mini-library), [Grapple Girl](https://opengameart.org/content/grapple-girl), [Troll Mauler](https://opengameart.org/content/troll-mauler), [SciFi Girl](https://opengameart.org/content/scifi-girl), [Low poly character (+Blend File)](https://opengameart.org/content/low-poly-character-blend-file), [Tiby 3D rigged model](https://opengameart.org/content/tiby-3d-rigged-model), [Iron Knife](https://opengameart.org/content/iron-knife), [Frog Guy](https://opengameart.org/content/frog-guy), [Low Poly Knight](https://opengameart.org/content/low-poly-knight), [The Dark Priest](https://opengameart.org/content/the-dark-priest), [John Williams Waterhouse Handpainted Set](https://opengameart.org/content/john-williams-waterhouse-handpainted-set), [Electric Axe Bass Guitar](https://opengameart.org/content/electric-axe-bass-guitar), [Elf, game-ready and animated](https://opengameart.org/content/elf-game-ready-and-animated), [Male Sci-Fi Character](https://opengameart.org/content/male-sci-fi-character)
- **monster**: [3rd person blender sci-fi pack](https://opengameart.org/content/3rd-person-blender-sci-fi-pack), [Cethiel's Dragon 3D](https://opengameart.org/content/cethiels-dragon-3d), [Troll Mauler](https://opengameart.org/content/troll-mauler), [Fire/Ice/Stone Golem](https://opengameart.org/content/fireicestone-golem), [Skinny Troll](https://opengameart.org/content/skinny-troll), [High-poly AK-47](https://opengameart.org/content/high-poly-ak-47), [Oozey the Slime](https://opengameart.org/content/oozey-the-slime), [Little Slime](https://opengameart.org/content/little-slime), [Low-poly spider (Glest)](https://opengameart.org/content/low-poly-spider-glest), [Rock Golem](https://opengameart.org/content/rock-golem), [Elemental Golem](https://opengameart.org/content/elemental-golem), [The Mobile Cactus](https://opengameart.org/content/the-mobile-cactus), [Low Poly Giant Spider ](https://opengameart.org/content/low-poly-giant-spider), [Big Guy](https://opengameart.org/content/big-guy), [Lava Spawn animated](https://opengameart.org/content/lava-spawn-animated)
- **motorcycle**: [Harakiri Warbike 1000cc](https://opengameart.org/content/harakiri-warbike-1000cc), [Scifi Moto](https://opengameart.org/content/scifi-moto)
- **nurse**: [Spitfire Mk VIII](https://opengameart.org/content/spitfire-mk-viii)
- **octopus**: [Little Slime](https://opengameart.org/content/little-slime), [Octobot](https://opengameart.org/content/octobot), [Captain Coggles](https://opengameart.org/content/captain-coggles)
- **old man**: [3D Dungeon Tileset](https://opengameart.org/content/3d-dungeon-tileset), [Low Poly Knight](https://opengameart.org/content/low-poly-knight), [Medi Kit/Box](https://opengameart.org/content/medi-kitbox), [Low Spec Velociraptor](https://opengameart.org/content/low-spec-velociraptor), [OLD Phone](https://opengameart.org/content/old-phone), [Old man without shirt  (Rak)](https://opengameart.org/content/old-man-without-shirt-rak)
- **old woman**: [Goth female - Fleur du Mal](https://opengameart.org/content/goth-female-fleur-du-mal)
- **police**: [PSX Style Cars](https://opengameart.org/content/psx-style-cars), [Neon Town](https://opengameart.org/content/neon-town), [Lowpoly Pig](https://opengameart.org/content/lowpoly-pig), [Pack of extremly low poly soviet vehicles in pixel art style.](https://opengameart.org/content/pack-of-extremly-low-poly-soviet-vehicles-in-pixel-art-style), [Police.blend](https://opengameart.org/content/policeblend), [Tonfa](https://opengameart.org/content/tonfa), [Riot shield](https://opengameart.org/content/riot-shield), [Police Voxel car](https://opengameart.org/content/police-voxel-car), [Police Tonfa](https://opengameart.org/content/police-tonfa), [Time Machine](https://opengameart.org/content/time-machine), [Colt Police Positive](https://opengameart.org/content/colt-police-positive)
- **rigged character**: [Dwarf - fixed](https://opengameart.org/content/dwarf-fixed), [Wizard](https://opengameart.org/content/wizard-4), [Grapple Girl](https://opengameart.org/content/grapple-girl), [Fire/Ice/Stone Golem](https://opengameart.org/content/fireicestone-golem), [UBot](https://opengameart.org/content/ubot), [lava golem](https://opengameart.org/content/lava-golem), [Tetine Elfe](https://opengameart.org/content/tetine-elfe), [Pirate](https://opengameart.org/content/pirate), [Tiby 3D rigged model](https://opengameart.org/content/tiby-3d-rigged-model), [SAP-1 (Sapper Bot Mark 1)](https://opengameart.org/content/sap-1-sapper-bot-mark-1), [Anime girl model (rigged, textured, high poly)](https://opengameart.org/content/anime-girl-model-rigged-textured-high-poly), [Robo Welder](https://opengameart.org/content/robo-welder), [anime school girl with blazer](https://opengameart.org/content/anime-school-girl-with-blazer), [Chained Demon](https://opengameart.org/content/chained-demon), [Frog Guy](https://opengameart.org/content/frog-guy)
- **shark**: [Tsundere Shark](https://opengameart.org/content/tsundere-shark), [Ugly shark](https://opengameart.org/content/ugly-shark), [Voxel creature pack1](https://opengameart.org/content/voxel-creature-pack1), [3D Weapons - Shark Tooth](https://opengameart.org/content/3d-weapons-shark-tooth), [ASC Bonaventure](https://opengameart.org/content/asc-bonaventure)
- **skeleton**: [Rigged Horse](https://opengameart.org/content/rigged-horse), [Base Human Models (Low Poly)  for Blender 2.5x](https://opengameart.org/content/base-human-models-low-poly-for-blender-25x), [Zombie](https://opengameart.org/content/zombie-0), [Anime girl model (rigged, textured, high poly)](https://opengameart.org/content/anime-girl-model-rigged-textured-high-poly), [anime school girl with blazer](https://opengameart.org/content/anime-school-girl-with-blazer), [Skeleton Outlaw 3D Character](https://opengameart.org/content/skeleton-outlaw-3d-character), [Cleaned-up base human models](https://opengameart.org/content/cleaned-base-human-models), [FLARE Skeleton Mod - Skeletal Occultist](https://opengameart.org/content/flare-skeleton-mod-skeletal-occultist), [FLARE Skeleton Mod - Skeletal Knight](https://opengameart.org/content/flare-skeleton-mod-skeletal-knight), [Undead Weapon Set and Weapon Rack](https://opengameart.org/content/undead-weapon-set-and-weapon-rack), [Flying skull](https://opengameart.org/content/flying-skull), [FLARE Mod - High Skeleton Mage](https://opengameart.org/content/flare-mod-high-skeleton-mage), [Imp](https://opengameart.org/content/imp), [Male body subD mesh](https://opengameart.org/content/male-body-subd-mesh), [Old Skull](https://opengameart.org/content/old-skull)
- **student**: [Male body subD mesh](https://opengameart.org/content/male-body-subd-mesh)
- **teenager**: [VRoid Studio CC0 models](https://opengameart.org/content/vroid-studio-cc0-models), [Icebergs in 3D](https://opengameart.org/content/icebergs-in-3d), [Milo, a 3D girl](https://opengameart.org/content/milo-a-3d-girl)
- **werewolf**: [Digy Boots & jacket + textures (non riged)](https://opengameart.org/content/digy-boots-jacket-textures-non-riged)
- **zombie**: [fps arms (rigged only)](https://opengameart.org/content/fps-arms-rigged-only), [Zombie](https://opengameart.org/content/zombie-0), [zombie](https://opengameart.org/content/zombie), [anime school girl with blazer](https://opengameart.org/content/anime-school-girl-with-blazer), [FLARE Zombie Mod - Pirate Crewman Ghost](https://opengameart.org/content/flare-zombie-mod-pirate-crewman-ghost), [FLARE Zombie Mod - Pirate Officer Ghost](https://opengameart.org/content/flare-zombie-mod-pirate-officer-ghost), [Chainsaw](https://opengameart.org/content/chainsaw), [Mobile Ready Zombie](https://opengameart.org/content/mobile-ready-zombie), [Dungeon Pack 1](https://opengameart.org/content/dungeon-pack-1), [Low Poly Weapons Pack with rigged arms](https://opengameart.org/content/low-poly-weapons-pack-with-rigged-arms), [Soccer Field](https://opengameart.org/content/soccer-field), [Hospital (Medical Center) from Moscow](https://opengameart.org/content/hospital-medical-center-from-moscow), [Zombie Head](https://opengameart.org/content/zombie-head), [NeuroBrain](https://opengameart.org/content/neurobrain), [WcDonald's Sign](https://opengameart.org/content/wcdonalds-sign)

## C. Unavailable / excluded sources

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

## D. Where to look first for current gaps

- **Teen / child / baby**: B2 blend-only items (lowpolykid, lowpoly-boy-1, lowpoly-girl-1, adventure-kid, adolescent-female-character) need conversion; otherwise new searches on OpenGameArt/itch.io with CC0 filter.
- **Elderly**: B2 `old-city-couple` (CC0, blend only).
- **Ghost / shadow**: B2 `emotional-ghosts`, `ghost-4`, `low-poly-ghost` (CC0, blend only); `shadow` (CC BY 3.0).
- **Monsters (Quaternius)**: B4 *Ultimate Monsters*, *Zombie Apocalypse Kit*, *Animated Men/Women* — Google Drive only; retry Drive later.
- **More KayKit**: B3 free packs not yet acquired; B5 repos.
- **Props/textures**: Poly Haven `not_used` lists (CC0, photoreal).
