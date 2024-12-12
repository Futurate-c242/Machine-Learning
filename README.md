# Models Folder
There are 3 types of bin files and model.json files (our model files).

# Encoder File (encoder.json)
An encoder is used to convert categorical or textual data into numerical values, ensuring the data is machine-readable. For instance, it transforms categories or labels into numerical representations, such as integers or one-hot encoded arrays. This makes it easier for models to process the data and generate outputs in a numerical format.

# Vectorizer File (vectorizer.json)
The function uses a TF-IDF Vectorizer to convert an array of strings into a numeric array, representing the "skills" as numerical values. It also adjusts the array's size to match the input requirements of the model, making the data suitable for further processing or predictions.

# Dataset 
Job_Data.csv is our dataset.

# Notebook (notebook.ipynb)
This notebook contains various processes, including data loading and preprocessing, model construction, a summary of the model architecture, model training with the training accuracy, and the creation of a function that is useful for displaying prediction samples with customized inputs.
