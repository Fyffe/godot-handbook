# godot-handbook
Useful tips and random information for using Godot after being slave to Unity for years.

## My inspectors keep folding after switching nodes
To disable inspector folding select `Editor -> Editor Settings...` in the menu bar and then inside `Interface -> Inspector` tab tick the `Disable Folding` checkbox.

<img src="./src/img/disable_folding.png?raw=true" alt="Disable inspector folding" width="512" />

## Lightning and the overall look is ugly in the built game
Add [WorldEnvironment](https://docs.godotengine.org/en/stable/classes/class_worldenvironment.html) node to your scene and set it up.

<img src="./src/img/world_environment_inspector.png?raw=true" alt="WorldEnvironment node inspector" width="256" />

## Negative Z axis is forward

[It really is](https://docs.godotengine.org/en/stable/tutorials/3d/using_transforms.html#introducing-transforms).

<img src="https://docs.godotengine.org/en/stable/_images/transforms_camera.png" alt="Godot 3D transforms" width="512" />
