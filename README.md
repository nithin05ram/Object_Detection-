Autonomous Vehicle Detection & Analysis System

An AI-powered vehicle analytics pipeline that performs vehicle detection, tracking, speed estimation, feature extraction, and risk assessment on traffic videos using YOLOv8 and LangGraph.

The system processes one or more videos, detects vehicles in each frame, tracks their movement, estimates speed, identifies vehicle characteristics, evaluates potential risks, and generates comprehensive reports with visualizations.
Features
🚘 Vehicle detection using YOLOv8
🎯 Multi-frame vehicle tracking
⚡ Speed estimation
🎨 Vehicle color detection
📏 Vehicle size estimation
🧭 Movement direction detection
🛣️ Lane position analysis
⚠️ Risk assessment based on vehicle behavior
📊 CSV reports for detected vehicles
📈 Summary statistics and visualizations
🎥 Annotated output videos
🖼️ Saved detection frames
Tech Stack
Python
YOLOv8 (Ultralytics)
OpenCV
NumPy
Pandas
Matplotlib
SciPy
LangGraph
Project Pipeline
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
Project Structure
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
Installation

Clone the repository:

git clone https://github.com/yourusername/autonomous-vehicle-analysis.git

cd autonomous-vehicle-analysis

Install dependencies:

pip install ultralytics langgraph opencv-python numpy pandas matplotlib scipy
Usage

Run the notebook or execute the pipeline after placing input videos inside the input directory.

The system will automatically:

Detect vehicles
Track their movement
Estimate speed
Analyze vehicle features
Evaluate risk
Save annotated videos
Generate reports and charts
Output

The pipeline generates:

✅ Annotated videos
✅ Vehicle tracking results
✅ Speed estimates
✅ Vehicle feature information
✅ Risk analysis
✅ CSV reports
✅ Statistical charts
✅ Summary report
Sample Analysis

For each detected vehicle, the system records:

Vehicle ID
Vehicle Type
Speed
Color
Size
Direction
Lane Position
Risk Level
Timestamp
Applications
Smart Traffic Monitoring
Intelligent Transportation Systems (ITS)
Road Safety Analysis
Traffic Flow Analytics
Autonomous Driving Research
Surveillance Systems
Future Improvements
DeepSORT/ByteTrack integration
License Plate Recognition (ALPR)
Traffic density estimation
Accident detection
Traffic violation detection
Real-time live camera support
Dashboard for analytics
License

This project is intended for educational and research purposes.

Author

Nithin Ram Gopal

If you found this project useful, consider giving it a ⭐ on GitHub.
