# Libraries, Tools, and Standards

Back to the main index: [README](README.md)

---

## Geometry Modeling / Geometry Processing / Mesh Work

| Name | Type | Best For | Notes | Link |
|---|---|---|---|---|
| CGAL | C++ computational geometry library | Boolean ops, triangulation, Voronoi, arrangements, mesh generation, robust geometry | Academic and industrial grade | [Official Site](https://www.cgal.org/) |
| libigl | C++ geometry processing library | Laplacians, parameterization, deformation, reconstruction, mesh algorithms | Excellent for research prototyping | [Official Site](https://libigl.github.io/) |
| geometry-central | Modern C++ geometry processing library | Surface mesh data structures, intrinsic geometry, geometric operators | Great for learning modern geometry code style | [Official Site](https://geometry-central.net/) |
| OpenMesh | Mesh data structure library | Half-edge and polygon mesh editing | Mature and widely known | [Official Site](https://www.openmesh.org/) |
| OpenSubdiv | Subdivision surface library | Subdivision evaluation for animation and film pipelines | Important in the Pixar ecosystem | [Official Site](https://www.opensubdiv.org/) |
| TetGen | Tetrahedral meshing tool | Tetrahedral mesh generation and constrained Delaunay meshing | Common in simulation preprocessing | [Official Site](https://wias-berlin.de/software/tetgen/) |
| Polyscope | Visualization and debugging tool | Inspecting meshes, point clouds, scalar fields, vector fields | Extremely useful for geometry debugging | [Official Site](https://polyscope.run/) |
| Geogram | Geometry algorithm library | Delaunay, Voronoi, parameterization, numerical geometry | Strong for research-oriented geometry work | [Official Site](https://brunolevy.github.io/geogram/index.html) |
| PMP Library | Polygon mesh processing library | Surface mesh work, remeshing, smoothing, curvature, simplification | Clean and modern | [Official Site](https://www.pmp-library.org/) |
| MeshLab | Mesh processing software | Mesh cleanup, repair, simplification, reconstruction, conversion | Very practical for real-world input data | [Official Site](https://www.meshlab.net/) |
| Open3D | 3D data processing library | Point clouds, meshes, reconstruction, visualization | Good bridge between geometry and 3D vision | [Official Site](https://www.open3d.org/) |
| Assimp | Asset import library | Reading many 3D asset formats | Useful in graphics pipelines | [Official Site](https://assimp.org/) |

---

## Rendering / Ray Tracing / Real-Time Graphics

| Name | Type | Best For | Notes | Link |
|---|---|---|---|---|
| pbrt-v4 | Research renderer | Physically based rendering, path tracing, light transport | Pairs with one of the best rendering books | [Official Site](https://pbrt.org/) |
| Mitsuba 3 | Research rendering system | Forward and inverse rendering, differentiable rendering, spectral rendering | Common in research | [Official Site](https://www.mitsuba-renderer.org/) |
| Embree | High-performance ray tracing kernels | CPU ray intersection and BVH acceleration | Very useful when building your own renderer | [Official Site](https://www.embree.org/) |
| Vulkan Samples | Graphics API sample collection | Learning modern Vulkan workflows | Practical reference set | [Official Repository](https://github.com/KhronosGroup/Vulkan-Samples) |
| OSPRay | CPU ray tracing / visualization framework | Scientific visualization, volume rendering, CPU rendering | Important in Intel’s visualization stack | [Official Site](https://www.ospray.org/) |
| Blender | Open-source DCC application | Modeling, shading, animation, geometry nodes, scripting | Also a major ecosystem for experimentation | [Official Site](https://www.blender.org/) |
| OpenImageIO | Image I/O toolkit | Reading and writing many image formats, HDR workflows, texture pipelines | Useful in graphics toolchains and renderers | [Documentation](https://openimageio.readthedocs.io/) |

---

## Volumetric / Implicit / Sparse Voxel Systems

| Name | Type | Best For | Notes | Link |
|---|---|---|---|---|
| OpenVDB | Sparse volumetric data structure library | Level sets, voxel modeling, sparse volume processing | A major standard in VFX and volume workflows | [Official Site](https://www.openvdb.org/) |
| NanoVDB | Lightweight / GPU-friendly OpenVDB variant | GPU volume access and real-time applications | Useful for real-time volume rendering | [Official Site](https://developer.nvidia.com/nanovdb) |
| libfive | Functional / implicit solid modeling system | Programmatic implicit modeling, SDF-style workflows | Highly relevant for implicit modeling | [Official Site](https://libfive.com/) |

---

## CAD / Solid Modeling / Robust Geometry

| Name | Type | Best For | Notes | Link |
|---|---|---|---|---|
| Manifold | Triangle-mesh solid geometry library | Manifold mesh Booleans and robust solid-style mesh ops | Good engineering-oriented option | [Repository](https://github.com/elalish/manifold) |
| Open CASCADE Technology (OCCT) | Open-source CAD kernel | B-rep, STEP/IGES workflows, solid modeling, CAD exchange | Important for CAD and engineering pipelines | [Documentation](https://dev.opencascade.org/doc/overview/html/) |
| Gmsh | Mesh generator | 2D/3D meshing, CAD + mesh preprocessing | Common in engineering workflows | [Official Site](https://gmsh.info/) |
| TetWild | Robust tetrahedral meshing | Tetrahedralization from messy surface input | Useful for hard real-world input | [Official Site](https://wildmeshing.github.io/tetwild/) |
| fTetWild | Faster robust tetrahedral meshing | Practical robust tetrahedral meshing | Performance-oriented variant | [Repository](https://github.com/wildmeshing/fTetWild) |

---

## Scene Description / Materials / Image Formats / Color Management

| Name | Type | Best For | Notes | Link |
|---|---|---|---|---|
| OpenUSD | Scene description and interchange | Large 3D scenes, collaboration, cross-tool exchange | Increasingly important in modern pipelines | [Official Site](https://openusd.org/) |
| MaterialX | Material and look-development standard | Exchanging material graphs across tools | Valuable in production workflows | [Official Site](https://materialx.org/) |
| Open Shading Language (OSL) | Shading language | Materials, lighting, displacement, procedural texturing | Common in offline rendering | [Documentation](https://open-shading-language.readthedocs.io/en/main/) |
| OpenEXR | HDR image format | High dynamic range imagery and multi-channel outputs | Essential in high-end rendering | [Official Site](https://openexr.com/) |
| OpenColorIO (OCIO) | Color management system | Color pipelines across animation and VFX tools | Widely used in production | [Official Site](https://opencolorio.org/) |

---

## Exchange Formats and Compression Standards

| Name | Type | Best For | Notes | Link |
|---|---|---|---|---|
| glTF | 3D asset transmission standard | Runtime assets, web graphics, lightweight model exchange | Very important for modern real-time pipelines | [Official Page](https://www.khronos.org/gltf/) |
| glTF Registry | Specification portal | Checking glTF 2.0 specs and extensions | Useful for import/export tooling | [Registry](https://registry.khronos.org/glTF/) |
| glTF Validator | Validation tool | Testing whether glTF / GLB files are valid | Great for pipeline debugging | [Official Tool](https://github.khronos.org/glTF-Validator/) |
| KTX 2.0 | GPU texture standard | Texture compression and transport | Closely related to real-time asset workflows | [Official Page](https://www.khronos.org/ktx/) |
| Draco | Geometry compression library | Compressing meshes and point clouds | Common for web and transmission workflows | [Official Site](https://google.github.io/draco/) |

---

## Recommended Shortlists

### If you focus on geometry processing
- CGAL
- libigl
- geometry-central
- OpenMesh
- PMP Library
- Geogram
- Polyscope

### If you focus on robust solid geometry or CAD
- CGAL
- Manifold
- OCCT
- TetGen
- TetWild / fTetWild
- Gmsh

### If you focus on implicit modeling or volumes
- OpenVDB
- NanoVDB
- libfive

### If you focus on rendering
- pbrt-v4
- Mitsuba 3
- Embree
- OpenEXR
- OSL
- OCIO

---

## Related Files

- [Courses and Tutorials](graphics_courses_and_tutorials.md)
- [Datasets and Asset Resources](graphics_datasets_and_assets.md)
- [Geometry / Mesh / Implicit / Robust Geometry Map](graphics_geometry_mesh_implicit.md)
