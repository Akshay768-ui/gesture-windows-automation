# Gesture-Based Windows Automation using Computer Vision & Touch

## Description
This project presents a multimodal human-computer interaction system that enables users to control Windows functionalities using both touch gestures and vision-based hand gestures.

The system integrates real-time hand tracking (MediaPipe) with touch gesture recognition (UWP APIs) to perform actions such as file transfer, brightness control, and screenshot capture.

## Objective
To develop an intuitive and efficient alternative to traditional keyboard/mouse interactions by enabling gesture-driven system control.

## Technologies Used
- Python (MediaPipe for computer vision)
- C# / UWP APIs (Touch gesture recognition)
- Google Drive API (Cloud integration)
- NSIS (Application packaging)

## Key Features
- Gesture-based file transfer to Google Drive
- Real-time brightness control using hand gestures
- Gesture-triggered screenshot capture
- System tray notifications and feedback
- Background execution with low resource usage
- Multimodal interaction (touch + vision)

## Workflow
1. Detect touch gestures using UWP APIs
2. Capture hand gestures using laptop camera (MediaPipe)
3. Map gestures to system actions
4. Execute tasks (file transfer, screenshot, brightness)
5. Provide real-time feedback via system tray

## Performance Metrics
- Touch Gesture Accuracy: 97%
- Vision Gesture Accuracy: 94% (well-lit), 89% (low-light)
- Latency: 60 ms (touch), 80 ms (vision)
- CPU Usage: <7%
- Memory Usage: <80 MB
- File Transfer Speed: ~2.1 MB/s

## Architecture Highlights
- Modular design for easy scalability
- Hybrid integration of Python (vision) + C# (system control)
- Real-time processing with minimal latency
- Portable executable for deployment

## Key Insights
- Multimodal systems improve usability and flexibility
- Vision-based gestures depend on lighting conditions
- Touch gestures provide higher reliability
- Hybrid approach balances accuracy and usability

