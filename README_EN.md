# 🥊 Fight Detection System
**Real-time Fight Detection System Based on YOLO Pose Estimation**

[中文版本](README.md) | English Version

---

## 📋 Project Information
- **School**: Taipei Municipal Shilin Vocational High School of Commerce
- **Type**: Vocational School Capstone Project
- **Technology**: Computer Vision + Deep Learning
- **Programming Language**: Python

---

## 🎯 System Features

### Core Functions
- ✅ **Real-time Human Pose Detection** - Using YOLOv8n Pose Model
- ✅ **Fighting Behavior Recognition** - Based on Arm Overlap Algorithm
- ✅ **Visualization Interface** - Skeleton Display + Real-time Status
- ✅ **Alert System** - Audio Alerts + Visual Warnings
- ✅ **Performance Monitoring** - FPS Display + Statistics

### Detection Logic
1. **Pose Extraction**: Detect 17 human keypoints
2. **Interaction Analysis**: Calculate arm overlap between multiple people
3. **Behavior Determination**: Trigger alert when threshold exceeded
4. **Continuous Tracking**: 3-second alert duration

---

## 🛠️ Environment Requirements

### System Requirements
- **Operating System**: Windows 10/11, macOS, Linux
- **Python**: Version 3.8 or higher
- **Hardware**: Computer with camera support

### Package Installation
```bash
# Install required packages
pip install ultralytics opencv-python numpy pygame
```

---

## 🚀 Quick Start

### 1. Download Project
[Download Here](https://github.com/slhs1121505/Fight_detection_system/releases/tag/Yogurt)

### 2. Install Dependencies
```bash
pip install ultralytics opencv-python numpy pygame
```

### 3. Run System
```bash
# Open the executable file
fight_detection_system.exe
```

### 4. Operation Commands
- **`q`**: Exit system
- **`r`**: Reset statistics

---

## 📊 System Parameters

### Detection Conditions
- **Distance Threshold**: Arm keypoint distance < 50 pixels
- **Overlap Count**: At least 2 keypoints overlapping
- **Average Distance**: Arm average distance < 80 pixels

---

## 🖥️ System Interface

### Main Display
- **Live Video**: Camera feed + Skeleton overlay
- **Status Bar**: Detection status, FPS, people count
- **Alert Zone**: Red flashing alerts
- **Statistics**: Runtime, total alert count

### Visual Elements
- 🟢 **Green Skeleton**: Normal status
- 🔴 **Red Alert**: Fight detected
- 📊 **Semi-transparent Panel**: System information display

---

## 🧠 Technical Architecture

### Core Technology
```
YOLOv8n Pose → Pose Estimation → Feature Extraction → Behavior Analysis → Alert Trigger
```

### Processing Flow
1. **Image Input** → Camera capture
2. **Pose Detection** → YOLO model inference
3. **Feature Calculation** → Keypoint distance analysis
4. **Behavior Determination** → Overlap assessment
5. **Result Output** → Visualization + Alerts

### Performance Optimization
- Image scaling (640px width)
- Buffer management (reduce latency)
- Multi-threaded audio playback
- Smooth FPS calculation

---

## 🐛 Troubleshooting

### Q: Cannot open camera?
**A**: Check if camera is being used by other applications.

### Q: No alert sound?
**A**: Verify system volume settings or check if pygame is correctly installed.

---

## 📈 Performance

### Test Environment
- **CPU**: AMD Ryzen 5 3600
- **RAM**: 8GB DDR4
- **Camera**: 720p @ 30fps

### Performance Metrics
- **FPS**: 6~7

---

## 👥 Development Team

### Project Members
- **Developer/Team Leader**: Tzu-Fu Chang
- **Team Members**: Bu-Ting Chang, Yu-Ting Zhao
- **Supervisor**: Bi-Da Xu
- **School**: Taipei Municipal Shilin Vocational High School of Commerce

### Contact Information
- **Email**: tzufu.taiwan@gmail.com
- **GitHub**: [@slhs1121505](https://github.com/slhs1121505)

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments
- **YOLOv8n**: Lightweight pose estimation model by Ultralytics team
- **OpenCV**: Powerful computer vision library
- **Supervisor**: Professional guidance and advice
- **Classmates**: Testing and feedback support

---

## 📚 References

### Technical Documentation
- [YOLOv8 Official Documentation](https://docs.ultralytics.com/)
- [OpenCV Python Tutorials](https://steam.oxxostudio.tw/category/python/ai/opencv-index.html)

### Academic Papers
- ["You Only Look Once: Unified, Real-Time Object Detection"](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Redmon_You_Only_Look_CVPR_2016_paper.pdf)

---

**⭐ If this project helps you, please give it a Star!**

---

*README.md generated with assistance from Claude Sonnet 4*
