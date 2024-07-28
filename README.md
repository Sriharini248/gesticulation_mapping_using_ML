# gesticulation_mapping_using_ml
# Gesticulation Mapping Using ML

## Project Overview

This project introduces a cutting-edge method to interact with PowerPoint presentations using hand gestures, making the process intuitive and hands-free. Leveraging the capabilities of OpenCV, a leading computer vision library, the system accurately interprets hand gestures in real-time, enabling effortless control of presentation slides.

## Key Features

- **Hand Gesture Recognition**: Integrates Haar Cascade classifiers for robust and precise hand detection, allowing accurate identification of hand regions within the camera feed.
- **Face Recognition Security**: Utilizes the Local Binary Patterns Histograms (LBPH) algorithm for face recognition, ensuring only authorized users can access slide control functionalities, thereby enhancing the confidentiality of sensitive information.
- **Seamless Experience**: Combines gesture recognition with face security checks, providing an engaging experience for presenters without the need for traditional input devices.

## Objectives

1. Develop a hand gesture recognition system using OpenCV for controlling PowerPoint slides.
2. Integrate face recognition for secure authentication of users.
3. Create an intuitive user interface for seamless interaction.
4. Implement security measures to prevent unauthorized access.
5. Test, optimize, and fine-tune the system for reliability and performance.

## System Requirements

### Software Requirements

- PyCharm Community
- Python version 3.7.7 & 3.7.4
- OpenCV
- NumPy
- PIL (Python Imaging Library)
- Cvzone

### Hardware Requirements

- RAM: 8GB
- Hard Disk: 250GB
- Processor: Intel Core Processor i5 & i7

## Existing System

- Human-computer interaction through gesture detection eliminates the need for traditional input devices like keyboards and mice.
- Previous methods utilizing gloves and markers increased system costs for gesture control.
- Current technology employs OpenCV and image processing for hand gesture recognition and slide control.
- The system enables presenters to seamlessly navigate PowerPoint slides using a range of hand gestures, enhancing presentation delivery.

## Proposed System

- **Gesture Control**: Gesture-controlled PowerPoint slides with hand movement analysis for user command interpretation using gesture threshold.
- **Security Integration**: Face recognition using LBPH and OpenCV for user authentication.
- **Authentication System**: The face authentication system captures and trains user data using a Haar Cascade Classifier, while the hand gesture control module uses the Hand Detector class from the Cvzone library.
- **Hand Tracking**: Combines hand segmentation techniques and hand tracking algorithms to isolate the hand from the background and track its movement and gestures in real-time.

## List of Modules

1. Hand Tracking Module
2. Face Database Creation Module
3. Face Recognition Training Module
4. Face Authentication Module
5. Integration Module

## Algorithms/Techniques/Methodologies Used

- **Face Detection**: Utilized Haar Cascade Classifier for face detection in the `face_generator()` function.
- **Face Recognition**: Training the face recognition model using the LBPH (Local Binary Patterns Histograms) algorithm from OpenCV.
- **Hand Detection**: Integrates the Hand Detector module from the Cvzone library for real-time hand detection and landmark tracking.
- **Image Processing**: OpenCV functions like `cv2.imread`, `cv2.cvtColor`, `cv2.rectangle`, `cv2.putText`, `cv2.line`, `cv2.resize`, and `cv2.imshow` are extensively used for image processing, drawing annotations, and displaying frames.
- **Gesture Threshold**: Sets a gesture threshold to differentiate between hand gestures and other hand movements.
## EXPERIMENT RESULTS / OUTPUTS
## HAND GESTURES
![image](https://github.com/user-attachments/assets/10eda197-cfd9-43b8-90e1-486076f650e1)

![image](https://github.com/user-attachments/assets/2d719713-8ac4-466c-b3f1-6dea65317f46)

![image](https://github.com/user-attachments/assets/e1b648ba-231c-44fa-a3d9-b23b63846897)

[a] represents the gesture to write or make notes in the Presentation
[b] represents the gesture to move to the previous slide
[c] represent the gesture to erase the content written in the Presentation
[d] represent the gesture to move the next slide
[e] represent the gesture to show a Pointer
[f] represent the gesture to Zoom in and Zoom Out
 ## FACE DETECTION
![image](https://github.com/user-attachments/assets/d22607f2-096c-42e2-a339-65d490ba3aea)

![image](https://github.com/user-attachments/assets/916a94d6-6c2f-4576-9550-eef7d056b229)

## Conclusion

By combining advanced gesture recognition and secure face authentication, this project aims to revolutionize the way presentations are controlled, making the process more intuitive, secure, and engaging for users.
