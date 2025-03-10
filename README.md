# ResNet50V2 Fine-Tuning for Animals-10

## 📌 Project Overview
This project explores **image classification** on the **Animals-10 dataset** using a **fine-tuned ResNet50V2** model. The goal is to compare a **baseline CNN** with **transfer learning** to enhance accuracy.

## 📂 Dataset & Preprocessing
- Animals-10 dataset with **10 animal classes**.
- **80% training, 20% validation** split.
- **Normalized & resized** images to **224x224 pixels**.
- Class names translated from **Italian to English**.

## 🎯 Model Development
### 🔹 Baseline CNN Model
- A simple CNN was trained but showed **suboptimal accuracy**.

### 🔹 Transfer Learning with ResNet50V2
- Used **pretrained ResNet50V2** from ImageNet.
- Replaced the classifier with a **custom fully connected layer**.
- **Froze initial layers**, trained new layers, then **fine-tuned deeper layers**.

### 🔹 Key Challenges
- **Higher validation accuracy** than training, indicating potential **data leakage**.
- Resolved by **refining augmentation and ensuring proper data splits**.

## 📊 Results & Evaluation
- **ResNet50V2 achieved 98.95% training accuracy** and **96.91% validation accuracy**.
- **Final evaluation metrics:**
  - **Test Accuracy:** 97.08%
  - **Test Loss:** 0.1255
  - **Validation Loss:** 0.1354
  - **Precision:** 97.22%
  - **Recall:** 96.71%
- Metrics: **Accuracy, Precision, Recall, F1-score, Confusion Matrix**.



## 📎 References
- [Animals-10 Dataset](https://www.kaggle.com/datasets)
- [ResNet50V2 Paper](https://arxiv.org/pdf/1603.05027.pdf)
- [Google Drive (Streamlit App & Transfer Learning Model)](https://drive.google.com/drive/folders/1dZ38ZjVkVjz5UbF1HMFOcl90fwzTT2Ou?usp=drive_link)



---
Made with ❤️ by **TriNet Vision Team**:  
1️⃣ Rawan Alnajim  
2️⃣ Nora Alshahrani  🚀
3️⃣ Albandari Altalhi 







