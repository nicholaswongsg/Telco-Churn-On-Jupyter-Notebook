# Telco Churn On Jupyter Notebook
# About
This is our Mini Project for SC1015 Intro to Data Science & Artificial Intelligence. We have selected a Telco Churn Dataset from Kaggle. Our motivation for this project is to find out which attributes affect churn rate and how can we predict churning customers and improve customer retention.
# Contributors

<ul>
  <li>Donavan Ng Chao Yu</li>
  <li>Nicholas Wong Jia Hao</li>
  <li>Don Seo Kang Rui</li>
</ul>  

# Problem Defination
How to stop customers who are leaving for other telcos? Which attributes affect churn rate and how can we predict churning customers and improve customer retention?

# Data Preprocessing
<ul>
  <li>Checked the dataset and removed all duplicated rows</li>
  <li>Removed rows that contained blank fields</li>
  <li>Check and remove any outliers using the box-plot and IQR</li>
  <li>Changing of data types from object to float for better prediction of data (one-hot encoder)</li>
  <li>Reclassified data into unique classes to better use it to predict</li>
</ul>  

# AI Models Used
<ul>
  <li>Decision Tree</li>
  <li>Random Forest</li>
  <li>Random Forest (With Hyperparameter)</li>
  <li>Artificial Neural Network</li>
  <li>K-Fold Logistic Regression Model</li>
  <li>K-Fold SVM</li>
  <li>K-Fold Random Forest Performance</li>
</ul>  

<img src="img/Comparing Of Strategies.png" alt="Comparing Of Strategies">

# Conclusion
Our recommendation to the telco is to establishing an Inside Sales Team to look for ways to grow the business from within rather than outwards. From our exploratory analysis we identified a 4 key pillars that is critical to the business.
<ul>
  <li>Churn customers profile are new customers with high monthly charges (3rd Quartile at $89.86)</li>
  <li>Loyal customers tend to have an increasing upward trend of total charges</li>
  <li>20% Churn comes from subscribers under 10 years</li>
  <li>Loyal customers is on a 2-years contract basis</li>
</ul>

Hence, we have charted out the consumer experience journey and show our recommendations at every phase.

<img src="img/Consumer Experience Journey.png" alt="Consumer Experience Journey">

# What Did We Learn From This Project?
Apart from what we learned in SC1015, our group has consistently consulted with our TA Xue Wani. This has challenged our outlook on how we approach data problems. We picked up one-hot encoding and AI models like Artificial Neural Network (ANN) and K-Fold to test which models work best to predict the true positives (churn customers).
