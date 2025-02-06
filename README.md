This repository contains the code for rendering glb files using PyTorch3D and unprojecting rendered rgb and depth to the world coordinate system, including the following steps:

- load a mesh from an `glb` file
- initialize a `Camera`, `Shader` and `Renderer`,
- render a mesh to rgb and depth
- compute a point's screen position
- unproject rendered rgb and depth to the world coordinate system
