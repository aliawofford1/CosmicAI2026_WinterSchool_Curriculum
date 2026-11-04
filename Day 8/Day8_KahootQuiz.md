## Lesson 8: Scikit-Learn and PyTorch Quiz

### Multiple Choice Questions

- What is Scikit-Learn primarily known for?  
    a) A library for data visualization.  
    b) A popular library for implementing machine learning algorithms.  
    c) A framework for web development.  
    d) A tool for deep learning model deployment.
- In Scikit-Learn, how is data typically structured for machine learning models?  
    a) As a one-dimensional list.  
    b) As a table (two-dimensional array) where rows are observations and columns are features.  
    c) As a nested dictionary.  
    d) As a graph structure.
- Which of the following is a key characteristic of Scikit-Learn's API?  
    a) It is highly inconsistent across different models.  
    b) It requires manual implementation of algorithms.  
    c) It offers an intuitive and consistent interface for various models.  
    d) It is primarily designed for deep learning.
- What does an "Estimator" in Scikit-Learn refer to?  
    a) A function used for data cleaning.  
    b) An object that learns from data (e.g., a classification or regression model).  
    c) A utility for loading datasets.  
    d) A method for evaluating model performance.
- What is a "feature matrix" in Scikit-Learn terminology?  
    a) A vector containing the target labels.  
    b) A 2D array where rows represent individual samples and columns represent features.  
    c) A list of model parameters.  
    d) A measure of model accuracy.
- Which of the following is an alternative machine learning framework to PyTorch, as mentioned in the notebooks?  
    a) NumPy  
    b) Pandas  
    c) TensorFlow  
    d) Matplotlib
- What is the fundamental data structure in PyTorch?  
    a) DataFrame  
    b) Array  
    c) Tensor  
    d) List
- What is the primary purpose of the autograd package in PyTorch?  
    a) To automatically optimize code for faster execution.  
    b) To automatically differentiate all operations on Tensors, enabling backpropagation.  
    c) To automatically handle data loading and preprocessing.  
    d) To automatically select the best model for a given dataset.
- If x.requires_grad = True for a PyTorch Tensor x, what does this imply?  
    a) The Tensor x can only be used for inference, not training.  
    b) Gradients will be computed for x during the backward pass.  
    c) The Tensor x is stored on the GPU.  
    d) The Tensor x is immutable.
- What is torch.nn.Module primarily used for in PyTorch?

a) Defining optimization algorithms.  
b) Representing neural network layers and models.  
c) Performing tensor operations.  
d) Visualizing training progress.

- What is the role of an "optimizer" in a PyTorch neural network training process?  
    a) To define the network architecture.  
    b) To calculate the loss between predictions and true labels.  
    c) To update the model's parameters based on gradients to minimize the loss.  
    d) To load and preprocess the training data.
- Which function is used to convert a PyTorch Tensor to a NumPy array?  
    a) tensor.to_numpy()  
    b) tensor.detach().numpy()  
    c) numpy(tensor)  
    d) tensor.as_array()
- In machine learning, what does the "target vector" (or "response vector") typically represent?  
    a) The input features for a model.  
    b) The labels or dependent variables that the model aims to predict.  
    c) The performance metrics of the model.  
    d) The unique identifiers for each data point.
- What does the fit() method do in Scikit-Learn's Estimator API?  
    a) It applies the learned model to new data.  
    b) It transforms the data into a new representation.  
    c) It trains the model using the provided training data.  
    d) It evaluates the model's performance.
- What is one of the key benefits of using TensorBoard with PyTorch?  
    a) It automates model deployment.  
    b) It helps visualize training progress and identify issues like overfitting.  
    c) It performs automatic hyperparameter tuning.  
    d) It converts PyTorch models to other frameworks.

  ## Solutions Key **

  

1 b) A popular library for implementing machine learning algorithms.
2 b) As a table (two-dimensional array) where rows are observations and columns are features.
3 c) It offers an intuitive and consistent interface for various models.
4 b) An object that learns from data (e.g., a classification or regression model).
5 b) A 2D array where rows represent individual samples and columns represent features.
6 c) TensorFlow
7 c) Tensor
8 b) To automatically differentiate all operations on Tensors, enabling backpropagation.
9 b) Gradients will be computed for x during the backward pass.
10 b) Representing neural network layers and models.
11 c) To update the model's parameters based on gradients to minimize the loss.
12 b) tensor.detach().numpy()
13 b) The labels or dependent variables that the model aims to predict.
14 c) It trains the model using the provided training data.
15 b) It helps visualize training progress and identify issues like overfitting.



