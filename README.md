# 3D models — Mohamed Idrissi

| Project | Main files |
|---|---|
| `imara-teal-r6/`: corner apartment building R+6 | `Imara_Teal_R6.glb` (PBR), `Imara_Teal_R6_HQ.glb` (lighting baked in, for After Effects), `Imara_Teal_R6.blend`, `build_imara.py`, `bake_hq.py` |
| `mirleft-bay/`: Mirleft Bay resort, whole site + hero duplex (**Blender only**) | `scenes/Mirleft_Bay_Scene_PACKED.blend` (everything inside, open anywhere), `scenes/Mirleft_Bay_Scene.blend` (textures linked from `assets/textures/`), `renders/` (14 final 9:16 shots, incl. streets, entrance and Tranches 1-2), `output/blender/BLENDER_RENDER_GUIDE.md` (how to open and render), `blender/20_pipeline.py` (rebuilds everything). D5: `d5/Mirleft_Bay_D5_FULL.fbx` (everything) and `d5/Mirleft_Bay_D5_NO_TREES_CARS.fbx` (to place D5 trees and cars), see `d5/D5_IMPORT_GUIDE.md`. |

Kept out of git: files over 100 MB (`Imara_Teal_R6_HQ.blend`, rebuild with `bake_hq.py`; the full Mirleft scene with 300k grass tufts, rebuild with `20_pipeline.py`) and all client documents.
