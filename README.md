# Project 1: Whiteboxing a Neural Network in PyTorch with Captum
- **Description:** We use Captum to describe the classification decisions of a neural network.
- **Role:** Working student
- **Tools/Technologies Used:** Python, PyTorch, Captum
- **Outcomes:** Several neurons shared a strong association with certain outcomes.

As neural networks have a black box structure by nature, methods for explaining their decision-making are needed. Captum (captum.ai) is a framework for achieving this. While regression models are widely documented for this framework, there is a lack of code for classification models. In my project, I shed light on explaining a feedforward neural network with ReLU activations and classical linear layers. To achieve high comparability, the widely known breast-cancer dataset is used. 
Using captum and its attribution techniques on a macro-, layer- and neuron-level, the decision-making of the classification network becomes more clear.