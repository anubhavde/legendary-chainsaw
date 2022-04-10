Implemented a 2 hidden layer neural network classifier from scratch in JAX.
<p>Two hidden layers here means (input - hidden1 - hidden2 - output).</p>
<p>Not used flax, optax, or any other library for this task.</p>
<p>Used MNIST dataset with 80:20 train:test split.</p>
<p>Manually optimized the number of neurons in hidden layers.</p>
<p>Used gradient descent from scratch to optimize your network. You should use the Pytree concept of JAX to do this elegantly.</p>
<p>Evaluated the model on test data with various classification metrics and briefly discuss their implications.</p>
