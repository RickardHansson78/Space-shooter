# Latios Space Shooter Sample – Latios Framework Open Project \#1

This is my first game project using Unity DOTS. It was used to validate
new features and improvements in Latios Framework up to version 0.4 and still
serves as an example project and compatibility validation. A version of the
framework is included as an embedded package.

The Unity version is currently 2022.3.10f1

## Getting Started

The entry scene is called Title and Menu in the Scenes folder. From there you
will be able to enter playmode. The game will use a gamepad as input if a
gamepad is detected. Otherwise it will fall back to mouse and keyboard controls.

## Special Project Restrictions

All assets in the game can be modified either directly in Unity (free UPM
package tools count) or via text editors. No other tools should be required.
Currently, meshes are procedurally generated from built-in primitives. All
texturing is done procedurally using ShaderGraph. Sound Effects are generated
from USFXR.

In stark contrast to my usual style.

### Design Work

The easiest way to contribute is to design prefabs, shader graphs, and scenes.
Have a look at the existing Mission scenes to understand how the scenes and
prefabs can be put together. A fun starting place is to try and create a custom
faction with its own kind of ships.

There are a few originally planned aspects not present in these scenes:

-   A secondary spawning world where spawned ships fly through the wormhole
    effect to enter the space battle
-   Asteroid fields
-   Space stations (provide spatial reference and interconnected hangars for
    interior combat)
-   Lighting

