## AI-DRIVEN CLASSIFICATION OF OCULAR DISEASES

This project focuses on building a highly accurate image classification model using the InceptionResNetV2 architecture. The main goal is to improve the model’s performance by using data augmentation and transfer learning. These techniques help the model generalize better, avoid overfitting, and perform well even on unseen images. The project shows how advanced deep learning methods can be used for real-world image recognition tasks.

## Dataset
The dataset consists of approximately 4000 retinal images categorized into four classes: Normal, Diabetic Retinopathy, Cataract, and Glaucoma, with around 1000 images per class. These images are collected from multiple sources like IDRiD, Ocular Recognition, and HRF, and are available on Kaggle.

## Model Architecture
The InceptionResNetV2 model was used in this project. It combines Inception modules and ResNet’s residual connections to extract complex features from images. Transfer learning was applied by using pre-trained weights. The model includes:
  1. Convolutional layers
  2. Residual connections
  3. ReLU activation
  4. Fully connected layers
  5. Softmax output
Training used the Adam optimizer and categorical cross-entropy loss.

## Result
The model achieved high accuracy:
  * Without Augmentation: 92.8%
  * With Augmentation: 96.5%

This shows that data augmentation significantly improved the model's performance. The model is both accurate and reliable for image classification tasks.

## How to Use
  Prepare Data: Organize images into class folders. Apply augmentation if needed.
  
  Load Model: Use the InceptionResNetV2 model with pre-trained weights.
  
  Train Model: Fine-tune using the augmented dataset.
  
  Predict: Use the trained model to classify new images.
  
  Evaluate: Check performance using accuracy, precision, recall, and F1-score.

This model can be used for various real-world image recognition applications.
