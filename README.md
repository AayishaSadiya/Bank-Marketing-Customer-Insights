## Bank Marketing
 
### Summary
This project undertakes a comprehensive analysis of a bank marketing dataset provided by Deloitte to formulate an effective strategy for term deposit subscriptions. The data is thoroughly examined, and key features are identified through data visualization. The preprocessing phase includes encoding categorical variables and scaling features. Six machine learning models, including Logistic Regression, Linear Support Vector Classifier, Decision Tree Classifier, Random Forest Classifier, Gradient Boosting Classifier, and XGBoost Classifier, are trained and evaluated for their performance on both training and testing sets. The results are used to propose a comprehensive marketing strategy. Insights include optimal marketing months, a call policy recommendation, age targeting, occupation influence, consideration of house loans and balances, call duration strategy, engagement strategies, contact preferences, and the impact of the outcome of previous campaigns and job influence on term deposit subscriptions.

### Breakdown of Project

#### 1. Importing Libraries and Understanding Data:
* Essential libraries like pandas, numpy, matplotlib, seaborn are imported.
* Data is read and an initial exploration is performed to understand its structure and characteristics.

#### 2. Data Exploration and Preprocessing:
* Categorical variables encoded using Label Encoding.
* Stratified sampling implemented for balanced class distribution.
* Feature scaling applied using StandardScaler.

#### 3. Model Training:
* Six models including Logistic Regression, Linear Support Vector Classifier, Decision Tree Classifier, Random Forest Classifier, Gradient Boosting Classifier, and XGBoost Classifier models trained.

#### 4. Model Evaluation:
* Train set accuracy scores analyzed for each model.
* Test set metrics (accuracy, f1_score, precision, recall, balanced_accuracy) computed for model evaluation.
* Based on the test set metrics, XGBoost Classifier emerges as the preferred model with the highest accuracy (84.47%) and balanced performance across other metrics. It is closely followed by Gradient Boosting Classifier and Random Forest Classifier.

#### 5. Feature Importance Analysis:
* Feature importance examined using Random Forest Classifier, Gradient Boosting Classifier, and XGBoost Classifier.
* Random Forest: Emphasizes call duration, financial status, age, temporal patterns, and occupation
* Gradient Boosting: Highlights call length, seasonality, communication channels, historical responses, and housing
* XGBoost: Underscores the influence of communication channels, historical responses, engagement length, housing situation, and past interactions

### Insights Derived:

1. Optimal Marketing Months: Focus efforts on February, March, September, October, and potentially December.
2. Call Policy: Limit calls to three per potential client to enhance efficiency while maintaining consistent contact.
3. Age Targeting: Prioritize targeting clients in their 20s or younger and 60s or older, as these groups show higher subscription probabilities.
4. Occupation Influence: Students and retirees are more likely to subscribe.
5. House Loans and Balances: Focus on individuals with average and high balances who are less likely to have house loans.
6. Call Duration Strategy: Target individuals with call durations above 375 seconds for a higher likelihood of subscription success.
7. Engagement Strategies: Employ engaging questionnaires during calls to increase conversation duration.
8. Contact Preference: Preferentially use cellular contact for higher subscription rates.
9. Outcome of Previous Campaign: Past subscribers are more likely to subscribe again.
10. Job Influence: Consider the occupation influence, where blue-collar workers are less likely to subscribe, while students show positive subscription indicators.
11. This strategy integrates timing, targeted demographics, engagement tactics, and contact preferences to enhance the overall success of the marketing campaign for term deposit subscriptions.

