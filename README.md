# Alzheimer-Disease-Classification

## 🛠️ Project Work

This project focuses on building an end-to-end deep learning pipeline for **multi-class Alzheimer’s disease classification** using brain MRI images. The work was carried out in structured stages, from data exploration to model fine-tuning.

### 1. Data Exploration & Analysis
- Performed exploratory data analysis (EDA) to understand class distribution and dataset balance.
- Visualized sample MRI images across all Alzheimer’s stages.
- Inspected image dimensions, quality, and potential data inconsistencies.
- Identified class imbalance to inform training strategies.

### 2. Data Preprocessing
- Resized all images to a uniform input size suitable for CNN architectures.
- Normalized pixel values to improve model convergence.
- Split the dataset into training and validation sets.
- Applied data augmentation techniques (rotation, flipping, zoom, brightness adjustment) to improve generalization and reduce overfitting.

### 3. Model Development
- Implemented a transfer learning approach using a pre-trained convolutional neural network as the feature extractor.
- Added a custom classification head with fully connected layers and softmax activation for four-class prediction.
- Used categorical cross-entropy loss and the Adam optimizer for training.

### 4. Training & Fine-Tuning
- Trained the model initially with frozen base layers to leverage pre-learned visual features.
- Fine-tuned the upper layers of the base model using a reduced learning rate to adapt features to medical imaging data.
- Monitored training and validation accuracy and loss to evaluate learning progress.

### 5. Model Evaluation
- Evaluated performance using validation accuracy and loss metrics.
- Analyzed training curves to detect underfitting or overfitting.
- Saved trained models for future inference and experimentation.

This structured workflow ensures the model is both **robust and scalable**, while demonstrating practical application of deep learning techniques in medical image analysis.

## 👤 Author
Chiemelie Onu
AI / ML Engineer
- 🔗 **GitHub:** https://github.com/1234Godwin  
