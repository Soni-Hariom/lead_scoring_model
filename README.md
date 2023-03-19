# Lead Generation Model

This model is designed to predict whether a lead will result in a win or a loss for a business. It uses a dataset containing information about leads, such as their budget, lease duration, and whether they ultimately resulted in a win or a loss.

## Cleaning and Preprocessing

Before training the model, the dataset was cleaned and preprocessed. This included removing missing values, outliers, and irrelevant columns. The status column, which indicated whether a lead resulted in a win or a loss, was encoded as a binary variable.

## Model Training and Evaluation

The cleaned dataset was split into training and testing sets. Several machine learning models were trained on the training set, including Gaussian Naive Bayes, Decision Tree,and Logistic Regression. The models were evaluated using various metrics, including accuracy, precision, recall, F-beta score, and ROC AUC.

The Decision Tree model achieved the highest accuracy of 100%. However, it is important to consider other metrics as well, such as precision and recall, to get a complete picture of the model's performance.

##Using the Model

Once the model has been trained and evaluated, it can be used to predict whether new leads will result in a win or a loss. Simply input the relevant information about the lead, such as their budget and lease duration, into the model, and it will output a predicted win or loss.
