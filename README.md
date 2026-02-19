# software-raster

A software rasterizer and 3D viewer built from scratch in C++ to deeply understand how GPUs render graphics.

## What I'm Implementing

### Rasterizer
- Line drawing (Bresenham's algorithm)
- Triangle rasterization (edge equations, barycentric coordinates)
- Z-buffer (depth testing)
- 3D transforms (model, view, projection matrices)
- Perspective projection
- Clipping (Sutherland-Hodgman)
- Texture mapping with UV coordinates
- Phong shading (ambient, diffuse, specular lighting)

### 3D Viewer
- OBJ file loader
- Camera controls (orbit, zoom, pan)
- Scene management (multiple objects)
- Real-time rendering with SDL2

## Resources
- [tinyrenderer](https://github.com/ssloy/tinyrenderer) - Primary reference
- [Scratchapixel](https://www.scratchapixel.com/) - Theory deep dives
- [Computer Graphics from Scratch](https://gabrielgambetta.com/computer-graphics-from-scratch/) - Additional reference
