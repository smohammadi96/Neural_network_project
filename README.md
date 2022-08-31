# Neural_network_project

**Task: Classification**

**Dataset: Fasion MNIST**

### Experiment 1: Change activation function


* Relu


![Relu](https://github.com/smohammadi96/Neural_network_project/blob/main/images/relu.PNG)



* Tanh


![Tanh](https://github.com/smohammadi96/Neural_network_project/blob/main/images/tanh.PNG)



* Sigmoid


![Sigmoid](https://github.com/smohammadi96/Neural_network_project/blob/main/images/sigmoid.PNG)


* ELU


![ELU](https://github.com/smohammadi96/Neural_network_project/blob/main/images/ELU.PNG)


Activation function | Optimizer | Accuracy on test set | Loss | 
--- | --- | --- | --- |
Relu | SGD | 0.87 | 0.33 | 
Tanh | SGD | 0.65 | 0.83 |
ELU | SGD | 0.87 | 0.36 |
Sigmoid | SGD | 0.77 | 0.63 |



### Experiment 2: change Optimizer

* Adam


![adam](https://github.com/smohammadi96/Neural_network_project/blob/main/images/adam.PNG)

* Nadam

![nadam](https://github.com/smohammadi96/Neural_network_project/blob/main/images/Nadam.PNG)

* RMSprop

![rmsprop](https://github.com/smohammadi96/Neural_network_project/blob/main/images/rmsprop.PNG)

Activation function | Optimizer | Accuracy on test set | Loss | 
--- | --- | --- | --- |
Relu | SGD | 0.86 | 0.33 | 
Relu | Adam | 0.87 | 0.51 |
Relu | RMSprop | 0.87 | 0.67 |
Relu | Nadam | 0.84 | 0.52


### Experiment 3: change layers and neurons number

![layers](https://github.com/smohammadi96/Neural_network_project/blob/main/images/layers.PNG)
