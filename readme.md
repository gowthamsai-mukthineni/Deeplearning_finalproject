# Data-Driven Feature Tracking for Aerial Imagery

## Objective
This project aims to apply a data-driven feature tracking method, originally designed for event cameras, to aerial imagery. By extracting features and building feature tracks over a sequence of images, this project seeks to estimate 3D camera poses using a Structure-from-Motion (SfM) algorithm. Additionally, the accuracy and robustness of the recovered camera poses will be evaluated.

## Goals
1.Feature Tracking Pipeline: Develop a robust feature tracking pipeline for aerial imagery using event camera technology.
2.3D Pose Estimation: Generate feature tracks from an aerial image sequence, integrating them with an SfM algorithm to estimate 3D camera poses.
3.Evaluation: Assess the accuracy and reliability of reconstructed camera poses across varied environmental conditions.

## Dependencies
Python 3.8+
Libraries: OpenCV, NumPy, PyTorch, COLMAP (or other SfM software)
Other Tools: Event-to-frame converters, data synchronization utilities
