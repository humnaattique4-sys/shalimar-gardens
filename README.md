# Shalimar Gardens, Lahore — Charbagh Collective

An interactive heritage showcase of Shalimar Gardens, a 17th-century Mughal
UNESCO World Heritage Site, built by **Charbagh Collective** (PMW × TechRealm).

🔗 **Live site:** https://humnaattique4-sys.github.io/shalimar-gardens/

## What's in this project

- History, architecture, and water-system breakdown of the gardens
- Interactive terrace and symmetry explainers
- A **3D point cloud viewer** rendering our own team-generated photogrammetric
  reconstruction (Three.js + PLYLoader), built from the pipeline in
  [`shalimar-gardens-3d-reconstruction`](https://github.com/humnaattique4-sys/shalimar-gardens-3d-reconstruction)

## Tech stack

- Plain HTML/CSS/JS — no build step, deployed via GitHub Pages
- [Three.js](https://threejs.org/) (r155) for the 3D point cloud viewer
- Fonts: Cormorant Garamond + Inter (Google Fonts)

## Reconstruction pipeline

The point cloud shown in the "3D Reconstruction" section was generated via:

1. `download_images_v2.py` — collects source imagery
2. `run_reconstruction_v2.py` — runs structure-from-motion to produce the `.ply`

See the [reconstruction repo](https://github.com/humnaattique4-sys/shalimar-gardens-3d-reconstruction)
for the full pipeline.

---
*A student heritage preservation initiative under PreserveMy.World × TechRealm.*
