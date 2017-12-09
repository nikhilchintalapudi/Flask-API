# Flask-WebService
Publish Machine Learning Model as RESTful Web Service using Flask.

"Iris-Plant-Classifier.ipynb" uses a Random Forest model to classify 3 different plants based on Sepal and Petal dimensions. 
This model is serialized and stored as "iris_classifier.pkl" file using Pickle.
"Flask-Web-Service.ipynb" builds a RESTful Web Service. When invoked, it loads the saved Pickle model and makes prediction based on the input parameters. 
