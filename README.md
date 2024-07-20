Tensors are a specialized data structure that are very similar to arrays and matrices. 
In PyTorch, we use tensors to encode the inputs and outputs of a model, as well as the model’s parameters.

Tensors are similar to NumPy’s ndarrays, except that tensors can run on GPUs or other hardware accelerators. 
In fact, tensors and NumPy arrays can often share the same underlying memory, eliminating the need to copy data. 
Tensors are also optimized for automatic differentiation
