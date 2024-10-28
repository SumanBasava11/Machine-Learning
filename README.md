                                     ----:Audiobook Customer Purchase Prediction:----
The audiobook dataset comprises information on customers who have made at least one purchase from an audiobook platform, specifically for audio content. The goal is to develop a machine learning model that predicts whether a customer will make another purchase. By identifying customers likely to buy again.

Project Structure <br>
-----------------
The repository includes the following main components: <br>

__Data Files:__ 
1. Audiobooks_data_raw.csv:  Original data with audiobook app information for customers who made at least one purchase.
2. Audiobooks_data_with_column_name.csv:  Cleaned data with added column names for easier analysis.
3. Output from Preprocessing: Three .npz files generated from the preprocessing stage, containing processed data used in the machine learning model.

__Jupyter Notebooks:__ 
1. Preprocessing Notebook:  Contains steps to clean, normalize, and prepare data for modeling.
2. Machine Learning Model Notebook:  Builds and trains a predictive model on the preprocessed data to classify customers based on their likelihood to repurchase.

Project Workflow <br>
----------------
- Data Preprocessing: The preprocessing notebook handles data preparation, transforming the raw dataset into a format suitable for machine learning.
  This includes handling missing values, feature scaling, and splitting the data into training, validation, and test sets. Processed data is saved as .npz files for efficient loading.

- Machine Learning Model: The model notebook trains a unsupervised learning algorithm using the preprocessed data. The model's objective is to predict customer behavior accurately, focusing on identifying those likely to make repeat purchases.

- Outcome: A trained model that allows the company to focus advertising efforts on high-potential returning customers.

Getting Started <br>
---------------
1. Run the Preprocessing Notebook to generate processed datasets.
2. Use the Machine Learning Model Notebook to train and evaluate the predictive model on the processed data.
