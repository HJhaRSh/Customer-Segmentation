# **Customer Segmentation Using K-Means Clustering and Power BI**

This project demonstrates customer segmentation using the **K-Means clustering algorithm** in Python. The insights are visualized using **Power BI** to create an interactive dashboard for analyzing customer behavior and identifying distinct groups for targeted marketing.

---

## **Project Overview**

- **Objective**: To analyze customer data and group them into meaningful clusters based on their demographics and spending behavior.
- **Dataset**: [Mall Customer Segmentation Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python).
- **Techniques Used**:
  - Data preprocessing and feature scaling.
  - Determining optimal clusters using the **Elbow Method**.
  - Applying **K-Means Clustering** for segmentation.
  - Visualizing insights using Power BI.

---

## **Key Features**

1. **Python Implementation**:
   - Preprocessing the data (handling missing values, encoding categorical variables).
   - Applying **K-Means Clustering** to segment customers.
   - Evaluating clustering performance using the **Elbow Method**.
   - Exporting clustered results to a CSV file for Power BI integration.

2. **Power BI Visualization**:
   - **Scatter Plot**: Income vs. Spending Score, colored by cluster.
   - **Cluster Distribution**: Bar charts or pie charts to represent customer distribution across clusters.
   - **Demographic Analysis**: Insights into gender and spending patterns within clusters.

3. **Insights**:
   - High-income, high-spending customers: Target for premium products.
   - Low-income, low-spending customers: Engage with budget-friendly offerings.
   - Moderate-income customers with average spending: Growth opportunities.

---

## **Project Structure**

- **Python Script**:
  - customer_segmentation.py: Full Python code for data preprocessing, clustering, and CSV export.

- **Dataset**:
  - Mall_Customers.csv: Input dataset used for analysis.

- **Power BI File**:
  - Customer_Segmentation_Dashboard.pbix: Interactive Power BI dashboard.

- **Clustered Results**:
  - Customer_Segmentation_Results.csv: CSV file containing customer data with cluster labels.

---

## **Tools & Libraries**

- **Python**:
  - Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Power BI**:
  - For interactive dashboard creation and visualization.

---

## **How to Run the Project**

1. Clone this repository:
   
bash
   git clone https://github.com/your-username/customer-segmentation.git


2. Install the required Python libraries:
   
bash
   pip install pandas numpy matplotlib seaborn scikit-learn


3. Run the Python script:
   
bash
   python customer_segmentation.py


4. Open Customer_Segmentation_Dashboard.pbix in **Power BI Desktop** to view and interact with the dashboard.

---

## **Results**

- **Cluster Distribution**: Number of customers in each segment.
- **Income vs. Spending Score Analysis**: Identifying distinct customer groups.
- **Demographic Insights**: Gender and behavioral patterns within clusters.

---

## **Future Enhancements**

- Add more customer attributes (e.g., age, purchase history) to improve segmentation.
- Experiment with advanced clustering algorithms like DBSCAN or Hierarchical Clustering.
- Automate the pipeline for seamless integration between Python and Power BI.

---

## **Contributions**

Contributions are welcome! Feel free to open an issue or submit a pull request with suggestions or improvements.

---

## **License**

This project is licensed under the MIT License. See the LICENSE file for details.
