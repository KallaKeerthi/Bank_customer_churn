# Bank_customer_churn
**OBJECTIVE:** The objective of the project is to build a bank customer churn using machine learning techniques to predict the bank customers who are going to leave the bank (or) left the bank

**Dataset information:**

Target Variable(Y):

Churn(1 = who left the bank, 0 = who didn't left the bank)

Features(X) are computed for each cell:

1. CreditScore
2. Geography
3. Gender
4. Age
5. Tenure
6. Balance
7. Num Of Products
8. Has Credit Card
9. Is Active Member
10. Estimated Salary

##**Import Library:**

**pandas:** For data manipulation and analysis.
**numpy:** For numerical operations and computations
**scikit-learn:** For implementing machine learning algorithms
**matplotlib/seaborn:** For data visualization

##**Import Data:** Load the bank customer dataset containing information such as balance, credit-card, Is active member or not

##**Describe Data:** Perform exploratory data analysis (EDA) to gain insights into the dataset, understand the who are going to leave the bank.

##**Data Visualization:** Create visualizations, such as histograms, bar charts, and scatter plots, to present the characteristics and relationships within the dataset.

##**Data Preprocessing:** Clean and preprocess the data by handling missing values, removing duplicates, and transforming categorical variables into numerical representations suitable for modeling.

##**Define Target Variable (y) and Feature Variables (X):** Identify the target variable, which could be Churn. Select relevant features such as CreditScore, Gender, Age, Balance, Has Credit Card, Is Active Member, Estimated Salary as input variables.

##**Train Test Split:** Split the dataset into training and testing subsets to evaluate the performance of the bank customer churn dataset. The training set will be used to train the model, and the testing set will be used to assess its accuracy.

##**Modeling:** Implement a collaborative filtering or content-based filtering algorithm, such as logistic regression,decision tree classifier, k-nearest neighbors (KNN), or support vector machines (SVM), to create the bank customer churn model.

##**Model Evaluation:** Evaluate the performance of the model using appropriate evaluation metrics, such as precision, recall, or f1 score, to measure the accuracy and effectiveness of the model.

##**Prediction:** Utilize the trained model to make model prediction based on user input.

##**Explanation in Colab File:** Provide a detailed explanation of the code implementation, including step-by-step instructions and code snippets, in a Colab notebook. Describe the data preprocessing steps, the model training process, and how the predictions are generated. And explanations throughout the code to make it easily understandable for others who might review or run the notebook.
