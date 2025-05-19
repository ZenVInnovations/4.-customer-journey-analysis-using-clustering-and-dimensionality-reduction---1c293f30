#Customer Journey Analysis Using Clustering and Dimensionality Reduction
This project aims to analyze customer behavior in the tourism industry by using machine learning techniques like clustering and dimensionality reduction. The analysis helps segment customers based on their interactions, preferences, and demographics, which can assist in targeted marketing and personalized recommendations.

📌 Overview
The dataset includes 11,760 records and 17 columns with a mix of categorical (7) and numerical (10) variables.

The target variable is Taken Product, indicating whether the customer has opted for the tourism service.

Key tasks include:

Data Cleaning

Handling Missing and Duplicate Values

Exploratory Data Analysis (EDA)

Dimensionality Reduction using PCA (Principal Component Analysis)

Customer Segmentation using KMeans Clustering

Data Visualization for cluster profiling

🛠️ Technologies & Libraries Used
Python

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Data visualization

Scikit-learn – Machine Learning (PCA, KMeans, Evaluation)

Yellowbrick – Cluster visualization

📊 Key Features
Data Cleaning: Mode used for imputing categorical missing values, median for numeric.

Exploratory Analysis: Summary statistics for demographics and user engagement metrics.

Dimensionality Reduction: PCA reduces high-dimensional data while preserving variance.

Clustering: KMeans used for segmentation, optimized via Elbow Method and Silhouette Score.

Visualization: Visual aids for PCA components, cluster distribution, and user profile differentiation.

📁 Dataset
Contains variables like Age, Duration of Pitch, Monthly Income, Number of Followups, etc.

Engagement metrics such as Yearly Average Views, Total Likes, and Check-ins.

🚀 Results
Segmented users into clusters such as "Highly Engaged", "Moderately Engaged", and "Low Engagement" based on features.

Insights from these segments can help in customizing offers, improving retention, and enhancing user experience.
