# Doori
Using python, deep learning, and computer vision to monitor social distancing.
Idea Credits: LandingAI

Objective & Problem Statement:
1. In the current Covid-19 situation, safety measures taken by the governments around the world have failed in front of Covid-19, due to lack of social distancing practice.
2. Newer variants of the virus have emerged that are equivalent to or more dangerous than the previous one. Thus, it becomes a monumental challenge to tackle the issue of social distancing in an overly populated country like India.
3. Doori aims to combine Computer Vision to create a real-time social distance monitoring software so that administrators can use them to locate a breach of bio-bubbles. It uses the OpenCV library and YOLO v3 for real-time human detection.

Hardware & software requirements:
-The Software requirements are:
OpenCV for Python
-Hardware requirements include:
Camera
24x7 running System for seamless tracking and to run python script

Overall system architecture diagram:
1. Apply object detection to detect all people (and only people) in a given image/frame.
2. Compute the pairwise distances between all detected people.
3. Based on these distances, check to see if any two people are less than N pixels apart.
4. Loop the entire process for all consequent frames.

[![Watch the video](/images/cover.png)](https://www.youtube.com/watch?v=kxFwbn7Tap0&feature=emb_title)

~ By Prantik (Junior Developer)
