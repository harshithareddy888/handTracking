#Hand Tracking Module
This module uses OpenCV and MediaPipe Hands to detect and track hands in real time via a webcam feed.

Features
Real-time hand detection using MediaPipe’s high-accuracy ML models

Landmark tracking – detects 21 key hand landmarks (fingers, joints, wrist)

Converts normalized landmark positions into pixel coordinates

Draws hand skeletons on the live video feed

Supports multiple hands simultaneously

Provides a simple interface for gesture recognition or custom interactions

How It Works
MediaPipe Hands processes each frame from the webcam to detect hands.

The model identifies 21 hand landmarks for each detected hand.

The module converts these normalized landmark coordinates into pixel coordinates.

The detected landmarks and hand connections are drawn on the frame using OpenCV.

The processed frame is displayed in real time.
