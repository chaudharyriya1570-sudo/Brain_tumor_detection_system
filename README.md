# 🧠 Brain Tumor Detection System

An AI-powered **Brain Tumor Detection System** that uses deep learning and medical image analysis to identify brain tumors from MRI scans.

The project provides a simple interface where users can upload an MRI image and receive a model-based prediction. It was developed as a machine learning/computer vision project to explore the application of deep learning in medical image classification.

> ⚠️ **Disclaimer:** This project is intended for educational and research purposes only. It is **not a medical device** and should not be used as a substitute for professional medical diagnosis or treatment.

---

## 📌 Overview

Brain tumor detection from MRI scans is an important application of computer vision and deep learning.

This project aims to automate the analysis of MRI images using a trained deep learning model. The system takes an MRI scan as input, processes the image, and predicts the corresponding tumor category.

### ✨ Key Features

- 🧠 Brain MRI image classification
- 📤 Upload MRI images for prediction
- 🤖 Deep learning-based classification
- 🖼️ Image preprocessing and normalization
- 📊 Model prediction and classification
- 🌐 User-friendly web interface
- ⚡ Fast prediction after image upload
- 🔬 Designed for educational and research purposes

---

## 🛠️ Tech Stack

### Machine Learning / AI

- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Scikit-learn

### Frontend / Web

- HTML
- CSS
- JavaScript
- Flask *(if used in the application)*

### Development Tools

- Jupyter Notebook / Google Colab
- VS Code
- Git & GitHub

---

## 🧠 How It Works

The overall workflow of the system is:

```text
                ┌─────────────────┐
                │   MRI Image     │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Image Upload    │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Preprocessing   │
                │ Resize / Scale  │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Deep Learning   │
                │     Model       │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │   Prediction    │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Display Result  │
                └─────────────────┘
```

### Workflow

1. The user uploads a brain MRI image.
2. The image is received by the application.
3. The image is resized and preprocessed according to the model's input requirements.
4. The processed image is passed to the trained deep learning model.
5. The model generates a prediction.
6. The predicted result is displayed to the user.

---

## 📂 Project Structure

```text
Brain_tumor_detection_system/
│
├── 📁 dataset/
│
├── 📁 static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── 📁 templates/
│   ├── index.html
│   └── ...
│
├── 📓 brain_tumor_detection.ipynb
│
├── 🐍 app.py
├── 📄 requirements.txt
├── 📄 README.md
└── 📄 .gitignore
```

> The structure above can be updated to exactly match the folders and files currently present in the repository.

---

## 📊 Dataset

The model is trained using a brain MRI image dataset containing different categories of brain conditions.

The dataset is used for:

- Training the deep learning model
- Validation during training
- Testing model performance
- Evaluating classification results

Images are preprocessed before being passed to the model to ensure consistency in size and pixel representation.

---

## 🔬 Model Development

The project follows a standard deep learning workflow:

```text
Dataset
   ↓
Data Preprocessing
   ↓
Train / Validation / Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Prediction
```

The model learns visual patterns present in MRI scans and uses those learned features to classify previously unseen images.

---

## 📈 Model Evaluation

The trained model can be evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics help evaluate how effectively the model distinguishes between the different MRI image classes.

---

## 💻 Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/chaudharyriya1570-sudo/Brain_tumor_detection_system.git
```

### 2. Navigate to the project

```bash
cd Brain_tumor_detection_system
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

### 7. Open the application

Visit:

```text
http://127.0.0.1:5000
```

---

## 🖥️ Application

The application allows users to:

```text
Upload MRI
     ↓
Process Image
     ↓
Run Prediction
     ↓
View Result
```

Screenshots of the application can be added here:

### 🏠 Home Page

*Add screenshot here*

### 📤 MRI Upload

*Add screenshot here*

### 🔍 Prediction Result

*Add screenshot here*

---

## 🚀 Future Improvements

Some possible improvements for future versions include:

- [ ] Deploy the application online
- [ ] Improve model accuracy
- [ ] Add Grad-CAM visualizations
- [ ] Add confidence scores
- [ ] Add detailed prediction reports
- [ ] Add user authentication
- [ ] Add prediction history
- [ ] Support additional MRI image formats
- [ ] Improve UI/UX
- [ ] Add model comparison
- [ ] Containerize the application using Docker

---

## 🌐 Deployment

🚧 **Deployment: Coming Soon**

The project is currently available as a local application and has **not yet been deployed**.

A live demo will be added here once the application is deployed.

```text
Live Demo: Coming Soon 🚧
```

---

## ⚠️ Medical Disclaimer

This project is created for **educational and research purposes**.

The predictions generated by this system should not be considered a medical diagnosis. Medical imaging should always be reviewed by qualified healthcare professionals, and clinical decisions should not be made solely on the basis of this application.

---

## 👩‍💻 Author

**Riya Chaudhary**

GitHub:
[https://github.com/chaudharyriya1570-sudo](https://github.com/chaudharyriya1570-sudo)

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is intended for educational and research purposes.
