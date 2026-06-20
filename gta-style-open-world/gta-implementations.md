# GTA Reimplementations and References

Godot-family GTA reimplementations, plus non-Godot reference engines useful for understanding GTA1's map data, asset formats, and game structure when building a Godot clone.

Last reviewed: 2026-06-20.

## Godot / Redot Implementations

| Repository | Inspired by | Notes |
|---|---|---|
| [FOSS-Supremacy/OpenLiberty](https://github.com/FOSS-Supremacy/OpenLiberty) | GTA III | GTA III reimplementation in Godot/Redot Engine. Loads original map and collision data, streams models and textures from the player-supplied game files. Most mature GTA-style project in the Godot ecosystem; study it for how to structure a GTA-style Godot project. |

## GTA1 Reference Implementations (Non-Godot)

These are not Godot projects, but are the best open-source references for GTA1's map layout, block/sprite data, vehicle physics, and game logic.

| Repository | Language | Notes |
|---|---|---|
| [codenamecpp/carnage3d](https://github.com/codenamecpp/carnage3d) | C++ | Full GTA1 reimplementation with a web build. Uses Box2D for physics and OpenGL for rendering. The primary technical reference for accurate GTA1 pedestrian AI, vehicle handling, and mission triggers. |
| [GitExl/GTAViewer](https://github.com/GitExl/GTAViewer) | Python | Map/asset viewer for GTA1, GTA1 demos, GTA London, and GTA2. Parses and dumps sprite atlases, block tile textures, and map structure — essential for understanding GTA1 data formats before writing an importer. |
| [madebr/OpenGTA](https://github.com/madebr/OpenGTA) | C | Copy of the original OpenGTA project; older and less active, but documents the GTA1 file format and engine loop in C. Treat as historical reference. |
