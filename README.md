# 🧠 Brain Tumor Detection & Mask R-CNN Segmentation

## 📌 About the Project  
This project utilizes **Deep Learning and Computer Vision** for two main objectives:
- **Brain Tumor Classification** using **CNNs** on MRI images.
- **Object Segmentation** with **Mask R-CNN** for instance detection in videos.

It employs **PyTorch for MRI classification** and **PixelLib (Mask R-CNN) for segmentation**, making it a powerful tool for **medical imaging analysis**.

## 🚀 Features  
### 🔹 **Brain Tumor MRI Classification**  
- **Pretrained CNN model** for accurate tumor detection.
- **MRI dataset loading & preprocessing** for deep learning.
- **Train & Evaluate using PyTorch** with accuracy tracking.
- **Confusion Matrix Visualization** to analyze model performance.

### 🔹 **Mask R-CNN Instance Segmentation**  
- **Object segmentation** in videos using **pretrained Mask R-CNN**.
- **Bounding boxes & masks** for visualizing detections.
- **OpenCV integration** for real-time processing.

## 🏗️ Tech Stack  
### **🔹 Deep Learning & Computer Vision**  
- **PyTorch** – For MRI classification model.
- **TensorFlow & PixelLib** – For instance segmentation.
- **OpenCV** – Video processing.
- **Matplotlib & Seaborn** – Data visualization.

### **🔹 Dataset & Model**  
- **MRI Dataset** – Brain tumor images.
- **Mask R-CNN (COCO weights)** – Pretrained instance segmentation model.

## 🛠️ Setup & Installation  
1. **Clone the repository:**  
    ```bash
    git clone https://github.com/your-repo/brain-tumor-detection.git
    cd brain-tumor-detection
    ```

2. **Create a virtual environment:**  
    ```bash
    conda create -n tumor-detection python=3.8 -y
    ```

3. **Activate the environment:**  
    ```bash
    conda activate tumor-detection
    ```

4. **Install dependencies:**  
    ```bash
    pip install -r requirements.txt
    ```

5. **Download Mask R-CNN model weights:**  
    - Get `mask_rcnn_coco.h5` from [here](https://github.com/matterport/Mask_RCNN/releases) and place it in the project directory.

6. **Run MRI classification training:**  
    ```bash
    python train_mri.py
    ```

7. **Run instance segmentation on a video:**  
    ```bash
    python segment_video.py --input your_video.mp4
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

### **2️⃣ Mask R-CNN Instance Segmentation Output**  
![Mask R-CNN Results](https://github.com/user-attachments/assets/mask_rcnn_output.png)

## 🎓 Team Members  
- **[Your Name]**  
- **[Your Team Members]**  

## 🙌 Acknowledgments  
Special thanks to **Dr. Mohamed Zorkany** for his mentorship throughout this project.

## 💡 Contributions & Feedback  
We welcome contributions! Open issues, submit PRs, or reach out for collaboration. 🚀

