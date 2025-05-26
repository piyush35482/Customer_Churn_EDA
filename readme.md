## 📊 Customer Churn EDA Project

This exploratory data analysis (EDA) focuses on understanding customer churn behavior using the **Telco Customer Churn** dataset. The analysis uses simple yet effective visualizations such as **count plots**, **pie charts**, e.t.c. to extract actionable business insights related to customer retention and service usage.

---

### 🔍 Key Objectives

* Identify key features affecting churn.
* Visualize categorical variables in relation to churn.
* Understand customer behavior across different services and contract types.
* Provide early churn insights using tenure distribution.

---

### 💡 Major Insights

1. **Churn Rate**:

   * Overall churn rate is approximately **26.5%**.

2. **Senior Citizens**:

   * **Senior citizens churn at \~42%**, while **non-seniors churn at \~24%**.

3. **Internet Service Type**:

   * **Fiber optic** users have the **highest churn around (\42%)**.
   * **DSL users churn less around (\19%)**.
   * **No internet service** customers rarely churn.

4. **Support & Protection Services**:

   * Churn is **notably higher** among users who **do not have**:

     * Online Security
     * Tech Support
     * Device Protection
     * Online Backup

5. **Contract Type**:

   * **Month-to-month** customers churn the most.
   * Customers with **1-year or 2-year contracts** churn far less.

6. **Streaming Services**:

   * Having **StreamingTV** or **StreamingMovies** doesn’t strongly reduce churn; rates remain moderate to high.

7. **Tenure**:

   * The histogram shows most churn occurs within the **first 10–15 months**, highlighting a key **early churn risk window**.

---

### 📁 Files

* `main_file.ipynb` – Jupyter notebook with all code and charts.
* Dataset: **[Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)**

---

### 🛠️ Tools Used

* Python
* Pandas, NumPy
* Seaborn, Matplotlib

---

### ✅ Conclusion

This EDA shows that churn is **closely linked to contract types, service subscriptions, and customer tenure**. These insights can support telecom companies in crafting **targeted retention strategies** focused on early engagement, bundling valuable services, and offering stable contracts.


