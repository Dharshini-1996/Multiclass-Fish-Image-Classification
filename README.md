**# Multiclass-Fish-Image-Classification**

**Problem Statement:**
This project focuses on classifying fish images into multiple categories using deep learning models. The task involves training a CNN from scratch and leveraging transfer learning with pre-trained models to enhance performance. The project also includes saving models for later use and deploying a Streamlit application to predict fish categories from user-uploaded images

**Business Use Cases:**
1. Enhanced Accuracy: Determine the best model architecture for fish image classification.
2. Deployment Ready: Create a user-friendly web application for real-time predictions.
3. Model Comparison: Evaluate and compare metrics across models to select the most suitable approach for the task.

**Approach:**
1. Data Preprocessing and Augmentation
2. Rescale images to [0, 1] range.
3. Apply data augmentation techniques like rotation, zoom, and flipping to enhance model robustness.
   
**Model Training**
1. Train a CNN model from scratch.
2. Experiment with five pre-trained models (e.g., VGG16, ResNet50, MobileNet, InceptionV3, EfficientNetB0).
3. Fine-tune the pre-trained models on the fish dataset.
4. Save the trained model (max accuracy model ) in .h5 or .pkl format for future use.
   
**Model Evaluation**
1. Compare metrics such as accuracy, precision, recall, F1-score, and confusion matrix across all models.
2. Visualize training history (accuracy and loss) for each model.
   
**Deployment**
1. Build a Streamlit application to:
      Allow users to upload fish images.
      Predict and display the fish category.
      Provide model confidence scores.

**Dataset**
   The dataset consists of images of fish, categorized into folders by species. The dataset is loaded using TensorFlow's ImageDataGenerator for efficient processing.
   Dataset:Data as Zip file : https://drive.google.com/drive/folders/1iKdOs4slf3XvNWkeSfsszhPRggfJ2qEd
