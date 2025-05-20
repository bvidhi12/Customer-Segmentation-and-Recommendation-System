# 🛒 Customer Segmentation & Product Recommendation for Online Retail

This project explores customer segmentation and recommendation system development using a transactional dataset from a UK-based online retailer, sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail). The dataset contains transactions occurring between 2010 and 2011. By leveraging K-Means clustering and customer-centric feature engineering, the goal is to segment customers into meaningful groups and recommend top-selling products to boost marketing efficiency and sales.

---

## 📌 Objectives

1. **Data Cleaning & Transformation**

   * Handle missing values, duplicates, and outliers.
   * Prepare data for downstream modeling.

2. **Feature Engineering**

   * Generate customer-level features from transaction-level data (e.g., purchase frequency, recency, monetary value).
   * Transform the dataset into a customer-centric view.

3. **Data Preprocessing**

   * Apply feature scaling to normalize numerical features.
   * Use dimensionality reduction (PCA) to streamline clustering input.

4. **Customer Segmentation**

   * Apply K-Means clustering to segment customers into distinct groups.
   * Visualize and interpret customer clusters.

5. **Cluster Analysis & Evaluation**

   * Profile each cluster based on behavior and spending habits.
   * Evaluate clustering effectiveness using metrics like silhouette score.

6. **Recommendation System**

   * Recommend best-selling products to customers in each cluster who haven’t purchased those items.
   * Leverage purchase patterns to drive cross-selling and upselling opportunities.

---

## 📂 Dataset

* **Source**: UCI Machine Learning Repository - [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)
* **Attributes**:

  * `InvoiceNo`: Transaction ID
  * `StockCode`: Product code
  * `Description`: Product description
  * `Quantity`: Number of products purchased
  * `InvoiceDate`: Date of the transaction
  * `UnitPrice`: Product price per unit
  * `CustomerID`: Unique identifier for each customer
  * `Country`: Customer's country

---

## 🛠️ Tools & Libraries

* **Languages**: Python
* **Libraries**:

  * `pandas`, `numpy` – Data manipulation
  * `matplotlib`, `seaborn` – Visualization
  * `scikit-learn` – Clustering, preprocessing, and evaluation
  * `mlxtend` – Association rules and product recommendation (if used)
  * `plotly` – Interactive visualization (optional)

---

## 📈 Results Overview

* Segmented customers into **K distinct groups** with unique behavioral traits.
* Developed **cluster profiles** to inform targeted marketing strategies.
* Created a **simple product recommendation system** tailored for each segment.
* Identified top-selling items for each cluster to aid cross-selling.

---

## 📬 Contact

For questions, collaborations, or feedback, feel free to connect:

* **Name**: Vidhi Bhatt
* **LinkedIn**: [linkedin.com/in/vidhi-bhatt](https://www.linkedin.com/in/vidhi2000/)
* **Email**: [your-email@example.com](mailto:bhattvidhi1203@gmail.com)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

