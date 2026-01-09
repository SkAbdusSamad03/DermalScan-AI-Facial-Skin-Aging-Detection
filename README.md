📌 Project Overview
DermalScan leverages state-of-the-art convolutional neural networks to automatically assess facial skin aging. The project focuses on early detection and classification of aging indicators to support better skincare decisions and interventions.

Key Objectives:
Automated detection of facial skin aging signs
Classification into multiple aging categories
High accuracy with visual and interpretable results
Web-based accessibility for easy user interaction

🧠 Aging Signs Detected
Wrinkles
Dark spots
Puffy eyes
Overall skin clarity degradation

🛠️ Core Technology
Model: EfficientNetB0 (Pre-trained, fine-tuned using Transfer Learning)
Face Detection: Haar Cascade Classifier
Approach: Feature extraction + multi-class classification
Platform: Web-based application

📊 Dataset Overview
The accuracy of DermalScan is built on a high-quality, diverse, and well-annotated dataset.
Thousands of labeled facial images
Four distinct aging categories
Balanced and diverse data to reduce bias and improve generalisation

🔄 Methodology & Workflow
Image Upload – User uploads a facial image via the web app
Face Detection – Haar Cascade identifies facial region
Preprocessing & Augmentation – Image resizing, normalisation, transformations
Feature Extraction – EfficientNetB0 extracts aging-related features
Classification – Model predicts aging category
Result Visualisation – Output displayed with percentages & bounding boxes

🔍 Exploratory Data Analysis (EDA)
Class distribution analysis
Image quality inspection (lighting, resolution, clarity)
Sample visualisation from each category
Outlier and inconsistency detection
EDA helps in identifying potential biases and improving data quality before training.

📈 Visualisation
Dataset sample images
Training & validation accuracy/loss graphs
Confusion matrix
Augmented image examples to show data diversity

⚙️ Data Preprocessing & Feature Extraction
Image Resizing & Normalisation – Standard input dimensions and pixel scaling
Data Augmentation – Rotation, flipping, etc. for better generalisation
EfficientNetB0 Feature Learning – Automatic extraction of discriminative aging features

🧬 Model Architecture & Training
Pretrained EfficientNetB0 as base model
Transfer Learning for domain adaptation
Optimizer: Adam
Loss Function: Categorical Crossentropy
Training Strategy: Iterative training with validation to prevent overfitting

✅ Results
Prediction Accuracy: ~92%
Percentage-Based Output: Probability for each aging sign
Bounding Box Visualisation: Highlights affected facial regions

🖥️ User Interface
DermalScan features a clean and intuitive web-based interface that allows:
Easy image upload
Quick processing
Clear result visualisation with highlighted aging areas

📁 Repository Structure (Suggested)
DermalScan/
│
├── DermalScan-AI-Facial-Skin-Aging-Detection.pptx
├── README.md
├── dataset/
├── models/
├── notebooks/
├── app/
└── requirements.txt

👤 Author
Sk Abdus Samad
Engineering Undergraduate | AI & Deep Learning Enthusiast
