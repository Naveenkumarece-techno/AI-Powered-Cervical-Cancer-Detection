# AI-Powered-Cervical-Cancer-Detection
AI-powered cervical cancer detection system using U-Net segmentation and YOLOv8 classification for automated Pap smear image analysis. The project applies preprocessing, ROI extraction, and Lion optimization to improve accuracy, reduce manual diagnostic effort, and support early-stage cervical cancer screening using deep learning techniques.
AI-Powered Cervical Cancer Detection using U-Net and YOLOv8

An advanced deep learning-based cervical cancer detection system using Pap smear images for accurate and early-stage cancer diagnosis. This project combines medical image processing, deep learning segmentation, and real-time classification techniques to automate cervical cancer screening and reduce manual diagnostic effort. The proposed system integrates preprocessing methods, U-Net segmentation, YOLOv8-n classification, and Lion optimization to improve feature extraction, segmentation accuracy, model convergence, and prediction performance. The model was trained and evaluated using the Herlev Pap Smear Dataset and achieved high accuracy in detecting cancerous and non-cancerous cervical cells.

Features
Pap Smear Image Preprocessing

Preprocessing techniques are applied to improve image quality and enhance important cellular features before segmentation and classification. The preprocessing pipeline includes grayscale conversion, normalization, resizing, smoothing, edge enhancement, and noise reduction.

CLAHE-based Contrast Enhancement

Contrast Limited Adaptive Histogram Equalization (CLAHE) is used to improve local image contrast and highlight nucleus boundaries more clearly. This improves segmentation quality and helps the model detect abnormal cell structures effectively.

U-Net Nucleus Segmentation

The U-Net deep learning architecture is used for precise nucleus segmentation and Region of Interest (ROI) extraction from Pap smear images. This step isolates important cellular regions and removes unnecessary background noise for better classification performance.

YOLOv8-n Cell Classification

YOLOv8-n is used as a lightweight and efficient deep learning classification model for identifying cancerous and non-cancerous cervical cells. The model provides fast and accurate predictions suitable for real-time medical screening applications.

Lion Optimizer Integration

The Lion optimizer is integrated into the training pipeline to improve learning efficiency, reduce overfitting, stabilize gradient updates, and achieve faster model convergence compared to traditional optimization algorithms.

Cancerous vs Non-Cancerous Detection

The proposed system classifies Pap smear images into cancerous and non-cancerous categories based on segmented nucleus features. The system can identify abnormal cervical cell patterns associated with dysplastic and carcinoma stages.

Confusion Matrix and Performance Analysis

Model performance is evaluated using confusion matrix analysis, accuracy, precision, recall, F1-score, and validation metrics. The results demonstrate strong classification capability and reliable medical image prediction performance.

Deep Learning-based Automated Screening

The entire workflow is automated using artificial intelligence and deep learning techniques, reducing dependence on manual microscopic analysis and improving screening speed and consistency.

Technologies Used
Python
TensorFlow / Keras
PyTorch
YOLOv8
OpenCV
NumPy
Matplotlib
Scikit-learn
Google Colab
Dataset
Herlev Pap Smear Dataset

The project uses the Herlev Pap Smear Dataset containing multiple classes of normal and abnormal cervical cells including:

Normal Columnar
Normal Intermediate
Normal Superficial
Light Dysplastic
Moderate Dysplastic
Severe Dysplastic
Carcinoma in Situ

The dataset is divided into training, validation, and testing sets for deep learning model development and evaluation.

Performance
Metric	Score
Accuracy	97.5%
Precision	95.8%
Recall	96.5%
F1-Score	96.1%

The proposed model achieved high classification accuracy and demonstrated strong capability in detecting cervical cancer from Pap smear images.

Workflow
Pap Smear Image Collection
Image Preprocessing
CLAHE Contrast Enhancement
U-Net Segmentation
Region of Interest (ROI) Extraction
YOLOv8-n Classification
Lion Optimization
Cancer Prediction
Performance Evaluation
Applications
Early Cervical Cancer Detection
AI-assisted Medical Diagnosis
Automated Pap Smear Screening
Medical Image Analysis
Healthcare AI Research
Clinical Decision Support Systems
Future Enhancements
Integration with Vision Transformers (ViT)
Explainable AI using Grad-CAM
Real-time Web and Mobile Deployment
Cloud-based Medical Screening Platform
Clinical Validation using Larger Datasets
Multi-class Cervical Cancer Stage Prediction
Hybrid Deep Learning Architectures
