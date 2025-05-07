**Customer Lifetime Value (LTV) Prediction Project Report**

---

**Introduction:**
Customer Lifetime Value (LTV) is a critical metric in modern business that predicts the total worth a customer will bring over the entire period of their relationship with a company. Understanding LTV helps in allocating marketing budgets effectively and prioritizing customer segments. This project aims to predict LTV based on customer purchase behaviors using regression modeling in Python.

**Abstract:**
This project involves building a machine learning model to predict LTV using a dataset that combines customer transaction history and behavior. Through data preprocessing, feature engineering, model training (XGBoost), and evaluation, we derive insights into the key drivers of customer value. The final model enables segmentation of customers based on predicted LTV for improved targeting and decision-making.

**Tools Used:**

* **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Joblib
* **Excel**: Initial data exploration and formatting
* **Google Collab**: Code development and visualization

**Steps Involved in Building the Project:**

1. **Data Collection & Merging**:

   * Loaded transaction data and customer ID mappings.
   * Merged into a single structured DataFrame for modeling.

2. **Feature Engineering**:

   * Calculated key features: Recency, Frequency, and Average Order Value (AOV).
   * Created the target variable: Monetary value (Total Customer Spend).

3. **Model Building**:

   * Selected XGBoost Regressor for predictive modeling.
   * Trained the model on the engineered features.

4. **Evaluation**:

   * Model evaluated using MAE (31.26) and RMSE (56.67).
   * Results show good prediction accuracy for a regression task.

5. **Visualization**:

   * Feature Importance chart identifies key influencers (Frequency, AOV).
   * Actual vs Predicted LTV plot visualizes model reliability.

6. **Model Saving & Deployment**:

   * Final model saved using Joblib (`ltv_model_.pkl`).
   * LTV predictions exported as a CSV (`LTV_predictions.csv`).

**Conclusion:**
This project successfully demonstrates the ability to predict Customer Lifetime Value using behavioral features and machine learning. The insights from feature importance and customer segmentation can be utilized for targeted marketing, customer retention strategies, and business growth. This streamlined 2-page report summarizes all major components and outcomes for future deployment and integration.

---

*End of Report*
