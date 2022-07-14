# legendary-chainsaw

Implemented a 2 hidden layer neural network classifier from scratch in JAX:

- Two hidden layers here means (input - hidden1 - hidden2 - output).
- Not used flax, optax, or any other library for this task.
- Used MNIST dataset with 80:20 train:test split.
- Manually optimized the number of neurons in hidden layers.
- Used gradient descent from scratch to optimize your network. You should use the Pytree concept of JAX to do this elegantly.
- Evaluated the model on test data with various classification metrics and briefly discuss their implications.
