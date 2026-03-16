# Nir David-Duani

Computer Science student focused on **algorithms, computer vision, and applied AI systems**.

---

# Featured Projects

## Deep Learning: From Classification to Detection
Python · PyTorch · Computer Vision · Deep Learning

A deep learning project exploring the transition from **image classification to object detection** using transfer learning.

Starting from a pretrained **ResNet-18 classifier**, the project evolves through three stages:

- **Backbone analysis** – understanding ResNet-18 as a feature extractor and analyzing its feature hierarchy.
- **Single-object detection** – adapting the classifier to regress a bounding box for a safety vest.
- **Multi-object detection** – extending the model to detect **helmet, person, and vest** simultaneously using a fixed-slot detection architecture.

The project focuses on **architectural reasoning, loss design, and IoU-based evaluation**.

---

### Single-Object Detection (Safety Vest)

<p>
  <img src="media/single_object.gif" width="260" style="display:inline-block; margin-right:10px;">
  <img src="media/single_object1.gif" width="260" style="display:inline-block;">
</p>

A ResNet-18 backbone with a lightweight regression head predicts a **single normalized bounding box per frame**.

---

### Multi-Object Detection (Helmet · Person · Vest)

<p>
  <img src="media/multi_object.gif" width="260" style="display:inline-block; margin-right:10px;">
  <img src="media/multi_object1.gif" width="260" style="display:inline-block;">
</p>

The detector predicts **up to three objects per frame** using fixed prediction slots and an **IoU-aware loss** to improve localization quality.

---

Repository:  
[Link to repository](https://github.com/Nir-David-Duani/classification-to-detection)
---

## Planar Augmented Reality
Python · OpenCV · Camera Geometry · Pose Estimation

An augmented reality pipeline that tracks planar targets in video and renders virtual content with correct **perspective, camera pose, and occlusion handling**.

The system combines **camera calibration, homography-based tracking, and pose estimation (solvePnP)** to align virtual 3D objects with the real scene.

### Occlusion Handling (Foreground Masking)

<img src="media/ar_occlusion_hand.gif" width="260">

### Multi-Plane Tracking with Portals

<p>
  <img src="media/part5_multi_plane_video_portal360vid5.gif" width="260" style="display:inline-block; margin-right:10px;">
  <img src="media/part5_multi_plane_video_portal3602.gif" width="260" style="display:inline-block;">
</p>

### Cube Rendering (Pose Estimation)

<img src="media/part2_cube.gif" width="260">

Repository:  
[Augmented Reality Planar Tracking](https://github.com/Nir-David-Duani/augmented-reality-planar)

---

## Lane Detection from Driving Videos
Python · OpenCV · Computer Vision

A computer vision system for detecting **lane boundaries and road structure** in driving videos across multiple scenarios including curved roads, crosswalks, and lane changes.

The project emphasizes **geometric reasoning, temporal consistency, and robustness to environmental changes**.

### Crosswalk Detection

<img src="media/lane_crosswalk.gif" width="520">

### Lane Tracking and Lane Change Detection

<img src="media/lane_change.gif" width="520">

### Curved Lane Detection

<img src="media/curve_detection_25_30_720.gif" width="520">

### Night Driving Scenario

<img src="media/night_lane.gif" width="520">

Repository:  
[Lane Detection System](https://github.com/Nir-David-Duani/lane-detection)

---

## Perfect Phylogeny (PP-Linear)
Java · Algorithms · Graph Algorithms

An implementation of the **Unrooted Perfect Phylogeny algorithm** with **O(n·m)** time complexity, focusing on algorithmic correctness and computational efficiency.

Repository:  
[Perfect Phylogeny Algorithm](https://github.com/Nir-David-Duani/pp-linear)

---

# Technical Focus

- Computer Vision
- Deep Learning for Visual Recognition
- Algorithms and Data Structures
- Geometry and optimization-based methods

---

# Contact

LinkedIn  
https://www.linkedin.com/in/nir-david-duani

GitHub  
https://github.com/Nir-David-Duani
