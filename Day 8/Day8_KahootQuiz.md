## Lesson 8: Intro to PyTorch Quiz 

### Multiple Choice Questions
1. What is a tensor in PyTorch?

A. A function used exclusively to train neural networks
B. A multidimensional data structure that stores numerical values
C. An algorithm used to calculate model accuracy
D. A type of optimizer used to update weights

2. What does the shape of a tensor describe?

A. The number of dimensions and the size of each dimension
B. The numerical values stored in the tensor
C. The data type of the tensor
D. Whether the tensor requires gradients

3. What does torch.randn(3, 4) create?

A. A tensor containing 12 zeros
B. A tensor containing the integers 3 and 4
C. A 3 × 4 tensor containing random values from a standard normal distribution
D. A 4 × 3 tensor containing random values between 0 and 1

4. What is the primary purpose of the .view() method?

A. To display a tensor as a graph
B. To reshape a tensor without changing its elements
C. To convert a tensor into a Python list
D. To calculate the gradient of a tensor

5. What is the purpose of torch.cat()?

A. To combine tensors along a specified dimension
B. To multiply two matrices
C. To calculate the mean of a tensor
D. To remove dimensions from a tensor

6. In PyTorch, what does the underscore in a method such as add_() generally indicate?

A. The method calculates a gradient
B. The method creates a new tensor on the GPU
C. The method performs an operation in place
D. The method converts a tensor into a NumPy array

7. What does requires_grad=True tell PyTorch to do?

A. Automatically train the neural network
B. Track operations so gradients can be computed
C. Convert the tensor to a floating-point number
D. Prevent the tensor from being modified

8. What is a computation graph?

A. A visual representation of model accuracy over time
B. A table containing training data and labels
C. A record of operations and dependencies used in a calculation
D. A list of hyperparameters used to train a model

9. What happens when .backward() is called on a scalar output that tracks gradients?

A. PyTorch calculates gradients through the computation graph
B. PyTorch automatically updates every model parameter
C. PyTorch deletes the computation graph and its input tensors
D. PyTorch converts the output into a NumPy array

10. What is the purpose of torch.no_grad()?

A. To permanently disable gradients for every tensor
B. To initialize model parameters with zeros
C. To temporarily prevent PyTorch from tracking gradient-related operations
D. To calculate gradients without storing them

11. Why are GPUs useful for deep learning?

A. They eliminate the need for training data
B. They can efficiently perform many numerical operations in parallel
C. They automatically select the best neural network architecture
D. They guarantee that a model will achieve higher accuracy

12. What is the purpose of nn.Module in PyTorch?

A. To provide a base class for defining neural network models
B. To convert tensors into NumPy arrays
C. To split a dataset into training and testing subsets
D. To automatically download pretrained models

13. What is the purpose of a nonlinear activation function such as Tanh?

A. To calculate the number of model parameters
B. To introduce nonlinearity so a network can represent complex relationships
C. To divide a dataset into batches
D. To save the model after training

14. What is the role of a loss function during neural network training?

A. To measure the difference between model predictions and target values
B. To determine which device should execute the model
C. To specify the number of training examples in a batch
D. To convert a tensor into a different shape

15. What is the primary purpose of an optimizer such as stochastic gradient descent (SGD)?

A. To create random training data
B. To determine the input dimensions of a neural network
C. To update model parameters using gradient information
D. To evaluate a trained model without using labels



** Solutions Key ** 

## Answer Key and Explanations

| Question | Correct Answer | Explanation |
|:---:|:---:|---|
| 1 | **B** | A tensor is a multidimensional data structure used to store numerical values. Scalars, vectors, and matrices can all be represented as tensors. |
| 2 | **A** | A tensor's shape describes its size along each dimension. For example, `(3, 4)` represents a two-dimensional tensor with three rows and four columns. |
| 3 | **C** | `torch.randn(3, 4)` creates a 3 × 4 tensor containing random values sampled from a standard normal distribution. |
| 4 | **B** | The `.view()` method reshapes a tensor without changing its elements. The total number of elements must remain the same. |
| 5 | **A** | `torch.cat()` concatenates tensors along a specified dimension. Tensor sizes must match along all other dimensions. |
| 6 | **C** | Methods ending with an underscore, such as `add_()`, generally modify the existing tensor in place rather than creating a new tensor. |
| 7 | **B** | `requires_grad=True` enables PyTorch to track operations on a tensor so gradients can be calculated using automatic differentiation. |
| 8 | **C** | A computation graph represents the mathematical operations and dependencies connecting inputs to outputs. PyTorch uses this graph during backpropagation. |
| 9 | **A** | Calling `.backward()` on a scalar output computes gradients through the computation graph. The optimizer subsequently uses these gradients to update model parameters. |
| 10 | **C** | `torch.no_grad()` temporarily disables gradient tracking, commonly during model evaluation or inference. |
| 11 | **B** | GPUs perform many numerical operations in parallel, making them useful for tensor computations and neural network training. |
| 12 | **A** | `nn.Module` is the base class used to define PyTorch neural network models, including their layers and forward computations. |
| 13 | **B** | Nonlinear activation functions such as `Tanh` allow neural networks to represent complex relationships that cannot be modeled using only linear transformations. |
| 14 | **A** | A loss function measures the difference between model predictions and target values, providing an objective to minimize during training. |
| 15 | **C** | Stochastic Gradient Descent (SGD) uses gradient information to update model parameters in a direction intended to reduce the loss. |
