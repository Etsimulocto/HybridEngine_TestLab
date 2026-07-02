# HybridEngine TestLab

A clean lab for comparing useful systems from two source projects without changing the originals.

## Source Projects

- Engine A: `Etsimulocto/SkyCorePi`
- Engine B: `Etsimulocto/BloomStudio`

## Core Rule

Do not merge projects directly. Audit systems, build adapters, then move only working pieces into `hybrid_core/`.

## Folder Map

```text
HybridEngine_TestLab/
├── docs/
├── legacy/
│   ├── engine_a_skycorepi/
│   └── engine_b_bloomstudio/
├── hybrid_core/
│   ├── adapters/
│   ├── assets/
│   ├── editor/
│   ├── input/
│   ├── objects/
│   ├── rooms/
│   ├── save_load/
│   ├── systems/
│   ├── ui/
│   └── utils/
├── prototypes/
├── tests/
└── restore_points/
```
