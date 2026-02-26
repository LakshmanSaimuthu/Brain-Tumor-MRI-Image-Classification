# Brain-Tumor-MRI-Image-Classification
Brain Tumor MRI Image Classification project uses deep learning and transfer learning models to classify brain MRI images into tumor categories. Custom CNN and pretrained models were trained with data augmentation, evaluated using accuracy and F1-score, and deployed via a Streamlit web app for real-time predictions.

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
