# Iris Flower Classification using Random Forest

A machine learning project that classifies Iris flower species using the **Random Forest Classifier** with Python and Scikit-learn.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Random Forest
- Machine Learning

## 📊 Dataset

The project uses the built-in **Iris dataset** from Scikit-learn.

The dataset contains four features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The model predicts three Iris species:

- Setosa
- Versicolor
- Virginica

## ⚙️ Machine Learning Workflow

1. Load the Iris dataset
2. Extract features and target values
3. Split the dataset into training and testing sets
4. Create a Random Forest Classifier
5. Train the model
6. Make predictions on the test dataset
7. Evaluate model accuracy

## 🌲 Machine Learning Model

**Algorithm:** Random Forest Classifier

**Number of Trees:** 20

**Training Data:** 70%

**Testing Data:** 30%

## 📈 Model Evaluation

The model performance is evaluated using **Accuracy Score**.

```python
metrics.accuracy_score(y_test, y_pred)
