# Merge Plan

## Goal

Compare `SkyCorePi` and `BloomStudio`, then build one hybrid test engine from the strongest working pieces.

## Method

1. Keep both source repos untouched.
2. Record what each project does well.
3. Identify matching systems.
4. Choose one system at a time.
5. Build adapter code when formats do not match.
6. Move only tested pieces into `hybrid_core/`.

## First Systems To Compare

- input
- editor UI
- object model
- room or scene format
- save/load
- asset handling
- export/build flow

## No-Go Rules

- No direct overwrite of source projects.
- No mass copy without notes.
- No deleting legacy material until the hybrid works.
- No renaming SkyCorePi or BloomStudio identity markers.
