# Datasets and Asset Resources

Back to the main index: [README](README.md)

---

## 3D Shapes / CAD / Printable Models

| Name | Type | Main Content | Best For | Link |
|---|---|---|---|---|
| ShapeNet | 3D shape dataset | Large-scale 3D object models with category structure | Retrieval, classification, generation, geometry learning | [Official Site](https://shapenet.org/) |
| ModelNet | CAD dataset | Classic CAD object dataset | Baseline shape recognition and benchmarking | [Official Site](https://modelnet.cs.princeton.edu/) |
| Objaverse / Objaverse-XL | Large-scale 3D object dataset | Massive 3D object collection with metadata | 3D generation, multimodal learning, retrieval | [Official Site](https://objaverse.allenai.org/) |
| ABC Dataset | CAD / geometric dataset | CAD models with curves, surfaces, and geometric ground truth | Geometric deep learning, feature detection, CAD analysis | [Official Site](https://deep-geometry.github.io/abc-dataset/) |
| Thingi10K | 3D printing model dataset | Real-world printable models | Mesh quality analysis and manufacturing-related research | [Official Site](https://ten-thousand-models.appspot.com/) |
| TOSCA | Non-rigid shape dataset | Classic non-rigid benchmark shapes | Correspondence and non-rigid shape matching | [Official Site](http://tosca.cs.technion.ac.il/) |
| 3D-FUTURE | Furniture dataset | High-quality furniture CAD models and assets | Indoor scenes, asset modeling, generation tasks | [Official Site](https://3dfuture-dataset.github.io/) |
| YCB Object and Model Set | Object benchmark set | Common household objects and 3D models | Robotics, pose estimation, evaluation, asset testing | [Official Site](https://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/) |

---

## Scanned Scenes / Indoor Spaces / 3D Reconstruction

| Name | Type | Main Content | Best For | Link |
|---|---|---|---|---|
| ScanNet | RGB-D scene dataset | Indoor scene scans, poses, reconstruction, labels | Reconstruction, segmentation, scene understanding | [Official Site](https://www.scan-net.org/) |
| Matterport3D | Indoor scene dataset | Large-scale real indoor RGB-D and panorama data | Reconstruction, navigation, view synthesis | [Official Site](https://niessner.github.io/Matterport/) |
| HM3D | High-resolution indoor scan dataset | Building-scale indoor 3D spaces | Embodied AI, navigation, scene understanding | [Official Site](https://aihabitat.org/datasets/hm3d/) |

---

## Human Shapes / Deformation / Motion

| Name | Type | Main Content | Best For | Link |
|---|---|---|---|---|
| FAUST | Human surface dataset | High-resolution human scans and correspondences | Non-rigid registration and correspondence learning | [Official Site](https://faust-leaderboard.is.tuebingen.mpg.de/) |
| DFAUST | Dynamic human 4D dataset | Time-varying high-resolution human meshes | Dynamic registration, deformation, temporal geometry | [Official Site](https://dfaust.is.tue.mpg.de/) |
| AMASS | Human motion dataset | Unified motion capture data in parametric form | Animation, motion modeling, motion generation | [Official Site](https://amass.is.tue.mpg.de/) |
| SMPL | Parametric human model | Learnable, controllable human body model | Animation, reconstruction, human modeling | [Official Site](https://smpl.is.tue.mpg.de/) |

---

## Materials / HDRI / Asset Libraries

| Name | Type | Main Content | Best For | Link |
|---|---|---|---|---|
| Poly Haven | Asset library | CC0 materials, HDRIs, and models | Rendering tests, material studies, lighting experiments | [Official Site](https://polyhaven.com/) |
| Substance 3D Assets | Asset platform | Materials, models, lighting resources | Product visualization and content creation pipelines | [Official Site](https://substance3d.adobe.com/assets) |

---

## Suggested Dataset Bundles by Goal

### Shape / Mesh / Geometry Learning
- ShapeNet
- ModelNet
- Objaverse
- ABC Dataset
- TOSCA

### Real-World Mesh Quality / Manufacturing
- Thingi10K
- YCB Object and Model Set

### Scene Reconstruction / Indoor Spaces
- ScanNet
- Matterport3D
- HM3D
- 3D-FUTURE

### Human Geometry / Motion / Non-Rigid Shapes
- FAUST
- DFAUST
- AMASS
- SMPL

### Rendering / Lighting / Materials
- Poly Haven
- Substance 3D Assets

---

## Notes

- Some academic datasets require registration or a research-use agreement.
- It is worth separating “benchmark datasets” from “production assets” in your own workflow.
- If you work on geometry processing rather than machine learning, datasets with messy real-world meshes are often more useful than overly clean benchmark models.

---

## Related Files

- [Libraries, Tools, and Standards](graphics_libraries_tools_and_standards.md)
- [Conferences, Journals, and Publications](graphics_conferences_and_publications.md)
- [Geometry / Mesh / Implicit / Robust Geometry Map](graphics_geometry_mesh_implicit.md)
