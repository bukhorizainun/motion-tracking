# 📱 Motion Tracking for Smartphone Carrying Position Classification  
### A Pervasive Computing Approach using Sensor Data and Machine Learning

---

## 📌 Abstract
This project presents a pervasive computing framework for classifying smartphone carrying positions using tri-axial accelerometer data. The study integrates signal processing, feature engineering, and machine learning to enable context-aware classification of user behavior.

Experimental results demonstrate that engineered motion features can effectively distinguish between carrying positions such as hand-held and pocket-based placements. The work highlights the role of data-driven methods in real-world embedded intelligence systems.

---

## 🧠 1. Introduction
Pervasive computing systems aim to provide intelligent, context-aware services by leveraging sensor data from everyday devices. Smartphones, equipped with accelerometers, offer a rich source of motion information that can be exploited for behavioral analysis.

This project focuses on identifying the carrying position of a smartphone using motion signals, which has applications in:
- Activity recognition
- Human-computer interaction
- Context-aware mobile systems
- Smart environments

---

## ⚙️ 2. Methodology

### 2.1 Data Representation
The dataset consists of tri-axial accelerometer signals transformed into engineered features and stored in ARFF format for machine learning workflows.

---

### 2.2 Feature Engineering
Features are extracted from both time and frequency domains, including:

- Statistical measures (mean, variance, standard deviation)
- Energy-based metrics
- Spectral features (Power Spectral Density)
- Entropy-based features

These features capture motion dynamics and signal variability across different carrying positions.

---

### 2.3 Classification Model
A supervised learning approach is used:

- Model: **K-Nearest Neighbors (KNN)**
- Distance-based classification using feature space similarity

---

### 2.4 Evaluation Strategy
Model performance is evaluated using:

- Confusion Matrix
- ROC Curve
- Learning Curve
- Cross-validation

---

### 2.5 Interpretability & Analysis
To understand feature contributions and structure:

- **PCA** for dimensionality reduction
- **Correlation analysis** for feature relationships
- **SHAP values** for feature importance explanation

---

## 📊 3. Results

The classification system achieves effective separation between smartphone carrying positions.

Key observations:

- Distinct clusters are visible in feature space
- High separability between hand-held and pocket positions
- Robust classification performance using engineered features

---

## 📈 4. Experimental Outputs


```markdown
![Confusion Matrix](results/figures/confusion_matrix.png)
![ROC Curve](results/figures/roc_curve.png)
![PCA Visualization](results/figures/pca.png)
