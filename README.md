#  Customer Segmentation Using K-Means Clustering

##  Objective

The goal of this project is to segment customers into different groups based on their annual income and spending behavior using the **K-Means clustering algorithm**.

---

##  Dataset

The dataset used is **Mall Customers Dataset**, which contains:

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

---

##  Steps Performed

* Data Loading
* Feature Selection (Annual Income & Spending Score)
* Data Scaling using StandardScaler
* Finding optimal clusters using Elbow Method
* Applying K-Means Clustering
* Visualization of clusters

---

##  Evaluation Metrics

* **Silhouette Score** → Measures how well clusters are separated *(higher is better)*
* **Davies-Bouldin Index** → Measures cluster similarity *(lower is better)*

---

##  Results

* Customers are grouped into **5 clusters**
* Each cluster represents different spending patterns and customer behavior

---

##  Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

---

##  Project Files

* `kmeans_model.ipynb` → Main notebook
* `Mall_Customers.csv` → Dataset
* `README.md` → Project description

---

##  Conclusion

K-Means clustering helps identify different types of customers based on their spending behavior. This insight can be used for **targeted marketing** and improved business strategies.

---

##  How to Run

1. Open the notebook in Google Colab
2. Upload the dataset (`Mall_Customers.csv`)
3. Run all cells

---

##  Submission

GitHub repository link is provided as part of the assignment submission.

---
