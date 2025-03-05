Forward Propagation (Computing Predictions)
Forward propagation is the process of passing input data through the network to compute the predicted output.
Z =wx+b
sigmoid func= 1/1+e^-x
z=w2h+b2
y pred=sigmoid(z2)
Compute Loss:    Binary Cross Entropy
-1/n summation (y *log(y pred) + 1-y log(1-ypred))

the make chian rule calculate gradient descent 
he forward and backward steps are repeated over many epochs.
Forward Propagation: Computes predictions and loss.
Backward Propagation: Computes gradients of the loss function.
Gradient Descent: Updates weights using the computed gradients.
Repeat until loss converges.
The loss keeps decreasing as the model learns.
Training stops when the loss converges.
