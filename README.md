# Gym-Rep-Counter-with-Posture-Correction
OpenCV,Tensorflow : rep counter for various gym exercises. Grabbed alot of attention and our AI instructor advised us to continue this as our FYP


Description: This Python script uses the MediaPipe library for pose estimation to count reps for various gym exercises such as bicep curls (right and left arm), push-ups, and shoulder presses. It uses a webcam to capture live video and processes the frames to detect key landmarks on the human body for each exercise.

Features:

Bicep Curl Counter (Right and Left Arm): The script tracks the angle of the elbow joint to count reps. It increments the counter when the arm is fully extended (angle < 30) and then brought back up (angle > 160).
Push-up Counter: The script tracks the position of the body to count push-ups. It increments the counter when the body is lowered (head and shoulders lower than hips) and then raised back up.
Shoulder Press Counter: Similar to the push-up counter, it tracks the position of the body to count shoulder presses. It increments the counter when the arms are fully extended upward and then brought back down.
Dependencies:

OpenCV (cv2)
MediaPipe (mediapipe)
NumPy (numpy)
Usage:

Ensure your webcam is connected and functional.
Run the script and perform the respective exercises in front of the webcam.
The counter for each exercise will be displayed on the screen in real-time.
Note: Make sure to position yourself properly and perform the exercises according to the specified guidelines for accurate counting.
