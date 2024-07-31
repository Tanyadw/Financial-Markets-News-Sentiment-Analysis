# Financial-Markets-News-Sentiment-Analysis
In this YBI Foundation Business and Data Analytics Internship Course Final Project, we undertook the following steps:

1. Importing Libraries: We imported essential libraries for the project, including NumPy and pandas.

2. Importing Dataset: The dataset was imported using pandas.

3. Data Preparation: We cleaned the news articles in the dataset by removing spaces using a for loop. We then combined all the cleaned news articles into a single variable, x. A new dataframe called 'Label' was created and named y.

4. Train-Test Split: We split the data into training and testing sets, allocating 70% of the data for training and the remaining 30% for testing.

5. Model Selection and Fitting: We selected the Random Forest Classifier from scikit-learn as our model and fitted the training data to it.

6. Prediction: We made predictions using the model by providing the necessary parameters.

7. Accuracy Check: We evaluated the model's accuracy by using the Confusion Matrix, Classification Report, and Accuracy Score from sklearn.metrics. The final output was verified to be correct.
