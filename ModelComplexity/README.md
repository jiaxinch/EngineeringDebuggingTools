# Model Memory Equivalent Capacity Calculation
Could calculate Keras Model's MEC given the model objet. The algorithm is implemented following the four rules:
- The output of a perceptron is maximally 1 bit.
- The maximum memory capacity of a perceptron is the number of parameters (including bias) in bits.
- The maximum memory capacity of perceptrons in parallel is additive.
- The maximum memory capacity of a layer of perceptrons depending on a previous layer of perceptrons is limited by the maximum output (in bits) of the previous layer.

Use this capacity calculation algorithm to measure the capacity of several common neural networks. Like AlexNet,ResNet, LeNet, VGGNet, ZFNet.
