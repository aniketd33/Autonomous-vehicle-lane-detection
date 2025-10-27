🚗 Autonomous Vehicle Lane Detection

🧠 Overview:
The Autonomous Vehicle Lane Detection project uses Computer Vision (OpenCV) techniques to detect and highlight road lanes in real time.
It’s a foundational component of self-driving vehicle systems that assists in lane keeping, path planning, and road boundary awareness.

This project processes each frame from a video feed or camera input to detect lanes using edge detection, region of interest masking, and Hough Line Transform, then overlays green lines on the detected lanes.

🎯 Objectives:
Detect lane markings in real-time road videos.
Highlight detected lanes using a green overlay.
Provide a base for advanced autonomous navigation systems.
Support further integration with steering angle prediction.

🌟 Features:
✅ Detects left and right lane boundaries
✅ Smooth green overlay for clear visualization
✅ Real-time video processing
✅ Modular and clean Python code
✅ Easy to modify ROI and thresholds for different road conditions
✅ Optional video saving support

🧩 Sample Output Frame (Illustration):
-----------------------------------
|                                 |
|        (Road Scene)             |
|                                 |
|      =====   =====              |
|     ||   || ||   ||  ← Green lines |
|                                 |
-----------------------------------

🚀 Future Improvements:
Use Deep Learning (CNNs) for more robust lane detection under all weather conditions.
Integrate bird’s-eye perspective transformation for better accuracy.
Predict steering angles for autonomous driving simulation.
Add lane curvature detection and lane departure alerts.
