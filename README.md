# BrainMRI: Deep Learning for Brain Tumor Detection 🧠📊

**BrainMRI** is a comprehensive deep learning-based solution for detecting brain tumors using MRI scans. This project implements pre-trained convolutional neural networks (CNNs) for binary (tumor vs. no tumor) and multi-class (glioma, meningioma, pituitary, and no tumor) classification tasks. The models used include **InceptionV3**, **ResNet-50**, **VGG-16**, **MobileNetV2**, and **DenseNet121**, optimized for accuracy and efficiency.

---

## 🌟 Key Features
- **Comprehensive Analysis**: Compares five pre-trained CNN models for brain tumor detection.
- **Binary & Multi-Class Classification**: Supports both tumor/no tumor and detailed tumor type classifications.
- **High Accuracy**:
  - Binary classification: Up to **99.42%** with DenseNet121.
  - Multi-class classification: Up to **93.78%** with MobileNetV2.
- **Efficient Preprocessing**: Applies grayscale conversion, contrast enhancement, resizing, and cropping for optimized input.

---

## 🚀 Technologies Used
- **Python**: For implementing deep learning models.
- **TensorFlow/Keras**: Deep learning framework for training and evaluation.
- **Matplotlib & Seaborn**: For data visualization and evaluation metrics.

---

## 📂 Dataset
- **Source**: [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).
- **Composition**: A total of **7,023 images** categorized into:
  - **Glioma**: 2,262 images
  - **Meningioma**: 1,708 images
  - **Pituitary**: 1,453 images
  - **No Tumor**: 1,600 images
- **Preprocessing Steps**:
  - Grayscale conversion and resizing to 224x224 pixels.
  - Contrast, brightness, and sharpening adjustments for clarity.
  - Focus cropping to isolate brain regions from non-important backgrounds.

---

## 🏗️ Model Architectures
### **1. InceptionV3**
- **Binary Accuracy**: 98.80%  
- **Multi-Class Accuracy**: 89.59%

### **2. ResNet-50**
- **Binary Accuracy**: 91.79%  
- **Multi-Class Accuracy**: 56.63%

### **3. VGG-16**
- **Binary Accuracy**: 99.02%  
- **Multi-Class Accuracy**: 90.76%

### **4. MobileNetV2**
- **Binary Accuracy**: 99.37%  
- **Multi-Class Accuracy**: 93.78%

### **5. DenseNet121**
- **Binary Accuracy**: 99.42%  
- **Multi-Class Accuracy**: 93.75%

---

## 📊 Model Performance Comparison
| Model        | Binary Accuracy | Multi-Class Accuracy | Training Loss (Binary) | Training Loss (Multi-Class) |
|--------------|-----------------|----------------------|------------------------|-----------------------------|
| **InceptionV3** | 98.80%        | 89.59%              | 3.46%                  | 27.54%                     |
| **ResNet-50**  | 91.79%        | 56.63%              | 22.4%                  | 92.9%                      |
| **VGG-16**     | 99.02%        | 90.76%              | 3.01%                  | 24.23%                     |
| **MobileNetV2**| 99.37%        | 93.78%              | 1.39%                  | 15.75%                     |
| **DenseNet121**| 99.42%        | 93.75%              | 1.92%                  | 17.20%                     |

---

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/abrarfahimsaraz/BrainMRI.git
   cd BrainMRI
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks for specific models:
   - `DenseNet121_all_trial_Simulated.ipynb`
   - `MobileNetV2_all_trial_Simulated.ipynb`
   - `MRI_InceptionV3_all_trial_case_simulated.ipynb`
   - `ResNet50_all_trial_simulated.ipynb`
   - `Vgg16_all_trial_simulated.ipynb`

---

## 📖 Usage
1. Open the desired Jupyter Notebook.
2. Execute the cells step-by-step to train and evaluate the model.
3. Modify the hyperparameters, datasets, or model architecture as needed for experimentation.

---

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
