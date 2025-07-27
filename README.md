This project implements a real-time face detection and augmentation system utilizing OpenCV's Haar cascade classifiers. The application captures live video input from a webcam, detects human faces within the frames, and overlays graphical filters—such as hats—precisely positioned relative to detected facial regions.

Key features include:

Face Detection: Employs Haar cascades for robust and efficient identification of faces in varying lighting and orientations.

Filter Overlay: Applies transparent PNG images with alpha channels, dynamically scaled and positioned based on face size and location to simulate virtual accessories.

Interactive Controls: Provides keyboard-based toggling of the webcam feed and graceful termination of the application.

Extensibility: Modular design enabling easy addition or modification of graphical filters and detection parameters.
