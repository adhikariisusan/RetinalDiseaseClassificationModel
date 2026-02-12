# Retinal Disease Classification using Deep Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)

This repository contains a Deep Learning model designed to classify retinal diseases from Optical Coherence Tomography (OCT) images. The project utilizes Convolutional Neural Networks (CNN) to assist in the diagnosis of common retinal pathologies.

## 📌 Overview

Early detection of retinal diseases is critical for preventing permanent vision loss. This project focuses on classifying OCT scans into four distinct categories:

* **CNV (Choroidal Neovascularization):** Abnormal blood vessel growth.
* **DME (Diabetic Macular Edema):** Fluid buildup in the retina.
* **DRUSEN:** Early signs of age-related macular degeneration.
* **NORMAL:** Healthy retinal scans.

## 📂 Project Structure

* `the_real_6th_proj.ipynb`: The main Jupyter Notebook containing the data pipeline, model architecture, training, and evaluation.
* `data/`: (Expected) Folder containing training, validation, and test datasets.

## 🚀 Key Features

* **Custom CNN Architecture:** Built using TensorFlow and Keras.
* **Data Augmentation:** Increases model robustness by applying random transformations to training images.
* **Performance Visualization:** Includes code to generate Accuracy/Loss graphs and Confusion Matrices.
* **Pre-processing Pipeline:** Handles image resizing and normalization for optimal model performance.

## 🛠️ Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/adhikariisusan/RetinalDiseaseClassificationModel.git](https://github.com/adhikariisusan/RetinalDiseaseClassificationModel.git)
    cd RetinalDiseaseClassificationModel
    ```

2.  **Install Dependencies:**
    Make sure you have Python installed, then run:
    ```bash
    pip install tensorflow numpy matplotlib pandas scikit-learn opencv-python
    ```

3.  **Dataset:**
    The project is designed to work with the [Kaggle OCT2017 Dataset](https://www.kaggle.com/datasets/paultimothymooney/kermany2018). Download and extract the data into your project directory.

## 📊 Results

The model evaluates performance using:
* **Training & Validation Accuracy:** To monitor learning progress.
* **Confusion Matrix:** To identify which classes are being confused by the model.
* **Classification Report:** Providing precision, recall, and F1-score for each category.

## 🛠 Future Improvements

* Implement **Transfer Learning** using ResNet or InceptionV3 for higher accuracy.
* Develop a **Streamlit Web App** for real-time image classification.
* Integrate **Grad-CAM** to provide heatmaps showing where the model is looking to make its prediction.

## 🤝 Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome!

---
**Author:** [Susan Adhikari](https://github.com/adhikariisusan)
