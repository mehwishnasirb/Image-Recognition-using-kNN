# 🧠 Machine Learning — Image Recognition using kNN

This project is a case study for applying the **k-Nearest Neighbors (kNN)** algorithm on the **MNIST handwritten digit dataset**. It is submitted as part of the Machine Learning course at the **University of Management & Technology**.

---

## 📌 Problem Statement

To recognize handwritten digits from the MNIST dataset using the **k-Nearest Neighbors (kNN)** algorithm and evaluate how different values of `k` impact the model’s accuracy and decision boundaries.

---

## 📂 Contents

- 📊 Data Preprocessing
- 🧮 Model Construction with kNN
- 📈 Model Evaluation with Metrics
- 🧪 Visualization of Decision Boundaries
- 📉 Accuracy Comparison for Various `k` Values

---

## ✅ Steps Performed

### 1. 🧹 Prepare the Data
- Load MNIST dataset using `mnist.load_data()`.
- Flatten 28x28 images into 784-length vectors.
- Normalize pixel values from [0, 255] to [0, 1] using `MinMaxScaler`.
- Split the data into:
  - 80% Training
  - 20% Validation
  - Separate Test Set
- Display dataset shapes using `rich` library.

---

### 2. 🏗️ Build & Train the kNN Model
- Test multiple values of `k` (3, 5, 7, etc.).
- For each `k`:
  - Train using `KNeighborsClassifier`.
  - Predict on validation set.
  - Evaluate accuracy, precision, recall, and F1-score.
- Display results in a table.
- Plot graph: **Accuracy vs k**.

---

### 3. 🧪 Evaluate on Test Set
- Use best `k` from validation phase.
- Predict on test dataset.
- Calculate final test accuracy.
- Show best performing `k` in results.

---

### 4. 🖼️ Visualize Decision Boundaries
- Use `matplotlib` to create subplots.
- Plot decision boundaries for different `k` values.
- Use a mesh grid for boundary regions.
- Overlay validation points.
- Display accuracy for each subplot.

---

## 🧰 Libraries Used

- `scikit-learn`
- `matplotlib`
- `seaborn`
- `rich`
- `numpy`
- `keras.datasets.mnist`

---

## 👩‍💻 Submitted By

- **Name:** Mehwish Nasir  
- **Student ID:** F2022332060  
- **Section:** A1  
- **Course:** Machine Learning  
- **Instructor:** Dr. Ashfaq Ahmad  
- **Department:** Data Science 
- **University:** University of Management & Technology 
