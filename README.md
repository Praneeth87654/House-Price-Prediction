# House-Price-Prediction
This project focuses on predicting house prices using a deep learning model built with PyTorch. It utilizes embeddings and batch normalization techniques to enhance model performance, achieving a low Root Mean Absolute Error (RMAE). The model is trained on structured data to learn meaningful patterns for accurate predictions.
# Project Overview
The House Price Prediction project uses machine learning and deep learning techniques to estimate house prices based on features such as size, location, number of rooms, and more. By leveraging PyTorch and advanced techniques like embeddings for categorical data and batch normalization, the model delivers high accuracy and stability.

# Features
1. Deep Learning Model: Built using PyTorch for flexible and efficient model training.
2. Embeddings: Converts categorical features into dense vectors for improved learning.
3. Batch Normalization: Stabilizes learning and accelerates training.
4. RMAE Metric: Achieved a Root Mean Absolute Error (RMAE) of 45,000.
5. Customizable: Easily adaptable to new datasets or additional features.

# Technologies Used
1. Programming Language: Python
2. Deep Learning Framework: PyTorch
3. Data Manipulation: Pandas, NumPy
4. Visualization: Matplotlib, Seaborn
5. Model Evaluation: Scikit-learn

# Dataset
The dataset includes:

1. Features: Size, location, year built, number of bedrooms/bathrooms, etc.
2. Target Variable: House price.
You can replace the dataset with your own. Ensure it is structured in a CSV file with clearly defined feature columns and a target column for the price.

# Model Architecture
1. Input Layer: Accepts both numerical and categorical features.
2. Embedding Layers: For categorical features.
3. Dense Layers: Fully connected layers with ReLU activation.
4. Batch Normalization: Applied after each dense layer.
5. Output Layer: Single neuron with linear activation for price prediction.
