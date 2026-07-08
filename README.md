# ForgeBrief Nocturne Visual Review

This repository contains visual review artifacts only for the local Nocturne companion prototype.

The main ForgeBrief project remains local. This repository intentionally does not include source code, state files, VRM files, Godot project files, VRoid project files, runtime logs, API keys, or private project internals.

## Current Visual

```text
blender_import_inspection.png
```

This image shows a Blender import inspection of the v4 Nocturne VRM0 asset. It is not an edited avatar and not a new runtime surface; it is visual evidence for the Blender/custom asset-production gate. The inspection makes the remaining issue clearer: the avatar imports, but the white frill/default costume structure still dominates the design.

Latest Godot staging screenshot:

```text
nocturne_vrm0_v4_staging.png
```

Earlier comparison images are also retained:

```text
nocturne_vrm0_import_scene.png
nocturne_vrm0_staging_polish.png
nocturne_vrm0_v2_staging.png
nocturne_vrm0_v3_staging.png
nocturne_vrm0_v4_staging.png
```

## How To Review

Share the GitHub image link or raw image link with ChatGPT for visual inspection.

Suggested inspection focus:

- avatar visibility
- scale
- pose and orientation
- materials/textures
- whether the white frill/default-costume structure is too dominant
- whether Blender material/color editing is worth testing on a copy
- whether the next local ForgeBrief task should do a copied-asset material/color test or switch asset-production strategy

## Not Included

This visual-review repository does not include:

- `companion_state.json`
- `nocturne_avatar.vrm`
- `nocturne_avatar_vrm0.vrm`
- `nocturne_avatar_v2.vrm`
- `nocturne_avatar_v2_vrm0.vrm`
- `nocturne_avatar_v3.vrm`
- `nocturne_avatar_v3_vrm0.vrm`
- `nocturne_avatar_v4.vrm`
- `nocturne_avatar_v4_vrm0.vrm`
- ForgeBrief source/runtime files
- Godot project folders
- VRoid project files
- Blender scripts or project files
- secrets or tokens
