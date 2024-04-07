# Drowsiness Detection System

## Agenda:
Drowsy driving is responsible for 21% of fatal accidents, and an estimated 6,400 people die every year in crashes involving drowsy driving. Most sleep-related crashes happen on motorways and dual-carriageways, probably because of the monotonous road environment and lack of driver stimulation.

## Required Packages
1) scipy
2) immutils
3) pygame
4) opencv
5) dlib
   
## Installing Packages:

##### Installing Scipy
```bash
pip install scipy
```
##### Installing Pygame
```bash
pip install pygame
```
##### Installing Opencv
```bash
pip install opencv
```
##### Installing dlib
Before installing dlib follow these this link https://youtu.be/eaEndTeUiSU?si=rJGFAf6EGzhhJ5OE
```bash
pip install dlib
```
## Working:
The provided code implements a driver drowsiness detection system using computer vision techniques. It begins by importing necessary libraries such as scipy, imutils, dlib, cv2, and pygame for various functionalities like distance calculation, image manipulation, facial landmark detection, and sound playback. The core functionality is encapsulated within a while True loop, continuously capturing frames from the webcam feed. These frames are then processed to detect faces using the dlib library, followed by the prediction of facial landmarks. Utilizing the facial landmarks, specifically those corresponding to the eyes, the script calculates the eye aspect ratio (EAR) to determine the level of drowsiness. When the EAR falls below a predefined threshold, indicative of drowsiness, the system triggers an alert by displaying a message on the frame and playing an alarm sound. This alert persists for a certain number of frames to ensure the drowsiness detection is sustained over time. The loop continues until the user terminates it by pressing the 'q' key, at which point the program releases the resources and exits gracefully. Overall, this code exemplifies the integration of computer vision techniques to address real-world problems, specifically targeting driver safety through drowsiness detection.

![eye](https://github.com/pabbathikarthikeya/Driver-Drowsiness/assets/124424165/8bf3bbaf-c435-485c-8839-82458d41c831)

![face](https://github.com/pabbathikarthikeya/Driver-Drowsiness/assets/124424165/92927cec-65af-49e5-b971-9b79d562fed9)

## Execution:
Run the code either using jupyter or python framework

To run the code 
```bash
python drowsiness.py
```

##### Made By P.V.Karthikeya
##### KL University
##### Email:2100039067cse.r@gmail.com
##### Phone:7815982634




