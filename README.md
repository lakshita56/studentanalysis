# studentanalysis
# Student Performance Analysis using K-Means Clustering

This project applies **K-Means clustering** to analyze student performance based on their study habits and academic results. The goal is to identify natural groupings of students using unsupervised machine learning techniques.

---

## 📊 Dataset

- Dataset: `student_data.csv`
- Contains demographic, social, and academic attributes
- Features used for clustering:
  - `studytime` – Weekly study time
  - `G3` – Final grade

---

## ⚙️ Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 🧠 Model Used

- **K-Means Clustering**
- Number of clusters: **3**
- Unsupervised learning approach

---

## 📈 Visualization

- Scatter plot showing:
  - X-axis: Study Time
  - Y-axis: Final Grade (G3)
- Different colors represent different student clusters

---

## 📊 Cluster Analysis

For each cluster, descriptive statistics are generated, including:
- Mean study time
- Mean final grade
- Distribution of student performance

This helps interpret patterns such as:
- High study time & high grades
- Moderate study time & average grades
- Low study time & low grades

---

## 🔮 New Student Assignment

The model can assign a new student to a cluster based on:
- Study time
- Expected final grade

This demonstrates practical usage of clustering results.

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-clustering.git
