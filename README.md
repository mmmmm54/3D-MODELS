# 3D models — Mohamed Idrissi

| Project | Main files |
|---|---|
| `imara-teal-r6/`: corner apartment building R+6 | `Imara_Teal_R6.glb` (PBR), `Imara_Teal_R6_HQ.glb` (lighting baked in, for After Effects), `Imara_Teal_R6.blend`, `build_imara.py`, `bake_hq.py` |
| `mirleft-bay/`: Mirleft Bay resort, whole site + hero duplex (**Blender only**) | `scenes/Mirleft_Bay_Scene_PACKED.blend` (everything inside, open anywhere), `scenes/Mirleft_Bay_Scene.blend` (textures linked from `assets/textures/`), `renders/` (13 final 9:16 shots, incl. streets + entrance parking), `output/blender/BLENDER_RENDER_GUIDE.md` (how to open and render), `blender/20_pipeline.py` (rebuilds everything). Old D5 files are in `d5/`. |

Kept out of git: files over 100 MB (`Imara_Teal_R6_HQ.blend`, rebuild with `bake_hq.py`; the full Mirleft scene with 300k grass tufts, rebuild with `20_pipeline.py`) and all client documents.
