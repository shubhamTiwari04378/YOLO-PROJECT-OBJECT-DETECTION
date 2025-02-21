# YOLO-PROJECT-OBJECT-DETECTION
# YOLOv8 Object Tracking with OpenCV

This project uses the YOLOv8 model for real-time object tracking in videos. The implementation leverages the `ultralytics` library for YOLOv8 and OpenCV for video processing and visualization.

## 📌 Features
- Loads a YOLOv8 model (`yolov8n.pt`).
- Reads a video file and processes each frame.
- Detects and tracks objects in the video.
- Displays the processed video with object tracking.

## 🚀 Usage
1. **Clone the repository** and navigate to the project directory.
2. **Ensure the video file exists** and update the `video_path` in `main.py` accordingly.
3. **Run the script** to start object tracking.
4. **Control the video playback** using `Q` to exit.

## 🔧 Troubleshooting
- If the video does not load, check the file path and format.
- If the video is slow or lags, consider resizing frames:
  ```python
  frame = cv2.resize(frame, (640, 480))
  ```

