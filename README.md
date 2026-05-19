# Intelligent-traffic-system
An end-to-end AI-powered traffic analytics system built using YOLOv8 for real-time vehicle detection, tracking, and traffic flow analysis. This project simulates a smart city traffic monitoring system, capable of Detecting vehicles across 14 classes, Tracking movement across frames, Estimating traffic density and flow nad Providing real-time analytics.
<img width="1983" height="793" alt="ChatGPT Image May 5, 2026, 11_42_33 AM" src="https://github.com/user-attachments/assets/15c5b375-7012-4812-9ecf-17952f5f10b3" />
# Key Features
- Multi-class Object Detection (YOLOv8)
- Multi-threaded Data Processing (ThreadPoolExecutor)
- COCO → YOLO Dataset Conversion
- Advanced EDA (blur, brightness, corrupt detection)
- Vehicle Tracking (ByteTrack)
- Traffic Analytics Engine (count, flow, density)

# Architecture

# Dataset
The experiments were conducted on UVH-26 dataset. The dataset contains 26,646 high resolution (1080p) images collected from 2,800 CCTV cameras as a part of Safe City initiative of Bengaluru. The dataset contains 14 classes of vehicles which are relevant to India. These are Cycle, 2-Wheeler (Motorcycle), 3-Wheeler (Auto-rickshaw), LCV (Light Commercial Vehicles), Van, Tempo-traveller, Hatchback, Sedan, SUV, MUV, Mini-bus, Bus, Truck and Other. Each frame is stored as an RGB image of 1920 × 1080 pixels with a small part at lower resolution. The collection includes different traffic scenarios, such as freeways, urban roads, intersections, congestion scenarios, different illuminations, and scenes with high occlusion.

# Pipeline
Data → Preprocessing → YOLO → Tracking → Analytics → API

# Results
mAP50 :
mAP50-95 :

# Demo (Sample Outputa)

# Author: Dr. Parag Bhuyan

![Python](https://img.shields.io/badge/Python-3.10-blue)
![YOLOv8](https://img.shields.io/badge/YOLOv8-ObjectDetection-red)
![License](https://img.shields.io/badge/License-AGPL-green)
