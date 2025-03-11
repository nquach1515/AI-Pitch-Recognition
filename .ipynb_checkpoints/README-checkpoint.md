# AI-Pitch-Recognition
Overview

AI-Pitch-Recognition is a computer vision-based system designed to identify baseball pitches using optical flow estimation and deep learning. This project leverages machine learning models trained on baseball pitch videos to classify different pitch types based on motion patterns and visual cues.

Features:

- Optical Flow Estimation: Tracks the motion of the baseball and key points in the pitching sequence to determine pitch type.

- YOLOv8 Object Detection: Identifies relevant field components such as the pitcher, batter, and baseball.

- MLB Pitch Video Analysis: Uses a dataset of MLB pitching videos for model training and evaluation.

- Pitch Classification: Classifies pitch types such as fastballs, curveballs, sliders, and changeups.

- Deep Learning Integration: Incorporates convolutional neural networks (CNNs) for feature extraction and classification.

Data Sources:

Roboflow Dataset: 2.4k images in YOLOv8 format for object detection.

MLB Pitching Videos: Self-compiled dataset of MLB videos filtered by specific pitch types.

Frame Sequences: Extracted from pitching videos for training optical flow models.