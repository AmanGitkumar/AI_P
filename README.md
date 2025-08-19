# 🎾 Tennis Player Tracking with YOLOv8 + DeepSORT  

This project tracks **two tennis players** in a broadcast match video, measures their **movement distance** in real-time, and visualizes results.  
It combines **YOLOv8** (for player detection) with **DeepSORT** (for identity tracking) to ensure stable tracking of the same players across frames.  

## 🚀 Features
- Detects and tracks **two main players** in a tennis match.
- Measures **total distance covered** by each player.
- Real-time visualization with:
  - Bounding boxes
  - Player names
  - Cumulative distance (in feet)
- Robust to short-term occlusions (thanks to DeepSORT).
- Customizable configuration (confidence threshold, pixels-to-feet ratio, etc.).

---

## ⚙️ Tech Stack
- **Python 3.8+**
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) – Player detection  
- [DeepSORT](https://github.com/levan92/deep-sort-realtime) – Multi-object tracking  
- [OpenCV](https://opencv.org/) – Video processing & visualization  
- **NumPy** – Distance calculations  

---

