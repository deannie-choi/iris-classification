# Iris Classification Project

## 📌 Overview
This project implements a classification model using the Iris dataset. The goal is to classify different species of the Iris flower based on sepal and petal measurements using a **Random Forest Classifier**.

There are two main components in this project:
1. **iris-classification.ipynb** - This file trains a machine learning model using the Iris dataset. It loads the dataset, preprocesses the data, splits it into training and test sets, trains a **Random Forest Classifier**, and evaluates its performance.
2. **iris-classification-input.ipynb** - This file allows users to input custom sepal and petal measurements to predict the corresponding Iris species using the trained model.

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn (RandomForestClassifier, train_test_split, accuracy_score)
- Jupyter Notebook

## 📂 Project Structure
```
📂 iris-classification-project
│-- 📜 README.md  # Project documentation
│-- 📜 requirements.txt  # Required libraries
│-- 📜 iris-classification.ipynb  # Model training and evaluation
│-- 📜 iris-classification-input.ipynb  # User input-based prediction
│-- 📂 dataset/  # Folder for dataset
│-- 📂 images/  # Folder for visualization images
```

## 🚀 How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/iris-classification-project.git
   ```
2. Navigate to the project folder:
   ```sh
   cd iris-classification-project
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
5. Run `iris-classification.ipynb` to train the model.
6. Run `iris-classification-input.ipynb` to input custom data and make predictions.

## 📊 Model Details
- Dataset: Iris dataset (from sklearn)
- Model: Random Forest Classifier
- Metric: Accuracy Score

## 🔥 Results
The trained model achieves **high accuracy** in classifying Iris species. The results can be visualized in the notebook.

## 📞 Contact
For any questions, reach out via [LinkedIn](https://www.linkedin.com/in/dean-choi/).

