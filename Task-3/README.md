
# 🌸 Iris Flower Classification using Machine Learning

## 📌 Project Overview

This project focuses on building a **Machine Learning classification model** to predict the species of an Iris flower based on its physical measurements.
The model analyzes features such as **sepal length, sepal width, petal length, and petal width** to classify the flower into one of three species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

The Iris dataset is one of the most widely used datasets for **introductory machine learning classification problems**.

---

## 🎯 Objective

The objective of this project is to develop a machine learning model that can accurately classify Iris flowers into their respective species using their sepal and petal measurements.

---

## 🧠 Machine Learning Workflow

The project follows a standard machine learning pipeline:

1. **Import Libraries**
   Import essential Python libraries required for data analysis, visualization, and machine learning.

2. **Dataset Loading**
   Load the Iris dataset using a CSV file and convert it into a Pandas DataFrame.

3. **Data Exploration**
   Analyze dataset structure using functions like:

   * `head()`
   * `info()`
   * `describe()`

4. **Data Visualization**
   Use Seaborn and Matplotlib to visualize feature relationships using pair plots.

5. **Feature Selection**
   Separate the dataset into:

   * Features (X)
   * Target variable (y)

6. **Train-Test Split**
   Split the dataset into training and testing sets to evaluate the model performance.

7. **Model Training**
   Train a **Logistic Regression model** using the training dataset.

8. **Model Prediction**
   Use the trained model to predict the species of new flower samples.

9. **Model Evaluation**
   Evaluate the model performance using:

   * Accuracy Score
   * Classification Report
   * Confusion Matrix

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 📊 Model Performance

The Logistic Regression model achieved **high accuracy (~95–100%)** in classifying Iris flower species.

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📂 Project Structure

```
Iris_Flower_Classification/
│
├── Iris_Flower_Classification.ipynb
├── IRIS.csv
└── README.md
```

---

## 🔍 Sample Prediction

Example input:

```
Sepal Length: 5.1  
Sepal Width: 3.5  
Petal Length: 1.4  
Petal Width: 0.2
```

Predicted Output:

```
Iris-setosa
```

---

## 🚀 Future Improvements

Possible improvements for this project include:

* Testing additional classification algorithms
* Hyperparameter tuning
* Model comparison
* Deploying the model as a web application

---

## 📎 Dataset

The dataset used in this project is the **Iris Flower Dataset**, a well-known dataset in machine learning used for classification tasks.

---

## 👨‍💻 Author

**Rmy4143**

B.Tech (Information Technology) Student
Dr. Babasaheb Ambedkar Technological University

---

⭐ If you found this project useful, consider giving the repository a star!
