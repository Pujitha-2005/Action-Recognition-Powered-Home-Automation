# Smart Home Automation Based on Video Activity Recognition

This project is a smart home automation system that controls electrical devices like **lights** and **AC** based on a person’s activity detected from a pre-recorded video file.

## 🎯 Objective

To automatically control home appliances using activity recognition from a video, enhancing energy efficiency and convenience.

## 🚀 Features

- Takes a **video file as input** (not live webcam).
- Detects human activities like **studying** or **sleeping**.
- Automatically:
  - Turns **ON light and AC** when the person is **studying**.
  - Turns **OFF light** when the person is **sleeping**.

## 🛠️ Technologies Used

- Python
- OpenCV (for video processing)
- Machine Learning / Computer Vision (for activity detection)
- IoT integration (optional): NodeMCU, relay modules, etc.

## 🖥️ How It Works

1. Load and process a **video file** using OpenCV.
2. Detect the activity in each frame:
   - **Studying** → Turn ON light & AC.
   - **Sleeping** → Turn OFF light.
3. Based on detected activity, the program sends control signals (can be simulated or integrated with IoT modules).
