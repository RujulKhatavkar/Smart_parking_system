# Smart_parking_system

# Parking Space Occupancy Detection System

## Overview

This repository contains the source code and documentation for a parking space occupancy detection system. The system is designed to capture live frames from a camera, process them for parking space occupancy detection, and provide real-time updates on the status of parking spaces. The core functionality involves using the YOLO (You Only Look Once) framework for efficient car detection, with Firebase serving as a real-time NoSQL cloud database for data storage and synchronization.

## Features

- **Live Frame Capture:** The system captures live frames from a camera to monitor parking spaces.

- **Grayscale Conversion and Normalization:** Initial preprocessing steps involve converting images to grayscale and normalizing them for enhanced processing.

- **YOLO Framework:** The YOLO framework is employed for real-time car detection. YOLO's efficiency lies in simultaneously predicting bounding boxes and class probabilities across a grid, making it suitable for identifying multiple objects within an image.

- **Car Counting:** Bounding box coordinates are averaged over time to improve stability, enabling accurate car counting.

- **Firebase Integration:** The system utilizes Firebase as a real-time NoSQL cloud database to store and synchronize occupancy status data. This ensures real-time updates and user verification.

- **Efficient Parking Space Monitoring:** The integrated approach of YOLO for object detection and Firebase for data storage ensures efficient and accurate parking space monitoring and management.

**Dependencies:**
   Ensure that you have all the required dependencies installed. This may include libraries for image processing, YOLO, and Firebase SDK.

**Configuration:**
   Update the configuration files with your specific camera details and Firebase credentials.

## Documentation

Refer to the [documentation](docs/) folder for detailed information on system architecture, configuration, and usage.

## Acknowledgments

- The YOLO framework: [YOLO GitHub Repository](https://github.com/AlexeyAB/darknet)
- Firebase for real-time cloud database: [Firebase](https://firebase.google.com/)

Feel free to contribute, report issues, or suggest improvements! Happy parking space monitoring!
