# Customer Segmentation using Clustering on Olist E-commerce Data

A machine learning project focused on discovering actionable customer segments from the Brazilian e-commerce platform **Olist** using unsupervised learning techniques. This project applies advanced data preprocessing, feature engineering, clustering algorithms, and business profiling to transform raw transactional data into strategic customer insights.

---

## Project Overview

Understanding customer behavior is essential for improving retention, personalization, logistics, and marketing performance. In this project, customer segmentation is performed using the **Olist Brazilian E-commerce Dataset (2016–2018)** containing over 100,000 orders across multiple relational tables.

The objective is to:

* Build meaningful **customer-level features**
* Apply and compare clustering techniques
* Evaluate cluster quality using internal metrics
* Generate business-friendly customer personas
* Provide data-driven marketing and operational recommendations

---

## Dataset

The dataset consists of multiple relational CSV files containing:

* Orders
* Customers
* Payments
* Reviews
* Products
* Sellers
* Geolocation
* Order items
* Product categories

Source: [Olist Brazilian E-commerce Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?utm_source=chatgpt.com)

---

## Project Workflow

### 1. Data Preprocessing & Feature Engineering

Key preprocessing steps include:

* Merging relevant relational tables
* Handling missing values and duplicates
* Removing outliers
* Converting date/time variables
* Aggregating transactional data at the **customer level**
* Encoding categorical variables
* Scaling numerical features

### Customer Features Created

Examples of engineered features:

* Total spending
* Average order value
* Purchase frequency
* Review score average
* Delivery delay
* Payment installment behavior
* Preferred product categories
* Customer geographic region
* Recency metrics

---

### 2. Exploratory Data Analysis (EDA)

Comprehensive EDA was conducted to understand:

* Spending distributions
* Purchase frequency patterns
* Customer geographic concentration
* Payment preferences
* Product category popularity
* Customer review sentiment
* Delivery performance

Visualization libraries used:

* Matplotlib
* Seaborn
* Plotly

---

### 3. Clustering Models

The project experiments with multiple clustering approaches:

#### Baseline Model

* **K-Means Clustering**

#### Alternative Models

* **Gaussian Mixture Models (GMM)**
* Hierarchical Clustering
* Density-based exploration (DBSCAN experimentation)

---

### 4. Dimensionality Reduction

To improve cluster separability and visualization:

* PCA (Principal Component Analysis)
* t-SNE visualizations
* Feature scaling comparisons

---

### 5. Cluster Validation

Internal validation metrics used:

* Silhouette Score
* Davies–Bouldin Index
* Elbow Method
* Cluster visualization diagnostics

---

## Final Customer Segments

The final model identifies distinct customer groups such as:

* High-value loyal customers
* Budget-conscious shoppers
* Infrequent bargain buyers
* Premium electronics consumers
* Dissatisfied low-retention customers

Each segment includes:

* Behavioral statistics
* Geographic patterns
* Product preferences
* Customer satisfaction indicators
* Actionable business recommendations

---

## Business Recommendations

Examples of strategic insights generated:

* Personalized promotions for high-value customers
* Free-shipping incentives for price-sensitive users
* Loyalty programs for repeat buyers
* Logistics optimization for delayed-delivery regions
* Retargeting campaigns for inactive customers

---

## Results

The clustering workflow successfully produced interpretable and business-relevant customer segments. Among the tested approaches, **Gaussian Mixture Models (GMM)** provided better flexibility in modeling overlapping customer behaviors compared to traditional K-Means.

Dimensionality reduction using PCA improved visualization clarity while maintaining strong cluster cohesion.

## Academic Context

This project was developed as part of a practical machine learning assignment focused on:

* Customer analytics
* Unsupervised learning
* Business intelligence
* Data-driven decision-making


