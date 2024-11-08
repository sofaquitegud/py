Car Dataset Exploratory Data Analysis (EDA)

This repository contains a Jupyter Notebook that performs an Exploratory Data Analysis (EDA) on a car dataset. The notebook walks through data loading, cleaning, and preparation, ultimately providing insights into the dataset’s structure and distributions. This EDA serves as a foundation for further analysis or modelling.

Table of Contents

- Overview
- Setup and Installation
- Usage
- Notebook Outline
- License

Overview
The notebook includes steps to:
1. Load and inspect the car dataset.
2. Clean and preprocess the data by removing irrelevant columns and handling duplicates.
3. Explore data distributions and relationships, setting the stage for future analysis or modelling.

Setup and Installation
To run this notebook, ensure you have the following Python libraries installed:
pandas
numpy
matplotlib
seaborn
Install them with:
pip install pandas numpy matplotlib seaborn

Usage
1. Dataset: Place the car dataset (data.csv) in the same directory as the notebook. Adjust the file path in the notebook if necessary.
2. Running the Notebook: Open the notebook (eda.ipynb) and run each cell in sequence to complete the analysis.

Notebook Outline
1. Import Libraries: Essential libraries for data handling and visualization (pandas, numpy, seaborn, matplotlib) are loaded.
2. Load Data: The dataset is read into a pandas DataFrame.
3. Data Cleaning:
- Unnecessary columns are dropped to simplify analysis.
- Columns are renamed for readability.
- Duplicate rows are identified and removed to maintain data quality.
4. Data Exploration:
- Displays initial and final rows to review data content.
- Shows data types, shape, and identifies duplicates.
- Summarizes key statistics to understand distributions and relationships within the data.

This notebook provides a comprehensive data exploration framework, making it easier to derive insights or prepare the data for further modeling.

License
This project is licensed under the MIT License.
