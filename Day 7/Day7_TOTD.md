Short Answer Questions

1.Explain how data is represented in Scikit-Learn for machine learning tasks, distinguishing between the feature matrix and the target vector.
2. Describe the three primary steps (phases) in the life cycle of an Estimator object in Scikit-Learn when performing a supervised learning task.
3. What is a PyTorch Tensor, and how does it differ from a standard Python list or NumPy array in the context of deep learning?

** Solution Key ** 

1. Explain how data is represented in Scikit-Learn for machine learning tasks, distinguishing between the feature matrix and the target vector.  

   In Scikit-Learn, data is typically thought of as a table or a two-dimensional array.
  - The **feature matrix** (often denoted as X) is a 2D array where each row represents a single observation or sample, and each column represents a specific feature or attribute of that observation. All features for a given observation are contained in one row.
  - The target vector (often denoted as y) is typically a 1D array or series that contains the labels or dependent variables that the machine learning model aims to predict. Each entry in the target vector corresponds to the respective row in the feature matrix.  
        This tabular representation is consistent across almost all models in Scikit-Learn.


2. Describe the three primary steps (phases) in the life cycle of an Estimator object in Scikit-Learn when performing a supervised learning task.  

  The three primary steps in the life cycle of an Estimator object in Scikit-Learn are:
  - **1\. Choose a model/class:** This involves selecting the appropriate Estimator class for the task at hand (e.g., sklearn.naive_bayes.GaussianNB for classification).
  - **2\. Instantiate the model/class:** Create an instance of the chosen Estimator class, and configure any hyperparameters specific to that model. This is where you set up the model before training.
  - 3\. Fit the model to data: Use the fit() method to train the model on the training data (feature matrix X and target vector y). During this step, the model learns the relationships between the features and the targets.  
        After fitting, the model can then be used for predict() on new data.

3. What is a PyTorch Tensor, and how does it differ from a standard Python list or NumPy array in the context of deep learning?  

   A PyTorch Tensor is the fundamental data structure in PyTorch, analogous to NumPy arrays, but with crucial differences that make them suitable for deep learning.
  - **Key Differences:**
    - **GPU Acceleration:** Tensors can seamlessly be moved to and operated on GPUs (Graphics Processing Units), which significantly speeds up numerical computations essential for training large neural networks. Standard Python lists and NumPy arrays are primarily CPU-bound.
    - **Automatic Differentiation (Autograd):** Tensors have a built-in mechanism (.requires_grad) to track the history of operations performed on them. This allows PyTorch to automatically compute gradients for backpropagation, which is the core algorithm for optimizing neural networks. NumPy arrays do not have this automatic differentiation capability.
    - **Dynamic Computation Graph:** PyTorch builds a dynamic computational graph, meaning the graph is built on the fly as operations are performed. This flexibility allows for more complex and dynamic network architectures compared to static graph frameworks.
