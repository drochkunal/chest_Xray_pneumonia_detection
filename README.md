🩺 Chest X-Ray Classification using CNN
📌 Project Overview

This project focuses on building a Convolutional Neural Network (CNN) to classify chest X-ray images into different categories (e.g., Normal vs Pneumonia). The goal is to leverage deep learning techniques to assist in medical image analysis and automate disease detection.

The model learns visual patterns from X-ray images and predicts the presence of abnormalities, helping demonstrate how AI can support healthcare diagnostics.

📊 Dataset Description

The dataset consists of chest X-ray images categorized into:

Normal – Healthy lungs
Pneumonia – Infected lungs

The images are pre-labeled and organized into training, validation, and testing sets.

⚙️ Project Workflow
1. Data Preprocessing
Image resizing and normalization
Train-validation-test split
Data augmentation (rotation, flipping, scaling)
2. Model Building
Implemented a CNN architecture with:
Convolutional layers
MaxPooling layers
Fully connected (Dense) layers
Activation functions (ReLU, Softmax/Sigmoid)
3. Model Training
Trained model on training dataset
Used validation set to monitor performance
Optimized using loss functions and optimizers
4. Model Evaluation
Evaluated using:
Accuracy
Loss
Compared training vs validation performance
🚀 Results
Model successfully learned patterns in X-ray images
Achieved good classification accuracy
Performance improved with data augmentation and tuning
🛠️ Tech Stack
Python 🐍
TensorFlow / Keras
NumPy
Matplotlib
Jupyter Notebook
📂 Project Structure
├── ChestXray_CNN.ipynb
├── dataset/
│   ├── train/
│   ├── test/
│   └── validation/
└── README.md
▶️ How to Run
pip install tensorflow numpy matplotlib

Open the notebook:

jupyter notebook ChestXray_CNN.ipynb

Run all cells step-by-step.

📈 Key Learnings
Understanding CNN architecture for image classification
Importance of data preprocessing in deep learning
Role of data augmentation in improving model performance
Model evaluation and overfitting handling
🔗 Future Improvements
Use pre-trained models (ResNet, VGG16)
Improve accuracy with hyperparameter tuning
Deploy as a web app
Add more medical classes for classification
👤 Author

Kunal Droch

📌 About

Deep learning project using CNN to classify chest X-ray images for detecting pneumonia and understanding medical image analysis.
