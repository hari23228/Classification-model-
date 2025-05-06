
<h1 align="center">🐾 Cat vs Dog Image Classification using SVR</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-007ACC?style=for-the-badge&logo=matplotlib&logoColor=white"/>
</p>

---

## 📌 Overview

🎯 This project showcases a full ML pipeline for classifying **cat and dog images** using **Support Vector Regression (SVR)**.

🔍 It covers:
- Image preprocessing with OpenCV
- Feature extraction (grayscale, resizing)
- Model training with SVR
- Evaluation using visual and quantitative metrics

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat) | Programming Language |
| ![OpenCV](https://img.shields.io/badge/OpenCV-27338e?logo=opencv&logoColor=white&style=flat) | Image Processing |
| ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white&style=flat) | ML Model (SVR) |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-007ACC?logo=matplotlib&logoColor=white&style=flat) | Visualization |
| ![Google Colab](https://img.shields.io/badge/Colab-F9AB00?logo=googlecolab&logoColor=white&style=flat) | Notebook Runtime |

---

## 📂 Dataset Structure

Images must be stored in this format:

Images/
├── cats/
│   ├── cat1.jpg
│   └── cat2.jpg
└── dogs/
    ├── dog1.jpg
    └── dog2.jpg




## 🚀 How to Run

1. **Mount Google Drive in Colab**
```python
from google.colab import drive
drive.mount('/content/drive')
```

2. **Set path to dataset**
```python
data_path = '/content/drive/MyDrive/Images/'
```

3. **Run all cells** in the notebook:
   - Preprocess images
   - Train SVR model
   - Evaluate performance

---

## 📊 Sample Output

📌 Outputs include:
- Performance metrics (e.g., MSE)
- Predicted vs actual visualization

---

## 📧 Contact

📬 Reach out at: [Hariai.td@gmail.com](mailto:Hariai.td@gmail.com)

---

<p align="center">
  <img src="https://media.giphy.com/media/3oriO0OEd9QIDdllqo/giphy.gif" width="150"/>
</p>
