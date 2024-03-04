   Dataset 1:

   Full Batch Gradient Descent converges after 768 epochs with learning rate 0.001 . Loss is very high in magnitude of $10^6$.

   Stochastic Gradient Descent converges after 28 epochs with learning rate 0.001.

   Dataset 2:

   Full Batch Gradient descent converges after 43 epochs with learning rate 0.1. Loss is not very high as compared to dataset 1 because theta_0 $\theta_0$ and theta_1 $\theta_1$ are initialised to 0 and 1 which are close to actual values 4 and 3.

   Stochastic Gradient Descent converges after 2 epochs with learning rate 0.1. 


   Full Batch Gradient descent takes larger number of epochs for dataset 1 because the learning rate is very small (0.001) which causes it to take small steps and full batch updates the parameter once after going through all the 40 examples while SGD with same learning rate updates the parameter after going through every example.
   Full batch gradient descent is updating the parameters with a small change in one epoch which causes it to take large number of epochs for convergence.

   ----------------------------------------------------------------------------------------------------------------------------------------------------------------------Dataset 1:

   Full batch gradient descent with momentum converges after 720 epochs with learning rate 0.001 and momentum = 0.1. For momentum = 0.5, full batch gradient descent converges after 200 epochs for the same learning rate.

   SGD with momentum converges after 28 epochs with learning rate 0.001 and momentum = 0.1 .

   Dataset 2:

   Full batch gradient descent with momentum converges after 39 epochs with learning rate 0.1 and momentum = 0.1 .
   SGD with momentum converges after 2 epochs with learning rate 0.1 and momentum = 0.1 .


   Observation:

   Number of epochs used by full batch gradient descent with momentum is halved as compared to vanilla gradient descent. SGD with momentum is using same number of epochs as SGD without momentum.





