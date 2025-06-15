# 🥊 Fight Detection System / 打架偵測系統
**Real-time Fight Detection System Based on YOLO Pose Estimation**  
**基於 YOLO Pose Estimation 的即時打架偵測系統**

[中文版](#中文版) | [English Version](#english-version)

---

## English Version

### 📋 Project Information
- **School**: Taipei Municipal Shilin Vocational High School of Commerce
- **Type**: Vocational School Capstone Project
- **Technology**: Computer Vision + Deep Learning
- **Programming Language**: Python

---

### 🎯 System Features

#### Core Functions
- ✅ **Real-time Human Pose Detection** - Using YOLOv8n Pose Model
- ✅ **Fighting Behavior Recognition** - Based on Arm Overlap Algorithm
- ✅ **Visualization Interface** - Skeleton Display + Real-time Status
- ✅ **Alert System** - Audio Alerts + Visual Warnings
- ✅ **Performance Monitoring** - FPS Display + Statistics

#### Detection Logic
1. **Pose Extraction**: Detect 17 human keypoints
2. **Interaction Analysis**: Calculate arm overlap between multiple people
3. **Behavior Determination**: Trigger alert when threshold exceeded
4. **Continuous Tracking**: 3-second alert duration

---

### 🛠️ Environment Requirements

#### System Requirements
- **Operating System**: Windows 10/11, macOS, Linux
- **Python**: Version 3.8 or higher
- **Hardware**: Computer with camera support

#### Package Installation
```bash
# Install required packages
pip install ultralytics opencv-python numpy pygame
```

---

### 🚀 Quick Start

#### 1. Download Project
[Download Here](https://github.com/slhs1121505/Fight_detection_system/releases/tag/Yogurt)

#### 2. Install Dependencies
```bash
pip install ultralytics opencv-python numpy pygame
```

#### 3. Run System
```bash
Open fight_detection_system.exe
```

#### 4. Operation Commands
- **`q`**: Exit system
- **`r`**: Reset statistics

---

### 📊 System Parameters

#### Detection Conditions
- **Distance Threshold**: Arm keypoint distance < 50 pixels
- **Overlap Count**: At least 2 keypoints overlapping
- **Average Distance**: Arm average distance < 80 pixels

---

### 🖥️ System Interface

#### Main Display
- **Live Video**: Camera feed + Skeleton overlay
- **Status Bar**: Detection status, FPS, people count
- **Alert Zone**: Red flashing alerts
- **Statistics**: Runtime, total alert count

#### Visual Elements
- 🟢 **Green Skeleton**: Normal status
- 🔴 **Red Alert**: Fight detected
- 📊 **Semi-transparent Panel**: System information display

---

### 🧠 Technical Architecture

#### Core Technology
```
YOLOv8n Pose → Pose Estimation → Feature Extraction → Behavior Analysis → Alert Trigger
```

#### Processing Flow
1. **Image Input** → Camera capture
2. **Pose Detection** → YOLO model inference
3. **Feature Calculation** → Keypoint distance analysis
4. **Behavior Determination** → Overlap assessment
5. **Result Output** → Visualization + Alerts

#### Performance Optimization
- Image scaling (640px width)
- Buffer management (reduce latency)
- Multi-threaded audio playback
- Smooth FPS calculation

---

### 🐛 Common Issues

#### Q: Cannot open camera?
**A**: Check if camera is being used by other applications.

#### Q: No alert sound?
**A**: Verify system volume settings or check if pygame is correctly installed.

---

### 📈 Performance

#### Test Environment
- **CPU**: AMD Ryzen 5 3600
- **RAM**: 8GB DDR4
- **Camera**: 720p @ 30fps

#### Performance
- **FPS**: 6~7

---

### 👥 Development Team

#### Project Members
- **Developer/Team Leader**: Tzu-Fu Chang
- **Team Members**: Bu-Ting Chang, Yu-Ting Zhao
- **Supervisor**: Bi-Da Xu
- **School**: Taipei Municipal Shilin Vocational High School of Commerce

#### Contact Information
- **Email**: tzufu.taiwan@gmail.com
- **GitHub**: [@slhs1121505](https://github.com/slhs1121505)

---

### 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### 🙏 Acknowledgments
- **YOLOv8n**: Lightweight pose estimation model by Ultralytics team
- **OpenCV**: Powerful computer vision library
- **Supervisor**: Professional guidance and advice
- **Classmates**: Testing and feedback support

---

### 📚 References

#### Technical Documentation
- [YOLOv8 Official Documentation](https://docs.ultralytics.com/)
- [OpenCV Python Tutorials](https://steam.oxxostudio.tw/category/python/ai/opencv-index.html)

#### Academic Papers
- ["You Only Look Once: Unified, Real-Time Object Detection"](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Redmon_You_Only_Look_CVPR_2016_paper.pdf)

---

**⭐ If this project helps you, please give it a Star!**

---

## 中文版

### 📋 專題資訊
- **學校**: 臺北市立士林高級商業職業學校
- **類型**: 高職專題製作
- **技術**: 電腦視覺 + 深度學習
- **開發語言**: Python

---

### 🎯 系統功能

#### 核心功能
- ✅ **即時人體姿態偵測** - 使用 YOLOv8n Pose 模型
- ✅ **打架行為識別** - 基於手臂重疊度算法
- ✅ **視覺化介面** - 骨架顯示 + 即時狀態
- ✅ **警報系統** - 聲音提醒 + 視覺警示
- ✅ **效能監控** - FPS 顯示 + 統計資料

#### 偵測邏輯
1. **姿態擷取**: 偵測人體 17 個關鍵點
2. **互動分析**: 計算多人間手臂重疊程度
3. **行為判定**: 超過閾值觸發警報
4. **持續追蹤**: 3 秒警報持續時間

---

### 🛠️ 環境需求

#### 系統需求
- **作業系統**: Windows 10/11, macOS, Linux
- **Python**: 3.8 或以上版本
- **硬體**: 支援攝像頭的電腦

#### 套件安裝
```bash
# 安裝必要套件
pip install ultralytics opencv-python numpy pygame
```

---

### 🚀 快速開始

#### 1. 下載專案
[點我下載](https://github.com/slhs1121505/Fight_detection_system/releases/tag/Yogurt)

#### 2. 安裝依賴
```bash
pip install ultralytics opencv-python numpy pygame
```

#### 3. 執行系統
```bash
開啟 fight_detection_system.exe
```

#### 4. 操作指令
- **`q`**: 退出系統
- **`r`**: 重置統計數據

---

### 📊 系統參數

#### 偵測條件
- **距離閾值**: 手臂關鍵點距離 < 50 像素
- **重疊數量**: 至少 2 個關鍵點重疊
- **平均距離**: 手臂平均距離 < 80 像素

---

### 🖥️ 系統介面

#### 主要顯示
- **即時影像**: 攝像頭畫面 + 骨架覆蓋
- **狀態欄**: 偵測狀態、FPS、人數統計
- **警報區**: 紅色閃爍提醒
- **統計資料**: 運行時間、總警報次數

#### 視覺元素
- 🟢 **綠色骨架**: 正常狀態
- 🔴 **紅色警示**: 偵測到打架
- 📊 **半透明面板**: 系統資訊顯示

---

### 🧠 技術架構

#### 核心技術
```
YOLOv8n Pose → 姿態估計 → 特徵提取 → 行為分析 → 警報觸發
```

#### 處理流程
1. **影像輸入** → 攝像頭擷取
2. **姿態偵測** → YOLO 模型推論
3. **特徵計算** → 關鍵點距離分析
4. **行為判定** → 重疊度評估
5. **結果輸出** → 視覺化 + 警報

#### 效能優化
- 影像縮放 (640px 寬度)
- 緩衝區管理 (減少延遲)
- 多執行緒音效播放
- FPS 平滑計算

---

### 🐛 常見問題

#### Q: 無法開啟攝像頭？
**A**: 檢查攝像頭是否被其他程式佔用。

#### Q: 沒有警報聲音？
**A**: 確認系統音量設定，或檢查 pygame 是否正確安裝。

---

### 📈 效能表現

#### 測試環境
- **CPU**: AMD Ryzen 5 3600
- **RAM**: 8GB DDR4
- **攝像頭**: 720p @ 30fps

#### 效能
- **FPS**: 6~7

---

### 👥 開發團隊

#### 專題成員
- **開發者/組長**: 張子夫
- **組員們**: 張步廷、趙御廷
- **指導老師**: 徐必大
- **學校**: 臺北市立士林高級商業職業學校

#### 聯絡資訊
- **Email**: tzufu.taiwan@gmail.com
- **GitHub**: [@slhs1121505](https://github.com/slhs1121505)

---

### 📄 授權條款
本專題採用 MIT 授權條款 - 詳見 [LICENSE](LICENSE) 檔案

---

### 🙏 致謝
- **YOLOv8n**: Ultralytics 團隊提供的輕量化姿態估計模型
- **OpenCV**: 強大的電腦視覺函式庫
- **指導老師**: 專業指導與建議
- **同學們**: 測試與回饋支持

---

### 📚 參考資料

#### 技術文件
- [YOLOv8 官方文檔](https://docs.ultralytics.com/)
- [OpenCV Python 教學](https://steam.oxxostudio.tw/category/python/ai/opencv-index.html)

#### 學術論文
- ["You Only Look Once: Unified, Real-Time Object Detection"](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Redmon_You_Only_Look_CVPR_2016_paper.pdf)

---

**⭐ 如果這個專題對你有幫助，請給個 Star！**

---

*README.md 中英雙語版本由 Claude Sonnet 4 協助撰寫*
