Iris Classification uses the K-Nearest Neighbors (KNN) model in Machine Learning to classify Iris flowers into three species: Setosa, Versicolor, and Virginica, based on their sepal length, sepal width, petal length, and petal width.
The Iris dataset is loaded from Scikit-learn using the load_iris() function. It contains 150 samples, 4 input features, 3 target species, and 50 samples per species.
KNN classifies a new data point by finding the nearest data points and assigning it the class that is most common among them. In this project, K=5, which means the model considers the 5 nearest data points for making a prediction.
KNN is used because it is a simple and easy-to-understand classification model. It works by comparing a new data point with existing data points and classifying it based on its nearest neighbours.
The dataset is divided into training and testing sets using an 80-20 split, that is, 120 samples for training and 30 samples for testing.
The performance of the model is evaluated using the following evaluation metrics: Accuracy Score, Confusion Matrix, and Classification Report.
The trained model is also used to predict the species of a new Iris flower by providing its sepal and petal measurements.
