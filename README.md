# Nir David-Duani

Computer Science student focused on **algorithms, computer vision, and applied AI systems**.

---

# Featured Projects

## Deep Learning: From Classification to Detection
**Python · PyTorch · Computer Vision · Deep Learning**

A deep learning project exploring the transition from **image classification to object detection** using transfer learning.

Starting from a pretrained **ResNet-18 classifier**, the system evolves through three stages:

- **Backbone analysis** – studying ResNet-18 as a feature extractor and analyzing its feature hierarchy  
- **Single-object detection** – adapting the classifier to regress a bounding box for a safety vest  
- **Multi-object detection** – extending the model to detect **helmet, person, and vest** using a fixed-slot architecture  

The project focuses on **architectural reasoning, detection loss design, and IoU-based evaluation**.

### Single-Object Detection (Safety Vest)

<p align="center">
  <img src="media/single_object.gif" width="340">
  <img src="media/single_object1.gif" width="340">
</p>

A ResNet-18 backbone with a lightweight regression head predicts a **single normalized bounding box per frame**.

### Multi-Object Detection (Helmet · Person · Vest)

<p align="center">
  <img src="media/multi_object.gif" width="340">
  <img src="media/multi_object1.gif" width="340">
</p>

The detector predicts **up to three objects per frame** using fixed prediction slots and an **IoU-aware loss** for improved localization.

Repository  
https://github.com/Nir-David-Duani/classification-to-detection

---

## Planar Augmented Reality
**Python · OpenCV · Camera Geometry · Pose Estimation**

An augmented reality pipeline that tracks planar targets in video and renders virtual content with correct **perspective, camera pose, and occlusion handling**.

The system combines **camera calibration, homography tracking, and pose estimation (solvePnP)** to align virtual 3D objects with the real scene.

### Occlusion Handling

<p align="center">
<img src="media/ar_occlusion_hand.gif" width="280">
</p>

### Multi-Plane Tracking

<p align="center">
  <img src="media/part5_multi_plane_video_portal360vid5.gif" width="280">
  <img src="media/part5_multi_plane_video_portal3602.gif" width="280">
</p>

### Cube Rendering (Pose Estimation)

<p align="center">
<img src="media/part2_cube.gif" width="280">
</p>

Repository  
https://github.com/Nir-David-Duani/augmented-reality-planar

---

## Lane Detection from Driving Videos
**Python · OpenCV · Computer Vision**

A computer vision system for detecting **lane boundaries and road structure** in driving videos across multiple scenarios including curved roads, crosswalks, and lane changes.

The project emphasizes **geometric reasoning, temporal consistency, and robustness across environments**.

### Crosswalk Detection

<p align="center">
<img src="media/lane_crosswalk.gif" width="550">
</p>

### Lane Tracking and Lane Change Detection

<p align="center">
<img src="media/lane_change.gif" width="550">
</p>

### Curved Lane Detection

<p align="center">
<img src="media/curve_detection_25_30_720.gif" width="550">
</p>

### Night Driving Scenario

<p align="center">
<img src="media/night_lane.gif" width="550">
</p>

Repository  
https://github.com/Nir-David-Duani/lane-detection

---

## Perfect Phylogeny (PP-Linear)
**Java · Algorithms · Graph Algorithms**

An implementation of the **Unrooted Perfect Phylogeny algorithm** with **O(n · m)** time complexity, focusing on algorithmic correctness and computational efficiency.

Repository  
https://github.com/Nir-David-Duani/pp-linear

---

# Technical Focus

- Computer Vision
- Deep Learning for Visual Recognition
- Algorithms and Data Structures
- Geometry and Optimization

---

# Contact

LinkedIn  
https://www.linkedin.com/in/nir-david-duani

GitHub  
https://github.com/Nir-David-Duani
