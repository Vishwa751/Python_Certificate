Dataset

The dataset is too large to store in this repository.

Download the PlantVillage dataset from Kaggle:

https://www.kaggle.com/datasets/mohitsingh1804/plantvillage?utm_source=chatgpt.com
````markdown
# 🌿 Plant Disease Detection Using Machine Learning (Python)

> A Machine Learning project that detects potato leaf diseases using image classification. The system compares **Logistic Regression** and **Support Vector Machine (SVM)** models to identify the best-performing classifier and provides disease treatment recommendations.

---

# 📖 Overview

Plant diseases are one of the major reasons for reduced agricultural productivity. Detecting diseases at an early stage helps farmers protect crops and improve yield.

This project uses **traditional Machine Learning algorithms** to classify potato leaf images into different disease categories. Images are preprocessed using OpenCV, converted into numerical feature vectors, and classified using Logistic Regression and SVM. The trained model can also predict diseases from user-uploaded images.

---

# ✨ Features

- 📷 Detect potato leaf diseases from images
- 🤖 Train Logistic Regression and SVM models
- 📊 Compare model performance
- 📈 Generate confusion matrix and classification report
- 🌱 Predict disease from a custom image
- 💡 Display treatment recommendations
- 📉 Visualize model accuracy with graphs

---

# 🎯 Objectives

- Detect potato leaf diseases using Machine Learning.
- Compare Logistic Regression and SVM performance.
- Classify leaf images into disease categories.
- Predict disease from uploaded images.
- Provide treatment suggestions based on predictions.

---

# 🦠 Disease Classes

The dataset contains three classes:

- Potato___Early_blight
- Potato___Late_blight
- Potato___Healthy

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Google Colab | Development Environment |
| OpenCV | Image Processing |
| NumPy | Numerical Computing |
| Pandas | Data Handling |
| Matplotlib | Data Visualization |
| Scikit-learn | Machine Learning |
| ZipFile | Dataset Extraction |

---

# 📂 Project Structure

```
Plant_Disease_Detection/
│
├── dataset/
│   ├── train/
│   │   ├── Potato___Early_blight/
│   │   ├── Potato___Late_blight/
│   │   └── Potato___Healthy/
│   │
│   └── val/
│       ├── Potato___Early_blight/
│       ├── Potato___Late_blight/
│       └── Potato___Healthy/
│
├── Plant_Disease_Detection.ipynb
├── README.md
└── requirements.txt
```

---

# ⚙️ Workflow

## 1. Dataset Preparation

- Extract dataset
- Verify folder structure
- Count images in each class

---

## 2. Data Visualization

- Display sample images
- Explore disease classes

---

## 3. Image Preprocessing

- Read images using OpenCV
- Resize images to **64 × 64**
- Convert images to NumPy arrays
- Flatten image pixels
- Normalize pixel values
- Encode labels using LabelEncoder

---

## 4. Model Training

### Logistic Regression

- Max Iterations: **1000**
- Baseline classifier

### Support Vector Machine (SVM)

- Kernel: **Linear**
- Trained using normalized image vectors

---

## 5. Model Evaluation

Performance is evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

---

## 6. Custom Image Prediction

The user can upload a potato leaf image.

The system will:

- Load the image
- Resize it to **64 × 64**
- Normalize pixel values
- Predict the disease
- Display treatment advice

---

# 🌱 Disease Treatment Recommendations

## 🍂 Early Blight

**Recommendation**

- Remove infected leaves.
- Apply recommended fungicide.
- Avoid overhead irrigation.
- Practice crop rotation.

---

## 🍁 Late Blight

**Recommendation**

- Remove infected plants immediately.
- Spray fungicide.
- Improve field drainage.
- Reduce excess moisture.

---

## 🌿 Healthy Leaf

**Recommendation**

- No disease detected.
- Continue regular monitoring.
- Maintain proper irrigation and nutrient management.

---

# 📊 Machine Learning Models

## Logistic Regression

### Advantages

- Fast training
- Simple implementation
- Low computational cost
- Good baseline model

---

## Support Vector Machine (SVM)

### Advantages

- High classification accuracy
- Works well with high-dimensional data
- Strong generalization performance
- Effective for image classification

---

# 📈 Model Comparison

| Model | Purpose |
|--------|----------|
| Logistic Regression | Baseline Machine Learning Model |
| Support Vector Machine | High Accuracy Image Classifier |

The model with the highest validation accuracy is selected as the final prediction model.

---

# 📷 Input Format

Supported image formats:

- JPG
- JPEG
- PNG

Example inputs:

- Healthy Leaf
- Early Blight Leaf
- Late Blight Leaf

---

# 📤 Sample Output

```
Predicted Disease

Potato___Late_blight

Treatment Recommendation

• Remove infected plants immediately.
• Spray appropriate fungicide.
• Avoid excess moisture.
```

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Plant-Disease-Detection.git
```

Move into the project directory:

```bash
cd Plant-Disease-Detection
```

Install required libraries:

```bash
pip install numpy pandas matplotlib opencv-python scikit-learn
```

Or install using requirements.txt

```bash
pip install -r requirements.txt
```

---

# ▶️ How to Run

1. Open Google Colab or Jupyter Notebook.
2. Upload the dataset.
3. Run all notebook cells.
4. Train the Logistic Regression and SVM models.
5. Upload a potato leaf image.
6. View the predicted disease.
7. Read the treatment recommendation.
8. Compare model performance.

---

# 📊 Performance Metrics

The notebook automatically generates:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix
- Accuracy Comparison Graph

---

# 📌 Required Libraries

```text
numpy
pandas
matplotlib
opencv-python
scikit-learn
```

---

# 🚀 Future Improvements

- Support additional crops (Tomato, Corn, Apple, Grapes)
- Deep Learning using CNN, ResNet, EfficientNet
- Flask/Django Web Application
- Android Mobile Application
- Real-time camera detection
- Cloud Deployment
- Multi-language support
- Fertilizer and pesticide recommendations

---

# 👨‍💻 Author

**Abhishek V. Badiger**

**Project:** Plant Disease Detection Using Machine Learning

**Algorithms**

- Logistic Regression
- Support Vector Machine (SVM)

**Language:** Python

**Environment:** Google Colab

---

# 📜 License

This project is developed for **educational and research purposes**.

You are free to use, modify, and extend the project with proper acknowledgment.

---

# ⭐ Conclusion

This project demonstrates the application of **Machine Learning** in agricultural disease detection. By preprocessing potato leaf images and training **Logistic Regression** and **Support Vector Machine (SVM)** models, the system accurately classifies plant diseases and recommends suitable treatments. The project provides a practical introduction to image classification using traditional machine learning and can be further enhanced with deep learning, web deployment, and mobile applications for real-world agricultural use.

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub!
````

