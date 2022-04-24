# Telco Churn On Jupyter Notebook
# About
This is our Mini Project for SC1015 Intro to Data Science & Artificial Intelligence. We have selected a Telco Churn Dataset from Kaggle. Our motivation for this project is to find out which attributes affect churn rate (in a telco) and how can we predict churning customers and improve customer retention.

<img src="img/cover.jpeg" alt="Cover Page for SC1015">

# Contributors

<table>
  <tr>
    <th>Member</th>
    <th>Contributions</th>
    <th>Github</th>
  </tr>
  <tr>
    <td>Donavan Ng Chao Yu</td>
    <td>Contributed</td>
    <td>@Account</td>
  </tr>
  <tr>
    <td>Nicholas Wong Jia Hao</td>
    <td>Data Preperation, Data Visualisation, K-Fold Logistic Regression Model, K-Fold SVM, K-Fold Random Forest</td>
    <td>@nicholaswongsg</td>
  </tr>
  <tr>
    <td>Don Seo Kang Rui</td>
    <td>Data Preparation, Data Visualisation, Decision Tree</td>
    <td>@donseokangrui</td>
  </tr>
</table>

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
Apart from what we learned in SC1015, our group has consistently consulted with our <b>TA Xue Wani</b>. This has challenged our outlook on how we approach data problems. We picked up one-hot encoding and AI models like Artificial Neural Network (ANN) and K-Fold to test which models work best to predict the true positives (churn customers).

# References
<ul>
  <li>Kaggle - </li>
  <li>ANN - https://www.bogotobogo.com/python/scikit-learn/Artificial-Neural-Network-ANN-1-Introduction.php</li>
  <li>K-Fold - https://notebook.community/RTHMaK/RPGOne/scipy-2017-sklearn-master/notebooks/13%20Cross%20Validation</li>
  <li>One-Hot Encoder - https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html</li>
</ul>
