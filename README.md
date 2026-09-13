# Nir David-Duani

Computer Science student focused on **algorithms, computer vision, and applied AI systems**.

---

# Featured Projects

## Coastal Shoreline Detection
**Python · PyTorch · OpenCV · CLIPSeg · SIFT · Computer Vision**

A semi-automatic system for extracting shorelines from fixed coastal cameras.

Each incoming frame is aligned with a location reference using **SIFT feature matching, RANSAC, and homography estimation**. A vision-language segmentation model produces water and land probability maps, from which the system extracts a connected shoreline inside a user-defined search region.

The method supports curved and irregular shorelines without assuming a fixed shoreline direction.

### Shoreline Results

<p align="center">
<img src="media/location_examples.png" width="750">
</p>

### Registration and Semantic Pipeline

<p align="center">
  <img src="media/registration_sift_alignment.png" width="390">
  <img src="media/porch_pipeline.png" width="390">
</p>

The complete pipeline includes reference-frame registration, CLIPSeg water/land segmentation, interactive region annotation, contour extraction, candidate scoring, and batch processing through a command-line interface.

[View repository →](https://github.com/Nir-David-Duani/coastal-shoreline-detection)

---

## Deep Learning: From Classification to Detection
**Python · PyTorch · Computer Vision · Deep Learning**

A deep learning project exploring the transition from **image classification to object detection** using transfer learning.

Starting from a pretrained **ResNet-18 classifier**, the system evolves from backbone feature analysis to single-object bounding-box regression and multi-object detection of helmets, people, and safety vests.

The project focuses on **architectural reasoning, detection loss design, and IoU-based evaluation**.

### Single-Object Detection

<p align="center">
  <img src="media/single_object.gif" width="340">
  <img src="media/single_object1.gif" width="340">
</p>

A ResNet-18 backbone with a lightweight regression head predicts a single normalized bounding box for a safety vest.

### Multi-Object Detection

<p align="center">
  <img src="media/multi_object.gif" width="340">
  <img src="media/multi_object1.gif" width="340">
</p>

The detector predicts up to three objects per frame using fixed prediction slots and an **IoU-aware loss** for improved localization.

[View repository →](https://github.com/Nir-David-Duani/classification-to-detection)

---

## Planar Augmented Reality
**Python · OpenCV · Camera Geometry · Pose Estimation**

An augmented reality pipeline that tracks planar targets in video and renders virtual content with correct **perspective, camera pose, and occlusion handling**.

The system combines camera calibration, homography tracking, and pose estimation with `solvePnP` to align virtual 3D objects with the real scene.

### Occlusion Handling

<p align="center">
<img src="media/ar_occlusion_hand.gif" width="280">
</p>

### Multi-Plane Tracking

<p align="center">
  <img src="media/part5_multi_plane_video_portal360vid5.gif" width="280">
  <img src="media/part5_multi_plane_video_portal3602.gif" width="280">
</p>

### 3D Cube Rendering

<p align="center">
<img src="media/part2_cube.gif" width="280">
</p>

[View repository →](https://github.com/Nir-David-Duani/augmented-reality-planar)

---

## Lane Detection from Driving Videos
**Python · OpenCV · Computer Vision**

A computer vision system for detecting **lane boundaries and road structure** in driving videos.

The system handles curved roads, crosswalks, lane changes, and nighttime driving, with an emphasis on **geometric reasoning, temporal consistency, and robustness across environments**.

### Crosswalk Detection

<p align="center">
<img src="media/lane_crosswalk.gif" width="550">
</p>

### Lane Tracking and Lane Changes

<p align="center">
<img src="media/lane_change.gif" width="550">
</p>

### Curved Lane Detection

<p align="center">
<img src="media/curve_detection_25_30_720.gif" width="550">
</p>

### Night Driving

<p align="center">
<img src="media/night_lane.gif" width="550">
</p>

[View repository →](https://github.com/Nir-David-Duani/lane-detection)

---

## Perfect Phylogeny (PP-Linear)
**Java · Algorithms · Graph Algorithms**

An implementation of the **Unrooted Perfect Phylogeny algorithm** with **O(n · m)** time complexity.

The project focuses on algorithmic correctness, graph-based reasoning, and computational efficiency.

[View repository →](https://github.com/Nir-David-Duani/pp-linear)

---

# Technical Focus

- Computer Vision
- Deep Learning for Visual Recognition
- Algorithms and Data Structures
- Camera Geometry and Optimization
- Applied AI Systems

---

# Contact

[LinkedIn](https://www.linkedin.com/in/nir-david-duani) · [GitHub](https://github.com/Nir-David-Duani)
