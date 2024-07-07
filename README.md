This project focuses on creating an eye-controlled mouse application using OpenCV, MediaPipe, and PyAutoGUI to track eye movement and control the mouse cursor. The workflow begins with initializing the webcam to capture video frames, which are then processed using OpenCV. MediaPipe's Face Mesh is employed to detect and refine facial landmarks, particularly focusing on the eyes. The video frames are flipped horizontally for a mirror-like effect and converted from BGR to RGB color space for accurate landmark extraction. Specific eye landmarks are mapped to the screen size, enabling the movement of the mouse cursor based on eye position. Additionally, blink detection is implemented by calculating the vertical distance between specific eye landmarks, triggering a mouse click when a blink is detected. The application visualizes the detected eye landmarks on the video frame and displays the processed video with annotations. Users can control the mouse cursor by moving their eyes and perform mouse clicks by blinking. The project demonstrates the integration of computer vision and human-computer interaction techniques, providing a hands-free mouse control system that enhances accessibility and interaction. Proper lighting conditions and possible adjustments to the blink detection threshold may be necessary for optimal performance.
