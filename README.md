# fashion_mnist

This project is a classification, computer vision project for the "MNIST-Fashion" dataset.
The problem we are solving in the project is a classification between 10 different types of clothes from the MNIST-Fashion dataset.


We use the following technologies for this project:
1. TensorFlow/Keras
2. NumPy
3. pandas
4. scikit-learn
5. Matplotlib

[Code Colab notebook](https://colab.research.google.com/drive/1MbHI25lGlxYorWsr_83uDF6iho6cN5N8?usp=sharing)

## Colab notebook structure:
The notebook is divided to 2 parts
The first part is a binary classification model
the second part is  a multiclass classification model which contains 3 parts of training:
Base model and 2 experiments.
The second model is also saved and uplodaded for later testing
Each part devided to sections 
1. import libraries
2. load dataset
3. data preprocessing
4. build the network layers
5. build the optimizer
6. compile the model
7. training
8. metrics visualization
9. test

## Installation - Must before training or testing
Run "import libraries", "load dataset" and "data preprocessing" sections for training the model.
Run "import libraries" for testing the model.

### Train model
1. Run "Data Preprocessing" section and the data will be extracted and normalized (also, the labels will be One-Hot Encoded)
2. Run "Model Architecture and Training" section and the model will be created and will train on the train set.
3. Run "Results and Evaluation Metrics" section and the model will be evaluated based on the train and test data.

### Test model
1. Each model (base, experiment1 and final) have his own section, running this section will build the model, compile it, train it, test it and show relevant metrics about his performance.
