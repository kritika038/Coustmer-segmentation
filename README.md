Customer Segmentation Project
📌 Project Overview

This project performs Customer Segmentation using transactional, item-level, and analytical base table (ABT) data.
The goal is to group customers based on behavioral patterns so businesses can design better targeting, marketing strategies, and personalized recommendations.

📂 Project Structure
customer-segmentation/
│
├── Customer Segmentation.ipynb      # Main notebook
├── analytical_base_table.csv        # ABT dataset
├── int_online_tx.csv                # Online transactions dataset
├── item_data.csv                    # Raw item-level dataset
├── pca_item_data.csv                # PCA-transformed item data
├── threshold_item_data.csv          # Threshold-filtered item data
└── README.md                        # Project documentation

🧠 Key Steps in the Project
1. Data Preprocessing

Cleansing missing values

Standardizing data

Merging multiple datasets

2. Feature Engineering

Creating RFM-like features

Item-level PCA

Thresholding based on frequency

3. Dimensionality Reduction

Using PCA to reduce feature complexity

Retaining key components that capture variance

4. Customer Segmentation (Clustering)

Applying clustering algorithms such as:

K-Means

Hierarchical Clustering (optional)

Selecting optimal clusters using:

Elbow Method

Silhouette Score

5. Insights & Interpretation

Understanding cluster behavior

Identifying customer groups for:

High-value segment

Churn-risk segment

Promo-sensitive customers

🚀 How to Run the Project
Requirements

Install these Python libraries:

pandas
numpy
scikit-learn
matplotlib
seaborn

Steps

Clone the repository:

git clone https://github.com/your-username/customer-segmentation


Install dependencies

Open the notebook:

jupyter notebook "Customer Segmentation.ipynb"


Run all cells to reproduce the analysis.

📊 Output

The notebook generates:

Customer clusters

PCA plots

Cluster interpretation tables

Segmentation-based insights

📝 Author

Kritika
Project for data analysis & customer behavior understanding
