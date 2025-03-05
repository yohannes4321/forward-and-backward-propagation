This project demonstrates the concepts of Forward Propagation and Backward Propagation in deep learning. These two processes are essential in training neural networks efficiently.

Forward Propagation
Input Layer → Receives the input data.
Hidden Layers → Apply weights, biases, and activation functions to transform the data.
Output Layer → Produces the final prediction.
The goal of forward propagation is to pass input through the network and compute the output.

Backward Propagation
After getting the output, we compare it to the actual values and calculate the error. Backward Propagation helps adjust the weights to minimize this error.

Steps:
Compute the Loss → Compare predicted output with actual labels.
Calculate Gradients → Determine how much each weight contributes to the error.
Update Weights → Adjust weights to improve future predictions.
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
