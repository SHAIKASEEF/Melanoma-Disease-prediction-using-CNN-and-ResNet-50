
# Melanoma Disease Detection Using CNN & Transfer Learning (ResNet-50)

## 🧠 Project Overview

Melanoma is one of the deadliest types of skin cancer, originating in pigment-producing melanocytes. Early detection is critical to prevent metastasis and ensure timely treatment. This project introduces an AI-powered solution that leverages deep learning and transfer learning to automate melanoma detection from dermoscopic images.

A web-based interface enables fast, non-invasive predictions, supporting dermatologists with quick and accurate diagnostic decisions.

----------

## 📊 Dataset

The model is trained on the **HAM10000** and **ISIC** skin lesion datasets, containing thousands of high-quality dermoscopic images. The data is augmented through rotation, flipping, normalization, and other preprocessing techniques to improve model generalization.

----------

## 🎯 Objectives

-   Automatically classify skin lesions as benign or melanoma.
    
-   Utilize transfer learning with ResNet-50 for efficient and accurate feature extraction.
    
-   Provide real-time diagnosis through a user-friendly web platform.
    
-   Reduce misclassification and inter-observer variability in manual diagnoses.
    

----------

## 🔍 Methodology

### 1. **Preprocessing**

-   Image resizing and normalization
    
-   Data augmentation (rotation, flipping)
    
-   Dataset splitting (train/test)
    

### 2. **Model Architecture**

-   **ResNet-50** (pre-trained on ImageNet)
    
-   Fine-tuned final layers for binary classification
    
-   Implemented using **TensorFlow** and **Keras**
    

### 3. **Web Interface**

-   Built using **Flask**
    
-   Allows users to upload dermoscopic images
    
-   Displays model predictions and confidence scores
    

----------

## 🧪 Models and Techniques Used

-   **Convolutional Neural Network (CNN)**
    
-   **Transfer Learning** using ResNet-50
    
-   **Data Augmentation**
    
-   **Flask Web Framework**
    

----------

## 📈 Evaluation Metrics

The model achieved the following metrics on the test dataset:

-   **Accuracy:** ~89%
    
-   **Precision:** >80%
    
-   **Recall:** >80%
    
-   **F1-Score:** Competitive with state-of-the-art solutions
    

----------

## 💡 Results & Discussion

-   The ResNet-50-based model performed robustly across melanoma stages.
    
-   Successfully distinguished malignant vs benign lesions with high confidence.
    
-   Generalized well despite the small medical image dataset, thanks to transfer learning and augmentation.
    
-   Integrated into a real-time prediction platform with a simple UI for clinicians.
    

----------

## 🔧 Future Enhancements

-   **Upgrade Models:** Explore EfficientNetV2, DenseNet, or Vision Transformers.
    
-   **Ensemble Learning:** Combine multiple models to reduce false positives/negatives.
    
-   **Explainable AI (XAI):** Add Grad-CAM, SHAP, or LIME for interpretability.
    
-   **Data Expansion:** Include more diverse datasets and synthetic image generation using GANs.
    



## 📚 References

1.  Jainesh Rathod et al., _Diagnosis of Skin Diseases Using CNNs_, ICECA 2018.
    
2.  Zhe Wu et al., _Studies on CNN Algorithms for Skin Disease Classification_, IEEE Access, 2019.
    
3.  Nurul Akmalia et al., _Skin Disease Classification Using LBP and CNN_, ELTICOM 2019.
