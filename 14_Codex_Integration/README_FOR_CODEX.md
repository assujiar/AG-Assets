# README FOR CODEX — Arsip Ganjil 3D Asset Library

Library root: `ARSIP-GANJIL-3D-ASSET-LIBRARY/` (all paths below and in the JSON files are relative to it).
Style target: dark stylized low-poly miniature. Horror comes from lighting/material/camera — base assets are neutral.

## 1. Where things are
| Folder | Content |
|---|---|
| 01_Characters/<Adult_Male, Adult_Female, Elderly_*, Profession_Specific, Fantasy, Skinnable_Base>/<PACK>/ | Human characters, one file per character |
| 02_Supernatural/<Skeleton, Ghost, Zombie, Monster, Demon, Cryptid, Aquatic_Creature, Giant_Creature>/<PACK>/ | Creatures |
| 03_Animals/<PACK>/ | Animals (many animated) |
| 04_Environments/<Residential, Urban, Public_Facilities, Forest, River, Underwater, Cemetery, Abandoned, Modular_Architecture>/<PACK_folder>/ | Modular kits, kept as whole pack folders (shared atlases) |
| 05_Vehicles, 06_Props/<Everyday, Investigation, Horror, Furniture, Equipment>, 07_Character_Accessories | Vehicles, props, hats/hair/weapons/gear |
| 08_Animations/<Locomotion, Interaction, Reaction, Combat, Horror, _Universal_Libraries, _Rigs_and_Mannequins> | Clip-library files (GLB/FBX that mostly hold animations) |
| 09_Materials_Textures | Poly Haven 1k PBR sets + 1k HDRIs, Kenney liminal textures, skyboxes |
| 10_Source_Archives | **Inventory only** (`SOURCE_INVENTORY.md/.json`): source of every asset (direct URL, SHA-256, license, formats inside) + packs found but not downloaded. Original archives are not in this repo. |
| 11_Licenses | License files per pack code |
| 12_Visual_Catalog | `index.html` (phone friendly), contact sheets, renders, official previews |
| 13_Metadata | Raw inspection data, QC, three.js load test, SHA256 |
| 14_Codex_Integration | This README + all index JSONs |

Assets are stored **once**. Multi-use assets are found through `tags`, `roles`, `category/subcategory` in `AssetRegistry.json` — never copy them per scene.
`06_Props/Investigation` is mostly Poly Haven photoreal items (style mismatch; restyle with flat/toon materials or use sparingly).

## 2. Finding assets
- `AssetRegistry.json` → `assets[]` (every production file; `duplicate_of` marks exact duplicates — skip those), `materials[]`, `unsupported[]` (Tier D, Blender-only), `unavailable_sources[]`.
- `CharacterIndex.json` → `human[]`, `supernatural[]`, `animals[]` with gender, age_group, roles, tier, skeleton family, clips, preview.
- `EnvironmentIndex.json` → environments/vehicles/props/accessories grouped by folder → pack, with tags; plus `materials`.
- `AnimationIndex.json` → every clip name (from the files), its source asset, skeleton family, duration, categories (Locomotion, Interaction, Dialogue, Reaction, Horror, Combat, Idle, Creature...).
- `SkeletonCompatibility.json` → rig families (identical bone-name sets) and which assets share clips.
Useful filters: `readiness_tier=="A"`, `approval_status`, `age_group`, `gender`, `roles` (e.g. "doctor", "police officer", "farmer", "driver", "mechanic", "shopkeeper", "gravekeeper"), `tags` (e.g. "cemetery", "lighting", "door").

## 3. Choosing an animated character
Unique human characters: 179 (Tier A with embedded clips: 167).
Best everyday-life casts:
- **QT-UACP** (Quaternius Ultimate Animated Character Pack, FBX, 32-joint rig, 11 clips each incl. Idle/Walk/Run/Wave/Punch/Death...; casual, suit, doctor young/old, chef, worker, soldier, elderly "OldClassy"). Faces are black silhouettes by design.
- **GH-SCITIZIA** (55 GLB, 19-bone rig, 10 clips: parado=idle, andar=walk, correr=run, empurrar=push, comemorar=celebrate, acenar=wave, pular=jump, sentar=sit, torcer=cheer, apontar=point; 31 cast members have 4 facial morph targets: boca, sorriso, sobrancelha, franze). Includes elderly men/women, mechanics, drivers, farmer, radio host. Retro pixel-texture look.
- **KN-MINICHAR / KN-GRAVE / KN-MINISHOP** (Kenney chibi GLB, 7-joint rig, 32 clips: idle, walk, sprint, sit, pick-up, interact, die, emote...). Police, doctor/scientist, office, worker, shopkeeper, gravekeeper, ghost, vampire, zombie, skeleton.
- **KN-BLOCKY** (18 Kenney blocky GLB: node-animated, 27 clips, no skeleton) — includes elderly man with glasses, police officer, businessman, zombie.
- **QT-UBC + QT-UAL1/UAL2**: athletic base bodies (65-joint) + 80+ library clips on the same Universal rig family; hair/eyebrow meshes in 07_Character_Accessories/QT-UBC rigged to the head bone.
- **KK-ADVENT / KK-SKEL / KK-ANIMS**: KayKit fantasy cast + skeletons with 76-95 embedded clips; KK-ANIMS = 147 clips on the KayKit Medium/Large rigs (+ mannequins).
Diving/swimming: QT-UAL1 has Swim_Fwd_Loop / Swim_Idle_Loop for the UAL rig (use with QT-UBC bodies after checking joint names).
Gaps: no usable teenage, child or baby model (only Blender-only candidates, Tier D). Elderly: QT-UACP ×4, Scitizia ×8, Kenney blocky ×1, Kenney gravekeeper.

## 4. Skeleton families (top by clip count)
- SKF-08 KK-ADVENT-41j: 10 assets, 835 clips (packs: KK-ADVENT×6, KK-SKEL×4)
- SKF-03 KN-MINICHAR-7j: 24 assets, 768 clips (packs: KN-MINICHAR×20, KN-MINIDUN×2, KN-MINIFOR×1, KN-MINISHOP×1)
- SKF-02 QT-UACP-32j: 52 assets, 572 clips (packs: QT-UACP×52)
- SKF-01 GH-SCITIZIA-19j: 55 assets, 550 clips (packs: GH-SCITIZIA×55)
- SKF-04 KK-ANIMS-23j: 15 assets, 173 clips (packs: KK-ANIMS×15)
- SKF-07 QT-CUTEMON-11j: 10 assets, 100 clips (packs: QT-CUTEMON×10)
- SKF-10 QT-RPGCHAR-44j: 6 assets, 81 clips (packs: QT-RPGCHAR×6)
- SKF-09 GH-VUENA-22j (Mixamo bone names): 8 assets, 80 clips (packs: GH-VUENA×8)
- SKF-52 QT-UAL1-53j: 1 assets, 46 clips (packs: QT-UAL1×1)
- SKF-05 QT-UBC-65j: 12 assets, 43 clips (packs: QT-UBC×10, QT-UAL2×2)
- SKF-11 QT-CUTEMON-7j: 5 assets, 32 clips (packs: QT-CUTEMON×5)
- SKF-18 QT-FARMANI-39j: 3 assets, 18 clips (packs: QT-FARMANI×3)
- SKF-15 QT-FPROPS-3j: 3 assets, 12 clips (packs: QT-FPROPS×1, QT-SCIFI×1, QT-SCIESS×1)
- SKF-06 OGA-CITYZOMBIE-66j (Mixamo bone names): 11 assets, 11 clips (packs: OGA-CITYZOMBIE×11)

Cross-family notes:
- QT-UBC base bodies, QT-UAL2 (UAL2_Standard.glb, Mannequin_F.glb) and the QT-UAL1 FBX share Quaternius' 65-joint Universal rig; the UAL1 Godot GLB uses a 53-joint variant (compare joint names before sharing clips).
- KK-ANIMS Rig_Medium_* clips target the KayKit "Medium" rig (Mannequin_Medium); KayKit 1.0 Adventurers/Skeletons use an older 41-joint rig and already embed their own clips.
- KN-MINICHAR characters and Kenney Graveyard/Mini Dungeon/Mini Shop/Mini Forest characters share the Kenney mini-character rig (~7 joints) and the same clip names.
- GH-VUENA uses Mixamo-compatible bone names (22 bones) -> Mixamo-style clips can be retargeted by Codex if ever needed (not done here).
- OGA-CITYZOMBIE: model + 11 separate animation FBX files on the same 66-joint rig (load model, then add clips from the animation files).

## 5. Animation clips
Total clips read from files: 4297. Per category (multi-label): Combat 889, Creature 406, Dialogue 455, Horror 9, Idle 536, Interaction 1002, Locomotion 1061, Reaction 322, Swimming 10, Uncategorized 469.
FBX clip names usually come as `Armature|Name` or `CharacterArmature|Name`; match on the part after `|`. No clips were created, retargeted or edited.

## 6. File formats
GLB (primary) > glTF (+ .bin + textures beside it) > FBX (only where the pack ships no glTF; FBX 7.x) > OBJ+MTL (static community items).
- Kenney GLBs reference `Textures/colormap.png` (external) — keep the `Textures/` folder next to the GLB.
- Quaternius megakit glTFs reference textures by bare filename; the needed PNGs were copied beside the glTF files (originals untouched).
- Texture-not-linked FBX (assign manually, file is beside the model): QT-CUTEMON (`<Name>_Texture.png`), DK-MONSTERS (`Color_01.png`), OGA-HORRORMON (`Colors/<color>/...AlbedoTransparency.png`), Kenney Animated Characters (`Skins/*.png`).
- Unresolvable source omissions (shipped without .mtl/texture): OGA-HORRORMAP, OGA-COFFIN, OGA-DIVEHELM, OGA-MOTO, OGA-ROWBOAT, OGA-BONEGOLEM, OGA-OCEANTRIO → they load untextured.
- Scale/orientation differ per pack (FBX often in centimetres). Normalize with a bounding box (`loaded_bbox_size` in the registry is from three.js).

## 7. Loading in Three.js
```js
import * as THREE from 'three';
import { GLTFLoader } from 'three/addons/loaders/GLTFLoader.js';
import { FBXLoader } from 'three/addons/loaders/FBXLoader.js';
const gltf = await new GLTFLoader().loadAsync('01_Characters/Elderly_Male/GH-SCITIZIA/multidao_03.glb');
const model = gltf.scene; const mixer = new THREE.AnimationMixer(model);
mixer.clipAction(THREE.AnimationClip.findByName(gltf.animations, 'andar')).play();   // walk
// facial morphs (Scitizia cast): mesh.morphTargetDictionary.sorriso -> mesh.morphTargetInfluences[i] = 1
const fbx = await new FBXLoader().loadAsync('01_Characters/Elderly_Female/QT-UACP/OldClassy_Female.fbx');
fbx.scale.setScalar(0.01);   // many FBX are in cm
const idle = fbx.animations.find(c => c.name.endsWith('|Idle')); new THREE.AnimationMixer(fbx).clipAction(idle).play();
// skin swap (Kenney animated characters)
const tex = await new THREE.TextureLoader().loadAsync('01_Characters/Skinnable_Base/<KN-ANIMCHAR folder>/Skins/zombieA.png');
tex.colorSpace = THREE.SRGBColorSpace; kenneyFbx.traverse(o => o.isMesh && (o.material.map = tex, o.material.needsUpdate = true));
// sharing clips: only between assets of the same skeleton_family (bone names must match)
```
Each production file was loaded with three.js r160 GLTFLoader/FBXLoader/OBJLoader in headless Chromium: 5029 OK, 2 failed (registry `threejs_load_test`).

## 8. Materials & textures
Most stylized packs use one small atlas/colormap per pack (cheap to recolor via `material.color` or by swapping the atlas). Poly Haven sets in `09_Materials_Textures/PH_PBR_Textures_1k/<id>/` (diff, nor_gl, rough/arm). HDRIs in `PH_HDRI_1k/` (night, forest, overcast, abandoned interiors) for RGBELoader/PMREM.

## 9. Category limits
- Characters: many chibi/blocky proportions; Scitizia is realistic-proportion but pixel-textured; UACP faces are black. Mixing packs needs unified materials/lighting.
- Indonesia-specific clothing/architecture/religious buildings: not available as free CC0 assets; use generic tropical vegetation (Quaternius/KayKit), modular houses and recolor.
- Supernatural: mostly spooky-cute or low-poly; true horror comes from lighting/material. Shadow entities, aquatic monsters and giant creatures are thin.
- Vehicles: cars/police/ambulance/bus/trains/boats/helicopter/1 motorcycle (OBJ). Few have separate wheel nodes animated; Kenney car-kit wheels are separate nodes.
- Underwater/diving: only Poly Haven roots, buoys/lifebuoy, diving helmet (OBJ), life jacket, rubber boots. No diver character, no scuba cylinder.
- Animations: humanoid swimming only via QT-UAL1 (Swim_Fwd_Loop, Swim_Idle_Loop) on the Quaternius UAL rig; no lip-sync clips; Scitizia morphs are the only facial controls.

## 10. Licenses & attribution
All production assets: CC0 except a few CC BY 3.0/4.0 community items (attribution REQUIRED, ready-made credit lines in `AssetLicenses.md`). Filter `attribution_required==true`. License files: `11_Licenses/<PACK_CODE>/`.

## 11. Need an asset that is missing?
Open `10_Source_Archives/SOURCE_INVENTORY.md` (machine-readable: `SOURCE_INVENTORY.json`):
- Section A: every source already used, with direct download URLs + SHA-256 (re-download to get the FBX/OBJ/Blend alternatives that were not copied into the library).
- Section B: candidates not downloaded yet — official Quaternius/Kenney OpenGameArt packs, itch.io packs with free/paid status, community items with checked licenses, Poly Haven ids not used, KayKit repos not cloned, unscanned search leads.
- "How to fetch" table: per-host access method (OpenGameArt direct links, itch.io free download endpoint, git clone, Poly Haven API) and known blocks (Google Drive quota, kenney.nl 403, Poly Pizza Cloudflare).
After downloading: check license, prefer GLB/glTF, run a three.js load test, add an entry to AssetRegistry.json with the same fields.
