# Hand-sign-detection-using-python
Hand sign detection using the mediapipe library! The code captures video from the webcam, processes hand landmarks, and detects gestures like “LIKE” and “DISLIKE” based on finger positions.

Here’s a brief overview of what this code does:

1- It initializes the mediapipe hands module and sets up the webcam capture.
2- Defines the fingertip indices and thumb tip index.
3- Loads images for “LIKE” and “DISLIKE” gestures.
4- Processes hand landmarks and checks if fingers are folded or extended.
5- If all fingers are folded, it identifies whether the thumb is up or down.
6- Displays the corresponding text (“LIKE” or “DISLIKE”) and overlays the respective image.
