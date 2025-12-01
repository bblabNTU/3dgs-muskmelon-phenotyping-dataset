# Muskmelon Greenhouse 3DGS Phenotyping Dataset

This dataset contains 3D plant geometry and organ-level instance predictions derived from greenhouse-grown muskmelon (*Cucumis melo L.*) using a 3D Gaussian Splatting (3DGS)–based phenotyping pipeline. 

## Data Overview

- **Location:** National Taiwan University Experimental Farm, muskmelon greenhouse  
- **Crop:** Muskmelon (*Cucumis melo L.*)  

The dataset consists of:

- **Phenotyping subset**
  - 6 greenhouse scenes, comprising **30 plants**
  - 3DGS Gaussian reconstructions and 3D point clouds of the plants
  - Exported organ-level segmentations (3D point clouds) from the pipeline

## Scale Factors

Per-plant scale factors for plants 01–30:

Plants 01–05: 0.2191882571
Plants 06–10: 0.2146275617
Plants 11–15: 0.2911442432
Plants 16–20: 0.5886465476
Plants 21–25: 0.2033402653
Plants 26–30: 0.2144933014

These factors can be used to rescale the per-plant geometry (e.g. when converting from reconstruction units to metric units).
