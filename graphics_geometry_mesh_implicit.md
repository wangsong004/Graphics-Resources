# Geometry / Mesh / Implicit / Robust Geometry Map

Back to the main index: [README](README.md)

This file is the most specialized section in the repository. It is aimed at readers working on mesh processing, robust geometry, solid geometry, implicit modeling, tetrahedral meshing, and CAD-related geometry kernels.

---

## Task-Oriented Entry Map

| What You Want to Do | Start With | Then Add | Typical Resources |
|---|---|---|---|
| Basic triangle mesh processing | Lightweight C++ geometry libraries | Visualization and cleanup tools | libigl, PMP, OpenMesh, MeshLab |
| Curvature, Laplacians, parameterization, spectral geometry | Geometry processing libraries + courses | More mathematical foundations | geometry-central, libigl, DDG |
| Booleans, CSG, robust solid operations | Robust geometry libraries and solid kernels | CAD kernels or volume-based workflows | CGAL, Manifold, OCCT, OpenVDB |
| Surface-to-volume meshing | Tetrahedral meshing tools | Quality improvement and robust meshing | TetGen, TetWild, fTetWild, Gmsh |
| Scan data / point cloud / RGB-D to mesh | 3D data processing frameworks | Cleanup and reconstruction tools | Open3D, MeshLab, ScanNet |
| Implicit modeling / SDF / functional representation | Implicit modeling libraries | Sparse voxel and neural implicit material | libfive, OpenVDB, NanoVDB |
| CAD / curves / surfaces / B-rep / STEP | CAD kernels and exchange formats | Meshing and engineering tools | OCCT, Gmsh, glTF, USD |
| Large-scale shape research and geometry learning | Shape datasets | Benchmarks and conference papers | ShapeNet, ABC, Objaverse, SGP |

---

## Core Libraries for Geometry / Mesh / Robust Geometry

### Lightweight Geometry Processing and Surface Mesh Work

| Name | Core Positioning | Best For | When to Pick It | Link |
|---|---|---|---|---|
| libigl | Lightweight geometry processing library | Laplacians, parameterization, deformation, remeshing, geometric prototyping | When you want fast algorithm prototyping without a heavy framework | [Official Site](https://libigl.github.io/) |
| geometry-central | Modern surface mesh and geometry library | Intrinsic / extrinsic geometry, modern data structures | When you want a clean modern API and strong geometric abstractions | [Official Site](https://geometry-central.net/) |
| PMP Library | Modern polygon mesh processing library | Simplification, subdivision, smoothing, remeshing, curvature analysis | When you want a neat and practical C++ mesh library | [Official Site](https://www.pmp-library.org/) |
| OpenMesh | Classic mesh data structure library | Half-edge mesh editing and topology support | When you want a mature and well-known mesh base | [Official Site](https://www.openmesh.org/) |
| Geogram | Geometry algorithm library | Delaunay, Voronoi, parameterization, numerical geometry | When you want a research-oriented geometry toolkit | [Official Site](https://brunolevy.github.io/geogram/index.html) |

### Robust Geometry / Solid Modeling / CAD Kernels

| Name | Core Positioning | Best For | Why It Matters | Link |
|---|---|---|---|---|
| CGAL | Classic computational geometry library | Booleans, triangulation, AABB queries, arrangements, robust geometry, PMP | One of the broadest and most deeply grounded geometry libraries | [Official Site](https://www.cgal.org/) |
| Manifold | Robust triangle-mesh solid geometry library | Manifold mesh Booleans and reliable solid-style triangle mesh output | Good when you want practical and stable solid mesh operations | [Repository](https://github.com/elalish/manifold) |
| Open CASCADE Technology (OCCT) | Open-source CAD kernel | B-rep, STEP/IGES exchange, CAD geometry, solid modeling | Highly relevant for engineering and CAD workflows | [Documentation](https://dev.opencascade.org/doc/overview/html/) |
| libfive | Functional / implicit solid modeling system | Programmatic solid modeling, SDF-like workflows, implicit shape composition | Very relevant if you care about implicit modeling | [Official Site](https://libfive.com/) |
| OpenVDB | Sparse volume and level-set framework | Sparse volumes, level sets, voxel workflows, implicit volumetric pipelines | Extremely useful for implicit and volumetric approaches | [Official Site](https://www.openvdb.org/) |

### Surface-to-Tetrahedral Meshing

| Name | Core Positioning | Best For | Notes | Link |
|---|---|---|---|---|
| TetGen | Tetrahedral mesh generation | Constrained Delaunay tetrahedralization and volume meshing | Classic and widely used | [Official Site](https://wias-berlin.de/software/tetgen/) |
| TetWild | Robust tetrahedral meshing | Tetrahedralization from difficult, messy surface input | Good for hard real-world models | [Official Site](https://wildmeshing.github.io/tetwild/) |
| fTetWild | Faster robust tetrahedral meshing | Performance-oriented tetrahedral meshing | Practical version of robust meshing ideas | [Repository](https://github.com/wildmeshing/fTetWild) |
| Gmsh | General mesh generator | CAD + mesh pipelines and engineering preprocessing | Common in engineering and simulation workflows | [Official Site](https://gmsh.info/) |

### Preprocessing / Inspection / Validation Tools

| Name | Best Used For | Link |
|---|---|---|
| MeshLab | Viewing, cleaning, repairing, and converting meshes | [Official Site](https://www.meshlab.net/) |
| Open3D | Point clouds, RGB-D, reconstruction, and rapid 3D prototyping | [Official Site](https://www.open3d.org/) |
| Blender | Quick inspection, geometry experiments, Geometry Nodes workflows | [Official Site](https://www.blender.org/) |
| Assimp | Importing and exporting many 3D file formats | [Official Site](https://assimp.org/) |
| Polyscope | Visual debugging for geometry algorithms | [Official Site](https://polyscope.run/) |

---

## Datasets Most Relevant to This Area

### Shape / CAD / Engineering Geometry

| Name | Main Use | Why It Is Relevant | Link |
|---|---|---|---|
| ShapeNet | General 3D shapes | Classic starting point for shape analysis and geometry learning | [Official Site](https://shapenet.org/) |
| ABC Dataset | CAD models with geometric structure | Excellent for CAD-related geometry and patch-level analysis | [Official Site](https://deep-geometry.github.io/abc-dataset/) |
| Thingi10K | Real-world printable meshes | Very good for messy real-world mesh problems | [Official Site](https://ten-thousand-models.appspot.com/) |
| Objaverse / Objaverse-XL | Large-scale object collection | Useful for large-scale asset analysis and modern 3D research | [Official Site](https://objaverse.allenai.org/) |

### Scene Reconstruction / RGB-D / Scan-Based Geometry

| Name | Main Use | Link |
|---|---|---|
| ScanNet | Indoor scene reconstruction and scene understanding | [Official Site](https://www.scan-net.org/) |
| Matterport3D | Large-scale indoor 3D spaces | [Official Site](https://niessner.github.io/Matterport/) |
| HM3D | High-resolution indoor digital spaces | [Official Site](https://aihabitat.org/datasets/hm3d/) |

### Human / Non-Rigid / Dynamic Meshes

| Name | Main Use | Link |
|---|---|---|
| FAUST | Static human correspondence benchmarks | [Official Site](https://faust-leaderboard.is.tuebingen.mpg.de/) |
| DFAUST | Dynamic human geometry | [Official Site](https://dfaust.is.tue.mpg.de/) |
| AMASS | Human motion data | [Official Site](https://amass.is.tue.mpg.de/) |
| SMPL | Parametric human model | [Official Site](https://smpl.is.tue.mpg.de/) |

---

## Courses and Tutorials Worth Revisiting for This Area

| Resource | Why It Matters | Link |
|---|---|---|
| Stanford CS348A | A strong course for modeling, curves, surfaces, and mesh processing | [Course Portal](https://graphics.stanford.edu/courses/) |
| Discrete Differential Geometry (DDG) | One of the best long-term foundations for geometry processing | [Official Site](https://brickisland.net/ddg-web/) |
| MIT 2.158J Computational Geometry | Strong background in CAD, CSG, geometric modeling, and robustness | [Official Site](https://ocw.mit.edu/courses/2-158j-computational-geometry-spring-2003/) |
| libigl Tutorial | Highly practical for implementation work | [Tutorial](https://libigl.github.io/tutorial/) |

---

## Practical Task Entry Table

### I want to clean, repair, or inspect triangle meshes
Start with:
- MeshLab

Then use:
- Open3D
- libigl
- PMP Library

If topology or robust Booleans are involved, also consider:
- CGAL
- Manifold

Typical keywords:
- non-manifold
- self-intersection
- duplicate vertices
- duplicate faces
- hole filling
- remeshing
- decimation

### I want to do mesh Booleans / solid geometry / arrangements
Start with:
- CGAL

For a more engineering-friendly path:
- Manifold

If CAD / STEP / B-rep is involved:
- OCCT

If you want to move toward volumetric or implicit approaches:
- OpenVDB
- libfive

Long-term venues to watch:
- SIGGRAPH
- SIGGRAPH Asia
- SGP
- CAD
- CAGD
- Computers & Graphics

### I want to tetrahedralize surface meshes
Start with:
- TetGen

If input is messy:
- TetWild
- fTetWild

If you also need engineering meshing:
- Gmsh
- OCCT

### I want to work on implicit modeling / SDF / level sets
Start with:
- libfive

For sparse volume / level-set workflows:
- OpenVDB

For GPU-facing volume workflows:
- NanoVDB

Helpful surrounding ecosystem:
- Blender Geometry Nodes
- Inigo Quilez’s SDF material
- OpenVDB-based pipelines

### I want to prototype geometry processing algorithms
Start with:
- libigl

If you want a more modern abstraction:
- geometry-central

For mathematical depth:
- DDG

Useful datasets:
- ShapeNet
- ABC Dataset
- FAUST / DFAUST

---

## Recommended Minimal Bookmark Set

- CGAL
- libigl
- geometry-central
- Geogram
- PMP Library
- OpenVDB
- Embree
- OpenUSD
- SIGGRAPH
- SGP
- Computer-Aided Design
- Ke-Sen Huang's Resource Page

---

## Related Files

- [Libraries, Tools, and Standards](graphics_libraries_tools_and_standards.md)
- [Datasets and Asset Resources](graphics_datasets_and_assets.md)
- [Conferences, Journals, and Publications](graphics_conferences_and_publications.md)
- [Blogs, Websites, and Video Channels](graphics_blogs_websites_and_videos.md)
