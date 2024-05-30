# DeepBeliefNetwork

Final project for the [Cognition and Computation](https://en.didattica.unipd.it/off/2022/LM/SC/SC2377/001PD/SCQ0089498/N0) course of my master's degree.

It is a Deep Belief Network analysis and implementation with PyTorch (based on some scripts given to us during the course). I trained this DBN with the [Fashion-MNIST dataset](https://github.com/zalandoresearch/fashion-mnist) and analyzed how it is performing representation learning.

The aim is to explain how the model is exctracting the underlying features of the data (latent variables) by visualizing the receptive fields of the hidden layers and checking how the representations are clustered in the latent space. Also, I explored how the DBN behaves when used in some scenarios such as classification, sample reconstruction, robustness to noise, and adversarial attacks (also in comparison with a simple Feed Forward Neural Network).

