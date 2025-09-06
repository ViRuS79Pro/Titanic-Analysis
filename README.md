Titanic Survival Prediction
This project contains a Jupyter Notebook that performs data exploration, feature engineering, and machine learning to predict passenger survival on the Titanic. The goal is to build a classification model that accurately predicts which passengers survived the disaster, based on a variety of passenger attributes.


Licensed by Google
Notebook Contents
The titanic-comp-finale (1).ipynb notebook follows a structured data science workflow, including:

Data Loading and Initial Exploration: The notebook begins by loading the primary train.csv and test.csv datasets, as well as the gender_submission.csv file. It performs an initial check for missing values to understand the scope of data cleaning required.

Data Cleaning and Feature Engineering: This is a crucial phase where raw data is transformed into a format suitable for a machine learning model.

Missing Cabin values are handled by replacing them with a placeholder value, 'No_Cabin'.

New features are created by extracting passenger titles (e.g., Mr., Miss., Mrs.) from the Name column. Less common titles are grouped into broader categories to simplify the data.

Missing Age and Fare values are imputed to ensure the dataset is complete.

Categorical features like Sex and Embarked are converted into numerical format using one-hot encoding, a standard technique for preparing data for models.

A final set of new features, including Family_size and Alone, are created from the SibSp (siblings/spouses aboard) and Parch (parents/children aboard) columns to capture information about family travel.

Model Training and Evaluation:

The preprocessed data is split into training and validation sets.

Feature scaling is applied using StandardScaler to normalize the numerical data, which is essential for many machine learning algorithms.

A powerful XGBoost Classifier model is trained on the prepared data.

The model's performance is evaluated using accuracy_score on the validation set.

Prediction and Submission: The trained model is used to make predictions on the untouched test.csv dataset, and the results are saved to a submission.csv file, formatted correctly for the Kaggle competition.

How to Run the Notebook
Clone the repository: Copy all the files to your local machine.

Install dependencies: Make sure you have a Python environment with Jupyter Notebook and the necessary libraries. You can install all required packages with a single pip command:

pip install numpy pandas scikit-learn seaborn xgboost

Download data: Place the train.csv, test.csv, and gender_submission.csv files from the Kaggle Titanic competition into the same directory as the notebook.

Launch Jupyter: From your terminal, start the Jupyter Notebook server:

jupyter notebook

Run cells: Open the titanic-comp-finale (1).ipynb notebook and run all the cells in order to see the full data analysis pipeline and generate the final submission file.
