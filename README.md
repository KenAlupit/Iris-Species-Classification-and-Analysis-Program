# Iris Species Classification and Analysis Program
The Iris Species Classification and Analysis program employs machine learning to categorize Iris flower species using logistic regression. It starts by importing the Iris dataset containing measurements of sepal length, sepal width, petal length, and petal width. The program extracts features (X) and target variables (y), scales the data using StandardScaler, and splits it into training and testing sets.

Key functionalities include training a logistic regression classifier to predict Iris species based on sepal and petal dimensions. It visualizes pairwise relationships in the data using seaborn's pair plot and evaluates the classifier's performance with a confusion matrix, displaying normalized true values.

The program interacts with users by validating input values for sepal and petal dimensions within the dataset's range. After preprocessing user inputs, it predicts the Iris species and presents classification probabilities using bar charts and numerical outputs. This functionality aids in understanding how machine learning can automate species identification based on botanical measurements.

Designed for educational purposes and practical applications in botany and machine learning, this program provides insights into data preprocessing, model training, and result interpretation, making it a valuable tool for both beginners and researchers in the field.
