<h1>Sentiment Analysis for Financial News Headlines</h1>
<h3>Overview</h3>
<p>This repository contains a Python script for sentiment analysis on financial news headlines. The sentiment analysis is performed using a Support Vector Machine (SVM) model trained on a dataset of labeled headlines.</p>

<h3>Environment</h3>
The code is developed and tested using Python 3, and it leverages popular data processing and machine learning libraries. It is recommended to use this code in an environment that supports Python 3.

<h3>Kaggle Environment</h3>
The code is originally designed to run on Kaggle using the Kaggle/Python Docker image. The environment provides various analytics libraries and tools, making it suitable for data analysis and machine learning tasks. The Docker image link is provided in the code comments.

<h3>Data</h3>
The training data is loaded from an Excel file (train.xlsx) located in the "/kaggle/input/train_data/pytorch/sample/1/" directory. The dataset includes financial news headlines and their corresponding sentiments.

<h3>Problem Statement</h3>
The problem statement is defined in the code as a multiline string. It introduces the context of the analysis, specifically focusing on the evolving Banking, Financial Services, and Insurance (BFSI) sector.

<h3>Code Structure</h3>

1.Data Loading and Exploration:

* Load and display the structure of the training data.
* Visualize the sentiment distribution using seaborn and matplotlib.
Data Preprocessing:

2.Preprocess the headlines by converting them to lowercase, removing punctuation, and eliminating stopwords.
Model Training and Evaluation:

* Split the data into training and testing sets.
* Vectorize the text data using TF-IDF.
* Train a Support Vector Machine (SVM) model on the training data.
* Evaluate the model accuracy on the test set.
3.Test Predictions:

* Load additional test headlines from the same dataset.
* Preprocess and vectorize the test data.
* Make predictions using the trained SVM model.
4.Predictions for New Headlines:

* Define a set of new headlines.
* Preprocess and vectorize the new headlines.
* Predict sentiments for the new headlines using the trained SVM model.

<h3>Usage</h3>
1.Clone the repository: git clone https://github.com/shivammm21/Winjit-Hackathon-.git<br>
2.Navigate to the project directory: cd repo<brr>
3.Install dependencies: pip install -r requirements.txt (if any)<br>
4.Run the Python script: python sentiment_analysis.py<br>

<br>
Feel free to customize the code, add more features, or use different datasets for training and testing. If you encounter any issues or have suggestions for improvements, please create an issue or submit a pull request.
<br>
Happy coding!
