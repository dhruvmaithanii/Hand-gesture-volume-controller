# Hand-gesture-volume-controller
This project uses hand tracking to control system volume via thumb-index finger distance using a webcam. The system detects hand gestures in real-time and adjusts the volume accordingly.

Libraries Used:
OpenCV – Captures video from the webcam and processes images.
MediaPipe – Tracks hand landmarks for detecting gestures.
NumPy – Used for mathematical operations and interpolation.
PyCaw – Controls system volume programmatically.
Math – Calculates the distance between fingers.
Working Principle:
The webcam captures hand movements.
MediaPipe detects key landmarks on the hand.
The distance between the thumb and index finger determines volume level.
PyCaw adjusts the system volume accordingly.
A real-time volume bar is displayed
