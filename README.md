# ML_Project14-FlowerSpeciesClassification

### Flower Species Classification with Logistic Regression
This project explores Logistic Regression for classifying Iris flower species based on sepal and petal measurements from the Iris dataset.

### Data Exploration and Preprocessing:

Seaborn is used to load the Iris dataset.
##### Exploratory data analysis (EDA) is conducted:
```
Visualizing the distribution of features using scatter plots.
Confirming no missing values are present.
Encoding flower species (setosa, versicolor, virginica) into numerical labels (0, 1, 2) using a custom function.
Creating boxplots to identify potential outliers in each feature.
Splitting the data into independent (features) and dependent (target variable) variables.
```

### Feature Scaling:

StandardScaler is applied to standardize the features, ensuring all features contribute equally during model training.

### Model Training and Evaluation:

The data is split into training and testing sets using train_test_split (75% for training, 25% for testing).
A Logistic Regression model is trained on the scaled training features.
The model's performance is evaluated on the unseen testing set using:
Classification Report: Provides detailed information about precision, recall, and F1-score for each flower species.
Accuracy Score: Measures the overall percentage of correct predictions.
Confusion Matrix: Visualizes the number of correct and incorrect predictions for each class.

### Results:

The Logistic Regression model achieves a perfect accuracy (100%) on the testing set, indicating excellent performance in classifying flower species based on the given features.

### Further Exploration:

Experiment with different machine learning algorithms like Random Forest or Support Vector Machines (SVM) for potential improvements.
Utilize additional features relevant to flower classification (e.g., color, texture).
Consider techniques like cross-validation for a more robust evaluation of model performance.
