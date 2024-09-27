![image](IMG-20240925-WA0030.jpg)

# JUST A VOICE - BUILDATHON
Tell us about your project here

## Team Members
1.NEHA SHAJU (Nehashaju212)   
2.SREELAKSHMI UV ()   
3.PRANAV BABU ()   
4.NIRMAL JOHN ()   

## Link to Project
[Embed the live link of project](live_link)

## How it Works ?
JUST A VOICE is a sign language interpreter that bridges the communication gap between mute and non-mute individuals by translating sign language into spoken words. Here’s a step-by-step overview of how it works: 

1. Data Collection 

Video Capture: The system captures real-time video input using a webcam. 

Keypoint Detection: MediaPipe is used to detect and extract keypoints from the hands, face, and body in each frame of the video. 

2. Preprocessing 

Normalization: The extracted keypoints are normalized to ensure consistency across different videos. 

Feature Extraction: Keypoints are flattened and prepared for input into the machine learning model. 

3. Model Training 

Model Architecture: A combination of Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks is used to handle the spatial and temporal aspects of sign language. 

Training: The model is trained on a labeled dataset of sign language gestures to recognize different signs. 

4. Real-Time Inference 

Gesture Recognition: The trained model predicts the sign language gestures from the real-time video feed. 

Text Conversion: The recognized gestures are converted into text. 

5. Text-to-Speech Conversion 

Speech Synthesis: The text is converted into speech using a text-to-speech API, providing audio output for the recognized signs. 

6. User Interaction 

Visual Feedback: The system provides visual feedback by displaying the recognized sign and corresponding text on the screen. 

Audio Output: The synthesized speech is played back to the audience, enabling effective communication. 

Example Workflow: 

Start the Application: Launch the Handspeak application. 

Sign Language Input: Perform sign language gestures in front of the webcam. 

Real-Time Processing: The system captures, processes, and recognizes the gestures. 

Audio Output: The recognized signs are converted to speech and played back. 

Handspeak leverages advanced machine learning and computer vision techniques to provide an intuitive and seamless communication experience for mute and non-mute individuals.   

## Technologies used
List out tech stacks you have used

## Other Links
Provide any other links ( for eg. Wireframe , UI, Abstract, Presentation )
