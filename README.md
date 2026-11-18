# 🔍 Fake Profile Detection on Social Media Using Random Forest Algorithm

## 📌 Project Overview

Social media platforms have become an essential part of modern communication. However, the increasing number of fake and malicious accounts creates security risks such as phishing attacks, online scams, misinformation, and identity impersonation.

**Fake Profile Detection on Social Media** is a Machine Learning-based project that identifies and classifies social media accounts as **Genuine or Fake** using the Random Forest Classification Algorithm.

The system analyzes profile attributes, account activity, and behavioral patterns to identify suspicious profiles and improve online security.

## 🎯 Project Objectives

- Develop a Machine Learning model to detect fake social media profiles.
- Analyze user profile attributes and behavioral patterns.
- Classify accounts as Genuine or Fake.
- Identify important features influencing classification.
- Evaluate model performance using standard evaluation metrics.

## ⚙️ Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Machine Learning | Random Forest Classifier |
| Libraries | NumPy, Pandas, Scikit-learn |
| Data Visualization | Matplotlib |
| Model Serialization | Joblib |
| Development Environment | Anaconda / Jupyter Notebook |
| Operating System | Windows |

## 🧠 Machine Learning Algorithm

### Random Forest Classifier

Random Forest is a supervised ensemble learning algorithm that combines multiple Decision Trees to generate a more reliable prediction.

In this project:

1. Multiple Decision Trees are trained using different subsets of the dataset.
2. Each tree independently predicts whether a profile is Fake or Genuine.
3. Majority voting determines the final classification.
4. Feature importance helps identify the parameters that influence predictions.

## 🔎 Features Analyzed

The system considers the following profile and behavioral attributes:

| Feature | Description |
|---|---|
| Account Age | Number of days since account creation |
| Friends Count | Number of connections |
| Posts Count | Total number of posts |
| Posts Per Day | Average posting frequency |
| Bio Length | Length of the profile biography |
| Profile Picture | Availability of a profile picture |
| Followers-Following Ratio | Relationship between followers and following |
| Average Post Length | Average length of published content |
| URL Frequency | Number of URLs shared per post |
| Like Rate | Average engagement rate |

## 🔄 System Workflow

```text
       Input Profile Dataset
                |
                ▼
        Data Preprocessing
                |
                ▼
          Feature Selection
                |
                ▼
       Train-Test Split (75:25)
                |
                ▼
       Random Forest Classifier
                |
                ▼
         Model Prediction
                |
          ┌─────┴─────┐
          ▼           ▼
       Genuine       Fake
        Profile     Profile
          |           |
          └─────┬─────┘
                ▼
       Performance Evaluation
                |
                ▼
       Results & Visualization
```

## 📊 Performance Evaluation

The project evaluates classification performance using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Curve
- Confusion Matrix

### Accuracy Comparison

| System | Accuracy |
|---|---:|
| Existing System | 90% |
| Proposed Random Forest System | 95% |

*Note: The 95% proposed accuracy and 90% existing-system accuracy are the comparison values stated in the project implementation/report. They should not be interpreted as independently verified real-world performance.*

## 📈 Project Outputs

The project generates the following outputs:

- Fake and Genuine profile predictions.
- Feature Importance visualization.
- Accuracy Comparison Graph.
- ROC Curve.
- Confusion Matrix.
- Classification Report.
- Saved Machine Learning Model.
- Prediction Results in CSV format.

## 📂 Project Structure

```text
Fake-Profile-Detection/
│
├── dataset/
│   └── fake_profile_dataset.csv
│
├── notebooks/
│   └── fake_profile_detection.ipynb
│
├── fake_profile_project/
│   ├── rf_fake_detector.joblib
│   ├── scaler.joblib
│   ├── sample_profiles.csv
│   ├── prediction_results.csv
│   ├── accuracy_comparison_fixed.png
│   ├── roc_curve.png
│   └── feature_importances.png
│
├── README.md
└── requirements.txt
```

*The structure above is a suggested GitHub repository organization. Include only files that are actually available in your repository.*

## 🚀 Installation & Execution

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Fake-Profile-Detection.git
```

### 2. Navigate to the Project Directory

```bash
cd Fake-Profile-Detection
```

### 3. Install Dependencies

```bash
pip install numpy pandas scikit-learn matplotlib joblib
```

### 4. Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook cells sequentially to preprocess the data, train the Random Forest model, generate predictions, and visualize the results.

## 🔮 Future Enhancements

- Integrate Natural Language Processing (NLP) to analyze profile descriptions and user-generated content.
- Explore Deep Learning models for improved classification.
- Integrate Firebase for real-time data monitoring and alert generation.
- Develop a user-friendly web dashboard.
- Explore real-time social media profile analysis through authorized platform APIs.

## 🎓 Project Information

| Detail | Information |
|---|---|
| Project Domain | Cyber Security / Machine Learning |
| Project Type | Academic Project |
| Degree | B.E. Computer Science and Engineering (Cyber Security) |
| Institution | K.L.N. College of Engineering |
| Project Year | 2025 |
| Algorithm | Random Forest Classifier |

## 👨‍💻 Contributors

- **Shriram Sankar LV**
- **Niranjan B**

## 📚 References

1. Nikhitha K. V., K. Bhavya, D. U. Nandini – Fake Account Detection on Social Media using Random Forest Classifier, IEEE, 2023.
2. Masood F. et al. – Spammer Detection and Fake User Identification on Social Networks, IEEE Open Access, 2020.
3. Y. Elyusufi and Z. Elyusufi – Social Networks Fake Profiles Detection Using Machine Learning Algorithm, 2019.
4. Bharti Goyal, Nasib Singh Gill, and Preeti Gulia – Securing Social Spaces: Machine Learning Techniques for Fake Profile Detection.

---
