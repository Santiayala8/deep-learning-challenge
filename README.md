# deep-learning-challenge

- Step 1: Preprocess the Data

- Step 2: Compile, Train, and Evaluate the Model

- Step 3: Optimize the Model

- Step 4: Write a Report on the Neural Network Model

  Overview of the analysis: Explain the purpose of this analysis
  - The goal of this project is to create an algorithm using machine learning and neural networks to predict whether applicants will be successful if funded by the fictional non-profit foundation, Alphabet Soup.
 
  Results
  - I was given a CSV file that I read into Pandas. This file contained more than 34,000 organizations that have received funding from the fictional foundation along with several columns of metadata about each organization.
  - Drop the EIN and NAME columns.
  - Determine the number of unique values for each column.
  - For columns that have more than 10 unique values, determine the number of data points for each unique value.
  - Use the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, Other, and then check if the binning was successful.
  - Use pd.get_dummies() to encode categorical variables.
  - Split the preprocessed data into a features array, X, and a target array, y. Use these arrays and the train_test_split function to split the data into training and testing datasets.
  - Scale the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.

  Summary
  - The model was unable to achieve a target predicted accuracy higher than 72.7%. Maybe we shpuld use another classificatrion model 
