# Deep Learning Scratch Implementations

## Why Scratch Implemantation??

Watch https://youtu.be/l9RWTMNnvi4?t=130,
The God Father of AI Geoffrey Hinton said "If you want to understand a really complicated device like brain, then you should build one".

Same goes for the Deep Learning technologies, if you really (like reeaally) want to understand such technologies then you should build them. Indeed Keras exists, but these kind of frameworks which takes not more than 5 lines to build a model actually hides everything from you, that makes you completely unknown what's going on under the hood. The purpose of such frameworks is rapid deployment and production, they are not meant to be used by people who are beginner in the field. If you already understand the technology, then be my guest and use such frameworks like a champ, otherwise if you are a beginner in the field......... you better listen to The God Father.

## List of topics implemented from scratch.

### Intro to Deep Learning.
- [Understanding Percepron - Linear Regression.](01. Intro to Deep Learning/Linear_Regression_MXNet_(From_Scratch).ipynb)
- Binary Classification - Logistic Regression.
- Multiclass Classification - Softmax Regression.
- The Modern Deep Learning - Neural Networks.

### Gradient Descent Variants. 
- Momentum Optimizer.
- NAG Optimizer.
- AdaGrad Optimizer.
- AdaDelta Optimizer.
- RMSProp Optimizer.
- Adam Optimizer.
- AMSGrad Optimizer.
- Nadam Optimizer.
- AdaMax Optimizer.

### Preventing Overfitting.
- L1 Regularization.
- L2 Regularization.
- Dropout.
- DropConnect.

### Making Deep Learning Learn Faster.
- Batch Normalization.
- Layer Normalization.

### Recurrent Neural Networks. 
- Recurrent Neural Networks (RNN).
- Long Short Term Memory Cell (LSTM).
- Gated Recurrent Unit (GRU).
- Sequence to Sequence.
- Multilayer Recurrent Neural Networks. __(To be implemented)__
- Bidirectional Recurrent Neural Networks. __(To be implemented)__

### Convolutional Neural Networks.
- Convolutional Neural Networks (CNN).
- Capsule Networks. __(To be implemented)__

### Generative Models.
- Autoencoder.
- Denoising Autoencoder.
- Variational Autoencoder.
- Generative Adversarial Networks.
- Style Transfer. __(To be implemented)__
- Pixel2Pixel. __(To be implemented)__
- Boltzmann Machines. __(To be implemented)__
- Restricted Boltzmann Machines. __(To be implemented)__
- Deep Belief Networks. __(To be implemented)__


## How to use notebooks provided.
It is recommended to run notebooks locally on your computer only if you have GPU(CUDA) support, otherwise it'd be quit painfull :O

If you don't have the GPU, then follow the steps as bellow:-

- Go to https://colab.research.google.com
- Sign In using your google account.
- From the menu top left, Go to "__File -> Upload notebook -> Choose File__".
- Then select the notebook you want to run located in your computer and click "__Open__".
- Wait for a while.
- When notebook is successfully loaded, from the menu top left go to "__Runtime -> Change runtime type__".
- Select GPU as your "__Hardware accelerator__".
- Click "__SAVE__".
- Now you are ready to roll.


## TODO

- Implement all above algorithms from scratch in Tensorflow.
- Implement all above algorithms from scratch in Pytorch.
- Provide resources to learn topics mentioned above.
- Add more explanations to notebooks for better understanding.
