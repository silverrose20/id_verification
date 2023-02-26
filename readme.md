## What is this?
This is a web-based ID Verification application. It uses webrtc to capture a video from your webcam. It detects your face and your face in the ID photo and compares them. It will verify your ID if the two faces are identifies as the same person.

## How it works
1. This is the home page (https://capstonertc-dzvisiwhya-wl.a.run.app).

<img src="https://github.com/silverrose20/id_verification/blob/master/pics/home_screen2.jpg" height="50%" width="50%"> 

2. Get your ID card (a driver's license, passport, etc.) ready.
3. Click START to connect your webcam. 
4. Hold your ID photo in front of the camera and look at the camera.
5. If you are holding your photo, you will see "Verified" and green rectangles around the faces.

<img src="https://github.com/silverrose20/id_verification/blob/master/pics/Verified2.jpg" height="40%" width="40%">

6. If you are holding someone else's photo, you will see "Not Verified" and red rectangles around the faces.

<img src="https://github.com/silverrose20/id_verification/blob/master/pics/NotVerified.jpg" height="40%" width="40%">

7. Click STOP to close the video screen.

## Dependencies/Libraries
- cmake
- dlib==19.24.0
- keras==2.11.0
- numpy==1.24.1
- opencv-python==4.7.0.68
- streamlit==1.17.0
- streamlit-webrtc==0.44.2
- tensorflow==2.11.0

## Challenges/Improvements
This application works in a local host, but it does not when it is deployed in the cloud. 
The webcam connects but disconnects in a few seconds.

