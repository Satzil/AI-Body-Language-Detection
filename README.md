# AI Body Language Detection with Mediapipe and OpenCV



https://github.com/Satzil/AI-Body-Language-Detection/assets/95362584/c5ed4231-d736-4d86-b692-cb4cb5b725ef



## Project Description

The "AI Body Language Detection" project employs Mediapipe, a custom classification model, and OpenCV to analyze and interpret human body language in real-time, focusing on classes such as "happy," "sad," and "victorious." By combining state-of-the-art pose detection with a specialized classification algorithm, the system provides insights into the emotional state and expressions of individuals.

## Key Features

1. **Mediapipe Pose Detection:**
   - Utilizes the Mediapipe library for accurate and efficient full-body pose detection.
   - Captures key landmarks on the human body, including facial features, hands, and body joints.

2. **Custom Classification Model:**
   - Implements a custom machine learning classification model trained to recognize body language classes: "happy," "sad," and "victorious."

3. **Real-time Processing with OpenCV:**
   - Integrates OpenCV for real-time video capture and processing.
   - Applies the pose detection and classification model to each frame, enabling dynamic analysis of body language.

4. **Visualization and Overlays:**
   - Visualizes the detected body poses in real-time on the video feed.
   - Overlays informative graphics to highlight key body landmarks and provides insights into recognized emotional states.

5. **User Interface:**
   - Implements a user-friendly interface using OpenCV windows to display the webcam feed and analysis results.
   - Includes informative status boxes showing the detected body language class and probability.

6. **Interpretation of Body Language:**
   - Classifies body language into meaningful emotional categories: "happy," "sad," or "victorious" based on the trained model.
