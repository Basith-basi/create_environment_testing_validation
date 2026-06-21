System Ingestion & Model Environment Setup

Project Overview


The objective of this task is to set up a reproducible Machine Learning environment, load and verify a dataset, perform proper data splitting, run a baseline model, and log evaluation metrics.

Objectives
Create a reproducible Machine Learning environment.
Load and inspect the dataset.
Verify dataset shape, data types, and class distribution.
Perform Train, Validation, and Test data splitting.
Run a baseline (Dummy) Machine Learning model.
Record evaluation metrics.
Maintain project version control using Git.
Technologies Used
Python 3.9
Pandas
NumPy
Scikit-learn
Jupyter Notebook
Git
Project Structure

PlaceMux_Task1/

├── data/

│ └── iris.csv

├── notebooks/

│ └── starter_notebook.ipynb

├── logs/

│ └── metrics_log.csv

├── requirements.txt

├── README.md

└── .gitignore

Dataset

The Iris dataset was used for this project.

Features:

Sepal Length
Sepal Width
Petal Length
Petal Width

Target:

Iris Species Classification
Steps Performed
1. Environment Setup
Created a virtual environment.
Installed required libraries.
Fixed random seeds for reproducibility.
2. Data Loading
Loaded the dataset using Pandas.
Verified dataset dimensions.
Checked data types.
Checked for missing values.
Verified class balance.
3. Data Splitting

The dataset was divided into:

Training Set (70%)
Validation Set (15%)
Test Set (15%)
4. Experiment Tracking
Created a metrics log file.
Stored model evaluation results.
5. Baseline Model

A DummyClassifier was trained as a smoke test to verify the complete Machine Learning pipeline.

6. Evaluation

Metric Used:

Accuracy Score

Results were recorded in the metrics_log.csv file.

How to Run the Project
Create Virtual Environment
python -m venv venv
Activate Environment

Windows:

venv\Scripts\activate
Install Dependencies
pip install -r requirements.txt
Launch Jupyter Notebook
jupyter notebook

Open:

starter_notebook.ipynb

Run all cells sequentially.

Output

The project successfully demonstrates:

Reproducible ML environment
Proper train/validation/test split
Baseline model training
Metrics logging
End-to-end pipeline execution