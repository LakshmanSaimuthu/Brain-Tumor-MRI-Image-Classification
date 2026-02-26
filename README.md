# Brain-Tumor-MRI-Image-Classification
Brain Tumor MRI Image Classification is a deep learning project that classifies MRI brain scans into tumor categories using transfer learning and custom CNN models.  
The system includes data preprocessing, augmentation, model training, evaluation, and a Streamlit web app for real-time prediction.

## Skills Demonstrated
- Deep Learning (CNN, Transfer Learning)
- Image Processing & Data Augmentation
- Model Evaluation (Accuracy, F1-score)
- Python, TensorFlow, Keras
- Streamlit Deployment
  
1️⃣ Dataset Understanding

Loaded and explored the Brain Tumor MRI dataset

Identified different tumor categories and sample images

Checked class distribution to detect imbalance

Verified image resolution and quality consistency

2️⃣ Data Preprocessing

Normalized pixel values to the 0–1 range

Resized all MRI images to a fixed size (224×224)

Converted images into a format suitable for deep learning models

3️⃣ Data Augmentation

Applied augmentation techniques such as rotation, flipping, zoom, brightness adjustment, and shifting

Increased dataset diversity to improve generalization

Reduced overfitting during training

4️⃣ Custom CNN Model Development

Designed a Convolutional Neural Network from scratch

Added convolution, max-pooling, and dense layers

Used Batch Normalization and Dropout for training stability

5️⃣ Transfer Learning Implementation

Loaded pretrained models with ImageNet weights

Implemented models such as ResNet50, MobileNet, InceptionV3, and EfficientNetB0

Replaced top layers with custom classification layers

Fine-tuned upper layers for better performance

6️⃣ Model Training

Trained both custom CNN and transfer learning models

Used EarlyStopping to prevent overfitting

Used ModelCheckpoint to save the best-performing model

7️⃣ Model Evaluation

Evaluated models using accuracy, precision, recall, and F1-score

Analyzed confusion matrix to understand misclassifications

Visualized training and validation accuracy and loss

8️⃣ Model Comparison

Compared performance of custom CNN and pretrained models

Selected the most accurate and efficient model for deployment

9️⃣ Streamlit Deployment

Built an interactive Streamlit web application

Enabled users to upload MRI images

Displayed predicted tumor type with confidence score

🔟 Final Outcome

Successfully developed an end-to-end deep learning solution

Delivered a deployable AI system for brain tumor classification

Demonstrated practical application of AI in medical imaging

# Dataset Information

# Labeled MRI Brain Tumor Dataset > Version 1
https://universe.roboflow.com/ali-rostami/labeled-mri-brain-tumor-dataset

Provided by a Roboflow user
License: CC BY 4.0

This project has created a labeled MRI brain tumor dataset for the detection of three tumor types: pituitary, meningioma, and glioma. The dataset contains 2443 total images, which have been split into training, validation, and test sets. The training set has 1695 images, the validation set has 502 images, and the test set has 246 images.

**Data:**
* Number of images: 2443
* Image types: MRI scans

**Classes:**
* Pituitary tumor
* Meningioma tumor
* Glioma tumor
* No Tumor

**Split:**
* Training set: 1695 images
* Validation set: 502 images
* Test set: 246 images

**Labeling:**
* The images have been labeled by medical experts using a standardized labeling protocol.
* The labels include the type of tumor and the location of the tumor.

**Potential Applications:**
* This dataset can be used to train machine learning models to automatically classify brain tumors.
* The models could be used to assist radiologists in diagnosing brain tumors.
* The dataset could also be used to develop new treatments for brain tumors.
