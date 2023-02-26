## What is this?
This is a web-based ID Verification application. It uses webrtc to capture a video from your webcam. 
Let's see how it works.

## How it works
1. This is the main page (https://capstonertc-dzvisiwhya-wl.a.run.app).
![Home Screen](pics/home_screen.jpg)
2. Get your ID card (a driver's license, passport, etc.) ready.
3. Click START to connect your webcam. 
4. Hold your IP photo in front of the camera and look at the camera.
5. If you are holding your photo, you will see "Verified" and green rectangles around the faces.
![Verified screen](pics/Verified.jpg)
6. If you are holding someone else's photo, you will see "Not Verified" and red rectangles around the faces.
![Verified screen](pics/NotVerified.jpg)
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

