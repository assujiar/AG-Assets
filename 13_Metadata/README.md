# 13_Metadata
- raw_file_inspection.json: every model file found in every extracted pack (format validity, joints, clip names, morph targets, deps, sha256).
- production_selection.json: the one production file chosen per asset (GLB > glTF > FBX > OBJ, exact-hash dedupe).
- qc.json: post-layout integrity check (dependency resolution, registry<->disk, duplicate textures).
- threejs_load_test.json: result of loading every production model with three.js r160 loaders in headless Chromium (meshes, bones, triangles, clips+durations, failed textures).
- previews.json: official preview image provenance.
- SHA256SUMS.txt: hashes of all production files.
- download_log_*.log: raw download logs.
