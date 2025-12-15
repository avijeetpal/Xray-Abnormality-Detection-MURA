# X-ray Abnormality Detection on MURA Dataset

This project focuses on detecting musculoskeletal abnormalities from X-ray images using deep learning. The goal is to train and compare multiple models to classify normal vs abnormal bone conditions.

---
**College Mini Project** — completed as a team project with Avijeet Pal, Bhavya Singhal and Khushi Gupta.
## 📌 Project Overview

- Developed a **deep learning pipeline** for X-ray image classification.
- Trained and compared **three models**:
  - Simple CNN
  - MobileNetV2
  - MobileNetV3-Large
- Evaluated performance using accuracy, confusion matrix, and other metrics.

---

## 📂 Dataset

- **Dataset:** [MURA (Musculoskeletal Radiographs) Dataset](https://stanfordmlgroup.github.io/competitions/mura/) by Stanford ML Group  
- **Size:** ~40,000 X-ray images  
- **Note:** Dataset is **not included** in this repository due to size and licensing restrictions. Please download and place in a folder named `Datasets/`.

---

## 🛠️ Tools & Technologies Used

- **Programming:** Python 3.x  
- **Deep Learning Framework:** PyTorch  
- **Development Environment:** VSCode, Jupyter Notebook  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn  
- **Version Control:** Git & GitHub  

---
## 📊 Results

| Model            | Accuracy |
|------------------|----------|
| Simple CNN       | 78%      |
| MobileNetV2      | 84%      |
| MobileNetV3-L    | 88%      |

> Trained model weights are **not included**. You can train your own using the notebooks.

