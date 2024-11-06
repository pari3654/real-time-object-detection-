# real-time-object-detection-
1. OVERVIEW-
   - Real-time object detection refers to the ability to identify and classify objects within video feeds as they are captured.
   - It allows systems to detect and track multiple objects simultaneously, providing immediate feedback. 

 2. WHAT IT DOES-
   Real-Time Detection:
   - The system detects various objects in real-time, including people, vehicles, animals, and more.
   - It draws bounding boxes around the objects with confidence levels, ensuring that the objects are identified correctly.
    Output:
   - Each frame from the video is analyzed by the model.
   - Detected objects are marked with bounding boxes and classified labels (e.g., "person", "car").

 3.HOW WE BUILT-
   Tech Stack:
    Python: Main programming language for implementing the model and video processing.
    OpenCV: Used for video capture, frame extraction, and displaying the processed frames.
    YOLO Model: The YOLOv8 weights file is loaded and used to process video frames and detect objects.

4. RESULT -
    Real-Time Detection:
   - Successfully implemented a system that detects and labels objects in video streams in real-time with low latency.
   - The system can detect multiple objects in a frame and classify them accurately with bounding boxes.
