# FACIAL EMOTION DETECTION USING DL

Emotion_Classification using FER_Dataset and Web_app Deployment using Flask

Introduction:
Facial recognition technology has gained significant attention in recent years due to its diverse applications in various fields, including security systems, identity verification, and personalized user experiences. This report presents the development and implementation of a facial recognition project using Convolutional Neural Networks (CNNs). The project aims to accurately detect and classify faces in real-time, enabling the identification of individuals based on their unique facial features.

Abstract:
The facial recognition project utilizes CNNs, a deep learning algorithm renowned for its exceptional performance in image recognition tasks. The project involves multiple steps, including dataset creation, model training, and face classification. The project's objective is to develop an accurate and efficient facial recognition system that can recognize individuals and classify them into predetermined categories.

Steps Followed:
Dataset Creation:
The first step in the project involves creating a comprehensive dataset of facial images. This dataset serves as the foundation for training the facial recognition model. The dataset includes images of individuals from various angles, lighting conditions, and expressions, capturing the variations in facial features.

Data Preprocessing:
Prior to training the CNN model, the dataset undergoes preprocessing steps to enhance the training process. This includes resizing the images to a standard size, normalizing pixel values, and augmenting the dataset through techniques like image rotation, flipping, and zooming. Data augmentation helps to increase the diversity of the dataset and improves the model's ability to generalize.

Model Architecture:
The CNN model architecture is designed to effectively learn and extract meaningful features from facial images. It typically consists of multiple convolutional layers for feature extraction, followed by fully connected layers for classification. The architecture may include additional components such as pooling layers, dropout layers, and activation functions to improve model performance.

Model Training:
The dataset is divided into training and validation sets. The CNN model is trained on the training set using backpropagation and gradient descent optimization algorithms. During training, the model learns to identify unique facial features that distinguish one individual from another. The model's performance is evaluated on the validation set, and adjustments are made to the model's parameters to optimize its accuracy.

Model Testing and Evaluation:
Once the model is trained, it is evaluated on a separate test set that was not used during training. The trained model is deployed to recognize and classify faces in real-time. The accuracy of the model is measured by comparing the predicted labels with the ground truth labels. Evaluation metrics such as accuracy, precision, recall, and F1 score are used to assess the model's performance.

Real-Time Face Recognition:
In the final step, the trained model is integrated into a real-time face recognition system. The system captures live video or images from a webcam, detects faces using the trained model, and matches them with the stored representations of known individuals. The system can identify individuals in real-time and perform specific actions based on their recognition, such as granting access or displaying personalized information.

Features Included:
Development of Webpage using Flask:
We have developed a webpage using Flask which transfers the image in the form of base 64 String Format and apply the model deployed and calculate the probabilitscore of the image given as input.Here is the Model Deployment that is shown below.

image

After the Image Uploaded:

image

#Real Time Facial Emotion Detection Implementation:

image

Conclusion:
The facial recognition project successfully implements a facial recognition system using CNNs. By following the aforementioned steps, the project achieves accurate face detection, classification, and real-time recognition capabilities. The developed system holds promising applications in various domains, including security, surveillance, and personalized user experiences. Future work may involve further optimization of the model architecture, exploring additional data augmentation techniques, and expanding the dataset to enhance the system's performance and robustness
