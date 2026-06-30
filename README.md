# Unsupervised-Learning-facebook-segmentation-Clustering-
Facebook User Segmentation using Unsupervised Machine Learning (K-Means Clustering) with data preprocessing, PCA visualization, and customer behavior analysis.

# Facebook User Segmentation using K-Means Clustering

## 📌 Project Overview

This project applies **Unsupervised Machine Learning** to segment Facebook users based on their profile and activity data. Using the **K-Means Clustering** algorithm, the project identifies groups of users with similar characteristics, helping businesses and researchers understand user behavior for targeted marketing and analytics.

---

## 🎯 Objectives

- Load and understand the Facebook dataset.
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the data.
- Handle missing values and duplicates.
- Scale numerical features using StandardScaler.
- Apply K-Means clustering.
- Determine the optimal number of clusters.
- Evaluate clustering performance using Silhouette Score.
- Visualize clusters using Principal Component Analysis (PCA).
- Save the trained clustering model.

---

## 📂 Dataset

The project uses the **Pseudo Facebook Dataset** (`pseudo_facebook.csv`), which contains user profile information and activity statistics.

Example features include:

- Age
- Gender
- Friend Count
- Friendships Initiated
- Likes
- Likes Received
- Mobile Likes
- Mobile Likes Received
- DOB information
- Other user engagement metrics

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📊 Machine Learning Workflow

1. Import required libraries
2. Load dataset
3. Perform data exploration
4. Handle missing values
5. Remove duplicate records
6. Encode categorical variables
7. Feature scaling using StandardScaler
8. Apply K-Means Clustering
9. Evaluate clusters using Silhouette Score
10. Reduce dimensions with PCA
11. Visualize user clusters
12. Save trained model

---

## 📈 Algorithms Used

- K-Means Clustering
- Principal Component Analysis (PCA)

---

## 📷 Visualizations

The notebook includes visualizations such as:

- Correlation Heatmap
- Elbow Method
- PCA Cluster Plot
- Cluster Distribution
- Feature Analysis

---

## 📁 Project Structure

```
Facebook-User-Segmentation/
│
├── facebook segmentation Clustering.ipynb
├── pseudo_facebook.csv
├── requirements.txt
├── README.md
└── saved_model/
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/facebook-user-segmentation.git
```

Move into the project folder:

```bash
cd facebook-user-segmentation
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
jupyter
```

---

## 📌 Results

- Successfully segmented Facebook users into meaningful clusters.
- Reduced high-dimensional data using PCA for visualization.
- Evaluated cluster quality using the Silhouette Score.
- Built a reusable clustering pipeline for user segmentation.

---

## 💡 Applications

- Customer Segmentation
- Personalized Marketing
- Recommendation Systems
- Social Media Analytics
- User Behavior Analysis
- Business Intelligence

---

## 📚 Future Improvements

- Compare K-Means with DBSCAN and Hierarchical Clustering.
- Hyperparameter tuning for better clustering.
- Interactive dashboards using Plotly or Streamlit.
- Deploy the clustering model as a web application.

---

## 👨‍💻 Author

**Mohammed Sinan**

If you found this project helpful, consider giving the repository a ⭐.
