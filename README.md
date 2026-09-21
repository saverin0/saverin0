# Abhishek Singh

M.Sc. Data Science. Machine learning for Earth observation and remote sensing. Berlin, Germany.

**I am looking for a PhD position in Earth observation, remote sensing or GeoAI, or a research
role in the same area.** Available immediately.

## About

I work on adapting vision foundation models to Earth observation problems where labelled data
does not exist. Most of my projects derive training labels from administrative registers, such
as crop declarations or cadastral records, that were never made for that purpose, and then deal
with the biases those labels carry.

A result that has come back in every project so far: past a small model budget, improving the
data moves accuracy further than adding model capacity does. I try to measure both sides rather
than assume it.

I build pipelines as numbered stages with pinned environments so they can be rerun by someone
else, and I evaluate on sites and conditions held out from training rather than on random splits.

## Education

- **M.Sc. Data Science**, University of Europe for Applied Sciences, Potsdam, 2024–2026.
- **B.Eng. Electronics and Communication Engineering**, Jaypee Institute of Information
  Technology, India, 2016–2020.

## Master's thesis

Carried out at the **DLR Earth Observation Center**, Oberpfaffenhofen: detection of greenhouses
and plastic-covered parcels in southern Germany from 20 cm aerial orthophotos, with no
hand-drawn annotation anywhere in training. Labels were derived from EU parcel-level crop
declarations and refined against the imagery. The detector combines a frozen satellite-pretrained
DINOv3 backbone, decoded back to 20 cm by guided feature upsampling, with a trainable ResNet-34
branch and a small fusion head. Supervised by Dr Ursula Gessner (DLR) and Prof Dr Iftikhar Ahmed
(UE). A paper is in preparation.

## Projects

**[vggt-omega-aura-benchmark](https://github.com/saverin0/vggt-omega-aura-benchmark)** — Failure
analysis of the released VGGT-Ω 3D reconstruction checkpoint on FZI-AURA, a driving dataset
published after the model and so outside its training data. Depth and pose error are broken down
by weather, lighting and object motion instead of averaged. Daytime depth on the held-out test
split reaches AbsRel 0.082; error concentrates on thin objects, people and moving vehicles.

**[Change-Detection-Using-Dinov3](https://github.com/saverin0/Change-Detection-Using-Dinov3)** —
Building change detection on frozen satellite-pretrained DINOv3 features, on SpaceNet-7 monthly
imagery and LEVIR-CD. Decoder designs compared on identical features: feature differencing at
0.56M parameters and cross-attention at 0.83M finished within 0.002 F1 of each other at 0.910 on
LEVIR-CD, so the smaller head was the one to keep. Both beat the frozen embeddings read directly
by roughly ten times on SpaceNet-7.

**[bavaria-wheat-sentinel2-oco2](https://github.com/saverin0/bavaria-wheat-sentinel2-oco2)** —
Monthly NDVI and NIRv for winter wheat across the 96 NUTS-3 regions of Bavaria, 2017–2024, from
Sentinel-2 L3A composites masked with yearly 10 m crop type maps, aggregated with exact
partial-pixel zonal statistics. The Sentinel-2 half of a two-person MSc capstone. A side analysis
matches Sentinel-2 reflectance to OCO-2 solar-induced fluorescence footprints.

## Experience

- **Student Assistant, Robotics and Perception**, TU Berlin, 2025–2026. Onboard image capture and
  control components in Python for REINCARNATE, a Horizon Europe consortium project.
- **Test Engineer**, Infosys, India, 2021–2024. Automated test pipelines in Java and JavaScript
  with Selenium and TestNG, and data validation in SQL.

## Tools

Python, PyTorch, C++17 (CMake, pybind11), SQL. GDAL, rasterio, geopandas, xarray, QGIS, Google
Earth Engine, STAC. Linux, Git, Docker, pinned environments. GPU training on A100 and HPC on LRZ
terrabyte (SLURM).

## Contact

- Email: abhishekzsingh.2p@gmail.com
- LinkedIn: [abhishekzsingh](https://www.linkedin.com/in/abhishekzsingh)
- Website: [saverin0.github.io](https://saverin0.github.io)
