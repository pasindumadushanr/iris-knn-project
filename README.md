# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

This project demonstrates how to use the **K-Nearest Neighbors (KNN)** algorithm to classify Iris flowers into three species: **Setosa**, **Versicolor**, and **Virginica** using the well-known **Iris dataset**.

🔗 **Live Demo**: [Click here to try it out](https://plum-dorris-21.tiiny.site/)

## 📂 Project Description

The Iris dataset is a classic example in the field of machine learning. It contains 150 samples of Iris flowers with four features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

Using these features, this project trains a KNN classifier and includes an interactive web app to predict the species of an Iris flower based on user input.

## ⚙️ Technologies Used
- Python (for model training and data preparation)
- HTML/CSS/JavaScript (for the interactive web UI)
- Scikit-learn (for model and dataset)
- Jupyter Notebook
- NumPy
- Matplotlib (optional, for visualization)

## 🖥️ Web App Features
- Input sepal and petal measurements
- Live prediction of Iris species using KNN (k=5)
- Example buttons for quick testing
- Stylish and responsive UI
- Species info cards with descriptions and key features

## 📈 Workflow (Python side)
1. Load and explore the Iris dataset
2. Split the data into training and test sets
3. Train the KNN model (with `k=3` or `k=5`)
4. Export sample training data to be used in the web app

## ✅ Results

The model performs with high accuracy and is capable of making reliable predictions on unseen data. The web version mimics this logic using hardcoded training data and JavaScript.

## 🔍 How to Run Locally

1. Clone this repository
2. Open the file `iris_classifier_webapp.html` in any modern web browser
3. Interact with the app to test different measurements and see predictions

## 📚 Dataset Source

The Iris dataset is built into the `scikit-learn` library. Originally introduced by **Ronald A. Fisher** in 1936.
