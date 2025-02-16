# Intelligent Agent Design: Dobot Robotic Arm

## Overview
This project is part of a group effort in an **Intelligent Agent Design** course. The goal was to create an intelligent system to control a Dobot robotic arm for arranging boxes based on digits. My specific responsibility in this project was to **train a Convolutional Neural Network (CNN)** to detect digits in real-time and integrate OpenCV techniques to filter out noise, ensuring only digits were recognized.

## Group Objective
Develop an intelligent system capable of:
1. Detecting and recognizing digits displayed on boxes.
2. Identifying box midpoints based on digits.
3. Sending the coordinates to a Dobot robotic arm for precise box arrangement.

## My Contribution
- **CNN Training:** Designed and trained a CNN model to recognize digits with high accuracy.
- **Noise Filtering:** Applied masking and OpenCV techniques to eliminate non-digit noise from the image.
- **Integration:** Ensured the digit recognition system worked seamlessly in real-time with a webcam feed for further processing by other team members.

## Features
- Real-time digit detection using a trained CNN model.
- Noise filtering to prevent false positives in digit recognition.
- Integration-ready for robotic applications, such as Dobot control.

## Technologies Used
- **Python**
- **TensorFlow/Keras** (for CNN training)
- **OpenCV** (for noise filtering and image preprocessing)

## How It Works
1. **Data Preparation:** 
   - Collected and preprocessed a dataset of digits for training.
   - Augmented the dataset to improve model robustness.
2. **Model Training:** 
   - Designed a CNN architecture for digit recognition.
   - Trained the model on a labeled dataset to achieve high accuracy.
3. **Noise Filtering:**
   - Applied OpenCV masking techniques to focus on the digits and ignore background noise.
4. **Real-Time Digit Detection:** 
   - Integrated the trained model with a webcam feed for real-time digit recognition.
5. **Output:** 
   - Detected digits and their positions were passed to the team for robotic arm control.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/digit-detection-dobot.git
