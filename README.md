🦷 Dental Disease Detection Using Image-Based Machine Learning

This project presents a deep learning–based system for automated dental disease detection using oral images. The system leverages an enhanced MobileNetV2 convolutional neural network with transfer learning to classify common dental conditions efficiently and accurately.

The model is trained on a labeled dental image dataset and is capable of identifying six dental disease categories:

1. Calculus
2. Caries
3. Gingivitis
4. Mouth Ulcer
5. Tooth Discoloration
6. Hypodontia

The application supports two modes of input:

Real-time webcam detection for live dental image analysis

Static image file prediction for offline diagnosis

Image preprocessing techniques such as resizing, normalization, and tensor conversion are applied to ensure consistency and improved model performance. The system outputs both the predicted disease class and a confidence score, with low-confidence predictions marked as Uncertain to enhance reliability.

Model performance is evaluated using standard classification metrics including accuracy, precision, recall, F1-score, and confusion matrix analysis. Due to its lightweight architecture, the system is suitable for real-time and resource-constrained environments.

This project demonstrates the potential of machine learning in dental healthcare by providing a cost-effective, non-invasive, and accessible solution for preliminary dental disease screening.

Tech Stack :-
1. Python
2. PyTorch
3. OpenCV
4. Torchvision
5. NumPy
6. Scikit-learn

🚀 Applications :-

1. Preliminary dental disease screening
2. Clinical decision support systems

Tele-dentistry and remote healthcare

Educational and research purposes
