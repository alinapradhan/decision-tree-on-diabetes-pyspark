# Decision Tree with PySpark

This repository contains a Jupyter Notebook implementation of a Decision Tree Classifier using PySpark. The project demonstrates how to preprocess data, train a decision tree model, evaluate its performance, and visualize results in a scalable environment.


## Features

* Data preprocessing with **PySpark DataFrame API**
* Feature engineering with **VectorAssembler**
* Train/test split and model training with **DecisionTreeClassifier**
* Model evaluation using accuracy, confusion matrix, and classification metrics
* Export and visualization of the trained decision tree


## Repository Structure

```
├── decision_tree_pyspark_prac7.ipynb   # Main Jupyter notebook
├── README.md                           # Project documentation
└── requirements.txt (optional)         # Python dependencies
```


##  Requirements

* Python 3.8+
* Apache Spark (PySpark)
* Jupyter Notebook
* pandas, matplotlib (for additional visualization)

You can install the dependencies with:

```bash
pip install pyspark pandas matplotlib jupyter
```


## Example Workflow

1. Load dataset into a Spark DataFrame
2. Clean and preprocess the data
3. Assemble features into a vector column
4. Train a Decision Tree Classifier
5. Evaluate accuracy and performance metrics
6. Visualize the tree structure

