The models used for our experiments.

For MNIST, we used the same model, but one with L1 regularization and another one with L2 regularziation, as mentioned in the paper.
For Fashion-MNIST, we used only one model, with regularization loss.
For CIFAR-10, we used two models. First model, ```CIFAR-10.h5``` is the model used in reporting our attack results in the online stream setup. The second model, a ResNet-20, 
is the model we used for evaluating our proposed adversarial attack efficacy, as mentioned in the papeer
