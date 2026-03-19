# Hi, I'm Malte 👋

**Robotics & AI Engineer** | M.Sc. Mechatronic Systems Engineering  
[Intelligent Agricultural Systems Research Group](https://hs-os-ag-intelligente-agrarsysteme.github.io) · Prof. Dr. Stefan Stiene · Hochschule Osnabrück  
Osnabrück, Germany

---

## What I'm working on

Building a **Real-to-Sim pipeline** for autonomous agricultural robotics — from raw LiDAR/Camera/IMU sensor data to simulation-ready Digital Twins in NVIDIA Isaac Sim from a single sensor pass.

`FAST-LIVO2 SLAM` → `3D Gaussian Splatting (3DGRUT)` → `USDZ / NuRec` → `NVIDIA Isaac Sim + PhysX`  


→ [Research topic overview](https://hs-os-ag-intelligente-agrarsysteme.github.io/topics/gaussian-slam-synthesis)

---

## Featured research

### Synthetic Data & Real-to-Sim Pipeline — AgrifoodTEF (2023–present)
Automated generation of high-fidelity Digital Twin simulation environments for autonomous agricultural robots.

- Multimodal sensor calibration: LiDAR/Camera/IMU, targetless, PTP/PPS synchronisation (Ouster, Allied Vision, Microstrain)
- FAST-LIVO2 LiDAR-Inertial-Visual SLAM for accurate pose estimation and point cloud generation
- Neural rendering via 3DGRUT with USDZ export and PhysX integration into NVIDIA Isaac Sim
- PSNR ≥ 27 dB reconstruction quality, further optimised via LVBA-based framework
- Dual simulator integration: ROS2-native Gazebo sensor plugin + NVIDIA Isaac Sim via NuRec

### Hyperspectral + LiDAR Fusion — Master's Thesis (2022–2023)
Open-source benchtop visual inspection system fusing laser line profiling and hyperspectral imaging to generate synthetic 3D plant training models for ML applications in precision agriculture.

- Dual Gocator 2350A laser line profilers + Resonon Pika L hyperspectral camera (281 channels, 400–1000 nm)
- **2.1 nm spectral resolution** and **0.019 mm Z-resolution** — exceeds state of the art at the time.
- PSO-based pixel-accurate sensor alignment; Poisson surface reconstruction; `.ply` / `.obj` export
- Implemented in Python with ROS sensor drivers and Open3D

→ [Short thesis documentation](https://hs-os-ag-intelligente-agrarsysteme.github.io/theses/malte_hagedorn)

---

## Tech stack

**Robotics & Perception**  
`SLAM` `Sensor Fusion` `Point Cloud Processing` `LiDAR / Camera / IMU` `ROS2` `Open3D`

**3D Reconstruction & Simulation**  
`3D Gaussian Splatting` `NeRF` `Novel View Synthesis` `NVIDIA Isaac Sim` `Omniverse / USD` `Gazebo`

**ML & Computer Vision**  
`PyTorch` `OpenCV` `YOLO` `Python` `NumPy` `Pandas` `C++`

**AI & Agentic Workflows**  
`Claude API` `Gemini CLI`

---

## Background

```
M.Sc. Mechatronic Systems Engineering  —  Hochschule Osnabrück
B.Sc. Mechanical Engineering           —  Hochschule Osnabrück
Research: AgrifoodTEF (EU) · Agri-Gaia · DFKI Nature Robots
```

---

## Contact

- 📧 [Mail](mailto:malte.hagedorn@hs-osnabrueck.de)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/malte-hagedorn-43b4b5261/)
- 🔬 [Intelligent Agricultural Systems Research Group](https://hs-os-ag-intelligente-agrarsysteme.github.io) · Prof. Dr. Stefan Stiene · Hochschule Osnabrück

---

*Open to roles in Robotics Engineering · AI Engineering · Technical Program Management · DACH region*
