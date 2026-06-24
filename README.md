# Autonomous Vehicle Detection & Analysis System

An AI-powered vehicle analytics pipeline that performs vehicle detection, tracking, speed estimation, feature extraction, and risk assessment on traffic videos using YOLOv8 and LangGraph.

The system processes one or more videos, detects vehicles in each frame, tracks their movement, estimates speed, identifies vehicle characteristics, evaluates potential risks, and generates comprehensive reports with visualizations.

## Features
* 🚘 Vehicle detection using YOLOv8
* 🎯 Multi-frame vehicle tracking
* ⚡ Speed estimation
* 🎨 Vehicle color detection
* 📏 Vehicle size estimation
* 🧭 Movement direction detection
* 🛣️ Lane position analysis
* ⚠️ Risk assessment based on vehicle behavior
* 📊 CSV reports for detected vehicles
* 📈 Summary statistics and visualizations
* 🎥 Annotated output videos
* 🖼️ Saved detection frames

## Tech Stack
* Python
* YOLOv8 (Ultralytics)
* OpenCV
* NumPy
* Pandas
* Matplotlib
* SciPy
* LangGraph

## Project Pipeline

```text
Input Video
      │
      ▼
Vehicle Detection (YOLOv8)
      │
      ▼
Vehicle Tracking
      │
      ▼
Speed Estimation
      │
      ▼
Feature Extraction
 ├── Color
 ├── Size
 ├── Direction
 └── Lane Position
      │
      ▼
Risk Assessment
      │
      ▼
Generate Reports
 ├── CSV
 ├── Charts
 ├── Annotated Video
 └── Summary
```
##Project Structure
```text
.
├── input_videos/
├── output/
│   ├── videos/
│   ├── frames/
│   ├── reports/
│   ├── charts/
│   └── summary/
├── notebook.ipynb
└── README.md
```
## Usage
```text
Run the notebook or execute the pipeline after placing input videos inside the input_videos directory.
>The system will automatically:

>Detect vehicles

>Track their movement

>Estimate speed

>Analyze vehicle features

>Evaluate risk

>Save annotated videos

>Generate reports and charts
```
## Applications
Smart Traffic Monitoring

Intelligent Transportation Systems (ITS)

Road Safety Analysis

Traffic Flow Analytics

Autonomous Driving Research

Surveillance Systems
