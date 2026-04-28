# 🩺 Chest X-Ray Classification using ResNet
📌 Project Overview

This project focuses on building a deep learning model to classify chest X-ray images using a pre-trained ResNet architecture. The objective is to detect pneumonia from X-ray images by leveraging transfer learning and convolutional neural networks.

By using ResNet, the model benefits from deep feature extraction capabilities and improved performance compared to basic CNN architectures.

📊 Dataset Description

The dataset consists of labeled chest X-ray images divided into:

Normal – Healthy lungs
Pneumonia – Infected lungs

The data is organized into training, validation, and testing sets to ensure proper evaluation.

⚙️ Project Workflow
1. Data Preprocessing
Image resizing and normalization
Data augmentation (rotation, flipping, zoom)
Splitting into train, validation, and test sets
2. Model Building (Transfer Learning)
Used ResNet (pre-trained on ImageNet)
Frozen initial layers for feature extraction
Added custom layers:
Fully connected (Dense) layers
Dropout for regularization
Output layer with Sigmoid activation
3. Model Training
Fine-tuned the network on X-ray dataset
Used appropriate loss function (Binary Crossentropy)
Optimized using Adam optimizer
4. Model Evaluation
Evaluated performance using:
Accuracy
Loss curves
Compared training vs validation metrics to detect overfitting
🚀 Results
ResNet significantly improved classification performance
Better generalization compared to basic CNN
Data augmentation helped reduce overfitting
🛠️ Tech Stack
Python 🐍
TensorFlow / Keras
ResNet (Transfer Learning)
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
jupyter notebook ChestXray_CNN.ipynb

Run all cells step-by-step.

📈 Key Learnings
Transfer learning improves performance significantly
Deep architectures like ResNet capture complex patterns
Data augmentation helps improve generalization
Importance of fine-tuning pre-trained models
🔗 Future Improvements
Use advanced architectures (EfficientNet, DenseNet)
Hyperparameter tuning for better accuracy
Deploy model using Streamlit or Flask
Expand dataset for multi-class classification
👤 Author

Kunal Droch

📌 About

Deep learning project using ResNet-based transfer learning to classify chest X-ray images and detect pneumonia with improved accuracy.
