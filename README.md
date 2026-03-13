# Traffic Sign Recognition with CNN and Explainable AI

This project implements a **Traffic Sign Recognition system using Convolutional Neural Networks (CNNs)** with **Explainable AI techniques (SHAP and LIME)** to interpret model predictions.

The model classifies traffic signs from images and highlights the important regions influencing the decision.

---

## Features

- CNN-based traffic sign classification
- Transfer learning using **MobileNetV2**
- Image preprocessing and augmentation
- Model evaluation using classification metrics
- Explainability using **SHAP and LIME**

---

## Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- SHAP
- LIME
- Matplotlib

---

## Dataset

This project uses the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset.

Download the dataset from:

https://benchmark.ini.rub.de/gtsrb_news.html

After downloading, place the dataset inside the project folder as:

```
dataset/
   Online-Test-sort/
```

---

## Project Structure

```
Traffic-Sign-Recognition-CNN-Explainable-AI
│
├── Traffic_Sign_Recognition.ipynb
├── README.md
├── requirements.txt
└── dataset/
```

---

## Installation

Install required libraries using:

```
pip install -r requirements.txt
```

---

## Running the Project

Open and run the notebook:

```
jupyter notebook Traffic_Sign_Recognition.ipynb
```

---

## Explainable AI

The project uses **SHAP and LIME** to explain model predictions.

These methods highlight the **important image regions responsible for classification**, helping verify that the CNN focuses on meaningful traffic sign features.

---

## Future Improvements

- Real-time traffic sign detection
- Deploy model on edge devices (Jetson Nano)
- Expand dataset with more traffic sign categories

---

## Author

Aditi Gaikwad
