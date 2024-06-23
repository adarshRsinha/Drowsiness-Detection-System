# Drowsiness-Detection-System

## Description

### This system implements a drowsiness detection system using eye aspect ratio and alerts the user when drowsiness is detected. It also plays music to help keep the user alert which help so that the user can doing the work well.

## Features

- ### Real-time Video Feed: Displays a live video feed from the camera.
- ### Eye Contours Overlay: Draws contours around detected eyes on the video feed.
- ### Alert Message: Shows a visual alert message on the video feed when drowsiness is detected.
- ### Facial Landmark Detection: Uses Dlib for detecting and predicting facial landmarks.
- ### Eye Aspect Ratio (EAR) Calculation: Computes EAR to monitor eye openness and detect drowsiness.
- ### Music Playback: Utilizes pygame to play predefined music files as an alert when drowsiness is detected.

## Technologies Used

### This System is built using the following technologies and libraries:

- ### OpenCV: Utilized for capturing video frames, processing images, and drawing contours around eyes.
- ### Dlib: Provides facial landmark detection and shape prediction functionalities.
- ### imutils: Used for resizing frames and converting them between color spaces.
- ### pygame: Enables playback of music files to alert the user when drowsiness is detected.

## Usage

- ### Uses computer vision techniques to detect facial landmarks and calculate the eye aspect ratio (EAR).
- ### Monitors the EAR to determine if the person's eyes are closing, indicating potential drowsiness.
- ### Alerts the user with a visual message on the video frame when drowsiness is detected.
- ### Plays a series of predefined music files to help keep the user awake and alert.
