
Credit Card Repayment Prediction

Identifying the Challenge
In the world of banking, predicting credit card repayment is crucial. The challenge lies in leveraging diverse customer features to gauge timely credit card bill payments. Unraveling the complexities inherent in predicting an individual's ability to meet monthly credit card obligations allows banks to tailor suitable credit card contracts for new customers.

Navigating the Process
The journey began with meticulous preprocessing involving data cleaning, exploratory data analysis (EDA), and strategic feature engineering. Utilizing a Kaggle dataset provided a comprehensive view of individual attributes, forming the foundation for the machine-learning algorithm. This phase included merging multiple files and removing potentially biased features.

Feature Selection
Every chosen feature had to contribute to predicting an individual's ability to meet credit card obligations. Considerations around potential bias, exemplified by excluding ethnicity, were crucial. The goal is to refine the data, ensuring a high-quality, representative sample to enhance prediction accuracy. The exclusion of ethnicity aligns with the broader goal of creating a fair and unbiased credit prediction model, ensuring ethnicity doesn't impact credit card offerings.

Model Selection
In pursuit of accuracy, logistic regression, random forest models, and XGBoost classification models were deployed. Meticulous hyperparameter tuning led to the random forest model emerging as the most adept, achieving a 71% accuracy. The well-balanced data, with around 300,000 data points for both on-time and late payments, contributed to model robustness.

Model Performance Metrics
Precision: 74% accuracy in predicting late payments.
Recall: Successful identification of actual late payments 61% of the time.
In simple terms, the model effectively identifies potential late payments but acknowledges room for improvement.

Real-World Application
Envision financial institutions employing the model strategically for loans, mortgages, and credit cards for new customers. However, it's crucial to acknowledge the dataset's limitations. A practical approach involves enriching the model's training with additional data, such as previous financial statements. This enhances accuracy and makes the model more adaptable to real-world financial complexities.
