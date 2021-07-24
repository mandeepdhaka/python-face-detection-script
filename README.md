# python-face-detection-script
A facial detection script, can be used to detect faces in an image, video or in live webcam streaming

In this script I used two frameworks:

1.OpenCV -4.5 - A real-time Computer Vision framework written in C/C++

2.MediaPipe -0.8.5 - An open-source cross-platform framework for customizable ML solutions developed by Google.

Process flow steps:

1.Load the image/video to cap variable.

2.Capture the video frame by frame by read() function.

3.Call the detector() function.

4.Pass the returned variables from detector() to the imgshow() to display output with detections

