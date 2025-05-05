# Credit-Card-Fraud-Detection-using-Python

### Credit Card Fraud Detection Analysis Report

#### **Overview**
This report examines a Python-based credit card fraud detection model using logistic regression. The dataset contains transactions labeled as either fraudulent or non-fraudulent, and the analysis aims to build a classification model to identify fraudulent transactions effectively.

#### **Dataset Overview**
- **Total transactions:** 284,807
- **Fraudulent transactions:** 492 (0.17%)
- **Non-fraudulent transactions:** 284,315 (99.83%)
- **Features:** 30 anonymized numerical variables (V1–V28), Time, and Amount.

#### **Data Processing**
- Loaded the dataset using pandas and examined basic statistics.
- Checked data distribution and imbalance, confirming that fraud cases are highly underrepresented.
- Split the dataset into:
  - **Training set:** 70% (199,364 transactions)
  - **Test set:** 30% (85,443 transactions)

#### **Model & Evaluation**
- **Classifier Used:** Logistic Regression
- **Evaluation Metrics:**
  - Confusion Matrix Visualization: Showed the classification performance.
  - **Recall Score (Sensitivity):** 0.61 (61% of fraudulent transactions correctly identified)
  - **F1 Score:** 0.71 (harmonic mean of precision and recall)
  - The recall score suggests moderate fraud detection performance, but improvements can be explored using other models such as Random Forest or Neural Networks.

#### **Observations & Recommendations**
- **Data Imbalance:** The dataset is highly skewed towards non-fraudulent transactions. Techniques like oversampling fraud cases or implementing anomaly detection methods could improve detection.
- **Model Performance:** While logistic regression performs reasonably, advanced techniques like ensemble learning or deep learning could enhance fraud identification.
- **Feature Importance:** Since variables are anonymized, further feature engineering or domain-specific knowledge might improve model accuracy.

#### **Conclusion**
The logistic regression model provides a foundational approach to fraud detection but has room for improvement. Future work should focus on mitigating class imbalance and exploring more complex classification models.
