--------------------------------------------------------------------------
## Results
### 1. Human Pose Estimation Benchmarking
#### Multi-Person (left: AlphaPose, right: OpenPose)
<p align = "center">
  <img src = "images/alphapose_multi.gif" height = "240px">
  <img src = "images/openpose_multi.gif" height = "240px">
</p>

-----------------------------------------------------------------------------------------
## Introduction
This project contain two main parts:
### 1. Human Pose Estimation Benchmarking
In this part, we conducted benchmarking test on the two most state-of-the-art human pose estimation models [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) and [AlphaPose](https://github.com/MVIG-SJTU/AlphaPose). We tested different modes on both single-person and multi-person scenarios.

### 2. Online Skeleton-Based Action Recognition
Real-time multi-person human action recognition based on [tf-pose-estimation](https://github.com/ildoonet/tf-pose-estimation). The pipeline is as follows:
* Real-time multi-person pose estimation via tf-pose-estimation
* Feature Extraction
* Multi-person action recognition using TensorFlow / Keras


