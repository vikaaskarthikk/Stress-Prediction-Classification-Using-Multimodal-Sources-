# 🚀 Stress Prediction & Classification Using Multimodal Sources  
###  | Machine Learning | Deep Learning | Multimodal Physiology

This project predicts and classifies human stress levels using **multimodal physiological data** such as:

- 🔵 Electrodermal Activity (EDA)  
- ❤️ Heart Rate Variability (HRV)  
- 🔗 Fused EDA + HRV features  

A **hybrid LSTM + CNN deep learning model** achieves **97%+ accuracy** in detecting:

- ✔ No Stress  
- ✔ Interruption  
- ✔ Time Pressure  

---

## 📌 Project Description

This BE major project implements a **multimodal stress detection system** using raw physiological signals collected from wearable sensors.  
Traditional stress prediction relies on subjective questionnaires, but this system uses **objective physiological markers**, preprocessed and learned through **deep neural networks**.

Core components include:

- ANN models for **EDA** and **HRV**  
- Multimodal **feature fusion**  
- Hybrid **LSTM + CNN** model  
- Confusion matrix, accuracy, loss curves  
- System testing & evaluation  

The project uses real datasets from **SWELL** and **WESAD**, and achieves **~98% accuracy**, outperforming existing machine learning approaches.

---

## 📂 Dataset Used

### 🟦 SWELL Dataset  
Contains physiological signals from 25 participants performing knowledge-work tasks under:
- Neutral condition  
- Time pressure  
- Email interruptions  

Sensors used:
- ECG → HRV  
- EDA → Skin conductance  

### 🟧 WESAD Dataset  
Standard wearable-based stress detection dataset.

---

## 🧠 Project Workflow

```mermaid
flowchart TD
    A[Collect EDA & HRV Signals] --> B[Data Cleaning & Scaling]
    B --> C[Feature Extraction]
    C --> D[Train ANN (EDA)]
    C --> E[Train ANN (HRV)]
    D --> F[Fuse Extracted Features]
    E --> F
    F --> G[Train Hybrid LSTM-CNN Model]
    G --> H[Predict Stress Level]

### 🔧 Programming Language
- Python 3.x

### 📚 Machine Learning & Deep Learning Libraries
- TensorFlow
- Keras
- Scikit-learn
- NumPy
- Pandas

### 📊 Visualization Libraries
- Matplotlib
- Seaborn

### 🧪 Development & Execution
- Jupyter Notebook
- Google Colab

### 🖥️ Tools / Platforms
- GitHub (Version Control)
- Wearable Sensor Data (EDA, HRV)
