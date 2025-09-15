# 🧍 HoloCare — Pose Detection

![Status](https://img.shields.io/badge/status-beta-yellow) ![Language](https://img.shields.io/badge/language-JavaScript-blue) ![License](https://img.shields.io/badge/license-MIT-green)

HoloCare is a **real-time pose detection web app** that tracks body movements and counts **jumping jacks** using **MediaPipe Pose**. It provides live feedback, a fitness dashboard, and progress tracking to help users stay active and motivated.

---

## 🎯 Features

- ✅ Real-time full-body pose detection
- ✅ Jumping jack counter
- ✅ Timer and estimated calories burned
- ✅ Progress bar toward exercise goals
- ✅ Interactive visual feedback
- ✅ Works directly in the browser (no backend needed)

---



## 🚀 Usage

1. Open `index.html` in a modern browser (Chrome / Edge recommended).  
2. Allow camera access.  
3. Stand fully visible in front of the camera.  
4. Perform **jumping jacks**:
   - Hands above your head
   - Feet apart  
5. Watch the dashboard update:
   - Reps counted
   - Calories burned
   - Timer
   - Progress toward goal

---

## 🛠 How It Works

1. **Camera Capture** – `navigator.mediaDevices.getUserMedia()` accesses the webcam.  
2. **Pose Detection** – MediaPipe Pose detects key body landmarks.  
3. **Exercise Logic** – Jumping jack detected when:
   - Hands above the head
   - Feet wider than shoulders  
4. **UI Feedback** – Real-time skeleton overlay + messages.  
5. **Fitness Stats** – Timer starts automatically; calories estimated at `0.2 cal per rep`.

---

## 📦 Built With

- **HTML / CSS / JavaScript**
- **[MediaPipe Pose](https://developers.google.com/mediapipe/solutions/vision/pose)**
- **Canvas API** for drawing skeletons
- **WebRTC / getUserMedia API** for camera access

---

## ⚙️ Setup

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/holocare-pose-detection.git

# 2. Open index.html in your browser
