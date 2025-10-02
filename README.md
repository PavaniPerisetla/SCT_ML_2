# customer-segmentation-kmeans
Customer Segmentation using K-Means

📌 Overview

This project applies K-Means clustering to segment retail store customers based on their purchase behavior. Customer segmentation helps businesses understand shopping patterns, improve marketing strategies, and enhance customer experience.

📂 Dataset

The dataset contains customer information such as:
CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1–100)
You can replace this with your own customer dataset.

🛠️ Methodology

Data Preprocessing
Loaded dataset using pandas
Selected relevant features (Annual Income, Spending Score)
Standardized data for fair clustering
Clustering with K-Means
Applied the Elbow Method to choose the optimal number of clusters
Trained the model with chosen k
Assigned each customer to a cluster
Visualization
Plotted clusters in 2D space
Marked cluster centers with red X

📊 Results

Customers were grouped into clusters such as:
High income, high spenders
Low income, high spenders
High income, low spenders
etc.
Each cluster can be targeted with specific marketing strategies.

🚀 How to Run

Clone the repository:
git clone https://github.com/PavaniPerisetla/customer-segentation-kmeans.git
cd customer-segmentation-kmeans

Install dependencies:
pip install -r requirements.txt

Run the notebook or script:
google colab notebook K-Cluster.ipynb

📌 Requirements

Python 3.x
pandas
numpy
scikit-learn
matplotlib

📬 Contact

If you find this project useful, feel free to ⭐ star the repo or connect with me.
