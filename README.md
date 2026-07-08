# ForgeBrief Nocturne Visual Review

This repository contains visual review artifacts only for the local Nocturne companion prototype.

The main ForgeBrief project remains local. This repository intentionally does not include source code, state files, VRM files, Godot project files, VRoid project files, runtime logs, API keys, or private project internals.

## Current Visual

```text
nocturne_v4_material_test_blender.png
```

This image shows a copied-asset Blender material/color test on the v4 Nocturne VRM0 asset. It is not a new runtime surface and no modified VRM/GLB is included here. The test darkens hair, clothing, and trim materials toward black/violet/silver to judge whether material work can move the avatar closer to Nocturne.

Previous Blender inspection:

```text
blender_import_inspection.png
```

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
- whether the darker black/violet/silver material direction helps
- whether the remaining frill/default-costume structure is still too dominant
- whether material work is enough or texture/mesh/clothing work is needed next
- whether movement should remain blocked until the avatar reads more clearly as Nocturne

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
- Blender `.blend` files
- secrets or tokens
