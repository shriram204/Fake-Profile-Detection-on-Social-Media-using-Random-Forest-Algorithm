# 🔍 Fake Profile Detection Using Random Forest

\<p align="center">
&#x20; \<b>Machine Learning-Based Social Media Security Solution\</b>
\</p>

\<p align="center">
&#x20; \<img src="[https://img.shields.io/badge/Python-3.x-blue?logo=python](https://img.shields.io/badge/Python-3.x-blue?logo=python)" />
&#x20; \<img src="[https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)" />
&#x20; \<img src="[https://img.shields.io/badge/Domain-Cybersecurity-red](https://img.shields.io/badge/Domain-Cybersecurity-red)" />
&#x20; \<img src="[https://img.shields.io/badge/Status-Completed-success](https://img.shields.io/badge/Status-Completed-success)" />
\</p>

## 📌 Overview

Fake social media profiles are increasingly exploited for phishing, online scams, impersonation, and spreading misinformation.

This project implements a **Machine Learning-based Fake Profile Detection System** using the Random Forest Classification algorithm to distinguish between fake and genuine social media accounts.

The model analyzes profile characteristics and behavioral patterns to identify suspicious accounts and generate classification results.

## 🎯 Key Objectives

- Automate fake profile identification.
- Analyze user profile attributes and behavioral patterns.
- Apply Random Forest for binary classification.
- Identify important features influencing predictions.
- Evaluate model performance using classification metrics.

## ⚙️ Tech Stack

- **Language:** Python
- **Algorithm:** Random Forest Classifier
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib
- **Development:** Jupyter Notebook
- **Model Storage:** Joblib

## 🔬 Detection Parameters

The model analyzes the following features:

- Account Age
- Followers / Friends Count
- Following-Followers Ratio
- Profile Bio Length
- Profile Picture Availability
- Posting Frequency
- Average Post Length
- URLs Per Post
- User Engagement Rate

## 🧠 Methodology

1. **Data Collection** – Prepare fake and genuine profile records.
2. **Data Preprocessing** – Clean and transform the dataset.
3. **Feature Analysis** – Extract relevant profile and behavioral attributes.
4. **Model Training** – Train the Random Forest Classifier.
5. **Prediction** – Classify profiles as Fake or Genuine.
6. **Evaluation** – Analyze classification performance using standard metrics.

## 📊 Performance Comparison

| Metric           | Existing System |   Proposed System |
| ---------------- | --------------: | ----------------: |
| Accuracy         |             90% |               95% |
| Detection Method |      Rule-Based |     Random Forest |
| Feature Analysis |         Limited | Multiple Features |

*Accuracy figures represent the comparison values documented in the project report. Actual test-set accuracy is evaluated separately.*

## 📈 Visualizations & Results

- Fake vs Genuine Profile Prediction
- Accuracy Comparison Graph
- Feature Importance Analysis
- ROC Curve
- Confusion Matrix
- Prediction Results

## 💻 Installation & Usage

**1. Clone the repository**

```bash
git clone https://github.com/your-username/Fake-Profile-Detection.git
```

**2. Navigate to the project directory**

```bash
cd Fake-Profile-Detection
```

**3. Install dependencies**

```bash
pip install numpy pandas scikit-learn matplotlib joblib
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

**5. Open the project notebook and run the cells.**

## 📁 Project Structure

```text
Fake-Profile-Detection/
│
├── README.md
├── Fake_Profile_Detection.ipynb
├── dataset/
├── models/
├── outputs/
└── results/
```

## 🚀 Future Enhancements

- Real-time suspicious profile monitoring.
- Firebase integration for data storage.
- NLP-based profile content analysis.
- Deep Learning-based detection techniques.
- Integration with authorized social media APIs.

## 🛡️ Project Domain

**Cybersecurity | Machine Learning | Social Media Security**

## 🎓 Academic Project

**Institution:** K.L.N. College of Engineering

**Academic Year:** 2025

**Project Type:** Machine Learning-Based Cybersecurity Project

---

\<p align="center">   \<b>Building Safer Social Media Through Intelligent Detection.\</b> \</p>
