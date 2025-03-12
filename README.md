# 🧠 Brain Tumor MRI Classification

## 📌 About the Project  
This project utilizes **Deep Learning** techniques to classify **brain tumor MRI images** into categories using a **Convolutional Neural Network (CNN)**. It processes MRI scans, trains a model to detect abnormalities, and evaluates its performance with a confusion matrix.

## 🚀 Features  
- **MRI Data Processing** – Load and preprocess MRI images.  
- **CNN Model for Tumor Classification** – A deep learning model trained to classify brain tumor images.  
- **Train and Test Pipeline** – Automatic model training and validation using PyTorch.  
- **Visualization Tools** – Display sample images, confusion matrix, and predictions.  
- **Model Saving & Loading** – Save and reuse trained models for predictions.  

### 🖼️ Sample MRI Images

![Sample MRI Images](https://github.com/user-attachments/assets/your-image-link)

## 🏗️ Tech Stack  
### 🔹 **Deep Learning Framework**  
- **PyTorch** – For training and testing the CNN model.  

### 🔹 **Data Processing & Visualization**  
- **Torchvision & PIL** – Image transformation and augmentation.  
- **Matplotlib & Seaborn** – Data visualization, including confusion matrices.
- 

## 🛠️ Setup & Installation  
1. Clone the repository:  
    ```bash
    git clone https://github.com/your-repo/brain-tumor-classification.git
    cd brain-tumor-classification
    ```
2. Create and activate a virtual environment:  
    ```bash
    conda create -n brain_tumor python=3.11 -y
    conda activate brain_tumor
    ```
3. Install dependencies:  
    ```bash
    pip install -r requirements.txt
    ```
4. Run the training script:  
    ```bash
    python train.py
    ```
5. Run the evaluation script:  
    ```bash
    python evaluate.py
    ```
## 📊 Results & Visualizations  
### **1️⃣ MRI Brain Tumor Classification Results**  
| Metric | Value |
|--------|-------|
| Accuracy | **95.6%** |
| Precision | **94.3%** |
| Recall | **96.1%** |

📌 **Confusion Matrix:**  
![Confusion Matrix](https://github.com/user-attachments/assets/confusion_matrix.png)
