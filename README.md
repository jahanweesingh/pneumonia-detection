# 🩺 Pneumonia Detection using Transfer Learning (CNN)

A deep learning-based system for detecting pneumonia from chest X-ray images using Convolutional Neural Networks (CNNs) and transfer learning.

The project compares multiple pretrained CNN architectures and evaluates feature extraction and fine-tuning strategies, with data augmentation and regularization techniques used to improve model generalization.

---

## 🚀 Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib

---

## 🧠 Models Evaluated

- VGG16
- ResNet50
- DenseNet121

---

## ⚙️ Methodology

- Transfer learning using pretrained CNN architectures
- Feature extraction and fine-tuning comparison
- Image preprocessing and normalization
- Data augmentation for improved generalization
- Batch normalization and dropout for regularization
- Model evaluation using accuracy, precision, recall, and F1-score

--- 

## 🏆 Final Model Performance
- **Validation Accuracy:** 96.5%  
- **Recall:** ~99%  
- High sensitivity for pneumonia detection  

---

## 📊 Model Comparison (Initial Results)
| Model        | Approach                     | Accuracy |
|-------------|-----------------------------|----------|
| VGG16       | Feature Extraction           | ~85%     |
| DenseNet121 | Fine-Tuning                 | ~85%     |
| ResNet50    | Fine-Tuning                 | ~63%     |

---

## 🔍 Key Insights
- Fine-tuning significantly improved performance over static feature extraction  
- Learning rate tuning reduced training instability  
- Data augmentation improved generalization  
- DenseNet121 showed strong robustness  

---

## 📁 Dataset
- Chest X-ray dataset (Kaggle Pneumonia Dataset)

---

## ▶️ How to Run
1. Install dependencies  
2. Load dataset  
3. Run notebook  

---

## 🎯 Objective
To build a reliable deep learning model for early detection of pneumonia from medical images.

---

## 📌 Future Improvements
- Deploy as a web application  
- Use EfficientNet / ensemble models  
- Add explainability (Grad-CAM)  

