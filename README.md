# Customer-Segmentation-Clustering

## 📌 Project Overview

This project focuses on customer segmentation using K-Means clustering, a popular unsupervised machine learning algorithm. The goal is to group customers based on their purchasing behavior and demographic features, enabling businesses to better understand customer patterns and tailor marketing strategies accordingly.

The project includes data preprocessing, clustering analysis, model training, and deployment-ready components.

## 📂 Repository Structure

├── customer-segmentation-clustering.ipynb  # Exploratory analysis & model training

├── customer_segmentation.csv               # Dataset used for clustering

├── kmeans_model.pkl                        # Trained K-Means model

├── scaler.pkl                              # StandardScaler used for preprocessing

├── main.py                                 # Script to run predictions

├── requirements.txt                        # Project dependencies

├── README.md                               # Project documentation

├── LICENSE                                 # License file

└── .gitignore                              # Ignored files

## 📊 Dataset

•	File: customer_segmentation.csv

•	Contains customer-related features such as spending patterns and demographic information.

•	Used to identify meaningful customer groups via clustering.

## 🧠 Methodology

1.	Data Cleaning & Preprocessing
	
  •	Handling missing values

  •	Feature scaling using StandardScaler

2.	Exploratory Data Analysis

  •	Understanding customer distributions

  •	Visualizing relationships between features

3.	Model Training
	
  •	Applied K-Means Clustering
	
  •	Optimal number of clusters determined using the Elbow Method

4.	Model Persistence

  •	Saved trained model (kmeans_model.pkl)

  •	Saved scaler (scaler.pkl) for consistent inference

## 🚀 How to Run the Project

1️⃣ Clone the Repository

```
git clone https://github.com/Kaushik-Puttaswamy/customer-segmentation.git
cd customer-segmentation
```
2️⃣ Install Dependencies

```
pip install -r requirements.txt
```
3️⃣ Run the Application

```
python main.py
```
## 📦 Dependencies

Main libraries used:
	
•	numpy

•	pandas

•	scikit-learn

•	matplotlib

•	seaborn

•	joblib

(See requirements.txt for the full list)


## 📈 Results

•	Customers are grouped into distinct clusters based on similarities.

•	Each cluster represents a unique customer segment that can be targeted differently for marketing or business strategies.


## 🛠 Future Improvements

•	Add cluster interpretation and labeling

•	Deploy as a web app using Flask or Streamlit

•	Include automated model evaluation

•	Add support for new customer data uploads


## 📜 License

This project is licensed under the terms of the MIT License.
See the LICENSE file for details.

## 👤 Author

Kaushik Puttaswamy
