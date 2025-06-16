# 🥊 Fight Detection System
**Real-time Fight Detection System Based on YOLO Pose Estimation**

[中文版本](README.md) | English Version

---

## 📋 Project Information
- **School**: Taipei Municipal Shilin High School of Commerce
- **Project Type**: Vocational Senior High School Capstone Project
- **Technologies Used**: Computer Vision and Deep Learning
- **Programming Language**: Python

---

## 🎯 System Features

### Core Functions
- ✅ **Real-time Human Pose Detection** - Powered by the YOLOv8n Pose Model
- ✅ **Fighting Behavior Recognition** - Based on the Arm Overlap Algorithm
- ✅ **Visualization Interface** -  Skeleton Rendering and Real-time Status Display
- ✅ **Alert System** - Includes Audio Alerts and Visual Warnings
- ✅ **Performance Monitoring** - FPS Counter and Live Statistics

### Detection Logic
1. **Pose Extraction**: Detect 17 human keypoints
2. **Interaction Analysis**: Calculate arm overlap among multiple people
3. **Behavior Determination**: Trigger an alert when the threshold is exceeded
4. **Continuous Tracking**: Maintain alert status for a duration of 3 seconds

---

## 🛠️ Environment Requirements

### System Requirements
- **Operating System**: Windows 10 or 11, macOS, and Linux
- **Python Version**: 3.8 or higher
- **Hardware**: Computer equipped with a camera

### Package Installation
```bash
# Install required packages
pip install ultralytics opencv-python numpy pygame
```

---

## 🚀 Quick Start

### 1. Download the Project
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
- **`q`**: Exit the system
- **`r`**: Reset statistics

---

## 📊 System Parameters

### Detection Conditions
- **Distance Threshold**: The distance between arm keypoints is less than 50 pixels
- **Overlap Count**: At least two keypoints must overlap
- **Average Distance**: The average distance between arm keypoints is less than 80 pixels

---

## 🖥️ System Interface

### Main Display
- **Live Video**: Camera feed with Skeleton overlay
- **Status Bar**: Detection status, FPS, and people count
- **Alert Zone**: Red flashing alerts
- **Statistics**: Runtime and total alert count

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
5. **Result Output** → Visualization and alerts

### Performance Optimization
- Image scaling to 640 pixels (width)
- Buffer management to reduce latency
- Multi-threaded audio playback
- Smooth FPS (frames per second) calculation

---

## 🐛 Troubleshooting

### Q: Cannot open the camera?
**A**: Ensure that the camera is not being used by other applications.

### Q: No alert sound?
**A**: Check your system’s volume settings, and verify that pygame is correctly installed.

---

## 📈 Performance

### Test Environment
- **CPU**: AMD Ryzen 5 3600
- **RAM**: 8GB DDR4
- **Camera**: 720p @ 30fps

### Performance Metrics
- **Frames Per Second (FPS)**: 6–7

---

## 👥 Development Team

### Project Members
- **Developer / Team Leader**: [Tzu-Fu Chang](https://github.com/slhs1121505)
- **Team Members**: Bu-Ting Chang, [Yu-Ting Zhao](https://github.com/Inadilemma666)
- **Supervisor**: Bi-Da Xu
- **School**: Taipei Municipal Shilin Vocational High School of Commerce

### Contact Information
- **Email**: tzufu.taiwan@gmail.com
- **GitHub**: [@slhs1121505](https://github.com/slhs1121505)

---

## 📄 License
This project is licensed under the MIT License - Please refer to the [LICENSE](LICENSE) file for full details.

---

## 🙏 Acknowledgments
- **YOLOv8n**: Lightweight pose estimation model by the Ultralytics team
- **OpenCV**: Powerful computer vision library
- **Supervisor**: Professional guidance and valuable feedback
- **Classmates**: Assistance with testing and evaluation

---

## 📚 References

### Technical Documentation
- [YOLOv8 Official Documentation](https://docs.ultralytics.com/)
- [OpenCV Python Tutorials](https://steam.oxxostudio.tw/category/python/ai/opencv-index.html)

### Academic Papers
- ["You Only Look Once: Unified, Real-Time Object Detection"](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Redmon_You_Only_Look_CVPR_2016_paper.pdf)

---

**⭐ If you found this project helpful, please consider giving it a ⭐ on GitHub!**

---

*README_EN.md was generated with assistance from Claude Sonnet 4 and was subsequently further edited by Yu-Ting Zhao*
