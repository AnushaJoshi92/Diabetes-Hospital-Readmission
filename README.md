1.	Diabetic patient hospital re-admission prediction in Python:
	Performed data pre-processing such as handling missing values, converting categorical data to numeric using LabelEncoder, range values to their means, alphanumeric to numeric and data normalization using MinMaxScaler.
	Applied feature selection methods such as RFE to select the best features and checked for multicollinearity by visualizing the correlation matrix via Heatmap.
	Applied Weighted/Cost sensitive Logistic Regression algorithm since the classification was skewed/imbalanced. 
	Calculated values of alpha (C) and weights using GridSearchCV from sklearn.model_selection
	Used F2 score as the metric to calculate the model’s performance.
	Also, moved the threshold (threshold moving) to manage the imbalanced classification in the dataset to further reduce the False Negatives.
