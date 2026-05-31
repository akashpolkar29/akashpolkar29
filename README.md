# Akash Polkar — Robotics & Perception Engineer

**MSc Mechatronics · RWU Ravensburg-Weingarten · Research Assistant @ BTU Cottbus-Senftenberg**

I build perception systems at the intersection of hardware and intelligence — sensor fusion pipelines, real-time vision, and autonomous robot behavior. My work runs from raw point clouds and camera frames all the way to calibrated 3D detections and empirically validated sensor models.

📍 Ravensburg, Germany &nbsp;|&nbsp; 🔗 [LinkedIn](https://linkedin.com/in/akashpolkar) &nbsp;|&nbsp; 🎓 Open to Werkstudent / Internship / Thesis roles

---

## What I work on

| Domain | Details |
|---|---|
| **Sensor Fusion** | Camera–LiDAR fusion (frustum-style), RADAR–LiDAR comparative analysis, multi-modal adverse-weather perception |
| **Computer Vision** | YOLOv8 object detection & instance segmentation, depth estimation, ArUco AR marker tracking, color detection |
| **Robotics** | Autonomous robot coursework (RWU MSc), ROS integration, embedded + edge deployment |
| **ML & Data** | PyTorch, Scikit-learn, feature engineering, ML pipelines, data preprocessing |

---

## Featured projects

### 🔭 [Camera–LiDAR Sensor Fusion — KITTI](https://github.com/akashpolkar29/Evaluation-of-YOLOv8-Object-Detection-and-Depth-Estimation-on-KITTI-Dataset)
Frustum-style fusion pipeline: YOLOv8 instance segmentation masks guide association of projected Velodyne point clouds. Full calibration chain implemented from scratch (P₂ · R₀ · T_velo→cam).
- **Mean distance error:** 1.16 m across 125 detections
- **93%** of estimates within 2 m
- Includes geometric ground-point filter and Bird's-Eye View (BEV) visualisation
- Identified systematic nearest-surface bias and frustum bleed-out as dominant error sources

---

### 🌫️ [Fog Influence on Automotive Sensors — LiDAR & RADAR](https://github.com/akashpolkar29/fog-sensor-analysis)
Empirical evaluation of three sensing modalities under artificially generated fog using the RWU dataset (500 frames/sensor/condition).

| Sensor | Fog effect |
|---|---|
| Velodyne Puck (mechanical LiDAR) | Up to **85% loss** of far-range returns |
| Blickfeld Cube 1 (MEMS LiDAR) | **37% near-field backscatter gain**, 85% intensity collapse |
| TI MMWCAS-RF-EVM (77 GHz RADAR) | Essentially **unaffected** |

Empirically validates Mie vs. Rayleigh scattering physics. Quantitative case for multi-modal fusion in adverse-weather stacks.

---

### 🌦️ [Physics-Informed Weather Simulation & RADAR–Camera Fusion](https://github.com/akashpolkar29/Physics-Informed-Weather-Simulation-and-Radar-Camera-Fusion-for-Object-Detection)
Physics-grounded weather simulation combined with RADAR–camera fusion for object detection. Bridges simulation fidelity and real-world sensor behavior.

---

### 🤖 [Autonomous Robots — RWU MSc Coursework](https://github.com/akashpolkar29/autonomous-robots-rwu)
Practical robotics coursework from the RWU MSc Mechatronics programme. Covers autonomous robot behaviour, control, and perception fundamentals.

---

### 🎯 [ArUco Marker-Based Augmented Reality](https://github.com/akashpolkar29/ArUco-marker-based-Augmented-Reality)
Real-time AR system using Python, OpenCV, and ArUco fiducial markers. Homography-based 2D overlay with sub-pixel accuracy and under 5 ms latency.

---

### 🎨 [Color Identification in Images](https://github.com/akashpolkar29/Color-Identification-In-Image)
Real-time color detection system mapping detected image regions to RGB and HEX codes via a predefined color database. Detects 100+ color shades at under 50 ms/frame.

---

### 📚 [Computer Vision — Daily Learning](https://github.com/akashpolkar29/Computer-Vision---Learning)
Ongoing log of computer vision concepts, experiments, and implementations.

---

### 🧠 [ML Learning](https://github.com/akashpolkar29/ML_Learning)
Structured machine learning study — algorithms, implementations, and experiments.

---

## Stack

```
Languages    Python · C++ · MATLAB · SQL
Perception   PyTorch · OpenCV · YOLOv8 · TensorFlow
Robotics     ROS · ArUco · Velodyne · KITTI calibration
Data         Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn
Cloud/DevOps AWS · Git
```

---

## Education & research

- **MSc Mechatronics** — RWU Hochschule Ravensburg-Weingarten *(Sep 2024 – Aug 2027)*
  Focus: Deep Learning · Computer Vision · Robotics · Embedded Systems · Autonomous Driving
- **Research Assistant** — BTU Cottbus-Senftenberg *(Nov 2025 – present)*
  Applied ML research for physical and robotic systems
- **BE Mechanical Engineering** — Savitribai Phule Pune University *(2019–2023)* · GPA 8.55/10

---

*Always open to discussing sensor fusion, perception systems, or robotics. Feel free to reach out.*
