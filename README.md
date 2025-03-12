# 🧠 Brain Tumor MRI Classification

## 📌 About the Project  
This project utilizes **Deep Learning** techniques to classify **brain tumor MRI images** into categories using a **Convolutional Neural Network (CNN)**. It processes MRI scans, trains a model to detect abnormalities, and evaluates its performance with a confusion matrix.

## 🚀 Features  
- **MRI Data Processing** – Load and preprocess MRI images.  
- **CNN Model for Tumor Classification** – A deep learning model trained to classify brain tumor images.  
- **Train and Test Pipeline** – Automatic model training and validation using PyTorch.  
- **Visualization Tools** – Display sample images, confusion matrix, and predictions.  
- **Model Saving & Loading** – Save and reuse trained models for predictions.  

### 🖼️ Sample MRI Classified Images

![Image](https://github.com/user-attachments/assets/6242799b-6a93-4cb2-a1f1-b3ba818fce17)
![Image](https://github.com/user-attachments/assets/61dbc0ca-6beb-4dbd-b6c2-bdc788e96559)
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
![Image](https://github.com/user-attachments/assets/0de3eee6-60ee-4ed6-b6e8-6ffe5853fd9b)
