# 📩 Message Intelligence System

A Machine Learning project that classifies messages as **Spam** or **Legitimate** using multiple classification algorithms. The project compares different models and evaluates their performance using standard machine learning metrics and cross-validation techniques.

---

# 📌 Project Overview

The **Message Intelligence System** is designed to automatically identify whether a message is **Spam (1)** or **Legitimate (0)**. The project follows a complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature scaling, model training, evaluation, and comparison.

Multiple classification algorithms are implemented and compared to identify the best-performing model.

---

# 🎯 Objectives

- Build a spam message classification system.
- Perform data preprocessing and exploratory data analysis.
- Train multiple machine learning classification models.
- Evaluate model performance using different metrics.
- Compare the performance of KNN, SVM, and Naive Bayes.
- Apply Cross Validation techniques to check model consistency.

---

# 📂 Project Structure

```text
Project - 4 Message Intelligence System/
│
├── Dataset/
│   └── Message_Intelligence_Dataset.csv
│
├── Notebook/
│   ├── Message_Intelligence_System.ipynb
│   └── Part - A Conceptual Understanding.ipynb
│
└── README.md
```

---

# 📊 Dataset Information

The dataset contains message-related features that help classify a message as Spam or Legitimate.

### Input Features

- Message Length
- Word Count
- Number of URLs
- Number of Digits
- Number of Special Characters
- Spam Keyword Score
- Legitimate Keyword Score
- Sender Activity Score
- Sender Account Age (Days)
- Messages Sent in Last 24 Hours
- Hour of Day
- Day of Week

### Target Variable

- **Spam Label**
  - 0 → Legitimate Message
  - 1 → Spam Message

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🤖 Machine Learning Algorithms

The following classification algorithms were implemented:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (Linear Kernel)
- Support Vector Machine (RBF Kernel)
- Support Vector Machine (Polynomial Kernel)
- Gaussian Naive Bayes

---

# 📈 Data Preprocessing

The following preprocessing steps were performed:

- Imported required libraries
- Loaded the dataset
- Explored the dataset
- Checked dataset information
- Checked missing values
- Handled missing values
- Converted categorical values (if required)
- Selected features and target variable
- Applied Feature Scaling
- Split the dataset into Training and Testing sets

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed using:

- Target Variable Distribution
- Histograms
- Correlation Heatmap
- Boxplots

These visualizations helped understand the data distribution and relationships between features.

---

# 📏 Model Evaluation Metrics

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# 🔄 Cross Validation

To check the consistency of the models, the following validation techniques were used:

- K-Fold Cross Validation
- Stratified K-Fold Cross Validation

---

# 📋 Model Comparison

The following models were compared:

- KNN
- Linear SVM
- RBF SVM
- Polynomial SVM
- Gaussian Naive Bayes

The comparison was based on:

- Accuracy
- Precision
- Recall
- F1-Score

---

# ✅ Conclusion

Different machine learning classification algorithms were applied to classify spam and legitimate messages.

The models achieved excellent performance on this dataset. Cross-validation also produced consistent results, indicating that the dataset is well-prepared and contains useful features for message classification.

This project demonstrates a complete machine learning workflow, from data preprocessing to model evaluation and comparison.

---

# 🎥 Project Explanation Video

A complete explanation of this project, including dataset understanding, preprocessing, EDA, model building, evaluation, and comparison, is available here:

**🔗 Explanatory Video :** 

---

# 👨‍💻 Author

**Gopi Gadara**

Machine Learning & Data Analytics Enthusiast
