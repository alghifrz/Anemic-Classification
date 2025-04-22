# 🩸 Anemia Classification with Random Forest

This project uses traditional machine learning (Random Forest Classifier) to classify blood smear images into two categories: **Anemic** and **Non-Anemic**. The model is trained on image data that has been resized, flattened, and standardized.

---

## 📂 Dataset Structure

The dataset is organized into two directories:
dataset/ 
├── anemic/ # Contains images of anemic blood smears 
└── nonanemic/ # Contains images of non-anemic blood smears

Each folder contains labeled JPEG or PNG image files used as inputs for training the model.

---

## 📌 Features

- 📷 Image-based anemia classification
- 🔍 Data preprocessing: resizing, flattening, normalization
- 🌲 Random Forest Classifier for training
- 📊 Model evaluation using standard metrics
- 📈 Visualization of class distribution and sample outputs

---

## 🧠 Methodology

### 1. Preprocessing
- Images are resized to **64×64 pixels**
- Pixel data is flattened into a 1D array
- Features are normalized using `StandardScaler` from `sklearn`

### 2. Model Training
- Machine learning model used: `RandomForestClassifier` from `sklearn.ensemble`
- Dataset split into training and test sets using `train_test_split`

### 3. Evaluation
- Evaluated using accuracy, precision, recall, F1-score
- Visualization of confusion matrix for performance analysis

---

## 📊 Exploratory Data Analysis (EDA)

- Distribution of classes displayed with a pie chart
- Preview of random samples from each class using `matplotlib`
- Raw pixel value inspection with `OpenCV`

---

## 📈 Results

The model achieved promising performance in distinguishing anemic vs non-anemic images, even with a traditional ML approach:

- ✅ **Accuracy**
- ✅ **Precision**
- ✅ **Recall**
- ✅ **F1-score**
- ✅ **Confusion Matrix**

> Further enhancements may be achieved using deep learning techniques or larger datasets.

---

## 📦 Dependencies

To install all required packages, run:

```bash
pip install numpy opencv-python matplotlib scikit-learn Pillow scikit-image
or use:
pip install -r requirements.txt


