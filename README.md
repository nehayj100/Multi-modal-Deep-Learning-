# Multi-Modal Digit Classification System

## Motivation
The increasing demand for accurate and efficient digit recognition systems has led to the exploration of innovative techniques that integrate multiple data modalities. This project aims to enhance the accuracy of handwritten digit classification by leveraging both visual and auditory information. By combining image data from handwritten digits with corresponding spoken audio samples, we can create a more robust classification model that outperforms traditional single-modal approaches.

## About
This project presents a multi-modal learning technique for handwritten digit classification. By integrating a Convolutional Neural Network (CNN) for image processing and a Recurrent Neural Network (RNN) for audio analysis, we developed a system that achieves 99.8% accuracy. Our model demonstrates a significant improvement in performance—1% and 9% respectively—compared to individual image and audio models.

## Features
- **Multi-Modal Learning:** Combines image and audio data to enhance classification accuracy.
- **High Accuracy:** Achieved 99.8% accuracy in digit classification tasks.
- **Latent Fusion Technique:** Seamlessly integrates information from both image and audio modalities.
- **Real-Time Classification:** Deployed for real-time Optical Character Recognition (OCR) and audio classification.
- **Production-Ready:** Utilizes AWS ECS and Docker for scalable deployment.

## Uses
- **Real-Time Digit Recognition:** Ideal for applications requiring instant digit identification, such as automated data entry systems.
- **Educational Tools:** Can be integrated into learning platforms to assist students in recognizing handwritten digits.
- **Accessibility Solutions:** Enhances accessibility for visually impaired users by providing audio feedback for digit recognition.

## Tech Stack
- **Deep Learning Frameworks:** PyTorch 
- **Image Dataset:** MNIST handwritten digit dataset
- **Audio Samples:** Corresponding spoken audio samples for each digit
- **Model Architecture:**
  - **CNN:** 4-layer Convolutional Neural Network for image processing
  - **RNN:** 1-layer Recurrent Neural Network for audio analysis
- **Integration Technique:** Latent fusion for combining modalities
- **Deployment:** AWS ECS, Docker for containerization and scalability

Feel free to explore the repository for implementation details and further insights into the project!

![mnist_2](https://github.com/user-attachments/assets/05d1afea-2858-454e-abb7-d2d9c1e2d082)

