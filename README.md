# Object Tracking Projects and Resources

## Table of Contents

* [Overview](#overview)
* [Projects](#projects)
    * [Object Tracking Fundamentals](#object-tracking-fundamentals)
    * [Multiple Object Tracking with YOLO and Advanced Algorithms](#multiple-object-tracking-with-yolo-and-advanced-algorithms)
    * [Vehicle Counting with YOLOv8, ByteTrack, and DeepSORT](#vehicle-counting-with-yolov8-bytetrack-and-deepsort)
* [Resources](#resources)
    * [Object Tracking Presentations and Tutorials](#object-tracking-presentations-and-tutorials)

## Overview

This collection explores various methodologies for object tracking, ranging from traditional computer vision techniques to modern deep learning models. It includes practical implementations and theoretical insights into single and multiple object tracking, with a particular focus on real-world applications such as vehicle counting.

## Projects

### Object Tracking Fundamentals

* `CVF_Object_Tracking_Problem.ipynb`
* `CVF_Object_Tracking_Solution.ipynb`

These notebooks introduce basic object tracking concepts, likely demonstrating techniques such as Meanshift or Camshift using OpenCV for tracking objects in video sequences.

### Multiple Object Tracking with YOLO and Advanced Algorithms

* `MOT.ipynb`

This project implements a Multiple Object Tracking (MOT) solution utilizing the `ultralytics` library, suggesting a YOLO-based detection system. It demonstrates the tracking of various objects, including persons, cars, trucks, birds, and kites, highlighting its capability in diverse environments.

### Vehicle Counting with YOLOv8, ByteTrack, and DeepSORT

* `Vehicle_counting_YOLOv8_with_ByteTrack_and_DeepSORT.ipynb`

This notebook provides a comprehensive solution for vehicle counting in video streams. It integrates YOLOv8 for efficient object detection with ByteTrack and DeepSORT for robust multi-object tracking. The system is designed for intelligent traffic management, addressing challenges such as congestion and accidents by accurately identifying and tracking vehicles like cars, motorcycles, buses, and trucks. The implementation leverages `ultralytics` and `supervision` libraries for streamlined development and deployment.

## Resources

### Object Tracking Presentations and Tutorials

* `Documents_2025-1_[Slide_v2] Object tracking using object detection_[Slide_v2] Object Tracking.pdf`
* `Documents_2025-1_Object tracking using object detection_YOLO_Tracking_Tutorial.pdf`

These PDF documents offer foundational knowledge and practical guidance on object tracking. Topics covered include an introduction to single and multiple object tracking, template matching, histogram matching, Mean Shift, SIFT features, and advanced concepts like Kalman Filters, SORT, and DeepSORT. The tutorials specifically delve into object tracking using YOLO, emphasizing its speed and accuracy in vehicle detection and its relevance in smart traffic systems.
