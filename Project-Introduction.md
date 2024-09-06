In this project I'll be tackling the challenge of predicting credit card fraud using a highly imbalanced dataset consisting of 284,807 transactions, among which only 492 are fraudulent, representing just 0.172% of the total. We will employ a variety of machine learning models and techniques to address this imbalance and improve detection accuracy. Our approach will include creating a neural network specifically designed to determine whether a transaction is fraudulent and to classify the pattern of fraud. Another data set containing over 100,00 rows of bank transactions will be used to identify and classify the fraud. By carefully analyzing and processing the data, we aim to enhance our ability to identify fraudulent transactions despite the significant imbalance between fraudulent and non-fraudulent cases.

<b> <u> Steps to Build a Fraud Detection ML Model </u> </b>

<b> Import Libraries: </b>
Import necessary libraries for data manipulation, visualization, and machine learning (e.g., Pandas, NumPy, Matplotlib, Scikit-Learn, TensorFlow/Keras).

<b> Import Data Set: </b>
Load the dataset into a DataFrame for analysis.

<b> Exploratory Data Analysis (EDA) and Visualizations: </b>
Perform exploratory data analysis to understand the data distribution and relationships. Create visualizations to identify patterns and anomalies (e.g., using histograms, box plots, pair plots).

<b> Data Preprocessing: </b>   
Identify and correct inconsistencies in the dataset, such as duplicate entries or erroneous values. Use NumPy and Pandas to address missing values through imputation or removal:

<i> Imputation: </i> Fill missing values with mean, median, or mode, or use advanced imputation techniques.

<i> Removal:</i> Drop rows or columns with missing values if appropriate

<i> Encode Categorical Features: </i> Convert categorical features into numerical formats using methods like one-hot encoding or label encoding.

<i>Normalize or scale numerical features: </i> Standardize numerical features to improve model performance using techniques such as normalization or scaling.

<i> Handle Outliers: </i> Outlier Detection and Removal: </i> Use techniques such as the Interquartile Range (IQR) to identify and handle outliers.

</i> Robust Scaling: </i> Apply robust scaling to minimize the impact of outliers on the model.


<b> Observing Class Distribution </b>  
Analyze class distribution using histograms or bar plots to understand class imbalance across the features

<b> Data Shuffling </b>  
Shuffle the data to ensure that the training and testing sets are representative and prevent any order bias.


<b> Splitting Data into Training and Testing Sets </b>  
Split the dataset into training and testing sets 
(e.g., using an 80/20 or 70/30 split).


<b> Addressing Data Imbalance </b>  
Apply techniques to handle class imbalance, such as:
<i> SMOTE (Synthetic Minority Over-sampling Technique): </i>
To generate synthetic samples for the minority class.
Other techniques: Such as <i> undersampling, oversampling </i>, or using different class weights in the model.

<b> Building and Training the Model </b>    
<i> Creating a Neural Network </i>  
Define and compile the neural network model. Training the Model: Fit the model on the training data and tune hyperparameters.

<b> Model Evaluation </b>  
Evaluate the model on the testing set using metrics such as accuracy, precision, recall, F1-score, ROC-AUC, etc. Perform cross-validation to validate the model’s performance.

<b> Model Stacking </b>    
Stacking Models Together: Combine multiple models (e.g., neural networks, decision trees, etc.) to improve performance using techniques like stacking or ensembling.

<b> Model Deployment (Currently Working On This!) </b>  
Deploy the trained model into a production environment for real-time fraud detection.
