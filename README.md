# Telecom Customer Churn

Dataset :: [Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn "Telco Customer Churn")

* Dataset :: 
  * Customer Churn - Customers who left within the last month.
  * Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
  * Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges.
  * Demographic info about customers – gender, age range, and if they have partners and dependents.

* Inspiration::
  * Our aim was to try to analyze the dataset and try to figure out what factors are important for not churn.
  * Predict behavior to retain customers.
  * Will customer go away?
  
  
##### Steps (What we did)

- EDA :: 
  1. Reduce memory usage, Checking Data information (With Pandas).
  1. Data Cleaning (Drop NA, Tenure groups, Handle numeric values).
  2. Data Exploration - Categorical columns, Numerical Columns, One Hot, Correlation. 
  3. Univariate analysis WRT Churn status(Plots).
  4. Bivariate Analysis WRT Churn Status and Gender.
  5. Conclusion

- Prediction ::
  1. Handle Categorical Values (OneHot encoding).
  3. Standardisation (Preprocessing of Data)
  4. Prediction by Decision Tree(0.72), Down Sampling, Random Forest Classifier(0.79), Neural Network (Tensorflow, Keras)(0.80)
  5. Accuracy :: 0.80 (Keras)
 


